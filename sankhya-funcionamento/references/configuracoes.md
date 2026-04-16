# Configurações do Sistema — Sankhya

## TOP — Tipo de Operação (TGFTOP)

A TOP é o **coração de configuração** do Sankhya. Ela define o comportamento de cada tipo de nota/pedido. Toda nota em TGFCAB tem um CODTIPOPER que aponta para uma TOP.

### Campos mais importantes da TOP

| Campo | Descrição | Impacto |
|-------|-----------|---------|
| GERADUP | Gera duplicata (título financeiro)? S/N | Controla se a nota cria registros em TGFFIN |
| GERAEST | Gera movimento de estoque? S/N | Controla se atualiza TGFEST |
| DEVOLUCAO | É uma devolução? S/N | Inverte efeitos (crédito de estoque, crédito financeiro) |
| TIPMOV | Tipo de movimento padrão | Define o TIPMOV default das notas com essa TOP |
| GERANFE | Gera NF-e? S/N | Controla transmissão para SEFAZ |
| MOVESTAB | Move estoque ao confirmar ou ao faturar | A=Ao confirmar, F=Ao faturar |

### TOPs típicas em distribuição/varejo

| Nome típico | TIPMOV | GERADUP | GERAEST | Uso |
|-------------|--------|---------|---------|-----|
| Venda Faturada | V | S | S | NF de saída que fatura e baixa estoque |
| Pedido de Venda | V | N | N | Pedido antes do faturamento |
| Compra | C | S | S | NF de entrada de fornecedor |
| Pedido de Compra | O | N | N | Ordem de compra ao fornecedor |
| Devolução de Venda | V | S | S | NF de retorno de mercadoria |
| Transferência | T | N | S | Movimentação entre locais |
| Ajuste Estoque + | T | N | S | Entrada de ajuste de inventário |
| Ajuste Estoque - | T | N | S | Saída de ajuste de inventário |

---

## Parâmetros do Sistema (Preferências)

### Estoque
| Parâmetro | Efeito |
|-----------|--------|
| Bloquear venda sem estoque | Impede confirmar nota quando TGFEST.ESTOQUE < TGFITE.QTDNEG |
| Usar custo médio | Recalcula CUSTOMED a cada entrada |
| Estoque negativo | Permite ou bloqueia saldo negativo em TGFEST |

### Financeiro
| Parâmetro | Efeito |
|-----------|--------|
| Dias de tolerância de vencimento | Dias após vencimento ainda sem multa automática |
| Conta padrão por empresa | TGFCTA default para lançamentos |
| Arredondamento de parcelas | Como tratar centavos nos desdobramentos |

### Numeração de notas
| Parâmetro | Efeito |
|-----------|--------|
| Numeração automática | NUMNOTA gerado pelo sistema vs. digitado manualmente |
| Numeração por série | Contador separado por série de NF |
| Numeração por empresa | Contador separado por CODEMP |

---

## Regras de Aprovação / Alçadas

### Como funciona
1. Configuração define **condições** (ex: VLRNOTA > 10.000) e **aprovadores**
2. Quando nota atende à condição, TGFCAB.TIPLIBERACAO = 'P' (Pendente)
3. Aprovador acessa fila, aprova ou reprova
4. Aprovado: TIPLIBERACAO = 'A' — nota segue o fluxo
5. Reprovado: TIPLIBERACAO = 'R' — nota bloqueada, solicitante notificado

### Campos relacionados
| Campo | Tabela | Significado |
|-------|--------|-------------|
| TIPLIBERACAO | TGFCAB | A=Aprovado, P=Pendente, R=Reprovado, S=Sem pendência |
| LIBPENDENTE | TGFCAB | Indica se há liberação pendente |
| STATUSLIB | TGFFIN | 1=Pendente, 2=Sem solicitação, 3=Autorizado, 4=Não autorizado |

### Casos de uso comuns
- Pedidos acima de valor X exigem aprovação gerencial
- Compras acima de limite exigem aprovação do financeiro
- Descontos acima de Y% exigem aprovação do supervisor

---

## Condições de Pagamento (TGFTNS)

Define como títulos são desdobrados a partir de uma nota.

Exemplo — "30/60/90 dias":
- Parcela 1: 30 dias, 33,33% do valor
- Parcela 2: 60 dias, 33,33%
- Parcela 3: 90 dias, 33,34%

Cada parcela pode ter tipo de título diferente (BOL, CHE, PIX etc.) e conta bancária específica.

---

## Naturezas Financeiras (TGFNAT)

Classifica receitas e despesas — funciona como **plano de contas operacional**.

### Estrutura hierárquica
```
Receita (TIPNAT='R')
  └── Receita de Vendas
        ├── Vendas Produto A
        └── Vendas Produto B
Despesa (TIPNAT='D')
  └── Despesas Operacionais
        ├── Aluguel
        └── Folha de Pagamento
```

- CODNATPAI = natureza pai (hierarquia)
- ANALITICA='S' = recebe lançamentos diretos
- Naturezas sintéticas agrupam para relatórios

---

## Locais de Estoque (TGFLOC)

- Hierárquicos via CODLOCALPAI
- ANALITICO='S' = recebe estoque diretamente
- VALESTINDEP='S' = estoque independente (não consolida)
- Pode ter tabela de preço própria (CODTAB)

---

## Grupos de Produto (TGFGRU)

Hierarquia de classificação de produtos usada para:
- Relatórios por categoria
- Tributação por grupo
- Precificação diferenciada
- Comissões de vendedor por grupo

```
Eletrônicos
  ├── Smartphones
  └── Notebooks
        ├── Gamer
        └── Corporativo
```
