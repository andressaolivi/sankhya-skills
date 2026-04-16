# TCS — CRM / Pré-vendas

> Gerado do dicionário oficial TDD Sankhya. 125 tabelas.


## TCSAFO — Autorizações de Faturamento de OS
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | NUMITEM |  |
| AUTORIZADO | String |  | Autorizado |  |
| NUMOTIVO | Integer |  | Motivo de Não Autorização |  |
| CODUSUAUT | Integer |  | Cód.Usuário Autorização |  |
| DHALTER | DateTime |  | Data da autorização |  |
| NUMOS | Integer |  | NUMOS |  |

## TCSAGE — VIEW TCSAGE
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID_A | Integer |  | Identificador B |  |
| TIPOOS | String |  | Tipo OS |  |
| ID_B | Integer |  | Identificador A |  |
| DHPREVISTA | DateTime |  | Data Prevista |  |
| DHPREVISTA_FIM | DateTime |  | Previsão de Término |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| RESPONSAVEL | Integer |  | Responsável |  |
| EXECUTANTE | Integer |  | Executante |  |
| ATENDENTE | Integer |  | Atendente |  |
| NUFAP | Integer |  | Número de Projeto (FAP) |  |
| CODSERV | Integer |  | Serviço |  |
| DESCRICAO | String |  | Descrição |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| NUMETAPA | Integer |  | Número da etapa do projeto |  |
| SITUACAO | String |  | Situação |  |
| STATUS | Integer |  | Status |  |
| ITETEMPOGASTO | Integer |  | Tempo Gasto Item |  |
| NUMCONTRATO | Integer |  | Num Contrato |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| DTPREVFECHAMENTO | DateTime |  | Dt. Previsão Fechamento |  |
| TIPO | String |  | Tipo |  |

## TCSAGF — Agenda Fixa
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| DIASEM | Integer |  | Dia da Senama |  |
| HORARIO | DateTime |  | Horário Marcado |  |
| TIPOPER | String |  | Tipo da Operação |  |
| OBSERVACOES | String |  | Observações |  |
| CODVEND | Integer |  | Vendedor |  |

## TCSALE — Alertas
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUFAP | Integer |  | Número da FAP |  |
| NUMETAPA | Integer |  | Número da Etapa |  |
| CODTIPACAO | Integer |  | Tipo Ação |  |
| DESCRALE | String |  | Descrição do Alerta |  |
| TIPVALOR | String |  | Tipo de valor |  |
| OPERADOR | String |  | Operador |  |
| VALOR | Integer |  | Valor |  |
| TIQUEM | String |  | Quem |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| QUEM | String |  | Quem |  |
| NUALE | Integer |  | Número do Alerta |  |

## TCSALT — Controle de Alterações nos bancos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSCRIPT | Integer |  | Script |  |
| DHALTER | DateTime |  | Data da Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| STATUS | String |  | Status da Alteração |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TCSAOS — Layout App Ordem de Serviço
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECAMPO | String |  | Campo |  |
| DESCRCAMPO | String |  | Descrição |  |
| VLRDEFAULT | String |  | Valor padrão |  |
| USAULTIMOVLR | String |  | Salvar último valor | `N`=Não `S`=Sim |
| APRESLANC | String |  | Apresentar no lançamento de nova OS | `S`=Sim `N`=Não |
| VISIVEL | String |  | Apresentar na edição de OS | `N`=Não `S`=Sim |
| READONLY | String |  | Somente leitura | `N`=Não `S`=Sim |
| NOMETAB | String |  | Tabela |  |
| NUCAMPO | Integer |  | Nro. Campo |  |
| TIPOAPRES | String |  | Tipo de apresentação |  |
| ENTIDADEESTRANG | String |  | Ligação com cadastro |  |
| EXPRESSAOTABESTRANG | String |  | Filtro para importação do cadastro |  |
| ORDEM | Integer |  | Ordem |  |

## TCSAUT — Autorizações
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| DHAUTOR | DateTime |  | Data e hora da Autorização |  |
| AUTORIZADO | String |  | Autorizado |  |
| NUFIN | Integer |  | Número do Financeiro |  |

## TCSCCF — Comissão Faturamento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMCONTRATO | Integer |  | NUMCONTRATO |  |
| CODPROD | Integer |  | CODPROD |  |
| CODVEND | Integer |  | CODVEND |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUNOTA | Integer |  | NUNOTA |  |

## TCSCGR — Comercial Grupo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GRUPO | Integer |  | Grupo |  |
| NUMCONTRATO | Integer |  | Contrato |  |
| QTDPARC | Integer |  | Quantidade de parceiros |  |

## TCSCNV — Comissão de Negociação
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCOMISSAO | Integer |  | Núm. Comissão |  |
| CODNAT | Integer |  | Natureza |  |
| COMISSAO | Float |  | Comissão (%) |  |
| CODUSUALTER | Integer |  | Usuário Alteração |  |
| DHALTER | DateTime |  | Data Alteração |  |
| NUMOS | Integer |  | Núm. OS |  |
| VLRBASE | Float |  | Vlr Base |  |
| VLRTOTCOMISSAO | Float |  | Total Comissão |  |
| CODVEND | Integer |  | Vendedor |  |
| GRIDMULT | Integer |  | Multiplicador |  |

## TCSCOM — Comissões
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| PERCCOM | Float |  | Percentual de Comissão |  |
| VLRCOMISSAO | Float |  | Valor da Comissão |  |
| NUMCONTRATO | Integer |  | Número do Contrato |  |

