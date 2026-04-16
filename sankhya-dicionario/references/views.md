# VGF / VGW / VIM — Views e Consultas

> Gerado do dicionário oficial TDD Sankhya. 83 tabelas.


## VCBEMP — View Empresa Contabilidade
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| UTILCENCUS | String |  | Utiliza Centro de Resultado |  |
| ACEITARHISTZERO | String |  | Aceitar histórico zero ? |  |
| ULTIMONUMEROUSADO | Integer |  | Último Número Usado |  |
| DTFIMPERCTB | DateTime |  | DTFIMPERCTB |  |
| NROLOTEMNUALINI | Integer |  | Início do número do lote manual |  |
| NUMLOTESAUT | String |  | Numeração dos Mestres de Lote | `R`=Empresa/Referência `E`=Empresa `M`=Manual |
| NROLOTEMNUALFIM | Integer |  | Fim do número do lote manual |  |
| MASCCTA | String |  | Máscara da conta |  |
| DTINICPERCTB | DateTime |  | Início do período contábil |  |
| PERALTQDCOM | String |  | Permitir alteração por outras empresas quando compartilhado | `S`=Sim `N`=Não |
| CODCTACTBENCRES | Integer |  | CODCTACTBENCRES |  |
| CODEMPPLACTA | Integer |  | Empresa do plano de contas |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| COREMPRESA | Integer |  | Cor Empresa |  |
| REFERENCIA | Date |  | Referência |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| MASCCTAEXT | String |  | Máscara da conta externa do Vínculo |  |
| CODINSTRESP | String |  | Instituição Resp. Man. Plano Contas Referencial |  |
| UTILPROJ | String |  | Utiliza Projeto |  |

## VCSCOS — VIEW VCSCOS
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRNAT | String |  | Natureza |  |
| CODPARC | Integer |  | Motivo |  |
| ACEITA | String |  | Aceita |  |
| MOTIVO | String |  | MOTIVO |  |
| NUMCONTRATO | Integer |  | Número |  |

## VFPFAI — View Tabela de Faixas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOTAB | String |  | Tipo Tabela |  |
| DESCRTAB | String |  | Descrição |  |
| REFERENCIA | Date |  | Referência |  |
| CODTAB | Integer |  | Cód. Tabela |  |

## VFPFAIX — FP Tabela de Faixas
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTAB | String |  | Descrição da Tabela |  |
| CODTAB | Integer |  | Código da Tabela |  |

## VFPFUN — Funcionários App
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| COD | Integer |  | Código |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| NOMEFUNC | String |  | Nome |  |
| SYNCAPPOS | String |  | Sinc. App | `S`=Sim `N`=Não |

## VFPLIDER — View dos Lideres
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNCLIDER | Integer |  | Código do Funcionário Líder |  |
| NOMEFUNCLIDER | String |  | Nome do Funcionário Líder |  |
| CODEMP | Integer |  | Código da Empresa do Funcionário |  |
| CODFUNC | Integer |  | Código do Funcionário |  |
| NOMEFUNC | String |  | Nome do Funcionário |  |
| CPFFUNC | String |  | CPF do Funcionário |  |
| CPFLIDER | String |  | CPF do Funcionário Líder |  |
| CODIGOPJ | Integer |  | Código do Vinculo a PJ |  |
| CODEMPLIDER | Integer |  | Código da Empresa do Líder |  |

## VFPLIDERIMEDIATO — View de Líderes Imediatos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPLIDER | Integer |  | Código da empresa do líder |  |
| CODUSULIDER | Integer |  | Código do usuário líder |  |
| TIPOREGISTRO | String |  | Tipo de registro |  |
| NOMELIDER | String |  | Nome do líder |  |
| CODIGOLIDER | Integer |  | Código do líder |  |

## VFPLIDERSUBSTITUTO — View de Líderes Substitutos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPLIDER | Integer |  | Código da empresa do líder |  |
| CODUSULIDER | Integer |  | Código do usuário líder |  |
| TIPOREGISTRO | String |  | Tipo de registro |  |
| NOMELIDER | String |  | Nome do líder |  |
| CODIGOLIDER | Integer |  | Código do líder |  |

## VGFADRCSTINCONS — VIEW VGFDRCSTINCONS
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro Único Nota |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| SERIENOTA | String |  | Série da nota |  |
| CODEMP | Integer |  | Empresa |  |
| DTNEG | Date |  | Dt. Neg. |  |
| CODPROD | Integer |  | Código do Produto |  |
| DIVERGENCIA | String |  | Divergência | `1`=Ausência de Seq. Fiscal] `0`=Ausência de Chave |
| TIPMOV | String |  | Tipo de Movimento | `V`=V-Venda `T`=T-Transferência `R`=R-Recebimento `Q`=Q-Requisição `P`=P-Pedido de venda_(+18)_ |

## VGFCAB2 — View Cabeçalho da Nota
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMNOTA | Integer |  | Nro. Nota |  |
| SERIENOTA | String |  | Série |  |
| DTNEG | Date |  | Dt. Negociação |  |
| DTMOV | Date |  | Dt. Movimento |  |
| DTFATUR | Date |  | Dt. Faturamento |  |
| VLRNOTA | Float |  | Vlr. Nota |  |
| COMISSAO | Float |  | % Comissão |  |
| COMGER | Float |  | % Comissão Gerente |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| DHTIPOPER | Date |  | Dt./Hr. Operação |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODTIPVENDA | Integer |  | Tipo Negoc. |  |
| DHTIPVENDA | Date |  | Dt./Hr. Tipo Negoc. |  |
| CODEMP | Integer |  | Empresa |  |
| TIPMOV | String |  | Tipo Mov. | `2`=2-PD Devol. / Procuração / Warrant `O`=O-Pedido de compra `K`=K-Pedido de Transferência `Q`=Q-Requisição `L`=L-Devolução de Requisição_(+3)_ |
| CODVEND | Integer |  | Vend/Comp |  |
| CODGERVEND | Integer |  | Ger. Vend/Comp |  |
| CODVENDPARC | Integer |  | Vend/Comp Parc. |  |
| CODASSESSOR | Integer |  | Assessor Parc. |  |
| CODVENDITE | Integer |  | Vend/Comp Item |  |
| CODGERVENDPARC | Integer |  | Ger. Parc. |  |
| CODEXEC | Integer |  | Executante |  |
| CODGERASSESSOR | Integer |  | Ger. Assessor |  |
| CODVENDLAN | Integer |  | Vend/Comp Lanç. |  |
| CODVENDCR | Integer |  | Vend. CR |  |
| CODGERVENDITE | Integer |  | Ger. Vend/Comp Item |  |
| CODGEREXEC | Integer |  | Ger. Executante |  |
| CODGERVENDLAN | Integer |  | Ger. Vend/Comp Lanç. |  |
| CODGERVENDCR | Integer |  | Ger. Vend/Comp CR |  |
| APELIDOVENDCR | String |  | Apelido Vend. CR |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |
| VLRCOMGER | Float |  | Vlr. Comissão Ger. |  |
| VLRCOMISSAO | Float |  | Vlr. Comissão |  |

## VGFCABBEM — View Despesas dos Bens
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| VLRRATEIO | Float |  | Valor Rateio |  |
| STATUSRATEIO | String |  | Status do Rateio | `P`=Pendente `C`=Concluído |
| NUNOTA | Integer |  | Nro. Único |  |
| DTNEG | Date |  | Dt. Neg. |  |
| VLRNOTA | Float |  | Vlr. Nota |  |
| CODEMP | Integer |  | Empresa |  |
| VLRICMS | Float |  | Vlr. do ICMS |  |
| VLRICMSRATEIO | Float |  | ICMS sobre o frete |  |
| DTENTSAI | Date |  | Dt. Entrada/Saída |  |
| CODBEM | String |  | Código do bem |  |

## VGFCMC7 — VIEW VGFCMC7
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBCO | Integer |  | Código do banco |  |
| PREFIXO | String |  | Prefix |  |
| DESCRICAO | String |  | Descrição |  |

## VGFCOM_FECH — Valores de Comissão p/ Fechamento
Campos: 45

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| APELIDO | String |  | Vendedor |  |
| NUNOTAORIG | Integer |  | Nro Único Nota Orig. |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| DESCRFORM | String |  | Fórmula |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODPARCVEN | Integer |  | Cód. Parceiro Vendedor |  |
| TIPO | String |  | Tip. Comissão | `O`=Outras `S`=Serviço `M`=Múltipla |
| COMLIQ | Float |  | Comissão Parcela |  |
| VLRDESC | Float |  | Vlr Desc. |  |
| NOMEPARC | String |  | Parceiro |  |
| DESCRNAT | String |  | Natureza |  |
| FINNUFIN | Integer |  | Nro. Único Fin. |  |
| TIPCALC | String |  | Tip.Pgt.Comis. | `B`=Baixa `N`=Negociação |
| VLRCOM | Float |  | Comissão Total |  |
| DESDOBRAMENTO | String |  | Desdob. |  |
| VLRDESDOB | Float |  | Vlr. Desdob. |  |
| VLRBAIXA | Float |  | Vlr. Baixa |  |
| DHBAIXA | Date |  | Dt. Baixa |  |
| DTVENC | Date |  | Dt. Venc. |  |
| CODTIPTIT | Integer |  | Cód. Tip. Título |  |
| DHCONCILIACAO | Date |  | Dt. Conciliação |  |
| NOSSONUM | String |  | Nosso Número |  |
| DTNEG | Date |  | Dt. Negoc. |  |
| DTFATUR | Date |  | Dt. Fatur. |  |
| COMISSAO | Float |  | Comissão |  |
| CODTIPVENDA | Integer |  | Cód. Tip. Negoc. |  |
| PERCCOM | Float |  | % Comissão |  |
| NUMOSORIG | Integer |  | Nro. O.S. |  |
| NUMITEMORIG | Integer |  | Nro. Item O.S. |  |
| DESCROPER | String |  | Tipo Operação |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |
| NUFINORIG | Integer |  | Nro. Fin. Orig. |  |
| TIPMOV | String |  | Tip.Movto | `G`=Pagamento `T`=Transferência `O`=Pedido de compra `K`=Pedido de transferência `1`=NF Depósito_(+17)_ |
| TAXA | Float |  | Taxa Cartão |  |
| POSICAO_QUERY | String |  | POSICAO_QUERY |  |
| CODEVENTO | Integer |  | Cód. Evento |  |
| COMLIQC | Float |  | Comissão Parc. Líq. |  |
| TIPINTEGRA | String |  | Tipo de Integração | `F`=Financeiro `P`=Folha Pgto. |
| CODFORM | Integer |  | Cód. Fórmula |  |
| TIPFATSERV | String |  | TIPFATSERV |  |
| DTMOV | Date |  | Dt. Movto. |  |
| INICEXEC | DateTime |  | Dh. Execução |  |
| CODCENCUSPAD | Integer |  | Cód.Centro Resultado Padrão |  |
| CODVEND | Integer |  | Cód. Vendedor |  |

## VGFCOS — VIEW VGFCOS
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód. Parceiro |  |
| ACEITA | String |  | Aceita |  |
| MOTIVO | String |  | Motivo |  |
| CODCONTATO | Integer |  | Cód. Contato |  |
| NOMECONTATO | String |  | Nome |  |

## VGFDEVCOMP — Devoluções de Compra
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| DTNEG | Date |  | Dt. Negociação |  |
| VALOR | Float |  | Valor |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |

## VGFDRCSTINCONS — VIEW VGFDRCSTINCONS
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro Único Nota |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| SERIENOTA | String |  | Série da nota |  |
| CODEMP | Integer |  | Empresa |  |
| TIPMOV | String |  | Tipo de movimento |  |
| DTNEG | Date |  | Dt. Neg. |  |
| MOTIVOCHAVENFE | String |  | Chave NFe Inconsistente? | `S`=Sim `N`=Não |
| MOTIVOSEQFISCAL | String |  | Sequência Fiscal Inconsistente? | `S`=Sim `N`=Não |
| CODPROD | Integer |  | Código do Produto |  |
| QTDINSUFICIENTE | String |  | Qtd. Insuficiente? | `S`=Sim `N`=Não |
| QTDNESC | Float |  | Qtd. Necessária |  |
| QTDGER | Float |  | Qtd. Gerada |  |
| MOTIVOFATCONV | String |  | Fator de Conv. Inconsistente? | `S`=Sim `N`=Não |

