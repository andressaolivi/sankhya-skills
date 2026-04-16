# Demais tabelas (BH_, TAP, TCI, TGM, AUD, etc.)

> Gerado do dicionário oficial TDD Sankhya. 426 tabelas.


## ASTAJU — 
            Regras de ajuste da API de serviços tomados
        
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | 
                    Código
                 |  |
| CODREQ | Integer |  | 
                    Código da requisição
                 |  |
| CAMPO | String |  | 
                    Campo com inconsistência
                 |  |
| TIPCAMPO | String |  | 
                    Campo com inconsistência
                 |  |
| VLRORIG | String |  | 
                    Vlr original
                 |  |
| VLRCORRIG | String |  | 
                    Vlr corrigido
                 |  |
| TIPAJUSTE | String |  | 
                    Tipo de ajuste
                 |  |
| DHALTER | DateTime |  | 
                    Data de criação/alteração
                 |  |

## ASTINC — 
            Inconsistência da API de serviços tomados
        
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | 
                    Código
                 |  |
| CODREQ | Integer |  | 
                    Código da requisição
                 |  |
| TIPINC | String |  | 
                    Código da requisição
                 | `M`=
                        Nota modelo
                     `P`=
                        Prestador
                     `S`=
                        Serviço
                     `G`=
                        Generica
                     |
| CAMPO | String |  | 
                    Campo com inconsistência
                 |  |
| TIPCAMPO | String |  | 
                    Campo com inconsistência
                 |  |
| VLRORIG | String |  | 
                    Vlr original
                 |  |
| MSGERRO | String |  | 
                    Mensagem de erro
                 |  |
| STATUS | String |  | 
                    Status
                 | `P`=
                        Pendente
                     `C`=
                        Corrigida
                     |
| DHALTER | DateTime |  | 
                    Data de criação/alteração
                 |  |

## ASTREQ — 
            Requisições da API de serviços tomados
        
Campos: 41

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| STATUSNOTA | String |  | 
                    Status da Nota
                 | `null`=
                        NF não encontrada
                     `A`=
                        Atendimento
                     `L`=
                        Confirmada
                     `P`=
                        Pendente
                     |
| XMLNOTA | C |  | 
                    XML Importado da Asis
                 |  |
| CODIGO | Integer |  | 
                    ID da requisição
                 |  |
| JSONREQ | C |  | 
                    JSON da requisição
                 |  |
| JSONAJU | C |  | 
                    JSON ajustadoa
                 |  |
| DHALTER | DateTime |  | 
                    Data de alteração
                 |  |
| NUNOTA | Integer |  | 
                    Nota Integrada
                 |  |
| NUMNFSE | String |  | 
                    Nro. Nota
                 |  |
| IDUNICAREQ | String |  | 
                    ID único de requisição
                 |  |
| STATUS | String |  | 
                    Status Integração
                 | `N`=
                         Não processado 
                     `D`=
                         Com divergencia 
                     `P`=
                         Processado 
                     `R`=
                         Disp. para Reprocessamento 
                     `C`=
                         Cancelado 
                     |
| CODEMP | Integer |  | 
                    Empresa
                 |  |
| CODPARC | Integer |  | 
                    Fornecedor
                 |  |
| CODPROD | Integer |  | 
                    Serviço
                 |  |
| CODTIPOPER | Integer |  | 
                    Tipo operação
                 |  |
| DHTIPOPER | DateTime |  | 
                    DH Tipo Operação
                 |  |
| DTCANCELAMENTO | DateTime |  | 
                    Data de Cancelamento
                 |  |
| DTEMISSAO | DateTime |  | 
                    Data de Emissão
                 |  |
| CODCIDISS | Integer |  | 
                    Cidade ISS Devido
                 |  |
| CODCIDPRE | Integer |  | 
                    Cidade de Prestação
                 |  |
| NRPROTASIS | String |  | 
                    Protocolo de Integração
                 |  |
| CNPJPRESTADOR | String |  | 
                    CNPJ do Prestador
                 |  |
| CODVERIFNFSE | String |  | 
                    C?digo Verificador da NFSe
                 |  |
| DTCOMPETENCIA | DateTime |  | 
                    Data de Competencia
                 |  |
| BASECALCULOISS | Float |  | 
                    Base de Calculo ISS
                 |  |
| VALORLIQUIDO | Float |  | 
                    Valor Liquido da NFe
                 |  |
| BASECALCULOCSRF | Float |  | 
                    Base de Calculo CSRF
                 |  |
| VALORPIS | Float |  | 
                    Valor PIS
                 |  |
| ALIQUOTAPIS | Float |  | 
                    Aliquota PIS
                 |  |
| VALORCOFINS | Float |  | 
                    Valor COFINS
                 |  |
| ALIQUOTACOFINS | Float |  | 
                    Aliquota COFINS
                 |  |
| VALORCSLL | Float |  | 
                    Valor CSLL
                 |  |
| ALIQUOTACSLL | Float |  | 
                    Aliquota CSLL
                 |  |
| BASECALCULOIRRF | Float |  | 
                    Base de Calculo IRRF
                 |  |
| ALIQUOTAIRRF | Float |  | 
                    Aliquota IRRF
                 |  |
| VALORIRRF | Float |  | 
                    Valor IRRF
                 |  |
| BASECALCULOINSS | Float |  | 
                    Base de Calculo INSS
                 |  |
| ALIQUOTAINSS | Float |  | 
                    Aliquota INSS
                 |  |
| VALORINSS | Float |  | 
                    Valor INSS
                 |  |
| SERIERPS | String |  | 
                    Série RPS
                 |  |
| CNPJTOMA | String |  | 
                    CNPJ do Tomador
                 |  |
| VLRTOTALNOTA | Float |  | 
                    Valor Total da Nota
                 |  |

## AUDITTFPAGE — Auditoria TFPAGE
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| VLRANT | String |  | VLRANT |  |
| VLRNOVO | String |  | VLRNOVO |  |
| CAMPO | String |  | CAMPO |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |

## AUDITTFPBAS — Auditoria da TFPBAS
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| TIPO | String |  | TIPO |  |
| STATUS | String |  | STATUS |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |
| ID | Integer |  | ID |  |

## AUDITTFPFOL — Auditoria da TFPFOL
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| TIPEVENTO | Integer |  | TIPEVENTO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| VLRANT | String |  | VLRANT |  |
| VLRNOVO | String |  | VLRNOVO |  |
| CAMPO | String |  | CAMPO |  |
| TIPO | String |  | TIPO |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |
| ID | Integer |  | ID |  |

## AUDITTFPMOV — Tabela de auditorias dos movimentos da folha
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPMOV | String |  | TIPMOV |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| VLRANT | String |  | VLRANT |  |
| VLRNOVO | String |  | VLRNOVO |  |
| CAMPO | String |  | CAMPO |  |
| STATUS | String |  | STATUS |  |
| TIPO | String |  | TIPO |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |
| ID | Integer |  | ID |  |

## AULAS — Aula Universidade
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID_CURSO | Integer |  | ID_CURSO |  |
| NM_AULA | String |  | Nome da aula |  |
| NM_VIDEO | String |  | Nome do vídeo |  |
| DURACAO_VIDEO | Integer |  | Duração do vídeo |  |
| SORTORDER | Integer |  | SORTORDER |  |
| FORMATO | String |  | Formato | `Y`=Youtube `P`=PDF `Q`=Quiz `M`=MP4 `J`=MP4 + JPG_(+1)_ |
| ID | Integer |  | Código |  |

## AULA_ALUNOS — TABLE AULA_ALUNOS
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID_AULA | Integer |  | ID_AULA |  |
| ALUNO | Integer |  | ALUNO |  |
| DT_INICIO | Integer |  | DT_INICIO |  |
| DT_ULTIMO_ACESSO | Integer |  | DT_ULTIMO_ACESSO |  |
| STATUS | Integer |  | STATUS |  |
| TEMPO_PERMANECIDO | Integer |  | TEMPO_PERMANECIDO |  |
| QTDACESSOS | Integer |  | QTDACESSOS |  |
| ID | Integer |  | ID |  |

## BHMKT_CATALOGO — View Catálogo
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROMOTIONAL_PRICE | Integer |  | PROMOTIONAL_PRICE |  |
| VARIACAO | String |  | VARIACAO |  |
| QTDVIRTUAL | Float |  | QTDVIRTUAL |  |
| VIRTUAL | String |  | VIRTUAL |  |
| ESTOQUE | Integer |  | ESTOQUE |  |
| ATIVO | String |  | ATIVO |  |
| CODMKT | Integer |  | CODMKT |  |
| NOME | String |  | NOME |  |
| CODPARC | Integer |  | CODPARC |  |
| CODTAB | Integer |  | CODTAB |  |
| CODPROD | Integer |  | CODPROD |  |
| PRICE | Integer |  | PRICE |  |

## BHMKT_ESTALT — VIEW BHMKT_ESTALT
Campos: 0

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|

## BHMKT_ESTEXC — Estoque e Preço Catálogo
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ESTOQUE | Integer |  | ESTOQUE |  |
| PROMOTIONAL_PRICE | Integer |  | PROMOTIONAL_PRICE |  |
| PRICE | Integer |  | PRICE |  |
| CODPROD | Integer |  | CODPROD |  |

## BHMKT_EXP — View Expedição
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RASTREIO | String |  | RASTREIO |  |
| NOMEPARC | String |  | NOMEPARC |  |
| CHAVE | String |  | CHAVE |  |
| DTEXP | DateTime |  | DTEXP |  |
| BH_CODEMKT | String |  | BH_CODEMKT |  |
| HOMEPAGE | String |  | HOMEPAGE |  |
| CODPARC | Integer |  | Cód Parceiro |  |

## BH_CONFIGB2W — Configuração B2W
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| RECDESP | Integer |  | Receita/Despesa |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| CODCTABCOINT | Integer |  | Código da conta bancária |  |
| CODCENCUS | Integer |  | Código |  |
| CODBCO | Integer |  | Cód. Banco |  |
| CODNAT | Integer |  | Cód. Natureza |  |

## BH_FINCAB — Fila Entregues
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTALTER | DateTime |  | DTALTER |  |
| CODSTATUS | Integer |  | CODSTATUS |  |
| DTENTREGA | Date |  | DTENTREGA |  |
| STATUS | String |  | STATUS |  |
| QTDTENTATIVAS | Integer |  | QTDTENTATIVAS |  |
| DTEFETIVA | String |  | DTEFETIVA |  |
| JSON | C |  | JSON |  |
| BH_CODEMKT | String |  | BH_CODEMKT |  |
| BH_LOJA | String |  | BH_LOJA |  |
| NUNOTA | Integer |  | NUNOTA |  |

## BH_IMPB2WCAB — Importação B2W Cabeçalho
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| DHIMPORT | Date |  | Dt. Importação |  |

## BH_IMPB2WCAN — Importação B2W Cancelados
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ROWNUMBER | Integer |  | Rownumber |  |
| ID | String |  | ID |  |
| DTPED | Date |  | Dt. Pedido |  |
| DTPREV | Date |  | Dt. Prevista |  |
| VALOR | Float |  | Valor |  |
| TIPO | String |  | Tipo |  |
| CODMKT | String |  | Cód. Integração |  |

## BH_IMPB2WDEV — Importação B2W Devoluções
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMKT | String |  | CODMKT |  |
| ID | String |  | ID |  |
| DTPED | Date |  | Dt. Pedido |  |
| NUFIN | Integer |  | N° Único Fin. |  |
| VALOR | Float |  | Valor |  |
| VLRDESDOB | Float |  | Vlr. Financeiro |  |
| PENDENCIA | String |  | Pendência | `S`=Sim `N`=Não |
| DIFERENCA | Float |  | Diferença |  |
| LIQUIDADO | String |  | Liquidado | `S`=Sim `N`=Não |
| VLRJUROS | Float |  | Vlr. Juros |  |
| DIF_BAIXA | Float |  | Dif. na Baixa |  |
| DHBAIXA | Date |  | Dt. Baixa |  |

## BH_IMPB2WPEN — Importação B2W Pendências
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| ROWNUMBER | Integer |  | Rownumber |  |
| DTPED | Date |  | Dt. Pedido |  |
| DTPREV | Date |  | Dt. Prevista |  |
| VALOR | Float |  | Valor |  |
| TIPO | String |  | Tipo |  |
| RESOLVIDO | String |  | Resolvido | `S`=Sim `N`=Não |
| CODMKT | String |  | Cód. Integração |  |

## BH_IMPB2WVEN — Importação B2W Vendas
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| CODMKT | String |  | Cód. Integração |  |
| DTPED | Date |  | Dt. Pedido |  |
| VALOR | Float |  | Valor |  |
| NUFIN | Integer |  | N° Único Fin. |  |
| VLRDESDOB | Float |  | Vlr. Financeiro |  |
| DHBAIXA | Date |  | Dt. Baixa |  |
| PENDENCIA | String |  | Pendência | `S`=Sim `N`=Não |
| LIQUIDADO | String |  | Liquidado? | `S`=Sim `N`=Não |
| DIFERENCA | Float |  | Diferença |  |
| VLRIPI | Float |  | Vlr. IPI |  |
| VLRJUROS | Float |  | Vlr. Juros |  |
| DIF_BAIXA | Float |  | Dif. Baixa |  |
| ROWNUMBER | Integer |  | Rownumber |  |

## BH_MKTABCPRO — Produtos A,B,C
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLOJA | Integer |  | CODLOJA |  |
| CODPROD | Integer |  | CODPROD |  |
| ATIVO | String |  | ATIVO | `2`=Desligado `1`=Ligado |
| BH_ID_SKU | String |  | BH_ID_SKU |  |
| BH_ID | String |  | BH_ID |  |
| CODPRODABC | String |  | CODPRODABC |  |

## BH_MKTCAMPANHA — Campanhas Market Place
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCAMP | Integer |  | Nro Campanha |  |
| ATIVO | Integer |  | Ativo? | `1`=Sim `2`=Nao |
| NOME | String |  | Nome da Campanha |  |
| CODLOJA | Integer |  | Loja de Conexao |  |
| CODVEND | Integer |  | Vendedor |  |
| DTINICIO | DateTime |  | Data de Inicio |  |
| DTFIM | DateTime |  | Data Final |  |
| PRECO_DE | Float |  | Preco De |  |
| PRECO_POR | Float |  | Preco Por |  |
| OBSERVACAO | String |  | Observacao |  |
| CODPROD | Integer |  | Cod Produto |  |

## BH_MKTCAT — Categorias Market Place
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOPROD | Integer |  | CODGRUPOPROD |  |
| CODGRUPAI | Integer |  | CODGRUPAI |  |
| BH_ID | String |  | BH_ID |  |
| BH_LOJA | String |  | BH_LOJA |  |
| DESCRGRUPOPROD | String |  | DESCRGRUPOPROD |  |

## BH_MKTCATMELI — Categorias Mercado Livre
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GRAU | Integer |  | GRAU |  |
| ANALITICO | String |  | ANALITICO |  |
| MLBPAI | Integer |  | MLBPAI |  |
| DESCRICAO | String |  | DESCRICAO |  |
| MLBMELI | String |  | MLBMELI |  |
| MLB | Integer |  | MLB |  |

## BH_MKTCD — Centros de Distribuição
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCD | Integer |  | Cód CD |  |
| CNPJ | String |  | CNPJ |  |
| CODEMP | Integer |  | Cód Empresa |  |
| STORE_CODE | String |  | Store Code |  |
| CODLOJA | Integer |  | Cód Loja |  |

## BH_MKTCDPRO — Centros Distribuição Produtos
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | ATIVO |  |
| CODPROD | Integer |  | CODPROD |  |
| CODLOJA | Integer |  | CODLOJA |  |
| CODCD | Integer |  | CODCD |  |

## BH_MKTCODEHTTP — Cód Retorno HTTP Skyhub
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRSTATUS | String |  | Descrição Status |  |
| COMPLSTATUS | String |  | Complemento |  |
| CODSTATUS | Integer |  | Cód Status |  |

## BH_MKTEMBPRO — Embalagens de Volume
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUEMB | Integer |  | Nro Embalagem |  |
| COMPRIMENTO | Float |  | Comprimento |  |
| ALTURA | Float |  | Altura |  |
| LARGURA | Float |  | Largura |  |
| PESO | Float |  | Peso |  |
| ESPESSURA | Float |  | Espessura |  |
| CODPROD | Integer |  | Cód Produto |  |

## BH_MKTEXPCAB — Fila de Expedição
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód Parceiro |  |
| DTEXP | DateTime |  | Data Expedição |  |

## BH_MKTEXPITE — Fila de Expedição Itens
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | CODPARC |  |
| CHAVENFE | String |  | CHAVENFE |  |
| DTALTER | DateTime |  | DTALTER |  |
| NUNOTA | Integer |  | NUNOTA |  |
| CODSTATUS | Integer |  | CODSTATUS |  |
| BH_CODEMKT | String |  | BH_CODEMKT |  |
| BH_LOJA | String |  | BH_LOJA |  |
| INTEGRADOR | String |  | INTEGRADOR |  |
| QTDTENTATIVAS | Integer |  | QTDTENTATIVAS |  |
| JSON | C |  | JSON |  |
| RETORNO | String |  | RETORNO |  |
| CODSTATUSINTELIPOST | Integer |  | CODSTATUSINTELIPOST |  |
| DTEXP | DateTime |  | DTEXP |  |

## BH_MKTITENS — Itens do Pedido
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODPROD | Integer |  | CODPROD |  |
| QTDNEG | Integer |  | QTDNEG |  |
| VLRUNIT | Float |  | VLRUNIT |  |
| VLRDESCTOT | Float |  | VLRDESCTOT |  |
| CODPRODORIG | String |  | CODPRODORIG |  |
| CODPRODEXT | String |  | CODPRODEXT |  |
| NUNOTA | Integer |  | NUNOTA |  |

## BH_MKTJOBS — Configurações JOBs
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTPROEXE | DateTime |  | Dt. Próxima Execução |  |
| CODLOJA | Integer |  | CODLOJA |  |
| DTULTEXE | DateTime |  | Dt. Última Execução |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| TEMPO | Integer |  | Tempo(em Minutos) |  |
| DESCRJOB | String |  | Nome |  |
| DOCUMENTACAO | String |  | Documentação |  |
| SQL | String |  | SQL |  |
| NUJOB | Integer |  | Nro Job |  |

## BH_MKTKONCILI — Koncili
Campos: 40

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OI | String |  | OI |  |
| CHANNELSTATUS | String |  | CHANNELSTATUS |  |
| INTERNALSTATUS | String |  | INTERNALSTATUS |  |
| ORDERCODE | String |  | ORDERCODE |  |
| ORDERDATE | DateTime |  | ORDERDATE |  |
| PAIDDATE | DateTime |  | PAIDDATE |  |
| INVOICENUMBER | String |  | INVOICENUMBER |  |
| INVOICEDATE | DateTime |  | INVOICEDATE |  |
| SENTDATE | DateTime |  | SENTDATE |  |
| ORDERID | String |  | ORDERID |  |
| ORIGIN | String |  | ORIGIN |  |
| PAYMENTMETHOD | String |  | PAYMENTMETHOD |  |
| PLOTVALUE | Float |  | PLOTVALUE |  |
| TOTALVALUE | Float |  | TOTALVALUE |  |
| PLOTSQUANTITY | Integer |  | PLOTSQUANTITY |  |
| PLOTNUMBER | Integer |  | PLOTNUMBER |  |
| EXTRACTTYPE | String |  | EXTRACTTYPE |  |
| EXPECTEDVALUE | Float |  | EXPECTEDVALUE |  |
| RELEASEDVALUE | Float |  | RELEASEDVALUE |  |
| EXPECTEDPERCENTUALCOMISSION | Float |  | EXPECTEDPERCENTUALCOMISSION |  |
| RELEASEDPERCENTUALCOMISSION | Float |  | RELEASEDPERCENTUALCOMISSION |  |
| EXPECTEDDATE | DateTime |  | EXPECTEDDATE |  |
| RELEASEDDATE | DateTime |  | RELEASEDDATE |  |
| SITUATION | String |  | SITUATION |  |
| CONCILIED | String |  | CONCILIED |  |
| OBSERVATION | String |  | OBSERVATION |  |
| CONCILIATIONID | Integer |  | CONCILIATIONID |  |
| CHANNEL | String |  | CHANNEL |  |
| RESOLVEDINERP | String |  | RESOLVEDINERP |  |
| ORDERIDHUBORIGIN | String |  | ORDERIDHUBORIGIN |  |
| ACCOUNTNAME | String |  | ACCOUNTNAME |  |
| CUSTOMERNAME | String |  | CUSTOMERNAME |  |
| CUSTOMERDOCUMENTNUMBER | String |  | CUSTOMERDOCUMENTNUMBER |  |
| CONCILIATIONINITDATE | DateTime |  | CONCILIATIONINITDATE |  |
| CONCILIATIONENDDATE | DateTime |  | CONCILIATIONENDDATE |  |
| CONCILIATIONCLOSEDATE | DateTime |  | CONCILIATIONCLOSEDATE |  |
| PARTIALCONCILIED | String |  | PARTIALCONCILIED |  |
| ORIGINALVALUE | Float |  | ORIGINALVALUE |  |
| RETORNO_KONCILI | String |  | RETORNO_KONCILI |  |
| ID | Integer |  | ID |  |

## BH_MKTLOGEXC — Logs Place Comunicação
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| METODO | String |  | METODO |  |
| CLASSE | String |  | CLASSE |  |
| PKORID | String |  | PKORID |  |
| JSON | C |  | JSON |  |
| DTALTER | DateTime |  | DTALTER |  |
| LOG | C |  | LOG |  |
| NULOG | Integer |  | NULOG |  |

## BH_MKTLOJAS — Lojas de Conexão
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| STATUS | Integer |  | Status Loja | `2`=Desligado `1`=Ligado |
| NOME | String |  | Nome Loja |  |
| IPCONEXAO | String |  | Ip Conexão Loja |  |
| LOGIN | String |  | Login |  |
| SENHA | String |  | Senha |  |
| TOKEN | String |  | Token |  |
| CODUSU | Integer |  | Código Usuário Pedidos |  |
| KEYACCOUNT | String |  | Keyaccount |  |
| NOMEPLA | String |  | Plataforma | `Koncili`=Koncili `AnyMarket`=AnyMarket `Intelipost`=Intelipost `Magazine Luiza`=Magazine Luiza `TrayCorp`=TrayCorp_(+3)_ |
| IPCONEXAOFILA | String |  | Ip Conexão Fila |  |
| SQL_PRODUTO | String |  | SQL_PRODUTO |  |
| SQL_PRECO | String |  | SQL_PRECO |  |
| SQL_ESTOQUE | String |  | SQL_ESTOQUE |  |
| SQL_ATRIBUTOS | String |  | SQL_ATRIBUTOS |  |
| CODLOJA | Integer |  | Código Loja |  |

## BH_MKTLOJPRO — Lojas de Conexão de Produtos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | CODPROD |  |
| ATIVO | String |  | ATIVO | `2`=Desligado `1`=Ligado |
| BH_ID | String |  | BH_ID |  |
| BH_ID_SKU | String |  | BH_ID_SKU |  |
| CODLOJA | Integer |  | CODLOJA |  |

## BH_MKTMAR — Marcas Market Place
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BH_ID | String |  | BH_ID |  |
| BH_LOJA | String |  | BH_LOJA |  |
| DESCRICAO | String |  | Descrição |  |

## BH_MKTNOTAS — Fila de Notas Fiscais
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVENFE | String |  | CHAVENFE |  |
| DTALTER | DateTime |  | DTALTER |  |
| QTDTENTATIVAS | Integer |  | QTDTENTATIVAS |  |
| CODSTATUS | Integer |  | CODSTATUS |  |
| DTORIGEM | DateTime |  | DTORIGEM |  |
| BH_LOJA | String |  | BH_LOJA |  |
| JSON | C |  | JSON |  |
| RETORNO | String |  | RETORNO |  |
| BH_CODEMKT | String |  | Cód Integração |  |
| CODSTATUSNFE | Integer |  | CODSTATUSNFE |  |
| JSONNFE | C |  | JSONNFE |  |
| RETORNONFE | String |  | RETORNONFE |  |
| AD_CODSTATUSETIQUETA | Integer |  | Etiqueta |  |
| NUNOTA | Integer |  | NUNOTA |  |

## BH_MKTPLACES — Market Places
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BH_LOJA | String |  | BH_LOJA |  |
| SQL | String |  | SQL |  |
| NOME | String |  | NOME |  |

## BH_MKTSALES — Canais de Vendas - Skyhub
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAB | Integer |  | Tabela de Preços |  |
| CODMKT | Integer |  | Cód Canal |  |
| CODPARC | Integer |  | Parceiro |  |
| NOME | String |  | Canal |  |

## BH_MKTSALESITE — Catálogo MKT Itens
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Código do Produto |  |
| PRICE | Float |  | Preço |  |
| DESCONTO | Float |  | % Desconto/Acréscimo |  |
| ASCRESCIMO | Float |  | Valor Desconto/Acréscimo |  |
| PROMOTIONAL_PRICE | Float |  | Preço Promocional |  |
| SINAL | String |  | Sinal | `1`=Acréscimo `-1`=Desconto |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ALTERNATIVO | String |  | Alternativo |  |
| ESTOQUE | Float |  | Estoque |  |
| STATUS | String |  | Status |  |
| VIRTUAL | String |  | Estoque Virtual? | `N`=Não `S`=Sim |
| CLASSIFICACAO | String |  | Classificação Estoque |  |
| QTDVIRTUAL | Float |  | Qtd Estoque Virtual |  |
| CODMKT | Integer |  | Código MKT |  |

## BH_MKTSHI — Rastreios Market Place
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| RASTREIO | String |  | RASTREIO |  |
| METODO | String |  | METODO |  |
| CARRIER | String |  | CARRIER |  |
| AD_PLP | String |  | PLP |  |
| AD_COLETA | String |  | AD_COLETA |  |
| AD_ROTABASE | String |  | Rota Base |  |
| AD_LETRADEST | String |  | Letra Destino |  |
| AD_ROTAMESTRE | String |  | ROTA MESTRE |  |
| BH_CODEMKT | String |  | BH_CODEMKT |  |

## BH_MKTSKUMKTPLACE — Publicações Market Place
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | CODPROD |  |
| LOJA | String |  | LOJA |  |
| DTORIGEM | DateTime |  | DTORIGEM |  |
| ACCOUNT_NAME | String |  | Nome da Conta |  |
| MARKETPLACE | String |  | Market Place |  |
| IDMARKETPLACE | String |  | ID no Market Place |  |
| SKUMARKETPLACE | String |  | SKU Market Place |  |
| STATUS | String |  | Status |  |
| MARKETPLACE_STATUS | String |  | Status Market Place |  |
| PRICE | Float |  | Preço |  |
| LISTPRICE | Float |  | Preço De |  |
| FREE_SHIPPING | String |  | Frete Grátis? |  |
| SHIPPING_LOCAL | String |  | Retira em Mãos? |  |
| FULFILLMENT | String |  | FulFillment? |  |
| SHIPPING_MODE | String |  | Modo de Envio |  |
| TIPOANUNCIO | String |  | Tipo de Anúncio |  |
| JSON | C |  | JSON |  |
| JSON_RETORNO | C |  | JSON_RETORNO |  |
| BH_ID_MARKETPLACE | Integer |  | ID Externo |  |
| NUFILA | Integer |  | NUFILA |  |

## BH_MKTSPECS — Especificações Produto
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome da Especificação |  |
| TIPO | String |  | Tipo de Especificação |  |
| CODPROD | Integer |  | Código do Produto |  |
| CHAVE | String |  | Chave |  |
| VALUE | String |  | Value |  |
| CODSPEC | Integer |  | Código da Especificação |  |

## BH_MKTSTATUS — Status Pedidos Market Place
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLOJA | Integer |  | Código Loja |  |
| NOME | String |  | Nome Status |  |
| TIPO | Integer |  | Tipo | `1`=Aprovado `2`=Pagamento Pendente `3`=Cancelado `4`=Pedido Enviado `5`=Pedido Entregue_(+1)_ |
| CODLOCAL | Integer |  | Local |  |
| CODCENCUS | Integer |  | Centro de Resultado |  |
| CODEMP | Integer |  | Empresa |  |
| CODNAT | Integer |  | Natureza |  |
| CODTAB | Integer |  | CODTAB |  |
| CODTIPOPER | Integer |  | Tipo de Operação |  |
| DHTIPOPER | DateTime |  | DHTIPOPER |  |
| FULFILLMENT | String |  | FulFillment? | `S`=Sim `N`=Não |
| CODSTATUS | Integer |  | Código Status |  |

## BH_MKTSYNC — Fila de Integração
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RESPONSE | C |  | Resposta |  |
| REQUEST | String |  | Requisição |  |
| METODO | String |  | Método |  |
| DTALTER | DateTime |  | Data Alteração |  |
| BH_CODEMKT | String |  | Cód Pedido |  |
| CODSTATUS | Integer |  | Cód Status |  |
| CODPROD | Integer |  | Cód Produto |  |
| PAGAMENTO | String |  | Pagamento |  |
| DTPEDIDO | DateTime |  | Data Pedido |  |
| BH_LOJA | String |  | Loja de Conexão |  |
| QTDTENTATIVAS | Integer |  | Quantidade de Tentativas |  |
| BH_ID | String |  | ID Remoto |  |
| BH_FULLFIL | String |  | BH_FULLFIL |  |
| CODLOJA | Integer |  | CODLOJA |  |
| NUNOTA | Integer |  | NUNOTA |  |
| NUFILA | Integer |  | Nro Fila |  |

## BH_MKTSYNCPRO — Fila de Produtos
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSTATUS | Integer |  | CODSTATUS |  |
| ORIGEM | String |  | ORIGEM |  |
| DTORIGEM | DateTime |  | DTORIGEM |  |
| METODO | String |  | METODO |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODPROD | Integer |  | CODPROD |  |
| QTDTENTATIVAS | Integer |  | QTDTENTATIVAS |  |
| JSON | C |  | JSON |  |
| CODLOJA | Integer |  | CODLOJA |  |
| PRIORIDADE | Integer |  | PRIORIDADE |  |
| RETORNO | String |  | RETORNO |  |
| CODPRODALT | String |  | CODPRODALT |  |
| JSON_RETORNO | C |  | JSON Retorno |  |
| CODUSU | Integer |  | CODUSU |  |
| NUFILA | Integer |  | NUFILA |  |

## BH_MKTVARIACAO — Variações de Produtos
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODVAR | Integer |  | Produto Variação |  |
| CODPROD | Integer |  | CODPROD |  |

## COURSE — Curso Universidade
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CATEGORY | Integer |  | CATEGORY |  |
| SORTORDER | Integer |  | SORTORDER |  |
| FULLNAME | String |  | Nome completo |  |
| TIMECREATED | Integer |  | TIMECREATED |  |
| TIMEMODIFIED | Integer |  | TIMEMODIFIED |  |
| SKJV | String |  | SKJV |  |
| COST | Integer |  | Tipo avaliação | `5`=Prática/Cliente `4`=Conceitos - S.A.F. `3`=Não Tem `2`=Teórica `1`=Prática |
| VISIBLE | String |  | Visível | `0`=Não `1`=Sim |
| ID | Integer |  | Código |  |

## COURSE_CATEGORIES — Categoria de Cursos
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NAME | String |  | Categoria |  |
| PARENT | Integer |  | PARENT |  |
| SORTORDER | Integer |  | SORTORDER |  |
| COURSECOUNT | Integer |  | COURSECOUNT |  |
| VISIBLE | Integer |  | VISIBLE |  |
| TIMEMODIFIED | Integer |  | TIMEMODIFIED |  |
| DEPTH | Integer |  | DEPTH |  |
| SKJV | String |  | Sankhya/Jiva | `S`=Sankhya `J`=Jiva |
| VISIVELB2B | String |  | Visível B2B | `N`=Não `S`=Sim |
| ID | Integer |  | ID |  |

## COURSE_USER — Curso do Aluno
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| USERID | Integer |  | USERID |  |
| COURSEID | Integer |  | Curso |  |
| SORTORDER | Integer |  | SORTORDER |  |
| STATUS | Integer |  | Situação | `3`=Aberto `2`=Concluído `1`=Cursando |
| DT_END | Integer |  | DT_END |  |
| CERTIFIED | Integer |  | CERTIFIED |  |
| NOTA_PRATICA | Integer |  | Nota |  |
| CERTIFIED_PRATICA | Integer |  | Aprovado | `1`=Sim `0`=Não |
| TENTATIVA | Integer |  | Tentativa | `0`=Nenhuma `3`=Terceira `2`=Segunda `1`=Primeira |
| QTDACESSOS | Integer |  | QTDACESSOS |  |
| TIMESTART | Integer |  | TIMESTART |  |
| ID | Integer |  | ID |  |

## EVTFILAREINF — Fila de Eventos Reinf
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCREVT | String |  | Descrição do Evento |  |
| DHINC | DateTime |  | Dt. Inclusão |  |
| SEQEVENTO | Integer |  | Sequência do Evento |  |
| REFERENCIA | Date |  | Dt. Referência |  |
| CHAVE | String |  | Chave |  |
| ACAO | String |  | Ação |  |
| INDAPURACAO | Integer |  | Indicador de Apuração |  |
| INDRETIF | Integer |  | Indicador de Retificação |  |
| TPAMB | Integer |  | Tipo de Ambiente |  |
| ORIGEM | String |  | Origem |  |
| VERSAOLAYOUT | Integer |  | Versão do layout | `null`=1.04.00 - Até Maio/2021 `151`=1.05.01 - Após Junho/2021 `150`=1.05.00 - Após Junho/2021 |
| TIPOEVENTO | String |  | Tipo do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| CHAVEEVENTO | String |  | Chave do Evento |  |
| SITUACAO | String |  | Situação |  |
| CODUSUINC | Integer |  | Cód. Usuário |  |
| CODRETORNO | Integer |  | Cód. do Retorno |  |
| DHPROC | DateTime |  | Dt. Processamento |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| NULOTE | Integer |  | Nro. do Lote |  |
| INIVALID | Date |  | Dt. Início da Validade |  |
| FIMVALID | Date |  | Dt. Fim da Validade |  |
| NROPROTLOTE | String |  | Nro. do Protocolo do Lote |  |
| VERPROC | String |  | Versão do Aplicativo de Emissão |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Empresa |  |

## EVTLOTEREINF — Fila de Lotes Reinf
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHINC | DateTime |  | Dt. Inclusão |  |
| XMLENVLOTE | C |  | XML de Envio |  |
| XMLRETLOTE | C |  | XML de Retorno |  |
| NROPROTLOTE | String |  | Nro. do Protocolo do Lote |  |
| STATUS | String |  | Status |  |
| DHPREVCONSULTA | DateTime |  | Dt. Previsão da Consulta |  |
| MSG | C |  | Mensagem |  |
| TPAMB | Integer |  | Tipo de Ambiente |  |
| NULOTE | Integer |  | Nro. do Lote |  |

## GESTOR_REPORT — Permissão Acesso Relatórios
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| USERID | Integer |  | Aluno |  |
| INSTITUTIONID | Integer |  | Instituição |  |
| ID | Integer |  | ID |  |

## INSTITUTION — Instituição
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| BPID | Integer |  | Unidade/Franquia |  |
| IMPLANTADO | Integer |  | Implantado | `0`=Não `1`=Sim |
| CODPARC | Integer |  | Parceiro |  |
| SKJV | String |  | Sankhya/Jiva | `J`=Jiva `S`=Sankhya |
| DT_INICIO_CONCOMITANTE | DateTime |  | Dt. Início Concomitante |  |
| QTDACESSOS | Integer |  | Qte. Matricula não concomitante |  |
| VISIBLE | Integer |  | Ativo | `0`=Não `1`=Sim |
| QTDACESSOS_CONT | Integer |  | Qte. Matricula concomitantes |  |
| ID | Integer |  | Código |  |

## LOGFOLHA — Logs da folha
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | DateTime |  | REFERENCIA |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| PROBLEMA | String |  | PROBLEMA |  |
| CODERRO | Integer |  | CODERRO |  |
| TIPERRO | Integer |  | TIPERRO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| STRACE | C |  | STRACE |  |
| DISMISS | String |  | DISMISS |  |
| CODANA | Integer |  | CODANA |  |
| PARAMS | C |  | PARAMS |  |
| CODUSUDISMISS | Integer |  | CODUSUDISMISS |  |
| TABELATESTE | String |  | TABELATESTE |  |
| DTHR | DateTime |  | DTHR |  |