## TCSCON — Contratos
Campos: 158

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CONTCOMPLETO | Integer |  | Instalações até o Período |  |
| PERCTOLEXCED | Float |  | % Tolerância Excedente |  |
| QTDNEG | Float |  | Quantidade Negociada |  |
| TOTNEG | Float |  | Valor Total Negociado |  |
| VALNEGSC | Float |  | Valor Negociado/SC |  |
| NUMCSTC | Integer |  | Característica de Serviço de Tele/Comunicação |  |
| DTREFULTFAT | Date |  | Referência último faturamento |  |
| ENDERECO | String |  | Endereço |  |
| INSCEST | String |  | Inscrição Estadual |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| QTDGERARPREV | Integer |  | Qtd. Provisões a Gerar |  |
| CODSAF | Integer |  | Safra |  |
| VLRFINPEND | Float |  | Valor Pend. Fin. |  |
| SITCONT | String |  | Situação do contrato | `F`=Finalizado `C`=Cancelado `A`=Ativo |
| QTDFINPEND | Integer |  | Qtd. Fin. Pendentes |  |
| DEFTIPA | String |  | Tipo de Armazenador | `D`=Depositante `C`=Comprador |
| MODALIDADE | String |  | Modalidade do Contrato | `A`=Armazenagem `C`=Comercialização |
| PARCELAFAT | Integer |  | Parcela Fat. |  |
| DTVENCTO | Date |  | Data Vencimento |  |
| QTDPREV | Integer |  | Qtd. Provisões |  |
| REFERENCIA | String |  | Referência |  |
| VLRTOTAL | Float |  | Valor Total |  |
| PADCLASS | Integer |  | Padrão de Classificação |  |
| REGLAUDSAIDA | String |  | Regra p/ Laudo nas Saídas | `D`=Vincula e desconta `N`=Não vincula `V`=Vincula e não desconta |
| CONTDESINSTAL | Integer |  | Desinstalações no Período |  |
| CODNATEX | Integer |  | Natureza |  |
| CONTINSTAL | Integer |  | Instalações no Período |  |
| NUMCONTRATO | Integer |  | Número do contrato |  |
| VALOR | Float |  | Valor |  |
| VLRORIGINAL | Float |  | Valor original |  |
| VLRSERVICOS | Float |  | Valor dos serviços |  |
| AMBIENTE | String |  | Ambiente |  |
| UNICONVSC | Float |  | Unidade de Conversão p/ SC |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| VALPEDFIN | String |  | Valida pendência financeira x estoque disponível | `S`=Sim `N`=Não |
| DTCONTRATO | Date |  | Data do contrato |  |
| TIPQUEBRA | String |  | Tipo de Quebra | `T`=Quebra Técnica `M`=Quebra de Massa `B`=Quebra de Transbordo `I`=Isento |
| DTFINENTREGA | Date |  | Data Final da Entrega |  |
| DTINIENTREGA | Date |  | Data Início da Entrega |  |
| CODPARC | Integer |  | Parceiro |  |
| NUMCONTIN | String |  | Contrato Interno |  |
| QUEBRATEC | Float |  | % Quebra Técnica |  |
| QTDEPREVISTA | Float |  | Qtd. Prevista |  |
| CODEMP | Integer |  | Empresa |  |
| UMIDPADRA | Float |  | % Umidade Padrão Quebra de Massa |  |
| NUNOTAREFARMAZE | Integer |  | % Ultima nota Armazenagem |  |
| NUNOTAREFEXPREC | Integer |  | % Ultima nota Expedição |  |
| NUNOTA | Integer |  | Pedido de Captação |  |
| CODCLC | Integer |  | Característica Analisável |  |
| CODCONTATO | Integer |  | Contato |  |
| DIACARENCEX | Integer |  | Tipo de Apuração por Percentual | `1`=Serviço `0`=Estoque |
| EQUIPAMENTO | String |  | Equipamento |  |
| PERDESCON | String |  | Periodicidade de Desconto |  |
| NUMCONTRATOORIGEM | Integer |  | Aditivo de |  |
| CODSERVEX | Integer |  | Serviço |  |
| CODMOEDA | Integer |  | Moeda |  |
| TIPCOBR | String |  | Tipo de Cobrança | `V`=Por valor `P`=Percentual `I`=Isento |
| PPAUTASC | Integer |  | Preço de Pauta/SC |  |
| CODMOEALTREAJ | Integer |  | Moeda alternativa para reajuste |  |
| TABPRECUMI | Integer |  | Tabela de Preços por Umidade |  |
| TABPRECUMIAR | Integer |  | Tabela de Preços por Umidade |  |
| CODNAT | Integer |  | Natureza |  |
| PERDESC | String |  | Periodicidade de Desconto | `Q`=Quinzenal `M`=Mensal `D`=Diária `F`=Final do Contrato |
| TIPISENCAO | String |  | Tipo de Isenção | `P`=Por períodos `D`=Por dias |
| CODCENCUS | Integer |  | Centro Resultado |  |
| DIACARENC | Integer |  | Prazo de Carência |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUSEX | Integer |  | Centro Resultado |  |
| TIPOTITULO | Integer |  | Tipo de título |  |
| CODCRITERIO | Integer |  | Critério de Rateio |  |
| TIPOTITULOEX | Integer |  | Tipo de título |  |
| CODTIPVENDA | Integer |  | Tipo negociação |  |
| CODTIPVENDAEX | Integer |  | Tipo negociação |  |
| DTBASEREAJ | Date |  | Data base reajuste |  |
| DTTERMINO | Date |  | Data de término |  |
| FREQREAJ | Integer |  | Frequência reajuste |  |
| DIAPAG | Integer |  | Dia do pagamento |  |
| PRAZOVENCTO | Integer |  | Prazo de vencimento |  |
| CODPROJSINT | Integer |  | Projeto sintético |  |
| IMPRPRECINDIV | String |  | Imprime preço individualizado | `S`=Sim `N`=Não |
| GERARNF | String |  | Gerar NF | `S`=Sim `N`=Não |
| IMPRIME | String |  | Imprime | `N`=Não `S`=Sim |
| DIAUTIL | String |  | Considera dia do pagamento como dia útil | `N`=Não `S`=Sim |
| ACESSAHISTSUBOS | String |  | Visualizar histórico na consulta Web | `N`=Não `S`=Sim |
| TEMMED | String |  | Tem medição | `N`=Não `S`=Sim |
| DIAFIMMED | Integer |  | Dia final p/ medição |  |
| REAJUSTENEGATIVO | String |  | Aceita reajuste com índice negativo | `S`=Sim `N`=Não |
| TIPPAG | String |  | Tipo de Pagamento | `C`=Mês corrente `A`=Antecipado `V`=Vencido |
| RECDESP | Integer |  | Tipo de Financeiro | `-1`=Despesa `1`=Receita `0`=Renegociado |
| TIPOCONTRATO | String |  | Tipo contrato | `S`=Exclusivo `N`=Não Exclusivo |
| TIPOARM | String |  | TIPOARM |  |
| TIPO | String |  | Periodicidade do Faturamento | `L`=Livre `M`=Mensal `S`=Semestral `Q`=Quadrimestral `B`=Bimestral_(+2)_ |
| DTREFPROXFAT | Date |  | Referência próximo faturamento |  |
| PARCELAATUAL | Integer |  | Parcela atual |  |
| PARCELAQTD | Integer |  | Qtd. parcelas |  |
| DTENVIOEMAIL | Date |  | Data envio email |  |
| CODIMPLANT | Integer |  | Responsável Técnico da Contratante |  |
| CODUSU | Integer |  | Usuário Inclusão |  |
| CODMONSANKHYA | Integer |  | Gerente do Contrato |  |
| CODUSUALTER | Integer |  | Usuário Última Alteração |  |
| FREQVISITAS | Integer |  | Intervalo entre visitas |  |
| DURACAO | Text |  | Duração da visita (horas e minutos) |  |
| TOTALFATURADO | Integer |  | Total faturado |  |
| OBSERVACOES | String |  | Observações |  |
| TOTALCONTRATO | Integer |  | Total do contrato |  |
| TOTALPROVPENDENTE | Integer |  | Total prov. pendente |  |
| GATILHO | Integer |  | Gatilho |  |
| CLAUSCONTRATO | String |  | Cláusulas do Contrato |  |
| CODPARCSEC | Integer |  | Parceiro atendido |  |
| NUSLA | Integer |  | SLA |  |
| CODPARCPREST | Integer |  | Parceiro prest. serviço |  |
| FERIADOMUN | String |  | Feriado municipal | `E`=Considerar na Contratante `A`=Considerar em ambos `O`=Considerar no Contratado `N`=Não considerar |
| FERIADOEST | String |  | Feriado estadual | `O`=Considerar no Contratado `N`=Não considerar `E`=Considerar na Contratante `A`=Considerar em ambos |
| FERIADONAC | String |  | Feriado nacional | `A`=Considerar em ambos `O`=Considerar no Contratado `E`=Considerar na Contratante `N`=Não considerar |
| LOCACAOBEM | String |  | Contrato de locação de bens | `N`=Não `S`=Sim |
| TEMISS | String |  | Calcular ISS | `S`=Sim `N`=Não |
| RETEMISS | String |  | Retém ISS | `S`=Sim `N`=Não |
| PERCISS | Float |  | % ISS |  |
| TEMIRF | String |  | Calcular IRF | `S`=Sim `N`=Não |
| FATURPRORATA | String |  | Faturamento pro rata? | `S`=Sim `N`=Não |
| PERCIRF | Float |  | % IRF |  |
| CONTRORGPUBLICO | String |  | Contrato de órgão público | `S`=Sim `N`=Não |
| PERCLOC | Float |  | Perc. Locação |  |
| CONTROLOCBENS | String |  | Contrato de locação de bens | `N`=Não `S`=Sim |
| GRUPOFATURPRORATA | String |  | Grupo de Faturamento |  |
| QTDPROVISAO | Integer |  | Qtd. Provisão |  |
| SERFATURCON | String |  | Série para faturamento em contratos |  |
| GERARFINNOTA | String |  | Gerar Financeiro da nota como | `R`=Real `P`=Provisão |
| NUNOTAPEDLOC | Integer |  | Número Pedido |  |
| TOPFATURCON | Integer |  | TOP para faturamento em contratos |  |
| QTDPARCPGCOM | Integer |  | Qtd parcelas p/ pagto de comissão |  |
| CODCID | Integer |  | Cidade de Execução do Serviço |  |
| COBPROPORCAR | String |  | Tipo de Cobrança | `S`=Sobre o Saldo `E`=Sobre a Entrada `I`=Isento |
| CODCENCUSAR | Integer |  | Centro Resultado |  |
| CODNATAR | Integer |  | Natureza |  |
| CODTIPVENDAAR | Integer |  | Tipo negociação |  |
| DIACARECAR | Integer |  | Períodos de Carência |  |
| PERCOBRAAR | String |  | Periodicidade de Cobrança | `Q`=Quinzenal `M`=Mensal `F`=Final do Contrato |
| RESPPAGAR | Integer |  | Responsável pelo Pagamento |  |
| TIPOTITULOAR | Integer |  | Tipo de título |  |
| ULTTABUMI | String |  | Utilizar tabela de preços por umidade? | `S`=Sim `N`=Não |
| DTREFARMAZE | Date |  | Data Referência Faturamento |  |
| DTREFEXPREC | Date |  | Data Referência Faturamento |  |
| FORMFATARMAZE | String |  | Apurar por peso líquido | `S`=Sim `N`=Não |
| FORMFATEXPREC | String |  | Apurar por peso líquido | `S`=Sim `N`=Não |
| VALQUEBTRANS | Float |  | % Quebra Transbordo |  |
| COBPROQUE | String |  | Cobrar Proporcional | `S`=Sim `N`=Não |
| EXIGEPEDIDOPES | String |  | Exige Pedido na Pesagem | `N`=Não `S`=Sim |
| TIPCON | String |  | Tipo de Contrato | `B`=Compra a Fixar `C`=Compra Fixada `V`=Venda Fixada |
| GRUPO | String |  | Grupo |  |
| CODOBS | Integer |  | Observação padrão |  |
| DIAFIXO | String |  | Dia Fixo para vencimento | `S`=Sim `N`=Não |
| PRAZOMENSAL | Integer |  | Prazo Mensal para Pagamento |  |
| CIF_FOB | String |  | CIF / FOB | `S`=Sem Frete `R`=Transp. Próprio Remetente `D`=Transp. Próprio Destinatário `C`=CIF `F`=FOB_(+1)_ |
| COLORFATFORASEQ | String |  | Colorir Faturamento Fora da Sequencia |  |
| PERCOBRA | String |  | Periodicidade de Cobrança | `Q`=Quinzenal `M`=Mensal `F`=Final do Contrato |
| TEMCRIRATESP | String |  | Possui critério de rateio específico |  |

## TCSCOS — Classificação de OS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| SUSPENDERSLA | String |  | Suspender SLA | `N`=Não `S`=Sim |
| FECHARSLA | String |  | Fechar SLA | `S`=Sim `N`=Não |
| CODCOS | Integer |  | Código |  |

## TCSCPA — Comercial Parceiro
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GRUPO | Integer |  | Grupo |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| DTPREVINST | Date |  | Data Prevista Instalação |  |
| DTINST | Date |  | Data Instalação |  |
| OBS1 | String |  | Observação |  |
| CODPROJ | Integer |  | Projeto |  |
| CONTATO | String |  | Contato |  |
| TELEFONE | String |  | Telefone |  |
| CIDADE_PARC | String |  | Cidade Parceiro |  |
| ESTADO_PARC | String |  | Estado |  |
| TIPO_PARC | String |  | Tipo |  |
| ENDERECO_PARC | String |  | Endereço |  |
| NUMERO_PARC | String |  | Número |  |
| COMPLEMENTO_PARC | String |  | Complemento |  |
| CEP_PARC | String |  | Cep |  |
| CGC_CPF | Integer |  | CGC CPF |  |
| TELEFONE_PARC | String |  | Telefone Parc. |  |
| NUMCONTRATO | Integer |  | Número do Contrato |  |

## TCSCPR — Comercial Produto
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GRUPO | Integer |  | Grupo |  |
| CODPROD | Integer |  | Produto |  |
| CODFORN | Integer |  | Fornecedor |  |
| QTDNEG | Float |  | Quantidade Cliente |  |
| QTDPEDIR | Float |  | Quantidade P/ Gerar Ped |  |
| QTDPED | Float |  | Quantidade Requisitada |  |
| DTPREVINST | Date |  | Data Prevista |  |
| PRINCIPAL | String |  | Principal | `S`=Sim `N`=Não |
| QTDPEDVDA | Float |  | Quantidade Entregue |  |
| IMPNOTA | String |  | Imprime na Nota | `S`=Sim `N`=Não |
| VALOR | Float |  | Valor |  |
| IMPOS | String |  | Imprime na Ordem de Serviço | `S`=Sim `N`=Não |
| COMPLDESC | String |  | Complemento |  |
| NUMCONTRATO | Integer |  | Número do Contrato |  |

