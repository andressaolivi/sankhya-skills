# TSE — Serviços / Helpdesk

> Gerado do dicionário oficial TDD Sankhya. 64 tabelas.


## TSERACJ — Ações Judiciais
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATAACAO | Date |  | Data da Ação Judicial |  |
| QTDACOES | Integer |  | OCORACAO |  |
| NATUREZA | String |  | Natureza da Ação |  |
| AVALISTA | String |  | Avalista | `S`=Sim `N`=Não |
| VALOR | Float |  | Valor |  |
| DISTRITO | Integer |  | Distrito |  |
| MOEDA | String |  | MOEDACAO |  |
| VARA | String |  | Vara |  |
| CIDUFACAO | String |  | Cidade/UF |  |
| CIDADE | String |  | CIDAACAO |  |
| UF | String |  | UFACAO |  |
| MSGSUBJUDICE | String |  | MSGSUBJUDICE |  |
| PRACASUBJUDICE | String |  | PRACAACO |  |
| DISTRITOSUBJUDICE | String |  | DISTRACO |  |
| VARASUBJUDICE | String |  | VARAACO |  |
| DATASUBJUDICE | DateTime |  | DATAACO |  |
| PROCESSOSUBJUDICE | String |  | PROCACO |  |
| CODNATUREZA | String |  | CDNATUACO |  |
| MSGSUBJUDICE2 | String |  | MSGSUBJUD |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| VALORTOTAL | Float |  | VALORTOTAL |  |
| CPFCNPJ | String |  | Documento CPF/CNPJ |  |
| VALORGERAL | Float |  | Valor |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERACS — Análise de Risco
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHCONSULTA | DateTime |  | Data da consulta |  |
| DOCUMENTO | String |  | Documento CPF/CNPJ |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| RESPOSTA | C |  | Resposta |  |
| URLENVIO | String |  | URL Enviada |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODPAP | Integer |  | Cód. Prospect |  |
| DTLIMITE | Date |  | Data de expiração da consulta |  |
| NUCONSULTA | Integer |  | Nro. Único |  |

## TSERALT — Endereço e Telefone Alternativos
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DDDDOTEL | Integer |  | DDD |  |
| NROFONE | String |  | DDD / Telefone |  |
| ENDERECO | String |  | Endereço |  |
| BAIRRO | String |  | Bairro |  |
| CEP | String |  | CEP |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| NOME | String |  | Nome do CPF |  |
| DTATUALIZA | Date |  | Data |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERANTEC — Antecessora
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| RAZAOANTEC | String |  | Razão Social Antecessor |  |
| DTMTANTEC | Date |  | Dt. de Motivo |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERASPC — Anotações SPC
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TPOPER | String |  | Comprador/Fiador/Avalista | `C`=Comprador |
| DATVEN | Date |  | Vencimento |  |
| NUMCON | String |  | Contrato |  |
| VLRDEB | Float |  | Valor |  |
| NOMASS | String |  | Associado Credor |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| NOMCON | String |  | NOMCON |  |
| ORIGEM | String |  | Origem |  |
| QTDOCOR | Integer |  | QTDOCOR |  |
| TOTDEB | Float |  | TOTDEB |  |
| MENSAGEM | String |  | MENSAGEM |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |
| DATINC | Date |  | Inclusão |  |

