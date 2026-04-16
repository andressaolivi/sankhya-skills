# TGF — Fiscal, Tributário, NF-e

> Gerado do dicionário oficial TDD Sankhya. 27 tabelas.


## TGFCFO — Código Fiscal de Operações
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCFO | String |  | Descrição da CFOP |  |
| TRIBUTADASCIAP | String |  | Utilizar nas Tributadas do CIAP | `B`=Base de ICMS `V`=Valor Contábil `N`=Não Utilizar `C`=Considerar config. por CST |
| TIPICMS | String |  | ICMS p/ o Livro Fiscal | `1`=Usar da TOP/Empresa `3`=Sem créd/deb - Outras `2`=Sem créd/déb - Isentas |
| CODCTACTB | Integer |  | Conta Contábil |  |
| GRUPOCFO | Integer |  | Grupo da CFOP | `0`=0.00 - Definição Automática `600`=6.00 - Saída para outro estado `100`=1.00 - Entrada do estado `500`=5.00 - Saída para o estado `700`=7.00 - Saída para o exterior_(+2)_ |
| TIPO | String |  | Tipo | `E`=Energia Elétrica `T`=Transferências `M`=Comunicação `O`=Outras `C`=Compras_(+3)_ |
| CONVPRODUZ | String |  | Convênio Produzir | `N`=Não `S`=Sim |
| CALCDIFICMS | String |  | Calcular Diferença de ICMS | `N`=Não `S`=Sim |
| DESCONSIDERARCFOREG47 | String |  | Desconsiderar CFOP na geração do registro 47 da DIME-SC? | `N`=Não `S`=Sim |
| RECBRUTAEFDBLOCOP | String |  | Receita bruta p/EFD Contribuições | `S`=Soma `N`=Não afeta `T`=Subtrai |
| TIPOPERPRODEPE | String |  | Tipo de Operação PRODEPE | `null`=Operação Incentivada `N`=Operação Não Incentivada |
| MOVIMFISICA | String |  | Movimentação Física do Item/Produto (IND_MOV C170 EFD) | `null`=Não se aplica `S`=Sim `N`=Não |
| AD_LDAPI | Integer |  | Linha DAPI |  |
| EMPCODSIT08EFD | String |  | Empresas para considerar a situação do documento '08' nos EFDs |  |
| RECBRUTACIAP | String |  | Receita Bruta p/ CIAP | `B`=Buscar da TOP `N`=Não afeta `S`=Soma `T`=Subtrai |
| INDAQUISICAO | String |  | Indicador de Aquisição | `1`=1-Aquisição da produção de produtor rural pessoa física ou segurado especial em geral `2`=2-Aquisição da produção de produtor rural PF ou segurado especial em geral por Entidade do PAA `3`=3-Aquisição da produção de produtor rural pessoa jurídica por Entidade do PAA `4`=4-Aquisição de produção de produtor rural pessoa física ou segurado especial em geral `5`=5-Aquisição de produção de produtor rural pessoa física ou segurado especial por entidade do PAA_(+2)_ |
| OPERESSACOMP | String |  | Operação com Ressarcimento/Complemento de ST | `N`=Não `S`=Sim |
| CODCFO | Integer |  | Código |  |

## TGFCODRECDIRF — Código de Receita para Dirf
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| PIS | String |  | Gerar para PIS? | `S`=Sim `N`=Não |
| COFINS | String |  | Gerar para COFINS? | `S`=Sim `N`=Não |
| CSLL | String |  | Gerar para CSLL? | `S`=Sim `N`=Não |
| IRF | String |  | Gerar para IRF? | `S`=Sim `N`=Não |
| ESTOQUE | String |  | Estoque? | `S`=Sim `N`=Não |
| FINANCEIRO | String |  | Financeiro? | `S`=Sim `N`=Não |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| IMPINCLUSO | String |  | Gerar para imposto incluso? | `S`=Sim `N`=Não |
| TIPOPESSOA | Integer |  | Tipos de Pessoa | `null`=Pessoa Jurídica `2`=Pessoa Física |
| IMPRETIDO | String |  | Gerar para imposto retido? | `S`=Sim `N`=Não |
| IMPNAORETIDO | String |  | Gerar para imposto não retido, Pessoa Física? | `S`=Sim `N`=Não |
| CODREC | String |  | Código |  |

