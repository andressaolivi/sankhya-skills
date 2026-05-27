# skill-formulas

> Conhecimento completo sobre fórmulas e o Construtor de Expressões do ERP Sankhya — sintaxe, funções, variáveis por contexto e armadilhas validadas em produção.

**Versão:** 1.0.0
**Última atualização:** 2026-05-27
**Autora:** Andressa Olivi — [Olivi Consultoria](https://github.com/andressaolivi)

---

## 🎯 Quando usar esta skill

- Pergunta menciona Construtor de Expressões, fórmula de custo, fórmula de comissão, fórmula de contabilização
- Usuário pede ajuda para montar, depurar ou explicar uma fórmula no Sankhya
- Menção a funções: PDES, IF, VAL, Round, Trunc, BuscaTSIPAR, VALORIMPOSTOFIN, getVlrPisNota, PRECO
- Menção a variáveis: TOTITENS, VLRICM, INDFRE, INDDES, CUSMEDSEMICM, Formula.VLRDESDOB, CHAMADOR
- Contexto envolve: precificação, comissionamento, contabilização de notas, EDI, formatação de TXT
- Palavras-chave: `fórmula`, `expressão`, `PDES`, `IF aninhado`, `custo/preço`, `contabilização`, `comissão`, `getVlr`, `VALORIMPOSTO`, `BuscaTSIPAR`, `escape de aspas`, `DUAL`

## 🚫 Quando NÃO usar

- NÃO use para perguntas sobre estrutura de tabelas e campos — use `sankhya-dicionario`
- NÃO use para fluxos de negócio e configuração funcional — use `sankhya-funcionamento`
- NÃO use para dashboards HTML5/JSP — use `sankhya-dashboard-html5`
- NÃO use para customização Java — use `sankhya-api-java`
- NÃO use para campos calculados de telas adicionais (expressão `$col_`) — use `sankhya-construtor-telas`

---

## 📚 Capacidades

- Explicar a sintaxe de qualquer função do Construtor de Expressões (IF, PDES, VAL, Round, etc.)
- Listar variáveis disponíveis em cada contexto (Custo, Contabilização, Comissão)
- Montar fórmulas de custo/preço, contabilização e comissão
- Depurar fórmulas com erros (escape de aspas, divisão de inteiros, referência circular de custos)
- Explicar como chamar functions Oracle via PDES+DUAL
- Orientar sobre rateio proporcional, IF aninhado, VALORIMPOSTOFIN/CAB/DIN
- Explicar fórmulas de devolução (CUSTODEV, CUSTOORIGEM)

## 📂 Arquivos de referência

```
sankhya-formulas/
├── SKILL.md                              ← índice + regras gerais
└── references/
    ├── construtor_expressoes.md          ← Interface, acesso, operadores, MGE×Om
    ├── funcoes_referencia.md             ← Catálogo completo de funções
    ├── variaveis_custo.md                ← Variáveis de Custo/Preço + nós BD
    ├── variaveis_contabilizacao.md       ← Variáveis Formula.* + nós BD + histórico
    ├── variaveis_comissao.md             ← Variáveis de Comissão + metas + faixas
    └── gotchas_e_padroes.md              ← 12 armadilhas validadas em produção
```

## 📦 Empacotamento

```bash
cd sankhya-formulas/
zip -r ../sankhya-formulas.zip . -x "*.DS_Store" "*.swp"
```

Subir o `.zip` em **Claude.ai → Settings → Capabilities → Skills → Upload skill**.

---

## 📝 Changelog

| Versão | Data | Mudança |
|--------|------|---------|
| 1.0.0 | 2026-05-27 | Versão inicial — funções, variáveis por contexto (custo/contabilização/comissão), 12 gotchas |

---

## 🔗 Skills relacionadas

- `sankhya-dicionario` — estrutura de tabelas e campos
- `sankhya-funcionamento` — fluxos de negócio e configurações
- `sankhya-construtor-telas` — telas adicionais e campos calculados
- `sankhya-dashboard-html5` — dashboards JSP/HTML5
- `sankhya-api-java` — customização Java

---

## 📄 Licença

MIT — veja [LICENSE](LICENSE) no root do repositório.
