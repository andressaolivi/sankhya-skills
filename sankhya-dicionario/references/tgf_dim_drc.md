# TGF — DIM, DRC, ADR (Obrigações Acessórias Regionais)

> Gerado do dicionário oficial TDD Sankhya. 118 tabelas.


## TGFADRCST — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| QTDCSTCSOSN | Integer |  | Qtd. de caracteres para CST_CSOSN |  |
| USASEQNFISCAL | String |  | Considerar sequência quando não encontrar sequência fiscal | `S`=Sim `N`=Não |
| DESCCAMPOSGER | String |  | Desconsiderar Registros no Processamento |  |
| NCM14101420 | String |  | NCM's dos produtos relacionados aos Registros 1410/1420 |  |
| NCM15101520 | String |  | NCM's dos produtos relacionados aos Registros 1510/1520 |  |
| CODVERSAO | String |  | Código da versão do leiaute do arquivo |  |
| CONSICMSSTCST60 | String |  | Considerar valores do ICMS ST Normal nos itens de entrada com CST 60? | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR0000 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 0000
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| COD_VERSAO | String |  | Código da versão do leiaute do arquivo |  |
| MES_ANO | String |  | Mês e Ano de referência do arquivo |  |
| CNPJ | String |  | CNPJ do estabelecimento declarante |  |
| IE | String |  | Inscrição Estadual do estabelecimento |  |
| CD_FIN | String |  | Código da finalidade do arquivo | `1`=Arquivo substituto `0`=Arquivo original |
| N_REG_ESPECIAL | String |  | Número do regime especial |  |
| CNPJ_CD | String |  | CNPJ do Centro de Distribuição |  |
| IE_CD | String |  | Inscrição  Estadual  do  Centro Distribuição |  |
| REG | String |  | Registro 0000 |  |
| OPCAO_R1200 | String |  | Código para reaver ou recolher o imposto nas saídas para consumidor final (R1200) | `1`=Ressarcimento para fornecedor `0`=Recuperação em conta gráfica `2`=Complementação do Imposto |
| OPCAO_R1300 | String |  | Código para reaver o imposto nas saídas interestaduais (R1300) | `1`=Ressarcimento para fornecedor `0`=Recuperação em conta gráfica |
| OPCAO_R1400 | String |  | Código para reaver o imposto nas saídas de que trata o art.119 do Anexo IX do RICMS/17 (R1400) | `1`=Ressarcimento para fornecedor `0`=Recuperação em conta gráfica |
| OPCAO_R1500 | String |  | Código para reaver o imposto nas saídas destinadas ao Simples Nacional (R1500) | `1`=Ressarcimento para fornecedor `0`=Recuperação em conta gráfica |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1000 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1000
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| IND_FECOP | String |  | Indicador de produto sujeito ao Fundo de Combate à Pobreza | `1`=Produto está sujeito ao FECOP `0`=Produto não está sujeito ao FECOP |
| COD_ITEM | Integer |  | Código do item |  |
| COD_BARRAS | String |  | Código GTIN/EAN Tributável do produto |  |
| COD_ANP | Integer |  | Código conforme tabela ANP |  |
| NCM | String |  | Codigo NCM |  |
| CEST | Integer |  | Código Especificador da Substituição Tributária |  |
| UNID_ITEM | String |  | Informar a unidade de medida utilizada na quantificação do estoque |  |
| ALIQ_ICMS_ITEM | Float |  | Alíquota do ICMS aplicável ao item nas operações internas |  |
| ALIQ_FECOP | Float |  | Alíquota do FECOP |  |
| QTD_TOT_ENTRADA | Float |  | Quantidade total do item adquirido no período |  |
| QTD_TOT_SAIDA | Float |  | Quantidade total de saídas do item no período |  |
| REG | String |  | Registro 1000 |  |
| REGPAI | String |  | Registro Pai |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1010 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1010
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| COD_ITEM | Integer |  | Código do item |  |
| UNID_ITEM | String |  | Informar a unidade de medida utilizada na quantificação do estoque |  |
| QTD | Float |  | Quantidade do produto no estoque |  |
| REG | String |  | Registro 1010 |  |
| VL_TOT_ITEM | Float |  | Valor total do produto |  |
| TXT_COMPL | String |  | Descrição complementar |  |
| REGPAI | String |  | Registro Pai |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1100 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1100
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| COD_ITEM | Integer |  | Código do item |  |
| QTD_TOT_ENTRADA | Float |  | Quantidade total do item adquirido no período |  |
| MENOR_VL_UNIT_ITEM | Float |  | Menor valor unitário do item adquirido no período |  |
| UNID_ITEM | String |  | Quantidade do produto no estoque |  |
| VL_BC_ICMSST_UNIT_MED | Float |  | Valor unitário médio da base de cálculo do ICMS ST |  |
| VL_TOT_ICMS_SUPORT_ENTR | Float |  | Valor total do ICMS do item suportado na entrada |  |
| REG | String |  | Registro 1100 |  |
| VL_UNIT_MED_ICMS_SUPORT_ENTR | Float |  | Valor unitário médio do ICMS suportado na entrada |  |
| REGPAI | String |  | Registro Pai |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1110 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1110
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| COD_RESP_RET | String |  | Código que indica o responsável pela retenção do ICMS-ST | `3`=Próprio declarante `2`=Remetente indireto `1`=Remetente direto |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave  de  acesso  do  documento  fiscal eletrônico |  |
| COD_ITEM | Integer |  | Código do item |  |
| N_NF | Integer |  | Número do documento fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| UF_EMIT | String |  | UF emitente |  |
| CNPJ_DEST | String |  | CNPJ do destinatário |  |
| REG | String |  | Registro 1110 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| NUNOTA | Integer |  | Nota |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| N_ITEM | Integer |  | Número do item do produto no documento fiscal |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| QTD_ENTRADA | Float |  | Quantidade do item adquirido |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| VL_BC_ICMS_ST | Float |  | Base de cálculo do ICMS ST |  |
| VL_ICMS_SUPORT_ENTR | Float |  | Valor do ICMS do item suportado na entrada |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1120 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1120
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave  de  acesso  do  documento eletrônico fiscal |  |
| N_NF | Integer |  | Número do documento fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| UF_EMIT | String |  | UF Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| CNPJ_DEST | String |  | CNPJ do destinatário |  |
| REG | String |  | Registro 1120 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item do produto no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| QTD_DEVOLVIDA | Float |  | Quantidade do item devolvida |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| VL_BC_ICMS_ST | Float |  | Base de cálculo do ICMS ST |  |
| VL_ICMS_SUPORT_ENTR | Float |  | Valor do ICMS do item suportado na entrada |  |
| CHAVE_REF | String |  | Chave  de  acesso  do  documento  fiscal referenciado |  |
| N_ITEM_REF | Integer |  | Número do item no documento fiscal referenciado |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1200 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1200
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| COD_ITEM | Integer |  | Código do item |  |
| QTD_TOT_SAIDA | Float |  | Quantidade total de saídas para consumidor final |  |
| UNID_ITEM | String |  | Informar a unidade de medida utilizada na quantificação do estoque |  |
| VL_TOT_ICMS_EFETIVO | Float |  | Valor total do ICMS efetivo nas saídas para consumidor final |  |
| VL_CONFRONTO_ICMS_ENTRADA | Float |  | Valor de confronto do ICMS das entradas |  |
| RESULT_RECUPERAR_RESSARCIR | Float |  | Resultado do valor a recuperar ou a ressarcir |  |
| RESULT_COMPLEMENTAR | Float |  | Resultado do valor a complementar |  |
| APUR_ICMSST_RECUPERAR_RESSARC | Float |  | Apuração do ICMS ST a recuperar ou a ressarcir |  |
| APUR_ICMSST_COMPLEMENTAR | Float |  | Apuração do ICMS ST a complementar |  |
| APUR_FECOP_RESSARCIR | Float |  | Apuração do FECOP a ressarcir |  |
| REG | String |  | Registro 1200 |  |
| REGPAI | String |  | Registro Pai |  |
| APUR_FECOP_COMPLEMENTAR | Float |  | Apuração do FECOP a complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1210 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1210
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave  de  acesso  do  documento eletrônico fiscal |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_CPF_DEST | String |  | CNPJ ou CPF do destinatário |  |
| REG | String |  | Registro 1210 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| QTD_SAIDA | Float |  | Quantidade do produto na saida |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| VL_ICMS_EFET | Float |  | Valor do ICMS efetivo na saida |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1220 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1220
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave  de  acesso  do  documento eletrônico fiscal |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_CPF_DEST | String |  | CNPJ ou CPF do destinatário |  |
| REG | String |  | UF Emitente |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| QTD_DEVOLVIDA | Float |  | Quantidade do item devolvida |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| VL_ICMS_EFETIVO | Float |  | Valor do ICMS efetivo na saída |  |
| CHAVE_REF | String |  | Chave  de  acesso  do  documento fiscal referenciado |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| N_ITEM_REF | Integer |  | Número do item no documento fiscal referenciado |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1300 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1300
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| QTD_TOT_SAIDA | Float |  | Quantidade total de saídas para outros estados |  |
| COD_ITEM | Integer |  | Código do item |  |
| VL_TOT_ICMS_EFETIVO | Float |  | Valor total do ICMS efetivo nas saídas para outros estados |  |
| VL_CONFRONTO_ICMS_ENTRADA | Float |  | Valor de confronto do ICMS das entradas |  |
| RESULT_RECUPERAR_RESSARCIR | Float |  | Resultado do valor a recuperar ou a ressarcir |  |
| REG | String |  | Registro 1300 |  |
| APUR_ICMSST_RECUPERAR_RESSARC | Float |  | Apuração do ICMS ST a recuperar ou a ressarcir |  |
| APUR_FECOP_RESSARCIR | Float |  | Apuração do FECOP a ressarcir |  |
| REGPAI | String |  | Registro Pai |  |
| UNID_ITEM | String |  | Informar a unidade de medida utilizada na quantificação do estoque |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1310 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1310
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave de acesso do documento fiscal eletrônico |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_CPF_DEST | String |  | CNPJ ou CPF do destinatário |  |
| REG | String |  | Registro 1310 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| QTD_SAIDA | Float |  | Quantidade do produto na saida |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| VL_ICMS_EFET | Float |  | Valor do ICMS efetivo na saida |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1320 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1320
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave  de  acesso  do  documento fiscal eletrônico |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_CPF_DEST | String |  | CNPJ ou CPF do destinatário |  |
| REG | String |  | Registro 1320 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| QTD_DEVOLVIDA | Float |  | Quantidade do item devolvida |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| VL_ICMS_EFET | Float |  | Valor do ICMS efetivo na saida |  |
| CHAVE_REF | String |  | Chave  de  acesso  do  documento fiscal referenciado |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| N_ITEM_REF | Integer |  | Número do item no documento fiscal referenciado |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1400 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1400
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| COD_ITEM | Integer |  | Código do item |  |
| QTD_TOT_SAIDA | Float |  | Quantidade total de saídas para outros estados |  |
| VL_TOT_ICMS_EFETIVO | Float |  | Valor total do ICMS efetivo nas saídas |  |
| REG | String |  | Registro 1400 |  |
| VL_CONFRONTO_ICMS_ENTRADA | Float |  | Valor de confronto do ICMS das entradas |  |
| APUR_ICMSST_RECUPERAR_RESSARC | Float |  | Apuração do ICMS ST a recuperar ou a ressarcir |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| REGPAI | String |  | Registro Pai |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1410 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1410
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave de acesso do documento fiscal eletrônico |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_DEST | String |  | CNPJ do destinatário |  |
| REG | String |  | Registro 1410 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | Integer |  | Unidade de medida do item |  |
| QTD_SAIDA | Float |  | Quantidade do produto na saida |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| VL_ICMS_EFET | Float |  | Valor do ICMS efetivo na saida |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1420 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1420
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave de acesso do documento fiscal eletrônico |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_DEST | String |  | CNPJ do destinatário |  |
| REG | String |  | Registro 1420 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| QTD_DEVOLVIDA | Float |  | Quantidade do item devolvida |  |
| VL_UNIT_ITEM | Float |  | Valor do ICMS efetivo na saida |  |
| VL_ICMS_EFET | Float |  | Quantidade do produto na saida |  |
| CHAVE_REF | String |  | Chave de acesso do documento fiscal referenciado |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| N_ITEM_REF | Integer |  | Número do item no documento fiscal referenciado |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1500 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1500
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| COD_ITEM | Integer |  | Código do item |  |
| QTD_TOT_SAIDA | Float |  | Quantidade total de saídas destinadas a contribuintes do Simples Nacional |  |
| VL_ICMSST_UNIT_ENTR | Float |  | É o valor do ICMS ST a recuperar por unidade |  |
| APUR_ICMSST_RECUPERAR_RESSARC | Float |  | Apuração do ICMS ST a recuperar ou a ressarcir |  |
| REG | String |  | Registro 1500 |  |
| UNID_ITEM | String |  | Informar a unidade de medida utilizada na quantificação do estoque |  |
| MVA_ICMSST | Float |  | MVA da operação |  |
| REGPAI | String |  | Registro Pai |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1510 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1510
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave de acesso do documento fiscal eletrônico |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_DEST | String |  | CNPJ do destinatário |  |
| REG | String |  | Registro 1510 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | String |  | Informar a unidade de medida utilizada na quantificação do estoque |  |
| QTD_SAIDA | Float |  | Quantidade do produto na saída |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1520 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1520
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| DT_DOC | Date |  | Data de Emissão do documento fiscal |  |
| CST_CSOSN | Integer |  | Código da Situação Tributária |  |
| CHAVE | String |  | Chave de acesso do documento fiscal eletrônico |  |
| N_NF | Integer |  | Número do documento Fiscal |  |
| CNPJ_EMIT | String |  | CNPJ Emitente |  |
| COD_ITEM | Integer |  | Código do item |  |
| UF_EMIT | String |  | UF Emitente |  |
| CNPJ_DEST | String |  | CNPJ do destinatário |  |
| REG | String |  | Registro 1520 |  |
| REGPAI | String |  | Registro Pai |  |
| UF_DEST | String |  | UF do Destinatário |  |
| CFOP | Integer |  | Código fiscal de operação e prestação |  |
| N_ITEM | Integer |  | Número do item no documento fiscal |  |
| NUNOTA | Integer |  | Nota |  |
| UNID_ITEM | String |  | Unidade de medida do item |  |
| QTD_DEVOLVIDA | Float |  | Quantidade do item devolvida |  |
| VL_UNIT_ITEM | Float |  | Valor unitário do item |  |
| CHAVE_REF | String |  | Chave de acesso do documento fiscal referenciado |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| N_ITEM_REF | Integer |  | Número do item no documento fiscal referenciado |  |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR1999 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 1999
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| QTD_LIN | Integer |  | Quantidade total de linhas |  |
| REG | String |  | Registro 1999 |  |
| REGPAI | String |  | Registro Pai |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR9000 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 9000
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| REG | String |  | Registro 9000 |  |
| REG1200_ICMSST_RECUPER_RESSARC | Float |  | Valor a recuperar ou a ressarcir nas saídas para consumidor final |  |
| REG1200_ICMSST_COMPLEMENTAR | Float |  | Valor a complementar nas saídas para consumidor final |  |
| REG1300_ICMSST_RECUPER_RESSARC | Float |  | Valor a recuperar ou a ressarcir nas saídas para outros estados |  |
| REGPAI | String |  | Registro Pai |  |
| REG1400_ICMSST_RECUPER_RESSARC | Float |  | Valor a recuperar ou a ressarcir nas saidas de que trata o art. 119 |  |
| REG1500_ICMSST_RECUPER_RESSARC | Float |  | Valor a recuperar ou a ressarcir nas saídas destinadas a contribuinte do Simples Nacional |  |
| REG9000_FECOP_RESSARCIR | Float |  | Valor a ressarcir do FECOP |  |
| REG9000_FECOP_COMPLEMENTAR | Float |  | Valor a complementar do FECOP |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFADRCSTR9999 — Arquivo Digital da Recuperação, do Ressarcimento e da Complementação do ICMS ST Registro 9999
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| QTD_LIN | Integer |  | Quantidade total de linhas do arquivo |  |
| REG | String |  | Registro 9999 |  |
| REGPAI | String |  | Registro Pai |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESC — DIME - Declaração de Informações do ICMS e Movimento Econômico
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CONSDIFAL | String |  | Considerar docs fiscais Op Interna com Valor Difal > 0? | `S`=Sim `N`=Não |
| CONSVLRCONTZERO | String |  | Considerar docs fiscais com Valor Contábil = 0? | `S`=Sim `N`=Não |
| INFANUAL | String |  | Informações Anuais | `S`=Sim `N`=Não |
| INFENCERRAMENTO | String |  | Informações Encerramento de Atividades | `S`=Sim `N`=Não |
| INFREGESPECIAL | String |  | Regime Especial | `S`=Sim `N`=Não |
| QTDTRABALHADOR | Integer |  | Quantidade de trabalhadores na atividade |  |
| TPAPURCONSOLIDA | Integer |  | Apuração Consolidada? | `3`=3 - É um estabelecimento consolidado `2`=2 - É um estabelecimento consolidador `1`=1 - Não é apuração consolidada |
| TPDECLARACAO | Integer |  | Tipo de Declaração | `4`=4 - Enquadramento no Simples Nacional `2`=2 - Encerramento de Atividades `1`=1 - Normal |
| TPESCCONTABIL | Integer |  | Escrita Contábil? | `3`=3 - Sim, dados informados no estabelecimento principal `2`=2 - Não `1`=1 - Sim é o estabelecimento principal |
| TPMOVIMENTO | Integer |  | Indicador de Movimento | `3`=3 - Para Arquivo Com Movimento Independente de Saldos `2`=2 - Para Arquivo Sem Movimento e Com Saldos `1`=1 - Para Arquivo Sem Movimento e Sem Saldos |
| TPREGIME | Integer |  | Regime de Apuração | `9`=9 - Produtor Primário `2`=2 - Normal |
| TPSUBSTIT | Integer |  | Substituto Tributário? | `3`=3 - Substituído solidário `2`=2 - Não `1`=1 - Sim |
| TPTRANSFCREDITO | Integer |  | Transferência de créditos no período? | `5`=5 - Apuração e reserva crédito sistema cooperativo agropecuário `4`=4 - Apurou ou reservou e recebeu créditos `3`=3 - Recebeu créditos `2`=2 - Apurou ou reservou créditos `1`=1 - Não apurou ou reservou nem recebeu créditos |
| CPFCONTADOR | String |  | CPF |  |
| NOMECONTADOR | String |  | Nome do Contador |  |
| INSCESTAD | String |  | Inscrição Estadual |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| REPROCESSATOT | String |  | Reprocessar totalizadores | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG30 — Códigos Ajustes p/ Reg. 30
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Referência |  |
| TPITEM | String |  | Item do quadro | `076`=076 - Segregação dos Débitos Relativos às Saídas com Crédito Presumido `060`=060 - Saldos credores recebidos de estabelecimentos consolidados `036`=036 - Segregação do Crédito Pres. Util. em Subs. Créditos Entradas `020`=020 - Saldos devedores recebidos de estabelecimentos consolidados `038`=038 - Segregação de Outros Créd. Permit. p/ Comp. Com Débito Pela Util. Créd. Presumido |
| CODIGO | String |  | Código |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| TPAJUSTE | String |  | Tipo de Ajuste | `D`=Dedução `null`=Adição |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG33 — Conf. p/ guias Fundo Social / FUMDES Reg. 33
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| TPFUNDORECOLHER | String |  | Tipo Fundo a Recolher | `099`=099 - FUMDES a Recolher `199`=199 - Fundo Social a Recolher |
| CODRECEITA | Integer |  | Cód. Receita |  |
| DIAVENCIMENTO | Integer |  | Dia vencimento |  |
| CODCLASSEVENCIM | Integer |  | Cód. classe vencimento |  |
| NROACORDOTTD | Integer |  | Número acordo TTD |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG48 — Config TOP para Quadro 48-VAF
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código | `9`=009 - Hipótese do artigo 10-B/RICMS-SC, Exportador dos produtos `8`=008 - Fornecedor de alimentos preparados `7`=007 - Depósito/Centro de distrib. Efetuar entrega mercad. vendida p/ outro estab. do mesmo titular `6`=006 - Empresa que opere com o marketing direto `507`=507 - Autoriz. Estabel. trading op. entrada mercad. import. p/ conta/ordem terc. CFOP 1949/2949/3949_(+14)_ |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG81 — 81/91 - Ativo
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código | `159`=159 - Intangível `157`=157 - Diferido (líquido) `155`=155 - Imobilizado (líquido) `151`=151 - Investimentos `148`=148 - Outras contas do realizável_(+6)_ |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG82 — 82/92 - Passivo
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código | `279`=279 - (-) Outras contas do patrimônio líquido `278`=278 - (+) Outras contas do patrimônio líquido `271`=271 - Capital social `269`=269 - Passivo a Descoberto `240`=240 - Resultados de exercícios futuros_(+4)_ |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG83 — 83/93 - DRE
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código | `363`=363 - Participações e contribuições `354`=354 - (+) Provisão para o IR e para a contribuição social `353`=353 - (-) Provisão para o IR e para a contribuição social `345`=345 - Despesas não operacionais `343`=343 - Receitas não operacionais_(+5)_ |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG84 — 84/94 - Despesas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código | `498`=498 - Outras despesas `461`=461 - Despesas financeiras `451`=451 - Serviços profissionais `443`=443 - Fretes e carretos `442`=442 - Seguros_(+10)_ |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCFG85 — 85 - FIA/FEI
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código | `501`=501 - Valor do IRPJ devido no exercício anterior `511`=511 - Contribuição para o FIA por meio de DARE destinado ao Fundo Estadual `512`=512 - Transferência ou contribuição para o FIA direcionados a Fundos Municipais `521`=521 - Contribuição para o FEI por meio de DARE destinado ao Fundo Estadual `522`=522 - Transferência ou contribuição para o FEI direcionados a Fundos Municipais |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCTB81 — Contas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código |  |
| CODCTACTB | Integer |  | Código reduzido |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCTB82 — Contas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código |  |
| CODCTACTB | Integer |  | Código reduzido |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCTB83 — Contas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código |  |
| CODCTACTB | Integer |  | Código reduzido |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCTB84 — Contas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código |  |
| CODCTACTB | Integer |  | Código reduzido |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCCTB85 — 85 - Contas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código |  |
| CODCTACTB | Integer |  | Código reduzido |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR22 — Registro tipo 22 - Valores Fiscais Entradas Documentos Fiscais de Emissão Própria e de Terceiros
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| REGPAI | String |  | Registro Pai |  |
| CODCFO | Integer |  | CFOP |  |
| VLRCTB | Float |  | Vlr. contábil |  |
| BASECALC | Float |  | Base de Cálculo |  |
| IMPOSTOCRED | Float |  | Imposto Creditado |  |
| ISENTASNAOTRIB | Float |  | Isentas/Não Tributadas |  |
| OUTRAS | Float |  | Outras |  |
| BASECALCIMPRET | Float |  | Base Calc. Imp. Retido |  |
| IMPOSTORETIDO | Float |  | Imposto Retido |  |
| DIFALIQUOTA | Float |  | Diferença Alíquota |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR23 — Registro tipo 23 - Valores Fiscais Saídas - Documentos Fiscais de emissão própria
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| REGPAI | String |  | Registro Pai |  |
| CODCFO | Integer |  | CFOP |  |
| VLRCTB | Float |  | Vlr. contábil |  |
| BASECALC | Float |  | Base de Cálculo |  |
| IMPOSTODEBIT | Float |  | Imposto Debitado |  |
| ISENTASNAOTRIB | Float |  | Isentas/Não Tributadas |  |
| OUTRAS | Float |  | Outras |  |
| BASECALCIMPRET | Float |  | Base Calc. Imp. Retido |  |
| IMPOSTORETIDO | Float |  | Imposto Retido |  |
| DIFALIQUOTA | Float |  | Diferença Alíquota |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR24 — Registro tipo 24 - Resumo dos Valores Fiscais Totalizados
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `104`=104 - Saída Imposto Retido `103`=103 - Saída Base de Cálculo Imposto Retido `100`=100 - Outras Operações Sem Débito de Imposto `090`=090 - Saída Operações Isentas/Não Tributadas `080`=080 - Imposto Debitado_(+10)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR25 — Registro tipo 25 - Resumo da Apuração dos Débitos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `990`=990 - Subtotal de Débitos `070`=070 - Outros Débitos `065`=065 - Estorno Crédito Entrada em Decorrência Util. Crédito Presumido `060`=060 - Outros Estornos de Crédito `050`=050 - Estorno de Crédito_(+5)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR26 — Registro tipo 26 - Resumo da Apuração dos Créditos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `990`=990 - Subtotal de Créditos `050`=050 - Crédito de Icms Retido por Subst. Tributária `045`=045 - Crédito da Dif. Alíquota de Oper./Prest. Cons. Final Outro Estado `040`=040 - Crédito por Diferencial de Alíquota Material Uso/Consumo `030`=030 - Crédito de Ativo Permanente_(+2)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR30 — Registro tipo 30 - Calculo do Imposto a Pagar ou Saldo Credor
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `160`=160 - Saldo credor transferível relativo à exportação `150`=150 - Saldo credor transferido ao estabelecimento consolidador `140`=140 - Saldo Credor `130`=130 - Saldo devedor transferido ao estabelecimento consolidador `120`=120 - Saldo devedor_(+23)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR31 — Registro tipo 31 - Débitos Específicos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `990`=990 - Total de débitos `050`=050 - Outros débitos eventuais `040`=040 - Outros débitos por ocasião do fato gerador `030`=030 - Débito por responsabilidade tributárias `020`=020 - Débito relativo a aquisições de atacadistas de outras Unidades da Federação_(+1)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR32 — Registro tipo 32 - Informações Sobre ST
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `070`=070 - Imposto retido com apuração mensal `999`=999 - Imposto a recolher sobre a substituição tributária `998`=998 - Saldo Credor para o mês seguinte `200`=200 - Saldo credor transferido ao estabelecimento consolidador `190`=190 - Saldo Credor_(+14)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR33 — Registro tipo 33 - Pagamentos
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPORIGEMRECOL | Integer |  | Origem Recolhimento | `3`=3 - Débitos Específicos `2`=2 - Substituição Tributária `1`=1 - Imposto `4`=4 - Valores Devidos de Fundos ou Saldo Credor de Fundos |
| CODRECEITA | Integer |  | Cód. Receita |  |
| DTVENCIMENTO | Date |  | Dt. Vencimento |  |
| VLRRECOLHIDO | Float |  | Vlr. Item |  |
| CODCLASSEVENC | Integer |  | Cód. Classe Vencimento |  |
| NROACORDOTTD | Integer |  | Numero Acordo TTD |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR34 — Registro tipo 34 - Difal
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `160`=160 - Saldo Credor a compensar em conta gráfica `150`=150 - Saldo Credor `130`=130 - Saldo devedor a compensar em conta gráfica `120`=120 - Saldo devedor `110`=110 - Total Pagamentos Antecipados_(+7)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR35 — Registro tipo 35 - DAICP
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `199`=199 - Imposto a Recolher pela Utilização do Crédito Presumido `198`=198 - Saldo Credor das Antecipações para o Mês Seguinte `150`=150 - Débito pela utilização do crédito presumido transferido ao estabelecimento consolidador `130`=130 - Total das Antecipações `120`=120 - Crédito decorrente do Pagamento Antecipado do ICMS_(+8)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR36 — Registro tipo 36 - FUMDES
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODTTD | Integer |  | Código TTD |  |
| NROACORDOTTD | String |  | Número TTD |  |
| SUBTIPODCIP | Integer |  | Subtipo DCIP sem exigência de TTD |  |
| BASEICMSEXONERADO | Float |  | Base de Cálculo do ICMS Exonerado |  |
| VLRICMSEXONERADO | Float |  | Valor do ICMS Exonerado |  |
| CODCALCFUMDES | String |  | Código do cálculo FUMDES | `0`=0 - Não exigido na Portaria SEF 143/22 `1`=1 - 2% do ICMS Exonerado |
| VLRFUMDES | Float |  | Valor do FUMDES |  |
| CODCALCFUNDOSOCIAL | String |  | Código do cálculo Fundo Social | `0`=0 - Não exigido na Portaria SEF 143/22 `1`=1 - 2,5% do ICMS Exonerado `2`=2 - 0,4% da BC ICMS - FUMDES `3`=3 - 0,4% da BC ICMS - (FUNDO SOCIAL + FUMDES) `4`=4 - 4,5% do ICMS Exonerado |
| VLRFUNDOSOCIAL | Float |  | Valor do Fundo Social |  |
| BASEICMSDEVOLUCAO | Float |  | Base de cálculo do ICMS Devolução |  |
| VLRICMSEXODEVOL | Float |  | Valor do ICMS Exonerado Devolução |  |
| VLRFUMDESDEVOL | Float |  | Valor do FUMDES Devolução |  |
| VLRFUNDOSOCIALDEVOL | Float |  | Valor do Fundo Social Devolução |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR37 — Registro tipo 37 - Apuração FUMDES
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `010`=010 - Soma Valor Devido aos FUMDES `020`=020 - Saldo Credor do FUMDES Apurado no Mês Anterior `030`=030 - Soma Valor FUMDES Relativo a Devolução `098`=098 - Saldo Credor para o Mês Seguinte FUMDES `099`=099 - FUMDES a Recolher_(+5)_ |
| VLRITEM | Float |  | Vlr. item |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR41 — Registro tipo 41 - Créditos Acumulados
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item | `000`=000 - |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR42 — Registro tipo 42 - Débitos por Reserva de Crédito Acumulado
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item |  |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR46 — Registro tipo 46 - Créditos Especiais
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| SEQUENCIA | Integer |  | Sequência |  |
| IDENTIFICACAO | String |  | Identificação |  |
| VLRCREDUTILAPUR | Float |  | Vlr. Créd. Util. Apur. |  |
| ORIGEM | Integer |  | Origem | `14`=2 - Créditos por DCIP `1`=1 - Crédito por tranferência de créditos |
| TIPCRED | String |  | Tipo de crédito | `S`=ICMS ST `I`=ICMS |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR47 — Registro tipo 47 - Entradas de Extratores, Produtores Agropecuários e Pescadores
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| CODCID | String |  | Cód. Cidade |  |
| VLRCOMPRA | Float |  | Vlr. Compra |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR48 — Registro tipo 48 - Débitos por Reserva de Crédito Acumulado
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| CODCID | String |  | Cód. Cidade |  |
| VLRRECPERC | Float |  | Vlr. Receita ou Percentual Adicionado |  |
| CODTIPATIV | String |  | Tipo de Atividade | `6`=006 - Empresa que opere com o marketing direto `507`=507 - Autoriz. Estabel. trading op. entrada mercad. import. p/ conta/ordem terc. CFOP 1949/2949/3949 `506`=506 - Autoriz. Estabel. trading op. saída mercad. import. p/ conta/ordem terc. CFOP 5949/6949 `505`=505 - Para a transmissão da propriedade do produto final `504`=504 - Para as saídas das partes e peças de um todo_(+14)_ |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR49 — Registro tipo 49 - Entradas por Unidade da Federação
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| UF | String |  | UF | `TO`=TO `SP`=SP `SE`=SE `SC`=SC `RS`=RS_(+22)_ |
| VLRCTB | Float |  | Valor Contábil |  |
| BASECALC | Float |  | Valor Base de Cálculo |  |
| OUTRAS | Float |  | Valor de Outras Entradas |  |
| VLRPETRENERG | Float |  | Valor ICMS por ST em Petróleo/Energia |  |
| OUTROSPROD | Float |  | Valor ICMS por ST em Outros Produtos |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR50 — Registro tipo 50 - Saídas por Unidade da Federação
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| UF | String |  | UF | `TO`=TO `SE`=SE `RS`=RS `RR`=RR `RN`=RN_(+22)_ |
| VLRCTBNAOCONTRIB | Float |  | Valor Contábil Não Contribuinte |  |
| VLRCTBCONTRIB | Float |  | Valor Contábil Contribuinte |  |
| BASECALCNAOCONTRIB | Float |  | Valor Base de Cálculo Não Contribuinte |  |
| BASECALCCONTRIB | Float |  | Valor Base de Cálculo Contribuinte |  |
| OUTRAS | Float |  | Valor de Outras |  |
| ICMSSUBSTIT | Float |  | ICMS Cobrado por ST |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR51 — Registro tipo 51 - Exclusões do Valor Adicionado no Mês
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `020`=020 - 25% das transferências recebidas a preço de venda a varejo `990`=990 - Total dos valores excluídos das saídas `980`=980 - Total dos valores excluídos das entradas `070`=070 - 25% das transferências efetuadas a preço de venda a varejo `060`=060 - Prestação de serviços sujeita ao ISS (Saídas)_(+2)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR80 — Registro tipo 80 - Resumo do Livro Registro de Inventário e Receita Bruta
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `030`=030 - Receita bruta de vendas e serviços `020`=020 - Estoque no fim do exercício `010`=010 - Estoque no início do exercício |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR81 — Registro tipo 81 - Ativo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `111`=111 - Disponibilidades `131`=131 - Contas a receber do realizável `159`=159 - Intangível `157`=157 - Diferido (líquido) `155`=155 - Imobilizado (líquido)_(+10)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR82 — Registro tipo 82 - Passivo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `299`=299 - Total geral do passivo e PL `279`=279 - (-) Outras contas do patrimônio líquido `278`=278 - (+) Outras contas do patrimônio líquido `271`=271 - Capital social `270`=270 - Patrimônio líquido_(+7)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR83 — Registro tipo 83 - DRE
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `399`=399 - Lucro  do exercício `398`=398 - Prejuízo do exercício `363`=363 - Participações e contribuições `361`=361 - Resultado negativo após o I.R. e a contribuição social `354`=354 - (+) Provisão para o IR e para a contribuição social_(+16)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR84 — Registro tipo 84 - Detalhamento das Despesas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `499`=499 - Total `498`=498 - Outras despesas `461`=461 - Despesas financeiras `451`=451 - Serviços profissionais `443`=443 - Fretes e carretos_(+11)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR85 — 85
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `501`=501 - Valor do IRPJ devido no exercício anterior `511`=511 - Contribuição para o FIA por meio de DARE destinado ao Fundo Estadual `512`=512 - Transferência ou contribuição para o FIA direcionados a Fundos Municipais `519`=519 - Total das contribuições ou transferências ao FIA `521`=521 - Contribuição para o FEI por meio de DARE destinado ao Fundo Estadual_(+2)_ |
| VLRITEM | Float |  | Vlr. item |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR90 — Registro tipo 90 - Resumo Liv. Reg. Invent. Rec. Bruta (Enc. de Atividades)
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `030`=030 - Receita bruta de vendas e serviços `020`=020 - Estoque no fim do exercício `010`=010 - Estoque no início do exercício |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR91 — Registro tipo 91 - Ativo (Enc. Atividades)
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `199`=199 - Total geral do ativo `159`=159 - Intangível `157`=157 - Diferido (líquido) `155`=155 - Imobilizado (líquido) `151`=151 - Investimentos_(+10)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR92 — Registro tipo 92 - Passivo (Encerramento de Atividades)
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `299`=299 - Total geral do passivo e PL `279`=279 - (-) Outras contas do patrimônio líquido `278`=278 - (+) Outras contas do patrimônio líquido `271`=271 - Capital social `270`=270 - Patrimônio líquido_(+7)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR93 — Registro tipo 93 - Demonstração de Resultados (Encerramento de Atividades)
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `399`=399 - Lucro  do exercício `398`=398 - Prejuízo do exercício `363`=363 - Participações e contribuições `360`=360 - Resultado após o I.R. e a contribuição social `354`=354 - (+) Provisão para o IR e para a contribuição social_(+16)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR94 — Registro tipo 94 - Det. das Despesas (Encerramento de Atividades)
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| TPITEM | String |  | Item do quadro | `499`=499 - Total `498`=498 - Outras despesas `461`=461 - Despesas financeiras `451`=451 - Serviços profissionais `443`=443 - Fretes e carretos_(+11)_ |
| VLRITEM | Float |  | Vlr. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR98 — Registro tipo 98 - Encerramento Declaração
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| QTDREG | Integer |  | Quantidade de Registros |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCR99 — Registro tipo 99 - Fechamento do Arquivo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| REG | String |  | Registro |  |
| QTDREG | Integer |  | Quantidade de Registros |  |
| QTDDECLARACAOICMS | Integer |  | Quantidade de Declar. ICMS |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIMESCTPO48 — Contas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODIGO | Integer |  | Código |  |
| CODTIPOPER | Integer |  | Tipo de Operação |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDRC — TGFDRC
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cod. Produto |  |
| CODVOL | String |  | Unidade |  |
| CODLOCALORIG | Integer |  | Local |  |
| CODEMP | Integer |  | Empresa |  |
| CONTROLE | String |  | Controle |  |
| QTDESTOQ | Float |  | Qtd. Estoque |  |
| VLRDESTINAR | Float |  | Valor a Destinar |  |
| CUSMEGERAN | Float |  | Custo Médio Gerencial (Antes) |  |
| QTDESTAT | Float |  | Vlr. Estoque (Antes) |  |
| CUSMEGERAP | Float |  | Custo Médio Gerencial (Após) |  |
| QTDESTAP | Float |  | Vlr. Estoque (Após) |  |
| NUDESTINACAO | Integer |  | NUDESTINACAO |  |
| STATUS | String |  | STATUS |  |
| NUNOTA | Integer |  | Nro. Único |  |
| DTREF | Date |  | Data Referência |  |