## TSERATV — Outras Atividades
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| OCUPACAO | String |  | Ocupação |  |
| PARTIC | Integer |  | % de participação |  |
| RENDA | Float |  | Renda |  |
| EMPRESA | String |  | Empresa |  |
| NUMCNPJ | String |  | CNPJ |  |
| DTADMISSAO | DateTime |  | Data admissão |  |
| CARGO | String |  | Cargo |  |
| ENDERECO | String |  | Endereço |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| CEP | Integer |  | CEP |  |
| DDD | Integer |  | DDD |  |
| TELEFONE | Integer |  | Telefone |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERBUR — Bureau
Campos: 45

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BANCO1CHQESP | String |  | Banco do Cheque Especial |  |
| CCBANCO1 | String |  | Banco |  |
| OCUPACAO | String |  | Ocupação |  |
| CCBANDEIRA1 | String |  | Bandeira |  |
| LIMITE1CHQESP | Float |  | Limite do Cheque Especial |  |
| RENDA | Float |  | Renda |  |
| BANCO2CHQESP | String |  | Banco do Cheque Especial |  |
| CARGO | String |  | Cargo |  |
| CCBANCO2 | String |  | Banco |  |
| CTSERIE | String |  | Série da Carteira de Trabalho |  |
| CCBANDEIRA2 | String |  | Bandeira |  |
| LIMITE2CHQESP | Float |  | Limite do Cheque Especial |  |
| NUMCT | String |  | Carteira de Trabalho |  |
| CCOUTREMIS | String |  | Outro emissor do Cartão de Crédito |  |
| EMPRESA | String |  | Empresa |  |
| CCBANDEIRA3 | String |  | Bandeira |  |
| DTADMISSAO | String |  | Data admissão |  |
| PROFISSAO | String |  | Profissão |  |
| CCTIPOSEGURO | String |  | Tipo de seguro |  |
| TIPOSEG | String |  | Tipo de seguro |  |
| TIPOSEG2 | String |  | Tipo de seguro |  |
| TIPOSEG3 | String |  | Tipo de seguro |  |
| TIPOSEG4 | String |  | Tipo de seguro |  |
| TIPOSEG5 | String |  | Tipo de seguro |  |
| OUTRRENDA | Float |  | Valor de Outras Rendas |  |
| RCSMSGFRASE | String |  | Msg. de risco |  |
| PERIODIC | Date |  | Periodicidade das Outras Rendas | `7`=Outra `6`=Anual `4`=Trimestral `3`=Bimestral `2`=Mensal_(+2)_ |
| RCSFATOR | Integer |  | Score |  |
| ORIGEM1 | String |  | Origem da 1ª Outra Renda | `9`=Outra `7`=Pró-labore `6`=Juros `5`=Aposentadoria `4`=Pensão_(+3)_ |
| CODIGODERETORNO | String |  | Código de retorno |  |
| TIPOSCORE | String |  | Descrição do Scoring escolhido |  |
| TAXA | String |  | Probabilidade de inadimplência |  |
| REFPESSOAL1 | String |  | Referência pessoal |  |
| REFDDD1 | Integer |  | DDD |  |
| REFFONE1 | Integer |  | Telefone |  |
| REFRAMAL1 | Integer |  | Ramal |  |
| REFPESSOAL2 | String |  | Referência pessoal |  |
| REFDDD2 | Integer |  | DDD |  |
| REFFONE2 | Integer |  | Telefone |  |
| REFRAMAL2 | Integer |  | Ramal |  |
| ORIGEM2 | String |  | Origem da 2ª Outra Renda | `9`=Outra `7`=Pró-labore `6`=Juros `5`=Aposentadoria `4`=Pensão_(+3)_ |
| RENDAFAML | Float |  | Outra renda familiar |  |
| FAMILIAR1 | String |  | Descrição do 1º  familiar que contribui com renda |  |
| FAMILIAR2 | String |  | Descrição do 2º  familiar que contribui com renda |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERCCC — Consulta Crédito e Cheque
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTOCORR | Date |  | Data |  |
| ORIGEM | String |  | Empresa |  |
| MODALIDADE | String |  | Modalidade |  |
| TIPOMOEDA | String |  | TIPOMOEDA |  |
| VALOR | Float |  | Valor |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERCNT — Contas do Perfil Financeiro
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECONTA | String |  | NOMECONTA |  |
| VLRCONTA | Float |  | VLRCONTA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TIPO | String |  | TIPO |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERCSFU — Cheques sem Fundos
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NMRCHEQUE | String |  | Número do cheque |  |
| ALIN | Integer |  | Alínea |  |
| QTDEBANCO | Integer |  | Quantidade no banco |  |
| VALOR | Float |  | Valor |  |
| BANCOCCF | String |  | Banco |  |
| AGENCIACCF | Integer |  | Agência |  |
| CIDACCF | String |  | Cidade |  |
| UFCCF | String |  | UF |  |
| CDNATU | String |  | Código da natureza |  |
| RESERVADOSERASA | String |  | ÁREA RESERVADA |  |
| MOEDA | String |  | Moeda |  |
| CCF | String |  | CCF | `S`=SIM `N`=NÃO |
| CPFCNPJ | String |  | Documento CPF/CNPJ |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| VALORTOTAL | Float |  | VALORTOTAL |  |
| QTDEOCOR | Integer |  | QTDEOCOR |  |
| DATAOCOR | Date |  | Data da ocorrência |  |

