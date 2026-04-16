---
name: sankhya-dicionario
description: >
  Dicionário de dados do ERP Sankhya com cobertura completa de todas as tabelas do sistema.
  Use esta skill sempre que o usuário perguntar sobre tabelas ou campos do Sankhya, como: "o que é TGFCAB?",
  "quais campos tem TGFFIN?", "em que tabela fica o estoque atual?", "como funciona o STATUSNOTA?",
  "qual o join entre notas e financeiro?", "gera DDL de TGFPRO", "me explica RECDESP", "qual tabela tem CODPARC?",
  "quais tabelas do EFD existem?", "me lista tabelas de produção", "o que é TGFEFD?",
  ou qualquer dúvida sobre estrutura, significado ou uso de tabelas e campos do Sankhya ERP.
  Também use para gerar scripts SQL, DDL, queries de exemplo ou explicar relacionamentos entre tabelas.
---

# Skill: Dicionário Sankhya ERP — Completo

Você é especialista no dicionário de dados do Sankhya ERP (banco Oracle/PostgreSQL).

> **Fonte:** Gerado diretamente das tabelas TDD do Sankhya (TDDTAB + TDDCAM + TDDOPC).
> Cobertura: **3.397 tabelas · 45.312 campos**.

---

## Mapa de arquivos de referência

**Passo 1:** Identifique o prefixo da tabela. **Passo 2:** Leia o arquivo correspondente.

### Tabelas TGF (módulo operacional principal)

| Arquivo | Conteúdo | Quando usar |
|---------|----------|-------------|
| `references/tgf_operacional.md` | TGFCAB, TGFITE, TGFPAR, TGFVEN, TGFTOP, TGFTIP, TGFVOL, TGFMOE, TGFREG, TGFZON, TGFROT, TGFCON, TGFCID e similares | Notas, pedidos, parceiros, vendedores, tipos de operação |
| `references/tgf_financeiro.md` | TGFFIN, TGFNAT, TGFLAN, TGFCTA, TGFCCU, TGFCRE, TGFBAN, TGFBAI, TGFDUP, TGFRAT, TGFTNS e similares | Financeiro, títulos, contas, naturezas, centros de custo |
| `references/tgf_estoque.md` | TGFPRO, TGFEST, TGFCTE, TGFLOC, TGFGRU, TGFCAT, TGFUNI, TGFCPR, TGFCUS, TGFPLA, TGFPAT e similares | Produtos, estoque, locais, grupos, custo |
| `references/tgf_fiscal.md` | TGFCFO, TGFTRI, TGFNOT, TGFNFE, TGFNFT, TGFCST, TGFDIR, TGFDIT, TGFGRF, TGFNCM, TGFCOD e similares | Fiscal, NF-e, CFOP, CST, NCM, tributação |
| `references/tgf_efd.md` | TGFEFD* (324 tabelas) | SPED Fiscal, EFD Contribuições, registros EFD |
| `references/tgf_dim_drc.md` | TGFDIM*, TGFDRC*, TGFADR*, TGFLCD* | DIM/SC, DRC, ADR, obrigações acessórias regionais |
| `references/tgf_outros.md` | Demais tabelas TGF não classificadas acima | Qualquer TGF* não coberto pelos arquivos anteriores |

### Outros módulos

| Arquivo | Prefixo | Conteúdo | Quando usar |
|---------|---------|----------|-------------|
| `references/tsi.md` | TSI | Sistema, configurações, segurança, usuários, empresas | TSIUSU, TSICID, TSIORG e todas TSI* |
| `references/tfp.md` | TFP | Módulo fiscal complementar (395 tabelas) | Qualquer TFP* |
| `references/tcb_contabil.md` | TCB | Contabilidade, plano de contas, lançamentos contábeis | Qualquer TCB* |
| `references/tim.md` | TIM | Indústria / manufatura | Qualquer TIM* |
| `references/tcs.md` | TCS | CRM, pré-vendas, comissões | Qualquer TCS* |
| `references/tpr.md` | TPR | Produção, ordens de produção | Qualquer TPR* |
| `references/tri.md` | TRI | Retail / PDV / frente de caixa | Qualquer TRI* |
| `references/tgw.md` | TGW | WMS — gestão de armazém | Qualquer TGW* |
| `references/tse.md` | TSE | Serviços, helpdesk, contratos de serviço | Qualquer TSE* |
| `references/views.md` | VGF, VGW, VIM, VFP, VIE… | Views e consultas do sistema | Qualquer V** |
| `references/ad_custom.md` | AD_ | Customizações e campos adicionais (271 tabelas) | Qualquer AD_* |
| `references/outros_misc.md` | BH_, TAP, TCI, TGM, AUD… | Tabelas diversas de módulos menores | Prefixos não listados acima |
| `references/indice_tabelas.md` | todas | Índice geral com nome + descrição de todas TGF e TSI | Identificar tabela desconhecida ou listar por módulo |

