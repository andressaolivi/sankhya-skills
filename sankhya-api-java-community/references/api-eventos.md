# API — Eventos Programáveis Java

Pacote: **`br.com.sankhya.extensions.eventoprogramavel`**
Tipo: API pública oficial de extensão.

Eventos programáveis são gatilhos disparados pela camada de persistência do Sankhya (JAPE) sempre que uma entidade é inserida/alterada/removida, ou no commit da transação. Permitem injetar lógica antes ou depois das operações de persistência sem alterar o código do produto.

---

## Interface principal: `EventoProgramavelJava`

```java
public interface br.com.sankhya.extensions.eventoprogramavel.EventoProgramavelJava {
    void beforeInsert(PersistenceEvent ev) throws Exception;
    void beforeUpdate(PersistenceEvent ev) throws Exception;
    void beforeDelete(PersistenceEvent ev) throws Exception;
    void afterInsert(PersistenceEvent ev) throws Exception;
    void afterUpdate(PersistenceEvent ev) throws Exception;
    void afterDelete(PersistenceEvent ev) throws Exception;
    void beforeCommit(TransactionContext ctx) throws Exception;
}
```

Sua classe implementa **todos** os métodos (deixe vazios os que não usar). É associada à entidade pelo cadastro de Eventos no Sankhya — informe a classe e marque os tipos de evento desejados.

---

## Objeto de evento: `PersistenceEvent`

Pacote: `br.com.sankhya.jape.event`. Carrega o estado da operação em curso.

### Métodos comuns em customização

```java
public class PersistenceEvent {

    // Constantes de tipo (uma delas é retornada por getType())
    public static final int BEFORE_INSERT;
    public static final int AFTER_INSERT;
    public static final int BEFORE_UPDATE;
    public static final int AFTER_UPDATE;
    public static final int BEFORE_DELETE;
    public static final int AFTER_DELETE;
    public static final int BEFORE_COMMIT;

    // Acesso ao registro
    EntityVO    getVo();              // VO atual (com valores novos em before*, persistido em after*)
    EntityVO    getOldVO();           // VO antes da alteração (em update/delete)
    Map         getModifiedFields();  // campos alterados desde o último carregamento

    // Acesso à transação
    JdbcWrapper getJdbcWrapper();     // mesma conexão da TX corrente

    // Metadados
    EntityMetaData getEntity();
    int            getType();
    boolean        isConsumed();
    void           setConsumed(boolean v);
}
```

### Notas

- O **VO retornado** por `getVo()` é a entidade com os valores que serão persistidos (em `before*`) ou já persistidos (em `after*`).
- `getOldVO()` só faz sentido em `beforeUpdate`/`afterUpdate`/`beforeDelete`.
- `getModifiedFields()` retorna apenas os campos que mudaram desde o último carregamento — útil para ignorar updates "vazios".
- `getJdbcWrapper()` dá acesso direto a SQL nativo na **mesma conexão** da transação corrente.

---

## Bloco no commit: `TransactionContext`

`beforeCommit` é chamado **uma única vez** ao final da transação, depois de todos os `afterInsert`/`afterUpdate`/`afterDelete`. Útil para validações cross-entidade ou agregações.

---

## Exemplo completo: gravar log de auditoria em afterUpdate

```java
package com.exemplo.eventos;

import br.com.sankhya.extensions.eventoprogramavel.EventoProgramavelJava;
import br.com.sankhya.jape.event.PersistenceEvent;
import br.com.sankhya.jape.event.TransactionContext;
import br.com.sankhya.jape.vo.DynamicVO;
import java.util.Map;

public class AuditoriaParceiro implements EventoProgramavelJava {

    @Override public void beforeInsert(PersistenceEvent ev) throws Exception {}
    @Override public void beforeDelete(PersistenceEvent ev) throws Exception {}
    @Override public void beforeUpdate(PersistenceEvent ev) throws Exception {}
    @Override public void afterInsert(PersistenceEvent ev) throws Exception {}
    @Override public void afterDelete(PersistenceEvent ev) throws Exception {}
    @Override public void beforeCommit(TransactionContext ctx) throws Exception {}

    @Override
    public void afterUpdate(PersistenceEvent ev) throws Exception {
        DynamicVO novo  = (DynamicVO) ev.getVo();
        DynamicVO antigo = (DynamicVO) ev.getOldVO();
        Map alterados = ev.getModifiedFields();

        if (alterados.containsKey("CGC_CPF")) {
            String sql =
                "INSERT INTO AD_LOG_PARC (CODPARC, CAMPO, VLR_ANT, VLR_NOVO, DT_ALT) " +
                "VALUES (?, 'CGC_CPF', ?, ?, SYSDATE)";
            try (var stmt = ev.getJdbcWrapper().getPreparedStatement(sql)) {
                stmt.setObject(1, novo.asBigDecimal("CODPARC"));
                stmt.setString(2, antigo.asString("CGC_CPF"));
                stmt.setString(3, novo.asString("CGC_CPF"));
                stmt.executeUpdate();
            }
        }
    }
}
```

---

## Pontos de atenção

- **Não comitar manualmente** dentro de `before*`/`after*` — o JAPE controla a transação.
- Em `beforeInsert`, **alterar o VO** (`vo.setProperty(...)`) afeta o que será gravado.
- Em `afterInsert`/`afterUpdate`, alterar o VO **não tem efeito** — o JAPE já persistiu.
- Lançar exceção em qualquer `before*`/`after*` aborta a transação inteira.
- Eventos rodam na **mesma thread/sessão JAPE** da transação que disparou — cuidado ao abrir nova `JapeSession` aninhada.

---

## Veja também

- `references/api-dynamicvo.md` — para manipular o VO recebido no evento.
- `references/api-jdbcwrapper.md` — para SQL nativo via `ev.getJdbcWrapper()`.
- `references/api-japesession.md` — para entender o ciclo de vida da transação.
