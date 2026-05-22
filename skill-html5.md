---
name: sankhya-dashboard-html5
description: >
  Conhecimento completo sobre como criar dashboards HTML5 (gadgets) no ERP Sankhya.
  Cobre a estrutura do XML de configuracao, criacao de JSPs com snk:query, prompt-parameters,
  empacotamento em ZIP, deploy via Upload Pacote HTML, taglibs disponiveis, API JavaScript nativa
  (executeQuery, openLevel, refreshDetails, openApp, openPage), parametros entity/singleList/multiList,
  drill-down via modal+executeQuery, export CSV client-side, XMLTABLE para parsing de XML de notas,
  e todas as armadilhas e workarounds descobertos na pratica (ORA-00920, datas, multiList, encoding,
  Internal Server Error em Level 2, openLevel que nao passa parametros).
  Use esta skill SEMPRE que o usuario pedir para criar, modificar ou debugar um gadget HTML5 no Sankhya,
  ou mencionar: dashboard Sankhya, gadget HTML5, snk:query, componente HTML5, tdb_dashboard.xml,
  Upload Pacote HTML, openLevel, refreshDetails, executeQuery, prompt-parameters, ou qualquer referencia
  a criacao de telas customizadas dentro do Sankhya via JSP/HTML5.
  Tambem use quando o usuario mencionar erros como "Internal Server Error" em gadgets,
  "setObject em PreparedStatement", "param -> null", ou problemas com datas em queries Sankhya.
---

# Sankhya Dashboard HTML5 - Guia Completo

Skill para criar dashboards (gadgets) HTML5 customizados no ERP Sankhya.
Baseado em experiencia real de desenvolvimento e debugging iterativo.

> **IMPORTANTE:** Leia este arquivo inteiro antes de escrever qualquer codigo.
> As armadilhas documentadas aqui foram descobertas com horas de debugging.

**Versao:** 2.0.0
**Ultima atualizacao:** 2026-05-22

---

## 1. Estrutura de Arquivos

Um gadget HTML5 no Sankhya consiste em:

```
meu_gadget/
├── tdb_dashboard.xml    (configuracao do gadget: levels, parametros)
├── tdb_partida.jsp      (JSP principal - ponto de entrada)
└── (outros .jsp, .js, .css conforme necessario)
```

### Regras de empacotamento ZIP

- Os arquivos devem estar **na raiz do ZIP**, sem pasta intermediaria
- Correto: `zip gadget.zip tdb_partida.jsp tdb_dashboard.xml`
- ERRADO: `zip gadget.zip minha_pasta/tdb_partida.jsp` (cria subpasta)
- O "Ponto de Entrada" configurado no Sankhya deve ser o **nome exato do JSP principal**

---

## 2. XML de Configuracao (tdb_dashboard.xml)

### Estrutura basica

```xml
<?xml version="1.0" encoding="UTF-8"?>
<gadget>
    <prompt-parameters>
        <!-- Parametros que o usuario preenche antes de abrir o gadget -->
    </prompt-parameters>
    <level id="lvl_principal" description="Meu Dashboard">
        <container orientacao="V" tamanhoRelativo="100">
            <container orientacao="V" tamanhoRelativo="100">
                <html5component id="html5_principal" entryPoint="tdb_partida.jsp"/>
            </container>
        </container>
    </level>
</gadget>
```

### Prompt Parameters - Tipos e Exemplos

#### Data
```xml
<parameter id="P_DTINI" description="Data inicial" metadata="date"
           required="true" keep-last="true" keep-date="false"
           show-inactives="false" label="P_DTINI : Data" order="1"/>
```
- `metadata` DEVE ser **minusculo**: `"date"` (nao `"Date"`)
- **NAO usar `<expression>` com default** em parametros de data
- O Sankhya envia como `java.util.Date`, EL `${P_DTINI}` renderiza `"2025-10-01 00:00:00.0"`

#### MultiList (selecao multipla com SQL)
```xml
<parameter id="P_CODEMP" description="Empresa" metadata="multiList:Text"
           listType="sql" required="true" keep-last="true" keep-date="false"
           show-inactives="false" label="P_CODEMP : multiList:Text" order="0">
    <expression type="SQL"><![CDATA[
        SELECT CODEMP AS VALUE, NOMEFANTASIA AS LABEL FROM TSIEMP ORDER BY CODEMP
    ]]></expression>
</parameter>
```
- Usar `multiList:Text` (nao `multiList:Integer`)
- Binding `:P_CODEMP` funciona no `snk:query` → `AND CODEMP IN (:P_CODEMP)`
- Quando nenhum item e desselecionado, TODOS os valores sao enviados