## TSERDAJ — Ações Judiciais
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NATUREZA | String |  | Natureza |  |
| DISTRIBUID | Integer |  | Distr |  |
| PRINCIPAL | String |  | Principal |  |
| VARA | Integer |  | Vara |  |
| CIDADE | String |  | Cidade |  |
| TIPOMOEDA | String |  | Tipo de moeda |  |
| UF | String |  | UF |  |
| DTOCORR | Date |  | Data |  |
| VALOR | Float |  | Valor |  |
| QTDEOCORR | Integer |  | Quantidade total de ocorrências |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERDCC — Detalhes de crédito e cheque
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| QTDETOTALCRED | Integer |  | QTDETOTALCRED |  |
| DATAATUALCRED | Date |  | DATAATUALCRED |  |
| QTDEATUALCRED | Integer |  | QTDEATUALCRED |  |
| QTDEMES1CRED | Integer |  | QTDEMES1CRED |  |
| QTDEMES2CRED | Integer |  | QTDEMES2CRED |  |
| QTDEMES3CRED | Integer |  | QTDEMES3CRED |  |
| QTDETOTALCHEQ | Integer |  | QTDETOTALCHEQ |  |
| QTDEATUALCHEQ | Integer |  | QTDEATUALCHEQ |  |
| QTDEMES1CHEQ | Integer |  | QTDEMES1CHEQ |  |
| QTDEMES2CHEQ | Integer |  | QTDEMES2CHEQ |  |
| QTDEMES3CHEQ | Integer |  | QTDEMES3CHEQ |  |
| POSICAO | Date |  | POSICAO |  |
| DATAFICAD | Date |  | DATAFICAD |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERDCHQ — Cheque sem fundo
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTOCORR | Date |  | Data da ocorrência |  |
| NUMCHEQUE | String |  | Número do cheque |  |
| ALINEA | Integer |  | Alínea da devolução do cheque |  |
| QTDE | Integer |  | Quantidade |  |
| BANCO | String |  | Banco |  |
| TIPOMOEDA | String |  | Tipo de moeda |  |
| AGENCIA | String |  | Agência |  |
| VALOR | Float |  | Valor do cheque devolvido |  |
| CONTA | Integer |  | Conta corrente |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| QTDEOCORR | Integer |  | Quantidade total de ocorrências |  |
| TIPOCONTA | String |  | Tipo de conta |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERDPROT — Protesto
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CARTORIO | Integer |  | Cartório |  |
| DTOCORR | DateTime |  | Data da ocorrência |  |
| CIDADE | String |  | Cidade |  |
| TIPOMOEDA | String |  | Tipo de moeda |  |
| UF | String |  | UF |  |
| DTPROT | Date |  | Data |  |
| VALOR | Float |  | Valor (R$) |  |
| QTDEOCORR | Integer |  | Quantidade total de ocorrências |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERDRE — Doc. Roubados, Furtados ou Extraviados
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPODOC | String |  | Tipo de documento |  |
| DESCTPDOC | String |  | Descrição do Tipo de Documento |  |
| NRODOC | String |  | Número do Documento |  |
| DATAOCORR | String |  | Data da Ocorrência |  |
| MOTIVOOCORR | String |  | Motivo da Ocorrência |  |
| DDDCONTATO | String |  | DDD |  |
| FONECONTATO | String |  | Telefone de Contato |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERDVENC — Dívida vencida
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTOCORR | Date |  | Data da ocorrência |  |
| MODALID | String |  | Modalidade |  |
| TIPOMOEDA | String |  | Tipo de moeda |  |
| VALOR | Float |  | Valor do título |  |
| TITULO | String |  | Número do título |  |
| ORIGEM | String |  | Instituição Cobradora |  |
| LOCAL | String |  | Local |  |
| QTDEOCORR | Integer |  | Quantidade total de ocorrências |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| VALORTOTAL | Float |  | VALORTOTAL |  |
| CPFCNPJ | String |  | Documento CPF/CNPJ |  |
| VALORGERAL | Float |  | Valor |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSEREVCF — Evolução do compromisso com o fornecedor
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANOEVO | Integer |  | ANOEVO |  |
| MESANO | String |  | Mês/Ano |  |
| AVENCER | Float |  | A Vencer |  |
| MESEVO | Integer |  | MESEVO |  |
| DESCRICAOMES | String |  | MESDESE |  |
| VENCIDOS | Float |  | VENC |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSEREVCFC — Evolução do compromisso com o fornecedor sumarizado visão cedente
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| MES | String |  | Mês/Ano |  |
| CODFAIXAVENC | String |  | Cód. da faixa vencidos |  |
| DESCRFAIXAVENC | String |  | Descrição da faixa vencidos |  |
| CODFAIXAAVEN | String |  | Cód. da faixa a vencer |  |
| DESCRFAIXAAVEN | String |  | Descrição da faixa a vencer |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSEREVCFI — Evolução do compromisso com o fornecedor sumarizado individual
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| MES | String |  | Mês/Ano |  |
| CODFAIXAVENC | String |  | Cód. da faixa vencidos |  |
| DESCRFAIXAVENC | String |  | Descrição da faixa vencidos |  |
| CODFAIXAAVEN | String |  | Cód. da faixa a vencer |  |
| DESCRFAIXAAVEN | String |  | Descrição da faixa a vencer |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSEREVCFS — Evolução do compromisso com o fornecedor sumarizado
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| MES | String |  | Mês/Ano |  |
| CODFAIXAVENC | String |  | Cód. da faixa vencidos |  |
| DESCRFAIXAVENC | String |  | Descrição da faixa vencidos |  |
| CODFAIXAAVEN | String |  | Cód. da faixa a vencer |  |
| DESCRFAIXAAVEN | String |  | Descrição da faixa a vencer |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERF900 — F900 GENÉRICO
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | CHAVE |  |
| CODFEAT | String |  | Feature |  |
| SUBTIPO | String |  | SUBTIPO |  |
| FATOR | Integer |  | SCORE |  |
| MENSAGEM | String |  | MENSAGEM |  |
| VALOR | Float |  | VALOR |  |
| APROVADO | String |  | APROVADO | `N`=Não `S`=Sim |
| GRAUAPROV | Integer |  | GRAU |  |
| TIPO | String |  | Tipo quando não ha dados |  |
| PRINAD | Float |  | Valor de posicionamento do ponteiro |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| MEDIA | String |  | Media |  |
| QTDAPROVREPROV | Integer |  | QUANTIDADE |  |
| DTPROC | Date |  | Data do processamento |  |
| CODRET | Float |  | Código de retorno |  |
| CAPACIDADE | Float |  | Capacidade |  |
| DTINC | Date |  | Data de inclusão |  |
| DTVENC | Date |  | Data de vencimento |  |
| NUMCON | String |  | Numero do contrato |  |
| CNPJASS | String |  | CNPJ associado |  |
| NOMASS | String |  | Nome associado |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| ORIGEM | String |  | Origem |  |
| QUANTATUAL | Integer |  | Quantidade de consultas do mês atual (0) |  |
| QUANTIDADE | Integer |  | Quantidade |  |
| QUANTMES1 | Integer |  | Quantidade de consultas do mês (-1) |  |
| QUANTMES2 | Integer |  | Quantidade de consultas do mês (-2) |  |
| QUANTMES3 | Integer |  | Quantidade de consultas do mês (-3) |  |
| QUANTMES4 | Integer |  | Quantidade de consultas do mês (-4) |  |
| QUANTMES5 | Integer |  | Quantidade de consultas do mês (-5) |  |
| QUANTMES6 | Integer |  | Quantidade de consultas do mês (-6) |  |
| REFMEN | String |  | Data da 1ª ocorrência |  |
| REFATUAL | String |  | Data da última ocorrência |  |
| REFMAI | String |  | Data da última ocorrência |  |
| DESCRICAO | String |  | Descrição |  |
| VLRTOT | Float |  | Valor total |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERFCONC — Falência e Concordata
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOFAC | String |  | Tipo |  |
| ORIGEMFAC | String |  | Origem |  |
| VARAFAC | String |  | Vara Civel |  |
| CIDAFAC | String |  | Cidade |  |
| UFFAC | String |  | UF |  |
| CPFCNPJ | String |  | CPFCNPJ |  |
| OCORFAC | Integer |  | QTDEOCOR |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DATAFAC | Date |  | Data |  |