## VGFDRCSTPROPDECL — VIEW VGFDRCSTPROPDECL
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro Único Nota |  |
| DTE | Date |  | Dt. de Entrada da Mercadoria |  |
| CODPARC | Integer |  | Parceiro Emitente |  |
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| CODRESPRET | Integer |  | Responsável pela Retenção do ICMS-ST | `3`=3 - Próprio Declarante `2`=2 - Remetente Indireto `1`=1 - Remetente Direto |
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Código do Produto |  |

## VGFFIN — VIEW VGFFIN
Campos: 107

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBCO | Integer |  | Banco |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODEMP | Integer |  | Empresa |  |
| DTVENC | Date |  | Dt. Vencimento |  |
| VLRLIQUIDO | Float |  | Vlr Líquido |  |
| HISTORICO | String |  | Histórico |  |
| VLRJUROEXTRA | Float |  | Vlr Juro extra |  |
| VLRMULTAEXTRA | Float |  | Vlr Multa extra |  |
| VLRISSEXTRA | Float |  | Vlr ISS extra |  |
| OUTROSIMPOSTOSEXTRA | Float |  | Outros impostos extra |  |
| VLRJUROINC | Float |  | Vlr Juro incluso |  |
| VLRMULTAINC | Float |  | Vlr Multa incluso |  |
| VLRISSINC | Float |  | Vlr ISS incluso |  |
| OUTROSIMPOSTOSINC | Float |  | Outros impostos incluso |  |
| NUMNOTA | Integer |  | Nro Nota |  |
| SERIENOTA | String |  | Série da Nota |  |
| DTNEG | Date |  | Dt. Negociação |  |
| DESDOBRAMENTO | String |  | Desdob. |  |
| DHMOV | DateTime |  | Dt/Hr Movimentação |  |
| DTVENCINIC | DateTime |  | Dt. Venc. Inicial |  |
| DHBAIXA | Date |  | Data Baixa |  |
| DTCONTAB | DateTime |  | Dt. Contabilização |  |
| DTCONTABBAIXA | DateTime |  | Dt. Contabilização Baixa |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| DHTIPOPER | DateTime |  | Dt/Hr Operação |  |
| CODCTABCOINT | Integer |  | Conta Bancária |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODPROJ | Integer |  | Projeto |  |
| CODVEND | Integer |  | Vendedor |  |
| CODMOEDA | Integer |  | Moeda |  |
| CODTIPTIT | Integer |  | Tipo de Título |  |
| NUMDUPL | Integer |  | Nro Duplicata |  |
| DESDOBDUPL | String |  | Desdob. Duplicata |  |
| NOSSONUM | String |  | Nosso Número |  |
| VLRDESDOB | Float |  | Vlr Desdob. |  |
| VLRVENDOR | Float |  | Vlr Vendor |  |
| VLRIRF | Float |  | Vlr IRRF |  |
| VLRISS | Float |  | Vlr ISS |  |
| VLRCHEQUE | Float |  | Vlr Cheque |  |
| DESPCART | Float |  | Despesas c/ Cartório |  |
| ISSRETIDO | String |  | ISS Retido | `N`=Não `S`=Sim |
| VLRDESC | Float |  | Vlr Desconto |  |
| VLRMULTA | Float |  | Vlr Multa |  |
| VLRINSS | Float |  | Vlr INSS |  |
| TIPMULTA | String |  | Tipo Multa | `2`=Extra Nota `1`=Incluso |
| VLRJURO | Float |  | Vlr Juros |  |
| TIPJURO | String |  | Tipo Juro | `1`=Incluso `2`=Extra Nota |
| BASEICMS | Float |  | Base ICMS |  |
| ALIQICMS | Float |  | % ICMS |  |
| CODEMPBAIXA | Integer |  | Emp. da Baixa |  |
| CODTIPOPERBAIXA | Integer |  | Cód.Tipo Operação Baixa |  |
| DHTIPOPERBAIXA | DateTime |  | Dt/Hr Tipo Operação |  |
| VLRBAIXA | Float |  | Vlr Baixa |  |
| NUMREMESSA | Integer |  | Nro Remessa |  |
| AUTORIZADO | String |  | Autorizado | `N`=Não `S`=Sim |
| RECDESP | Integer |  | Receita/Despesa | `-1`=Despesa `1`=Receita |
| PROVISAO | String |  | Provisão | `S`=Sim `N`=Não |
| ORIGEM | String |  | Origem | `F`=Financeiro `E`=Estoque `P`=Pessoal |
| TIPMARCCHEQ | String |  | Tipo Marcação Cheque | `H`=Agrupar nominal ao histórico `I`=Sem cheque `K`=Agrupar nominal à empresa `G`=Nominal ao histórico `F`=Agrupar não nominal_(+6)_ |
| NUNOTA | Integer |  | Nro Único Nota |  |
| NUBCO | Integer |  | Nro Único Bancário |  |
| NUDEV | Integer |  | Nro Único Devolução |  |
| NURENEG | Integer |  | Nro Renegociação |  |
| RATEADO | String |  | Rateado | `N`=Não `S`=Sim |
| DTENTSAI | DateTime |  | Dt. Entrada e Saída |  |
| CODUSUBAIXA | Integer |  | Cód. Usuário Baixa |  |
| IDTRANSACAOPIX | String |  | TXID Pix |  |
| CARTA | Integer |  | Nro Carta |  |
| VLRPROV | Float |  | Vlr Provisão Financeira |  |
| INSSRETIDO | String |  | INSS Retido | `N`=Não `S`=Sim |
| IRFRETIDO | String |  | IRRF Retido | `N`=Não `S`=Sim |
| CARTAODESC | Float |  | Taxa Administradora |  |
| DTALTER | DateTime |  | Últ. Alteração |  |
| NUMCONTRATO | Integer |  | Nro Contrato |  |
| ORDEMCARGA | Integer |  | Ordem de Carga |  |
| CODVEICULO | Integer |  | Veículo |  |
| CODBARRA | String |  | Código de Barras |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| VLRVARCAMBIAL | Float |  | Variação Cambial |  |
| CODIGOBARRA | String |  | Cód. Barras Receb. |  |
| LINHADIGITAVEL | String |  | Linha Dig. Receb. |  |
| VLRMULTAEMBUT | Float |  | Vlr Multa Embutida |  |
| VLRJUROEMBUT | Float |  | Vlr Juros Embutidos |  |
| VLRDESCEMBUT | Float |  | Vlr Desc. Embutido |  |
| VLRMOEDA | Float |  | Vlr Moeda |  |
| VLRMOEDABAIXA | Float |  | Vlr Moeda na Baixa |  |
| NUCOMPENS | Integer |  | Nro Compensação/Acerto |  |
| DTBAIXAPREV | DateTime |  | Dt. Prevista p/ Baixa |  |
| CODCFO | Integer |  | CFOP |  |
| VLRMULTANEGOC | Float |  | Vlr Multa Negociada |  |
| VLRJURONEGOC | Float |  | Vlr Juros Negociados |  |
| VLRMULTALIB | Float |  | Vlr Perdão de Multa |  |
| VLRJUROLIB | Float |  | Vlr Perdão de Juros |  |
| NUMOS | Integer |  | Nro da OS |  |
| NATUREZAOPERDES | String |  | Natureza Oper. DES-BH |  |
| SERIENFDES | String |  | Série NF DES-BH |  |
| MODELONFDES | String |  | Modelo NF DES-BH |  |
| NUAPONTA | Integer |  | Nro Único Apontamento |  |
| CODCONTATO | Integer |  | Contato |  |
| DIGSAFRA | String |  | Dig. Safra |  |
| NUMBOR | Integer |  | Nro Borderô |  |
| CODFUNC | Integer |  | Funcionário |  |
| M2 | Float |  | M2 |  |
| MONIOCOREM | String |  | MONIOCOREM | `S`=Sim `N`=Não |
| NUFIN | Integer |  | Nro Único |  |

## VGFFNF — Frete para Nota Financeiro
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Número da Nota |  |
| VLRFRETE | Float |  | Valor do frete |  |
| TIPFRETE | String |  | Tipo do frete | `N`=Extra nota `S`=Incluso |
| CODPARC | Integer |  | Parceiro |  |
| DTNEG | Date |  | Dt. Negociação |  |
| DTVENC | Date |  | Dt. Vencimento |  |
| NUFIN | Integer |  | Número no Financeiro |  |

## VGFFPAGCSGA — Agentes Causadores
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODUSU | Integer |  | Código do Usuário |  |
| DHALTER | DateTime |  | Data de Alteração |  |
| TIPO | String |  | Tipo |  |
| CODIGO | Integer |  | Código |  |

## VGFFREM — VGFFREM
Campos: 112

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VLRMULTAEXTRA | Float |  | VLRMULTAEXTRA |  |
| VLRISSEXTRA | Float |  | VLRISSEXTRA |  |
| OUTROSIMPOSTOSEXTRA | Float |  | OUTROSIMPOSTOSEXTRA |  |
| VLRJUROINC | Float |  | VLRJUROINC |  |
| VLRMULTAINC | Float |  | VLRMULTAINC |  |
| VLRISSINC | Float |  | VLRISSINC |  |
| OUTROSIMPOSTOSINC | Float |  | OUTROSIMPOSTOSINC |  |
| VLRLIQUIDO | Float |  | VLRLIQUIDO |  |
| NUFIN | Integer |  | NUFIN |  |
| CODEMP | Integer |  | CODEMP |  |
| NUMNOTA | Integer |  | NUMNOTA |  |
| SERIENOTA | String |  | SERIENOTA |  |
| DTNEG | DateTime |  | DTNEG |  |
| DESDOBRAMENTO | String |  | DESDOBRAMENTO |  |
| DHMOV | DateTime |  | DHMOV |  |
| DTVENCINIC | DateTime |  | DTVENCINIC |  |
| DTVENC | DateTime |  | DTVENC |  |
| DHBAIXA | DateTime |  | DHBAIXA |  |
| DTCONTAB | DateTime |  | DTCONTAB |  |
| DTCONTABBAIXA | DateTime |  | DTCONTABBAIXA |  |
| CODPARC | Integer |  | CODPARC |  |
| CODTIPOPER | Integer |  | CODTIPOPER |  |
| DHTIPOPER | DateTime |  | DHTIPOPER |  |
| CODBCO | Integer |  | CODBCO |  |
| CODCTABCOINT | Integer |  | CODCTABCOINT |  |
| CODNAT | Integer |  | CODNAT |  |
| CODCENCUS | Integer |  | CODCENCUS |  |
| CODPROJ | Integer |  | CODPROJ |  |
| CODVEND | Integer |  | CODVEND |  |
| CODMOEDA | Integer |  | CODMOEDA |  |
| CODTIPTIT | Integer |  | CODTIPTIT |  |
| NUMDUPL | Integer |  | NUMDUPL |  |
| DESDOBDUPL | String |  | DESDOBDUPL |  |
| NOSSONUM | String |  | NOSSONUM |  |
| HISTORICO | String |  | HISTORICO |  |
| VLRDESDOB | Float |  | VLRDESDOB |  |
| VLRVENDOR | Float |  | VLRVENDOR |  |
| VLRIRF | Float |  | VLRIRF |  |
| VLRISS | Float |  | VLRISS |  |
| VLRCHEQUE | Float |  | VLRCHEQUE |  |
| DESPCART | Float |  | DESPCART |  |
| ISSRETIDO | String |  | ISSRETIDO |  |
| VLRDESC | Float |  | VLRDESC |  |
| VLRMULTA | Float |  | VLRMULTA |  |
| VLRINSS | Float |  | VLRINSS |  |
| TIPMULTA | String |  | TIPMULTA |  |
| VLRJURO | Float |  | VLRJURO |  |
| TIPJURO | String |  | TIPJURO |  |
| BASEICMS | Float |  | BASEICMS |  |
| ALIQICMS | Float |  | ALIQICMS |  |
| CODEMPBAIXA | Integer |  | CODEMPBAIXA |  |
| CODTIPOPERBAIXA | Integer |  | CODTIPOPERBAIXA |  |
| DHTIPOPERBAIXA | DateTime |  | DHTIPOPERBAIXA |  |
| VLRBAIXA | Float |  | VLRBAIXA |  |
| NUMREMESSA | Integer |  | NUMREMESSA |  |
| AUTORIZADO | String |  | AUTORIZADO |  |
| RECDESP | Integer |  | RECDESP |  |
| PROVISAO | String |  | PROVISAO |  |
| ORIGEM | String |  | ORIGEM |  |
| TIPMARCCHEQ | String |  | TIPMARCCHEQ |  |
| NUNOTA | Integer |  | NUNOTA |  |
| IDTRANSACAOPIX | String |  | TXID Pix |  |
| NUBCO | Integer |  | NUBCO |  |
| NUDEV | Integer |  | NUDEV |  |
| NURENEG | Integer |  | NURENEG |  |
| RATEADO | String |  | RATEADO |  |
| DTENTSAI | DateTime |  | DTENTSAI |  |
| CODUSUBAIXA | Integer |  | CODUSUBAIXA |  |
| CARTA | Integer |  | CARTA |  |
| VLRPROV | Float |  | VLRPROV |  |
| INSSRETIDO | String |  | INSSRETIDO |  |
| IRFRETIDO | String |  | IRFRETIDO |  |
| CARTAODESC | Float |  | CARTAODESC |  |
| DTALTER | DateTime |  | DTALTER |  |
| NUMCONTRATO | Integer |  | NUMCONTRATO |  |
| ORDEMCARGA | Integer |  | ORDEMCARGA |  |
| CODVEICULO | Integer |  | CODVEICULO |  |
| CODBARRA | String |  | CODBARRA |  |
| CODUSU | Integer |  | CODUSU |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| VLRVARCAMBIAL | Float |  | VLRVARCAMBIAL |  |
| CODIGOBARRA | String |  | CODIGOBARRA |  |
| LINHADIGITAVEL | String |  | LINHADIGITAVEL |  |
| VLRMULTAEMBUT | Float |  | VLRMULTAEMBUT |  |
| VLRJUROEMBUT | Float |  | VLRJUROEMBUT |  |
| VLRDESCEMBUT | Float |  | VLRDESCEMBUT |  |
| VLRMOEDA | Float |  | VLRMOEDA |  |
| VLRMOEDABAIXA | Float |  | VLRMOEDABAIXA |  |
| NUCOMPENS | Integer |  | NUCOMPENS |  |
| DTBAIXAPREV | DateTime |  | DTBAIXAPREV |  |
| CODCFO | Integer |  | CODCFO |  |
| VLRMULTANEGOC | Float |  | VLRMULTANEGOC |  |
| VLRJURONEGOC | Float |  | VLRJURONEGOC |  |
| VLRMULTALIB | Float |  | VLRMULTALIB |  |
| VLRJUROLIB | Float |  | VLRJUROLIB |  |
| NUMOS | Integer |  | NUMOS |  |
| NATUREZAOPERDES | String |  | NATUREZAOPERDES |  |
| SERIENFDES | String |  | SERIENFDES |  |
| MODELONFDES | String |  | MODELONFDES |  |
| NUAPONTA | Integer |  | NUAPONTA |  |
| CODFUNC | Integer |  | CODFUNC |  |
| CODCONTATO | Integer |  | CODCONTATO |  |
| NUMBOR | Integer |  | NUMBOR |  |
| M2 | Float |  | M2 |  |
| DIGSAFRA | String |  | DIGSAFRA |  |
| OCORRENCIA | String |  | OCORRENCIA |  |
| CAMPO | String |  | CAMPO |  |
| MONIOCOREM | String |  | MONIOCOREM |  |
| ABATIMENTO | Float |  | ABATIMENTO |  |
| ABATIMENTOCAN | Float |  | ABATIMENTOCAN |  |
| VLRJUROEXTRA | Float |  | VLRJUROEXTRA |  |
| TIPO | String |  | TIPO | `L`=Liquidação `A`=Alteração `E`=Entrada |