## TCSCSE — Contratos e Serviços
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODSERV | Integer |  | Serviço |  |
| PARCELAS | Integer |  | Parcelas |  |
| VALOR | Float |  | Valor |  |
| NUMCONTRATO | Integer |  | Número do Contrato |  |

## TCSCSL — Cores SLA
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMREG | Integer |  | Núm. Regra |  |
| SEQCOR | Integer |  | Sequência de Cor |  |
| DECORESTA | String |  | Decorrido/Restante | `D`=Decorrido `R`=Restante |
| TIPOTEMPO | String |  | Tipo de Tempo | `P`=Percentual `H`=Horas |
| VALORTEMPO | Integer |  | Tempo |  |
| CORRGB | Integer |  | Valor da Cor em RGB |  |
| NUSLA | Integer |  | Nro. Único SLA |  |

## TCSCSTC — Características de Serviço de Tele/Comunicação
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMCSTC | Integer |  | Número da Característica de Serviço de Tele/Comunicação |  |
| TIPSVCOM | String |  | Tipo Serviço Comunicação | `TVA`=TVA - Diversos serviços de TV mediante assinatura (TVA, TVC, DTH, MMDS e SeAC) `STFC`=STFC - Serviço de Telefonia Fixa Comutada Geral `SCM`=SCM - Serviço de Comunicação Multimídia |
| TIPMEIO | String |  | Tipo Meio | `satelite`=satelite `radio`=radio `fibra`=fibra `cabo_metalico`=cabo_metalico `cabo_coaxial`=cabo_coaxial |
| TIPTEC | String |  | Tipo Tecnologia | `NR`=NR `FTTH`=FTTH `ETHERNET`=ETHERNET |
| TIPPRO | String |  | Tipo Produto - SCM | `outros`=outros `m2m`=m2m `linha_dedicada`=linha_dedicada `internet`=internet |
| TIPATE | String |  | Tipo Atendimento - SCM | `Urbano`=Urbano `Rural`=Rural |
| VELCOM | Integer |  | Velocidade Contratada - SCM |  |

## TCSCTT — ContatoProspect
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCONTATO | Integer |  | Contato |  |
| NOMECONTATO | String |  | Nome |  |
| APELIDO | String |  | Apelido |  |
| CARGO | String |  | Cargo |  |
| EMAIL | String |  | E-mail |  |
| TELEFONE | String |  | Telefone |  |
| RAMAL | String |  | Ramal |  |
| CELULAR | String |  | Celular |  |
| CODPAP | Integer |  | Prospect |  |

## TCSCVE — Contrato Veículos
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVEICULO | Integer |  | Veiculo |  |
| TELEFONE | String |  | Telefone |  |
| DTALTER | DateTime |  | Data de alteração |  |
| NUMOSINSTAL | Integer |  | OS Instalação |  |
| DTINSTAL | DateTime |  | Data de Instalação |  |
| NUMOSDESINSTAL | Integer |  | OS Desinstalação |  |
| DTDESINSTAL | DateTime |  | Data de Desinstalação |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODSERV | Integer |  | Serviço |  |
| NUMCONTRATO | Integer |  | Número do Contrato |  |

## TCSCXT — Centro de resultado por tipo de negociação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| NURFE | Integer |  | Modelo de Proposta |  |
| NURFEFR | Integer |  | Modelo Folha de Rosto |  |
| CODTPN | Integer |  | Cód. Tipo de Negociação Pré-Venda |  |

## TCSEAG — EventoAgendado
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRABREV | String |  | Descrição abreviada |  |
| DESCRLONGA | String |  | Descrição completa |  |
| DHINICIO | DateTime |  | Data e hora início |  |
| DHFINAL | DateTime |  | Data e hora fim |  |
| CODUSU | Integer |  | Cód. Usuário Executante |  |
| CONFIRMADO | String |  | Confirmado | `N`=Não `S`=Sim |
| CANCELADO | String |  | Cancelado | `N`=Não `S`=Sim |
| SINCRONIZAR | String |  | Sincronizar | `N`=Não `S`=Sim |
| IDSINC | String |  | ID Sincronização |  |
| ICALEXP | String |  | Expressão de recorrência |  |
| DHALTERSINC | DateTime |  | Data sincronização |  |
| NUEVENTOPAI | Integer |  | Evento Pai |  |
| DHINICIOPAI | DateTime |  | Dh. Início pai |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| NUMOS | Integer |  | Número da OS |  |
| SUBOS | Integer |  | Sub OS |  |
| NUFAP | Integer |  | Projeto |  |
| NUMETAPA | Integer |  | Etapa do projeto |  |
| DIATODO | String |  | Dia todo | `N`=Não `S`=Sim |
| DHLCTO | DateTime |  | Dh. Lançamento |  |
| CODUSULANCADOR | Integer |  | Cód. Usuário Lançador |  |
| LOCALEVENTO | String |  | Local do evento |  |
| NUSELECAO | Integer |  | Nro. Seleção |  |
| CODETAPA | Integer |  | Cód. Etapa |  |
| NUCURRICULO | Integer |  | Nro. Currículo |  |
| CHANGEKEY | String |  | Change Key |  |
| IDOFFICE | String |  | ID Sinc. Office |  |
| FALHASINC | Integer |  | FALHASINC |  |
| MOTIVO | String |  | Motivo do Cancelamento |  |
| DHCANCELAMENTO | DateTime |  | Data de Cancelamento |  |
| CODPAP | Integer |  | Cód. Prospect |  |
| NUMCONTRATO | Integer |  | Contrato |  |
| NUEVENTO | Integer |  | Num. Evento |  |

## TCSEFL — Executantes por fluxo de processo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VARIACAO | Integer |  | Variação |  |
| CODSERV | Integer |  | Cód. Serviço |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODPROD | Integer |  | Cód. Produto |  |

## TCSEFP — Exceção Faturamento Pedido
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ACEITACOMPL | String |  | Aceita Serviço Complementar | `N`=Não `S`=Sim |
| OBS | String |  | Observação |  |
| DHALTER | DateTime |  | Dt./Hota Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUNOTA | Integer |  | Nro. Único Pedido |  |

## TCSEHI — Histórico de Etapas de Projeto (HistoricoEtapa)
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CONCLUIDA | String |  | Concluída |  |
| DTALTER | DateTime |  | Data de alteração |  |
| DTCEDOFIMPREV | DateTime |  | Início Limite |  |
| DTCEDOINIPREV | DateTime |  | Início Previsto |  |
| DTTARDEFIMPREV | DateTime |  | Término limite |  |
| DTTARDEINIPREV | DateTime |  | Término previsto |  |
| NUFAP | Integer |  | Número da FAP |  |
| NUMETAPA | Integer |  | Número da Etapa |  |
| NUMSEQ | Integer |  | Número de sequência |  |
| SUPLEMENTA | String |  | Suplementa | `S`=Sim `N`=Não |
| SUPLEMENTADO | String |  | Suplementado | `S`=Sim `N`=Não |
| TIPVALOR | String |  | Tipo de Valor |  |
| VALOR | Float |  | Valor |  |
| VLRSUPLEMENTA | Float |  | Valor Suplementa |  |
| VLRSUPLEMENTADO | Float |  | Valor Suplementado |  |
| VLRSUPLEMENTADOREA | Float |  | Valor Suplementado Real |  |
| VLRSUPLEMENTAREA | Float |  | Valor Suplementa Real |  |

## TCSELC — Empresas Licenciadas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJCPF | String |  | CNPJ/CPF |  |
| NOME | String |  | Nome |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| NUMCONTRATO | Integer |  | Número do contrato |  |

## TCSEPD — Etapa predecessora
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMETAPAPRED | Integer |  | NUMETAPAPRED |  |
| TIPO | String |  | TIPO | `II`=Início-a-Início (II) `TT`=Término-a-Término (TT) `TI`=Término-a-Início (TI) |
| NUFAP | Integer |  | NUFAP |  |
| NUMETAPA | Integer |  | NUMETAPA |  |

## TCSEPV — Expectativas do Esforço Pré-Venda
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEPV | Integer |  | Código |  |
| PERCPRO | Float |  | Percentual de Projeção |  |
| DESCRICAO | String |  | Descrição |  |

## TCSEQP — Equipe
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCOORD | Integer |  | Coordenador |  |
| NOME | String |  | Nome Da Equipe |  |
| TIPOCOORD | String |  | Tipo Coordenador | `F`=Funcionário `P`=Parceiro `U`=Usuário |
| NOMECOORD | String |  | Nome Coordenador |  |
| CODEMPFUN | Integer |  | Empresa |  |
| ATIVA | String |  | Ativa | `S`=Sim `N`=Não |
| NUEQUIPE | Integer |  | Cód. Equipe |  |

## TCSERR — Erros e Soluções
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| ASSUNTO | String |  | Assunto |  |
| DESCRICAO | String |  | Descrição |  |
| SOLUCAO | String |  | Solução |  |
| DTCAD | DateTime |  | Data do Cadastro |  |
| DTATUAL | DateTime |  | Data Atual |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODUSUATUAL | Integer |  | Cód. Usuário Atual |  |
| STATUS | String |  | Status |  |
| CODERRO | Integer |  | Código |  |

## TCSESA — Serviço por Etapa de Projeto (ServicoEtapa)
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| COMPLEMENTAR | String |  | Complementar? | `N`=Não `S`=Sim |
| CODPROD | Integer |  | Serviço |  |
| NUFAP | Integer |  | Número da Fap |  |
| NUMETAPA | Integer |  | Número da Etapa |  |

## TCSEVC — Tabela de Eventos de Contrato
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMCONTRATO | Integer |  | NUMCONTRATO |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| DHINCLUSAO | DateTime |  | DHINCLUSAO |  |
| DHPROCESS | DateTime |  | DHPROCESS |  |
| SEQEVENTO | Integer |  | SEQEVENTO |  |
| ATIVO | String |  | ATIVO |  |
| DIASTOLERANCIA | Integer |  | DIASTOLERANCIA |  |
| TENTENVIO | Integer |  | TENTENVIO |  |
| CODPARC | Integer |  | CODPARC |  |

## TCSEXN — TCSEXN
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEXECUTANTE | Integer |  | Executante |  |
| NUNEGOCIACAO | Integer |  | Negociação |  |

## TCSEXR — Etapa por requisição
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMETAPA | Integer |  | Número da Etapa |  |
| NUNOTA | Integer |  | Nro. Requisição |  |
| NUFAP | Integer |  | FAP |  |

