# TGF — Financeiro (Títulos, Naturezas, Contas, Baixas)

> Gerado do dicionário oficial TDD Sankhya. 13 tabelas.


## TGFCRED — Tabela de Crediários
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| NUNOTA | Integer |  | Nr Nota |  |
| DTNEG | DateTime |  | Dt Negociação |  |
| VLRCONTRATO | Float |  | Vlr Contrato |  |
| VLRENTRADA | Float |  | Vlr Entrada |  |
| QTDPARCELAS | Integer |  | Qtd Parcelas |  |
| SITUACAO | String |  | Situação | `L`=Liquidado `C`=Cancelado `A`=Aberto |
| RENEGOCIADO | String |  | Renegociado | `S`=Sim `N`=Não |
| CODCONTRATOORIG | Integer |  | Contrato Origem |  |
| AVALISTA | String |  | Avalista | `S`=Sim `N`=Não |
| CODCLIENTE | Integer |  | Código do cliente |  |
| CODCONTRATO | Integer |  | Contrato |  |
| MEDATRASODIAS | Float |  | Média de Atraso (Dias) |  |

## TGFCREDAUDIT — Tabela de auditoria de crediário
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECAMPO | String |  | Nome do campo alterado |  |
| SEQUENCIA | Integer |  | Sequência de alteração do campo |  |
| VLRANTERIOR | String |  | Valor anterior à alteração |  |
| VLRNOVO | String |  | Novo valor do campo |  |
| DHALTER | DateTime |  | Data e hora de alteração do campo |  |
| CODUSUALTER | Integer |  | Código do usuário que realizou a alteração |  |
| CODCLIENTE | Integer |  | Código do cliente |  |

## TGFCREDCLI — Tabela de cliente de crediário
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LIMCREDITO | Float |  | Limite de crédito |  |
| NATURALIDADE | Integer |  | Naturalidade |  |
| ESTADOCIVIL | Integer |  | Estado civil | `7`=União estável `6`=Divorciado(a) `5`=Desquitado(a) `4`=Separado(a) judicialmente `3`=Viúvo_(+2)_ |
| CONJUGE | Integer |  | Cônjuge |  |
| FILIACAOPAI | String |  | Filiação pai |  |
| FILIACAOMAE | String |  | Filiação mãe |  |
| DTCADASTRO | DateTime |  | Data cadastro |  |
| CODUSUCADASTRO | Integer |  | Usuário cadastro |  |
| CELULAR | String |  | Celular |  |
| MORADIAPROPRIA | String |  | Moradia própria | `S`=Sim `N`=Não |
| TEMPOMORADIA | Integer |  | Tempo moradia |  |
| TIPEMPREGO | String |  | Tipo de Emprego | `E`=Empregado `A`=Autônomo |
| DTADMISSAO | DateTime |  | Data de admissão |  |
| CARGO | String |  | Cargo |  |
| PROFISSAO | String |  | Profissão |  |
| GRAUINSTRU | Integer |  | Grau de instrução | `9`=Pós graduação incompleta `8`=Ensino superior completo `7`=Ensino superior incompleto `6`=Ensino médio completo `5`=Ensino médio incompleto_(+5)_ |
| SCORE | Float |  | Score |  |
| CODENDEMPREGO | Integer |  | Cod. endereço emprego |  |
| CODCIDEMPREGO | Integer |  | Código cidade |  |
| CEPEMPREGO | String |  | CEP |  |
| TELEMPREGO | String |  | Telefone emprego |  |
| NOMEREFEMPREGO | String |  | Nome referência |  |
| TELREFEMPREGO | String |  | Telefone referência |  |
| EMPRESAEMPREGO | String |  | Empresa |  |
| CODBAIEMPREGO | Integer |  | Código bairro |  |
| CODCLIENTE | Integer |  | Código do cliente |  |

## TGFCREDCLIREND — Tabela de declaração de renda do cliente
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCLIENTE | Integer |  | Código cliente |  |
| DESCRRENDA | String |  | Descrição renda |  |
| TIPRENDA | String |  | Tipo de renda | `D`=Declarada `C`=Confirmada |
| DTCOMPROVACAO | DateTime |  | Data comprovação |  |
| VLRRENDA | Float |  | Valor de renda |  |
| CODRENDA | Integer |  | Código renda |  |

## TGFCRESTCOMST — Códigos de Mot. de Restit. e Comple. ICMS ST
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIO | Date |  | Data de início |  |
| DTFIM | Date |  | Data de Fim |  |
| CODAJUSTE | String | 5 | Código de Ajuste |  |
| DESCAJUSTE | String | 500 | Descrição do Ajuste |  |
| CODEMP | Integer |  | Empresa |  |
| CODCFO | Integer |  | CFOP |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| CLASSICMS | Integer |  | Classificação do ICMS | `5`=Produtor Rural `4`=Consumidor Final Contribuinte `3`=Revendedor `2`=Consumidor Final Não Contribuinte `1`=Isento de ICMS_(+1)_ |
| NUFOP | Integer |  | Finalidade da Operação |  |
| CODUF | Integer |  | UF de Ajuste |  |
| FILPERSONALIZADO | String |  | Filtro Personalizado |  |
| CONSIDR1255 | String |  | Considerar na totalização do registro 1255? | `S`=Sim `N`=Não |
| SEQUENCIA | Integer |  | Sequência |  |