## MKTCATALOGOITENSPROD —  Itens Catalogo  
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| AD_DHALTERPRECO | Date |  | Data de Envio Preço |  |
| AD_DHALTERESTOQ | Date |  | Data de Envio Estoque |  |
| AD_IDMKT | String |  | ID MKT |  |
| SEQUENCIA | Integer |  |  Sequencia  |  |
| CODPROD | Integer |  |  Produto |  |
| ESTOQUE | Float |  |  Estoque |  |
| PRECO | Float |  |  Preço |  |
| PRECOPROMOCAO | Float |  |  Preço Promocional |  |
| DHALTER | DateTime |  |  Dh. ALteração  |  |

## MKTCATALOGOPROD —  Fila Receptiva   
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  |  Sequencia  |  |
| CODIGOLOJ | Integer |  |  Cód. Lojas  |  |

## MKTFILA —  Fila Receptiva   
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| AD_DHALTER | DateTime |  | Data |  |
| SEQUENCIA | Integer |  |  Sequencia  |  |
| CODIGOLOJ | Integer |  |  Cód. Lojas  |  |
| EMPRESAJSON | String |  |  Empresa  |  |
| CODEMP | Integer |  | Cód Empresa |  |
| LOJAJSON | String |  |  Loja  |  |
| TIPO | String |  |  Tipo  |  |
| ITEMID | String |  |  Id   |  |
| TEXTOJSON | String |  |  Json  |  |
| STATUS | String |  |  Status  |  |
| ERRO | String |  |  Erro  |  |
| PKDESTINO | String |  |  PK Destino  |  |

## MKTFILAREM —  Fila Receptiva   
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| AD_DHALTER | DateTime |  | Data |  |
| AD_IDMKT | String |  | ID_MKT |  |
| SEQUENCIA | Integer |  |  Sequencia  |  |
| CODIGOLOJ | Integer |  |  Cód. Lojas  |  |
| EMPRESAJSON | String |  |  Empresa  |  |
| CODEMP | Integer |  | Cód Empresa |  |
| LOJAJSON | String |  |  Loja  |  |
| longDescription | String |  |  longDescription  |  |
| TIPO | String |  |  Tipo  |  |
| ITEMID | String |  |  Id   |  |
| TEXTOJSON | String |  |  Json  |  |
| STATUS | String |  |  Status  |  |
| ERRO | String |  |  Erro  |  |
| PKORIGEM | String |  |  PK Destino  |  |

## MKTLOC —  Locais de Estoque   
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGOLOJ | Integer |  |  Cód Loja  |  |
| CODLOCAL | Integer |  |  Cód. Local  |  |

## MKTLOGRECEP —  Locais de Estoque   
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  |  Sequencia  |  |
| SEQUENCIALOG | Integer |  |  Seq. Log |  |
| LOG | String |  |  Log  |  |
| DHLOG | DateTime |  |  Dh. Log  |  |

## MKTLOJA —  Lojas   
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGOLOJ | Integer |  | Cód. Lojas  |  |
| DESCRICAO | String |  | Descriçao  |  |
| CODEMP | Integer |  | Empresa |  |
| MODELOPEDIDO | Integer |  | Modelo Pedido |  |
| CODTAB | Integer |  | Código Tabela Preço  |  |

## MKTVAR —  Variação de Produto MKT   
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Cód.  |  |
| DESCRICAO | String |  | Descriçao  |  |
| ID | String |  | ID  |  |
| ProductType | String |  | Product Type  |  |

## MKTVARPROD —  Produtos da Variação 
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  |  Cód  |  |
| CODPROD | Integer |  |  Produto |  |

## MKTVARTIP —  Locais de Estoque   
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  |  Cód |  |
| CODPROD | Integer |  |  Produto  |  |
| TIPO | String |  | Tipo  |  |
| VALOR | String |  | Valor  |  |

## TAIALTERP — Alteração de dados ERP
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NuNota |  |
| CODEMP | Integer |  | Empresa |  |
| AUDITORIAID | Integer |  | Auditoria |  |
| DHALTER | DateTime |  | DhAlter |  |
| DIAGNOSTICOC | String |  | Diagnostico Campo |  |
| DIAGNOSTICOI | Integer |  | Diagnostico Indice |  |
| VALORERP | Float |  | Valor ERP |  |
| VALORSUGEST | Float |  | Valor Sugerido |  |
| CODUSU | Integer |  | CodUsu |  |

## TAIAPURREF — Apuração - Reforma Tributária
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROTOCOLO | String |  | Protocolo |  |
| CODEMP | Integer |  | Empresa |  |
| CGC | String |  | CPF/CNPJ |  |
| DTINI | DateTime |  | Dh. Início Apuração |  |
| DTFIM | DateTime |  | Dh. Fim Apuração |  |
| STATUSPROTOCOLO | String |  | Status |  |

## TAIAPURREFATUAL — Apuração Atual
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROTOCOLO | String |  | Protocolo |  |
| CODEMP | Integer |  | Empresa |  |
| DTINI | DateTime |  | Dh. Início Apuração |  |
| DTFIM | DateTime |  | Dh. Fim Apuração |  |
| JSONRETORNO | C |  | Json de Retorno |  |

## TAIAPURREFCD — Apuração - Custo/Despesa
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROTOCOLO | String |  | Protocolo |  |
| CODEMP | Integer |  | Empresa |  |
| DTINI | DateTime |  | Dh. Início Apuração |  |
| DTFIM | DateTime |  | Dh. Fim Apuração |  |
| JSONRETORNO | C |  | Json de Retorno |  |

## TAIAPURREFCOMP — Apuração - Comparativo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROTOCOLO | String |  | Protocolo |  |
| CODEMP | Integer |  | Empresa |  |
| DTINI | DateTime |  | Dh. Início Apuração |  |
| DTFIM | DateTime |  | Dh. Fim Apuração |  |
| JSONRETORNO | C |  | Json de Retorno |  |

## TAICEMP — Credenciamento Empresas
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| APPKEY | String |  | Appkey |  |
| ACCKEY | String |  | Acckey |  |
| INTEGRADO | String |  | Integrado |  |
| INTEGRARAUTOMATICO | String |  | Integrar Automatico |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| DTPINTEG | String |  | Data para Integração | `N`=Dt. de Negociação `M`=Dt. do Movimento `E`=Dt. Entrada/Saída |

## TAIDOCAUDIT — Auditoria dos Documentos Integrados
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| NUNOTA | Integer |  | NuNota |  |
| NUMNOTA | Integer |  | NumNota |  |
| DTINTEG | DateTime |  | Dh. Integração |  |
| DTNEG | DateTime |  | Dt. Negociação |  |
| PROTOCOLO | String |  | Protocolo |  |
| DIAGNOSTICO | String |  | Diagnóstico |  |
| CODIGO | String |  | Código |  |
| NOMEAUDIT | String |  | Nome |  |
| EMENTA | String |  | Ementa |  |
| VALORAUDIT | Float |  | Valor Auditoria |  |
| CODPROD | Integer |  | Código Produto |  |
| INDICEDIAG | Integer |  | Diagnóstico Indice |  |
| ALTERADOERP | String |  | Alterado no ERP? |  |
| JSONAUDITORIA | C |  | Json Auditoria |  |
| NIVELAUDITORIA | Integer |  | Nível Auditoria |  |

## TAIDOCINT — Documentos Integrados
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| TIPMOV | String |  | Tipo de Movimento | `1`=
                        1-NF Depósito
                     `2`=
                        2-PD Devol. / Procuração / Warrant
                     `3`=
                        3-Saídas
                     `4`=
                        4-Faturamento
                     `8`=
                        8-RD8
                    _(+18)_ |
| NUNOTA | Integer |  | Número Único |  |
| NUMNOTA | Integer |  | Número Nota |  |
| CODMODDOC | Integer |  | Modelo |  |
| SERIENOTA | String |  | Serie |  |
| CHAVENFE | String |  | Chave de Acesso |  |
| DTINTEG | DateTime |  | Dh. Integração |  |
| STATUSENV | String |  | Status de Envio | `Pendente`=Pendente `Processando`=Processando `Processado`=Processado `Finalizado`=Finalizado |
| STATUSNFE | String |  | Status Sefaz |  |
| PROTOCOLO | String |  | Protocolo |  |
| AUDITADO | String |  | Auditado | `S`=Sim `N`=Não `E`=Erro |
| ERROS | Integer |  | Erros |  |
| ADVERTENCIA | Integer |  | Advertência |  |
| BENEFICIOS | Integer |  | Beneficios |  |
| XML | C |  | 
                    XML de Resposta da Asis
                 |  |
| DTNEG | DateTime |  | Data de Negociação |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TIPO | String |  | Tipo |  |
| OCORRENCIA | String |  | Ocorrência |  |
| MENSAGEM | String |  | Mensagem |  |
| NUARQUIVO | Integer |  | Nro. Arquivo |  |
| AUDITORIACONSULTADA | String |  | Auditoria Consultada |  |

## TAIHCEMP — Histórico de Credenciamento Empresas
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| NOMECAMPO | String |  | Campo Alterado |  |
| OLDVALUE | String |  | Valor Antigo |  |
| NEWVALUE | String |  | Valor Novo |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequencia |  |

## TAIMONITORIA — Monitoria de Alíquotas
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| DATA | DateTime |  | Data de Integração |  |
| CABECALHO | String |  | Cabeçalho |  |
| CODIGO | String |  | Código |  |
| DADOS | String |  | Dados |  |
| ACEITAALTERACAO | String |  | Aceita Alteração |  |
| CODUSU | Integer |  | Código Usuário Aceite |  |
| STATUSMON | String |  | Status |  |
| TIPOTRIB | String |  | Tipo Trib |  |
| DHMON | DateTime |  | Data Monitoria |  |
| STATUSAPLIC | String |  | 
                    Status de Utilização
                 | `P`=
                         Pendente 
                     `A`=
                         Aplicado 
                     `D`=
                         Descartado 
                     |

## TAIOBGAUDIT — Obrigações Acessórias Auditadas
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| JSONAUDITORIA | C |  | Json Auditoria |  |
| NIVELAUDITORIA | Integer |  | Nível Auditoria |  |
| CODEMP | Integer |  | Empresa |  |
| ORIGDOC | String |  | Origem Documento |  |
| REFERENCIA | DateTime |  | Referência |  |
| ARQUIVO | String |  | Arquivo |  |
| DTINTEG | DateTime |  | Dh. Integração |  |
| PROTOCOLO | String |  | Protocolo |  |
| DIAGNOSTICO | String |  | Diagnóstico |  |
| CODIGO | String |  | Código |  |
| NOMEAUDIT | String |  | Nome |  |
| EMENTA | String |  | Ementa |  |

## TAIOBGINT — Obrigações Acessórias
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| ORIGDOC | String |  | Origem Documento |  |
| REFERENCIA | DateTime |  | Referência |  |
| ARQUIVO | String |  | Arquivo |  |
| TPESCRIT | String |  | Tipo Escrituração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| VERSAOLAYOUT | Integer |  | Versão Layout |  |
| DTINTEG | DateTime |  | Dh. Integração |  |
| STATUSENV | String |  | Status de Envio |  |
| PROTOCOLO | String |  | Protocolo |  |
| AUDITADO | String |  | Auditado |  |
| AUDITORIACONSULTADA | String |  | Auditoria Consultada |  |
| ERROS | Integer |  | Erros |  |
| ADVERTENCIA | Integer |  | Advertência |  |
| BENEFICIOS | Integer |  | Beneficios |  |
| TIPO | String |  | Tipo |  |
| OCORRENCIA | String |  | Ocorrência |  |
| MENSAGEM | String |  | Mensagem |  |

## TAPAMO — Amostra
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDAMOSTRA | String |  | Identificador |  |
| CODPROJ | Integer |  | Projeto |  |
| IDOBJETO | String |  | ID objeto |  |
| NOMETAB | String |  | Tabela |  |
| TIPOAMOSTRA | String |  | Tipo de amostra | `S`=Solo `F`=Fase Livre `A`=Água |
| PROFINICIAL | Float |  | Prof. inicial |  |
| PROFFINAL | Float |  | Prof. final |  |
| OBSERVACAO | String |  | Observação |  |
| NUCLL | Integer |  | Padrão de classificação |  |
| NUAMOSTRAORIG | Integer |  | NUAMOSTRAORIG |  |
| NUAMOSTRA | Integer |  | Número amostra |  |

## TAPARM — Faturamento de Item de Apontamento
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | NUMITEM |  |
| NURM | Integer |  | NURM |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUAPONTA | Integer |  | NUAPONTA |  |

## TAPCAM — Coleta amostra
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUAPONTA | Integer |  | NUAPONTA |  |
| NUMITEM | Integer |  | NUMITEM |  |
| IDAMOSTRA | String |  | IDAMOSTRA |  |
| NUMCUSTODIA | Integer |  | NUMCUSTODIA |  |
| CODBARRA | String |  | CODBARRA |  |
| DHREMESSA | DateTime |  | DHREMESSA |  |
| STATUSREC | String |  | STATUSREC |  |
| OBSREC | String |  | OBSREC |  |
| HRCOLETA | Integer |  | HRCOLETA |  |
| PROFINICIAL | Float |  | PROFINICIAL |  |
| PROFFINAL | Float |  | PROFFINAL |  |
| NUAMOSTRA | Integer |  | NUAMOSTRA |  |

## TAPCQM — Composto Químico
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SIGLA | String |  | Sigla |  |
| DESCRCIAO | String |  | Descrição |  |
| VALORPADRAO | Float |  | Valor Padrão |  |
| CODCQM | Integer |  | Composto Químico |  |

## TAPCUS — Custódia Apontamento
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHREMESSA | DateTime |  | DHREMESSA |  |
| TIPOAMOSTRA | String |  | TIPOAMOSTRA |  |
| CODTIPANA | Integer |  | CODTIPANA |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODPROJ | Integer |  | CODPROJ |  |
| NUMCUSTODIA | Integer |  | NUMCUSTODIA |  |

## TAPEAP — Equipe por Apontamento
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | NUMITEM |  |
| NUEQUIPE | Integer |  | NUEQUIPE |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUAPONTA | Integer |  | NUAPONTA |  |

## TAPEPJ — Equipamento por Projeto
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | CODPROD |  |
| CODBEM | String |  | CODBEM |  |
| CODPROJFINAL | Integer |  | CODPROJFINAL |  |
| DHFINAL | DateTime |  | DHFINAL |  |
| DHINICIAL | DateTime |  | DHINICIAL |  |
| CODPROJ | Integer |  | CODPROJ |  |

## TAPEQJ — Equipe por Projeto
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUEQUIPE | Integer |  | NUEQUIPE |  |
| CODPROJFINAL | Integer |  | CODPROJFINAL |  |
| DHINICIAL | DateTime |  | DHINICIO |  |
| DHFINAL | DateTime |  | DHFINAL |  |
| CODPROJ | Integer |  | CODPROJ |  |

## TAPEQT — Equipamento por Apontamento
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | NUMITEM |  |
| CODPROD | Integer |  | CODPROD |  |
| CODBEM | String |  | CODBEM |  |
| NUAPONTA | Integer |  | NUAPONTA |  |

## TAPFAT — Resumo de Faturamento
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMCONTRATO | Integer |  | NUMCONTRATO |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHMOV | DateTime |  | DHMOV |  |
| DTINICIAL | DateTime |  | DTINICIAL |  |
| DTFINAL | DateTime |  | DTFINAL |  |
| NUFAT | Integer |  | NUFAT |  |

## TAPFRM — Faturamento de RM
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NURM | Integer |  | NURM |  |
| TIPO | String |  | TIPO |  |
| PERCFAT | Float |  | PERCFAT |  |
| NUFAT | Integer |  | NUFAT |  |

## TAPIAP — Item Apontamento
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMITEM | Integer |  | Número Item |  |
| NOMETAB | String |  | Nome da Tabela |  |
| IDOBJETO | String |  | ID Objeto |  |
| CODSERV | Integer |  | Serviço |  |
| QTDSERV | Float |  | Quantidade Serviço |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODVOL | String |  | Volume |  |
| OBSERVACAO | String |  | Observação |  |
| NUAPONTA | Integer |  | Nro Único Apontamento |  |

## TAPIFT — Item de Faturamento
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODVOL | String |  | CODVOL |  |
| CODSERV | Integer |  | CODSERV |  |
| QTDCOMDESC | Float |  | QTDCOMDESC |  |
| QTDSEMDESC | Float |  | QTDSEMDESC |  |
| QTDDESC | Float |  | QTDDESC |  |
| VLRUNIT | Float |  | VLRUNIT |  |
| QTDRET | Float |  | QTDRET |  |
| NUFAT | Integer |  | NUFAT |  |

## TAPIRM — Item do Movimento de RM
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODSERV | Integer |  | CODSERV |  |
| CODVOL | String |  | CODVOL |  |
| QTDSERV | Float |  | QTDSERV |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| VLRUNI | Float |  | VLRUNI |  |
| NURM | Integer |  | NURM |  |
| TOTAL | Integer |  | Valor total do item |  |

## TAPLOG — Tabela de log
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOEVENTO | Integer |  | Tipo de Evento | `-1`=Todos `3`=Transmissão de Custódia `0`=Início da Conexão `1`=Fim da Conexão `4`=Sincronização de Dados Básicos_(+2)_ |
| DHMOV | DateTime |  | Data do movimento |  |
| BYTESENVIADOS | Float |  | Qtd. Bytes Enviados(KB) |  |
| BYTESRECEBIDOS | Float |  | Qtd. Bytes Recebidos(KB) |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TAPMAP — Movimento Apontamento
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROJ | Integer |  | Projeto |  |
| DHMOV | DateTime |  | Data Mov. |  |
| HRINICIAL | Integer |  | Hora inicial |  |
| HRFINAL | Integer |  | Hora Final |  |
| NUMRDO | Integer |  | Número RDO |  |
| OBSERVACAO | String |  | Observação |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CONTEUDORDO | Boolean |  | Conteúdo RDO |  |
| CONDCLIMATICAMANHA | String |  | Condição Clima Manhã |  |
| CONDCLIMATICATARDE | String |  | Condição Clima Tarde |  |
| INTERVALO | Integer |  | Intervalo |  |
| STATUS | String |  | Status |  |
| NUAPONTA | Integer |  | Nro Único Apontamento |  |

## TAPMDO — Metadado objeto projeto
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFORMTOP | Integer |  | CODFORMTOP |  |
| CODFORMVAL | Integer |  | CODFORMVAL |  |
| DIMENSAO | String |  | DIMENSAO | `U`=Unidimensionamento `M`=Multidimensionamento |
| NOMETAB | String |  | NOMETAB |  |

## TAPMRM — Movimento de RM
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHMOV | DateTime |  | DHMOV |  |
| CODPROJ | Integer |  | CODPROJ |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUMCONTRATO | Integer |  | NUMCONTRATO |  |
| NURM | Integer |  | NURM |  |

## TAPORG — Orgão Regulamentador
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| SIGLA | String |  | Sigla |  |
| CODORG | Integer |  | Orgão Regulamentador |  |

## TAPPAA — Paralisações por Apontamento
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPAR | Integer |  | Parceiro |  |
| SEQUENCIA | Integer |  | Sequência |  |
| HRINICIAL | Integer |  | Hora Inicial |  |
| HRFINAL | Integer |  | Hora Final |  |
| OBSERVACAO | String |  | Observação |  |
| HRFECHAMENTO | Integer |  | Hora Fechamento |  |
| NUAPONTA | Integer |  | Nro Único Apontamento |  |

## TAPPFA — Previsão Faturamento
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMETAB | String |  | NOMETAB |  |
| IDOBJETO | String |  | IDOBJETO |  |
| CODPROD | Integer |  | CODPROD |  |
| QTDNEG | Float |  | QTDNEG |  |
| VLRUNIT | Float |  | VLRUNIT |  |
| CODPROJ | Integer |  | CODPROJ |  |

## TAPRAM — Resultado Análise
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDAMOSTRA | String |  | Id Amostra |  |
| SIGLA | String |  | Sigla |  |
| DHINC | DateTime |  | Data de inclusão |  |
| VALOR | String |  | Valor |  |
| IDSESSAO | String |  | IDSESSAO |  |
| CODPROJ | Integer |  | Projeto |  |

## TAPSAM — Status Amostra
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDAMOSTRA | String |  | IDAMOSTRA |  |
| STATUS | String |  | STATUS |  |
| DHINC | DateTime |  | DHINC |  |
| OBSREC | String |  | OBSREC |  |
| IDSESSAO | String |  | IDSESSAO |  |
| CODPROJ | Integer |  | CODPROJ |  |

## TAPSEO — Serviço por Objeto
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMETAB | String |  | Tabela |  |
| IDOBJETO | String |  | Objeto |  |
| CODSERV | Integer |  | Servico |  |
| QTDPLA | Float |  | Quantidade Planejada |  |
| CODVOL | String |  | Unidade |  |
| CODPROJ | Integer |  | Projeto |  |
| QTDREAL | Float |  | Quantidade real |  |

## TAPTAA — Tipo de análise por amostra
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUAMOSTRA | Integer |  | Amostra |  |
| CODTIPANA | Integer |  | Tipo Análise |  |

## TAPTAN — Tipo de Análise
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODTIPANA | Integer |  | Código |  |

## TAPTOP — Topografia
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMETAB | String |  | Tabela |  |
| IDOBJETO | String |  | Objeto |  |
| IDTOPOGRAFIA | String |  | Identificador |  |
| COORDX | Float |  | Coordenada X |  |
| COORDY | Float |  | Coordenada Y |  |
| COORDZ | Float |  | Coordenada Z |  |
| QUINTACOLUNA | Float |  | Quinta coluna |  |
| CODPROJ | Integer |  | Projeto |  |

## TAPTPA — Tipo de Paralisação
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CAUSA | String |  | Causa | `L`=Liberação `T`=Terceiros `C`=Cliente `E`=Empresa |
| CODPAR | Integer |  | Código |  |

## TAPVOR — Valor Referência por Órgão
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCQM | Integer |  | CODCQM |  |
| VALOR | Float |  | VALOR |  |
| CODORG | Integer |  | CODORG |  |

## TAPVPJ — Veículo por Projeto
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVEICULO | Integer |  | CODVEICULO |  |
| DHINICIAL | DateTime |  | DHINICIAL |  |
| DHFINAL | DateTime |  | DHFINAL |  |
| CODPROJ | Integer |  | CODPROJ |  |

## TASAGE — Agentes
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRAGENTE | String |  | Descrição |  |
| STATUS | String |  | Status | `P`=Pendente `I`=Inativo `A`=Ativo |
| CONTEUDO | Boolean |  | CONTEUDO |  |
| DESCRITOR | C |  | DESCRITOR |  |
| DHINC | DateTime |  | Incluído em? |  |
| NOTIFICADO | String |  | Hub Notificado? | `S`=Sim `N`=Não |
| SCHEDULE | String |  | SCHEDULE |  |
| QTDEXEC | Integer |  | Qtd. de Execuções |  |
| VERSAO | String |  | VERSAO |  |
| ULTLOG | C |  | Ultimo Log de execução |  |
| HASH | String |  | HASH |  |
| ID | String |  | ID |  |

## TASPAG — Permissões de Agente
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PERMISSAO | String |  | Permissão | `writefsys`=Leitura e escrita no disco rígido `writedb`=Leitura e escrita base de dados `all`=Permissão requirida |
| AUTORIZADO | String |  | Permitir? | `S`=Sim `P`=Pendente `N`=Não |
| DHAUTORIZACAO | DateTime |  | Autorizado em |  |
| ID | String |  | Plugin |  |

## TBINTINTEGRACAO — Integração Carrus
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FLESTADOINTEGRACAO | String |  | FLESTADOINTEGRACAO |  |
| DTGERACAO | DateTime |  | DTGERACAO |  |
| HRGERACAO | String |  | HRGERACAO |  |
| DTINTEGRACAO | DateTime |  | DTINTEGRACAO |  |
| HRINTEGRACAO | String |  | HRINTEGRACAO |  |
| NUSEQUENCIAINTEGRACAO | Integer |  | NUSEQUENCIAINTEGRACAO |  |

## TBINTITEMPEDIDO — Item Pedido Carrus
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CDEMPRESA | String |  | CDEMPRESA |  |
| CDROMANEIO | String |  | CDROMANEIO |  |
| CDPEDIDO | String |  | CDPEDIDO |  |
| CDTIPOCONFERENCIA | String |  | CDTIPOCONFERENCIA |  |
| CDPRODUTO | String |  | CDPRODUTO |  |
| CDBARRAS | String |  | CDBARRAS |  |
| DSUNIDADE | String |  | DSUNIDADE |  |
| DSPRODUTO | String |  | DSPRODUTO |  |
| QTORIGINAL | Integer |  | QTORIGINAL |  |
| QTMINBAIXARLOTE | Integer |  | QTMINBAIXARLOTE |  |
| FLUSALASTRO | String |  | FLUSALASTRO |  |
| QTLASTRO | Integer |  | QTLASTRO |  |
| NUSEQUENCIAINTEGRACAO | Integer |  | NUSEQUENCIAINTEGRACAO |  |

## TBINTPEDIDO — Pedido Carrus
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CDEMPRESA | String |  | CDEMPRESA |  |
| CDROMANEIO | String |  | CDROMANEIO |  |
| CDPEDIDO | String |  | CDPEDIDO |  |
| CDTIPOCONFERENCIA | String |  | CDTIPOCONFERENCIA |  |
| DSPEDIDO | String |  | DSPEDIDO |  |
| NUSEQUENCIA | Integer |  | NUSEQUENCIA |  |
| VLPESO | Integer |  | VLPESO |  |
| DSLOGRADOURO | String |  | DSLOGRADOURO |  |
| DSBAIRRO | String |  | DSBAIRRO |  |
| DSCOMPLEMENTO | String |  | DSCOMPLEMENTO |  |
| DSCIDADE | String |  | DSCIDADE |  |
| DSESTADO | String |  | DSESTADO |  |
| DSOBSERVACAO | String |  | DSOBSERVACAO |  |
| DSLISTAEMAILDESTPEDIDOERRO | String |  | DSLISTAEMAILDESTPEDIDOERRO |  |
| DSLISTAEMAILDESTPEDIDOSUCESSO | String |  | DSLISTAEMAILDESTPEDIDOSUCESSO |  |
| NUSEQUENCIAINTEGRACAO | Integer |  | NUSEQUENCIAINTEGRACAO |  |

## TBINTROMANEIO — Romaneio Carrus
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CDEMPRESA | String |  | CDEMPRESA |  |
| CDROMANEIO | String |  | CDROMANEIO |  |
| CDTIPOCONFERENCIA | String |  | CDTIPOCONFERENCIA |  |
| DSROMANEIO | String |  | DSROMANEIO |  |
| VLPESO | Integer |  | VLPESO |  |
| DSREGIAO | String |  | DSREGIAO |  |
| DTROMANEIO | DateTime |  | DTROMANEIO |  |
| HRROMANEIO | String |  | HRROMANEIO |  |
| DSOBSERVACAO | String |  | DSOBSERVACAO |  |
| NUSEQUENCIAINTEGRACAO | Integer |  | NUSEQUENCIAINTEGRACAO |  |

## TBSACE — Ação Estratégica
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| DHINICIO | DateTime |  | Data e Hora Início |  |
| DHLIMITE | DateTime |  | Data e Hora Limite |  |
| NUACE | Integer |  | Ação Estratégica |  |

## TBSACL — TABLE TBSACL
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUACEDEST | Integer |  | Ação Estratégica Destino |  |
| TIPO | String |  | Tipo | `B`=Bidirecional `U`=Unidirecional |
| NUACEORIG | Integer |  | Ação Estratégica Origem |  |

## TBSEIX — Eixos Estratégicos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| OBSERVACAO | String |  | Observação |  |
| NUEIXO | Integer |  | Eixo Estratégico |  |

## TBSIND — TABLE TBSIND
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUEIXO | Integer |  | Eixo Estratégico |  |
| DESCRICAO | String |  | Descrição |  |
| UNMED | String |  | Unidade de Medição |  |
| DESCFORM | String |  | Descrição Fórmula |  |
| AREAS | String |  | Áreas |  |
| DESCPARAM | String |  | Descrição do Paramêtro |  |
| NUIND | Integer |  | Indicador Estratégico |  |

## TBSOBJ — TABLE TBSOBJ
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| NUOBJ | Integer |  | Objetivo |  |

## TBSOBL — Ligação entre Objetivos Estratégicos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUOBJDEST | Integer |  | Objetivo Destino |  |
| TIPO | String |  | Tipo | `B`=Bidirecional `U`=Unidirecional |
| NUOBJORIG | Integer |  | Objetivo Origem |  |

## TBSPLE — TABLE TBSPLE
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| OBSERVACAO | String |  | Observação |  |
| MISSAO | String |  | Missão |  |
| VISAO | String |  | Visão |  |
| VALOR | String |  | Valor |  |
| DTINI | DateTime |  | Data início |  |
| DTFIN | DateTime |  | Data Final |  |
| NUPLE | Integer |  | Planejamento Estratégico |  |

## TBSPST — Perspectiva
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| NUPST | Integer |  | Perspectiva |  |

## TCAALU — Alunos
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANOINGRESSO | Integer |  | Ano de Ingresso |  |
| CODMAE | Integer |  | Cód.Mãe |  |
| CODPAI | Integer |  | Cód.Pai |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| CODRESP | Integer |  | Cód.Responsável |  |
| CODTPRESP | Integer |  | Cód.Tipo responsável |  |
| DTDESATIVO | String |  | DTDESATIVO |  |
| FOTO | Boolean |  | Foto |  |
| SEXO | String |  | Sexo |  |

## TCAANO — Ano letivo
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODCUR | String |  | Cód.Curso |  |
| CODSER | String |  | Cód.Série |  |
| PARCELA | String |  | Parcela |  |
| DESCRICAO | String |  | Descrição |  |
| DTINICIOAULAS | DateTime |  | Data de início das aulas |  |
| DTFIMAULAS | DateTime |  | Data do fim das aulas |  |
| QTDPERIODO | Integer |  | Quantidade Período |  |
| CLASSIFDIARIO | String |  | CLASSIFDIARIO |  |
| RENOVAMATRICULA | DateTime |  | Data para renovar matrícula |  |
| NROMAXDEPEND | Integer |  | Número máximo de dependências |  |
| NROMAXRECUPERACAO | Integer |  | Número máximo de recuperações |  |
| MSGINCENTIVO | String |  | Mensagem de incentivo |  |
| QTDDIALETIVO | Integer |  | Quantidade de dias letivos |  |
| MEDIA | Integer |  | Média |  |
| FREQDIARIA | String |  | Frequência diária |  |
| CODANO | Integer |  | Cód.Ano |  |

## TCACON — Controles
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODANO | Integer |  | Cód.Ano |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| VLRMIN | Float |  | Valor Mínimo |  |
| VLRMAX | Float |  | Valor Máximo |  |
| NOMCON | String |  | Nome do Controle |  |
| FLGABXMED | String |  | FLGABXMED |  |
| ORDCON | Integer |  | Ordem do Controle |  |
| SITCON | String |  | Situação do Controle |  |
| CODCON | String |  | Cód.Controle |  |

## TCACPI — Ítens de Precificação
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNAT | Integer |  | Cód. Natureza |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| PRECOUNIT | Float |  | Preço Unitário |  |
| PRECOTOTAL | Float |  | Preço Total |  |
| QTD | Float |  | Quantidade |  |
| OBS | String |  | Observação |  |
| NUCURSO | Integer |  | Cód.Curso |  |

## TCACPR — Precificação do Curso
Campos: 43

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODNATRECEITA | Integer |  | Cód. Natureza Receita |  |
| NUSALA | Integer |  | Número Sala |  |
| NUCURSO | Integer |  | Número Curso |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| ANO | Integer |  | Ano |  |
| MES | Integer |  | Mês |  |
| HORAS | Integer |  | Horas |  |
| HORASSALA | Integer |  | Horas Sala |  |
| DIAS | Integer |  | Dias |  |
| TURMAS | Integer |  | Turmas |  |
| PRECOTOTAL | Float |  | Preço Total |  |
| MARKUP | Float |  | Markup |  |
| PERIODOS | Integer |  | Períodos |  |
| PUBLICOALVO | String |  | Público Alvo |  |
| DESCRICAO | String |  | Descrição |  |
| PERCPIS | Float |  | Percentual PIS |  |
| PERCCOFINS | Float |  | Percentual FINS |  |
| PERCCSL | Float |  | Percentual CSL |  |
| PERCINSS | Float |  | Percentual INSS |  |
| PERCISS | Integer |  | Percentual ISS |  |
| PARTICIPANTES | Integer |  | Participantes |  |
| RECBRUT | Float |  | Receita Bruta |  |
| IMPOSTOS | Float |  | Imposto |  |
| RECLIQ | Float |  | Receita Líquida |  |
| CUSTOSDIR | Float |  | Custos Diretos |  |
| CUSTOSINDIR | Float |  | Custos Indiretos |  |
| LUCBRUT | Float |  | Lucro Bruto |  |
| DESPCOM | Float |  | Despesa Comercial |  |
| DESPADMIN | Float |  | Despesa Administrativa |  |
| FINANCLIQ | Float |  | Financeiro Líquido |  |
| DEPRECIACAO | Float |  | Depreciação |  |
| CUSTOCONSULTUNIT | Float |  | Custo Unitário da Consultoria |  |
| CUSTOCONSULTTOT | Float |  | Custo Total da Consultoria |  |
| OUTRASDESP | Float |  | Outras Despesas |  |
| PROGRAMA | Integer |  | Programa |  |
| IRCS | Float |  | IRCS |  |
| CRPROGRAMA | Integer |  | Cód.Centro de resultado do Programa |  |
| RESULTADO_LIQ | Float |  | Resultado Líquido |  |
| EBITDA | Float |  | EBITDA |  |
| EBIT | Float |  | EBIT |  |
| CONSULTORES | Integer |  | Consultores |  |

## TCACUR — Tabela de Cursos
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEABREVIADO | String |  | Nome abreviado do Curso |  |
| CODDURA | Integer |  | Cód.Duração |  |
| GRAU | Integer |  | Grau |  |
| CODCUR | String |  | Cód.Curso |  |
| PORCINC | Integer |  | PORCINC |  |
| CODTPENS | Integer |  | Cod.Tipo Ensino |  |
| MODULOAULA | Integer |  | Módulo |  |
| NOMECUR | String |  | Nome do Curso |  |

## TCADIA — Diário
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód.Parceiro |  |
| CODMAT | String |  | Cód.Matéria |  |
| DATMOV | DateTime |  | Data do Movimento |  |
| SITUACAO | String |  | Situação |  |
| SEQUENCIAL | Integer |  | Sequência |  |
| CODTURMA | Integer |  | Cód.Turma |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| NUMDIARIO | Integer |  | Número do Diário |  |

## TCADIS — Disciplina
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome da Disciplina |  |
| CODDISC | String |  | Cód.Disciplina |  |

## TCADOC — Documentos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DSCDOC | String |  | Descrição |  |
| SITUACAO | String |  | Situação |  |
| CODDOC | Integer |  | Cód.Documento |  |

## TCADSE — Disciplina Semanal
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| CODTPDISC | String |  | Cód.Tipo Disciplina |  |
| RECUPERACAO | String |  | Recuperação |  |
| TIPOAVALIACAO | String |  | Tipo de Avaliação |  |
| AULAS_SEMANAIS | Integer |  | Aulas Semanais |  |
| OBRIGATORIA | String |  | Obrigatória |  |
| REPROVAPORNOTA | String |  | Reprova por nota |  |
| CARHORECUPERA | Integer |  | Carga horária Recuperação |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| REPROVAPORFALTA | String |  | Reprova por falta |  |
| CODDISC | String |  | Cód.Disciplina |  |
| CONTACOMORECUPERACAO | String |  | Conta como recuperação |  |
| CODANO | Integer |  | Cód.Ano |  |
| CARGA_HORARIA | Integer |  | Carga horária |  |
| CODCUR | String |  | Cód.Curso |  |
| CODDSE | Integer |  | Cód.Disciplina Semanal |  |
| CODSER | String |  | Cód.Série |  |