## TCSFAP — Projeto Serviço (FAP)
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód. Parceiro |  |
| QTDHORAS | Integer |  | Quantidade de Horas |  |
| CODMETOD | Integer |  | Modelo |  |
| STATUS | String |  | Status | `E`=Cancelado `S`=Suspenso `C`=Concluído `NC`=Não Configurado `P`=Em Andamento |
| OBSERVACAO | String |  | Observação |  |
| CODCONTATO | Integer |  | Contato |  |
| CODCOORD | Integer |  | Coordenador |  |
| IMPLANTADOR | String |  | Implantador | `N`=Não `S`=Sim |
| NUNOTA | Integer |  | Número da Nota |  |
| LIMITAPROD | String |  | Limitar Produtos | `S`=Sim `N`=Não |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| COR | String |  | Cor das etapas (no gráfico) |  |
| NUFAP | Integer |  | Número do Projeto |  |

## TCSFATHC — TCSFATHC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | Nro. Item |  |
| NUNOTA | Integer |  | Pedido |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUMOS | Integer |  | Nro. OS |  |

## TCSFEE — Membro de Equipe de Etapa (EquipeEtapa)
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PRINCIPAL | String |  | Principal | `N`=Não `S`=Sim |
| CODTIPFUNCAO | Integer |  | Função |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUFAP | Integer |  | Número da FAP |  |
| NUMETAPA | Integer |  | Número da Etapa |  |

## TCSFEQ — Membro de Equipe de Projeto (EquipeProjeto)
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPFUNCAO | Integer |  | Função |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUFAP | Integer |  | Número da FAP |  |

## TCSFET — Etapa de Projeto
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VALOR | Float |  | Valor |  |
| DTCEDOINIPREV | Date |  | Início |  |
| DTCEDOFIMPREV | Date |  | Fim |  |
| CONCLUIDA | String |  | Concluída | `N`=Não `S`=Sim |
| CODPROD | Integer |  | Serviço |  |
| DTTARDEINIPREV | Date |  | Início Limite |  |
| DTTARDEFIMPREV | Date |  | Fim Limite |  |
| NUFAP | Integer |  | Número da FAP |  |
| NUMETAPA | Integer |  | Número da Etapa |  |
| NUMETAPAPAI | Integer |  | Número da Etapa Pai |  |
| NUMSEQ | Integer |  | Sequência |  |
| SUPLEMENTA | String |  | Empresta | `S`=Sim `N`=Não |
| SUPLEMENTADO | String |  | Pega Emprestado | `S`=Sim `N`=Não |
| TIPVALOR | String |  | Tipo de Valor |  |
| VLRSUPLEMENTA | Float |  | Hrs. Suplementa |  |
| VLRSUPLEMENTADO | Float |  | Hrs. Suplementado |  |
| VLRSUPLEMENTADOREA | Float |  | Hrs. Suplementado Real |  |
| VLRSUPLEMENTAREA | Float |  | Hrs. Suplementa Real |  |
| CONCLUSAOAUTOMATICA | String |  | Concluir ao fechar Sub-OS | `S`=Sim `N`=Não |
| CHAVEIMP | Integer |  | Chave para importação do Project |  |
| EXIGEREQ | String |  | Exigir requisito em Sub-OS | `S`=Sim `N`=Não |
| OBSERVACAO | String |  | Observação |  |
| NUMMODELO | Integer |  | Número do Modelo |  |
| DESCRICAO | String |  | Descrição |  |

## TCSFHA — Histórico de alteração projeto
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Usuário |  |
| OBSERVACAO | String |  | Observação |  |
| NUFAP | Integer |  | Projeto |  |

## TCSFHS — Histórico Status de Projeto
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| STATUS | String |  | STATUS | `NC`=Não Configurado `E`=Cancelado `P`=Em Andamento `C`=Concluído `S`=Suspenso |
| NUFAP | Integer |  | NUFAP |  |

## TCSFIP — Detalhe natureza da proposta
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQPROPOSTA | Integer |  | Seq. Proposta |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| SEQNAT | Integer |  | Seq. Natureza |  |
| VALOR | Float |  | Valor |  |
| VLRFINANCIADO | Float |  | Valor Financiado |  |
| NROPARCELAS | Integer |  | Número de Parcelas |  |
| VLRENTRADA | Float |  | Valor da Entrada |  |
| DTENTRADA | DateTime |  | Data de Entrada |  |
| DIAPGTO | Integer |  | Dia de Pagamento |  |
| NROCARTAO | String |  | Número do Cartão |  |
| VALCARTAO | DateTime |  | Validade do Cartão |  |
| OBSERVACAO | String |  | Observação |  |
| NUMOS | Integer |  | Número da OS |  |

## TCSFLD — Fluxo de Diagnóstico
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| FLUXO | C |  | FLUXO |  |
| CODFLD | Integer |  | Cód. Fluxo |  |

## TCSFPD — Pedidos da FAP
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| QTDHORAS | Integer |  | QTDHORAS |  |
| ATIVO | String |  | ATIVO | `N`=Não `S`=Sim |
| NUFAP | Integer |  | NUFAP |  |

## TCSFPE — Insumos de etapas
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMETAPA | Integer |  | Etapa |  |
| CODPROD | Integer |  | Produto |  |
| CODVOL | String |  | Volume |  |
| CODLOCAL | Integer |  | Local |  |
| CONTROLE | String |  | Controle |  |
| QTDNEG | Float |  | Qtd. Negociada |  |
| SEQUENCIA | Integer |  | Sequência |  |
| QTDREQUISITADA | Float |  | Qtd. Requisitada |  |
| NUFAP | Integer |  | FAP |  |

## TCSFPR — Produto  por Projeto
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| NUFAP | Integer |  | Número da FAP |  |

## TCSFXO — Fluxo por Ordem Serviço
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFLD | Integer |  | Cód. Fluxo |  |
| NUMOS | Integer |  | Núm. O.S. |  |

## TCSGEC — Grupo Econômico
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| PERCCUSTO | Float |  | % de custo |  |
| NUMCONTRATO | Integer |  | Número do contrato |  |

## TCSGMT — Grupos de Metodologias
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNAT | Integer |  | Cód. Natureza |  |
| NOMEGMETOD | String |  | Nome do Método |  |
| DESCRGMETOD | String |  | Descrição do Método |  |
| CODMETOD | Integer |  | Método |  |

## TCSHSE — Histórico de Suplementações
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUFAP | Integer |  | Nro único FAP |  |
| NUMETAPAORIG | Integer |  | Etapa origem |  |
| NUMETAPADEST | Integer |  | Etapa destino |  |
| QTDHORAS | Float |  | Qtd. horas |  |
| DHALTER | DateTime |  | Dt. alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| SEQUENCIA | Integer |  | Sequência |  |

## TCSIE — TABLE TCSIE
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVEND | Integer |  | Vendedor |  |
| INDICE1 | Float |  | Índice 1 |  |
| INDICE2 | Float |  | Índice 2 |  |
| INDICE3 | Float |  | Índice 3 |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| REFERENCIA | Date |  | Referência |  |

## TCSITE — Ítens da Ordem de Serviço
Campos: 70

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | Sub-OS |  |
| INICEXEC | Date |  | Dt execução |  |
| HRINICIAL | Text |  | Hora Inicial |  |
| HRFINAL | Text |  | Hora Final |  |
| TIPOOS | String | 15 | Tipo OS |  |
| CODUSU | Integer |  | Cód. Usuário Executante |  |
| CLASSIFICACAO | String | 25 | Classificação | `C`=Conformidade `N`=Não Conformidade `S`=Serviços Complementares `I`=Indeterminado |
| CODSERV | Integer |  | Cód. Serviço |  |
| CODPROD | Integer |  | Cód. Produto |  |
| SOLUCAO | String |  | Solução |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| CODPROJ | Integer |  | Cód. Projeto |  |
| CODOCOROS | Integer |  | Motivo |  |
| COBRAR | String |  | Cobrar | `S`=Sim `N`=Não |
| CODUSUALTER | Integer |  | Cód. Usuário |  |
| DESCSERV | String |  | Problema |  |
| DHPREVISTA | DateTime |  | Agendamento |  |
| DTALTER | DateTime |  | Dt. alteração do item |  |
| DTPREVFECHAMENTO | DateTime |  | Data Limite Sub OS |  |
| EXECUTANTE | String |  | Executante (Painel de filtros) | `F`=Executante e Filas que participa `A`=Atendente `E`=Executante `R`=Responsável |
| GRAUDIFIC | Integer |  | Grau de dificuldade |  |
| INTERVALO | Integer |  | Intervalo |  |
| LIBERADO | String |  | Liberado | `S`=Sim `N`=Não |
| QTDSERV | Float |  | Quantidade serviço |  |
| RETRABALHO | String |  | Retrabalho | `S`=Sim `N`=Não |
| SERIE | String |  | Série |  |
| QTDHORA | Text |  | Qtd. Horas |  |
| TEMPGASTO | Integer |  | Tempo gasto |  |
| QTDHORAEXT | Float |  | Qtd. Horas Extras |  |
| TEMPPREVISTO | DateTime |  | Tempo previsto para executar a OS |  |
| QTDHORABONIF | Float |  | Qtd. Horas Bonif. |  |
| TERMEXEC | DateTime |  | Término da execução |  |
| QTDHORAEXTBONIF | Float |  | Qtd. Horas Extras Bonif. |  |
| TIPO | String |  | Tipo | `I`=Atendimento `P`=Pré-Venda `A`=Todas `T`=Interna |
| QTDHORACOMBONIF | Float |  | Qtd.Horas Com.Bonif. |  |
| VLRCOBRADO | Float |  | Valor a ser cobrado |  |
| CODUSUREM | Integer |  | Cód. Usuário Remetente |  |
| QTDHORAEXTCOMBONIF | Float |  | Qtd.Horas Extras Com.Bonif. |  |
| DHENTRADA | DateTime |  | Dt Entrada Sub-OS |  |
| VLRHORAFAT | Float |  | Vlr. Hora |  |
| NUMETAPA | Integer |  | Num. Etapa |  |
| VLRHORAEXTFAT | Float |  | Vlr. Hora Extra |  |
| CODSIT | Integer |  | Cód. Status Sub-OS |  |
| VLRHORACOM | Float |  | Vlr.Hora Comissão |  |
| CODEPV | Integer |  | Expectativa Fechamento |  |
| VLRHORAEXTCOM | Float |  | Vlr.Hora Extra Comissão |  |
| CORSLA | Integer |  | Cor de SLA |  |
| DHLIMITESLA | DateTime |  | Data Limite do SLA |  |
| TURNO | Integer |  | Turno |  |
| CODSERVRAIZ | Integer |  | Cód. Serv. Raiz |  |
| DHVALIDACAO | DateTime |  | Dh validação |  |
| DHEMAILVAL | DateTime |  | Dh email validação |  |
| TEMPOGASTOSLAPROC | Integer |  | TEMPOGASTOSLAPROC |  |
| NUMFLUXO | Integer |  | Num. Fluxo |  |
| CODREQ | Integer |  | Requisito |  |
| COMPLETUDE | Integer |  | Completude |  |
| SEQFLUXO | Integer |  | Sequência do Fluxo |  |
| CONTADORFLUXO | Integer |  | CONTADORFLUXO |  |
| NUNEGOCIACAO | Integer |  | Negociação |  |
| NUNOTA | Integer |  | Nro. Nota |  |
| DHPAUSEAPP | DateTime |  | Data Hora pausa aplicativo |  |
| CODCENCUSPAD | Integer |  | Cód.Centro Resultado Padrão |  |
| CODUNNEXEC | Integer |  | Cód. un. negócio executante |  |
| CODUNNOS | Integer |  | Cód. un. negócio OS |  |
| CODVEND | Integer |  | Cód.Vendedor |  |
| DESCRCENCUS | String |  | Centro de Resultado |  |
| NUMOS | Integer |  | Núm. OS |  |
| PRODUTIVIDADE | Float |  | Produtividade |  |
| TEMPOGASTOSLASUB | Integer |  | TEMPOGASTOSLASUB |  |
| VLRCOMISSAO | Float |  | Vlr. Comissão |  |