## TGFFIN — Financeiro
Campos: 329

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMNOTA | Integer |  | Nro Nota |  |
| SERIENOTA | String |  | Série da Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| SANGDESPDV | String |  | Sangria de despesa PDV | `N`=Não `S`=Sim |
| CGC_CPF_PARC | String |  | CNPJ / CPF |  |
| CODEMP | Integer |  | Empresa |  |
| CONTABILIZADOPDD | String |  | Título contabilizado PDD |  |
| PERTENCEAC | String |  | Pertence ao acerto de carga | `N`=Não `S`=Sim |
| DESCRHISTAC | String |  | Descrição histórico |  |
| OBSERVACAOAC | String |  | Observação |  |
| RETORNADOAC | String |  | Retornado | `N`=Não `S`=Sim |
| STATUSLIB | Integer |  | Status liberação | `4`=Não autorizado `3`=Autorizado `2`=Sem solicitação `1`=Pendente |
| RECDESP | Integer |  | Receita/Despesa | `1`=Receita `-1`=Despesa |
| PROVISAO | String |  | Provisão | `N`=Não `S`=Sim |
| DTVENC | Date |  | Dt. Vencimento |  |
| DHBAIXA | Date |  | Data Baixa |  |
| DTNEG | Date |  | Dt. Negociação |  |
| DHMOV | DateTime |  | Dt/Hr Movimentação |  |
| DTBAIXAPREV | DateTime |  | Dt. Prevista p/ Baixa |  |
| CODPARCMATRIZ | Integer |  | Cod. Parceiro Matriz |  |
| DTENTSAI | Date |  | Dt. Entrada e Saída |  |
| NROCESSAOFDIC | String |  | Nro. Cessao FDIC |  |
| VLRDESDOB | Float |  | Vlr do Desdobramento |  |
| CONTABILIZADO | String |  | Contabilizado? | `S`=Sim `N`=Não |
| VLRDESDOBCALC | Float |  | Vlr do Desdobramento Calc |  |
| VLRATUAL | Integer |  | Vlr. Atual |  |
| VLRDESC | Float |  | Vlr Desconto |  |
| VLRMULTA | Float |  | Vlr Multa |  |
| VLRJURO | Float |  | Vlr Juros |  |
| VLRVENDOR | Float |  | Vlr Vendor |  |
| VLRALIBERAR | Float |  | Vlr. a liberar |  |
| VLRBAIXA | Float |  | Vlr Baixa |  |
| DESDOBDUPL | String |  | Desdob. Duplicata |  |
| VLRLIQUIDO | Float |  | Valor Líquido |  |
| ATRASO | Integer |  | Atraso (dias) |  |
| CODHISTAC | Integer |  | Histórico |  |
| HISTORICO | String |  | Histórico |  |
| CODTIPOPER | Integer |  | Tipo Operação |  |
| CODTIPTIT | Integer |  | Tipo de Título |  |
| BASEICMS | Float |  | Base ICMS |  |
| CODNAT | Integer |  | Natureza |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| CODPROJ | Integer |  | Projeto |  |
| NUMCONTRATO | Integer |  | Nro Contrato |  |
| REFATCON | Date |  | Ref. Faturamento do Contrato |  |
| ORIGEM | String |  | Origem | `E`=Estoque `P`=Pessoal `F`=Financeiro |
| CODVEND | Integer |  | Vendedor |  |
| AUTORIZADO | String |  | Autorizado | `N`=Não `S`=Sim |
| CODCBE | Integer |  | Acerto Benefício |  |
| CODREGUA | Integer |  | Régua |  |
| CARTA | Integer |  | Nro Carta |  |
| CODOBSPADRAO | Integer |  | Observação padrão |  |
| VALORPRESENTE | Float |  | Valor Presente |  |
| DTINITREFAPURACAO | DateTime |  | Data apuração |  |
| JUROSAVP | Float |  | Juros Ajuste do Valor Presente |  |
| BLOQVAR | String |  | Bloq. Calculo Variação | `N`=Não `S`=Sim |
| NUCOMPENS | Integer |  | Nro Compensação/Acerto |  |
| INDRECEFDCONT | String |  | Indicador de Receita (registro F525 - EFD Cont.) | `99`=99-Outros `05`=05- Item vendido (produtos e serviços) `04`=04- Documento fiscal `03`=03- Título de crédito - Duplicata, nota promissória, cheque, etc. `02`=02- Administradora de cartão de débito/crédito_(+1)_ |
| CODFUNC | Integer |  | Funcionário |  |
| INFCOMPLEFDCONT | String |  | Informação complementar do Indic. comp. receita recebida |  |
| CODCONTATO | Integer |  | Contato |  |
| PDD | String |  | PDD | `N`=Não `S`=Sim |
| CODIMOVELRURAL | Integer |  | Imóvel Rural |  |
| RECADIANTAMENTORURAL | String |  | Receita de Adiantamentos | `S`=Sim `N`=Não |
| CONCILIADO | String |  | Conciliado | `S`=Sim `N`=Não |
| IDTRANSACAOPIX | String |  | TXID Pix |  |
| DHCONCIL | DateTime |  | Dh. Conciliação |  |
| ANTECIPADO | String |  | Antecipado | `S`=Sim `N`=Não |
| DTANTECIPACAO | Date |  | Dt. antecipação |  |
| M2 | Float |  | Metro Quadrado |  |
| NUANTBANC | Integer |  | Nro. único antecipação |  |
| PRAZO | Integer |  | Prazo |  |
| CODMOEDA | Integer |  | Moeda |  |
| VLRJUROCALC | Float |  | Juros Calculados |  |
| VLRVARCAMBIAL | Float |  | Variação Cambial |  |
| VLRMOEDA | Float |  | Vlr Moeda |  |
| VLRMULTACALC | Float |  | Multa Calculada |  |
| TIPJURO | String |  | Tipo Juro | `1`=Incluso `2`=Extra Nota |
| VLRTOTALCALC | Float |  | Total Calculado |  |
| TIPMULTA | String |  | Tipo Multa | `2`=Extra Nota `1`=Incluso |
| VLRTROCO | Float |  | Vlr Troco |  |
| VLRMULTAEMBUT | Float |  | Vlr Multa Embutida |  |
| NUMTRANSF | Integer |  | Nro da Transferência |  |
| VLRJUROEMBUT | Float |  | Vlr Juros Embutidos |  |
| CODLANC | Integer |  | Cód. Lançamento |  |
| VLRJUROLIB | Float |  | Vlr Perdão de Juros |  |
| DHTIPOPERBAIXA | DateTime |  | Dt/Hr Tipo Operação |  |
| VLRMULTALIB | Float |  | Vlr Perdão de Multa |  |
| VLRJURONEGOC | Float |  | Vlr Juros Negociados |  |
| DESCRLANCBCO | String |  | Desc. Lanc. Bancário |  |
| VLRMULTANEGOC | Float |  | Vlr Multa Negociada |  |
| CTABCOBAIXA | String |  | Conta Baixa |  |
| RECDESPFILTER | String |  | Rec Desp p/ o Filtro |  |
| CODUSUBAIXA | Integer |  | Usuário Baixa |  |
| RATEADO | String |  | Rateado | `S`=Sim `N`=Não |
| CODTIPOPERBAIXA | Integer |  | Tipo Operação Baixa |  |
| CODEMPBAIXA | Integer |  | Emp. da Baixa |  |
| VLRMOEDABAIXA | Float |  | Vlr Moeda na Baixa |  |
| ORDEMCARGA | Integer |  | Ordem de Carga |  |
| CODVEICULO | Integer |  | Veículo |  |
| VLRPROV | Float |  | Vlr Provisão Financeira |  |
| NURENEG | Integer |  | Nro Renegociação |  |
| RATEADOCAB | String |  | Proveniente de nota rateada |  |
| PARCRENEG | String |  | Parcelas da Renegociação |  |
| NUCKC | Integer |  | Nro. Checkout |  |
| VLRICMS | Float |  | Vlr ICMS |  |
| SEQCAIXA | Integer |  | Seq. Caixa |  |
| IDLOTEFDIC | Integer |  | Identificador do Lote FDIC |  |
| MOSTRARENEG | String |  | Mostrar Renegociados |  |
| VLRCESSAO | Float |  | Vlr. Cessão FDIC |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Últ. Alteração |  |
| DTCONTABBAIXA | DateTime |  | Dt. Contabilização Baixa |  |
| VLRDESCEMBUT | Float |  | Vlr Desc. Embutido |  |
| NUBCO | Integer |  | Nro Único Bancário |  |
| AD_MAXIMA_RECEBE | String |  | Maxima Recebe |  |
| AD_MAXIMA_IDFIN | String |  | Financeiro Máxima |  |
| DTPRAZO | Date |  | Dt. Prazo |  |
| RECEBCARTAO | String |  | Recebim. c/ cartão | `N`=Não `S`=Sim |
| NUVERBA | Integer |  | Nro. Verba |  |
| VLRLANCORIG | Float |  | Valor lançamento |  |
| PIXTEF | Integer |  | Pix TEF |  |
| VLRDESCCALC | Float |  | Vlr. Desconto Calc. |  |
| CODUSUCOBR | Integer |  | CODUSUCOBR |  |
| CODBCO | Integer |  | Banco |  |
| CODCTABCOINT | Integer |  | Conta Bancária |  |
| CODBARRA | String |  | Código de Barras |  |
| CODIGOBARRA | String |  | Cód. Barras Receb. |  |
| TPAGNFCE | String |  | Tipo de pgto para NFC-e | `99`=99-Outros `12`=12-Vale Presente `02`=02-Cheque `01`=01-Dinheiro `13`=13-Vale Combustível_(+13)_ |
| DESDOBRAMENTO | String |  | Desdob. |  |
| DTNEGFILTER | Date |  | Filtro p/ Dt Negociação |  |
| NOSSONUM | String |  | Nosso Número |  |
| NUNOTA | Integer |  | Nro Único Nota |  |
| LINHADIGITAVEL | String |  | Linha Dig. Receb. |  |
| NUMREMESSA | Integer |  | Nro Remessa |  |
| DHTIPOPER | DateTime |  | Dt/Hr Operação |  |
| NUMDUPL | Integer |  | Nro Duplicata |  |
| IDUNICO | Integer |  | Identificador boleto rápido |  |
| MONIOCOREM | String |  | Monitora Ocorrência de Remessa | `S`=Sim `N`=Não |
| ABATIMENTO | Float |  | Abatimento (Cob. Registrada) |  |
| ABATIMENTOCAN | Float |  | Abatimento Cancelado (Cob. Registrada) |  |
| DTCONTAB | DateTime |  | Dt. Contabilização |  |
| EMVPIX | String |  | PIX Copia e Cola |  |
| NUPED | Integer |  | Número Único do Pedido |  |
| NUDEV | Integer |  | Nro Único Devolução |  |
| NUMNFSE | String |  | Nro. NFS-e |  |
| CHAVECTEREF | String |  | Chave CT-e de referência |  |
| NUCCR | Integer |  | Nro do cartão de crédito |  |
| CHAVECTE | String |  | Chave CT-e |  |
| CODCFO | Integer |  | CFOP |  |
| CODLST | Integer |  | Tipo de Serviço |  |
| OBRACONSTCIVIL | Integer |  | Obra de Construção Civil | `2`=2 - Empreitada Parcial `1`=1 - Empreitada Total |
| CODOBRA | String |  | Cód. da Obra |  |
| CODCIDFIMCTE | Integer |  | Cód. Cid. Fim CT-e |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODCIDINICTE | Integer |  | Cód. Cid. Inicio CT-e |  |
| DESCRTPAGNFCE | String |  | Descrição do Tipo de Pagto NFC-e/NF-e/CF-e (Outros) |  |
| NUMOS | Integer |  | Nro da OS |  |
| CODTRIB | Integer |  | Tributação CT-e | `90`=90-Outras `60`=60-ICMS cobrado anteriormente por substituição `51`=51-Diferimento `50`=50-Suspensão `41`=41-Não tributada_(+10)_ |
| CLASSIFCESSAOOBRA | Integer |  | Classificação Cessão M.d.Obra | `100000031`=Trabalho temporário na forma da Lei nº 6.019, de janeiro de 1974 `100000030`=Telefonia ou telemarketing `100000029`=Saúde `100000028`=Secretaria e expediente `100000027`=Promoção de vendas ou de eventos_(+26)_ |
| CODCC | Integer |  | CODCC |  |
| DTENTSAIINFO | Date |  | Data Extemporânea |  |
| DIGSAFRA | String |  | Dígito Safra |  |
| REGESPTRIBUT | String |  | Regime Especial de Tributação DES-BH |  |
| NUAPONTA | Integer |  | Nro Único Apontamento |  |
| BASEIRF | Float |  | Base IRF |  |
| ALIQICMS | Float |  | % ICMS |  |
| BASEINSS | Float |  | Base INSS |  |
| NUMBOR | Integer |  | Nro Borderô |  |
| INSSRETIDO | String |  | INSS Retido | `S`=Sim `N`=Não |
| IRFRETIDO | String |  | IRRF Retido | `N`=Não `S`=Sim |
| ISSRETIDO | String |  | ISS Retido | `S`=Sim `N`=Não |
| VLRINSS | Float |  | Vlr INSS |  |
| VLRIRF | Float |  | Vlr IRF |  |
| ATRASOINICIAL | Integer |  | Atraso 1º Vencto (dias) |  |
| VLRISS | Float |  | Vlr ISS |  |
| PERCDESC | Float |  | Percentual de Desconto |  |
| VLRJUROSMAISMULTA | Float |  | Juros + Multa |  |
| PRAZOINICIAL | Integer |  | Prazo 1º Vencto |  |
| TIMVENDALOTE | Integer |  | Contrato de venda de lote |  |
| VLRCHEQUE | Float |  | Vlr Cheque |  |
| TIPMARCCHEQ | String |  | Tipo Marcação Cheque | `J`=Nominal à empresa `E`=Não nominal `C`=Nominal ao bco. de pgto. `I`=Sem emitir cheque `D`=Agrupar nominal ao bco de pagto_(+6)_ |
| NOMEEMITENTE_CMC7 | String |  | Nome Emitente CMC7 |  |
| CGC_CPF_CMC7 | String |  | CNPJ/CPF CMC7 |  |
| CODBCO_CMC7 | Integer |  | Código Banco CMC7 |  |
| AGENCIA_CMC7 | String |  | Agência CMC7 |  |
| CONTA_CMC7 | String |  | Conta CMC7 |  |
| DESCALINEACHEQDEV | String |  | Alínea Dev. Cheque |  |
| TIMVENDAIMV | Integer |  | Contrato de venda do imóvel |  |
| TIMRENEGIMV | Integer |  | Renegociação da venda do imóvel |  |
| CHEQUERASTREADO_CMC7 | String |  | Cheque rastreado |  |
| NUCHQ | Integer |  | Nro. cheque |  |
| CHAVEPIX | String |  | Chave Pix |  |
| CARTAODESC | Float |  | Taxa Administradora |  |
| SUBTIPOVENDA | Float |  | Subtipo do Tipo de Título |  |
| NUFTC | Integer |  | Nro único da fatura |  |
| AD_BOLETO | String |  | Tem Boleto | `S`=Sim `N`=Não |
| VLRFATCARTAO | Float |  | Vlr. Fatura Cartão |  |
| AD_IDB2W | String |  | IDB2W |  |
| AD_IDMELI | String |  | IDMELI |  |
| CODRECEITA | String |  | Código receita Darf |  |
| DTREFERENCIA | Date |  | Período de referência |  |
| DTINTEGRACAOIPI | Date |  | Data integração |  |
| TAXAVENDAMAIS | Float |  | Taxa Venda Mais |  |
| DHAPROVACAOVENDAMAIS | DateTime |  | Dt. Aprovação |  |
| CODOPERACAOVENDAMAIS | String |  | Código da Operação |  |
| VENDAMAIS | String |  | Venda Mais | `N`=Não `S`=Sim |
| NROLOTEGNRE | Integer |  | Número Lote GNRE |  |
| REJEICAOGNRE | String |  | Motivo Rejeição GNRE |  |
| STATUSGNRE | String |  | Status GNRE |  |
| CHAVENFEGNRE | String |  | Chave de acesso NFe |  |
| TIPAPURACAO | String |  | Tipo Apuração | `T`=ICMS ST FCP `S`=ICMS ST `F`=ICMS FCP `D`=ICMS DIFAL `C`=ICMS_(+2)_ |
| VLRGNREDOIS | Float |  | Vlr GNRE dois |  |
| PRORROGADO | String |  | Prorrogado VM | `N`=Não `S`=Sim |
| NVDTVENC | Date |  | Nova data de vencimento |  |
| CODUSUPROR | Integer |  | Prorrogado por |  |
| PENDENTECRIARDESP | String |  | Prorrogado VM |  |
| DTPROR | DateTime |  | Prorrogado em |  |
| CODPROR | String |  | Cód. Prorrogação VM |  |
| CUSTASPROCESSUAIS | String |  | Custas Processuais? | `S`=Sim `N`=Não |
| DEPOSITOJUDICIAL | String |  | Depósito Judicial? | `S`=Sim `N`=Não |
| RECEBIDO | String |  | Recebido | `S`=Sim `N`=Não |
| DESPADVOGADO | String |  | Desp. com Advogado(s)? | `S`=Sim `N`=Não |
| AD_OUTIMP | Float |  | Impostos (retidos) |  |
| DESPCART | Float |  | Despesas c/ Cartório |  |
| AD_DARFCODRECEITA | String |  | Cód DARF  |  |
| NUMPROCADMJUDIC | String |  | Nº Processo Administrativo/Judicial |  |
| AD_CODEMKT | String |  | Pedido MktPlace |  |
| AD_GPSATUAMONET | Float |  | Atualização Monetária GPS |  |
| AD_GPSCODPAG | String |  | Código da Pagamento GPS |  |
| AD_GPSVLRENTIDADES | Float |  | Valor Outras Entidades GPS |  |
| AD_GPSVLRINSS | Float |  | Valor INSS GPS |  |
| AD_DARFNUMREF | Integer |  | Numero de Referência DARF |  |
| AD_DARFPERIODO | Date |  | Periodo Apuração DARF |  |
| AD_IDENTIFICADORFGTS | String |  | Identificador FGTS |  |
| AD_LACRECONECTSOCIAL | Integer |  | Lacre Conectividade Social |  |
| EXIGEISSQN | String |  | Exigibilidade do ISSQN DES-BH |  |
| AD_DLACRECONECTSOCIAL | Integer |  | Dígito Lacre Conect. Social |  |
| MODELONFDES | String |  | Modelo NF DES-BH |  |
| AD_GARECODRECEITA | String |  | Código da Receita GARE |  |
| NATUREZAOPERDES | String |  | Natureza Oper. DES-BH | `Q`=Q-Não Tributável `N`=N-Turismo/Fundos `M`=M-Inscrito na PBH `L`=L-Incentivo a Cultura `K`=K-Depósito em Juízo_(+12)_ |
| AD_GAREDIVATIV | Integer |  | Dívida Ativa / Nro Etiqueta GARE |  |
| SERIENFDES | String |  | Série NF DES-BH |  |
| AD_GAREPARCELA | Integer |  | Parcela (Gare) |  |
| MOTNAORETERISSQN | String |  | Motivo de não Retenção ISSQN DES-BH |  |
| AD_GARERECEITA | Float |  | Receita (GARE) |  |
| AD_GAREREFERENCIA | String |  | Referência (MM/AAAA) GARE |  |
| SITESPECIALRESP | String |  | Situação Especial de Responsabilidade DES-BH |  |
| AD_FGTSCODRECOLHIMENTO | String |  | Código de Recolhimento do FGTS |  |
| DTVENCINIC | DateTime |  | Dt. Venc. Inicial |  |
| TIMDHGERREPPARCIAL | DateTime |  | Dh. Ger. Rep. Parcial |  |
| TIMBLOQUEADA | String |  | Bloqueada | `S`=Sim `N`=Não |
| TIMVLRCORRMONET | Float |  | Vlr. Corr. Monetária |  |
| TIMVLRJUROCONTRATO | Float |  | Vlr. Juro Contrato |  |
| CODIPTU | Integer |  | Conta IPTU |  |
| TIMVLRALUGUEL | Float |  | Vlr. Aluguel |  |
| TIMVLRAMORTCONTRATO | Float |  | Vlr. Amortização Contrato |  |
| TIMDTIMPBOLLOCAL | DateTime |  | Dh. Imp. Local Boleto |  |
| TIMDTREPPARCIAL | Date |  | Dt. Repasse Parcial |  |
| TIMTIPOINTERMED | Integer |  | Tipo de Intermediária |  |
| TIMCONTALANC | Integer |  | Conta Lançamento |  |
| TIMESTAGIO | String |  | Estágio | `Jurídico`=Jurídico `Baixado`=Baixado `Atrasado`=Atrasado `Aberto`=Aberto |
| TIMTXADMGERALU | String |  | Tx Adm pela Parcela | `S`=Sim `N`=Não |
| TIMREPPARCIAL | String |  | Repasse Parcial | `S`=Sim `N`=Não |
| TIMFINGARANTORIG | Integer |  | Fin. Resp. Garantia |  |
| TIMREPINTELIGENTE | Integer |  | Usuário Rep. Inteligente |  |
| TIMRESCISAOLOC | Integer |  | Rescisão de Locação |  |
| TIMORIGEM | String |  | Tipo Parcela | `RP`=Repasse `RB`=Repasse ao Beneficiário `PP`=FPP `PI`=Intermediária `PD`=Diferenciada_(+30)_ |
| TIMDHGERREPASSE | DateTime |  | Dh. Ger. Repasse |  |
| TIMORIGRENEG | String |  | Repactuação | `S`=Sim `N`=Não |
| TIMDATADEJUR | DateTime |  | Dt. Ida Jurídico |  |
| TIMPARCELA | Integer |  | Parcela |  |
| TIMCONTRATOLOC | Integer |  | Contrato de Locação |  |
| TIMCONTRATOLTV | Integer |  | Contrato de Venda Lotes |  |
| TIMNEGOCIACAO | Integer |  | Negociação |  |
| TIMRENEGLOTE | Integer |  | Renegociação Contrato |  |
| TIMNUFINORIG | Integer |  | Financeiro Origem |  |
| TIMIMOVEL | Integer |  | Imóvel |  |
| TIMCONTRATOADM | Integer |  | Contrato Adm. |  |
| TIMDHBAIXA | DateTime |  | Dt. Pagamento |  |
| TIMDTREPASSE | Date |  | Dt. Repasse |  |
| TIMSAC | Integer |  | Atendimento ao cliente (OS) |  |
| TIMFECHAMENTO | Integer |  | Fechamento Cond. |  |
| TIMFECHAMENTOALU | Integer |  | Fechamento Aluguel Perc. |  |
| TIMCONTAREP | Integer |  | Conta rep. prop. |  |
| TIMDTIMPBOL | DateTime |  | Dt. Impressão Boleto |  |
| TIMNOMEADVOGADO | String |  | Advogado |  |
| TIMNUMREG | Integer |  | Sequência Banco |  |
| TIMRENEGCANCLOTE | Integer |  | Renegociado Por |  |
| TIMRESCISAOLTV | Integer |  | Rescisão de Contrato |  |
| BAIXAAPI | String |  | Baixa via API |  |
| NROIMPORT | Integer |  | Nro da importação |  |
| NFCOMPLFIX | Integer |  | Nf. Complemento Fixação |  |
| NFENTSEQFIX | String |  | Nf. Entrada Fixação/Sequência |  |
| NUMENTSAFFIX | Integer |  | Nro Nota Entrada Fixação |  |
| SERIEENTSAFFIX | String |  | Série Entrada Fixação |  |
| NUMCOMPLFIX | Integer |  | Nro Nota Complemento Fixação |  |
| SERIENOTACOMPL | String |  | Série Complemento Fixação |  |
| TROCOPDV | Float |  | Vlr Troco |  |
| AD_DTPAGAMENTO | Date |  | Dt. Pagamento (EDI Pag) |  |
| NUMDOCARRECAD | String |  | Nro Documento de arrecadação |  |
| DH_IMPRESSAO | Date |  | Data Impressão |  |
| AD_DDACNPJ | String |  | DDA CNPJ |  |
| AD_DDARAZAOSOCIAL | String |  | DDA RAZAOSOCIAL |  |
| AD_NUNOTA | Integer |  | Nr. Unico Notas |  |
| AD_QTDPARCELAS | Integer |  | Qtd de Parcelas |  |
| VLRICMSXMLCTE | Float |  | Vlr ICMS_XML |  |
| AD_CRIADOPELACONCILIACAO | String |  | Criado Pela Conciliação | `S`=Sim `N`=Não |
| AD_LIBERADOVAN | String |  | Liberado VAN | `S`=Sim `N`=Não |
| AD_NUNOTAORIG | Integer |  | Nr Unico Original |  |
| AD_DATAVENCIMENTO | Date |  | datavencimento |  |
| AD_LOGTI | String |  | Log TI |  |
| AD_TELEVENDASNSU | String |  | NSU (Televendas) |  |
| AD_TELEVENDASTID | String |  | TID (Televendas) |  |
| AD_TELEVENDASAUTORIZACAO | String |  | AUT (Televendas) |  |
| AD_PEDIDOKONCILI | String |  | Pedido Koncili |  |
| AD_DTCONFIRMACAONOTA | DateTime |  | Data de Confimacção NF |  |
| AD_NRAUTORIZACAOZANTHUS | String |  | NR de Autorização do Cartão Zanthus |  |
| AD_NRPIXZANTHUS | String |  | Numero de Autorização Pix Zanthus |  |
| AD_NSUZANTHUS | String |  | Nr de NSU do Cartão Zanthus |  |
| AD_DTPREVENT | DateTime |  | Data de previsão de entrega |  |
| AD_STATUSTRANSP | String |  | Último status transportadora |  |
| AD_DTSTATUSINTELIP | DateTime |  | Data do último status transportadora |  |
| AD_STATUSDOOTAX | String |  | Status Dootax | `P`=Pendente envio `E`=Enviado `PR`=Processado `PG`=Pago |
| AD_TID | String |  | TID |  |
| NUFIN | Integer |  | Nro Único |  |
| METODOCALCIRRF | String |  | Método de Cálculo IRRF | `S`=Por Desconto Simplificado `L`=Por Deduções Legais |
| NUMOCORRENCIAS | String |  | Nr. da Ocorrência Caixa |  |
| NUCAIXA | Integer |  | Núm. Caixa |  |

