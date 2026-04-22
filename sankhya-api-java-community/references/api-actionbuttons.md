# API — Action Buttons (Botões de Ação Java)

Pacote: **`br.com.sankhya.extensions.actionbutton`**
Tipo: API pública oficial de extensão.

Botões de ação Java permitem associar uma rotina Java customizada a um botão na tela do Sankhya. O ERP carrega a classe via reflection a partir do cadastro de "Botão de Ação" → tipo `Java`.

---

## Interface principal: `AcaoRotinaJava`

```java
public interface br.com.sankhya.extensions.actionbutton.AcaoRotinaJava {
    void doAction(ContextoAcao ctx) throws Exception;
}
```

Sua classe precisa **implementar essa interface** e ser empacotada num jar instalado no servidor de aplicação. Depois, no cadastro de Botão de Ação, informar o **nome qualificado** da classe.

---

## Contexto da execução: `ContextoAcao`

Recebe-se via parâmetro `doAction`. Dá acesso a registros selecionados na tela, consultas SQL, parâmetros do sistema e meios de comunicar com o usuário.

```java
public interface br.com.sankhya.extensions.actionbutton.ContextoAcao {
    QueryExecutor getQuery();              // Executor de SQL/procedures
    Registro getLinhaPai();                // Registro mestre (cabeçalho), quando aplicável
    Registro[] getLinhas();                // Todas as linhas selecionadas pelo usuário
    BigDecimal getUsuarioLogado();         // CODUSU do usuário que disparou o botão

    Registro novaLinha() throws Exception;             // Cria nova linha na entidade base
    Registro novaLinha(String entidade) throws Exception; // Cria nova linha em outra entidade

    Object getParam(String nome);          // Parâmetro do botão (definido no cadastro)
    Object getParametroSistema(String nome); // Parâmetro global do sistema (chave em TSIPRM)

    boolean confirmarSimNao(String titulo, String mensagem, int icone);
    void confirmar(String titulo, String mensagem, int icone);

    void eMail(String para, String assunto, String corpo) throws Exception;

    void setMensagemRetorno(String mensagem); // Define mensagem que aparece após sucesso
    void mostraErro(String mensagem) throws Exception; // Aborta com erro visível ao usuário
}
```

### Notas

- `getLinhas()` retorna `Registro[]` mesmo em telas de linha única (array de 1 elemento).
- `getLinhaPai()` é útil em telas mestre/detalhe (ex.: cabeçalho de nota + itens).
- `getParam(...)` lê parâmetros configurados no cadastro do próprio botão de ação (não confundir com parâmetros do sistema).
- `mostraErro(...)` lança a exceção e cancela a transação — preferir esse caminho em vez de `throw new RuntimeException`.

---

## Manipulação de registros: `Registro`

Cada item retornado por `getLinhas()`/`novaLinha()` é um `Registro` — wrapper sobre o VO da entidade.

```java
public interface br.com.sankhya.extensions.actionbutton.Registro {
    void remove();                                   // Remove o registro (com eventos)
    void save();                                     // Persiste o registro (com eventos)
    void setCampo(String nomeCampo, Object valor) throws Exception;
    Object getCampo(String nomeCampo);
}
```

### Notas

- `setCampo`/`getCampo` usam o **nome lógico do campo** conforme o dicionário (ex.: `"NUNOTA"`, `"CODPARC"`), não o nome físico da coluna.
- `save()` dispara os eventos JAPE configurados (`BeforeUpdate`/`AfterUpdate`).
- `remove()` dispara `BeforeDelete`/`AfterDelete`.

---

## Execução de SQL/procedures: `QueryExecutor`

Acessível via `ContextoAcao.getQuery()`. Executor leve para SQL ad-hoc dentro do botão.

```java
public interface br.com.sankhya.extensions.actionbutton.QueryExecutor {
    boolean next() throws Exception;
    void reset();

    void nativeSelect(String sql) throws Exception;
    void update(String sql) throws Exception;
    Map<String, Object> executeProcedure(
        String nomeProcedure,
        Collection<Object> parametros,
        Collection<String> nomesRetorno) throws Exception;

    void setParam(String nome, Object valor);
    void close();

    BigDecimal getBigDecimal(int col);  BigDecimal getBigDecimal(String nome);
    double     getDouble(int col);      double     getDouble(String nome);
    int        getInt(int col);         int        getInt(String nome);
    String     getString(int col);      String     getString(String nome);
    Timestamp  getTimestamp(int col);   Timestamp  getTimestamp(String nome);
    Date       getDate(int col);        Date       getDate(String nome);
}
```

### Notas

- Use `:NOME` como placeholder no SQL e `setParam("NOME", valor)` para vincular.
- Sempre `close()` no `finally`.
- `nativeSelect` aceita SQL nativo do banco (Oracle/SQL Server) — útil para joins complexos.

---

## Exemplo completo: botão "Recalcular total da nota"

```java
package com.exemplo.botoes;

import br.com.sankhya.extensions.actionbutton.AcaoRotinaJava;
import br.com.sankhya.extensions.actionbutton.ContextoAcao;
import br.com.sankhya.extensions.actionbutton.QueryExecutor;
import br.com.sankhya.extensions.actionbutton.Registro;
import java.math.BigDecimal;

public class RecalcularTotalNota implements AcaoRotinaJava {

    @Override
    public void doAction(ContextoAcao ctx) throws Exception {
        Registro[] notas = ctx.getLinhas();
        if (notas.length == 0) {
            ctx.mostraErro("Selecione ao menos uma nota.");
            return;
        }

        QueryExecutor q = ctx.getQuery();
        try {
            for (Registro nota : notas) {
                BigDecimal nunota = (BigDecimal) nota.getCampo("NUNOTA");

                q.setParam("NUNOTA", nunota);
                q.nativeSelect("SELECT NVL(SUM(VLRTOT),0) FROM TGFITE WHERE NUNOTA = :NUNOTA");
                if (q.next()) {
                    BigDecimal total = q.getBigDecimal(1);
                    nota.setCampo("VLRNOTA", total);
                    nota.save();
                }
                q.reset();
            }
            ctx.setMensagemRetorno("Totais recalculados em " + notas.length + " nota(s).");
        } finally {
            q.close();
        }
    }
}
```

---

## Pontos de atenção

- A classe **deve estar no classpath do servidor de aplicação** quando o servidor sobe.
- Excepcionar via `mostraErro()` é o canal correto para exibir erro ao usuário; outras exceções aparecem como erro técnico genérico.
- Botão de ação roda **dentro da transação** do servidor — alterações são commitadas no fim, ou totalmente revertidas em erro.

---

## Veja também

- `references/api-dynamicvo.md` — para conversões avançadas do `Registro`.
- `references/api-eventos.md` — para gatilhos disparados pelo `save()`.