## VGFGRA — VIEW VGFGRA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPPARC | Integer |  | Perfil |  |
| CODPROD | Integer |  | Produto |  |

## VGFITEPLAN — View Itens Planejamento de Entrega
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| DESCRPROD | String |  | Descrição do Produto |  |
| SEQUENCIA | Float |  | Sequência |  |
| QTDNEG | Integer |  | Quantidade |  |
| QTDPENDENTE | Integer |  | Qtd. Pendente |  |
| NUNOTA | Integer |  | Nro. Único |  |

## VGFLEADTIMECOMPRA — View Lead Time de Compra
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| DESCRPROD | String |  | Descrição Produto |  |
| CODPARCFORN | Integer |  | Fornecedor |  |
| QTDFORN | Integer |  | Qtd. Fornecedores |  |
| MENORPRAZO | Integer |  | Menor tempo de entrega |  |
| PRAZOMEDIO | Integer |  | Tempo médio de entrega |  |
| MAIORPRAZO | Integer |  | Maior tempo de entrega |  |
| LEADTIME_PROD | Integer |  | Lead time registrado |  |
| LEADTIME_EMP | Integer |  | Lead time registrado |  |
| CODEMP | Integer |  | Empresa |  |

## VGFLIBEVE — View Eventos Liberacao
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| EVENTO | Integer |  | Evento |  |

## VGFMARCA — VIEW VGFMARCA
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MARCA | String |  | Marca |  |

## VGFMPX — VIEW VGFMPX
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDTRANSACAO | String |  | ID Transação |  |
| SITCOBRANCA | String |  | Situação Cobrança | `X`=Cancelada `D`=Devolvida `C`=Concluída `A`=Ativa |
| VLRTRANSACAO | Float |  | Vlr. transação |  |
| DTTRANSACAO | DateTime |  | Dt. Transação |  |
| NUFIN | Integer |  | Nro. Único Financeiro |  |
| CODPARC | Integer |  | Parceiro |  |
| STATUSPIX | String |  | Status de Envio | `R`=Enviada `E`=Erro ao Enviar `A`=Pendente |
| CODCTABCOINT | Integer |  | Conta Bancária |  |

## VGFPCP — View Perfil Contato
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| CODTIPPARC | Integer |  | Perfil |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| EMAIL | String |  | E-Mail |  |
| APELIDO | String |  | Apelido |  |
| CARGO | String |  | Cargo |  |
| CODCONTATO | Integer |  | Contato |  |

## VGFPLAC — View Cabeçalho Planejamento Entrega
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPLAN | Integer |  | Nro. Planejamento |  |
| NUNOTADEST | Integer |  | Nro. Único |  |
| NUMNOTADEST | Integer |  | Nro. Nota |  |
| ORDEMCARGA | Integer |  | Ordem de Carga |  |
| CODCONTATO | Integer |  | Contato |  |
| CODPARCFAT | Integer |  | Parceiro |  |
| ENTREGUE | Integer |  | Entregue |  |
| CODPARCTRANSP | Integer |  | Parceiro Transportadora |  |

## VGFPOS — VIEW VGFPOS
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPARC | String |  | Nome |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| NOMECID | String |  | Cidade |  |
| UF | String |  | UF |  |
| TELEFONE | String |  | Telefone |  |
| ACEITA | String |  | Aceita |  |
| MOTIVO | String |  | Motivo |  |
| CGC | String |  | CNPJ / CPF |  |
| INSCESTAD | String |  | Inscrição Estadual |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## VGFPPA — View Perfil Parceiro
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPPARC | Integer |  | Perfil |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| EMAIL | String |  | E-Mail |  |
| CODPARC | Integer |  | Parceiro |  |

## VGFPPC — Planejamento de Produção e Compra
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | String |  | REFERENCIA |  |
| DESCRPROD | String |  | DESCRPROD |  |
| UNIDADE | String |  | UNIDADE |  |
| CODPROD | Integer |  | CODPROD |  |

## VGFPROCTRABCONSOL — Visualização Tributos Disponíveis para Consolidação
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREFPGTO | Date |  | Referência de pagamento |  |
| CODEMP | Integer |  | Código da Empresa |  |
| TPAMBESOCIAL | String |  | Ambiente | `P`=Produção `T`=Teste |
| POSSUIINCLUSAO | Integer |  | Possui Inclusão? | `0`=Não `1`=Sim |
| NRPROCESSO | String |  | Número do processo |  |

## VGFPROS — VIEW VGFPROS
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRPROD | String |  | Produto |  |
| CODPROD | Integer |  | Cód. Produto |  |
| ACEITA | String |  | Aceita |  |
| MOTIVO | String |  | Motivo |  |
| NUMCONTRATO | Integer |  | Contrato |  |

## VGFRASTST — VIEW VGFRASTST
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro Único Nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Código Produto |  |
| CODEMP | Integer |  | Empresa |  |
| TIPMOV | String |  | Tipo de movimento |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| DHTIPOPER | DateTime |  | Data e hora alteração |  |
| DTENTSAI | DateTime |  | Dt. Entrada e Saída |  |
| QTDNEG | Float |  | Quantidade |  |
| CODLOCALORIG | Integer |  | Local origem |  |
| CONTROLE | String |  | Controle |  |
| ATUALLIVFIS | String |  | Atualização de Livro ICMS |  |
| SALDO | Float |  | Saldo |  |

## VGFSELECAO_CURRICULO — view processo de seleção curriculo
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SITSELECAO | Integer |  | Situação | `1`=Fechado `2`=Suspenso `0`=Em Aberto |
| DTINICIO | Date |  | Data início |  |
| DTPREVTERMINO | Date |  | Previsão de término |  |
| CODUSURESPONSAVEL | Integer |  | Cód. Responsável |  |
| NOMEUSU | String |  | Nome Responsável |  |
| NUSELECAO | Integer |  | Número de seleção |  |
| NUCURRICULO | Integer |  | NUCURRICULO |  |
| DESCRSELECAO | String |  | Descrição Seleção |  |

## VGFSELECAO_ETAPA_CANDIDATO — VGFSELECAO_ETAPA_CANDIDATO
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSTAETAPA | Integer |  | Cód. Status Etapa |  |
| DESCRSELECAO | String |  | Descr. Seleção |  |
| CODETAPA | Integer |  | Cód. Etapa Padrão |  |
| DESCRETAPA | String |  | Descr. Etapa |  |
| NUCURRICULO | Integer |  | Nro. Currículo |  |
| NOMECANDIDATO | String |  | Nome Completo |  |
| STATUSETAPA | String |  | Status por Etapa | `P`=Pendente `A`=Aprovado `R`=Reprovado |
| RESULTADO | Float |  | Nota |  |
| CODUSU | Integer |  | Cód. Responsável |  |
| NUEVENTO | Integer |  | Nro. Evento |  |
| DHINICIO | DateTime |  | Dh. Início |  |
| DHFINAL | DateTime |  | Dh. Final |  |
| NUREQUISICAO | Integer |  | Nro. Requisição |  |
| TIPOETAPA | String |  | Tipo Etapa Selecionada | `N`=Padrão `P`=Personalizado |
| NUSELECAO | Integer |  | Cód. Seleção |  |

## VGFSER — View VGFSER
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| CODLOCAL | Integer |  | Cód. Local |  |
| SERIE | String |  | Série do Produto |  |
| SMARTCARD | String |  | SmartCard |  |
| ATUALESTOQUE | Integer |  | Atual Estoque |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## VGFTAB — ViewTabelaPrecos
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OBS | String |  | OBS |  |
| NOMETAB | String |  | NOMETAB |  |
| DECVENDA | Integer |  | DECVENDA |  |
| CODTIPPARC | Integer |  | CODTIPPARC |  |
| CODTABFLEX | Integer |  | CODTABFLEX |  |
| CODREG | Integer |  | CODREG |  |
| CODMOEDA | Integer |  | CODMOEDA |  |
| ATIVO | String |  | ATIVO |  |
| PERCENTUAL | Float |  | PERCENTUAL |  |
| NUTAB | Integer |  | NUTAB |  |
| FORMULA | String |  | FORMULA |  |
| DTVIGOR | DateTime |  | DTVIGOR |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODTABORIG | Integer |  | CODTABORIG |  |
| CODTAB | Integer |  | CODTAB |  |

