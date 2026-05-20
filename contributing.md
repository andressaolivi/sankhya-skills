# 🤝 Contribuindo com sankhya-skills

Obrigada pelo interesse em contribuir! Este documento define o processo para reportar problemas, propor melhorias e adicionar novas skills.

---

## 📌 Antes de começar

**Escopo do projeto.** Este repositório agrega skills do Claude focadas em **Sankhya ERP** — dicionário de dados, fluxos de negócio, customizações Java, HTML5, Construtor de Telas e documentação oficial. Contribuições devem caber em uma dessas áreas (ou abrir uma área nova bem justificada).

**O que NÃO entra aqui:**
- Skills genéricas de SQL, Java, XML ou Oracle (existem skills melhores no ecossistema pra isso)
- Conhecimento proprietário de clientes — exemplos devem ser anonimizados/generalizados
- Hacks que dependem de bugs do Sankhya não confirmados pelo fabricante

**Tom.** Comentários, issues e PRs em português ou inglês. Seja direto e respeitoso. Críticas vão para o código/conteúdo, não para a pessoa.

---

## 🐛 Reportando bugs ou sugerindo melhorias

Abra uma **issue** com as seguintes informações:

**Para bugs em uma skill existente:**
- Skill afetada (ex: `sankhya-dicionario`, `sankhya-html5`)
- Versão da skill (do changelog do `SKILL.md`)
- Versão do Sankhya em que o problema apareceu
- Pergunta que você fez ao Claude
- Resposta que recebeu
- Resposta que esperava
- Comportamento real validado em produção (se aplicável)

**Para novas regras/gotchas:**
- Contexto onde o problema aparece
- Reprodução mínima (SQL/XML/Java/passos)
- Versão do Sankhya em que foi observado
- Correção aplicada e por que funciona

**Para sugestões de skill nova:**
- Área coberta (ex: "RH/folha", "produção/MRP")
- Por que merece ser uma skill separada (em vez de virar reference de uma existente)
- O que ela responderia que as atuais não respondem

---

## ✨ Adicionando uma skill nova

1. **Fork** o repositório
2. **Crie uma branch**: `git checkout -b feature/sankhya-<area>`
3. **Crie a pasta** `sankhya-<area>/` no root
4. **Copie o template** [`docs/SKILL_TEMPLATE.md`](docs/SKILL_TEMPLATE.md) como `sankhya-<area>/SKILL.md`
5. **Preencha o template** seguindo as convenções abaixo
6. **Crie os arquivos de referência** em `sankhya-<area>/references/`
7. **Gere o `.zip`** (ver seção "Empacotamento")
8. **Atualize o README** principal — seção "Skills disponíveis", tabela de downloads, estrutura do repositório, tabela "Pergunta → Skill acionada"
9. **Commit, push, PR** seguindo o padrão abaixo

### Convenções de naming

- **Pasta da skill**: `sankhya-<area>` em **kebab-case** (ex: `sankhya-html5`, `sankhya-construtor-telas`)
- **Nome no frontmatter**: idêntico ao nome da pasta
- **Arquivos de reference**: `<tema>.md` em **snake_case** (ex: `prompt_parameters.md`, `tipos_campos.md`)
- **Sempre incluir um `indice.md`** quando houver mais de 4 references

### Estrutura mínima

```
sankhya-<area>/
├── SKILL.md
└── references/
    ├── <tema_1>.md
    ├── <tema_2>.md
    └── indice.md       ← obrigatório se houver 5+ references
```

### Convenções de conteúdo

- **Quando NÃO usar** é obrigatório no `SKILL.md` — sem isso, a skill conflita com outras
- **Tabela de "Carregar reference quando…"** é obrigatória — gatilhos explícitos por arquivo
- **Toda regra crítica precisa de** Contexto + Regra + Por quê + Exemplo ruim + Exemplo bom — sem o exemplo, não é regra crítica, é parágrafo solto
- **Changelog na própria SKILL.md** — versão semântica (major.minor.patch), data, descrição da mudança
- **Linkar skills relacionadas no final** — ajuda Claude a saber quando passar a bola pra outra skill

---

## 🔧 Editando uma skill existente

### Quando bumpar versão

Versão semântica: `MAJOR.MINOR.PATCH`

