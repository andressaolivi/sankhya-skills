---
name: sankhya-api-java
description: >
  Conhecimento sobre os pontos de extensão Java do ERP Sankhya — interfaces oficiais
  de customização e padrões de uso da camada de persistência. Use quando o usuário
  perguntar sobre customização Java do Sankhya: AcaoRotinaJava, EventoProgramavelJava,
  RegraNegocioJava, TarefaJava, AcaoReguaCobranca, DynamicVO, JapeSession, EntityFacade,
  JdbcWrapper, ServiceContext, ServiceBroker; action buttons, eventos programáveis,
  regras de negócio, workflow Java, régua de cobrança, manipulação de VOs, persistência
  JAPE, SQL nativo com macros do Sankhya. NÃO use para configuração funcional do ERP
  (use sankhya-funcionamento) nem para tabelas do TDD (use sankhya-dicionario).
---

# Skill: API Java do Sankhya (Comunidade)

Esta skill cobre os **pontos de extensão Java oficiais** do ERP Sankhya — as interfaces
e padrões que consultores e parceiros usam para customizar o produto sem alterar
código do fabricante.

> Esta skill cobre **APIs de extensão Java**.
> Para configurações funcionais do ERP, use `sankhya-funcionamento`.
> Para tabelas e campos, use `sankhya-dicionario`.

---

## Arquivos de referência

Leia o(s) arquivo(s) relevante(s) antes de responder:

| Arquivo | Conteúdo | Quando usar |
|---------|----------|-------------|
| `references/indice-geral.md` | Índice das interfaces documentadas, por categoria | Sempre que precisar localizar uma interface por nome |
| `references/api-actionbuttons.md` | `AcaoRotinaJava`, `ContextoAcao`, `QueryExecutor`, `Registro` | "Botão de ação Java", customização disparada por botão na tela |
| `references/api-eventos.md` | `EventoProgramavelJava` (BeforeInsert/AfterUpdate/etc.) + `PersistenceEvent` | Eventos programáveis Java (gatilhos antes/depois de insert/update/delete) |
| `references/api-regrasnegocio.md` | `RegraNegocioJava`, `ContextoRegra` | Regra de negócio Java em alçadas/liberações |
| `references/api-flow.md` | Workflow: `EventoProcessoJava`, `TarefaJava`, contextos do BPM | Customização de processos de Workflow em Java |
| `references/api-reguacobranca.md` | `AcaoReguaCobranca`, `ContextoRegua` | Régua de cobrança Java |
| `references/api-dynamicvo.md` | Padrão de uso do `DynamicVO` (leitura/escrita de campos) | Manipulação de registros em customizações |
| `references/api-entityfacade.md` | Padrão CRUD via `EntityFacade` + `FinderWrapper` | Consultar, criar, atualizar e remover entidades |
| `references/api-japesession.md` | Padrões de uso do `JapeSession` (abertura, blocos transacionais) | Controle de sessão e transação em jobs/scripts standalone |
| `references/api-jdbcwrapper.md` | Padrão de uso do `JdbcWrapper` para SQL nativo | Quando customização precisa rodar SQL/procedure |
| `references/api-servicebroker.md` | Padrão do ServiceBroker e `ServiceContext`; chamadas HTTP | Chamar serviços do Sankhya por HTTP/JSON, criar SPs novos |
| `references/api-utils.md` | Convenções gerais: `BigDecimal`, `Timestamp`, `MGEModelException` | Helpers transversais |

---

## Como responder

1. **Identifique o conceito-chave** na pergunta (botão de ação, evento, regra, flow, VO, sessão, SQL nativo, serviço HTTP).
2. **Leia o arquivo de referência apropriado** antes de redigir a resposta.
3. **Cite o pacote completo** (`br.com.sankhya.extensions.…`) quando a interface for da API pública de extensão.
4. **Forneça um exemplo Java mínimo** sempre que possível — o consultor aprende melhor com código pronto.
5. Lembre que **APIs internas** (DynamicVO, JapeSession, EntityFacade, JdbcWrapper) não têm garantia de estabilidade entre versões — sempre validar contra o ambiente do cliente.

## Avisos importantes

- A skill cobre os padrões usados em **Sankhya Om 4.x** (família de versões).
- As interfaces em `br.com.sankhya.extensions.*` são as **APIs oficiais de customização** do Sankhya — preferir essas sempre que possível.
- Outras classes citadas (`DynamicVO`, `JapeSession`, `EntityFacade`, `JdbcWrapper`, `ServiceContext`) são amplamente usadas em customizações de cliente, mas são **APIs internas** sem garantia de estabilidade entre versões — testar em cada upgrade.
- Os exemplos de código nesta skill seguem padrões públicos compartilhados na comunidade de consultores Sankhya.