#### SingleList (dropdown com valores estaticos)
```xml
<parameter id="P_SOVENDA" description="Somente Venda?" metadata="singleList:Text"
           listType="text" required="true" keep-last="true" keep-date="false"
           show-inactives="false" label="P_SOVENDA : singleList:Text" order="4">
    <item value="S" label="Sim"/>
    <item value="N" label="Nao"/>
</parameter>
```
- Usar `metadata="singleList:Text"` com `listType="text"`
- Opcoes via `<item value="X" label="Descricao"/>` (nao SQL UNION)
- Retorna `""` quando nao ha opcoes, `"0"` quando ha opcoes mas nenhuma selecionada
- No SQL: `AND ('${P_SOVENDA}' = 'N' OR UPPER(CAMPO) LIKE '%VENDA%')`

#### MultiList com valores estaticos
```xml
<parameter id="P_SERIE" description="Canal" metadata="multiList:Text"
           listType="text" required="true" keep-last="true" order="3">
    <item value="3" label="3 - MeLi"/>
    <item value="7" label="7 - Amazon Full"/>
    <item value="8" label="8 - Magalu Full"/>
</parameter>
```
- Mesmo padrao do singleList mas com `multiList:Text`
- No SQL: `AND SERIEDOC IN (:P_SERIE)`

#### Entity (entidade do Sankhya - busca com autocomplete)
```xml
<parameter id="MARCA" description="Marca" metadata="entity:MarcaProduto@CODIGO"
           required="false" keep-last="true" keep-date="false"
           show-inactives="false" label="MARCA : Entidade/Tabela" order="5"/>
<parameter id="CODPARC" description="Fornecedor"
           metadata="entity:ParceiroFornecedorCotacao@CODPARC"
           required="false" keep-last="true" order="6"/>
```
- Formato: `entity:NomeDaEntidade@CAMPO_CHAVE`
- Pode ser `required="false"` — quando nao preenchido, valor e NULL
- No SQL usar padrao OR IS NULL: `WHERE (CAMPO = :PARAM OR :PARAM IS NULL)`
- O EL `${MARCA}` retorna o valor da chave selecionada ou string vazia

#### Ordem dos parametros
- Usar atributo `order="N"` para controlar a ordem visual no prompt
- Sem `order`, o Sankhya pode exibir em ordem diferente da declarada

---

## 3. JSP - Cabecalho Padrao

```jsp
<%@ page language="java" contentType="text/html; charset=ISO-8859-1"
         pageEncoding="UTF-8" isELIgnored ="false"%>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"
    "http://www.w3.org/TR/html4/loose.dtd">
<%@ page import="java.util.*" %>
<%@ taglib uri="http://java.sun.com/jstl/core_rt" prefix="c" %>
<%@ taglib prefix="snk" uri="/WEB-INF/tld/sankhyaUtil.tld" %>
<html>
<head>
    <title>Meu Dashboard</title>
    <snk:load/>
</head>
<body>
    <!-- conteudo -->
</body>
</html>
```

- `<snk:load/>` e **obrigatorio** no `<head>`
- `isELIgnored="false"` e **obrigatorio** (note: o Sankhya aceita com espaco antes do `=`)
- `fmt:formatDate` **NAO EXISTE** no Sankhya — usar SUBSTR/EL ou scriptlet

---

## 4. snk:query - Regras de Binding

### Binding vs EL - Quando Usar Cada Um

| Tipo do Parametro | Usar | Exemplo |
|-------------------|------|---------|
| Data (date) | **EL** `'${P_DT}'` com TO_DATE/SUBSTR | `TO_DATE(SUBSTR('${P_DT}', 1, 10), 'YYYY-MM-DD')` |
| MultiList (Text) | **Binding** `:P_CODEMP` | `AND CODEMP IN (:P_CODEMP)` |
| SingleList (Text) | **EL** `'${P_PARAM}'` | `AND ('${P_SOVENDA}' = 'N' OR ...)` |
| Entity | **Binding** `:PARAM` com OR IS NULL | `AND (CAMPO = :PARAM OR :PARAM IS NULL)` |
| Texto simples | **EL** `'${P_TEXTO}'` | `AND CAMPO = '${P_TEXTO}'` |
| Numerico | **EL** `${P_NUM}` (sem aspas) | `AND CODPROD = ${P_NUM}` |