- **PATCH** (1.0.0 → 1.0.1) — correção de erro, ajuste de redação, link quebrado, exemplo melhor
- **MINOR** (1.0.1 → 1.1.0) — nova regra crítica, novo reference, nova capacidade, ampliação de escopo sem quebra
- **MAJOR** (1.1.0 → 2.0.0) — mudança que invalida uso anterior (caminho de import mudou, schema do XML mudou, escopo da skill foi redefinido)

### Atualizando o changelog

Adicione uma linha nova na tabela de changelog do `SKILL.md`:

```markdown
| 1.1.0 | AAAA-MM-DD | Adicionada regra sobre [X]; novo reference `<tema>.md` |
```

Se a mudança corrige uma regra que estava **errada**, marque explicitamente na descrição (transparência > polidez).

---

## 📦 Padrão de commit

Prefixo + escopo + descrição curta no imperativo:

```
Add: skill sankhya-html5
Fix: caminho de import no sankhya-construtor-telas
Update: regra de datas em snk:query (sankhya-html5)
Refactor: extrai gotchas para arquivo dedicado em sankhya-dicionario
Docs: atualiza tabela de downloads no README
```

**Prefixos aceitos:** `Add` (novo), `Fix` (correção), `Update` (mudança evolutiva), `Refactor` (reorganização sem mudança de comportamento), `Docs` (só documentação), `Chore` (manutenção de repo, .gitignore, etc.)

**Mensagens em português ou inglês**, contanto que sejam claras.

---

## 🚀 Padrão de pull request

### Título

Mesma convenção do commit: `Add: skill sankhya-rh`.

### Descrição

```markdown
## O que muda

Resumo em 1-3 linhas do que esta PR faz.

## Por quê

Motivo da mudança. Se é uma regra nova, conte o caso que te levou a descobrir.

## Como testei

- [ ] Carreguei a skill em conversa nova no Claude.ai
- [ ] Rodei as perguntas do checklist de teste do `SKILL.md`
- [ ] Confirmei que `gotchas.md` é carregado nos cenários esperados
- [ ] Nenhuma resposta confundiu com outra skill do repo
- [ ] (Se aplicável) Validei em ambiente Sankhya real, versão X.Y

## Checklist

- [ ] Bumpei a versão no `SKILL.md` (se aplicável)
- [ ] Atualizei o changelog
- [ ] Atualizei o README (se a skill é nova ou se download/estrutura mudou)
- [ ] Gerei o `.zip` atualizado
- [ ] XML/JSON/SQL nos exemplos passam em parser
```

### Tamanho

PRs menores são revisadas mais rápido. Se você está adicionando uma skill grande, considere quebrar:
1. PR 1 — `SKILL.md` + estrutura de pastas
2. PR 2 — references principais
3. PR 3 — references restantes + atualização do README

---

## 🧪 Como testar antes de submeter

1. **Validar XML/markdown/SQL dos exemplos** — copie-cole num parser/validador
2. **Carregar a skill em conversa nova no Claude.ai** — sem outras skills sankhya ativas
3. **Rodar o checklist do `SKILL.md`** — as 3 perguntas representativas devem funcionar
4. **Testar interferência** — ativar TODAS as skills sankhya e fazer perguntas de fronteira (ex: "como faço uma tela?" com `sankhya-html5` E `sankhya-construtor-telas` ativas — deve carregar a certa)
5. **Validar links internos** — `[link](path)` no markdown precisa apontar pra arquivo que existe

---

## 📦 Empacotamento

```bash
cd sankhya-<area>/
zip -r ../sankhya-<area>.zip . -x "*.DS_Store" "*.swp" "*.pyc"
```

O `.zip` fica no **root do repositório**, com o mesmo nome da pasta. A tabela de downloads no README aponta pra ele via `/raw/main/<nome>.zip`.

---

## 🏷️ Após o merge

Quem fizer o merge é responsável por:

1. **Gerar e commitar o `.zip` atualizado** no root (se a skill mudou)
2. **Atualizar a tabela de downloads no README** (se é skill nova)
3. **Atualizar a seção "Em desenvolvimento" ou "Skills disponíveis"** (se uma skill mudou de status)
4. **Criar uma tag** se a mudança merece release: `git tag sankhya-<area>-vX.Y.Z && git push --tags`

---

## ❓ Dúvidas

- Abra uma **discussion** no repositório
- Ou um **issue com label `question`**

Não tenha medo de propor mudanças no próprio processo — este documento também é melhorável.

---

## 📄 Licença

Ao contribuir, você concorda que sua contribuição será licenciada sob a [MIT License](LICENSE) do repositório.
