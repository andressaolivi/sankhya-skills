---
name: nome-da-skill
description: Uma frase objetiva (1 linha, < 200 chars) descrevendo QUANDO Claude deve carregar esta skill. Use verbos de ação e palavras-chave que o usuário provavelmente vai usar. Ex.- "Consulta o dicionário de dados do Sankhya ERP — tabelas, campos, tipos, joins e geração de DDL/SQL."
---

# 📛 nome-da-skill

> Resumo curto (1–2 linhas) em prosa, repetindo o essencial do `description` mas com mais cor. Aparece no topo dos READMEs e na listagem do repositório.

**Versão:** 1.0.0
**Última atualização:** AAAA-MM-DD
**Autora:** Andressa Olivi — [Olivi Consultoria](https://github.com/andressaolivi)

---

## 🎯 Quando usar esta skill

Liste os gatilhos concretos. Claude lê isso para decidir se carrega a skill.

- Pergunta menciona [termo/tabela/módulo X, Y, Z]
- Usuário pede [tipo de artefato — DDL, SQL, configuração, fluxo]
- Contexto envolve [versão, módulo, integração]
- Palavras-chave: `palavra1`, `palavra2`, `palavra3`, ...

## 🚫 Quando NÃO usar

Tão importante quanto o "quando usar". Evita conflito com outras skills.

- NÃO use para [tema que outra skill cobre melhor — referenciar pelo nome]
- NÃO use quando a pergunta é sobre [escopo fora desta skill]
- Para [caso adjacente], use `outra-skill` em vez desta

---

## 📚 Capacidades

O que esta skill permite o Claude fazer, em tópicos:

- Responder sobre [conceito/objeto 1]
- Gerar [tipo de artefato — query, DDL, XML, JSP, etc.]
- Validar [tipo de input do usuário]
- Cruzar dados de [origem A] com [origem B]
- Apontar pitfalls conhecidos de [tema]

## 📂 Arquivos de referência

Estrutura esperada da pasta da skill:

```
nome-da-skill/
├── SKILL.md                    ← este arquivo (índice + regras gerais)
└── references/
    ├── prefixo_tema1.md        ← Descrição curta
    ├── prefixo_tema2.md        ← Descrição curta
    └── indice.md               ← Mapa de navegação entre os references
```

Quando carregar cada reference (Claude lê isto para decidir):

| Reference | Carregar quando |
|---|---|
| `prefixo_tema1.md` | Pergunta menciona [X, Y, Z] |
| `prefixo_tema2.md` | Pergunta menciona [A, B, C] |
| `indice.md` | Sempre que precisar localizar um item sem saber o reference exato |

---

## 🧭 Workflow típico

Passo a passo de como Claude deve operar com esta skill. Numere — agentes seguem ordem melhor que prosa.

1. **Identificar o objeto da pergunta** (tabela? campo? fluxo? configuração?)
2. **Consultar o reference apropriado** (usar a tabela acima)
3. **Se não encontrar:** verificar `references/indice.md` antes de afirmar "não existe"
4. **Validar contra regras conhecidas** (ver seção "Regras críticas" abaixo)
5. **Responder no formato esperado** (ver seção "Formato de resposta")
6. **Se o usuário pedir SQL/DDL/XML:** [convenções específicas]

---

## ⚠️ Regras críticas (gotchas)

Aqui ficam as armadilhas validadas em produção. Toda regra precisa de exemplo concreto.

### Regra 1 — [Nome curto e mnemônico]
**Contexto:** Quando [situação].
**Regra:** [O que fazer / não fazer].
**Por quê:** [Razão técnica].
**Exemplo ruim:**
```sql
-- código que falha
```
**Exemplo bom:**
```sql
-- código correto
```

### Regra 2 — [...]
[mesma estrutura]

> 💡 **Dica:** Toda vez que uma regra deste tipo for descoberta em uma conversa real, adicione aqui com link para o commit/PR onde foi corrigida.

---

## 💬 Exemplos de uso

Perguntas reais que esta skill resolve bem. Misture níveis (iniciante → avançado).

**Básico:**
- "O que é [objeto X]?"
- "Para que serve [conceito Y]?"

**Intermediário:**
- "Como configurar [funcionalidade Z]?"
- "Qual a diferença entre [A] e [B]?"

**Avançado:**
- "Gera [artefato complexo] que faz [requisito 1, 2, 3]"
- "Por que [comportamento inesperado] acontece quando [contexto]?"

---

## 🧪 Como testar esta skill

Antes de fazer commit de uma mudança:

1. Carregue a skill em uma conversa nova no Claude.ai
2. Faça as 3 perguntas representativas listadas acima
3. Confira se:
   - [ ] Claude carrega o(s) reference(s) certo(s)
   - [ ] Respostas seguem as "Regras críticas"
   - [ ] Nenhuma regra de outra skill é invadida
   - [ ] Formato de saída bate com o esperado

---

## 📦 Empacotamento

```bash
# Gerar o .zip / .skill da skill
cd nome-da-skill/
zip -r ../nome-da-skill.zip . -x "*.DS_Store" "*.swp"
```

Subir o `.zip` em **Claude.ai → Settings → Capabilities → Skills → Upload skill**.

---

## 📝 Changelog

| Versão | Data | Mudança |
|---|---|---|
| 1.0.0 | AAAA-MM-DD | Versão inicial |

---

## 🔗 Skills relacionadas

- `outra-skill-1` — quando precisar de [tema adjacente]
- `outra-skill-2` — para [outro tema]

---

## 📄 Licença

MIT — veja [LICENSE](../LICENSE) no root do repositório.