### Padrao CTE PARAMS para datas

```jsp
<snk:query var="dados">
WITH PARAMS AS (
    SELECT TO_DATE(SUBSTR('${P_DTINI}', 1, 10), 'YYYY-MM-DD') AS DT_INI,
           TO_DATE(SUBSTR('${P_DTFIM}', 1, 10), 'YYYY-MM-DD') AS DT_FIM
    FROM DUAL
)
SELECT V.CODPROD, V.DESCRPROD
FROM MINHA_TABELA V, PARAMS P
WHERE V.DTNEG BETWEEN P.DT_INI AND P.DT_FIM + 0.99999
  AND V.CODEMP IN (:P_CODEMP)
  AND V.SERIEDOC IN (:P_SERIE)
</snk:query>
```

### snk:query NAO pode ficar dentro de c:if/c:choose

O Sankhya compila todas as `snk:query` no carregamento, independente de condicionais JSTL.
Colocar `snk:query` dentro de `<c:when>` ou `<c:if>` causa **Internal Server Error**.
Se precisar de query condicional, usar scriptlet `out.println(sql)` dentro do snk:query.

### Scriptlet dentro de snk:query (padrao modelo Sankhya)

Para queries condicionais ou que recebem parametros de args/refreshDetails:

```jsp
<snk:query var="dados">
<%
    String query;
    if (request.getAttribute("MEU_PARAM") != null) {
        query = "SELECT * FROM TABELA WHERE CAMPO = :MEU_PARAM";
    } else {
        query = "SELECT NULL AS CAMPO FROM DUAL WHERE 1 <> 1";
    }
    out.println(query);
%>
</snk:query>
```

---

## 5. API JavaScript Nativa do Sankhya

O Sankhya disponibiliza funcoes JS globais nos gadgets HTML5:

### executeQuery (PRINCIPAL - mais usado)

```javascript
// Signature: executeQuery(query, params, onSuccess, onError)
// Retorna JSON: [{"COLUNA1":"VALOR","COLUNA2":"VALOR"}, ...]

var query = "SELECT CODPROD, DESCRPROD FROM TGFPRO WHERE CODPROD IN (?)";
var params = [{value: "${P_CODEMP}", type: "IN"}];

executeQuery(query, params, function(json) {
    var rows = JSON.parse(json);
    rows.forEach(function(r) {
        console.log(r.CODPROD, r.DESCRPROD);
    });
}, function(erro) {
    alert("Erro: " + erro);
});
```

#### Tipos de parametros no executeQuery

| Tipo | Uso | Exemplo |
|------|-----|---------|
| `"D"` | Data | `{value: "${P_DTINI}", type: "D"}` |
| `"I"` | Integer | `{value: "123", type: "I"}` |
| `"S"` | String | `{value: "texto", type: "S"}` |
| `"IN"` | Lista IN (multiList) | `{value: "${P_CODEMP}", type: "IN"}` com `WHERE COL IN (?)` |

#### Datas no executeQuery

O `type:"D"` pode nao aceitar formato `"YYYY-MM-DD"` diretamente.
**Solucao segura:** inline a data no SQL via concatenacao JS (valor vem do proprio dado, nao do usuario):

```javascript
var query = "SELECT * FROM TAB WHERE TRUNC(DTNEG) = TO_DATE('" + diaISO + "','YYYY-MM-DD')";
executeQuery(query, [], onSuccess, onError);
```

#### Construcao condicional de query

```javascript
var q = "SELECT * FROM TGFPRO pro JOIN TGFMAR mar ON mar.CODIGO = pro.CODMARCA WHERE 1=1";
var params = [];

// Empresa (multiList)
q += " AND pro.CODEMP IN (?)";
params.push({value: "${P_CODEMP}", type: "IN"});

// Marca (entity, opcional)
var vMarca = "${MARCA}";
if (vMarca && vMarca != "0" && vMarca != "") {
    q += " AND mar.CODIGO = " + vMarca;
}

executeQuery(q, params, onSuccess, onError);
```

