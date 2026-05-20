---
name: sankhya-html5
description: Desenvolvimento de dashboards, gadgets e telas HTML5 no Sankhya ERP — geração de JSP+XML, snk:query com bindings EL/JDBC, parâmetros de prompt, multi-tabs, links entre gadgets e gotchas validados em produção (ORA-00920, datas, multiList, encoding em CDATA).
---

# 🎨 sankhya-html5

> Skill para construir e debugar dashboards HTML5, gadgets e relatórios no Sankhya — incluindo o formato JSP+XML, parâmetros de prompt, integração com `snk:query` e os gotchas que mais quebram projetos em produção.

**Versão:** 1.0.0
**Última atualização:** 2026-05-19
**Autora:** Andressa Olivi — [Olivi Consultoria](https://github.com/andressaolivi)

---

## 🎯 Quando usar esta skill

- Pergunta envolve **gadget HTML5**, **dashboard HTML5**, **JSP + XML**, `snk:query`, `snk:command`
- Usuário quer **criar/editar/debugar uma tela HTML5** no Sankhya
- Pergunta menciona **parâmetro de prompt** (`<prompt-parameter>`), **prompt-bind**, **type=date/text/integer/multiList**
- Erros típicos: `ORA-00920`, parâmetro de data não filtra, `multiList` não recebe valores, prompt não aparece
- Palavras-chave: `gadget`, `html5`, `dashboard`, `snk:query`, `prompt-parameter`, `bind`, `JSP`, `XML gadget`, `GadgetCustomizado`

## 🚫 Quando NÃO usar

- Para **estrutura de tabela do Sankhya** (campos, tipos, joins) → usar `sankhya-dicionario`
- Para **fluxos de negócio** (faturamento, baixa financeira, custo médio) → usar `sankhya-funcionamento`
- Para **telas customizadas via `metadata.xml`** (Construtor de Telas) → usar `sankhya-construtor-telas`
- Para **customizações Java** (Acao, JdbcWrapper, módulos Java) → usar `sankhya-api-java`
- Para **dúvidas sobre como usar uma funcionalidade do Sankhya pelo usuário final** → usar `sankhya-ajuda-online`

---

## 📚 Capacidades

- Gerar **estrutura completa de gadget HTML5** (JSP + XML) pronta pra upload
- Escrever **`snk:query`** com bindings corretos (EL vs JDBC) para cada tipo de parâmetro
- Definir **`<prompt-parameter>`** com os tipos corretos (lowercase, com regras específicas para `date` e `multiList`)
- Montar **dashboards multi-tab** com links entre gadgets e drill-down
- Diagnosticar e corrigir **ORA-00920** quando o erro vem de operadores HTML-encoded dentro de CDATA
- Linkar documentos via `TGFIXN/DOCSREF` em gadgets que cruzam notas/operações
- Empacotar gadget para import em **Configurações → Gadgets → Importar**

## 📂 Arquivos de referência

```
sankhya-html5/
├── SKILL.md                          ← este arquivo
└── references/
    ├── gadget_estrutura.md           ← Layout JSP+XML, taglib, IDs, namespaces
    ├── snk_query.md                  ← snk:query, bindings, CDATA, encoding
    ├── prompt_parameters.md          ← Tipos, defaults, regras por tipo
    ├── multi_tab_dashboard.md        ← Tabs, links entre gadgets, drill-down
    ├── gotchas.md                    ← ORA-00920, datas, multiList, encoding
    └── indice.md                     ← Mapa de navegação
```

| Reference | Carregar quando |
|---|---|
| `gadget_estrutura.md` | Pergunta menciona "criar gadget", "como começar", "estrutura JSP" |
| `snk_query.md` | Pergunta envolve `snk:query`, bind, parâmetros em SQL, CDATA |
| `prompt_parameters.md` | Pergunta envolve `<prompt-parameter>`, tipos, prompt no início do gadget |
| `multi_tab_dashboard.md` | Pergunta envolve abas, dashboards complexos, navegação entre gadgets |
| `gotchas.md` | Erro `ORA-00920`, parâmetro não filtra, comportamento inesperado |
| `indice.md` | Quando não souber em qual reference está o tema |

---

## 🧭 Workflow típico

1. **Identificar o tipo de gadget** — relatório simples, dashboard multi-tab, lista com drill-down, gráfico
2. **Definir parâmetros de prompt** ANTES de escrever o SQL — tipos, defaults, obrigatoriedade
3. **Escrever a `snk:query`** seguindo as regras de binding (ver "Regras críticas")
4. **Embrulhar no JSP+XML** com o `<gadget>` raiz e os namespaces corretos
5. **Validar localmente** — fazer o XML passar por um parser antes de subir
6. **Importar** via **Configurações → Gadgets → Importar** (ou a tela equivalente no MGE Web)
7. **Testar com cada combinação de parâmetros** — datas em borda, listas vazias, multiList com 0/1/N seleções

---

## ⚠️ Regras críticas (gotchas)

### Regra 1 — Datas em `snk:query` exigem EL, não JDBC binding

**Contexto:** Quando você tem um `<prompt-parameter name="P_DATA" type="date"/>` e quer usá-lo num WHERE.

**Regra:** Nunca use `:P_DATA` (JDBC binding) para parâmetros de data dentro do `snk:query`. Sempre use EL syntax com `TO_DATE`:

**Por quê:** O `java.util.Date.toString()` que o framework usa renderiza como `'YYYY-MM-DD HH:MM:SS.S'` (com horário e milissegundos). O Oracle não consegue fazer cast implícito disso para `DATE` quando vem como bind JDBC, gerando erros silenciosos ou filtros que não filtram nada.

**Exemplo ruim:**
```sql
WHERE T.DTNEG BETWEEN :P_DT_INI AND :P_DT_FIM
-- Falha silenciosa: retorna vazio ou filtros não aplicam
```

**Exemplo bom:**
```sql
WHERE T.DTNEG BETWEEN
    TO_DATE(SUBSTR('${P_DT_INI}', 1, 10), 'YYYY-MM-DD')
AND TO_DATE(SUBSTR('${P_DT_FIM}', 1, 10), 'YYYY-MM-DD')
```

O `SUBSTR(..., 1, 10)` corta o horário, deixando só `YYYY-MM-DD`.

---

### Regra 2 — Tipos de `prompt-parameter` SEMPRE em lowercase

**Contexto:** Definição do atributo `type` no `<prompt-parameter>`.

**Regra:** O framework é case-sensitive. Use `date`, `text`, `integer`, `multiList` — nunca `Date`, `Text`, `Integer`.

**Por quê:** Parser do gadget não reconhece o tipo capitalizado, e o resultado é o prompt aparecer como campo texto livre (ou pior, não aparecer).

**Exemplo ruim:**
```xml
<prompt-parameter name="P_DATA" type="Date" label="Data" />
```

**Exemplo bom:**
```xml
<prompt-parameter name="P_DATA" type="date" label="Data" />
```

---

### Regra 3 — `multiList` usa `:Text`, NÃO `:Integer`

**Contexto:** Parâmetros do tipo `multiList` (seleção múltipla a partir de uma query auxiliar).

**Regra:** O atributo `bind` do `multiList` deve referenciar como `:Text`, mesmo quando os valores selecionados são numéricos.

**Por quê:** O framework serializa a seleção como string CSV (`'1','2','3'`). Se você declarar como `:Integer`, o bind tenta tratar como inteiro único e quebra com IN-list.

**Exemplo ruim:**
```xml
<prompt-parameter name="P_TOPS" type="multiList" bind=":Integer">
    <query>SELECT CODTOP, DESCROPER FROM TGFTOP</query>
</prompt-parameter>
```

**Exemplo bom:**
```xml
<prompt-parameter name="P_TOPS" type="multiList" bind=":Text" label="TOPs">
    <query>SELECT CODTOP, DESCROPER FROM TGFTOP ORDER BY DESCROPER</query>
</prompt-parameter>
```

E no `snk:query`:
```sql
WHERE T.CODTOP IN (${P_TOPS})
```

---

### Regra 4 — Parâmetros `date` NÃO podem ter default SQL

**Contexto:** Default value de um `<prompt-parameter type="date">`.

**Regra:** Não defina default via expressão SQL para parâmetros de data. O usuário **deve** escolher no runtime — deixe sem default ou use uma string literal (não recomendado).

**Por quê:** O parser do prompt avalia a expressão como string e gera erro de parsing, ou pior, congela o gadget no carregamento. Outros tipos (integer, text) aceitam default SQL — date não.

**Exemplo ruim:**
```xml
<prompt-parameter name="P_DATA" type="date" label="Data">
    <default>SELECT SYSDATE FROM DUAL</default>
</prompt-parameter>
```

**Exemplo bom:**
```xml
<prompt-parameter name="P_DATA" type="date" label="Data" required="true" />
```

---

### Regra 5 — Dentro de CDATA, operadores ficam LITERAIS (não HTML-encoded)

**Contexto:** Bloco SQL dentro de `<![CDATA[ ... ]]>` no `snk:query`.

**Regra:** O CDATA já desabilita o parsing XML. Use operadores literais (`<`, `>`, `&`, `<=`, `>=`). Se vier código com `&lt;`, `&gt;`, `&amp;` dentro de CDATA, é bug — corrigir antes de testar.

**Por quê:** O Oracle vai receber a string literal `&lt;` no SQL e disparar `ORA-00920: invalid relational operator`. É o erro mais comum em gadgets gerados via copy-paste de editor HTML/Markdown.

**Exemplo ruim (gera ORA-00920):**
```xml
<snk:query>
    <![CDATA[
        SELECT * FROM TGFCAB WHERE VLRNOTA &gt;= 1000 AND DTNEG &lt;= SYSDATE
    ]]>
</snk:query>
```

**Exemplo bom:**
```xml
<snk:query>
    <![CDATA[
        SELECT * FROM TGFCAB WHERE VLRNOTA >= 1000 AND DTNEG <= SYSDATE
    ]]>
</snk:query>
```

> 💡 **Dica de diagnóstico:** Quando der `ORA-00920` no gadget, a PRIMEIRA coisa a checar é se o SQL tem `&lt;` / `&gt;` / `&amp;` dentro de CDATA. Vale mais que 90% dos casos.

---

### Regra 6 — `snk:query` precisa de `id` único por gadget

**Contexto:** Múltiplas queries no mesmo gadget (ex: dashboard multi-tab).

**Regra:** Cada `<snk:query id="...">` deve ter `id` único dentro do gadget. IDs duplicados fazem a segunda query ser ignorada silenciosamente.

**Por quê:** O framework resolve queries por ID no DOM — duplicado vira shadowing.

---

## 💬 Exemplos de uso

**Básico:**
- "Como crio um gadget HTML5 que mostre vendas do mês?"
- "Como faço prompt de data num gadget?"
- "Qual a estrutura mínima de um XML gadget?"

**Intermediário:**
- "Como ligar 4 tabs num mesmo dashboard?"
- "Como faço um multiList que filtra por TOP?"
- "Como fazer drill-down de um gráfico pra uma lista?"

**Avançado:**
- "Estou dando ORA-00920 num gadget que era pra funcionar, por quê?"
- "Como linko `TGFIXN/DOCSREF` entre dois gadgets de auditoria?"
- "Como faço o gadget receber parâmetro de data e usar no BETWEEN sem dar bug?"
- "Como detectar duplicidade de pedidos em um gadget de marketplace?"

---

## 🧪 Como testar esta skill

Antes de fazer commit de uma mudança:

1. Carregue a skill em uma conversa nova no Claude.ai
2. Rode as 3 perguntas representativas:
   - "Como faço prompt de data num gadget HTML5?" → deve mencionar `EL + TO_DATE + SUBSTR`
   - "Estou recebendo ORA-00920 no meu snk:query, o que pode ser?" → deve sugerir checar HTML-encoded operators em CDATA
   - "Como uso multiList num prompt-parameter?" → deve mencionar `bind=":Text"` mesmo para valores numéricos
3. Confira se:
   - [ ] Claude carrega `gotchas.md` quando aparece erro `ORA-00920`
   - [ ] Claude carrega `snk_query.md` quando a pergunta envolve bind/parâmetro em SQL
   - [ ] Nenhuma resposta confunde com `sankhya-construtor-telas` (metadata.xml é OUTRA coisa)

---

## 📦 Empacotamento

```bash
cd sankhya-html5/
zip -r ../sankhya-html5.zip . -x "*.DS_Store" "*.swp"
```

Upload em **Claude.ai → Settings → Capabilities → Skills → Upload skill**.

Para importar o gadget gerado no Sankhya:
**Configurações → Gadgets → Importar** (ou via MGE Web na tela equivalente).

---

## 📝 Changelog

| Versão | Data | Mudança |
|---|---|---|
| 1.0.0 | 2026-05-19 | Versão inicial. Cobre gadgets JSP+XML, snk:query, prompt-parameters e seis regras críticas validadas em produção |

---

## 🔗 Skills relacionadas

- `sankhya-dicionario` — para descobrir qual tabela/campo usar no SQL do gadget
- `sankhya-funcionamento` — para entender o fluxo de negócio que o gadget vai modelar
- `sankhya-construtor-telas` — para telas custom de cadastro (metadata.xml), que é caminho diferente
- `sankhya-api-java` — quando o gadget precisa chamar uma Ação Java customizada

---

## 📄 Licença

MIT — veja [LICENSE](../LICENSE) no root do repositório.
