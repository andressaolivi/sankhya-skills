# Fluxo Financeiro — Sankhya

## Conceitos fundamentais

### Título (TGFFIN)
Representa uma obrigação financeira: parcela a receber (RECDESP=1) ou a pagar (RECDESP=-1).

- **NUFIN**: chave única do título (não confundir com NUNOTA da nota)
- **NUMNOTA + SERIENOTA**: vínculo com a nota fiscal de origem
- **VLRDESDOB**: valor original da parcela
- **VLRBAIXA**: quanto já foi pago/recebido
- **Saldo em aberto**: `VLRDESDOB - VLRBAIXA`
- **DHBAIXA**: data/hora da baixa. NULL = em aberto

### Provisão vs. Título real
| | Provisão (PROVISAO='S') | Título real (PROVISAO='N') |
|--|------------------------|---------------------------|
| Originem | Previsão de caixa | NF confirmada |
| Baixa caixa? | Não | Sim |
| Aparece no fluxo de caixa? | Depende da config | Sim |

---

## Ciclo de vida de um título

```
Criação (NF confirmada)
    │
    ▼
Em aberto: DHBAIXA IS NULL, VLRBAIXA=0
    │
    ├─→ Baixa total:    DHBAIXA preenchida, VLRBAIXA = VLRDESDOB
    ├─→ Baixa parcial:  DHBAIXA preenchida, VLRBAIXA < VLRDESDOB
    └─→ Renegociação:   título original baixado, novos títulos criados (NUFIN_PAI aponta ao original)
```

---

## Baixa financeira

### Baixa manual
1. Usuário acessa Financeiro → Contas a Receber/Pagar
2. Seleciona título → informa data, valor, conta bancária (TGFCTA), desconto/juros/multa
3. Sistema preenche DHBAIXA, VLRBAIXA, VLRDESC, VLRJURO, VLRMULTA

### Baixa por remessa bancária (CNAB)
1. Gera arquivo CNAB 240/400 para o banco
2. Banco retorna arquivo de retorno
3. Sistema processa retorno e baixa automaticamente os títulos

### Baixa por integração (API)
- Via endpoint REST do Sankhya, possível disparar baixa programaticamente
- Requer autenticação e permissão de baixa financeira

---

## Tipos de título (CODTIPTIT)
Exemplos comuns:

| Código | Descrição |
|--------|-----------|
| BOL | Boleto bancário |
| CHE | Cheque |
| DIN | Dinheiro |
| CC | Cartão de crédito |
| TED | Transferência eletrônica |
| PIX | Pix |
| DEB | Débito automático |

---

## Conciliação bancária
1. Importa extrato bancário (OFX ou digitado)
2. Sistema sugere conciliação: relaciona lançamentos do extrato com baixas em TGFFIN
3. Diferenças viram ajustes manuais ou novos lançamentos de tarifa/IOF

---

## Fluxo de caixa
- Baseia-se em TGFFIN filtrado por DTVENC (previsão) ou DHBAIXA (realizado)
- Inclui ou não provisões conforme configuração
- Agrupa por TGFNAT (natureza) e TGFCTA (conta bancária)

---

## Queries úteis

### Fluxo de caixa previsto (próximos 30 dias)

```sql
SELECT
    fin.DTVENC,
    nat.DESCRNAT,
    SUM(CASE WHEN fin.RECDESP = 1  THEN fin.VLRDESDOB - fin.VLRBAIXA ELSE 0 END) AS receitas,
    SUM(CASE WHEN fin.RECDESP = -1 THEN fin.VLRDESDOB - fin.VLRBAIXA ELSE 0 END) AS despesas
FROM TGFFIN fin
JOIN TGFNAT nat ON nat.CODNAT = fin.CODNAT
WHERE fin.DHBAIXA  IS NULL
  AND fin.PROVISAO = 'N'
  AND fin.DTVENC BETWEEN SYSDATE AND SYSDATE + 30
GROUP BY fin.DTVENC, nat.DESCRNAT
ORDER BY fin.DTVENC, nat.DESCRNAT
```

### Títulos vencidos em aberto

```sql
SELECT
    fin.NUFIN,
    fin.DTVENC,
    TRUNC(SYSDATE) - TRUNC(fin.DTVENC)  AS dias_atraso,
    par.NOMEPARC,
    fin.VLRDESDOB - fin.VLRBAIXA        AS saldo,
    CASE fin.RECDESP WHEN 1 THEN 'Receber' ELSE 'Pagar' END AS tipo
FROM TGFFIN fin
JOIN TGFPAR par ON par.CODPARC = fin.CODPARC
WHERE fin.DHBAIXA  IS NULL
  AND fin.PROVISAO = 'N'
  AND fin.DTVENC   < TRUNC(SYSDATE)
ORDER BY fin.DTVENC ASC
```

### DRE simplificado por natureza (mês)

```sql
SELECT
    nat.TIPNAT,
    nat.DESCRNAT,
    SUM(fin.VLRBAIXA) AS total_realizado
FROM TGFFIN fin
JOIN TGFNAT nat ON nat.CODNAT = fin.CODNAT
WHERE fin.DHBAIXA IS NOT NULL
  AND TRUNC(fin.DHBAIXA, 'MM') = TRUNC(DATE '2025-01-01', 'MM')
GROUP BY nat.TIPNAT, nat.DESCRNAT
ORDER BY nat.TIPNAT DESC, total_realizado DESC
```