**Regra:** se não souber qual arquivo, consulte `references/indice_tabelas.md` primeiro para localizar a tabela, depois leia o arquivo do módulo correspondente.

---

## Regras de resposta

### Consulta de tabela
- Leia o arquivo de referência correto antes de responder
- Liste os campos com nome, tipo, tamanho, descrição e opções de valor quando existirem
- Destaque a chave primária (campo com menor ORDEM ou sufixo identificador)
- Mencione FKs com base nos sufixos (CODPARC → TGFPAR, CODPROD → TGFPRO, CODEMP → TSIORG etc.)
- Inclua observações práticas de uso

### Busca reversa (campo → tabelas)
- Indique em quais tabelas o campo aparece e em qual módulo
- Explique se há diferença semântica entre tabelas

### Explicação semântica
- Explique o propósito em linguagem clara com exemplos
- Mencione armadilhas quando relevante

### DDL
- Oracle: `NUMBER`, `VARCHAR2`, `DATE`, `CHAR`, `CLOB`
- Inclua `COMMENT ON COLUMN`
- Declare PK e FKs como `CONSTRAINT`

### SQL / queries
- Use aliases curtos e descritivos
- Joins corretos com todas as condições necessárias
- Comentários explicando cada bloco

---

## Armadilhas conhecidas ⚠️

| Situação | ❌ Errado | ✅ Correto |
|----------|-----------|-----------|
| Estoque atual | `SELECT FROM TGFCTE` | `SELECT FROM TGFEST` (campo `ESTOQUE`) |
| Nota confirmada | `STATUSNOTA='A'` | `STATUSNOTA='L'` (Liberada) |
| Título em aberto | sem filtro PROVISAO | `PROVISAO='N'` + `DHBAIXA IS NULL` |
| Número NF impresso | usar NUNOTA | usar `NUMNOTA` (NUNOTA é chave interna) |
| Join nota × financeiro | por NUNOTA | por `NUMNOTA + SERIENOTA` (TGFFIN não tem NUNOTA) |
| RECDESP no TGFFIN | `'R'` ou `'D'` | **Integer**: `1`=Receita, `-1`=Despesa |
| TIPMOV valores | só V/C/T | `V`=Venda, `C`=Compra, `K`=Ped.Transf., `O`=Ped.Compra, `Q`=Requisição, `L`=Dev.Requisição |

---

## Relacionamentos principais

```
TGFCAB (NUNOTA — chave interna)
  ├── TGFITE        via NUNOTA            → itens do pedido
  ├── TGFPAR        via CODPARC           → cliente/fornecedor
  ├── TGFTOP        via CODTIPOPER        → tipo de operação
  ├── TGFVEN        via CODVEND           → vendedor
  ├── TGFNAT        via CODNAT            → natureza
  └── TGFFIN        via NUMNOTA+SERIENOTA → títulos (NÃO por NUNOTA)

TGFFIN (NUFIN)
  ├── TGFNAT        via CODNAT            → natureza financeira
  ├── TGFPAR        via CODPARC           → parceiro
  └── TGFTOP        via CODTIPOPER        → tipo de operação

TGFPRO (CODPROD)
  ├── TGFEST        via CODPROD+CODEMP+CODLOCAL+CONTROLE → estoque atual
  ├── TGFGRU        via CODGRUPOPROD      → grupo
  └── TGFITE        via CODPROD           → itens da nota

TGFPAR (CODPARC)
  └── referenciado em TGFCAB, TGFFIN, TGFITE, TGFEST, TGFCTE
```

---

## Campos com semântica especial

| Campo | Tabela | Tipo | Valores |
|-------|--------|------|---------|
| STATUSNOTA | TGFCAB | String | `L`=Liberada, `A`=Atendimento, `P`=Pendente |
| TIPMOV | TGFCAB | String | `V`=Venda, `C`=Compra, `K`=Ped.Transf., `O`=Ped.Compra, `Q`=Requisição, `L`=Dev.Requisição |
| RECDESP | TGFFIN | Integer | `1`=Receita, `-1`=Despesa |
| PROVISAO | TGFFIN | String | `S`=Provisão, `N`=Normal |
| TIPNAT | TGFNAT | String | `R`=Receita, `D`=Despesa |
| TIPPESSOA | TGFPAR | String | `J`=Jurídica, `F`=Física |
| CONFIRMADA | TGFCAB | String | `Sim` / `Não` |
| TIPO (TGFEST) | TGFEST | String | `P`=Próprio, `T`=Terceiro |
| ATIVO | vários | String | `S`=Sim, `N`=Não |
