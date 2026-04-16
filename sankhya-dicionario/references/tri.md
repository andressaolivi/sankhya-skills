# TRI — Retail / PDV

> Gerado do dicionário oficial TDD Sankhya. 88 tabelas.


## TRIACPRB — Ajustes p/ CPRB Reinf
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CODATIVECON | String |  | Cód. da Atividade Econômica |  |
| TIPOAJUSTE | Integer |  | Tipo do Ajuste | `1`=1 - Ajuste de Adição `0`=0 - Ajuste de Exclusão |
| CODAJUSTE | Integer |  | Cód. do Ajuste | `9`=9 - Receita bruta reconhecida pela construção, recuperação, reforma, etc `8`=8 - ICMS, quando cobrado na condição de substituto `7`=7 - IPI, se incluído na receita bruta `6`=6 - Vendas canceladas e os descontos incondicionais concedidos `5`=5 - Transporte internacional de cargas_(+6)_ |
| VLRAJUSTE | Float |  | Vlr. do Ajuste |  |
| DESCRAJUSTE | String |  | Descrição do Ajuste |  |
| CODEMP | Integer |  | Empresa |  |

## TRIAPPJ — R4020 - Informações de Advogados de Processos
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referêcia |  |
| CODIMP | Integer |  | Imposto |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nr. Documento |  |
| TIPODOCUMENTO | String |  | Tipo Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| CODPARCADV | Integer |  | Código Parceiro Advogado |  |
| NRPROC | String |  | Nro. Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do processo |  |
| TPINSCADV | Integer |  | Tipo Inscrição Advogado | `1`=CNPJ `2`=CPF |
| NRINSCADV | String |  | CPF/CNPJ Advogado |  |
| SEQITE | Integer |  | Sequência ITE |  |
| VLRADV | Float |  | Valor Despesa do Advogado |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODEMP | Integer |  | Empresa |  |

## TRIAPPR — R4080 - Processos Relacionados a Não Retenção de Tributos
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| CODIMP | Integer |  | Imposto |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Número do Documento |  |
| TIPODOCUMENTO | String |  | Tipo do Documento | `N`=Nota Fiscal `F`=Financeiro |
| NATREND | Integer |  | Código da natureza do rendimento |  |
| TPPROCRET | Integer |  | Tipo Processo | `1`=1 - Administrativo `2`=2 - Judicial |
| NRPROCRET | String |  | Nro. do Processo |  |
| NUPROCESSO | String |  | Nro. Único do processo |  |
| DTFG | Date |  | Data Pagamento |  |
| CODSUSP | Integer |  | Cód. da Suspensão |  |
| SEQITE | Integer |  | Sequência ITE |  |
| VLRBASESUSPIR | Float |  | Vlr. Base IR c/ exigibilidade Suspensa |  |
| VLRNIR | Float |  | Vlr. da suspensão |  |
| VLRDEPIR | Float |  | Vlr. do Depósito Judicial |  |
| CODEMP | Integer |  | Empresa |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIAQPR — R2055 - Aquisição de Produção Rural
Campos: 39

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VLRCPAPUR | Float |  | Vlr. Contribuição Previdenciária |  |
| DATACHANGE | C |  | Dados alterados |  |
| DTREF | DateTime |  | Dt. Referência |  |
| IDEVENTO | String |  | ID do Evento |  |
| MSG | C |  | Mensagem |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| NRINSCPROD | String |  | Número de inscrição do produtor |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| SEQUENCIA | Integer |  | Sequência |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| TPAMB | String |  | Ambiente EFD-Reinf | `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `2`=3 - CAEPF `1`=1 - CNPJ |
| TPINSCPROD | Integer |  | Tipo de inscrição do produtor | `2`=2 - CPF `1`=1 - CNPJ |
| VLRBASECPAPUR | Float |  | Vlr. Base Contribuição Previdenciária |  |
| VLRBASERATAPUR | Float |  | Vlr. Base Contribuição Previdenciária GILRAT |  |
| VLRBASESENARAPUR | Float |  | Vlr. Base Contribuição Previdenciária SENAR |  |
| VLRCPAPURRET | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRCPSUSPTOTAL | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRCPSUSPTOTALRET | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATAPUR | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRRATAPURRET | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRRATSUSPTOTAL | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRRATSUSPTOTALRET | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRRECBRUTATOTAL | Float |  | Vlr. Receita Bruta Total |  |
| VLRSENARAPUR | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRSENARAPURRET | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRSENARSUSPTOTAL | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| VLRSENARSUSPTOTALRET | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| CHAVE | String |  | Chave |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CONTROLE | String |  | Controle de Alteração | `I`=Íntegro `E`=Excluído `A`=Alterado |
| INDOPCCP | Integer |  | Tributação Contr.Previdenciária (Prod.Rural) |  |

## TRIAQPRRES — R2055 - Aquisição de Produção Rural
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| SEQEVENTO | Integer |  | Sequência do Evento |  |
| VLRCPAPURSIS | Float |  | Valor da contribuição previdenciária |  |
| VLRCPSUSPTOTALSIS | Float |  | Valor da contribuição previdenciária com exigibilidade suspensa |  |
| VLRCPAPURRET | Float |  | Valor da contribuição previdenciária |  |
| VLRCPSUSPTOTALRET | Float |  | Valor da contribuição previdenciária com exigibilidade suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRICAB — Cabeçalho do Reinf
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data de Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| VERSAOLAYOUT | Integer |  | Versão do layout | `null`=1.04.00 - Inicio 01/05/2021 `151`=1.05.01 - Inicio 01/06/2021 `150`=1.05.00 - Inicio 01/06/2021 `211`=2.01.02 - Inicio 01/09/2023 |
| SEQUENCIAATUAL | Integer |  | Sequência Atual de Geração Grupo 2000 |  |
| STATUS | Integer |  | Status da Referência Grupo 2000 | `10`=Alterações pendentes de geração `1`=Eventos pendentes para o envio `0`=Referência não iniciada `9`=Referência reaberta com sucesso `8`=Em processo de reabertura_(+6)_ |
| CONTROLE | String |  | Controle de Alteração | `E`=Excluído `I`=Íntegro `A`=Alterado |
| EVTTOTAIS | Integer |  | Total de Eventos |  |
| SEQUENCIAATUAL4000 | Integer |  | Sequência Atual de Geração Grupo 4000 |  |
| EVTPENDENTE | Integer |  | Eventos Pendentes |  |
| STATUS_GRUPO4000 | Integer |  | Status da Referência Grupo 4000 | `0`=Referência não iniciada `1`=Eventos pendentes para o envio `10`=Alterações pendentes de geração `2`=Eventos enviados com sucesso - Pendentes de finalização `3`=Eventos aguardando correção_(+6)_ |
| EVTENVIADO | Integer |  | Eventos Enviados |  |
| EVTAGUARCORRECAO | Integer |  | Eventos Aguard. Correção |  |
| EVTERROEVTPRIOR | Integer |  | Eventos c/ Erro em Evento Prioritário |  |
| EVTFINALIZADO | Integer |  | Eventos Finalizados |  |
| CODEMP | Integer |  | Empresa |  |

## TRICPPR — R2050 - Comercialização Produção Produtor Rural
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `E`=Excluído `I`=Íntegro `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| VLRRECBRUTATOTAL | Float |  | Vlr. Receita Bruta Total |  |
| VLRBASECPAPUR | Float |  | Vlr. Base Contribuição Previdenciária |  |
| VLRCPAPUR | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRBASERATAPUR | Float |  | Vlr. Base Contribuição Previdenciária GILRAT |  |
| VLRRATAPUR | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRBASESENARAPUR | Float |  | Vlr. Base Contribuição Previdenciária SENAR |  |
| VLRSENARAPUR | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRCPSUSPTOTAL | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSPTOTAL | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSPTOTAL | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| VLRCPAPURRET | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRRATAPURRET | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRSENARAPURRET | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRCPSUSPTOTALRET | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSPTOTALRET | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSPTOTALRET | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRICPPRRES — R2050 - Resumo Produtor Rural
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| SEQEVENTO | Integer |  | Sequência do Evento |  |
| VLRCPAPURSIS | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRTOTCPAPURSIS | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRRATAPURSIS | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRSENARAPURSIS | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRCPSUSPTOTALSIS | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSPTOTALSIS | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSPTOTALSIS | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| VLRCPAPURRET | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRRATAPURRET | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRSENARAPURRET | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRCPSUSPTOTALRET | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSPTOTALRET | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSPTOTALRET | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRICPRB — R2060 - Contribuição Previdenciária Receita Bruta
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `E`=Excluído `I`=Íntegro `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ |
| NRINSC | String |  | Nro. de Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `4`=4 - CNO `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. de Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| VLRRECBRUTATOTAL | Float |  | Vlr. Receita Bruta Total |  |
| VLRBCCPRBTOTAL | Float |  | Vlr. Base Contribuição Previdenciária Receita Bruta |  |
| VLRCPAPURTOTAL | Float |  | Vlr. Contribuição Previdenciária Receita Bruta |  |
| VLRCPRBSUSPTOTAL | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| CODRECEITA | String |  | Código de Receita |  |
| VLRCPAPURTOTALRET | Float |  | Vlr. Contribuição Previdenciária Receita Bruta |  |
| VLRCPRBSUSPTOTALRET | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRICPRBRES — R2060 - Resumo Receita Bruta
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CODRECEITA | String |  | Código de Receita |  |
| VLRCPAPURTOTALSIS | Float |  | Vlr. Contribuição Previdenciária Receita Bruta |  |
| VLRCPRBSUSPTOTALSIS | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRCPAPURTOTALRET | Float |  | Vlr. Contribuição Previdenciária Receita Bruta |  |
| VLRCPRBSUSPTOTALRET | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRIDAPR — Detalhamento da Aquisição de Produção Rural
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| DTREF | DateTime |  | Dt. Referência |  |
| INDAQUIS | String |  | Indicador de Aquisição | `7`=Aquisição de produção de produtor rural pessoa física ou segurado especial para exportação `6`=Aquisição de produção de produtor rural pessoa jurídica por entidade do PAA `5`=Aquisição de produção de produtor rural pessoa física ou segurado especial por entidade do PAA `4`=Aquisição de produção de produtor rural pessoa física ou segurado especial em geral `3`=Aquisição da produção de produtor rural pessoa jurídica por Entidade do PAA_(+2)_ |
| NRINSC | String |  | Nro. da Inscrição |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| NRINSCPROD | String |  | Número de inscrição do produtor |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Tipo de Ambiente | `2`=Produção restrita - dados reais `1`=Produção |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `2`=3 - CAEPF `1`=1 - CNPJ |
| TPINSCPROD | Integer |  | Tipo de inscrição do produtor |  |
| VLRBASECPAPUR | Float |  | Vlr. Base Contribuição Previdenciária |  |
| VLRBASERATAPUR | Float |  | Vlr. Base Contribuição Previdenciária GILRAT |  |
| VLRBASESENARAPUR | Float |  | Vlr. Base Contribuição Previdenciária SENAR |  |
| VLRBRUTO | Float |  | Valor Bruto da Aquisição da Produção Rural |  |
| VLRCPAPUR | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRCPSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATAPUR | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRRATSUSP | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARAPUR | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRSENARSUSP | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| INDOPCCP | Integer |  | Tributação Contr.Previdenciária (Prod.Rural) |  |