## VGF_DIRF_BASE_BPFDEC_DOC — View Beneficiário Pessoa Física Dirf por Documento
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CPF | String |  | CPF |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| TIPO | String |  | Tipo Documento | `F`=Financeiro `E`=Estoque |
| NUDOC | Integer |  | Nro. Único Documento |  |
| BASE | Float |  | Base |  |
| VALOR | Float |  | Valor |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| DTREF | Date |  | Referência |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_DIRF_BASE_BPFDEC_IMP — View Beneficiário Pessoa Física Dirf por Documento/Imposto
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CPF | String |  | CPF |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| REGPAI4 | String |  | Registro Pai 4 |  |
| TIPO | String |  | Tipo Documento | `E`=Estoque `F`=Financeiro |
| CODIMP | Integer |  | Código Imposto |  |
| TIPOIMPOSTO | Integer |  | Tipo Imposto | `8`=IRF `7`=COFINS `6`=PIS `9`=CSLL |
| BASE | Float |  | Base |  |
| NUDOC | Integer |  | Nro. Único Documento |  |
| VALOR | Float |  | Valor |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_DIRF_BASE_BPFDEC_ITE — View Beneficiário Pessoa Física Dirf por Documento
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CPF | String |  | CPF |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| REGPAI4 | String |  | Registro Pai 4 |  |
| TIPO | String |  | Tipo Documento | `E`=Estoque `F`=Financeiro |
| BASE | Float |  | Base |  |
| VALOR | Float |  | Valor |  |
| NUDOC | Integer |  | Nro. Único Documento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_DIRF_BASE_BPFDEC_ITE_IMP — View Beneficiário Pessoa Física Dirf por Item e Imposto
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CPF | String |  | CPF |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| REGPAI4 | String |  | Registro Pai 4 |  |
| REGPAI5 | String |  | Registro Pai 5 |  |
| TIPO | String |  | Tipo Documento | `F`=Financeiro `E`=Estoque |
| CODIMP | Integer |  | Código Imposto |  |
| TIPOIMPOSTO | Integer |  | Tipo Imposto | `9`=CSLL `8`=IRF `6`=PIS `7`=COFINS |
| NUDOC | Integer |  | Nro. Único Documento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| BASE | Float |  | Base |  |
| VALOR | Float |  | Valor |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_DIRF_BASE_BPJDEC_DOC — View Beneficiário Pesso Jurídica Dirf por Documento
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CNPJ | String |  | CNPJ |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| TIPO | String |  | Tipo Documento | `E`=Estoque `F`=Financeiro |
| NUDOC | Integer |  | Nro. Único Documento |  |
| BASE | Float |  | Base |  |
| VALOR | Float |  | Valor |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| DTREF | Date |  | Referência |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_DIRF_BASE_BPJDEC_IMP — View Beneficiário Pesso Jurídica Dirf por Documento\Imposto
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CNPJ | String |  | CNPJ |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| REGPAI4 | String |  | Registro Pai 4 |  |
| TIPO | String |  | Tipo Documento | `F`=Financeiro `E`=Estoque |
| CODIMP | Integer |  | Código Imposto |  |
| TIPOIMPOSTO | Integer |  | Tipo Imposto | `6`=PIS `7`=COFINS `8`=IRF `9`=CSLL |
| BASE | Float |  | Base |  |
| NUDOC | Integer |  | Nro. Único Documento |  |
| VALOR | Float |  | Valor |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_DIRF_BASE_BPJDEC_ITE — View Beneficiário Pesso Jurídica Dirf por Documento
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CNPJ | String |  | CNPJ |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| REGPAI4 | String |  | Registro Pai 4 |  |
| TIPO | String |  | Tipo Documento | `E`=Estoque `F`=Financeiro |
| BASE | Float |  | Base |  |
| VALOR | Float |  | Valor |  |
| NUDOC | Integer |  | Nro. Único Documento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_DIRF_BASE_BPJDEC_ITE_IMP — View Beneficiário Pesso Jurídica Dirf por Item e Imposto
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CNPJ | String |  | CNPJ |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| REGPAI3 | String |  | Registro Pai 3 |  |
| REGPAI4 | String |  | Registro Pai 4 |  |
| REGPAI5 | String |  | Registro Pai 5 |  |
| TIPO | String |  | Tipo Documento | `F`=Financeiro `E`=Estoque |
| CODIMP | Integer |  | Código Imposto |  |
| TIPOIMPOSTO | Integer |  | Tipo Imposto | `9`=CSLL `6`=PIS `8`=IRF `7`=COFINS |
| SEQUENCIA | Integer |  | Sequência |  |
| NUDOC | Integer |  | Nro. Único Documento |  |
| BASE | Float |  | Base |  |
| VALOR | Float |  | Valor |  |
| CODEMP | Integer |  | Empresa |  |

## VGF_FOLHA_EDI — VIEW FOLHA EDI
Campos: 50

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO_FUNC | Integer |  | CODIGO_FUNC |  |
| NOME_FUNC | String |  | NOME_FUNC |  |
| MATRICULA_FUNC | Integer |  | MATRICULA_FUNC |  |
| SEXO_FUNC | String |  | SEXO_FUNC |  |
| IDENTIDADE_FUNC | String |  | IDENTIDADE_FUNC |  |
| CPF_FUNC | String |  | CPF_FUNC |  |
| PIS_FUNC | String |  | PIS_FUNC |  |
| ADMISSAO_FUNC | DateTime |  | ADMISSAO_FUNC |  |
| AVISO_PREVIO_FUNC | DateTime |  | AVISO_PREVIO_FUNC |  |
| CODIGO_BANCO_FUNC | Integer |  | CODIGO_BANCO_FUNC |  |
| VINCULO_FUNC | Integer |  | VINCULO_FUNC |  |
| SITUACAO_FUNC | String |  | SITUACAO_FUNC |  |
| CODIGO_DEP_FUNC | Integer |  | CODIGO_DEP_FUNC |  |
| CODIGO_FUNCAO_FUNC | Integer |  | CODIGO_FUNCAO_FUNC |  |
| FUNCAO_FUNC | String |  | FUNCAO_FUNC |  |
| DEPARTAMENTO_FUNC | String |  | DEPARTAMENTO_FUNC |  |
| SALARIO_LIQUIDO | Float |  | SALARIO_LIQUIDO |  |
| DATA_REFERENCIA | DateTime |  | DATA_REFERENCIA |  |
| TIPO_FOLHA | String |  | TIPO_FOLHA |  |
| CONTA_FUNCIONARIO | String |  | CONTA_FUNCIONARIO |  |
| AGENCIA_FUNCIONARIO | String |  | AGENCIA_FUNCIONARIO |  |
| RAZAO_SOCIAL | String |  | RAZAO_SOCIAL |  |
| CGC_EMPRESA | String |  | CGC_EMPRESA |  |
| INSC_ESTADUAL_EMPRESA | String |  | INSC_ESTADUAL_EMPRESA |  |
| ENDERECO_EMPRESA | String |  | ENDERECO_EMPRESA |  |
| TIPO_END_EMPRESA | String |  | TIPO_END_EMPRESA |  |
| NUMERO_END_EMPRESA | String |  | NUMERO_END_EMPRESA |  |
| COMPLEMENTO_END_EMPRESA | String |  | COMPLEMENTO_END_EMPRESA |  |
| BAIRRO_EMPRESA | String |  | BAIRRO_EMPRESA |  |
| CIDADE_EMPRESA | String |  | CIDADE_EMPRESA |  |
| UF_EMPRESA | String |  | UF_EMPRESA |  |
| CEP_EMPRESA | String |  | CEP_EMPRESA |  |
| COD_ENDERECO_FUNC | Integer |  | COD_ENDERECO_FUNC |  |
| ENDERECO_FUNC | String |  | ENDERECO_FUNC |  |
| TIPO_ENDERECO_FUNC | String |  | TIPO_ENDERECO_FUNC |  |
| NUMERO_END_FUNC | String |  | NUMERO_END_FUNC |  |
| COMPLEMENTO_END_FUNC | String |  | COMPLEMENTO_END_FUNC |  |
| BAIRRO_FUNC | String |  | BAIRRO_FUNC |  |
| CIDADE_FUNC | String |  | CIDADE_FUNC |  |
| UF_FUNC | String |  | UF_FUNC |  |
| CEP_FUNC | String |  | CEP_FUNC |  |
| CONVENIO | Float |  | CONVENIO |  |
| TIPO_CONTA_FUNC | String |  | TIPO_CONTA_FUNC |  |
| DIGITO_AGENCIA_FUNC | String |  | DIGITO_AGENCIA_FUNC |  |
| DIGITO_CONTA_FUNC | String |  | DIGITO_CONTA_FUNC |  |
| TAMANHO_CGC_CPF | Integer |  | TAMANHO_CGC_CPF |  |
| DATAPAGAMENTO | DateTime |  | DATAPAGAMENTO |  |
| NUFIN | Integer |  | Numero Financeiro |  |
| SEQUENCIA_FOLHA | Integer |  | SEQUENCIA_FOLHA |  |
| CODIGO_EMPRESA | Integer |  | CODIGO_EMPRESA |  |

## VGMLPO — Linha planej. orçament
Campos: 54

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REALIZADO5 | Float |  | Realizado 5 |  |
| REALIZADO6 | Float |  | Realizado 6 |  |
| REALIZADO7 | Float |  | Realizado 7 |  |
| REALIZADO8 | Float |  | Realizado 8 |  |
| REALIZADO9 | Float |  | Realizado 9 |  |
| PREVISTO1 | Float |  | Previsto 1 |  |
| PREVISTO10 | Float |  | Previsto 10 |  |
| PREVISTO11 | Float |  | Previsto 11 |  |
| PREVISTO12 | Float |  | Previsto 12 |  |
| PREVISTO2 | Float |  | Previsto 2 |  |
| PREVISTO3 | Float |  | Previsto 3 |  |
| PREVISTO4 | Float |  | Previsto 4 |  |
| PREVISTO5 | Float |  | Previsto 5 |  |
| PREVISTO6 | Float |  | Previsto 6 |  |
| PREVISTO7 | Float |  | Previsto 7 |  |
| PREVISTO8 | Float |  | Previsto 8 |  |
| PREVISTO9 | Float |  | Previsto 9 |  |
| PREVISTOOFICIAL1 | Float |  | P. Oficial 1 |  |
| PREVISTOOFICIAL10 | Float |  | P. Oficial 10 |  |
| PREVISTOOFICIAL11 | Float |  | P. Oficial 11 |  |
| PREVISTOOFICIAL12 | Float |  | P. Oficial 12 |  |
| PREVISTOOFICIAL2 | Float |  | P. Oficial 2 |  |
| PREVISTOOFICIAL3 | Float |  | P. Oficial 3 |  |
| PREVISTOOFICIAL4 | Float |  | P. Oficial 4 |  |
| PREVISTOOFICIAL5 | Float |  | P. Oficial 5 |  |
| PREVISTOOFICIAL6 | Float |  | P. Oficial 6 |  |
| PREVISTOOFICIAL7 | Float |  | P. Oficial 7 |  |
| PREVISTOOFICIAL8 | Float |  | P. Oficial 8 |  |
| PREVISTOOFICIAL9 | Float |  | P. Oficial 9 |  |
| REALIZADO1 | Float |  | Realizado 1 |  |
| REALIZADO10 | Float |  | Realizado 10 |  |
| REALIZADO11 | Float |  | Realizado 11 |  |
| REALIZADO12 | Float |  | Realizado 12 |  |
| REALIZADO2 | Float |  | Realizado 2 |  |
| REALIZADO3 | Float |  | Realizado 3 |  |
| REALIZADO4 | Float |  | Realizado 4 |  |
| CODMETA | Integer |  | Cód. Meta |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODREG | Integer |  | Cód. Região |  |
| CODPROD | Integer |  | Produto |  |
| CODVEND | Integer |  | Vendedor |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODUF | Integer |  | Cód. UF |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODPAIS | Integer |  | Cód. País |  |
| CODTIPPARC | Integer |  | Perfil |  |
| CODGER | Integer |  | Gerente de Vendedor |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CODGRUPOPROD | Integer |  | Grupo Produto |  |
| CODEMP | Integer |  | Empresa |  |
| MARCA | String |  | Marca |  |
| CODLOCAL | Integer |  | Local |  |
| CODGRUPONAT | Integer |  | Cód. Grupo Nat. |  |

## VGMMET — View Metas Simplificadas
Campos: 39

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| JAN_PERC | Float |  | % |  |
| REFERENCIA | String |  | Referência |  |
| JAN_VLR | Float |  | Vlr. |  |
| JAN_QTD | Float |  | Qtd. |  |
| FEV_VLR | Float |  | Vlr. |  |
| FEV_PERC | Float |  | % |  |
| FEV_QTD | Float |  | Qtd. |  |
| MAR_PERC | Float |  | % |  |
| MAR_VLR | Float |  | Vlr. |  |
| MAR_QTD | Float |  | Qtd. |  |
| ABR_PERC | Float |  | % |  |
| ABR_VLR | Float |  | Vlr. |  |
| ABR_QTD | Float |  | Qtd. |  |
| MAI_PERC | Float |  | % |  |
| MAI_VLR | Float |  | Vlr. |  |
| MAI_QTD | Float |  | Qtd. |  |
| JUN_PERC | Float |  | % |  |
| JUN_VLR | Float |  | Vlr. |  |
| JUN_QTD | Float |  | Qtd. |  |
| JUL_PERC | Float |  | % |  |
| JUL_VLR | Float |  | Vlr. |  |
| JUL_QTD | Float |  | Qtd. |  |
| AGO_PERC | Float |  | % |  |
| AGO_VLR | Float |  | Vlr. |  |
| AGO_QTD | Float |  | Qtd. |  |
| SET_PERC | Float |  | % |  |
| SET_VLR | Float |  | Vlr. |  |
| SET_QTD | Float |  | Qtd. |  |
| OUT_PERC | Float |  | % |  |
| OUT_VLR | Float |  | Vlr. |  |
| OUT_QTD | Float |  | Qtd. |  |
| NOV_PERC | Float |  | % |  |
| NOV_VLR | Float |  | Vlr. |  |
| NOV_QTD | Float |  | Qtd. |  |
| DEZ_PERC | Float |  | % |  |
| DEZ_VLR | Float |  | Vlr. |  |
| DEZ_QTD | Float |  | Qtd. |  |
| CODIGO | Integer |  | Código |  |