## TGFCODRECDIRFNAT — Natureza por Código de Receita para Dirf
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREC | String |  | Código |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODNAT | Integer |  | Natureza |  |

## TGFCODRECDIRFPRO — Serviço por Código de Receita para Dirf
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREC | String |  | Código |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODPROD | Integer |  | Produto\Serviço |  |

## TGFCST — Entradas com ICMS/ST
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Produto |  |
| NUNOTAENTRADA | Integer |  | Nro. Único Entrada |  |
| SEQUENCIAENTRADA | Integer |  | Sequencia na Nota |  |
| VLRICMSUNIT | Float |  | Vlr. ICMS Unit. |  |
| BASESUBSTUNIT | Float |  | Base ST Unit. |  |
| VLRSUBSTUNIT | Float |  | Vlr. ST Unit. |  |
| PERCSUBST | Float |  | % ST |  |
| BASESTFCPINTANTUNIT | Float |  | Base ST FCP Int. Ant. Unit. |  |
| VLRSTFCPINTANTUNIT | Float |  | Vlr. ST FCP Int. Ant. Unitário |  |
| PERCSTFCPINTANTUNIT | Float |  | % ST FCP Int. Ant. |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| NUNOTAAMPARO | Integer |  | Nro. Único Amparo |  |
| SEQUENCIAAMPARO | Integer |  | Sequencia Amparo |  |

