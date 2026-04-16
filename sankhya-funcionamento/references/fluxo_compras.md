# Fluxo de Compras — Sankhya

## Visão geral do ciclo

```
Solicitação de Compra → Cotação → Pedido de Compra → NF de Entrada → Financeiro (contas a pagar)
      (SC)               (CO)          (PC)              (NF)            (TGFFIN)
```

---

## Etapas detalhadas

### 1. Solicitação de Compra (SC)
- TIPMOV='Q' (Requisição) na TGFCAB
- Gerada por usuário ou automaticamente por ponto de pedido (estoque mínimo)
- Não movimenta estoque nem financeiro
- Pode ser aprovada por alçada antes de virar cotação

### 2. Cotação / Pedido de Compra
- TIPMOV='O' (Pedido de Compra) em TGFCAB
- TOP com GERADUP='N' e GERAEST='N' (ainda não confirma nada)
- Vinculado ao fornecedor (CODPARC com FORNECEDOR='S')
- Ao confirmar: STATUSNOTA='L' — reserva o pedido junto ao fornecedor

### 3. Recebimento / NF de Entrada
- TIPMOV='C' (Compra) na TGFCAB
- TOP com GERAEST='S' → credita estoque em TGFEST
- TOP com GERADUP='S' → gera títulos de contas a pagar em TGFFIN (RECDESP=-1)
- XML da NF-e do fornecedor pode ser importado automaticamente
- Vinculado ao pedido de compra via referência

### 4. Geração de contas a pagar
- TGFFIN.RECDESP = -1 (Despesa)
- PROVISAO='N', DHBAIXA IS NULL (em aberto)
- VLRDESDOB = valor de cada parcela conforme condição negociada

### 5. Pagamento
- Baixa do título em TGFFIN: DHBAIXA preenchida, VLRBAIXA = valor pago
- Pode gerar lançamento bancário

---

## Devolução de Compra

```
NF de Devolução ao Fornecedor (TOP DEVOLUCAO='S', TIPMOV='C') → Estorna estoque → Crédito financeiro
```

---

## Campos-chave TGFCAB para compras

| TIPMOV | Significado |
|--------|-------------|
| Q | Solicitação / Requisição de compra |
| O | Pedido de Compra |
| C | Nota fiscal de entrada (compra efetiva) |
| K | Pedido de Transferência entre locais |
| L | Devolução de Requisição |

---

## Query: Contas a pagar em aberto

```sql
SELECT
    fin.NUFIN,
    fin.NUMNOTA,
    fin.DTNEG,
    fin.DTVENC,
    par.NOMEPARC        AS fornecedor,
    nat.DESCRNAT        AS natureza,
    fin.VLRDESDOB,
    fin.VLRBAIXA,
    fin.VLRDESDOB - fin.VLRBAIXA AS saldo
FROM TGFFIN fin
JOIN TGFPAR par ON par.CODPARC = fin.CODPARC
JOIN TGFNAT nat ON nat.CODNAT  = fin.CODNAT
WHERE fin.RECDESP  = -1        -- Despesa
  AND fin.PROVISAO = 'N'
  AND fin.DHBAIXA  IS NULL     -- Em aberto
ORDER BY fin.DTVENC ASC
```

---

## Query: Pedidos de compra pendentes de recebimento

```sql
SELECT
    cab.NUNOTA,
    cab.NUMNOTA,
    cab.DTNEG,
    par.NOMEPARC        AS fornecedor,
    SUM(ite.QTDNEG - ite.QTDENTREGUE) AS qtd_pendente,
    cab.VLRNOTA
FROM TGFCAB cab
JOIN TGFPAR par ON par.CODPARC = cab.CODPARC
JOIN TGFITE ite ON ite.NUNOTA  = cab.NUNOTA
WHERE cab.TIPMOV     = 'O'     -- Pedido de compra
  AND cab.STATUSNOTA = 'L'     -- Confirmado
GROUP BY cab.NUNOTA, cab.NUMNOTA, cab.DTNEG, par.NOMEPARC, cab.VLRNOTA
HAVING SUM(ite.QTDNEG - ite.QTDENTREGUE) > 0
ORDER BY cab.DTNEG ASC
```