## VGPESQCC — VIEW VGPESQCC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPARC | String |  | Parceiro |  |
| NOMEMPREE | String |  | Empreendimento |  |
| DESCRPROD | String |  | Unidade |  |
| CODCC | Integer |  | Contrato |  |

## VGUNIDADESCC — View Unidades Civil
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DESCRPROD | String |  | DESCRPROD |  |
| CODPROD | Integer |  | CODPROD |  |

## VGWENTMAPA — View Entrega Mapa
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Código |  |

## VGWEST — View Estoque por Endereço WMS
Campos: 51

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEND | Integer |  | End. Reduzido |  |
| ENDERECO | String |  | Endereço |  |
| DESCREND | String |  | Desc. Endereço |  |
| CODPROD | Integer |  | Cód. Produto |  |
| DESCRPROD | String |  | Desc. Produto |  |
| ESTOQUEVOLPAD | Float |  | Est. Atual Un. Padrão |  |
| CONTROLE | String |  | Controle |  |
| DTVAL | Date |  | Dt. Validade |  |
| CODVOLPAD | String |  | Un. Padrão |  |
| IDPALETE | Integer |  | ID Palete |  |
| PICKING | String |  | Picking | `N`=Não `S`=Sim |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| BLOQUEADO | String |  | Bloqueado | `S`=Sim `N`=Não |
| EXCLCONF | String |  | Exclusivo p/ Conferência | `N`=Não `S`=Sim |
| EHDOCA | String |  | Doca | `N`=Não `S`=Sim |
| EXPEDICAO | String |  | Expedição | `N`=Não `S`=Sim |
| MULTIPROD | String |  | Multi-Produto | `N`=Não `S`=Sim |
| ENTRADASPEND | Float |  | A receber |  |
| SAIDASPEND | Float |  | A entregar |  |
| ESTOQUE | Float |  | Est. Atual |  |
| ESTDISP | Float |  | Est. Disponível |  |
| ENTRPENDVOLPAD | Float |  | A receber Un. Padrão |  |
| SAIDPENDVOLPAD | Float |  | A entregar Un. Padrão |  |
| ESTDISPVOLPAD | Float |  | Est. Disp. Un. Padrão |  |
| MARCA | String |  | Marca |  |
| COMPLDESC | String |  | Complemento |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| NOMEPARC | String |  | Nome do Parceiro |  |
| OBSERVACAO | String |  | Observação |  |
| DTVALMINEXP | Date |  | Dt. Val. Mín. Expedição |  |
| CODGRUPOPROD | Integer |  | Cód. Grupo |  |
| DESCRGRUPOPROD | String |  | Descrição do Grupo |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| NOMEFANTASIA | String |  | Nome Empresa |  |
| PROFUNDIDADE | Float |  | Profundidade |  |
| M3MAX | Float |  | M³ Máximo |  |
| NIVEL | Integer |  | Nível |  |
| LARGURA | Float |  | Largura |  |
| ALTURA | Float |  | Altura |  |
| PESOMAX | Float |  | Peso Máximo |  |
| REFERENCIA | String |  | Referência |  |
| REFFORN | String |  | Ref. Fornecedor |  |
| CODLOCAL | Integer |  | Cód. Local |  |
| DESCRLOCAL | String |  | Desc. Local |  |
| ENDMOVVERTICAL | String |  | End. Mov. Vertical | `S`=Sim `N`=Não |
| LOCALIZACAO | String |  | Localização |  |
| CODVOL | String |  | Un. Estoque |  |
| CODENDPAI | Integer |  | Cód. End. Pai |  |
| DTREC | DateTime |  | Dt. Recebimento |  |
| CODAREASEP | Integer |  | Cód. Área Sep. |  |
| NOMEAREASEP | String |  | Nome Área Sep. |  |

## VGWESTOCO — View Estoque Endereço Ocorrência
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEND | Integer |  | Cód. Endereço |  |
| ENDERECO | String |  | Endereço |  |
| DESCREND | String |  | Descr. Endereço |  |
| CODPROD | Integer |  | Cód. Produto |  |
| CONTROLE | String |  | Controle |  |
| CODLOCAL | Integer |  | Cód.Local |  |
| DESCRLOCAL | String |  | Descr. Local |  |
| REFERENCIA | String |  | Referência |  |
| DESCRPROD | String |  | Descr. Produto |  |
| COMPLDESC | String |  | Complemento |  |
| ESTOQUE | Integer |  | Estoque Atual |  |
| ENTRADASPEND | Integer |  | Entradas Pendentes |  |
| SAIDASPEND | Integer |  | Saídas Pendentes |  |
| CODVOL | String |  | Unidade |  |
| CODVOLEST | String |  | Volume Estoque |  |
| ESTOQUEVOLEST | Integer |  | Estoque Vol.Estoque |  |
| ESTOQUEDISP | Integer |  | Estoque Disponível |  |
| QTDEPERDA | Float |  | Qtd Envio p/Perda |  |
| TIPOEND | String |  | TIPOEND |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## VGWLOC — View Liberação Ordem Carga
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDTOTNAOLIB | Integer |  | Qtd. Sep não liberadas |  |
| QTDTOTPEDIDO | Integer |  | Qtd. Pedidos |  |
| PESOBRUTOTOTAL | Float |  | Peso total |  |
| QTDTOTSEPARACAO | Integer |  | Qtd. Separação |  |
| SEPINICIADA | String |  | Separação iniciada |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| DTINIC | DateTime |  | Dt. Inicio |  |
| ORDEMCARGA | Integer |  | Ordem Carga |  |
| NROFROTA | Integer |  | Nro. Frota |  |
| CODREG | Integer |  | Cód. Região |  |
| CODROTA | Integer |  | Cód. Rota |  |
| CODDOCA | Integer |  | Cód. Doca |  |
| STATUSLOC | String |  | Status | `P`=Parcialmente liberadas `N`=Não Liberadas `L`=Totalmente liberadas |
| QTDTOTLIB | Integer |  | Qtd. Sep liberadas |  |

## VGWREC — Recebimento
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTRECEBIMENTO | Date |  | Dt. Recebimento |  |
| CODDOCA | Integer |  | Cód. Doca |  |
| CODENDDOCA | Integer |  | Cód. End. Doca |  |
| DESCRICAO | String |  | Descrição |  |
| ENDERECO | String |  | Endereço |  |
| SITUACAO | Integer |  | Situação | `23`=Aguardando recontagem `6`=Concluído `2`=Conferência com divergência `50`=Armazenado parcial `30`=Parcialmente conferido_(+6)_ |
| CODPARC | Integer |  | Cód. Parceiro |  |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |
| CODUSUCONF | Integer |  | Cód. Usuário Conferente |  |
| NOMEPARC | String |  | Descr. Parceiro |  |
| NOMEUSUCONF | String |  | Conferente |  |
| NUTAREFA | Integer |  | Nro. Tarefa |  |
| STATUSCONF | Integer |  | Status Conferência |  |
| CANCELADA | String |  | Cancelada | `N`=Não `S`=Sim `P`=Parcial |
| OBSERVACAO | String |  | Observação |  |
| USACONFPARCIAL | String |  | Usa conferência parcial? | `N`=Não `S`=Sim |
| CONFFINAL | String |  | Conf. Final | `N`=Não `S`=Sim |
| M3CONFERIDO | Integer |  | M3 Conferido |  |
| PESOCONFERIDO | Integer |  | Peso Conferido |  |
| M3ARMAZENADO | Integer |  | M3 Armazenado |  |
| PESOARMAZENADO | Integer |  | Peso Armazenado |  |
| M3TOTAL | Integer |  | M3 Total |  |
| PESOTOTAL | Integer |  | Peso Total |  |
| ESTOQUESEMSAIDA | String |  | Estoque sem saídas pendentes |  |
| ESTOQUEENDERECO | String |  | Estoque Endereço |  |
| DHINICIOCONF | DateTime |  | Dh. Ini. Conferência |  |
| DHFINALCONF | DateTime |  | Dh. Fin. Conferência |  |
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |

## VGWRESPREV — View Ressuprimento Preventivo
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEND | Integer |  | End. Reduzido |  |
| DESCREND | String |  | Desc. Endereço |  |
| ENDERECO | String |  | Endereço |  |
| SUGESTAOUNPAD | Float |  | Qtd.Sug (UN.Pad) |  |
| PERCCOMPLETUDE | Integer |  | % Completude |  |
| ESTMAXVOLPAD | Integer |  | Est.Max (UN.Pad) |  |
| SUGESTAOUNPK | Float |  | Qtd.Sug (UN.PK) |  |
| CODEMP | Integer |  | Cód. Emp. |  |
| NIVEL | Integer |  | Nível |  |
| CONTROLE | String |  | Controle |  |
| REFERENCIA | String |  | Referência |  |
| MARCA | String |  | Marca |  |
| COMPLDESC | String |  | Complemento |  |
| CODAREASEP | Integer |  | Cód. Área Separação |  |
| NOMEAREASEP | String |  | Descr. Área Separação |  |
| ESTOQUEUNPK | Integer |  | Est.Picking |  |
| CODVOLPK | String |  | Un.Picking |  |
| ESTOQUEUNPAD | Integer |  | Est.Picking (UN.Pad) |  |
| ENTRPENDVOLPAD | Integer |  | Ent.Pendentes (UN.Pad) |  |
| CODVOLPAD | String |  | Un. Padrão |  |
| ESTMINVOLPAD | Integer |  | Est.Min (UN.Pad) |  |
| ESTRESSUPUNPK | Integer |  | Qtd.Ressuprir (UN.PK) |  |
| ORDEM | Integer |  | Ordem End. |  |
| ESTMAX | Integer |  | Est.Max (UN.PK) |  |
| ESTOQUEOUTROSUNPAD | Integer |  | Est.Pulmões (UN.Pad) - (Entr. Pen + Est. Atual) |  |
| ESTOQUEOUTROSATUAL | Integer |  | ESTOQUEOUTROSATUAL |  |
| CODPROD | Integer |  | Cód. Prod. |  |
| CODPARC | Integer |  | Cód. Parc. |  |

## VGWSEPCHK — VIEW VGWSEPCHK
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTAREFA | Integer |  | Nro. Tarefa |  |
| DTSEPARACAO | Date |  | Dt. Separação |  |
| CODDOCA | Integer |  | Cod. Doca |  |
| DESCRICAO | String |  | Descrição |  |
| CODENDDESTINO | Integer |  | End. Destino |  |
| CODUSUCONF | Integer |  | Cod. Usu. Conferente |  |
| NOMEUSUCONF | String |  | Usu. Conferente |  |
| CANCELADA | String |  | Cancelado | `N`=Não `S`=Sim |
| DESTFINAL | String |  | Dest. Final |  |
| CODEMPOC | Integer |  | Empresa OC |  |
| ORDEMCARGA | Integer |  | Ord. Carga |  |
| NUNOTA | Integer |  | Nro. Único |  |
| NUMNOTA | Integer |  | Num. Nota |  |
| STATUSCONF | String |  | Status Conferência |  |
| NUSEPARACAO | Integer |  | Nro. Separação |  |