## TGFDIRF — Demonstrativo p/ Apuração do Ressarcimento de ST
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Data Inicial |  |
| DTFINAL | Date |  | Data Final |  |
| IDESTLEIAUTE | String |  | Identificador de estrutura do leiaute | `AT65HD8`=AT65HD8 `VR4QLM8`=VR4QLM8 `XJFSFHB`=XJFSFHB `ARNZRXP`=ARNZRXP `B3VH8RQ`=B3VH8RQ_(+1)_ |
| TIPDECLARACAO | String |  | Retificadora? | `S`=Sim `N`=Não |
| NUMRECIBO | String |  | Número recibo |  |
| ARQCONFIRMADO | String |  | Arquivo Confirmado? | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFBPFDEC — Beneficiário Pessoa Física Dirf
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CPF | String |  | CPF |  |
| NOME | String |  | Nome |  |
| DTMOLESTIAGRAVE | Date |  | Dt. atribuída pelo laudo da moléstia grave |  |
| IDALIMENTANDO | String |  | Indicador de identificação do alimentando | `S`=Sim `N`=Não |
| IDPREVCOMP | String |  | Indicador de identificação da previdência complementar | `S`=Sim `N`=Não |
| REGPAI2 | String |  | Registro Pai 2 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFBPJDEC — Beneficiário Pesso Jurídica Dirf
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CNPJ | String |  | CNPJ |  |
| NOME | String |  | Nome |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| REGPAI2 | String |  | Registro Pai 2 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFDECPJ — Declarante Pessoa Jurídica Dirf
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| NOME | String |  | Nome |  |
| CNPJ | String |  | CNPJ |  |
| NATDECL | String |  | Natureza Declarante | `8`=8 - Entidade com alteração de natureza jurídica (uso restrito) `4`=4 - Empresa pública ou sociedade de economia mista estadual, municipal ou do Distrito Federal `3`=3 - Empresa pública ou sociedade de economia mista federal `2`=2 - Órgãos, autarquias e fundações da adm. pública estadual, municipal ou do Distrito Federal `1`=1 - Órgãos, autarquias e fundações da administração pública federal_(+1)_ |
| CPFRESP | String |  | CPF responsável |  |
| INDSOCOST | String |  | Sócio ostensivo | `S`=Sim `N`=Não |
| INDDEPDECJUD | String |  | Depositário de crédito de decisão judicial | `S`=Sim `N`=Não |
| INDDEPFUNINV | String |  | Administrador de Fundo de Investimento | `S`=Sim `N`=Não |
| INDPGEXT | String |  | Pagou rendimentos a residentes no exterior | `S`=Sim `N`=Não |
| INDPLPRIASS | String |  | Plano de assistência à saúde | `S`=Sim `N`=Não |
| INDENTIMUNE | String |  | Entidade em que a União detém controle | `S`=Sim `N`=Não |
| INDPGFUNDPUB | String |  | Fundação pública de direito privado | `S`=Sim `N`=Não |
| DTEVENTO | Date |  | Data Evento |  |
| INDSITESP | String |  | Declaração de Situação Especial | `S`=Sim `N`=Não |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFIDREC — Identificação Código Receita Dirf
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| REGPAI | String |  | Registro Pai |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFPFRTIRF — Rendimentro Tributável Imposto Retido na Fonte Dirf Pessoa Física
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro |  |
| CPF | String |  | CPF |  |
| REGPAI2 | String |  | Registro |  |
| VLRJAN | Float |  | Janeiro |  |
| VLRFEV | Float |  | Fevereiro |  |
| VLRMAR | Float |  | Março |  |
| VLRABR | Float |  | Abril |  |
| VLRMAI | Float |  | Maio |  |
| VLRJUN | Float |  | Junho |  |
| VLRJUL | Float |  | Julho |  |
| VLRAGO | Float |  | Agosto |  |
| VLRSET | Float |  | Setembro |  |
| VLROUT | Float |  | Outubro |  |
| VLRNOV | Float |  | Novembro |  |
| VLRDEZ | Float |  | Dezembro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| REGPAI3 | String |  | Registro Pai 3 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFPFRTPO — RTPO - Dedução previdência Social  (Mês / 13º)
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro |  |
| CPF | String |  | CPF |  |
| REGPAI2 | String |  | Registro |  |
| VLRJAN | Float |  | Janeiro |  |
| VLRFEV | Float |  | Fevereiro |  |
| VLRMAR | Float |  | Março |  |
| VLRABR | Float |  | Abril |  |
| VLRMAI | Float |  | Maio |  |
| VLRJUN | Float |  | Junho |  |
| VLRJUL | Float |  | Julho |  |
| VLRAGO | Float |  | Agosto |  |
| VLRSET | Float |  | Setembro |  |
| VLROUT | Float |  | Outubro |  |
| VLRNOV | Float |  | Novembro |  |
| VLRDEZ | Float |  | Dezembro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| REGPAI3 | String |  | Registro Pai 3 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFPFRTRT — Rendimento Tributável Dirf Pessoa Física
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CPF | String |  | CPF |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| VLRJAN | Float |  | Janeiro |  |
| VLRFEV | Float |  | Fevereiro |  |
| VLRMAR | Float |  | Março |  |
| VLRABR | Float |  | Abril |  |
| VLRMAI | Float |  | Maio |  |
| VLRJUN | Float |  | Junho |  |
| VLRJUL | Float |  | Julho |  |
| VLRAGO | Float |  | Agosto |  |
| VLRSET | Float |  | Setembro |  |
| VLROUT | Float |  | Outubro |  |
| VLRNOV | Float |  | Novembro |  |
| VLRDEZ | Float |  | Dezembro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| REGPAI3 | String |  | Registro Pai 3 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFPJRTIRF — Rendimentro Tributável Imposto Retido na Fonte Dirf Pessoa Jurídica
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro |  |
| CNPJ | String |  | CNPJ |  |
| REGPAI2 | String |  | Registro |  |
| VLRJAN | Float |  | Janeiro |  |
| VLRFEV | Float |  | Fevereiro |  |
| VLRMAR | Float |  | Março |  |
| VLRABR | Float |  | Abril |  |
| VLRMAI | Float |  | Maio |  |
| VLRJUN | Float |  | Junho |  |
| VLRJUL | Float |  | Julho |  |
| VLRAGO | Float |  | Agosto |  |
| VLRSET | Float |  | Setembro |  |
| VLROUT | Float |  | Outubro |  |
| VLRNOV | Float |  | Novembro |  |
| VLRDEZ | Float |  | Dezembro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| REGPAI3 | String |  | Registro Pai 3 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFPJRTRT — Rendimento Tributável Dirf Pessoa Jurídica
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTFINAL | Date |  | Dt. Final |  |
| DTINICIAL | Date |  | Dt. Inicial |  |
| REG | String |  | Registro |  |
| CODREC | String |  | Código de Receita |  |
| REGPAI | String |  | Registro Pai |  |
| CNPJ | String |  | CNPJ |  |
| REGPAI2 | String |  | Registro Pai 2 |  |
| VLRJAN | Float |  | Janeiro |  |
| VLRFEV | Float |  | Fevereiro |  |
| VLRMAR | Float |  | Março |  |
| VLRABR | Float |  | Abril |  |
| VLRMAI | Float |  | Maio |  |
| VLRJUN | Float |  | Junho |  |
| VLRJUL | Float |  | Julho |  |
| VLRAGO | Float |  | Agosto |  |
| VLRSET | Float |  | Setembro |  |
| VLROUT | Float |  | Outubro |  |
| VLRNOV | Float |  | Novembro |  |
| VLRDEZ | Float |  | Dezembro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| REGPAI3 | String |  | Registro Pai 3 |  |
| CODEMP | Integer |  | Empresa |  |