## TRIDBPF — R4010 - Dependentes e Beneficiarios de Pensão
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CPFDEP | String |  | CPF Dependente |  |
| INDTPDEDUCAO | Integer |  | Indicativo tipo Dedução | `1`=1 - Previdência oficial `2`=2 - Previdência privada `3`=3 - Fundo de aposentadoria programada individual - Fapi `4`=4 - Fundação de previdência complementar do servidor público - Funpresp `5`=5 - Pensão alimentícia_(+1)_ |
| CODIMP | Integer |  | Imposto |  |
| NOMEDEP | String |  | Nome Dependente |  |
| VLRDEPEN | Float |  | Vlr. Dependente |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nr. Documento |  |
| TIPODOCUMENTO | String |  | Tipo Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| SEQITE | Integer |  | Sequência ITE |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIDPDE — Dados Dependentes
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CNPJ | String |  | CNPJ da operadora do plano de saúde |  |
| CPFDEP | Integer |  | CPF Dependente |  |
| NOMEDEP | String |  | Nome Dependente |  |
| VLRSAUDE | Float |  | Valor Saúde |  |
| VLRREEMB | Float |  | Valor Reembolso |  |
| VLRREEMBANOANT | Float |  | Valor Reembolso ano anterior |  |
| CODPARCASS | Integer |  | Parceiro prestador de serviços de assistência médica |  |

## TRIDPPF — Dependentes de parceiro de pagamentos
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEDEP | String |  | Nome Dependente |  |
| CPFDEP | String |  | CPF Dependente |  |
| RELDEP | String |  | Relação de Dependencia | `1`=1 -  Cônjuge `10`=10 - Menor pobre do qual detenha a guarda judicial `11`=11 - A pessoa absolutamente incapaz, da qual seja tutor ou curador `12`=12 - Ex-cônjuge `2`=2 - Companheiro(a) qual tenha filho ou viva há mais de 5 anos ou possua declaração de união estável_(+5)_ |
| DESCRDEP | String |  | Descrição da Dependencia |  |
| NATREND | Integer |  | Natureza Rendimento |  |
| CODEMP | Integer |  | Empresa |  |
| NRODOCUMENTO | Integer |  | Nro Único |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIDRCEE — Detalhamento dos recursos recebidos pela associação desportiva
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CNPJASSOCDESP | String |  | CNPJ do Parceiro do Repasse |  |
| NMEMPREXT | String |  | Nome Empresa Exterior |  |
| CODPARCASSOCDESP | Integer |  | Parceiro do Repasse |  |
| TPREPASSE | Integer |  | Tipo de Repasse | `5`=5 - Transmissão de espetáculos `4`=4 - Propaganda `3`=3 - Publicidade `2`=2 - Licenciamento de marcas e símbolos `1`=1 - Patrocínio |
| DESCRECURSO | String |  | Descrição do Recurso |  |
| VLRBRUTO | Float |  | Vlr. Bruto Recurso Recebido |  |
| VLRBASEAPUR | Float |  | Vlr. Base Retenção Efetuada |  |
| VLRRETAPUR | Float |  | Vlr. Retenção Efetuada |  |
| RECEMPREXT | String |  | Empresa Exterior | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TRIDREE — Detalhamento dos repasses efetuados pelo estabelecimento
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CNPJASSOCDESP | String |  | CNPJ da Associação Desportiva |  |
| CODPARCASSOCDESP | Integer |  | Parceiro Associação Desportiva |  |
| VLRTOTALREP | Float |  | Vlr. Total Repasse |  |
| VLRTOTALBASERET | Float |  | Vlr. Total Base Retenção Efetuada |  |
| VLRTOTALRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIDRPF — R4010 - Detalhamento de Rendimento de Pagamento
Campos: 42

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NRODOCUMENTO | Integer |  | Nr. Único |  |
| CODIMP | Integer |  | Imposto |  |
| INDORIGREC | String |  | Indicativo de Origem dos Recursos | `1`=1 `2`=2 |
| TIPODOCUMENTO | String |  | Tipo Documento | `F`=Financeiro `N`=Nota Fiscal |
| OBSERV | String |  | Observação |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| VLRRENDBRUTO | Float |  | Valor Bruto |  |
| TEMDEDIRPF | String |  | Tem Dedução Base IRPF? | `N`=Não `S`=Sim |
| VLRRENDTRIB | Float |  | Valor Rendimento Tributável |  |
| VLRIR | Float |  | Valor IR Retenção |  |
| INDFCISCP | String |  | Indicador FCI ou SCP | `1`=1 `2`=2 |
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQITE | Integer |  | Sequência ITE |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NATREND | Integer |  | Natureza Rendimento |  |
| COMPFP | String |  | Competência Rendimentos |  |
| INDDECTERC | String |  | Ind. 13 Salário |  |
| NRINSCFCISCP | String |  | Nr. Inscrição FCI ou SCP |  |
| DTESCRCONT | Date |  | Dt. Escrituração Contábil. |  |
| PERCSCP | Integer |  | Percentual SCP |  |
| INDJUD | String |  | Indicador Jud. |  |
| PAISRESIDEXT | String |  | País Residência Exterior |  |
| NRPROC | String |  | Nro. do Processo |  |
| CNPJORIGRECURSO | String |  | CNPJ Origem Recurso |  |
| DESCRDEP | String |  | Descrição |  |
| VLRDESPCUSTAS | Float |  | Valor Despesa custas Judiciais |  |
| VLRDESPADVOGADOS | Float |  | Valor Despesa ADV |  |
| DSCLOGRAD | String |  | DSCLOGRAD |  |
| NRLOGRAD | String |  | NRLOGRAD |  |
| COMPLEM | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Cidade |  |
| ESTADO | String |  | Estado |  |
| CODPOSTAL | String |  | Código Postal |  |
| TELEF | String |  | Telefone |  |
| FRMTRIBUT | Integer |  | Código Tributação IR |  |
| INDNIF | Integer |  | Indicador de NIF | `1`=Beneficiário com NIF `2`=Beneficiário dispensado do NIF `3`=País não exige NIF |
| NIFBENEF | String |  | Número NIF |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIDRPJ — R4020 - Detalhamento de Rendimento de Pagamento PJ
Campos: 47

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| OBSERV | String |  | Observação |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nro Único |  |
| TIPODOCUMENTO | String |  | Tipo de Documento | `F`=Financeiro `N`=Nota Fiscal |
| VLRBRUTO | Float |  | Vlr. Bruto |  |
| INDFCISCP | Integer |  | Indicador FCI ou SCP |  |
| NATREND | String |  | Código da Natureza do Rendimento |  |
| NRINSCFCISCP | Integer |  | Indicador FCI ou SCP |  |
| SEQITE | Integer |  | Sequência ITE |  |
| PERCSCP | Float |  | Percentual do SCP |  |
| INDJUD | String |  | Indicativo de Rendimentos de descisão judicial |  |
| PAISRESIDEXT | String |  | País residência no Exterior |  |
| NRPROC | String |  | Nro. Processo |  |
| VLRBASEIR | Float |  | Vlr. Base IR Retenção |  |
| VLRIR | Float |  | Vlr. IR Retenção |  |
| VLRBASEAGREG | Float |  | Vlr. Base AGREGADO Retenção |  |
| DTESCRCONT | Date |  | Dt. Escrituração Contábil. |  |
| VLRAGREG | Float |  | Vlr. AGREGADO Retenção |  |
| VLRBASECSLL | Float |  | Vlr. Base CSLL Retenção |  |
| VLRCSLL | Float |  | Vlr. CSLL Retenção |  |
| VLRBASECOFINS | Float |  | Vlr. Base COFINS Retenção |  |
| VLRCOFINS | Float |  | Vlr. COFINS Retenção |  |
| VLRBASEPP | Float |  | Vlr. Base PIS Retenção |  |
| VLRPP | Float |  | Vlr. PIS Retenção |  |
| INDORIGREC | Integer |  | Indicativo de Origem dos Recursos |  |
| VLRDESPCUSTAS | Float |  | Valor Despesa custas Judiciais |  |
| VLRDESPADVOGADOS | Float |  | Valor Despesa ADV |  |
| CNPJORIGRECURSO | String |  | CNPJ Origem Recurso |  |
| DESCRDEP | String |  | Descrição |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| INDNIF | Integer |  | Indicador de NIF | `1`=Beneficiário com NIF `2`=Beneficiário dispensado do NIF `3`=País não exige NIF |
| NIFBENEF | String |  | Número NIF |  |
| RELFONTPG | Integer |  | Tipo Relação Fonte Pagadora |  |
| FRMTRIBUT | Integer |  | Código Tributação IR |  |
| DSCLOGRAD | String |  | Logradouro |  |
| NRLOGRAD | String |  | Número Logradouro |  |
| COMPLEM | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Nome Cidade |  |
| ESTADO | String |  | Nome Estado |  |
| CODPOSTAL | String |  | CEP |  |
| TELEF | String |  | Número Telefone |  |
| CODEMP | Integer |  | Empresa |  |

## TRIDRR — R4080 - Detalhamento de recebimento do rendimento
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| CODIMP | Integer |  | Imposto |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| OBSERV | String |  | Observação |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nro Único |  |
| TIPODOCUMENTO | String |  | Tipo de Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| DTFG | Date |  | Data Pagamento |  |
| SEQITE | Integer |  | Sequência ITE |  |
| VLRBRUTO | Float |  | Vlr. Bruto |  |
| VLRBASEIR | Float |  | Vlr. Base Retenção |  |
| VLRIR | Float |  | Vlr. Retenção |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODEMP | Integer |  | Empresa |  |

## TRIDRRA — Detalhamento dos repasses recebidos pelo estabelecimento
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CNPJASSOCDESP | String |  | CNPJ do Parceiro do Repasse |  |
| NMEMPREXT | String |  | Nome Empresa Exterior |  |
| CODPARCASSOCDESP | Integer |  | Parceiro do Repasse |  |
| VLRTOTALREP | Float |  | Vlr. Total Recurso Recebido |  |
| VLRTOTALBASERET | Float |  | Vlr. Total Base Retenção Efetuada |  |
| VLRTOTALRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| RECEMPREXT | String |  | Empresa Exterior | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TRIDRRE — Detalhamento dos recursos repassados a associação desportiva
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CNPJASSOCDESP | String |  | CNPJ da Associação Desportiva |  |
| CODPARCASSOCDESP | Integer |  | Parceiro Associação Desportiva |  |
| TPREPASSE | Integer |  | Tipo de Repasse | `5`=5 - Transmissão de espetáculos `4`=4 - Propaganda `3`=3 - Publicidade `2`=2 - Licenciamento de marcas e símbolos `1`=1 - Patrocínio |
| DESCRECURSO | String |  | Descrição do Recurso |  |
| VLRBRUTO | Float |  | Vlr. Bruto Repasse |  |
| VLRBASEAPUR | Float |  | Vlr. Base Retenção Efetuada |  |
| VLRRETAPUR | Float |  | Vlr. Retenção Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIDRTF — Deduções Rendimentos Tributaveis
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INDTPDEDUCAO | Integer |  | Indicativo tipo Dedução | `1`=1 - Previdência oficial `2`=2 - Previdência privada `3`=3 - Fundo de aposentadoria programada individual - Fapi `4`=4 - Fundação de previdência complementar do servidor público - Funpresp `5`=5 - Pensão alimentícia_(+2)_ |
| CODIMP | Integer |  | Imposto |  |
| VLRDEDUCAO | Float |  | Vlr Dedução |  |
| CODEMP | Integer |  | Empresa |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Número do Documento |  |
| TIPODOCUMENTO | String |  | Tipo do Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Código da Natureza do Rendimento |  |
| SEQITE | Integer |  | Sequência ITE |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIETC — Consolidado Por Referência
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Pré-Produção - dados reais `3`=3 - Pré-Produção - dados fictícios |
| SEQUENCIA | Integer |  | Sequência |  |
| NATREND | Integer |  | Cód. Natureza Rendimento |  |
| CODRECEITA | Integer |  | Cód. Receita DARF |  |
| VLRTRIBRETINF | Float |  | Vlr. Tributo retido Informado |  |
| VLRTRIBEXISUSINF | Float |  | Vlr. Trib. Com Exigibilidade suspensa Informado |  |
| VLRTRIBRETCALCRFB | Float |  | Vlr. Tributo retido Calculado RFB |  |
| VLRTRIBEXISUSPCALCRFB | Float |  | Vlr. Trib. Com Exigibilidade suspensa Informado RFB |  |
| VLRTRIBRETCALCDCTFWEB | Float |  | Vlr. Tributo retido Calculado DCTFWeb |  |
| VLRTRIBEXISUSPCALCDCTFWEB | Float |  | Vlr. Trib. Com Exigibilidade suspensa Informado DCTFWeb |  |
| CODEMP | Integer |  | Código Empresa |  |