## TGFFINVM — Financeiro Venda Mais
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Número único Nota |  |
| NOSSONUM | String |  | Nosso Número |  |
| RECDESP | Integer |  | Receita/Despesa |  |
| NUFIN | Integer |  | Nro Único |  |

## TGFFINVMOCOR — Ocorrência Financeira
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUFIN | Integer |  | Financeiro |  |
| DTOCOR | DateTime |  | Data Ocorrência |  |
| OCORRENCIA | String |  | Descrição da ocorrência |  |
| TICKETNUMBER | String |  | Número Ticket |  |

## TGFFIN_EXC — TGFFIN_EXC
Campos: 70

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| CODTIPOPERBAIXA | Integer |  | Cód.Tipo Operação baixa |  |
| CODTIPTIT | Integer |  | Tipo de título |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODUSUBAIXA | Integer |  | Cód. Usuário Baixa |  |
| CODVEND | Integer |  | Vendedor |  |
| DESDOBDUPL | String |  | Desdobramento duplicata |  |
| DESDOBRAMENTO | String |  | Desdobramento |  |
| DESPCART | Float |  | Despesas com cartório |  |
| DHBAIXA | DateTime |  | Data e hora da baixa |  |
| DHEXCLUSAO | DateTime |  | Data Hora Exclusão |  |
| DHMOV | DateTime |  | Data e hora do movimento |  |
| DHTIPOPER | DateTime |  | Data e hora operação |  |
| DHTIPOPERBAIXA | DateTime |  | Data e hora operação baixa |  |
| DTCONTAB | DateTime |  | Data de Contabilização |  |
| DTCONTABBAIXA | DateTime |  | Data da Contabilização da Baixa |  |
| DTENTSAI | DateTime |  | Data de Entrada e Saída da Nota |  |
| DTNEG | DateTime |  | Data da negociação |  |
| ALIQICMS | Float |  | Alíquota ICMS |  |
| AUTORIZADO | String |  | Autorizado |  |
| BASEICMS | Float |  | Base ICMS |  |
| CARTA | Integer |  | Carta |  |
| CARTAODESC | Float |  | Valor do desconto da administradora de cartões |  |
| CODBARRA | String |  | Código de barras |  |
| CODBCO | Integer |  | Banco cobrança |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODCTABCOINT | Integer |  | Conta Bancária |  |
| CODEMP | Integer |  | Empresa |  |
| DTVENC | DateTime |  | Data do vencimento |  |
| DTVENCINIC | DateTime |  | Data vencimento inicial |  |
| HISTORICO | String |  | Histórico |  |
| HOSTNAME | String |  | HOSTNAME |  |
| INSSRETIDO | String |  | INSS Retido |  |
| IRFRETIDO | String |  | IRF Retido |  |
| ISSRETIDO | String |  | ISS Retido |  |
| NOSSONUM | String |  | Nosso número |  |
| NT_USERNAME | String |  | NT_USERNAME |  |
| NUBCO | Integer |  | Número único bancário |  |
| NUDEV | Integer |  | Número único devolução |  |
| NUFIN | Integer |  | Número único Financeiro |  |
| NUMDUPL | Integer |  | Número da duplicata |  |
| NUMNOTA | Integer |  | Número da nota |  |
| NUMREMESSA | Integer |  | Número da remessa |  |
| NUNOTA | Integer |  | Número único Nota |  |
| NURENEG | Integer |  | Número da Renegociação |  |
| ORIGEM | String |  | Origem |  |
| PROVISAO | String |  | Provisão |  |
| CODEMPBAIXA | Integer |  | Empresa da baixa |  |
| CODMOEDA | Integer |  | Moeda |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODPROJ | Integer |  | Projeto |  |
| RATEADO | String |  | Rateado |  |
| RECDESP | Integer |  | Receita ou Despesa |  |
| SERIENOTA | String |  | Série da nota |  |
| TIPJURO | String |  | Tipo de juro |  |
| TIPMARCCHEQ | String |  | Tipo marcação cheque |  |
| TIPMULTA | String |  | Tipo de multa |  |
| USUARIO | String |  | Usuário |  |
| VLRBAIXA | Float |  | Valor da baixa |  |
| VLRCHEQUE | Float |  | Valor do Cheque |  |
| VLRDESC | Float |  | Valor do desconto |  |
| VLRDESDOB | Float |  | Valor do desdobramento |  |
| VLRINSS | Float |  | Valor do INSS |  |
| VLRIRF | Float |  | Valor do IRF |  |
| VLRISS | Float |  | Valor do ISS |  |
| VLRJURO | Float |  | Valor do juro |  |
| VLRMULTA | Float |  | Valor da multa |  |
| VLRPROV | Float |  | Valor da Provisão Financeira |  |
| VLRVENDOR | Float |  | Valor do vendor |  |