## TGFDIRFRESPO — Responsável Dirf
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| CPF | String |  | Cpf |  |
| NOME | String |  | Nome |  |
| DDD | String |  | DDD |  |
| TELEFONE | String |  | Telefone |  |
| RAMAL | String |  | Ramal |  |
| FAX | String |  | Fax |  |
| EMAIL | String |  | E-mail |  |
| REG | String |  | Registro |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFDITB — Integração Tributo Detalhe
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOIMP | Integer |  | Tipo |  |
| DHIMPORT | DateTime |  | Data |  |
| CODUSU | Integer |  | Usuário |  |
| STATUS | String |  | Status | `null`=Pendente `L`=Liberada |
| CODEMP | Integer |  | Código da Empresa |  |

## TGFDITBF — Importação tributos detalhes de PIS/COFINS
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOIMP | Integer |  | Tipo | `3`=IPI `2`=PIS/COFINS `1`=ICMS |
| DHIMPORT | DateTime |  | Data |  |
| STATUSIMP | String |  | Status importação | `null`=Pendente `P`=Processado `D`=Erro |
| CSTENT | Integer |  | CST Entrada |  |
| CSTSAI | Integer |  | CST Saída |  |
| ALIQPIS | Float |  | Alíquota PIS |  |
| ALIQCOFINS | Float |  | Alíquota COFINS |  |
| NRI | String |  | Natureza de Receita Isenta |  |
| NCM | String |  | NCM |  |
| CODPROD | Integer |  | Produto |  |
| CODEMP | Integer |  | Código da Empresa |  |

## TGFDITBI — Importação tributos detalhes de ICMS
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOIMP | Integer |  | Tipo |  |
| IDALIQICMS | Integer |  | Código Alíquota ICMS |  |
| DHIMPORT | DateTime |  | Data |  |
| UF | String |  | UF |  |
| CARACTRIB | String |  | Característica tributável | `8`=Pessoa Física não Contribuinte do ICMS `7`=Pessoa Jurídica não Contribuinte do ICMS `6`=Produtor Rural Pessoa Física `4`=Produtor Rural Pessoa Jurídica `3`=Varejista_(+3)_ |
| FINALIDADE | String |  | Destinação da mercadoria adquirida | `2`=Uso e Consumo Ou Ativo Imobilizado `1`=Insumo `0`=Revenda |
| STATUSIMP | String |  | Status importação | `null`=Pendente `P`=Processado `D`=Erro |
| NCM | String |  | NCM |  |
| CFOP | Integer |  | CFOP |  |
| CST | Integer |  | CST |  |
| CSOSN | Integer |  | CSOSN |  |
| ALIQICMSINTERNA | Float |  | Alíquota de ICMS |  |
| ALIQICMSINTERESTADUAL | Float |  | Alíquota de ICMS Interestadual |  |
| REDUCAOBCICMS | Float |  | Redução da Base de Cálculo do ICMS |  |
| REDUCAOSTICMS | Float |  | Redução da Base de Cálculo do ICMS ST |  |
| ALIQICMSST | Float |  | Alíquota do ICMS ST |  |
| IVA | Float |  | MVA/IVA do produto |  |
| FCP | Float |  | Alíquota de ICMS FCP do produto |  |
| CODBENEF | String |  | Código do benefício fiscal |  |
| PDIFER | Float |  | Percentual do Diferimento de ICMS |  |
| ANTECIPADO | String |  | Antecipação | `S`=Sim `N`=Não |
| DESONERADO | String |  | Desoneração | `S`=Sim `N`=Não |
| ISENTO | String |  | Isento | `S`=Sim `N`=Não |
| CODPROD | Integer |  | Produto |  |
| CODESPECST | Integer |  | CEST |  |
| MVAAJUSTADO | Float |  | MVA/IVA Ajustada |  |
| CODEMP | Integer |  | Código da Empresa |  |