## VGWTARSEP — VIEW VGWTARSEP
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTAREFA | String |  | Descr. Tarefa |  |
| CODEMP | Integer |  | Cod. Empresa |  |
| NUTAREFA | Integer |  | Tarefa |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cod. Produto |  |
| DESCRPROD | String |  | Descr. Produto |  |
| COMPLDESC | String |  | Complemento |  |
| CODENDORIGEM | Integer |  | Cod. End. Origem |  |
| DESCRORIG | String |  | Descr. End. Origem |  |
| ENDORIG | String |  | End. Origem |  |
| CODENDDESTINO | Integer |  | Cod. End. Destino |  |
| QTDORIG | Integer |  | Qtd. Origem |  |
| CODVOLORIG | String |  | Un. Origem |  |
| DESCRDEST | String |  | Descr. End. Destino |  |
| ENDDEST | String |  | End. Destino |  |
| QTDDEST | Integer |  | Qtd. Destino |  |
| CODVOLDEST | String |  | Un. Destino |  |
| SITUACAO | String |  | Situação | `A`=Aberta `F`=Fechada `E`=Em execução |
| CODAREASEP | Integer |  | Cod. Área Sep. |  |
| NOMEAREASEP | String |  | Área Separação |  |
| CODUSUTAR | Integer |  | Cod. Usu. Executante |  |
| NOMEUSUTAR | String |  | Executante |  |
| POSSUIDEPENDENTE | String |  | Pos. Tar. Dependentes? | `N`=Não `S`=Sim |
| DEPENDEDEOUTRA | String |  | Dep. da exe. de outra tarefa? | `S`=Sim `N`=Não |
| CODTAREFA | Integer |  | Cod. Tarefa |  |

## VIEWADIANTAMENTOBAIXA — VIEW VIEWADIANTAMENTOBAIXA
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód. Parceiro |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| VLRTAXA | Integer |  | Vlr. Taxa |  |
| VLRDESDOB | Integer |  | Vlr. Desdobramento |  |
| NUANTECIPA | Integer |  | Nro. Antecipação |  |

## VIEW_FLOW_EXEC_2 — VIEW_FLOW_EXEC_2
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VWFEBD_UNIDADE | String |  | Unidade de Medida |  |
| VWFEBD_GRUPO | String |  | Grupo |  |
| VWFEBD_DESCRICAO | String |  | Descrição |  |
| VWFEBD_CONTAEFD | String |  | CONTAEFD |  |
| VWFEBD_CONTACTB4 | String |  | CONTACTB4 |  |
| VWFEBD_CONTACTB3 | String |  | CONTACTB3 |  |
| VWFEBD_CONTACTB2 | String |  | CONTACTB2 |  |
| VWFEBD_CONTACTB1 | String |  | CONTACTB1 |  |
| VWFEBD_USADOCOMO | String |  | Usado Como | `1`=Subproduto `2`=Prod.Intermediário `B`=Brinde `C`=Consumo `4`=Demonstração_(+1)_ |
| VWFEBD_IPI | String |  | IPI |  |
| OBSCANCEL | String |  | Observação do cancelamento |  |
| TEMPO_ATENDIMENTO | Integer |  | Tempo de atendimento |  |
| SUSPENSO_SLA | String |  | SLA Suspenso |  |
| STATUS_SLA | String |  | Status do SLA | `A`=A vencer `V`=Vencido `I`=Início prazo `M`=Muito vencido `P`=No prazo |
| SITUACAOEXEC | String |  | Situação da solicitação | `C`=Cancelado `F`=Finalizado `I`=Iniciado |
| PRAZO_SLA | DateTime |  | Prazo do SLA |  |
| NOME_TAREFA | String |  | Tarefa |  |
| IS_APPOINTMENTCRUD | String |  | Tipo manipulação apontamento |  |
| IDINSTPRN | Integer |  | Nro. Solicitação |  |
| EFIC_EXECUCAO | Integer |  | Eficiência de execução |  |
| DHINCLUSAO | DateTime |  | Dh. da solicitação |  |
| DHCONCLUSAO_PROCESSO | DateTime |  | Dh. conclusão da solicitação |  |
| DHACEITE | DateTime |  | Início da tarefa |  |
| CODUSUINC | Integer |  | Usuário inclusão |  |
| VERSAO_ATUAL | Integer |  | Versão atual do processo |  |
| APPOINTMENT_STARTED | Integer |  | Apontamento Iniciado |  |
| TEMPO_EXECUCAO | Integer |  | Tempo de execução |  |
| CODUSUCANCEL | Integer |  | Responsável cancelamento |  |
| TEMPO_APONTAMENTO | Integer |  | Tempo de apontamento |  |
| VERSAO_PROCESSO | Integer |  | Versão |  |
| STATUS_TAREFA | String |  | Status da Tarefa | `P`=No prazo `A`=A vencer `V`=Vencido `M`=Muito vencido |
| SOLICITANTE | Integer |  | Solicitante |  |
| PRAZO_TAREFA | DateTime |  | Prazo da Tarefa |  |
| NUGRUPO | Integer |  | Grupo processo |  |
| NOME_PROCESSO | String |  | Nome processo |  |
| IS_APPOINTMENT | String |  | Tipo apontamento |  |
| EFIC_FILA | Integer |  | Eficiência de fila |  |
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| DHCRIACAO | DateTime |  | Dh. criação da tarefa |  |
| IDELEMENTO | String |  | Id Elemento |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão da tarefa |  |
| COD_PROCESSO | Integer |  | Processo |  |
| CODUSUDONO | Integer |  | Responsável da tarefa |  |
| TEMPO_FILA | Integer |  | Tempo de fila |  |
| TEMPO_DECORRIDO | Integer |  | Tempo decorrido |  |
| VWFEBD_APROVACAO | String |  | Aprovado? | `S`=Sim `N`=Não |

## VIEW_FLOW_EXEC_3 — VIEW_FLOW_EXEC_3
Campos: 41

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VWFEBD_MARKETPLACE | String |  | Marketplace | `11`=MAGALUex `1`=SITE `12`=SHOPEEex `2`=B2Wex `3`=B2W_(+7)_ |
| VWFEBD_DTSOLICI | Date |  | Data da Solicitação |  |
| VWFEBD_INICIAL | Date |  | inicial |  |
| VWFEBD_AUTORIZADO | String |  | Autorizado |  |
| VWFEBD_NUNOTA | String |  | numero unico |  |
| OBSCANCEL | String |  | Observação do cancelamento |  |
| TEMPO_ATENDIMENTO | Integer |  | Tempo de atendimento |  |
| SUSPENSO_SLA | String |  | SLA Suspenso |  |
| STATUS_SLA | String |  | Status do SLA | `P`=No prazo `A`=A vencer `V`=Vencido `I`=Início prazo `M`=Muito vencido |
| SITUACAOEXEC | String |  | Situação da solicitação | `C`=Cancelado `F`=Finalizado `I`=Iniciado |
| PRAZO_SLA | DateTime |  | Prazo do SLA |  |
| NOME_TAREFA | String |  | Tarefa |  |
| IS_APPOINTMENTCRUD | String |  | Tipo manipulação apontamento |  |
| IDINSTPRN | Integer |  | Nro. Solicitação |  |
| EFIC_EXECUCAO | Integer |  | Eficiência de execução |  |
| DHINCLUSAO | DateTime |  | Dh. da solicitação |  |
| DHCONCLUSAO_PROCESSO | DateTime |  | Dh. conclusão da solicitação |  |
| DHACEITE | DateTime |  | Início da tarefa |  |
| CODUSUINC | Integer |  | Usuário inclusão |  |
| VERSAO_ATUAL | Integer |  | Versão atual do processo |  |
| APPOINTMENT_STARTED | Integer |  | Apontamento Iniciado |  |
| TEMPO_EXECUCAO | Integer |  | Tempo de execução |  |
| CODUSUCANCEL | Integer |  | Responsável cancelamento |  |
| TEMPO_APONTAMENTO | Integer |  | Tempo de apontamento |  |
| VERSAO_PROCESSO | Integer |  | Versão |  |
| STATUS_TAREFA | String |  | Status da Tarefa | `P`=No prazo `A`=A vencer `V`=Vencido `M`=Muito vencido |
| SOLICITANTE | Integer |  | Solicitante |  |
| PRAZO_TAREFA | DateTime |  | Prazo da Tarefa |  |
| NUGRUPO | Integer |  | Grupo processo |  |
| NOME_PROCESSO | String |  | Nome processo |  |
| IS_APPOINTMENT | String |  | Tipo apontamento |  |
| EFIC_FILA | Integer |  | Eficiência de fila |  |
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| DHCRIACAO | DateTime |  | Dh. criação da tarefa |  |
| IDELEMENTO | String |  | Id Elemento |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão da tarefa |  |
| COD_PROCESSO | Integer |  | Processo |  |
| CODUSUDONO | Integer |  | Responsável da tarefa |  |
| TEMPO_FILA | Integer |  | Tempo de fila |  |
| TEMPO_DECORRIDO | Integer |  | Tempo decorrido |  |
| VWFEBD_TANSPORTADORA | String |  | Transportadora |  |

## VIEW_FLOW_SOLI_2 — VIEW_FLOW_SOLI_2
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VWFEBD_UNIDADE | String |  | Unidade de Medida |  |
| VWFEBD_GRUPO | String |  | Grupo |  |
| VWFEBD_DESCRICAO | String |  | Descrição |  |
| VWFEBD_CONTAEFD | String |  | CONTAEFD |  |
| VWFEBD_CONTACTB4 | String |  | CONTACTB4 |  |
| VWFEBD_CONTACTB3 | String |  | CONTACTB3 |  |
| VWFEBD_CONTACTB2 | String |  | CONTACTB2 |  |
| VWFEBD_CONTACTB1 | String |  | CONTACTB1 |  |
| VWFEBD_USADOCOMO | String |  | Usado Como | `1`=Subproduto `2`=Prod.Intermediário `B`=Brinde `C`=Consumo `4`=Demonstração_(+1)_ |
| VWFEBD_IPI | String |  | IPI |  |
| SOLICITANTE | Integer |  | Solicitante |  |
| TEMPO_EXECUCAO | Integer |  | Tempo de execução |  |
| STATUS_SLA | String |  | Status do SLA | `A`=A vencer `V`=Vencido `I`=Início prazo `M`=Muito vencido `P`=No prazo |
| TEMPO_FILA | Integer |  | Tempo de fila |  |
| RESPONSAVEL_TAREFA_ATUAL | Integer |  | Responsável da tarefa atual |  |
| CODUSUCANCEL | Integer |  | Responsável cancelamento |  |
| TEMPO_APONTAMENTO | Integer |  | Tempo de apontamento |  |
| SITUACAOEXEC | String |  | Situação da solicitação | `C`=Cancelado `F`=Finalizado `I`=Iniciado |
| OBSCANCEL | String |  | Observação do cancelamento |  |
| TEMPO_ATENDIMENTO | Integer |  | Tempo de atendimento |  |
| IDINSTPRN | Integer |  | Nro Solicitação |  |
| PRAZO_SLA | DateTime |  | Prazo do SLA |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão da solicitação |  |
| DHINCLUSAO | DateTime |  | Dh. da solicitação |  |
| COD_PROCESSO | Integer |  | Cód. Processo |  |
| IDPRNMESTRE | Integer |  | Nro Solicitação mestre |  |
| EFIC_FILA | Integer |  | Eficiência de fila |  |
| EFIC_EXECUCAO | Integer |  | Eficiência de execução |  |
| TAREFA_ATUAL | String |  | Tarefa atual |  |
| VERSAO | Integer |  | Versão |  |
| VERSAO_ATUAL | Integer |  | Versão atual do processo |  |
| VWFEBD_APROVACAO | String |  | Aprovado? | `S`=Sim `N`=Não |

## VIEW_FLOW_SOLI_3 — VIEW_FLOW_SOLI_3
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VWFEBD_MARKETPLACE | String |  | Marketplace | `11`=MAGALUex `1`=SITE `12`=SHOPEEex `2`=B2Wex `3`=B2W_(+7)_ |
| VWFEBD_DTSOLICI | Date |  | Data da Solicitação |  |
| VWFEBD_INICIAL | Date |  | inicial |  |
| VWFEBD_AUTORIZADO | String |  | Autorizado |  |
| VWFEBD_NUNOTA | String |  | numero unico |  |
| SOLICITANTE | Integer |  | Solicitante |  |
| TEMPO_EXECUCAO | Integer |  | Tempo de execução |  |
| STATUS_SLA | String |  | Status do SLA | `P`=No prazo `A`=A vencer `V`=Vencido `I`=Início prazo `M`=Muito vencido |
| TEMPO_FILA | Integer |  | Tempo de fila |  |
| RESPONSAVEL_TAREFA_ATUAL | Integer |  | Responsável da tarefa atual |  |
| CODUSUCANCEL | Integer |  | Responsável cancelamento |  |
| TEMPO_APONTAMENTO | Integer |  | Tempo de apontamento |  |
| SITUACAOEXEC | String |  | Situação da solicitação | `F`=Finalizado `I`=Iniciado `C`=Cancelado |
| OBSCANCEL | String |  | Observação do cancelamento |  |
| TEMPO_ATENDIMENTO | Integer |  | Tempo de atendimento |  |
| IDINSTPRN | Integer |  | Nro Solicitação |  |
| PRAZO_SLA | DateTime |  | Prazo do SLA |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão da solicitação |  |
| DHINCLUSAO | DateTime |  | Dh. da solicitação |  |
| COD_PROCESSO | Integer |  | Cód. Processo |  |
| IDPRNMESTRE | Integer |  | Nro Solicitação mestre |  |
| EFIC_FILA | Integer |  | Eficiência de fila |  |
| EFIC_EXECUCAO | Integer |  | Eficiência de execução |  |
| TAREFA_ATUAL | String |  | Tarefa atual |  |
| VERSAO | Integer |  | Versão |  |
| VERSAO_ATUAL | Integer |  | Versão atual do processo |  |
| VWFEBD_TANSPORTADORA | String |  | Transportadora |  |