## TGFNAT — Natureza de Receitas e Despesas
Campos: 30

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRNAT | String |  | Descrição |  |
| ATIVA | String |  | Ativa | `N`=Não `S`=Sim |
| ANALITICA | String |  | Analítica | `S`=Sim `N`=Não |
| INCRESULT | String |  | Incide no resultado | `N`=Não `S`=Sim |
| CODCTACTB | Integer |  | Conta contábil |  |
| CODCTACTB2 | Integer |  | Conta contábil 2 |  |
| CODHISTCTB | Integer |  | Cód. Histórico 1 |  |
| CODHISTCTB2 | Integer |  | Cód. Histórico 2 |  |
| GRUPOMKP | String |  | Grupo MKP |  |
| SUBGRUPOMKP | String |  | Sub Grupo MKP |  |
| DECVLR | Integer |  | Decimal para Valor |  |
| GRAU | Integer |  | Grau |  |
| CODNATPAI | Integer |  | Cód. Natureza Pai |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| FORMULA | String |  | Fórmula |  |
| CODSERVUNICO | Integer |  | Serviço único faturamento |  |
| CODGRUPONAT | Integer |  | Grupo da Natureza |  |
| TIPNAT | String |  | Tipo de natureza | `D`=Despesa `R`=Receita |
| CSTPIS | Integer |  | Cód. Sit. Tribut. PIS | `51`=51-Operação com Direito a Crédito - Vinc. Exclus. Receita Não-Tributada Mercado Interno `50`=50-Operação com Direito a Crédito - Vinc. Exclus. Receita Tributada Mercado Interno `49`=49-Outras Operações de Saída `09`=09-Operação com Suspensão da Contribuição `08`=08-Operação sem Incidência da Contribuição_(+28)_ |
| ALIQPIS | Float |  | Alíquota de PIS |  |
| CODCTACTBEFD | Integer |  | Conta Contábil para EFD |  |
| CSTCOFINS | Integer |  | Cód. Sit. Tribut. COFINS | `50`=50-Operação com Direito a Crédito - Vinc. Exclus. Receita Tributada Mercado Interno `49`=49-Outras Operações de Saída `09`=09-Operação com Suspensão da Contribuição `08`=08-Operação sem Incidência da Contribuição `07`=07-Operação Isenta da Contribuição_(+28)_ |
| AD_MAXIMA | String |  | Integra com a Máxima? | `S`=Sim `N`=Não |
| ALIQCOFINS | Float |  | Alíquota de COFINS |  |
| NATBCCRED | String |  | Natureza da Base de Cálculo do Crédito de PIS/COFINS | `16`=16-Atividade Imobiliária - Custo Orçado de unidade não concluída `15`=15-Atividade Imobiliária - Custo Incorrido de Unidade Imobiliária `14`=14-Atividade de Transporte de Cargas - Subcontratação `13`=13-Outras Operações com Direito a Crédito `12`=12-Devolução de Vendas Sujeitas à Incidência Não-Cumulativa_(+13)_ |
| REGIMEEFD | String |  | Regime (EFD PIS/COFINS) | `B`=Regime de Competência (Dt.Negociação) `C`=Regime de Competência (Dt.Entrada/Saída) `A`=Regime de Caixa |
| GERALCDPR | String |  | Gera informações para o Livro Caixa Digital Produtor Rural | `S`=Sim `N`=Não |
| NATEFDCONTM410M810 | Integer |  | Cod. Natureza (PIS/COFINS M410/M810) |  |
| RECADIANTRURAL | String |  | Receita de Adiantamentos para o Livro Caixa Digital Produtor Rural | `N`=Não `S`=Sim |
| CODNAT | Integer |  | Cód. Natureza |  |

