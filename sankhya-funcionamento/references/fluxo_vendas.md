# Fluxo de Vendas e Faturamento — Sankhya

## Visão geral do ciclo

```
Orçamento → Pedido de Venda → Faturamento (NF) → Entrega → Financeiro (títulos)
   (OP)          (PV)             (NF-e)           (WMS)       (TGFFIN)
```

Todas as etapas são **notas** em TGFCAB — o que muda é a TOP (Tipo de Operação) e o STATUSNOTA.

---

## Etapas detalhadas

### 1. Orçamento / Cotação
- TOP configurada com GERADUP='N' e GERAEST='N' (não gera financeiro nem estoque)
- STATUSNOTA='P' (Pendente) enquanto em elaboração
- Pode ser convertido em Pedido de Venda via "Confirmar"

### 2. Pedido de Venda
- TIPMOV='V', STATUSNOTA='P' ou 'A'
- Quando confirmado: STATUSNOTA='L' (Liberada) → reserva estoque (TGFEST.RESERVADO)
- Pode passar por **regras de aprovação** antes de liberar (fluxo de alçada)
- CONFIRMADA='Sim' indica que o pedido foi confirmado pelo usuário

### 3. Faturamento (emissão da NF)
- Gerado a partir do pedido ou diretamente
- TOP com GERADUP='S' → cria títulos em TGFFIN
- TOP com GERAEST='S' → movimenta estoque em TGFEST (baixa RESERVADO, baixa ESTOQUE)
- STATUSNOTA='L' na nota de saída
- NF-e transmitida para SEFAZ → STATUSNFE='A' (Autorizada)
- NUNOTA é a chave interna; NUMNOTA é o número impresso na NF

### 4. Geração de títulos financeiros
- Para cada condição de pagamento (TGFTNS): cria desdobramentos em TGFFIN
- RECDESP=1 (Receita), PROVISAO='N', BAIXADO depende da baixa
- VLRDESDOB = valor de cada parcela
- Títulos ficam em aberto: DHBAIXA IS NULL

### 5. Entrega / Expedição
- Pode envolver WMS (TGFW*) para separação e conferência
- TGFCAB.RETORNADOAC = status de entrega: E=Entregue, D=Devolvido, N=Não Entregue

---

## Devolução de Venda

```
NF de Devolução (TOP com DEVOLUCAO='S') → Estorna estoque → Gera título de crédito (RECDESP=-1)
```

- TIPMOV='V' com TOP de devolução
- Referencia a nota original via TGFCAB.NUMNOTA/SERIENOTA
- Estoque é creditado de volta em TGFEST

---

## Campos-chave em TGFCAB para acompanhar o ciclo

| Campo | O que indica |
|-------|-------------|
| STATUSNOTA | L=Liberada (confirmada), A=Atendimento, P=Pendente |
| CONFIRMADA | Sim/Não — se o usuário confirmou o pedido |
| TIPMOV | V=Venda, C=Compra, O=Pedido Compra, etc. |
| TIPLIBERACAO | A=Aprovado, P=Pendente, R=Reprovado, S=Sem pendência (alçada) |
| STATUSNFE | A=Autorizada, C=Cancelada, D=Denegada |
| RETORNADOAC | E=Entregue, D=Devolvido, N=Não Entregue, R=Reentregar |
| SITUACAOWMS | Status de separação no WMS |

---

## Query: Pedidos de venda em aberto

```sql
SELECT
    cab.NUNOTA,
    cab.NUMNOTA,
    cab.DTNEG,
    par.NOMEPARC        AS cliente,
    ven.APELIDO         AS vendedor,
    cab.VLRNOTA,
    cab.STATUSNOTA,
    cab.TIPLIBERACAO
FROM TGFCAB cab
JOIN TGFPAR par ON par.CODPARC = cab.CODPARC
JOIN TGFVEN ven ON ven.CODVEND = cab.CODVEND
JOIN TGFTOP top ON top.CODTIPOPER = cab.CODTIPOPER
WHERE cab.TIPMOV     = 'V'
  AND cab.STATUSNOTA = 'A'   -- Em atendimento
  AND top.GERADUP    = 'S'   -- Só pedidos que geram fatura
ORDER BY cab.DTNEG DESC
```

---

## Query: Faturamento do período

```sql
SELECT
    cab.NUMNOTA,
    cab.SERIENOTA,
    cab.DTNEG,
    par.NOMEPARC        AS cliente,
    cab.VLRNOTA,
    cab.STATUSNFE
FROM TGFCAB cab
JOIN TGFPAR par ON par.CODPARC = cab.CODPARC
WHERE cab.TIPMOV      = 'V'
  AND cab.STATUSNOTA  = 'L'
  AND cab.DTNEG BETWEEN DATE '2025-01-01' AND DATE '2025-12-31'
ORDER BY cab.DTNEG DESC
```
