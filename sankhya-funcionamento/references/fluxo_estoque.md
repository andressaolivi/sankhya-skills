# Fluxo de Estoque — Sankhya

## Como o estoque funciona

O Sankhya mantém o estoque atual em **TGFEST** (por CODPROD + CODEMP + CODLOCAL + CONTROLE).
Cada movimentação de nota (entrada ou saída) atualiza esses saldos automaticamente quando a TOP tem GERAEST='S' e a nota é confirmada (STATUSNOTA='L').

---

## Movimentações que afetam estoque

| Tipo | TIPMOV | Efeito |
|------|--------|--------|
| Venda (NF saída) | V | Diminui ESTOQUE no local de origem |
| Compra (NF entrada) | C | Aumenta ESTOQUE no local de destino |
| Transferência entre locais | T | Diminui origem, aumenta destino |
| Pedido de venda confirmado | V + STATUSNOTA='L' | Aumenta RESERVADO (não sai do estoque ainda) |
| Devolução de venda | V (TOP devolução) | Aumenta ESTOQUE |
| Devolução de compra | C (TOP devolução) | Diminui ESTOQUE |
| Produção (entrada) | produção | Aumenta ESTOQUE produto acabado |
| Produção (saída de matéria-prima) | produção | Diminui ESTOQUE matéria-prima |

---

## Campos de TGFEST

| Campo | Significado |
|-------|-------------|
| ESTOQUE | Saldo atual físico |
| RESERVADO | Qtd reservada por pedidos confirmados mas não faturados |
| ESTMIN | Estoque mínimo (ponto de pedido) |
| ESTMAX | Estoque máximo |
| Disponível (calculado) | `ESTOQUE - RESERVADO` |

> **Atenção:** TGFEST não tem histórico. Para rastrear movimentações, use TGFITE (itens das notas) com join em TGFCAB.

---

## Controle por lote / série

- Quando o produto usa controle (TGFPRO com configuração de controle ativo), o campo CONTROLE em TGFEST e TGFITE identifica o lote ou número de série
- TGFEST terá um registro por lote/série — saldos separados
- Nas notas (TGFITE), o campo CONTROLE indica de qual lote saiu/entrou

---

## Custo médio

- Sankhya recalcula o custo médio a cada entrada de produto
- Fórmula: `(estoque_atual × custo_atual + qtd_entrada × custo_entrada) / (estoque_atual + qtd_entrada)`
- Campo TGFPRO.CUSTOMED reflete o custo médio atual
- Nas saídas (vendas), o campo TGFITE.VLRCUSMED registra o custo no momento da saída

---

## Inventário / Contagem de estoque

1. Gera contagem via módulo de inventário → cria registros em TGFCTE
2. Usuário digita quantidades físicas
3. Sistema compara com TGFEST e gera NF de ajuste (positivo ou negativo)
4. Após confirmação, TGFEST é atualizado

---

## Transferência entre locais/empresas

```
Local A (CODLOCALORIG) → nota TIPMOV='T' → Local B (CODLOCALDEST)
```
- Uma única nota de transferência
- TOP com GERAEST='S' em ambos os lados
- Pode exigir NF fiscal se for entre empresas diferentes (CODEMP diferente)

---

## Queries úteis

### Posição de estoque atual

```sql
SELECT
    pro.CODPROD,
    pro.DESCRPROD,
    loc.DESCRLOCAL,
    est.CONTROLE,
    est.ESTOQUE,
    est.RESERVADO,
    est.ESTOQUE - est.RESERVADO AS disponivel,
    est.ESTMIN,
    pro.CUSTOMED,
    (est.ESTOQUE * pro.CUSTOMED) AS valor_estoque
FROM TGFEST est
JOIN TGFPRO pro ON pro.CODPROD  = est.CODPROD
JOIN TGFLOC loc ON loc.CODLOCAL = est.CODLOCAL
WHERE est.CODEMP  = 1          -- filtrar empresa
  AND est.ESTOQUE > 0
ORDER BY pro.DESCRPROD
```

### Produtos abaixo do estoque mínimo

```sql
SELECT
    pro.CODPROD,
    pro.DESCRPROD,
    loc.DESCRLOCAL,
    est.ESTOQUE,
    est.ESTMIN,
    est.ESTMIN - est.ESTOQUE AS qtd_repor
FROM TGFEST est
JOIN TGFPRO pro ON pro.CODPROD  = est.CODPROD
JOIN TGFLOC loc ON loc.CODLOCAL = est.CODLOCAL
WHERE est.ESTOQUE < est.ESTMIN
  AND est.ESTMIN  > 0
ORDER BY (est.ESTMIN - est.ESTOQUE) DESC
```

### Histórico de movimentações de um produto

```sql
SELECT
    cab.DTNEG,
    cab.NUMNOTA,
    cab.TIPMOV,
    CASE cab.TIPMOV
        WHEN 'V' THEN 'Saída (Venda)'
        WHEN 'C' THEN 'Entrada (Compra)'
        WHEN 'T' THEN 'Transferência'
        ELSE cab.TIPMOV
    END                     AS tipo,
    par.NOMEPARC,
    ite.QTDNEG,
    ite.VLRUNIT,
    ite.VLRCUSMED
FROM TGFITE ite
JOIN TGFCAB cab ON cab.NUNOTA  = ite.NUNOTA
JOIN TGFPAR par ON par.CODPARC = cab.CODPARC
JOIN TGFTOP top ON top.CODTIPOPER = cab.CODTIPOPER
WHERE ite.CODPROD      = :P_CODPROD
  AND cab.STATUSNOTA   = 'L'
  AND top.GERAEST      = 'S'
ORDER BY cab.DTNEG DESC
```
