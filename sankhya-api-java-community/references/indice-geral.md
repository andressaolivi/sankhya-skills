# Índice Geral — APIs documentadas

Mapa rápido das interfaces e classes cobertas nesta skill, com link para o arquivo de referência onde estão documentadas.

---

## APIs públicas de extensão (`br.com.sankhya.extensions.*`)

São as **interfaces oficialmente expostas** pela Sankhya para customização. Documentadas no portal de parceiros e estáveis entre versões.

### Action Buttons (`br.com.sankhya.extensions.actionbutton`)

| Interface | Tipo | Documentado em |
|---|---|---|
| `AcaoRotinaJava` | interface | [api-actionbuttons.md](api-actionbuttons.md) |
| `ContextoAcao` | interface | [api-actionbuttons.md](api-actionbuttons.md) |
| `QueryExecutor` | interface | [api-actionbuttons.md](api-actionbuttons.md) |
| `Registro` | interface | [api-actionbuttons.md](api-actionbuttons.md) |

### Eventos Programáveis (`br.com.sankhya.extensions.eventoprogramavel`)

| Interface | Tipo | Documentado em |
|---|---|---|
| `EventoProgramavelJava` | interface | [api-eventos.md](api-eventos.md) |

### Regras de Negócio (`br.com.sankhya.extensions.regrasnegocio`)

| Interface | Tipo | Documentado em |
|---|---|---|
| `RegraNegocioJava` | interface | [api-regrasnegocio.md](api-regrasnegocio.md) |
| `ContextoRegra` | interface | [api-regrasnegocio.md](api-regrasnegocio.md) |

### Workflow / BPM (`br.com.sankhya.extensions.flow`)

| Interface | Tipo | Documentado em |
|---|---|---|
| `EventoProcessoJava` | interface | [api-flow.md](api-flow.md) |
| `TarefaJava` | interface | [api-flow.md](api-flow.md) |
| `ContextoFlowGet` | interface | [api-flow.md](api-flow.md) |
| `ContextoFlow` | interface | [api-flow.md](api-flow.md) |
| `ContextoTarefa` | interface | [api-flow.md](api-flow.md) |
| `ContextoEvento` | interface | [api-flow.md](api-flow.md) |

### Régua de Cobrança (`br.com.sankhya.extensions.reguacobranca`)

| Interface | Tipo | Documentado em |
|---|---|---|
| `AcaoReguaCobranca` | interface | [api-reguacobranca.md](api-reguacobranca.md) |
| `ContextoRegua` | interface | [api-reguacobranca.md](api-reguacobranca.md) |

---

## APIs internas amplamente usadas

Não são interfaces oficialmente públicas, mas aparecem em quase todo código de customização. Estabilidade entre versões **não é garantida** pela Sankhya — sempre validar contra o ambiente do cliente.

### Persistência — JAPE

| Classe / Interface | Pacote | Documentado em |
|---|---|---|
| `EntityFacade` | `br.com.sankhya.jape` | [api-entityfacade.md](api-entityfacade.md) |
| `FinderWrapper` | `br.com.sankhya.jape.util` | [api-entityfacade.md](api-entityfacade.md) |
| `PersistentLocalEntity` | `br.com.sankhya.jape.bmp` | [api-entityfacade.md](api-entityfacade.md) |
| `EntityPrimaryKey` | `br.com.sankhya.jape.dao` | [api-entityfacade.md](api-entityfacade.md) |
| `DynamicVO` | `br.com.sankhya.jape.vo` | [api-dynamicvo.md](api-dynamicvo.md) |
| `EntityVO` | `br.com.sankhya.jape.vo` | [api-dynamicvo.md](api-dynamicvo.md) |
| `JdbcWrapper` | `br.com.sankhya.jape.dao` | [api-jdbcwrapper.md](api-jdbcwrapper.md) |
| `PersistenceEvent` | `br.com.sankhya.jape.event` | [api-eventos.md](api-eventos.md) |
| `TransactionContext` | `br.com.sankhya.jape.event` | [api-eventos.md](api-eventos.md) |

### Sessão / Contexto — JAPE

| Classe | Pacote | Documentado em |
|---|---|---|
| `JapeSession` | `br.com.sankhya.jape.core` | [api-japesession.md](api-japesession.md) |
| `JapeSession.SessionHandle` | `br.com.sankhya.jape.core` | [api-japesession.md](api-japesession.md) |
| `JapeSession.TXBlock` (interface) | `br.com.sankhya.jape.core` | [api-japesession.md](api-japesession.md) |
| `JapeSession.NewTXBody` (interface) | `br.com.sankhya.jape.core` | [api-japesession.md](api-japesession.md) |
| `JapeSession.NoTXBody` (interface) | `br.com.sankhya.jape.core` | [api-japesession.md](api-japesession.md) |
| `JapeSessionContext` | `br.com.sankhya.jape.util` | [api-japesession.md](api-japesession.md), [api-utils.md](api-utils.md) |

### ServiceBroker

| Classe | Pacote | Documentado em |
|---|---|---|
| `ServiceContext` | `br.com.sankhya.ws` | [api-servicebroker.md](api-servicebroker.md) |
| `GatewayServiceProviderSP` (serviço público) | — | [api-servicebroker.md](api-servicebroker.md) |
| `ActionButtonsSP` (serviço público) | — | [api-servicebroker.md](api-servicebroker.md) |
| `DatasetSP` (serviço público) | — | [api-servicebroker.md](api-servicebroker.md) |
| `PesquisaSP` (serviço público) | — | [api-servicebroker.md](api-servicebroker.md) |

### Helpers

| Classe | Pacote | Documentado em |
|---|---|---|
| `EntityFacadeFactory` | `br.com.sankhya.modelcore.util` | [api-entityfacade.md](api-entityfacade.md), [api-utils.md](api-utils.md) |
| `MGEModelException` | `br.com.sankhya.modelcore` | [api-utils.md](api-utils.md) |

---

## Convenções

| Tópico | Onde |
|---|---|
| `BigDecimal` (chaves primárias e valores numéricos) | [api-utils.md](api-utils.md) |
| `Timestamp` (datas/hora) | [api-utils.md](api-utils.md) |
| Conversão `Registro` ↔ `DynamicVO` | [api-utils.md](api-utils.md), [api-dynamicvo.md](api-dynamicvo.md) |
| Identificar usuário corrente | [api-japesession.md](api-japesession.md), [api-utils.md](api-utils.md) |
| Macros do Sankhya em SQL (`:USUARIO_LOGADO`, `:DATA_CORRENTE`) | [api-jdbcwrapper.md](api-jdbcwrapper.md) |

---

## Não coberto nesta skill

- Catálogo completo de SPs (Service Providers) internos do Sankhya — varia por versão e módulos instalados; consulte a documentação oficial.
- Classes específicas de módulos verticais (comercial, financeiro, fiscal, contábil, RH, WMS, produção) — consulte o portal de parceiros para a vertical em questão.
- Internals da camada DWF (`br.com.sankhya.dwf.*`), módulo de relatórios e infra de UI — não são pontos de extensão estáveis.

Para esses casos, sempre prefira:
1. Documentação oficial do **Portal de Parceiros Sankhya**
2. Consulta direta ao **suporte/canal oficial** Sankhya
3. **Comunidade de consultores** (fóruns, grupos)

---

## Como contribuir

PRs com correções, novos exemplos de uso ou cobertura de interfaces faltantes são bem-vindos. Mantenha o foco em **APIs públicas de extensão** e **padrões da comunidade** — não envie conteúdo extraído por engenharia reversa do produto.