### openLevel

```javascript
// Abrir outro nivel do dashboard
openLevel('lvl_drill', {P_CODPROD: 12345});
```

**ATENCAO:** openLevel com `<args>` causa **Internal Server Error** em html5components.
O parametro nao chega ao JSP do Level 2 por nenhum mecanismo (`EL`, `request.getAttribute`, `request.getParameter`).
**Alternativa recomendada:** usar modal + executeQuery no mesmo JSP (ver secao 8).

### refreshDetails

```javascript
// Atualizar outro componente no MESMO nivel
refreshDetails('html5_detalhe', {CODPARC: codParc});
```

- Funciona para passar parametros entre componentes do mesmo level
- O JSP destino recebe via `request.getAttribute("CODPARC")`
- No snk:query, usar scriptlet + `:CODPARC` (binding JDBC)

### openApp / openPage

```javascript
openApp('br.com.sankhya.com.mov.NotaFiscal', {NUNOTA: 12345}); // Abre tela nativa
openPage('https://meusite.com', {}); // Abre pagina externa
```

---

## 6. Padrao JSON - JSTL para JavaScript

Para transferir dados do snk:query (server-side) para JavaScript (client-side):

```jsp
<script>
var dados = [
<c:forEach items="${resultado.rows}" var="r" varStatus="s">
    {cod:"<c:out value='${r.CODPROD}'/>",
     desc:"<c:out value='${r.DESCRPROD}'/>",
     vlr:<c:out value="${r.VALOR}"/>
    }<c:if test="${!s.last}">,</c:if>
</c:forEach>
];
</script>
```

**Cuidados:**
- Usar `TO_CHAR(valor, 'FM999999999990.00')` no Oracle para evitar notacao cientifica nos numeros
- Campos texto com aspas/quebra de linha podem quebrar o JSON — usar `<c:out>` que escapa HTML
- NAO acumular valores com `<c:set>` em JSTL (problemas de precisao/notacao cientifica) — agregar em JS

---

## 7. Drill-Down via Modal + executeQuery (Padrao Recomendado)

Como o openLevel nao funciona confiavelmente para html5components, o padrao
recomendado e usar um modal overlay no mesmo JSP:

### 1. Carregar dados resumidos via snk:query (server-side)
### 2. Ao clicar, buscar detalhes via executeQuery (client-side)
### 3. Exibir no modal

```html
<!-- Modal HTML -->
<div id="modal" style="display:none;position:fixed;top:0;left:0;width:100%;height:100%;
     background:rgba(0,0,0,.75);z-index:999">
    <div style="background:#1e293b;margin:30px auto;width:95%;max-height:85vh;
         border-radius:12px;overflow:hidden;display:flex;flex-direction:column">
        <div style="padding:14px 20px;border-bottom:1px solid #334155;display:flex;
             justify-content:space-between">
            <h2 id="modalTitle">Itens</h2>
            <button onclick="fecharModal()">&times;</button>
        </div>
        <div style="overflow-y:auto;padding:16px 20px">
            <table><tbody id="modalBody"></tbody></table>
        </div>
    </div>
</div>
```

```javascript
function abrirDrill(diaISO) {
    var q = "SELECT ... FROM TABELA WHERE TRUNC(DTNEG) = TO_DATE('" + diaISO + "','YYYY-MM-DD')"
          + " AND CODEMP IN (?)";
    executeQuery(q, [{value:"${P_CODEMP}", type:"IN"}], function(json) {
        var rows = JSON.parse(json);
        // montar tabela no modal
        document.getElementById('modal').style.display = 'flex';
    }, function(err) { alert(err); });
}

function fecharModal() {
    document.getElementById('modal').style.display = 'none';
}
// Fechar ao clicar fora
document.getElementById('modal').addEventListener('click', function(e) {
    if (e.target === this) fecharModal();
});
```

### Hibrido: pendentes do snk:query + processados do executeQuery

Quando parte dos dados vem de snk:query (ex: XMLTABLE que so roda server-side)
e parte pode ser buscada on-demand:

1. snk:query carrega pendentes como array JS (`pendData[]`) no load da pagina
2. Ao clicar num dia, filtra `pendData` por dia (JS) + busca processados via `executeQuery`
3. Combina ambos no modal

---

## 8. XMLTABLE em snk:query

Para parsear XML de notas (TGFIXN.XML) dentro do snk:query:

```sql
SELECT x.CPROD, x.XPROD, x.QCOM, x.VPROD
FROM TGFIXN ixn,
     XMLTABLE('/nfeProc/NFe/infNFe/det' PASSING XMLTYPE(ixn.XML)
         COLUMNS
             CPROD VARCHAR2(60)  PATH 'prod/cProd',
             XPROD VARCHAR2(120) PATH 'prod/xProd',
             QCOM  VARCHAR2(20)  PATH 'prod/qCom',
             VPROD VARCHAR2(20)  PATH 'prod/vProd') x
WHERE ixn.XML IS NOT NULL
```

**Gotchas XMLTABLE:**
- XMLs gerados pelo Mercado Livre (`mercadolivre.invoice`) NAO tem namespace — nao usar XMLNAMESPACES
- CPROD pode conter sufixos nao-numericos (ex: `102426_FBA`) — usar `REGEXP_REPLACE(x.CPROD,'[^0-9]','')` para limpar
- Extrair valores como VARCHAR2 (nao NUMBER) para evitar `ORA-01722` em valores sujos
- Conversao numerica fazer no JavaScript com `parseFloat` (tolerante a erros)

### Padrao subquery para LEFT JOIN com TGFPRO

XMLTABLE nao combina bem com INNER/LEFT JOIN na mesma clausula FROM.
Solucao: encapsular o XMLTABLE numa subquery e fazer o JOIN no SELECT externo:

```sql
SELECT BASE.*, TGFPRO.MARCA, TGFMAR.DESCRICAO AS MARCA_DESC
FROM (
    SELECT REGEXP_REPLACE(x.CPROD,'[^0-9]','') AS CPROD, x.XPROD, x.QCOM, x.VPROD
    FROM TGFIXN ixn,
         XMLTABLE('/nfeProc/NFe/infNFe/det' PASSING XMLTYPE(ixn.XML) ...) x
    WHERE ...
) BASE
LEFT JOIN TGFPRO ON BASE.CPROD = TO_CHAR(TGFPRO.CODPROD)
LEFT JOIN TGFMAR ON TGFMAR.CODIGO = TGFPRO.CODMARCA
WHERE (TGFMAR.CODIGO = :MARCA OR :MARCA IS NULL)
  AND (TGFPRO.CODPARCFORN = :CODPARC OR :CODPARC IS NULL)
```

- Usar **LEFT JOIN** (nao INNER) para nao perder itens sem correspondencia em TGFPRO/TGFMAR
- Usar INNER JOIN faz os totais nao baterem com os resumos

---

## 9. Export CSV Client-Side

Para permitir download de dados do dashboard:

```javascript
function downloadCSV(filename, csvContent) {
    var BOM = '\uFEFF'; // BOM UTF-8 para Excel abrir com acentos
    var blob = new Blob([BOM + csvContent], {type: 'text/csv;charset=utf-8;'});
    var link = document.createElement('a');
    link.href = URL.createObjectURL(blob);
    link.download = filename;
    document.body.appendChild(link);
    link.click();
    document.body.removeChild(link);
}

function exportar() {
    var csv = 'Cod;Descricao;Qtd;Valor\n';
    dados.forEach(function(r) {
        csv += r.cod + ';' + r.desc + ';' + r.qtd + ';' + r.vlr.toFixed(2) + '\n';
    });
    downloadCSV('relatorio.csv', csv);
}
```

- Usar `;` como separador (padrao BR, Excel abre direto)
- BOM UTF-8 (`\uFEFF`) garante acentos no Excel
- Escapar campos com aspas se contiverem `;` ou `"`

---

## 10. Armadilhas e Workarounds

### 10.1 Internal Server Error em Level 2 / openLevel

**Causa:** O mecanismo `<args>` com `openLevel` causa Internal Server Error em html5components.
Testado com `type="text"`, `type="integer"`, `type="date"` — nenhum funciona.

**Solucao:** Usar modal + executeQuery no mesmo JSP (ver secao 7).
Se precisar de dois componentes, usar `refreshDetails` no mesmo level.

