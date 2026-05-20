# 🧠 sankhya-skills

> O copiloto de IA para quem trabalha com Sankhya. Skills prontas para Claude com dicionário de dados completo, fluxos operacionais, integrações Java e construção de telas/dashboards — para consultores, desenvolvedores e times de TI.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Skills](https://img.shields.io/badge/Claude-Skills-blueviolet)](https://claude.ai)
[![Sankhya ERP](https://img.shields.io/badge/ERP-Sankhya-orange)](https://www.sankhya.com.br)
[![Skills](https://img.shields.io/badge/skills-3%20publicadas%20%2B%203%20em%20dev-green)](#-skills-disponíveis)

---

## ⚡ Como funciona

Cada skill é uma pasta com um `SKILL.md` (índice + regras) e arquivos de referência em `references/`. Quando você sobe o `.zip` no Claude.ai, ele passa a consultar essa base sempre que sua pergunta cair no escopo da skill.

Você pode instalar **uma, várias ou todas** — elas foram desenhadas pra se complementar sem se atropelar.

---

## 📦 Skills disponíveis

### 📚 sankhya-dicionario

Dicionário completo de dados do Sankhya ERP, gerado diretamente das tabelas TDD oficiais do sistema.

- **3.397 tabelas** cobertas
- **45.312 campos** documentados com tipo, tamanho, descrição e valores possíveis
- Busca reversa: dado um campo, encontra em quais tabelas ele aparece
- Geração de DDL Oracle e queries SQL com joins corretos
- Cobertura de todos os módulos: TGF, TSI, TFP, TCB, TIM, TCS, TPR, TRI, TGW, TSE, EFD, Views e mais

**Exemplos de uso:**
```
"O que é TGFCAB?"
"Quais campos tem TGFFIN?"
"Em que tabela fica o estoque atual?"
"Gera um DDL de TGFPRO"
"Qual tabela tem CODPARC?"
"Me explica o campo RECDESP"
```

---

### ⚙️ sankhya-funcionamento

Conhecimento sobre como o Sankhya funciona na prática: fluxos de negócio, regras operacionais e configurações do sistema.

- Fluxo completo de **Vendas**: orçamento → pedido → faturamento → entrega → financeiro
- Fluxo completo de **Compras**: solicitação → cotação → pedido → recebimento → pagamento
- **Financeiro**: títulos, baixas, fluxo de caixa, conciliação bancária, DRE
- **Estoque**: movimentações, custo médio, inventário, transferências, lote/série
- **Configurações**: TOP, parâmetros do sistema, alçadas de aprovação, naturezas, locais, grupos

**Exemplos de uso:**
```
"Como funciona o faturamento no Sankhya?"
"Como configurar uma TOP?"
"O que é GERADUP?"
"Como funciona a baixa financeira?"
"Como o Sankhya calcula custo médio?"
"Como funciona alçada de aprovação?"
```

---

### ☕ sankhya-api-java-community

Desenvolvimento de customizações Java no Sankhya (Módulos Java) — padrões de código, conexão com banco via `JdbcWrapper`, integração com APIs externas e empacotamento.

- Padrões para `Acao`/`Service`/`Servlet` no ambiente Sankhya
- Boas práticas com `JdbcWrapper`, `ResultSet` e múltiplas queries por conexão
- Upload de JARs externos (OkHttp, Okio, etc.) pela tela **Módulos Java**
- Tratamento de erros comuns: `NoClassDefFoundError`, `SQLException: Nome de coluna inválido`
- Geração de planilhas com Apache POI (incluindo o bug do `setCellValue("")` que omite cells)

**Exemplos de uso:**
```
"Como conectar no banco dentro de uma Ação Java?"
"Como subir OkHttp como dependência no Sankhya?"
"Porque dá 'Nome de coluna inválido' depois do update?"
"Como gerar XLSX com cells vazias usando POI no Sankhya?"
```

---

## 🛠️ Em desenvolvimento

Skills funcionais já em uso interno, sendo polidas para release público:

| Skill | Foco | Status |
|---|---|---|
| `sankhya-html5` | Dashboards HTML5/JSP+XML, `snk:query`, EL bindings, parâmetros de prompt | 🟡 Em revisão |
| `sankhya-construtor-telas` | Telas customizadas via `metadata.xml`, import path correto | 🟡 Em revisão |
| `sankhya-ajuda-online` | Consulta a `ajuda.sankhya.com.br` via web search | 🟡 Em revisão |

---

## 🚀 Como instalar

### No Claude.ai

1. Acesse **Settings → Capabilities → Skills**
2. Clique em **Upload skill**
3. Faça upload do arquivo `.zip` da skill desejada
4. A skill estará disponível em todas as suas conversas

### Downloads

| Skill | Download |
|---|---|
| sankhya-dicionario | [⬇️ sankhya-dicionario.zip](https://github.com/andressaolivi/sankhya-skills/raw/main/sankhya-dicionario.zip) |
| sankhya-funcionamento | [⬇️ sankhya-funcionamento.zip](https://github.com/andressaolivi/sankhya-skills/raw/main/sankhya-funcionamento.zip) |
| sankhya-api-java-community | [⬇️ sankhya-api-java-community.zip](https://github.com/andressaolivi/sankhya-skills/raw/main/sankhya-api-java-community.zip) |

---

## 🗂️ Estrutura do repositório

```
sankhya-skills/
├── README.md
├── LICENSE
├── CONTRIBUTING.md                 # como contribuir + padrão de skill
├── docs/
│   └── SKILL_TEMPLATE.md           # esqueleto padrão de toda SKILL.md
│
├── sankhya-dicionario/
│   ├── SKILL.md
│   └── references/
│       ├── tgf_operacional.md      # TGFCAB, TGFITE, TGFPAR, TGFVEN, TGFTOP...
│       ├── tgf_financeiro.md       # TGFFIN, TGFNAT, TGFCTA, TGFCCU...
│       ├── tgf_estoque.md          # TGFPRO, TGFEST, TGFCTE, TGFLOC, TGFGRU...
│       ├── tgf_fiscal.md           # TGFCFO, TGFTRI, TGFNOT, TGFNFE...
│       ├── tgf_efd.md              # 324 tabelas TGFEFD* (SPED)
│       ├── tgf_dim_drc.md          # DIM/SC, DRC, ADR regionais
│       ├── tgf_outros.md           # Demais tabelas TGF
│       ├── tsi.md                  # 200 tabelas TSI (sistema/config)
│       ├── tfp.md                  # 395 tabelas TFP (fiscal complementar)
│       ├── tcb_contabil.md         # 100 tabelas TCB (contabilidade)
│       ├── tim.md                  # TIM (indústria/manufatura)
│       ├── tcs.md                  # TCS (CRM/pré-vendas)
│       ├── tpr.md                  # TPR (produção)
│       ├── tri.md                  # TRI (retail/PDV)
│       ├── tgw.md                  # TGW (WMS)
│       ├── tse.md                  # TSE (serviços/helpdesk)
│       ├── views.md                # Views VGF, VGW, VIM...
│       ├── ad_custom.md            # AD_ customizações (271 tabelas)
│       ├── outros_misc.md          # Demais prefixos
│       └── indice_tabelas.md       # Índice geral TGF + TSI
│
├── sankhya-funcionamento/
│   ├── SKILL.md
│   └── references/
│       ├── fluxo_vendas.md         # Ciclo completo de vendas
│       ├── fluxo_compras.md        # Ciclo completo de compras
│       ├── fluxo_financeiro.md     # Títulos, baixas, fluxo de caixa
│       ├── fluxo_estoque.md        # Movimentações, custo médio, inventário
│       └── configuracoes.md        # TOP, parâmetros, alçadas, naturezas
│
└── sankhya-api-java-community/
    ├── SKILL.md
    └── references/
        ├── conexao_jdbc.md         # JdbcWrapper, ResultSet, transações
        ├── dependencias_externas.md# Upload de JARs via Módulos Java
        ├── erros_comuns.md         # SQLException, NoClassDefFoundError
        └── apache_poi.md           # XLSX, cells vazias, RichTextString
```

---

## 💡 Dicas de uso

As skills se complementam:

| Pergunta | Skill acionada |
|---|---|
| "O que é TGFCAB?" | sankhya-dicionario |
| "Quais campos tem TGFFIN?" | sankhya-dicionario |
| "Como funciona o faturamento?" | sankhya-funcionamento |
| "Como configurar uma TOP?" | sankhya-funcionamento |
| "Gera SQL de contas a receber" | sankhya-dicionario + sankhya-funcionamento |
| "Por que o estoque não baixou?" | sankhya-funcionamento |
| "Como subir OkHttp no Sankhya?" | sankhya-api-java-community |
| "Erro 'Nome de coluna inválido' depois de subir versão" | sankhya-api-java-community |

---

## 🎨 Filosofia das skills

Toda SKILL.md neste repo segue o mesmo padrão — definido em [`docs/SKILL_TEMPLATE.md`](docs/SKILL_TEMPLATE.md). Os princípios:

1. **Quando NÃO usar é tão importante quanto quando usar** — evita conflito entre skills.
2. **References têm gatilhos explícitos** — Claude não adivinha qual ler.
3. **Gotchas documentados com exemplo ruim + exemplo bom** — toda regra crítica precisa de código que falha e código que funciona.
4. **Versionadas em changelog** — quem instala sabe o que mudou.

---

## 🤝 Contribuindo

Contribuições são bem-vindas — veja [`CONTRIBUTING.md`](CONTRIBUTING.md) para o passo-a-passo.

Resumo:
1. Fork o repositório
2. Use [`docs/SKILL_TEMPLATE.md`](docs/SKILL_TEMPLATE.md) como esqueleto
3. Crie uma branch: `git checkout -b feature/nova-skill`
4. Commit: `git commit -m 'Add: skill sankhya-XXX'`
5. Push: `git push origin feature/nova-skill`
6. Abra um Pull Request

---

## 📋 Roadmap

**Próximas (já em desenvolvimento):**
- [ ] `sankhya-html5` — dashboards e telas no HTML5 (JSP + XML gadget, `snk:query`)
- [ ] `sankhya-construtor-telas` — telas customizadas via `metadata.xml`
- [ ] `sankhya-ajuda-online` — consulta direta à documentação oficial

**Backlog:**
- [ ] `sankhya-api-rest` — autenticação JWT e endpoints da API REST
- [ ] `sankhya-fiscal` — obrigações acessórias, SPED, NF-e, Reforma Tributária (CBS/IBS)
- [ ] `sankhya-producao` — ordens de produção, MRP, apontamento
- [ ] `sankhya-rh` — folha de pagamento, ponto eletrônico
- [ ] `sankhya-integracoes` — Mercado Livre Full, Amazon FBA, Magalu, Shopee, marketplaces

---

## 👩‍💻 Autora

Feito por **Andressa Olivi** — [Olivi Consultoria](https://github.com/andressaolivi)

Engenheira de Controle e Automação, 10+ anos em tecnologia e e-commerce. Consultora especialista em transformação digital, integração de ERPs e automação de processos com IA.

---

## 📄 Licença

MIT License — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

⭐ Se este projeto te ajudou, deixa uma estrela no repositório!