## TCSITE_DAS — Ítens da Ordem de Serviço Doc Assinados
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | Sub-OS |  |
| NUDOC | Integer |  | Núm. Documento |  |
| NUMOS | Integer |  | Núm. OS |  |

## TCSITS — Tabela de situação
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODSIT | Integer |  | Código |  |

## TCSLBE — Linha de base da etapa do projeto
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMETAPA | Integer |  | NUMETAPA |  |
| SEQLIBASE | Integer |  | SEQLIBASE |  |
| NUMSEQ | Integer |  | NUMSEQ |  |
| CODPROD | Integer |  | CODPROD |  |
| TIPVALOR | String |  | TIPVALOR | `P`=Porcentagem `H`=Horas |
| VALOR | Float |  | VALOR |  |
| DTCEDOINIPREV | DateTime |  | DTCEDOINIPREV |  |
| DTCEDOFIMPREV | DateTime |  | DTCEDOFIMPREV |  |
| DTTARDEINIPREV | DateTime |  | DTTARDEINIPREV |  |
| DTTARDEFIMPREV | DateTime |  | DTTARDEFIMPREV |  |
| NUMETAPAPAI | Integer |  | NUMETAPAPAI |  |
| NUFAP | Integer |  | NUFAP |  |

## TCSLBP — Linha de base do projeto
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DHBASE | DateTime |  | DHBASE |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| NUFAP | Integer |  | NUFAP |  |

## TCSLBQ — Linha Base Requisito Etapa
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMETAPA | Integer |  | NUMETAPA |  |
| CODREQ | Integer |  | CODREQ |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUFAP | Integer |  | NUFAP |  |

## TCSLBR — Linha Base Requisito
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUFAP | Integer |  | NUFAP |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NOME | String |  | NOME |  |
| DESCRICAO | String |  | DESCRICAO |  |
| CASOUSO | String |  | CASOUSO |  |
| PESO | Float |  | PESO |  |
| TODAETAPA | String |  | TODAETAPA |  |
| CODREQ | Integer |  | CODREQ |  |

## TCSLIATIVA — TABLE TCSLIATIVA
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cod. Usuário Solicitante |  |
| CODUSULIB | Integer |  | Cod. Usuário Liberador |  |
| CODFONE | String |  | Id |  |
| DTLIB | DateTime |  | Data Liberação |  |
| DTSOLI | DateTime |  | Data Solicitação |  |
| APP | Integer |  | App |  |
| NOME | String |  | Nome |  |
| CODSOLI | Integer |  | Cod.Solicitação |  |

## TCSLIHIST — TABLE TCSLIHIST
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSOLI | Integer |  | Código da Solicitação |  |
| CODUSU | Integer |  | Código do Usuário |  |
| CODFONE | String |  | Id |  |
| CODUSULIB | Integer |  | Código Usuário Liberador |  |
| CODFONEDESTINO | String |  | Id Destino |  |
| STATUS | String |  | Status | `U`=Substituído `S`=Solicitado `L`=Liberado |
| DTLIB | DateTime |  | Data de Liberação |  |
| DTSOLI | DateTime |  | Data de Solicitação |  |
| NOME | String |  | Nome |  |
| APP | Integer |  | App |  |
| CODHIST | Integer |  | Código Histórico |  |

## TCSLIP — Parcelas Adicionais Por Nota
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NUMCONTRATO | Integer |  | Contrato |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |

## TCSLIPENDENTE — TABLE TCSLIPENDENTE
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cod. Usuário Solicitante |  |
| CODUSULIB | Integer |  | Cod. Usuário Liberador |  |
| CODFONE | String |  | Id |  |
| DTLIB | DateTime |  | Data Liberação |  |
| DTSOLI | DateTime |  | Data Solicitação |  |
| APP | Integer |  | App |  |
| NOME | String |  | Nome |  |
| CODSOLI | Integer |  | Cod. Solicitação |  |

## TCSMED — Medição
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| DHAUTOR | DateTime |  | Data e hora de Autorição |  |
| VLRMED | Float |  | Valor da medicao |  |
| NUFIN | Integer |  | Número do Finânceiro |  |

## TCSMEQ — Membro de Equipe
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMEMBRO | Integer |  | Membro |  |
| NOMEMEMBRO | String |  | Nome do membro |  |
| CODFUNCAO | Integer |  | Função |  |
| INICIOPARTICIPA | Date |  | Início de Participação |  |
| FINALPARTICIPA | Date |  | Final de Participação |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| NUEQUIPE | Integer |  | Nro Equipe |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NOME | String |  | Nome |  |
| CODEMPFUN | Integer |  | Empresa |  |
| TIPOMEMBRO | String |  | Tipo do Membro | `U`=Usuário `F`=Funcionário `P`=Parceiro |

## TCSMET — Modelo de Projeto
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEMETOD | String |  | Nome |  |
| DESCRMETOD | String |  | Descrição |  |
| OBSERVACOES | String |  | Observações |  |
| QTDHORAS | Integer |  | Quantidade de Horas |  |
| ATIVO | String |  | Status |  |
| NOTAMODPREVENDA | Integer |  | Mod. Pedido Negociação |  |
| CODMETOD | Integer |  | Modelo |  |

## TCSMFU — Recurso por Modelo de Etapa
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMETOD | Integer |  | Metodologia |  |
| CODTIPFUNCAO | Integer |  | Função |  |
| NUMMODELO | Integer |  | Número do Modelo |  |

## TCSMOD — Modelo Etapa
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OBRIGATORIA | String |  | OBRIGATORIA |  |
| OBSERVACAO | String |  | Observação |  |
| EXIGEPRODUTOS | String |  | Exige Prod. na Negociação |  |
| CODMETOD | Integer |  | Código |  |
| CODPROD | Integer |  | Servico |  |
| DESCRICAO | String |  | Descrição do modelo |  |
| NUMMODELO | Integer |  | Número do Modelo |  |
| NUMMODELOPAI | Integer |  | Número do modelo pai |  |
| NUMSEQ | Integer |  | Sequência |  |
| SUPLEMENTA | String |  | Suplementa | `N`=Não `S`=Sim |
| SUPLEMENTADO | String |  | Suplementado | `S`=Sim `N`=Não |
| TIPVALOR | String |  | Tipo do Valor | `P`=Percentual `H`=Horas |
| VALOR | Float |  | Valor |  |
| VLRSUPLEMENTA | Float |  | Valor Suplementa |  |
| VLRSUPLEMENTADO | Float |  | Valor Suplementado |  |

## TCSMPD — Modelos de etapas predecessoras
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMMODELO | Integer |  | Modelo |  |
| NUMMODELOPRED | Integer |  | Etapa Predecessora |  |
| TIPO | String |  | Tipo | `II`=Início-a-Início (II) `TT`=Término-a-Término (TT) `TI`=Término-a-Início (TI) |
| CODMETOD | Integer |  | Cód. Método |  |

## TCSMPR — Insumos dos modelos de etapas
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMMODELO | Integer |  | Modelo |  |
| CODPROD | Integer |  | Produto |  |
| CODVOL | String |  | Volume |  |
| CODLOCAL | Integer |  | Local |  |
| CONTROLE | String |  | Controle |  |
| QTDNEG | Float |  | Qtde. Negociada |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODMETOD | Integer |  | Cód. Método |  |

## TCSMSA — Serviço por Modelo de Etapa
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| COMPLEMENTAR | String |  | Complementar? | `N`=Não `S`=Sim |
| CODMETOD | Integer |  | Metodologia |  |
| CODPROD | Integer |  | Serviço |  |
| NUMMODELO | Integer |  | Número do Modelo |  |

## TCSMTE — Motivos Exceção Faturamento
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRMOTIVO | String |  | Descrição |  |
| TIPOMOTIVO | String |  | Tipo | `A`=Não autorização de O.S. `E`=Exceção de faturamento |
| NUMOTIVO | Integer |  | Nro. Motivo |  |

## TCSNHC — TCSNHC
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUNNCOMPRADORA | Integer |  | Un. Compradora |  |
| DTINI | Date |  | Dt. Inicial |  |
| DTFIN | Date |  | Dt. Final |  |
| VLRHORA | Float |  | Vlr. Hora |  |
| MULTHORAEXTRA | Float |  | Multip. Hora Extra |  |
| NUFAP | Integer |  | Nro. Projeto |  |
| NUNOTA | Integer |  | Pedido Avulso |  |
| NUNEGOCIACAO | Integer |  | Código |  |
| CODUNNVENDEDORA | Integer |  | Un. Vendedora |  |
| CODUSU | Integer |  | Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODPARC | Integer |  | Parceiro |  |