## TSERFLC — Falência
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATAOCOR | DateTime |  | Data da ocorrência |  |
| TIPOOCOR | String |  | Tipo de ocorrência |  |
| CNPJPIE | String |  | CNPJ da empresa |  |
| EMPRESA | String |  | Nome da empresa da ocorrência |  |
| TOTALOCOR | Integer |  | Quantidade total de ocorrências no CPF |  |
| QUALIF | String |  | Código da qualificação |  |
| VARACIVIL | Integer |  | Vara Cível |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERGRAF — Grafias
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Grafia |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERHPQ — Histórico de pagamentos por quantidade
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DESCR1 | String |  | Pontual |  |
| VALOR1 | Float |  | Qtde |  |
| PERC1 | Integer |  | % |  |
| DESCR2 | String |  | 8-15 |  |
| VALOR2 | Float |  | Qtde |  |
| PERC2 | Integer |  | % |  |
| DESCR3 | String |  | 16-30 |  |
| VALOR3 | Float |  | Qtde |  |
| PERC3 | Integer |  | % |  |
| DESCR4 | String |  | 31-60 |  |
| VALOR4 | Float |  | Qtde |  |
| PERC4 | Integer |  | % |  |
| DESCR5 | String |  | +60 |  |
| VALOR5 | Float |  | Qtde |  |
| PERC5 | Integer |  | % |  |
| DESCR6 | String |  | A Vista |  |
| VALOR6 | Float |  | Qtde |  |
| QTDFONTESHISTPAG | Float |  | Fontes consultadas |  |
| PERC6 | Integer |  | % |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERHPQS — Histórico de pagamentos por quantidade sumarizado
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DESCRICAO | String |  | Descrição |  |
| CODFAIXA | String |  | Cód. da faixa |  |
| DESCRFAIXA | String |  | Descrição da faixa |  |
| PERCFAIXA | String |  | % da faixa |  |
| QTDFONTESHISTPAG | Float |  | Qtd de fontes do histórido de pgto |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERHPV — Histórico de pagamentos por valores
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| MES | DateTime |  | Mês/Ano |  |
| DESCR1 | String |  | Pontual |  |
| VALOR1 | Float |  | Valor |  |
| PERC1 | Integer |  | % |  |
| DESCR2 | String |  | 8-15 |  |
| VALOR2 | Float |  | Valor |  |
| PERC2 | Integer |  | % |  |
| DESCR3 | String |  | 16-30 |  |
| VALOR3 | Float |  | Valor |  |
| PERC3 | Integer |  | % |  |
| DESCR4 | String |  | 31-60 |  |
| VALOR4 | Float |  | Valor |  |
| PERC4 | Integer |  | % |  |
| DESCR5 | String |  | +60 |  |
| VALOR5 | Float |  | Valor |  |
| PERC5 | Integer |  | % |  |
| DESCR6 | String |  | P.M.A |  |
| VALOR6 | Float |  | Valor |  |
| PERC6 | Integer |  | % |  |
| DESCR7 | String |  | A VISTA |  |
| VALOR7 | Float |  | Valor |  |
| PERC7 | Integer |  | % |  |
| TOTAL | Float |  | Total Mês |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERHPVI — Histórico de pagamentos por valores sumarizados individual
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| MES | DateTime |  | Mês/Ano |  |
| DESCRICAO | String |  | Descrição |  |
| CODFAIXA | String |  | Cód. da faixa |  |
| DESCRFAIXA | String |  | Descrição da Faixa |  |
| PERCFAIXA | String |  | % da faixa |  |
| PMAFAIXA | String |  | PMA da faixa |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERHPVS — Histórico de pagamentos por valores sumarizado
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| MES | DateTime |  | Mês |  |
| DESCRICAO | String |  | Descrição |  |
| CODFAIXA | String |  | Cód. da faixa |  |
| DESCRFAIXA | String |  | Descrição da faixa |  |
| PERCFAIXA | String |  | % da faixa |  |
| PMAFAIXA | String |  | PMA da faixa |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERIMOV — Imoveis
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DESCRICAO | String |  | Tipo de bem |  |
| CIDADE | String |  | Cidade |  |
| VLRPRESTACAO | Float |  | Valor de prestação mensal |  |
| OUTRINFORM | String |  | Outras informações |  |
| PRESTREST | Integer |  | Número de prestações restantes |  |
| VLMERCADO | Float |  | Valor de mercado |  |
| UF | String |  | UF |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERIND — Indices do Perfil Financeiro
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INDICE | String |  | Índices |  |
| EMPRESA | Float |  | Empresa |  |
| PADRAO | Float |  | Padrão (Referência do Setor) |  |
| FORMA | String |  | FORMA | `V`=Valor `P`=Porcentagem |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERINGR — Informações Gerais Serasa
Campos: 58

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRSITRF | String |  | Situação |  |
| NOME | String |  | Nome |  |
| SITUACAORF | Integer |  | Situação da empresa | `6`=SUSPENSA `4`=NULA `2`=ATIVA `0`=INAPTA `7`=BAIXADA |
| DATANASC | Date |  | Data de nascimento |  |
| RAZAO | String |  | Razão social |  |
| NOMEFANTASIA | String |  | Nome fantasia |  |
| NOMEMAE | String |  | Nome da mãe |  |
| RAMOATV | String |  | Ramo de atividade |  |
| SEXO | String |  | Sexo | `M`=Masculino `F`=Feminino |
| TIPOSOCIEDADE | String |  | Tipo de sociedade |  |
| TIPRELATO | String |  | Tipo de Relato |  |
| NRUTRG | String |  | Registro |  |
| SITCPF | Integer |  | Situação do Cpf | `2`=REGULAR `1`=ATIVO `3`=PENDENTE DE REGULARIZAÇÃO |
| DTUTRG | Date |  | Data do registro |  |
| NIRE | String |  | Nire |  |
| ENDERECO | String |  | Endereço |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| CEP | String |  | Cep |  |
| FONECOM | String |  | Telefone |  |
| NRFAX | String |  | Fax |  |
| HOMEPAGE | String |  | Home Page |  |
| DATAFUND | Date |  | Data de fundação |  |
| FILIAIS | String |  | Filiais |  |
| NROFILIAIS | Integer |  | Qtde. Filiais |  |
| NUMEMPREGADOS | Integer |  | Qtde. empregados |  |
| RG | String |  | RG |  |
| NRODEPENDENTES | Integer |  | Qtde. dependentes |  |
| OPCAOTRIBUTARIA | String |  | Opção tributária |  |
| CNAE | String |  | CNAE |  |
| CODSERASA | String |  | Cód. Atividade Serasa |  |
| TIPODOC | String |  | Tipo de documento |  |
| EMISRG | String |  | Órgão emissor |  |
| PERCIMPORT | Integer |  | Imp. s/ Compras |  |
| DTRG | Date |  | Data de emissão |  |
| PERCEXPORT | Integer |  | Exp. s/ Vendas |  |
| UFRG | String |  | UF RG |  |
| ESTADOCIVIL | String |  | Estado civil | `9`=Outro `5`=Separado `4`=Divorciado `3`=Viúvo `2`=Solteiro_(+1)_ |
| ESCOLARIDADE | String |  | Escolaridade | `5`=Pós-Graduação `4`=Superior Incompleto `3`=Superior Completo `2`=2º Grau `1`=1º Grau |
| MUNNASC | String |  | Cidade de nascimento |  |
| UFNASC | String |  | UF Nascimento |  |
| CPFCONJUGE | String |  | CPF Cônjuge |  |
| DDDRES | String |  | DDD Residêncial |  |
| FONERES | String |  | Telefone residêncial |  |
| DDDCOM | String |  | DDD Comercial |  |
| CNPJ | String |  | CNPJ |  |
| RAMAL | Integer |  | Ramal |  |
| DTATUALIZACAO | Date |  | Data Atualização |  |
| CELULAR | String |  | Celular |  |
| CODMOSAIC | String |  | Código Mosaic |  |
| DDDCEL | String |  | DDD do Celular |  |
| MSGMOSAIC | String |  | Mensagem Mosaic |  |
| EMAIL | String |  | E-mail |  |
| DTRESIDECIA | Date |  | Residente desde |  |
| INSCRICAOESTADUAL | String |  | Inscrição estadual |  |
| DATACNPJ | Date |  | Data do Cnpj |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERMSGCONS — Mensagem da consulta
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODOPCAO | String |  | CODOPCAO |  |
| MSG | String |  | MSG |  |
| CODMSG | Integer |  | CODMSG |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSEROUTRBENS — Outros Bens
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| OUTRBEM | String |  | Outro bem |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERPART — Participações
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJCPF | String |  | CPF / CNPJ |  |
| CNPJCPFPARTICIPADA | String |  | CPF / CNPJ |  |
| NOMEPARTICIPANTE | String |  | Nome do Participante |  |
| CODEMBRATEL | String |  | CDEBPANTE |  |
| VINCULOPARTICIPANTE | String |  | Vínculo |  |
| MUNICIPIO | String |  | Cidade do participante |  |
| PERCENTUAL | Float |  | % Capital |  |
| UF | String |  | UF do participante |  |
| RESTRICAO | String |  | Anotações | `S`=Sim `N`=Não |
| SEQCNPJ | String |  | CNPJSEQPANTE |  |
| DIGCNPJ | String |  | DIGPANTE |  |
| TIPOPESSOA | String |  | IDENTPANTE |  |
| SITUACAORF | String |  | CDSITRFPANTE |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| EMPRESAPARTICIPADA | String |  | EMPLIGPADA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERPERF — Perfil Financeiro
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJ | String |  | CNPJ |  |
| RAZAO | String |  | Razão Social |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DTBALANCO | DateTime |  | Data |  |
| TIPOBALANCO | String |  | Padrão Contábil |  |
| DEMONSTRATIVO | String |  | Tipo de Demonstrativo |  |
| PERIODO | String |  | PDR |  |
| UNIDADE | String |  | Valor em |  |
| MOEDA | String |  | MOEDA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERPFAL — Participação em Falência
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOPIE | String |  | Tipo |  |
| CNPJ | String |  | CNJP |  |
| EMPRESAPIE | String |  | Empresa |  |
| CPFCNPJ | String |  | CPFCNPJ |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |
| QTDEOCOR | Integer |  | QTDEOCOR |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DATAOCOR | Date |  | Data da ação judicial |  |

