# 🧠 sankhya-skills

> O copiloto de IA para quem trabalha com Sankhya. Skills prontas para Claude com dicionário de dados completo, fluxos operacionais e configurações do sistema — para consultores, desenvolvedores e times de TI.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Skills](https://img.shields.io/badge/Claude-Skills-blueviolet)](https://claude.ai)
[![Sankhya ERP](https://img.shields.io/badge/ERP-Sankhya-orange)](https://www.sankhya.com.br)

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

## 🚀 Como instalar

### No Claude.ai
1. Acesse **Settings → Skills**
2. Clique em **Upload skill**
3. Faça upload do arquivo `.skill` desejado
4. A skill estará disponível em todas as suas conversas

### Download das skills
| Skill | Download |
|-------|----------|
| sankhya-dicionario | [sankhya-dicionario.skill](sankhya-dicionario/SKILL.md) |
| sankhya-funcionamento | [sankhya-funcionamento.skill](sankhya-funcionamento/SKILL.md) |

---

## 🗂️ Estrutura do repositório

```
sankhya-skills/
├── README.md
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
└── sankhya-funcionamento/
    ├── SKILL.md
    └── references/
        ├── fluxo_vendas.md         # Ciclo completo de vendas
        ├── fluxo_compras.md        # Ciclo completo de compras
        ├── fluxo_financeiro.md     # Títulos, baixas, fluxo de caixa
        ├── fluxo_estoque.md        # Movimentações, custo médio, inventário
        └── configuracoes.md        # TOP, parâmetros, alçadas, naturezas
```

---

## 💡 Dicas de uso

As duas skills se complementam:

| Pergunta | Skill acionada |
|----------|---------------|
| "O que é TGFCAB?" | sankhya-dicionario |
| "Quais campos tem TGFFIN?" | sankhya-dicionario |
| "Como funciona o faturamento?" | sankhya-funcionamento |
| "Como configurar uma TOP?" | sankhya-funcionamento |
| "Gera SQL de contas a receber" | sankhya-dicionario |
| "Por que o estoque não baixou?" | sankhya-funcionamento |

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você tem conhecimento sobre módulos não cobertos (API REST, HTML5, produção, RH, contabilidade...) abra uma issue ou pull request.

1. Fork o repositório
2. Crie uma branch: `git checkout -b feature/nova-skill`
3. Commit suas mudanças: `git commit -m 'Add: skill sankhya-api'`
4. Push: `git push origin feature/nova-skill`
5. Abra um Pull Request

---

## 📋 Roadmap

- [ ] sankhya-api — autenticação e endpoints da API REST
- [ ] sankhya-html5 — criação de telas e relatórios no HTML5
- [ ] sankhya-fiscal — obrigações acessórias, SPED, NF-e
- [ ] sankhya-producao — ordens de produção, MRP
- [ ] sankhya-rh — folha de pagamento, ponto eletrônico

---

## 👩‍💻 Autora

Feito por **Andressa Olivi** — [Olivi Consultoria](https://github.com/andressaolivi)

Consultora especialista em transformação digital, integração de ERPs e automação de processos com IA.

---

## 📄 Licença

MIT License — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

⭐ Se este projeto te ajudou, deixa uma estrela no repositório!