## TCSNTE — Números dos Terminais Telefônicos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODAREADDD | Integer |  | Código da Localidade |  |
| NUMTERMTEL | Integer |  | Número de Identificação do Terminal Telefônico |  |
| PRINCIPAL | String |  | Principal | `S`=Sim `N`=Não |
| CODUFIBGE | String |  | UF | `11`=Rondônia `12`=Acre `13`=Amazonas `14`=Roraima `15`=Pará_(+22)_ |
| NUMCONTRATO | Integer |  | Número do Contrato |  |

## TCSNTS — Natureza X Serviço
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNAT | Integer |  | Cód. Natureza |  |
| CODSERV | Integer |  | Serviço |  |

## TCSNXT — Natureza por tipo de negociação pré-venda
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNAT | Integer |  | Cód. Natureza |  |
| CODTPN | Integer |  | Cód. Tipo de Negociação Pré-Venda |  |

## TCSOAT — Origem do Atendimento
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCROAT | String |  | Descrição |  |
| ANALITICO | String |  | Analítico | `S`=Sim `N`=Não |
| CODOATPAI | Integer |  | Codigo Pai |  |
| TIPO | String |  | Tipo | `B`=Ambos `P`=Pré-Venda `A`=Atendimento |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Data de Alteração |  |
| GRAU | Integer |  | Grau |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODOAT | Integer |  | Código |  |

## TCSOCC — Ocorrências do Contrato
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTOCOR | Date |  | Dt. ocorrência |  |
| CODCONTATO | Integer |  | Contato |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DESCRICAO | String |  | Descrição |  |
| NUMCONTRATO | Integer |  | Número do contrato |  |
| CODPROD | Integer |  | Produto |  |
| CODOCOR | Integer |  | Ocorrência |  |
| CODUSUALTREG | Integer |  | Cód. Usuário Alteração |  |
| DHALTREG | DateTime |  | Dt. Alteração |  |

## TCSOCO — Ocorrências
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| SITPROD | String |  | Situação do produto | `A`=Ativo `E`=Expirar `L`=Liberado por 1 dia `C`=Cancelado `B`=Bonificado_(+1)_ |
| CODOCOR | Integer |  | Ocorrência |  |

## TCSOOS — Ocorrências da OS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| COBRAR | String |  | Valor a Cobrar |  |
| CODOCOROS | Integer |  | Código |  |
| DESCROCOROS | String |  | Descrição |  |
| PREVISTO | String |  | Valor Previsto |  |

## TCSOSE — Ordem de Serviço
Campos: 56

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMOS | Integer |  | Núm. da OS |  |
| STATUSNEG | String |  | Status |  |
| CODCOS | Integer |  | Cód. Status OS |  |
| NUMCONTRATO | Integer |  | Núm. Contrato |  |
| NUMETAPA | Integer |  | Número Etapa |  |
| POSSUISLA | String |  | Possui SLA | `N`=Não `S`=Sim |
| TEMPOGASTOSLA | Integer |  | Tempo Gasto SLA |  |
| TEMPOSLA | Integer |  | Tempo SLA |  |
| DHCHAMADA | DateTime |  | Dt/Hr Chamada |  |
| CODPAP | Integer |  | Cód. Prospect |  |
| TEMPGASTO | Integer |  | Tempo gasto na OS |  |
| IDENTIFICADOR | String |  | Identificador |  |
| TIPO | String |  | Tipo | `P`=Pré-Venda `I`=Interno `A`=Atendimento `T`=Todas |
| TELCONTATO | String |  | Tel. Contato |  |
| SITUACAO | String |  | Situação | `F`=Fechada `P`=Aberta |
| CODBEM | String |  | Bem |  |
| DTFECHAMENTO | DateTime |  | Data de fechamento |  |
| COMPLEMENTO | String |  | Complemento |  |
| NUMOSCLIENTE | String |  | Núm. OS Cliente |  |
| TEMPPREVISTO | Integer |  | Tempo previsto |  |
| ENDERECO | String |  | Endereço |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Cidade |  |
| CODATEND | Integer |  | Atendente |  |
| CONTATO | String |  | Contato |  |
| DTPREVISTA | DateTime |  | Dt/Hr limite OS |  |
| CODUSUALTER | Integer |  | Cód. Usuário Alteração |  |
| CODCONTATO | Integer |  | Cód. Contato |  |
| DESCRICAO | String |  | Problema |  |
| NUFAP | Integer |  | Número Unico FAP |  |
| DTALTER | DateTime |  | Dt alteração |  |
| CODUSUFECH | Integer |  | Cód. Usuário Fechamento |  |
| CODUSURESP | Integer |  | Cód. Usuário Responsável |  |
| NUNOTA | Integer |  | Nro.único do pedido |  |
| SERIE | String |  | Série |  |
| CODVEND | Integer |  | Gerente de Contas |  |
| NOMECONTATO | String |  | Nome Contato |  |
| CODCONTATOPAP | Integer |  | Cód. Contato Prospect |  |
| DHFECHAMENTOSLA | DateTime |  | Fechamento SLA |  |
| CODCOSANT | Integer |  | CODCOSANT |  |
| NUMOSRELACIONADA | Integer |  | OS Relacionada |  |
| CODSERVFLUXO | Integer |  | CODSERVFLUXO |  |
| VARIACAOFLUXO | Integer |  | VARIACAOFLUXO |  |
| CODUSUSOLICITANTE | Integer |  | Cód. Usuário Solicitante |  |
| CODTPN | Integer |  | CODTPN |  |
| CODOAT | Integer |  | Cód. Origem de Atendimento |  |
| CODPARCATEND | Integer |  | Cód. Parceiro Atendido |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| NOMEMODELO | String |  | Nome do Modelo |  |
| CODPLA | Integer |  | Plano de Ação |  |
| ETAPANEG | String |  | Etapa |  |
| MODELOVISIVELAPPOS | String |  | Modelo visível App OS | `N`=Não `S`=Sim |
| CODPROCMAHA | Integer |  | Processo/Procedimento Maha |  |
| IMPACTO | String |  | Impacto |  |
| URGENCIA | String |  | Urgência |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TCSPAD — Parcelas Adicionais
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNAT | Integer |  | Natureza |  |
| REFERENCIA | Date |  | Dt. referência |  |
| DTREAJUSTE | Date |  | Dt. base reajuste |  |
| VENCTO | Integer |  | Prazo vencto |  |
| DIAPAG | Integer |  | Dia do pagto |  |
| PERIODICIDADE | String |  | Periodicidade | `M`=Mensal `A`=Anual `S`=Semestral `Q`=Quadrimestral `T`=Trimestral_(+2)_ |
| NUMCONTRATO | Integer |  | Contrato |  |
| QTDGERARPREV | Integer |  | Qtd. provisões a gerar |  |
| QTDPREV | Integer |  | Qtd. provisões |  |
| VALOR | Float |  | Valor |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt. alteração |  |
| DTVENCTO | Date |  | Data vencimento |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |

## TCSPAP — ParceiroProspect
Campos: 59

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPAP | String |  | Nome |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| CGC_CPF | String |  | CNPJ/CPF |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODVEND | Integer |  | Vendedor |  |
| DTCAD | DateTime |  | Data do Cadastro |  |
| ENDERECO | String |  | Endereço |  |
| NUMEND | String |  | Número |  |
| COMPLEMENTO | String |  | Complemento |  |
| NOMEBAI | String |  | Bairro |  |
| NOMECID | String |  | Cidade |  |
| CODUF | Integer |  | UF |  |
| TELEFONE | String |  | Telefone Prospect |  |
| CEP | String |  | CEP |  |
| NROANS | Integer |  | NROANS |  |
| NROBEN | Integer |  | NROBEN |  |
| TIPPESSOA | String |  | Tipo de pessoa | `F`=Física `J`=Jurídica |
| IDENTINSCESTAD | String |  | Insc. Estadual |  |
| EMAIL | String |  | E-mail |  |
| CODTIPPARC | Integer |  | Cód. Perfil Principal |  |
| DTNASC | Date |  | Data de Nascimento |  |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| CARTEIRATRAB | Integer |  | Carteira de Trabalho |  |
| RG | String |  | Identidade |  |
| DATAEMISSAORG | Date |  | Dt. de Emissão Identidade |  |
| EMISSAORG | String |  | Órgão Emissor |  |
| UFRG | Integer |  | Estado emissor da RG |  |
| NATURALIDADE | Integer |  | Naturalidade |  |
| NOMEMAE | String |  | Nome da mãe |  |
| NOMEPAI | String |  | Nome do pai |  |
| ESTADOCIVIL | String |  | Estado Civil | `C`=Casado(a) `D`=Divorciado(a) `S`=Separado(a) Judicialmente `O`=Solteiro(a) |
| NOMECONJUGE | String |  | Nome do Cônjuge |  |
| CELULARCONJUGE | String |  | Celular do Cônjuge |  |
| ESCOLARIDADE | String |  | Escolaridade | `S`=Superior `M`=Ensino Médio `A`=Analfabeto `F`=Ensino Fundamental `E`=Mestrado_(+1)_ |
| QTDEDEPENDENTES | Integer |  | Qtd. Dependentes |  |
| TELCELULAR | String |  | Telefone Celular |  |
| POSSUICARTAOCREDITO | String |  | Possui Cartao de Crédito | `N`=Não `S`=Sim |
| CARTAOCREDITO | String |  | Bandeira do Cartão |  |
| TIPORESIDENCIA | String |  | Tipo de Residência | `F`=Financiada `P`=Própria `O`=Outros com despesa `A`=Alugada `S`=Outros sem despesa |
| STATUSPROPOSTA | String |  | Status da Proposta | `T`=Inconsistente `I`=Indeferida `D`=Deferida `N`=Não Avaliada |
| ISPROPOSTACARTAO | String |  | Informa se cadastrado foi na tela Proposta Cartão |  |
| CODPARCB2B | Integer |  | Cód.Parceiro B2B |  |
| DIAPAGTO | Integer |  | Dia pagto |  |
| LIMCRED | Float |  | Limite crédito |  |
| NOMECARTAO | String |  | Nome no cartão |  |
| OBSERVACOES | String |  | Observações |  |
| SITCADSEFAZ | String |  | Situação Cadastral SEFAZ | `0`=Não Habilitado `1`=Habilitado |
| DHCADSEFAZ | DateTime |  | Data/Hora da Última Consulta SEFAZ |  |
| INTERVANALISCRED | Integer |  | Intervalo p/ análise de crédito |  |
| SITCADRF | Integer |  | Situação Cadastral ReceitaWS | `1`=Habilitado `0`=Não Habilitado |
| DHCADRF | DateTime |  | Data/Hora da Última Consulta ReceitaWS |  |
| CNAE | String |  | CNAE principal do contribuinte |  |
| INDCREDNFE | Integer |  | Contribuinte credenciado a emitir NF-e | `4`=A SEFAZ não fornece a informação `3`=Credenciado com obrigatoriedade parcial `2`=Credenciado com obrigatoriedade para todas operações `1`=Credenciado `0`=Não credenciado para emissão da NF-e |
| INDCREDCTE | Integer |  | Contribuinte credenciado a emitir CTe | `4`=A SEFAZ não fornece a informação `3`=Credenciado com obrigatoriedade parcial `2`=Credenciado com obrigatoriedade para todas operações `1`=Credenciado `0`=Não credenciado para emissão da CT-e |
| DTINIATIV | Date |  | Início da Atividade do Contribuinte |  |
| DTULTSIT | Date |  | Última mod. da situação cadastral |  |
| DTBAIXA | Date |  | Data da baixa do contribuinte |  |
| REGAPUR | String |  | Regime de apuração |  |
| CODPAP | Integer |  | Prospect |  |

