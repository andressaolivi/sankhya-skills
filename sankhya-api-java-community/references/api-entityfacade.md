# API — EntityFacade (CRUD JAPE)

Pacote: **`br.com.sankhya.jape`**
Tipo: API interna do JAPE — central para qualquer operação de persistência.

`EntityFacade` é o ponto de acesso para criar, ler, atualizar e remover entidades do dicionário Sankhya. Usado em botões de ação, eventos, integrações, jobs.

> Por ser interno do produto, não há garantia de estabilidade entre versões — sempre validar contra o ambiente do cliente.

---

## Obtenção da instância

Não instancie `EntityFacade` diretamente. Use o factory de `mge-modelcore`:

```java
import br.com.sankhya.modelcore.util.EntityFacadeFactory;
import br.com.sankhya.jape.EntityFacade;

EntityFacade ef = EntityFacadeFactory.getDWFFacade();   // 99% dos casos
// ou:
EntityFacade efCore = EntityFacadeFactory.getCoreFacade();  // entidades nativas mapeadas
```

| Factory | Para quê |
|---|---|
| `getDWFFacade()` | Entidades **dinâmicas** (lidas do TDD/dicionário em runtime) — qualquer entidade do TDD, inclusive customizadas (`AD_*`). É o padrão. |
| `getCoreFacade()` | Entidades nativas mapeadas em XML do produto (uso pontual em integrações específicas). |

---

## Operações comuns

### Buscar por chave primária

```java
// Versão mais idiomática para leitura — retorna o VO direto:
EntityVO vo = ef.findEntityByPrimaryKeyAsVO("Parceiro", new Object[]{ codparc });
DynamicVO parc = (DynamicVO) vo;

// Versão que retorna PersistentLocalEntity (para load + save):
PersistentLocalEntity ple = ef.findEntityByPrimaryKey("Parceiro", new Object[]{ codparc });
DynamicVO p = (DynamicVO) ple.getValueObject();

// Chave composta (ex.: ItemNota = NUNOTA + SEQUENCIA):
EntityPrimaryKey pk = ef.getPrimaryKeyFromMap("ItemNota",
        Map.of("NUNOTA", nunota, "SEQUENCIA", BigDecimal.ONE));
PersistentLocalEntity item = ef.findEntityByPrimaryKey("ItemNota", pk);
```

### Buscar por filtro (FinderWrapper)

```java
import br.com.sankhya.jape.util.FinderWrapper;

FinderWrapper f = new FinderWrapper(
    "CabecalhoNota",
    "this.CODPARC = ? AND this.DTNEG > ?",
    "this.NUNOTA DESC",
    new Object[]{ codparc, dataInicio }
);

Collection<EntityVO> notas = ef.findByDynamicFinderAsVO(f);
```

Sintaxe do `where`:
- Use **`this.NOMECAMPO`** para referenciar campos da entidade base.
- Placeholders **`?`** correspondem na ordem aos `Object[]` passado.
- Suporta operadores SQL básicos (`=`, `<>`, `LIKE`, `IN (...)`, `IS NULL`, etc.).

Variantes:

```java
ef.findByDynamicFilter("Parceiro", "this.ATIVO = 'S'");        // sem parâmetros
ef.findByDynamicFinder(f);                                      // retorna PersistentLocalEntity
ef.findByDynamicFinderAsVO(f);                                  // retorna EntityVO
ef.findByDynamicFinderAsVO(f, MeuVOWrapper.class);              // com wrapper customizado
```

### Criar nova entidade

```java
DynamicVO novo = (DynamicVO) ef.getDefaultValueObjectInstance("Parceiro");
novo.setProperty("NOMEPARC", "Cliente Novo LTDA");
novo.setProperty("CGC_CPF", "00000000000191");
novo.setProperty("ATIVO", "S");
ef.createEntity("Parceiro", novo); // dispara BeforeInsert/AfterInsert
```

### Atualizar existente