## TRIEVT — Evento Reinf
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTIPOEVENTO | String |  | Descrição do Tipo de Evento |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| GRUPO | String |  | Grupo | `R`=Reabertura `M`=Movimentação `F`=Fechamento `C`=Cadastro |
| ORDEMEVENTO | Integer |  | Ordem do Evento |  |
| TIPOEVENTO | String |  | Tipo do Evento |  |

## TRIFEP — R2099 - Fechamento de Evento Periódico
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. de Inscrição |  |
| NMRESP | String |  | Nome do Responsável |  |
| CPFRESP | String |  | CPF do Responsável |  |
| TELEFONE | String |  | Telefone |  |
| EMAIL | String |  | E-mail |  |
| EVTSERVTM | String |  | Contratou serviços sujeitos à retenção de contribuição previdenciária? | `S`=Sim `N`=Não |
| EVTSERVPR | String |  | Prestou serviços sujeitos à retenção de contribuição previdenciária? | `S`=Sim `N`=Não |
| EVTASSDESPREC | String |  | A associação desportiva possui informações sobre recursos recebidos? | `S`=Sim `N`=Não |
| EVTASSDESPREP | String |  | A associação desportiva possui informações sobre repasses efetuados? | `S`=Sim `N`=Não |
| EVTCOMPROD | String |  | O Produtor Rural PJ/Agroindústria possui informações de comercialização de produção? | `S`=Sim `N`=Não |
| EVTCPRB | String |  | Possui informações sobre a apuração da Contribuição Previdenciária sobre a Receita Bruta? | `S`=Sim `N`=Não |
| EVTPGTOS | String |  | Possui informações de pagamento diversos  no período de apuração? | `S`=Sim `N`=Não |
| COMPSEMMOVTO | Date |  | Competência sem movimento |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| XMLCONSULTA | C |  | XML de Consulta |  |
| XMLRETORNOCONSULTA | C |  | XML de Retorno da Consulta |  |
| CODUSU | Integer |  | Usuário responsável pelo fechamento |  |
| EVTAQUIS | String |  | Possui informações sobre aquisição de produção rural de pessoas físicas? | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TRIFEREP — R4099 - Fechamento/reabertura dos eventos R-4000
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data de Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Pré-Produção - dados reais `3`=3 - Pré-Produção - dados fictícios |
| SEQUENCIA | Integer |  | Sequência |  |
| STATUSREG | String |  | Status do Registro | `A`=Aguardando Correção `E`=Enviado `F`=Finalizado `P`=Pendente `X`=Erro em Evento Prioritário |
| FECHRET | Integer |  | Indicativo de fechamento/reabertura | `0`=Fechamento `1`=Reabertura |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ `2`=2 - CPF |
| NRINSC | String |  | Nro. da Inscrição |  |
| NMRESP | String |  | Nome do Responsável |  |
| CPFRESP | String |  | CPF do Responsável |  |
| TELEFONE | String |  | Telefone |  |
| EMAIL | String |  | E-mail |  |
| COMPSEMMOVTO | Date |  | Competência sem movimento |  |
| CODUSU | Integer |  | Usuário responsável pelo fechamento |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| EVTPNI | String |  | Possui informações de Pagamentos/créditos a beneficiários não identificados no período de apuração? | `N`=Não `S`=Sim |
| EVTPPF | String |  | Possui informações de Pagamentos/créditos a beneficiário pessoa física no período de apuração? | `N`=Não `S`=Sim |
| EVTPPJ | String |  | Possui informações de Pagamentos/créditos a beneficiário pessoa jurídica no período de apuração? | `N`=Não `S`=Sim |
| EVTRRC | String |  | Possui informações de Retenção no recebimento no período de apuração? | `N`=Não `S`=Sim |
| XMLCONSULTA | C |  | XML de Consulta |  |
| CODEMP | Integer |  | Empresa |  |

