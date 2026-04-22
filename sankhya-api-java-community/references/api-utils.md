# API — Utilitários e convenções

Conjunto de helpers e convenções transversais usados em quase todo código de customização Sankhya.

---

## `EntityFacadeFactory` — obtenção de `EntityFacade`

Pacote: `br.com.sankhya.modelcore.util`

```java
public class EntityFacadeFactory {
    public static EntityFacade getCoreFacade();
    public static EntityFacade getDWFFacade();    // usado em 99% dos casos
}
```

Detalhes em `references/api-entityfacade.md`. Ponto-chave: **use sempre `getDWFFacade()`** salvo se você está integrando com uma entidade nativa específica do produto.

---

## `MGEModelException` — exceção de negócio

Pacote: `br.com.sankhya.modelcore`

A exceção que vira mensagem amigável ao usuário quando lançada de SPs ou eventos. Use em vez de `RuntimeException` quando quiser que o usuário veja a mensagem:

```java
throw new br.com.sankhya.modelcore.MGEModelException("Cliente bloqueado para venda.");
```

Em action buttons, prefira `ContextoAcao.mostraErro(...)` — internamente lança `MGEModelException`.

---

## `BigDecimal` — convenções

Toda chave primária (`CODPARC`, `NUNOTA`, `CODPROD`, `CODEMP`, etc.) é `BigDecimal` no Sankhya. Convenções comuns:

```java
new BigDecimal(123)        // OK para inteiros
new BigDecimal("123.45")   // SEMPRE use String para decimais (evita imprecisão flutuante)
BigDecimal.ZERO            // melhor que new BigDecimal(0)
vo.asBigDecimalOrZero(...) // null-safe — retorna ZERO em vez de null
```

Comparações:

```java
if (a.compareTo(b) > 0)       // a > b
if (a.signum() == 0)          // a == 0 (mais robusto que compareTo(ZERO) — ignora escala)
```

---

## Datas — `Timestamp` em vez de `Date`/`LocalDateTime`

O Sankhya usa `java.sql.Timestamp` para campos de data/hora (mapeia direto para `DATE` no Oracle ou `DATETIME` no SQL Server).

```java
Timestamp agora = new Timestamp(System.currentTimeMillis());
vo.setProperty("DTNEG", agora);

Timestamp dt = vo.asTimestamp("DTNEG"); // null-safe — retorna null se vazio
```

Não use `LocalDateTime`/`Instant` em VOs — não são reconhecidos pelo serializer JAPE.

---

## Conversão `Registro` ↔ `DynamicVO`

`Registro` (de action buttons / régua / flow) é um wrapper em torno de `DynamicVO`. Em customizações, a conversão típica passa por classes utilitárias do `mge-modelcore`:

```java
DynamicVO vo = (DynamicVO) ((WrappedRegistro) registro).getVO();
```

A forma exata varia por versão. Em código novo, **prefira ficar na API de `Registro`** (`setCampo`/`getCampo`) — só desça para `DynamicVO` quando precisar de `asBigDecimalOrZero`, `getProperty`, etc.

---

## Identificar usuário corrente

```java
import br.com.sankhya.jape.util.JapeSessionContext;
import java.math.BigDecimal;

BigDecimal codUsu = (BigDecimal) JapeSessionContext.getProperty("USUARIO_LOGADO");
```

Mais detalhes em `references/api-japesession.md`.

---

## Pontos de atenção

- Toda **leitura de campo numérico** que pode ser nulo deve usar `asBigDecimalOrZero` ou checar `null` — `asBigDecimal` retorna `null` e quebra `compareTo` se você esquecer.
- Em multi-threading, `JapeSessionContext` é **ThreadLocal** — uma thread filho NÃO herda automaticamente. Use `getProperties()` + `reactivateSession()`.
- Nomes de campo (`"NUNOTA"`, `"CODPARC"`) são **case-sensitive** no JAPE — sempre maiúsculas.
- Em logs, evitar imprimir o `JapeSessionContext.getProperties()` inteiro — pode conter dados sensíveis.

---

## Veja também

- `references/api-japesession.md` — base do contexto de execução.
- `references/api-entityfacade.md` — onde `EntityFacadeFactory` é usado.
- `references/api-jdbcwrapper.md` — para macros do Sankhya em SQL.