## TCADUR — Duração
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCUR | String |  | Cód.Curso |  |
| DESCRICAO | String |  | Descrição |  |
| CODDURA | Integer |  | Cód.Duração |  |

## TCAINS — Rede de ensino
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEINS | String |  | Nome |  |
| REDENSINO | String |  | Rede de Ensino |  |
| ZONA | String |  | Zona |  |
| CODINS | Integer |  | Cód.Rede de ensino |  |

## TCAMAP — Mapa do Diário
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMDIARIO | Integer |  | Número do Diário |  |
| CODDSE | Integer |  | Cód.Disciplina Semanal |  |
| NUPERIODO | Integer |  | Número do Período |  |
| CODALU | Integer |  | Cód.Aluno |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODANO | Integer |  | Cód.Ano |  |
| CODPROF | Integer |  | Cód.Professor |  |
| CODTURMA | Integer |  | Cód.Turma |  |
| TOTFALTA | Float |  | Total de Faltas |  |
| TOTNOTA | Float |  | Nota total |  |
| FALTAJUS | Float |  | Faltas Justificadas |  |
| CONCEITO | String |  | Conceito |  |
| NUMAPA | Integer |  | Número do Mapa do Diário |  |
| TCA_CODTURMA | Integer |  | Cód.Turma |  |

## TCAMAT — Materiais
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPVENDA | Integer |  | Cód.Tipo de Negociação |  |
| DHTIPVENDA | DateTime |  | Data e hora tipo de negociação |  |
| CODCUR | String |  | Cód.Curso |  |
| CODSER | String |  | Cód.Série |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| DTMAT | DateTime |  | Data Material |  |
| SITMAT | String |  | SITMAT |  |
| SITATU | String |  | SITATU |  |
| DTSITATU | DateTime |  | DTSITATU |  |
| TURMA | String |  | Turma |  |
| FINANCEIRO | String |  | Financeiro |  |
| VALORDESCONTO | Float |  | Valor do Desconto |  |
| CODTURNO | Integer |  | Cód.Turno |  |
| CODANO | Integer |  | Cód.Ano |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| VLRMAT | Float |  | Valor do Material |  |
| SITNOVREP | String |  | SITNOVREP |  |
| SEGURADO | String |  | Segurado |  |
| SITESPEC | String |  | SITESPEC |  |
| PERCDESC | Float |  | PERCDESC |  |
| SELECAO | String |  | Seleção |  |
| OBSERVACAO | String |  | Observação |  |
| RESULTADO | String |  | Resultado |  |
| VALORTOTAL | Float |  | Valor Total |  |
| CODMAT | String |  | Cód.Material |  |

## TCAPAR — Parcelamento do Vencimento
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODANO | Integer |  | Cód.Ano |  |
| CODCUR | String |  | Cód.Curso |  |
| CODSER | String |  | Cód.Série |  |
| PARCELA | String |  | Parcela |  |
| CODNAT | Integer |  | Cód.Natureza |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODTIPTIT | Integer |  | Cód.Tipo de título |  |
| TSI_CODEMP | Integer |  | Cód.Empresa (TSIEMP) |  |
| DTVENC | DateTime |  | Data Vencimento |  |
| VLRDESDOB | Float |  | Valor do Desdobramento |  |
| TEMDESCONTO | String |  | Tem Desconto? |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCAPER — Período
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODANO | Integer |  | Cód.Ano |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| DTINICIO | DateTime |  | Data de Início |  |
| DTFIM | DateTime |  | Data do Fim |  |
| DIASLETIVOS | Integer |  | Quantidade de dias Letivos |  |
| VLRPERIODO | Integer |  | Valor Período |  |
| NOTAMINIMA | Integer |  | Nota Mínima |  |
| MSGPERIODO | String |  | Mensagem |  |
| TIPSUB | String |  | TIPSUB |  |
| PERSUBINI | Integer |  | PERSUBINI |  |
| PERSUBFIM | Integer |  | PERSUBFIM |  |
| NOME | String |  | Nome |  |
| NUPERIODO | Integer |  | Número do Período |  |

## TCAPRE — Mensalidade por Período
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODANO | Integer |  | Cód.Ano |  |
| CODCUR | String |  | Cód.Curso |  |
| CODSER | String |  | Cód.Série |  |
| VLRMATRICULA | Float |  | Valor da Matrícula |  |
| VLRTOTMENSALIDADE | Float |  | Valor total da mensalidade |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCAREF — Referência do Período
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREF | String |  | Cód.Referência |  |
| PERINI | Float |  | Início do Período |  |
| PERFIM | Float |  | Fim do Período |  |
| SITUACAO | String |  | Situação |  |
| CODANO | Integer |  | Cód.Ano |  |

## TCAREM — Remanejamento de Turmas
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMAT | String |  | Cód.Material |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODTURMA | Integer |  | Cód.Turma |  |
| CODTURANT | Integer |  | Cód.Turma anterior |  |
| CODANO | Integer |  | Cód.Ano |  |
| DTREM | DateTime |  | Data do remanejamento |  |

## TCASAL — Salas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| METRAGEM | Float |  | Metragem |  |
| ATIVA | String |  | Ativa |  |
| NUSALA | Integer |  | Número Sala |  |

## TCASER — Séries
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCUR | String |  | Cód.Curso |  |
| NOME | String |  | Nome |  |
| CODPROXSER | String |  | Cód.Próxima Série |  |
| CODPROXCUR | String |  | Cód.Próximo Curso |  |
| CODSER | String |  | Cód.Série |  |

## TCATDI — Tipo de Disciplinas
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODTPDISC | String |  | Cód.Tipo de Disciplina |  |

## TCATEN — Tipos de Encerramentos
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| CODTPENS | Integer |  | Cód.Tipo Encerramento |  |

## TCATNO — Turnos
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODTURNO | Integer |  | Cód.Turno |  |

## TCATPA — Tipos de Avaliação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| PESO | Integer |  | Peso |  |
| TIPOAVL | String |  | Tipo de avaliação |  |
| CODTPA | Integer |  | Cód.Tipo de avaliação |  |

## TCATUR — Turmas
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODCUR | String |  | Cód.Curso |  |
| CODSER | String |  | Cód.Série |  |
| CODTURNO | Integer |  | Cód.Turno |  |
| CODANO | Integer |  | Cód.Ano |  |
| NOME | String |  | Nome |  |
| TURMA | String |  | Turma |  |
| CAPMAX | Integer |  | Capacidade máxima |  |
| CAPMIN | Integer |  | Capacidade mínima |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| CODTURMA | Integer |  | Cód.Turma |  |

## TCCACA — Acabamento CC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Acabamento Diferenciado |  |
| DESCRICAO | String |  | Descrição |  |
| CODPROD | Integer |  | Residencial |  |
| CODCC | Integer |  | CODCC |  |

## TCCCOM — Compradores Civil
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| PERCOMPRA | Float |  | Percentual Compra |  |
| CODCC | Integer |  | CODCC |  |

## TCCCON — Contrato Civil
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODEMPREE | Integer |  | Empreendimento |  |
| CODEMP | Integer |  | Empresa |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| DTCONTRATO | Date |  | Data Contrato |  |
| DTASSINATURA | Date |  | Data Assinatura |  |
| TPCONTRATO | String |  | Tipo Contrato | `T`=Adiantamento `A`=Obra em Andamento `P`=Permuta `D`=Com Dação em Pagamento `C`=Obra Concluída |
| DTPREVISAO | Date |  | Dt Previsão de Entrega das Chaves |  |
| CODPARCFIN | Integer |  | Cód. Parceiro Responsável Financeiro |  |
| CODMOEDA | Integer |  | Moeda do Contrato |  |
| CODFORM | Integer |  | Fórmula Padrão |  |
| DTULTVAR | Date |  | Última Variação |  |
| OBSERVACAO | String |  | Observação |  |
| CODUSUVAR | Integer |  | Usuário Responsável |  |
| CODCC | Integer |  | Nro. Contrato |  |

## TCCCOR — Corretores CC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| VLRCOMISSAO | Float |  | Vlr. Comissão |  |
| PERCOMISSAO | Float |  | Percentual Comissão |  |
| CODCC | Integer |  | CODCC |  |

## TCCEMP — Empreendimentos
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEMPREE | String |  | Empreendimento |  |
| CEP | String |  | Cep |  |
| CODEND | Integer |  | Endereço |  |
| NUMEND | String |  | Nro |  |
| CODBAI | Integer |  | Bairro |  |
| COMPLEMENTO | String |  | Complemento |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CAIXAPOSTAL | String |  | Caixa Postal |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| DTINICIO | Date |  | Dt. Inicio |  |
| QTDTORRES | Integer |  | Qtd. Torres |  |
| QTDANDAR | Integer |  | Qtd. Andares |  |
| QTDPAVIMENTO | Integer |  | Qtd. Pavimento |  |
| QTDUNIDADES | Integer |  | Qtd. Unidades |  |
| QTDUNIDANDAR | Integer |  | Qtd. Unidades Andar |  |
| REGISCARTO | String |  | Nro. Registro Cartório |  |
| MATRIMOVEL | String |  | Matricula |  |
| CARACINCORP | String |  | Característica da Incorporação |  |
| AREATERRENO | Float |  | Área Terreno |  |
| CARACTERRENO | String |  | Caracteriística do Terreno |  |
| CODEMPREE | Integer |  | Cód. Empreendimento |  |

## TCCFIN — Financeiro Civil
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMNEG | Integer |  | NUMNEG |  |
| NUFINORIG | Integer |  | NUFINORIG |  |
| NUFIN | Integer |  | NUFIN |  |
| CODCC | Integer |  | CODCC |  |

## TCCFOR — Formula Calculo Civil
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRFORM | String |  | Descrição Formula |  |
| FORMULA | String |  | Formula |  |
| CODFORM | Integer |  | Cod. Formula |  |

## TCCHTF — Troca Formula CC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIO | Date |  | Data |  |
| CODMOEDA | Integer |  | Moeda |  |
| CODCC | Integer |  | Contrato |  |
| CODFORM | Integer |  | Fórmula |  |

## TCCITE — Item CC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Unidade |  |
| VLRTAB | Float |  | Preço Tabela |  |
| VLRNEG | Float |  | Valor Negociado |  |
| CODCC | Integer |  | Contrato |  |

## TCCNEG — Negociação CC
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATAINI | Date |  | Dt. Inicio |  |
| QTDPAR | Integer |  | Qtd. Parcelas |  |
| VLRPAR | Float |  | Vlr. Parcela |  |
| CODMOEDA | Integer |  | Moeda |  |
| VLRTOT | Float |  | Vlr. Total |  |
| TIPVENC | String |  | Tipo Vencimento | `P`=Período `M`=Mensal |
| DIAVENC | Integer |  | Dia Vencimento |  |
| PERIODO | Integer |  | Periodicidade |  |
| NUMNEG | Integer |  | NUMNEG |  |
| FORPAG | String |  | Forma de Pagamento |  |
| DESCRICAO | String |  | Descrição |  |
| CODFORM | Integer |  | Fórmula |  |
| CODTIPVENDA | Integer |  | Negociação |  |
| DHTIPVENDA | DateTime |  | DHTIPVENDA |  |
| CODCTABCOINT | Integer |  | Banco |  |
| CODTIPTIT | Integer |  | Tipo Titulo |  |
| PROVIVAR | String |  | Provisiona Variação? | `N`=Não `S`=Sim |
| CODCC | Integer |  | CODCC |  |

## TCCPRO — Protocolo Civil
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTRECEBI | DateTime |  | Data Recebimento |  |
| DOCUMENTO | String |  | Documento |  |
| PESSOA | String |  | Nome Pessoa |  |
| IDENTIDADE | String |  | Identidade |  |
| NUMPROTOCOLO | Integer |  | Nro. Protocolo |  |
| ENTREGUE | String |  | Entregue | `N`=Não `S`=Sim |
| TIPO | String |  | Tipo Documento |  |
| OBSERVACAO | String |  | Observação |  |
| CODCC | Integer |  | CODCC |  |

## TCCRAT — TABLE TCCRAT
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUFIN | Integer |  | NUFIN |  |
| CODNAT | Integer |  | CODNAT |  |
| CODCENCUS | Integer |  | CODCENCUS |  |
| CODPROJ | Integer |  | CODPROJ |  |
| PERCRATEIO | Float |  | PERCRATEIO |  |
| CODCTACTB | Integer |  | CODCTACTB |  |
| NUMCONTRATO | Integer |  | NUMCONTRATO |  |
| DIGITADO | String |  | DIGITADO |  |
| CODPARC | Integer |  | CODPARC |  |
| CODSITE | Integer |  | CODSITE |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| ORIGEM | String |  | ORIGEM |  |

## TCCRES — ResidenciasEmpreendimento
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCENCUS | Integer |  | Cód.Centro Resultado Residencial |  |
| DTPREVISAO | Date |  | Dt Previsão de Entrega das Chaves |  |
| CODEMPREE | Integer |  | Empreendimento |  |

## TCCTES — TABLE TCCTES
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CPF | String |  | CPF |  |
| NOME | String |  | Nome |  |
| RG | String |  | Nro. Identidade |  |
| CODCC | Integer |  | CODCC |  |

## TCEDESP — Financeiro Comercio Exterior
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUFIN | Integer |  | NUFIN |  |
| NUIMP | Integer |  | NUIMP |  |

## TCIBEM — Imobilizados
Campos: 75

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEMATUAL | String |  | Bem atual |  |
| CODDEP | Integer |  | Departamento |  |
| DESCRBEM | String |  | Descrição do bem |  |
| DESCRABREV | String |  | Descrição abreviada |  |
| DTCOMPRA | Date |  | Data da compra |  |
| DTBAIXA | Date |  | Data da baixa |  |
| NUNOTA | Integer |  | Nro. Único |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| NUMNOTABAIXA | Integer |  | Nf. baixa |  |
| VLRAQUISICAO | Float |  | Valor aquisição |  |
| CODEMP | Integer |  | Empresa |  |
| CODPOSSUIDOR | Integer |  | Cód. possuidor |  |
| DTRETORNO | Date |  | Data retorno |  |
| NFDEVVENDA | Integer |  | Nf. devolução venda |  |
| NFRETORNO | Integer |  | Nf. retorno |  |
| NFSAIDA | Integer |  | Nf. saída |  |
| NOMEPOSSUIDOR | String |  | Nome possuidor |  |
| CODPROD | Integer |  | Produto |  |
| DTINICIODEP | Date |  | Data inicial |  |
| DTINICIOAJ | Date |  | Data inicial |  |
| DTFIMDEP | Date |  | Data final |  |
| DTFIMAJ | Date |  | Data final |  |
| VLRDEP | Float |  | Valor atual do bem |  |
| VLRDEPAJ | Float |  | Valor atual do bem |  |
| VLRSALDO | Float |  | Valor depreciado inicial |  |
| VLRSALDOAJ | Float |  | Valor depreciado inicial |  |
| TEMDEPRECIACAO | String |  | Tem depreciação | `S`=Sim `N`=Não |
| TEMAJ | String |  | Tem depreciação | `S`=Sim `N`=Não |
| NUNOTABAIXA | Integer |  | Nro. único baixa |  |
| CODBEMORIG | String |  | Bem origem |  |
| NUNOTADEV | Integer |  | Nro. único nota de devolução |  |
| NUNOTASAIDA | Integer |  | Nro. único nota de saída |  |
| DTINIREFCIAP | Date |  | Data inicial |  |
| VLRICMSFRTCIAP | Float |  | Valor crédito ICMS sobre frete |  |
| DTFIMREFCIAP | Date |  | Data final |  |
| QTDMESESCIAP | Integer |  | Quantidade de meses |  |
| DESCRUTILBEM | String |  | Descrição Utilização do Bem |  |
| VLRICMSCIAP | Float |  | Valor do ICMS |  |
| VLRICMSSTCIAP | Float |  | Valor crédito ICMS por subst.tributária |  |
| UTILIMOB | Integer |  | Util.Imobilizado | `09`=Outros `03`=Locação a Terceiros `02`=Prestação de Serviços `01`=Produção de Bens Destinados a Venda |
| TEMCREDPISCOFINSDEPR | String |  | Tem Créd.PIS/COFINS sobre Dep.mensal | `S`=Sim `N`=Não |
| VLRICMSDIFCIAP | Float |  | Valor crédito de ICMS dif.alíquota |  |
| CSTPIS | Integer |  | Cód.Sit.Tributária PIS | `99`=99 - Outras `98`=98 - Outras Entradas `9`=09 - Com Suspensão `8`=08 - Sem Incidência `75`=75 - Aquisição por Substituição Tributária_(+28)_ |
| TEMCREDPISCOFINSAQUI | String |  | Tem Créd. PIS/COFINS sobre Aquisição? | `N`=Não `S`=Sim |
| NUMCONTRATO | Integer |  | Número do contrato |  |
| CSTCOFINS | Integer |  | Cód.Sit.Tributária COFINS | `99`=99 - Outras `98`=98 - Outras Entradas `9`=09 - Com Suspensão `8`=08 - Sem Incidência `75`=75 - Aquisição por Substituição Tributária_(+28)_ |
| CREDPISCOFINSAQUIPAR | Integer |  | Parcelas Créd. PIS/COFINS sobre Aquisição | `12`=12 Parcelas `48`=48 Parcelas |
| NUNOTADEVVENDA | Integer |  | Nro. único dev.venda de bens |  |
| ALIQPIS | Float |  | Alíquota PIS |  |
| ALIQCOFINS | Float |  | Alíquota COFINS |  |
| VALORPRESENTE | Float |  | Valor Presente |  |
| TIPOENTCIAP | String |  | Tipo de Movimentação do Bem ou Componente | `SI`=SI - Saldo inicial de bens imobilizados `PE`=PE - Perecimento, Extravio ou Deterioração `OT`=OT - Outras Saídas do Imobilizado `MC`=MC - Imobilização oriunda do Ativo Circulante `IM`=IM - Imobilização de bem individual_(+4)_ |
| VLRCOMPRAAQUISICAO | Float |  | Valor total dos Bens |  |
| VLRTOTDESPESABEM | Float |  | Valor total das despesas |  |
| VLRDEPORIG | Float |  | Valor do Bem a ser Depreciado |  |
| VLREXCBASECRED | Float |  | Vlr. Parcela Exclusão BC Crédito |  |
| VIDAUTIL | Integer |  | Vida Útil do Bem (meses) |  |
| PISCOFMP540 | String |  | Participa da MP540 PIS/COFINS | `S`=Sim `N`=Não |
| NPARCPISCOF | Integer |  | Nro. Parcelas Apr. Cred. PIS/COFINS |  |
| DHDESMEMBRAMENTO | Date |  | Data do desmembramento |  |
| NUNOTAORIGDESMEMB | Integer |  | Nro. Único nota origem desmembramento |  |
| CODPRODORIG | Integer |  | Produto de origem desmembramento |  |
| CODUSUDESMEMBRAMENTO | Integer |  | Código Usuário Desmembramento |  |
| VLRCOMPRAAQUISICAOCALC | Float |  | Valor total dos Bens |  |
| VLRICMSCIAPCALC | Float |  | Valor do ICMS |  |
| VLRICMSSTCIAPCALC | Float |  | Valor crédito ICMS por subst.tributária |  |
| VLRPISCOMPRA | Float |  | Valor do PIS na compra |  |
| VLRCOFINSCOMPRA | Float |  | Valor da COFINS na compra |  |
| DIGITADOCOMPRA | String |  | Digitado na compra | `N`=Não `S`=Sim |
| CODUSUCOMPRA | Integer |  | Cód. Usuário Manut. Compra |  |
| DHALTERCOMPRA | DateTime |  | Data Manut. Compra |  |
| CODBEM | String |  | Código do bem |  |
| CODLOCAL | Integer |  | Local |  |
| DESCRLOCAL | String |  | Descrição Local |  |
| SALDO | Float |  | Saldo |  |

## TCICABCTE — Inventário de Bens
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINVENT | Date |  | Data Inventário |  |
| CODEMP | Integer |  | Empresa |  |

## TCICEX — Credito extemporâneo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | CODBEM |  |
| NUMPARCELA | Integer |  | Número da parcela |  |
| REFERENCIA | DateTime |  | Referência p/apropriação |  |
| BASECREDITO | Float |  | Base do crédito |  |
| CODPROD | Integer |  | CODPROD |  |

## TCICTA — Contas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo de Depreciação |  |
| CODBEM | String |  | Cód.Bem |  |
| CODCTACTB | Integer |  | Cód.Conta Contábil |  |
| CODHISTCTB | Integer |  | Cód.Histórico |  |
| CODPROD | Integer |  | Cód.Produto |  |

## TCICTE — Inventário de Bens
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINVENT | Date |  | Data Inventário |  |
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Produto |  |
| CODBEM | String |  | Código do Bem |  |
| EXISTENACP | String |  | Existe na Cópia | `S`=Sim `N`=Não |
| CODDEPCP | Integer |  | Departamento da Cópia |  |
| EXISTENACT | String |  | Existe na Contagem | `S`=Sim `N`=Não |
| CODDEPCT | Integer |  | Departamento da Contagem |  |
| CODEMPSIS | Integer |  | Empresa no Sistema |  |
| CODDEPSIS | Integer |  | Departamento no Sistema |  |
| AJUSTADO | String |  | Ajustado | `N`=Não `S`=Sim |
| NUNOTA | Integer |  | Nota da Baixa |  |

## TCIDEM — Demonstrativos
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Bem |  |
| REFERENCIA | DateTime |  | Data referência |  |
| TOTDEPINICIAL | Float |  | Total Depósito Inicial |  |
| VLRDEP | Float |  | Valor do Depósito |  |
| TOTDEPFINAL | Float |  | Total Depósito Final |  |
| SALDOINICIAL | Float |  | Saldo inicial |  |
| VLRBAIXA15 | Float |  | Valor baixa 15 |  |
| VLRINC15 | Float |  | VLRINC15 |  |
| VLRBAIXA16 | Float |  | Valor baixa 16 |  |
| VLRINC16 | Float |  | VLRINC16 |  |
| SALDOFINAL | Float |  | Saldo final |  |
| CODPROD | Integer |  | Produto |  |

## TCIDIB — Despesa Instalacao Bem
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTADESP | Integer |  | N° Único Nota de Despesa |  |
| VLRTOTRATEIO | Float |  | Valor Total Rateio |  |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Código Usuário |  |
| VLRPENDNOTA | Float |  | Valor Pendente da Nota |  |
| STATUSRATEIO | String |  | Status do Rateio | `P`=Pendente `C`=Concluído |
| NURATEIO | Integer |  | Nº de Rateio |  |

## TCIDIBI — Item Despesa Instalação Bem
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| CODBEM | String |  | Cód. Bem |  |
| VLRRATEIO | Float |  | Valor Rateio |  |
| VLRICMSRATEIO | Float |  | Valor ICMS Rateado |  |
| NURATEIO | Integer |  | Nº Rateio |  |

## TCIEST — Estrutura
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULO | String |  | Título |  |
| ORDEM | Integer |  | Ordem |  |
| TAMANHO | Integer |  | Tamanho |  |
| TIPO | String |  | Tipo | `T`=Texto `I`=Inteiro `M`=Lista `D`=Data `N`=Número |
| LISTA | String |  | Lista |  |
| CODPROD | Integer |  | Cód.Produto |  |

## TCIIBE — Bens da Nota Fiscal
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cód. produto |  |
| CODBEM | String |  | Cód. bem |  |
| ORDEM | Integer |  | Ordem de entrada do bem |  |
| NUNOTA | Integer |  | Nro. nota |  |

## TCILOC — Local
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Cód.Bem |  |
| DTENTRADA | DateTime |  | Data de entrada |  |
| CODUSU | Integer |  | Cód.Usuario |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODDEPTO | Integer |  | Cód.Departamento |  |
| NUNOTA | Integer |  | Número de nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cód.Produto |  |

## TCILOC_ATUAL — Local Atual
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Cód. Bem |  |
| DTENTRADA | DateTime |  | Data de Entrada |  |
| CODUSU | Integer |  | Usuário |  |
| CODEMP | Integer |  | Empresa |  |
| CODDEPTO | Integer |  | Departamento |  |
| NUNOTA | Integer |  | Número de nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |

## TCIMOV — Movimentação de Imobilizado
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Cód.Código do Bem |  |
| REFERENCIA | DateTime |  | Data referência |  |
| DTMOVTO | DateTime |  | Data do movimento |  |
| VALOR | Float |  | Valor |  |
| VLRDEP | Float |  | Valor |  |
| TIPO | Integer |  | Tipo |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| NUMLOTE | Integer |  | Lote |  |
| NUMLANC | Integer |  | Lançamento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPMOV | String |  | Tipo Movimento | `D`=Estorno Dep. Baixa `C`=Deprec. Baixa `A`=Deprec. Mensal |
| CODDEP | Integer |  | Cód.Departamento |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODPROD | Integer |  | Cód.Produto |  |

## TCIMOVAQ — Movimentação PIS/COFINS na aquisição
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Código do produto |  |
| CODBEM | String |  | Código do bem |  |
| CODIMP | Integer |  | Tipo imposto | `6`=PIS `7`=COFINS |
| CODEMP | Integer |  | Código empresa |  |
| STATUS | String |  | Status | `AC`=A contabilizar `AE`=A estornar `AF`=A finalizar `C`=Contabilizado `E`=Estornado_(+2)_ |
| REFERENCIA | Date |  | Data referência |  |
| DTMOVTO | Date |  | Data movimento |  |
| QTDPARC | Integer |  | Quantidade de parcelas | `12`=12 Parcelas `48`=48 Parcelas |
| VLRPARC | Float |  | Valor parcela |  |
| PARCACONTAB | Integer |  | Parcelas a contabilizar |  |
| VLRAQUI | Float |  | Valor aquisição |  |
| VLRTOTIMP | Float |  | Valor total do imposto |  |
| SALACONTAB | Float |  | Saldo a contabilizar |  |
| NUMLOTE | Integer |  | Número do Lote |  |
| CODCENCUS | Integer |  | Centro resultado |  |
| CODCTACTB | Integer |  | Conta contábil |  |
| CODCTACTBCTPR | Integer |  | Conta contábil contrapartida |  |
| CODEMPCONTAB | Integer |  | Código empresa contábil |  |
| NUPARCELA | Integer |  | Numero da parcela |  |

## TCISAL — Saldos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Cód.Bem |  |
| REFERENCIA | Date |  | Data referência |  |
| SALDO | Float |  | Saldo |  |
| TOTALDEP | Float |  | Total depreciado |  |
| CODPROD | Integer |  | Cód.Produto |  |

## TCISAL_ATUAL — Saldo Imobilizado Atual
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Cód. Bem |  |
| REFERENCIA | Date |  | Data referência |  |
| SALDO | Float |  | Saldo |  |
| TOTALDEP | Float |  | Total depreciado |  |
| CODPROD | Integer |  | Produto |  |

## TCITAX — Taxas de Depreciação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Cód.Bem |  |
| DTINICIO | Date |  | Data Inicial |  |
| TAXA | Float |  | Taxa |  |
| CODPROD | Integer |  | Cód.Produto |  |

## TCITAXAJ — Taxas de Ajustes de Depreciação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEM | String |  | Cód.Bem |  |
| DTINICIO | Date |  | Data Inicial |  |
| TAXA | Float |  | Taxa |  |
| CODPROD | Integer |  | Cód.Produto |  |

## TC_TGFCAB — Eixos Estratégicos
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHALTER | DateTime |  | Data de inclusão |  |
| APPKEY | String |  | Appkey |  |
| HASHLINHA | String |  | Hash |  |
| STATUS | Integer |  | Status |  |
| INTEGRADO | String |  | Integrado |  |
| IDPERSONALIZACAO | String |  | Id Personalização |  |
| ORIGEM | String |  | Origem |  |
| NUCHAVE | Integer |  | Nro Nota |  |

## TC_TGFFIN — Eixos Estratégicos
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHALTER | DateTime |  | Data de inclusão |  |
| APPKEY | String |  | Appkey |  |
| HASHLINHA | String |  | Hash |  |
| STATUS | Integer |  | Status |  |
| INTEGRADO | String |  | Integrado |  |
| IDPERSONALIZACAO | String |  | Id Personalização |  |
| ORIGEM | String |  | Origem |  |
| NUCHAVE | Integer |  | Nro Nota |  |

## TFCBCO — tabela de Currículos - recrutamento e seleção
Campos: 75

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECANDIDATO | String |  | Nome Completo |  |
| STATUS | Integer |  | Status | `3`=Funcionário `2`=Contratado externo `4`=Ex-funcionário `6`=Convocado `1`=Reprovado_(+2)_ |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| DTNASC | Date |  | Data de Nascimento |  |
| ESTADOCIVIL | Integer |  | Estado Civil | `6`=Divorciado(a) `5`=Desquitado(a) `1`=Solteiro(a) `7`=Outros `2`=Casado(a)_(+2)_ |
| NATURALIDADE | String |  | Naturalidade |  |
| GRAUINSTR | Integer |  | Grau de Instrução | `10`=Mestrado Completo `1`=Analfabeto `11`=Doutorado Completo `9`=Superior Completo `8`=Superior Incompleto_(+6)_ |
| PRETSALARIAL | Float |  | Pretensão salarial |  |
| PRETSALARIALINICIAL | Float |  | Pretensão salarial inicial |  |
| PRETSALARIALFINAL | Float |  | Pretensão salarial final |  |
| TIPOCURRICULO | Integer |  | Origem do Currículo | `3`=Outros `2`=Empresa `1`=Site |
| EMAIL | String |  | E-mail |  |
| CPF | String |  | CPF |  |
| IDENTIDADE | String |  | RG |  |
| ORGAORG | String |  | Órgão Expedidor |  |
| CNH | String |  | Número da CNH |  |
| DTVALCNH | Date |  | Data de validade CNH |  |
| NUMCPS | Integer |  | CTPS |  |
| SERIECPS | String |  | Série |  |
| UFCPS | Integer |  | UF CTPS |  |
| PIS | String |  | PIS |  |
| CATEGORIACNH | String |  | Categoria CNH |  |
| PAIS | String |  | Nacionalidade |  |
| VEICPROPRIO | String |  | Possui veículo próprio | `N`=Não `S`=Sim |
| DISPVIAGEM | String |  | Disponibilidade p/ viagem | `N`=Não `S`=Sim |
| DISPMUDANCA | String |  | Disponibilidade p/ mudança | `N`=Não `S`=Sim |
| ESTRANGEIRO | String |  | É estrangeiro | `N`=Não `S`=Sim |
| INDICACAO | String |  | Indicação |  |
| FOTO | Boolean |  | Foto |  |
| TELPREF | String |  | Telefone Preferencial |  |
| TELCEL | String |  | Telefone Celular |  |
| TELRES | String |  | Telefone Residencial |  |
| TELCOM | String |  | Telefone Comercial |  |
| RAMAL | String |  | Ramal |  |
| TIPOEND | String |  | Tipo Endereço | `RUA`=Rua `VIE`=Viela `JD`=Jd `TV`=Tv `QD`=Qd_(+7)_ |
| NOMEEND | String |  | Endereço |  |
| NUMEND | String |  | Número |  |
| COMPLEND | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| CEP | String |  | CEP |  |
| DEFICIENTE | String |  | Deficiente |  |
| DESCRDEFICIENCIA | String |  | Descrição Deficiencia |  |
| ANOCHEGPAIS | Integer |  | Ano de chegada ao país |  |
| RNE | String |  | RNE |  |
| SITPAIS | String |  | Situação Pais |  |
| DTVALPAIS | Date |  | Data Volta Pais |  |
| DTINCLUSAO | Date |  | Data de Inclusão |  |
| CODTIPPARC | Integer |  | Cód Parceiro | `0`=default |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Cód Usuário |  |
| CONSIDERACOES | String |  | Considerações |  |
| INCLUSAOMGE | String |  | Inclusão MGE |  |
| NUCURRICULOBT | Integer |  | Número Currículo |  |
| TIPDEFICIENCIA | Integer |  | Tipo Deficiência |  |
| SKYPE | String |  | Skype |  |
| GOOGLEPLUS | String |  | Google+ |  |
| FACEBOOK | String |  | Facebook |  |
| TWITTER | String |  | Twitter |  |
| LINKEDIN | String |  | Linkedin |  |
| DEFINDEPENDENTE | String |  | É independente para as atividades da vida diária? | `N`=Não `S`=Sim |
| DEFAUDITIVO | String |  | Possui deficiência auditiva? | `N`=Não `S`=Sim |
| USOAPAUDITIVO | String |  | Faz uso de aparelho auditivo? | `S`=Sim `N`=Não |
| DEFINTELECTUAL | String |  | Possui deficiência intelectual? | `N`=Não `S`=Sim |
| DEFVISUAL | String |  | Possui deficiência visual? | `S`=Sim `N`=Não |
| DEFICIENTEF | String |  | Possui Deficiencia Fisica? | `S`=Sim `N`=Não |
| DEFFALA | String |  | Possui deficiência na fala? | `N`=Não `S`=Sim |
| DEFOUTRAS | String |  | Outras deficiências |  |
| DEFRECURSOS | Integer |  | Quais recursos utiliza para a realização do trabalho? | `11`=Outros `10`=Software de voz `8`=Prótese `9`=Muletas `5`=Cadeira de rodas_(+6)_ |
| DEFOUTROSRECURSOS | String |  | Outros recursos/adaptações que utiliza para realização do trabalho |  |
| DEFRECURSOSIMPRES | Integer |  | Recursos imprescindíveis para a acessibilidade no local de trabalho | `4`=Banco ou assento específico `3`=Elevador `2`=Indicação em Braile `1`=Rampas `5`=Outros |
| INAPROPRIADO | String |  | Currículo Inapropriado | `S`=Sim `N`=Não |
| NUCURRICULO | Integer |  | Cód. Currículo |  |

## TFCCAR — Cargos selecionados no currículo
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCARGO | Integer |  | Cargo |  |
| CANDIDATO | String |  | Candidato | `N`=Não `S`=Sim |
| TRIAGEM | String |  | Triagem | `S`=Sim `N`=Não |
| NUCURRICULO | Integer |  | Curriculo |  |

## TFCCUR — Curso - currículo
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODTIPCURSO | Integer |  | Tipo |  |
| TITULO | String |  | Curso |  |
| DATINICIO | Date |  | Data Início |  |
| DATFIM | Date |  | Data Fim |  |
| CARGAHORARIA | Integer |  | Carga horária em horas |  |
| LOCAL | String |  | Instituição |  |
| NUCURRICULO | Integer |  | NUCURRICULO |  |

## TFCDEP — Dependentes - currículo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| GRAUPARENTESCO | Integer |  | Grau | `6`=Inválido(a) `3`=Sogro(a) `1`=Esposo(a) `7`=Outros `4`=Filho(a)_(+2)_ |
| DTNASC | Date |  | Data de Nascimento |  |
| SEXO | String |  | Sexo | `M`=Masculino `F`=Feminino |
| NUCURRICULO | Integer |  | NUCURRICULO |  |

## TFCEXP — Tabela experiência profissional - currículo
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCURRICULO | Integer |  | NUCURRICULO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NOMEEMPRESA | String |  | Nome da empresa |  |
| TIPOEMPRESA | String |  | Tipo | `3`=Filantrópica `1`=Privada `2`=Pública |
| DATADM | Date |  | Data Início |  |
| DATDEM | Date |  | Data Saída |  |
| ULTCARGOOCUPADO | String |  | Último Cargo |  |
| ULTSALARIO | Float |  | Último salário |  |
| TIPOEND | String |  | Tipo Endereço | `TV`=Tv `PCA`=Pca `VIE`=Viela `AL`=Al `AV`=Av_(+7)_ |
| NOMEEND | String |  | Endereço |  |
| NUMEND | String |  | Número |  |
| COMPLEND | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | UF |  |
| CEP | String |  | CEP |  |
| EMAIL | String |  | E-mail |  |
| TELEFONE | String |  | Telefone |  |
| FAIXASALARIALINICIAL | Float |  | FAIXASALARIALINICIAL |  |
| FAIXASALARIALFINAL | Float |  | FAIXASALARIALFINAL |  |
| DESCRATIVIDADES | String |  | Descrição Atividades |  |
| Atual | String |  | Emprego Atual | `N`=Não `S`=Sim |

## TFCFCO — Funções currículo
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCURRICULO | Integer |  | Curriculo |  |
| CODFUNCAO | Integer |  | Função |  |