## TCSPEP — Tabela de Processos e Procedimentos
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROCPAI | Integer |  | Processo Pai |  |
| DESCRPROC | String |  | Descrição |  |
| ANALITICO | String |  | Analítico | `S`=Sim `N`=Não |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| GRAU | Integer |  | Grau |  |
| CODQUEST | Integer |  | Questionário |  |
| CODPROC | Integer |  | Processo/Procedimento |  |
| CODPERG | Integer |  | Pergunta |  |

## TCSPFP — Pendencia Faturamento Prorata
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| PENDENCIA | String |  | Pendência | `C`=Crédito `D`=Débito |
| VALOR | Float |  | Valor |  |
| VLRACERTADO | Float |  | Vlr. Acertado |  |
| DTOCOR | Date |  | Referência |  |
| CODOCOR | Integer |  | Ocorrência |  |
| NUMCONTRATO | Integer |  | Contrato |  |

## TCSPIT — Itens Parcelas Adicionais
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| QUANTIDADE | Integer |  | Quantidade |  |
| VALOR | Float |  | Valor |  |
| VLRIGUALPARC | String |  | Valor igual à Parcela? | `S`=Sim `N`=Não |
| PARCPROP | String |  | 1ª Parc. Proporcional | `N`=Não `S`=Sim |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| NUMCONTRATO | Integer |  | Contrato |  |

## TCSPNP — Proposta negociação pré-venda
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQPROPOSTA | Integer |  | Seq. Proposta |  |
| IDPROPOSTA | String |  | Identificador Proposta |  |
| DHALTER | DateTime |  | Data da Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TEMFINANC | Integer |  | Financiamento? | `1`=Possui `0`=Não Possui |
| IMPRIMIU | String |  | Imprimiu | `N`=Não `S`=Sim |
| DESCRPROPOSTA | String |  | Descrição do cenário |  |
| NUMOS | Integer |  | Número da OS |  |

## TCSPOS — Pesquisa X Ordem de Serviço
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMOS | Integer |  | NUMOS |  |
| NUMITEM | Integer |  | NUMITEM |  |
| CODFLD | Integer |  | CODFLD |  |
| APLICAVEL | String |  | APLICAVEL |  |
| NUPESQ | Integer |  | NUPESQ |  |

## TCSPOSSEQ — Histórico Pesquisa X Ordem de Serviço
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMOS | Integer |  | NUMOS |  |
| NUPESQ | Integer |  | NUPESQ |  |
| NUMITEM | Integer |  | NUMITEM |  |
| CODFLD | Integer |  | CODFLD |  |
| APLICAVEL | String |  | APLICAVEL |  |
| SEQPROPOSTA | Integer |  | SEQPROPOSTA |  |

## TCSPPF — Preço por Faixa
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDFINAL | Integer |  | Qtd. Final |  |
| PRECOUNIT | Float |  | Preço Unitário |  |
| VLRFATMIN | Float |  | Faturamento Mínimo |  |
| NUMCONTRATO | Integer |  | Número do Contrato |  |
| CODPROD | Integer |  | Produto |  |
| DTALTER | Date |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| QTDINICIAL | Integer |  | Qtd. Inicial |  |

## TCSPPP — PerfilProspect
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPPARC | Integer |  | Cód. Perfil |  |
| CODPAP | Integer |  | CODPAP |  |

## TCSPRE — Preços do Contrato
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| REFERENCIA | Date |  | Referência |  |
| VALOR | Float |  | Valor |  |
| CODSERV | Integer |  | Serviço |  |
| CODTERRESPAR | Integer |  | Cód. Terceiro Responsável |  |
| NUMCONTRATO | Integer |  | Número do contrato |  |
| CODUSUALTREG | Integer |  | Cód. Usuário Alteração |  |
| DHALTREG | DateTime |  | Dt. Alteração |  |

## TCSPREQTD — Preços Descontos por faixa de quantidades
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód.Produto |  |
| REFERENCIA | DateTime |  | Referência |  |
| QUANTIDADE | Integer |  | Quantidade |  |
| VALOR | Float |  | Valor |  |
| TIPO | String |  | Tipo | `V`=Preço fixo `P`=% Desconto |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data da Alteração |  |
| SERIE | String |  | Série |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| NUMCONTRATO | Integer |  | Número do contrato |  |

## TCSPRJ — Cadastro de Projetos
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDENTIFICACAO | String |  | Identificação |  |
| AMOSTRACUSMAX | Integer |  | Amostras por Custódia |  |
| ABREVIATURA | String |  | Abreviação Projeto |  |
| CODPROD | Integer |  | Produto |  |
| CODEMP | Integer |  | Empresa |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| DTINICIO | DateTime |  | Data Início |  |
| DTTERMINO | DateTime |  | Data de Término |  |
| LIMBONIF | Float |  | Limite de Bonificação |  |
| GRAU | Integer |  | Grau |  |
| CODCLT | Integer |  | Padrão de Classificação |  |
| CODUSURESP | Integer |  | Cód. Usuário Responsável |  |
| ULTIMORDO | Integer |  | Último número RDO |  |
| HRINICIALMIN | Integer |  | Hora Inicial Mínima |  |
| HRFINALMAX | Integer |  | Hora Final Máxima |  |
| INTERVALOMIN | Integer |  | Intervalo Mínimo |  |
| INTERVALOMAX | Integer |  | Intervalo Máximo |  |
| CARGAHORMAX | Integer |  | Carga Horária Máxima |  |
| RETENCAOATIVA | String |  | Retenção Ativa | `N`=Não `S`=Sim |
| PERCRETENCAO | Float |  | Percentual de Retenção |  |
| CODPROJPAI | Integer |  | Projeto pai |  |
| CODCTACTB | Integer |  | Conta Contábil 1 |  |
| CODCTACTB2 | Integer |  | Conta Contábil 2 |  |
| NUQUE | Integer |  | Questionário |  |
| TIMCONTACOMPART | String |  | Conta Compartilhada | `S`=Sim `N`=Não |
| TIMTXPART | Float |  | Participação % |  |
| TIMPARCPROJ | Integer |  | Parceiro |  |
| TIMNMCTACOMP | Integer |  | Conta Bancária |  |
| AD_CODPARC | Integer |  | Parceiro |  |
| CODPROJ | Integer |  | Projeto |  |

## TCSPRN — Produtos da negociação
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| VLRTOT | Float |  | Valor Total |  |
| NUMOS | Integer |  | Núm. da OS |  |

## TCSPRNSEQ — Histórico de produtos da negociação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| VLRTOT | Float |  | Valor Total |  |
| SEQPROPOSTA | Integer |  | Sequência |  |
| NUMOS | Integer |  | Núm. da OS |  |

## TCSPSC — Produtos e Serviços do Contrato
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| SITPROD | String |  | Situação | `S`=Suspenso `A`=Ativo `B`=Bonificado `C`=Cancelado |
| QTDEPREVISTA | Float |  | Qtd. Prevista |  |
| LIMITANTE | String |  | Limitante | `N`=Não `S`=Sim |
| PRODPRINC | String |  | Produto principal | `S`=Sim `N`=Não |
| CODPARCPREF | Integer |  | Cód. Parceiro Fornecedor preferencial |  |
| QTDMESES | Integer |  | Quantidade de meses do contrato |  |
| FREQUENCIA | Integer |  | Frequência |  |
| VERSAO | String |  | Versão |  |
| DTVERSAO | Date |  | Data da versão |  |
| VLRUNIT | Float |  | Valor unitário |  |
| NUMUSUARIOS | Float |  | Número de usuários |  |
| QTDUSU | Integer |  | Quantidade de usuário / login |  |
| NUMSERIE | String |  | Número de série |  |
| IMPRNOTA | String |  | Imprimir nota | `S`=Sim `N`=Não |
| IMPROS | String |  | Imprimir OS | `S`=Sim `N`=Não |
| GRUPIMPRESSAO | Integer |  | Grupo de impressão |  |
| OBSERVACAO | String |  | Local de instalação |  |
| TOPFATURCON | Integer |  | TOP para faturamento em contratos |  |
| SERFATURCON | String |  | Série para faturamento em contratos |  |
| NUMCONTRATO | Integer |  | Número do contrato |  |
| CODUSUALTREG | Integer |  | Cód. Usuário Alteração |  |
| DHALTREG | DateTime |  | Dt. Alteração |  |

## TCSPSS — Produto Serviço Série
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| SERIE | String |  | Nro. Série |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | Date |  | Data da alteração |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| NUMCONTRATO | Integer |  | Número do contrato |  |

## TCSPXT — Produto por tipo de negociação pré-venda
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| CODTPN | Integer |  | Cód. Tipo de Negociação Pré-Venda |  |

## TCSQXF — Questionário por fluxo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFLD | Integer |  | Cód. Fluxo de Diagnóstico |  |
| CODPERG | Integer |  | Pergunta abertura |  |
| CODRESP | Integer |  | Resposta abertura |  |
| CODQUEST | Integer |  | Cód. Questionário |  |
| PERCENTUALRESPONDIDO | Float |  | Percentual respondido |  |

