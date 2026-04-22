# API — Régua de Cobrança Java

Pacote: **`br.com.sankhya.extensions.reguacobranca`**
Tipo: API pública oficial de extensão.

A Régua de Cobrança do Sankhya executa ações automatizadas (envio de e-mail, mudança de status, registro de protesto, etc.) sobre títulos a receber. Para regras customizadas que não cabem no que vem de fábrica, implementa-se uma `AcaoReguaCobranca` em Java.

---

## Interface principal: `AcaoReguaCobranca`

```java
public interface br.com.sankhya.extensions.reguacobranca.AcaoReguaCobranca {
    void execute(ContextoRegua ctx) throws Exception;
}
```

Sua classe é referenciada no cadastro da Régua (na configuração de cada etapa) — o motor da régua a invoca quando os títulos baterem nas condições de disparo.

---

## Contexto de execução: `ContextoRegua`

```java
public interface br.com.sankhya.extensions.reguacobranca.ContextoRegua {
    QueryExecutor       getQuery();
    Object              getParam(String nome);              // parâmetros configurados na etapa
    Object              getParametroSistema(String nome);   // parâmetro global (TSIPRM)

    Collection<Registro> getTitulos();                      // títulos elegíveis nesta execução

    void logTitulo(BigDecimal nufin, boolean sucesso, String mensagem);
    void logExecucao(String mensagem);
}
```

### Notas

- `getTitulos()` devolve a coleção de **`Registro`** (mesmo tipo dos botões de ação) — cada um representa um título da `TGFFIN`.
- `logTitulo(NUFIN, sucesso, msg)` grava na trilha de execução da régua **por título** — fica visível no monitor da régua.
- `logExecucao(msg)` grava log **da execução inteira** (não vinculado a um título específico).
- A régua não bloqueia, apenas executa ações; o controle de sucesso/falha por título é via `logTitulo(..., false, ...)`.

---

## Exemplo: enviar e-mail customizado para títulos vencidos

```java
package com.exemplo.regua;

import br.com.sankhya.extensions.reguacobranca.AcaoReguaCobranca;
import br.com.sankhya.extensions.reguacobranca.ContextoRegua;
import br.com.sankhya.extensions.actionbutton.QueryExecutor;
import br.com.sankhya.extensions.actionbutton.Registro;
import java.math.BigDecimal;

public class EmailCobrancaCustomizado implements AcaoReguaCobranca {

    @Override
    public void execute(ContextoRegua ctx) throws Exception {
        QueryExecutor q = ctx.getQuery();
        try {
            for (Registro titulo : ctx.getTitulos()) {
                BigDecimal nufin   = (BigDecimal) titulo.getCampo("NUFIN");
                BigDecimal codparc = (BigDecimal) titulo.getCampo("CODPARC");

                q.setParam("CODPARC", codparc);
                q.nativeSelect("SELECT EMAIL FROM TGFPAR WHERE CODPARC = :CODPARC");
                String email = q.next() ? q.getString(1) : null;
                q.reset();

                if (email == null || email.isBlank()) {
                    ctx.logTitulo(nufin, false, "Cliente sem e-mail cadastrado");
                    continue;
                }

                String corpo = "Identificamos pendência no título " + nufin +
                               ". Por favor, entrar em contato.";
                EmailService.enviar(email, "Cobrança — título " + nufin, corpo);

                ctx.logTitulo(nufin, true, "E-mail enviado para " + email);
            }
            ctx.logExecucao("Régua executada em " + ctx.getTitulos().size() + " títulos.");
        } finally {
            q.close();
        }
    }
}
```

---

## Pontos de atenção

- `getTitulos()` já retorna **apenas** os títulos que casam com as condições da etapa configurada — não é preciso filtrar de novo.
- Cada execução roda **transacional** — uma exceção não tratada cancela tudo. Para resiliência, capturar exceção por título e logar via `logTitulo(..., false, ...)`.
- A régua já controla envio repetido pelo histórico; se sua ação grava status próprio, marque via `setCampo` + `save` no próprio `Registro`.

---

## Veja também

- `references/api-actionbuttons.md` — `Registro` e `QueryExecutor` têm a mesma API aqui.