## TFCPER — Perfil do Currículo
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERFIL | Integer |  | Cód. Perfil |  |
| NUCURRICULO | Integer |  | Cód. Currículo |  |

## TFCTPC — Tipo de Curso
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTIPCURSO | String |  | Descrição |  |
| CODTIPCURSO | Integer |  | Cód. Curso |  |

## TFTCTA — Conta Fintech
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PAGAMENTOATIVO | String |  | Pagamento Ativo | `S`=Sim `N`=Não |
| CODCTA | Integer |  | Cód. Conta |  |
| ULIDAPI | String |  | ID API |  |
| PIXATIVO | String |  | Pix Ativo | `S`=Sim `N`=Não |
| CODTIPTITPIX | Integer |  | Tipo de Título |  |
| CODTIPOPERBAIXAPIX | Integer |  | Tipo de Operação Baixa |  |
| CODLANCBAIXAPIX | Integer |  | Lançamento Baixa |  |
| APIBAIXAAUTOMATICA | String |  | Baixa Automática |  |
| APICONCILIACAOAUTOMATICA | String |  | Conciliação Automática |  |

## TFTPIX — Pix Fintech
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPIX | Integer |  | Nro. Único Pix |  |
| NUFIN | Integer |  | Nro. Financeiro |  |
| SEQPIX | Integer |  | Sequencial Pix |  |
| CONTA | Integer |  | Conta Pix |  |
| TXID | String |  | ID Transação |  |
| EMV | String |  | EMV |  |
| IDAPI | String |  | ID Pix API |  |
| MODALIDADE | String |  | Modalidade |  |
| STATUS | String |  | Status |  |
| MSGPAGADOR | String |  | Mensagem Pagador |  |
| VALOR | Float |  | Vlr. Pix |  |
| DHEXPIRACAO | DateTime |  | Dt. Expiração |  |
| DHCRIACAO | DateTime |  | Dt. Criação |  |
| DHPAGAMENTO | DateTime |  | Dt. Pagamento |  |
| DHCANCELAMENTO | DateTime |  | Dt. Cancelamento |  |

## TFXADF — Tabela de Ajuste de Documento do Checkout
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| STATUS | String |  | Status | `I`=Processado `P`=Pendente `E`=Processado com Erro |
| CODEMP | Integer |  | Código da Empresa |  |
| SEQVDA | Integer |  | Seq. Venda |  |
| NUMNOTA | Integer |  | Nro. Único Fiscal |  |
| SERIENOTA | String |  | Série |  |
| VLRVENDA | Float |  | Valor da Nota |  |
| EXCCAN | String |  | Excluir Cancelamento? | `S`=Sim `N`=Não |
| EXCINU | String |  | Excluir Inutilização? | `N`=Não `S`=Sim |
| EXCXML | String |  | Excluir XML? | `N`=Não `S`=Sim |
| INCCAN | String |  | Incluir Cancelamento? | `S`=Sim `N`=Não |
| INCINU | String |  | Incluir Inutilização? | `N`=Não `S`=Sim |
| INCXML | String |  | Incluir XML? | `S`=Sim `N`=Não |
| INCNOTA | String |  | Incluir Nota? | `S`=Sim `N`=Não |
| ARQUIVO | C |  | Arquivo |  |
| MOTIVOCAN | String |  | Motivo do Cancelamento |  |
| NUMPROTOCCAN | String |  | Núm. Protocolo de Cancelamento |  |
| DHPROTOCCAN | DateTime |  | Dh. Protocolo de Cancelamento |  |
| MOTIVOINU | String |  | Motivo da Inutilização |  |
| NUMPROTOCINU | String |  | Núm. Protocolo da Inutilização |  |
| DHPROTOCINU | DateTime |  | Dh. Protocolo da Inutilização |  |
| DHIMPORT | DateTime |  | Dh. Importação |  |
| ERRO | String |  | Mensagem de Erro |  |
| NUAJUSTE | Integer |  | Nro. Único Ajuste |  |

## TFXAII — Acompanhamento Informacao de Integração
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHECKOUT | String |  | Checkout |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| EMPRESA | String |  | Empresa |  |
| NROUNICO | Integer |  | Nr. Único |  |
| SERIE | Integer |  | Série |  |
| NOMEINTEGRACAO | String |  | Nome Integração |  |
| NUACOMPANHAMENTO | Integer |  | Núm. Acompanhamento |  |
| DHALTERACAO | DateTime |  | Dh. Alteração |  |
| NROCHECKOUT | Integer |  | Núm. Checkout |  |

## TFXBLC — FOX-TFXBLC
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBALANCA | Integer |  | Cód.Balança |  |
| DESCRICAO | String |  | Descrição |  |
| MODELO | String |  | Modelo |  |
| PORTA | String |  | Porta | `COM9`=COM9 `COM8`=COM8 `COM7`=COM7 `COM6`=COM6 `COM5`=COM5_(+4)_ |
| VELOCIDADE | Integer |  | Velocidade |  |
| TIMEOUT | Integer |  | TimeOut |  |
| ATIVA | String |  | Ativa | `S`=Sim `N`=Não |
| NUVERSAO | Integer |  | NUVERSAO |  |
| CODPDV | Integer |  | Cód.PDV |  |

## TFXBPA — BandeiraParceiro
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SUBTIPOVENDA | Integer |  | Subtipovenda |  |
| FISCAL | String |  | Fiscal |  |
| CODPARCTEF | Integer |  | CodParceiroTef |  |
| NUVERSAO | Integer |  | Nuversao |  |
| EHPOS | String |  | EhPos |  |
| ID | Integer |  | Identificador |  |

## TFXCNF — FOX-TFXCNF
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCONTINGENCIA | Integer |  | Cód.Contingência |  |
| CODEMPRESA | Integer |  | Cód.Empresa |  |
| DATAENTRADA | DateTime |  | Dt.Entrada |  |
| HORAENTRADA | Integer |  | Hora Entrada |  |
| DATASAIDA | DateTime |  | Dt.Saída |  |
| HORASAIDA | Integer |  | Hora Saída |  |
| TIPOCONTINGENCIA | Integer |  | Tipo de Contingência |  |
| TIPOENTRADA | String |  | Tipo de Entrada |  |
| JUSTIFICATIVA | String |  | Justificativa |  |
| APLICARPARATODOS | String |  | Aplicar para Todos | `S`=Sim `N`=Não |
| NUVERSAO | Integer |  | NUVERSAO |  |
| CODPDV | Integer |  | Cód.Pdv |  |

## TFXEAN — TABLE TFXEAN
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBARRA | String |  | CODBARRA |  |
| CODVOL | String |  | CODVOL |  |
| CODPROD | Integer |  | CODPROD |  |
| VOLUMEPRINCIPAL | String |  | VOLUMEPRINCIPAL |  |
| DIVIDEMULTIPLICA | String |  | DIVIDEMULTIPLICA |  |
| QUANTIDADE | Integer |  | QUANTIDADE |  |
| PRODUTONFE | Integer |  | PRODUTONFE |  |
| TIPGTINNFE | Integer |  | TIPGTINNFE |  |
| UNIDTRIB | String |  | UNIDTRIB |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| ORIGEMEAN | Integer |  | ORIGEMEAN |  |
| CONTROLE | String |  | CONTROLE |  |
| CODLOCAL | Integer |  | CODLOCAL |  |
| MULTIPVLR | Float |  | MULTIPVLR |  |
| ATUNUVERSAO | String |  | ATUNUVERSAO |  |
| ID | Integer |  | ID |  |

## TFXECE — FOX-TFXECE
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| AMBIENTE | String |  | AMBIENTE |  |
| CERTIFICADO | C |  | CERTIFICADO |  |
| PWCERTIFICADO | String |  | PWCERTIFICADO |  |
| ASSINATURASAT | String |  | ASSINATURASAT |  |
| DTVALIDADE | DateTime |  | DTVALIDADE |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| CODEMPRESA | Integer |  | CODEMPRESA |  |

## TFXFCO — FOX-TFXFCO
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMETELA | String |  | Nome tela |  |
| NOMETELAPAI | String |  | Nome Tela Pai |  |
| DESCRICAO | String |  | Descrição |  |
| ATALHO | String |  | Atalho padrão |  |
| ATALHOTEXT | String |  | Atalho Externo |  |
| MENU | String |  | Menu |  |
| SUBMENU | String |  | SubMenu |  |
| CONCENTRADOR | String |  | Concentrador |  |
| ORDEM | Integer |  | Ordem |  |
| DEFINEACESSO | String |  | Define Acesso |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| IDFUNCAO | String |  | Id.Função |  |

## TFXFPU — FOX-TFXFPU
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSUARIO | Integer |  | CODUSUARIO |  |
| IDFUNCAO | String |  | IDFUNCAO |  |
| ATALHO | String |  | ATALHO |  |
| ATALHOTEXT | String |  | ATALHOTEXT |  |
| NOMETELA | String |  | NOMETELA |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| ATUNUVERSAO | String |  | ATUNUVERSAO |  |
| CODPERFIL | Integer |  | CODPERFIL |  |

## TFXIMP — FOX-TFXIMP
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIMP | Integer |  | Cód.Impressora |  |
| DESCRICAO | String |  | Descrição |  |
| MODELO | String |  | Modelo | `SwedaSI300`=SWEDA SI300 `EponTm_T20`=EPSON TMT20 `Emulador`=EMULADOR `ElginI9`=ELGIN I9 `DarumaDR800`=DARUMA DR800_(+2)_ |
| PORTA | String |  | Porta | `COM9`=COM9 `COM8`=COM8 `COM7`=COM7 `COM6`=COM6 `COM5`=COM5_(+5)_ |
| ATIVA | String |  | Ativa | `S`=Sim `N`=Não |
| PADRAO | String |  | Padrão | `S`=Sim `N`=Não |
| COMPARTILHA | String |  | Compartilha | `S`=Sim `N`=Não |
| TERMICA | String |  | Térmica | `S`=Sim `N`=Não |
| QTDCOLUNAS | Integer |  | Qtd. de Colunas |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| CODPDV | Integer |  | Cód.PDV |  |

## TFXINU — FOX-TFXINU
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPRESA | Integer |  | Cód.Empresa |  |
| SERIE | String |  | Série |  |
| DOCFISCAL | Integer |  | Documento Fiscal |  |
| DTMOV | DateTime |  | Dt.Movimento |  |
| MOTIVO | String |  | Motivo |  |
| NUMPROTOC | String |  | Nro.Protocolo |  |
| DHPROTOC | DateTime |  | Dh.Protocolo |  |
| CODUSUARIO | Integer |  | Cód.Usuário |  |
| TPAMBNFE | Integer |  | Tipo de Ambiente |  |
| ENTSAI | String |  | Entrada ou Saida |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| NROUNICOFISCAL | Integer |  | Nro.Unico Fiscal |  |

## TFXIPV — FOX-TFXIPV
Campos: 92

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ALIQDIFERENCIAL | Float |  | ALIQDIFERENCIAL |  |
| ALIQINTDEST | Float |  | ALIQINTDEST |  |
| ALIQPARADIFAL | Float |  | ALIQPARADIFAL |  |
| ALIQTRIBESTADUAL | Float |  | ALIQTRIBESTADUAL |  |
| ALIQTRIBFEDIMP | Float |  | ALIQTRIBFEDIMP |  |
| ALIQTRIBFEDNAC | Float |  | ALIQTRIBFEDNAC |  |
| ALIQTRIBIMPORTACAO | Float |  | ALIQTRIBIMPORTACAO |  |
| ALIQTRIBMUNICIPAL | Float |  | ALIQTRIBMUNICIPAL |  |
| ALIQTRIBNACIONAL | Float |  | ALIQTRIBNACIONAL |  |
| ALIQUOTA | Float |  | ALIQUOTA |  |
| ALIQUOTANORMAL | Float |  | ALIQUOTANORMAL |  |
| BASE | Float |  | BASE |  |
| BASEDIFAL | Float |  | BASEDIFAL |  |
| BASEFCP | Float |  | BASEFCP |  |
| BASEFCPINT | Float |  | BASEFCPINT |  |
| BASERED | Float |  | BASERED |  |
| BASICMMOD | Integer |  | BASICMMOD |  |
| BASICMSTMOD | Integer |  | BASICMSTMOD |  |
| CODEMP | Integer |  | CODEMP |  |
| CODESPECST | Integer |  | CODESPECST |  |
| CODIMP | Integer |  | CODIMP |  |
| CODINC | Integer |  | CODINC |  |
| CODLST | Integer |  | CODLST |  |
| CODPROD | Integer |  | CODPROD |  |
| CODTRIBMUNISS | String |  | CODTRIBMUNISS |  |
| CODUSU | Integer |  | CODUSU |  |
| COMIVA | String |  | COMIVA |  |
| CST | Integer |  | CST |  |
| CSOSN | Integer |  | CSOSN |  |
| CODTRIB | Integer |  | CODTRIB |  |
| CODCFO | Integer |  | CODCFO |  |
| DHALTER | DateTime |  | DHALTER |  |
| DIGITADO | String |  | DIGITADO |  |
| IVA | Float |  | IVA |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| PAUTA | Float |  | PAUTA |  |
| PERCFCP | Float |  | PERCFCP |  |
| PERCFCPINT | Float |  | PERCFCPINT |  |
| PERCINSSESPECIAL | Float |  | PERCINSSESPECIAL |  |
| PERCPARTDIFAL | Float |  | PERCPARTDIFAL |  |
| PERCREDBASE | Float |  | PERCREDBASE |  |
| PERCVLR | String |  | PERCVLR |  |
| RETEMFIN | String |  | RETEMFIN |  |
| TIPCALCDIFAL | Integer |  | TIPCALCDIFAL |  |
| TIPO | Integer |  | TIPO |  |
| TIPODEDISS | String |  | TIPODEDISS |  |
| TIPOINSSESPECIAL | String |  | TIPOINSSESPECIAL |  |
| VALOR | Float |  | VALOR |  |
| VALORDIFERENCIAL | Float |  | VALORDIFERENCIAL |  |
| VLRCRED | Float |  | VLRCRED |  |
| VLRDIFALDEST | Float |  | VLRDIFALDEST |  |
| VLRDIFALREM | Float |  | VLRDIFALREM |  |
| VLRFCP | Float |  | VLRFCP |  |
| VLRFCPINT | Float |  | VLRFCPINT |  |
| VLRICMSPARADIFAL | Float |  | VLRICMSPARADIFAL |  |
| VLRINSSESPECIAL | Float |  | VLRINSSESPECIAL |  |
| VLRREPDIFALFCP | Float |  | VLRREPDIFALFCP |  |
| VLRREPRED | Float |  | VLRREPRED |  |
| PERCREDBASEEFET | Float |  | PERCREDBASEEFET |  |
| BASEREDEFET | Float |  | BASEREDEFET |  |
| ALIQUOTAEFET | Float |  | ALIQUOTAEFET |  |
| VALOREFET | Float |  | VALOREFET |  |
| PRODUTONFE | String |  | Produto para NF-e |  |
| GTINNFE | String |  | GTINNFE |  |
| GTINTRIBNFE | String |  | GTINTRIBNFE |  |
| RECALCULAR | String |  | "RECALCULAR" |  |
| CODBENEFNAUF | String |  | Cód. de Benefício Fiscal na UF |  |
| ATUNUVERSAO | String |  | ATUNUVERSAO |  |
| CODMOTDESONERACAO | Integer |  | Cód. Motivo Desoneração |  |
| REDICMSBCPISCOFINS | String |  | "Deduzir valor do ICMS na Base do PIS e COFINS" |  |
| CODCST | String |  | Código de Situação Tributária |  |
| CCLASSTRIB | String |  | Código de Classificação Tributária |  |
| PERCISESPEC | Float |  | Alíquota específica por unidade de medida apropriada |  |
| PERCDIF | Float |  | Percentual do diferimento |  |
| VLRDIF | Float |  | Valor do Diferimento |  |
| VLRDEVTRIB | Float |  | Valor do tributo devolvido |  |
| PERCREDALIQ | Float |  | Percentual da redução de alíquota |  |
| PERCALIQEFET | Float |  | Alíquota Efetiva que será aplicada a Base de Cálculo |  |
| CCREDPRES | String |  | Código de Class. Créd. Presumido |  |
| PCREDPRES | Float |  | % do Crédito Presumido |  |
| VCREDPRES | Float |  | Valor do Crédito Presumido |  |
| CREDPRESCOND | Float |  | Valor do Crédito Pres. Cond. Susp. |  |
| JUSTIFICATIVASCORE | String |  | Justificativa do Score da Aliquota |  |
| ALIQADREM | Float |  | Alíquota ad rem do IBS/CBS |  |
| VLRMONO | Float |  | Valor do IBS/CBS monofásico |  |
| ALIQADREMSR | Float |  | Alíquota ad rem do IBS/CBS sujeito a retenção |  |
| VLRMONOSR | Float |  | Valor do IBS/CBS monofásico sujeito a retenção |  |
| ALIQADREDRETANT | Float |  | Alíquota ad rem do IBS/CBS retido anteriormente |  |
| VLRRETANT | Float |  | Valor do IBS/CBS retido anteriormente |  |
| TOTIBSMONO | Float |  | Total de IBS Monofásico |  |
| PERCREDGOVALIQ | Float |  | Percentual da redução de alíquota Governamental |  |
| VLRANTREDGOV | Float |  | Valor do IBS/CBS sem a redução governamental |  |

## TFXITV — FOX-TFXITV
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PDV | Integer |  | Pdv |  |
| CODSTATUS | Integer |  | Cód. Status |  |
| STATUS | String |  | Status |  |
| DADOS | C |  | Dados |  |
| DTINCLUSAO | DateTime |  | Data Inclusão |  |
| DTALTER | DateTime |  | Data Alteração |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| TABELA | String |  | Tabela |  |
| PROCESSORDER | Integer |  | Ordem de Processamento |  |
| SEQ | Integer |  | Seq |  |

## TFXIVD — FOX-TFXIVD
Campos: 43

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ALIQICMS | Float |  | ALIQICMS |  |
| ALIQICMSRED | Float |  | ALIQICMSRED |  |
| BASEICMS | Float |  | BASEICMS |  |
| BASESTUFDEST | Float |  | BASESTUFDEST |  |
| BASESUBSTIT | Float |  | BASESUBSTIT |  |
| BASESUBSTSEMRED | Float |  | BASESUBSTSEMRED |  |
| BASICMMOD | Integer |  | BASICMMOD |  |
| BASICMSTMOD | Integer |  | BASICMSTMOD |  |
| CANCELADO | String |  | CANCELADO |  |
| CODANTECIPST | String |  | CODANTECIPST |  |
| CODCFO | Integer |  | CODCFO |  |
| CODEMP | Integer |  | CODEMP |  |
| CODESPECST | Integer |  | CODESPECST |  |
| CODEXEC | Integer |  | CODEXEC |  |
| CODLOCALORIG | Integer |  | CODLOCALORIG |  |
| CODOBSPADRAO | Integer |  | CODOBSPADRAO |  |
| CODPROD | Integer |  | CODPROD |  |
| CODTRIB | Integer |  | CODTRIB |  |
| CODVEND | Integer |  | CODVEND |  |
| CODVOL | String |  | CODVOL |  |
| CONTROLE | String |  | CONTROLE |  |
| CSOSN | Integer |  | CSOSN |  |
| IDALIQICMS | Integer |  | IDALIQICMS |  |
| NUFOP | Integer |  | NUFOP |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| ORIGPROD | String |  | ORIGPROD |  |
| PENDENTE | String |  | PENDENTE |  |
| PERCDESC | Float |  | PERCDESC |  |
| PESO | Float |  | PESO |  |
| PRODUTONFE | String |  | PRODUTONFE |  |
| QTDNEG | Float |  | QTDNEG |  |
| QTDVOL | Integer |  | QTDVOL |  |
| USOPROD | String |  | USOPROD |  |
| VARIACAOFCP | Integer |  | VARIACAOFCP |  |
| VLRCUS | Float |  | VLRCUS |  |
| VLRDESC | Float |  | VLRDESC |  |
| VLRICMS | Float |  | VLRICMS |  |
| VLRICMSUFDEST | Float |  | VLRICMSUFDEST |  |
| VLRREPRED | Float |  | VLRREPRED |  |
| VLRSUBST | Float |  | VLRSUBST |  |
| VLRTOT | Float |  | VLRTOT |  |
| VLRUNIT | Float |  | VLRUNIT |  |
| CODBENEFNAUF | String |  | Cód. de Benefício Fiscal na UF |  |

## TFXPAF — FOX-TFXPAF
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERFIL | Integer |  | Cód.Perfil |  |
| CODUSUARIO | Integer |  | Cód.Usuário |  |
| CHAVE | String |  | Chave |  |
| DESCRICAO | String |  | Descrição |  |
| GRUPO | String |  | Grupo |  |
| TIPO | String |  | Tipo | `L`=Lógico `I`=Inteiro `H`=Hexadecimal `C`=Combo `D`=Data_(+1)_ |
| LOGICO | String |  | Lógico | `S`=Sim `N`=Não |
| INTEIRO | Integer |  | Inteiro |  |
| NUMERICO | Float |  | Numero |  |
| DT | Date |  | Data |  |
| TEXTO | String |  | Texto |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| CODEMPRESA | Integer |  | Cód.Empresa |  |

## TFXPDU — FOX-TFXPDU
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSUARIO | Integer |  | CODUSUARIO |  |
| ATIVO | String |  | ATIVO |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| ATUNUVERSAO | String |  | ATUNUVERSAO |  |
| CODPDV | Integer |  | CODPDV |  |

## TFXPDV — FOX-TFXPDV
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPRESA | Integer |  | Cód.Empresa |  |
| APRESENTAIMGPRODUTO | String |  | Apresenta Imagem Produto | `S`=Sim `N`=Não |
| TIPOEQPFISCAL | Integer |  | Tp.Equipamento Fiscal | `1`=SAT `0`=NFC-e |
| IMPRESSORADEFAULT | String |  | Impressora Default |  |
| SATDEFAULT | String |  | Sat.Default |  |
| ASSINATURA | String |  | Assinatura |  |
| CONFIGURADO | String |  | Configurado | `S`=Sim `N`=Não |
| HOMOLOGACAO | String |  | Homologação | `S`=Sim `N`=Não |
| CONTINGENCIASAT | String |  | ContigenciaSAT | `S`=Sim `N`=Não |
| INTEGRAPARCEIRO | String |  | Integra Parceiro | `S`=Sim `N`=Não |
| IP | String |  | IP |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| TIPOTEF | Integer |  | Tipo TEF | `3`=Pay&Go `1`=Auttar `0`=Não Usa |
| CSCH | String |  | CSC Homologação |  |
| IDTOKENH | String |  | Id.Token Homologação |  |
| SERIE | String |  | Serie |  |
| HARDWAREINFO | C |  | Informações de Hardware |  |
| CODPDV | Integer |  | Cód.Pdv |  |
| DESCRICAO | String |  | Descrição |  |

## TFXPRC — TABLE TFXPRC
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTAB | Integer |  | NUTAB |  |
| VLRVENDA | Float |  | VLRVENDA |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| DATAVIGOR | DateTime |  | DATAVIGOR |  |
| CODTAB | Integer |  | Código |  |
| CODPROD | Integer |  | CODPROD |  |

## TFXRTP — Restrições de Tipo de Negociação
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTAB | Integer |  | Nro. Tabela de Preços |  |
| CODTPV | Integer |  | Cód. Tipo de Negociação |  |
| DHALTERTPV | DateTime |  | Data & Hora Alteração Tipo de Negociação |  |
| DHALTER | DateTime |  | Data & Hora de Alteração |  |
| ATIVO | String |  | Ativo |  |
| ID | Integer |  | Identificação |  |

## TFXSAT — FOX-TFXSAT
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSAT | Integer |  | Cód.Sat |  |
| DESCRICAO | String |  | Descrição |  |
| MODELO | String |  | Modelo |  |
| PORTA | String |  | Porta | `COM9`=COM9 `COM8`=COM8 `COM7`=COM7 `COM6`=COM6 `COM5`=COM5_(+5)_ |
| CODATIVACAO | String |  | Cód.Ativação |  |
| NROSERIE | String |  | Nro.Série |  |
| ATIVA | String |  | Ativo | `S`=Sim `N`=Não |
| COMPARTILHA | String |  | Compartilha | `S`=Sim `N`=Não |
| NUVERSAO | Integer |  | NUVERSAO |  |
| CODPDV | Integer |  | Cód.PDV |  |

## TGCCAL — Informações de Crédito do Parceiro
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCRED | Integer |  | Cód.Crédito |  |
| CHAVE | String |  | Chave |  |
| DTCALC | DateTime |  | Data Cálculo |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| FORMULA | String |  | Fórmula |  |
| VALOR | Float |  | Valor |  |
| OBS | String |  | Observação |  |
| CODPARC | Integer |  | Cód.Parceiro |  |

## TGCCRED — Grupo para Análise de Crédito
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCRED | String |  | Descrição Crédito |  |
| FORMULALC | String |  | Fórmula Limite de Crédito |  |
| FORMULALCM | String |  | Fórmula Crédito Mensal |  |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODCRED | Integer |  | Cód.Crédito |  |

## TGCGRU — Grupo para Informações da Análise de Crédito
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOCRED | Integer |  | Cód.Grupo Crédito |  |
| DESCRGRUPOCRED | String |  | Descrição Grupo Crédito |  |
| ORDEM | Integer |  | Ordem |  |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODCRED | Integer |  | Cód.Crédito |  |

## TGCINF — Informações Necessárias para o Cálculo
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOCRED | Integer |  | Cód.Grupo Crédito |  |
| CODINFCRED | Integer |  | Cód.Informações de Crédito |  |
| DESCRINFCRED | String |  | Descrição das Informações de Crédito |  |
| CHAVE | String |  | Chave |  |
| TIPO | String |  | Tipo | `L`=Lista `V`=Valor `C`=Fórmula `S`=Comando SQL |
| OBRIGATORIO | String |  | Obrigatório | `S`=Sim `N`=Não |
| PERIODICIDADE | Integer |  | Periodicidade |  |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ORDEM | Integer |  | Ordem |  |
| DECIMAIS | Integer |  | Decimais |  |
| FORMULA | String |  | Fórmula |  |
| OBS | String |  | Observação |  |
| CODCRED | Integer |  | Cód.Crédito |  |

## TGCPAR — GC Limites de Crédito
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTCALC | DateTime |  | Data Cálculo |  |
| CODCRED | Integer |  | Cód.Crédito |  |
| LIMCREDCALC | Float |  | Cálculo Limite Crédito |  |
| LIMCREDMENSALCALC | Float |  | Cálculo Limite Crédito Mensal |  |
| CODUSUCALC | Integer |  | Cód. Usuário Calculo |  |
| DTEFETIVACAO | DateTime |  | Data Efetivação |  |
| LIMCRED | Float |  | Limite Crédito |  |
| LIMCREDMENSAL | Float |  | Limite Crédito Mensal |  |
| OBS | String |  | Observação |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODPARC | Integer |  | Cód.Parceiro |  |

## TGICAB — TGICAB
Campos: 58

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAOPROJETO | String |  | Versão |  |
| NOMEPROJ | String |  | Nome Projeto |  |
| DTPROJETO | DateTime |  | Dt.Projeto |  |
| CODPARC | Integer |  | Parceiro |  |
| CODMOEDA | Integer |  | Moeda |  |
| VLRMOEDA | Float |  | Valor Moeda |  |
| PERCCOMISSAO1 | Float |  | PERCCOMISSAO1 |  |
| PERCCOMISSAO2 | Float |  | PERCCOMISSAO2 |  |
| PERCCOMISSAO3 | Float |  | PERCCOMISSAO3 |  |
| PERCCOMISSAO4 | Float |  | PERCCOMISSAO4 |  |
| PERCCOMISSAO5 | Float |  | PERCCOMISSAO5 |  |
| PERCDESCONTO | Float |  | Percentual de Desconto |  |
| PERCMARGEMPROP | Float |  | PERCMARGEMPROP |  |
| PERCIMPOSTOSVEN | Float |  | Imposto s/Venda R$ |  |
| PERCINTERNACAO | Float |  | Percentual de Internação |  |
| VLRDESCONTO | Float |  | Desconto U$ |  |
| VLRMARGEMPROP | Float |  | VLRMARGEMPROP |  |
| VLRINTERNACAO | Float |  | Internação U$ |  |
| VLRIMPOSTOSVEN | Float |  | Valor Imposto s/Venda R$ |  |
| VLRTREINAMENTO | Float |  | Treinamento U$ |  |
| VLRINSTALACAO | Float |  | Instalação U$ |  |
| VLRVIAGEMNAC | Float |  | Valor 1 U$ |  |
| VLRVIAGEMINT | Float |  | Valor 2 U$ |  |
| VLRCUSEQUIPFOB | Float |  | Custo Equip. FOB U$ |  |
| VLRGARHARDFOB | Float |  | Garantia Hard. FOB U$ |  |
| VLRGARSOFTFOB | Float |  | Garantia Software FOB U$ |  |
| VLRCUSEQUIPCIF | Float |  | Custo Equip. CIF U$ |  |
| VLRGARHARDCIF | Float |  | Garantia Hard. CIF U$ |  |
| VLRGARSOFTCIF | Float |  | Garantia Software CIF U$ |  |
| VLRCUSEQUIPMARGEM | Float |  | Custo Equip. c/Margem U$ |  |
| VLRGARHARDMARGEM | Float |  | Garantia Hard. c/Margem U$ |  |
| VLRGARSOFTMARGEM | Float |  | Garantia Soft. c/Margem U$ |  |
| VLRGARANTIATECNICO | Float |  | Valor 3 U$ |  |
| VLRTOTAL | Float |  | Total Geral U$ |  |
| VLRTOTALREAL | Float |  | Total Geral R$ |  |
| VLRLUCROLIQUIDOREAL | Float |  | Saldo R$ |  |
| PERCLUCROLIQUIDO | Float |  | Percentual Saldo R$ |  |
| VLRTOTALFOB | Float |  | Total FOB U$ |  |
| VLRTOTALCIF | Float |  | Total CIF U$ |  |
| VLROUTROSCUSCIF | Float |  | Outros Custos CIF U$ |  |
| VLROUTROSCUSMARGEM | Float |  | Outros Custos c/Margem U$ |  |
| VLRTOTALCUS | Float |  | Total Custo R$ |  |
| VLRTOTALCOMSPARE | Float |  | Total c/Rateio R$ |  |
| VLRTOTALARREDONDADO | Float |  | Total Arredondado R$ |  |
| VLRTOTALCOMISSAO | Float |  | Comissões |  |
| OBS | C |  | OBS |  |
| DUPNOVAVERSAO | String |  | Duplicado Nova Versão | `S`=Sim `N`=Não |
| PERCMARGEMPROD | Float |  | Percentual Margem Produto |  |
| PERCINTERNACAOPROD | Float |  | Percentual Internação Produto |  |
| PERCIMPOSTOPROD | Float |  | Imposto s/Venda do Produto |  |
| PERCMARGEMSERV | Float |  | Percentual Margem Serviço |  |
| PERCINTERNACAOSERV | Float |  | Percentual Internação Serviço |  |
| PERCIMPOSTOSERV | Float |  | Imposto s/Venda do Serviço |  |
| CODUSU | Integer |  | Usuário |  |
| PERCFRETE | Float |  | Percentual de Frete |  |
| PERCDESCPROD | Float |  | Percentual de Desconto do Produto |  |
| PERCDESCSERV | Float |  | Percentual de Desconto do Serviço |  |
| NUPROJETO | Integer |  | Projeto |  |

## TGICIP — TGICIP
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAOPROJETO | String |  | VERSAOPROJETO |  |
| NROIMPRESSAO | Integer |  | Número Proposta |  |
| IMPRESSO | String |  | Proposta Gerada | `N`=Não `S`=Sim |
| LOGOPARC | String |  | Arquivo Logo Cliente |  |
| CODPARC | Integer |  | CODPARC |  |
| NOMEPARC | String |  | Nome Cliente |  |
| CODCONTATO | Integer |  | Contato |  |
| NOMECONTATO | String |  | Nome Contato |  |
| CARGOCONTATO | String |  | Cargo Contato |  |
| DEPTOCONTATO | String |  | Departamento Contato |  |
| TELEFONECONTATO | String |  | Telefone Contato |  |
| EMAILCONTATO | String |  | Email Contato |  |
| RESUMOOBJETO | String |  | Resumo Objeto |  |
| TEXTOOBJETO | C |  | Texto Objeto |  |
| PRAZOENTREGA | Integer |  | Prazo Entrega |  |
| PRAZOINSTALACAO | Integer |  | Prazo Instalação |  |
| PRAZOGARANTIA | Integer |  | Prazo Garantia |  |
| MODALIDADEREPOSICAO | String |  | Modalidade Reposição |  |
| MODALIDADESUPORTE | String |  | Modalidade Suporte |  |
| PRAZOSUPORTE | Integer |  | Prazo Suporte |  |
| TEXTOTREINAMENTO | C |  | Texto Treinamento |  |
| PRAZOPAGAMENTO | Integer |  | Prazo Pagamento |  |
| TEXTOOBS | C |  | Texto Obs |  |
| CODVEND | Integer |  | CODVEND |  |
| NOMEVENDEDOR | String |  | Nome Vendedor |  |
| CARGOVENDEDOR | String |  | Cargo Vendedor |  |
| TELEFONEVENDEDOR | String |  | Telefone Vendedor |  |
| EMAILVENDEDOR | String |  | Email Vendedor |  |
| CAMINHOARQIMP | String |  | Arquivo Modelo de Impressão |  |
| CELULARVENDEDOR | String |  | Celular Vendedor |  |
| NUPROJETO | Integer |  | NUPROJETO |  |

## TGIFIN — TGIFIN
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAOPROJETO | String |  | VERSAOPROJETO |  |
| TIPFIN | String |  | TIPFIN |  |
| CODNAT | Integer |  | Natureza |  |
| VLRDESP | Float |  | Valor |  |
| NUPROJETO | Integer |  | NUPROJETO |  |
| RATEADO | String |  | RATEADO | `N`=Não `S`=Sim |

## TGIITE — TGIITE
Campos: 60

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PARTNUMBER | String |  | Part Number |  |
| CODPROD | Integer |  | Produto |  |
| CODNBM | String |  | Código NBM |  |
| QTD | Float |  | Qtde |  |
| QTDSPARE | Float |  | Qtde Spare |  |
| VLRUNITFOB | Float |  | Preço FOB |  |
| PERCDESC | Float |  | % Desc |  |
| VLRUNITFOBDESC | Float |  | Unit FOB c/Desc. |  |
| VLRTOTFOB | Float |  | Total FOB c/Desc. |  |
| PERCFRETE | Float |  | % Frete |  |
| ALIQIPI | Float |  | Alíq.IPI |  |
| ALIQII | Float |  | Alíq.II |  |
| PERCINTERNACAO | Float |  | % Internação |  |
| PERCCSSL | Float |  | % CSSL |  |
| PERCPIS | Float |  | % PIS |  |
| PERCCOFINS | Float |  | % Cofins |  |
| ALIQICMS | Float |  | Alíq.ICMS |  |
| PERCIMPOSTOSCOM | Float |  | % Impostos s/Compra |  |
| VLRUNITCIF | Float |  | Unit CIF |  |
| VLRTOTCIF | Float |  | Total CIF |  |
| PERCMARGEMPROP | Float |  | % Margem Lucro |  |
| FATORVERNET | Float |  | Fator Margem |  |
| PERCIMPOSTOSVEN | Float |  | % Impostos s/Venda |  |
| FATORIMPOSTOS | Float |  | Fator Impostos s/Venda |  |
| VLRUNITCOMMARGEM | Float |  | Unit Final U$ |  |
| VLRTOTCOMMARGEM | Float |  | Total Final U$ |  |
| VLRUNITFINAL | Float |  | Unit Final R$ |  |
| VLRTOTFINAL | Float |  | Total Final R$ |  |
| VLRUNITCOMSPARE | Float |  | Unit c/Rateio R$ |  |
| VLRTOTCOMSPARE | Float |  | Total c/Rateio R$ |  |
| VLRUNITFINALARRED | Float |  | Unit Arred. R$ |  |
| VLRTOTFINALARRED | Float |  | Total Arred. R$ |  |
| CODPARCFORN | Integer |  | Fornecedor |  |
| NUNOTA | Integer |  | Nro Único Pedido |  |
| SEQUENCIA | Integer |  | Seq.Pedido |  |
| NUPROJETO | Integer |  | Projeto |  |
| VERSAOPROJETO | String |  | Versão |  |
| TIPKIT | String |  | Tipo Kit |  |
| SEQKIT | Integer |  | Sequencia Kit |  |
| SEQITEM | Integer |  | Sequencia |  |
| DESCRITEM | String |  | Descrição do item |  |
| VLRDESCONTO | Float |  | Unit. Desc |  |
| VLRTOTDESC | Float |  | Total Desconto |  |
| VLRUNITIPI | Float |  | Unit. IPI |  |
| VLRUNITII | Float |  | Unit.II |  |
| VLRUNITCSSL | Float |  | Unit. CSSL |  |
| VLRUNITPIS | Float |  | Unit. PIS |  |
| VLRUNITCOFINS | Float |  | Unit. Cofins |  |
| VLRUNITFRETE | Float |  | Unit.Frete |  |
| VLRUNITICMS | Float |  | Unit. ICMS |  |
| VLRINTERNACAO | Float |  | Unit Internação |  |
| VLRTOTINTERNACAO | Float |  | Total Internação |  |
| VLRIMPOSTOSVEN | Float |  | Unit Impostos S/Venda |  |
| VLRTOTIMPOSTOSVEN | Float |  | Total Impostos s/Venda |  |
| VLRIMPOSTOSCOM | Float |  | Unit Impostos S/Compra |  |
| VLRTOTIMPOSTOSCOM | Float |  | Total Impostos s/Compra |  |
| VLRMARGEM | Float |  | Unit Margem |  |
| VLRTOTMARGEM | Float |  | Total Margem Vernet |  |
| RATEADO | String |  | RATEADO | `N`=Não `S`=Sim |
| SERVICO | String |  | Serviço | `N`=Não `S`=Sim |