## TRIIAPF — R4010 - Informações de Advogados de Processos
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NRINSCADV | String |  | CPF/CNPJ Advogado |  |
| CODIMP | Integer |  | Imposto |  |
| VLRADV | Float |  | Valor Despesa do Advogado |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nr. Documento |  |
| TIPODOCUMENTO | String |  | Tipo Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| CODPARCADV | Integer |  | Código Parceiro Advogado |  |
| TPINSCADV | Integer |  | Tipo Inscrição Advogado | `1`=CNPJ `3`=CPF |
| DTREF | Date |  | Dt. Referência |  |
| SEQITE | Integer |  | Sequência ITE |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| CODEMP | Integer |  | Empresa |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIICR — R1000 - Informações do Contribuinte
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `E`=Excluído `I`=Íntegro `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| DTOBITO | Date |  | Data Óbito do Contribuinte |  |
| DTTRANSFFINSLUCR | Date |  | Data transformação da entidade em fins lucrativos |  |
| INDUNIAO | Integer |  | Entidade Vinculada a União | `0`=0 - Não aplicável `1`=1 - Órgão, autarquias e fund. da admin. púb. fed. direta, soc. de econ. mista ou demais entidades... |
| NRINSC | String |  | Nro. da Inscrição |  |
| INIVALID | Date |  | Dt. Inicial da Vigência |  |
| FIMVALID | Date |  | Dt. Final da Vigência |  |
| CLASSTRIB | Integer |  | Classificação Tributária | `99`=99 - Pessoas Jurídicas em Geral `9`=9 - Órgão Gestor de Mão de Obra `85`=85 - Ente Federativo, Órgãos da União, Autarquias e Fundações Públicas `80`=80 - Entidade Imune ou Isenta `8`=8 - Consórcio Simplificado de Produtores Rurais_(+14)_ |
| INDESCRITURACAO | Integer |  | Indicativo da Escrituração | `1`=1 - Empresa obrigada à ECD `0`=0 - Empresa Não obrigada à ECD |
| INDDESONERACAO | Integer |  | Desoneração da Folha - CPRB | `1`=1 - Empresa enquadrada nos termos da Lei 12.546/2011 e alterações `0`=0 - Não Aplicável |
| INDACORDOISENMULTA | Integer |  | Indicativo do Acordo de Isenção de Multa | `1`=1 - Com acordo `0`=0 - Sem acordo |
| INDSITPJ | Integer |  | Indicativo da Situação de PJ | `4`=4 - Incorporação `3`=3 - Cisão `2`=2 - Fusão `1`=1 - Extinção `0`=0 - Situação Normal |
| NMCTT | String |  | Nome do Contato |  |
| CPFCTT | String |  | CPF do Contato |  |
| FONEFIXOCTT | String |  | Telefone Fixo do Contato |  |
| FONECEL | String |  | Celular do Contato |  |
| EMAILCTT | String |  | Email do Contato |  |
| IDEEFR | String |  | Ente Federativo Responsável | `S`=Sim `N`=Não |
| CNPJEFR | String |  | CNPJ do Ente Federativo Responsável |  |
| INIVALIDNOVO | Date |  | Dt. Inicial da Nova Vigência |  |
| FIMVALIDNOVO | Date |  | Dt. Final da Nova Vigência |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIINFSP — Itens das Notas Fiscais Serviços Prestados
Campos: 43

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| TPSERVICO | String |  | Tipo de Serviço |  |
| NUPROCESSO_INSS_PRINC | Integer |  | Nro. do Processo INSS Principal |  |
| SEQPROCESSO_INSS_PRINC | Integer |  | Sequência do Processo INSS Principal |  |
| NUPROCESSO_INSS_ADICIONAL | Integer |  | Nro. do Processo INSS Adicional |  |
| SEQPROCESSO_INSS_ADICIONAL | Integer |  | Sequência do Processo INSS Adicional |  |
| VLRBASERET | Float |  | Vlr. Base Retenção |  |
| VLRRETENCAO | Float |  | Vlr. Retenção |  |
| VLRRETENCAOCALC | Float |  | Vlr. Retenção Calculada |  |
| VLRDIFRET | Float |  | Vlr. Diferença Cálculo Retenção |  |
| VLRRETSUB | Float |  | Vlr. Retenção Subcontratada |  |
| VLRNRETPRINC | Float |  | Vlr. Retenção Principal Não Efetuada |  |
| VLRSERVICOS15 | Float |  | Vlr. Serviços 15 anos |  |
| VLRSERVICOS20 | Float |  | Vlr. Serviços 20 anos |  |
| VLRSERVICOS25 | Float |  | Vlr. Serviços 25 anos |  |
| VLRADICIONAL | Float |  | Vlr. Retenção Adicional |  |
| VLRADICIONALCALC | Float |  | Vlr. Retenção Adicional Calculada |  |
| VLRADICIONALDIF | Float |  | Vlr. Diferença Cálculo Retenção Adicional |  |
| VLRNRETADIC | Float |  | Vlr. Retenção Adicional Não Efetuada |  |
| TPINSC | Integer |  | Tipo de Inscrição |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTABPREST | Integer |  | Tipo de Inscrição do Prestador |  |
| NRINSCESTABPREST | String |  | Nro. da Inscrição do Prestador |  |
| CODEMPESTABPREST | Integer |  | Empresa Prestadora |  |
| TPINSCTOMADOR | Integer |  | Tipo de Inscrição do Tomador |  |
| NRINSCTOMADOR | String |  | Nro. da Inscrição do Tomador |  |
| CODPARCTOMADOR | Integer |  | Parceiro Tomador |  |
| INDOBRA | Integer |  | Indicativo de Prestação de Serviço em Obra |  |
| VLRTOTALBRUTO | Float |  | Vlr. Total Bruto |  |
| NUPROCESSO_INSS_15 | Integer |  | Nro. do Processo INSS 15 anos |  |
| SEQPROCESSO_INSS_15 | Integer |  | Sequência do Processo INSS 15 anos |  |
| NUPROCESSO_INSS_20 | Integer |  | Nro. do Processo INSS 20 anos |  |
| SEQPROCESSO_INSS_20 | Integer |  | Sequência do Processo INSS 20 anos |  |
| NUPROCESSO_INSS_25 | Integer |  | Nro. do Processo INSS 25 anos |  |
| SEQPROCESSO_INSS_25 | Integer |  | Sequência do Processo INSS 25 anos |  |
| VLRNRETADIC15 | Float |  | Vlr. Retenção Principal Não Efetuada 15 anos |  |
| VLRNRETADIC20 | Float |  | Vlr. Retenção Principal Não Efetuada 20 anos |  |
| VLRNRETADIC25 | Float |  | Vlr. Retenção Principal Não Efetuada 25 anos |  |
| CODEMP | Integer |  | Empresa |  |

## TRIINFST — Itens das Notas Fiscais Serviços Tomados
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| TIPODOCUMENTO | String |  | Tipo de Documento | `N`=Nota `F`=Financeiro |
| TPSERVICO | Integer |  | Tipo de Serviço |  |
| NUPROCESSO_INSS_PRINC | Integer |  | Nro. do Processo INSS Principal |  |
| SEQPROCESSO_INSS_PRINC | Integer |  | Sequência do Processo INSS Principal |  |
| NUPROCESSO_INSS_ADICIONAL | Integer |  | Nro. do Processo INSS Adicional |  |
| SEQPROCESSO_INSS_ADICIONAL | Integer |  | Sequência do Processo INSS Adicional |  |
| VLRBASERET | Float |  | Vlr. Base Retenção |  |
| VLRRETENCAO | Float |  | Vlr. Retenção |  |
| VLRRETENCAOCALC | Float |  | Vlr. Retenção Calculada |  |
| VLRDIFRET | Float |  | Vlr. Diferença Cálculo Retenção |  |
| VLRRETSUB | Float |  | Vlr. Retenção Subcontratada |  |
| VLRNRETPRINC | Float |  | Vlr. Retenção Principal Não Efetuada |  |
| VLRSERVICOS15 | Float |  | Vlr. Serviço 15 anos |  |
| VLRSERVICOS20 | Float |  | Vlr. Serviços 20 anos |  |
| VLRSERVICOS25 | Float |  | Vlr. Serviços 25 anos |  |
| VLRADICIONAL | Float |  | Vlr. Retenção Adicional |  |
| VLRADICIONALCALC | Float |  | Vlr. Retenção Adicional Calculada |  |
| VLRADICIONALDIF | Float |  | Vlr. Diferença Cálculo Retenção Adicional |  |
| VLRNRETADIC | Float |  | Vlr. Retenção Adicional Não Efetuada |  |
| TPINSC | Integer |  | Tipo de Inscrição |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| INDOBRA | Integer |  | Indicativo de Prestação de Serviço em Obra |  |
| CNPJPRESTADOR | String |  | CNPJ do Prestador |  |
| CODPARCPRESTADOR | Integer |  | Parceiro Prestador |  |
| INDCPRB | Integer |  | Indicativo de Contrib. Previdenciária Rec. Bruta |  |
| VLRTOTALBRUTO | Float |  | Vlr. Total Bruto |  |
| NUPROCESSO_INSS_15 | Integer |  | Nro. do Processo INSS 15 anos |  |
| SEQPROCESSO_INSS_15 | Integer |  | Sequência do Processo INSS 15 anos |  |
| NUPROCESSO_INSS_20 | Integer |  | Nro. do Processo INSS 20 anos |  |
| SEQPROCESSO_INSS_20 | Integer |  | Sequência do Processo INSS 20 anos |  |
| NUPROCESSO_INSS_25 | Integer |  | Nro. do Processo INSS 25 anos |  |
| SEQPROCESSO_INSS_25 | Integer |  | Sequência do Processo INSS 25 anos |  |
| VLRNRETADIC15 | Float |  | Vlr. Retenção Adicional Não Efetuada 15 anos |  |
| VLRNRETADIC20 | Float |  | Vlr. Retenção Adicional Não Efetuada 20 anos |  |
| VLRNRETADIC25 | Float |  | Vlr. Retenção Adicional Não Efetuada 25 anos |  |
| VLRCRTOM | Float |  | Vlr. Contrib. Previdenciária |  |
| VLRCRTOMSUSP | Float |  | Vlr. Contrib. c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRIIPFC — Informações de Processos Favoráveis ao Contribuinte
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| INDCOM | Integer |  | Indicativo de Comercialização | `7`=7 - Com. da Produção com Isenção de Contrib. Prev., de acordo com a Lei n° 13.606/2018 `9`=9 - Comercialização direta da Produção no Mercado Externo `8`=8 - Com. da Produção para Entidade do Programa de Aquisição de Alimentos - PAA `1`=1 - Com. da Produção por Prod. Rural PJ ou Agroindústria, exceto para PAA |
| CHAVEPROCESSO | String |  | Chave do Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPPROC | Integer |  | Tipo de Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROC | String |  | Nro. do Processo |  |
| CODSUSP | String |  | Cód. da Suspensão |  |
| VLRCPSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSP | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSP | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRIIPRC — Informações de processos relacionados a não retenção de contribuição previdenciária
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave | `N`=visivel |
| CNPJASSOCDESP | String |  | CNPJ da Associação Desportiva |  |
| CHAVEPROCESSO | String |  | Chave do Processo | `N`=visivel |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPRISET | Integer |  | Sequência do Processo |  |
| TPPROC | Integer |  | Tipo do Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROC | String |  | Nro. do Processo |  |
| CODSUSP | String |  | Cód. da Suspensão |  |
| VLRNRET | Float |  | Vlr. Retenção Não Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIIPRJ — Informação Processo Judicial Produtor Rural
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave |  |
| CHAVEPROCESSO | String |  | Chave do Processo |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODSUSP | String |  | Cód. da Suspensão |  |
| DTREF | DateTime |  | Dt. Referência |  |
| INDAQUIS | String |  | Indicador de Aquisição | `7`=Aquisição de produção de produtor rural pessoa física ou segurado especial para exportação `6`=Aquisição de produção de produtor rural pessoa jurídica por entidade do PAA `5`=Aquisição de produção de produtor rural pessoa física ou segurado especial por entidade do PAA `4`=Aquisição de produção de produtor rural pessoa física ou segurado especial em geral `3`=Aquisição da produção de produtor rural pessoa jurídica por Entidade do PAA_(+2)_ |
| NRPROC | String |  | Nro. do Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Ambiente EFD-Reinf | `2`=Produção restrita - dados reais `1`=Produção |
| TPPROC | Integer |  | Tipo de Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| VLRCPSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSP | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSP | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| INDOPCCP | Integer |  | Tributação Contr.Previdenciária (Prod.Rural) |  |

## TRIIPSC — Informações de Processos da Suspensação da CPRB
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CODATIVECON | String |  | Cód. da Atividade Econômica |  |
| CHAVEPROCESSO | String |  | Chave do Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPPROC | Integer |  | Tipo de Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROC | String |  | Nro. do Processo |  |
| CODSUSP | String |  | Cód. da Suspensão |  |
| VLRCPRBSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRIIRPF — Informação de redimentos de pagamento
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NATREND | Integer |  | Natureza do Rendimento |  |
| OBSERV | String |  | Descrição da Natureza de Rendimentos |  |
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIIRPJ — R4020 - Rendimentos
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NATREND | Integer |  | Natureza do Rendimento |  |
| OBSERV | String |  | Descrição da Natureza de Rendimentos |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODEMP | Integer |  | Empresa |  |

## TRIMON — Monitoramento Reinf
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMETAB | String |  | Nome da Tabela |  |
| NOMEVIEW | String |  | Nome da View |  |
| NOMETABPAI | String |  | Nome da Tabela Pai |  |
| ORDEM | Integer |  | Ordem |  |
| VIEWDETALHE | String |  | View de Detalhes? | `S`=Sim `N`=Não |
| NOMEEVENTO | String |  | Nome do Evento |  |

## TRINFAP — Notas Fiscais Aquisição Produtor Rural
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| DTREF | DateTime |  | Dt. Referência |  |
| INDAQUIS | String |  | Indicador de Aquisição | `7`=Aquisição de produção de produtor rural pessoa física ou segurado especial para exportação `6`=Aquisição de produção de produtor rural pessoa jurídica por entidade do PAA `5`=Aquisição de produção de produtor rural pessoa física ou segurado especial por entidade do PAA `4`=Aquisição de produção de produtor rural pessoa física ou segurado especial em geral `3`=Aquisição da produção de produtor rural pessoa jurídica por Entidade do PAA_(+2)_ |
| INDOPCCP | Integer |  | Tributação Contr.Previdenciária (Prod.Rural) |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| NRINSCPROD | String |  | Número de inscrição do produtor |  |
| NUNOTA | Integer |  | Nro. Único |  |
| NUPROCESSO_GILRAT | Integer |  | Nro. do Processo GILRAT |  |
| NUPROCESSO_INSS | Integer |  | Nro. do Processo INSS |  |
| NUPROCESSO_SENAR | Integer |  | Nro. do Processo SENAR |  |
| SEQPROCESSO_GILRAT | Integer |  | Sequência do Processo GILRAT |  |
| SEQPROCESSO_INSS | Integer |  | Sequência do Processo INSS |  |
| SEQPROCESSO_SENAR | Integer |  | Sequência do Processo SENAR |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Ambiente EFD-Reinf | `2`=Produção restrita - dados reais `1`=Produção |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ `2`=2 - CPF |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `2`=3 - CAEPF `1`=1 - CNPJ |
| TPINSCPROD | Integer |  | Tipo de inscrição do produtor | `2`=2 - CPF `1`=1 - CNPJ |
| VLRBASECPAPUR | Float |  | Vlr. Base Contribuição Previdenciária |  |
| VLRBASERATAPUR | Float |  | Vlr. Base Contribuição Previdenciária GILRAT |  |
| VLRBASESENARAPUR | Float |  | Vlr. Base Contribuição Previdenciária SENAR |  |
| VLRBRUTO | Float |  | Valor Bruto da Aquisição da Produção Rural |  |
| VLRCPAPUR | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRCPSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATAPUR | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRRATSUSP | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARAPUR | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRSENARSUSP | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |

## TRINFPR — Notas Fiscais Produtor Rural
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| INDCOM | String |  | Indicativo de Comercialização | `9`=9 - Comercialização direta da Produção no Mercado Externo `8`=8 - Com. da Produção para Entidade do Programa de Aquisição de Alimentos - PAA `7`=7 - Com. da Produção com Isenção de Contrib. Prev., de acordo com a Lei n° 13.606/2018 `1`=1 - Com. da Produção por Prod. Rural PJ ou Agroindústria, exceto para PAA |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| NUPROCESSO_INSS | Integer |  | Nro. do Processo INSS |  |
| SEQPROCESSO_INSS | Integer |  | Sequência do Processo INSS |  |
| NUPROCESSO_GILRAT | Integer |  | Nro. do Processo GILRAT |  |
| SEQPROCESSO_GILRAT | Integer |  | Sequência do Processo GILRAT |  |
| NUPROCESSO_SENAR | Integer |  | Nro. do Processo SENAR |  |
| SEQPROCESSO_SENAR | Integer |  | Sequência do Processo SENAR |  |
| TPINSC | Integer |  | Tipo da Inscrição |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| VLRRECBRUTA | Float |  | Vlr. Receita Bruta |  |
| VLRBASECPAPUR | Float |  | Vlr. Base Contribuição Previdenciária |  |
| VLRCPAPUR | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRBASERATAPUR | Float |  | Vlr. Base Contribuição Previdenciária GILRAT |  |
| VLRRATAPUR | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRBASESENARAPUR | Float |  | Vlr. Base Contribuição Previdenciária SENAR |  |
| VLRSENARAPUR | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRCPSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSP | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSP | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRINFRB — Notas Fiscais Receita Bruta
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CODATIVECON | String |  | Cód. da Atividade Econômica |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| NUPROCESSO_INSS | Integer |  | Nro. do Processo INSS |  |
| SEQPROCESSO_INSS | Integer |  | Sequência do Processo INSS |  |
| TPINSC | Integer |  | Tipo de Inscrição |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| VLRRECEITABRUTAESTAB | Float |  | Vlr. Receita Bruta do Estabelecimento |  |
| VLRRECEITABRUTAATIV | Float |  | Vlr. Receita Bruta da Atividade |  |
| VLRABATIMENTOBRUTOATIV | Float |  | Vlr. Abatimento Bruto da Atividade |  |
| VLREXCLUSAOBRUTAATIV | Float |  | Vlr. Exclusão Receita Bruta da Atividade |  |
| VLREXCRECBRUTA | Float |  | Vlr. Exclusão Receita Bruta |  |
| VLRADICRECBRUTA | Float |  | Vlr. Adicional Receita Bruta |  |
| VLRBCCPRB | Float |  | Vlr. Base Contribuição Receita Bruta |  |
| VLRCPRBAPUR | Float |  | Vlr. Contribuição Receita Bruta |  |
| VLRCPRBSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| CODRECOLHIMENTO | String |  | Cód. Recolhimento |  |
| ALIQUOTA | Float |  | Alíquota |  |
| EMPFILIAL | Integer |  | Empresa Filial |  |
| CODEMP | Integer |  | Empresa |  |

## TRINFSP — Notas Fiscais Serviços Prestados
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SERIE | String |  | Série |  |
| NUMDOCTO | String |  | Nro. Documento |  |
| DTEMISSAONF | Date |  | Dt. Emissão Nota |  |
| VLRBRUTO | Float |  | Vlr. Bruto |  |
| OBS | String |  | Observação |  |
| VLRBASERET | Float |  | Vlr. Base Retenção |  |
| VLRRETENCAO | Float |  | Vlr. Retenção |  |
| VLRRETENCAOCALC | Float |  | Vlr. Retenção Calculada |  |
| VLRDIFRET | Float |  | Vlr. Diferença Cálculo Retenção |  |
| VLRADICIONAL | Float |  | Vlr. Retenção Adicional |  |
| VLRADICIONALCALC | Float |  | Vlr. Retenção Adicional Calculada |  |
| VLRADICIONALDIF | Float |  | Vlr. Diferença Cálculo Retenção Adicional |  |
| CODEMP | Integer |  | Empresa |  |

## TRINFST — Notas Fiscais Serviços Tomados
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| TIPODOCUMENTO | String |  | Tipo de Documento | `N`=Nota `F`=Financeiro |
| SERIE | String |  | Série |  |
| NUMDOCTO | String |  | Nro. Documento |  |
| DTEMISSAONF | Date |  | Dt. Emissão Nota |  |
| VLRBRUTO | Float |  | Vlr. Bruto |  |
| OBS | String |  | Observação |  |
| VLRBASERET | Float |  | Vlr. Base Retenção |  |
| VLRRETENCAO | Float |  | Vlr. Retenção |  |
| VLRRETENCAOCALC | Float |  | Vlr. Retenção Calculada |  |
| VLRDIFRET | Float |  | Vlr. Diferença Cálculo Retenção |  |
| VLRADICIONAL | Float |  | Vlr. Retenção Adicional |  |
| VLRADICIONALCALC | Float |  | Vlr. Retenção Adicional Calculada |  |
| VLRADICIONALDIF | Float |  | Vlr. Diferença Cálculo Retenção Adicional |  |
| CODEMP | Integer |  | Empresa |  |

## TRINRN — Detalhamento de Naturezas de Rendimento
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NATREND | Integer |  | Natureza do Rendimento |  |
| OBSERV | String |  | Observação |  |
| CODEMP | Integer |  | Empresa |  |

## TRINRRC — R4080 - Detalhamento de Naturezas de Rendimento
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NATREND | Integer |  | Natureza do Rendimento |  |
| OBSERV | String |  | Descrição da Natureza de Rendimentos |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPAJ — Tabela de Processos Administrativos Judiciais
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| NUMPROCESSO | String |  | Nro. do Processo |  |
| DTINIVALIDADE | Date |  | Data Início da Validade |  |
| DTFIMVALIDADE | Date |  | Data Fim da Validade |  |
| AUTORIA | String |  | Autoria da Ação Judicial | `2`=2 - Outra entidade ou empresa `1`=1 - Próprio contribuinte |
| CODCID | Integer |  | Cidade |  |
| CODIDENTVARA | String |  | Cód. Identificação da Vara |  |
| TIPO | Integer |  | Tipo | `2`=2 - Judicial `1`=1 - Administrativo |
| INDORIGPROC | Integer |  | Indicador da Origem do Processo | `9`=9 - Outros `3`=3 - Secretaria da Receita Federal do Brasil `1`=1 - Justiça Federal |
| DESCRCOMPLREG1011 | String |  | Descrição Complementar Registro 1011 |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| GERTAGPROXMLNFE | String |  | Gerar Tag´s do grupo procRef no XML da NF-e | `N`=Não `S`=Sim |
| ORIGEMPROCESSO | Integer |  | Origem do Processo | `9`=9 - Outros `3`=3 - Secex/RFB `2`=2 - Justica Estadual `0`=0 - SEFAZ `1`=1 - Justica Federal_(+1)_ |
| TIPATOCONCES | Integer |  | Tipo do Ato Concessório | `8`=08 - Termo de Acordo `12`=12 - Autorização Específica `10`=10 - Regime Especial `14`=14 - Ajuste SINIEF |
| ADVATUAPROC | Integer |  | Advogado Atuante no processo |  |
| NUPROCESSO | Integer |  | Nro. Único do processo |  |

## TRIPAJR — R1070 - Processos Administrativos/Judiciais Reinf
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `E`=Excluído `I`=Íntegro `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPPROC | Integer |  | Tipo do Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROC | String |  | Nro. do Processo |  |
| INIVALID | Date |  | Dt. Inicial da Vigência |  |
| FIMVALID | Date |  | Dt. Final da Vigência |  |
| INDAUTORIA | Integer |  | Indicador da Autoria | `2`=2 - Outra Entidade ou Empresa `1`=1 - Próprio Contribuinte |
| UFVARA | String |  | UF da Seção Judiciária |  |
| CODMUNIC | Integer |  | Cód. do Município da Seção Judiciária |  |
| IDVARA | String |  | Cód. de Identificação da Vara |  |
| INIVALIDNOVO | Date |  | Dt. Inicial da Nova Vigência |  |
| FIMVALIDNOVO | Date |  | Dt. Final da Nova Vigência |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPASP — Processo Adicional Serviços Prestados
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CHAVEPROCESSO | String |  | Chave do Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPPROCRETADIC | Integer |  | Tipo de Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROCRETADIC | String |  | Nro. do Processo |  |
| CODSUSPADIC | String |  | Cód. da Suspensão |  |
| VALORADIC | Float |  | Vlr. Retenção |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPAST — Processo Adicional Serviços Tomados
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CHAVEPROCESSO | String |  | Chave do Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPPROCRETADIC | Integer |  | Tipo de Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROCRETADIC | String |  | Nro. do Processo |  |
| CODSUSPADIC | String |  | Cód. da Suspensão |  |
| VALORADIC | Float |  | Vlr. Retenção |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPBN — Pagamentos a beneficiários não indentificados
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód. Empresa |  |
| CODIMP | Integer |  | Imposto |  |
| DTREF | Date |  | Data Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nro Único |  |
| TIPODOCUMENTO | String |  | Tipo de Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| DTFG | Date |  | Data Pagamento |  |
| VLRLIQ | Float |  | Vlr. Líquido do Pagamento |  |
| SEQITE | Integer |  | Sequência ITE |  |
| VLRBASEIR | Float |  | Vlr. Base Retenção |  |
| VLRIR | Float |  | Vlr. Retenção |  |
| DESCR | String |  | Descrição |  |
| DTESCRCONT | Date |  | Dt. Escrituração Contábil. |  |