## TGFDRCST — Demonstrativo p/ Apuração do Ressarcimento de ST
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| VERSAOLAYOUT | Integer |  | Versão do Layout | `9`=009 - Versão 108 - Início 01/01/2015 `8`=008 - Versão 107 - Início 01/01/2014 `7`=007 - Versão 106 - Início 01/01/2013 `6`=006 - Versão 105 - Início 01/07/2012 `5`=005 - Versão 104 - Início 01/01/2012_(+8)_ |
| FINAPRESENTACAO | Integer |  | Finalidade de Apresentação do Arquivo | `1`=1 - Remessa do arquivo substituto `0`=0 - Remessa do arquivo original |
| INDPERFIL | String |  | Perfil de Apresentação do Arquivo | `C`=Perfil C `B`=Perfil B `A`=Perfil A `D`=Perfil D |
| DTINV | Date |  | Dt. do Inventário |  |
| TIPESTOQUE | String |  | Gerar bloco H baseado na | `T`=Contagem `P`=Cópia |
| ARQCONFIRMADO | String |  | Arquivo Confirmado? | `S`=Sim `N`=Não |
| ALIQEFETIVA | Float |  | Alíquota Efetiva do ICMS |  |
| PERMVNDCST60 | String |  | Permitir notas de vendas para SN com CST 60 sem retenção ST no R2113? | `S`=Sim `N`=Não |
| PERCST60SEMVLRANT | String |  | Permite itens de entrada c/ Tributação 60 s/ vlr. ant. informado? | `S`=Trazer sem Valores `N`=Não trazer `V`=Trazer considerando Vlrs do ST Normal |
| LISTNOTASREG2113TIP10 | String |  | Lista de notas reg. 2113 - Venda à consumidor final |  |
| LISTNOTASREG2113TIP20 | String |  | Lista de notas reg. 2113 - Venda p/ outra unidade da federação |  |
| LISTNOTASREG2113TIP30 | String |  | Lista de notas reg. 2113 - Venda para Simples Nacional |  |
| LISTNOTASREG2130 | String |  | Lista de notas reg. 2130 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTAJUSTE — Ajustes Sequência Fiscal p/ Notas de Entrada
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| SERIENOTA | String |  | Série da nota |  |
| CHAVEARQUIVO | String |  | Chave NF-e |  |
| CODPROD | Integer |  | Produto |  |
| SEQUENCIAFISCAL | Integer |  | Sequência Fiscal |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |

## TGFDRCSTR0000 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0000
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODVER | Integer |  | Cód. da Versão do Layout | `9`=009 - Versão 108 - Início 01/01/2015 `8`=008 - Versão 107 - Início 01/01/2014 `7`=007 - Versão 106 - Início 01/01/2013 `6`=006 - Versão 105 - Início 01/07/2012 `5`=005 - Versão 104 - Início 01/01/2012_(+8)_ |
| CODFIN | Integer |  | Cód. da Finalidade do Arquivo | `1`=1 - Remessa do arquivo substituto `0`=0 - Remessa do arquivo original |
| NOME | String |  | Nome Empresarial |  |
| CNPJ | String |  | CNPJ |  |
| CPF | String |  | CPF |  |
| UF | String |  | UF |  |
| IE | String |  | Inscrição Estadual |  |
| CODMUN | Integer |  | Cód. do Município Fiscal |  |
| IM | String |  | Inscrição Municipal |  |
| SUFRAMA | String |  | Inscrição na Entidade SUFRAMA |  |
| INDPERFIL | String |  | Perfil de Apresentação do Arquivo | `C`=Perfil C `B`=Perfil B `A`=Perfil A `D`=Perfil D |
| INDATIV | Integer |  | Indicador de Tipo de Atividade | `1`=1 - Outros `0`=0 - Industrial ou equiparado a industrial |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0001 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| INDMOV | Integer |  | Indicador de Movimento | `1`=1 - Bloco sem dados informados `0`=0 - Bloco com dados informados |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0005 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0005
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| FANTASIA | String |  | Nome Fantasia |  |
| CEP | String |  | CEP |  |
| ENDER | String |  | Endereço |  |
| NUM | String |  | Número |  |
| COMPL | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| FONE | String |  | Telefone |  |
| FAX | String |  | FAX |  |
| EMAIL | String |  | E-mail |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0100 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0100
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| NOME | String |  | Nome do Contador |  |
| CPF | String |  | CPF do Contador |  |
| CRC | String |  | CRC do Contador |  |
| CNPJ | String |  | CNPJ do Contador |  |
| CEP | String |  | CEP |  |
| ENDER | String |  | Endereço |  |
| NUM | String |  | Número |  |
| COMPL | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| FONE | String |  | Telefone |  |
| FAX | String |  | FAX |  |
| EMAIL | String |  | E-mail |  |
| CODMUN | Integer |  | Cód. do Município Fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0150 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0150
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REG | String |  | Registro |  |
| CODEMPPART | Integer |  | Código do Participante |  |
| CODEMP | Integer |  | Código da Empresa |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| RAZAO | String |  | Nome |  |
| CODPAIS | Integer |  | Código País |  |
| CNPJDECLPAR | String |  | CNPJ da Empresa |  |
| CPFCONTADOR | String |  | CPF do Contador |  |
| IE | String |  | Inscrição Estadual |  |
| CODMUNICIPAL | Integer |  | Cód. Municipal |  |
| CODSUFRAMA | String |  | Cód. Suframa |  |
| ENDERECO | String |  | Endereço |  |
| NUMERO | Integer |  | Nro - Endereço |  |
| COMPLEMENTO | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |

## TGFDRCSTR0190 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0190
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| UNID | String |  | Unidade de Medida |  |
| DESCR | String |  | Descrição da Unidade de Medida |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0200 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0200
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| DESCRITEM | String |  | Descrição do Item |  |
| CODBARRA | String |  | Cód. Barra |  |
| CODANTITEM | String |  | Cód. Anterior do Item |  |
| UNIDINV | String |  | Unidade de Medida |  |
| TIPOITEM | String |  | Tipo do Item | `99`=99 - Outras `10`=10 - Outros Insumos `09`=09 - Serviços `08`=08 - Ativo Imobilizado `07`=07 - Material de Uso e Consumo_(+7)_ |
| CODNCM | String |  | NCM |  |
| EXIPI | Integer |  | Cód. Exceção NCM |  |
| CODGEN | Integer |  | Cód. Gênero do Item |  |
| CODLST | Integer |  | Tipo de Serviço |  |
| ALIQICMS | Float |  | Alíquota de ICMS |  |
| CEST | Integer |  | Cód. Especificador ST |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0206 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0206
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI | String |  | Registro Pai |  |
| CODPROD | Integer |  | Produto |  |
| REG | String |  | Registro |  |
| CODCOMB | Integer |  | Código ANP (Combustível) |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0220 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0220
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI | String |  | Registro Pai |  |
| CODPROD | Integer |  | Produto |  |
| REG | String |  | Registro |  |
| UNDCONV | String |  | Unidade de Medida |  |
| FATCONV | Float |  | Fator de Conversão |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR0990 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 0990
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| QTDLIN0 | Integer |  | Qtd. de Linhas do Bloco 0 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2001 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| INDMOV | Integer |  | Indicador de Movimento | `1`=1 - Bloco sem dados informados `0`=0 - Bloco com dados informados |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2100 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2100
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| SVLICMSSTREST | Float |  | Vlr. do ICMS-ST a Restituir |  |
| SVLICMSSTCOMPL | Float |  | Vlr. do ICMS-ST a Complementar |  |
| SDICMSSTREST | Float |  | Saldo do ICMS-ST c/ Direito à Restituição |  |
| SDICMSSTRESS | Float |  | Saldo do ICMS-ST c/ Direito ao Ressarcimento |  |
| SDICMSSTCOMPL | Float |  | Saldo do ICMS-ST a Complementar |  |
| SDICMSOP | Float |  | Saldo do ICMS sobre Operações Próprias |  |
| VAPURCREDICMS | Float |  | Vlr. do Crédito do ICMS |  |
| VAPURICMSCOMP | Float |  | Vlr. do ICMS a Complementar |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2110 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2110
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI | String |  | Registro Pai |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| QTDETVCF | Float |  | Qtd. das Vendas à Cons. Final com ICMS-ST nas Op. Anteriores |  |
| VLTVCF | Float |  | Vlr. das Vendas à Cons. Final com ICMS-ST nas Op. Anteriores |  |
| VLMUNITVCF | Float |  | Vlr. Médio Unitário das Vendas |  |
| VLTBCSTVCF | Float |  | Vlr. da Base de Cálculo da ST Proporcional às Vendas |  |
| VLDIFMAIORBCST | Float |  | Vlr. da Diferença da Maior Base de Cálculo da ST |  |
| VLDIFMENORBCST | Float |  | Vlr. da Diferença da Menor Base de Cálculo da ST |  |
| ALIQEF | Float |  | Alíquota Efetiva do ICMS |  |
| VLICMSSTREST | Float |  | Vlr. do ICMS a Restituir |  |
| VLICMSSTCOMPL | Float |  | Vlr. do ICMS a Complementar |  |
| QTDETINDSOE | Float |  | Qtd. de Saídas p/ Outros Estados c/ Direito ao Ressarcimento |  |
| VLICMSINDSOE | Float |  | Vlr. do ICMS das Saídas p/ Outros Estados |  |
| VLICMSSTINDSOE | Float |  | Vlr. do ICMS-ST das Saídas p/ Outros Estados |  |
| QTDETINDSSN | Float |  | Qtd. de Saídas p/ Optantes do Simples Nacional |  |
| VLTCREDITOMVASN | Float |  | Vlr. do Crédito decorrente das Saídas p/ Optantes do Simples Nacional |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2111 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2111
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| REGPAI | String |  | Registro Pai |  |
| CODPROD | Integer |  | Produto |  |
| REG | String |  | Registro |  |
| CODSITESP | Integer |  | Cód. da Situação Especial | `99`=99 - Outros `1`=1 - Veículo automotor |
| COMPLCODITEM | String |  | Complemento do Cód. Item |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2112 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2112
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |
| CODEMP | Integer |  | Empresa |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| CODPROD | Integer |  | Produto |  |
| REGPAI | String |  | Registro Pai |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| REG | String |  | Registro |  |
| QTDEVCF | Float |  | Qtd. de Vendas |  |
| UNID | String |  | Unidade de Medida |  |
| FATCONV | Float |  | Fator de Conversão |  |
| QTDEVCFC | Float |  | Qtd. de Vendas Convertida p/ Unidade Padrão |  |
| VLVCF | Float |  | Vlr. das Vendas |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMPMOV | Integer |  | Empresa Movimento |  |

## TGFDRCSTR2113 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2113
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |
| CODEMP | Integer |  | Empresa |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| CODPROD | Integer |  | Produto |  |
| REGPAI | String |  | Registro Pai |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| REG | String |  | Registro |  |
| SEQUENCIA | Integer |  | Sequência (Nro. do Item) |  |
| INDOPER | String |  | Indicador do Tipo de Operação | `0`=0 - Saída (Venda) `1`=1 - Devolução de Vendas |
| INDS | Integer |  | Tipo de Operação de Saída | `30`=30 - Venda para Simples Nacional `20`=20 - Venda para outra unidade da federação `10`=10 - Venda à consumidor final |
| CHVNFE | String |  | Chave NF-e |  |
| DTNFE | Date |  | Dt. de Emissão da NF-e |  |
| DTE | Date |  | Dt. de Entrada da Devolução |  |
| CODPARC | Integer |  | Parceiro Destinatário |  |
| CNPJ | String |  | CNPJ do Destinatário |  |
| CPF | String |  | CPF do Destinatário |  |
| QTDEINDS | Float |  | Qtd. do Item |  |
| UNID | String |  | Unidade de Medida |  |
| FATCONV | Float |  | Fator de Conversão |  |
| QTDEINDSC | Float |  | Qtd. do Item Convertida p/ Unidade Padrão |  |
| VLVINDS | Float |  | Vlr. da Mercadoria |  |
| CODCFO | Integer |  | CFOP |  |
| VLCREDITOMVASN | Float |  | Vlr. do Crédito decorrente da Saída p/ Optante do Simples Nacional |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| SEQUENCIAFISCAL | Integer |  | Sequência Fiscal |  |
| CODEMPMOV | Integer |  | Empresa Movimento |  |

