# API — JdbcWrapper (SQL nativo)

Pacote: **`br.com.sankhya.jape.dao`**
Tipo: API interna do JAPE — usada quando `EntityFacade`/`FinderWrapper` não cobrem a query.

`JdbcWrapper` é um wrapper sobre `java.sql.Connection` que adiciona suporte a **macros do Sankhya** (placeholders especiais como `:USUARIO_LOGADO`), conhecimento do dialeto do banco, e statement cache. Implementa `AutoCloseable`.

> Por ser interno do produto, não há garantia de estabilidade entre versões — sempre validar contra o ambiente do cliente.

---

## Como obter

```java
// (1) Datasource padrão (conexão da sessão JAPE corrente):
JdbcWrapper jdbc = ef.getJdbcWrapper();

// (2) Datasource alternativo (outra base):
JdbcWrapper jdbc2 = ef.getJdbcWrapper("java:/MEU_DS_ALTERNATIVO");

// (3) Dentro de evento programável (mesma conexão da TX corrente):
public void afterUpdate(PersistenceEvent ev) throws Exception {
    JdbcWrapper jdbc = ev.getJdbcWrapper();
    // ...
}
```

---

## Métodos comuns em customização

```java
public class JdbcWrapper implements AutoCloseable {

    // ─── conexão ──────────────────────────────────────────────────────────
    public Connection getConnection();
    public DataSource getDataSource();
    public String     getDSJndiName();

    // ─── dialeto ──────────────────────────────────────────────────────────
    public boolean isOracle();
    public boolean isSQLServer();
    public String  getDatabaseVendor();

    // ─── statements ───────────────────────────────────────────────────────
    public PreparedStatement getPreparedStatement(String sql) throws Exception;
    public PreparedStatement getPreparedStatementForSearch(String sql) throws Exception;

    // ─── macros ───────────────────────────────────────────────────────────
    public String  doTranslateMacros(String sql) throws Exception;
    public boolean getTranslateMacros();
    public void    setTranslateMacros(boolean v);

    // ─── limites ──────────────────────────────────────────────────────────
    public int  getMaxRows();
    public void setMaxRows(int n);
    public int  getQueryTimeout();
    public void setQueryTimeout(int seg);

    // ─── ciclo de vida ────────────────────────────────────────────────────
    public void closeSession();
    // close() herdado de AutoCloseable
}
```

---

## Macros do Sankhya em SQL

Quando obtém o statement via `JdbcWrapper.getPreparedStatement(...)`, o wrapper substitui placeholders especiais antes de executar:

| Macro | Resolve para |
|---|---|
| `:USUARIO_LOGADO` | `CODUSU` do usuário corrente |
| `:CODEMPRESA_LOGADA` | empresa corrente |
| `:NOMEUSUARIO` | nome do usuário corrente |
| `:DATA_CORRENTE` | data/hora corrente do servidor |

A lista exata depende da versão e dos `Domain` registrados.

---

## Padrões idiomáticos

### Leitura simples

```java
JdbcWrapper jdbc = ef.getJdbcWrapper();
String sql = "SELECT NOMEPARC, CGC_CPF FROM TGFPAR WHERE CODPARC = ?";
try (PreparedStatement ps = jdbc.getPreparedStatement(sql)) {
    ps.setBigDecimal(1, codparc);
    try (ResultSet rs = ps.executeQuery()) {
        if (rs.next()) {
            String nome = rs.getString("NOMEPARC");
            String cgc  = rs.getString("CGC_CPF");
            // ...
        }
    }
}
```

### Update / DML

```java
String upd = "UPDATE TGFCAB SET OBSERVACAO = ? WHERE NUNOTA = ?";
try (PreparedStatement ps = jdbc.getPreparedStatement(upd)) {
    ps.setString(1, "Atualizado em job " + new Date());
    ps.setBigDecimal(2, nunota);
    int n = ps.executeUpdate();
}
```

### Procedure

```java
String call = "{ call SP_RECALCULA_CUSTO(?, ?) }";
try (CallableStatement cs = jdbc.getConnection().prepareCall(call)) {
    cs.setBigDecimal(1, codprod);
    cs.registerOutParameter(2, java.sql.Types.NUMERIC);
    cs.execute();
    BigDecimal custo = cs.getBigDecimal(2);
}
```

### Usando macros do Sankhya

```java
String sql = "INSERT INTO AD_LOG (USU, DH, MSG) VALUES (:USUARIO_LOGADO, :DATA_CORRENTE, ?)";
try (PreparedStatement ps = jdbc.getPreparedStatement(sql)) {
    ps.setString(1, "ação executada");
    ps.executeUpdate();
}
// :USUARIO_LOGADO e :DATA_CORRENTE são resolvidos pelo wrapper antes da execução
```

---

## Pontos de atenção

- **Não chame `getConnection().close()`** diretamente — isso devolve a conexão ao pool, mas o JAPE pode estar reutilizando-a na mesma sessão. Use try-with-resources nos statements e deixe o JAPE gerenciar a conexão.
- Em customizações dentro de evento/SP, **a mesma conexão** carrega a TX corrente. Operações em outra conexão (`getJdbcWrapper("java:/OUTRO_DS")`) **não participam** da TX corrente.
- `setMaxRows(0)` = sem limite; default herda do datasource.
- `isOracle()` / `isSQLServer()` é a forma correta de fazer SQL condicional ao banco — evita string-matching em `getDatabaseVendor()`.
- Macros (`:USUARIO_LOGADO` etc.) **não funcionam** em statements obtidos de uma conexão crua (`Connection.prepareStatement`) — só passam pelo wrapper se você usar `jdbc.getPreparedStatement(...)`.

---

## Veja também

- `references/api-entityfacade.md` — `getJdbcWrapper()` é um método dela.
- `references/api-japesession.md` — sessão controla a vida da conexão.
- `references/api-eventos.md` — `PersistenceEvent.getJdbcWrapper()` dá a conexão da TX em curso.
