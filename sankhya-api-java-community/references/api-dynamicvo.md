# API — DynamicVO (manipulação de registros)

Pacote: **`br.com.sankhya.jape.vo`**
Tipo: API interna do JAPE — amplamente usada em customizações.

`DynamicVO` é a representação de uma linha de qualquer entidade Sankhya em memória. Tudo que sai do `EntityFacade` é um `DynamicVO`. É o objeto manipulado em eventos programáveis, action buttons, regras, integrações.

> Por ser interno do produto, não há garantia de estabilidade entre versões — sempre validar contra o ambiente do cliente.

---

## Métodos comuns em customização

### Leitura tipada (atalhos `as*`)

A forma idiomática de ler campos:

```java
DynamicVO nota = ...; // obtido via EntityFacade ou cast de Registro

BigDecimal nunota   = nota.asBigDecimal("NUNOTA");
BigDecimal codparc  = nota.asBigDecimal("CODPARC");
String     statusNF = nota.asString("STATUSNFE");
Timestamp  dtNeg    = nota.asTimestamp("DTNEG");
boolean    confirm  = nota.asBoolean("CONFIRMADA"); // S/N → true/false
int        seq      = nota.asInt("SEQUENCIA");
double     vlr      = nota.asDouble("VLRTOT");
```

Variantes úteis:

| Método | Comportamento |
|---|---|
| `asBigDecimal(campo)` | retorna `null` se o campo for nulo no banco |
| `asBigDecimalOrZero(campo)` | retorna `BigDecimal.ZERO` em vez de null (útil em somatórios) |
| `asString(campo)` | retorna `null` se vazio |
| `asTimestamp(campo)` | `java.sql.Timestamp` para datas |
| `asInt(campo)` / `asLong(campo)` / `asDouble(campo)` | conversões diretas |
| `asBlob(campo)` / `asClob(campo)` | binários e textos longos |

### Escrita: `setProperty`

```java
nota.setProperty("STATUSNFE", "L"); // Liberada
nota.setProperty("DTALTER", new Timestamp(System.currentTimeMillis()));
```

Após `setProperty`, o VO fica marcado como modificado. A persistência ocorre quando:
- Você chama `EntityFacade.saveEntity(...)` passando o VO.
- Você chama `Registro.save()` (em botões de ação — `Registro` envelopa um `DynamicVO`).

**Importante:** alterar um VO recebido em `afterUpdate` não tem efeito — já foi gravado.

### Leitura genérica e existência

```java
Object  v = nota.getProperty("CODVEND");
boolean tem = nota.containsProperty("AD_CAMPOCUSTOM");
```

### Identidade

```java
String nomeEntidade = nota.getElementName();   // "CabecalhoNota", "Parceiro", etc.
Object pk           = nota.getPrimaryKey();
```

---

## Padrão de uso em customização

### Em evento programável

```java
public void beforeInsert(PersistenceEvent ev) throws Exception {
    DynamicVO nota = (DynamicVO) ev.getVo();

    if (nota.asString("CIF_FOB") == null) {
        nota.setProperty("CIF_FOB", "C"); // default CIF se não vier
    }

    BigDecimal codtipoper = nota.asBigDecimal("CODTIPOPER");
    if (codtipoper != null && codtipoper.intValue() == 1100) {
        String obs = nota.asString("OBSERVACAO");
        nota.setProperty("OBSERVACAO",
            (obs == null ? "" : obs) + " [Auto] Venda comum");
    }
}
```

### Em integração / job

```java
DynamicVO parc = (DynamicVO) ef.findEntityByPrimaryKeyAsVO("Parceiro", new Object[]{ codparc });
parc.setProperty("OBSERVACAO", "Atualizado via integração");
ef.saveEntity("Parceiro", parc);
```

---

## Conversão: `Registro` → `DynamicVO`

`Registro` (de action buttons / régua / flow) é um wrapper em torno de `DynamicVO`. Em customizações, a conversão típica usa cast a partir do método auxiliar disponível:

```java
// O método exato varia por versão; padrão observado em consultoria:
DynamicVO vo = (DynamicVO) ((WrappedRegistro) registro).getVO();
```

Em customizações novas, prefira **ficar na API de `Registro`** (`setCampo`/`getCampo`) — só desça para `DynamicVO` quando precisar de `asBigDecimalOrZero`, `getProperty`, ou métodos que `Registro` não expõe.

---

## Pontos de atenção

- O nome do campo passado para `as*`/`getProperty` é o **nome lógico** (mesmo que aparece no TDD — coluna `NOMECAMPO`), não o físico da coluna.
- Nomes de campo são **case-sensitive** — sempre maiúsculas no padrão Sankhya.
- VOs **não são thread-safe**. Não compartilhar entre threads.
- Em valores numéricos que podem ser nulos, prefira `asBigDecimalOrZero` ou cheque `null` — `asBigDecimal` retorna `null` e quebra `compareTo` se você esquecer.
- Use `Timestamp` (não `LocalDateTime`/`Instant`) — o serializer JAPE não reconhece os tipos modernos do `java.time`.

---

## Veja também

- `references/api-entityfacade.md` — para obter VOs do banco.
- `references/api-eventos.md` — VOs chegam via `PersistenceEvent.getVo()`.
- `references/api-actionbuttons.md` — `Registro` é a versão "amigável" do VO.