## TGIKIT — TGIKIT
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAOPROJETO | String |  | Versão |  |
| TIPKIT | String |  | Tipo Kit |  |
| SEQKIT | Integer |  | Sequencia Kit |  |
| DESCRKIT | String |  | Descrição |  |
| CODPARCFORN | Integer |  | Fornecedor Padrão |  |
| NUPROJETO | Integer |  | Projeto |  |

## TGIRAT — TGIRAT
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAOPROJETO | String |  | VERSAOPROJETO |  |
| TIPO | String |  | TIPO |  |
| CHAVE | Integer |  | CHAVE |  |
| SEQKIT | Integer |  | SEQKIT |  |
| SEQITEM | Integer |  | SEQITEM |  |
| RATEADO | String |  | RATEADO |  |
| PERCRATEIO | Float |  | PERCRATEIO |  |
| VLRRATEIO | Float |  | VLRRATEIO |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODUSU | Float |  | CODUSU |  |
| NUPROJETO | Integer |  | NUPROJETO |  |

## TGMAI — Autorização de Investimento
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMETA | Integer |  | Orçamento |  |
| CODEMP | Integer |  | Empresa |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| BLOQUEADO | String |  | Bloqueada |  |
| DTAUTINV | DateTime |  | Dt.Autorização |  |
| VLRAUTINV | Float |  | Vlr.Autorização |  |
| VLRSUPLEMENTO | Float |  | Vlr.Suplementação |  |
| VLRTRANSFSALDO | Float |  | Transferência Saldo |  |
| VLRTRANSFERENCIA | Float |  | Vlr.Transferência |  |
| VLRUSADO | Float |  | Vlr.Usado |  |
| VLRCANCELADO | Float |  | Vlr.Cancelado |  |
| VLRCOMPROMISSO | Float |  | Vlr Compromisso |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt.Alteração |  |
| OBSERVACAO | String |  | Observações |  |
| NUAUTINV | Integer |  | Nro Autorização |  |

## TGMAIB — Bloqueio de Autorização de Investimento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINI | Date |  | Data Inícial |  |
| DTFIM | Date |  | Data Final |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data Alteração |  |
| NUAUTINV | Integer |  | Nro Autorização |  |

## TGMAPO — Alteração Planejamento Orçamentária
Campos: 39

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHINTUNICO | Date |  | Ano |  |
| PREVISTO1 | Float |  | Previsto 1 |  |
| PREVISTO2 | Float |  | Previsto 2 |  |
| PREVISTO3 | Float |  | Previsto 3 |  |
| PREVISTO4 | Float |  | Previsto 4 |  |
| PREVISTO5 | Float |  | Previsto 5 |  |
| PREVISTO6 | Float |  | Previsto 6 |  |
| PREVISTO7 | Float |  | Previsto 7 |  |
| PREVISTO8 | Float |  | Previsto 8 |  |
| PREVISTO9 | Float |  | Previsto 9 |  |
| PREVISTO10 | Float |  | Previsto 10 |  |
| PREVISTO11 | Float |  | Previsto 11 |  |
| PREVISTO12 | Float |  | Previsto 12 |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| EXECUTANTE | Integer |  | EXECUTANTE |  |
| VENDEDOR | Integer |  | VENDEDOR |  |
| VENDITEM | Integer |  | VENDITEM |  |
| CODPAIS | Integer |  | Cód. País |  |
| CODGER | Integer |  | Gerente de Vendedor |  |
| CODGRUPOPROD | Integer |  | Grupo Produto |  |
| CODPROD | Integer |  | Produto |  |
| CODTIPPARC | Integer |  | Perfil |  |
| CODEMP | Integer |  | Empresa |  |
| CODPROJ | Integer |  | Projeto |  |
| CONTROLE | String |  | Controle |  |
| CODREG | Integer |  | Cód. Região |  |
| MARCA | String |  | Marca |  |
| CODLOCAL | Integer |  | Local |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODVEND | Integer |  | Vendedor |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODSOLICITANTE | Integer |  | Código solicitante |  |
| ANO | Integer |  | Ano |  |
| NUSOLICITACAO | Integer |  | Número solicitação |  |
| CODGRUPONAT | Integer |  | Cód. Grupo Nat. |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CODMETA | Integer |  | Código |  |
| CODUF | Integer |  | Cód. UF |  |
| RECDESP | String |  | Receita/Despesa | `R`=Receita `D`=Despesa |

## TGMCFG — Configurações de Metas
Campos: 50

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPMETA | String |  | Tipo de Meta | `C`=Comercial `F`=Financeira |
| DESCRMETA | String |  | Descrição da Meta |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| DATA | Integer |  | Período |  |
| PERIODO | Integer |  | Periodicidade | `6`=Trimestral `5`=Bimestral `4`=Mensal `8`=Semestral `7`=Quadrimestral_(+4)_ |
| EMPRESA | Integer |  | Empresa |  |
| PROJETO | Integer |  | Projeto |  |
| NATUREZA | Integer |  | Natureza |  |
| CENTRORESULTADO | Integer |  | Centro de resultado |  |
| CONTROLE | Integer |  | Controle |  |
| LOCAL | Integer |  | Local |  |
| REGIAO | Integer |  | Região |  |
| GRUPO | Integer |  | Grupo de Produtos |  |
| PRODUTO | Integer |  | Produto |  |
| VENDEDOR | Integer |  | Vendedor/Comprador |  |
| TIPOMSG | String |  | Quando exceder a Despesa Prevista | `A`=Avisar e Aceitar o lançamento `S`=Exigir Liberação SEMPRE, mesmo que não exceda o orçamento `I`=Não avisar e Aceitar `L`=Avisar e Não aceitar o lançamento |
| CODPARC | Integer |  | Parceiro |  |
| MARCA | Integer |  | Marca |  |
| TIPQTD | String |  | Produtos por | `P`=Peso Bruto `Q`=Quantidade |
| TIPVLR | String |  | Tipo do Valor | `V`=Valor da Venda/Compra `L`=Lucratividade `M`=Margem de Contribuição |
| TIPODATA | String |  | Tipo de Data | `L`=Movimento `V`=Vencimento `B`=Baixa `N`=Negociação `E`=Entrada/Saída |
| CODGER | Integer |  | Gerente |  |
| UF | Integer |  | Estado (UF) |  |
| CIDADE | Integer |  | Cidade |  |
| PAIS | Integer |  | País |  |
| PERFIL | Integer |  | Perfil principal |  |
| VERSAO | Integer |  | Versão |  |
| IGNORCNAOPREV | String |  | Ignora orçamento não previsto | `S`=Sim `N`=Não |
| DTAPROV | DateTime |  | Data da Aprovação |  |
| APRESCOD | String |  | Ver código com a descrição no Planejamento | `S`=Sim `N`=Não |
| VALPREVIGOR | String |  | Valida alteração do período em vigor | `S`=Sim `N`=Não |
| CODUSUAPROV | Integer |  | Cód. Usuário Aprovação |  |
| PERCAVISO | Float |  | % p/avisar antes de exceder a Despesa |  |
| CODMETAANT | Integer |  | Cód. Meta anterior |  |
| VENDITEM | Integer |  | Vendedor Item |  |
| EXECUTANTE | Integer |  | Executante |  |
| INVESTIMENTO | String |  | Investimento | `N`=Não `S`=Sim |
| SOMARISSRET | String |  | Somar ISSRET |  |
| SOMARINSS | String |  | Somar INSS |  |
| SOMARIRRF | String |  | Somar IRRF |  |
| SOMARIMP | String |  | Somar IMP |  |
| VALORBRUTO | String |  | Usar valor Bruto | `N`=Não `S`=Sim |
| SIMPLIFICADA | String |  | Simplificada |  |
| INCCOMP | String |  | Considerar Componentes | `S`=Sim `N`=Não |
| GRUPONAT | Integer |  | Grupo Natureza |  |
| ARQIMPORTPO | String |  | Arq. de Importação de Planej. Orçamentário |  |
| METAPORQTD | String |  | Meta por quantidade | `S`=Sim `N`=Não |
| DTINICORC | Integer |  | Data Início | `9`=Outubro `8`=Setembro `7`=Agosto `5`=Junho `4`=Maio_(+7)_ |
| CODMETA | Integer |  | Código |  |
| CAMPOSUBSTITUTO | String |  | Campos Substitutos |  |

## TGMCFGF — Log alteração Limitações Intervalo Único
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFIM | Date |  | Data fim. |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | Date |  | Data Alteração |  |
| CODMETA | Integer |  | CODMETA |  |

## TGMCFGI — Limitações de Intervalo Único
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODPARC | Integer |  | Parceiro |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| CODPROJ | Integer |  | Projeto |  |
| DTINIC | Date |  | Data inicial |  |
| DTFIM | Date |  | Data Final |  |
| CODUSU | Integer |  | Usuário |  |
| DTALTER | DateTime |  | Data alteração |  |
| CODCENCUSFIM | Integer |  | Centro Resultado Fim |  |
| CODMETA | Integer |  | CODMETA |  |

## TGMDFM — Detalhe previsão Meta
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Período |  |
| CODUSU | Integer |  | Usuário Solicitante |  |
| PREVISTO | Float |  | Prevista |  |
| CODMETA | Integer |  | Cód. Meta |  |
| CODCENARIO | Integer |  | Codigo cenário |  |
| RECDESP | String |  | Receita/Despesa |  |
| VALUEDETAIL | String |  | Valor detalhe |  |

## TGMFCT — Previsão Meta
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OBSERVACAO | String |  | Observação |  |
| CODMETA | Integer |  | Cód. Meta |  |
| CODCENARIO | Integer |  | Codigo cenário |  |
| CODUSU | Integer |  | Usuário Solicitante |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODREG | Integer |  | Cód. Região |  |
| CODPROD | Integer |  | Produto |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODUF | Integer |  | Cód. UF |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODPAIS | Integer |  | Cód. País |  |
| CODTIPPARC | Integer |  | Perfil |  |
| CODGER | Integer |  | Gerente de Vendedor |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CODGRUPOPROD | Integer |  | Grupo Produto |  |
| CODEMP | Integer |  | Empresa |  |
| CONTROLE | String |  | Controle |  |
| MARCA | String |  | Marca |  |
| CODLOCAL | Integer |  | Local |  |
| EXECUTANTE | Integer |  | Executante |  |
| VENDITEM | Integer |  | Executante |  |
| VENDEDOR | Integer |  | Executante |  |
| CODVEND | Integer |  | CODVEND |  |
| MES | Integer |  | Mês |  |
| ANO | Integer |  | Ano |  |
| CODGRUPONAT | Integer |  | Cód. Grupo Nat. |  |
| NOMECENARIO | String |  | Nome do cenário |  |
| CAMPODETALHE | String |  | Campo detalhe |  |

## TGMMET — Meta
Campos: 41

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Período |  |
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Produto |  |
| CODGRUPOPROD | Integer |  | Grupo Produto |  |
| CODLOCAL | Integer |  | Local |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODREG | Integer |  | Cód. Região |  |
| CODGER | Integer |  | Gerente de Vendedor |  |
| CODVEND | Integer |  | Vendedor |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODUF | Integer |  | Cód. UF |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CODPAIS | Integer |  | Cód. País |  |
| CODTIPPARC | Integer |  | Perfil |  |
| CONTROLE | String |  | Controle |  |
| MARCA | String |  | Marca |  |
| QTDPREV | Float |  | Qtde.Prevista |  |
| PREVREC | Float |  | Receita Prevista |  |
| PREVDESP | Float |  | Despesa Prevista |  |
| QTDREAL | Float |  | Qtde.Real |  |
| REALREC | Float |  | Receita Real |  |
| REALDESP | Float |  | Despesa Real |  |
| PERCENTUAL | Float |  | Percentual |  |
| SUPLEMENTODESP | Float |  | Suplemento |  |
| ANTECIPDESP | Float |  | Antecipação |  |
| TRANSFDESP | Float |  | Transferência |  |
| TRANSFSALDODESP | Float |  | Transf.Saldo |  |
| REDUCAODESP | Float |  | Redução |  |
| COMPROMISSODESP | Float |  | Compromisso |  |
| ANALITICO | String |  | Analítico | `S`=Sim `N`=Não |
| TIPOMSG | String |  | Tipo | `S`=Exigir liberação SEMPRE `Z`=Usar o padrão da Meta/Orçamento `L`=Avisar e não aceitar o lançamento `I`=Não avisar e aceitar `A`=Avisar e aceitar o lançamento |
| PERCAVISO | Float |  | % Aviso |  |
| DIA | Integer |  | Dia |  |
| SEMANAMES | Integer |  | Semana do mês |  |
| TOTALAUTINV | Float |  | Total Autorização de Investimento |  |
| CODVOL | String |  | Unidade |  |
| CODGRUPONAT | Integer |  | Cód. Grupo Nat. |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| CODMETA | Integer |  | Cód. Meta |  |

## TGMMSG — GM Mensagens
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODVEND | Integer |  | Cód.Vendedor |  |
| CODPROD | Integer |  | Cód.Produto |  |
| CODGRUPOPROD | Integer |  | Cód.Grupo de Produtos |  |
| CODLOCAL | Integer |  | Cód.Local |  |
| CODPROJ | Integer |  | Cód.Projeto |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODREG | Integer |  | Cód.Região |  |
| CODMETA | Integer |  | Cód.Meta |  |
| CONTROLE | String |  | Controle |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| MARCA | String |  | Marca |  |
| CODGER | Integer |  | Cód. do Gerente |  |
| TIPOMSG | String |  | Tipo de Mensagem |  |
| PODESUPLEMENTAR | String |  | Pode Suplementar? | `S`=Permitido `N`=Proibido |
| PODEANTECIPAR | String |  | Pode Antecipar? | `S`=Permitido `N`=Proibido |
| PODETRANSFSALDO | String |  | Pode Transferir Saldo? | `S`=Permitido `N`=Proibido |
| MSG | String |  | Mensagem |  |
| PERCAVISO | Float |  | Percentual de Aviso |  |
| MSGAVISO | String |  | Mensagem de Aviso |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| DTREF | DateTime |  | Data de Referência |  |

## TGMSLO — Solicitação Liberação Orçamentária
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSOLICITANTE | Integer |  | Código solicitante |  |
| NUSOLICITACAO | Integer |  | Número solicitação |  |
| DHSOLICITACAO | DateTime |  | Data da solicitação |  |
| STATUS | String |  | Status | `R`=Reprovado `P`=Pendente `A`=Aprovado |
| CODAPROVADOR | Integer |  | Código aprovador |  |
| DHAPROVACAO | DateTime |  | Data da aprovação |  |
| OBSERVACAO | String |  | Observação solicitante |  |
| CODMETA | Integer |  | Código |  |

## TGMSUB — Campos Substitutos
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCAMPO | String |  | Campos Disponíveis |  |
| CAMPOSUBSTITUTO | String |  | Campos Substitutos |  |
| GRAU | Integer |  | Grau |  |
| CODMETA | Integer |  | Cód.Meta |  |

## TGMTME — Tipos de Metas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMETA | Integer |  | Meta |  |
| RECDESP | Integer |  | Receita/Despesa | `-1`=Despesa `1`=Receita `0`=Usar da TOP |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| COMPROMISSO | String |  | Compromisso | `S`=Sim `N`=Não |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |

## TGMTRA — Transferências
Campos: 47

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODVEND | Integer |  | Vendedor |  |
| NUFIN | Integer |  | Nro Único Financeiro |  |
| NUNOTA | Integer |  | Nro Único Nota |  |
| CODPROD | Integer |  | Produto |  |
| SEQUENCIAITE | Integer |  | Sequência Item |  |
| CODGRUPOPROD | Integer |  | Grupo de Produtos |  |
| CODLOCAL | Integer |  | Local |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| CODNAT | Integer |  | Natureza |  |
| CODREG | Integer |  | Região |  |
| CODMETA | Integer |  | Meta |  |
| CONTROLE | String |  | Controle |  |
| CODPARC | Integer |  | Parceiro |  |
| MARCA | String |  | Marca |  |
| CODGER | Integer |  | Gerente |  |
| NUMTRANSF | Integer |  | Número da Transferência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPO | String |  | Tipo | `S`=Suplementação `I`=Indefinido `T`=Transferência `A`=Antecipação |
| SINAL | Integer |  | Sinal |  |
| CODUF | Integer |  | Unidade Federativa |  |
| VALOR | Float |  | Valor Solicitado |  |
| CODCID | Integer |  | Cidade |  |
| CODPAIS | Integer |  | País |  |
| CODUSU | Integer |  | Usuário Solicitante |  |
| DTALTER | DateTime |  | Data da Alteração |  |
| CODTIPPARC | Integer |  | Tipo de Parceiro |  |
| VALOR_ORIG | Float |  | Valor Origem |  |
| CODUSULIB | Integer |  | Usuário Liberação |  |
| STATUS | String |  | Status | `A`=Aprovada `P`=Pendente `R`=Reprovada |
| GRAU | Integer |  | Grau |  |
| DIA | Integer |  | Dia |  |
| OBSERVACAO | String |  | Observação Solicitante |  |
| OBSLIB | String |  | Observação Liberador #4 |  |
| OBSLIB1 | String |  | Observação Liberador #1 |  |
| OBSLIB2 | String |  | Observação Liberador #2 |  |
| OBSLIB3 | String |  | Observação Liberador #3 |  |
| VLRDESDOB | Float |  | Vlr do Desdobramento |  |
| CODTIPOPER | Integer |  | Tipo Operação |  |
| CODCTACTB | Integer |  | Conta Bancária |  |
| NUAUTINV | Integer |  | Nro Autorização |  |
| CODGRUPONAT | Integer |  | Grupo da Natureza |  |
| CODCENCUSLIB | Integer |  | CR Liberador |  |
| NUTVO | Integer |  | Transferência de Verba |  |
| DTREF | Date |  | Período |  |
| EXCLUIDO | Integer |  | Excluido |  |

## TGMTVO — Transferência de Verba
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHTRANSF | DateTime |  | Dh. transferência |  |
| VLRTRANSF | Float |  | Vlr. transferência |  |
| CODMETA | Integer |  | Meta/Orçamento |  |
| NUTVO | Integer |  | Nro. único |  |

## TGMUSLB — Liberação Planejamento
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMETA | Integer |  | Código |  |
| CODUSU | Integer |  | Código |  |

## TGPESC — TABLE TGPESC
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRESCALA | String |  | DESCRESCALA |  |
| CONCEITO | String |  | CONCEITO |  |
| TIPOESCALA | Integer |  | TIPOESCALA |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| TIPOPONTUACAO | Integer |  | TIPOPONTUACAO |  |
| GRAUALTOIMPACTO | Integer |  | GRAUALTOIMPACTO |  |
| CODESCALA | Integer |  | CODESCALA |  |

## TGPFCP — TABLE TGPFCP
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCOMPETENCIA | Integer |  | Cód. Competência |  |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Fim |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | Date |  | DHALTER |  |
| CODFUNCAO | Integer |  | CODFUNCAO |  |

## TGPFCT — TABLE TGPFCT
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAREFA | Integer |  | Cód. Tarefa |  |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Final |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODFUNCAO | Integer |  | Cód. Função |  |

## TGPGRE — TABLE TGPGRE
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRAU | Integer |  | CODGRAU |  |
| DESCRGRAU | String |  | DESCRGRAU |  |
| PONTUACAO | Integer |  | PONTUACAO |  |
| CONTEUDO | String |  | CONTEUDO |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| LIMITEINI | Integer |  | LIMITEINI |  |
| LIMITEFIM | Integer |  | LIMITEFIM |  |
| CODESCALA | Integer |  | CODESCALA |  |

## TGPGSL — TABLE TGPGSL
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRELHA | String |  | DESCRGRELHA |  |
| QTDCLASSES | Integer |  | QTDCLASSES |  |
| QTDSTEPS | Integer |  | QTDSTEPS |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODGRELHA | Integer |  | CODGRELHA |  |

## TGPNIV — TABLE TGPNIV
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRNIVEL | String |  | DESCRNIVEL |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODNIVEL | Integer |  | CODNIVEL |  |

## TGPNVC — Níveis por Cargo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNIVEL | Integer |  | Nível |  |
| POSSUIREP | String |  | Possui Representatividade | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data de Alteração |  |
| CODCARGO | Integer |  | Cód. Cargo |  |

## TGPPRC — TABLE TGPPRC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRPROCEDIMENTO | String |  | Descrição |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODPROCEDIMENTO | Integer |  | Cód. Procedimentos |  |

## TGPREL — TABLE TGPREL
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCARGO | Integer |  | CODCARGO |  |
| TIPO | String |  | Tipo | `P`=Parceiro `F`=Funcionário |
| CODPARC | Integer |  | Parceiro |  |
| CODEMPFUNC | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| TIPORELACAO | Integer |  | Tipo Relação | `3`=Outros `2`=Subordinados `0`=Superiores `1`=Pares |

## TGPTAR — TABLE TGPTAR
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTAREFA | String |  | Descrição |  |
| CODESCALA | Integer |  | Cód. Escala |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODTAREFA | Integer |  | Cód. Tarefa |  |

## TGPTPR — TABLE TGPTPR
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROCEDIMENTO | Integer |  | Cód. Procedimento |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Final |  |
| CODTAREFA | Integer |  | CODTAREFA |  |

## TGVGEP — TABLE TGVGEP
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUEVOPRECO | String |  | DESCRGRUEVOPRECO |  |
| CGC | String |  | CNPJ para o grupo |  |
| CODGRUEVOPRECO | Integer |  | CODGRUEVOPRECO |  |

## TGVIDC — TABLE TGVIDC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CGC | String |  | CNPJ do grupo |  |
| NIVEL0 | String |  | NIVEL0 |  |
| NIVEL1 | String |  | NIVEL1 |  |
| CODIDC | Integer |  | CODIDC |  |

## TGVIGEP — TABLE TGVIGEP
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODPROD | Integer |  | CODPROD |  |
| CODGRUEVOPRECO | Integer |  | CODGRUEVOPRECO |  |

## THGITE — Hidrogeologia Itens do Relatório de produção
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMOTIVOPARADA | Integer |  | CODMOTIVOPARADA |  |
| CODPRD | Integer |  | CODPRD |  |
| COORDX | Float |  | COORDX |  |
| COORDY | Float |  | COORDY |  |
| DTCOLETAAMOSTRA | DateTime |  | DTCOLETAAMOSTRA |  |
| DTDESENVOLVIMENTO | DateTime |  | DTDESENVOLVIMENTO |  |
| DTENVIOAMOSTRA | DateTime |  | DTENVIOAMOSTRA |  |
| DTMEDICAOFQ | DateTime |  | DTMEDICAOFQ |  |
| PM | String |  | PM |  |
| SLUG_CODMOTIVOPARADA | Integer |  | SLUG_CODMOTIVOPARADA |  |
| SLUG_DATA | DateTime |  | SLUG_DATA |  |
| ZCOTA | Float |  | ZCOTA |  |

## THGMTV — Hidrogeologia Motivo de Parada
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMOTIVO | Integer |  | CODMOTIVO |  |
| DESCRICAO | String |  | DESCRICAO |  |

## THGPRD — Hidrogeologia Relatório de Produção
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRD | Integer |  | CODPRD |  |
| CODPROJ | Integer |  | CODPROJ |  |
| CODUSUCOORCAMPO | Integer |  | CODUSUCOORCAMPO |  |
| CODUSUCOORPROJETO | Integer |  | CODUSUCOORPROJETO |  |
| DATAINICIO | DateTime |  | DATAINICIO |  |
| OBSERVACAO | String |  | OBSERVACAO |  |

## TJCEDI — JC Edições
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCADERNO | Integer |  | Caderno |  |
| PAGINA | Integer |  | Pagina |  |
| CODCAD | Integer |  | Sessão |  |
| AREATOTAL | Integer |  | Área total |  |
| AREAUTILIZADA | Integer |  | Área utilizada |  |
| SITUACAO | String |  | Situação |  |
| DTEDICAO | DateTime |  | Data da edição |  |

## TLFALIQCBS — Tabela de Tributação do CBS
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa do Cadastro |  |
| CODREGTRIB | Integer |  | Regime Tributário da Empresa | `0`=Sem Regime Tributário `1`=Simples Nacional `2`=Simples Nacional – Sublimite `3`=Regime Normal |
| CODCNAE | String |  | CNAE da Empresa |  |
| CODCST | String |  | Código da Situação Tributária |  |
| CODCSTREGULAR | String |  | Código de Situação Tributária do CBS Regular |  |
| CODCCLASTRIB | String |  | Código de Classificação Tributária |  |
| CODCLASTRBREG | String |  | Código de Classificação Tributária do CBS Regular |  |
| CODNCM | String |  | NCM do Produto |  |
| CODNBS | String |  | NBS do Serviço |  |
| NUFOP | Integer |  | Finalidade da Operação |  |
| CODTIPOPER | Integer |  | Tipo de Operação |  |
| DHALTER | DateTime |  | Dt./Hr. Operação |  |
| CODUF | Integer |  | UF Destino |  |
| CODCID | Integer |  | Município de Destino |  |
| PREFCBS | Float |  | Alíquota Referência |  |
| PALIQREG | Float |  | Alíquota Regular do CBS |  |
| PFEDERALCBS | Float |  | % Federal |  |
| PCBS | Float |  | Alíquota CBS |  |
| PREDALIQCBS | Float |  | % da Redução de Alíquota CBS |  |
| PALIQEFETCBS | Float |  | Alíquota Efetiva CBS |  |
| PDIFCBS | Float |  | % do Diferimento CBS |  |
| CCREDPRESCBS | String |  | Código de Class. do Crédito Presumido |  |
| PCREDPRESCBS | Float |  | % de Crédito Presumido |  |
| PREDUTORCBS | Float |  | % Redução Alíquota (Gov.) |  |
| OBSERVADFISCOIB | String |  | Observações |  |
| DTINIVIG | Date |  | Vigência Início |  |
| DTFIMVIG | Date |  | Vigência Fim |  |
| CHAVEUNICA | String |  | Chave Única |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| GRUPOIBSCBS | Integer |  | Grupo CBS |  |
| CODPROD | Integer |  | Código do Produto |  |
| IDCBS | Integer |  | Cód. Alíq. CBS |  |

## TLFALIQIBS — Tabela de Tributação do IBS
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa do cadastro |  |
| CODREGTRIB | Integer |  | Regime tributário da empresa | `0`=Sem Regime Tributário `1`=Simples Nacional `2`=Simples Nacional - Sublimite `3`=Regime Normal |
| CODCNAE | String |  | CNAE da empresa |  |
| CODCST | String |  | Código da situação tributária |  |
| CODCSTREGULAR | String |  | Código de Situação Tributária do IBS Regular |  |
| CODCCLASTRIB | String |  | Código de Classificação Tributária |  |
| CODCLASTRBREG | String |  | Código de Classificação Tributária do IBS Regular |  |
| CODNCM | String |  | NCM do Produto |  |
| CODNBS | String |  | NBS do serviço |  |
| NUFOP | Integer |  | Finalidade da operação |  |
| CODTIPOPER | Integer |  | Tipo de operação |  |
| DHALTER | DateTime |  | Dt./Hr. Operação |  |
| CODUF | Integer |  | UF destino |  |
| CODCID | Integer |  | Município destino |  |
| PALIQREF | Float |  | Alíquota Referência |  |
| PALIQREGMUN | Float |  | Alíquota Regular do IBS do Município |  |
| PALIQREGUF | Float |  | Alíquota Regular do IBS da UF |  |
| PALIQEST | Float |  | % Estado |  |
| PALIQMUN | Float |  | % Município |  |
| PIBSUF | Float |  | Alíquota IBS Estado |  |
| PIBSMUN | Float |  | Alíquota IBS Município |  |
| PALIQEFTUFIBS | Float |  | Alíquota Efetiva IBS Estado |  |
| PALIQEFTMUIBS | Float |  | Alíquota Efetiva IBS Municipio |  |
| PREDALIQIBSUF | Float |  | % da Redução de Alíquota IBS Estadual |  |
| PREDALIQIBSMUN | Float |  | % da Redução de Alíquota IBS Municipal |  |
| PDIFIBSUF | Float |  | % de Diferimento IBS Estadual |  |
| PDIFIBSMUN | Float |  | % de Diferimento IBS Municipal |  |
| PREDUTORIBS | Float |  | % Redução Alíquota (Gov.) |  |
| CREDPRESIBS | String |  | Código de class. do crédito presumido |  |
| PCREDPRESIBS | Float |  | % de Crédito Presumido |  |
| DTINIVIG | Date |  | Vigência início |  |
| DTFIMVIG | Date |  | Vigência fim |  |
| OBSERVADFISCOIB | String |  | Observações |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CHAVEUNICA | String |  | Chave Única |  |
| GRUPOIBSCBS | Integer |  | Grupo IBS |  |
| CODPROD | Integer |  | Código do Produto |  |
| IDIBS | Integer |  | Cód. Alíq. IBS |  |

## TLFALIQIS — Tabela de Tributação do IS
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa do Cadastro |  |
| CODREGTRIB | Integer |  | Regime Tributário da Empresa | `0`=Sem Regime Tributário `1`=Simples Nacional `2`=Simples Nacional – Sublimite `3`=Regime Normal |
| CODCNAE | String |  | CNAE da Empresa |  |
| CODCST | String |  | Código da Situação Tributária |  |
| CODCCLASTRIB | String |  | Código de Classificação Tributária |  |
| CODNCM | String |  | NCM do Produto |  |
| CODNBS | String |  | NBS do Serviço |  |
| NUFOP | Integer |  | Finalidade da Operação |  |
| CODTIPOPER | Integer |  | Tipo de Operação |  |
| DHALTER | DateTime |  | Dt./Hr. Operação |  |
| CODUF | Integer |  | UF Destino |  |
| CODCID | Integer |  | Município de Destino |  |
| PIS | Float |  | Alíquota IS |  |
| PISESPEC | Float |  | Alíquota IS por Unidade de Medida Apropriada |  |
| OBSERVADFISCOIB | String |  | Observações |  |
| DTINIVIG | Date |  | Vigência Início |  |
| DTFIMVIG | Date |  | Vigência Fim |  |
| CHAVEUNICA | String |  | Chave Única |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| GRUPOIS | Integer |  | Grupo IS |  |
| CODPROD | Integer |  | Código do Produto |  |
| IDIS | Integer |  | Cód. Alíq. IS |  |

## TLFBEN — Beneficiário
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARCBEN | Integer |  | Parceiro beneficiário do plano de saúde |  |
| VLRSAUDE | Float |  | Valor Saúde |  |
| VLRREEMB | Float |  | Valor Reembolso |  |
| VLRREEMBANOANT | Float |  | Valor Reembolso ano anterior |  |
| CODPARCASS | Integer |  | Parceiro prestador de serviços de assistência médica |  |
| NUFIN | Integer |  | Nro Único |  |

## TLFCCREDPRESIC — Código de Classificação do Crédito Presumido
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCR | String |  | Descrição |  |
| DHINIVIG | Date |  | Data Início Vigência |  |
| INDGAPRNF | String |  | Apropria Via NF? | `N`=Não é permitido `S`=Exige |
| DHFIMVIG | Date |  | Data Fim Vigência |  |
| INDGAPREVE | String |  | Apropria via Evento? | `N`=Não é permitido `S`=Exige |
| DHULTATT | Date |  | Última Atualização |  |
| INDGDED | String |  | Dedução? | `N`=Não é permitido `S`=Exige |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |
| INDGCBS | String |  | Aplica sobre Cbs? | `N`=Não é permitido `S`=Exige |
| INDGIBS | String |  | Aplica sobre IBS? | `N`=Não é permitido `S`=Exige |
| CCREDPRES | String |  | Código de Classificação do Crédito Presumido |  |

## TLFCLASTRIBIC — cClassTrib de IBS/CBS/Monofasia
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCCCLASTRIB | String |  | Descrição |  |
| CSTIC | String |  | CST IS |  |
| PREDIBS | Float |  | % Redução IBS |  |
| PREDCBS | Float |  | % Redução CBS |  |
| INDGTRIBREGULAR | String |  | Tributação Regular? | `N`=Não é permitido `S`=Exige |
| INDCREDPRES | String |  | Crédito Presumido? | `N`=Não é permitido `S`=Exige |
| INDMONO | String |  | Monofásico? | `N`=Não é permitido `S`=Exige |
| INDMONORETEN | String |  | Retenção de monofásico? | `N`=Não é permitido `S`=Exige |
| INDMONORET | String |  | Ret. Monofásico? | `N`=Não é permitido `S`=Exige |
| INDMONODIF | String |  | Diferimento de monofásico? | `N`=Não é permitido `S`=Exige |
| INDGESTORNOCRED | String |  | Exige estorno de crédito? | `N`=Não é permitido `S`=Exige |
| INDNFE | String |  | NF-e? | `N`=Nao `S`=Sim |
| INDNFCE | String |  | NFC-e? | `N`=Nao `S`=Sim |
| INDCTE | String |  | CT-e? | `N`=Nao `S`=Sim |
| INDCTEOS | String |  | CT-e OS? | `N`=Nao `S`=Sim |
| INDNFCOM | String |  | NFCom? | `N`=Nao `S`=Sim |
| INDNFSE | String |  | NFS-e? | `N`=Nao `S`=Sim |
| DHINIVIG | Date |  | Data Início Vigência |  |
| DHFIMVIG | Date |  | Data Fim Vigência |  |
| DHULTATT | Date |  | Última Atualização |  |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |
| CODCCLASTRIB | String |  | Código ClassTrib |  |

## TLFCLASTRIBIS — cClassTrib de IS
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCCCLASTRIB | String |  | Descrição |  |
| DHINIVIG | Date |  | Data Início Vigência |  |
| DHFIMVIG | Date |  | Data Fim Vigência |  |
| DHULTATT | Date |  | Última Atualização |  |
| CSTIS | String |  | CST IS |  |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |
| CODCCLASTRIB | String |  | Código ClassTrib |  |

## TLFCNAE — CNAEs
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCNAE | String |  | Código CNAE |  |
| DESCCNAE | String |  | Descrição do CNAE |  |
| TIPO | String |  | Tipo | `C`=Classes `D`=Divisões `G`=Grupos `S`=Seções |
| CODIGOPAI | String |  | Código Pai |  |
| NIVEL | Integer |  | Nível | `0`=0 `1`=1 `2`=2 `3`=3 `4`=4 |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |

## TLFCSTIC — CST de IBS/CBS/Monofasia
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCCST | String |  | Descrição |  |
| INDGIBSCBS | String |  | IBS/CBS? | `N`=Não é permitido `S`=Exige |
| DHINIVIG | Date |  | Data Início Vigência |  |
| INDGIBSCBSMONO | String |  | IBS/CBS Monofásico? | `N`=Não é permitido `S`=Exige |
| DHFIMVIG | Date |  | Data Fim Vigência |  |
| INDGRED | String |  | Redução? | `N`=Não é permitido `S`=Exige |
| DHULTATT | Date |  | Última Atualização |  |
| INDGDIF | String |  | Diferimento? | `N`=Não é permitido `S`=Exige |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |
| INDGTRANSFCRED | String |  | Transferência de Crédito? | `N`=Não é permitido `S`=Exige |
| INDGCREDPRESIBZZFM | String |  | Exige Crédito Presumido IBS ZFM? | `N`=Nao `S`=Sim |
| INDGAJUSTECOMPET | String |  | Exige Ajuste de Competência? | `N`=Nao `S`=Sim |
| INDGREDUTORBC | String |  | Exige Redução da Base de Cálculo? | `N`=Nao `S`=Sim |
| CODCST | String |  | Código CST de IS |  |

## TLFCSTIS — CST de IS
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCCST | String |  | Descrição |  |
| DHINIVIG | Date |  | Data Início Vigência |  |
| DHFIMVIG | Date |  | Data Fim Vigência |  |
| DHULTATT | Date |  | Última Atualização |  |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |
| CODCST | String |  | Código CST de IS |  |

## TLFDEP — Dependentes
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARCBEN | Integer |  | Parceiro beneficiário do plano de saúde |  |
| CODPARC | Integer |  | Código Parceiro |  |
| CODDEPEND | Integer |  | Código Dependente |  |
| VLRSAUDE | Float |  | Valor Saúde |  |
| VLRREEMB | Float |  | Valor Reembolso |  |
| VLRREEMBANOANT | Float |  | Valor Reembolso ano anterior |  |
| CODPARCASS | Integer |  | Parceiro prestador de serviços de assistência médica |  |
| NUFIN | Integer |  | Nro Único |  |

## TLFDINVR — Impostos Item Venda Rapida
Campos: 98

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQIVR | Integer |  | Seq. Item |  |
| SEQUENCIA | Integer |  | Sequência |  |
| INDGIBSCBS | String |  | IBS/CBS? | `N`=Não é permitido `S`=Exige |
| CODIMP | Integer |  | Imposto | `1`=ICMS `10`=IRPJ `11`=CPP `2`=ST `3`=IPI_(+6)_ |
| CODINC | Integer |  | Incidência | `0`=Geral `1`=Produto `2`=Serviço `3`=Frete `4`=Seguro_(+4)_ |
| BASE | Float |  | Base de Cálculo |  |
| BASERED | Float |  | Base Cálc.Reduzida |  |
| VLRREPRED | Float |  | Vlr.Repasse de Redução |  |
| PAUTA | Float |  | Pauta |  |
| ALIQUOTA | Float |  | Alíquota |  |
| IDALIQ | Integer |  | Código Alíquota |  |
| ALIQDESPACESS | Float |  | Alíquota Despesas Acessórias |  |
| VALOR | Float |  | Valor |  |
| TIPO | Integer |  | Tipo Retenção | `-1`=Retido `0`=Não Aplicado `1`=Não Retido |
| TPIRRFEXT | Integer |  | Tributação IRRF - Exterior REINF | `10`=10 - Retenção do IRRF - Alíquota padrão `11`=11 - Retenção do IRRF - Alíquota da tabela progressiva `12`=12 - Retenção do IRRF - Alíquota diferenciada (países com tributação favorecida) `13`=13 - Retenção do IRRF - Alíquota limitada conforme cláusula em convênio `30`=30 - Retenção do IRRF - Outras hipóteses |
| VLRCRED | Float |  | Vlr.Crédito |  |
| CODNATREND | Integer |  | Código Natureza de Rendimento |  |
| CST | Integer |  | Cst/Csosn |  |
| RETEMFIN | String |  | Retém Financeiro | `N`=Não `S`=Sim |
| PERCVLR | String |  | Percentual / Valor | `P`=Percentual `V`=Valor |
| COMIVA | String |  | Tem IVA | `N`=Não `S`=Sim |
| IVA | Float |  | IVA |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt.Alteração |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| TIPODEDISS | String |  | Tipo Ded. ISS |  |
| CODTRIBMUNISS | String |  | Cod. Trib. Município |  |
| CODLST | Integer |  | Tipo de Serviço |  |
| PERCREDBASE | Float |  | Perc.Red.base |  |
| ALIQUOTANORMAL | Float |  | Alíquota Normal |  |
| ALIQINTDEST | Float |  | Alíq. Interna Destino |  |
| PERCPARTDIFAL | Float |  | Percentual de Partilha DIFAL |  |
| VLRDIFALDEST | Float |  | Valor DIFAL UF Destino |  |
| VLRDIFALREM | Float |  | Valor DIFAL UF Remet. |  |
| PERCFCP | Float |  | Perc. para Fundo Comb. Pobreza |  |
| VLRFCP | Float |  | Vlr. para Fundo Comb. Pobreza |  |
| BASEDIFAL | Float |  | Base Difal |  |
| TIPCALCDIFAL | Integer |  | Tipo de Cálculo do DIFAL | `0`=0 - Sem considerar Redução da Base `1`=1 - Com redução da base aplicada na base `10`=10 - Cálculo da base, valor do DIFAL e do FCP por fórmula `2`=2 - Com redução da base aplicada na alíquota `3`=3 - ICMS Interestadual calculado sob a BC do DIFAL_(+6)_ |
| BASEFCP | Float |  | Base para Fundo Comb. Pobreza |  |
| BASEFCPINT | Float |  | Base FCP Interno |  |
| PERCFCPINT | Float |  | % FCP Interno |  |
| VLRFCPINT | Float |  | Vlr. FCP Interno |  |
| ALIQPARADIFAL | Float |  | Alíquota para cálculo do DIFAL |  |
| VLRICMSPARADIFAL | Float |  | Vlr. Icms Para Difal |  |
| TIPOINSSESPECIAL | String |  | Tipo de INSS Especial | `1`=INSS 15 anos `2`=INSS 20 anos `3`=INSS 25 anos |
| VLRREPDIFALFCP | Float |  | Vlr. Repasse Difal e Fcp |  |
| PERCINSSESPECIAL | Float |  | % INSS Especial |  |
| VLRINSSESPECIAL | Float |  | Vlr. INSS Especial |  |
| ALIQDIFERENCIAL | Float |  | Alíquota de Diferencial |  |
| VALORDIFERENCIAL | Float |  | Valor de Diferencial |  |
| PERCREDBASEEFET | Float |  | Perc. Red. base Efetivo |  |
| BASEREDEFET | Float |  | Base Cálc.Reduzida Efetivo |  |
| ALIQUOTAEFET | Float |  | Alíquota Efetivo |  |
| VALOREFET | Float |  | Valor Efetivo |  |
| PERCREDVLRIPI | Float |  | % Redução de Vlr. IPI |  |
| VLRREPREDSEMDESC | Float |  | Vlr. redução sem desconto |  |
| ALIQUOTADESON | Float |  | Alíquota PIS/COFINS Desonerados |  |
| BASENORMDIFICMS | Float |  | Base Normal Diferimento ICMS |  |
| VALORDESON | Float |  | Valor PIS/COFINS Desonerados |  |
| TIPCALCFCPESPEC | Integer |  | Tipo de Cálculo de FCP Específico | `1`=1 - FECOP ST Majorado (CE) `null`=0 - Não específico (Regra Geral) |
| CODCST | String |  | Código de Situação Tributária |  |
| CODCSTREG | String |  | Código de Situação Tributária Regular |  |
| CCLASSTRIB | String |  | Código de Classificação Tributária |  |
| CCLASSTRIBREG | String |  | Código de Classificação Tributária Regular |  |
| PERCISESPEC | Float |  | Alíquota específica por unidade de medida apropriada |  |
| PERCDIF | Float |  | Percentual do diferimento |  |
| PERCALIQADREMICMS | Float |  | % Redução Alíquota ad rem ICMS |  |
| VLRDIF | Float |  | Valor do Diferimento |  |
| MOTREDADREM | Integer |  | Motivo Redução do ad rem |  |
| VLRDEVTRIB | Float |  | Valor do tributo devolvido |  |
| VLRICMSMONODEV | Float |  | Valor do ICMS Monofásico Devido |  |
| PALIQIBSMUNREG | Float |  | Alíquota efetiva regular do IBS do Município |  |
| PALIQIBSUFREG | Float |  | Alíquota efetiva regular do IBS da UF |  |
| PERCREDALIQ | Float |  | Percentual da redução de alíquota |  |
| PALIQCBSREG | Float |  | Alíquota efetiva regular da CBS |  |
| VLRICMSMONODIF | Float |  | Valor ICMS Monofásico Diferido |  |
| PERCALIQEFET | Float |  | Alíquota Efetiva que será aplicada a Base de Cálculo |  |
| CCREDPRES | String |  | Código de Class. Créd. Presumido |  |
| PCREDPRES | Float |  | % do Crédito Presumido |  |
| SOMARPISCOFINSST | String |  | Indica se o valor do PIS/COFINS ST compõe o valor total da NF-e | `N`=Não `S`=Sim |
| VCREDPRES | Float |  | Valor do Crédito Presumido |  |
| CREDPRESCOND | Float |  | Valor do Crédito Pres. Cond. Susp. |  |
| TOTIBSMONO | Float |  | Total de IBS Monofásico |  |
| VLRMONO | Float |  | Valor do IBS/CBS monofásico |  |
| VLRMONOSR | Float |  | Valor do IBS/CBS monofásico sujeito a retenção |  |
| VLRRETANT | Float |  | Valor do IBS/CBS retido anteriormente |  |
| ALIQADREDRETANT | Float |  | Alíquota ad rem do IBS/CBS retido anteriormente |  |
| ALIQADREM | Float |  | Alíquota ad rem do IBS/CBS |  |
| ALIQADREMSR | Float |  | Alíquota ad rem do IBS/CBS sujeito a retenção |  |
| PERCREDGOVALIQ | Float |  | Percentual da redução de alíquota Governamental |  |
| VLRANTREDGOV | Float |  | Valor do IBS/CBS sem a redução governamental |  |
| VLRCBSREG | Float |  | Valor da CBS Regular |  |
| VLRIBSMUNREG | Float |  | Valor do IBS Regular do Município |  |
| VLRIBSUFREG | Float |  | Valor do IBS Regular da UF |  |
| VLRDEDUZCREDPRES | Float |  | Valor com dedução do Crédito Presumido |  |
| JUSTIFICATIVASCORE | String |  | Justificativa do Score da Aliquota |  |
| NUCVR | Integer |  | Nro. Único |  |
| NUNOTA | Integer |  | Nro.Único Nota |  |

## TLFEFDF0221 — EFD Fiscal Registro 0221
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| COD_ITEM_ATOM | String |  | Código do Item Atômico |  |
| REGISTRO | String |  | Registro |  |
| QTD_ITEM_ATOM | Integer |  | Quantidade Contida no Item Atômico |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CHAVE0200 | String |  | Chave 0200 |  |
| COD_ITEM | String |  | Cód. Item |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD700 — EFD Fiscal Registro D700
Campos: 39

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador do tipo de operação | `0`=Aquisição `1`=Prestação |
| IND_EMIT | String |  | Indicador do emitente do documento fiscal | `0`=Emissão própria `1`=Terceiros |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| DT_E_S | Date |  | Data da entrada ou da saída |  |
| VL_DOC | Float |  | Valor total do documento fiscal |  |
| VL_DESC | Float |  | Valor total do desconto |  |
| VL_SERV | Float |  | Valor da prestação de serviços |  |
| VL_SERV_NT | Float |  | Valor total dos serviços não-tributados pelo ICMS |  |
| VL_TERC | Float |  | Valores cobrados em nome de terceiros |  |
| VL_DA | Float |  | Valor de outras despesas indicadas no documento fiscal |  |
| VL_BC_ICMS | Float |  | Valor da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS |  |
| COD_INF | String |  | Código da informação complementar |  |
| VL_PIS | Float |  | Valor do PIS |  |
| VL_COFINS | Float |  | Valor da COFINS |  |
| CHV_DOCE | String |  | Chave    da    Nota    Fiscal    Fatura    de    Serviço    de Comunicação Eletrônica. |  |
| FIN_DOCE | Integer |  | Finalidade da emissão do documento eletrônico | `0`=NFCom Normal `3`=NFCom de Substituição `4`=NFCom de Ajuste |
| TIP_FAT | Integer |  | Tipo de faturamento do documento eletrônico | `0`=Faturamento normal `1`=Faturamento Centralizado `2`=Cofaturamento |
| COD_MOD_DOC_REF | Integer |  | Código do modelo do documento fiscal referenciado |  |
| CHV_DOCE_REF | String |  | Chave da nota referenciada. |  |
| HASH_DOC_REF | String |  | Código de autenticação digital do registro |  |
| SER_DOC_REF | String |  | Série do documento fiscal referenciado. |  |
| NUM_DOC_REF | Integer |  | Número do documento fiscal referenciado. |  |
| MES_DOC_REF | String |  | Mês e ano da emissão do documento fiscal referenciado. |  |
| COD_MUN_DEST | Integer |  | Código do município do destinatário conforme a tabela do IBGE. |  |
| DED | Float |  | Deduções |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD730 — EFD Fiscal Registro D730
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_OPR | Float |  | Valor da operação |  |
| VL_BC_ICMS | Float |  | Parcela correspondente ao "Valor da base de cálculo do ICMS" |  |
| VL_ICMS | Float |  | Parcela correspondente ao "Valor do ICMS" |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base de cálculo do ICMS |  |
| COD_OBS | Integer |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD731 — EFD Fiscal Registro D731
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQD730 | Integer |  | SEQD730 |  |
| REGISTRO | String |  | Registro |  |
| VL_FCP_OP | Float |  | Valor do FCP vinc. à operação própria |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD735 — EFD Fiscal Registro D735
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_OBS | String |  | Cód. Observação |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD737 — EFD Fiscal Registro D737
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQD735 | Integer |  | SEQD735 |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ | String |  | Código do ajustes/benefício/incentivo |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste do doc. fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_BC_ICMS | Float |  | Base de cálculo do ICMS ou do ICMS ST |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS ou do ICMS ST |  |
| VL_OUTROS | Float |  | Outros valores |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD750 — EFD Fiscal Registro D750
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| COD_MOD | String |  | Código do modelo do documento fiscal, conforme a Tabela 4.1.1 |  |
| SER | String |  | Série do documento fiscal |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| DT_DOC | Date |  | Data da emissão dos documentos |  |
| REGISTRO | String |  | Registro |  |
| QTD_CONS | Integer |  | Quantidade de documentos consolidados neste registro |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| IND_PREPAGO | Integer |  | Forma de pagamento | `0`=0 – pré pago `1`=1 – pós pago |
| ORDEM | Integer |  | Ordem |  |
| VL_DOC | Float |  | Valor total dos documentos |  |
| VL_SERV | Float |  | Valor dos serviços tributados pelo ICMS |  |
| VL_SERV_NT | Float |  | Valores cobrados em nome do prestador sem destaque de ICMS |  |
| VL_TERC | Float |  | Valor total cobrado em nome de terceiros |  |
| VL_DESC | Float |  | Valor total dos descontos |  |
| VL_DA | Float |  | Valor total das despesas acessórias |  |
| VL_BC_ICMS | Float |  | Valor total da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor total do ICMS |  |
| VL_PIS | Float |  | Valor total do PIS |  |
| VL_COFINS | Float |  | Valor total da COFINS |  |
| DED | Float |  | Deduções |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD760 — EFD Fiscal Registro D760
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_OPR | Float |  | Valor da operação |  |
| VL_BC_ICMS | Float |  | Parcela correspondente ao "Valor da base de cálculo do ICMS" |  |
| VL_ICMS | Float |  | Parcela correspondente ao "Valor do ICMS" |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base de cálculo do ICMS |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TLFEFDFD761 — EFD Fiscal Registro D761
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQD760 | Integer |  | SEQD760 |  |
| REGISTRO | String |  | Registro |  |
| VL_FCP_OP | Float |  | Valor do FCP vinc. à operação própria |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TLFHGR — Histórico Agendador Geração Reinf
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUHISTORICO | Integer |  | Número do histórico |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPOAGE | String |  | Tipo de agendamento |  |
| DHINIEXEC | DateTime |  | Dh. Ini execução |  |
| DHFIMEXEC | DateTime |  | Dh. Fim execução |  |
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Data de Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Pré-Produção - dados reais |
| EVTTOTAIS | Integer |  | Total de Eventos |  |
| MSG | C |  | Mensagem |  |
| NUAGENDAMENTO | Integer |  | Nro. agendamento |  |

## TLFICMONO — Tabela de Impostos Monofásicos
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa do cadastro |  |
| CODREGTRIB | Integer |  | Regime tributário da empresa | `0`=Sem Regime Tributário `1`=Simples Nacional `2`=Simples Nacional - Sublimite `3`=Regime Normal |
| CODCNAE | String |  | CNAE da empresa |  |
| CODCST | String |  | Código da situação tributária |  |
| CODCCLASTRIB | String |  | Código de Classificação Tributária |  |
| CODNCM | String |  | NCM do Produto |  |
| CODNBS | String |  | NBS do serviço |  |
| CODTIPOPER | Integer |  | Tipo de operação |  |
| NUFOP | Integer |  | Finalidade da operação |  |
| DHALTER | DateTime |  | Dt./Hr. Operação |  |
| CODUF | Integer |  | UF destino |  |
| CODCID | Integer |  | Município destino |  |
| ADREMIBS | Float |  | Alíquota ad rem IBS |  |
| ADREMCBS | Float |  | Alíquota ad rem CBS |  |
| ADREMIBSRET | Float |  | Alíquota ad rem IBS (retenção) |  |
| ADREMCBSRET | Float |  | Alíquota ad rem CBS (retenção) |  |
| ADREMIBSRETANT | Float |  | Alíquota ad rem IBS (retida ant.) |  |
| ADREMCBSRETANT | Float |  | Alíquota ad rem CBS (retida ant.) |  |
| PDIFIBSMON | Float |  | % diferim. monofásico IBS |  |
| PDIFCBSMON | Float |  | % diferim. monofásico CBS |  |
| DTINIVIG | Date |  | Vigência início |  |
| DTFIMVIG | Date |  | Vigência fim |  |
| OBSERVADFISCOIB | String |  | Observações |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CHAVEUNICA | String |  | Chave Única |  |
| GRUPOIBSCBS | Integer |  | Grupo IBS/CBS |  |
| CODPROD | Integer |  | Código do Produto |  |
| IDIBSCBSMONO | Integer |  | Cód. Ibs. Cbs. Mono |  |

## TLFNBS — NBS
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCNBS | String |  | Descrição do NBS |  |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |
| CODNBS | String |  | Código NBS |  |

## TLFNCM — NCM
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCNCM | String |  | Descrição do NCM |  |
| ATIVO | String |  | Ativo | `N`=Nao `S`=Sim |
| CODNCM | String |  | Código NCM |  |

## TLFREFWIZLOG — Tabela de Log de Integração
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário da Operação |  |
| DTINTEG | DateTime |  | Data da Integração |  |
| QTDALIQIBS | Integer |  | Alíquotas de IBS Cadastradas |  |
| QTDALIQCBS | Integer |  | Alíquotas de CBS Cadastradas |  |
| QTDERROS | Integer |  | Quantidade de Erros |  |
| CODINTEG | Integer |  | Código Integração |  |

## TLFREFWIZLOGERR — Tabela de Log de Erros da Integração
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODINTEG | Integer |  | Código Integração |  |
| ERRO | String |  | Mensagem de Erro |  |
| CODERRO | Integer |  | Código do Erro |  |

## TLFREFWIZTERMO — Tabela de Usuários que aceitaram o termo de uso do wizard da reforma
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ACEITO | String |  | Termo Aceito |  |
| CODUSU | Integer |  | Código do Usuário |  |

## TMDAMG — Anexo Mensagens
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANEXO | Boolean |  | ANEXO |  |
| NOMEARQUIVO | String |  | NOMEARQUIVO |  |
| TIPO | String |  | TIPO |  |
| CID | String |  | Content-ID |  |
| NUANEXO | Integer |  | NUANEXO |  |

## TMDAXM — Anexo por Mensagem
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUANEXO | Integer |  | NUANEXO |  |
| CODFILA | Integer |  | CODFILA |  |

## TMDCAM — Tabela de campos para variáveis do tipo tabela
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECAM | String |  | Nome do campo |  |
| DESCCAM | String |  | Descrição do campo |  |
| TIPOCAM | String |  | Tipo do campo | `S`=Texto `H`=Data e Hora `D`=Data `I`=Inteiro `F`=Decimal_(+2)_ |
| TAMANHO | Integer |  | Tamanho do campo |  |
| CODCAM | Integer |  | Código do campo |  |

## TMDCON — Tabela de definição de destinatários
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECON | String |  | Nome do Destinatário |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CELULAR | String |  | Celular |  |
| EMAIL | String |  | E-mail |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODFUNC | Integer |  | Código do Funcionário |  |
| CODCONT | Integer |  | Código do Contato |  |
| CODCON | Integer |  | Código do Destinatário |  |

## TMDCPE — Tabela de ligação Consumidor - Perfil
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCON | Integer |  | Código do destinatário |  |
| CODPER | Integer |  | Código do perfil |  |

## TMDCPV — Tabela de ligação entre Campos e Variáveis
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCAM | Integer |  | Código do campo |  |
| CODVAR | Integer |  | Código da variável |  |

## TMDDMG — Tabela de ligação Destinatário - Mensagens
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCON | Integer |  | Código do consumidor |  |
| CODMSG | Integer |  | Código da mensagem |  |
| INTMIN | Integer |  | Intervalo mínimo |  |
| ULTENVIO | DateTime |  | Data do último envio para o destinatário |  |

## TMDFMD — Tabela de Fila de Contatos de Mensagens
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| EMAIL | String |  | EMAIL |  |
| CODFILA | Integer |  | CODFILA |  |

## TMDFMG — Tabela da fila de mensagens
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMSG | Integer |  | Código da Mensagem |  |
| STATUS | String |  | Status |  |
| DTENTRADA | DateTime |  | Data de Entrada |  |
| TENTENVIO | Integer |  | Tentativas de Envio |  |
| CODCON | Integer |  | Código do Consumidor |  |
| TIPOENVIO | String |  | TIPOENVIO | `M`=Mensagem Instantânea `E`=E-mail `C`=SMS `B`=Aplicativo Móvel `S`=Notificação do Sistema_(+1)_ |
| MAXTENTENVIO | Integer |  | MAXTENTENVIO |  |
| ASSUNTO | String |  | ASSUNTO |  |
| NUANEXO | Integer |  | NUANEXO |  |
| CELULAR | String |  | Celular |  |
| EMAIL | String |  | EMAIL |  |
| MIMETYPE | String |  | MIMETYPE |  |
| TIPODOC | String |  | Tipo Documento | `B`=Boleto `E`=Evento |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUCHAVE | Integer |  | Pedido do Evento |  |
| CODUSUREMET | Integer |  | Usuário Remetente |  |
| REENVIAR | String |  | Reenviar | `S`=Sim `N`=Não |
| MSGERRO | String |  | Mensagem de Erro |  |
| CODSMTP | Integer |  | Conta SMTP |  |
| CODCONTASMS | Integer |  | Conta SMTP |  |
| DHULTTENTA | DateTime |  | DHULTTENTA |  |
| DBHASHCODE | String |  | DBHASHCODE |  |
| CODFILA | Integer |  | Código na Fila |  |
| EMAILSEMCOPIA | String |  | Em cópia para |  |
| MENSAGEM | C |  | Mensagem SLA |  |

## TMDGRU — Tabela de grupos de variáveis
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPO | String |  | Descrição |  |
| ORDEM | Integer |  | Ordem |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODGRUPO | Integer |  | Código do Grupo |  |

## TMDGRV — Tabela de ligação Variável - Grupo de variáveis
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPO | Integer |  | Código do grupo |  |
| CODVAR | Integer |  | Código da variável |  |

## TMDMPE — Tabela de ligação Mensagem - Perfil
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMSG | Integer |  | Código da Mensagem |  |
| CODPER | Integer |  | Código do Perfil |  |

## TMDMSG — Tabela de definição de  mensagens
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CONDICAO | C |  | Condição |  |
| MENSAGEM | C |  | Mensagem |  |
| INTMIN | Integer |  | INTMIN |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| INDICACAO | String |  | Indicação | `M`=Mensagem Instantânea `A`=E-mail/SMS `C`=SMS `E`=E-mail `S`=Notificação do Sistema_(+1)_ |
| TENTATIVAS | Integer |  | Número de Tentativas |  |
| ATIVA | String |  | Ativa | `S`=Sim `N`=Não |
| PROXRESOL | DateTime |  | Data para a próxima resolução da mensagem |  |
| ULTRESOL | DateTime |  | Data da última resolução da mensagem |  |
| CFGDTRESOL | String |  | Configuração das datas de resolução |  |
| TIPOCONTEUDO | String |  | Tipo Conteúdo | `P`=Texto Plano `H`=HTML |
| ASSUNTO | String |  | Assunto |  |
| CODSMTP | Integer |  | Conta SMTP |  |
| CODMSG | Integer |  | Código da Mensagem |  |

## TMDMSR — Tabela de mensagens resolvidas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMSG | Integer |  | Código da mensagem |  |
| DTALTER | DateTime |  | Data de alteração |  |
| MENSAGEM | C |  | Mensagem |  |
| NOVA | Integer |  | Nova? |  |

## TMDPER — Tabela de perfis
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPER | String |  | Nome do Perfil |  |
| DESCPER | String |  | Descrição do Perfil |  |
| ENVULT | String |  | Enviar Somente Última | `N`=Não `S`=Sim |
| INTMIN | Integer |  | Intervalo Mínimo |  |
| USAQUERYLISTA | String |  | Lista Destinatários Variável | `S`=Sim `N`=Não |
| QUERYLISTADEST | C |  | Consulta |  |
| CODPER | Integer |  | Código do Perfil |  |

## TMDPRM — Contém a data da próxima mensagem a ser resolvida
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROXRESOL | DateTime |  | Data da próxima ativação do Job de Mensagens |  |

## TMDPRS — Contém a data da próxima variável a ser resolvida
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROXRESOL | DateTime |  | Data da próxima ativação do Job de Variáveis |  |

## TMDVAR — Tabela de definição de variáveis
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEVAR | String |  | Nome da Variável |  |
| DESCRVAR | String |  | Descrição da Variável |  |
| NOMEEXIB | String |  | Nome de Exibição |  |
| TIPO | String |  | Tipo | `C`=Calculado `S`=SQL `V`=Valor |
| TIPOSAIDA | String |  | Tipo de Saída | `S`=Texto `H`=Hora `I`=Inteiro `R`=Data-hora `T`=Tabela_(+2)_ |
| ORDEM | Integer |  | Ordem |  |
| PERIODICIDADE | Integer |  | Periodicidade |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODGRUPO | Integer |  | Código do Grupo |  |
| FORMULA | C |  | Fórmula |  |
| EXPDTREF | String |  | Expressão de Data de Referência |  |
| VALORPADRAO | String |  | A variável permite valor padrão? |  |
| OBS | String |  | Observação |  |
| ATIVA | String |  | Ativa? |  |
| ULTRESOL | DateTime |  | Data da última resolução da variável |  |
| PROXRESOL | DateTime |  | Data para a próxima resolução da variável |  |
| CFGDTRESOL | String |  | Configuração da data de resolução |  |
| CODVAR | Integer |  | Código da Variável |  |

## TMDVRE — Tabela de variáveis resolvidas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VALORNUMERICO | Float |  | VALORNUMERICO |  |
| CODVAR | Integer |  | Código da variável |  |
| CODVARRES | Integer |  | Código da variável resolvida |  |
| DTALTER | DateTime |  | Data de alteração |  |
| DTREF | DateTime |  | Data de referência |  |
| VALOR | String |  | Valor |  |

## TMIAUN — Acesso Unidade Gerencial
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| CODGRUPO | Integer |  | Grupo |  |
| TEMACESSO | String |  | Tem acesso | `S`=Sim `N`=Não |
| CODUNG | Integer |  | Un. Gerencial |  |

## TMICAU — Causa efeito
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCAUSA | Integer |  | Causa |  |
| DESCRICAO | String |  | Descrição |  |
| NUCAUSAORIG | Integer |  | Causa Origem |  |
| IMPORTANCIA | String |  | Importância | `2`=Muito Importante `0`=Sem Importância `1`=Importante |
| DETALHES | String |  | Detalhes |  |
| ACOES | Integer |  | Ações |  |
| NUEFEITO | Integer |  | Núm. Efeito |  |

## TMICEP — Causa Efeito Problema
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUEFEITO | Integer |  | Análise de Causa |  |
| CODCAUSA | Integer |  | Cód. Causa |  |
| CODPLA | Integer |  | Cód. Plano de Ação |  |

## TMIEFE — Efeito/Problema
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| NUMET | Integer |  | Meta |  |
| CODEXE | Integer |  | Exercício |  |
| PERINI | DateTime |  | Período |  |
| CODUNG | Integer |  | Unidade Gerencial |  |
| DTANALISE | DateTime |  | Dt. Análise |  |
| OBSERVACAO | String |  | Observação |  |
| STATUS | String |  | Status | `P`=Pendente `F`=Finalizado |
| NUEFEITO | Integer |  | Cód. Análise |  |

## TMIEXE — Exercícios
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| DTINI | Date |  | Data de Início |  |
| DTFIN | Date |  | Data de Finalização |  |
| OBS | String |  | Observação |  |
| CODUSU | Integer |  | Usuário |  |
| DHALTER | DateTime |  | Última alteração |  |
| CODEXE | Integer |  | Exercício |  |

## TMIFME — Faixas de Farol
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FAROL | Integer |  | Farol | `2`=Muito bom `1`=Bom `-1`=Ruim `-2`=Muito ruim `0`=Neutro |
| EXPFAROL | C |  | Expressão do Farol |  |
| ORDEMAVAL | Integer |  | Ordem de Avaliação |  |
| NUMET | Integer |  | Nro. Meta |  |

## TMIIND — Indicadores
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPO | String |  | Tipo | `V`=Valor `P`=Percentual |
| ORIENTACAO | String |  | Orientação | `F`=Entre Faixas `E`=Menor melhor `A`=Maior melhor |
| UNMEDIDA | String |  | Und. Medida |  |
| CODUSU | Integer |  | Usuário |  |
| DHALTER | DateTime |  | Última alteração |  |
| QTDDEC | Integer |  | Qtd. casas decimais |  |
| CODIND | Integer |  | Cód. Indicador |  |

## TMILOG — LogAtualizacaoMetas
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEXE | Integer |  | Cód. Exercício |  |
| DHULTEXEC | DateTime |  | Dh. Inclusão |  |
| SITULTATUAL | String |  | Evento | `E`=Erro `A`=Atualização |
| TEMPOTOTAL | String |  | Tempo Total |  |
| TIPOATUAL | String |  | Tipo Atualização | `M`=Manual `A`=Automático |
| LOG | C |  | Log Execução |  |
| TEMPOREAL | String |  | Tempo Real. |  |
| TEMPOPREV | String |  | Tempo Prev. |  |
| TEMPOREALACUM | String |  | Tempo Real. Acum. |  |
| TEMPOPREVACUM | String |  | Tempo Prev. Acum. |  |
| NUMET | Integer |  | Nro. Meta |  |

## TMIMET — Metas
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INFOPERIODO | String |  | Informações de período |  |
| DESCRICAO | String |  | Descrição |  |
| NUMETPAI | Integer |  | Nro. Meta Pai |  |
| CODUNG | Integer |  | Und. Gerencial |  |
| CODIND | Integer |  | Indicador |  |
| NUDSB | Integer |  | Dashboard de detalhamento |  |
| APRESDECGRAF | String |  | Apresentar casas decimais no gráfico | `S`=Sim `N`=Não |
| PERIODICIDADE | Integer |  | Periodicidade | `5`=Trimestral `8`=Bienal `7`=Anual `6`=Semestral `4`=Bimestral_(+4)_ |
| PERIODICIDADEATU | Integer |  | Periodicidade Atualização | `1`=Diário `4`=Mensal `3`=Quinzenal `2`=Semanal `5`=Semanal (Dom. à Sab.) |
| DHPROXATUAL | DateTime |  | Data Próx. Atualização |  |
| HORARIOATU | Text |  | Horário Atualização |  |
| EXPSQLREALPER | C |  | Expressão SQL para calculo do realizado no período |  |
| QTDPERLINEAR | Integer |  | Qtd. períodos para cálculo da tendência |  |
| EXPVALREALPER | C |  | Expressão de Valor Realizado no Período |  |
| TIPOREALACUM | String |  | Tipo de Realizado Acumulado | `M`=Média Simples `C`=Calculado `A`=Manual `S`=Soma |
| EXPSQLREALACUM | C |  | Expressão de Valor Realizado Acumulado |  |
| EXPVALREALACUM | C |  | Expressão de Valor Realizado Acumulado |  |
| TIPPREV | String |  | Tipo de Valor Previsto | `C`=Calculado `M`=Manual |
| EXPSQLPREVPER | C |  | Expressão SQL para Previsto no Período |  |
| EXPVALPREVPER | C |  | Expressão de Valor Previsto no Período |  |
| TIPOACUMPREV | String |  | Tipo de Acumulado Previsto | `S`=Soma `C`=Calculado `A`=Manual `M`=Média Simples |
| EXPSQLPREVACUM | C |  | Expressão de SQL para Previsto Acumulado |  |
| TIPOREAL | String |  | Tipo de Valor Realizado | `C`=Calculado `M`=Manual |
| EXPVALPREVACUM | C |  | Expressão de Valor Previsto Acumulado |  |
| DSREALPER | String |  | DSREALPER |  |
| DSREALACUM | String |  | DSREALACUM |  |
| DSPREVPER | String |  | DSPREVPER |  |
| DSPREVACUM | String |  | DSPREVACUM |  |
| NUMET | Integer |  | Nro. Meta |  |
| CODINSTQUEBRA | Integer |  | Código da quebra |  |
| NOMEINSTAQUEBRA | String |  | NOMEINSTAQUEBRA |  |

## TMIMXE — Metas por Exercícios
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEXE | Integer |  | Exercício |  |
| NUMET | Integer |  | Nro. Meta |  |

## TMINGE — Níveis Gerenciais
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| NIVEL | Integer |  | Nível |  |
| CODNGE | Integer |  | Cód. Nível Gerencial |  |

## TMIPLA — Plano de Ação
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| STATUS | String |  | Status | `F`=Finalizado `E`=Em Execução `C`=Cancelado `I`=Planejado `A`=Finalizado com atraso_(+1)_ |
| CODUNG | Integer |  | Un. Gerencial |  |
| NUMET | Integer |  | Meta |  |
| CODEXE | Integer |  | Exercício |  |
| CODUSU | Integer |  | Cód. Usuário Inclusão |  |
| DTPLA | DateTime |  | Dt./Hora Inclusão |  |
| CODUSUEXEC | Integer |  | Quem |  |
| OQUE | String |  | O que |  |
| ONDE | String |  | Onde |  |
| PORQUE | String |  | Porque |  |
| COMO | String |  | Como |  |
| QUANTO | String |  | Quanto custa |  |
| DTINIPREVISTO | DateTime |  | Início previsto |  |
| RETORNO | String |  | Retorno esperado |  |
| OBS | String |  | Observação |  |
| DTFIMPREVISTO | DateTime |  | Fim previsto |  |
| DTINIREALIZADO | DateTime |  | Início realizado |  |
| DTFIMREALIZADO | DateTime |  | Fim realizado |  |
| NUMOS | Integer |  | Ordem de serviço |  |
| COMPLETUDE | Float |  | % Completude | `100`=100% `95`=95% `90`=90% `85`=85% `80`=80%_(+16)_ |
| ESFORCOPREVISTO | String |  | Esforço Previsto |  |
| ESFORCOREALIZADO | String |  | Esforço Realizado |  |
| CODUSUALTER | Integer |  | Cód. Usuário Modificação |  |
| DHALTER | DateTime |  | Dt./Hora Modificação |  |
| CODPLA | Integer |  | Código |  |