## TGFDRCSTR2114 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2114
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI3 | String |  | Registro Terceiro Pai |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| CODPROD | Integer |  | Produto |  |
| REGPAI | String |  | Registro Pai |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQUENCIA | Integer |  | Sequência (Nro. do Item) |  |
| REG | String |  | Registro |  |
| CODPARC | Integer |  | Parceiro Destinatário da NF-e de venda referenciada |  |
| CNPJ | String |  | CNPJ do Destinatário da NF-e de venda referenciada |  |
| CPF | String |  | CPF  do Destinatário da NF-e de venda referenciada |  |
| CHVNFEREF | String |  | Chave NF-e da venda referenciada |  |
| ECFCXREF | Integer |  | Nro. do Caixa atribuído ao ECF |  |
| NUMDOCREF | Integer |  | Nro. do Documento Fiscal |  |
| DTDOCREF | Date |  | Dt. de Emissão do Cupom ou da NF-e de saída referenciada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |

## TGFDRCSTR2120 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2120
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| REGPAI | String |  | Registro Pai |  |
| CODPROD | Integer |  | Produto |  |
| REG | String |  | Registro |  |
| SQTDEC | Float |  | Qtd. da Mercadoria |  |
| SVLBCSTINT | Float |  | Vlr. da Base de Cálculo da ST |  |
| VLMUNITBCST | Float |  | Vlr. Médio Unitário da Base de Cálculo da ST |  |
| SVLICMS | Float |  | Vlr. do ICMS sobre Oper. Próprias |  |
| VLMUNITICMS | Float |  | Vlr. Médio Unitário do ICMS sobre Oper. Próprias |  |
| SVLICMSST | Float |  | Vlr. do ICMS-ST |  |
| VLMUNITICMSST | Float |  | Vlr. Médio Unitário do ICMS-ST |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2121 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2121
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| REGPAI | String |  | Registro Pai |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| SQTDECT | Float |  | Soma Total das Qtd. da Mercadoria |  |
| SVLBCSTINTVLM | Float |  | Soma Vlr. Integrais da Base de Cálculo da ST |  |
| SQTDECVLM | Float |  | Soma Entradas das Qtd. da Mercadoria |  |
| VLMUNITBCSTG | Float |  | Vlr. Médio Unitário da Base de Cálculo da ST |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2130 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2130
Campos: 40

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |
| CODEMP | Integer |  | Empresa |  |
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| CODPROD | Integer |  | Produto |  |
| REGPAI | String |  | Registro Pai |  |
| REG | String |  | Registro |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQUENCIA | Integer |  | Sequência (Nro. do Item) |  |
| INDOPER | String |  | Indicador do Tipo de Operação | `1`=1 - Devolução de Aquisições `0`=0 - Entrada (Aquisição) |
| CHVNFE | String |  | Chave NF-e de entrada |  |
| DTE | Date |  | Dt. de Entrada da Mercadoria |  |
| DTNFE | Date |  | Dt. de Emissão da NF-e de Devolução |  |
| CODPARC | Integer |  | Parceiro Emitente |  |
| CNPJ | String |  | CNPJ do Emitente da NF-e |  |
| CODRESPRET | Integer |  | Responsável pela Retenção do ICMS-ST | `3`=3 - Próprio Declarante `2`=2 - Remetente Indireto `1`=1 - Remetente Direto |
| QTDE | Float |  | Qtd. do Item |  |
| UNID | String |  | Unidade de Medida |  |
| FATCONV | Float |  | Fator de Conversão |  |
| QTDEC | Float |  | Qtd. do Item Convertida p/ Unidade Padrão |  |
| VLE | Float |  | Vlr. da Mercadoria |  |
| CODCFO | Integer |  | CFOP |  |
| VLBCICMS | Float |  | Vlr. da Base de Cálculo da Oper. Própria |  |
| ALIQICMS | Float |  | Alíquota do ICMS |  |
| VLICMS | Float |  | Vlr. do ICMS sobre Oper. Próprias |  |
| VLBCST | Float |  | Vlr. da Base de Cálculo do ICMS pago por ST |  |
| VLBCSTINT | Float |  | Vlr. Integral da Base de Cálculo do ICMS-ST p/ Alíq. Efetiva |  |
| ALIQSTE | Float |  | Alíquota do cálculo de ICMS pago por ST |  |
| ALIQSTEF | Float |  | Alíquota do ICMS Efetiva |  |
| CALICMSST | Float |  | Vlr. do ICMS-ST Calculado |  |
| VLICMSST | Float |  | Vlr. do ICMS-ST |  |
| CODDA | String |  | Cód. do Modelo do Documento de Arrecadação | `1`=1 - GNRE `0`=0 - DARE |
| NUMDARE | String |  | Nro. do DARE |  |
| CODAJ | String |  | Cód. do Ajuste |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| VLRSUBSTANT | Float |  | Vlr. do ICMS da  ST da oper. ant. |  |
| SEQUENCIAFISCAL | Integer |  | Sequência Fiscal |  |
| REGPAI3 | String |  | Registro Terceiro Pai |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| CODEMPMOV | Integer |  | Empresa Movimento |  |