## VIMADM — View Contrato de Administração
Campos: 74

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ADMIMOVEL | Integer |  | Nro. Imóvel |  |
| ADMDATA | Date |  | Dt. Contrato |  |
| ADMVENDA | String |  | Imóvel para venda |  |
| ADMLOCACAO | String |  | Imóvel para locação |  |
| ADMLCTAXAMIN | Integer |  | ADMLCTAXAMIN |  |
| ADMLCTIPRILOC | String |  | ADMLCTIPRILOC |  |
| ADMLCTIPRIPARC | Integer |  | ADMLCTIPRIPARC |  |
| ADMLCTIMOTIVO | String |  | ADMLCTIMOTIVO |  |
| ADMLCGARANTIA | String |  | ADMLCGARANTIA |  |
| ADMLCQTGARANTE | Integer |  | ADMLCQTGARANTE |  |
| ADMLCRPTIPDIAS | Integer |  | ADMLCRPTIPDIAS |  |
| ADMUSUARIO | Integer |  | Usuário Alteração |  |
| ADMIMOBILIARIA | Integer |  | Imobiliária Locação |  |
| ADMCAPTADOR | Integer |  | Captador |  |
| ADMDESTINACAO | String |  | Destinação |  |
| ADMVISITAS | String |  | Visitas |  |
| ADMOBSVISITAS | String |  | Obs. sobre visitas |  |
| ADMDFQUITADO | String |  | Quitado |  |
| ADMDFAGENTEFINANCEIRO | Integer |  | Agente Financeiro |  |
| ADMDFFINANCIAMENTO | String |  | Financiamento |  |
| ADMDFTRANSFERENCIA | Float |  | Transferência (%) |  |
| ADMDFPRECODEVENDA | Float |  | Vlr. Venda |  |
| ADMDFPRECOALUGUEL | Float |  | Vlr. Aluguel |  |
| ADMDFPOUPANCA | Float |  | Vlr. Poupança |  |
| ADMDFSALDODEVEDOR | Float |  | Vlr. saldo devedor |  |
| ADMDFPRESTACAO | Float |  | Vlr. Prestação Financiamento |  |
| ADMDFCOMISSAO | Float |  | Comissão (%) |  |
| ADMDATALIBERACAO | Date |  | Dt. Liberação |  |
| ADMDATACADASTRO | DateTime |  | Dh. Inclusão |  |
| ADMDFCOMISSAOADM | Float |  | Tx. Adm. (%) |  |
| ADMQUANTIDADEANUNCIO | Integer |  | Qtd. Anúncios |  |
| ADMDATADESOCUPADO | Date |  | Dt. Baixa Locação |  |
| ADMPORQUEDESOCUPOU | String |  | Motivo Baixa Locação |  |
| ADMDIASOPCAO | Integer |  | Qtd. dias exclusividade |  |
| ADMDESTAQUE | String |  | Destaque Site |  |
| ADMPRIMEIROALUGUEL | String |  | Cobrar Tx. Interm. |  |
| ADMDATAFIMOPCAO | Date |  | Dt. Fim Exclusividade |  |
| ADMTAXADIFERENTE | Float |  | Tx. Interm. (%) |  |
| ADMPRIPARPRI | Integer |  | Nro. parcela de início de cobrança |  |
| ADMQTDPARPRI | Integer |  | Diluído em (qtd. parc.) |  |
| ADMPRILOCACAO | String |  | ADMPRILOCACAO |  |
| ADMTXADMMINIMA | Integer |  | ADMTXADMMINIMA |  |
| ADMJUSTIFADMINTER | String |  | ADMJUSTIFADMINTER |  |
| ADMTIPOALUGUEL | String |  | ADMTIPOALUGUEL |  |
| ADMDIASUTEIS | String |  | Tipo Dias |  |
| ADMREPASSEMULTA | String |  | ADMREPASSEMULTA |  |
| ADMIMOB2 | Integer |  | Imobiliária Venda |  |
| ADMSEMCHAVES | String |  | Sem Chaves |  |
| ADMVAISITE | String |  | Anuncia no site |  |
| ADMSEMANUNCIOS | String |  | ADMSEMANUNCIOS |  |
| ADMSEMPLACA | String |  | Sem Placa |  |
| ADMFIMOPCAOLOCA | DateTime |  | ADMFIMOPCAOLOCA |  |
| ADMPQDESOCUPOU | String |  | Motivo Baixa Venda |  |
| ADMCONTABANCO | Integer |  | ADMCONTABANCO |  |
| ADMVAIJURIDICO | String |  | ADMVAIJURIDICO |  |
| ADMCONDICOESDAVENDA | String |  | Condições Venda |  |
| ADMFINANCIAMENTOBCO | Integer |  | Banco Financiamento |  |
| ADMEXCLUSIVOLOC | String |  | Loc. Exclusiva |  |
| ADMEXCLUSIVO | String |  | Ven. Exclusiva |  |
| ADMESTAGIO | String |  | Estágio |  |
| ADMJUSTIFICAINTER | String |  | Justificativa Intermediação |  |
| ADMDIASREPASSE | Integer |  | Qtd. dias até o repasse |  |
| ADMDATABASEREP | String |  | ADMDATABASEREP |  |
| ADMDATADESOCUPADOVENDA | Date |  | Dt. Baixa Venda |  |
| ADMGARANTIDO | String |  | Garantido |  |
| ADMCHAVES | String |  | Chaves |  |
| ADMCORRESPBANCARIO | String |  | Correspondente Bancário |  |
| ADMCONDLOC | String |  | Condições Locação |  |
| ADMPRAZOADM | Integer |  | Vigência p/ Adm. |  |
| ADMPRAZOLOC | Integer |  | Vigência do Contrato |  |
| ADMCODUSUINC | Integer |  | Usuário Inclusão |  |
| ADMDHALTER | DateTime |  | Dh. Alteração |  |
| ADMEMPRESANF | Integer |  | Empresa NF |  |
| ADMNUCONTRATO | Integer |  | Nro. Contrato |  |

## VIMAPR — View Compradores Loteamento
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LVCPROCURADOR | Integer |  | Procurador |  |
| LTELOTEAMENTO | Integer |  | Loteamento |  |
| LVCDESCRICAO | String |  | Descrição |  |
| LVCCLIENTE | Integer |  | Cliente |  |

## VIMBUA — VIEW VIMBUA
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FACCODIGO | Integer |  | FAC |  |
| FACPROSPECT | Integer |  | Cod. Prospect |  |
| PPRNOME | String |  | Prospect |  |
| PPRTELEFONES | String |  | Telefones do Prospect |  |
| CORRETOR | String |  | Corretor |  |
| GERENTE | String |  | Gerente |  |
| TELEFONES_CORRETOR | String |  | Telefones do Corretor |  |
| CGC | String |  | CPF/CNPJ do Prospect |  |
| FACOBSERVACAO | String |  | Observação |  |
| PPREMAIL | String |  | Email |  |
| DIAS | Integer |  | Dias Inativos |  |

## VIMDER — VIMDER
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RECDESP | Integer |  | Receita/Despesa | `1`=Receita `-1`=Despesa |
| VLRDESDOB | Float |  | Vlr do Desdobramento |  |
| VLRJUROEMBUT | Float |  | Vlr Juros Embutidos |  |
| VLRMULTAEMBUT | Float |  | Vlr Multa Embutida |  |
| VLRDESCEMBUT | Float |  | Vlr Desc. Embutido |  |
| TIPJURO | String |  | Tipo Juro | `2`=Extra Nota `1`=Incluso |
| TIPMULTA | String |  | Tipo Multa | `2`=Extra Nota `1`=Incluso |
| VLRJURO | Float |  | Vlr Juros |  |
| VLRMULTA | Float |  | Vlr Multa |  |
| VLRDESC | Float |  | Vlr Desconto |  |
| DTVENCINIC | DateTime |  | Dt. Venc. Inicial |  |
| DTVENC | Date |  | Dt. Vencimento |  |
| TIMPARCELA | Integer |  | Parcela |  |
| TIMORIGEM | String |  | Tipo Parcela | `RP`=Repasse `RL`=Registro de Lote `PP`=FPP `PI`=Intermediária `PD`=Diferenciada_(+29)_ |
| DHBAIXA | Date |  | Data Baixa |  |
| DTLPARCELA | Integer |  | ID Parcela |  |
| DTLCODIGO | Integer |  | Código |  |
| DTLHISTORICO | Integer |  | Tipo do Detalhamento |  |
| DTLCOMPLEMENTO | String |  | Complemento |  |
| DTLDTINIC | Date |  | Dt. Início Período |  |
| DTLDTFIM | Date |  | Dt. Fim Período |  |
| DTLCODIPTU | Integer |  | Cod. IPTU |  |
| DTLPARCELAIPTU | Integer |  | Cod. Parcela IPTU |  |
| DTLCOMISSAOIPTU | Float |  | Comissão Iptu |  |
| DTLDHGERREPASSE | DateTime |  | Dh. Ger. Repasse |  |
| DTLGARANTIDO | String |  | Garantido | `S`=Sim `N`=Não |
| NUFIN | Integer |  | Nro Único |  |

## VIMFAC — Ficha de Atendimento ao Cliente
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FACESTAGIO | String |  | Estágio | `P`=Prospecção `N`=Negociação `F`=Com Sucesso `C`=Com Proposta `I`=Pegou Chaves_(+1)_ |
| FACOBSERVACAO | String |  | Observação |  |
| FACVEICULO | Integer |  | Veículo |  |
| FACBUSCAPOR | String |  | Interesse em | `VE`=Vender `LO`=Alugar `CO`=Comprar `CL`=Captação para locação `CB`=Corresp. Bancário_(+2)_ |
| FACCORRETOR | Integer |  | Corretor |  |
| FACLANCAMENTO | DateTime |  | Dh. Inclusão |  |
| FACUSUARIO | Integer |  | Usuário Inclusão |  |
| FACEMPREENDIMENTO | Integer |  | Empreendimento |  |
| FACTIPOIMOVEL | Integer |  | Tipo de imóvel |  |
| FACQUARTOS | Integer |  | Quartos |  |
| FACBAIRROIMOVEL | Integer |  | Bairro do imóvel |  |
| FACORIGEM | String |  | Origem | `X`=Feirão Caixa `V`=Visita `R`=Prospecção Telefone `L`=Ligação `I`=Lista Telefônica_(+4)_ |
| FACEDIFICIO | Integer |  | Edifício |  |
| FACVALORPEDIDO | Integer |  | Valor pedido |  |
| FACRETORNAR | DateTime |  | Dt. Retorno |  |
| FACPROSPECT | Integer |  | Prospect |  |
| FACCAPTACAO | String |  | Captação |  |
| FACDHALTER | DateTime |  | Dh. Alteração |  |
| FACUSUALTER | Integer |  | Usuário Alteração |  |
| FACSITUACAOCHAVE | String |  | Situação Chaves |  |
| FACDHDEVCHAVE | DateTime |  | Dh. Dev. Chaves |  |
| FACDHENTCHAVE | DateTime |  | Dh. Entrega Chaves |  |
| FACDOCCHAVE | String |  | Doc. Entrega Chaves |  |
| FACNOMEPPROSPECT | String |  | Nome Prospect |  |
| FACCODIGO | Integer |  | Código |  |

## VIMTHI — Tipo de SAC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| THIDESCRICAO | String |  | Descrição Motivo |  |
| THIORIGEM | String |  | Produto | `VL`=Venda de Lote `MO`=Modelo de SAC `LE`=Lote `IN`=Informação `IM`=Imóvel_(+8)_ |
| THICODHISTORICO | Integer |  | Motivo |  |
| THICODIGO | Integer |  | Código |  |