## TMIPME — Parâmetros de Metas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPAR | String |  | Nome do Parâmetro |  |
| TIPO | String |  | Tipo | `T`=Texto `N`=Numérico (decimal) `I`=Numérico (inteiro) `D`=Data |
| LISTA | String |  | Lista | `N`=Não `S`=Sim |
| FONTE | String |  | Fonte |  |
| VALOR | String |  | Valor |  |
| NUMET | Integer |  | Nro. Meta |  |

## TMIPXM — Plano de ação x Meta
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMET | Integer |  | Cód. Meta |  |
| CODPLA | Integer |  | Cód. Plano Ação |  |

## TMIQUEI — TABLE TMIQUEI
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| AD_DESQUEBRA | String |  | Descrição |  |
| CODUNG | Integer |  | Código da unidade gerencial |  |
| NUMETBASE | Integer |  | Número do item da meta |  |
| CODQUEBRA | Integer |  | Código |  |

## TMIQUEL — TABLE TMIQUEL
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODQUEBRA | Integer |  | Código do item da quebra |  |
| NUMETBASE | Integer |  | Número do item da meta |  |
| NUMETQUEBRA | Integer |  | Número do item da quebra |  |

## TMIQUEP — TABLE TMIQUEP
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPAR | String |  | Nome do Parâmetro |  |
| NUMETBASE | Integer |  | Número de Itens da Meta |  |
| TIPO | String |  | Tipo de parâmetro | `T`=Texto `N`=Numérico (decimal) `I`=Numérico (inteiro) `D`=Data |
| VALOR | String |  | Valor Parâmetro |  |
| CODQUEBRA | Integer |  | Código da quebra |  |
| ID | Integer |  | ID do parâmetro |  |

## TMIRME — Realizados de Metas
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEXE | Integer |  | Exercício |  |
| DESCRPERIODO | String |  | Descrição do período |  |
| VLRPREV | Float |  | Valor Previsto |  |
| VLRREAL | Float |  | Valor Real |  |
| VLRPREVACUM | Float |  | Valor Previsto Acumulado |  |
| VLRREALACUM | Float |  | Valor Real Acumulado |  |
| PERINI | Date |  | Início do Período |  |
| PERFIN | Date |  | Final do Período |  |
| FAROL | Integer |  | Farol |  |
| FAROLACUM | Integer |  | Farol do Acumulado |  |
| FECHADO | String |  | Fechado | `N`=Não `S`=Sim |
| DHALTERPREV | DateTime |  | Última alteração valor previsto |  |
| DHALTERREAL | DateTime |  | Última alteração valor realizado |  |
| NUMET | Integer |  | Nro. Meta |  |
| CODUSU | Integer |  | Usuário |  |
| MANUAL | String |  | Atualização Manual | `S`=Sim `N`=Não |

## TMIUNG — Unidades Gerenciais
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativa | `S`=Sim `N`=Não |
| GRAU | Integer |  | Grau |  |
| CODNGE | Integer |  | Nível Gerencial |  |
| CODUNGPAI | Integer |  | Und. Gerencial Pai |  |
| CODUSURESP | Integer |  | Usuário Responsável |  |
| UNIDADE | String |  | Unidade |  |
| CODUNG | Integer |  | Und. Gerencial |  |

## TMIUXG — Usuários por Unidades Gerenciais
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| CODUNG | Integer |  | Cód. Und. Gerencial |  |

## TPOSOH — TABLE TPOSOH
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPROJETO | String |  | NOMEPROJETO |  |
| IDOBJETO | Integer |  | IDOBJETO |  |
| NOMEOBJETO | String |  | NOMEOBJETO |  |
| STATUSOBJETO | Integer |  | STATUSOBJETO |  |
| CODUSU | Integer |  | CODUSU |  |
| DESCRICAOSTATUSOBJETO | String |  | DESCRICAOSTATUSOBJETO |  |
| NOMEUSU | String |  | NOMEUSU |  |
| IDPROJETO | Integer |  | IDPROJETO |  |

## TPQANE — Anexo de pergunta
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERG | Integer |  | Cód. Pergunta |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| DESCRICAO | String |  | Descrição |  |
| CONTEUDO | Boolean |  | Conteúdo |  |
| NOMEARQUIVO | String |  | Nome do anexo |  |
| NUPESQ | Integer |  | Cód. Pesquisa |  |

## TPQAVD — TPQAVD
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPLA | Integer |  | Pla. Avaliador |  |
| NUPLAAVALIADO | Integer |  | Pla. Avaliado |  |
| CODUSU | Integer |  | Cód. Usu. Alteração |  |
| DHALTER | DateTime |  | Dh. Alteração |  |
| NUAVALIACAO | Integer |  | Avaliação |  |

## TPQCON — TPQCON
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPESQAVALIADO | Integer |  | NUPESQAVALIADO |  |
| NUPESQCONSENSO | Integer |  | NUPESQCONSENSO |  |
| NUAVALIACAO | Integer |  | NUAVALIACAO |  |
| STATUS | String |  | STATUS |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| PLANODEACAO | String |  | PLANODEACAO |  |
| NUPESQ | Integer |  | NUPESQ |  |

## TPQDPD — Relação entre perguntas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERGDEP | Integer |  | Cód. pergunta dependente |  |
| CODRESPMESTRE | Integer |  | Cód. resposta mestre |  |
| DHALTER | DateTime |  | Data de alteração |  |
| ORDEM | Integer |  | Ordem |  |
| CODPERGMESTRE | Integer |  | Cód. pergunta mestre |  |

## TPQDPL — Destinatario Planejamento
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUINSTANCIA | Integer |  | NUINSTANCIA |  |
| CHAVE | Integer |  | CHAVE |  |
| EVENTO | String |  | EVENTO |  |
| APRESENTACAO | String |  | Valor do campo de apresentação |  |
| CHAVE2 | Integer |  | CHAVE2 |  |
| NUPLA | Integer |  | NUPLA |  |

## TPQENV — Envio de e-mails para destinatários
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUINSTANCIA | Integer |  | NUINSTANCIA |  |
| CHAVE | Integer |  | CHAVE |  |
| CHAVE2 | Integer |  | CHAVE2 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| QTDENVIO | Integer |  | QTDENVIO |  |
| DHULTENVIO | DateTime |  | DHULTENVIO |  |
| EMAIL | String |  | EMAIL |  |
| RESPONDIDO | String |  | RESPONDIDO | `N`=Não `S`=Sim |
| CODFILA | Integer |  | CODFILA |  |
| NUPLA | Integer |  | NUPLA |  |

## TPQGRP — Grupo Perguntas
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOPERGPAI | Integer |  | Cód. Grupo pergunta pai |  |
| DESCRGRUPOPERG | String |  | Descrição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data de alteração |  |
| GRAU | Integer |  | Grau |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| CODGRUPOPERG | Integer |  | Cód Grupo pergunta |  |

