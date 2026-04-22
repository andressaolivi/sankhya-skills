# API — JapeSession (controle de sessão e transação)

Pacote: **`br.com.sankhya.jape.core`** e **`br.com.sankhya.jape.util`**
Tipo: API interna do JAPE — central para qualquer ciclo de vida de transação.

`JapeSession` é o ponto de controle para abrir, transacionar e fechar uma sessão JAPE. Em customizações dentro do servidor (eventos, action buttons, regras, services SP) **a sessão já está aberta** pela infra — você só precisa abrir manualmente em jobs/scripts/threads próprias.

> Por ser interno do produto, não há garantia de estabilidade entre versões — sempre validar contra o ambiente do cliente.

---

## Modelo conceitual

- Uma **sessão JAPE** está vinculada a uma `Thread` via `ThreadLocal`.
- Dentro de uma sessão, você abre um **`SessionHandle`** para usar a conexão JDBC e (opcionalmente) demarcar transação.
- Existem três blocos transacionais principais:
  - **`TXBlock`** → executa em transação corrente (cria se não houver).
  - **`NewTXBody`** → suspende a TX corrente e abre uma **autônoma** (commita independente da pai).
  - **`NoTXBody`** → executa **sem** transação (read-only ou DDL).

---

## Padrão idiomático: abrir → executar em TX → fechar

### Forma com handle explícito

```java
import br.com.sankhya.jape.core.JapeSession;

JapeSession.SessionHandle hnd = null;
try {
    hnd = JapeSession.open();
    hnd.execWithTX(() -> {
        EntityFacade ef = EntityFacadeFactory.getDWFFacade();
        DynamicVO vo = (DynamicVO) ef.findEntityByPrimaryKeyAsVO("Parceiro", new Object[]{ codparc });
        vo.setProperty("OBSERVACAO", "Atualizado via job");
        ef.saveEntity("Parceiro", vo);
    });
} finally {
    JapeSession.close(hnd);
}
```

### Forma estática (mais enxuta)

```java
JapeSession.execWithAutonomousTX(() -> {
    // código aqui — TX abre e commita ao final do bloco
    return resultado;
});
```

---

## API estática (uso comum)

```java
public class JapeSession {
    // ─── ciclo de vida ─────────────────────────────────────────────────────
    public static SessionHandle open();
    public static void          close();
    public static void          close(SessionHandle h);
    public static boolean       hasCurrentSession();
    public static JapeSession   getCurrentSession();

    // ─── execução transacional ────────────────────────────────────────────
    public static void   execEnsuringTX(TXBlock body) throws Exception;
    public static Object execWithNoTX(NoTXBody body) throws Exception;
    public static Object execWithAutonomousTX(NewTXBody body) throws Exception;

    // ─── propriedades da sessão (snapshot por-thread) ─────────────────────
    public static Object getProperty(String chave);
    public static Object getProperty(String chave, Object dflt);
}
```

### Quando usar cada modo

| Bloco | Quando |
|---|---|
| `execEnsuringTX(TXBlock)` | Customização que precisa estar em transação, mas pode aproveitar a TX em curso. |
| `execWithAutonomousTX(NewTXBody)` | Você precisa **commitar independente** do que aconteça com a TX externa (logs de auditoria, jobs disparados de evento). |
| `execWithNoTX(NoTXBody)` | Apenas leitura ou comandos que não exigem TX. |

---

## Tipos funcionais (lambdas) — interfaces dos blocos

```java
public interface JapeSession.TXBlock {
    void doWithTx() throws Exception;
}

public interface JapeSession.NewTXBody {
    Object run() throws Exception;
}

public interface JapeSession.NoTXBody {
    Object run() throws Exception;
}
```

Em Java 8+, podem ser passados como lambdas:

```java
JapeSession.execEnsuringTX(() -> {
    /* ... */
});
```

---

## `SessionHandle` — handle ativo

Retornado por `JapeSession.open()`. Métodos comuns em customização:

```java
public class JapeSession.SessionHandle {

    public boolean execWithTX    (TXBlock body) throws Exception;
    public void    execEnsuringTX(TXBlock body) throws Exception;

    // Tarefas pós-commit / pós-rollback:
    public void addOnSucessTXTask (Runnable r) throws Exception;
    public void addOnFailureTXTask(Runnable r) throws Exception;

    // Limites:
    public void setFindersMaxRows(int n);
    public void setSessionTimeout(long ms);
}
```

> O método pós-commit chama-se literalmente `addOnSucessTXTask` (assim mesmo no produto). Use-o para disparar notificações depois que a transação confirmar — sem risco de o destinatário ler dado antes do commit.

---

## `JapeSessionContext` — propriedades de contexto

Pacote: `br.com.sankhya.jape.util`. Estado por-thread (ThreadLocal) usado para passar identidade do usuário, idioma, etc.

```java
public class JapeSessionContext {
    public static Object getProperty(String chave);
    public static Object getProperty(String chave, Object dflt);
    public static void   putProperty(String chave, Object valor);
    public static Object removeProperty(String chave);
    public static Map    getProperties();
    public static void   reactivateSession(Map props);
    public static void   clear();
}
```

### Propriedades-chave usadas pelo Sankhya

| Chave (string) | Significado |
|---|---|
| `"USUARIO_LOGADO"` | `BigDecimal` com o `CODUSU` corrente |

> O nome exato e a presença de outras chaves variam entre versões. Em caso de dúvida, faça `JapeSessionContext.getProperties().forEach(...)` em runtime para listar.

---

## Exemplo: job standalone (fora do servidor) que precisa abrir sessão

```java
import br.com.sankhya.jape.core.JapeSession;
import br.com.sankhya.jape.util.JapeSessionContext;
import br.com.sankhya.modelcore.util.EntityFacadeFactory;
import br.com.sankhya.jape.EntityFacade;
import java.math.BigDecimal;

public class MeuJob {

    public void executar() throws Exception {
        JapeSession.SessionHandle hnd = JapeSession.open();
        try {
            JapeSessionContext.putProperty("USUARIO_LOGADO", new BigDecimal(0)); // SUP
            hnd.execWithTX(() -> {
                EntityFacade ef = EntityFacadeFactory.getDWFFacade();
                // ... operações ...
            });
        } finally {
            JapeSession.close(hnd);
        }
    }
}
```

> Em event programáveis, action buttons e SPs, o servidor **já abriu** a sessão e populou `USUARIO_LOGADO`. Não chame `open()`/`close()` lá — vai dar erro de sessão duplicada.

---

## Pontos de atenção

- `JapeSession.open()` **sem** `JapeSession.close()` causa vazamento de conexão (e travamento do pool). **Sempre** em `try/finally`.
- Evite `execWithAutonomousTX` desnecessário — abrir TX nova é caro. Use só quando precisar commitar isolado.
- Em `addOnSucessTXTask`, evite operações longas — elas atrasam a percepção de fim da transação.
- Lambdas dentro de blocos JAPE devem **lançar exceções** (todas as interfaces declaram `throws Exception`).

---

## Veja também

- `references/api-entityfacade.md` — operações executadas dentro da sessão.
- `references/api-jdbcwrapper.md` — `EntityFacade.getJdbcWrapper()` reutiliza a conexão da sessão.
- `references/api-eventos.md` — eventos rodam dentro da sessão da TX que disparou.