## TRIPEMP — Tabela PROCESSOS POR EMPRESA
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUPROCESSO | Integer |  | Nº Processo |  |

## TRIPIMP — Tabela PROCESSOS POR IMPOSTO
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| TIPOIMPOSTO | Integer |  | Tipo Imposto | `9`=INSS 15 anos (EFD REINF) `8`=INSS CPRB (EFD REINF e Contribuições) `7`=COFINS Retido (EFD REINF e Contribuições) `6`=PIS/PASEP Retido (EFD REINF e Contribuições) `5`=CSLL (EFD REINF)_(+8)_ |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| GRUCAMFORMULA | String |  | Grupo de campos que serão calculados com as fórmulas | `E`=Conforme a escrituração `D`=Conforme a decisão judicial `null`=Não se aplica |
| FORMULACST | String |  | Fórmula para código da situação tributária |  |
| FORMULABASE | String |  | Fórmula para a base de cálculo |  |
| FORMULAALIQUOTA | String |  | Fórmula para a alíquota |  |
| FORMULAVALOR | String |  | Fórmula para o valor |  |
| NUPROCESSO | Integer |  | Nº Processo |  |

## TRIPISET — Processos Por Informações de Suspensão de Exibilidade de Tributos
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODSUSP | String |  | Cód. Suspensão |  |
| DESCRDECISAO | String |  | Descrição da Decisão |  |
| DTDECISAO | Date |  | Data da Decisão |  |
| DTINIVIGOR | Date |  | Dt. Inicial da Vigência |  |
| DTFIMVIGOR | Date |  | Dt. Final da Vigência |  |
| INDDEPOSITO | String |  | Depósito Montante Integral | `S`=Sim `N`=Não |
| PERCSUSPIMP | Float |  | % de Suspensão do Imposto |  |
| INDSUSPREINF | Integer |  | Indicativo da Suspensão | `92`=Sem suspensão da exigibilidade `90`=Decisão Definitiva a favor do contribuinte `9`=Sentença em Ação Ordinária Favorável ao Contribuinte e Confirmada pelo TRF `8`=Sentença em Mandado de Segurança Favorável ao Contribuinte `5`=Liminar em Medida Cautelar_(+8)_ |
| INDNATACAOJUD | Integer |  | Indicador da Natureza da Ação Judicial | `99`=99 - Outros `9`=9 - Decisão judicial oriunda de liminar em mandado de segurança coletivo `8`=8 - Súmula vinculante aprovada pelo STF ou STJ `7`=7 - Medida judicial em que a pessoa jurídica não é o autor `6`=6 - Decisão judicial vinculada a depósito administrativo ou judicial em montante integral_(+12)_ |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUPROCESSO | Integer |  | Nro Único do processso |  |

## TRIPLDS — Plano de Saúde
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CNPJ | String |  | CNPJ da operadora do plano de saúde |  |
| VLRSAUDE | Float |  | Valor Saúde |  |
| VLRREEMB | Float |  | Valor Reembolso |  |
| VLRREEMBANOANT | Float |  | Valor Reembolso ano anterior |  |
| CODPARCASS | Integer |  | Parceiro prestador de serviços de assistência médica |  |