## TPQGRQ — Grupo de Questionário
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPOQUEST | String |  | Descrição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data de alteração |  |
| CODGRUPOQUESTPAI | Integer |  | Código do pai |  |
| GRAU | Integer |  | Grau |  |
| ATIVO | String |  | Ativo | `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não |
| CODGRUPOQUEST | Integer |  | Cód. Grupo |  |

## TPQINF — Informações Questionario
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| DESCRICAO | String |  | Descrição |  |
| TEXTO | String |  | Texto |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data de alteração |  |
| CODQUEST | Integer |  | Código do Questionário |  |

## TPQPEQ — Pergunta X Questionário
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERG | Integer |  | Cód. da pergunta |  |
| ORDEM | Integer |  | Ordem |  |
| APELIDO | String |  | Apelido |  |
| PESO | Integer |  | Peso |  |
| CODQUEST | Integer |  | Cód. do questionário |  |

## TPQPER — Pergunta
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOPERG | Integer |  | Cód. grupo pergunta |  |
| DESCRPERG | String |  | Descrição |  |
| INSTRUCAOAPLICADOR | String |  | Instrução para aplicação |  |
| QTDMAXLINHAS | Integer |  | Qtd. máxima de linhas |  |
| TIPO | String |  | Tipo | `4`=Opções em linhas (Múltipla escolha) `3`=Opções em colunas (Única escolha) `2`=Opções em linhas (Única escolha) `1`=Caixa de texto (Múltiplas linhas) `0`=Caixa de texto (Única linha)_(+5)_ |
| QTDMAXESCOLHAS | Integer |  | Qtd. máxima de escolhas |  |
| NROTENTATIVAS | Integer |  | Núm. de tentativas |  |
| PERMITEANEXO | String |  | Permite Anexo | `S`=Sim `N`=Não |
| TEMPOPARARESPOSTA | Float |  | Tempo para resposta |  |
| ACEITAOBSERVACAO | String |  | Aceita observação | `S`=Sim `N`=Não |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data de alteração |  |
| CODPERGTAB | Integer |  | Cód. da tabela |  |
| ORDEMTAB | Integer |  | Ordem na tabela |  |
| OBRIGATORIA | String |  | Obrigatória | `S`=Sim `N`=Não |
| PERMITEFILTRAR | String |  | Permite filtrar pergunta | `N`=Não `S`=Sim |
| CODPERG | Integer |  | Cód. pergunta |  |

## TPQPES — Pesquisa
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPLA | Integer |  | NUPLA |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| DTAPLICACAO | DateTime |  | DTAPLICACAO |  |
| HORAAPLICACAO | Integer |  | HORAAPLICACAO |  |
| NOTAFINAL | Float |  | NOTAFINAL |  |
| DHALTER | DateTime |  | DHALTER |  |
| NOMEPESQ | String |  | NOMEPESQ |  |
| CODPARCPESQ | Integer |  | Cód. Parceiro Pesq |  |
| NUCURRICULOPESQ | Integer |  | NUCURRICULOPESQ |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEMPFUNPESQ | Integer |  | CODEMPFUNPESQ |  |
| CODFUNCPESQ | Integer |  | CODFUNCPESQ |  |
| CODUSUPESQ | Integer |  | CODUSUPESQ |  |
| CODPAPPESQ | Integer |  | CODPAPPESQ |  |
| TIPOPESQ | String |  | TIPOPESQ | `CE`=Contato de prospect `R`=Prospect `F`=Funcionário `U`=Usuário `C`=Candidato_(+2)_ |
| CODCONTATOPESQ | Integer |  | CODCONTATOPESQ |  |
| CODQUEST | Integer |  | CODQUEST |  |
| CODPRODPESQ | Integer |  | CODPRODPESQ |  |
| NUPESQ | Integer |  | NUPESQ |  |

## TPQPESSEQ — Histórico de Pesquisa
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMOS | Integer |  | NUMOS |  |
| NUPESQ | Integer |  | NUPESQ |  |
| NUPLA | Integer |  | NUPLA |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| DTAPLICACAO | DateTime |  | DTAPLICACAO |  |
| HORAAPLICACAO | Integer |  | HORAAPLICACAO |  |
| NOTAFINAL | Float |  | NOTAFINAL |  |
| DHALTER | DateTime |  | DHALTER |  |
| NOMEPESQ | String |  | NOMEPESQ |  |
| CODPARCPESQ | Integer |  | CODPARCPESQ |  |
| NUCURRICULOPESQ | Integer |  | NUCURRICULOPESQ |  |
| CODUSU | Integer |  | CODUSU |  |
| CODEMPFUNPESQ | Integer |  | CODEMPFUNPESQ |  |
| CODFUNCPESQ | Integer |  | CODFUNCPESQ |  |
| CODUSUPESQ | Integer |  | CODUSUPESQ |  |
| CODPAPPESQ | Integer |  | CODPAPPESQ |  |
| TIPOPESQ | String |  | TIPOPESQ |  |
| CODCONTATOPESQ | Integer |  | CODCONTATOPESQ |  |
| CODQUEST | Integer |  | CODQUEST |  |
| CODPRODPESQ | Integer |  | CODPRODPESQ |  |
| SEQPROPOSTA | Integer |  | SEQPROPOSTA |  |

## TPQPFI — Perfil X Questionário
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERFIL | Integer |  | Cód. Perfil |  |
| DHALTER | DateTime |  | Data da alteração |  |
| CODQUEST | Integer |  | Cód. do questionário |  |

## TPQPLA — Planejamento
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODQUEST | Integer |  | Cód. Questionário |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTINICIO | DateTime |  | Data Inicio |  |
| DTFIM | DateTime |  | Data Fim |  |
| STATUS | String |  | Status | `R`=Realizado `C`=Configurado `P`=Pendente |
| FORMADEAPLICAR | String |  | Forma de Aplicar | `5`=Manual `4`=E-mail `3`=Terminal `2`=Impressa `1`=Palm_(+1)_ |
| DHALTER | DateTime |  | Data/Hora Alteração |  |
| ASSUNTOEMAIL | String |  | Assunto do email |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| MAXENVIO | Integer |  | Máx. envio notificações |  |
| INTERVALOENVIO | Integer |  | Intervalo de envio |  |
| CODUSUAVALIADOR | Integer |  | Cód. Avaliador |  |
| CODSMTP | Integer |  | Conta SMTP |  |
| MODELOEMAIL | C |  | Modelo de email |  |
| NUPLA | Integer |  | Cód. Planejamento |  |

## TPQQU1 — Questionário
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRQUEST | String |  | Descrição |  |
| ATIVO | String |  | Ativo |  |
| PODEFECHARORDCARG | String |  | Pode fechar ordem de carga |  |
| PODEOBS | String |  | Obs |  |
| NOTAMIN | Integer |  | Nota Mínima |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODQUEST | Integer |  | Cód. Questionário |  |

## TPQQUE — Questionário
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRQUEST | String |  | Descrição |  |
| CODGRUPOQUEST | Integer |  | Cód. Grupo |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ORDEMALEATORIA | String |  | Ordem Aleatória | `N`=Não `S`=Sim |
| NROPERGPORPAG | Integer |  | Núm. de perguntas por pág. |  |
| EXIBERESPCORRETA | String |  | Exibir resposta correta | `S`=Sim `N`=Não |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| DHALTER | DateTime |  | Data e hora da alteração |  |
| PERGUNTASPORGRUPO | String |  | Organizar por grupos de pergunta | `N`=Não `S`=Sim |
| CODQUEST | Integer |  | Código |  |

## TPQRES — Resposta por Pergunta
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERG | Integer |  | Cód. Pergunta |  |
| CODRESP | Integer |  | Cód. resposta |  |
| DESCRRESP | String |  | Descrição da Resposta |  |
| VALORMIN | Float |  | Valor mínimo |  |
| VALORMAX | Float |  | Valor máximo |  |
| TAMANHOMAX | Integer |  | Tamanho máximo |  |
| NOTA | Float |  | Nota |  |
| PENALIDADE | Float |  | Penalidade |  |
| SEQAGRUPA | Integer |  | Agrupamento |  |
| ACEITAOBSERVACAO | String |  | Aceita Observação | `N`=Não `S`=Sim |
| NOMEARQUIVO | String |  | Nome do anexo |  |
| ANEXO | Boolean |  | Anexo |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data alteração |  |
| PADRAO | String |  | Padrão | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| LIMPAAGRUPA | String |  | Limpa agrupamentos |  |
| ATIVO | String |  | Resposta Ativa | `N`=Não `S`=Sim |

## TPQRPE — Resposta de Pergunta em Pesquisa
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERG | Integer |  | CODPERG |  |
| CODRESP | Integer |  | CODRESP |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TEXTO | String |  | TEXTO |  |
| VALOR | Float |  | VALOR |  |
| DHCORRECAO | DateTime |  | DHCORRECAO |  |
| NOTA | Float |  | NOTA |  |
| DHALTER | DateTime |  | DHALTER |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| ANEXO | Boolean |  | ANEXO |  |
| PROIBELIMPEZA | String |  | PROIBELIMPEZA |  |
| CODUSUCORRETOR | Integer |  | CODUSUCORRETOR |  |
| NUPESQ | Integer |  | NUPESQ |  |

## TPQRPESEQ — Histórico Resposta de Pergunta em Pesquisa
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQPROPOSTA | Integer |  | SEQPROPOSTA |  |
| NUPESQ | Integer |  | NUPESQ |  |
| CODPERG | Integer |  | CODPERG |  |
| CODRESP | Integer |  | CODRESP |  |
| CODUSU | Integer |  | CODUSU |  |
| TEXTO | String |  | TEXTO |  |
| VALOR | Float |  | VALOR |  |
| DHCORRECAO | DateTime |  | DHCORRECAO |  |
| NOTA | Float |  | NOTA |  |
| DHALTER | DateTime |  | DHALTER |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| ANEXO | Boolean |  | ANEXO |  |
| CODUSUCORRETOR | Integer |  | CODUSUCORRETOR |  |
| PROIBELIMPEZA | String |  | PROIBELIMPEZA |  |
| NUMOS | Integer |  | NUMOS |  |

## TRDBLC — BloqueioControle
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHINC | DateTime |  | DHINC |  |
| MOTIVO | String |  | MOTIVO |  |
| CODUSU | Integer |  | CODUSU |  |
| RESOURCEID | String |  | RESOURCEID |  |

## TRDEAC — Estatística de Acesso
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RESOURCEID | String |  | Resource ID |  |
| CODUSU | Integer |  | Usuário |  |
| DHULTACESSO | DateTime |  | Último acesso |  |
| DTINIPERIODO | DateTime |  | Início do período |  |
| QTDGERAL | Integer |  | Qtd. Acesso geral |  |
| QTDPERIODO | Integer |  | Qtd. Acesso no período |  |
| NUEAC | Integer |  | NUEAC |  |

## TRPCAM — Campo Replay
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CAMPOORIGEM | String |  | Campo de Origem |  |
| CAMPODESTINO | String |  | Campo de Destino |  |
| FILTRO | String |  | Filtro |  |
| NULIGACAO | Integer |  | Num. Ligação |  |

## TRPLOG — Tabela de Log Replay
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMOS | Integer |  | Núm. Ordem de Serviço/Ticket |  |
| TIPPROC | String |  | Tipo de processo |  |
| TABELA | String |  | Tabela |  |
| CONDICAO | String |  | Condição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHPROC | DateTime |  | Dt. Processo |  |
| NOMEARQUIVOORI | String |  | Arquivo Originário |  |
| NOMEARQUIVOBKP | String |  | Arquivo Backup |  |
| TABELAGERADA | String |  | Tabela e campo gerados |  |
| ID | Integer |  | ID |  |

## TRPMAP — Tabela de Mapa Replay
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRMAPA | String |  | Descrição do Mapa |  |
| TABRAIZ | String |  | Tabela Raíz |  |
| CODMAPA | Integer |  | Cód. Mapa |  |

## TRPTAB — Tabela Replay
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMAPA | Integer |  | Cód. Mapa |  |
| TABORIGEM | String |  | Tabela de Origem |  |
| TABDESTINO | String |  | Tabela de Destino |  |
| NULIGACAO | Integer |  | Num. Ligação |  |

## TRSANU — Anúncio de Vagas
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTENTRADA | Date |  | Data Abertura |  |
| DTTERMINO | Date |  | Data Término |  |
| DESCRVAGA | String |  | Descrição da Vaga |  |
| GRAUINSTR | Integer |  | Grau de Instrução | `10`=Mestrado Completo `11`=Doutorado Completo `7`=Ensino Médio Completo `5`=Fundamental Completo `8`=Superior Incompleto_(+6)_ |
| FAIXASALARIALINICIAL | Float |  | Faixa Salarial |  |
| FAIXASALARIALFINAL | Float |  | Faixa Salarial Final |  |
| NUREQUISICAO | Integer |  | Nro Requisição |  |
| NUVAGAS | Integer |  | Nro de Vagas |  |
| STATUS | String |  | Status | `A`=Aberto `C`=Cancelado `S`=Suspenso `F`=Fechado |
| RESUMO | String |  | Resumo da Vaga |  |
| TIPO | String |  | Tipo |  |
| CODANUNCIO | Integer |  | Cód. Anúncio |  |

## TRSAVR — TRSAVR
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUREQUISICAO | Integer |  | Nro. Requisição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODMOTIVO | Integer |  | Cód. Motivo |  |
| DHAVALIACAO | DateTime |  | Data Avaliação |  |
| STATUS | String |  | Status |  |
| OBSAVALIACAO | String |  | Observação |  |
| NUAVALIACAO | Integer |  | Nro. Avaliação |  |

## TRSCAN — Seleção Curriculo
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCURRICULO | Integer |  | Número Curriculo |  |
| NUREQUISICAO | Integer |  | Cód. Requisição |  |
| NOTASELECAO | Float |  | Nota de seleção |  |
| RESULTADO | Float |  | Média obtida |  |
| STATUS | String |  | Situação | `R`=Reprovado `A`=Aprovado `P`=Pendente `C`=Contratado |
| STATUSAPROV | String |  | Avaliação | `C`=Contratado `A`=Aprovado `P`=Pendente `N`=Não Teve Interesse `D`=Desistiu_(+1)_ |
| DTAPROV | Date |  | Data avaliação |  |
| CODUSUAPROV | Integer |  | Cód. Avaliador |  |
| OBSAPROV | String |  | Observações do avaliador para a requisição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | Date |  | Data de Alteração |  |
| CODEMP | Integer |  | Cód. Empresa Pessoal |  |
| CODFUNC | Integer |  | Cód. funcionário |  |
| NUSELECAO | Integer |  | Número de seleção |  |

## TRSECG — TRSECG
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODETAPA | Integer |  | Etapa |  |
| CODCARGO | Integer |  | Cargo |  |
| PONTUACAOMINIMA | Integer |  | Pontuação Mínima (%) |  |
| PESO | Integer |  | Peso |  |
| VLRETAPA | Float |  | Valor da Etapa |  |
| CODUSU | Integer |  | Usuário |  |
| DTALTER | DateTime |  | Data Alteração |  |
| SEQETAPA | Integer |  | Seq. Etapa |  |
| CODEMP | Integer |  | Empresa |  |

## TRSEPE — Etapa Personalizada
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEPE | Integer |  | Código Etapa Personalizada |  |
| CODETAPA | Integer |  | Código Etapa |  |
| CODUSU | Integer |  | Código Usúario |  |
| NUSELECAO | Integer |  | NUSELECAO |  |
| ARQMODEMAIL | String |  | Arquivo Modelo Email |  |
| DTALTER | Date |  | Data Alteração |  |
| DTABERTURA | Date |  | Data Abertura |  |
| NUREQUISICAO | Integer |  | Numero Requisição |  |

## TRSETA — TRSETA
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRETAPA | String |  | Descr. Etapa |  |
| CODQUESTIONARIO | Integer |  | Questionário |  |
| CODUSU | Integer |  | Usuário |  |
| DTALTER | DateTime |  | Data Alteração |  |
| ARQMODEMAIL | String |  | Modelo de e-mail p/ Seleção |  |
| NUSELECAO | Integer |  | NUSELECAO |  |
| NUCURRICULO | Integer |  | NUCURRICULO |  |
| NUREQUISICAO | Integer |  | NUREQUISICAO |  |
| CODETAPA | Integer |  | Etapa |  |

## TRSMOT — Motivos para Requisição
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRMOTIVO | String |  | Descrição |  |
| TIPMOTIVO | String |  | Tipo | `A`=Aprovação Requisição `N`=Negação Requisição `R`=Requisição Pessoal |
| CODMOTIVO | Integer |  | Código |  |

## TRSPER — Perfis da Requisição
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PESO | Integer |  | Peso |  |
| IMPRESCINDIVEL | String |  | Imprescindível | `N`=Não `S`=Sim |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Usuário |  |
| NUREQUISICAO | Integer |  | Requisição |  |
| CODPERFIL | Integer |  | Cód. Perfil |  |

## TRSPFV — Perfil de Vaga
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERFIL | Integer |  | Cód. Perfil |  |
| CODANUNCIO | Integer |  | Cód. Anúncio |  |

## TRSPON — TRSPON
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCURRICULO | Integer |  | Número Curriculo |  |
| CODETAPA | Integer |  | Cód.Etapa |  |
| SEQETAPA | Integer |  | Sequência |  |
| PONTUACAOMINIMA | Integer |  | Pontuação Mínima (%) |  |
| PESO | Integer |  | Peso |  |
| DTPLAN | DateTime |  | Data Planejamento |  |
| CODUSUPLAN | Integer |  | Cód Usuário Planejamento |  |
| OBSPLAN | String |  | Obs Planejamento |  |
| DTEXECUCAO | DateTime |  | Data Execução |  |
| CODUSUEXEC | Integer |  | Cód. Usuário Execução |  |
| OBSEXEC | String |  | Obs Execução |  |
| NUREQUISICAO | Integer |  | Número Requisição |  |
| VALORETAPA | Float |  | Valor Etapa |  |
| RESULTADO | Float |  | Nota Etapa |  |
| NUSELECAO | Integer |  | Número Seleção |  |

## TRSREQ — Requisição de Pessoal
Campos: 35

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRREQUISICAO | String |  | Descrição Requisição |  |
| CODEMP | Integer |  | Empresa |  |
| CODDEP | Integer |  | Departamento |  |
| CODCARGO | Integer |  | Cargo |  |
| CODUSUREQUISITANTE | Integer |  | Requisitante |  |
| CODUSU | Integer |  | Recrutador Responsável |  |
| SITREQUISICAO | Integer |  | Situação | `7`=Fechada `6`=Cancelada `5`=Suspensa `4`=Recrutando `3`=Negado_(+3)_ |
| DTREQUISICAO | Date |  | Data Requisição |  |
| DTPREVATEND | Date |  | Dt. Previsão Atend. |  |
| STATUSSELECAO | Integer |  | Status Seleção | `2`=Suspenso `1`=Fechado `0`=Em Aberto `99`=Não iniciado |
| PRIORIDADE | Integer |  | Prioridade |  |
| QTDVAGAS | Integer |  | Qtd. Vagas |  |
| QTDVAGASATEND | Integer |  | Vagas Atendidas |  |
| TIPVAGA | String |  | Tipo de Vaga | `E`=Efetivo `T`=Temporário |
| VINCULO | Integer |  | Vínculo | `90`=90 - Autônomo `80`=80 - Diretor sem vínculo empregatício `75`=75 - Prazo determinado rural (física) `70`=70 - Prazo determinado rural (jurídica) `40`=40 - Funcionário avulso_(+12)_ |
| CODCARGAHOR | Integer |  | Horário de trabalho |  |
| CODMOTIVO | Integer |  | Motivo |  |
| GRAUINSTR | Integer |  | Grau de Instrução | `10`=Mestrado Completo `1`=Analfabeto `11`=Doutorado Completo `5`=Fundamental Completo `4`=6º Ao 9º Ano Incompleto_(+6)_ |
| INIFAIXSAL | Float |  | Início faixa salarial |  |
| FIMFAIXSAL | Float |  | Fim faixa salarial |  |
| TIPOSELECAO | Integer |  | Tipo Seleção | `0`=Geral `2`=Externo `1`=Interno |
| CODPARC | Integer |  | Parceiro |  |
| PERMITEEXFUNC | String |  | Permite Ex. Funcionário | `N`=Não `S`=Sim |
| DTALTER | DateTime |  | Data Alteração |  |
| STATUS | String |  | Status | `S`=Suspenso `F`=Fechado `A`=Aberto |
| TIPO | Integer |  | Tipo | `0`=Substituição `1`=Aumento de quadro |
| JUSTIFICATIVA | String |  | Justificativa |  |
| OBS | String |  | Detalhamento adicional |  |
| OBSAVALIACAO | String |  | Observações |  |
| CODUSUAVAL | Integer |  | Avaliador |  |
| OBSCARGO | String |  | Detalhamento cargo |  |
| DHAVALIACAO | DateTime |  | Dt. Avaliação |  |
| CODMOTIVOAVAL | Integer |  | Motivo Aval |  |
| STATUSAVAL | String |  | Status Avaliação |  |
| NUREQUISICAO | Integer |  | Código |  |

## TRSRQS — Requisição seleção Curriculo
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUREQUISICAO | Integer |  | NUREQUISICAO |  |
| NUSELECAO | Integer |  | NUSELECAO |  |

## TRSSEL — Processo de Seleção
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRSELECAO | String |  | Descrição |  |
| NUREQUISICAO | Integer |  | Requisição |  |
| CODANUNCIO | Integer |  | Anúncio |  |
| DTINICIO | Date |  | Data de Início |  |
| DTPREVTERMINO | Date |  | Previsão de Término |  |
| DTFECHAMENTO | Date |  | Data de Fechamento |  |
| SITSELECAO | Integer |  | Situação | `2`=Suspenso `1`=Fechado `0`=Em Aberto `3`=Cancelado |
| CODUSURESPONSAVEL | Integer |  | Responsável |  |
| OBS | String |  | Observações |  |
| CODUSU | Integer |  | Usuário |  |
| DTALTER | DateTime |  | Data Alteração |  |
| PERSONALIZAR | String |  | Personalizar | `S`=Sim `N`=Não |
| QTDVAGASREQ | Integer |  | Qtd. Vagas Requisitadas |  |
| QTDVAGASPRE | Integer |  | Qtd. Vagas Preenchidas |  |
| NUSELECAO | Integer |  | Código |  |

## TRSSTE — Status Etapas
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRNUCURRICULO | String |  | Nome Candidato |  |
| NUSELECAO | Integer |  | N° Seleção |  |
| CODETAPA | Integer |  | Cód. Etapa |  |
| DESCRETAPA | String |  | Descr. Etapa |  |
| NUREQUISICAO | Integer |  | N° Requisição |  |
| DESCRREQUISICAO | String |  | Descr. Requisição |  |
| STATUSETAPA | String |  | Status do Candidato(Etapa) | `X`=Não Participou `R`=Reprovada `P`=Pendente `A`=Aprovado |
| CODSTAETAPA | Integer |  | Cód. Status Etapa |  |
| TIPOETAPA | String |  | Tipo da Etapa | `P`=Personalizado `N`=Padrão |
| NUCURRICULO | Integer |  | N° Curriculo |  |

## TRSVNE — Vagas por Nó de Estrutura
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDVAGAS | Integer |  | Qtd Vagas |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODEMP | Integer |  | Empresa |  |
| NUNO | Integer |  | Número do Nó |  |

## TSLCIB — Tabela de contingências de informações não sincronizadas com o servidor da BIA
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGBI | Integer |  | Código da informação |  |
| TIPO | String |  | Tipo da contingência | `S`=Salvar `D`=Deletar |
| TENTENVIO | Integer |  | Número de tentativas não bem sucedidas |  |
| DHOCORRENCIA | DateTime |  | Data e hora da contingência |  |
| SEQUENCIA | Integer |  | Identificador único |  |

## TSLCLU — Contingência do Login Único
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| TIPO | String |  | Tipo | `NU`=Nome `NC`=Nome Completo `IN`=Interno `FT`=Foto `EM`=E-mail_(+1)_ |
| DHOCORRENCIA | DateTime |  | Dt./Hr. Ocorrência |  |

## TSLIPG — Grupo de execuções.
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPO | Integer |  | Código do Grupo. |  |
| DESCRGRUPO | String |  | Descrição do grupo. |  |
| NOMEGRUPO | String |  | Nome do agrupamento. |  |

## TSLIPV — Dados de Previsão de Vendas
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEXEC | Integer |  | Código do Produto |  |
| VENDAS | Float |  | Vendas Previstas |  |
| MARGEM | Float |  | Margem Prevista |  |

## TSLIPX — Tabela de execução de previsão
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPO | Integer |  | Código do grupo de previsões. |  |
| CODEXEC | Integer |  | Código da execução |  |
| CODPROD | Integer |  | Código do Produto |  |
| TIPO | String |  | Tipo de Previsão |  |
| DIRETORIO | String |  | Diretório da previsão na AWS |  |

## TSLISC — Agendamento da Previsão de Vendas
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEXEC | Integer |  | Código do Produto |  |

## TSLIVA — Variáveis customizadas adicionais.
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave da variável |  |
| CODEXEC | Integer |  | Código da Execução |  |
| TIPO | String |  | Chave da variável |  |

## TSLIVD — Variáveis customizadas adicionais em periodicidade diária.
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Variável de previsão mensal |  |
| DIA | Date |  | Dias em que as variáveis se aplicam |  |
| VALOR | Float |  | Valor da variável |  |

## TSLIVM — Variáveis customizadas adicionais em periodicidade mensal.
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave da variável |  |
| MES | Date |  | Meses em que as variáveis se aplicam |  |
| VALOR | Float |  | Valor da variável |  |

## TSLSVM — Sincronizador de Versões Mobile
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEINSTANCIA | String |  | Nome da Instância |  |
| VERSAO | Integer |  | Versão do Registro |  |
| ID | String |  | ID do Registro |  |

## TSSBNR — Binarios de Solucoes
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Chave primaria |  |
| SOLUTIONID | String |  | Id da solucao na Area do Desenvolvedor |  |
| APPLICATIONID | String |  | ID externo da aplicacao |  |
| VERSION | String |  | Versao da solucao |  |
| FILENAME | String |  | Nome do arquivo original, utilizado durante processamento interno |  |
| STATUS | String |  | Status: WAITING_AUTH, AUTHORIZED, INSTALLED |  |
| FEATURES | C |  | Funcionalidades desta solucao |  |
| DESCRIPTION | String |  | Descricao desta solucao |  |
| CTX | String |  | Contexto desta solucao |  |
| SOLUTIONBINARY | Boolean |  | Binario da solucao em estado bruto, sem processamento |  |
| CODUSU | Integer |  | Usuário que iniciou Instalação |  |
| IS_SIGNED | String |  | Solução é Assinada | `S`=Sim `N`=Não |

## TSSHIS — Histórico Instalações Sankhya Store
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVESS | String |  | Chave no Sankhya Store |  |
| NOMEPAC | String |  | Nome Pacote |  |
| DHINST | DateTime |  | Data Instalação |  |
| CODUSUCAD | Integer |  | Usuário Instalador |  |
| APPKEY | String |  | App Key |  |
| STATUS | String |  | Status | `N`=Não Instalado `S`=Instalado |
| CODHIS | Integer |  | Código Histórico |  |

## TSSITP — ItensPacote
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Cód. Item |  |
| NOMEITEM | String |  | Nome |  |
| TIPO | String |  | Tipo | `T`=Tela Adicional `O`=EDI Retorno `N`=Cadastro Naturezas `I`=Relatório iReport `E`=EDI Remessa_(+4)_ |
| NUDSB | Integer |  | Dashboard |  |
| CODLIC | Integer |  | Código Licença Mestre |  |
| NUINSTANCIA | Integer |  | Instância |  |
| CADASTROPADRAO | C |  | Cadastro Padrão |  |
| NURFE | Integer |  | Relatório iReport |  |
| MODULO | String |  | Módulo EDI | `C`=Comercial `B`=Bancário |
| CODIGO | Integer |  | Layout EDI remessa |  |
| CODMODNF | Integer |  | Modelo de Impressão |  |
| DTALTERACAO | DateTime |  | Dt. Alteração |  |
| CODRET | Integer |  | Layout EDI retorno |  |
| NOMEARQUIVO | String |  | Arquivo Anexo |  |
| ARQUIVO | Boolean |  | Arquivo |  |
| NUINSTANCIACAD | Integer |  | Instância |  |
| ORDEMPK | String |  | Campos PKs do cadastro padrão |  |
| TIPO_BD | String |  | Tipo do Banco | `M`=MSSQL(SqlServer) `O`=Oracle `A`=Ambos |
| SCRIPT_BD | C |  | Script |  |
| STOPONERROR | String |  | Se ocorrer erro ao exec. script | `N`=Continuar `S`=Parar Instalação |
| SEQITP | Integer |  | Sequência |  |
| NUPAC | Integer |  | Nº Pacote |  |

## TSSLOG — Log de Instalações Pacotes Sankhya Store
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NOMEITE | String |  | Nome Item |  |
| NOMEINSREG | String |  | Tipo Item Instalação |  |
| PKREG | String |  | Chave Item Instalação |  |
| CODHIS | Integer |  | Cód. Histórico |  |
| CODLOG | Integer |  | Cód. Log |  |
| PRIVADO | String |  | Privado |  |
| CHAVESS | String |  | Chave Sankhya Store |  |

## TSSPAC — Pacotes Sankhya Store
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| IMAGEM | Boolean |  | Imagem |  |
| NOMEPAC | String |  | Nome |  |
| CATEGORIA | String |  | Categoria | `G`=Geral `C`=Comercial `F`=Financeiro `O`=Contabilidade `I`=Patrimonial_(+5)_ |
| TIPOPAC | String |  | Tipo | `T`=Tela Adicional `S`=Scripts de Banco `P`=Módulo Adicional `I`=Relatório iReport `ES`=EDI Remessa_(+4)_ |
| CODUSUCAD | Integer |  | Usuário Cadastro |  |
| CRIPTOGRAFADO | String |  | Solução protegida | `T`=Sim `F`=Não |
| TERMOUSO | String |  | Termos de uso | `S`=Sim `N`=Não |
| DHCAD | DateTime |  | Data Cadastro |  |
| DHALTER | DateTime |  | Data Alteração |  |
| CODUSUALTER | Integer |  | Usuário Alteração |  |
| TIPOBD | String |  | Funciona em | `M`=MSSQL `A`=Ambos `O`=Oracle |
| MODSPT | String |  | Modelo de suporte | `I`=Suporte incluso `N`=Suporte negociado `S`=Sem suporte |
| ARQUIVODOC | Boolean |  | ARQUIVODOC |  |
| NOMEARQUIVO | String |  | Documento |  |
| DESCRTECNICA | String |  | Descrição Técnica |  |
| GRATIS | String |  | Gratis | `S`=Sim `N`=Não |
| VLRPACOTE | Float |  | Valor da instalação (R$) |  |
| EXCLUSIVA | String |  | Solução exclusiva | `N`=Não `S`=Sim |
| CGC_CPF | String |  | CNPJ Cliente |  |
| VLRMENSAL | Float |  | Mensalidade (R$) |  |
| VLRTRANSACAO | Float |  | Transações adicionais (R$) |  |
| NUPAC | Integer |  | Nº Pacote |  |

## TTFFILA — Telemetria Fiscal Fila
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| JSONREQ | C |  | Json da requisição |  |
| DHALTER | DateTime |  | Data de alteração |  |
| TIPO | Integer |  | Tipo |  |
| STATUS | Integer |  | Status |  |

## TTKCARGOESOCIAL — Cargo eSocial
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCARGOESOCIAL | String |  | Cód. Cargo eSocial |  |
| CODCARGO | Integer |  | Cód. Cargo Sistema |  |

## TTKDIT — Diagnóstico de Item Tributação
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPROC | Integer |  | Número do processo |  |
| DHCONS | DateTime |  | Data da Consulta |  |
| DHRESP | DateTime |  | Data da Resposta |  |
| TIPO | String |  | Tipo do Item Tributação |  |
| RESPONSE | C |  | Response |  |

## TTKEVT — Eventos de Setup Inicial
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| STATUS | String |  | Status | `null`=Pendente `X`=Processando `E`=Erro `F`=Processado `D`=Processado em Duplicidade_(+1)_ |
| TIPO | String |  | Tipo | `CFE`=CF-e `CTE`=CT-e `NFE`=NF-e `NFSE`=NFS-e `EFD`=EFD_(+5)_ |
| NOMEARQUIVO | String |  | Nome do arquivo |  |
| MENSAGEM | C |  | Mensagem |  |
| DHCRIACAO | DateTime |  | Data Criação |  |
| DHINICIOPROC | DateTime |  | Data Início Processamento |  |
| DHFIMPROC | DateTime |  | Data Final Processamento |  |
| NFEPROPRIA | String |  | Nota própria |  |
| PARAMETROS | C |  | Parâmetros |  |
| EVENTO | String |  | Evento |  |

## TTKFUNLEG — Códigos legados de funcionários importados por planilha
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJEMP | String |  | CNPJ do estabelecimento |  |
| CPFTRAB | String |  | CPF funcionário |  |
| MATRICULA | String |  | Matrícula funcionário |  |
| CODFUNC | Integer |  | Código funcionário |  |

## TTKINDAGT — Indicadores do Agente
Campos: 47

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDERROESOCIAL | Integer |  | eSocial com Pendencia |  |
| QTDSUCESSOESOCIAL | Integer |  | eSocial processados |  |
| EMPRESASESOCIAL | Integer |  | Empresas Cadastrados |  |
| FUNCIONARIO | Integer |  | Funcionários Cadastrados |  |
| DEPENDENTE | Integer |  | Dependentes Cadastrados |  |
| BASEFOLHA | Integer |  | Base de Folha Cadastrados |  |
| FOLHA | Integer |  | Registros de Folha Cadastrados |  |
| CARGO | Integer |  | Cargps Cadastrados |  |
| REMUNERACAO | Integer |  | Remunerações Cadastradas |  |
| FERIAS | Integer |  | Ferias Cadastradas |  |
| OCORRENCIA | Integer |  | Ocorrências Cadastradas |  |
| PAGAMENTO | Integer |  | Pagamentos Cadastrados |  |
| EVENTOS | Integer |  | Eventos Cadastrados |  |
| DESLIGAMENTO | Integer |  | Desligamentos Cadastrados |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DHINICIOPROC | DateTime |  | Data Início Processamento |  |
| DHFIMPROC | DateTime |  | Data Final Processamento |  |
| QTDARQUIVOS | Integer |  | Arquivos |  |
| QTDERRO | Integer |  | Arquivos com Pendencia |  |
| QTDVAZIO | Integer |  | Arquivos Vazio |  |
| QTDINVALIDO | Integer |  | Arquivos Inválidos |  |
| QTDSUCESSO | Integer |  | Arquivos processados |  |
| QTDARQUIVOSNFE | Integer |  | Nf-e total |  |
| QTDERRONFE | Integer |  | Nf-e com Pendencia |  |
| QTDSUCESSONFE | Integer |  | Nf-e processados |  |
| QTDBASICONFE | Integer |  | Nf-e processados |  |
| EMPRESAS | Integer |  | Empresas Cadastradas |  |
| PARCEIROS | Integer |  | Parceiros Cadastrados |  |
| PRODUTOS | Integer |  | Produtos Cadastrados |  |
| VOLUMES | Integer |  | Volumes Cadastrados |  |
| TIPOSOPERACAO | Integer |  | Tipos de Operação Cadastrados |  |
| TIPOSNEGOCIACAO | Integer |  | Tipos de Negociação Cadastrados |  |
| TIPOSTITULOS | Integer |  | Tipos de Títulos Cadastrados |  |
| PARCELAS | Integer |  | Parcelas Cadastradas |  |
| PAIS | Integer |  | Países Cadastrados |  |
| ESTADOS | Integer |  | Estados Cadastrados |  |
| CIDADES | Integer |  | Cidades Cadastradas |  |
| BAIRROS | Integer |  | Bairros Cadastrados |  |
| ENDERECOS | Integer |  | Endereços Cadastrados |  |
| NOTASCOMPRAS | Integer |  | Notas de Compras Cadastradas |  |
| NOTASVENDAS | Integer |  | Notas de Vendas Cadastradas |  |
| NOTASDEVOLUCAOCOMPRAS | Integer |  | Notas de Devolução de Compras Cadastradas |  |
| NOTASDEVOLUCAOVENDAS | Integer |  | Notas de Devolução de Vendas Cadastradas |  |
| NOTASCANCELADAS | Integer |  | Notas Canceladas Cadastradas |  |
| FINANCEIROSPAGAR | Integer |  | Contas a Pagar Cadastradas |  |
| FINANCEIROSRECEBER | Integer |  | Contas a Receber Cadastradas |  |
| QTDARQUIVOSESOCIAL | Integer |  | eSocial total |  |

## TTKNOT — Notas instaladas pelo Setup
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NUNOTA | Integer |  | Nro Único Nota |  |
| NUMNOTA | Integer |  | Nro Nota |  |
| DHEMISS | DateTime |  | Data Emissão |  |
| DTCANC | DateTime |  | Data de Cancelamento |  |

## TTKNOTALIG — Ligação da Nota com Processo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDARTEFATO | String |  | Id do artefato de instalação |  |
| NUPROC | Integer |  | Numero do processo |  |
| CHAVE | String |  | Chave |  |

## TTKPITC — Cabecalho Processamento ICMS
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| NUPROC | Integer |  | Numero do processo |  |
| STATUS | String |  | Numero do processo |  |

## TTKPITD — Documentos Processados ICMS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| CHAVE | String |  | Chave |  |
| XML | C |  | Xml |  |
| NUPROC | Integer |  | Numero do processo |  |

## TTKPITI — Informacoes Processamento ICMS
Campos: 61

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VALICMS | Float |  | Valor ICMS |  |
| VALICMSST | Float |  | Valor ST Icms |  |
| MODBCICMS | Integer |  | Mod. Base ICMS |  |
| INDPRES | Integer |  | Indicador Operação Presencial |  |
| ALIQSUBTRIB | Float |  | Alíquota ST Icms |  |
| PERREDBCST | Float |  | % Redução Base ST |  |
| ALIQFCPST | Float |  | Alíquota FCP ST |  |
| CBENEFUF | String |  | Cód. de Benefício Fiscal na UF |  |
| CPAISDEST | String |  | Código do País Destino |  |
| PERCDIF | Float |  | Percetual Diferimento |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| OPERACAO | String |  | Operação |  |
| DATA | Date |  | Data |  |
| ESPECIE | String |  | Espécie |  |
| SERIE | String |  | Serie |  |
| NUMERO | String |  | Numero |  |
| CPFCNPJORIG | String |  | CNPJ Origem |  |
| TIPOORIG | String |  | Tipo Origem |  |
| RAZAOSOCORIG | String |  | Razão Social Origem |  |
| UFORIG | String |  | UF Origem |  |
| CPFCNPJDEST | String |  | CNPJ Destino |  |
| TIPODEST | String |  | Tipo Destino |  |
| RAZAOSOCDEST | String |  | Razão Social Destino |  |
| UFDEST | String |  | UF Destino |  |
| CFOP | String |  | CFOP |  |
| CODIGO | String |  | Código |  |
| DESCRICAO | String |  | Descrição |  |
| NCM | String |  | NCM |  |
| CEST | String |  | CEST |  |
| ORIGEM | String |  | Origem |  |
| UNIDADE | String |  | Unidade |  |
| CSTCSOSN | String |  | CST |  |
| ALIQICMS | Float |  | Aliq. ICMS |  |
| ASISALIQICMS | String |  | Validação ASIS - Aliq. ICMS |  |
| ASISVALORALIQICMS | String |  | Valor ASIS - Aliq. ICMS |  |
| MVA | Float |  | MVA |  |
| ASISMVA | String |  | Validação ASIS - MVA |  |
| ASISVALORMVA | String |  | Valor ASIS - MVA |  |
| ALIQICMSFCP | Float |  | Aliq. ICMS FCP |  |
| PERREDBCICMS | Float |  | Perc. Red. Base ICMS |  |
| ASISPERREDBCICMS | String |  | Validação ASIS - Perc. Red. Base ICMS |  |
| ASISVALORPERREDBCICMS | String |  | Valor ASIS - Perc. Red. Base ICMS |  |
| MODBCICMSST | Integer |  | Mod. Base ICMS ST |  |
| NUPROC | Integer |  | Numero do processo |  |
| VALIDASIS | String |  | Validação ASIS |  |
| CSTIPI | Integer |  | CST IPI |  |
| ALIQIPI | Float |  | Aliq. IPI |  |
| CSTPIS | Integer |  | CST PIS |  |
| ALIQPIS | Float |  | Alíquota PIS |  |
| VALIQPIS | Float |  | Alíquota PIS R$ |  |
| ALIQPISST | Float |  | Alíquota PIS ST |  |
| VALIQPISST | Float |  | Alíquota PIS ST R$ |  |
| CSTCOFINS | Integer |  | CST COFINS |  |
| ALIQCOFINS | Float |  | Alíquota COFINS |  |
| VALIQCOFINS | Float |  | Alíquota COFINS R$ |  |
| ALIQCOFINSST | Float |  | Alíquota COFINS ST |  |
| VALIQCOFINSST | Float |  | Alíquota COFINS ST R$ |  |
| IDDEST | Integer |  | Destino da Operação |  |
| INDFINAL | Integer |  | Consumidor Final |  |
| FINNFE | Integer |  | Finalidade |  |
| CHAVE | String |  | Chave |  |

## TTKPITRI — Regras Processadas ICMS
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CPFCNPJORIG | String |  | Empresa |  |
| ALIQSUBTRIB | Float |  | Alíquota ST Icms |  |
| PERREDBCST | Float |  | % Redução Base ST |  |
| ALIQFCPST | Float |  | Alíquota FCP ST |  |
| ALIQICMSFCP | Float |  | Alíquota ICMS FCP |  |
| MODBCICMSST | Float |  | Mod. Base ICMS ST |  |
| MODBCICMS | Float |  | Mod. Base ICMS |  |
| ORIGEM | Integer |  | Origem |  |
| CODPAISDEST | String |  | Código do País Destino |  |
| PERCDIF | Float |  | % Diferimento ICMS |  |
| NUPROC | Integer |  | Numero do processo |  |
| UFORIG | String |  | UF Origem |  |
| UFDEST | String |  | UF Destino |  |
| TIPO | String |  | Tipo |  |
| GRUPOICMS | Integer |  | Grupo ICMS |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CSTCSOSN | String |  | CST/CSOSN |  |
| CEST | String |  | CEST |  |
| REDICMS | Float |  | Redução de Base de ICMS |  |
| ALIQICMS | Float |  | Alíquota de ICMS |  |
| MVA | Float |  | Alíquota de MVA |  |
| NCM | String |  | NCM |  |
| TPIMPOSTO | String |  | Tipo do Imposto |  |
| ALIQ | Float |  | Alíquota |  |
| CFOP | String |  | CFOP |  |
| OPERACAO | String |  | Operação |  |
| CST | Integer |  | CST |  |
| REGRAGERAL | String |  | Regra Geral |  |

## TTKPROC — Processo do projeto Turnkey
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPROC | Integer |  | Numero do processo |  |
| NROUNICOPROC | Integer |  | Numero unico do processo |  |
| IDARTEFATO | String |  | Id do artefato de instalação |  |
| DHINIART | DateTime |  | Data de inicio da instalação |  |
| DHALTER | DateTime |  | Data de alteração da instalação |  |
| DATA | C |  | Dados de instalação do artefato |  |
| CODUSU | Integer |  | Código usuário responsável do processo |  |
| TIPOEXECUCAO | String |  | Tipo de execução |  |

## TTKPROTEMP — Produto Temporario
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPCONTEST | String |  | 
					 Tipo de controle de estoque 
				 | `E`=
						 Série 
					 `G`=
						 Grade 
					 `I`=
						 Livre 
					 `L`=
						 Número do lote 
					 `N`=
						 Sem controle adicional 
					_(+3)_ |
| USALOTEDTFAB | String |  | 
					 Utiliza data de Fabricação 
				 | `S`=
						 Sim 
					 `N`=
						 Não 
					 |
| TITCONTEST | String |  | 
					 Título Controle de estoque 
				 |  |
| CODPROD | Integer |  | 
					Código
				 |  |
| NUPROC | Integer |  | 
					Número do processo
				 |  |
| DESCRPROD | String |  | 
					Descrição
				 |  |
| USOPROD | String |  | 
					Usado como
				 | `1`=
						 Subproduto 
					 `2`=
						 Prod.Intermediário 
					 `4`=
						 Demonstração 
					 `B`=
						 Brinde 
					 `C`=
						 Consumo 
					_(+11)_ |
| CODGRUPOPROD | Integer |  | 
					Grupo
				 |  |
| ATIVO | String |  | 
					 Ativo 
				 |  |
| USALOTEDTVAL | String |  | 
					 Utiliza data de Validade 
				 | `S`=
						 Sim 
					 `N`=
						 Não 
					 |
| LISCONTEST | String |  | 
					 Lista Controle de estoque 
				 |  |
| ALTERADO | String |  | 
					 Alterado? 
				 |  |
| CODVOL | String |  | 
					Unidade padrão
				 |  |
| VOLUMEALTERNATIVO | String |  | 
					Unidade alternativa
				 |  |
| QUANTIDADE | String |  | 
					Quantidade
				 |  |
| DIVIDEMULTIPLICA | String |  | 
					Divide/Multiplica
				 | `D`=
						 Divide 
					 `M`=
						 Multiplica 
					 |
| UNIDADECOMPRA | String |  | 
					Unidade de Compra?
				 | `N`=
						 Não 
					 `S`=
						 Sim 
					 |
| CODVOLCOMPRA | String |  | 
					Unidade Compra
				 |  |

## TTKRELRUBAGT — Relacionamento Rúbricas x Eventos
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NROUNICO | Integer |  | Número único |  |
| CODEVENTO | Integer |  | Evento (Sistema) |  |
| DESCREVENTO | String |  | Descrição Evento (Sistema) |  |
| CODNATRUBRICA | String |  | Natureza (Sistema) |  |
| CODINCFGTS | String |  | Incidência FGTS (Sistema) |  |
| CODINCCP | String |  | Incidência INSS (Sistema) |  |
| CODINCIRRF | String |  | Incidência IRRF (Sistema) |  |
| SANKHYA | String |  | Sankhya (Padrão) | `S`=
                         Sim 
                     `N`=
                         Não 
                     |
| ATIVO | String |  | Ativo | `S`=
                         Sim 
                     `N`=
                         Não 
                     |
| CODRUBXML | String |  | Rubrica (eSocial) |  |
| DSCRUBRXML | String |  | Descrição Rubrica (eSocial) |  |
| IDETABRUBRXML | String |  | Identificador da Tabela de Rubricas (eSocial) |  |
| NATRUBRXML | String |  | Natureza (eSocial) |  |
| CODINCFGTSXML | String |  | Incidência FGTS (eSocial) |  |
| CODINCCPXML | String |  | Incidência INSS (eSocial) |  |
| CODINCIRRFXML | String |  | Incidência IRRF (eSocial) |  |
| IMPORTADOXML | String |  | Importado via XML |  |

## TTKSTPPE — Acompanhamento Processamento PIS COFINS Empresa
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPROC | Integer |  | Número do processo |  |
| CODEMP | Integer |  | Código da Empresa |  |
| CNPJ | String |  | CNPJ |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| DHCONFIG | DateTime |  | Data de Configuração |  |

## TWFAPVT — Prazo de Vencimento da Tarefa
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPRN | Integer |  | Cód. Processo |  |
| VERSAO | Integer |  | Versão |  |
| IDELEMENTO | String |  | Código do Elemento |  |
| SITUACAO | String |  | Situação |  |
| TIPONOTIFICACAO | String |  | Tipo de notificação | `S`=Notificação sistema `N`=Nenhuma `E`=E-mail `A`=Ambas |
| ATIVO | String |  | Ativa | `S`=Sim `N`=Não |
| NOTIFICAGESTOR | String |  | Notificar gestor | `S`=Sim `N`=Não |
| NOTIFICADONO | String |  | Notificar dono | `S`=Sim `N`=Não |
| EXPRDESTINATARIOS | C |  | Expressão de destinatarios |  |
| DECORRIDO | Float |  | Decorrido |  |
| CODSMTP | Integer |  | Cód. Conta |  |
| NUELE | Integer |  | Núm. Elemento |  |

## TWFASLA — Alerta SLA
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAO | Integer |  | Versão |  |
| REGRA | Integer |  | Regra |  |
| SEQUENCIA | Integer |  | Sequência |  |
| SITUACAO | String |  | Situação | `P`=No prazo `M`=Mais atrasado `I`=Início prazo `A`=A vencer `V`=Vencido |
| TIPONOTIFICACAO | String |  | Tipo de notificação | `S`=Notificação sistema `E`=E-mail `A`=Ambas `N`=Nenhuma |
| ATIVO | String |  | Active | `S`=Sim `N`=Não |
| NOTIFICAPADRAO | String |  | Notificar padrão | `S`=Sim `N`=Não |
| CODSMTP | Integer |  | Conta SMTP |  |
| EXPRDESTINATARIOS | C |  | Expressão de destinatarios |  |
| TEMPOLIMITE | Integer |  | Tempo limite |  |
| CODPRN | Integer |  | Cód. Processo |  |

## TWFCPN — Compartilhamento de Processos
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| TIPUSUGRU | String |  | Tipo | `E`=Equipe `U`=Usuário `G`=Grupo de Usuário |
| CODUSU | Integer |  | Cód. Usuário/Grupo/Equipe |  |
| PERMITEEDICAO | String |  | Permite Edição | `S`=Sim `N`=Não |
| PERMITECOMPARTILHAR | String |  | Permite Compartilhar | `S`=Sim `N`=Não |
| PERMITEINICIAR | String |  | Permite Iniciar Processo | `S`=Sim `N`=Não |
| CODPRN | Integer |  | Cód. Processo |  |

## TWFCRD — Credenciais do processo
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| CODUSUALTER | Integer |  | Usuário resp. alteração |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| DHPUBLICACAO | DateTime |  | Dh. publicação |  |
| CODUSUPUBLICACAO | Integer |  | Usuário resp. publicação |  |
| CONFIG | C |  | Configuração |  |
| NOMEVIEW | String |  | Nome view |  |
| STATUS | String |  | Status da credencial | `N`=Não publicado `M`=Manutenção `D`=Despublicada `P`=Publicada |
| PUBLICACAOAUTO | String |  | Publicação automática | `S`=Sim `N`=Não |
| VERSAOCREDENCIAL | String |  | Versão de alteração da credencial |  |
| CODPRN | Integer |  | Cód. Processo |  |

## TWFDHE — DashBoardFlow
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUGDG | Integer |  | Dashboard |  |
| TITULO | String |  | Título |  |
| NUELE | Integer |  | Código do Elemento |  |

## TWFELE — Elementos de Processo
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRN | Integer |  | Cód. Processo |  |
| VERSAO | Integer |  | Versão |  |
| IDELEMENTO | String |  | Id. Elemento |  |
| NOME | String |  | Nome |  |
| TIPO | String |  | Tipo |  |
| DOCUMENTACAO | C |  | Documentação |  |
| NOTIFICATIONOWNER | String |  | Notificação ao Dono |  |
| NOTIFICATIONCANDIDATE | String |  | Notificação ao Candidato |  |
| BACKGROUND | String |  | Background |  |
| HISTORYTEMPLATE | C |  | Template de histórico |  |
| EXPRESSLANGUAGE | String |  | Expressão linguagem |  |
| NUELE | Integer |  | Núm. Elemento |  |
| EXPRESSCANDITADE | String |  | Expressão candidato |  |

## TWFEVE — Evento de Processo Negocio
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRN | Integer |  | Código do Processo de Négocio |  |
| VERSAO | Integer |  | Versão |  |
| DESCREVENTO | String |  | Nome do Evento |  |
| FORMATO | String |  | Formato |  |
| ONDE | String |  | Onde | `P`=Processo `E`=Formulário Embarcado `A`=Apontamento `T`=Tarefa `F`=Formulário Formatado |
| ACAO | String |  | Ação | `V`=Salvar `S`=Iniciar `I`=Incluir `H`=Concluir `A`=Alterar_(+5)_ |
| QUANDO | String |  | Quando | `D`=Depois `A`=Antes |
| REFERENCIA | String |  | Referência |  |
| FORMULARIO | String |  | Formulário |  |
| TIPOACAO | Integer |  | Tipo Ação |  |
| IDELEMENTO | String |  | Código do Elemento |  |
| NUEVENT | Integer |  | Número do Evento |  |

## TWFFORM — Formularios de Processo
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUELE | Integer |  | Núm. Elemento |  |
| DESCRICAO | String |  | Descrição do formulário |  |
| NOMEINSTANCIA | String |  | Nome do formulário |  |
| CARDINALIDADE | String |  | Cardinalidade |  |
| ESCOPO | String |  | Escopo | `T`=Tarefa `P`=Processo |
| ORDEM | Integer |  | Ordem |  |
| ORDEMABAS | String |  | Ordem abas |  |
| SALVARDESTINO | String |  | Quando salvar destino |  |
| TIPO | String |  | Tipo |  |
| POLITICAREETRANCIA | String |  | Política Reentrância |  |
| NUFORMPAI | Integer |  | Núm. Formulário pai |  |
| CONFIGCAMPOS | C |  | Configuração de campos |  |
| SALVARFINALPROCESSO | String |  | Salvar no final do processo |  |
| UTILIZATAREFA | String |  | Utiliza na tarefa |  |
| NUFORM | Integer |  | Núm. Formulário |  |

## TWFGPR — Gestor de Processo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Seq. Gestor |  |
| CODGESTOR | Integer |  | Gestor |  |
| CODPRN | Integer |  | Código do Processo de Négocio |  |

## TWFGRU — Grupo de Processos
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GRUPOPAI | Integer |  | Grupo Pai |  |
| DESCRICAO | String |  | Descrição |  |
| CODUSU | Integer |  | Cod. Usuário |  |
| NUGRUPO | Integer |  | Nro. Grupo de Processo |  |

## TWFIEXE — Apontameto Execução Tarefa
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODUSU | Integer |  | Cód. usuário |  |
| DHINICIAL | DateTime |  | Dh. inicial |  |
| DHFINAL | DateTime |  | Dh. final |  |
| INTERVALO | Text |  | Intervalo |  |
| TEMPO | Text |  | Tempo |  |
| CODUSUALTER | Integer |  | Cod. usuário alteração |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| IDINSTPRN | Integer |  | Id Instância do Processo |  |

## TWFIHIS — Histórico de Intância de Processo
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTELE | Integer |  | Id Instância do Elemento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| IDELEMENTO | String |  | Id Elemento |  |
| TIPO | String |  | Tipo | `W`=Web Service `S`=Script `P`=Platform Service `M`=Mensagem `J`=Java_(+2)_ |
| DHEXECUCAO | DateTime |  | Dh. Execução |  |
| TEMPOEXECUCAO | Integer |  | Tempo de execução |  |
| STATUS | String |  | Status |  |
| RESUMO | String |  | Resumo |  |
| IDINSTPRN | Integer |  | Id Instância de Processo |  |

## TWFIPRN — Instância de Processos
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRN | Integer |  | Cód. Processo |  |
| VERSAO | Integer |  | Versão |  |
| OBSCANCEL | String |  | Observação de cancelamento |  |
| CODUSUINC | Integer |  | Usuário inclusão |  |
| CODUSUCANCEL | Integer |  | Usuário responsável pelo cancelamento |  |
| DHINCLUSAO | DateTime |  | Dh. inclusão |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão |  |
| SLAATUAL | Integer |  | Saldo atual |  |
| TEMPODECORRIDO | Float |  | Tempo decorrido |  |
| PERCDECORRIDO | Float |  | Percentual decorrido |  |
| TEMPOLIMITE | Float |  | Tempo limite |  |
| SITUACAO | String |  | Situação | `V`=Vencido `P`=No prazo `M`=Mais atrasado `I`=Início prazo `A`=A vencer |
| DHVENCIMENTO | DateTime |  | Dh. final do SLA do processo |  |
| IDPRNMESTRE | Integer |  | Inst. Processo mestre |  |
| SITUACAOEXEC | String |  | Situação da execução | `I`=Iniciado `F`=Finalizado `C`=Cancelado |
| IDINSTPRN | Integer |  | Nro Solicitação |  |

## TWFITAR — Instância de Tarefas
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| IDELEMENTO | String |  | Id Elemento |  |
| CODUSUSOLICITANTE | Integer |  | Usuário solicitante |  |
| CODUSUDONO | Integer |  | Usuário dono |  |
| DHCRIACAO | DateTime |  | Dh. criação |  |
| DHACEITE | DateTime |  | Dh. aceite |  |
| DHCONCLUSAO | DateTime |  | Dh. conclusão |  |
| SITUACAOEXEC | String |  | Situação da execução | `I`=Iniciado `F`=Finalizado `C`=Cancelado |
| PERCDECORRIDO | Float |  | Percentual Decorrido |  |
| TEMPODECORRIDO | Float |  | Tempo Decorrido |  |
| TEMPOLIMITE | Float |  | Tempo Limite |  |
| SITUACAO | String |  | Situação |  |
| DHVENCIMENTO | DateTime |  | Dh. Vencimento |  |
| CODUSUALTER | Integer |  | Cod. usuário alteração dono |  |
| DHALTER | DateTime |  | Dh. alteração dono |  |
| IDINSTPRN | Integer |  | Id Instância do Processo |  |
| NOMEELEMENTO | String |  | Nome |  |

## TWFIVAR — Instância de Variáveis
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| NOME | String |  | Nome |  |
| TIPO | String |  | Tipo |  |
| NUMINT | Integer |  | Número inteiro |  |
| NUMDEC | Float |  | Número decimal |  |
| DTA | DateTime |  | Data e Hora |  |
| TEXTO | String |  | Texto |  |
| TEXTOLONGO | String |  | Texto formatado |  |
| IDINSTPRN | Integer |  | Id Instância do Processo |  |

## TWFPDP — Processo Dependente
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAOPRNMESTRE | Integer |  | Versão Processo Mestre |  |
| NUPRNSUB | Integer |  | Cód. Subprocesso |  |
| NUPRNMESTRE | Integer |  | Cód. Processo Mestre |  |

## TWFPRE — Propriedade dos Elementos de Processo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| VALOR | String |  | Valor |  |
| NUELE | Integer |  | Núm. Elemento |  |

## TWFPRN — Processos de Negócios
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAO | Integer |  | Versão |  |
| NOME | String |  | Descrição |  |
| ATIVO | String |  | Publicado | `S`=Sim `N`=Não |
| DOCUMENTACAO | C |  | Documentação |  |
| NUGRUPO | Integer |  | Grupo Processo |  |
| CODUSUDONO | Integer |  | Usuário resp. cadastro |  |
| DHCRIACAO | DateTime |  | Dh. cadastro |  |
| CODUSUALTER | Integer |  | Usuário resp. alteração |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| DHPUBLICACAO | DateTime |  | Dh. publicação |  |
| XMLBPMN | C |  | XML do BPMN |  |
| IMGBPMN | C |  | Imagem do BPMN |  |
| ULTIMAVERSAO | String |  | Ultima versão |  |
| VERANTDHPUBLICACAO | DateTime |  | Dh. publicação da versão anterior |  |
| CODPRN | Integer |  | Cód. Processo |  |

## TWFPRV — Propriedade das Variáveis de Processo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| VALOR | String |  | Valor |  |
| NUVAR | Integer |  | Núm. Variável |  |

## TWFPVT — Prazo de Vencimento da Tarefa
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Active | `S`=Sim `N`=Não |
| CARGAHORARIA | Integer |  | Carga horária |  |
| TIPOPRAZO | String |  | Term type | `V`=Variável `F`=Fixo |
| TIPOTEMPO | String |  | Weather type | `H`=Horas `D`=Dias |
| TEMPOFIXO | Float |  | Tempo fixo |  |
| TEMPOVARIAVEL | String |  | Tempo variável |  |
| TIPOCONTAGEM | String |  | Tipo de Contagem | `P`=Percentagem `H`=Horas `D`=Dias |
| NUELE | Integer |  | Núm. Elemento |  |

## TWFRFA — Relatorio formatado por atividade
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NURFE | Integer |  | Código de Relatório |  |
| DESCRICAO | String |  | Nome do Relatório |  |
| NUELE | Integer |  | Código do Elemento |  |

## TWFRSLA — SLA Processo Negócio
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VERSAO | Integer |  | Versão |  |
| REGRA | Integer |  | Regra |  |
| ATIVO | String |  | Active | `N`=Não `S`=Sim |
| NOMEREGRA | String |  | Nome da regra |  |
| CARGAHORARIA | Integer |  | Carga horária |  |
| TIPOTEMPO | String |  | Tipo de tempo | `H`=Horas `D`=Dias |
| TEMPOLIMITE | Integer |  | Tempo limite |  |
| CONDICOESESCOLHA | C |  | Condição de escolha |  |
| CONDICOESSUSPENSAO | C |  | Condição de suspensão |  |
| TIPOTEMPOAVISO | String |  | Tipo de tempo do aviso | `H`=Hora `P`=Percento `D`=Dia |
| CODPRN | Integer |  | Cód. Processo |  |

## TWFTNF — Tela Nativa Flow
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUELE | Integer |  | Núm. Elemento |  |
| DESCRICAO | String |  | Descrição |  |
| RESOURCEID | String |  | ID do Recurso |  |
| NOMEINSTANCIA | String |  | Nome da Instância |  |
| NOMETAB | String |  | Nome da Tabela |  |
| PROPERTIES | C |  | Propriedades |  |
| CARDINALIDADE | String |  | Quantidade de registros | `N`=Vários `1`=Único |
| ESCOPO | String |  | Escopo | `T`=Tarefa `P`=Processo |
| POLITICAREENTRANCIA | String |  | Política de Reentrância | `R`=Recuperar dados anteriores `C`=Criar sempre um novo registro |
| FILTRO | String |  | Filtro de tela |  |
| CODTELA | Integer |  | Código da Tela |  |

## TWFUCP — Usuários Candidatos de Processo
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDELEMENTO | String |  | Id. Elemento |  |
| DINAMICO | String |  | Id Instância da Tarefa |  |
| IDINSTTAR | Integer |  | Id Instância da Tarefa |  |
| SEQUENCIA | Integer |  | Sequência |  |
| ATIVO | String |  | Ativo |  |
| CODEQUIPE | Integer |  | Cód. Equipe |  |
| CODUSU | Integer |  | Cód. usuário |  |
| CODGRUPOUSU | Integer |  | Cód. grupo |  |
| EXPRESSAO | String |  | Expressão variável |  |
| CODPRN | Integer |  | Cód. Processo |  |
| IDINSTPRN | Integer |  | Id Instância do Processo |  |

## TWFUST — Usuário Substituto de Tarefas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Alterado por |  |
| CODANTERIOR | Integer |  | Usuário anterior |  |
| CODSUBSTITUTO | Integer |  | Usuário Substituto |  |
| DHALTER | DateTime |  | Data alteração |  |
| OBSERVACAO | String |  | Observação |  |
| CODPRN | Integer |  | Cód. Processo |  |

## TWFVAR — Variaveis de Processo
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUELE | Integer |  | Núm. Elemento |  |
| NOME | String |  | Nome |  |
| TIPO | String |  | Tipo |  |
| ESCOPO | String |  | Escopo | `T`=Tarefa `P`=Processo |
| DESCRICAO | String |  | Descrição |  |
| VALORPADRAO | String |  | Valor padrão |  |
| OBRIGATORIO | String |  | Obrigatório | `S`=Sim `N`=Não |
| LEITURA | String |  | Leitura | `S`=Sim `N`=Não |
| DEFAULTLONG | String |  | Valor padrão |  |
| ORDEM | Integer |  | Ordem |  |
| NUVAR | Integer |  | Núm. Variável |  |

## TWUSU — Usuários
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| USUARIO | String |  | Login do Usuário |  |
| SENHA | String |  | Senha de Acesso |  |
| CODPARC | Integer |  | Cód.Parceiro |  |

## USUARIO — Aluno Universidade
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DELETED | Integer |  | Ativo | `1`=Não `0`=Sim |
| USERNAME | String |  | Nome |  |
| PASSWORD | String |  | Senha |  |
| FULLNAME | String |  | Nome Completo |  |
| EMAIL | String |  | E-Mail |  |
| INSTITUTIONID | Integer |  | Parceiro da universidade |  |
| FIRSTACCESS | DateTime |  | FIRSTACCESS |  |
| LASTACCESS | DateTime |  | LASTACCESS |  |
| TIMEMODIFIED | DateTime |  | TIMEMODIFIED |  |
| NOVATO | Integer |  | Novato | `0`=Não `1`=Sim |
| TODASEMPRESAS | Integer |  | Acesso ao Relat. Todas Empresas | `0`=Não `1`=Sim |
| IMPLANTADOR | Integer |  | Implantador | `1`=Sim `0`=Não |
| CARGO | String |  | Cargo |  |
| OBSERVACAO | String |  | Observação |  |
| NIVEL | Integer |  | Nível do usuário | `10`=Aluno `5`=Gestor Franquia `0`=Administrador `6`=Gestor Cliente `7`=Gestor Projeto_(+1)_ |
| CHANGEPASS | Integer |  | Alterar senha no próximo logon | `1`=Sim `0`=Não |
| SKJV | String |  | SKJV |  |
| CONCOMITANTE | Integer |  | Concomitante/Individual | `0`=Individual `1`=Concomitante |
| DTINICIO | DateTime |  | Dt. Início |  |
| DTFIM | DateTime |  | Dt. Fim |  |
| MATRMODELO | String |  | Matrícula modelo | `0`=Não `1`=Sim |
| ID | Integer |  | Código |  |