## TSERPFIN — Pendências financeiras
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDPENDENCIA | Integer |  | QTDEOCOR |  |
| QTDULTOCOR | Integer |  | ULTOCOR |  |
| DTOCORRENCIA | Date |  | Data |  |
| DESCRICAO | String |  | Modalidade |  |
| AVALISTA | String |  | Avalista | `S`=Sim `N`=Não |
| VALOR | Float |  | Valor |  |
| CONTRATO | String |  | Contrato |  |
| ORIGEM | String |  | Origem |  |
| FILIAL | String |  | FILIAL |  |
| MSGSUBJUDICE | String |  | MSGSUBJUDICE |  |
| PRACA | String |  | PRACAPEF |  |
| DISTRITO | String |  | DISTRPEF |  |
| VARA | String |  | VARAPEF |  |
| DATASUBJUDICE | Date |  | Data |  |
| PROCESSO | String |  | PROCPEF |  |
| NATUREZA | String |  | CDNATUPEF |  |
| MSGSUBJUDICE2 | String |  | MSGSUBJUD |  |
| VALORTOTAL | Float |  | QTDEVALO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CPFCNPJ | String |  | CPFCNPJ |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERPPAG — Pendência de pagamento
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CONTRATO | String |  | Contrato |  |
| SIGLAMOD | String |  | Modalidade | `VL`=VEICULO LEVE `TT`=TELEF FIXA `TP`=RENEG DIVIDA `TM`=TELEF MOVEL `TF`=TELEF FIXA_(+71)_ |
| ORIGEM | String |  | Empresa |  |
| DTOCORR | Date |  | Data |  |
| TIPOMOEDA | String |  | Tipo de moeda |  |
| VALOR | Float |  | Valor |  |
| PRINCIPAL | String |  | Avalista? | `S`=Sim `N`=Não |
| FILIAL | String |  | Filial |  |
| QTDEOCORR | Integer |  | Total de ocorrências |  |
| CODBANCO | String |  | Código da instituição |  |
| SUBJUDX | String |  | Condição de Sub Judice |  |
| UF | String |  | UF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERPRCFORN — Principal fornecedor
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEFORNECEDOR | String |  | Nome |  |
| CNPJ | String |  | CNPJ |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERPROT — Protestos
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATAPROTESTO | Date |  | Data do Protesto |  |
| QTDPROTESTO | Integer |  | OCORPROT |  |
| VALOR | Float |  | Valor |  |
| CARTORIO | String |  | Cartório |  |
| MOEDA | String |  | MOEDPROT |  |
| CIDUFPROT | String |  | Cidade/UF |  |
| CIDADE | String |  | CIDAPROT |  |
| UF | String |  | UFPROT |  |
| MSGSUBJUDICE | String |  | MSGSUBJUDICE |  |
| PRACASUBJUDICE | String |  | PRACAPRO |  |
| DISTRITOSUBJUDICE | String |  | DISTRPRO |  |
| VARASUBJUDICE | String |  | VARAPRO |  |
| DATASUBJUDICE | DateTime |  | DATAPRO |  |
| PROCESSOSUBJUDICE | String |  | PROCPRO |  |
| CODNATUREZA | String |  | CDNATUPRO |  |
| TIPCARTAANUENCIA | String |  | TPANUEPROT |  |
| DTRECEBANUENCIA | DateTime |  | DTANUEPROT |  |
| MSGSUBJUDICE2 | String |  | MSGSUBJUD |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| VALORTOTAL | Float |  | VALORTOTAL |  |
| CPFCNPJ | String |  | CPFCNPJ |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERPSC — Participação societária
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EMPRESA | String |  | Razão social |  |
| CNPJ | String |  | CNPJ |  |
| PARTIC | Integer |  | Participação (%) |  |
| ESTADO | String |  | Estado |  |
| SITUACAO | String |  | Situação da Empresa |  |
| DTINIPARTIC | Date |  | Desde |  |
| DTULTATU | Date |  | Data da última atualização |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERQRA — Quadro administrativo
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPPESSOA | String |  | IDENTADM | `J`=Jurídica `F`=Física |
| CPFCNPJ | String |  | CPF / CNPJ |  |
| SEQCNPJ | String |  | CNPJSEQADM |  |
| DIGCPFCNPJ | String |  | DIGCPFADM |  |
| NOME | String |  | Administração |  |
| CARGO | String |  | Cargo |  |
| NACIONALIDADE | String |  | Nacionalidade |  |
| ESTADOCIVIL | String |  | Estado Civil |  |
| DTINIMANDATO | Date |  | Inicio mandato |  |
| DTFIMMANDATO | Date |  | Fim mandato |  |
| RESTRICAO | String |  | Restrição |  |
| CARGOADMIX | String |  | Cargo |  |
| SITUACAORF | String |  | CDSITRF |  |
| DTADMISSAO | Date |  | Entrada |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| MANDATO | String |  | Mandato |  |
| IDENTIDADE | String |  | Identidade |  |
| DTNASCIMENTO | Date |  | Data Nasc |  |
| NATURALDE | String |  | Natural de |  |
| TELEFONE | String |  | Telefone |  |
| VINCULO | String |  | Vínculo |  |
| ENDERECO | String |  | Endereço |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERQRS — Quadro societário
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CPFCNPJ | String |  | CPF/CNPJ |  |
| TIPPESSOA | String |  | Identif. pessoa |  |
| SOCIOS | String |  | Sócio/Acionista |  |
| DHADMISSAO | Date |  | Entrada |  |
| SEQCNPJ | String |  | Seq. CNPJ |  |
| DIGCPFCNPJ | String |  | Digito CNPJ |  |
| NACIONALIDADE | String |  | Nacionalidade |  |
| PERCENTUALVOTANTE | Float |  | Votante |  |
| PERCENTUAL | Float |  | Total |  |
| RESTRICAOSOCIO | String |  | Restrição do sócio |  |
| SITUACAORF | String |  | Situação da empresa |  |
| CODIGOSERASA | String |  | Cód. serasa |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TELEFONE | String |  | TELEFONE |  |
| ENDERECO | String |  | ENDERECO |  |
| DTFUNDACAO | Date |  | DTFUNDACAO |  |
| VINCULO | String |  | VINCULO |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRBCO — Referência bancaria
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DTABERTURA | Date |  | Data de abertura |  |
| BANCO | String |  | Banco |  |
| AGENCIA | Integer |  | Agência |  |
| CONTA | Integer |  | Conta |  |
| DDD | Integer |  | DDD |  |
| TELEFONE | Integer |  | Telefone |  |
| RAMAL | Integer |  | Ramal |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRCH — Cheque e Recheque
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECORRENT | String |  | Nome do Correntista |  |
| DTABERTURADACTA | DateTime |  | Data de Abertura da Conta Corrente |  |
| MSGSITUACTA | String |  | Mensagem da Situação da Conta Corrente |  |
| BANCO | Integer |  | Banco |  |
| AGENCIA | Integer |  | Agência |  |
| CTACORRENTE | Integer |  | Número da Conta Corrente |  |
| CHQINICIAL | Integer |  | Número do Cheque Inicial |  |
| CHQFINAL | Integer |  | Número do Cheque Final |  |
| MOTIVO | String |  | Motivo da Restrição do Cheque |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRCNC — Resumo do concentre
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Ocorrência |  |
| QTDETOTAL | Integer |  | Quantidade |  |
| DATAMENOR | String |  | Data da 1ª ocorrência |  |
| PERIODO | String |  | Período |  |
| DATAMAIOR | String |  | Data última ocorrência |  |
| VLRULTIMA | Float |  | Valor |  |
| ORIGEM | String |  | Mais Recente |  |
| UF | String |  | UF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRCSPC — Registro de consulta no SPC
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATCON | String |  | DATCON |  |
| HORCON | String |  | HORCON |  |
| NOMASS | String |  | NOMASS |  |
| CIDADE | String |  | CIDADE |  |
| UF | String |  | UF |  |
| ORIGEM | String |  | ORIGEM |  |
| QTCONS | Integer |  | QTCONS |  |
| CNPJCONS | String |  | CNPJCONS |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRECHE — Recheque
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BANCO | String |  | Banco |  |
| AGENCIA | Integer |  | Agência |  |
| CONTACORRENTE | Integer |  | Conta corrente |  |
| DIGITOCONTA | Integer |  | Dígito da conta |  |
| CHEQUEINICIAL | Integer |  | Cheque inicial |  |
| CHEQUEFINAL | Integer |  | Cheque final |  |
| MOTIVO | String |  | Motivo |  |
| CONTACORRENTEDOZE | Integer |  | Conta corrente |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |
| CPFCNPJ | String |  | Documento CPF/CNPJ |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| QTDOCO | Integer |  | QTDOCO |  |
| QTDULTOCO | Integer |  | QTDULTOCO |  |
| VALORGERAL | Float |  | Valor Geral |  |
| DATA | Date |  | Data |  |