```java
PersistentLocalEntity ple = ef.findEntityByPrimaryKey("Parceiro", new Object[]{ codparc });
DynamicVO vo = (DynamicVO) ple.getValueObject();
vo.setProperty("OBSERVACAO", "Atualizado via integração");
ef.saveEntity("Parceiro", vo); // dispara BeforeUpdate/AfterUpdate
```

### Remover

```java
ef.removeEntity("Parceiro", new Object[]{ codparc });

// Em massa, por critério:
int removidos = ef.removeByCriteria(
    new FinderWrapper("MinhaEntidade", "this.STATUS = ?", new Object[]{"X"})
);
```

---

## Helpers

```java
// VO em branco com defaults da entidade:
EntityVO vazio = ef.getDefaultValueObjectInstance("Parceiro");

// JdbcWrapper para SQL nativo (ver references/api-jdbcwrapper.md):
JdbcWrapper jdbc = ef.getJdbcWrapper();

// Construir EntityPrimaryKey a partir de Map:
EntityPrimaryKey pk = ef.getPrimaryKeyFromMap("ItemNota",
        Map.of("NUNOTA", nunota, "SEQUENCIA", seq));
```

---

## Exemplo completo: criar nota e itens em transação

```java
import br.com.sankhya.jape.EntityFacade;
import br.com.sankhya.jape.bmp.PersistentLocalEntity;
import br.com.sankhya.jape.core.JapeSession;
import br.com.sankhya.jape.vo.DynamicVO;
import br.com.sankhya.modelcore.util.EntityFacadeFactory;
import java.math.BigDecimal;

public class CriadorNota {

    public BigDecimal criar(BigDecimal codparc, BigDecimal codtipoper) throws Exception {
        return (BigDecimal) JapeSession.execWithAutonomousTX(() -> {
            EntityFacade ef = EntityFacadeFactory.getDWFFacade();

            DynamicVO cab = (DynamicVO) ef.getDefaultValueObjectInstance("CabecalhoNota");
            cab.setProperty("CODPARC", codparc);
            cab.setProperty("CODTIPOPER", codtipoper);
            cab.setProperty("DTNEG", new java.sql.Timestamp(System.currentTimeMillis()));
            cab.setProperty("CODEMP", BigDecimal.ONE);
            cab.setProperty("CODVEND", BigDecimal.ZERO);

            PersistentLocalEntity ple = ef.createEntity("CabecalhoNota", cab);
            BigDecimal nunota = ((DynamicVO) ple.getValueObject()).asBigDecimal("NUNOTA");

            DynamicVO item = (DynamicVO) ef.getDefaultValueObjectInstance("ItemNota");
            item.setProperty("NUNOTA", nunota);
            item.setProperty("CODPROD", new BigDecimal("1001"));
            item.setProperty("QTDNEG", new BigDecimal("10"));
            item.setProperty("VLRUNIT", new BigDecimal("25.00"));
            ef.createEntity("ItemNota", item);

            return nunota;
        });
    }
}
```

---

## Pontos de atenção

- Toda operação requer **uma `JapeSession` aberta** na thread (em event/action button já está aberta; em jobs standalone você precisa abrir — ver `references/api-japesession.md`).
- O nome da entidade (`"CabecalhoNota"`, `"Parceiro"`, `"ItemNota"`) é o nome lógico do dicionário — consultar TDD ou skill `sankhya-dicionario`.
- Em `findEntityByPrimaryKey`, se o registro não existir, é lançada `PersistenceException` — capturar quando a ausência for caso esperado.
- `createEntity`/`saveEntity` disparam **eventos programáveis** configurados na entidade.

---

## Veja também

- `references/api-japesession.md` — abrir/fechar sessão e blocos transacionais.
- `references/api-dynamicvo.md` — manipular o VO retornado.
- `references/api-jdbcwrapper.md` — quando precisar de SQL nativo (e não cabe em `FinderWrapper`).