## TGFDITBP — Importação tributos detalhes de IPI
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOIMP | Integer |  | Tipo | `3`=IPI `2`=PIS/COFINS `1`=ICMS |
| DHIMPORT | DateTime |  | Data |  |
| STATUSIMP | String |  | Status importação | `null`=Pendente `D`=Erro `P`=Processado |
| CSTENT | Integer |  | CST Entrada |  |
| CSTSAI | Integer |  | CST Saída |  |
| ALIQIPI | Float |  | Alíquota IPI |  |
| CODENQ | String |  | Código do Enquadramento |  |
| EX | String |  | Exceção |  |
| NCM | String |  | NCM |  |
| CODPROD | Integer |  | Produto |  |
| CODEMP | Integer |  | Código da Empresa |  |

## TGFNCM — CODNCM
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNCM | String |  | NCM |  |
| DSNCM | String |  | Descrição |  |
| DINIVIGENCIA | Date |  | Data Início Vigência |  |
| DFIMVIGENCIA | Date |  | Data Fim Vigência |  |
| CATEGORIA | String |  | Categoria |  |
| DSUNITRIBUTACAO | String |  | Descrição Unidade de Tributação |  |
| UNITRIBUTACAO | String |  | Unidade de Tributação |  |
| IPI | String |  | IPI |  |
| AD_CAMEX | String |  | Lista Lessin ( Camex) | `S`=Sim `N`=Não |
| AD_DATACAMEX | Date |  | Inicio de Vigor da Lista Lessin (Camex) |  |

## TGFNFE — Arquivos XML de NFe
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVENFE | String |  | CHAVENFE |  |
| XML | C |  | XML |  |
| XMLPROTAUTNOT | C |  | XMLPROTAUTNOT |  |
| XMLENVCLI | C |  | XMLENVCLI |  |
| QRCODE | String |  | QRCODE |  |
| XMLENVEPEC | C |  | XMLENVEPEC |  |
| XMLPROTAUTEPEC | C |  | XMLPROTAUTEPEC |  |
| XMLENVCANCPRORROG | C |  | Xml de envio do Cancelamento do Evento de Prorrogação de Prazo de Suspensão do Icms |  |
| XMLENVPRORROG | C |  | Xml de envio do Evento de Prorrogação de Prazo de Suspensão do Icms |  |
| XMLENVCLICANCPRORROG | C |  | XMLENVCLICANCPRORROG |  |
| XMLENVCLIPRORROG | C |  | XMLENVCLIPRORROG |  |
| XMLPROTAUTCANCPRORROG | C |  | Xml de Autorização do Cancelamento do Evento de Prorrogação de Prazo de Suspensão do Icms |  |
| XMLPROTAUTPRORROG | C |  | Xml de Autorização do Evento de Prorrogação de Prazo de Suspensão do Icms |  |
| NUNOTA | Integer |  | NUNOTA |  |
| XMLCANC | C |  | XMLCANC |  |
| XMLENVCARTA | C |  | Xml Envio Carta de Correção |  |
| XMLENVCLICANC | C |  | XMLENVCLICANC |  |
| XMLENVCLICARTA | C |  | Xml de Distribuição da Carta de Correção |  |
| XMLPROTAUTCARTA | C |  | Xml de Autorização de Carta de Correção |  |
| XMLPROTCANC | C |  | XMLPROTCANC |  |

## TGFNFENT — Nota Técnica NFe
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVONT | String |  | Ativo | `S`=Sim `N`=Nao |
| VERSAONT | String |  | Versão Nota Técnica | `2`=Nota Técnica 2021.004 - v1.30 `1`=Nota Técnica 2021.004 - v1.10 `0`=Anterior `3`=Nota Técnica 2020.005 - v1.21 `4`=Nota Técnica 2022.003 - v.1.00_(+9)_ |
| DTENTHOMOLOG | DateTime |  | Data de Homologação |  |
| DTENTPROD | DateTime |  | Data de Produção |  |
| CODEMP | Integer |  | Empresa |  |

## TGFNFT — NFSTModelo21e22
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. de Referência |  |
| FINALIDADE | String |  | Finalidade | `S`=S - Substituto `N`=N - Normal |