## VPRLPIPRO — View Produto Intermediário
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | CODPRODPA |  |
| CONTROLEPA | String |  | CONTROLEPA |  |
| CODPRODPI | Integer |  | Produto (PI) |  |
| CONTROLEPI | String |  | Controle (PI) |  |
| TIPOPI | String |  | TIPOPI |  |
| TIPOSUBOP | String |  | TIPOSUBOP |  |
| AGUARDARSUBOP | String |  | AGUARDARSUBOP |  |
| TIPONROLOTE | String |  | TIPONROLOTE |  |
| DESCRPRODPA | String |  | DESCRPRODPA |  |
| DESCRPRODPI | String |  | Descrição Produto (PI) |  |
| IDPROC | Integer |  | IDPROC |  |

## VPRMER — Movimentação de Estoque em Repositório
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRATIVIDADE | String |  | Descr. Operação |  |
| IDRPAORIG | Integer |  | Cód. Origem |  |
| IDRPADEST | Integer |  | Cód. Destino |  |
| DHMOV | DateTime |  | Dh. Movimentação |  |
| QTD | Float |  | Quantidade |  |
| CODPRODPA | Integer |  | Cód. Produto (PA) |  |
| REFERENCIA | String |  | Referência do Produto |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| IDIPROC | Integer |  | Instãncia do Processo |  |

## VRI_ACOMPANHAMENTO_TRANSMISSAO — View Acompanhamento da Transmissão
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| SEQUENCIA | Integer |  | Sequência |  |
| EVENTO | String |  | Evento | `R2040`=R2040 `R2099`=R2099 `R2098`=R2098 `R2060`=R2060 `R2050`=R2050_(+11)_ |
| AGUARDEVTPRIORITARIO | Integer |  | Aguard. Evento Prioritário |  |
| PENDENTES | Integer |  | Pendentes |  |
| ENVIADOS | Integer |  | Aguard. Processamento |  |
| AGUARDCORRECAO | Integer |  | Aguard. Correção |  |
| ERROEVTPRIORITARIO | Integer |  | Erro em Evento Prioritário |  |
| FINALIZADO | Integer |  | Finalizados |  |
| TOTAL | Integer |  | Total de Eventos |  |
| CODEMP | Integer |  | Empresa |  |

## VRI_ACOMP_TRANSMISSAO_ERRO — View Acompanhamento da Transmissão c/ Erro
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| SEQUENCIA | Integer |  | Sequência |  |
| EVENTO | String |  | Evento |  |
| CHAVE | String |  | Chave |  |
| IDENTIFICADOR | String |  | Identificador |  |
| IDEVENTO | String |  | ID do Evento |  |
| SITUACAO | String |  | Situação |  |
| MSG | C |  | Mensagem |  |
| CODEMP | Integer |  | Empresa |  |

## VSILIB — View Liberacao Limites
Campos: 45

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCHAVE | Integer |  | Nro Único |  |
| EVENTO | Integer |  | Evento |  |
| NUNOTA | Integer |  | Nro Único Nota |  |
| CODUSUSOLICIT | Integer |  | Cód. Usuário Solicitante |  |
| PERCLIMITE | Float |  | % Limite |  |
| PERCSOLIC | Float |  | % Solicitado |  |
| VLRLIMITE | Float |  | Valor Limite |  |
| VLRATUAL | Float |  | Valor Solicitado |  |
| DHSOLICIT | DateTime |  | Data Solicitação |  |
| CODUSULIB | Integer |  | Cód. Usuário Liberador |  |
| DHLIB | DateTime |  | Data Liberação |  |
| PERCANTERIOR | Float |  | % Anterior |  |
| VLRANTERIOR | Float |  | Vlr.Solicit.Anterior |  |
| SEQUENCIA | Integer |  | Sequência |  |
| OBSERVACAO | String |  | Observação |  |
| OBSLIB | String |  | Observação Liberador |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODVEND | Integer |  | Cód.Vendedor |  |
| CODPARCTRANSP | Integer |  | Cód. Parceiro Transportadora |  |
| OBSCOMPL | String |  | Observação Complementar |  |
| DTNEG | Date |  | Dt. Negociação |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| VLRNOTA | Float |  | Valor Nota/Financ. |  |
| DTVENC | Date |  | Prim.Dt.Venc |  |
| REPROVADO | String |  | Reprovado | `N`=Não `S`=Sim |
| CODNAT | Integer |  | Cód.Natureza |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODPROJ | Integer |  | Cód.Projeto |  |
| TOTALDESCONTONOTA | Integer |  | Valor Desconto Nota |  |
| TABELA | String |  | Tabela |  |
| NURNG | Integer |  | Regra de negócio |  |
| VLRTOTAL | Float |  | Valor Total |  |
| NULBO | Integer |  | Número do limite de bonificação |  |
| SUPLEMENTO | String |  | Suplemento |  |
| TRANSF | String |  | Transferência |  |
| VLRDESDOB | Float |  | Valor Desconto |  |
| DHTIPOPER | DateTime |  | Data Operação |  |
| STATUSNOTA | String |  | Status Nota |  |
| SEQCASCATA | Integer |  | Sequência Cascata |  |
| ORDEM | Integer |  | Ordem |  |
| NUCLL | Integer |  | Número Controle Liberação |  |
| DTPREVENT | DateTime |  | Previsão de entrega |  |
| PRECOLIQUIDO | Float |  | Preço Liquido |  |
| VLRLIBERADO | Float |  | Valor Liberado |  |

## VSIUSU — View Usuário/Grupo/Equipe
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEUSU | String |  | Nome Usuário/Grupo/Equipe |  |
| TIPUSUGRU | String |  | Tipo | `E`=Equipe `U`=Usuário `G`=Grupo |
| CODUSU | Integer |  | Cód. Usuário/Grupo/Equipe |  |

## VTSI001 — View Usuário API
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| NOMEUSU | String |  | Nome usuário |  |
| QTDACESSOS | Integer |  | Total de usuários |  |

## VWFEBD — Campos Embarcado Tarefa
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| DESCRICAO | String |  | Descrição |  |
| NOME | String |  | Nome |  |
| DTA | DateTime |  | Data e Hora |  |
| NUMDEC | Float |  | Número decimal |  |
| NUMINT | Integer |  | Número inteiro |  |
| TEXTO | String |  | Texto |  |
| TEXTOLONGO | String |  | Texto formatado |  |
| TIPO | String |  | Tipo |  |
| VALORPADRAO | String |  | Valor padrão |  |
| DEFAULTLONG | String |  | Valor padrão longo |  |
| IDINSTPRN | Integer |  | Nro Solicitação |  |

## VWFEQP — Equipe Flow
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMEMBRO | Integer |  | Código do usuário |  |
| NUEQUIPE | Integer |  | Número equipe |  |

## VWFITAR — Instância de Tarefas
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROCESSVERSION | Integer |  | Versão |  |
| PROCESSINSTANCEID | Integer |  | Id Instância do Processo |  |
| PROCESSNAME | String |  | Nome do Processo |  |
| PROCESSDOCUMENTATION | String |  | Documentação do Processo |  |
| PROCESSXML | String |  | XML do Processo |  |
| PROCESSUSERCREATECOD | Integer |  | Cód. Usuário solicitante |  |
| PROCESSUSERCREATENAME | String |  | Usuário solicitante |  |
| PROCESSCREATETIME | DateTime |  | Dh. criação do Processo |  |
| PROCESSENDTIME | DateTime |  | Dh. conclusão do Processo |  |
| TASKIDELEMENTO | String |  | Id do Elemento da Tarefa |  |
| TASKINSTANCEID | Integer |  | Id da Instância da Tarefa |  |
| TASKNAME | String |  | Nome da Tarefa |  |
| TASKDOCUMENTATION | String |  | Documentação da Tarefa |  |
| TASKUSERASSIGNEECOD | Integer |  | Cód. Usuário responsável |  |
| TASKUSERASSIGNEENAME | String |  | Usuário responsável |  |
| TASKCREATETIME | DateTime |  | Dh. criação |  |
| TASKSTARTTIME | DateTime |  | Dh. aceite |  |
| TASKENDTIME | DateTime |  | Dh. conclusão |  |
| PROCESSID | Integer |  | Cód. Processo |  |

## VWFSOLI — View Lista de Tarefas
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTPRN | Integer |  | Nro Solicitação |  |
| SOLICITANTE | Integer |  | Solicitante |  |
| COD_PROCESSO | Integer |  | Cód. Processo |  |
| VERSAO | Integer |  | Versão |  |
| SITUACAOEXEC | String |  | Situação da solicitação | `I`=Iniciado `F`=Finalizado `C`=Cancelado |
| DHINCLUSAO | DateTime |  | Dh. da solicitação |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão da solicitação |  |
| TAREFA_ATUAL | String |  | Tarefa atual |  |
| RESPONSAVEL_TAREFA_ATUAL | Integer |  | Responsável da tarefa atual |  |
| STATUS_SLA | String |  | Status do SLA | `V`=Vencido `P`=No prazo `M`=Muito vencido `I`=Início prazo `A`=A vencer |
| PRAZO_SLA | DateTime |  | Prazo do SLA |  |
| CODUSUCANCEL | Integer |  | Responsável cancelamento |  |
| OBSCANCEL | String |  | Observação do cancelamento |  |
| TEMPO_APONTAMENTO | Integer |  | Tempo de apontamento |  |
| EFIC_EXECUCAO | Integer |  | Eficiência de execução |  |
| EFIC_FILA | Integer |  | Eficiência de fila |  |
| TEMPO_ATENDIMENTO | Integer |  | Tempo de atendimento |  |
| TEMPO_EXECUCAO | Integer |  | Tempo de execução |  |
| TEMPO_FILA | Integer |  | Tempo de fila |  |
| IDPRNMESTRE | Integer |  | Nro Solicitação mestre |  |
| VERSAO_ATUAL | Integer |  | Versão atual do processo |  |

## VWFTAR — View Lista de Tarefas
Campos: 35

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| APPOINTMENT_STARTED | Integer |  | Apontamento Iniciado |  |
| IS_APPOINTMENTCRUD | String |  | Tipo manipulação apontamento |  |
| IS_APPOINTMENT | String |  | Tipo apontamento |  |
| SUSPENSO_SLA | String |  | SLA Suspenso |  |
| IDINSTPRN | Integer |  | Nro. Solicitação |  |
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| IDELEMENTO | String |  | Id Elemento |  |
| DHCRIACAO | DateTime |  | Dh. criação da tarefa |  |
| DHACEITE | DateTime |  | Início da tarefa |  |
| DHCONCLUSAO_PROCESSO | DateTime |  | Dh. conclusão da solicitação |  |
| CODUSUDONO | Integer |  | Responsável da tarefa |  |
| SOLICITANTE | Integer |  | Solicitante |  |
| SITUACAOEXEC | String |  | Situação da solicitação | `I`=Iniciado `F`=Finalizado `C`=Cancelado |
| STATUS_TAREFA | String |  | Status da Tarefa | `V`=Vencido `P`=No prazo `M`=Muito vencido `A`=A vencer |
| PRAZO_TAREFA | DateTime |  | Prazo da Tarefa |  |
| DHINCLUSAO | DateTime |  | Dh. da solicitação |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão da tarefa |  |
| CODUSUINC | Integer |  | Usuário inclusão |  |
| PRAZO_SLA | DateTime |  | Prazo do SLA |  |
| STATUS_SLA | String |  | Status do SLA | `V`=Vencido `P`=No prazo `M`=Muito vencido `I`=Início prazo `A`=A vencer |
| COD_PROCESSO | Integer |  | Processo |  |
| VERSAO_PROCESSO | Integer |  | Versão |  |
| NOME_PROCESSO | String |  | Nome processo |  |
| NUGRUPO | Integer |  | Grupo processo |  |
| NOME_TAREFA | String |  | Tarefa |  |
| CODUSUCANCEL | Integer |  | Responsável cancelamento |  |
| OBSCANCEL | String |  | Observação do cancelamento |  |
| TEMPO_APONTAMENTO | Integer |  | Tempo de apontamento |  |
| TEMPO_DECORRIDO | Integer |  | Tempo decorrido |  |
| EFIC_EXECUCAO | Integer |  | Eficiência de execução |  |
| EFIC_FILA | Integer |  | Eficiência de fila |  |
| TEMPO_ATENDIMENTO | Integer |  | Tempo de atendimento |  |
| TEMPO_EXECUCAO | Integer |  | Tempo de execução |  |
| TEMPO_FILA | Integer |  | Tempo de fila |  |
| VERSAO_ATUAL | Integer |  | Versão atual do processo |  |