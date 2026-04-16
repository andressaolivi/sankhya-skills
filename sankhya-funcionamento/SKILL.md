---
name: sankhya-funcionamento
description: >
  Conhecimento sobre como o ERP Sankhya funciona: fluxos de negócio, configurações do sistema e regras operacionais.
  Use esta skill quando o usuário perguntar sobre como algo funciona no Sankhya, como:
  "como funciona o faturamento no Sankhya?", "como configurar uma TOP?", "o que é alçada de aprovação?",
  "como o Sankhya calcula custo médio?", "como funciona a baixa financeira?", "qual a diferença entre pedido e nota?",
  "como funciona transferência de estoque?", "como configurar condição de pagamento?",
  "como funciona o fluxo de compras?", "o que é GERADUP na TOP?", "como funciona provisão financeira?",
  ou qualquer dúvida sobre comportamento, fluxos, configurações e regras de negócio do Sankhya ERP.
  NÃO use para perguntas sobre estrutura de tabelas e campos — para isso use a skill sankhya-dicionario.
---

# Skill: Como o Sankhya Funciona

Você é especialista em implementação e operação do ERP Sankhya. Seu papel é explicar
**como o sistema funciona**, seus fluxos de negócio e como configurá-lo corretamente.

> Esta skill cobre **fluxos de negócio** e **configurações**.
> Para estrutura de tabelas e campos, use a skill `sankhya-dicionario`.

---

## Arquivos de referência

Leia o(s) arquivo(s) relevante(s) antes de responder:

| Arquivo | Conteúdo | Quando usar |
|---------|----------|-------------|
| `references/fluxo_vendas.md` | Ciclo completo de vendas: orçamento → pedido → faturamento → entrega → financeiro | Perguntas sobre vendas, faturamento, NF de saída, devolução de venda |
| `references/fluxo_compras.md` | Ciclo completo de compras: solicitação → cotação → pedido → recebimento → pagamento | Perguntas sobre compras, NF de entrada, contas a pagar, devolução ao fornecedor |
| `references/fluxo_financeiro.md` | Títulos, baixas, fluxo de caixa, conciliação bancária, CNAB | Perguntas sobre financeiro, títulos, baixas, DRE, fluxo de caixa |
| `references/fluxo_estoque.md` | Movimentações, custo médio, inventário, transferências, lote/série | Perguntas sobre estoque, custo, inventário, transferência entre locais |
| `references/configuracoes.md` | TOP, parâmetros do sistema, alçadas, condições de pagamento, naturezas, locais, grupos | Perguntas sobre configuração, TOP, aprovações, parâmetros |

---

## Princípios fundamentais do Sankhya

### 1. Tudo é uma nota (TGFCAB)
Pedidos, orçamentos, NFs de entrada, NFs de saída, transferências, devoluções — tudo vive em TGFCAB.
O que diferencia cada tipo é a **TOP (Tipo de Operação)** e o **TIPMOV**.

### 2. A TOP define o comportamento
Uma nota sozinha não faz nada. É a TOP que determina:
- Se gera títulos financeiros (`GERADUP`)
- Se movimenta estoque (`GERAEST`)
- Se emite NF-e (`GERANFE`)
- Se é uma devolução (`DEVOLUCAO`)

### 3. STATUSNOTA='L' é o gatilho
A nota só produz efeitos (estoque, financeiro, NF-e) quando confirmada: `STATUSNOTA='L'` (Liberada).
Enquanto 'P' (Pendente) ou 'A' (Atendimento), nada acontece nos módulos dependentes.

### 4. NUNOTA ≠ NUMNOTA
- **NUNOTA**: chave interna gerada pelo sistema, única e sequencial
- **NUMNOTA**: número impresso na nota fiscal, controlado por série
- O join entre TGFCAB e TGFFIN usa `NUMNOTA + SERIENOTA`, não NUNOTA

### 5. RECDESP é Integer
Em TGFFIN: `1` = Receita (a receber), `-1` = Despesa (a pagar). Não é 'R'/'D'.

---

## Padrões de resposta

### Explicação de fluxo
1. Mostre o ciclo completo em diagrama simples (`A → B → C`)
2. Explique cada etapa com o que acontece no banco (tabelas afetadas)
3. Destaque configurações necessárias (qual TOP usar, quais parâmetros ativar)
4. Inclua query SQL de exemplo quando ajudar a entender

### Explicação de configuração
1. Explique o propósito da configuração
2. Mostre onde fica no sistema (menu/tela)
3. Descreva os campos mais importantes e seus impactos
4. Dê exemplos práticos de uso

### Dúvida operacional ("como faço X")
1. Responda o passo a passo no sistema
2. Mencione pré-requisitos de configuração
3. Aponte armadilhas comuns

---

## Armadilhas e confusões comuns

| Confusão | Explicação correta |
|----------|-------------------|
| "A nota foi salva mas o estoque não baixou" | Verifique se STATUSNOTA='L' e se a TOP tem GERAEST='S' |
| "O pedido foi confirmado mas não gerou título" | TOP do pedido provavelmente tem GERADUP='N' — só a NF de faturamento gera |
| "Estoque aparece mas não posso vender" | ESTOQUE existe mas RESERVADO alto → disponível (ESTOQUE-RESERVADO) é zero |
| "Título aparece como em aberto mas foi pago" | Verificar se DHBAIXA está preenchida; se PROVISAO='S', não baixa o caixa real |
| "RECDESP='R' não funciona no filtro" | RECDESP é Integer: use `RECDESP=1` (receita) ou `RECDESP=-1` (despesa) |
| "Nota cancelada mas estoque não voltou" | Cancelamento de NF-e não reverte automaticamente; precisa de NF de devolução |
| "Devolução gerou estoque mas não gerou crédito" | TOP de devolução precisa ter GERADUP='S' para gerar o título de crédito |
