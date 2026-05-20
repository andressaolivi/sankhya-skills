---
name: sankhya-ajuda-online
description: Consulta a documentação oficial do Sankhya (ajuda.sankhya.com.br) em tempo real via web search — para dúvidas sobre funcionalidades, telas, parâmetros do sistema, mensagens de erro e termos do produto. Sempre cita a URL da fonte oficial e nunca inventa quando não encontra.
---

# 🔎 sankhya-ajuda-online

> Skill que transforma o Claude em pesquisador da documentação oficial do Sankhya — usa `web_search` com filtro `site:ajuda.sankhya.com.br` pra responder com base em conteúdo oficial, citando URL. Diferente das outras skills do repo, **não traz conhecimento embarcado**: traz a habilidade de buscar o conhecimento certo.

**Versão:** 1.0.0
**Última atualização:** 2026-05-19
**Autora:** Andressa Olivi — [Olivi Consultoria](https://github.com/andressaolivi)

---

## 🎯 Quando usar esta skill

- Pergunta sobre **como o usuário final usa** uma funcionalidade no Sankhya
- Significado de uma **mensagem de erro/alerta** do sistema
- **"Onde fica a tela X"** no MGE, MGE Web ou Sankhya Om
- Definição/uso de um **parâmetro do sistema** (`STP_*`)
- Termos de produto não-óbvios (ex: "centralizadora", "alçada", "GERADUP", "REGRADESC", "duplicata virtual")
- Confirmar/refutar comportamento documentado oficialmente
- Quando o usuário pede explicitamente: "o que diz a documentação oficial sobre…"
- Palavras-chave: `ajuda`, `manual`, `documentação`, `como faz no Sankhya`, `onde fica`, `oficial`, `STP_`

## 🚫 Quando NÃO usar

- Para **estrutura de tabela/campo** → usar `sankhya-dicionario` (conhecimento embarcado é mais rápido)
- Para **fluxo de negócio interpretativo** (entender por que algo acontece) → usar `sankhya-funcionamento`
- Para **customização Java** → usar `sankhya-api-java`
- Para **dashboards HTML5** → usar `sankhya-html5`
- Para **telas customizadas via metadata.xml** → usar `sankhya-construtor-telas`
- **Quando outra skill já cobre o tema com conhecimento curado** — esta skill é fallback / fonte primária, não substituta

> 💡 **Princípio:** as outras skills têm conhecimento **curado e validado**. Esta tem conhecimento **fresco e oficial**. Quando ambas servem, prefira a curada (mais rápida, mais confiável); use esta pra confirmar, atualizar ou cobrir o que ficou de fora.

---

## 📚 Capacidades

- Buscar conteúdo na documentação oficial via `web_search` (`site:ajuda.sankhya.com.br`)
- Ler páginas específicas via `web_fetch` quando a URL é conhecida
- **Citar a URL da fonte** em toda resposta baseada em conteúdo encontrado
- Confirmar ou refutar afirmações sobre comportamento padrão do Sankhya
- Identificar a versão/módulo a que uma página se refere (quando indicado)
- Reconhecer e declarar quando **não encontrou** nada (em vez de inventar)
- Combinar resultados de múltiplas buscas pra cobrir um tema completo

## 📂 Arquivos de referência

```
sankhya-ajuda-online/
├── SKILL.md                          ← este arquivo
└── references/
    ├── padroes_busca.md              ← Sintaxe site:, operadores, termos canônicos
    ├── terminologia.md               ← Termos do produto + sinônimos (PT-BR)
    ├── paginas_chave.md              ← URLs frequentes da documentação
    ├── gotchas.md                    ← Páginas desatualizadas, links quebrados, ambiguidade entre versões
    └── indice.md                     ← Mapa de navegação
```

| Reference | Carregar quando |
|---|---|
| `padroes_busca.md` | Resultado da primeira busca veio fraco/genérico — refinar |
| `terminologia.md` | Termo da pergunta tem sinônimo formal/informal (ex: usuário diz "TOP" mas doc usa "Tipo de Operação") |
| `paginas_chave.md` | Tema é recorrente — talvez a URL já esteja mapeada |
| `gotchas.md` | Resposta encontrada parece contradizer comportamento real, ou versão da doc é antiga |
| `indice.md` | Para localizar referências sem saber qual é a certa |

---

## 🧭 Workflow típico

1. **Identificar o termo-chave** da pergunta (tela, parâmetro, conceito, mensagem de erro)
2. **Traduzir para a terminologia oficial** se necessário — usuário diz "TOP", doc diz "Tipo de Operação" (ver `terminologia.md`)
3. **Buscar com `web_search`** usando o padrão obrigatório:
   ```
   <termo> site:ajuda.sankhya.com.br
   ```
4. **Avaliar os resultados** — se vieram fracos, refinar query (ver `padroes_busca.md`)
5. **Ler a página relevante** com `web_fetch` (resultado da busca traz só snippet)
6. **Sintetizar a resposta** no idioma da pergunta, com:
   - O conteúdo essencial em poucas linhas
   - A **URL da página oficial** citada explicitamente
   - Indicação de versão/módulo se a página indicar
7. **Se não encontrou** nada relevante, **declarar** que a documentação oficial não cobre (em vez de chutar)

---

## ⚠️ Regras críticas (gotchas)

### Regra 1 — SEMPRE incluir `site:ajuda.sankhya.com.br` na busca

**Contexto:** Toda chamada de `web_search` desta skill.

**Regra:** O filtro `site:ajuda.sankhya.com.br` é obrigatório. Sem ele, a busca traz fórum, blog, artigos de consultoria e conteúdo desatualizado.

**Por quê:** A documentação oficial é a única fonte que esta skill compromete em citar. Resultados de outros sites podem ser corretos, mas **não são o escopo desta skill** — se for usar conteúdo de outro lugar, deixe claro que é fonte secundária.

**Exemplo ruim:**
```
web_search("como configurar TOP no Sankhya")
```
Traz blog post antigo, artigo de consultoria, pergunta em fórum genérico.

**Exemplo bom:**
```
web_search("Tipo de Operação configuração site:ajuda.sankhya.com.br")
```
Traz a página oficial.

---

### Regra 2 — SEMPRE citar a URL da fonte

**Contexto:** Qualquer resposta baseada em conteúdo da documentação oficial.

**Regra:** A URL da página consultada deve aparecer na resposta. Sem URL, vira "Claude disse" — com URL, vira "Sankhya documenta".

**Por quê:** Auditabilidade. O usuário precisa poder validar e linkar pra outros stakeholders.

**Exemplo ruim:**
> A documentação diz que o STP_XXX habilita o uso de centralizadora.

**Exemplo bom:**
> A documentação oficial diz que o `STP_XXX` habilita o uso de centralizadora — ver [ajuda.sankhya.com.br/...](https://ajuda.sankhya.com.br/...).

---

### Regra 3 — Nunca inventar quando não encontrou

**Contexto:** A busca não trouxe resultados relevantes, ou os resultados não tratam exatamente do tema perguntado.

**Regra:** Declarar **explicitamente** que não encontrou. Não preencher o vazio com chute baseado em "deve ser assim".

**Por quê:** Esta skill existe pra trazer confiança de fonte oficial. Resposta inventada com aparência de oficial é o pior cenário possível.

**Exemplo ruim:**
> [busca não trouxe resultado]
> "Provavelmente o parâmetro habilita validação de CNPJ no cadastro."

**Exemplo bom:**
> Não encontrei o `STP_XXX` na documentação oficial. Pode ser um parâmetro de versão recente, deprecado, ou customização local. Posso tentar:
> - Buscar com termo alternativo se você souber o nome funcional (ex: "validação de CNPJ")
> - Consultar `sankhya-dicionario` se for parâmetro de uma tabela específica
> - Você pode verificar diretamente em Configurações → Parâmetros do Sistema no seu ambiente

---

### Regra 4 — Considerar a VERSÃO do Sankhya

**Contexto:** A documentação online pode descrever uma versão diferente daquela em que o usuário está.

**Regra:** Quando a página indica versão (ex: "Disponível a partir da versão 4.X"), citar isso. Quando não indica, mencionar que a versão do cliente pode divergir.

**Por quê:** Sankhya evolui — funcionalidades aparecem, mudam de nome, mudam de caminho. Resposta correta na versão X pode estar errada na versão Y.

---

### Regra 5 — Termos formais vs informais

**Contexto:** Usuário usa nome curto/jargão, doc usa nome formal (ou vice-versa).

**Regra:** Quando a primeira busca falhar, traduzir antes de desistir. Alguns mapeamentos comuns:

| Jargão | Termo oficial provável |
|---|---|
| TOP | Tipo de Operação |
| MGE | Sankhya MGE / Sankhya-W |
| Lateral | Painel lateral / acesso lateral |
| Ação | Ação Java / customização |
| Gadget | Gadget / Dashboard |
| Construtor | Construtor de Telas |
| EFD | SPED Fiscal / EFD ICMS-IPI |
| GERADUP | Geração de duplicatas |

(Ver `terminologia.md` para a lista completa.)

---

### Regra 6 — Resposta deve ser RESUMO, não cópia

**Contexto:** Você leu uma página longa da documentação via `web_fetch`.

**Regra:** Responder com **síntese curta** + URL. Não despejar a página inteira na resposta.

**Por quê:**
- Direitos autorais — conteúdo da documentação é da Sankhya
- Útil — usuário quer a resposta, não o material todo
- Confiável — síntese pequena é mais fácil de auditar contra a fonte

**Tamanho-alvo:** 3-8 linhas de resposta + URL. Se o usuário pedir detalhe, expandir.

---

## 💬 Exemplos de uso

**Básico:**
- "Para que serve o parâmetro STP_XXXX?"
- "Onde fica a tela de cadastro de TOP no Sankhya?"
- "O que significa o erro 'Saldo insuficiente em centralizadora'?"

**Intermediário:**
- "A documentação oficial confirma que o cálculo de custo médio considera devoluções?"
- "Qual a diferença entre 'Filial' e 'Empresa' na documentação do Sankhya?"
- "Como o Sankhya documenta o fluxo de aprovação por alçada?"

**Avançado:**
- "A funcionalidade X mudou entre a versão 4 e a 5? O que diz a doc?"
- "Não acho a tela Y no meu ambiente — é nome diferente em outra versão?"
- "Quero linkar pra documentação oficial num e-mail pro cliente sobre o tema Z — me passa as URLs canônicas"

---

## 🧪 Como testar esta skill

Antes de fazer commit de uma mudança:

1. Carregue a skill em uma conversa nova no Claude.ai
2. Rode as 3 perguntas representativas:
   - "Onde fica a tela de Tipo de Operação no Sankhya?" → deve buscar com `site:ajuda.sankhya.com.br` E citar URL
   - "O que é uma centralizadora no Sankhya?" → deve trazer definição da doc oficial + URL
   - "O parâmetro STP_INEXISTENTE_999 existe?" → deve declarar "não encontrei na documentação oficial" (Regra 3)
3. Confira se:
   - [ ] Toda resposta baseada na doc cita URL
   - [ ] Nenhuma busca foi feita sem `site:ajuda.sankhya.com.br`
   - [ ] Quando a doc cobre tema que `sankhya-funcionamento` também cobre, Claude **escolhe** ou **complementa** (não duplica)
   - [ ] Quando não encontrou nada, declara isso explicitamente

---

## 📦 Empacotamento

```bash
cd sankhya-ajuda-online/
zip -r ../sankhya-ajuda-online.zip . -x "*.DS_Store" "*.swp"
```

Upload em **Claude.ai → Settings → Capabilities → Skills → Upload skill**.

> ⚠️ **Pré-requisito de ambiente:** esta skill depende das ferramentas `web_search` e `web_fetch` estarem **habilitadas** na conversa. Em ambientes Claude sem acesso à web, ela não funciona. Considere documentar isso no onboarding do seu cliente.

---

## 📝 Changelog

| Versão | Data | Mudança |
|---|---|---|
| 1.0.0 | 2026-05-19 | Versão inicial. Padrão `site:ajuda.sankhya.com.br` validado como working access pattern. Seis regras críticas, com ênfase em citar fonte e não inventar |

---

## 🔗 Skills relacionadas

- `sankhya-funcionamento` — tem conhecimento curado de fluxos; esta skill complementa com fonte oficial
- `sankhya-dicionario` — para campos/tabelas (mais rápido que buscar na doc)
- `sankhya-construtor-telas` / `sankhya-html5` / `sankhya-api-java` — pra implementação técnica do que a doc descreve conceitualmente

---

## 📄 Licença

MIT — veja [LICENSE](../LICENSE) no root do repositório.
