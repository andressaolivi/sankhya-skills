# API — Regras de Negócio Java

Pacote: **`br.com.sankhya.extensions.regrasnegocio`**
Tipo: API pública oficial de extensão.

Regras de negócio Java rodam em pontos de **alçada/liberação** (especialmente liberações de pedido, central de notas, financeiro). Cada regra recebe um contexto enxuto e devolve sucesso/falha + mensagem ao usuário.

---

## Interface principal: `RegraNegocioJava`

```java
public interface br.com.sankhya.extensions.regrasnegocio.RegraNegocioJava {
    void executa(ContextoRegra ctx) throws Exception;
}
```

Sua classe implementa essa interface. No cadastro de Regra de Negócio, informa-se a classe (`com.exemplo.regras.MinhaRegra`). O Sankhya carrega via reflection no momento da execução da liberação.

---

## Contexto da regra: `ContextoRegra`

```java
public interface br.com.sankhya.extensions.regrasnegocio.ContextoRegra {
    void setCodUsuLib(Number codUsuario); // sugere usuário responsável pela liberação
    void setMensagem(String mensagem);    // mensagem mostrada ao usuário
    void setSucesso(boolean sucesso);     // true = aprova, false = bloqueia

    BigDecimal getNunota();               // NUNOTA da nota em liberação (quando aplicável)
    BigDecimal getSequencia();            // sequência da regra na cadeia (ordem)
    BigDecimal getUsuarioLogado();        // CODUSU do usuário corrente

    JdbcWrapper getJdbcWrapper();
    QueryExecutor getQuery();
    Object getParametroSistema(String nome);

    void eMail(String para, String assunto, String corpo) throws Exception;
    void mostraErro(String mensagem) throws Exception;
}
```

### Notas

- **`setSucesso(true)`** = aprova esta regra (passa para a próxima da cadeia ou libera).
- **`setSucesso(false)`** + **`setMensagem(...)`** = bloqueia, mostra a mensagem ao usuário.
- `mostraErro(...)` é equivalente a `setSucesso(false) + throw` — aborta com erro visível.
- `getNunota()` retorna o número da nota em análise (apenas em regras de central de notas).
- `getJdbcWrapper()` reutiliza a conexão da transação corrente — não fechá-la.

---

## Exemplo: bloquear liberação se o cliente está inadimplente

```java
package com.exemplo.regras;

import br.com.sankhya.extensions.regrasnegocio.RegraNegocioJava;
import br.com.sankhya.extensions.regrasnegocio.ContextoRegra;
import br.com.sankhya.extensions.actionbutton.QueryExecutor;
import java.math.BigDecimal;

public class BloqueiaInadimplente implements RegraNegocioJava {

    @Override
    public void executa(ContextoRegra ctx) throws Exception {
        BigDecimal nunota = ctx.getNunota();
        QueryExecutor q = ctx.getQuery();
        try {
            q.setParam("NUNOTA", nunota);
            q.nativeSelect(
                "SELECT NVL(SUM(VLRDESDOB - VLRBAIXA),0) " +
                "  FROM TGFFIN F " +
                " INNER JOIN TGFCAB N ON N.CODPARC = F.CODPARC " +
                " WHERE N.NUNOTA = :NUNOTA " +
                "   AND F.DTVENC < SYSDATE " +
                "   AND F.RECDESP = 1 " +
                "   AND F.DESDOBRAMENTO IS NULL"
            );
            if (q.next()) {
                BigDecimal saldoVencido = q.getBigDecimal(1);
                if (saldoVencido.signum() > 0) {
                    ctx.setSucesso(false);
                    ctx.setMensagem(
                        "Cliente possui R$ " + saldoVencido + " vencido. " +
                        "Liberação bloqueada — encaminhar para análise financeira."
                    );
                    return;
                }
            }
            ctx.setSucesso(true);
        } finally {
            q.close();
        }
    }
}
```

---

## Pontos de atenção

- Regra de negócio **NÃO** persiste alterações sozinha — só decide aprovar/bloquear. Para alterar dados, use Botão de Ação ou Evento Programável.
- Se a regra esquecer de chamar `setSucesso(...)`, o comportamento padrão é **bloquear** (segurança).
- Em cadeia de regras, o motor executa na ordem definida e **para na primeira falha**.
- A `JdbcWrapper` retornada compartilha a transação principal — fazer `INSERT` aqui é arriscado.

---

## Veja também

- `references/api-actionbuttons.md` — `QueryExecutor` e `Registro` têm a mesma semântica.
- `references/api-jdbcwrapper.md` — para SQL avançado.