### 10.2 Datas em snk:query

O binding JDBC `:P_DATA` NAO funciona para datas. Sempre usar EL + TO_DATE + SUBSTR.

### 10.3 ORA-00920 em CDATA

Dentro de `<![CDATA[]]>`, usar operadores literais (`<`, `>`, `<=`, `>=`).
Fora de CDATA, usar entidades HTML (`&lt;`, `&gt;`).

### 10.4 TO_NUMBER em dados de XML

`TO_NUMBER()` em valores extraidos de XMLTABLE pode causar Internal Server Error
se algum valor nao for numerico. Alternativas:
- Extrair como VARCHAR2 e converter no JavaScript com parseFloat
- Usar `DEFAULT 0 ON CONVERSION ERROR` (Oracle 12.2+)

### 10.5 snk:query dentro de c:if / c:choose

Causa Internal Server Error. Queries devem ficar fora de condicionais JSTL.

### 10.6 Acumulacao EL com c:set

`<c:set var="total" value="${total + r.VALOR}"/>` pode gerar notacao cientifica
para numeros grandes. Fazer a agregacao em JavaScript apos transferir os dados como JSON.

### 10.7 Cache apos upload

O Sankhya pode manter cache do JSP anterior. Usar `Ctrl+Shift+R` no navegador.

### 10.8 Acentos em comentarios SQL

Nao usar acentos em comentarios `--` dentro do snk:query. Usar ASCII puro ou comentarios JSP.

---

## 11. Deploy no Sankhya

1. Acesse **Administracao > Gadgets** no Sankhya
2. Crie um novo gadget (ou edite existente)
3. Clique em **"XML"** e cole o conteudo do XML
4. Clique em **"Upload Pacote HTML"** e selecione o arquivo `.zip`
5. Configure o **Ponto de Entrada** com o nome do JSP principal
6. Salve e abra no Dashboard

### Checklist pre-deploy

- [ ] ZIP tem arquivos na raiz (sem pasta)
- [ ] Ponto de Entrada bate com o nome do JSP
- [ ] Nenhum acento em comentarios SQL
- [ ] Datas usando EL + TO_DATE/SUBSTR (nao binding `:`)
- [ ] MultiList usando binding `:` (nao EL)
- [ ] Entity usando `:PARAM` com `OR :PARAM IS NULL`
- [ ] SingleList usando EL `'${P_PARAM}'`
- [ ] `<snk:load/>` presente no `<head>`
- [ ] `isELIgnored="false"` no `<%@ page %>`
- [ ] snk:query fora de qualquer c:if / c:choose
- [ ] Numeros formatados com TO_CHAR(..., 'FM999999990.00') para evitar notacao cientifica

---

## 12. Tabelas Uteis para Dashboards

### Notas Fiscais
- `TGFIXN` — Importacao de XML de Notas (STATUS: 1=Cancelado, 2=Importado, 5=Confirmado)
- `TGFCAB` — Cabecalho de notas/pedidos
- `TGFITE` — Itens de notas/pedidos

### Estoque
- **TGFEST** — Estoque ATUAL (campo `ESTOQUE`, chaves `CODPROD+CODEMP+CODLOCAL+CONTROLE`)
- **TGFCTE** — Historico de contagem (SEQUENCIA=1 = snapshot)

### Produto
- `TGFPRO` — Cadastro (CODPROD, DESCRPROD, CODMARCA, CODPARCFORN, REFERENCIA)
- `TGFMAR` — Marcas (CODIGO, DESCRICAO)

### Parceiro / Empresa
- `TGFPAR` — Parceiros (CODPARC, NOMEPARC)
- `TSIEMP` — Empresas (CODEMP, NOMEFANTASIA)

---

## Changelog

| Versao | Data | Mudanca |
|---|---|---|
| 1.0.0 | 2026-05-19 | Versao inicial |
| 2.0.0 | 2026-05-22 | API JS nativa (executeQuery, openLevel, refreshDetails, openApp, openPage), parametros entity/singleList com item estatico, padrao modal+executeQuery para drill-down, XMLTABLE com subquery+LEFT JOIN, export CSV client-side, padrao JSON via JSTL, gotchas openLevel/args Internal Server Error, snk:query dentro de c:if, TO_NUMBER em XML, acumulacao EL |