## TCSREE — Requisito da Etapa
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMETAPA | Integer |  | Etapa |  |
| CODREQ | Integer |  | Requisito |  |
| NUFAP | Integer |  | FAP |  |

## TCSREQ — Requisitos FAP
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUFAP | Integer |  | FAP |  |
| NOME | String |  | Nome |  |
| DESCRICAO | String |  | Descrição |  |
| CASOUSO | String |  | Caso de uso |  |
| PESO | Float |  | Peso |  |
| TODAETAPA | String |  | Participa em toda etapa | `N`=Não `S`=Sim |
| CODREQ | Integer |  | Requisição |  |

## TCSRPN — Resumo preço Negociação
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNAT | Integer |  | Cód. Natureza |  |
| VALOR | Float |  | Valor |  |
| GRIDMULT | Integer |  | GRIDMULT |  |
| VLRIMP | Float |  | Vlr. Impostos |  |
| VLRLIQ | Float |  | Vlr. Líquido |  |
| NUMOS | Integer |  | Núm. da OS |  |

## TCSRPNSEQ — Histórico resumo preço negociação
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMOS | Integer |  | Núm. da OS |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| VALOR | Float |  | Valor |  |
| GRIDMULT | Integer |  | GRIDMULT |  |
| VLRIMP | Float |  | Vlr. Impostos |  |
| VLRLIQ | Float |  | Vlr. Líquido |  |
| SEQPROPOSTA | Integer |  | Sequência |  |

## TCSRSI — Regra de SLA por sub-OS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMREG | Integer |  | Num. Regra |  |
| NUMOS | Integer |  | Número da OS |  |
| NUMITEM | Integer |  | Número do Ítem |  |
| NUSLA | Integer |  | Nro. Único SLA |  |

## TCSRSL — Regra SLA
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMREG | Integer |  | Num. Regra |  |
| ORDEM | Integer |  | Ordem de Classificação |  |
| BASECALCTEMPO | String |  | Base de Cálculo para Tempo | `S`=Dt. Chegada Sub-OS `O`=Dt. Chamada OS |
| CODPROD | Integer |  | Produto |  |
| CODSERV | Integer |  | Serviço |  |
| CODGRUPOPROD | Integer |  | Grupo de Produtos |  |
| CODOCOROS | Integer |  | Motivo |  |
| PADRAO | String |  | Regra Padrão |  |
| TIPOTEMPO | String |  | Tipo de Tempo | `H`=Horas `D`=Dias |
| VALORTEMPO | Integer |  | Tempo |  |
| USAREGRAPADRAO | String |  | Usar em conjunto com a regra |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| TEMPOTOTAL | Integer |  | TEMPOTOTAL |  |
| CODCARGAHOR | Integer |  | Carga Horária |  |
| NUSLA | Integer |  | Nro. Único SLA |  |

## TCSRUS — Relacionamento de usuário
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CODUSUREL | Integer |  | Cód. Usuário Relacionamento |  |
| TIPO | String |  | Tipo de Usuário |  |
| LIDERIMEDIATO | String |  | Líder Imediato | `S`=Sim `N`=Não |
| VINCULO | String |  | Liderança | `S`=Sim `N`=Não |

## TCSSAG — Conta Sincronização de Agenda
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SINCAGENDA | String |  | Sincronizar com | `G`=Google Agenda `M`=Office 365 |
| CONTASINCAGENDA | String |  | Conta |  |
| SENHASINCAGENDA | String |  | Senha |  |
| DHULTSINCAGENDA | DateTime |  | Dh. Última sincronização |  |
| IDSINCAGENDA | String |  | Identificador Agenda |  |
| TOKEN | String |  | Token |  |
| REFRESHTOKEN | String |  | Refresh Token |  |
| AUTHCODE | String |  | Código autorização |  |
| EMAILENVIADO | String |  | Email Enviado |  |
| EMAIL | String |  | Email |  |
| EXPIREIN | Integer |  | Expira em |  |
| DHTOKEN | DateTime |  | Dh. Token |  |
| SINCSTATUS | String |  | Status da Sincronização |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TCSSDN — Destinatários de Notificações SLA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMREG | Integer |  | Nro. Regra |  |
| SEQNOTIFICA | Integer |  | Sequência Notificação |  |
| SEQDEST | Integer |  | Sequência Destinatário |  |
| TIPODEST | String |  | Tipo de Destinatário | `A`=Atendente `G`=Gerente de Serviços `R`=Responsável `E`=Executante `C`=Consumidor BI |
| CODCON | Integer |  | Consumidor MSD |  |
| NUSLA | Integer |  | Nro. Único SLA |  |

## TCSSEM — Relacionamento serviço motivo
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODOCOROS | Integer |  | Ocorrência |  |
| CODPROD | Integer |  | Produto |  |

## TCSSER — Produtos e Serviços
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Serviço |  |
| LIMITANTE | String |  | Limitante | `N`=Não `S`=Sim |
| QTDEPREVISTA | Float |  | Quantidade prevista |  |
| FREQUENCIA | Integer |  | Freqüência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPO | String |  | Tipo |  |
| USAOSPORTAL | String |  | Usado em OS no portal | `N`=Não `S`=Sim |
| CODNAT | Integer |  | Cód. Natureza |  |

## TCSSES — Relacionamento serviço status
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSIT | Integer |  | Status |  |
| CODPROD | Integer |  | Produto |  |

## TCSSLA — Cadastro de SLA
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPOFILTRO | String |  | Tipo de Filtragem de Regras | `T`=Todas Regras combinando `P`=Primeira Regra combinando |
| CODCARGAHOR | Integer |  | Carga Horária |  |
| NUSLA | Integer |  | Nro. Único SLA |  |

## TCSSLN — Notificações SLA
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMREG | Integer |  | Nro. Regra |  |
| SEQNOTIFICA | Integer |  | Sequência local |  |
| TIPOALERTA | String |  | Tipo de Alerta | `M`=Mensagem Instantânea `E`=E-mail `C`=SMS `S`=Sonoro |
| DECORESTA | String |  | Decorrido/Restante | `R`=Restante `D`=Decorrido |
| TIPOTEMPO | String |  | Tipo de Tempo | `P`=Percentual `H`=Hora |
| VALORTEMPO | Integer |  | Tempo |  |
| RECORRENCIA | Integer |  | Recorrência |  |
| ARQSOM | String |  | Arquivo de Som |  |
| NUSLA | Integer |  | Nro. Único |  |

## TCSSLT — Tempo de SLA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | Sub-OS |  |
| TEMPOSLA | Integer |  | Tempo de SLA |  |
| SLADECORRIDO | Integer |  | SLA Decorrido |  |
| SLARESTANTE | Integer |  | SLA Restante |  |
| HORASUTEIS | String |  | HORASUTEIS | `N`=Não `S`=Sim |
| NUMOS | Integer |  | OS |  |

## TCSSNI — Notificação Item
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMREG | Integer |  | NUMREG |  |
| SEQNOTIFICA | Integer |  | SEQNOTIFICA |  |
| NUMOS | Integer |  | NUMOS |  |
| NUMITEM | Integer |  | NUMITEM |  |
| DHULTPOSTAGEM | DateTime |  | DHULTPOSTAGEM |  |
| NUSLA | Integer |  | NUSLA |  |

## TCSSNS — Notificação Sonora
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | Nro. Item |  |
| ARQSOM | String |  | Arquivo de som |  |
| NUMOS | Integer |  | Nro. OS |  |

## TCSSPN — Simulação preço Negociação
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Ateração |  |
| NUMOS | Integer |  | Núm. da OS |  |

## TCSSPNSEQ — Histórico simulação preço negociação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMOS | Integer |  | Núm. da OS |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Ateração |  |
| SEQPROPOSTA | Integer |  | Sequência |  |

## TCSSPT — Scripts
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DECRSCRIPT | String |  | Decrição |  |
| DHCRIACAO | DateTime |  | Data e Hota de Criação |  |
| CONTEUDO | String |  | Conteúdo |  |
| CODSCRIPT | Integer |  | Script |  |

## TCSTAC — Tipos de Ações
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEACAO | String |  | Nome |  |
| DESCRACAO | String |  | Descrição |  |
| MANIPULADOR | String |  | Manipulador |  |
| CODTIPACAO | Integer |  | Tipo Ação |  |

## TCSTFL — Transições por fluxo de processo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VARIACAO | Integer |  | Variação |  |
| CODSERVORIG | Integer |  | Cód. Serviço de origem |  |
| SEQUENCIAORIG | Integer |  | Sequencia de origem |  |
| CODSERVDEST | Integer |  | Cód. Serviço de destino |  |
| SEQUENCIADEST | Integer |  | Sequência de destino |  |
| CODPROD | Integer |  | Cód. Produto |  |

## TCSTFU — Tipo de Recursos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEFUNCAO | String |  | Função |  |
| DESCRFUNCAO | String |  | Descrição |  |
| ABREVFUNCAO | String |  | Abreviação |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODTIPFUNCAO | Integer |  | Código |  |

## TCSTPN — Tipo de Negociação Pré-venda
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODTPN | Integer |  | Código |  |

## TCSUMO — Usuários/Grupos por Modelo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Código |  |
| TIPO | String |  | Tipo |  |
| NUMOS | Integer |  | Num. Ordem Serviço |  |

## TCSVPC — Vendedores do Produto do Contrato
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMCONTRATO | Integer |  | Contrato |  |
| CODPROD | Integer |  | Produto |  |
| CODVEND | Integer |  | Vendedor |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPO | String |  | Tipo | `R`=Renegociação `U`=Usuário Adicional `N`=Nova Negociação `A`=Produto Adicional |
| VLRBASE | Float |  | Valor Base p/ Comissão |  |
| PERCCOM | Float |  | Percentual de Comissão |  |
| DTINI | Date |  | Data Inicial |  |
| DTFIM | Date |  | Data Final |  |
| NUNOTA | Integer |  | Nro. Único Pedido |  |
| OBSERVACAO | String |  | Observação |  |
| QTDFAT | Integer |  | Qtd. Faturada |  |
| DHALTER | DateTime |  | Dt./Hora Alteração |  |
| CODUSU | Integer |  | Cód. Usuário Alteração |  |