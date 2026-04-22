# sankhya-api-java (community)

Skill de conhecimento sobre as **APIs de extensão Java do ERP Sankhya** para uso no Claude.ai.

Voltada para consultores, parceiros e desenvolvedores que customizam o Sankhya em Java.

## O que cobre

Os **pontos de extensão oficiais** do produto, documentados pela própria Sankhya
no portal de parceiros e amplamente discutidos na comunidade de consultores:

- **Action Buttons** — `AcaoRotinaJava` + contexto de execução
- **Eventos Programáveis** — `EventoProgramavelJava` (BeforeInsert, AfterUpdate, etc.)
- **Regras de Negócio** — `RegraNegocioJava` para alçadas e liberações
- **Workflow / BPM** — `EventoProcessoJava`, `TarefaJava`
- **Régua de Cobrança** — `AcaoReguaCobranca`

Mais padrões comuns de uso da camada de persistência:

- **DynamicVO** — leitura/escrita de campos
- **EntityFacade** + **FinderWrapper** — CRUD de entidades
- **JapeSession** — controle de sessão/transação
- **JdbcWrapper** — SQL nativo com macros do Sankhya
- **ServiceBroker** + **ServiceContext** — padrão de chamadas HTTP/JSON

## Origem do conteúdo

Compilado a partir de:

- Documentação oficial do **Portal de Parceiros Sankhya** (interfaces públicas de extensão)
- **Treinamentos de customização** Sankhya
- Conhecimento compartilhado em **fóruns e comunidades** de consultores
- Experiência prática de implementação em projetos

Não inclui código-fonte do produto, descritores internos, mapeamentos JNDI privados
ou catálogo completo de serviços internos. Apenas as interfaces e padrões usados
no dia a dia da consultoria.

## Versão

Voltada para a família **Sankhya Om 4.x**. Em versões mais antigas (3.x) ou mais
recentes, algumas assinaturas podem variar — sempre validar contra o ambiente real
do cliente.

## Estrutura

- `SKILL.md` — manifesto da skill
- `README.md` — este arquivo
- `references/*.md` — categorias da API (action buttons, eventos, JAPE, etc.)
- `LICENSE` — licença MIT

## Uso

1. Baixe o `.zip` do release (ou clone o repositório).
2. No Claude.ai, vá em **Settings → Capabilities → Skills**.
3. **Upload skill** apontando para o `.zip`.
4. Pronto — o Claude passa a responder dúvidas de customização Java do Sankhya
   usando este conhecimento como base.

## Limitações

- Cobertura de **interfaces e padrões públicos**, não da implementação interna do produto.
- APIs internas (`DynamicVO`, `JapeSession`, `EntityFacade`, etc.) **não têm garantia
  de estabilidade** entre versões do Sankhya — exemplos podem precisar de ajuste em
  upgrades maiores.
- Esta skill é mantida pela comunidade, **não tem vínculo oficial** com a Sankhya.
- Para **suporte oficial**, sempre consulte o portal de parceiros e os canais
  oficiais da Sankhya.

## Aviso legal

Sankhya, Sankhya Om e marcas relacionadas são propriedade da **Sankhya Gestão de
Negócios**. Este projeto é um material educativo da comunidade e **não substitui**
a documentação oficial nem implica endosso por parte da fabricante.

## Contribuir

PRs com correções, novos exemplos de uso ou cobertura de interfaces faltantes são
bem-vindos. Mantenha o foco em **APIs públicas de extensão** e **padrões da
comunidade** — não envie conteúdo extraído por engenharia reversa, descompilação
ou outros meios que possam infringir o EULA do produto.

## Licença

MIT — veja `LICENSE`. Aplica-se ao **conteúdo desta skill** (textos, exemplos,
estrutura), não a marcas ou produtos da Sankhya.