## TRIPNI — R4040 - Pagamentos/créditos a beneficiários não identificados
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `A`=Aguardando Correção `E`=Enviado `F`=Finalizado `P`=Pendente `X`=Erro em Evento Prioritário |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle | `A`=Alterado `E`=Excluído `I`=Íntegro |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. de Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| PROCEMI | Integer |  | Tipo Aplicativo | `1`=Aplicativo do contribuinte `2`=Aplicativo governamental |
| VERPROC | String |  | Versão do processo de emissão do evento |  |
| PERAPUR | String |  | Ano/Mês Referência |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| TIPO | String |  | Tipo de Envio | `A`=Alteração `E`=Exclusão `I`=Inclusão |
| VLRTOTALLIQ | Float |  | Vlr. Total líquido do pagamento |  |
| VLRTOTALBASEIR | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALIR | Float |  | Vlr. Total Retenção |  |
| VLRBASECRRET | Float |  | Base de calculo |  |
| VLRBASECRSUSPRET | Float |  | Base de Calculo c/ Exigibilidade Suspensa |  |
| VLRCRCALCRET | Float |  | Vlr Tributo retido Calculado RFB |  |
| VLRCRSUSPCALCRET | Float |  | Vlr Tributo c/ Exigibilidade Susp Calc RFB |  |
| DATACHANGE | C |  | Dados alterados |  |
| INDRETIF | Integer |  | Controle de Alteração | `1`=Original `2`=Retificação |
| CODEMP | Integer |  | Empresa |  |

## TRIPNIRES — R4040 - Pagamentos/créditos a beneficiários não identificados
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Pré-Produção - dados reais `3`=3 - Pré-Produção - dados fictícios |
| NATREND | Integer |  | Código Natureza Rendimento |  |
| CODRECDARF | Integer |  | Código Receita DARF |  |
| VLRBASECALSIS | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSSIS | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFSIS | Float |  | Valor Tributo retido Informado |  |
| VLRTRIEXISUSINFSIS | Float |  | Valor Tributo Com Exigibilidade suspensa Informado |  |
| VLRBASECALRET | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSRET | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFRET | Float |  | Valor Tributo retido Calculado RFB |  |
| VLRTRIEXISUSINFRET | Float |  | Valor Tributo Com Exigibilidade Suspensa Calculado RFB |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPPARC — Tabela PROCESSOS POR PARCEIRO
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUPROCESSO | Integer |  | Nº Processo |  |

## TRIPPF — R4010 - Pagamentos/créditos a beneficiário pessoa física
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `A`=Aguardando Correção `E`=Enviado `F`=Finalizado `P`=Pendente `X`=Erro em Evento Prioritário |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle | `A`=Alterado `E`=Excluído `I`=Íntegro |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ `2`=2 - CPF |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ `2`=2 - CPF `3`=3 - CAEPF |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CPFBENEF | String |  | CPF do Beneficiário Prestador |  |
| NMBENEF | String |  | Parceiro do Beneficiário Prestador |  |
| VLRTOTALBRUTO | Float |  | Vlr. total Bruto |  |
| VLRTOTALIR | Float |  | Vlr. total IR |  |
| VLRTOTALADV | Float |  | Vlr. total Adv |  |
| VLRTOTALISENTO | Float |  | Vlr. total Isento |  |
| VLRTOTALDEDUCAO | Float |  | Vlr. total Dedução |  |
| VLRTOTALRENDSUSP | Float |  | Vlr. total Redimento Suspenso |  |
| VLRBASECRRET | Float |  | Base de calculo |  |
| VLRBASECRSUSPRET | Float |  | Base de Cálculo c/ Exigibilidade Suspensa |  |
| VLRCRCALCRET | Float |  | Vlr Tributo retido Calculado RFB |  |
| VLRCRSUSPCALCRET | Float |  | Vlr Tributo c/ Exigibilidade Susp Calc RFB |  |
| PROCEMI | String |  | Processo de Emissão do Evento | `1`=Aplicativo do contribuinte `2`=Aplicativo governamental |
| TIPO | String |  | Tipo de Envio | `A`=Alteração `E`=Exclusão `I`=Inclusão |
| VERPROC | String |  | Versão do processo de emissão do evento |  |
| DATACHANGE | C |  | Dados alterados |  |
| NATJUR | String |  | Natureza Jurídica |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Pré-Produção - dados reais `3`=3 - Pré-Produção - dados fictícios |
| DTREF | Date |  | Data de Referência |  |
| CODEMP | Integer |  | Empresa |  |
| INDRETIF | Integer |  | Controle de Alteração | `1`=Original `2`=Retificação |
| PERAPUR | String |  | Ano/Mes Referencia |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIPPFRES — R4010 - Pagamentos/créditos a beneficiário pessoa física
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Pré-Produção - dados reais `3`=3 - Pré-Produção - dados fictícios |
| CPFBENEF | String |  | CPF do Beneficiário Prestador |  |
| NMBENEF | String |  | Parceiro do Beneficiário Prestador |  |
| NATREND | Integer |  | Código Natureza Rendimento |  |
| CODRECDARF | Integer |  | Código Receita DARF |  |
| VLRBASECALSIS | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSSIS | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFSIS | Float |  | Valor Tributo retido Informado |  |
| VLRTRIEXISUSINFSIS | Float |  | Valor Tributo Com Exigibilidade suspensa Informado |  |
| VLRBASECALRET | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSRET | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFRET | Float |  | Valor Tributo retido Calculado RFB |  |
| VLRTRIEXISUSINFRET | Float |  | Valor Tributo Com Exigibilidade Suspensa Calculado RFB |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPPJ — R4020 - Pagamentos/créditos a beneficiário pessoa jurídica
Campos: 44

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `A`=Aguardando Correção `E`=Enviado `F`=Finalizado `P`=Pendente `X`=Erro em Evento Prioritário |
| INDRETIF | Integer |  | Controle de Alteração | `1`=Original `2`=Retificação |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `A`=Alterado `E`=Excluído `I`=Íntegro |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. de Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| PROCEMI | Integer |  | Tipo Aplicativo | `1`=Aplicativo do contribuinte `2`=Aplicativo governamental |
| VERPROC | String |  | Versão do processo de emissão do evento |  |
| PERAPUR | String |  | Ano/Mês Referência |  |
| NATJUR | String |  | Natureza Jurídica |  |
| ISENIMUN | Integer |  | Tipo Entidade Tributação | `1`=1 - Entidade não isenta/não imune - Tributação normal `2`=2 - Instituição de educação e assistência social sem fins lucrativos art 12 Lei 9532 de 10 dez 1997 `3`=3 - Instituição filantrópica, recreativa, cultural, científico e assoc. civis, art 15 Lei 9.532/1997 |
| CNPJBENEF | String |  | CNPJ do Prestador |  |
| NMBENEF | String |  | Parceiro Prestador |  |
| VLRTOTALBRUTO | Float |  | Vlr. Total Bruto |  |
| VLRTOTALBASEIR | Float |  | Vlr. Total Base IR Retenção |  |
| TIPO | String |  | Tipo de Envio | `A`=Alteração `E`=Exclusão `I`=Inclusão |
| VLRTOTALIR | Float |  | Vlr. Total IR Retenção |  |
| VLRTOTALBASEAGREG | Float |  | Vlr. Total Base AGREGADO Retenção |  |
| VLRTOTALAGREG | Float |  | Vlr. Total AGREGADO Retenção |  |
| VLRTOTALBASECSLL | Float |  | Vlr. Total Base CSLL Retenção |  |
| VLRTOTALCSLL | Float |  | Vlr. Total CSLL Retenção |  |
| VLRTOTALBASECOFINS | Float |  | Vlr. Total Base COFINS Retenção |  |
| VLRTOTALCOFINS | Float |  | Vlr. Total COFINS Retenção |  |
| VLRTOTALBASEPP | Float |  | Vlr. Total Base PIS Retenção |  |
| VLRTOTALPP | Float |  | Vlr. Total PIS Retenção |  |
| VLRBASECRRET | Float |  | Base de calculo |  |
| VLRBASECRSUSPRET | Float |  | Base de Cálculo c/ Exigibilidade Suspensa |  |
| VLRCRCALCRET | Float |  | Vlr Tributo retido Calculado RFB |  |
| VLRCRSUSPCALCRET | Float |  | Vlr Tributo c/ Exigibilidade Susp Calc RFB |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPPJRES — R4020 - Pagamentos/créditos a beneficiário pessoa jurídica
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Pré-Produção - dados reais `3`=3 - Pré-Produção - dados fictícios |
| CNPJBENEF | Integer |  | CNPJ do Prestador |  |
| NMBENEF | String |  | Parceiro Prestador |  |
| NATREND | Integer |  | Código Natureza Rendimento |  |
| CODRECDARF | Integer |  | Código Receita DARF |  |
| VLRBASECALSIS | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSSIS | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFSIS | Float |  | Valor Tributo retido Informado |  |
| VLRTRIEXISUSINFSIS | Float |  | Valor Tributo Com Exigibilidade suspensa Informado |  |
| VLRBASECALRET | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSRET | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFRET | Float |  | Valor Tributo retido Calculado RFB |  |
| VLRTRIEXISUSINFRET | Float |  | Valor Tributo Com Exigibilidade Suspensa Calculado RFB |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPPROD — Tabela PROCESSOS POR PRODUTO
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cód. Produto |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUPROCESSO | Integer |  | Núm. Processo |  |

## TRIPPSP — Processo Principal Serviços Prestados
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CHAVEPROCESSO | String |  | Chave do Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPPROCRETPRINC | Integer |  | Tipo de Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROCRETPRINC | String |  | Nro. do Processo |  |
| CODSUSPPRINC | String |  | Cód. da Suspensão |  |
| VALORPRINC | Float |  | Vlr. Retenção |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPPST — Processo Principal Serviços Tomados
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CHAVEPROCESSO | String |  | Chave Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPPROCRETPRINC | Integer |  | Tipo de Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROCRETPRINC | String |  | Nro. do Processo |  |
| CODSUSPPRINC | String |  | Cód. da Suspensão |  |
| VALORPRINC | Float |  | Vlr. Retenção |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPRISET — Processos Reinf Por Informações de Suspensão de Exibilidade de Tributos
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPRISET | Integer |  | Sequência da Suspensão |  |
| CODSUSP | String |  | Cód. da Suspensão |  |
| INDSUSP | Integer |  | Indicativo de Suspensão |  |
| DTDECISAO | Date |  | Dt. Decisão |  |
| INDDEPOSITO | String |  | Depósito Montante Integral | `S`=Sim `N`=Não |
| INIVALID | Date |  | Dt. Inicial da Vigência |  |
| FIMVALID | Date |  | Dt. Final da Vigência |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPRRC — nformações de processos relacionados a não retenção de contribuição previdenciária
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave | `N`=visivel |
| CNPJASSOCDESP | String |  | CNPJ da Associação Desportiva |  |
| CHAVEPROCESSO | String |  | Chave do Processo | `N`=visivel |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPRISET | Integer |  | Sequência do Processo |  |
| TPPROC | Integer |  | Tipo do Processo | `2`=2 - Judicial `1`=1 - Administrativo |
| NRPROC | String |  | Nro. do Processo |  |
| CODSUSP | String |  | Cód. da Suspensão |  |
| VLRNRET | Float |  | Vlr. Retenção Não Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIPRRJ — R4020 - Processos relacionados a não retenção de tributos
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód. Empresa |  |
| CODIMP | Integer |  | Imposto |  |
| DTREF | Date |  | Data Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nr. Documento |  |
| TIPODOCUMENTO | String |  | Tipo Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| NRPROCRET | String |  | Nro. do Processo |  |
| NUPROCESSO | Integer |  | Nro. Único do processo |  |
| TPPROCRET | Integer |  | Tipo Processo |  |
| CODSUSP | String |  | Cód. da Suspensão |  |
| SEQITE | Integer |  | Sequência ITE |  |
| VLRBASESUSPIR | Float |  | Vlr. Base IR NÃO Retenção |  |
| VLRNIR | Float |  | Vlr. IR NÃO Retenção |  |
| VLRDEPIR | Float |  | Vlr. IR Depósito Judicial |  |
| VLRBASESUSPCSLL | Float |  | Vlr. Base CSLL NÃO Retenção |  |
| VLRNCSLL | Float |  | Vlr. CSLL NÃO Retenção |  |
| VLRDEPCSLL | Float |  | Vlr. CSLL Depósito Judicial |  |
| VLRBASESUSPCOFINS | Float |  | Vlr. Base COFINS Retenção |  |
| VLRNCOFINS | Float |  | Vlr. COFINS NÃO Retenção |  |
| VLRDEPCOFINS | Float |  | Vlr. COFINS Depósito Judicial |  |
| VLRBASESUSPPP | Float |  | Vlr. Base PIS NÃO Retenção |  |
| VLRNPP | Float |  | Vlr. PIS NÃO Retenção |  |
| VLRDEPPP | Float |  | Vlr. PIS Depósito Judicial |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIPRRT — R4040 - Processos relacionados a não retenção de tributos
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód. Empresa |  |
| CODIMP | Integer |  | Imposto |  |
| DTREF | Date |  | Data Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nr. Documento |  |
| TIPODOCUMENTO | String |  | Tipo Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| DTFG | Date |  | Data Pagamento |  |
| NRPROCRET | String |  | Nro. do Processo |  |
| NUPROCESSO | String |  | Nro. Único do processo |  |
| TPPROCRET | Integer |  | Tipo Processo |  |
| CODSUSP | Integer |  | Cód. da Suspensão |  |
| SEQITE | Integer |  | Sequência ITE |  |
| VLRBASESUSPIR | Float |  | Vlr. da Base do IR exigibilidade Suspensa |  |
| VLRNIR | Float |  | Vlr. da suspensão |  |
| VLRDEPIR | Float |  | Vlr. do Depósito Judicial |  |