## TSERRELFORN — Relacionamento com o fornecedor
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRPERIODO | String |  | Descrição |  |
| QUANTIDADE | Integer |  | Quantidade |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRESU — Resumos
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDRESUMO | Integer |  | Qtde |  |
| GRUPORESUMO | String |  | Discriminação |  |
| DESCRMESINI | String |  | MESIDES |  |
| PERIODO | String |  | Período |  |
| MESINI | Integer |  | MESI |  |
| VALOR | Float |  | Valor |  |
| ANOINI | Integer |  | ANOI |  |
| ORIGEM | String |  | Origem |  |
| AGENCIA | String |  | Praça |  |
| DESCRMESFIM | String |  | MESFDES |  |
| MESFIM | Integer |  | MESF |  |
| ANOFIM | Integer |  | ANOF |  |
| MOEDA | String |  | MOED |  |
| VALORTOTAL | Float |  | TOTALRES |  |
| NATUREZA | String |  | NATUREZA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRFIN — Referência financeira
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDREFERENCIA | Integer |  | QTDEOCOR |  |
| QTDULTOCOR | Integer |  | ULTOCOR |  |
| DTOCORRENCIA | Date |  | Data |  |
| DESCRICAO | String |  | Modalidade |  |
| AVALISTA | String |  | Avalista | `N`=Não `S`=Sim |
| VALOR | Float |  | Valor |  |
| CONTRATO | String |  | Contrato |  |
| ORIGEM | String |  | Origem |  |
| FILIAL | String |  | FILIAL |  |
| MSGSUBJUDICE | String |  | MSGSUBJUDICE |  |
| PRACA | String |  | PRACAPEF |  |
| DISTRITO | String |  | DISTRPEF |  |
| VARA | String |  | VARAPEF |  |
| DATASUBJUDICE | Date |  | Data |  |
| PROCESSO | String |  | PROCPEF |  |
| NATUREZA | String |  | CDNATUPEF |  |
| MSGSUBJUDICE2 | String |  | MSGSUBJUD |  |
| VALORTOTAL | Float |  | QTDEVALO |  |
| SEQUENCIA | Integer |  | SEQUENCIA | `N`=visivel |
| CPFCNPJ | String |  | CPFCNPJ |  |
| NUCONSULTA | Integer |  | NUCONSULTA | `N`=visivel |

## TSERRFN — Referêncial de negócio
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição do negócio |  |
| DTPOTENCIAL | Date |  | Data |  |
| VALORPOTENCIAL | Float |  | Valor |  |
| MEDIAPOTENCIAL | Float |  | Média |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRFNI — Referêncial de negócio sumarizado individual
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| MES | String |  | Mês/Ano |  |
| DESCRICAO | String |  | Descrição |  |
| CODFAIXAPOT | String |  | Cód. da faixa potencial |  |
| DESCRFAIXAPOT | String |  | Descrição da faixa potencial |  |
| CODFAIXAMED | String |  | Cód. da faixa média |  |
| DESCRFAIXAMED | String |  | Descrição da faixa média |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRFNS — Referêncial de negócio sumarizado
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| MES | String |  | Mês/Ano |  |
| DESCRICAO | String |  | Descrição |  |
| CODFAIXAPOT | String |  | Cód. da faixa potencial |  |
| DESCRFAIXAPOT | String |  | Descrição da faixa potencial |  |
| CODFAIXAMED | String |  | Cód. da faixa média |  |
| DESCRFAIXAMED | String |  | Descrição da faixa média |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRGC — Registros de consultas
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANOCONS | Integer |  | ANOCONS |  |
| MESCONS | Integer |  | MESCONS |  |
| MESDESCOM | String |  | MESDESCOM |  |
| QTDCONS | Integer |  | Qtde de Consultas no Dia |  |
| QTDBCOCONS | Integer |  | QTDBCOCONS |  |
| INDBCOEMP | String |  | INDBCOEMP |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERRLT — Relato
Campos: 40

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATAULTATCS | Date |  | Dt. últ. atualização das informações |  |
| VRCAPSOCCS | Float |  | Vlr. capital social |  |
| VRCAPREACS | Float |  | Vlr. capital realizado |  |
| VRCAPAUTCS | Float |  | Vlr. capital autorizado |  |
| DESCDNACS | String |  | Descr. nacionalidade |  |
| DESCDCRAOCS | String |  | Descr. origem |  |
| DESCPARCS | String |  | Descr. natureza |  |
| TIPRETCS | String |  | Controle societário c/ base na junta comercial |  |
| DHRISKSCO | DateTime |  | Data RiskScoring |  |
| FATORRISKSCO | Float |  | Fator RiskScoring |  |
| VLFATP | Float |  | Valor faturamento |  |
| FATPRESPONTOS | Integer |  | Pontuação |  |
| LIMCREDDHCALCULO | DateTime |  | Data do limite de crédito |  |
| LIMCREDVALOR | Float |  | Limite de crédito |  |
| LIMCREDOBS | String |  | Obs. limite de crédito |  |
| FRASEALERTA | String |  | Frase alerta |  |
| DATAALERTA | Date |  | Data de alerta |  |
| IDPJPONTUACAO | Integer |  | Pontuação |  |
| IDPJMENSPROD | String |  | Mensagem do produto |  |
| IDPJFRASE | String |  | Mensagem |  |
| IDPJVISAO | String |  | Visão |  |
| IRCPONTUACAO | Integer |  | Pontuação |  |
| IRCCLASSE | String |  | Classe |  |
| IRCINTERPRETACAO | String |  | Interpretação |  |
| IRCCODMENSAGEM | Integer |  | Cód. mensagem |  |
| IRCMENSAGEM | String |  | Mensagem |  |
| IRMVALOR | String |  | Valor |  |
| RCSFATOR | Integer |  | Score |  |
| RCSPRINY | Float |  | Valor priny |  |
| RCSMSGFRASE | String |  | Msg. de risco |  |
| FATPRESMSG | String |  | Mensagem |  |
| IRMFRASE | String |  | Frase |  |
| IRMDTATUALIZACAO | DateTime |  | Data de atualização |  |
| FATPRESFAIXADE | Integer |  | Faixa da pontuação DE |  |
| FATPRESFAIXAATE | Integer |  | Faixa da pontuação ATE |  |
| FATPRESFRASENCALC | String |  | Motivo de não cálculo |  |
| CODIGODERETORNO | String |  | Código de retorno |  |
| MENSAGEMGERENCIE | String |  | Mensagem de retorno do gerencie |  |
| MENSAGEMCONFIE | String |  | Mensagem de retorno do confie |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERSCRS — Score Socios Serasa
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DOC | Integer |  | DOC |  |
| FILIAL | Integer |  | FILIAL |  |
| DIGITO | Integer |  | DIGITO |  |
| SEQ | Integer |  | SEQ |  |
| VINCULO | String |  | VINCULO |  |
| NOME | String |  | NOME |  |
| RCSFATOR | Integer |  | Score |  |
| FAIXA | String |  | FAIXA |  |
| TAXA | Float |  | TAXA |  |
| CGC | String |  | CGC |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERSUS — Contumância e Sustação
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTOCORR | Date |  | Data da ocorrência |  |
| ORIGEM | String |  | Nome do Banco |  |
| AGENCIA | Integer |  | Agência |  |
| CONTACORR | Integer |  | Conta corrente |  |
| CHINICIAL | Integer |  | Número do cheque inicial |  |
| CHFINAL | Integer |  | Número do cheque final |  |
| MOTIVOSUSTA | String |  | Motivo da sustação |  |
| QTDEOCORR | Integer |  | Quantidade total de ocorrências |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERTCM — Total de consumo no mês
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANOCONS | Integer |  | ANOCONS |  |
| MESCONS | Integer |  | MESCONS |  |
| MESDESCR | String |  | MESDESCR |  |
| QTDCONS | Integer |  | QTDCONS |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERTMEI — Totais de mercado sumarizado individual
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DESCRICAO | String |  | Descrição |  |
| CODFAIXA | String |  | Cód. da faixa |  |
| DESCRFAIXA | String |  | Descrição da faixa |  |
| CODMEDFAIXA | String |  | Cód. da faixa média |  |
| DESCRMEDFAIXA | String |  | Descrição da faixa média |  |
| PERCFAIXA | String |  | % da faixa |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERTMER — Totais de mercado sumarizado
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DESCRICAO | String |  | Descrição |  |
| CODFAIXA | String |  | Cód. da faixa |  |
| DESCRFAIXA | String |  | Descrição da faixa |  |
| CODMEDFAIXA | String |  | Cód. da faixa média |  |
| DESCRMEDFAIXA | String |  | Descrição da faixa média |  |
| PERCMEDFAIXA | String |  | % médio da faixa |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERULC — Últimas consultas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATACONS | Date |  | Data da Consulta |  |
| CNPJCONS | String |  | CNPJ Consultante |  |
| RAZAOSOCIAL | String |  | Cliente consultante |  |
| QUANTIDADE | Integer |  | Qtde de consultas no dia |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |

## TSERVEI — Veiculos
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| MARCAVEIC | String |  | Marca do veículo |  |
| MODELOVEIC | String |  | Modelo do veículo |  |
| ANOVEIC | Integer |  | Ano/modelo do veículo |  |
| PLACAVEIC | String |  | Placa do veículo |  |
| VLPREST | Float |  | Valor da prestação |  |
| PRESTRESTVEIC | Integer |  | Prestações restantes |  |
| SEGVEIC | String |  | Indicativo se o veículo tem seguro |  |
| VENCTO | Date |  | Data de vencimento do seguro |  |
| NUCONSULTA | Integer |  | NUCONSULTA |  |