## TGFNATPC — Relação de natureza e PIS/COFINS
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNAT | Integer |  | Cód. Natureza |  |
| DTINIVALIDADE | Date |  | Data Início Validade |  |
| DTFIMVALIDADE | Date |  | Data Fim Validade |  |
| CSTPIS | Integer |  | Cód. Sit. Tribut. PIS | `99`=99-Outras Operações `66`=66-Créd. Presumido-Oper.Aquis.Vinc.Receitas Tributadas e Não-Tribut. no Mercado Int. e de Exportação `65`=65-Crédito Presumido - Oper. Aquis. Vinc. Receitas Não-Tributadas no Mercado Interno e de Exportação `64`=64-Crédito Presumido - Oper. Aquis. Vinc. Receitas Tributadas no Mercado Interno e de Exportação `63`=63-Crédito Presumido - Oper. Aquis. Vinc. Receitas Tributadas e Não-Tributadas no Mercado Interno_(+28)_ |
| CSTCOFINS | Integer |  | Cód. Sit. Tribut. COFINS | `53`=53-Operação com Direito a Crédito - Vinc. Receitas Tributadas e Não-Tributadas no Mercado Interno `52`=52-Operação com Direito a Crédito - Vinc. Exclus. a Receita de Exportação `51`=51-Operação com Direito a Crédito - Vinc. Exclus. Receita Não-Tributada Mercado Interno `50`=50-Operação com Direito a Crédito - Vinc. Exclus. Receita Tributada Mercado Interno `49`=49-Outras Operações de Saída_(+28)_ |
| ALIQPIS | Float |  | Alíquota de PIS |  |
| ALIQCOFINS | Float |  | Alíquota de COFINS |  |
| NATBCCRED | String |  | Natureza da Base de Cálculo do Crédito de PIS/COFINS | `18`=18-Estoque de Abertura de Bens `17`=17-Atividade Prest. Serv. de Limp., Conserv. e Manut. - V.T., V.R. ou V.A., fardamento ou uniforme `16`=16-Atividade Imobiliária - Custo Orçado de unidade não concluída `15`=15-Atividade Imobiliária - Custo Incorrido de Unidade Imobiliária `14`=14-Atividade de Transporte de Cargas - Subcontratação_(+13)_ |
| REGIMEEFD | String |  | Regime (EFD PIS/COFINS) | `C`=Regime de Competência (Dt.Entrada/Saída) `B`=Regime de Competência (Dt.Negociação) `A`=Regime de Caixa |
| CODUSU | Integer |  | Usuário |  |
| DHALTER | DateTime |  | Dh. Alteração |  |
| NUNATPISCOF | Integer |  | Nro Único |  |

## TGFNATPCEMP — Relação de PIS/COFINS e empresa
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODUSU | Integer |  | Usuário |  |
| DHALTER | DateTime |  | Dh. Alteração |  |
| NUNATPISCOF | Integer |  | Nro Único |  |

## TGFRAT — Rateio por Natureza de Receita e Despesa
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCTACTB | Integer |  | Conta Contábil |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODSITE | Integer |  | Site |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| NUFIN | Integer |  | Num. Financeiro |  |
| NUMCONTRATO | Integer |  | Num. Contrato |  |
| ORIGEM | String |  | Origem | `F`=Financeiro `E`=Estoque `P`=Pessoal |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | DTALTER |  |
| PERCRATEIO | Float |  | % Rateio |  |