## TRIPRTF — Processos de Retenção de Tributos
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODIMP | Integer |  | Imposto |  |
| DTREF | Date |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| DTFG | Date |  | Dt. Fato Gerador |  |
| CHAVE | String |  | Chave |  |
| TPPROCRET | Integer |  | Tipo de Processo | `1`=1 - Administrativo `2`=2 - Judicial |
| CODSUSP | String |  | Cód. da Suspensão |  |
| NRPROCRET | String |  | Nro. do Processo |  |
| NUPROCESSO | String |  | Nro. Único do processo |  |
| VLRNRETIDO | Float |  | Vlr. IR NÃO Retenção |  |
| SEQITE | Integer |  | Sequência ITE |  |
| VLRDEPJUD | Float |  | Vlr. IR Depósito Judicial |  |
| VLRRENDSUSP | Float |  | Vlr. IR Rendimentos Suspensos |  |
| NRODOCUMENTO | Integer |  | Número do Documento |  |
| TIPODOCUMENTO | String |  | Tipo do Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Código da Natureza do Rendimento |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIPTOP — Tipo de Operação
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODTIPOPER | Integer |  | Tipo de Operação |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUPROCESSO | Integer |  | Nº Processo |  |

## TRIPTPSV — Tabela PROCESSOS POR TIPO DE SERVIÇO
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODLST | Integer |  | Cód. Lista Serviço |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUPROCESSO | Integer |  | Nº Processo |  |

## TRIRCSP — R2020 - Retenção Contribuição Serviços Prestados
Campos: 41

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `E`=Excluído `I`=Íntegro `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTABPREST | Integer |  | Tipo de Inscrição do Prestador | `1`=1 - CNPJ |
| NRINSCESTABPREST | String |  | Nro. da Inscrição do Prestador |  |
| CODEMPESTABPREST | Integer |  | Empresa Prestadora |  |
| TPINSCTOMADOR | Integer |  | Tipo de Inscrição do Tomador | `4`=4 - CNO `1`=1 - CNPJ |
| NRINSCTOMADOR | String |  | Nro. da Inscrição do Tomador |  |
| CODPARCTOMADOR | Integer |  | Parceiro Tomador |  |
| INDOBRA | Integer |  | Indicatvio de Prestação de Serviço em Obra | `2`=2 - Obra de Construção Civil - Empreitada Parcial `1`=1 - Obra de Construção Civil - Empreitada Total `0`=0 - Não é obra de construção civil ou não está sujeita a matrícula de obra |
| VLRTOTALBRUTO | Float |  | Vlr. Total Bruto |  |
| VLRTOTALBASERET | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINC | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETENCAOCALC | Float |  | Vlr. Total Retenção Principal Calculada |  |
| VLRTOTALDIFRET | Float |  | Vlr. Total Diferença Cálculo Retenção |  |
| VLRTOTALRETADIC | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALRETADICCALC | Float |  | Vlr. Total Retenção Adicional Calculada |  |
| VLRTOTALRETADICDIF | Float |  | Vlr. Total Diferença Cálculo Retenção Adicional |  |
| VLRTOTALNRETPRINC | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADIC | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| TPINSCTOMADORRET | Integer |  | Tipo de Inscrição do Tomador |  |
| NRINSCTOMADORRET | String |  | Nro. da Inscrição do Tomador |  |
| VLRTOTALBASERETRET | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINCRET | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETADICRET | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALNRETPRINCRET | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADICRET | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRCSPRES — R2020 - Resumo Serviços Prestados
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCTOMADOR | Integer |  | Tipo de Inscrição do Tomador |  |
| NRINSCTOMADOR | String |  | Nro. da Inscrição do Tomador |  |
| VLRTOTALBASERETSIS | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINCSIS | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETADICSIS | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALNRETPRINCSIS | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADICSIS | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| VLRTOTALBASERETRET | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINCRET | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETADICRET | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALNRETPRINCRET | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADICRET | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRCST — R2010 - Retenção Contribuição Serviços Tomados
Campos: 44

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `E`=Excluído `I`=Íntegro `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `4`=4 - CNO `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| INDOBRA | Integer |  | Indicativo de Prestação de Serviço em Obra | `2`=2 - Obra de Construção Civil - Empreitada Parcial `1`=1 - Obra de Construção Civil - Empreitada Total `0`=0 - Não é obra de construção civil ou não está sujeita a matrícula de obra |
| CNPJPRESTADOR | String |  | CNPJ do Prestador |  |
| CODPARCPRESTADOR | Integer |  | Parceiro Prestador |  |
| INDCPRB | Integer |  | Indicativo de Contrib. Previdenciária Rec. Bruta | `1`=1 - Contribuinte da Contribuição Previdenciária sobre a Receita Bruta (CPRB) - Retenção 3,5% `0`=0 - Não é contribuinte da Contribuição Previdenciária sobre a Receita Bruta (CPRB) - Retenção 11% |
| VLRTOTALBRUTO | Float |  | Vlr. Total Bruto |  |
| VLRTOTALBASERET | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINC | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETENCAOCALC | Float |  | Vlr. Total Retenção Principal Calculada |  |
| VLRTOTALDIFRET | Float |  | Vlr. Total Diferença Cálculo Retenção |  |
| VLRTOTALRETADIC | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALRETADICCALC | Float |  | Vlr. Total Retenção Adicional Calculada |  |
| VLRTOTALRETADICDIF | Float |  | Vlr. Total Diferença Cálculo Retenção Adicional |  |
| VLRTOTALNRETPRINC | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADIC | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| CNPJPRESTADORRET | String |  | CNPJ do Prestador |  |
| VLRTOTALBASERETRET | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINCRET | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETADICRET | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALNRETPRINCRET | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADICRET | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| VLRCRTOM | Float |  | Vlr. Total Contrib. Previdenciária |  |
| VLRCRTOMSUSP | Float |  | Vlr. Total Contrib. c/ Exigibilidade Suspensa |  |
| VLRCRTOMRET | Float |  | Vlr. Total Contrib. Previdenciária |  |
| VLRCRTOMSUSPRET | Float |  | Vlr. Total Contrib. c/ Exigibilidade Suspensa |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRCSTRES — R2010 - Resumo Serviços Tomados
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CNPJPRESTADOR | String |  | CNPJ do Prestador |  |
| VLRTOTALBASERETSIS | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINCSIS | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETADICSIS | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALNRETPRINCSIS | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADICSIS | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| VLRTOTALBASERETRET | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALRETPRINCRET | Float |  | Vlr. Total Retenção Principal |  |
| VLRTOTALRETADICRET | Float |  | Vlr. Total Retenção Adicional |  |
| VLRTOTALNRETPRINCRET | Float |  | Vlr. Total Retenção Principal Não Efetuada |  |
| VLRTOTALNRETADICRET | Float |  | Vlr. Total Retenção Adicional Não Efetuada |  |
| VLRCRTOMSIS | Float |  | Vlr. Total Contrib. Previdenciária |  |
| VLRCRTOMSUSPSIS | Float |  | Vlr. Total Contrib. c/ Exigibilidade Suspensa |  |
| VLRCRTOMRET | Float |  | Vlr. Total Contrib. Previdenciária |  |
| VLRCRTOMSUSPRET | Float |  | Vlr. Total Contrib. c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |

## TRIREAD — R2030 - Recursos Recebidos por Associação Desportiva
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `I`=Íntegro `E`=Excluído `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| MSG | String |  | Mensagem |  |
| XMLEVENTO | String |  | XML de Envio |  |
| XMLRETORNO | String |  | XML de Retorno |  |
| VLRTOTALREP | Float |  | Vlr. Total Recurso Recebido |  |
| VLRTOTALBASERET | Float |  | Vlr. Total Base Retenção Efetuada |  |
| VLRTOTALRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| VLRTOTALREPRET | Float |  | Vlr. Total Recurso Recebido |  |
| VLRTOTALRETRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRETRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIREADRES — R2030 - Resumo Repasse Recebidos por Associação Desportiva
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CNPJASSOCDESP | String |  | CNPJ da Associação Desportiva |  |
| VLRTOTALREPSIS | Float |  | Vlr. Total Repasse |  |
| VLRTOTALRETSIS | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRETSIS | Float |  | Vlr. Total Retenção Não Efetuada |  |
| VLRTOTALREPRET | Float |  | Vlr. Total Repasse |  |
| VLRTOTALRETRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRETRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIREAD_NFS — Notas de Recursos Recebidos por Associação Desportiva
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `1`=1 - Produção `2`=2 - Pré-Produção - dados reais |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| DOCUMENTO | Integer |  | Nro Único |  |
| NMEMPREXT | String |  | Nome Empresa Exterior |  |
| TIPO | String |  | Tipo de Documento | `N`=Nota `F`=Financeiro |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPREPASSE | Integer |  | Tipo de Repasse | `5`=5 - Transmissão de espetáculos `4`=4 - Propaganda `3`=3 - Publicidade `1`=1 - Patrocínio `2`=2 - Licenciamento de marcas e símbolos |
| DESCRECURSO | String |  | Descrição do Recurso |  |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CNPJASSOCDESP | String |  | CNPJ do Parceiro do Repasse |  |
| CODPARCASSOCDESP | Integer |  | Parceiro do Repasse |  |
| VLRBRUTO | Float |  | Vlr. Bruto Recurso Recebido |  |
| VLRBASEAPUR | Float |  | Vlr. Base Retenção Efetuada |  |
| VLRRETAPUR | Float |  | Vlr. Retenção Efetuada |  |
| RECEMPREXT | String |  | Empresa Exterior | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TRIREP — R2098 - Reabertura de Evento Periódico
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. de Inscrição |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRES — Resumo Por Referência
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSC | Integer |  | Tipo de Inscrição |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| DHPROCESS | DateTime |  | Dh. Processamento |  |
| IDEV | String |  | ID do Evento |  |
| NRRECARQBASE | String |  | Nro. do Recibo |  |
| INDEXISTINFO | Integer |  | Ind. de Existência de Valores de Bases | `3`=3 - Não há movimento na competência `2`=2 - Há movimento, porém não há informações de bases ou de tributos `1`=1 - Há informações de bases e/ou de tributos |
| CODEMP | Integer |  | Empresa |  |