## TGFDRCSTR2131 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2131
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI4 | String |  | Registro Quarto Pai |  |
| REGPAI3 | String |  | Registro Terceiro Pai |  |
| CODPROD | Integer |  | Produto |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| REGPAI | String |  | Registro Pai |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQUENCIA | Integer |  | Sequência (Nro. do Item) |  |
| REG | String |  | Registro |  |
| CHVNFERET | String |  | Chave da NF-e emitida pelo Substituto Tributário |  |
| CODPARC | Integer |  | Parceiro Emitente da NF-e |  |
| CNPJNFERET | String |  | CNPJ do Emitente da NF-e |  |
| NUMITEMNFERET | Integer |  | Nro. do Item da NF-e (Sequência) |  |
| QTDENFERET | Float |  | Qtd. do Item na NF-e |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |

## TGFDRCSTR2131EXT — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2131
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR2132 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2132
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REGPAI4 | String |  | Registro Quarto Pai |  |
| REGPAI3 | String |  | Registro Terceiro Pai |  |
| CODPROD | Integer |  | Produto |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| REGPAI | String |  | Registro Pai |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQUENCIA | Integer |  | Sequência (Nro. do Item) |  |
| REG | String |  | Registro |  |
| CODPARC | Integer |  | Parceiro Emitente da NF-e referenciada |  |
| CNPJ | String |  | CNPJ do Emitente da NF-e referenciada |  |
| CHVNFEREF | String |  | Chave NF-e da Entrada Referenciada |  |
| DTEREF | Date |  | Dt. da Entrada da NF-e referenciada |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |

## TGFDRCSTR2134 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2134
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODPARC | Integer |  | Parceiro Emitente da NF-e |  |
| CODPROD | Integer |  | Produto |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODINDXML | Integer |  | Cod. preenchimento de tag com inf. do ICMS cobrado anteriormente por ST |  |
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| REG | String |  | Registro |  |
| REGPAI | String |  | Registro Pai |  |
| REGPAI2 | String |  | Registro Segundo Pai |  |
| REGPAI3 | String |  | Registro Terceiro Pai |  |
| REGPAI4 | String |  | Registro Quarto Pai |  |
| SEQUENCIA | Integer |  | Sequência (Nro. do Item) |  |
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |

## TGFDRCSTR2990 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 2990
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| QTDLIN2 | Integer |  | Qtd. de Linhas do Bloco 2 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR9001 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 9001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| INDMOV | Integer |  | Indicador de Movimento | `1`=1 - Bloco sem dados informados `0`=0 - Bloco com dados informados |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR9900 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 9900
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| REGBLC | String |  | Registro a ser Totalizado | `H990`=Registro H990 `H010`=Registro H010 `H005`=Registro H005 `H001`=Registro H001 `9999`=Registro 9999_(+24)_ |
| QTDREGBLC | Integer |  | Total do Registro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR9990 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 9990
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| QTDLIN9 | Integer |  | Qtd. de Linhas do Bloco 9 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTR9999 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro 9999
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| QTDLIN | Integer |  | Qtd. Total de Linhas do Arquivo |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTRH001 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro H001
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| INDMOV | Integer |  | Indicador de Movimento | `1`=1 - Bloco sem dados informados `0`=0 - Bloco com dados informados |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTRH005 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro H005
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| DTINV | Date |  | Dt. do Inventário |  |
| VLINV | Float |  | Vlr. Total do Estoque |  |
| MOTINV | String |  | Motivo do Inventário | `05`=05 - Por determinação dos fiscos |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDRCSTRH010 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro H010
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REGPAI | String |  | Registro Pai |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| UNID | String |  | Unidade do Item |  |
| QTD | Float |  | Qtd. do Item |  |
| VLUNIT | Float |  | Vlr. Unitário do Item |  |
| VLITEM | Float |  | Vlr. do Item |  |
| INDPROP | String |  | Indicador de propriedade/posse do Item | `2`=2 - Item de propriedade de terceiros em posse do informante `1`=1 - Item de propriedade do informante em posse de terceiros `0`=0 - Item de propriedade do informante e em seu poder |
| CODPARC | String |  | Parceiro |  |
| TXTCOMPL | String |  | Descrição complementar |  |
| CODCTA | String |  | Cód. Conta Contábil |  |
| VLITEMIR | Float |  | Vlr. do Item p/ Efeitos do IRPF |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CNPJDECLPAR | String |  | CNPJ Declarante/Participante |  |

