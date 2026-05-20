---
name: sankhya-construtor-telas
description: Criação e import de telas customizadas no Sankhya ERP via Construtor de Telas — geração de metadata.xml, vinculação com tabelas AD_*, definição de campos/agrupamentos/validações e o caminho correto de import (Configurações → Avançado → Construtor de Telas → Importar, NÃO via Dicionário de Dados).
---

# 🧱 sankhya-construtor-telas

> Skill para criar e importar telas customizadas no Sankhya pelo **Construtor de Telas** — incluindo a estrutura do `metadata.xml`, vinculação com tabelas `AD_*`, definição de campos e a regra mais quebrada do processo: **qual tela usar para importar**.

**Versão:** 1.0.0
**Última atualização:** 2026-05-19
**Autora:** Andressa Olivi — [Olivi Consultoria](https://github.com/andressaolivi/com)

---

## 🎯 Quando usar esta skill

- Pergunta envolve **Construtor de Telas**, **metadata.xml**, **tela customizada**, **tela custom**
- Usuário quer **criar/editar/importar tela de cadastro** customizada
- Pergunta menciona **tabelas `AD_*`** vinculadas a uma tela própria
- Erros típicos: "importei mas a tela não apareceu", "campo do XML não vinculou", "validação não disparou", "tela apareceu mas está em branco"
- Palavras-chave: `metadata.xml`, `construtor de telas`, `AD_`, `tela custom`, `tela customizada`, `importar tela`, `Construtor`

## 🚫 Quando NÃO usar

- Para **dashboards e gadgets HTML5** (JSP+XML, `snk:query`) → usar `sankhya-html5`
- Para **estrutura/criação de tabela** (campos, tipos, foreign keys) → usar `sankhya-dicionario`
- Para **fluxo de negócio** que a tela vai operar (vendas, compras, financeiro) → usar `sankhya-funcionamento`
- Para **customizações Java** acionadas pela tela → usar `sankhya-api-java`

> ⚠️ **Distinção importante:** `sankhya-html5` é para **dashboards/relatórios** (gadgets que mostram dados). `sankhya-construtor-telas` é para **telas de cadastro** (CRUD em tabelas, geralmente `AD_*`). São formatos e caminhos de import DIFERENTES.

---

## 📚 Capacidades

- Gerar `metadata.xml` completo de uma tela customizada
- Definir **campos** com tipo, label, ordem, agrupamento, obrigatoriedade
- Configurar **validações** (regex, faixa de valores, dependências entre campos)
- Configurar **filtros default** e **ordenação default** da grade
- Vincular a tela a uma **tabela `AD_*`** existente
- Diagnosticar import que "passou mas a tela não aparece"
- Empacotar e importar pelo caminho correto

## 📂 Arquivos de referência

```
sankhya-construtor-telas/
├── SKILL.md                          ← este arquivo
└── references/
    ├── metadata_estrutura.md         ← Anatomia do XML (root, tabela, campos, grupos)
    ├── tipos_campos.md               ← text, integer, decimal, date, lookup, checkbox, combo
    ├── validacoes_filtros.md         ← Validações, filtros default, ordenação, máscara
    ├── tabelas_ad.md                 ← Convenção AD_*, criação no TDD antes da tela
    ├── import_path.md                ← Caminho correto de import (+ por que NÃO via Dicionário de Dados)
    ├── gotchas.md                    ← Path errado, campos órfãos, IDs duplicados, reimport
    └── indice.md                     ← Mapa de navegação
```

| Reference | Carregar quando |
|---|---|
| `metadata_estrutura.md` | Pergunta menciona "como começar", "estrutura básica", "XML de tela" |
| `tipos_campos.md` | Pergunta sobre tipo de campo específico (lookup, combo, decimal, etc.) |
| `validacoes_filtros.md` | Pergunta envolve validação, filtro default, máscara, regex |
| `tabelas_ad.md` | Pergunta envolve `AD_*`, "criar tabela antes da tela", convenção de nomenclatura |
| `import_path.md` | Pergunta envolve "como importar", "onde importar", "não acho a tela de import" |
| `gotchas.md` | Comportamento inesperado (tela não aparece, campo não vincula, reimport quebra coisa) |
| `indice.md` | Quando não souber em qual reference está o tema |

---

## 🧭 Workflow típico

1. **Criar a tabela `AD_*` primeiro** via Dicionário de Dados (TDD) — TODOS os campos que a tela usará precisam existir
2. **Validar a tabela** — abrir o registro no TDD, confirmar tipos, tamanhos, obrigatoriedades
3. **Escrever o `metadata.xml`** seguindo a estrutura padrão (ver `metadata_estrutura.md`)
4. **Validar o XML localmente** com um parser antes de subir (XML quebrado falha import sem mensagem clara)
5. **Importar pelo caminho correto**: **Configurações → Avançado → Construtor de Telas → Importar** (NÃO pelo Dicionário de Dados — ver Regra 1)
6. **Testar a tela** — criar registro, editar, validar, excluir, testar cada filtro default
7. **Versionar o XML** no git junto com a versão da tabela (se um mudar, o outro provavelmente muda)

---

## ⚠️ Regras críticas (gotchas)

### Regra 1 — Import via Construtor de Telas, NÃO via Dicionário de Dados

**Contexto:** Você gerou o `metadata.xml` e quer importar no Sankhya.

**Regra:** O caminho correto é **Configurações → Avançado → Construtor de Telas → Importar**. **NÃO** importe pelo Dicionário de Dados.

**Por quê:**
- **Dicionário de Dados (TDD)** controla **estrutura de tabela** — criar/alterar tabela, campos, tipos, índices.
- **Construtor de Telas** controla **a tela** — layout, campos visíveis, agrupamentos, validações.

Importar o `metadata.xml` no Dicionário de Dados pode "passar" sem erro (porque o XML é lido) mas **nada acontece** — a tela não é criada. Você fica achando que importou e procurando a tela que não existe.

**Sintoma:** "Importei o XML e a tela não aparece em lugar nenhum."

**Diagnóstico:**
1. Confirmar onde você importou. Se foi no Dicionário de Dados → esse é o problema.
2. Importar de novo, agora em **Configurações → Avançado → Construtor de Telas → Importar**.

> 💡 Esta regra estava **errada** em versões anteriores desta skill (apontava o Dicionário de Dados como caminho de import). Foi corrigida após validação em produção.

---

### Regra 2 — Tabela `AD_*` precisa existir ANTES do import da tela

**Contexto:** Importando `metadata.xml` que referencia uma tabela `AD_*`.

**Regra:** A tabela referenciada no XML precisa já estar criada no TDD com **TODOS** os campos que o XML menciona.

**Por quê:** O Construtor de Telas valida a vinculação no momento do import. Campo no XML que não existe na tabela → import abortado, ou pior, importado com o campo "fantasma" que quebra ao tentar abrir a tela.

**Exemplo ruim:**
```xml
<!-- XML referencia campo NOMECLI mas a tabela AD_CLIENTES_CUSTOM tem só CLIENTE -->
<field name="NOMECLI" type="text" label="Nome do Cliente" />
```

**Exemplo bom:**
1. Dicionário de Dados → confirmar que `AD_CLIENTES_CUSTOM` tem o campo `NOMECLI`
2. Se não tiver, criar lá primeiro
3. Só depois importar o `metadata.xml`

---

### Regra 3 — Convenção `AD_*` para tabelas customizadas

**Contexto:** Criando uma tabela nova que vai ter tela própria via Construtor de Telas.

**Regra:** Tabelas customizadas devem começar com o prefixo `AD_` (de "Adicional"). Tabelas padrão do Sankhya não devem ser modificadas estruturalmente para receber telas custom.

**Por quê:**
- O Sankhya reserva os prefixos padrão (`TGF`, `TSI`, `TFP`, etc.) para tabelas do produto. Mudanças neles podem ser **revertidas** em updates da versão.
- O prefixo `AD_` é o "espaço seguro" do cliente — não é tocado por upgrade.

**Sintoma de violação:** Você adicionou campos numa tabela `TGF*` e, após um update do Sankhya, eles sumiram.

---

### Regra 4 — IDs e nomes únicos dentro do `metadata.xml`

**Contexto:** XML com múltiplos campos, agrupamentos ou validações.

**Regra:** Cada elemento com `id` ou `name` (campo, agrupamento, validação, lookup) deve ser único dentro do XML.

**Por quê:** O parser processa em ordem. Duplicidade vira shadowing silencioso — a segunda definição sobrescreve a primeira, e você descobre só na hora de usar.

**Sintoma:** "Tem dois campos com o mesmo nome no XML, mas só um aparece na tela."

---

### Regra 5 — Reimport ATUALIZA a tela, mas NÃO mexe na tabela

**Contexto:** Você editou o `metadata.xml` (adicionou um campo, mudou um label) e quer reimportar.

**Regra:** Reimport pelo Construtor de Telas atualiza a definição da tela — mas **NÃO** modifica a estrutura da tabela. Se o XML novo referencia campo que ainda não existe na tabela, você cai na Regra 2.

**Por quê:** Construtor de Telas e Dicionário de Dados são responsabilidades separadas, por design. Cada um cuida do seu domínio.

**Fluxo correto para adicionar um campo numa tela existente:**
1. Adicionar o campo na tabela via TDD
2. Atualizar o `metadata.xml`
3. Reimportar pelo Construtor de Telas

---

### Regra 6 — XML quebrado falha import sem mensagem clara

**Contexto:** Import "não funciona" mas o Sankhya não dá um erro óbvio.

**Regra:** Sempre validar o XML com um parser (qualquer um — `xmllint`, validador online, IDE) **antes** de subir.

**Por quê:** Erros de sintaxe XML (tag não fechada, caractere especial não escapado, encoding errado) costumam falhar silenciosamente ou com mensagem genérica tipo "arquivo inválido".

**Comando rápido pra validar:**
```bash
xmllint --noout metadata.xml
# se não imprimir nada, o XML está OK
```

---

## 💬 Exemplos de uso

**Básico:**
- "Como crio uma tela customizada no Sankhya?"
- "Qual a estrutura mínima de um `metadata.xml`?"
- "Para que serve o prefixo `AD_` nas tabelas?"

**Intermediário:**
- "Como adiciono uma validação que verifica se o CNPJ é válido?"
- "Como faço um campo que é lookup pra `TGFPAR`?"
- "Como definir um filtro default na grade da tela?"

**Avançado:**
- "Importei meu XML e a tela não aparece, o que pode ser?"
- "Como atualizo uma tela existente sem perder os registros da tabela?"
- "Por que meu reimport quebrou um campo que estava funcionando?"
- "Qual a diferença entre fazer tela via Construtor de Telas e via HTML5?"

---

## 🧪 Como testar esta skill

Antes de fazer commit de uma mudança:

1. Carregue a skill em uma conversa nova no Claude.ai
2. Rode as 3 perguntas representativas:
   - "Onde eu importo o `metadata.xml` da tela custom?" → deve responder **Configurações → Avançado → Construtor de Telas → Importar** (não Dicionário de Dados)
   - "Importei o XML e a tela não aparece, o que pode ser?" → deve sugerir checar o caminho de import (Regra 1) ANTES de outras hipóteses
   - "Como adiciono um campo numa tela existente?" → deve mencionar criar o campo na tabela PRIMEIRO (Regra 5)
3. Confira se:
   - [ ] Claude carrega `import_path.md` quando a pergunta envolve "como importar" / "onde importar"
   - [ ] Claude **não** confunde com `sankhya-html5` (que é para dashboards/gadgets)
   - [ ] Quando pergunta envolve `AD_*`, `tabelas_ad.md` é puxado
   - [ ] Erro silencioso de import dispara consulta a `gotchas.md`

---

## 📦 Empacotamento

```bash
cd sankhya-construtor-telas/
zip -r ../sankhya-construtor-telas.zip . -x "*.DS_Store" "*.swp"
```

Upload em **Claude.ai → Settings → Capabilities → Skills → Upload skill**.

---

## 📝 Changelog

| Versão | Data | Mudança |
|---|---|---|
| 1.0.0 | 2026-05-19 | Versão inicial. Cobre metadata.xml, tabelas AD_*, seis regras críticas. Caminho de import corrigido (Configurações → Avançado → Construtor de Telas → Importar) |

---

## 🔗 Skills relacionadas

- `sankhya-dicionario` — para criar a tabela `AD_*` antes da tela e descobrir campos de tabelas padrão para lookup
- `sankhya-html5` — quando o que você quer é **dashboard/relatório**, não tela de cadastro (formato e import são diferentes)
- `sankhya-funcionamento` — para entender o fluxo de negócio que a tela vai apoiar
- `sankhya-api-java` — quando a tela precisa disparar uma Ação customizada (ex: botão "Calcular ICMS")

---

## 📄 Licença

MIT — veja [LICENSE](../LICENSE) no root do repositório.