## TRIRNTF — R4010 - Rendimentos Isentos ou não Tributáveis
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TPISENCAO | String |  | Tipo de Isenção | `1`=1 - Parcela Isenta 65 anos `2`=2 - Diária de viagem `3`=3 - Indenização e rescisão de contrato, inclusive a título de PDV e acidentes de trabalho `4`=4 - Abono pecuniário `5`=5 - Valor Pago a titular, sócio ME ou EPP, exceto pró-labore, aluguéis e serviços prestados_(+7)_ |
| CODIMP | Integer |  | Imposto |  |
| VLRISENTO | Float |  | Valor Isenção |  |
| DESCRENDIMENTO | String |  | Descrição do Rend. Isento/Não tributável |  |
| DTFG | Date |  | Dt. Fato Gerador |  |
| DTLAUDO | Date |  | Data Laudo |  |
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRODOCUMENTO | Integer |  | Nr. Documento |  |
| SEQITE | Integer |  | Sequência ITE |  |
| TIPODOCUMENTO | String |  | Tipo Documento | `F`=Financeiro `N`=Nota Fiscal |
| NATREND | Integer |  | Natureza Rendimento |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TRIRRAD — Recursos Repassados para Associação Desportiva
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `X`=Erro em Evento Prioritário `P`=Pendente `F`=Finalizado `E`=Enviado `A`=Aguardando Correção |
| TIPO | String |  | Tipo de Envio | `I`=Inclusão `E`=Exclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `I`=Íntegro `E`=Excluído `A`=Alterado |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| MSG | String |  | Mensagem |  |
| XMLEVENTO | String |  | XML de Envio |  |
| XMLRETORNO | String |  | XML de Retorno |  |
| VLRTOTALREP | Float |  | Vlr. Total Repasse |  |
| VLRTOTALBASERET | Float |  | Vlr. Total Base Retenção Efetuada |  |
| VLRTOTALRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| VLRTOTALREPRET | Float |  | Vlr. Total Repasse |  |
| VLRTOTALRETRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRETRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRRADRES — R2040 - Resumo Repasse p/ Associação Desportiva
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CNPJASSOCDESP | String |  | CNPJ da Associação Desportiva |  |
| VLRTOTALREPSIS | Float |  | Vlr. Total Repasse |  |
| VLRTOTALRETSIS | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRETSIS | Float |  | Vlr. Total Retenção Não Efetuada |  |
| VLRTOTALREPRET | Float |  | Vlr. Total Repasse |  |
| VLRTOTALRETRET | Float |  | Vlr. Total Retenção Efetuada |  |
| VLRTOTALNRETRET | Float |  | Vlr. Total Retenção Não Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRRAD_NFS — Notas de Recursos Repassados para Associação Desportiva
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| DOCUMENTO | Integer |  | Nro Único |  |
| TIPO | String |  | Tipo de Documento | `N`=Nota `F`=Financeiro |
| NUPROCESSO | Integer |  | Nro. Único do Processo |  |
| SEQPROCESSO | Integer |  | Sequência do Processo |  |
| TPREPASSE | Integer |  | Tipo de Repasse | `5`=5 - Transmissão de espetáculos `4`=4 - Propaganda `3`=3 - Publicidade `2`=2 - Licenciamento de marcas e símbolos `1`=1 - Patrocínio |
| DESCRECURSO | String |  | Descrição do Recurso |  |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=2 - CPF `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CNPJASSOCDESP | String |  | CNPJ da Associação Desportiva |  |
| CODPARCASSOCDESP | Integer |  | Parceiro Associação Desportiva |  |
| VLRBRUTO | Float |  | Vlr. Bruto Repasse |  |
| VLRBASEAPUR | Float |  | Vlr. Base Retenção Efetuada |  |
| VLRRETAPUR | Float |  | Vlr. Retenção Efetuada |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRRC — R-4080 - Retenção no recebimento
Campos: 34

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `2`=2 - Produção restrita |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `F`=Finalizado `P`=Pendente `A`=Aguardando Correção `E`=Enviado `X`=Erro em Evento Prioritário |
| INDRETIF | Integer |  | Tipo de Envio | `1`=Original `2`=Retificação |
| TIPO | String |  | Tipo de Envio | `A`=Alteração `E`=Exclusão `I`=Inclusão |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| NRORECIBOANT | String |  | Nro. do Recibo Anterior |  |
| CONTROLE | String |  | Controle de Alteração | `A`=Alterado `E`=Excluído `I`=Íntegro |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento | `1`=1 - CNPJ |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| CNPJFONT | String |  | CNPJ da Fonte Pagadora |  |
| NOMEFONT | String |  | Fonte pagadora do rendimento |  |
| VLRTOTALBRUTO | Float |  | Vlr. Total Bruto |  |
| VLRTOTALBASEIR | Float |  | Vlr. Total Base Retenção |  |
| VLRTOTALIR | Float |  | Vlr. Total Retenção |  |
| PERAPUR | String |  | Ano/Mes Referencia |  |
| PROCEMI | Integer |  | Tipo Aplicativo | `1`=Aplicativo do contribuinte `2`=Aplicativo governamental |
| VERPROC | String |  | Versão do processo de emissão do evento |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| VLRBASECRRET | Float |  | Base de calculo |  |
| VLRBASECRSUSPRET | Float |  | Base de Cálculo c/ Exigibilidade Suspensa |  |
| VLRCRCALCRET | Float |  | Vlr Tributo retido Calculado RFB |  |
| VLRCRSUSPCALCRET | Float |  | Vlr Tributo c/ Exigibilidade Susp Calc RFB |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRIRRCRES — R4080 - Retenção no recebimento
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Tipo de Ambiente | `1`=1 - Produção `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais |
| CNPJFONT | Integer |  | CNPJ da Fonte Pagadora |  |
| NATREND | Integer |  | Código Natureza Rendimento |  |
| CODRECDARF | Integer |  | Código Receita DARF |  |
| VLRBASECALSIS | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSSIS | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFSIS | Float |  | Valor Tributo retido Informado |  |
| VLRTRIEXISUSINFSIS | Float |  | Valor Tributo Com Exigibilidade suspensa Informado |  |
| VLRBASECALRET | Float |  | Base de cálculo |  |
| VLRBASECALEXISUSRET | Float |  | Base de Cálculo Com Exigibilidade Suspensa |  |
| VLRTRIRETINFRET | Float |  | Valor Tributo retido Calculado RFB |  |
| VLRTRIEXISUSINFRET | Float |  | Valor Tributo Com Exigibilidade Suspensa Calculado RFB |  |
| CODEMP | Integer |  | Empresa |  |

## TRITCAE — Tipo de Código de Atividade Econômica
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| CODATIVECON | String |  | Cód. da Atividade Econômica |  |
| VLRRECBRUTAATIV | Float |  | Vlr. Receita Bruta da Atividade |  |
| VLREXCRECBRUTA | Float |  | Vlr. Exclusão Receita Bruta |  |
| VLRADICRECBRUTA | Float |  | Vlr. Adicional Receita Bruta |  |
| VLRBCCPRB | Float |  | Vlr. Base Contribuição Receita Bruta |  |
| VLRCPRBAPUR | Float |  | Vlr. Contribuição Receita Bruta |  |
| VLRCPRBSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| TPINSC | Integer |  | Tipo de Inscrição |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODRECOLHIMENTO | String |  | Cód. Recolhimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| CODEMP | Integer |  | Empresa |  |

## TRITEL — R1050 - Entidades Ligadas
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `2`=2 - Produção restrita `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| STATUSREG | String |  | Status do Registro | `A`=Aguardando Correção `E`=Enviado `F`=Finalizado `P`=Pendente `X`=Erro em Evento Prioritário |
| TIPO | String |  | Tipo de Envio | `E`=Exclusão `I`=Inclusão `A`=Alteração |
| IDEVENTO | String |  | ID do Evento |  |
| NRORECIBO | String |  | Nro. do Recibo |  |
| TPENTLIG | Integer |  | Tipo Entidade Ligada | `1`=Fundo de investimento `2`=Fundo de investimento imobiliário `4`=Sociedade em conta de participação `3`=Clube de investimento |
| CONTROLE | String |  | Controle de Alteração | `A`=Alterado `E`=Excluído `I`=Íntegro |
| TPINSC | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ `2`=2 - CPF |
| NRINSC | String |  | Nro. da Inscrição |  |
| CNPJLIG | String |  | Número CNPJ |  |
| INIVALID | Date |  | Dt. Inicial da Vigência |  |
| FIMVALID | Date |  | Dt. Final da Vigência |  |
| MSG | C |  | Mensagem |  |
| XMLEVENTO | C |  | XML de Envio |  |
| XMLRETORNO | C |  | XML de Retorno |  |
| PROCEMI | Integer |  | Tipo Aplicativo | `1`=Aplicativo do contribuinte `2`=Aplicativo governamental |
| VERPROC | String |  | Versão do processo de emissão do evento |  |
| DATACHANGE | C |  | Dados alterados |  |
| CODEMP | Integer |  | Empresa |  |

## TRITPCO — Tipo de Comercialização
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| TPAMB | String |  | Tipo de Ambiente | `3`=3 - Pré-Produção - dados fictícios `2`=2 - Pré-Produção - dados reais `1`=1 - Produção |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| INDCOM | Integer |  | Indicativo de Comercialização | `7`=7 - Com. da Produção com Isenção de Contrib. Prev., de acordo com a Lei n° 13.606/2018 `9`=9 - Comercialização direta da Produção no Mercado Externo `8`=8 - Com. da Produção para Entidade do Programa de Aquisição de Alimentos - PAA `1`=1 - Com. da Produção por Prod. Rural PJ ou Agroindústria, exceto para PAA |
| VLRRECBRUTA | Float |  | Vlr. Receita Bruta |  |
| TPINSC | Integer |  | Tipo da Inscrição |  |
| NRINSC | String |  | Nro. da Inscrição |  |
| TPINSCESTAB | Integer |  | Tipo de Inscrição do Estabelecimento |  |
| NRINSCESTAB | String |  | Nro. da Inscrição do Estabelecimento |  |
| CODEMPESTAB | Integer |  | Empresa do Estabelecimento |  |
| VLRBASECPAPUR | Float |  | Vlr. Base Contribuição Previdenciária |  |
| VLRCPAPUR | Float |  | Vlr. Contribuição Previdenciária |  |
| VLRBASERATAPUR | Float |  | Vlr. Base Contribuição Previdenciária GILRAT |  |
| VLRRATAPUR | Float |  | Vlr. Contribuição Previdenciária GILRAT |  |
| VLRBASESENARAPUR | Float |  | Vlr. Base Contribuição Previdenciária SENAR |  |
| VLRSENARAPUR | Float |  | Vlr. Contribuição Previdenciária SENAR |  |
| VLRCPSUSP | Float |  | Vlr. Contribuição c/ Exigibilidade Suspensa |  |
| VLRRATSUSP | Float |  | Vlr. Contribuição GILRAT c/ Exigibilidade Suspensa |  |
| VLRSENARSUSP | Float |  | Vlr. Contribuição SENAR c/ Exigibilidade Suspensa |  |
| CODEMP | Integer |  | Empresa |  |