## TGFDRCSTRH990 — Demonstrativo p/ Apuração do Ressarcimento de ST Registro H990
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| QTDLINH | Integer |  | Qtd. de Linhas do Bloco H |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFLCDPR — Livro Caixa Digital do Produtor Rural
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| CODVER | String |  | Versão do Layout | `0011`=Versão 0011 `0013`=Versão 0013 |
| INDSITINIPER | String |  | Indicador do Início do Período | `2`=Início de obrigatoriedade da escrituração no curso do ano calendário `1`=Abertura `0`=Regular |
| SITESPECIAL | String |  | Indicador de Situação Especial e Outros Eventos | `3`=Saída definitiva do País `2`=Espólio `1`=Falecimento `0`=Normal |
| DTSITESP | Date |  | Data da Situação Especial |  |
| FORMAAPUR | String |  | Forma de Apuração | `2`=Apuração do lucro pelo disposto no art. 5º da Lei nº 8.023, de 1990 `1`=Livro Caixa |
| ARQCONFIRMADO | String |  | Arquivo Confirmado? | `S`=Sim `N`=Não |
| CONSTRUIRHISTQ100 | String |  | Construir histórico do registro Q100 de forma automática? | `S`=Sim `N`=Não |
| CONSIDERANATRATMOVFIN | String |  | Considerar naturezas do rateio da Movimentação Financeira para gerar o Q100? | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Produtor |  |
| CODPARC | Integer |  | Produtor |  |

## TGFLCDPRR0000 — Livro Caixa Digital do Produtor Rural Registro 0000
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| NOMEESC | String |  | Tipo de arquivo |  |
| CODVER | String |  | Versão do Layout | `0011`=Versão 0011 `0013`=Versão 0013 |
| CPF | String |  | CPF do declarante |  |
| NOME | String |  | Nome da pessoa física |  |
| INDSITINIPER | String |  | Indicador do Início do Período | `2`=Início de obrigatoriedade da escrituração no curso do ano calendário `1`=Abertura `0`=Regular |
| CODPARC | Integer |  | Produtor |  |
| SITESPECIAL | String |  | Indicador de Situação Especial e Outros Eventos | `3`=Saída definitiva do País `2`=Espólio `1`=Falecimento `0`=Normal |
| DTSITESP | Date |  | Data da Situação Especial |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRR0010 — Livro Caixa Digital do Produtor Rural Registro 0010
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| FORMAAPUR | String |  | Forma de Apuração | `1`=Livro Caixa `2`=Apuração do lucro pelo disposto no art. 5º da Lei nº 8.023, de 1990 |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODPARC | Integer |  | Produtor |  |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRR0030 — Livro Caixa Digital do Produtor Rural Registro 0030
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEND | Integer |  | Endereço da pessoa física |  |
| NUM | String |  | Número |  |
| COMPL | String |  | Complemento |  |
| REG | String |  | Registro |  |
| CODBAI | Integer |  | Bairro/Distrito |  |
| CEP | String |  | CEP |  |
| CODMUN | Integer |  | Município |  |
| UF | Integer |  | Estado |  |
| NUMTEL | String |  | Telefone |  |
| CODPARC | Integer |  | Produtor |  |
| EMAIL | String |  | Email |  |
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRR0040 — Livro Caixa Digital do Produtor Rural Registro 0040
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODIMOVEL | Integer |  | Código Sequencial do Imóvel |  |
| PAIS | String |  | País |  |
| MOEDA | String |  | Moeda |  |
| CADITR | String |  | CAFIR (Com DV) |  |
| CAEPF | String |  | Cadastro de Atividade Econômica da Pessoa Física |  |
| CODPARC | Integer |  | Produtor |  |
| INSCRESTADUAL | String |  | Inscrição Estadual |  |
| NOMEIMOVEL | String |  | Nome do Imóvel |  |
| NUM | String |  | Número |  |
| COMPL | String |  | Complemento |  |
| UF | Integer |  | Estado |  |
| CODMUN | Integer |  | Município |  |
| CEP | String |  | CEP |  |
| TIPOEXPLORACAO | String |  | Tipo de Exploração do Imóvel | `6`=Outros `5`=Comodato `3`=Imóvel arrendado `2`=Condomínio `1`=Exploração individual (Imóvel próprio)_(+1)_ |
| CODEND | Integer |  | Endereço do Imóvel |  |
| PARTICIPACAO | Float |  | Participação em percentual na exploração do Imóvel |  |
| CODBAI | Integer |  | Bairro/Distrito |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRR0045 — Livro Caixa Digital do Produtor Rural Registro 0045
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| REGPAI | String |  | Registro Pai |  |
| CODIMOVEL | Integer |  | Código Sequencial do Imóvel |  |
| TIPOCONTRAPARTE | String |  | Tipo de terceiro relacionado ao imóvel | `5`=Outro `3`=Parceiro `2`=Arrendador `1`=Condômino `4`=Comodante |
| CPFCONTRAPARTE | String |  | Número do CPF/CNPJ do terceiro que explora em conjunto ou do arrendador/comodante do imóvel rural |  |
| NOMECONTRAPARTE | String |  | Nome do terceiro que explora em conjunto ou do arrendador/comodante do imóvel rural |  |
| CODPARC | Integer |  | Produtor |  |
| PERCCONTRAPARTE | Float |  | Percentual de participação na exploração do imóvel |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRR0050 — Livro Caixa Digital do Produtor Rural Registro 0050
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODCONTA | String |  | Código da conta bancária |  |
| PAISCTA | String |  | Código de identificação do país |  |
| BANCO | String |  | Número código de compensação da instituição financeira |  |
| NOMEBANCO | String |  | Nome da Instituição Financeira |  |
| AGENCIA | String |  | Número da Agência Bancária (Sem dígito verificador) |  |
| CODPARC | Integer |  | Produtor |  |
| NUMCONTA | String |  | Número da Conta com dígito verificador |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRR9999 — Livro Caixa Digital do Produtor Rural Registro 9999
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| IDENTNOM | String |  | Nome do Contador |  |
| IDENTCPFCNPJ | String |  | CPF/CNPJ do Contador |  |
| INDCRC | String |  | Número de inscrição do Contador no CRC |  |
| EMAIL | String |  | Email do Contador |  |
| FONE | String |  | Telefone do Contador |  |
| CODPARC | Integer |  | Produtor |  |
| QTDLIN | Integer |  | Quantidade total de registros do arquivo |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRRQ100 — Livro Caixa Digital do Produtor Rural Registro Q100
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| DATA | Date |  | Data |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| CODIMOVEL | String |  | Código Sequencial do Imóvel |  |
| CODCONTA | String |  | Código Sequencial da conta bancária |  |
| NUMDOC | String |  | Número do documento |  |
| TIPODOC | String |  | Tipo de Documento | `6`=Outros `5`=Folha de Pagamento `4`=Contrato `3`=Recibo `2`=Fatura_(+1)_ |
| CODPARC | Integer |  | Produtor |  |
| HIST | String |  | Histórico |  |
| IDPARTIC | String |  | CPF/CNPJ do participante |  |
| TIPOLANC | String |  | Tipo de Lançamento | `3`=Produtos entregues no ano referente a adiantamento de recursos financeiros `2`=Despesas de custeio e investimentos `1`=Receita da Atividade Rural |
| VLENTRADA | Float |  | Valor de entrada dos recursos |  |
| SLDFIN | Float |  | Saldo Final |  |
| VLSAIDA | Float |  | Valor de saída dos recursos |  |
| NATSLDFIN | String |  | Natureza do Saldo Final | `P`=Positivo `N`=Negativo |
| VLTOTALDOC | Float |  | Valor Total da Baixa |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| VLBAIXANAT | Float |  | Valor da baixa por Natureza |  |
| CONCILIADO | String |  | Conciliado | `S`=Sim `N`=Não |
| CODCTABCOINT | Integer |  | Conta Bancária |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODEMP | Integer |  | Produtor |  |
| MES | String |  | Mês |  |
| NUFIN | Integer |  | Nro Financeiro |  |

## TGFLCDPRRQ200 — Livro Caixa Digital do Produtor Rural Registro Q200
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| MES | Date |  | Mês |  |
| VLENTRADA | Float |  | Valor de entrada dos recursos |  |
| VLSAIDA | Float |  | Valor de saída dos recursos |  |
| SLDFIN | Float |  | Saldo Final |  |
| NATSLDFIN | String |  | Natureza do Saldo Final do mês | `P`=Positivo `N`=Negativo |
| CODPARC | Integer |  | Produtor |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Produtor |  |

## TGFLCDPRTERC — Cadastro de Terceiros
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro Vinculado |  |
| PERCEXPLORACAO | Float |  | Percentual de Exploração |  |
| TIPOEXPLORACAO | String |  | Tipo de Exploração | `4`=Comodante `3`=Parceiro `1`=Condômino `5`=Outros `2`=Arrendador |
| CODEMP | Integer |  | Empresa |  |