## TGFNFTDESTINAT — TGFNFTDESTINAT
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. de Referência |  |
| FINALIDADE | String |  | Finalidade | `S`=S - Substituto `N`=N - Normal |
| NUNOTA | Integer |  | Número da Nota |  |
| CGC_CPF | String |  | CNPJ ou CPF |  |
| INSCESTAD | String |  | Inscrição estadual |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| NOMEEND | String |  | Endereço |  |
| NUMEND | String |  | Número |  |
| COMPLEMENTO | String |  | Complemento |  |
| CEP | String |  | CEP |  |
| NOMEBAI | String |  | Bairro |  |
| NOMECID | String |  | Cidade |  |
| UF | String |  | UF |  |
| TELEFONE | String |  | Telefone de Contato |  |
| CODIDENTCONS | Integer |  | Código de identificação do consumidor ou assinante |  |
| NUMTERMTELUNC | String |  | Nro. Identificação do Terminal Telefônico ou da unidade consumidora |  |
| UFTERMINAL | String |  | UF do Terminal Telefônico |  |
| DTNEG | Date |  | Dt. Neg. |  |
| CODMODDOC | Integer |  | Modelo do Doc. |  |
| SERIENOTA | String |  | Série da nota |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODIBGE | Integer |  | Cod. Município IBGE |  |
| BRANCOSRFUT | String |  | Brancos - reservado para uso futuro |  |
| MD5LINHA | String |  | Código de Autenticação Digital do registro MD5 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODPARC | Integer |  | Cód. Parceiro |  |

## TGFNFTITENS — TGFNFTITENS
Campos: 43

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. de Referência |  |
| FINALIDADE | String |  | Finalidade | `S`=S - Substituto `N`=N - Normal |
| NUNOTA | Integer |  | Número da Nota |  |
| CGC_CPF | String |  | CNPJ ou CPF |  |
| UF | String |  | UF |  |
| CLASSCONS | Integer |  | Classe de Consumo |  |
| TIPUTILCOM | Integer |  | Fase ou Tipo de Utilização | `6`=6 - Outros `5`=5 - Multimídia `4`=4 - Provimento de acesso à Internet `3`=3 - TV por Assinatura `2`=2 - Comunicação de dados_(+1)_ |
| GRUPOTENS | Integer |  | Grupo de Tensão |  |
| DTNEG | Date |  | Dt. Neg. |  |
| CODMODDOC | Integer |  | Modelo do Doc. |  |
| SERIENOTA | String |  | Série da nota |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODCFO | Integer |  | CFOP |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Produto |  |
| DESCRPROD | String |  | Descrição |  |
| CODSERVTELECOM | Integer |  | Cód. Serviço de Telecomunicação |  |
| CODVOL | String |  | Unidade |  |
| QTDCONTR | Integer |  | Quantidade Contratada |  |
| QTDMEDID | Integer |  | Quantidade Medida |  |
| VLRTOT | Float |  | Valor Total |  |
| VLRDESC | Float |  | Vlr. desconto |  |
| VLRACRDESACES | Float |  | Vlr. Acréscimo ou Despesas Acessórias |  |
| BASEICMS | Float |  | Base do ICMS |  |
| VLRICMS | Float |  | Vlr. do ICMS |  |
| VLRISENTONTRIB | Float |  | Vlr. Op. Isento Não Tributado |  |
| VLROUTROS | Float |  | Vlr. Outros |  |
| ALIQICMS | Float |  | Alíq. ICMS |  |
| STATUSDOC | String |  | Situação | `S`=S - Em se tratando de doc. fiscal cancelado dentro do mesmo período de apuração `R`=R - Em se tratando de doc. fiscal emitido em subst. doc. fiscal cancelado no período de apuração `N`=N - Nos demais casos `C`=C - Em se tratando de doc. fiscal complementar |
| DTREFANOMES | Date |  | Dt. de Referência Ano Mês de Apuração |  |
| NUMCONTRATO | Integer |  | Número do contrato |  |
| QTDNEG | Float |  | Quantidade |  |
| TARAPLPRMEF | Float |  | Tarifa Aplicada / Preço Médio Efetivo |  |
| ALIQPIS | Float |  | Alíquota PIS |  |
| VLRPIS | Float |  | Vlr. PIS |  |
| ALIQCOFINS | Float |  | Alíquota COFINS |  |
| VLRCOFINS | Float |  | Vlr. COFINS |  |
| INDDESJUD | String |  | Indicador de Desconto Judicial |  |
| TIPOISENREDBC | Integer |  | Tipo de Isenção/Redução de Base de Cálculo |  |
| BRANCORESFISC | Integer |  | Brancos - reservado para uso futuro |  |
| MD5LINHA | String |  | Código de Autenticação Digital do registro MD5 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |

## TGFNFTMESTRE — TGFNFTMESTRE
Campos: 41

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Dt. de Referência |  |
| FINALIDADE | String |  | Finalidade | `S`=S - Substituto `N`=N - Normal |
| NUNOTA | Integer |  | Nro. Único Nota |  |
| CGC_CPF | String |  | CNPJ ou CPF |  |
| INSCESTAD | String |  | Inscrição estadual |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| UF | String |  | UF |  |
| CLASSCONS | Integer |  | Classe de Consumo |  |
| TIPUTILCOM | Integer |  | Fase ou Tipo de Utilização | `6`=6 - Outros `5`=5 - Multimídia `4`=4 - Provimento de acesso à Internet `3`=3 - TV por Assinatura `2`=2 - Comunicação de dados_(+1)_ |
| GRUPOTENS | Integer |  | Grupo de Tensão |  |
| CODIDENTCONS | String |  | Código de identificação do consumidor ou assinante |  |
| DTNEG | Date |  | Dt. Neg. |  |
| CODMODDOC | Integer |  | Modelo do Doc. |  |
| SERIENOTA | String |  | Série da nota |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODAUDIG | String |  | Código de Autenticação Digital do doc. fiscal |  |
| VLRNOTA | Float |  | Vlr. Total NF |  |
| BASEICMS | Float |  | Base do ICMS |  |
| VLRICMS | Float |  | Vlr. do ICMS |  |
| VLRISENTONTRIB | Float |  | Vlr. Op. Isento Não Tributado |  |
| VLROUTROS | Float |  | Vlr. Outros |  |
| STATUSDOC | String |  | Situação | `S`=S - Em se tratando de doc. fiscal cancelado dentro do mesmo período de apuração `R`=R - Em se tratando de doc. fiscal emitido em subst. doc. fiscal cancelado no período de apuração `N`=N - Nos demais casos `C`=C - Em se tratando de doc. fiscal complementar |
| DTREFANOMES | Date |  | Dt. de Referência Ano Mês de Apuração |  |
| REFITEMNF | Integer |  | Referência ao item da NF |  |
| NUMTERMTELUNC | String |  | Nro. Identificação do Terminal Telefônico ou da unidade consumidora |  |
| INDTIPOINFO | Integer |  | Indicação do tipo de informação contida no campo 1 | `4`=4 - Extrangeiro `3`=3 - ISENTO - Sem inscrição `2`=2 - CPF `1`=1 - CNPJ |
| TIPCLIENTESERVCOM | Integer |  | Tipo Cliente de Serviços de Comunicação | `6`=06 - Prestador de serviço de telecomunicação..., nos termos do Convênio ICMS 17/13 `5`=05 - Órgão da Administração..., nos termos do Convênio ICMS 107/95 `4`=04 - Produtor Rural `3`=03 - Residencial/Pessoa Física `2`=02 - Industrial_(+4)_ |
| SUBCLASSCONS | Integer |  | Subclasse de consumo |  |
| NUMTERMTEL | String |  | Nro. Identificação do Terminal Telefônico |  |
| CGC_CPF_EMIT | String |  | CNPJ ou CPF do emitente |  |
| NUMFATURACOM | Integer |  | Nro. Código da fatura comercial |  |
| VLRTOTAL | Float |  | Valor total da fatura comercial |  |
| DTLEITUANTE | Date |  | Dt. Leitura anterior |  |
| DTLEITUATUA | Date |  | Dt. Leitura atual |  |
| BRANCOSRFU1 | String |  | Brancos Reservados para uso futuro I |  |
| BRANCOSRFU2 | Integer |  | Brancos Reservados para uso futuro II |  |
| INFOADCI | String |  | Informações adicionais |  |
| BRANCOSRFU3 | Integer |  | Brancos Reservados para uso futuro III |  |
| MD5LINHA | String |  | Código de Autenticação Digital do registro MD5 |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |