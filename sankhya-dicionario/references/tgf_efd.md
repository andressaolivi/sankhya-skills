# TGF — EFD (SPED Fiscal e Contribuições)

> Gerado do dicionário oficial TDD Sankhya. 324 tabelas.


## TGFEFDC — EFD Contribuições
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| VERSAOLAYOUT | Integer |  | Versão do Layout | `6`=006 - Fatos geradores: Início 01/01/2020 `5`=005 - Fatos geradores: Início 01/01/2019 `4`=004 - Fatos geradores: Início 01/06/2018 `3`=003 - Versão 2.01 - ADE Cofis nº 20/2012 - Início 01/07/2012 `2`=002 - Versão 2.00 - ADE Cofis nº 20/2012 - Início 01/04/2011_(+1)_ |
| ARQCONFIRMADO | String |  | Arquivo Confirmado? | `S`=Sim `N`=Não |
| CONFIG | C |  | Configuração |  |
| TIPO_ESCRIT_CSLL | Integer |  | Tipo escrituração | `1`=Retificadora `0`=Original |
| NOMEARQUIVO | String |  | Nome Arquivo |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0000 — EFD Contribuições Registro 0000
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| COD_VER | Integer |  | Cód. versão leiaute conforme tabela 3.1.1 | `5`=005 - Fatos geradores: Início 01/01/2019 `4`=004 - Fatos geradores: Início 01/06/2018 `3`=003 - Versão 2.01 - ADE Cofis nº 20/2012 - Início 01/07/2012 `2`=002 - Versão 2.00 - ADE Cofis nº 20/2012 - Início 01/04/2011 `1`=001 - Versão 1.00 - ADE Cofis nº 31/2010 - Início 01/01/2011 |
| TIPO_ESCRIT | Integer |  | Tipo escrituração | `1`=Retificadora `0`=Original |
| IND_SIT_ESP | Integer |  | Indicador situação especial | `4`=Encerramento `3`=Incorporação `2`=Fusão `1`=Cisão `0`=Abertura |
| NUM_REC_ANTERIOR | String |  | Núm. Rec. Escr. anterior a ser retificada |  |
| DT_INI | Date |  | Dt. inicial inform. contidas no arquivo |  |
| DT_FIN | Date |  | Dt. final inform. contidas no arquivo |  |
| NOME | String |  | Nome emp. PJ |  |
| CNPJ | String |  | Núm. inscr. estab. matriz |  |
| UF | String |  | Sigla Unid. Fed. da PJ |  |
| COD_MUN | Integer |  | Cód. munic. domic. fiscal PJ tabela IBGE |  |
| SUFRAMA | String |  | Inscr. PJ na Suframa |  |
| IND_NAT_PJ | String |  | Indicador natureza PJ | `05`=Sociedade em Conta de Participação - SCP `04`=Sociedade cooperativa participante de SCP como sócia ostensiva `03`=Pessoa jurídica em geral participante de SCP como sócia ostensiva `02`=Entidade sujeita ao PIS/Pasep exclusivamente com base na Folha de Salários `01`=Sociedade cooperativa_(+1)_ |
| IND_ATIV | Integer |  | Indicador tipo atividade preponderante | `9`=Outros `4`=Atividade imobiliária `3`=Pessoas jurídicas referidas nos §§ 6º, 8º e 9º do art. 3º da Lei nº 9.718, de 1998 `2`=Atividade de comércio `1`=Prestador de serviços_(+1)_ |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0001 — EFD Contribuições Registro 0001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_0 | Integer |  | Qtd. total linhas Bloco 0 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0035 — EFD Contribuições Registro 0035
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_SCP | String |  | Identificação da SCP |  |
| DESC_SCP | String |  | Descrição da SCP |  |
| INF_COMP | String |  | Informação Complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0100 — EFD Contribuições Registro 0100
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| NOME | String |  | Nome do contabilista |  |
| CPF | String |  | CPF do contabilista |  |
| CRC | String |  | CRC do contabilista |  |
| CNPJ | String |  | CNPJ do escritório de contabilidade |  |
| CEP | String |  | Cód. de Endereçamento Postal |  |
| ENDE | String |  | Logr. e endereço do imóvel |  |
| NUM | String |  | Número do imóvel |  |
| COMPL | String |  | Dados compl. do endereço |  |
| BAIRRO | String |  | Bairro do imóvel |  |
| FONE | String |  | Núm. do telefone |  |
| FAX | String |  | Núm. do fax. |  |
| EMAIL | String |  | End. correio eletrônico |  |
| COD_MUN | Integer |  | Cód. Munic. conforme tab. IBGE |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0110 — EFD Contribuições Registro 0110
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_INC_TRIB | Integer |  | Cód. indicador incid. trib. período | `3`=Escrituração de operações com incidência nos regimes não-cumulativo e cumulativo `2`=Escrituração de operações com incidência exclusivamente no regime cumulativo `1`=Escrituração de operações com incidência exclusivamente no regime não-cumulativo |
| IND_APRO_CRED | Integer |  | Cód. indicador mét. aprop. créd. comuns | `2`=Método de Rateio Proporcional (Receita Bruta) `1`=Método de Apropriação Direta |
| COD_TIPO_CONT | Integer |  | Cód. Tipo Contrib. Apurada Período | `2`=Apuração da Contribuição a Alíquotas Específicas sendo Diferenciadas e/ou por Unidade de `1`=Apuração da Contribuição Exclusivamente a Alíquota Básica |
| IND_REG_CUM | Integer |  | Cód. indicador critério escrit. e apur. adotado | `9`=Regime de Competência - Escrituração detalhada, com base nos registros dos Blocos A, C, D e F `2`=Regime de Competência - Escrituração consolidada (Registro F550) `1`=Regime de Caixa – Escrituração consolidada (Registro F500) |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0111 — EFD Contribuições Registro 0111
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGNIV2 | String |  | Registro Nível 2 |  |
| REGISTRO | String |  | Registro |  |
| REC_BRU_NCUM_TRIB_MI | Float |  | Rec. Bruta Não-Cumul. - Trib. Merc. Interno |  |
| REC_BRU_NCUM_NT_MI | Float |  | Rec. Bruta Não-Cumul. - Não Trib. Merc. Interno |  |
| REC_BRU_NCUM_EXP | Float |  | Rec. Bruta Não-Cumul. - Exportação |  |
| REC_BRU_CUM | Float |  | Rec. Bruta Cumulativa |  |
| REC_BRU_TOTAL | Float |  | Rec. Bruta Total |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0120 — EFD Contribuições Registro 0120
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| MES_REFER | Date |  | Mês ref. ano-calend. da escrituração sem dados |  |
| INF_COMP | String |  | Informação complementar do registro | `07`=Escrit. decorrente de incorporação, fusão ou cisão, sem operações geradoras de rec. ou de créd. `06`=Sociedade Cooperativa, que não realizou operações geradoras de receitas ou de créditos `05`=Soc. em Conta de Participação - SCP, que não realizou operações geradoras de receitas ou de créditos `04`=Pessoa jurídica em geral, que não realizou operações geradoras de receitas ou de créditos `03`=Pessoa jurídica inativa_(+6)_ |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0140 — EFD Contribuições Registro 0140
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| COD_EST | String |  | Cód. identif. estab. |  |
| NOME | String |  | Nome emp. estab. |  |
| CNPJ | String |  | CNPJ do estab. |  |
| UF | String |  | Sigla Unid. Fed. estab. |  |
| IE | String |  | Inscr. Est. estab. |  |
| COD_MUN | Integer |  | Cód. munic. dom. fiscal estab. tab. IBGE |  |
| IM | String |  | Inscr. Munic. estab. |  |
| SUFRAMA | String |  | Inscr. estab. Suframa |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0145 — EFD Contribuições Registro 0145
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| COD_INC_TRIB | Integer |  | Cód. indicador incid. trib. período | `1`=Contribuição Previdenciária apurada no período, exclusivamente com base na Receita Bruta `2`=Contribuição Previdenciária apurada no período, com base na Receita Bruta e nas Remunerações pagas |
| VL_REC_TOT | Float |  | Vlr. Rec. Bruta Total da PJ no Per. |  |
| VL_REC_ATIV | Float |  | Vlr. Rec. Bruta da(s) Ativ.(s) Suj.(s) à Contrib. Previd. |  |
| VL_REC_DEMAIS_ATIV | Float |  | Vlr. Rec. Bruta da(s) Ativ.(s) não Suj.(s) à Contrib. Previd. |  |
| INFO_COMPL | String |  | Info. complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0150 — EFD Contribuições Registro 0150
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. ident. part. no arquivo |  |
| NOME | String |  | Nome pessoal ou emp. part. |  |
| COD_PAIS | Integer |  | Cód. país part., conforme tab. indicada item 3.2.1 |  |
| CNPJ | String |  | CNPJ participante |  |
| CPF | String |  | CPF participante |  |
| IE | String |  | Inscr. Estad. part. |  |
| COD_MUN | Integer |  | Cód. munic. conforme tab. IBGE |  |
| SUFRAMA | String |  | Núm. inscr. part. Suframa |  |
| ENDE | String |  | Lograd. e Ender. imóvel |  |
| NUM | String |  | Núm. imóvel |  |
| COMPL | String |  | Dados compl. endereço |  |
| BAIRRO | String |  | Bairro do imóvel |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0190 — EFD Contribuições Registro 0190
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| UNID | String |  | Cód. un. de medida |  |
| DESCR | String |  | Descr. un. de medida |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0200 — EFD Contribuições Registro 0200
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. item |  |
| DESCR_ITEM | String |  | Descr. do item |  |
| COD_BARRA | String |  | Repr. alfan. cód. barra prod. |  |
| COD_ANT_ITEM | String |  | Cód. anterior item relação à última info. apresentada |  |
| UNID_INV | String |  | Un. medida utilizada quant. estoq. |  |
| TIPO_ITEM | String |  | Tipo do item | `99`=Outras `10`=Outros insumos `09`=Serviços `08`=Ativo Imobilizado `07`=Material de Uso e Consumo_(+7)_ |
| COD_NCM | String |  | Cód. Nomenc. Comum Mercosul |  |
| EX_IPI | String |  | Cód. EX, conforme a TIPI |  |
| COD_GEN | Integer |  | Cód. gên. item conforme tab. 4.2.1 |  |
| COD_LST | Integer |  | Cód. do serviço |  |
| ALIQ_ICMS | Float |  | Alíq. ICMS aplic. item oper. internas |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0205 — EFD Contribuições Registro 0205
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DESCR_ANT_ITEM | String |  | Descr. anterior do item |  |
| DT_INI | Date |  | Dt. ini. utilização descr. do item |  |
| DT_FIM | Date |  | Dt. fin. utilização descr. do item |  |
| COD_ANT_ITEM | String |  | Cód. ant. do item relação à última info. apresentada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| COD_ITEM | String |  | Cód. Item |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0206 — EFD Contribuições Registro 0206
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_COMB | String |  | Cód. combustível tabela ANP |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| COD_ITEM | String |  | Cód. Item |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0208 — EFD Contribuições Registro 0208
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_TAB | String |  | Cód. indicador Tab. de Incid. | `13`=Tabela XIII `12`=Tabela XII `11`=Tabela XI `10`=Tabela X `09`=Tabela IX_(+8)_ |
| COD_GRU | String |  | Cód. do grupo |  |
| MARCA_COM | String |  | Marca Comercial |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0400 — EFD Contribuições Registro 0400
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| COD_NAT | String |  | Cód. natureza operação/prestação |  |
| DESCR_NAT | String |  | Descr. natureza operação/prestação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0450 — EFD Contribuições Registro 0450
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| COD_INF | String |  | Cód. info. compl. doc. fiscal |  |
| TXT | String |  | Texto livre info. compl. exist. no doc. fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0500 — EFD Contribuições Registro 0500
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DT_ALT | Date |  | Dt. inclusão/alteração |  |
| COD_NAT_CC | String |  | Cód. nat. conta/grupo contas | `09`=Outras `05`=Contas de compensação `04`=Contas de resultado `03`=Patrimônio líquido `02`=Contas de passivo_(+1)_ |
| IND_CTA | String |  | Indicador tipo conta | `S`=Sintética (grupo de contas) `A`=Analítica (conta) |
| NIVEL | Integer |  | Nív. conta analítica/grupo contas |  |
| COD_CTA | String |  | Cód. conta analítica/grupo contas |  |
| NOME_CTA | String |  | Nome conta analítica/grupo contas |  |
| COD_CTA_REF | String |  | Cód. conta correl. Plano Contas Ref. |  |
| CNPJ_EST | String |  | CNPJ do estabelecimento |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0600 — EFD Contribuições Registro 0600
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| DT_ALT | Date |  | Dt. inclusão/alteração |  |
| COD_CCUS | String |  | Cód. centro de custos |  |
| CCUS | String |  | Nome centro de custos |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC0900 — EFD Contribuições Registro 0900
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| REC_TOTAL_BLOCO_A | Float |  | Receita Total Bloco A |  |
| REC_NRB_BLOCO_A | Float |  | Parcela da Receita Total Bloco A |  |
| REC_TOTAL_BLOCO_C | Float |  | Receita Total Bloco C |  |
| REC_NRB_BLOCO_C | Float |  | Parcela da Receita Total Bloco C |  |
| REC_TOTAL_BLOCO_D | Float |  | Receita Total Bloco D |  |
| REC_NRB_BLOCO_D | Float |  | Parcela da Receita Total Bloco D |  |
| REC_TOTAL_BLOCO_F | Float |  | Receita Total Bloco F |  |
| REC_NRB_BLOCO_F | Float |  | Parcela da Receita Total Bloco F |  |
| REC_TOTAL_BLOCO_I | Float |  | Receita Total Bloco I |  |
| REC_NRB_BLOCO_I | Float |  | Parcela da Receita Total Bloco I |  |
| REC_TOTAL_BLOCO_1 | Float |  | Receita Total Bloco 1 |  |
| REC_NRB_BLOCO_1 | Float |  | Parcela da Receita Total Bloco 1 |  |
| REC_TOTAL_PERIODO | Float |  | Receita Bruta Total |  |
| REC_TOTAL_NRB_PERIODO | Float |  | Parcela da Receita Total |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |
| CODSCP | Integer |  | Código SCP |  |

## TGFEFDC1001 — EFD Contribuições Registro 1001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de mov. | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_1 | Integer |  | Qtd. total linhas Bloco 1 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1010 — EFD Contribuições Registro 1010
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. Núm. Processo Jud. |  |
| ID_SEC_JUD | String |  | Ident. Seção Jud. |  |
| ID_VARA | String |  | Ident. Vara |  |
| IND_NAT_ACAO | String |  | Ind. Natureza Ação Jud. | `99`=99 - Outros `09`=09 - Decisão jud. oriunda de liminar em mandado de seg. coletivo `08`=08 - Súmula vinculante aprovada pelo STF ou STJ `07`=07 - Medida jud. em que a PJ não é o autor `06`=06 - Decisão jud. vinculada a depósito adm. ou jud. em montate integral_(+5)_ |
| DESC_DEC_JUD | String |  | Descr. Resum. Efeitos Trib. |  |
| DT_SENT_JUD | Date |  | Dt. Sentença/Decisão Jud. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1011 — EFD Contribuições Registro 1011
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| REG_REF | String |  | Registro da Escrituração |  |
| CHAVE_DOC | String |  | Chave do documento eletrônico |  |
| COD_PART | String |  | Código do Participante |  |
| COD_ITEM | String |  | Código do Item |  |
| DT_OPER | Date |  | Dt. da Operação |  |
| VL_OPER | Float |  | Vlr. da Operação/Item |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. a PIS |  |
| VL_BC_PIS | Float |  | Vlr. Base de Cálculo PIS |  |
| ALIQ_PIS | Float |  | Alíquota PIS |  |
| VL_PIS | Float |  | Vlr. PIS |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Vlr. Base de Cálculo COFINS |  |
| ALIQ_COFINS | Float |  | Alíquota COFINS |  |
| VL_COFINS | Float |  | Vlr. COFINS |  |
| CST_PIS_SUSP | String |  | Cód. Sit. Trib. ref. a PIS conforme dec. judicial |  |
| VL_BC_PIS_SUSP | Float |  | Vlr. Base de Cálculo PIS conforme dec. judicial |  |
| ALIQ_PIS_SUSP | Float |  | Alíquota PIS conforme dec. judicial |  |
| VL_PIS_SUSP | Float |  | Vlr. PIS conforme dec. judicial |  |
| CST_COFINS_SUSP | String |  | Cód. Sit. Trib. ref. a COFINS conforme dec. judicial |  |
| VL_BC_COFINS_SUSP | Float |  | Vlr. Base de Cálculo COFINS conforme dec. judicial |  |
| ALIQ_COFINS_SUSP | Float |  | Alíquota COFINS conforme dec. judicial |  |
| VL_COFINS_SUSP | Float |  | Vlr. COFINS conforme dec. judicial |  |
| COD_CTA | String |  | Cód. Conta Contábil debitada/creditada |  |
| COD_CCUS | String |  | Cód. Centro de Custos |  |
| DESC_DOC_OPER | String |  | Descrição do Documento/Operação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1020 — EFD Contribuições Registro 1020
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident.  Proc. Adm. ou da Decisão Adm. |  |
| IND_NAT_ACAO | String |  | Ind. Natureza da Ação | `99`=Outros `06`=Auto de Infração `05`=Decisão Administrativa de DRJ ou do CARF `04`=Ato Declaratório Interpretativo `03`=Ato Declaratório Executivo_(+2)_ |
| DT_DEC_ADM | Date |  | Dt. Despacho/Decisão Adm. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1100 — EFD Contribuições Registro 1100
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| PER_APU_CRED | Date |  | Período Apur. Créd. |  |
| ORIG_CRED | String |  | Ind. origem créd. | `02`=Crédito transferido por PJ sucedida `01`=Crédito decorrente de operações próprias |
| CNPJ_SUC | String |  | CNPJ da PJ cedente do créd. |  |
| COD_CRED | Integer |  | Cód. Tipo Créd. |  |
| VL_CRED_APU | Float |  | Vlr. total créd. apur. na EFD (Reg. M100) ou dem. DACON |  |
| VL_CRED_EXT_APU | Float |  | Vlr. Créd. Extemp. Apur. |  |
| VL_TOT_CRED_APU | Float |  | Vlr. Total Créd. Apur. |  |
| VL_CRED_DESC_PA_ANT | Float |  | Vlr. Créd. util. mediante Desconto |  |
| VL_CRED_PER_PA_ANT | Float |  | Vlr. Créd. util. med. Ped. Ressarcimento |  |
| VL_CRED_DCOMP_PA_ANT | Float |  | Vlr. Créd. util. med. Decl. Comp. Interm. |  |
| SD_CRED_DISP_EFD | Float |  | Saldo Créd. Disp. Utilização |  |
| VL_CRED_DESC_EFD | Float |  | Vlr. Créd. descontado |  |
| VL_CRED_PER_EFD | Float |  | Vlr. Créd. obj. Ped. Ressarc. |  |
| VL_CRED_DCOMP_EFD | Float |  | Vlr. do Créd. utilizado mediante Declaração de Comp. Interm. |  |
| VL_CRED_TRANS | Float |  | Vlr. créd. transf. evento cisão, fus ou incorp. |  |
| VL_CRED_OUT | Float |  | Vlr. créd. util. por outras formas |  |
| SLD_CRED_FIM | Float |  | Saldo créd. utilizar apur. futuro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1300 — EFD Contribuições Registro 1300
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| IND_NAT_RET | String |  | Indic. Natur. Ret. na Fonte | `99`=Outras Retenções - Rendimentos sujeitos à regra geral de incidência (não cumulativa ou cumulativa) `59`=Outras Retenções - Rendimentos sujeitos à regra específica de incidência cumulativa `55`=Retenção por Fabricante de Máquinas e Veículos `54`=Recolhimento por Sociedade Cooperativa `53`=Retenção por Pessoas Jurídicas de Direito Privado_(+7)_ |
| PR_REC_RET | Date |  | Período Receb. e da Retenção |  |
| VL_RET_APU | Float |  | Vlr. Total da Retenção |  |
| VL_RET_DED | Float |  | Vlr. Retenção ded. Contrib devida a escrituração |  |
| VL_RET_PER | Float |  | Vlr. Retenção util. med. Ped. Rest. |  |
| VL_RET_DCOMP | Float |  | Vlr. Retenção util. med. Decl. Comp. |  |
| SLD_RET | Float |  | Saldo Ret. util. em per. de apur. futuros |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1500 — EFD Contribuições Registro 1500
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| PER_APU_CRED | Date |  | Período Apur. Créd. |  |
| ORIG_CRED | String |  | Indicador origem créd. | `02`=Crédito transferido por pessoa jurídica sucedida `01`=Crédito decorrente de operações próprias |
| CNPJ_SUC | String |  | CNPJ da PJ cedente créd. |  |
| COD_CRED | Integer |  | Cód. Tipo Créd. |  |
| VL_CRED_APU | Float |  | Vlr. Total do créd. apurado EFD |  |
| VL_CRED_EXT_APU | Float |  | Vlr. Créd. Extemp. Apurado |  |
| VL_TOT_CRED_APU | Float |  | Vlr. Total Créd. Apurado |  |
| VL_CRED_DESC_PA_ANT | Float |  | Vlr. Créd. util. mediante Desconto |  |
| VL_CRED_PER_PA_ANT | Float |  | Vlr. mediante Ped. Ressarc. |  |
| VL_CRED_DCOMP_PA_ANT | Float |  | Vlr. Créd. util. med. Decl.  Comp. Interm. |  |
| SD_CRED_DISP_EFD | Float |  | Saldo Créd. Disponível para Utilização |  |
| VL_CRED_DESC_EFD | Float |  | Vlr. Créd. descontado |  |
| VL_CRED_PER_EFD | Float |  | Vlr. Créd. objeto Ped. Ressarc. |  |
| VL_CRED_DCOMP_EFD | Float |  | Vlr. Crédito util. med. Decl. Comp. Interm. |  |
| VL_CRED_TRANS | Float |  | Vlr. créd. transf. em evento de cisão, fusão ou incorp. |  |
| VL_CRED_OUT | Float |  | Vlr. créd. util. por out. formas |  |
| SLD_CRED_FIM | Float |  | Saldo créd. a utilizar per. de apur. fut. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1700 — EFD Contribuições Registro 1700
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| IND_NAT_RET | String |  | Ind. Natureza Retenção Fonte | `99`=Outras Retenções - Rendimentos sujeitos à regra geral de incidência (não cumulativa ou cumulativa) `59`=Outras Retenções - Rendimentos sujeitos à regra específica de incidência cumulativa `55`=Retenção por Fabricante de Máquinas e Veículos `54`=Recolhimento por Sociedade Cooperativa `53`=Retenção por Pessoas Jurídicas de Direito Privado_(+7)_ |
| PR_REC_RET | Date |  | Período Recebimento e da Retenção |  |
| VL_RET_APU | Float |  | Vlr. Total da Retenção |  |
| VL_RET_DED | Float |  | Vlr. Retenção deduzida da Contrib. |  |
| VL_RET_PER | Float |  | Vlr. Retenção util. med. Ped. Rest. |  |
| VL_RET_DCOMP | Float |  | Vlr. Retenção util. med. Decl. Comp. |  |
| SLD_RET | Float |  | Saldo Retenção a util. per. apur. fut. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC1900 — EFD Contribuições Registro 1900
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| CNPJ | String |  | CNPJ estab. PJ emit. doc. gerad. rec. |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `99`=Outros Documentos `98`=Nota Fiscal de Prestação de Serviços (ISSQN) |
| SER | String |  | Série do doc. fiscal |  |
| SUB_SER | String |  | Subserie do doc. fiscal |  |
| COD_SIT | String |  | Cód. situação doc. fiscal | `99`=Outros `02`=Documento cancelado `00`=Documento regular |
| VL_TOT_REC | Float |  | Vlr. total receita doc. emit. |  |
| QUANT_DOC | Integer |  | Qtd. total doc. emit. |  |
| CST_PIS | String |  | Cód. Situação Trib. PIS/Pasep |  |
| CST_COFINS | String |  | Cód. Situação Trib. Cofins |  |
| CFOP | Integer |  | Cód. fiscal operação e prestação |  |
| INF_COMPL | String |  | Infor. complementares |  |
| COD_CTA | String |  | Cód. conta analítica cont. repres. rec. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |
| CODSCP | Integer |  | Código SCP |  |

## TGFEFDC9001 — EFD Contribuições Registro 9001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Ind. de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_9 | Integer |  | Qtd. total linhas Bloco 9 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC9900 — EFD Contribuições Registro 9900
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| REG_BLC | String |  | Reg. totalizado próx. campo |  |
| QTD_REG_BLC | Integer |  | Total reg. tipo info. campo anterior |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDC9999 — EFD Contribuições Registro 9999
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| QTD_LIN | Integer |  | Qtd. total linhas arq. digital |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCA001 — EFD Contribuições Registro A001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Ind. de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_A | Integer |  | Qtd. total linhas Bloco A |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCA010 — EFD Contribuições Registro A010
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| CNPJ | String |  | Núm. inscr. estab. CNPJ |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCA100 — EFD Contribuições Registro A100
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Ind. tipo operação | `1`=Serviço Prestado pelo Estabelecimento `0`=Serviço Contratado pelo Estabelecimento |
| IND_EMIT | String |  | Ind. emit. doc. fiscal | `1`=Emissão de Terceiros `0`=Emissão Própria |
| COD_PART | String |  | Cód. participante |  |
| COD_SIT | String |  | Cód. situação doc. fiscal | `01`=Documento cancelado `00`=Documento regular |
| SER | String |  | Série doc. fiscal |  |
| SUB | String |  | Subsérie doc. fiscal |  |
| NUM_DOC | String |  | Núm. doc. fiscal ou doc. intern. equiv. |  |
| CHV_NFSE | String |  | Chave/Cód. Verificação NFSE |  |
| DT_DOC | Date |  | Dt. emissão doc. fiscal |  |
| DT_EXE_SERV | Date |  | Dt. Execução / Concl. Serviço |  |
| VL_DOC | Float |  | Vlr. total doc. |  |
| IND_PGTO | String |  | Ind. tipo pag. | `9`=Sem pagamento `1`=A prazo `0`=À vista |
| VL_DESC | Float |  | Vlr. total desconto |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. PIS/PASEP |  |
| VL_PIS | Float |  | Vlr. total PIS |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. COFINS |  |
| VL_COFINS | Float |  | Vlr. total COFINS |  |
| VL_PIS_RET | Float |  | Vlr. total PIS retido fonte |  |
| VL_COFINS_RET | Float |  | Vlr. total COFINS retido fonte |  |
| VL_ISS | Float |  | Vlr. ISS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CONFDESGRACARG | String |  | Confirmar desconto grande carga? | `S`=Sim `N`=Não |
| TEMVLRLIQITEM | String |  | Tem valor líquido no Item da NF-e? | `S`=Sim `N`=Não |
| VLRDESCSERV | Float |  | Total desc. serviços |  |
| VLRTOT | Float |  | Vlr. Total Itens |  |
| BASESUBST | Float |  | Base Substituição Total Itens |  |
| VLRRESIDUODESCONTO | Float |  | Vlr. Resíduo de Desconto |  |
| NATBCCRED | String |  | Cód. base cálc. créd. |  |
| DTMOV | Date |  | Dt. Movimento |  |
| NUMNOTA | Integer |  | Nro. da Nota |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCA110 — EFD Contribuições Registro A110
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_INF | String |  | Cód. info. compl. doc. fiscal |  |
| TXT_COMPL | String |  | Info. Compl. Doc. Fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODINF0450 | Integer |  | Cód. info. compl. doc. fiscal registro 0450 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCA111 — EFD Contribuições Registro A111
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Ind. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCA120 — EFD Contribuições Registro A120
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| VL_TOT_SERV | Float |  | Vlr. total serviço, prest. por PF ou PJ domic. no exterior |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. Op. – PIS/PASEP – Import. |  |
| VL_PIS_IMP | Float |  | Vlr. pag./recol. PIS/PASEP – Import. |  |
| DT_PAG_PIS | Date |  | Dt. pag. PIS/PASEP – Import. |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. Op. – COFINS – Import. |  |
| VL_COFINS_IMP | Float |  | Vlr. pag./recol. COFINS – Import. |  |
| DT_PAG_COFINS | Date |  | Dt. de pag. COFINS – Import. |  |
| LOC_EXE_SERV | String |  | Local exec. serv. | `1`=Executado no Exterior, cujo resultado se verifique no País `0`=Executado no País |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCA170 — EFD Contribuições Registro A170
Campos: 45

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQITEM | Integer |  | Sequência do Item |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Núm. seq. item doc. fiscal |  |
| COD_ITEM | String |  | Cód. item |  |
| DESCR_COMPL | String |  | Descr. compl. item adotado doc. fiscal |  |
| VL_ITEM | Float |  | Vlr. total item (merc. ou serv.) |  |
| VL_DESC | Float |  | Vlr. desc. com. / excl. base cálc. PIS/PASEP e COFINS |  |
| NAT_BC_CRED | String |  | Cód. base cálc. créd. |  |
| IND_ORIG_CRED | String |  | Ind. origem créd. | `1`=Operação de Importação `0`=Operação no Mercado Interno |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Vlr. base cálculo PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP |  |
| VL_PIS | Float |  | Vlr. PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. ao COFINS |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. do COFINS |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| COD_CCUS | String |  | Cód. centro de custos |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ESTRANGEIRO | String |  | Estrangeiro | `S`=Sim `N`=Não |
| NUPROCESSOPISRET | Integer |  | Nro. Único do Processo Pis Retido |  |
| SEQPROCESSOPISRET | Integer |  | Sequência do Processo Pis Retido |  |
| NUMPROCESSOPISRET | String |  | Nro. do Processo Pis Retido |  |
| INDORIGPROCPISRET | Integer |  | Indicador da Origem do Processo Pis Retido |  |
| NUPROCESSOCOFINSRET | Integer |  | Nro. Único do Processo Cofins Retido |  |
| SEQPROCESSOCOFINSRET | Integer |  | Sequência do Processo Cofins Retido |  |
| NUMPROCESSOCOFINSRET | String |  | Nro. do Processo Cofins Retido |  |
| INDORIGPROCCOFINSRET | Integer |  | Indicador da Origem do Processo Cofins Retido |  |
| NUPROCESSOPIS | Integer |  | Nro. Único do Processo Pis |  |
| SEQPROCESSOPIS | Integer |  | Sequência do Processo Pis |  |
| NUMPROCESSOPIS | String |  | Nro. do Processo Pis |  |
| INDORIGPROCPIS | Integer |  | Indicador da Origem do Processo Pis |  |
| NUPROCESSOCOFINS | Integer |  | Nro. Único do Processo Cofins Retido Cofins |  |
| SEQPROCESSOCOFINS | Integer |  | Sequência do Processo Cofins Retido Cofins |  |
| NUMPROCESSOCOFINS | String |  | Nro. do Processo Cofins Retido Cofins |  |
| INDORIGPROCCOFINS | Integer |  | Indicador da Origem do Processo Cofins Retido Cofins |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC001 — EFD Contribuições Registro C001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Ind. de movimento | `0`=Bloco com dados informados `1`=Bloco sem dados informados |
| QTD_LIN_C | Integer |  | Qtd. total linhas Bloco C |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC010 — EFD Contribuições Registro C010
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| CNPJ | String |  | Núm. inscri. estab. CNPJ |  |
| IND_ESCRI | String |  | Ind. apur. contrib. e créd. por NF-e e ECF | `2`=Apuração com base no registro individualizado de NF-e e de ECF `1`=Apuração com base nos registros de consolidação das operações por NF-e e por ECF |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC100 — EFD Contribuições Registro C100
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Ind. tipo operação | `1`=Saída `0`=Entrada |
| IND_EMIT | String |  | Ind. emitente doc. fiscal | `1`=Terceiros `0`=Emissão própria |
| COD_PART | String |  | Cód. participante |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `65`=65-Nota Fiscal Eletrônica para Consumidor Final `55`=55-Nota Fiscal Eletrônica `1B`=1B-Nota Fiscal Avulsa `04`=04-Nota Fiscal de Produtor `01`=01-Nota Fiscal |
| COD_SIT | String |  | Cód. situação doc. fiscal | `08`=Documento Fiscal emitido com base em Regime Especial ou Norma Específica `05`=NFe ou CT-e Numeração inutilizada `04`=NFe ou CT-e denegada `03`=Documento cancelado extemporâneo `02`=Documento cancelado_(+4)_ |
| SER | String |  | Série doc. fiscal |  |
| NUM_DOC | Integer |  | Núm. doc. fiscal |  |
| CHV_NFE | String |  | Chave NFE ou NFC-e |  |
| DT_DOC | Date |  | Dt. emissão do doc. fiscal |  |
| DT_E_S | Date |  | Dt. entrada ou saída |  |
| VL_DOC | Float |  | Vlr. total doc. fiscal |  |
| IND_PGTO | String |  | Indic. tipo pag. | `2`=Outros `1`=A prazo `0`=À vista |
| VL_DESC | Float |  | Vlr. total desconto |  |
| VL_ABAT_NT | Float |  | Abat. não trib. e não com. desc. ICMS |  |
| VL_MERC | Float |  | Vlr. total merc. e serviços |  |
| IND_FRT | String |  | Ind. tipo frete/transporte | `9`=Sem ocorrência de transporte `4`=Transporte próprio por conta do destinatário `2`=Frete por conta de terceiros `1`=Frete por conta do destinatário (FOB) `0`=Frete por conta do remetente (CIF)_(+1)_ |
| VL_FRT | Float |  | Vlr. frete ind. no doc. fiscal |  |
| VL_SEG | Float |  | Vlr. seguro ind. no doc. fiscal |  |
| VL_OUT_DA | Float |  | Vlr. outras desp. acessórias |  |
| VL_BC_ICMS | Float |  | Vlr. base cálc. do ICMS |  |
| VL_ICMS | Float |  | Vlr. do ICMS |  |
| VL_BC_ICMS_ST | Float |  | Vlr. base cálc. do ICMS subst. trib. |  |
| VL_ICMS_ST | Float |  | Vlr. ICMS retido por subst. trib. |  |
| VL_IPI | Float |  | Vlr. total do IPI |  |
| VL_PIS | Float |  | Vlr. total do PIS |  |
| VL_COFINS | Float |  | Vlr. total da COFINS |  |
| VL_PIS_ST | Float |  | Vlr. total PIS retido por subst. trib. |  |
| VL_COFINS_ST | Float |  | Vlr. total COFINS retido por subst. trib. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC110 — EFD Contribuições Registro C110
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_INF | String |  | Cód. info. compl. do doc. fiscal |  |
| TXT_COMPL | String |  | Descr. compl. do cód. de ref. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODINF0450 | Integer |  | Cód. info. compl. doc. fiscal registro 0450 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC111 — EFD Contribuições Registro C111
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Ind. origem do processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC120 — EFD Contribuições Registro C120
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_DOC_IMP | String |  | Doc. de importação | `2`=Declaração Única de Importação `1`=Declaração Simplificada de Importação `0`=Declaração de Importação |
| NUM_DOC_IMP | String |  | Núm. doc. de Importação |  |
| VL_PIS_IMP | Float |  | Vlr. pago de PIS na import. |  |
| VL_COFINS_IMP | Float |  | Vlr. pago de COFINS na import. |  |
| NUM_ACDRAW | String |  | Núm. Ato Conc. regime Drawback |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC170 — EFD Contribuições Registro C170
Campos: 48

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Núm. seq. item doc. fiscal |  |
| COD_ITEM | String |  | Cód. do item |  |
| DESCR_COMPL | String |  | Descr. compl. item adotado doc. fiscal |  |
| QTD | Float |  | Qtd. do item |  |
| UNID | String |  | Unid. do item |  |
| VL_ITEM | Float |  | Vlr. total do item |  |
| VL_DESC | Float |  | Vlr. desc. com. / excl. base cálc. PIS/PASEP e COFINS |  |
| IND_MOV | String |  | Mov. física Item/Produto | `1`=Não `0`=Sim |
| CST_ICMS | String |  | Cód. Sit. Trib. ref. ao ICMS |  |
| CFOP | Integer |  | Cód. Fiscal Oper. e Prestação |  |
| COD_NAT | String |  | Cód. natureza operação |  |
| VL_BC_ICMS | Float |  | Vlr. base cálc. do ICMS |  |
| ALIQ_ICMS | Float |  | Alíq. do ICMS |  |
| VL_ICMS | Float |  | Vlr. ICMS cred./deb. |  |
| VL_BC_ICMS_ST | Float |  | Vlr. base cálc. ref. à subst. trib. |  |
| ALIQ_ST | Float |  | Alíq. ICMS subst. trib. na unid. da fed. dest. |  |
| VL_ICMS_ST | Float |  | Vlr. ICMS ref. à subst. trib. |  |
| IND_APUR | String |  | Ind. período apur. do IPI | `1`=Decendial `0`=Mensal |
| CST_IPI | String |  | Cód. Sit. Trib. ref. ao IPI |  |
| COD_ENQ | String |  | Cód. enquadr. legal do IPI |  |
| VL_BC_IPI | Float |  | Vlr. base cálc. do IPI |  |
| ALIQ_IPI | Float |  | Alíq. do IPI |  |
| VL_IPI | Float |  | Vlr. IPI cred./deb. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS |  |
| QUANT_BC_PIS | Float |  | Qtd. – Base cálc. PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. ao COFINS |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| QUANT_BC_COFINS | Float |  | Qtd. – Base cálc. COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| UNIDPORPARCEIRO | String |  | Unididade por Parceiro |  |
| CODTIPOPER | Integer |  | Cód. Tipo de Operação |  |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC175 — EFD Contribuições Registro C175
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CFOP | Integer |  | Cód. Fiscal Operação e Prestação |  |
| VL_OPR | Float |  | Vlr. da oper. na comb. de CFOP, CST e alíq. |  |
| VL_DESC | Float |  | Vlr. desconto com. / excl. base cálc. do PIS/PASEP e da COFINS |  |
| CST_PIS | String |  | Cód. da Situação Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP (em valor) |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| QUANT_BC_PIS | Float |  | Base cálc. PIS/PASEP (em quantidade) |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. do PIS (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. da Situação Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| ORDEM | Integer |  | Ordem |  |
| QUANT_BC_COFINS | Float |  | Base cálc. COFINS (em quantidade) |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. da COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. da conta an. contábil deb./cred. |  |
| INFO_COMPL | String |  | Info. Complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC180 — EFD Contribuições Registro C180
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Modelo do Documento | `65`=65-Nota Fiscal Eletrônica de Venda a Consumidor `55`=55-Nota Fiscal Eletrônica |
| DT_DOC_INI | Date |  | Dt. de Emissão Ini. dos Doc. |  |
| DT_DOC_FIN | Date |  | Dt. de Emissão Final dos Doc. |  |
| COD_ITEM | String |  | Cód. do Item |  |
| COD_NCM | String |  | Cód. da NCM |  |
| EX_IPI | String |  | Cód. EX, conf. a TIPI |  |
| VL_TOT_ITEM | Float |  | Vlr. Total do Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC181 — EFD Contribuições Registro C181
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| VL_ITEM | Float |  | Vlr. do item |  |
| VL_DESC | Float |  | Vlr. do desc. com. / excl. base cálc. |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| QUANT_BC_PIS | Float |  | Qtd. – Base cálc. PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. PIS/PASEP |  |
| COD_CTA | String |  | Cód. da conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC185 — EFD Contribuições Registro C185
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| VL_ITEM | Float |  | Vlr. do item |  |
| VL_DESC | Float |  | Vlr. do desc. com. / excl. base de cálc. |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| QUANT_BC_COFINS | Float |  | Qtd. – Base cálc. da COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. da conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC188 — EFD Contribuições Registro C188
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Ind. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC190 — EFD Contribuições Registro C190
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Modelo do Documento | `55`=55-Nota Fiscal Eletrônica |
| DT_REF_INI | Date |  | Dt. Ini. Ref. Consolidação |  |
| DT_REF_FIN | Date |  | Dt. Final Ref. Consolidação |  |
| COD_ITEM | String |  | Cód. do item |  |
| COD_NCM | String |  | Cód. da NCM |  |
| EX_IPI | String |  | Cód. EX, conf. a TIPI |  |
| VL_TOT_ITEM | Float |  | Vlr. Total do Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC191 — EFD Contribuições Registro C191
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| CNPJ_CPF_PART | String |  | CNPJ/CPF do Participante |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| VL_ITEM | Float |  | Vlr. do item |  |
| VL_DESC | Float |  | Vlr. desconto Com. / Excl. |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| QUANT_BC_PIS | Float |  | Qtd. – Base cálc. PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC195 — EFD Contribuições Registro C195
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| CNPJ_CPF_PART | String |  | CNPJ/CPF do Participante |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| VL_ITEM | Float |  | Vlr. do item |  |
| VL_DESC | Float |  | Vlr. desconto Com. / Exclusão |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| QUANT_BC_COFINS | Float |  | Qtd. – Base cálc. da COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an.cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC198 — EFD Contribuições Registro C198
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. do processo ou ato concessório |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC199 — EFD Contribuições Registro C199
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODPROD | Integer |  | Produto |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_DOC_IMP | String |  | Doc. de importação | `2`=Declaração Única de Importação `1`=Declaração Simplificada de Importação `0`=Declaração de Importação |
| NUM_DOC_IMP | String |  | Núm. doc. Importação |  |
| VL_PIS_IMP | Float |  | Vlr. pago PIS na importação |  |
| VL_COFINS_IMP | Float |  | Vlr. pago COFINS na importação |  |
| NUM_ACDRAW | String |  | Núm. Ato Conc. regime Drawback |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC380 — EFD Contribuições Registro C380
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `02`=02-Nota Fiscal de Venda a Consumidor |
| DT_DOC_INI | Date |  | Dt. Emissão Ini. dos Doc. |  |
| DT_DOC_FIN | Date |  | Dt. Emissão Final dos Doc. |  |
| NUM_DOC_INI | Integer |  | Núm. doc. fiscal inicial |  |
| NUM_DOC_FIN | Integer |  | Núm. doc. fiscal final |  |
| VL_DOC | Float |  | Vlr. total doc. emitidos |  |
| VL_DOC_CANC | Float |  | Vlr. total doc. cancelados |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC381 — EFD Contribuições Registro C381
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `02`=02-Nota Fiscal de Venda a Consumidor |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. PIS/PASEP |  |
| COD_ITEM | String |  | Cód. do item |  |
| VL_ITEM | Float |  | Vlr. total itens |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| QUANT_BC_PIS | Float |  | Qtd. – Base cálc. do PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC385 — EFD Contribuições Registro C385
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `02`=Nota Fiscal de Venda a Consumidor |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| COD_ITEM | String |  | Cód. do item |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| QUANT_BC_COFINS | Float |  | Qtd. – Base cálc. da COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. da COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC395 — EFD Contribuições Registro C395
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `25`=25-Manifesto de Carga `24`=24-Autorização de Carregamento de Transporte `23`=23-GNRE `22`=22-Nota Fiscal de Serviço de Telecomunicações `21`=21-Nota Fiscal de Serviço de Comunicação_(+30)_ |
| COD_PART | String |  | Cód. participante emit. do doc. |  |
| SER | String |  | Série doc. fiscal |  |
| SUB_SER | String |  | Subsérie doc. fiscal |  |
| NUM_DOC | String |  | Núm. doc. fiscal |  |
| DT_DOC | Date |  | Dt. emissão doc. fiscal |  |
| VL_DOC | Float |  | Vlr. total doc. fiscal |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC396 — EFD Contribuições Registro C396
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQUENCIA | Integer |  | Sequência do Item |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. do item |  |
| VL_ITEM | Float |  | Vlr. total do item |  |
| VL_DESC | Float |  | Vlr. desconto com. do item |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. do Créd. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. créd. de PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. créd. de PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. créd. de COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. créd. de COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC400 — EFD Contribuições Registro C400
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODMAQ | Integer |  | Cód. da Máquina |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `2D`=2D-Cupom Fiscal emitido por ECF |
| ECF_MOD | String |  | Mod. do equip. |  |
| ECF_FAB | String |  | Núm. série fabric. do ECF |  |
| ECF_CX | Integer |  | Núm. caixa atrib. ao ECF |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC405 — EFD Contribuições Registro C405
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODMAQ | Integer |  | Cód. da Máquina |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DT_DOC | Date |  | Dt. mov. ref. a Redução Z |  |
| CRO | Integer |  | Posição Cont. Reinício Oper. |  |
| CRZ | Integer |  | Posição Cont. de Redução Z |  |
| NUM_COO_FIN | Integer |  | Núm. COO últ. doc. emit. no dia |  |
| GT_FIN | Float |  | Vlr. Grande Total final |  |
| VL_BRT | Float |  | Vlr. venda bruta |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC481 — EFD Contribuições Registro C481
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODMAQ | Integer |  | Cód. da Máquina |  |
| SEQC405 | Integer |  | Sequência C405 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| QUANT_BC_PIS | Float |  | Qtd. – Base cálc. PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_ITEM | String |  | Cód. do item |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC485 — EFD Contribuições Registro C485
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODMAQ | Integer |  | Cód. da Máquina |  |
| SEQC405 | Integer |  | Sequência C405 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_ITEM_F | Float |  | Vlr. total dos itens |  |
| VL_BC_COFINS_F | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| QUANT_BC_COFINS | Float |  | Qtd. – Base cálc. da COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_ITEM | String |  | Cód. do item |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC489 — EFD Contribuições Registro C489
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODMAQ | Integer |  | Cód. da Máquina |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Ind. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC490 — EFD Contribuições Registro C490
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| DT_DOC_INI | Date |  | Dt. Emissão Inicial dos Doc. |  |
| DT_DOC_FIN | Date |  | Dt. Emissão Final dos Doc. |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `59`=59-Cupom Fiscal Eletrônico `2D`=2D-Cupom Fiscal emitido por ECF `02`=02-Nota Fiscal de Venda a Consumidor |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC491 — EFD Contribuições Registro C491
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `59`=59-Cupom Fiscal Eletrônico `2D`=2D-Cupom Fiscal emitido por ECF `02`=02-Nota Fiscal de Venda a Consumidor |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. do item |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| CFOP | Integer |  | Cód. Fiscal Oper. e Prestação |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| QUANT_BC_PIS | Float |  | Qtd. – Base cálc. PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC495 — EFD Contribuições Registro C495
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `59`=59-Cupom Fiscal Eletrônico `2D`=2D-Cupom Fiscal emitido por ECF `02`=02-Nota Fiscal de Venda a Consumidor |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. do item |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| QUANT_BC_COFINS | Float |  | Qtd. – Base cálc. da COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC499 — EFD Contribuições Registro C499
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `59`=59-Cupom Fiscal Eletrônico `2D`=2D-Cupom Fiscal emitido por ECF `02`=02-Nota Fiscal de Venda a Consumidor |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Indic. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC500 — EFD Contribuições Registro C500
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. do participante do fornec. |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `55`=55-Nota Fiscal Eletrônica `29`=29-Nota Fiscal/Conta De Fornecimento D'água Canalizada `28`=28-Nota Fiscal/Conta de Fornecimento de Gás Canalizado `06`=06-Nota Fiscal Conta de Energia Elétrica |
| COD_SIT | String |  | Cód. situação doc. fiscal | `08`=Documento Fiscal emitido com base em Regime Especial ou Norma Específica `07`=Documento Fiscal Complementar extemporâneo `06`=Documento Fiscal Complementar `03`=Documento cancelado extemporâneo `02`=Documento cancelado_(+2)_ |
| SER | String |  | Série doc. fiscal |  |
| SUB | Integer |  | Subsérie doc. fiscal |  |
| NUM_DOC | Integer |  | Núm. doc. fiscal |  |
| DT_DOC | Date |  | Dt. emissão doc. fiscal |  |
| DT_ENT | Date |  | Dt. da entrada |  |
| VL_DOC | Float |  | Vlr. total doc. fiscal |  |
| VL_ICMS | Float |  | Vlr. acum. do ICMS |  |
| COD_INF | String |  | Cód. info. compl. doc. fiscal |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| CHV_DOCE | String |  | Chave do Doc. Fiscal Eletrônico |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODINF0450 | Integer |  | Cód. info. compl. doc. fiscal registro 0450 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC501 — EFD Contribuições Registro C501
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. Créd. |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC505 — EFD Contribuições Registro C505
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. Crédito |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC509 — EFD Contribuições Registro C509
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. do processo ou ato concessório |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC600 — EFD Contribuições Registro C600
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `55`=55-Nota Fiscal Eletrônica `29`=29-Nota Fiscal/Conta De Fornecimento D'água Canalizada `28`=28-Nota Fiscal/Conta de Fornecimento de Gás Canalizado `06`=06-Nota Fiscal Conta de Energia Elétrica `01`=01-Nota Fiscal |
| COD_MUN | Integer |  | Cód. munic. pontos consumo |  |
| SER | String |  | Série doc. fiscal |  |
| SUB | Integer |  | Subsérie doc. fiscal |  |
| COD_CONS | Integer |  | Cód. classe cons. en. elétr. |  |
| QTD_CONS | Integer |  | Qtd. doc. consol. registro |  |
| QTD_CANC | Integer |  | Qtd. doc. cancel. |  |
| DT_DOC | Date |  | Dt. doc. consolidados |  |
| VL_DOC | Float |  | Vlr. total doc. |  |
| VL_DESC | Float |  | Vlr. acumulado descontos |  |
| CONS | Integer |  | Cons. total acum. kWh |  |
| VL_FORN | Float |  | Vlr. acum. fornecimento |  |
| VL_SERV_NT | Float |  | Vlr. acum. serv. não-trib. pelo ICMS |  |
| VL_TERC | Float |  | Vlr.s cobr.  em nome de terc. |  |
| VL_DA | Float |  | Vlr. acum. desp. acessórias |  |
| VL_BC_ICMS | Float |  | Vlr. acum. base cálc. do ICMS |  |
| VL_ICMS | Float |  | Vlr. acum. do ICMS |  |
| VL_BC_ICMS_ST | Float |  | Vlr. acum. base cálc. ICMS subs. trib. |  |
| VL_ICMS_ST | Float |  | Vlr. acum. ICMS retido por subs. trib. |  |
| VL_PIS | Float |  | Vlr. acum. do PIS/PASEP |  |
| VL_COFINS | Float |  | Vlr. acum. da COFINS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC601 — EFD Contribuições Registro C601
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQC600 | Integer |  | Sequência C600 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC605 — EFD Contribuições Registro C605
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQC600 | Integer |  | Sequência C600 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC609 — EFD Contribuições Registro C609
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQC600 | Integer |  | Sequência C600 |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Indic. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC860 — EFD Contribuições Registro C860
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `59`=59-Cupom Fiscal Eletrônico |
| NR_SAT | Integer |  | Núm. Série do equip. SAT |  |
| DT_DOC | Date |  | Dt. emissão doc. fiscais |  |
| DOC_INI | Integer |  | Núm. doc. inicial |  |
| DOC_FIM | Integer |  | Núm. doc. final |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCC870 — EFD Contribuições Registro C870
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cód. produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. do item |  |
| CFOP | Integer |  | Cód. Fiscal de Oper. Prestação |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_DESC | Float |  | Vlr. da excl./desc. com. dos itens |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD001 — EFD Contribuições Registro D001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Ind. de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_D | Integer |  | Qtd. total linhas Bloco D |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD010 — EFD Contribuições Registro D010
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| CNPJ | String |  | Núm. inscr. estab. no CNPJ |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD100 — EFD Contribuições Registro D100
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Ind. tipo operação | `0`=Aquisição |
| IND_EMIT | String |  | Indic. emitente doc. fiscal | `1`=Emissão por Terceiros `0`=Emissão Própria |
| COD_PART | String |  | Cód. do participante |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `8B`=8B-Conhecimento de Transporte de Cargas Avulso `67`=67-Conhecimento de Transporte Eletrônico para Outros Serviços `63`=63-Bilhete de Passagem Eletrônico `57`=57-Conhecimento Transporte Rodoviário Eletrônico `27`=27-Nota Fiscal De Transporte Ferroviário De Carga_(+6)_ |
| COD_SIT | String |  | Cód. sit. doc. fiscal | `08`=Documento Fiscal emitido com base em Regime Especial ou Norma Específica `07`=Documento Fiscal Complementar extemporâneo `06`=Documento Fiscal Complementar `03`=Documento cancelado extemporâneo `02`=Documento cancelado_(+2)_ |
| SER | String |  | Série doc. fiscal |  |
| SUB | String |  | Subsérie doc. fiscal |  |
| NUM_DOC | Integer |  | Núm. doc. fiscal |  |
| CHV_CTE | String |  | Chave do CTE |  |
| DT_DOC | Date |  | Dt. ref./emis. dos doc. fiscais |  |
| DT_A_P | Date |  | Dt. aquis. ou prest. do serv. |  |
| TP_CTE | Integer |  | Tipo de CT-e |  |
| CHV_CTE_REF | String |  | Chv. CT-e ref. Vlr.s complementados. |  |
| VL_DOC | Float |  | Vlr. total do doc. fiscal |  |
| VL_DESC | Float |  | Vlr. total desconto |  |
| IND_FRT | String |  | Indic. do tipo do frete | `9`=Sem cobrança de frete `2`=Por conta de terceiros `1`=Por conta do destinatário/remetente `0`=Por conta do emitente |
| VL_SERV | Float |  | Vlr. total prestação serviço |  |
| VL_BC_ICMS | Float |  | Vlr. base cálc. do ICMS |  |
| VL_ICMS | Float |  | Vlr. do ICMS |  |
| VL_NT | Float |  | Vlr. não-trib. do ICMS |  |
| COD_INF | String |  | Cód. info. compl. doc. |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODINF0450 | Integer |  | Cód. info. compl. doc. fiscal registro 0450 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD101 — EFD Contribuições Registro D101
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_NAT_FRT | String |  | Indic. Natureza do Frete Contr. | `9`=Outras `5`=Transferência de produtos em elaboração entre estabelecimentos da pessoa jurídica `4`=Transferência de produtos acabados entre estabelecimentos da pessoa jurídica `3`=Operações de compras (bens para revenda, matérias-prima e outros produtos, não geradores de crédito) `2`=Operações de compras (bens para revenda, matérias-prima e outros produtos, geradores de crédito)_(+2)_ |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. do Créd. |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD105 — EFD Contribuições Registro D105
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_NAT_FRT | String |  | Indic. Natureza Frete Contr. | `9`=Outras `5`=Transferência de produtos em elaboração entre estabelecimentos da pessoa jurídica `4`=Transferência de produtos acabados entre estabelecimentos da pessoa jurídica `3`=Operações de compras (bens para revenda, matérias-prima e outros produtos, não geradores de crédito) `2`=Operações de compras (bens para revenda, matérias-prima e outros produtos, geradores de crédito)_(+2)_ |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| NAT_BC_CRED | String |  | Cód. base Cálc. Créd. |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD111 — EFD Contribuições Registro D111
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório. |  |
| IND_PROC | String |  | Ind. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD200 — EFD Contribuições Registro D200
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `57`=57-Conhecimento Transporte Rodoviário Eletrônico `27`=27-Nota Fiscal De Transporte Ferroviário De Carga `26`=26-Conhecimento de Transporte Multimodal de Cargas `11`=11-Conhecimento de Transporte Ferroviário de Cargas `10`=10-Conhecimento Aéreo_(+6)_ |
| COD_SIT | String |  | Cód. sit. doc. fiscal | `08`=Documento Fiscal emitido com base em Regime Especial ou Norma Específica `07`=Documento Fiscal Complementar extemporâneo `06`=Documento Fiscal Complementar `01`=Documento regular extemporâneo `00`=Documento regular |
| SER | String |  | Série doc. fiscal |  |
| SUB | String |  | Subsérie doc. fiscal |  |
| NUM_DOC_INI | Integer |  | Núm. doc. fiscal ini. emitido |  |
| NUM_DOC_FIN | Integer |  | Núm. doc. fiscal fin. emitido |  |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| DT_REF | Date |  | Dt. dia ref. do resumo diário |  |
| VL_DOC | Float |  | Vlr. total doc. fiscais |  |
| VL_DESC | Float |  | Vlr. total descontos |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD201 — EFD Contribuições Registro D201
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD205 — EFD Contribuições Registro D205
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_ITEM | Float |  | Vlr. total dos itens |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD209 — EFD Contribuições Registro D209
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Indic. origem processo | `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal `9`=Outros |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD500 — EFD Contribuições Registro D500
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Ind. tipo operação | `0`=Aquisição |
| IND_EMIT | String |  | Ind. emitente doc. fiscal | `0`=Emissão própria `1`=Terceiros |
| COD_PART | String |  | Cód. part. prestador do serviço |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `22`=22-Nota Fiscal de Serviço de Telecomunicações `21`=21-Nota Fiscal de Serviço de Comunicação `62`=62-Nota Fiscal Eletrônica de Serviços de Comunicação |
| COD_SIT | String |  | Cód. situação doc. fiscal | `08`=Documento Fiscal emitido com base em Regime Especial ou Norma Específica `07`=Documento Fiscal Complementar extemporâneo `06`=Documento Fiscal Complementar `03`=Documento cancelado extemporâneo `01`=Documento regular extemporâneo_(+2)_ |
| SER | String |  | Série doc. fiscal |  |
| SUB | Integer |  | Subsérie doc. fiscal |  |
| NUM_DOC | Integer |  | Núm. doc. fiscal |  |
| DT_DOC | Date |  | Dt. emissão doc. fiscal |  |
| DT_A_P | Date |  | Dt. entrada (aquisição) |  |
| VL_DOC | Float |  | Vlr. total doc. fiscal |  |
| VL_DESC | Float |  | Vlr. total desconto |  |
| VL_SERV | Float |  | Vlr. prestação serviços |  |
| VL_SERV_NT | Float |  | Vlr. total serv. não-trib. pelo ICMS |  |
| VL_TERC | Float |  | Vlr.s cobr. em nome de terc. |  |
| VL_DA | Float |  | Vlr. outras desp. indic. doc. fiscal |  |
| VL_BC_ICMS | Float |  | Vlr. base cálc. do ICMS |  |
| VL_ICMS | Float |  | Vlr. do ICMS |  |
| COD_INF | String |  | Cód. info. complementar |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| CHV_DOCE | String |  | Chave do Documento Fiscal Eletrônico |  |
| ORDEM | Integer |  | Ordem |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODINF0450 | Integer |  | Cód. info. compl. doc. fiscal registro 0450 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD501 — EFD Contribuições Registro D501
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_ITEM | Float |  | Vlr. Total Itens (Serviços) |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. Crédito |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD505 — EFD Contribuições Registro D505
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| REGISTRO | String |  | Registro |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_ITEM | Float |  | Vlr. Total Itens |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. Crédito |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD509 — EFD Contribuições Registro D509
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório. |  |
| IND_PROC | String |  | Ind. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD600 — EFD Contribuições Registro D600
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `22`=22-Nota Fiscal de Serviço de Telecomunicações `21`=21-Nota Fiscal de Serviço de Comunicação `62`=62-Nota Fiscal Eletrônica de Serviços de Comunicação |
| COD_MUN | Integer |  | Cód. munic. term. faturados |  |
| SER | String |  | Série doc. fiscal |  |
| SUB | Integer |  | Subsérie doc. fiscal |  |
| IND_REC | Integer |  | Indic. tipo receita | `9`=Outras receitas `8`=Outras receitas de terceiros `7`=Outras receitas próprias de natureza não-cumulativa `6`=Receita própria – serviços a faturar em período futuro `5`=Receita própria - co-faturamento_(+5)_ |
| QTD_CONS | Integer |  | Qtd. doc. consolidados reg. |  |
| DT_DOC_INI | Date |  | Dt. Inicial doc. consol. no per. |  |
| DT_DOC_FIN | Date |  | Dt. Final doc. consol. no per. |  |
| VL_DOC | Float |  | Vlr. total acum. doc. fiscais |  |
| VL_DESC | Float |  | Vlr. acumulado descontos |  |
| VL_SERV | Float |  | Vlr. acum. prest. serv. trib. ICMS |  |
| VL_SERV_NT | Float |  | Vlr. acum. serv. não-trib. ICMS |  |
| VL_TERC | Float |  | Vlr.s cobr. em nome de terc. |  |
| VL_DA | Float |  | Vlr. acum. desp. acessórias |  |
| VL_BC_ICMS | Float |  | Vlr. acum. base cálc. ICMS |  |
| VL_ICMS | Float |  | Vlr. acum. ICMS |  |
| VL_PIS | Float |  | Vlr. PIS/PASEP |  |
| VL_COFINS | Float |  | Vlr. COFINS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD601 — EFD Contribuições Registro D601
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_CLASS | Integer |  | Cód. classif. item serv. comunic. ou telecom. |  |
| VL_ITEM | Float |  | Vlr. acum. do item |  |
| VL_DESC | Float |  | Vlr. acum. desc./excl. base cálc. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. PIS/PASEP |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| COD_CTA | String |  | Cód. conta cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCD605 — EFD Contribuições Registro D605
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_CLASS | Integer |  | Cód. classif. item serv. comunic. ou telecom. |  |
| VL_ITEM | Float |  | Vlr. acum. do item |  |
| VL_DESC | Float |  | Vlr. acum. desc./excl. base cálc. |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_CTA | String |  | Cód. conta cont. deb./cred. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF001 — EFD Contribuições Registro F001
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Ind. movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_F | Integer |  | Qtd. total linhas Bloco F |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| OST_SEMDADOS | String |  | Ostensiva sem dados | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF010 — EFD Contribuições Registro F010
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| CNPJ | String |  | Núm. inscr. estab. no CNPJ |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF100 — EFD Contribuições Registro F100
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador Tipo Operação | `2`=Operação Representativa de Receita Auferida Não Sujeita... (CST 04, 06, 07, 08, 09, 49 ou 99) `1`=Operação Representativa de Receita Auferida... (CST 01, 02, 03 ou 05) `0`=Operação Representativa de Aquisição, Custos, Despesa ou Encargos, ou Receitas... (CST 50 a 66) |
| COD_PART | String |  | Cód. participante |  |
| COD_ITEM | String |  | Cód. item |  |
| DT_OPER | Date |  | Dt. Operação |  |
| VL_OPER | Float |  | Vlr. Operação/Item |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Base cálc. PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. dos Créditos |  |
| IND_ORIG_CRED | String |  | Indic. origem crédito | `1`=Operação de Importação `0`=Operação no Mercado Interno |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| COD_CCUS | String |  | Cód. Centro de Custos |  |
| DESC_DOC_OPER | String |  | Descr. do Doc./Oper. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF111 — EFD Contribuições Registro F111
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório. |  |
| IND_PROC | String |  | Ind. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF120 — EFD Contribuições Registro F120
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NAT_BC_CRED | String |  | Cód. Base Cálc. do Créd. Bens. Inc. ao Atv. Imob. | `09`=Crédito com Base nos Encargos de Depreciação `11`=Crédito com Base nos Encargos de Amortização |
| IDENT_BEM_IMOB | String |  | Ident. Bens/Grupo de Bens Inc. ao Atv. Imob. | `05`=Equipamentos `99`=Outros `06`=Veículos `04`=Máquinas `03`=Instalações_(+2)_ |
| IND_ORIG_CRED | String |  | Ind. orig. do bem inc. ao atv. imob. ger. créd. | `0`=Aquisição no Mercado Interno `1`=Aquisição no Mercado Externo |
| IND_UTIL_BEM_IMOB | Integer |  | Indic. da Util. dos Bens Inc. ao Atv. Imob. | `9`=Outros `3`=Locação a Terceiros `2`=Prestação de Serviços `1`=Produção de Bens Destinados a Venda |
| VL_OPER_DEP | Float |  | Vlr. do Encargo Depr./Amort. Incorrido Per. |  |
| PARC_OPER_NAO_BC_CRED | Float |  | Parcela do Vlr. do Enc. Deprec./Amort.a excl. da base cálc. Créd. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Base Cálc. Créd. de PIS/PASEP no per. |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do Créd. de PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Base Cálc. Créd. da COFINS no per. |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS |  |
| VL_COFINS | Float |  | Vlr. créd. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| COD_CCUS | String |  | Cód. Centro de Custos |  |
| DESC_BEM_IMOB | String |  | Descr. compl. bem ou grupo de bens com créd. apur. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF129 — EFD Contribuições Registro F129
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Ind. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF130 — EFD Contribuições Registro F130
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NAT_BC_CRED | String |  | Modelo do Documento | `10`=10-Conhecimento Aéreo |
| IDENT_BEM_IMOB | String |  | Ident. dos bens ou grupo de bens inc. ao Atv. Imob. | `99`=Outros bens incorporados ao Ativo Imobilizado `06`=Veículos `05`=Equipamentos `04`=Máquinas `03`=Instalações_(+1)_ |
| IND_ORIG_CRED | String |  | Ind. origem do bem inc. ao atv. imob. ger. créd. | `1`=Aquisição no Mercado Externo (Importação) `0`=Aquisição no Mercado Interno |
| IND_UTIL_BEM_IMOB | Integer |  | Ind. da Util. dos Bens Inc. ao Atv. Imob. | `9`=Outros `3`=Locação a Terceiros `2`=Prestação de Serviços `1`=Produção de Bens Destinados a Venda |
| MES_OPER_AQUIS | Date |  | Mês/Ano de Aquis. dos Bens Inc. ao Atv. Imob. |  |
| VL_OPER_AQUIS | Float |  | Vlr. Aquis. dos Bens Inc. ao Atv. Imob. |  |
| PARC_OPER_NAO_BC_CRED | Float |  | Parc. Vlr. Aquis. a excl. da base cálc. créd. |  |
| VL_BC_CRED | Float |  | Valor da Base Cálc. Créd. sobre Bens Inc. ao Atv. Imob. |  |
| IND_NR_PARC | Integer |  | Ind. Núm. Parc. a serem apropriadas | `9`=Outra periodicidade definida em Lei `5`=6 Meses (Embalagens de bebidas frias) `4`=48 Meses `3`=24 Meses `2`=12 Meses_(+1)_ |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Base cálc. Mensal Créd. de PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP |  |
| VL_PIS | Float |  | Vlr. Créd. de PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Base Cálc. Mensal Créd. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS |  |
| VL_COFINS | Float |  | Vlr. créd. da COFINS |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| COD_CCUS | String |  | Cód. Centro de Custos |  |
| DESC_BEM_IMOB | String |  | Descr. compl. do bem ou grupo de bens com créd. apur. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF139 — EFD Contribuições Registro F139
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. proc. ou ato concessório |  |
| IND_PROC | String |  | Indic. origem processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF200 — EFD Contribuições Registro F200
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Ind. Tipo da Operação | `05`=Outras `04`=Venda a Prazo de Unidade em Construção `02`=Venda a Prazo de Unidade Concluída `01`=Venda a Vista de Unidade Concluída `03`=Venda a Vista de Unidade em Construção |
| UNID_IMOB | String |  | Indic. tipo unid. imob. Vendida | `05`=Prédio construído/em construção para venda `04`=Unidade resultante de incorporação imobiliária `03`=Lote oriundo de desmembramento de terreno `02`=Terreno decorrente de loteamento `01`=Terreno adquirido para venda_(+1)_ |
| IDENT_EMP | String |  | Ident./Nome do Empreend. |  |
| DESC_UNID_IMOB | String |  | Descr. resumida unid. imob. vendida |  |
| NUM_CONT | String |  | Núm. Contr./Doc. formaliza Venda Unid. Imob. |  |
| CPF_CNPJ_ADQU | String |  | Ident. da PF (CPF) ou PJ (CNPJ) adquir. da unid. imobi. |  |
| DT_OPER | Date |  | Dt. oper. venda unid. imob. |  |
| VL_TOT_VEND | Float |  | Vlr. total unid. imob. vend. atualizada até per. escrit. |  |
| VL_REC_ACUM | Float |  | Vlr. receb. acum. até mês anterior da escrit. |  |
| VL_TOT_REC | Float |  | Vlr. total receb. mês da escrit. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_BC_PIS | Float |  | Base Cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_COFINS | Float |  | Base Cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| PERC_REC_RECEB | Float |  | Perc. rec. total recebida até o mês, da unid. imob. vend. |  |
| IND_NAT_EMP | Integer |  | Ind. Natureza Espec. Empreend. | `3`=Incorporação em Condomínio `2`=SCP `1`=Consórcio `4`=Outras |
| INF_COMP | String |  | Info. Compl. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF205 — EFD Contribuições Registro F200
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NUM_CONT | String |  | Núm. Contr./Doc. formaliza Venda Unid. Imob. |  |
| VL_BC_CUS_INC | Float |  | Valor da Base de Cálculo do Crédito sobre o Custo Incorrido, acumulado até o período da escrituração |  |
| VL_CRED_COFINS_ACUM | Float |  | Valor Total do Crédito Acumulado sobre o custo incorrido - COFINS |  |
| VL_CRED_COFINS_DESC | Float |  | Parcela a descontar no período da escrituração – COFINS |  |
| VL_CRED_COFINS_DESC_ANT | Float |  | Parcela do crédito descontada até o período anterior da escrituração – COFINS |  |
| VL_CRED_COFINS_DESC_FUT | Float |  | Parcela a descontar em períodos futuros – COFINS |  |
| VL_CRED_PIS_ACUM | Float |  | Valor Total do Crédito Acumulado sobre o custo incorrido – PIS/PASEP |  |
| VL_CRED_PIS_DESC | Float |  | Parcela a descontar no período da escrituração – PIS/PASEP |  |
| VL_CRED_PIS_DESC_ANT | Float |  | Parcela do crédito descontada até o período anterior da escrituração – PIS/PASEP |  |
| VL_CRED_PIS_DESC_FUT | Float |  | Parcela a descontar em períodos futuros – PIS/PASEP |  |
| VL_CUS_INC_ACUM | Float |  | Valor Total do Custo Incorrido da unidade imobiliária acumulado até o mês da escrituração |  |
| VL_CUS_INC_ACUM_ANT | Float |  | Valor Total do Custo Incorrido da unidade imobiliária acumulado até o mês anterior ao da escrituração |  |
| VL_CUS_INC_PER_ESC | Float |  | Valor Total do Custo Incorrido da unidade imobiliária no mês da escrituração |  |
| VL_EXC_BC_CUS_INC_ACUM | Float |  | Parcela do Custo Incorrido sem direito ao crédito da atividade imobiliária, acumulado até o período. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF210 — EFD Contribuições Registro F200
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| SEQ_F210 | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_BC_CRED | Float |  | Valor da Base de Cálculo do Crédito sobre o Custo Orçado referente ao mês da escrituração, proporcionalizada em função da receita recebida no mês |  |
| VL_CRED_COFINS_UTIL | Float |  | Valor do Crédito sobre o custo orçado a ser utilizado no período da escrituração - COFINS |  |
| VL_CRED_PIS_UTIL | Float |  | Valor do Crédito sobre o custo orçado a ser utilizado no período da escrituração - PIS/PASEP |  |
| VL_CUS_ORC | Float |  | Valor Total do Custo Orçado para Conclusão da Unidade Vendida |  |
| VL_CUS_ORC_AJU | Float |  | Valor da Base de Calculo do Crédito sobre o Custo Orçado Ajustado |  |
| VL_EXC | Float |  | Valores Referentes a Pagamentos a Pessoas Físicas, Encargos Trabalhistas, Sociais e Previdenciários e à aquisição de bens e serviços não sujeitos ao pagamento das contribuições |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF500 — EFD Contribuições Registro F500
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| CODEMPSCP | Integer |  | SCP |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_REC_CAIXA | Float |  | Vlr. total receita receb. ref. à comb. de CST e Alíq. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_DESC_PIS | Float |  | Vlr. desc. / exclusão base cálc. |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_DESC_COFINS | Float |  | Vlr. desc. / excl. base cálc. |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `8B`=8B-Conhecimento de Transporte de Cargas Avulso `67`=67-Conhecimento Transporte Eletrônico Outros Serviços `65`=65-Nota Fiscal Eletrônica de Venda a Consumidor `63`=63-Bilhete de Passagem Eletrônico `59`=59-Cupom Fiscal Eletrônico_(+30)_ |
| CFOP | Integer |  | Cód. Fiscal Oper. Prestação |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| INFO_COMPL | String |  | Info. compl. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF509 — EFD Contribuições Registro F509
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. do proc. ou ato concessório |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF510 — EFD Contribuições Registro F510
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_REC_CAIXA | Float |  | Vlr. total rec. receb. ref. à comb. de CST e Alíq. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_DESC_PIS | Float |  | Vlr. desconto / exclusão |  |
| QUANT_BC_PIS | Float |  | Base cálc. em qtd. - PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_DESC_COFINS | Float |  | Vlr. do desconto / exclusão |  |
| QUANT_BC_COFINS | Float |  | Base cálc. qtd. - COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. da COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `8B`=8B-Conhecimento de Transporte de Cargas Avulso `67`=67-Conhecimento Transporte Eletrônico Outros Serviços `65`=65-Nota Fiscal Eletrônica de Venda a Consumidor `63`=63-Bilhete de Passagem Eletrônico `59`=59-Cupom Fiscal Eletrônico_(+30)_ |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| COD_CTA | String |  | Cód. conta an. contábil deb./cred. |  |
| INFO_COMPL | String |  | Info. Compl. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF525 — EFD Contribuições Registro F525
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| CODEMPSCP | Integer |  | SCP |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| VL_REC | Float |  | Vlr. total da rec. receb. corresp. ao ind. infor. no campo posterior |  |
| IND_REC | String |  | Indic. da compos. da rec. receb. no per. | `99`=Outros (Detalhar no campo 10 – Informação Complementar) `05`=Item vendido (produtos e serviços) `04`=Documento fiscal `03`=Título de crédito - Duplicata, nota promissória, cheque, etc. `02`=Administradora de cartão de débito/crédito_(+1)_ |
| CNPJ_CPF | String |  | CNPJ/CPF do participante ou adm. de cartões |  |
| NUM_DOC | String |  | Núm. tít. de créd. ou doc. fiscal |  |
| COD_ITEM | String |  | Cód. do item |  |
| VL_REC_DET | Float |  | Vlr. receita detalhada |  |
| CST_PIS | String |  | Cód. Sit. Trib. do PIS/Pasep |  |
| CST_COFINS | String |  | Cód. Sit. Trib. da Cofins |  |
| INFO_COMPL | String |  | Info. compl. |  |
| COD_CTA | String |  | Cód. conta an. contábil repres. da rec. receb. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF550 — EFD Contribuições Registro F550
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| CODEMPSCP | Integer |  | SCP |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_REC_COMP | Float |  | Vlr. total rec. auferida, ref. à comb. de CST e Alíq. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_DESC_PIS | Float |  | Vlr. desconto / exclusão base cálc. |  |
| VL_BC_PIS | Float |  | Vlr. base cálc. do PIS/PASEP |  |
| ALIQ_PIS | Float |  | Alíq. do PIS/PASEP (em percentual) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_DESC_COFINS | Float |  | Vlr. desconto / exclusão base cálc; |  |
| VL_BC_COFINS | Float |  | Vlr. base cálc. da COFINS |  |
| ALIQ_COFINS | Float |  | Alíq. da COFINS (em percentual) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `8B`=8B-Conhecimento de Transporte de Cargas Avulso `67`=67-Conhecimento Transporte Eletrônico Outros Serviços `65`=65-Nota Fiscal Eletrônica de Venda a Consumidor `63`=63-Bilhete de Passagem Eletrônico `59`=59-Cupom Fiscal Eletrônico_(+30)_ |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| COD_CTA | String |  | Cód. conta an. contábil deb. / cred. |  |
| INFO_COMPL | String |  | Info. complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF550MOV — Financeiro
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| CODPARC | Integer |  | Parceiro |  |
| IND_OPER | String |  | Ind. tipo operação | `1`=Saída `0`=Entrada |
| REG | String |  | Registro |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_EMIT | String |  | Ind. emitente doc. fiscal | `1`=Terceiros `0`=Emissão própria |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| COD_PART | String |  | Cód. participante |  |
| COD_MOD | String |  | Cód. modelo doc. fiscal | `65`=65-Nota Fiscal Eletrônica para Consumidor Final `55`=55-Nota Fiscal Eletrônica `1B`=1B-Nota Fiscal Avulsa `04`=04-Nota Fiscal de Produtor `01`=01-Nota Fiscal |
| COD_SIT | String |  | Cód. situação doc. fiscal | `08`=Documento Fiscal emitido com base em Regime Especial ou Norma Específica `07`=Documento Fiscal Complementar extemporâneo `06`=Documento Fiscal Complementar `05`=NFe ou CT-e Numeração inutilizada `04`=NFe ou CT-e denegada_(+4)_ |
| SER | String |  | Série doc. fiscal |  |
| NUM_DOC | Integer |  | Núm. doc. fiscal |  |
| CHV_NFE | String |  | Chave NFE ou NFC-e |  |
| DT_DOC | Date |  | Dt. emissão do doc. fiscal |  |
| DT_E_S | Date |  | Dt. entrada ou saída |  |
| VL_DOC | Float |  | Vlr. total doc. fiscal |  |
| IND_PGTO | String |  | Indic. tipo pag. | `2`=Outros `1`=A prazo `0`=À vista |
| VL_DESC | Float |  | Vlr. total desconto |  |
| VL_ABAT_NT | Float |  | Abat. não trib. e não com. desc. ICMS |  |
| VL_MERC | Float |  | Vlr. total merc. e serviços |  |
| IND_FRT | String |  | Ind. tipo frete/transporte | `9`=Sem ocorrência de transporte `4`=Transporte próprio por conta do destinatário `3`=Transporte próprio por conta do remetente `2`=Frete por conta de terceiros `1`=Frete por conta do destinatário (FOB)_(+1)_ |
| VL_FRT | Float |  | Vlr. frete ind. no doc. fiscal |  |
| VL_SEG | Float |  | Vlr. seguro ind. no doc. fiscal |  |
| VL_OUT_DA | Float |  | Vlr. outras desp. acessórias |  |
| VL_BC_ICMS | Float |  | Vlr. base cálc. do ICMS |  |
| VL_ICMS | Float |  | Vlr. do ICMS |  |
| VL_BC_ICMS_ST | Float |  | Vlr. base cálc. do ICMS subst. trib. |  |
| VL_ICMS_ST | Float |  | Vlr. ICMS retido por subst. trib. |  |
| VL_IPI | Float |  | Vlr. total do IPI |  |
| VL_PIS | Float |  | Vlr. total do PIS |  |
| VL_COFINS | Float |  | Vlr. total do COFINS |  |
| VL_PIS_ST | Float |  | Vlr. total PIS retido por subst. trib. |  |
| VL_COFINS_ST | Float |  | Vlr. total COFINS retido por subst. trib. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| NUFIN | Integer |  | Nro Único Financeiro |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF559 — EFD Contribuições Registro F550
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. do proc. ou ato concessório |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `3`=Secretaria da Receita Federal do Brasil `1`=Justiça Federal |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |

## TGFEFDCF560 — EFD Contribuições Registro F560
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_REC_COMP | Float |  | Vlr. total rec. auferida, ref. à comb. de CST e Alíq. |  |
| CST_PIS | String |  | Cód. Sit. Trib. ref. ao PIS/PASEP |  |
| VL_DESC_PIS | Float |  | Vlr. desconto / exclusão |  |
| QUANT_BC_PIS | Float |  | Base cálc. em qtd. - PIS/PASEP |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. do PIS/PASEP (em reais) |  |
| VL_PIS | Float |  | Vlr. do PIS/PASEP |  |
| CST_COFINS | String |  | Cód. Sit. Trib. ref. a COFINS |  |
| VL_DESC_COFINS | Float |  | Vlr. desconto / exclusão |  |
| QUANT_BC_COFINS | Float |  | Base cálc. em qtd. – COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. da COFINS (em reais) |  |
| VL_COFINS | Float |  | Vlr. da COFINS |  |
| COD_MOD | String |  | Cód. mod. doc. fiscal | `8B`=8B-Conhecimento de Transporte de Cargas Avulso `67`=67-Conhecimento Transporte Eletrônico Outros Serviços `65`=65-Nota Fiscal Eletrônica de Venda a Consumidor `63`=63-Bilhete de Passagem Eletrônico `59`=59-Cupom Fiscal Eletrônico_(+30)_ |
| CFOP | Integer |  | Cód. Fiscal de Oper. e Prestação |  |
| COD_CTA | String |  | Cód. conta an. contábil deb. / cred. |  |
| INFO_COMPL | String |  | Info. complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCF600 — EFD Contribuições Registro F600
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_NAT_RET | String |  | Ind. Natureza da Retenção na Fonte | `99`=Outras Retenções `04`=Recolhimento por Sociedade Cooperativa `03`=Retenção por Pessoas Jurídicas de Direito Privado `02`=Retenção por outras Entidades da Administração Pública Federal `01`=Retenção por Órgãos, Autarquias e Fundações Federais_(+1)_ |
| DT_RET | Date |  | Dt. da Retenção |  |
| VL_BC_RET | Float |  | Base cálc. da retenção ou recol. (soc. coop.) |  |
| VL_RET | Float |  | Vlr. Total Ret. na Fonte / Recol. (soc. coop.) |  |
| COD_REC | Integer |  | Cód. da Receita |  |
| IND_NAT_REC | Integer |  | Ind. Natureza da Receita | `1`=Receita de Natureza Cumulativa `0`=Receita de Natureza Não Cumulativa |
| CNPJ | String |  | CNPJ |  |
| VL_RET_PIS | Float |  | Vlr. Ret. na Fonte - Parc. Ref. ao PIS/PASEP |  |
| VL_RET_COFINS | Float |  | Vlr. Ret. na Fonte – Parc. Ref. a COFINS |  |
| IND_DEC | Integer |  | Ind. condição PJ declarante | `0`=Beneficiária da Retenção / Recolhimento `1`=Responsável pelo Recolhimento |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM001 — EFD Contribuições Registro M001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Ind. de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_M | Integer |  | Qtd. total linhas Bloco M |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM100 — EFD Contribuições Registro M100
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_CRED | Integer |  | Cód. Tipo Créd. apurado no per. |  |
| IND_CRED_ORI | Integer |  | Ind. Créd. Oriundo | `1`=Evento de incorporação, cisão ou fusão `0`=Operações próprias |
| VL_BC_PIS | Float |  | Vlr. Base Cálc. Crédito |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| QUANT_BC_PIS | Float |  | Qtd. – Base cálc. PIS |  |
| ALIQ_PIS_QUANT | Float |  | Alíq. PIS (em reais) |  |
| VL_CRED | Float |  | Vlr. total créd. apurado no per. |  |
| VL_AJUS_ACRES | Float |  | Vlr. total ajustes de acrésc. |  |
| VL_AJUS_REDUC | Float |  | Vlr. total ajustes de redução |  |
| VL_CRED_DIF | Float |  | Vlr. total créd. diferido no per. |  |
| VL_CRED_DISP | Float |  | Vlr. Total Créd. Disp. relativo ao Per. |  |
| IND_DESC_CRED | String |  | Ind. opção util. créd. disp. no per. | `1`=Utilização de valor parcial para desconto da contribuição apurada no período, no Registro M200 `0`=Utilização do valor total para desconto da contribuição apurada no período, no Registro M200 |
| VL_CRED_DESC | Float |  | Vlr. Créd. disp. descont. contrib. apura. próprio per. |  |
| SLD_CRED | Float |  | Saldo créd. a utilizar em per. fut. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM110 — EFD Contribuições Registro M110
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_AJ | String |  | Indicador do tipo de ajuste | `0`=Ajuste de redução `1`=Ajuste de acréscimo |
| VL_AJ | Float |  | Vlr. do ajuste |  |
| COD_AJ | String |  | Cód. do ajuste |  |
| NUM_DOC | String |  | Núm. do proc. doc. ou ato conces. ao qual ajuste está vinc. |  |
| DESCR_AJ | String |  | Descr. resumida do ajuste |  |
| DT_REF | Date |  | Dt. ref. do ajuste |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM115 — EFD Contribuições Registro M115
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| ALIQ_PIS | Float |  | Alíq. PIS/PASEP (em percentual) |  |
| SEQM110 | Integer |  | Sequência M110 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DET_VALOR_AJ | Float |  | Detalh. vlr. do créd. reduzido ou acrescido |  |
| CST_PIS | String |  | Cód. Situação Trib. ref. à operação detalhada |  |
| DET_BC_CRED | Float |  | Detalh. base cálc. geradora ajuste de créd. |  |
| DET_ALIQ | Float |  | Detalh. alíq. ref. o ajuste de créd. |  |
| DT_OPER_AJ | Date |  | Dt. oper. ref. o ajuste informado |  |
| DESC_AJ | String |  | Descr. da(s) oper.(ões) ref. o valor informado |  |
| COD_CTA | String |  | Cód. conta contábil deb./cred. |  |
| INFO_COMPL | String |  | Info. complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM200 — EFD Contribuições Registro M200
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| VL_TOT_CONT_NC_PER | Float |  | Vlr. Total Contrib. Não Cumul. do Per. |  |
| VL_TOT_CRED_DESC | Float |  | Vlr. Créd. Descont. Apur. no Próprio Per. da Escrit. |  |
| VL_TOT_CRED_DESC_ANT | Float |  | Vlr. Crédito Descont. Apur. Per. de Apur. Anterior |  |
| VL_TOT_CONT_NC_DEV | Float |  | Vlr. Total Contrib. Não Cumul. Devida |  |
| VL_RET_NC | Float |  | Vlr. Retido na Fonte Ded. no Per. |  |
| VL_OUT_DED_NC | Float |  | Outras Deduções no Per. |  |
| VL_CONT_NC_REC | Float |  | Vlr. Contrib. Não Cumul. a Recolher/Pagar |  |
| VL_TOT_CONT_CUM_PER | Float |  | Vlr. Total Contrib. Cumul. do Per. |  |
| VL_RET_CUM | Float |  | Vlr. Retido na Fonte Ded. no Per. |  |
| VL_OUT_DED_CUM | Float |  | Outras Deduções no Per. |  |
| VL_CONT_CUM_REC | Float |  | Vlr. da Contrib. Cumul. a Recolher/Pagar |  |
| VL_TOT_CONT_REC | Float |  | Vlr. Total da Contrib. a Recolher/Pagar no Per. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM400 — EFD Contribuições Registro M400
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| CST_PIS | String |  | Cód. de Situação Trib. |  |
| VL_TOT_REC | Float |  | Vlr. total receita bruta no per. |  |
| COD_CTA | String |  | Cód. da conta an. cont. deb./cred. |  |
| DESC_COMPL | String |  | Descr. Compl. da Natureza da Receita |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM410 — EFD Contribuições Registro M410
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CST_PIS | String |  | Cód. de Situação Trib. |  |
| REGISTRO | String |  | Registro |  |
| NAT_REC | String |  | Nat. Receita, conf. relação const. nas Tab. de Detalham. da Nat. da Receita por Sit. Trib. |  |
| VL_REC | Float |  | Vlr. rec. bruta no período, relativo a natureza da rec. |  |
| COD_CTA | String |  | Cód. da conta an. cont. deb./cred. |  |
| DESC_COMPL | String |  | Descr. Compl. da Natureza da Receita |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM500 — EFD Contribuições Registro M500
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_CRED | String |  | Cód. Tipo Crédito apur. no per. |  |
| IND_CRED_ORI | Integer |  | Indicador de Crédito Oriundo | `0`=Operações próprias `1`=Evento de incorporação, cisão ou fusão |
| VL_BC_COFINS | Float |  | Vlr. Base Cálc. do Créd. |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| QUANT_BC_COFINS | Float |  | Qtd. – Base cálc. COFINS |  |
| ALIQ_COFINS_QUANT | Float |  | Alíq. COFINS (em reais) |  |
| VL_CRED | Float |  | Vlr. total crédito apur. no per. |  |
| VL_AJUS_ACRES | Float |  | Vlr. total ajustes de acréscimo |  |
| VL_AJUS_REDUC | Float |  | Vlr. total ajustes de redução |  |
| VL_CRED_DIFER | Float |  | Vlr. total créd. diferido no per. |  |
| VL_CRED_DISP | Float |  | Vlr. Total Créd. Disp. relativo ao Per. |  |
| IND_DESC_CRED | String |  | Ind. utilização créd. disp. no per. | `1`=Utilização de valor parcial para desconto da contribuição apurada no período, no Reg. M600 `0`=Utilização do valor total para desconto da contribuição apurada no período, no Reg. M600 |
| VL_CRED_DESC | Float |  | Vlr. Créd. disp. descontado da contrib. apur. no próprio per. |  |
| SLD_CRED | Float |  | Saldo créd. a utilizar em per. futuros |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM510 — EFD Contribuições Registro M510
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_AJ | String |  | Ind. do tipo de ajuste | `1`=Ajuste de acréscimo `0`=Ajuste de redução |
| VL_AJ | Float |  | Vlr. do ajuste |  |
| COD_AJ | Integer |  | Cód. do ajuste |  |
| NUM_DOC | String |  | Núm. proc. doc. ou ato conces. ajuste vinculado |  |
| DESCR_AJ | String |  | Descrição resumida do ajuste |  |
| DT_REF | Date |  | Dt. de .referência do ajuste |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM515 — EFD Contribuições Registro M515
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| ALIQ_COFINS | Float |  | Alíq. COFINS (em percentual) |  |
| SEQM510 | Integer |  | Sequência M510 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DET_VALOR_AJ | Float |  | Detalh. valor créd. reduzido ou acrescido |  |
| CST_COFINS | String |  | Cód. Situação Trib. ref. à operação detalhada |  |
| DET_BC_CRED | Float |  | Detalh. base cálc. geradora de ajuste de créd. |  |
| DET_ALIQ | Float |  | Detalh. da alíq. ref. o ajuste de créd. |  |
| DT_OPER_AJ | Date |  | Dt. oper. ref. o ajuste informado |  |
| DESC_AJ | String |  | Descr. da(s) oper.(ões) ref. o valor informado |  |
| COD_CTA | String |  | Cód. conta contábil deb./cred. |  |
| INFO_COMPL | String |  | Informação complementar |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM600 — EFD Contribuições Registro M600
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| VL_TOT_CONT_NC_PER | Float |  | Vlr. Total Contrib. Não Cum. do Per. |  |
| VL_TOT_CRED_DESC | Float |  | Vlr. Créd. Descontado Apur. no Próprio Per. da Escrit. |  |
| VL_TOT_CRED_DESC_ANT | Float |  | Vlr. Créd. Descontado Apur. em Per. de Apur. Anterior |  |
| VL_TOT_CONT_NC_DEV | Float |  | Vlr. Total Contrib. Não Cumul. Devida |  |
| VL_RET_NC | Float |  | Vlr. Retido na Fonte Deduzido no Per. |  |
| VL_OUT_DED_NC | Float |  | Outras Deduções no Período |  |
| VL_CONT_NC_REC | Float |  | Vlr. Contrib. Não Cumul. a Recolher/Pag. |  |
| VL_TOT_CONT_CUM_PER | Float |  | Vlr. Total Contrib. Cumul. do Per. |  |
| VL_RET_CUM | Float |  | Vlr. Retido na Fonte Ded. no Per. |  |
| VL_OUT_DED_CUM | Float |  | Outras Deduções no Período |  |
| VL_CONT_CUM_REC | Float |  | Vlr. Contrib. Cumul. a Recolher/Pagar |  |
| VL_TOT_CONT_REC | Float |  | Vlr. Total Contrib. a Recolher/Pagar no Per. |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM800 — EFD Contribuições Registro M800
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| CST_COFINS | String |  | Cód. de Situação Tributária |  |
| VL_TOT_REC | Float |  | Vlr. total rec. bruta no per. |  |
| COD_CTA | String |  | Cód. conta an. cont. deb./cred. |  |
| DESC_COMPL | String |  | Descr. Compl. da Nat. da Receita |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCM810 — EFD Contribuições Registro M810
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CST_COFINS | String |  | Cód. de Situação Tributária |  |
| REGISTRO | String |  | Registro |  |
| NAT_REC | String |  | Natureza da Receita |  |
| VL_REC | Float |  | Vlr. rec. bruta per. relativo a Natureza da Receita |  |
| COD_CTA | String |  | Cód. conta an. contábil deb./cred. |  |
| DESC_COMPL | String |  | Descr. Compl. Natureza da Receita |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCP001 — EFD Contribuições Registro P001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_P | Integer |  | Qtd. total linhas Bloco P |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCP010 — EFD Contribuições Registro P010
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| REGISTRO | String |  | Registro |  |
| CNPJ | String |  | Núm. inscr. estabelec. no CNPJ |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCP100 — EFD Contribuições Registro P100
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| DT_INI | Date |  | Dt. inicial apuração |  |
| DT_FIN | Date |  | Dt. final apuração |  |
| VL_REC_TOT_EST | Float |  | Vlr. Rec. Bruta Total Estab. no Per. |  |
| COD_ATIV_ECON | String |  | Cód. ind. ativ. suj. incid. Contrib. Previd. sobre Rec. Bruta |  |
| VL_REC_ATIV_ESTAB | Float |  | Vlr. Rec. Bruta Estab. corresp. às ativ./prod. referidos |  |
| VL_EXC | Float |  | Vlr. Excl. Receita Bruta info. |  |
| VL_BC_CONT | Float |  | Vlr. Base Cálc. Contrib. Previd. sobre Rec. Bruta |  |
| ALIQ_CONT | Float |  | Alíq. Contrib. Previd. sobre Receita Bruta |  |
| VL_CONT_APU | Float |  | Vlr. Contrib. Previd. Apur. sobre Rec. Bruta |  |
| COD_CTA | String |  | Cód. conta an. contábil ref. Contrib. Previd. sobre Rec. Bruta |  |
| INFO_COMPL | String |  | Info. compl. do registro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| COD_INC_TRIB | Integer |  | Cód. indicador incid. trib. período | `2`=Contribuição Previdenciária apurada no período, com base na Receita Bruta e nas Remunerações pagas `1`=Contribuição Previdenciária apurada no período, exclusivamente com base na Receita Bruta |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCP199 — EFD Contribuições Registro P199
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Ident. processo ou ato concessório |  |
| IND_PROC | String |  | Ind. da origem do processo | `9`=Outros `1`=Justiça Federal `3`=Secretaria da Receita Federal do Brasil |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDCP200 — EFD Contribuições Registro P200
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| PER_REF | Date |  | Per. ref. da escrituração |  |
| VL_TOT_CONT_APU | Float |  | Vlr. total apur. Contrib. Previd. sobre Rec. Bruta |  |
| VL_TOT_AJ_REDUC | Float |  | Vlr. total de “Ajustes de redução” |  |
| VL_TOT_AJ_ACRES | Float |  | Vlr. total de “Ajustes de acréscimo” |  |
| VL_TOT_CONT_DEV | Float |  | Vlr. total Contrib. Previd. sobre Rec. Bruta a recolher |  |
| COD_REC | String |  | Cód. Receita ref. à Contrib. Previd. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | ORDEM |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF — EFD Fiscal
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| VERSAOLAYOUT | Integer |  | Versão do Layout | `15`=016 - Versão 115 - Início 01/01/2022 `16`=017 - Versão 116 - Início 01/01/2023 `17`=018 - Versão 117 - Início 01/01/2024 `14`=015 - Versão 114 - Início 01/01/2021 `18`=019 - Versão 118 - Início 01/01/2025_(+1)_ |
| ARQCONFIRMADO | String |  | Arquivo confirmado | `S`=Sim `N`=Não |
| COD_FIN_CSLL | Integer |  | Código da Finalidade do Arquivo | `1`=Remessa do arquivo substituto `0`=Remessa do arquivo original |
| NOMEARQUIVO | String |  | Nome Arquivo |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0000 — EFD Fiscal Registro 0000
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| COD_VER | Integer |  | Código da versão do leiaute conforme a tabela indicada no Ato COTEPE | `9`=009 - Versão 108 - Início 01/01/2015 `8`=008 - Versão 107 - Início 01/01/2014 `7`=007 - Versão 106 - Início 01/01/2013 `6`=006 - Versão 105 - Início 01/07/2012 `5`=005 - Versão 104 - Início 01/01/2012_(+15)_ |
| COD_FIN | Integer |  | Código da finalidade do arquivo | `1`=Remessa do arquivo substituto `0`=Remessa do arquivo original |
| DT_INI | Date |  | Data inicial das informações contidas no arquivo |  |
| DT_FIN | Date |  | Data final das informações contidas no arquivo |  |
| NOME | String |  | Nome empresarial |  |
| CNPJ | String |  | Cnpj |  |
| CPF | String |  | Número de inscrição CPF |  |
| UF | String |  | UF |  |
| IE | String |  | Inscrição Estadual |  |
| COD_MUN | Integer |  | Cód. IBGE |  |
| IM | String |  | Inscrição Municipal |  |
| SUFRAMA | String |  | Inscrição SUFRAMA |  |
| IND_PERFIL | String |  | Perfil de apresentação do arquivo fiscal | `C`=Perfil C `B`=Perfil B `A`=Perfil A |
| IND_ATIV | Integer |  | Indicador de tipo de atividade | `1`=Outros `0`=Industrial ou equiparado a industrial |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0001 — EFD Fiscal Registro 0001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_0 | Integer |  | Qtd. Linhas 0 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0002 — EFD Fiscal Registro 0002
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| CLAS_ESTAB_IND | Integer |  | Informar a classificação do estabelecimento |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0005 — EFD Fiscal Registro 0005
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| FANTASIA | String |  | Nome de fantasia associado ao nome empresarial |  |
| CEP | String |  | Cep |  |
| ENDERECO | String |  | Logradouro e endereço |  |
| NUMERO | String |  | Número |  |
| COMPL | String |  | Dados complementares do endereço |  |
| BAIRRO | String |  | Bairro em que o imóvel está situado |  |
| FONE | String |  | Número do telefone |  |
| FAX | String |  | Número do FAX |  |
| EMAIL | String |  | Endereço do correio eletrônico |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0015 — EFD Fiscal Registro 0015
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| UF_ST | String |  | Sigla da UF |  |
| IE_ST | String |  | Inscrição Estadual |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0100 — EFD Fiscal Registro 0100
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| NOME | String |  | Nome do contabilista |  |
| CPF | String |  | Número CPF do contabilista |  |
| CRC | String |  | Número CRC do contabilista |  |
| CNPJ | String |  | Número CNPJ do escritório de contabilidade |  |
| CEP | String |  | Cep |  |
| ENDERECO | String |  | Logradouro e endereço |  |
| NUM | String |  | Número |  |
| COMPL | String |  | Complemento do endereço |  |
| BAIRRO | String |  | Bairro |  |
| FONE | String |  | Número do telefone |  |
| FAX | String |  | Número do fax |  |
| EMAIL | String |  | E-mail |  |
| COD_MUN | Integer |  | Código do município IBGE |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0150 — EFD Fiscal Registro 0150
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| NOME | String |  | Nome pessoal ou empresarial do participante |  |
| COD_PAIS | Integer |  | Código do país do participante |  |
| CNPJ | String |  | CNPJ do participante |  |
| CPF | String |  | CPF do participante |  |
| IE | String |  | IE do participante |  |
| COD_MUN | Integer |  | Código do município IBGE |  |
| SUFRAMA | String |  | Número de inscrição do participante na SUFRAMA |  |
| ENDERECO | String |  | Logradouro e endereço do imóvel |  |
| NUM | String |  | Número do imóvel |  |
| COMPL | String |  | Dados complementares do endereço |  |
| BAIRRO | String |  | Bairro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0175 — EFD Fiscal Registro 0175
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| DT_ALT | Date |  | Data de alteração do cadastro |  |
| NR_CAMPO | String |  | Número do campo alterado |  |
| CONT_ANT | String |  | Conteúdo anterior do campo |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0190 — EFD Fiscal Registro 0190
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| UNID | String |  | Código da unidade de medida |  |
| DESCR | String |  | Descrição da unidade de medida |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0200 — EFD Fiscal Registro 0200
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. Item |  |
| DESCR_ITEM | String |  | Descrição do item |  |
| COD_BARRA | String |  | Representação alfanumérico do código de barra do produto |  |
| COD_ANT_ITEM | String |  | Código anterior do item com relação à última inf. apresentada |  |
| UNID_INV | String |  | Unidade de medida utilizada na quantificação de estoques |  |
| CHAVE | String |  | Chave |  |
| TIPO_ITEM | Integer |  | Tipo do item – Atividades Industriais, Comerciais e Serviços | `99`=Outras `10`=Outros insumos `09`=Serviços `08`=Ativo Imobilizado `07`=Material de Uso e Consumo_(+7)_ |
| COD_NCM | String |  | Código da Nomenclatura Comum do Mercosul |  |
| EX_IPI | String |  | Código EX, conforme a TIPI |  |
| COD_GEN | Integer |  | Código do gênero do item |  |
| COD_LST | String |  | Cód. Lista Serviço |  |
| ALIQ_ICMS | Float |  | Alíquota de ICMS aplicável ao item nas operações internas |  |
| CEST | Integer |  | Código Especificador da Substituição Tributária |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0205 — EFD Fiscal Registro 0205
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. Item |  |
| DESCR_ANT_ITEM | String |  | Descrição anterior do item |  |
| DT_INI | Date |  | Data inicial de utilização da descrição do item |  |
| DT_FIN | Date |  | Data final de utilização da descrição do item |  |
| COD_ANT_ITEM | String |  | Código anterior do item com relação à última inf. apresentada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0206 — EFD Fiscal Registro 0206
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_COMB | String |  | Cód. produto, conforme tabela publicada pela ANP |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0210 — EFD Fiscal Registro 0210
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM_COMP | String |  | Código do item componente/insumo |  |
| QTD_COMP | Integer |  | Quantidade do item componente/insumo para se produzir uma unidade do item composto/resultante |  |
| PERDA | Integer |  | Perda/quebra normal percentual do insumo/componente para se produzir uma unidade do item composto/resultante |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0220 — EFD Fiscal Registro 0220
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| UNID_CONV | String |  | Unidade comercial a ser convertida na unidade de estoque |  |
| FAT_CONV | Integer |  | Fator de conversão |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| COD_BARRA | String |  | Código de barra da unidade comercial do produto |  |
| COD_ITEM | String |  | Cód. Item |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0300 — EFD Fiscal Registro 0300
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_IND_BEM | String |  | Código individualizado do bem |  |
| IDENT_MERC | String |  | Identificação do tipo de mercadoria | `2`=componente `1`=bem |
| DESCR_ITEM | String |  | Descrição do bem ou componente |  |
| COD_PRNC | String |  | Código de cadastro do bem principal |  |
| COD_CTA | String |  | Código da conta analítica de contabilização do bem |  |
| NR_PARC | Integer |  | Número total de parcelas a serem apropriadas |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0305 — EFD Fiscal Registro 0305
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPROD | Integer |  | Produto |  |
| COD_IND_BEM | String |  | COD_IND_BEM |  |
| REGISTRO | String |  | Registro |  |
| COD_CCUS | String |  | Cód. centro de custo utilizado |  |
| FUNC | String |  | Descrição sucinta da função do bem |  |
| VIDA_UTIL | Integer |  | Vida útil estimada do bem, em número de meses |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0400 — EFD Fiscal Registro 0400
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_NAT | String |  | Código da natureza da operação/prestação |  |
| DESCR_NAT | String |  | Descrição da natureza da operação/prestação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0450 — EFD Fiscal Registro 0450
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_INF | String |  | Cód. informação complementar do doc. fiscal |  |
| TXT | String |  | Texto livre da inf. complementar existente no doc. fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0460 — EFD Fiscal Registro 0460
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_OBS | String |  | Código da Observação do lançamento fiscal |  |
| TXT | String |  | Descrição da observação vinculada ao lançamento fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0500 — EFD Fiscal Registro 0500
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DT_ALT | Date |  | Data Alteração |  |
| COD_NAT_CC | String |  | Código da natureza da conta/grupo de contas | `09`=Outras `05`=Contas de compensação `04`=Contas de resultado `03`=Patrimônio líquido `02`=Contas de passivo_(+1)_ |
| IND_CTA | String |  | Indicador do tipo de conta | `S`=Sintética (grupo de contas) `A`=Analítica (conta) |
| NIVEL | Integer |  | Nível da conta analítica/grupo de contas |  |
| COD_CTA | String |  | Código da conta analítica/grupo de contas |  |
| NOME_CTA | String |  | Nome da conta analítica/grupo de contas |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF0600 — EFD Fiscal Registro 0600
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| DT_ALT | Date |  | Data da inclusão/alteração |  |
| COD_CCUS | String |  | Código do centro de custos |  |
| CCUS | String |  | Nome do centro de custos |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1001 — EFD Fiscal Registro 1001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `0`=Bloco com dados informados `1`=Bloco sem dados informados |
| QTD_LIN_1 | Integer |  | Qtd. Linhas 1 |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1010 — EFD Fiscal Registro 1010
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| IND_EXP | String |  | Reg. 1100 - Ocorreu averbação (conclusão) de exportação no período | `S`=Sim `N`=Não |
| IND_CCRF | String |  | Reg 1200 – Existem informações acerca de créditos de ICMS a serem controlados, definidos pela Sefaz | `N`=Não `S`=Sim |
| IND_COMB | String |  | Reg. 1300 – É comércio varejista de combustíveis com movimentação e/ou estoque no período | `S`=Sim `N`=Não |
| IND_USINA | String |  | Reg. 1390 – Usinas de açúcar e/álcool – O estabelecimento é produtor de açúcar e/ou álcool carburante com movimentação e/ou estoque no período | `S`=Sim `N`=Não |
| IND_VA | String |  | Reg 1400 - Sendo o registro obrigatório em sua Unidade de Federação, existem informações a serem prestadas neste registro | `N`=Não `S`=Sim |
| IND_EE | String |  | Reg 1500 - A empresa é distribuidora de energia e ocorreu fornecimento de energia elétrica para consumidores de outra UF | `N`=Não `S`=Sim |
| IND_CART | String |  | Reg 1600 - Realizou vendas com Cartão de Crédito ou de débito | `S`=Sim `N`=Não |
| IND_FORM | String |  | Reg. 1700 - Foram emitidos doc. fiscais em papel no período em unid. da federação que exija o controle de utiliz. de doc. fiscais | `S`=Sim `N`=Não |
| IND_AER | String |  | Reg 1800 - A empresa prestou serviços de transporte aéreo de cargas e de passageiros | `S`=Sim `N`=Não |
| IND_GIAF1 | String |  | Reg. 1960 - Possui informações GIAF1? | `N`=Não `S`=Sim |
| IND_GIAF3 | String |  | Reg. 1970 - Possui informações GIAF3? | `S`=Sim `N`=Não |
| IND_GIAF4 | String |  | Reg. 1980 - Possui informações GIAF4? | `S`=Sim `N`=Não |
| IND_REST_RESSAR_COMPL_ICMS | String |  | Reg. 1250 – Possui informações consolidadas de saldos de restituição, ressarcimento e complementação do ICMS? | `S`=Sim `N`=Não |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1100 — EFD Fiscal Registro 1100
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_DOC | Integer |  | Informe o tipo de documento | `2`=Declaração Única de Exportação `1`=Declaração Simplif. Exportação `0`=Declaração de Exportação |
| NRO_DE | String |  | Número da declaração |  |
| DT_DE | Date |  | Data da declaração |  |
| NAT_EXP | Integer |  | Preencher com | `1`=Exportação Indireta `0`=Exportação Direta |
| NRO_RE | String |  | Núm. do registro de Exportação |  |
| DT_RE | Date |  | Dt. Registro de Exportação |  |
| CHC_EMB | String |  | Núm. do conhecimento de embarque |  |
| DT_CHC | Date |  | Dt. conhecimento de embarque |  |
| DT_AVB | Date |  | Dt.averbação da Declaração de exportação |  |
| TP_CHC | Integer |  | Inf. tipo de conhecimento de embarque | `99`=OUTROS `93`=HNAO IATA `92`=MNAO IATA `91`=NÂO IATA `20`=CP2_(+17)_ |
| PAIS | Integer |  | Cód. país de destino da mercadoria |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1105 — EFD Fiscal Registro 1105
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQ1100 | Integer |  | SEQ1100 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Cód. modelo do documento fiscal |  |
| SERIE | String |  | Série da Nota Fiscal |  |
| NUM_DOC | Integer |  | Núm. NF de Exportação emitida pelo Exportador |  |
| CHV_NFE | String |  | Chave da Nota Fiscal Eletrônica |  |
| DT_DOC | Date |  | Data da emissão da NF de exportação |  |
| COD_ITEM | String |  | Cód. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1110 — EFD Fiscal Registro 1110
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQ1100 | Integer |  | SEQ1100 |  |
| SEQ1105 | Integer |  | SEQ1105 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Cód. modelo do documento fiscal |  |
| SER | String |  | Série doc. fiscal recebido com fins específicos de exportação |  |
| NUM_DOC | Integer |  | Núm. doc. fiscal receb. com fins específicos de exportação |  |
| DT_DOC | Date |  | Dt. emissão doc. fiscal recebido com fins específicos de exportação |  |
| CHV_NFE | String |  | Chave da Nota Fiscal Eletrônica |  |
| NR_MEMO | String |  | Número do Memorando de Exportação |  |
| QTD | Float |  | Qtd. item efetivamente exportado |  |
| UNID | String |  | Unidade do item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1200 — EFD Fiscal Registro 1200
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ_APUR | String |  | Código de ajuste |  |
| SLD_CRED | Float |  | Saldo de créd. fiscais de períodos ant. |  |
| CRED_APR | Float |  | Tot. crédito apropriado no mês |  |
| CRED_RECEB | Float |  | Tot. créditos recebidos por transferência |  |
| CRED_UTIL | Float |  | Tot. de créditos utilizados no período |  |
| SLD_CRED_FIM | Float |  | Saldo de créd. fiscal acumulado a transportar para o período seguinte |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1210 — EFD Fiscal Registro 1210
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQ1200 | Integer |  | Sequência 1200 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| TIPO_UTIL | String |  | Tipo de utilização do crédito |  |
| NR_DOC | String |  | Núm. doc. utilizado na baixa de créditos |  |
| VL_CRED_UTIL | Float |  | Total de crédito utilizado |  |
| CHV_DOCE | String |  | Chave do Documento Eletrônico |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1250 — EFD Fiscal Registro 1250
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| VL_CREDITO_ICMS_OP | Float |  | Total ICMS |  |
| VL_ICMS_ST_REST | Float |  | Total ICMS ST |  |
| VL_FCP_ST_REST | Float |  | Total FCP ST |  |
| VL_ICMS_ST_COMPL | Float |  | Total ICMS ST Complementar |  |
| VL_FCP_ST_COMPL | Float |  | Total FCP ST Complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1255 — EFD Fiscal Registro 1255
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| COD_MOT_REST_COMPL | String |  | Código Motivo Restituição/Complementação |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQ1250 | Integer |  | Sequência 1200 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| VL_CREDITO_ICMS_OP_MOT | Float |  | Valor Total de ICMS |  |
| VL_ICMS_ST_REST_MOT | Float |  | Valor Total de ICMS ST |  |
| VL_FCP_ST_REST_MOT | Float |  | Valor Total de FCP ST |  |
| VL_ICMS_ST_COMPL_MOT | Float |  | Valor Total de ICMS ST Compl. |  |
| VL_FCP_ST_COMPL_MOT | Float |  | Valor Total de FCP ST Compl. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1400 — EFD Fiscal Registro 1400
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM_IPM | String |  | Código do item |  |
| MUN | Integer |  | Código do Município de origem/destino |  |
| VALOR | Float |  | Valor mensal correspondente ao município |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1600 — EFD Fiscal Registro 1600
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| TOT_CREDITO | Float |  | Vlr. tot. operações de créd. realizadas no período |  |
| TOT_DEBITO | Float |  | Vlr. tot. operações de déb. realizadas no período |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1601 — EFD Fiscal Registro 1601
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| COD_PART_IP | Integer |  | Parceiro Intermediador |  |
| REGISTRO | String |  | Registro |  |
| COD_PART_IT | String |  | Parceiro Intermediador |  |
| TOT_VS | Float |  | Valor Bruto Vendas |  |
| TOT_ISS | Float |  | Valor Bruto Serviços |  |
| TOT_OUTROS | Float |  | Valor Vendas Outros |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1900 — EFD Fiscal Registro 1900
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| IND_APUR_ICMS | String |  | Indicador de outra apuração do ICMS | `8`=APURAÇÃO 6 `7`=APURAÇÃO 5 `5`=APURAÇÃO 3 `4`=APURAÇÃO 2 `3`=APURAÇÃO 1_(+1)_ |
| DESCR_COMPL_OUT_APUR | String |  | Descrição complementar de Outra Apuração do ICMS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1910 — EFD Fiscal Registro 1910
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_APUR_ICMS | String |  | Indicador de outra apuração do ICMS |  |
| REGISTRO | String |  | Registro |  |
| DT_INI | Date |  | Data inicial da sub-apuração |  |
| DT_FIN | Date |  | Data final da sub-apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1920 — EFD Fiscal Registro 1920
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_APUR_ICMS | String |  | IND_APUR_ICMS |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| REGISTRO | String |  | Registro |  |
| VL_TOT_TRANSF_DEBITOS_OA | Float |  | Vlr. tot. débitos por “Saídas e prestações com débito do imposto" |  |
| VL_TOT_AJ_DEBITOS_OA | Float |  | Vlr. tot. de “Ajustes a débito” |  |
| VL_ESTORNOS_CRED_OA | Float |  | Vlr. tot. Ajustes “Estornos de créditos" |  |
| VL_TOT_TRANSF_CREDITOS_OA | Float |  | Vlr. tot. créditos por “Entradas e aquisições com crédito do imposto” |  |
| VL_TOT_AJ_CREDITOS_OA | Float |  | Vlr. tot. “Ajustes a crédito” |  |
| VL_ESTORNOS_DEB_OA | Float |  | Vlr. tot. Ajustes “Estornos de Débitos" |  |
| VL_SLD_CREDOR_ANT_OA | Float |  | Vlr. tot. “Saldo credor do período anterior" |  |
| VL_SLD_APURADO_OA | Float |  | Vlr. saldo devedor apurado |  |
| VL_TOT_DED | Float |  | Vlr. tot. “Deduções” |  |
| VL_ICMS_RECOLHER_OA | Float |  | Vlr. tot. "ICMS a recolher (09-10) |  |
| VL_SLD_CREDOR_TRANSP_OA | Float |  | Vlr. tot. “Saldo credor a transportar para o período seguinte” |  |
| DEB_ESP_OA | Float |  | Vlr. recolhidos ou a recolher, extra-apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1921 — EFD Fiscal Registro 1921
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_APUR_ICMS | String |  | IND_APUR_ICMS |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| REGNIV4 | String |  | Registro Nível 4 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ_APUR | String |  | Código do ajuste da SUB-APURAÇÃO e dedução |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste da apuração |  |
| VL_AJ_APUR | Float |  | Valor do ajuste da apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1922 — EFD Fiscal Registro 1922
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_APUR_ICMS | String |  | IND_APUR_ICMS |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| REGNIV4 | String |  | Registro Nível 4 |  |
| SEQ1921 | Integer |  | Sequência 1921 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NUM_DA | String |  | Núm. documento de arrecadação estadual |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `2`=Justiça Estadual `1`=Justiça Federal `0`=SEFAZ |
| DESCPROC | String |  | Descrição resumida do processo que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1923 — EFD Fiscal Registro 1923
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_APUR_ICMS | String |  | IND_APUR_ICMS |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| REGNIV4 | String |  | Registro Nível 4 |  |
| SEQ1921 | Integer |  | SEQ1921 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | Integer |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_AJ_ITEM | Float |  | Valor do ajuste para a operação/item |  |
| CHV_DOCE | String |  | Chave do Documento Eletrônico |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1925 — EFD Fiscal Registro 1925
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_APUR_ICMS | String |  | IND_APUR_ICMS |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| REGNIV4 | String |  | Registro Nível 4 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_INF_ADIC | String |  | Código da informação adicional |  |
| VL_INF_ADIC | Float |  | Valor referente à informação adicional |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1926 — EFD Fiscal Registro 1926
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| IND_APUR_ICMS | String |  | IND_APUR_ICMS |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| REGNIV4 | String |  | Registro Nível 4 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_OR | String |  | Código da obrigação a recolher |  |
| VL_OR | Float |  | Valor da obrigação a recolher |  |
| DT_VCTO | Date |  | Data de vencimento da obrigação |  |
| COD_REC | String |  | Código de receita referente à obrigação |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `2`=Justiça Estadual `1`=Justiça Federal `0`=SEFAZ |
| DESCPROC | String |  | Descrição resumida do processo que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| MES_REF | Date |  | Mês de Referência |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1960 — EFD Fiscal Registro 1960
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| IND_AP | Integer |  | Indicador da sub-apuração por tipo de benefício |  |
| G1_01 | Float |  | Percentual de crédito presumido |  |
| G1_02 | Float |  | Saídas não incentivadas de PI |  |
| G1_03 | Float |  | Saídas incentivadas de PI |  |
| G1_04 | Float |  | Saídas incentivadas de PI para fora do Nordeste |  |
| G1_05 | Float |  | Saldo devedor do ICMS antes das deduções do incentivo |  |
| G1_06 | Float |  | Saldo devedor do ICMS relativo à faixa incentivada de PI |  |
| G1_07 | Float |  | Crédito presumido nas saídas incentivadas de PI para fora do Nordeste |  |
| G1_08 | Float |  | Saldo devedor relativo à faixa incentivada de PI após o crédito presumido nas saídas para fora do Nordeste |  |
| G1_09 | Float |  | Crédito presumido |  |
| G1_10 | Float |  | Dedução de incentivo da Indústria (crédito presumido) |  |
| G1_11 | Float |  | Saldo devedor do ICMS após deduções |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1970 — EFD Fiscal Registro 1970
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| DTREF | Date |  | Data Referência |  |
| IND_AP | Integer |  | Indicador da sub-apuração por tipo de benefício | `3`=3-Item incentivado (sub-apuração 3) `4`=4-Item incentivado (sub-apuração 4) `5`=5-Item incentivado (sub-apuração 5) `6`=6-Item incentivado (sub-apuração 6) `7`=7-Item incentivado (sub-apuração 7)_(+5)_ |
| ORDEM | Integer |  | Ordem |  |
| REGISTRO | String |  | Registro |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| G3_01 | Float |  | Importações com ICMS diferido |  |
| G3_02 | Float |  | ICMS diferido nas importações |  |
| G3_03 | Float |  | Saídas não incentivadas de PI |  |
| G3_04 | Float |  | Percentual de incentivo nas saídas para fora do Estado |  |
| G3_05 | Float |  | Saídas incentivadas de PI para fora do Estado |  |
| G3_06 | Float |  | ICMS das saídas incentivadas de PI para fora do Estado |  |
| G3_07 | Float |  | Crédito presumido nas saídas para fora do Estado |  |
| G3_T | Float |  | Dedução de incentivo da Importação (crédito presumido) |  |
| G3_08 | Float |  | Saldo devedor do ICMS antes das deduções do incentivo |  |
| G3_09 | Float |  | Saldo devedor do ICMS após deduções do incentivo |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1975 — EFD Fiscal Registro 1975
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| DTREF | Date |  | Data Referência |  |
| IND_AP | Integer |  | Indicador da sub-apuração por tipo de benefício |  |
| ORDEM | Integer |  | Ordem |  |
| REGISTRO | String |  | Registro |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| ALIQ_IMP_BASE | Float |  | Alíquota incidente sobre as importações-base |  |
| G3_10 | Float |  | Saídas incentivadas de PI |  |
| G3_11 | Float |  | Importações-base para o crédito presumido |  |
| G3_12 | Float |  | Crédito presumido nas saídas internas |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF1980 — EFD Fiscal Registro 1980
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| IND_AP | Integer |  | Indicador da sub-apuração por tipo de benefício |  |
| G4_01 | Float |  | Entradas (percentual de incentivo) |  |
| G4_02 | Float |  | Entradas não incentivadas de PI |  |
| G4_03 | Float |  | Entradas incentivadas de PI |  |
| G4_04 | Float |  | Saídas (percentual de incentivo) |  |
| G4_05 | Float |  | Saídas não incentivadas de PI |  |
| G4_06 | Float |  | Saídas incentivadas de PI |  |
| G4_07 | Float |  | Saldo devedor do ICMS antes das deduções do incentivo (PI e itens não incentivados) |  |
| G4_08 | Float |  | Crédito presumido nas entradas incentivadas de PI |  |
| G4_09 | Float |  | Crédito presumido nas saídas incentivadas de PI |  |
| G4_10 | Float |  | Dedução de incentivo da Central de Distribuição (entradas/saídas) |  |
| G4_11 | Float |  | Saldo devedor do ICMS após deduções do incentivo |  |
| G4_12 | Float |  | Índice de recolhimento da central de distribuição |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF9001 — EFD Fiscal Registro 9001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_9 | Integer |  | Qtd. Linhas 9 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF9900 — EFD Fiscal Registro 9900
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| REG_BLC | String |  | Registro que será totalizado no próximo campo |  |
| QTD_REG_BLC | Integer |  | Total de registros do tipo informado no campo anterior |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDF9999 — EFD Fiscal Registro 9999
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| QTD_LIN | Integer |  | Qtd. Linhas |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFB001 — EFD Fiscal Registro B001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_DAD | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_B | Integer |  | Qtd. Linhas B |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFB020 — EFD Fiscal Registro B020
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador do tipo de operação | `1`=Prestação `0`=Aquisição |
| IND_EMIT | String |  | Indicador do emitente do documento | `1`=Terceiros `0`=Emissão própria |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento |  |
| SER | String |  | Série do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| CHV_NFE | String |  | Chave da Nota Fiscal Eletrônica |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| COD_MUN_SERV | String |  | Cód. IBGE onde o serviço foi prestado |  |
| VL_CONT | Float |  | Valor contábil |  |
| VL_MAT_TERC | Float |  | Valor do material fornecido por terceiros na prest. serviço |  |
| VL_SUB | Float |  | Valor da subempreitada |  |
| VL_ISNT_ISS | Float |  | Vlr. Operações isentas ou não tributadas pelo ISS |  |
| VL_DED_BC | Float |  | Vlr da dedução da base de cálculo |  |
| VL_BC_ISS | Float |  | Valor da base de cálculo do ISS |  |
| VL_BC_ISS_RT | Float |  | Vlr. Base de cálculo de retenção do ISS |  |
| VL_ISS_RT | Float |  | Valor do ISS retido pelo tomador |  |
| VL_ISS | Float |  | Valor ISS |  |
| COD_INF_OBS | String |  | Cód. Observação do lançamento |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFB025 — EFD Fiscal Registro B025
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| VL_CONT_P | Float |  | Parcela correspondente ao “Valor Contábil" |  |
| VL_BC_ISS_P | Float |  | Parcela corresp. ao “Vlr. d abase de cálculo ISS |  |
| ALIQ_ISS | Float |  | Alíquota ISS |  |
| VL_ISS_P | Float |  | Parcela correspondente ao “Vlr. do ISS" |  |
| VL_ISNT_ISS_P | Float |  | Parcela correspondente ao “Vlr. Operações isentas ou não tributadas pelo ISS" |  |
| COD_SERV | String |  | Item da lista de serviços |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFB420 — EFD Fiscal Registro B420
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_CONT | Float |  | Valor contábil |  |
| VL_BC_ISS | Float |  | Valor acumulado da base de cálculo do ISS |  |
| ALIQ_ISS | Float |  | Alíquota ISS |  |
| VL_ISNT_ISS | Float |  | Vlr. acumulado das operações isentas ou não-tibutadas pelo ISS |  |
| VL_ISS | Float |  | Valor ISS |  |
| COD_SERV | String |  | Item da lista de serviços |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFB440 — EFD Fiscal Registro B440
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | Integer |  | Indicador do tipo de operação | `1`=Prestação `0`=Aquisição |
| COD_PART | String |  | Cód. Participante |  |
| VL_CONT_RT | Float |  | Totalização do Vlr. Contábil |  |
| VL_BC_ISS_RT | Float |  | Totalização do Vlr. da base de cálcuo de retenção do ISS |  |
| VL_ISS_RT | Float |  | Totalização do Vlr. ISS retido pelo tomador das presetações e/ou aquisições do declarante |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFB460 — EFD Fiscal Registro B460
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_DED | String |  | Indicador do tipo de dedução | `9`=Outros `2`=Decisão administrativa ou judicial `1`=Benefício fiscal por incentivo à cultura `0`=Compensação do ISS calculado a maior |
| VL_DED | Float |  | Valor da dedução |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `2`=Justiça Estadual `1`=Justiça Federal `0`=Sefaz |
| DESCPROC | String |  | Descrição do processo que embasou o lançamento |  |
| COD_INF_OBS | String |  | Código da observação do lançamento fiscal |  |
| IND_OBR | String |  | Indicador da obrigação onde será aplicada a dedução | `2`=ISS Uniprofissionais `1`=ISS Substituto (devido pelas aquisições de serviços do declarante) `0`=ISS Próprio |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFB470 — EFD Fiscal Registro B470
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| VL_CONT | Float |  | Valor total referente às prestações de serviço do período |  |
| VL_MAT_TERC | Float |  | Valor total do material fornecido por terceiros na prest. serviço |  |
| VL_MAT_PROP | Float |  | Valor do material próprio utilizado na prest. serviço |  |
| VL_SUB | Float |  | Valor total das subempreitadas |  |
| VL_ISNT | Float |  | Valor total das operações isentas ou não tributadas pelo ISS |  |
| VL_DED_BC | Float |  | Valor total das deduções da base de cálculo |  |
| VL_BC_ISS | Float |  | Valor total da base de cálculo do ISS |  |
| VL_BC_ISS_RT | Float |  | Valor total da base de cálculo de retenção do ISS ref. às prest. do declarante |  |
| VL_ISS | Float |  | Valor total do ISS destacado |  |
| VL_ISS_RT | Float |  | Valor total do ISS retido pelo tomador nas prest. do declarante |  |
| VL_DED | Float |  | Valor total das deduções do ISS próprio |  |
| VL_ISS_REC | Float |  | Valor total apurado do ISS próprio a recolher |  |
| VL_ISS_ST | Float |  | Valor total do ISS substituto a recolher pelas aquisições do declarante |  |
| VL_ISS_REC_UNI | Float |  | Valor do ISS próprio a recolher pela SU |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC001 — EFD Fiscal Registro C001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_C | Integer |  | Qtd. Linhas C |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC100 — EFD Fiscal Registro C100
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador do tipo de operação | `1`=Saída `0`=Entrada |
| IND_EMIT | String |  | Indicador do emitente do documento fiscal | `1`=Terceiros `0`=Emissão própria |
| COD_PART | String |  | Código do participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| CHV_NFE | String |  | Chave da Nota Fiscal Eletrônica |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| DT_E_S | Date |  | Data da entrada ou da saída |  |
| VL_DOC | Float |  | Valor total do documento fiscal |  |
| IND_PGTO | String |  | Indicador do tipo de pagamento | `9`=Sem pagamento `1`=A prazo `0`=À vista |
| VL_DESC | Float |  | Valor total do desconto |  |
| VL_ABAT_NT | Float |  | Abatimento não tributado e não comercial |  |
| VL_MERC | Float |  | Valor total das mercadorias e serviços |  |
| IND_FRT | String |  | Indicador do tipo do frete | `9`=Sem Ocorrência de Transporte `3`=Transporte Próprio por conta do Remetente `2`=Contratação do Frete por conta de Terceiros `1`=Contratação do Frete por conta do Destinatário (FOB) `0`=Contratação do Frete por conta do Remetente (CIF)_(+1)_ |
| VL_FRT | Float |  | Valor do frete indicado no documento fiscal |  |
| VL_SEG | Float |  | Valor do seguro indicado no documento fiscal |  |
| VL_OUT_DA | Float |  | Valor de outras despesas acessórias |  |
| VL_BC_ICMS | Float |  | Valor da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS |  |
| VL_BC_ICMS_ST | Float |  | Valor da base de cálculo do ICMS substituição tributária |  |
| VL_ICMS_ST | Float |  | Valor do ICMS retido por substituição |  |
| VL_IPI | Float |  | Valor total do IPI |  |
| VL_PIS | Float |  | Valor total do PIS |  |
| VL_COFINS | Float |  | Valor total da COFINS |  |
| VL_PIS_ST | Float |  | Valor total do PIS retido por substituição tributária |  |
| VL_COFINS_ST | Float |  | Valor total da COFINS retido por substituição tributária |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC101 — EFD Fiscal Registro C101
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_FCP_UF_DEST | Float |  | Valor total relativo ao FCP da UF de destino |  |
| VL_ICMS_UF_DEST | Float |  | Valor total do ICMS Interestadual para a UF do destino |  |
| VL_ICMS_UF_REM | Float |  | Valor total do ICMS Interestadual para a UF do remetente |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC110 — EFD Fiscal Registro C110
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_INF | String |  | Cód. Informação complementar |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC111 — EFD Fiscal Registro C111
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| COD_INF | String |  | Código da informação complementar |  |
| REGISTRO | String |  | Registro |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `3`=SECEX/SRF `2`=Justiça Estadual `1`=Justiça Federal `0`=SEFAZ |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC112 — EFD Fiscal Registro C112
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| COD_INF | String |  | Código da informação complementar do documento fiscal |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_DA | String |  | Código do modelo do documento de arrecadação | `1`=GNRE `0`=Documento estadual de arrecadação |
| UF | String |  | UF |  |
| NUM_DA | String |  | Número do documento de arrecadação estadual, |  |
| COD_AUT | String |  | Código completo da autenticação bancária |  |
| VL_DA | Float |  | Valor do total do documento de arrecadação |  |
| DT_VCTO | Date |  | Data de vencimento do documento de arrecadação |  |
| DT_PGTO | Date |  | Data de Pagamento do documento e arrecadação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC113 — EFD Fiscal Registro C113
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| COD_INF | String |  | Cód. Informação |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador do tipo de operação | `1`=Saída/prestação `0`=Entrada/aquisição |
| IND_EMIT | String |  | Indicador do emitente do título | `1`=Terceiros `0`=Emissão própria |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | Integer |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| CHV_DOCE | String |  | Chave do Documento Eletrônico |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC114 — EFD Fiscal Registro C114
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| COD_INF | String |  | Cód. Informação |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do documento fiscal |  |
| ECF_FAB | String |  | Número de série de fabricação do ECF |  |
| ECF_CX | Integer |  | Número do caixa atribuído ao ECF |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC115 — EFD Fiscal Registro C115
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| COD_INF | String |  | Cód. da informação |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_CARGA | Integer |  | Indicador do tipo de transporte | `9`=Outros `5`=Aéreo `4`=Dutoviário `3`=Aquaviário `2`=Rodo-Ferroviário_(+2)_ |
| CNPJ_COL | String |  | Número do CNPJ do contribuinte do local de coleta |  |
| IE_COL | String |  | IE do contribuinte do local de coleta |  |
| CPF_COL | String |  | CPF do contribuinte do local de coleta das mercadorias |  |
| COD_MUN_COL | Integer |  | Código do Município IBGE do local de coleta |  |
| CNPJ_ENTG | String |  | Número do CNPJ do contribuinte do local de entrega |  |
| IE_ENTG | String |  | Inscrição Estadual do contribuinte do local de entrega |  |
| CPF_ENTG | String |  | CPF do contribuinte do local de entrega |  |
| COD_MUN_ENTG | Integer |  | Código do Município IBGE do local de entrega |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC116 — EFD Fiscal Registro C116
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| COD_INF | String |  | Cód. Informação |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| NR_SAT | Integer |  | Número de Série do equipamento SAT |  |
| CHV_CFE | String |  | Chave do Cupom Fiscal Eletrônico |  |
| NUM_CFE | Integer |  | Número do cupom fiscal eletrônico |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC120 — EFD Fiscal Registro C120
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_DOC_IMP | String |  | Documento de importação | `1`=Declaração Simplificada de Importação `0`=Declaração de Importação `2`=Declaração Única de Importação (DUIMP) |
| NUM_DOC_IMP | String |  | Número do documento de Importação |  |
| PIS_IMP | Float |  | Valor pago de PIS na importação |  |
| COFINS_IMP | Float |  | Valor pago de COFINS na importação |  |
| NUM_ACDRAW | String |  | Número do Ato Concessório do regime Drawback |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC130 — EFD Fiscal Registro C130
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_SERV_NT | Float |  | Valor dos serviços sob não-incidência |  |
| VL_BC_ISSQN | Float |  | Valor da base de cálculo do ISSQN |  |
| VL_ISSQN | Float |  | Valor do ISSQN |  |
| VL_BC_IRRF | Float |  | Valor da base de cálculo do Imposto de Renda Retido fonte |  |
| VL_IRRF | Float |  | Valor do Imposto de Renda - Retido na Fonte |  |
| VL_BC_PREV | Float |  | Valor da base de cálculo de retenção da Previdência Social |  |
| VL_PREV | Float |  | Valor destacado para retenção da Previdência Social |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC140 — EFD Fiscal Registro C140
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| IND_EMIT | String |  | Indicador do emitente do título | `1`=Terceiros `0`=Emissão própria |
| IND_TIT | String |  | Indicador do tipo de título de crédito | `99`=Outros (descrever) `03`=Recibo `02`=Promissória `01`=Cheque `00`=Duplicata |
| DESC_TIT | String |  | Descrição complementar do título de créd. |  |
| NUM_TIT | String |  | Número ou código identificador do título de crédito |  |
| QTD_PARC | Integer |  | Quantidade de parcelas a receber/pagar |  |
| VL_TIT | Float |  | Valor total dos títulos de créditos |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC141 — EFD Fiscal Registro C141
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| REGISTRO | String |  | Registro |  |
| NUM_PARC | Integer |  | Número da parcela a receber/pagar |  |
| DT_VCTO | Date |  | Data de vencimento da parcela |  |
| VL_PARC | Float |  | Valor da parcela a receber/pagar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC160 — EFD Fiscal Registro C160
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| VEIC_ID | String |  | Placa de identificação do veículo automotor |  |
| QTD_VOL | String |  | Quantidade de volumes transportados |  |
| PESO_BRT | Float |  | Peso bruto dos volumes transportados (em kg) |  |
| PESO_LIQ | Float |  | Peso líquido dos volumes transportados (em kg) |  |
| UF_ID | String |  | Sigla da UF da placa do veículo |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC170 — EFD Fiscal Registro C170
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Número sequencial do item no documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| DESCR_COMPL | String |  | Descrição complementar do item |  |
| QTD | Float |  | Quantidade do item |  |
| UNID | String |  | Unidade do item |  |
| VL_ITEM | Float |  | Valor total do item |  |
| VL_DESC | Float |  | Valor do desconto comercial |  |
| IND_MOV | String |  | Movimentação física do ITEM/PRODUTO | `1`=Não `0`=Sim |
| CST_ICMS | Integer |  | Código da Situação Tributária ref ICMS |  |
| CFOP | Integer |  | CFOP |  |
| COD_NAT | String |  | Código da natureza da operação |  |
| VL_BC_ICMS | Float |  | Valor da base de cálculo do ICMS |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS creditado/debitado |  |
| VL_BC_ICMS_ST | Float |  | Valor da base de cálculo ref. ST |  |
| ALIQ_ST | Float |  | Alíquota do ST |  |
| VL_ICMS_ST | Float |  | Valor da base de cálculo ref ST |  |
| IND_APUR | String |  | Indicador de período de apuração do IPI | `1`=Decendial `0`=Mensal |
| CST_IPI | String |  | Código da Situação Tributária ref IPI |  |
| COD_ENQ | String |  | Código de enquadramento legal do IPI |  |
| VL_BC_IPI | Float |  | Valor da base de cálculo do IPI |  |
| ALIQ_IPI | Float |  | Alíquota do IPI |  |
| VL_IPI | Float |  | Valor do IPI creditado/debitado |  |
| CST_PIS | Integer |  | Código da Situação Tributária referente ao PIS |  |
| VL_BC_PIS | Float |  | Valor da base de cálculo do PIS |  |
| ALIQ_PIS_PERC | Float |  | Alíquota do PIS (em percentual) |  |
| QUANT_BC_PIS | Integer |  | Quantidade – Base de cálculo PIS |  |
| ALIQ_PIS_REAIS | Float |  | Alíquota do PIS (em reais) |  |
| VL_PIS | Float |  | Valor do PIS |  |
| CST_COFINS | Integer |  | Código da Situação Tributária ref COFINS |  |
| VL_BC_COFINS | Float |  | Valor da base de cálculo da COFINS |  |
| ALIQ_COFINS_PERC | Float |  | Alíquota do COFINS (em percentual) |  |
| QUANT_BC_COFINS | Integer |  | Quantidade – Base de cálculo COFINS |  |
| ALIQ_COFINS_REAIS | Float |  | Alíquota da COFINS (em reais) |  |
| VL_COFINS | Float |  | Valor da COFINS |  |
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| VL_ABAT_NT | Float |  | Valor do abatimento não tributado e não comercial |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC172 — EFD Fiscal Registro C172
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC170 | Integer |  | SEQC170 |  |
| REGISTRO | String |  | Registro |  |
| VL_BC_ISSQN | Float |  | Valor da base de cálculo do ISSQN |  |
| ALIQ_ISSQN | Float |  | Alíquota do ISSQN |  |
| VL_ISSQN | Float |  | Valor do ISSQN |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC173 — EFD Fiscal Registro C173
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC170 | Integer |  | SEQC170 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| LOTE_MED | String |  | Número do lote de fabricação do medicamento |  |
| QTD_ITEM | Float |  | Quantidade de item por lote |  |
| DT_FAB | Date |  | Data de fabricação do medicamento |  |
| DT_VAL | Date |  | Data de expiração da validade do medicamento |  |
| IND_MED | String |  | Indicador de Tipo de Referência da BC do ICMS ST | `4`=4 - Base de cálculo referente à Lista Neutra `3`=3 - Base de cálculo referente à Lista Positiva `2`=2 - Base de cálculo referente à Lista Negativa `1`=1 - Base cálculo – Margem de valor agregado `0`=0 - Base de cálculo referente ao preço tabelado ou preço máximo sugerido |
| TP_PROD | String |  | Tipo de produto | `2`=Ético ou de marca `1`=Genérico `0`=Similar |
| VL_TAB_MAX | Float |  | Valor do preço tabelado ou valor do preço máximo |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC176 — EFD Fiscal Registro C176
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC170 | Integer |  | SEQC170 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD_ULT_E | String |  | Cód. do modelo do doc. fiscal |  |
| NUM_DOC_ULT_E | Integer |  | Nº doc. fiscal relativa a última entrada |  |
| SER_ULT_E | String |  | Série do documento fiscal relativa a última entrada |  |
| DT_ULT_E | Date |  | Data relativa a última entrada da mercadoria |  |
| COD_PART_ULT_E | String |  | Cód. participante |  |
| QUANT_ULT_E | Float |  | Quantidade do item relativa a última entrada |  |
| VL_UNIT_ULT_E | Float |  | Vlr unit. mercadoria constante na NF |  |
| VL_UNIT_BC_ST | Float |  | Valor unitário da base de cálculo do imposto pago por substituição |  |
| CHAVE_NFE_ULT_E | String |  | Número completo da chave da NFe relat. à últ. entrada |  |
| NUM_ITEM_ULT_E | Integer |  | Nº sequencial do item na NF |  |
| VL_UNIT_BC_ICMS_ULT_E | Float |  | Vlr unit. base de cálc. da operação própria à merc. |  |
| ALIQ_ICMS_ULT_E | Float |  | Alíquota do ICMS aplicável à últ. merc. |  |
| VL_UNIT_LIMITE_BC_ICMS_ULT_E | Float |  | Vlr unit. base de cálculo do ICMS |  |
| VL_UNIT_ICMS_ULT_E | Float |  | Valor unitário do crédito de ICMS |  |
| ALIQ_ST_ULT_E | Float |  | Alíquota do ICMS ST relativa à última entrada da mercadoria |  |
| VL_UNIT_RES | Float |  | Valor unitário do ressarcimento |  |
| COD_RESP_RET | Integer |  | Cód. indica o responsável pela retenção do ICMS ST | `3`=Próprio declarante `2`=Remetente Indireto `1`=Remetente Direto `4`=Remetente Direto Simples Nacional |
| COD_MOT_RES | Integer |  | Cód. motivo do ressarcimento | `9`=Outros `6`=Venda interna para Simples Nacional `5`=Exportação `4`=Furto ou roubo `3`=Perda ou deterioração_(+2)_ |
| CHAVE_NFE_RET | String |  | Núm. completo da chave da NF-e emitida pelo substituto |  |
| COD_PART_NFE_RET | String |  | Cód. participante do emitente da NF-e |  |
| SER_NFE_RET | String |  | Série da NF-e em que houve a retenção do ICMS ST |  |
| NUM_NFE_RET | Integer |  | Nº NF-e em que houve a retenção do ICMS ST |  |
| ITEM_NFE_RET | Integer |  | Nº sequencial do item na NF-e |  |
| COD_DA | String |  | Cód. modelo do doc. arrecadação | `1`=GNRE `0`=Documento estadual de arrecadação |
| NUM_DA | String |  | Nº doc. arrecadação estadual |  |
| VL_UNIT_RES_FCP_ST | Float |  | Vlr unit. ressarcimento de FCP |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC177 — EFD Fiscal Registro C177
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC170 | Integer |  | SEQC170 |  |
| REGISTRO | String |  | Registro |  |
| COD_INF_ITEM | String |  | Código da inf. adicional |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC178 — EFD Fiscal Registro C178
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC170 | Integer |  | SEQC170 |  |
| REGISTRO | String |  | Registro |  |
| CL_ENQ | String |  | Cód. da classe de enquadramento do IPI |  |
| VL_UNID | Float |  | Valor por unidade padrão de tributação |  |
| QUANT_PAD | Float |  | Qtd. total de produtos na unid. padrão de trib. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC180 — EFD Fiscal Registro C180
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC170 | Integer |  | SEQC170 |  |
| REGISTRO | String |  | Registro |  |
| COD_RESP_RET | Integer |  | Cod. Ind. Responsável retenção do ICMS ST |  |
| QUANT_CONV | Float |  | Quantidade do item |  |
| UNID | String |  | Unidade do item |  |
| VL_UNIT_CONV | Float |  | Valor Unit. Mercadoria |  |
| VL_UNIT_ICMS_OP_CONV | Float |  | Valor Unit. ICMS |  |
| VL_UNIT_BC_ICMS_ST_CONV | Float |  | Valor Unit. BC. ICMS ST |  |
| VL_UNIT_ICMS_ST_CONV | Float |  | Valor Unit. ICMS ST |  |
| VL_UNIT_FCP_ST_CONV | Float |  | Valor Unit. FCP ST |  |
| COD_DA | String |  | Cod. modelo Doc. Arrecadação |  |
| NUM_DA | String |  | Num. Doc. Arrecadação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC181 — EFD Fiscal Registro C181
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| SEQC170 | Integer |  | SEQC170 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| COD_MOT_REST_COMPL | String |  | Cod. Motivo restituição ou complementação |  |
| QUANT_CONV | Float |  | Quantidade do item |  |
| UNID | String |  | Unidade do item |  |
| COD_MOD_SAIDA | String |  | Cod. Modelo Saida |  |
| SERIE_SAIDA | String |  | Serie saida |  |
| ECF_FAB_SAIDA | String |  | Num. Fabricacao ECF |  |
| NUM_DOC_SAIDA | String |  | Num. Documento saída |  |
| CHV_DFE_SAIDA | String |  | Chave |  |
| NUM_ITEM_SAIDA | Integer |  | Num. item saída |  |
| VL_UNIT_CONV_SAIDA | Float |  | Valor Unit. Saida |  |
| VL_UNIT_ICMS_OP_EST_CONV_SAIDA | Float |  | Valor médio unit. ICMS |  |
| VL_UNIT_ICMS_ST_EST_CONV_SAIDA | Float |  | Valor médio unit. ICMS ST |  |
| VL_UNIT_FCP_ST_EST_CONV_SAIDA | Float |  | Valor médio unit. FCP ICMS ST |  |
| VL_UNIT_ICMS_NA_OP_CONV_SAIDA | Float |  | Valor Unit. ICMS Oper. Saida |  |
| VL_UNIT_ICMS_OP_CONV_SAIDA | Float |  | Valor Unit. ICMS Saida |  |
| VL_UNIT_ICMS_ST_CONV_REST | Float |  | Valor Unit. ICMS ST Oper. Restituído ou Ressarcido |  |
| VL_UNIT_FCP_ST_CONV_REST | Float |  | Valor Unit. FCP ICMS ST |  |
| VL_UNIT_ICMS_ST_CONV_COMPL | Float |  | Valor Unit. estorno do Ressarcimento/restituição |  |
| VL_UNIT_FCP_ST_CONV_COMPL | Float |  | Valor Unit. FCP ICMS ST Complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC185 — EFD Fiscal Registro C185
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUM_ITEM | Integer |  | Número Item |  |
| COD_ITEM | String |  | Cód. Item |  |
| CST_ICMS | Integer |  | Código da Situação Tributária ref ICMS |  |
| CFOP | Integer |  | CFOP |  |
| COD_MOT_REST_COMPL | String |  | Cód. Motivo restituição ou complementação |  |
| QUANT_CONV | Float |  | Quantidade do item |  |
| UNID | String |  | Unidade do item |  |
| VL_UNIT_CONV | Float |  | Valor unit. |  |
| VL_UNIT_ICMS_NA_OP_CONV | Float |  | Valor do ICMS |  |
| VL_UNIT_ICMS_OP_CONV | Float |  | Valor do ICMS por UF |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| VL_UNIT_ICMS_OP_EST_CONV | Float |  | Valor médio unit. do ICMS |  |
| VL_UNIT_ICMS_ST_EST_CONV | Float |  | Valor médio unit. do ICMS ST |  |
| VL_UNIT_FCP_ICMS_ST_EST_CONV | Float |  | Valor médio unit. do FCP ST |  |
| VL_UNIT_ICMS_ST_CONV_REST | Float |  | Valor Total ICMS ST Restituição/Ressarcimento |  |
| VL_UNIT_FCP_ST_CONV_REST | Float |  | Valor unit. ICMS FCP ST Restituição/Ressarcimento |  |
| VL_UNIT_ICMS_ST_CONV_COMPL | Float |  | Valor unit. Compl. ICMS |  |
| VL_UNIT_FCP_ST_CONV_COMPL | Float |  | Valor unit. Compl. ICMS FCP ST |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC186 — EFD Fiscal Registro C186
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODEMP | Integer |  | Empresa |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Número sequencial do item no documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| CST_ICMS | Integer |  | Código da Situação Tributária ref ICMS |  |
| CFOP | Integer |  | CFOP |  |
| COD_MOT_REST_COMPL | String |  | Cód. Motivo restituição ou complementação |  |
| QUANT_CONV | Float |  | Quantidade do item |  |
| UNID | String |  | Unidade do item |  |
| COD_MOD_ENTRADA | String |  | Modelo |  |
| SERIE_ENTRADA | String |  | Série |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| NUM_DOC_ENTRADA | String |  | Número Documento |  |
| CHV_DFE_ENTRADA | String |  | Chave |  |
| DT_DOC_ENTRADA | String |  | Data da emissão do documento fiscal |  |
| NUM_ITEM_ENTRADA | Integer |  | Número sequencial do item no documento fiscal |  |
| VL_UNIT_CONV_ENT | Float |  | Valor Unitário |  |
| VL_UNIT_ICMS_OP_CONV_ENT | Float |  | Valor ICMS |  |
| VL_UNIT_BC_ICMS_ST_CONV_ENT | Float |  | Valor BC. ICMS ST |  |
| VL_UNIT_ICMS_ST_CONV_ENT | Float |  | Valor ICMS ST |  |
| VL_UNIT_FCP_ST_CONV_ENT | Float |  | Valor FCP ST |  |
| SEQUENCIA | Integer |  | Sequência |  |

## TGFEFDFC190 — EFD Fiscal Registro C190
Campos: 19

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
| VL_OPR | Float |  | Vlr operação na comb. CST ICMS, CFOP e alíq. ICMS |  |
| VL_BC_ICMS | Float |  | Parcela correspondente ao "Valor da base de cál. do ICMS" |  |
| VL_ICMS | Float |  | Parcela corresp. ao "Valor do ICMS" |  |
| VL_BC_ICMS_ST | Float |  | Parcela corresp. ao "Valor da base de cálc. do ICMS-ST" |  |
| VL_ICMS_ST | Float |  | Parcela correspondente ao valor créd./déb. do ICMS da ST |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base de cálc. do ICMS |  |
| VL_IPI | Float |  | Parcela correspondente ao "Valor do IPI" |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC191 — EFD Fiscal Registro C191
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC190 | Integer |  | SEQC190 |  |
| REGISTRO | String |  | Registro |  |
| VL_FCP_OP | Float |  | Valor do FCP vinc. à operação própria |  |
| VL_FCP_ST | Float |  | Valor do Fundo de Combate à Pobreza (FCP) vinc. à ST |  |
| VL_FCP_RET | Float |  | Vlr relativo ao FCP retido ant. |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC195 — EFD Fiscal Registro C195
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
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC197 — EFD Fiscal Registro C197
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC195 | Integer |  | SEQC195 |  |
| SEQUENCIA | Integer |  | Sequência |  |
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

## TGFEFDFC300 — EFD Fiscal Registro C300
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | String |  | Subsérie do documento fiscal |  |
| NUM_DOC_INI | Integer |  | Núm. documento fiscal inicial |  |
| NUM_DOC_FIN | Integer |  | Núm. documento fiscal final |  |
| DT_DOC | Date |  | Data da emissão dos documentos fiscais |  |
| VL_DOC | Float |  | Valor total dos documentos |  |
| VL_PIS | Float |  | Valor total do PIS |  |
| VL_COFINS | Float |  | Valor total da COFINS |  |
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC310 — EFD Fiscal Registro C310
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC300 | Integer |  | SEQC300 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NUM_DOC_CANC | String |  | Número do documento fiscal cancelado |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC320 — EFD Fiscal Registro C320
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC300 | Integer |  | SEQC300 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota ICMS |  |
| VL_OPR | Float |  | Valor total acumulado das operações |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor acumulado do ICMS |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base cálc. ICMS |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC321 — EFD Fiscal Registro C321
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC300 | Integer |  | SEQC300 |  |
| SEQC320 | Integer |  | SEQC320 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTD | Float |  | Quantidade |  |
| UNID | String |  | Unidade do item |  |
| VL_ITEM | Float |  | Valor acumulado do item |  |
| VL_DESC | Float |  | Valor do desconto acumulado |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor acumulado do ICMS debitado |  |
| VL_PIS | Float |  | Valor acumulado do PIS |  |
| VL_COFINS | Float |  | Valor acumulado da COFINS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC350 — EFD Fiscal Registro C350
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| SER | String |  | Série do documento fiscal |  |
| SUB_SER | String |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| CNPJ_CPF | String |  | Cnpj |  |
| VL_MERC | Float |  | Valor das mercadorias constantes no doc. fiscal |  |
| VL_DOC | Float |  | Valor total do documento fiscal |  |
| VL_DESC | Float |  | Valor total do desconto |  |
| VL_PIS | Float |  | Valor total do PIS |  |
| VL_COFINS | Float |  | Valor total da COFINS |  |
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC370 — EFD Fiscal Registro C370
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC350 | Integer |  | SEQC350 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Número sequencial do item no documento |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTD | Float |  | Quantidade do item |  |
| UNID | String |  | Unidade do item |  |
| VL_ITEM | Float |  | Valor total do item |  |
| VL_DESC | Float |  | Valor total do desconto no item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC390 — EFD Fiscal Registro C390
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC350 | Integer |  | SEQC350 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota ICMS |  |
| VL_OPR | Float |  | Valor total acumulado das operações |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor acumulado do ICMS |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base cálc. ICMS |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC400 — EFD Fiscal Registro C400
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| ECF_MOD | String |  | Modelo do equipamento |  |
| ECF_FAB | String |  | Número de série de fabricação do ECF |  |
| ECF_CX | Integer |  | Número do caixa atribuído ao ECF |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC405 — EFD Fiscal Registro C405
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC400 | Integer |  | SEQC400 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DT_DOC | Date |  | Data do movimento a que se refere a Redução Z |  |
| CRO | Integer |  | Posição do Contador de Reinício de Operação |  |
| CRZ | Integer |  | Posição do Contador de Redução Z |  |
| NUM_COO_FIN | Integer |  | Número do Contador de Ordem de Operação do último doc |  |
| GT_FIN | Float |  | Valor do Grande Total final |  |
| VL_BRT | Float |  | Valor da venda bruta |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC410 — EFD Fiscal Registro C410
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC400 | Integer |  | SEQC400 |  |
| SEQC405 | Integer |  | SEQC405 |  |
| REGISTRO | String |  | Registro |  |
| VL_PIS | Float |  | Valor total do PIS |  |
| VL_COFINS | Float |  | Valor total da COFINS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC420 — EFD Fiscal Registro C420
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC400 | Integer |  | SEQC400 |  |
| SEQC405 | Integer |  | SEQC405 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_TOT_PAR | String |  | Código do totalizador |  |
| VLR_ACUM_TOT | Float |  | Valor acumulado no totalizador |  |
| NR_TOT | Integer |  | Número do totalizador |  |
| DESCR_NR_TOT | String |  | Descrição da situação tributária |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC425 — EFD Fiscal Registro C425
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC400 | Integer |  | SEQC400 |  |
| SEQC405 | Integer |  | SEQC405 |  |
| SEQC420 | Integer |  | SEQC420 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTD | Float |  | Quantidade acumulada do item |  |
| UNID | String |  | Unidade |  |
| VL_ITEM | Float |  | Valor acumulado do item |  |
| VL_PIS | Float |  | Valor do PIS |  |
| VL_COFINS | Float |  | Valor do COFINS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC460 — EFD Fiscal Registro C460
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC400 | Integer |  | SEQC400 |  |
| SEQC405 | Integer |  | SEQC405 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal (COO) |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| VL_DOC | Float |  | Valor total do documento fiscal |  |
| VL_PIS | Float |  | Valor do PIS |  |
| VL_COFINS | Float |  | Valor da COFINS |  |
| CPF_CNPJ | String |  | Cnpj ou Cpf |  |
| NOM_ADQ | String |  | Nome do adquirente |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC470 — EFD Fiscal Registro C470
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC400 | Integer |  | SEQC400 |  |
| SEQC405 | Integer |  | SEQC405 |  |
| SEQC460 | Integer |  | SEQC460 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTD | Float |  | Quantidade do item |  |
| QTD_CANC | Float |  | Quantidade cancelada |  |
| UNID | String |  | Unidade do item |  |
| VL_ITEM | Float |  | Valor total do item |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota de ICMS |  |
| VL_PIS | Float |  | Valor do PIS |  |
| VL_COFINS | Float |  | Valor do COFINS |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC490 — EFD Fiscal Registro C490
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQC400 | Integer |  | SEQC400 |  |
| SEQC405 | Integer |  | SEQC405 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_OPR | Float |  | Valor da operação |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor acumulado do ICMS |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC495 — EFD Fiscal Registro C495
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chvave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTD | Float |  | Quantidade acumulada do item |  |
| QTD_CANC | Float |  | Quantidade cancelada acumulada |  |
| UNID | String |  | Unidade do item |  |
| VL_ITEM | Float |  | Valor acumulado do item |  |
| VL_DESC | Float |  | Valor acumulado dos descontos |  |
| VL_CANC | Float |  | Valor acumulado dos cancelamentos |  |
| VL_ACMO | Float |  | Valor acumulado dos acréscimos |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor acumulado do ICMS |  |
| VL_ISEN | Float |  | Valor das saídas isentas do ICMS |  |
| VL_NT | Float |  | Valor das saídas sob não-incidência ou não trib. pelo ICMS |  |
| VL_ICMS_ST | Float |  | Valor das saídas de mercadorias adquiridas com ST do ICMS |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC500 — EFD Fiscal Registro C500
Campos: 47

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador do tipo de operação | `0`=Entrada `1`=Saída |
| IND_EMIT | String |  | Indicador do emitente do documento | `1`=Terceiros `0`=Emissão própria |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | String |  | Subsérie do documento fiscal |  |
| COD_CONS | String |  | Código de classe de consumo de energia elétrica ou gás | `08`=Serviço Público `07`=Rural `06`=Residencial `05`=Poder Público `04`=Industrial_(+3)_ |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| DT_E_S | Date |  | Data da entrada ou da saída |  |
| VL_DOC | Float |  | Valor total do documento fiscal |  |
| VL_DESC | Float |  | Valor total do desconto |  |
| VL_FORN | Float |  | Valor total fornecido/consumido |  |
| VL_SERV_NT | Float |  | Valor total dos serviços não-tributados pelo ICMS |  |
| VL_TERC | Float |  | Valor total cobrado em nome de terceiros |  |
| VL_DA | Float |  | Valor total de despesas acessórias indicadas no doc fiscal |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor acumulado do ICMS |  |
| VL_BC_ICMS_ST | Float |  | Valor acumulado da base de cálculo do ICMS ST |  |
| VL_ICMS_ST | Float |  | Valor acumulado do ICMS retido por ST |  |
| COD_INF | String |  | Código da informação complementar |  |
| VL_PIS | Float |  | Valor do PIS |  |
| VL_COFINS | Float |  | Valor do COFINS |  |
| TP_LIGACAO | Integer |  | Código de tipo de Ligação | `1`=Monofásico `3`=Trifásico `2`=Bifásico |
| COD_GRUPO_TENSAO | String |  | Código de grupo de tensão | `14`=B4b - Iluminação Pública - bulbo de lâmpada `13`=B4a - Iluminação Pública - rede de distribuição `10`=B2 - Cooperativa de Eletrificação Rural `09`=B2 - Rural 09 `08`=B1 - Residencial Baixa Renda 08_(+9)_ |
| CHV_DOCE | String |  | Chave da Nota Fiscal de Energia Elétrica Eletrônica |  |
| FIN_DOCE | Integer |  | Finalidade da emissão do documento eletrônico | `2`=Substituição `1`=Normal `3`=Normal com ajuste |
| CHV_DOCE_REF | String |  | Chave da nota referenciada |  |
| IND_DEST | Integer |  | Indicador do Destinatário/Acessante | `1`=Contribuinte do ICMS `2`=Contribuinte Isento de Inscrição no Cad. e Contrib. ICMS `9`=Não Contribuinte |
| COD_MUN_DEST | Integer |  | Código do município IBGE do destinatário |  |
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| COD_MOD_DOC_REF | String |  | Código do modelo do documento fiscal referenciado |  |
| HASH_DOC_REF | String |  | Código de autenticação digital do registro |  |
| SER_DOC_REF | String |  | Série do documento fiscal referenciado |  |
| NUM_DOC_REF | Integer |  | Número do documento fiscal referenciado |  |
| MES_DOC_REF | String |  | Mês e ano da emissão do documento fiscal referenciado |  |
| ENER_INJET | Float |  | Energia injetada |  |
| OUTRAS_DED | Float |  | Outras deduções |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC590 — EFD Fiscal Registro C590
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota de ICMS |  |
| VL_OPR | Float |  | Valor da operação |  |
| VL_BC_ICMS | Float |  | Parcela correspondente ao "Valor da base de cálc. ICMS" |  |
| VL_ICMS | Float |  | Parcela correspondente ao "Valor do ICMS" |  |
| VL_BC_ICMS_ST | Float |  | Parcela correspondente ao "Valor da base de cálc. o ICMS" da ST |  |
| VL_ICMS_ST | Float |  | Parcela correspondente ao valor créd./déb. do ICMS da ST |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base de cálc. do ICMS |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC591 — EFD Fiscal Registro C591
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC590 | Integer |  | SEQC590 |  |
| REGISTRO | String |  | Registro |  |
| VL_FCP_OP | Float |  | Valor do FCP vinculado à operação própria |  |
| VL_FCP_ST | Float |  | Valor do FCP vinculado à operação de ST |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC595 — EFD Fiscal Registro C595
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

## TGFEFDFC597 — EFD Fiscal Registro C597
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQC595 | Integer |  | SEQC595 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ | String |  | Código do ajustes/benefício/incentivo |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste do documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_BC_ICMS | Float |  | Base de cálculo do ICMS ou do ICMS ST |  |
| ALIQ_ICMS | Float |  | Alíquota ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS ou do ICMS ST |  |
| VL_OUTROS | Float |  | Outros valores |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC800 — EFD Fiscal Registro C800
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento fiscal |  |
| NUM_CFE | Integer |  | Número do Cupom Fiscal Eletrônico |  |
| DT_DOC | Date |  | Data da emissão do Cupom Fiscal Eletrônico |  |
| VL_CFE | Float |  | Valor total do Cupom Fiscal Eletrônico |  |
| VL_PIS | Float |  | Valor total do PIS |  |
| VL_COFINS | Float |  | Valor total da COFINS |  |
| CNPJ_CPF | String |  | CNPJ ou CPF |  |
| NR_SAT | Integer |  | Número de Série do equipamento SAT |  |
| CHV_CFE | String |  | Chave do Cupom Fiscal Eletrônico |  |
| VL_DESC | Float |  | Valor total de descontos |  |
| VL_MERC | Float |  | Valor total das mercadorias e serviços |  |
| VL_OUT_DA | Float |  | Valor total de outras despesas acessórias e acréscimos |  |
| VL_ICMS | Float |  | Valor total do ICMS |  |
| VL_PIS_ST | Float |  | Valor total do PIS retido por subst. trib. |  |
| VL_COFINS_ST | Float |  | Valor total da COFINS retido por subst. trib |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC850 — EFD Fiscal Registro C850
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota de ICMS |  |
| VL_OPR | Float |  | “Valor total do CF-e” na combinação de CST_ICMS |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Parcela correspondente ao “Valor do ICMS” |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC855 — EFD Fiscal Registro C855
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| SEQUENCIA | Integer |  | Sequência |  |
| ORDEM | Integer |  | Ordem |  |
| COD_OBS | String |  | Cód. Observação |  |
| DESCCOMPL | String |  | Descrição Complementar |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC857 — EFD Fiscal Registro C857
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODAJUSTE | Integer |  | Código do ajustes/benefício/incentivo |  |
| REGISTRO | String |  | Registro |  |
| CODAJUSTEUF | String |  | Código do ajuste/benefício/incentivo |  |
| DESCCOMPL | String |  | Descrição complementar do ajuste do documento fiscal |  |
| CODITEM | Integer |  | Cód. Item |  |
| BASEICMS | Float |  | Base de cálculo do ICMS ou do ICMS ST |  |
| ALIQ | Float |  | Alíquota do ICMS |  |
| ORDEM | Integer |  | Ordem |  |
| VALORICMS | Float |  | Valor do ICMS ou do ICMS ST |  |
| OUTROSVALORES | Float |  | Outros valores |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC860 — EFD Fiscal Registro C860
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| NR_SAT | Integer |  | Número de Série do equipamento SAT |  |
| DT_DOC | Date |  | Data de emissão doc. fiscais |  |
| DOC_INI | Integer |  | Número do documento inicial |  |
| DOC_FIM | Integer |  | Número do documento final |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC890 — EFD Fiscal Registro C890
Campos: 15

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
| VL_OPR | Float |  | Valor total do CF-e (Vlr. Operação) |  |
| VL_BC_ICMS | Float |  | Valor acumulado da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Parcela correspondente ao "Valor do ICMS" |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC895 — EFD Fiscal Registro C895
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| SEQUENCIA | Integer |  | Sequência |  |
| ORDEM | Integer |  | Ordem |  |
| COD_OBS | String |  | Cód. Observação |  |
| DESCCOMPL | String |  | Descrição Complementar |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFC897 — EFD Fiscal Registro C897
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODAJUSTE | Integer |  | Código do ajustes/benefício/incentivo |  |
| REGISTRO | String |  | Registro |  |
| CODAJUSTEUF | String |  | Código do ajuste/benefício/incentivo |  |
| DESCCOMPL | String |  | Descrição complementar do ajuste do documento fiscal |  |
| CODITEM | Integer |  | Cód. Item |  |
| BASEICMS | Float |  | Base de cálculo do ICMS ou do ICMS ST |  |
| ALIQ | Float |  | Alíquota do ICMS |  |
| ORDEM | Integer |  | Ordem |  |
| VALORICMS | Float |  | Valor do ICMS ou do ICMS ST |  |
| OUTROSVALORES | Float |  | Outros valores |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD001 — EFD Fiscal Registro D001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `0`=Bloco com dados informados `1`=Bloco sem dados informados |
| QTD_LIN_D | Integer |  | Qtd. Linhas D |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD100 — EFD Fiscal Registro D100
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador do tipo de operação | `0`=Aquisição `1`=Prestação |
| IND_EMIT | String |  | Indicador do emitente do documento fiscal | `1`=Terceiros `0`=Emissão própria |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | String |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| CHV_CTE | String |  | Chave do CT-e ou do Bilhete de Passagem Eletrônico |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| DT_A_P | Date |  | Data da aquisição ou da prestação do serviço |  |
| TP_CTE | Integer |  | Tipo de CT-e |  |
| CHV_CTE_REF | String |  | Chave do Bilhete de Passagem Eletrônico substituído |  |
| VL_DOC | Float |  | Valor total do documento fiscal |  |
| VL_DESC | Float |  | Valor total do desconto |  |
| IND_FRT | String |  | Indicador do tipo do frete | `9`=Sem cobrança de frete `2`=Por conta de terceiros `1`=Por conta do destinatário/remetente `0`=Por conta do emitente |
| VL_SERV | Float |  | Valor total da prestação de serviço |  |
| VL_BC_ICMS | Float |  | Valor da base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS |  |
| VL_NT | Float |  | Valor não-tributado |  |
| COD_INF | String |  | Código da informação complementar do documento fiscal |  |
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| COD_MUN_ORIG | Integer |  | Código do município IBGE de origem do serviço |  |
| COD_MUN_DEST | Integer |  | Código do município IBGE de destino |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD101 — EFD Fiscal Registro D101
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| VL_FCP_UF_DEST | Float |  | Valor total relativo ao Fundo de Combate à Pobreza da UF de Destino |  |
| VL_ICMS_UF_DEST | Float |  | Valor total do ICMS Interestadual para a UF de destino |  |
| VL_ICMS_UF_REM | Float |  | Valor total do ICMS Interestadual para a UF do remetente |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD110 — EFD Fiscal Registro D110
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Número sequencial do item no documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_SERV | Float |  | Valor do serviço |  |
| VL_OUT | Float |  | Outros valores |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD120 — EFD Fiscal Registro D120
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| NUM_ITEM | Integer |  | Número sequencial do item no documento fiscal |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MUN_ORIG | Integer |  | Código do município IBGE de origem do serviço |  |
| COD_MUN_DEST | Integer |  | Código do município IBGE de destino |  |
| VEIC_ID | String |  | Placa de identificação do veículo |  |
| UF_ID | String |  | Sigla da UF da placa do veículo |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD130 — EFD Fiscal Registro D130
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARCCONSIGNATARIO | Integer |  | Cód. Parceiro Consignatário |  |
| CODPARCREDESPACHO | Integer |  | Cód. Parceiro Redespacho |  |
| REGISTRO | String |  | Registro |  |
| COD_PART_CONSG | String |  | Código do participante consignatário |  |
| COD_PART_RED | String |  | Código do participante redespachado |  |
| IND_FRT_RED | String |  | Indicador do tipo do frete da operação de redespacho | `9`=Outros `2`=Por conta do destinatário `0`=Sem redespacho `1`=Por conta do emitente |
| COD_MUN_ORIG | Integer |  | Código do município IBGE de origem |  |
| COD_MUN_DEST | Integer |  | Código do município IBGE de destino |  |
| VEIC_ID | String |  | Placa de identificação do veículo |  |
| VL_LIQ_FRT | Float |  | Valor líquido do frete |  |
| VL_SEC_CAT | Float |  | Soma de valores de Sec/Cat |  |
| VL_DESP | Float |  | Soma de valores de despacho |  |
| VL_PEDG | Float |  | Soma dos valores de pedágio |  |
| VL_OUT | Float |  | Outros valores |  |
| VL_FRT | Float |  | Valor total do frete |  |
| UF_ID | String |  | Sigla da UF da placa do veículo |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD160 — EFD Fiscal Registro D160
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DESPACHO | String |  | Identificação do número do despacho |  |
| CNPJ_CPF_REM | String |  | CNPJ ou CPF do remetente das mercadorias que constam na nota fiscal |  |
| IE_REM | String |  | IE do remetente das mercadorias que constam na nota fiscal |  |
| COD_MUN_ORI | Integer |  | Código do Município IBGE de origem |  |
| CNPJ_CPF_DEST | String |  | CNPJ ou CPF do destinatário das mercadorias que constam na nota fiscal |  |
| IE_DEST | String |  | IE do destinatário das mercadorias que constam na nota fiscal |  |
| COD_MUN_DEST | Integer |  | Código do Município IBGE de destino |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD161 — EFD Fiscal Registro D161
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQD160 | Integer |  | SEQD160 |  |
| REGISTRO | String |  | Registro |  |
| IND_CARGA | Integer |  | Indicador do tipo de transporte da carga coletada | `9`=Outros `5`=Aéreo `4`=Dutoviário `2`=Rodo-Ferroviário `1`=Ferroviário_(+2)_ |
| CNPJ_CPF_COL | String |  | Número do CNPJ ou CPF do local da coleta |  |
| IE_COL | String |  | IE do contribuinte do local de coleta |  |
| COD_MUN_COL | Integer |  | Código do Município IBGE do local de coleta |  |
| CNPJ_CPF_ENTG | String |  | Número do CNPJ ou CPF do local da entrega |  |
| IE_ENTG | String |  | Inscrição Estadual do contribuinte do local de entrega |  |
| COD_MUN_ENTG | Integer |  | Código do Município IBGE do local de entrega |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD190 — EFD Fiscal Registro D190
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
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD195 — EFD Fiscal Registro D195
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_OBS | String |  | Código da observação do lançamento fiscal |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD197 — EFD Fiscal Registro D197
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQD195 | Integer |  | SEQD195 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ | String |  | Código do ajustes/benefício/incentivo |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste do documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_BC_ICMS | Float |  | Base de cálculo do ICMS ou do ICMS ST |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS ou do ICMS ST |  |
| VL_OUTROS | Float |  | Outros valores |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD500 — EFD Fiscal Registro D500
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_OPER | String |  | Indicador do tipo de operação | `1`=Prestação `0`=Aquisição |
| IND_EMIT | String |  | Indicador do emitente do documento fiscal | `0`=Emissão própria `1`=Terceiros |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| COD_SIT | Integer |  | Código da situação do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | String |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| DT_A_P | Date |  | Data da entrada (aquisição) ou da saída (prestação do serviço) |  |
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
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| TP_ASSINANTE | Integer |  | Código do Tipo de Assinante | `5`=Semi-Público `4`=Público `3`=Residencial/Pessoa física `2`=Poder Público `1`=Comercial/Industrial_(+1)_ |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD510 — EFD Fiscal Registro D510
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Número sequencial do item no documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| COD_CLASS | Integer |  | Código de classificação do item do serviço de comunicação ou de telecomunicação |  |
| QTD | Float |  | Quantidade do item |  |
| UNID | String |  | Unidade do item |  |
| VL_ITEM | Float |  | Valor do item |  |
| VL_DESC | Float |  | Valor total do desconto |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| VL_BC_ICMS | Float |  | Valor da base de cálculo do ICMS |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_ICMS | Float |  | Valor do ICMS creditado/debitado |  |
| VL_BC_ICMS_UF | Float |  | Valor da base de cálculo do ICMS de outras UFs |  |
| VL_ICMS_UF | Float |  | Valor do ICMS de outras UFs |  |
| IND_REC | String |  | Indicador do tipo de receita | `9`=Outras receitas de terceiros `5`=Receitas de terceiros (co-faturamento) `4`=Outras receitas próprias `2`=Receita própria - venda de mercadorias `1`=Receita própria - cobrança de débitos_(+2)_ |
| COD_PART | String |  | Cód. Participante |  |
| VL_PIS | Float |  | Valor do PIS |  |
| VL_COFINS | Float |  | Valor da COFINS |  |
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD530 — EFD Fiscal Registro D530
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_SERV | String |  | Indicador do tipo de serviço prestado | `9`=Outros `4`=Multimídia `3`=Provimento de acesso à Internet `2`=TV por assinatura `1`=Comunicação de dados_(+1)_ |
| DT_INI_SERV | Date |  | Data em que se iniciou a prestação do serviço |  |
| DT_FIN_SERV | Date |  | Data em que se encerrou a prestação do serviço |  |
| PER_FISCAL | Integer |  | Período fiscal da prestação do serviço |  |
| COD_AREA | String |  | Código de área do terminal faturado |  |
| TERMINAL | String |  | Identificação do terminal faturado |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD590 — EFD Fiscal Registro D590
Campos: 18

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
| VL_BC_ICMS_UF | Float |  | Parcela correspondente ao valor da base de cálculo do ICMS de outras UFs |  |
| VL_ICMS_UF | Float |  | Parcela correspondente ao valor do ICMS de outras UFs |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base de cálculo do ICMS |  |
| COD_OBS | Integer |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD695 — EFD Fiscal Registro D695
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| NRO_ORD_INI | Integer |  | Número de ordem inicial |  |
| NRO_ORD_FIN | Integer |  | Número de ordem final |  |
| DT_DOC_INI | Date |  | Data de emissão inicial dos documentos |  |
| DT_DOC_FIN | Date |  | Data de emissão final dos documentos |  |
| NOM_MEST | String |  | Nome do arquivo Mestre de Documento Fiscal |  |
| CHV_COD_DIG | String |  | Chave de codificação digital do arquivo Mestre de Doc. Fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFD696 — EFD Fiscal Registro D696
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Data Referência |  |
| REGNIV1 | String |  | REGNIV1 |  |
| SEQD695 | Integer |  | SEQD695 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Código da Situação Tributária |  |
| CFOP | Integer |  | CFOP |  |
| ALIQ_ICMS | Float |  | Alíquota do ICMS |  |
| VL_OPR | Float |  | Valor da Operação |  |
| VL_BC_ICMS | Float |  | Parcela correspondente ao "Valor da base de cálculo de ICMS" |  |
| VL_ICMS | Float |  | Parcela correspondente ao "Valor do ICMS" |  |
| VL_BC_ICMS_UF | Float |  | Parcela correspondente ao valor da base de cálculo do ICMS de outras UFs |  |
| VL_ICMS_UF | Float |  | Parcela correspondente ao valor do ICMS de outras UFs |  |
| VL_RED_BC | Float |  | Valor não tributado em função da redução da base de cálc. do ICMS |  |
| COD_OBS | String |  | Cód. Observação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE001 — EFD Fiscal Registro E001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_E | Integer |  | Qtd. Linhas E |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE100 — EFD Fiscal Registro E100
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE110 — EFD Fiscal Registro E110
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE100 | Integer |  | SEQE100 |  |
| REGISTRO | String |  | Registro |  |
| VL_TOT_DEBITOS | Float |  | Valor total dos débitos por "Saídas e prestações com débito do imposto" |  |
| VL_AJ_DEBITOS | Float |  | Valor total dos ajustes a débito decorrentes do doc. fiscal |  |
| VL_TOT_AJ_DEBITOS | Float |  | Valor total de "Ajustes a débito" |  |
| VL_ESTORNOS_CRED | Float |  | Valor total de Ajustes “Estornos de créditos” |  |
| VL_TOT_CREDITOS | Float |  | Valor total dos créditos por "Entradas e aquisições com crédito do imposto" |  |
| VL_AJ_CREDITOS | Float |  | Valor total dos ajustes a crédito decorrentes do doc. fiscal |  |
| VL_TOT_AJ_CREDITOS | Float |  | Valor total de "Ajustes a crédito |  |
| VL_ESTORNOS_DEB | Float |  | Valor total de Ajustes “Estornos de Débitos” |  |
| VL_SLD_CREDOR_ANT | Float |  | Valor total de "Saldo credor do período anterior" |  |
| VL_SLD_APURADO | Float |  | Valor do saldo devedor apurado |  |
| VL_TOT_DED | Float |  | Valor total de "Deduções" |  |
| VL_ICMS_RECOLHER | Float |  | Valor total de "ICMS a recolher (11-12)" |  |
| VL_SLD_CREDOR_TRANSPORTAR | Float |  | Valor total de "Saldo credor a transportar para o período seguinte" |  |
| DEB_ESP | Float |  | Valores recolhidos ou a recolher, extra-apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE111 — EFD Fiscal Registro E111
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE100 | Integer |  | SEQE100 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ_APUR | String |  | Código do ajuste da apuração e dedução |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste da apuração |  |
| VL_AJ_APUR | Float |  | Valor do ajuste da apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE112 — EFD Fiscal Registro E112
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE100 | Integer |  | SEQE100 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQE111 | Integer |  | Sequência E111 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NUM_DA | String |  | Núm.  doc. de arrecadação estadual |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `2`=Justiça Estadual `1`=Justiça Federal `0`=Sefaz |
| DESCPROC | String |  | Descrição resumida do proc. que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE113 — EFD Fiscal Registro E113
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE100 | Integer |  | SEQE100 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQE111 | Integer |  | SEQE111 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | Integer |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_AJ_ITEM | Float |  | Valor do ajuste para a operação/item |  |
| CHV_DOCE | String |  | Chave do Documento Eletrônico |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE115 — EFD Fiscal Registro E115
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE100 | Integer |  | SEQE100 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_INF_ADIC | String |  | Código da informação adicional |  |
| VL_INF_ADIC | Float |  | Valor referente à informação adicional |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE116 — EFD Fiscal Registro E116
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE100 | Integer |  | SEQE100 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_OR | String |  | Código da obrigação a recolher |  |
| VL_OR | Float |  | Valor da obrigação a recolher |  |
| DT_VCTO | Date |  | Data de vencimento da obrigação |  |
| COD_REC | String |  | Código de receita referente à obrigação, |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `2`=Justiça Estadual `1`=Justiça Federal `0`=SEFAZ |
| DESCPROC | String |  | Descrição resumida do processo que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| MES_REF | Date |  | Mês de Referência |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE200 — EFD Fiscal Registro E200
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| UF | String |  | UF |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE210 — EFD Fiscal Registro E210
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE200 | Integer |  | SEQE200 |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV_ST | String |  | Indicador de movimento | `1`=Com operações de ST `0`=Sem operações com ST |
| VL_SLD_CRED_ANT_ST | Float |  | Valor do "Saldo credor de período anterior ST |  |
| VL_DEVOL_ST | Float |  | Valor total do ICMS ST de devolução de mercadorias |  |
| VL_RESSARC_ST | Float |  | Valor total do ICMS ST de ressarcimentos |  |
| VL_OUT_CRED_ST | Float |  | Valor total de Ajustes "Outros créditos ST" e “Estorno de débitos ST” |  |
| VL_AJ_CREDITOS_ST | Float |  | Valor total dos ajustes a crédito de ICMS ST |  |
| VL_RETENCAO_ST | Float |  | Valor Retenção de ST |  |
| VL_OUT_DEB_ST | Float |  | Valor Total dos ajustes "Outros débitos ST" " e “Estorno de créditos ST” |  |
| VL_AJ_DEBITOS_ST | Float |  | Valor total dos ajustes a débito de ICMS ST |  |
| VL_SLD_DEV_ANT_ST | Float |  | Valor total de Saldo devedor antes das deduções |  |
| VL_DEDUCOES_ST | Float |  | Valor total dos ajustes "Deduções ST" |  |
| VL_ICMS_RECOL_ST | Float |  | Imposto a recolher ST |  |
| VL_SLD_CRED_ST_TRANSPORTAR | Float |  | Saldo credor de ST a transportar para o período seguinte |  |
| DEB_ESP_ST | Float |  | Valores recolhidos ou a recolher, extra-apuração |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE220 — EFD Fiscal Registro E220
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE200 | Integer |  | SEQE200 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ_APUR | String |  | Código do ajuste da apuração e dedução |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste da apuração |  |
| VL_AJ_APUR | Float |  | Valor do ajuste da apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE230 — EFD Fiscal Registro E230
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE200 | Integer |  | SEQE200 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQE220 | Integer |  | Sequência E220 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NUM_DA | String |  | Número do documento de arrecadação estadual, |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | Integer |  | Indicador da origem do processo | `2`=Justiça Estadual `1`=Justiça Federal `0`=Sefaz `9`=Outros |
| DESCPROC | String |  | Descrição resumida do processo que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE240 — EFD Fiscal Registro E240
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE200 | Integer |  | SEQE200 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQE220 | Integer |  | SEQE220 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | Integer |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_AJ_ITEM | Float |  | Valor do ajuste para a operação/item |  |
| CHV_DOCE | String |  | Chave do Documento Eletrônico |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE250 — EFD Fiscal Registro E250
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE200 | Integer |  | SEQE200 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_OR | String |  | Código da obrigação a recolher |  |
| VL_OR | Float |  | Valor da obrigação ICMS ST a recolher |  |
| DT_VCTO | Date |  | Data de vencimento da obrigação |  |
| COD_REC | String |  | Código de receita referente à obrigação, |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo | `9`=Outros `2`=Justiça Estadual `1`=Justiça Federal `0`=SEFAZ |
| DESCPROC | String |  | Descrição resumida do processo que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| MES_REF | Date |  | Mês de Referência |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE300 — EFD Fiscal Registro E300
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| UF | String |  | UF |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE310 — EFD Fiscal Registro E310
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE300 | Integer |  | SEQE300 |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV_FCP_DIFAL | String |  | Indicador de movimento | `1`=Com operações de ICMS Diferencial de Alíquota da UF de Origem/Destino `0`=Sem operações com ICMS Diferencial de Alíq. da UF de Origem/Destino |
| VL_SLD_CRED_ANT_DIFAL | Float |  | Valor do "Saldo credor de período anterior |  |
| VL_TOT_DEBITOS_DIFAL | Float |  | Valor total dos débitos por "Saídas e prestações com débitos do ICMS |  |
| VL_OUT_DEB_DIFAL | Float |  | Valor Total dos ajustes "Outros débitos ICMS Difal |  |
| VL_TOT_CREDITOS_DIFAL | Float |  | Valor total dos créditos do ICMS ref. ao dif. de alíq. |  |
| VL_OUT_CRED_DIFAL | Float |  | Valor total de Ajustes "Outros créditos ICMS Difal |  |
| VL_SLD_DEV_ANT_DIFAL | Float |  | Valor total de Saldo devedor ICMS Diferencial de Alíquota |  |
| VL_DEDUCOES_DIFAL | Float |  | Valor total dos ajustes "Deduções ICMS Diferencial de alíquota |  |
| VL_RECOL_DIFAL | Float |  | Valor recolhido ou a recolher referente ao ICMS DIFAL |  |
| VL_SLD_CRED_TRANSPORTAR_DIFAL | Float |  | Saldo credor a transportar para o período seguinte ref ICMS Difal |  |
| DEB_ESP_DIFAL | Float |  | Valores recolhidos ou a recolher, extra-apuração ICMS Dif. Alíquota |  |
| VL_SLD_CRED_ANT_FCP | Float |  | Valor do "Saldo credor de período anterior – FCP" |  |
| VL_TOT_DEB_FCP | Float |  | Valor total dos débitos FCP por "Saídas e prestações" |  |
| VL_OUT_DEB_FCP | Float |  | Valor total dos ajustes "Outros débitos FCP" e "Estorno de créditos FCP" |  |
| VL_TOT_CRED_FCP | Float |  | Valor total dos créditos FCP por Entradas |  |
| VL_OUT_CRED_FCP | Float |  | Valor total dos créditos FCP por Entradas |  |
| VL_SLD_DEV_ANT_FCP | Float |  | Valor total de Saldo devedor FCP antes das deduçoes |  |
| VL_DEDUCOES_FCP | Float |  | Valor total das deduções "FCP" |  |
| VL_RECOL_FCP | Float |  | Valor recolhido ou a recolher referente ao FCP |  |
| VL_SLD_CRED_TRANSPORTAR_FCP | Float |  | Saldo credor a transportar para o período seguinte ref. ao FCP |  |
| DEB_ESP_FCP | Float |  | Valores recolhidos ou a recolher, extra-apuração FCP |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE311 — EFD Fiscal Registro E311
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE300 | Integer |  | SEQE300 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_AJ_APUR | String |  | Código do ajuste da apuração e dedução |  |
| DESCR_COMPL_AJ | String |  | Descrição complementar do ajuste da apuração |  |
| VL_AJ_APUR | Float |  | Valor do ajuste da apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE312 — EFD Fiscal Registro E312
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE300 | Integer |  | SEQE300 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQE311 | Integer |  | SEQE311 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NUM_DA | String |  | Número do documento de arrecadação estadual, |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | Integer |  | Indicador da origem do processo | `9`=Outros `2`=Justiça Estadual `1`=Justiça Federal `0`=Sefaz |
| DESCPROC | String |  | Descrição resumida do processo que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE313 — EFD Fiscal Registro E313
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE300 | Integer |  | Sequência E300 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQE311 | Integer |  | SEQE311 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | Integer |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| CHV_DOC | String |  | Chave do Documento Eletrônico |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_AJ_ITEM | Float |  | Valor do ajuste para a operação/item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE316 — EFD Fiscal Registro E316
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE300 | Integer |  | SEQE300 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| VL_OR | Float |  | Valor da obrigação recolhida ou a recolher |  |
| DT_VCTO | Date |  | Data vencimento |  |
| COD_REC | String |  | Código de receita referente à obrigação, |  |
| NUM_PROC | String |  | Número do processo |  |
| IND_PROC | String |  | Indicador da origem do processo |  |
| DESCPROC | String |  | Descrição resumida do processo que embasou o lançamento |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| MES_REF | Date |  | Mês de Referência |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE500 — EFD Fiscal Registro E500
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_APUR | String |  | Indicador de período de apuração do IPI | `1`=Decendial `0`=Mensal |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE510 — EFD Fiscal Registro E510
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE500 | Integer |  | SEQE500 |  |
| REGISTRO | String |  | Registro |  |
| CFOP | Integer |  | CFOP |  |
| CST_IPI | String |  | Código da Situação Tributária referente ao IPI |  |
| VL_CONT_IPI | Float |  | Parcela correspondente ao "Valor Contábil" |  |
| VL_BC_IPI | Float |  | Parcela correspondente ao "Valor da base de cálculo do IPI" |  |
| VL_IPI | Float |  | Parcela correspondente ao "Valor do IPI" |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE520 — EFD Fiscal Registro E520
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE500 | Integer |  | SEQE500 |  |
| REGISTRO | String |  | Registro |  |
| VL_SD_ANT_IPI | Float |  | Saldo credor do IPI transferido do período anterior |  |
| VL_DEB_IPI | Float |  | Valor total dos débitos por "Saídas com débito do imposto" |  |
| VL_CRED_IPI | Float |  | Valor total dos créditos por "Entradas e aquisições com crédito do imposto" |  |
| VL_OD_IPI | Float |  | Valor de "Outros débitos" do IPI (inclusive estornos de crédito) |  |
| VL_OC_IPI | Float |  | Valor de "Outros créditos" do IPI (inclusive estornos de débitos) |  |
| VL_SC_IPI | Float |  | Valor do saldo credor do IPI a transportar para o período seguinte |  |
| VL_SD_IPI | Float |  | Valor do saldo devedor do IPI a recolher |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE530 — EFD Fiscal Registro E530
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE500 | Integer |  | SEQE500 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| IND_AJ | String |  | Indicador do tipo de ajuste | `1`=Ajuste a crédito `0`=Ajuste a débito |
| VL_AJ | Float |  | Valor do ajuste |  |
| COD_AJ | String |  | Código do ajuste da apuração |  |
| IND_DOC | String |  | Indicador da origem do documento vinculado ao ajuste | `9`=Outros `3`=Documento Fiscal `2`=PER/DCOMP `1`=Processo Administrativo `0`=Processo Judicial |
| NUM_DOC | String |  | Número do documento |  |
| DESCR_AJ | String |  | Descrição detalhada do ajuste, com citação dos documentos fiscais |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFE531 — EFD Fiscal Registro E531
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| SEQE500 | Integer |  | SEQE500 |  |
| REGNIV3 | String |  | Registro Nível 3 |  |
| SEQE530 | Integer |  | SEQE530 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SER | String |  | Série do documento fiscal |  |
| SUB | Integer |  | Subsérie do documento fiscal |  |
| NUM_DOC | Integer |  | Número do documento fiscal |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| VL_AJ_ITEM | Float |  | Valor do ajuste para a operação/item |  |
| CHV_NFE | String |  | Chave da Nota Fiscal Eletrônica |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFG001 — EFD Fiscal Registro G001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `0`=Bloco com dados informados `1`=Bloco sem dados informados |
| QTD_LIN_G | Integer |  | Qtd. linhas G |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFG110 — EFD Fiscal Registro G110
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| SALDO_IN_ICMS | Float |  | Saldo inicial de ICMS do CIAP |  |
| SOM_PARC | Float |  | Somatório das parcelas de ICMS passível de apropriação |  |
| VL_TRIB_EXP | Float |  | Vlr. do somatório das saídas tributadas e saídas para exportação |  |
| VL_TOTAL | Float |  | Valor total de saídas |  |
| IND_PER_SAI | Float |  | Índice de participação do vlr. do somatório das saídas tributadas e saídas para exportação no valor total de saídas |  |
| ICMS_APROP | Float |  | Valor de ICMS a ser apropriado na apuração do ICMS |  |
| SOM_ICMS_OC | Float |  | Vlr. outros créditos a ser apropriado na Apuração do ICMS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFG125 — EFD Fiscal Registro G125
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| COD_IND_BEM | String |  | Código individualizado do bem |  |
| DT_MOV | Date |  | Data da movimentação ou do saldo inicial |  |
| TIPO_MOV | String |  | Tipo de movimentação do bem ou componente | `SI`=Saldo inicial de bens imobilizados `PE`=Perecimento, Extravio ou Deterioração `OT`=Outras Saídas do Imobilizado `MC`=Imobilização oriunda do Ativo Circulante `IM`=Imobilização de bem individual_(+4)_ |
| VL_IMOB_ICMS_OP | Float |  | Valor do ICMS da Operação Própria na entrada do bem ou componente |  |
| VL_IMOB_ICMS_ST | Float |  | Valor do ICMS da Oper. por Sub. Tributária na entrada do bem ou componente |  |
| VL_IMOB_ICMS_FRT | Float |  | Valor do ICMS sobre Frete do Conhecimento de Transporte na entrada do bem ou componente |  |
| VL_IMOB_ICMS_DIF | Float |  | Valor do ICMS - Diferencial de Alíquota, conforme Doc. de Arrecadação, na entrada do bem ou componente |  |
| NUM_PARC | Integer |  | Número da parcela do ICMS |  |
| VL_PARC_PASS | Float |  | Valor da parcela de ICMS passível de apropriação |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFG126 — EFD Fiscal Registro G126
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQG125 | Integer |  | Sequência Reg 125 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| NUM_PARC | Integer |  | Número da parcela do ICMS |  |
| VL_PARC_PASS | Float |  | Vlr parcela de ICMS passível de apropriação |  |
| VL_TRIB_OC | Float |  | Vlr somatório das saídas tribut. e saídas para exportação |  |
| VL_TOTAL | Float |  | Vlr total de saídas no período indicado |  |
| IND_PER_SAI | Float |  | Índice participação do vlr do somatório das saídas |  |
| VL_PARC_APROP | Float |  | Vlr outros créditos de ICMS a ser apropriado na apuração |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFG130 — EFD Fiscal Registro G130
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQG125 | Integer |  | Sequência Reg G125 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| REGISTRO | String |  | Registro |  |
| IND_EMIT | String |  | Indicador do emitente do documento fiscal | `0`=Emissão própria `1`=Terceiros |
| COD_PART | String |  | Cód. Participante |  |
| COD_MOD | String |  | Código do modelo do documento fiscal |  |
| SERIE | String |  | Série |  |
| NUM_DOC | Integer |  | Número de documento fiscal |  |
| CHV_NFE_CTE | String |  | Chave do documento fiscal eletrônico |  |
| DT_DOC | Date |  | Data da emissão do documento fiscal |  |
| NUM_DA | String |  | Núm. documento de arrecadação estadual |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFG140 — EFD Fiscal Registro G140
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| CHAVE | String |  | Chave |  |
| SEQG125 | Integer |  | Sequência Reg G125 |  |
| SEQG130 | Integer |  | Sequência Reg G130 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| NUM_ITEM | Integer |  | Núm. sequencial do item no doc. fiscal |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTDE | Integer |  | Quantidade |  |
| UNID | String |  | Unidade do item |  |
| VL_ICMS_OP_APLICADO | Float |  | Vlr ICMS da Op. Própria na entrada do item |  |
| VL_ICMS_ST_APLICADO | Float |  | Vlr ICMS ST na entrada do item |  |
| VL_ICMS_FRT_APLICADO | Float |  | Vlr ICMS sobre Frete do CT-e na entrada item |  |
| VL_ICMS_DIF_APLICADO | Float |  | Vlr ICMS Diferencial de Alíq. na entrada item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFH001 — EFD Fiscal Registro H001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `0`=Bloco com dados informados `1`=Bloco sem dados informados |
| QTD_LIN_H | Integer |  | Qtd. linhas H |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFH005 — EFD Fiscal Registro H005
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| DT_INV | Date |  | Data do inventário |  |
| VL_INV | Float |  | Valor total do estoque |  |
| MOT_INV | String |  | Motivo do Inventário | `06`=P/ controle das mercadorias sujeita ao reg. de subst. trib. restituição/ressarcimento/complementação `05`=Por determinação dos fiscos `04`=Na alteração regime de pagamento – condição do contri. `02`=Na mudança de forma de tributação da mercadoria (ICMS) `01`=No final no período_(+1)_ |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFH010 — EFD Fiscal Registro H010
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INV | Date |  | Data inventário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| MOT_INV | String |  | Motivo do Inventário | `06`=P/ controle das mercadorias sujeita ao reg. de subst. trib. restituição/ressarcimento/complementação `05`=Por determinação dos fiscos `04`=Na alteração regime de pagamento – condição do contri. `03`=Na solicitação da baixa cadast., paralisação temp. e outros. `02`=Na mudança de forma de tributação da mercadoria (ICMS)_(+1)_ |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Cód. Item |  |
| UNID | String |  | Unidade do item |  |
| QTD | Float |  | Quantidade do item |  |
| VL_UNIT | Float |  | Valor unitário do item |  |
| VL_ITEM | Float |  | Valor item |  |
| IND_PROP | String |  | Indicador de propriedade/posse do item | `2`=Item de propriedade de terceiros em posse do informante `1`=Item de propriedade do informante em posse de terceiros `0`=Item de propriedade do informante e em seu poder |
| COD_PART | String |  | Cód. Participante |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| COD_CTA | String |  | Cód. Conta analítica contábil debitada/creditada |  |
| VL_ITEM_IR | Float |  | Valor do item para efeitos do Imposto de Renda. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFH020 — EFD Fiscal Registro H020
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INV | Date |  | Data inventário |  |
| SEQH010 | Integer |  | SEQH010 |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| CST_ICMS | Integer |  | Cód. ST referente ICMS |  |
| BC_ICMS | Float |  | Base de cálculo do ICMS |  |
| VL_ICMS | Float |  | Valor ICMS a ser debitado ou creditado |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFH030 — EFD Fiscal Registro H030
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INV | Date |  | Data inventário |  |
| SEQH010 | Integer |  | SEQH010 |  |
| VL_ICMS_OP | Float |  | Valor Unitário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| VL_BC_ICMS_ST | Float |  | Base de cálculo do ICMS ST |  |
| VL_ICMS_ST | Float |  | Valor ICMS ST |  |
| VL_FCP | Float |  | Valor FCP |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK001 — EFD Fiscal Registro K001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGISTRO | String |  | Registro |  |
| IND_MOV | String |  | Indicador de movimento | `1`=Bloco sem dados informados `0`=Bloco com dados informados |
| QTD_LIN_K | Integer |  | Qtd. Linhas K |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK010 — EFD Fiscal Registro K010
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| INDTIPLAYOUT | String |  | Indicador de tipo de Layout | `0`=Leiaute simplificado `1`=Leiaute completo `2`=Leiaute restrito aos saldos de estoque |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK100 — EFD Fiscal Registro K100
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| REGISTRO | String |  | Registro |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK200 — EFD Fiscal Registro K200
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_EST | Date |  | Data do estoque final |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTD | Float |  | Quantidade em estoque |  |
| IND_EST | String |  | Indicador do tipo de estoque | `2`=Estoque de propriedade de terceiros e em posse do informante. `1`=Estoque de propriedade do informante e em posse de terceiros `0`=Estoque de propriedade do informante e em seu poder |
| COD_PART | String |  | Cód. Participante |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK210 — EFD Fiscal Registro K210
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_INI_OS | Date |  | Data de início da ordem de serviço |  |
| DT_FIN_OS | Date |  | Data de conclusão da ordem de serviço |  |
| COD_DOC_OS | String |  | Código de identificação da orgem de serviço |  |
| COD_ITEM_ORI | Integer |  | Código item origem |  |
| QTD_ORI | Float |  | Quantidade de origem - saída de estoque |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK215 — EFD Fiscal Registro K215
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| CHAVEPAI | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM_DES | String |  | Código do item do destino(campo 02 do Registro 0200) |  |
| QTD_DES | Float |  | Quantidade de destino - entrada em estoque |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK220 — EFD Fiscal Registro K220
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| CHAVE | String |  | Chave |  |
| REGISTRO | String |  | Registro |  |
| DT_MOV | Date |  | Data da movimentação |  |
| CODPRODDES | String |  | Cód. Produto Destino |  |
| CODPRODORI | String |  | Cód. Produto Origem |  |
| QTD_DES | Float |  | Quantidade de destino - entrada de estoque |  |
| QTD_ORI | Float |  | Quantidade de origem - saída de estoque |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK230 — EFD Fiscal Registro K230
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_INI_OP | Date |  | Data de início da ordem de produção |  |
| DT_FIN_OP | Date |  | Data de conclusão da ordem de produção |  |
| COD_DOC_OP | String |  | Código de identificação da ordem de produção |  |
| COD_ITEM | String |  | Código do item produzido |  |
| QTD_ENC | Float |  | Quantidade de produção acabada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK235 — EFD Fiscal Registro K235
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_SAIDA | Date |  | Dt saída estoque para alocação ao produto |  |
| COD_ITEM | String |  | Cód. item componente/insumo |  |
| QTD | Float |  | Quantidade consumida do item |  |
| COD_INS_SUBST | String |  | Cód. insumo que foi substituído |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK250 — EFD Fiscal Registro K250
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_PROD | Date |  | Data do reconhecimento da produção ocorrida no terceiro |  |
| COD_ITEM | String |  | Código do item produzido |  |
| QTD | Float |  | Quantidade produzida |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK255 — EFD Fiscal Registro K255
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| CHAVE | String |  | CHAVE |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_CONS | Date |  | Data do reconhecimento do consumo do insumo |  |
| COD_ITEM | String |  | Código do insumo |  |
| QTD | Float |  | Quantidade de consumo do insumo |  |
| COD_INS_SUBST | String |  | Código do insumo que foi substituído |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK260 — EFD Fiscal Registro K260
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Fim |  |
| CHAVE | String |  | Chave |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_RET | Date |  | Data de retorno ao estoque (entrada) |  |
| DT_SAIDA | Date |  | Data de saída do estoque |  |
| COD_ITEM | Integer |  | Código do produto/insumo a ser reprocessado/reparado ou já reprocessado/reparado |  |
| COD_OP_OS | String |  | Código de identificação da ordem de produção |  |
| QTDRET | Float |  | Quantidade de retorno ao estoque (entrada) |  |
| QTDSAIDA | Float |  | Quantidade de saída do estoque |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK265 — EFD Fiscal Registro K265
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | Data Início |  |
| DT_FIN | Date |  | Data Final |  |
| CHAVE | String |  | CHAVE |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| COD_ITEM | String |  | Código da mercadoria |  |
| QTDRET | Float |  | Quantidade retornada - entrada em estoque |  |
| QTDSAIDA | Float |  | Quantidade consumida - saída do estoque |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK280 — EFD Fiscal Registro K280
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Parceiro |  |
| CODPROD | Integer |  | Produto |  |
| REGISTRO | String |  | Registro |  |
| DT_EST | Date |  | Dt. estoque final escriturado q está sendo corrigido |  |
| COD_ITEM | String |  | Cód. Item |  |
| QTD_COR_POS | Float |  | Qtd. correção positiva de apontamento ocorrido em período de apuração ant. |  |
| QTD_COR_NEG | Float |  | Qtd. correção negativa de apontamento ocorrido em período de apuração ant. |  |
| IND_EST | String |  | Indicador do tipo de estoque | `2`=Estoque de propriedade de terceiros e em posse do informante `1`=Estoque de propriedade do informante e em posse de terceiros `0`=Estoque de propriedade do informante e em seu poder |
| COD_PART | String |  | Cód. Participante |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK290 — EFD Fiscal Registro K290
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| ORDEM | Integer |  | Ordem |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| IDICOP | Integer |  | Nro. OP Conjunta |  |
| DHINST | Date |  | Data de início da ordem de produção |  |
| DHTERMINO | Date |  | Data de conclusão da ordem de produção |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK291 — EFD Fiscal Registro K291
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| ORDEM | Integer |  | Ordem |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| COD_ITEM | Integer |  | Código do item produzido |  |
| IDICOP | Integer |  | Nro. OP Conjunta |  |
| QTD | Float |  | Quantidade |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFK292 — EFD Fiscal Registro K291
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| REGNIV1 | String |  | Registro Nível 1 |  |
| DT_INI | Date |  | DT_INI |  |
| DT_FIN | Date |  | DT_FIN |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REGISTRO | String |  | Registro |  |
| ORDEM | Integer |  | Ordem |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| COD_ITEM_CON | Integer |  | Código do item consumido |  |
| IDICOP | Integer |  | Nro. OP Conjunta |  |
| QTD | Float |  | Quantidade |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDFPFR — EFD Fiscal Parâmetros
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| DTINI | Date |  | Período Inicial |  |
| DTFIM | Date |  | Período Final |  |
| UF | String |  | UF |  |
| CBXFINALIDADE | String |  | Finalidade de Apresentário do Arquivo | `02`=Remessa do arquivo substituto `01`=Remessa do arquivo original |
| DTINVENTARIO | Date |  | Data do Inventário |  |
| DTK200CTE | Date |  | Data da contagem p/ K200 |  |
| PERFILEFD | String |  | Perfil EFD |  |
| NROUNICO | Integer |  | Nro. Único Nota |  |
| CONFIGOPCOES | C |  | CONFIG OPCÇÕES |  |
| CONFIGREST | C |  | CONFIG RESTITUIÇÕES |  |
| DTINVENTARIOSUBBLOK | Date |  | Data de Inventario em substituição ao Bloco K |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDID695 — EFD Icms Ipi Registro D695
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NOMMEST | String |  | Nome do Arquivo |  |
| REGISTRO | String |  | Registro |  |
| CODMOD | String |  | Modelo Doc. |  |
| SER | String |  | Série |  |
| NROORDINI | Integer |  | Nro. Nota. Inicial |  |
| NROORDFIN | Integer |  | Nro. Nota. Final |  |
| DTDOCINI | DateTime |  | Dt. Emis. Inicial |  |
| DTDOCFIN | DateTime |  | Dt. Emis. Final |  |
| CHVCODDIG | String |  | Chave de Codificação |  |
| CODEMP | Integer |  | Empresa |  |

## TGFEFDISA — Sub Apuração EFD
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| INDSUBAPURACAO | String |  | Indicador Sub-Apuração | `8`=Apuração 6 `7`=Apuração 5 `6`=Apuração 4 `5`=Apuração 3 `4`=Apuração 2_(+1)_ |
| SALDOCREDORICMS | Float |  | Saldo Credor do ICMS |  |
| CODEMP | Integer |  | Cod. Empresa |  |

## TGFEFDVMRSTDIA — Consultar a Média Diária dos Impostos ICMS/ST
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| CODPROD | Integer |  | Produto |  |
| TIPIMPOSTO | String |  | Tipo do Imposto | `S`=ST `I`=ICMS `F`=FCP `B`=BASE ST |
| TIPMEDIA | String |  | Tipo da Média | `I`=Inventário `D`=Diária |
| DTMOV | Date |  | Data do Movimento |  |
| DTCALCULO | Date |  | Data do Cálculo |  |
| QTDTOT | Float |  | Qtd. Inicial do Estoque |  |
| VLRTOT | Float |  | Vlr. Total do Imposto |  |
| VLRUNITMED | Float |  | Vlr. Unit. do Item |  |
| QTDFIM | Float |  | Qtd. Final do Estoque |  |
| VLRFIM | Float |  | Vlr. Final do Imposto |  |
| QTDTOTENT | Float |  | Total das entradas |  |
| QTDTOTSAI | Float |  | Total das saídas |  |
| CODEMP | Integer |  | Empresa |  |