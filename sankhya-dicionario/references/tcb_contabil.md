# TCB — Contabilidade

> Gerado do dicionário oficial TDD Sankhya. 100 tabelas.


## TCBAAECD — Arquivos Anexos para ECD
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPODOC | String |  | Tipo de documento | `011`=011 - Relatório da Administração `010`=010 - Notas Explicativas `099`=099 - Outros `012`=012 - Parecer dos Auditores `003`=003 - Demonstração do Valor Adicionado_(+2)_ |
| DESCRICAO | String |  | Descrição do Arquivo |  |
| NOMEARQUIVOSKW | String |  | Nome Arquivo |  |
| CAMINHOARQUIVO | String |  | CAMINHOARQUIVO |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBAAECDSUB — Arquivos Anexos para ECD de Substituição
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPODOC | String |  | Tipo de documento | `001`=001 - Termo de Verificação para Fins Substituição da ECD |
| DESCRICAO | String |  | Descrição do Arquivo |  |
| CAMINHOARQUIVO | String |  | CAMINHOARQUIVO |  |
| CODMOTSUBS | String |  | Motivo da substituição | `099`=099 - Outros `005`=005 - Alteração do número do livro `004`=004 - Alteração da forma de escrituração contábil `003`=003 - Alteração de demonstrações contábeis `002`=002 - Alteração de assinatura_(+1)_ |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| NOMEARQUIVOSKW | String |  | Nome Arquivo |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBABE — Termos de abertura e encerramento
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPTERMO | String |  | Tipo do termo |  |
| TERMO | String |  | Termo |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCBAIN — Auditores Independentes
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REGCVM | String |  | Registro na CVM |  |
| NOME | String |  | Nome do Auditor |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CPF | String |  | CPF/CNPJ |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBANA — Análise Financeira
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| DESCRANALISE | String |  | Descrição |  |
| FORMULA | Boolean |  | Fórmula |  |
| CODANALISE | Integer |  | Cód.Análise |  |

## TCBARP — Arquivos Relatórios Personalizados
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TABELA | Integer |  | Tabela | `9`=ImpostosContribuicoes `8`=ImpostosRendaContribuicao `7`=EmprestimosFinanciamentos `6`=CustoServicosVendidos `5`=ClientesContasReceber_(+9)_ |
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| ARQPERSONALIZADO | String |  | Nome Arquivo Personalizado |  |
| IDPASTA | String |  | Periodo referência do arquivo |  |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBATI — Ativo Imobilizado
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição |  |
| INSTALEDIF | Float |  | Instalações e Edificações |  |
| MOVEIS | Float |  | Benfeitorias, Moveis e utensílios |  |
| CONSTRUCOESAND | Float |  | Construções em Andamento |  |
| EQUIPAMENTO | Float |  | Ferramentas, Máquinas e Equipamentos |  |
| IMOBILIZADO | Float |  | Imobilizado em Andamento |  |
| MARCASPATENTES | Float |  | Marcas e Patentes |  |
| TERRENO | Float |  | Terrenos |  |
| VEICULO | Float |  | Veículos |  |
| TIPO | String |  | Tipo Ativo Imobilizado | `D`=Depreciação Acumulada `C`=Custo Imobilizado |
| PARTTOTALIZACAO | String |  | Tem totalização? | `S`=Sim `N`=Não |
| MAQUINA | Float |  | Maquinas e Motores |  |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBATIN — Ativo Intangível
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBBENS — Bens
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Codigo Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição do bem |  |
| TAXDEP | Float |  | Taxa Depreciação |  |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBBFC — Bloqueio Fechamento Contábil
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Código Empresa |  |
| SEQUENCIA | Integer |  | Sequência Bloqueio |  |
| TIPOFECHAESTENT | String |  | Tipo de Fechamento Estoque - Entrada | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTOENT | Date |  | Dt Fechamento Estoque - Entrada |  |
| TIPOFECHAESTSAI | String |  | Tipo de Fechamento Estoque - Saída | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTOSAI | Date |  | Dt Fechamento Estoque Saída |  |
| TIPOFECHACALCUST | String |  | Tipo de Fechamento Calculo Custo | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTOCUS | Date |  | Dt Fechamento Calculo Custo |  |
| TIPOFECHAFINREC | String |  | Tipo de Fechamento Financeiro - Receita | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTOREC | Date |  | Dt Fechamento Financeiro - Receita |  |
| TIPOFECHAFINDESP | String |  | Tipo de Fechamento Financeiro - Despesa | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTODESP | Date |  | Dt Fechamento Financeiro - Despesa |  |
| TIPOFECHAMOVBCO | String |  | Tipo de Fechamento Movimento Bancário | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTOBCO | Date |  | Dt Fechamento Movimento Bancário |  |
| TIPOFECHAMOVCTB | String |  | Tipo de Fechamento Contábil | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTOCTB | Date |  | Dt Fechamento Contábil |  |
| TIPOFECHAMOVFIS | String |  | Tipo de Fechamento Fiscal | `null`=Data `Q`=Quinzenal `D`=48 Horas |
| DTFECHAMENTOFIS | Date |  | Dt Fechamento Fiscal |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| REFERENCIA | Date |  | Referência |  |
| REFFIXA | String |  | Referência fixa | `N`=Não `S`=Sim |
| NUBLOQUEIO | Integer |  | Nro. Config. Bloqueio |  |

## TCBCAIXA — Caixa e Equivalentes de Caixa
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBCALCLUCPRES — Cálculo do Lucro Presumido
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VALORTOTALDESCONTO | Float |  | Vlr total desconto item |  |
| VALORTOTALITEM | Float |  | Vlr total item |  |
| VLRIRF | Float |  | Vlr. do IRF |  |
| VLRIRFOUTROSIMP | Float |  | Vlr. do IRF Outros Impostos |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODNATLP | Integer |  | Item da Apuração |  |
| VLRIPI | Float |  | Vlr. do IPI |  |
| VLRSUBST | Float |  | Vlr. da Substituição |  |
| DTDOCUMENTO | Date |  | Data Documento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPLANC | String |  | Tipo de Lançamento |  |
| TIPMOV | String |  | Tipo de Movimento |  |
| ICMSSTFRETE | Float |  | Vlr. ICMS/ST sobre o frete |  |
| VLRDESCTOT | Float |  | Desconto no total |  |
| VLRDESCTOTITEM | Float |  | Desconto Total por Item |  |
| VLRDOCUMENTO | Float |  | Valor Documento |  |
| VLRICMSFCP | Float |  | Vlr. ICMS Fundo Comb. Pobreza |  |
| VLRICMSFCPINT | Float |  | Vlr. ICMS FCP Interno |  |
| VLRSTFCPINT | Float |  | Vlr. ST FCP Interno |  |
| RECDESP | Integer |  | Tipo de Financeiro |  |
| CODEMP | Integer |  | Empresa |  |

## TCBCBM — Configuração Bloqueio Movimento
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRBLOQUEIO | String |  | Descrição |  |
| CODEMP | Integer |  | Código Empresa |  |
| ATIVO | String |  | Ativa | `S`=Sim `N`=Não |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dh. Alteração |  |
| FECHAMOVENT | String |  | Fechamento Mov. Entrada | `6`=48 Horas `4`=Primeiro dia do mês subsequente `7`=Quinzenal `3`=Dia especifico do mês subsequente `5`=Ultimo dia do mês |
| DIAFECHAMOVENT | Integer |  | Dia Fechamento Mov. Entrada | `9`=9 `7`=7 `5`=5 `31`=31 `3`=3_(+26)_ |
| FECHAMOVSAI | String |  | Fechamento Mov. Saída | `7`=Quinzenal `6`=48 Horas `5`=Ultimo dia do mês `3`=Dia especifico do mês subsequente `4`=Primeiro dia do mês subsequente |
| DIAFECHAMOVSAI | Integer |  | Dia Fechamento Mov. Saída | `6`=6 `3`=3 `24`=24 `2`=2 `18`=18_(+26)_ |
| FECHAMOVCALCCUS | String |  | Fechamento Mov. Calculo Custo | `6`=48 Horas `4`=Primeiro dia do mês subsequente `5`=Ultimo dia do mês `7`=Quinzenal `3`=Dia especifico do mês subsequente |
| DIAFECHAMOVCALCCUS | Integer |  | Dia Fechamento Mov. Calculo Custo | `9`=9 `8`=8 `7`=7 `6`=6 `5`=5_(+26)_ |
| FECHAMOVREC | String |  | Fechamento Mov.  Receita | `7`=Quinzenal `5`=Ultimo dia do mês `4`=Primeiro dia do mês subsequente `6`=48 Horas `3`=Dia especifico do mês subsequente |
| DIAFECHAMOVREC | Integer |  | Dia Fechamento Mov.  Receita | `7`=7 `31`=31 `29`=29 `26`=26 `23`=23_(+26)_ |
| FECHAMOVDESP | String |  | Fechamento Mov. Despesa | `6`=48 Horas `4`=Primeiro dia do mês subsequente `7`=Quinzenal `5`=Ultimo dia do mês `3`=Dia especifico do mês subsequente |
| DIAFECHAMOVDESP | Integer |  | Dia Fechamento Mov. Despesa | `9`=9 `6`=6 `4`=4 `30`=30 `3`=3_(+26)_ |
| FECHAMOVBCO | String |  | Fechamento Mov. Bancário | `7`=Quinzenal `3`=Dia especifico do mês subsequente `6`=48 Horas `5`=Ultimo dia do mês `4`=Primeiro dia do mês subsequente |
| DIAFECHAMOVBCO | Integer |  | Dia Fechamento Mov. Bancário | `9`=9 `8`=8 `7`=7 `6`=6 `5`=5_(+26)_ |
| FECHAMOVCTB | String |  | Fechamento Mov. Contábil | `7`=Quinzenal `6`=48 Horas `3`=Dia especifico do mês subsequente `5`=Ultimo dia do mês `4`=Primeiro dia do mês subsequente |
| DIAFECHAMOVCTB | Integer |  | Dia Fechamento Mov. Contábil | `30`=30 `3`=3 `29`=29 `28`=28 `27`=27_(+26)_ |
| FECHAMOVFIS | String |  | Fechamento Mov. Livro Fiscais | `4`=Primeiro dia do mês subsequente `6`=48 Horas `7`=Quinzenal `3`=Dia especifico do mês subsequente `5`=Ultimo dia do mês |
| DIAFECHAMOVFIS | Integer |  | Dia Fechamento Mov. Livro Fiscais | `9`=9 `7`=7 `5`=5 `31`=31 `3`=3_(+26)_ |
| AD_DTFECHAMENTO | Date |  | Data de Fechamento |  |
| NUCONFBLOQUEIO | Integer |  | Nro. Configuração |  |

## TCBCCO — Configuração do Controle Orçamentário Contábil
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EMPPART | String |  | Empresa | `S`=Sim `N`=Não |
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CTACTBPART | String |  | Conta Contábil | `S`=Sim `N`=Não |
| GRUCTACTBPART | String |  | Grupo de Contas Contábeis | `S`=Sim `N`=Não |
| PROJPART | String |  | Projeto | `N`=Não `S`=Sim |
| APRESCOD | String |  | Apresenta Código Junto com a Descrição | `S`=Sim `N`=Não |
| CRPART | String |  | Centro de Resultado | `S`=Sim `N`=Não |
| CALDESINRECDESP | String |  | Calculo do desvio considerando lançamentos inversos | `S`=Sim `N`=Não |
| DETALHARPOR | String |  | Detalhar por | `R`=Centro Resultado `P`=Projeto `C`=Conta Contábil |
| PERIODIC | String |  | Periodicidade | `T`=Trimestral `S`=Semestral `M`=Mensal `A`=Anual `B`=Bimestral |
| ZERARCTACTAB | String |  | Desprezar zeramento de contas de resultado | `S`=Sim `N`=Não |
| USASALCONREALI | String |  | Utiliza Resultado Mensal das Contas para coluna de Realizado e Desvio | `N`=Não `S`=Sim |
| DTINICORC | Integer |  | Data Início | `4`=Maio `3`=Abril `2`=Março `10`=Novembro `1`=Fevereiro_(+7)_ |
| CODCCO | Integer |  | Código |  |

## TCBCCR — Clientes e contas a receber
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `N`=Não `S`=Sim |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBCDM — Contas do Demonstrativo
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTDM | Integer |  | Código Tipo Demonstrativo |  |
| CODDMT | String |  | Código Hierárquia Demonstrativo |  |
| CODCTACTB | Integer |  | Código Reduzido |  |
| CODEMP | Integer |  | Código Empresa |  |

## TCBCFGAPLP — Configurações para apuração do Lucro Presumido
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNATLP | Integer |  | Item da Apuração |  |
| TIPDATANOTAS | String |  | Tipo de Data para Notas | `M`=Data de Movimento `N`=Data de Negociação `null`=Data Entrada e Saída |
| TIPDATAFIN | String |  | Tipo de Data para Financeiro | `M`=Data de Movimento `N`=Data de Negociação `null`=Data Entrada e Saída |
| DEDIPIBC | String |  | Deduz IPI da BC | `N`=Não `S`=Sim |
| DEDICMSSTBC | String |  | Deduz ICMS ST da BC | `N`=Não `S`=Sim |
| DEDDESCINCBC | String |  | Deduz Descontos Incondicionais da BC | `N`=Não `S`=Sim |
| CONFIG | C |  | Configuração |  |
| CONSIRRECEITA | String |  | Usa valor total item para receita | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |

## TCBCFGAPLPNAT — Natureza de Receitas e Despesas
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNATLP | Integer |  | Item da Apuração |  |
| CODNAT | Integer |  | Natureza |  |
| CODEMP | Integer |  | Empresa |  |

## TCBCOM — Composição dos Grupos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOCTA | Integer |  | Grupo dos demonstrativos |  |
| CODCTACTB | Integer |  | Cód.Conta contábil |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCBCRA — Configuração para Razão Auxiliar
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TAMFONTE | Integer |  | Tamanho da Fonte |  |
| NATLIV | String |  | Natureza do Livro |  |
| LISTCAMPOSORDENACAO | String |  | Lista de Campos p/ Ordenação |  |
| NROORDEM | Integer |  | Nro. Ordem |  |
| CMDSQL | String |  | SQL |  |
| CODRAZAUX | Integer |  | Cód. Razão Auxiliar |  |

## TCBCRAD — Detalhes Configuração para Razão Auxiliar
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NOMECAMPO | String |  | Nome do Campo |  |
| DESCRCAMPO | String |  | Descrição do Campo |  |
| TAMCAMPO | Integer |  | Tamanho do Campo |  |
| LARGCAMPO | Integer |  | Largura do Campo |  |
| TIPOCAMPO | String |  | Tipo do Campo | `C`=Caracter `N`=Numérico |
| QTDCASADEC | Integer |  | Qtd. Casas Decimais |  |
| TOTALIZACAO | String |  | Totalização | `F`=Texto Fixo `Z`=Zerar na Totalização `T`=Totalizar |
| TEXTOFIXO | String |  | Texto Fixo |  |
| PARTQUEBRA | String |  | Participa Quebra? | `N`=Não `S`=Sim |
| CODRAZAUX | Integer |  | Cód. Razão Auxiliar |  |

## TCBCRP — Cabecalho Relatórios Personalizados
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| TABELA | Integer |  | Tabela | `9`=ImpostosContribuicoes `8`=ImpostosRendaContribuicao `7`=EmprestimosFinanciamentos `6`=CustoServicosVendidos `5`=ClientesContasReceber_(+9)_ |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBCTE — Conta Contábil Estorno
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTACTB | Integer |  | Conta reduzida |  |
| CODCTACTBEST | Integer |  | Conta vinculada |  |

## TCBCTR — Conta Contábil Referencial
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | Integer |  | Tipo | `10`=10 - Financeiras - Lucro Presumido `9`=9 - Partidos Políticos `8`=8 - Entidades Fechadas de Previdência Complementar `7`=7 - Imunes e Isentas - Seguradoras `6`=6 - Imunes e Isentas - Financeiras_(+5)_ |
| CODCTAREF | String |  | Cód. Conta Ref. |  |
| CODCTACTB | Integer |  | Conta reduzida |  |

## TCBDEM — Demonstrativos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODDEMONST | Integer |  | Cód.Demonstrativo |  |
| DESCRDEMONST | String |  | Descrição |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCBDEP — Método de Depreciação
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANO | Integer |  | Ano |  |
| TIPO | String |  | Tipo |  |
| METODO | String |  | Método | `A`=Depreciação para ajuste  Lei 11.638/2007 `T`=Fiscal/Contábil Tradicional |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODEMP | Integer |  | CODEMP |  |

## TCBDIN — Tabelas Dinâmicas Importadas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | String |  | Código |  |
| TIPOLANC | String |  | Tipo de Lançamento |  |
| DESCRICAO | String |  | Descrição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| TABELA | String |  | Tabela |  |

## TCBDMT — Hierarquia de Demonstrativos
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTDM | Integer |  | Cód. Tipo Demonstrativo |  |
| CODDMT | String |  | Código |  |
| DESCRDMT | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| CODDMTPAI | String |  | Código Pai |  |
| GRAU | Integer |  | Grau |  |
| SITUACAO | String |  | Situação | `A`=Automático `T`=Subtotal ou total |
| INDGRUBAL | String |  | Grupo Balanço | `2`=Passivo e Patrimônio Líquido `1`=Ativo |
| AGRUPDLPA | String |  | Agrupamento p/ DLPA | `N`=Não `S`=Sim |
| GRUPODEMONST | String |  | Grupo p/ Demonstrativo | `5`=Passivo Não Circulante `4`=Patrimônio Líquido `3`=Passivo Circulante `2`=Ativo Não Circulante `1`=Ativo Circulante |
| GERADRA | String |  | Gera DRA ? | `S`=Sim `N`=Não |
| INVERTVLRALT | String |  | Inverter valor automático | `S`=Sim `N`=Não |
| GRUPDEMONSDFC | String |  | Grupo p/ Demonstrativo | `5`=Outras Atividades `4`=Totalizador das Atividades Principais `3`=Atividades De Financiamento `2`=Atividades De Investimento `1`=Atividades Operacionais |
| SITDFC | String |  | Situação | `4`=Subtotal ou total `2`=Saldo Final `1`=Saldo Inicial `3`=Saldo do Movimento |
| INDGRPDRE | String |  | Indicador de grupo da DRE | `R`=Representa incremento do lucro `D`=Representa redução do lucro |
| NUORDEM | Integer |  | Número da Ordem |  |
| INDDCCTAINI | String |  | Classificação do Saldo Inicial | `C`=Credor `D`=Devedor |
| INDDCCTAFIN | String |  | Classificação do Saldo Final | `D`=Devedor `C`=Credor |
| CODEMP | Integer |  | Código Empresa |  |

## TCBDNE — Demonstrativos Notas Explicativas
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Nro. Nota Explicativa |  |
| NUDNEPAI | Integer |  | Nro Nota Explicativa Pai |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| GERASSINATURA | String |  | Gerar Assinaturas | `N`=Não `S`=Sim |
| QUEBRAPAGINA | String |  | Quebrar página | `N`=Não `S`=Sim |
| INDENTTIT | String |  | Identificador do título |  |
| NIVEL | Integer |  | Ordem |  |
| TIPO | String |  | Tipo da Nota Explicativa | `T`=Texto `I`=Imagens `B`=Planilha(Tabelas) |
| TITULO | String |  | Título da Nota Explicativa |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| TEXTO | C |  | Descrição Nota Explicativa |  |
| IMAGEM | String |  | Imagem |  |
| DESCIMAGEM | String |  | Descrição Objetiva da Imagem |  |
| CODTAB | Integer |  | Tabela | `13`=ReceitasDespesasFinanceiras `5`=ClientesContasReceber `1`=AtivoImobilizado `8`=ImpostosRendaContribuicao `7`=EmprestimosFinanciamentos_(+9)_ |
| PERCENTUAL | String |  | Percentual | `N`=Não `S`=Sim |
| FORMATDTIMPR | Integer |  | Formato data p/ impressão | `2`=MM/AAAA `1`=DD/MM/AAAA `3`=AAAA |
| SIMBOLOS | Integer |  | Valores Negativos | `5`=( 100,00) `4`=(100,00) `3`=-100,00 `2`=100,00D `1`=100,00- |
| CODTDM | Integer |  | Tipo Demonstrativo | `1`=Balanço Patrimonial `2`=DRE/DRA `4`=DFC |
| CODDMT | String |  | Código demonstrativos ECD |  |
| CODUSU | Integer |  | Código Usuário |  |
| GERANECOLUNASVALOR | String |  | Gerar N.E somente para colunas com valores ? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBDPLR — Tabelas Dinâmicas do Plano de Conta Referencial
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | Integer |  | Tipo |  |
| ANO | Integer |  | Ano |  |
| VERSAO | String |  | Versão |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| TABELA | String |  | Tabela |  |

## TCBECB — Definição dos blocos a serem gerados EBC
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BLOCO | String |  | Bloco |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCRICAO | String |  | Descrição |  |
| GERARBLOCO | String |  | Gerar Bloco | `S`=Sim `N`=Não |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODEMP | Integer |  | Cód.Emp |  |

## TCBECF — Configurador de Blocos e Registros
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BLOCO | String |  | Bloco | `W`=W `U`=U `N`=N `Q`=Q `V`=V_(+4)_ |
| REGISTRO | Integer |  | Registro |  |
| CODIGO | String |  | Código |  |
| TIPO | String |  | Tipo de Dados | `P`=P - Plano de contas `S`=S - Comando sql `V`=V - Valor `A`=A - Arquivo texto |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| PERMVLRZERADO | String |  | Permite gerar registro com valor zerado? | `S`=Sim `N`=Não |
| ARQUIVOSKW | String |  | Arquivo |  |
| CMDSQL | String |  | SQL |  |
| VALOR | Float |  | Valor |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TABELA | String |  | Tabela |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBECFC — Contas p/ Configurador de Blocos e Registros
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CTACTB | String |  | Cód. Conta |  |
| CODIGO | String |  | Código |  |
| BLOCO | String |  | Bloco |  |
| REGISTRO | Integer |  | Registro |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODCTACTB | Integer |  | Cód. Reduzido |  |

## TCBECR — Definição Registro Bloco ECB
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BLOCO | String |  | Bloco |  |
| REGISTRO | String |  | Registro |  |
| DESCRICAO | String |  | Descrição |  |
| FORMAESCRIT_G | String |  | G | `N`=Não `S`=Sim |
| FORMAESCRIT_R | String |  | R | `N`=Não `S`=Sim |
| FORMAESCRIT_A | String |  | A | `S`=Sim `N`=Não |
| FORMAESCRIT_B | String |  | B | `N`=Não `S`=Sim |
| FORMAESCRIT_Z | String |  | Z | `N`=Não `S`=Sim |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODEMP | Integer |  | Cód.Emp |  |

## TCBEFB — Definição dos blocos a serem gerados EFB
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BLOCO | String |  | Bloco |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCRICAO | String |  | Descrição |  |
| GERARBLOCO | String |  | Gerar Bloco | `N`=Não `S`=Sim |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBEFR — Definição Registro Bloco EFB
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BLOCO | String |  | Bloco |  |
| REGISTRO | String |  | Registro |  |
| DESCRICAO | String |  | Descrição |  |
| GERARREGISTRO | String |  | Gerar Registro | `N`=Não `S`=Sim |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBEMP — Empresas (contabilidade)
Campos: 111

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTABERTURA | Date |  | Data da abertura |  |
| DTINICPERCTB | Date |  | Início do período contábil |  |
| DTFIMPERCTB | Date |  | Fim do período contábil |  |
| REFERENCIA | Date |  | Referência |  |
| NUMDIARIO | Integer |  | Número do diário |  |
| ULTPAGDIARIO | Integer |  | Última página do diário |  |
| CONTADOR | String |  | Contador |  |
| CRC | String |  | CRC |  |
| MASCCTA | String |  | Máscara da conta |  |
| DIGCTA | String |  | Dígito da conta | `1`=Com dígito de verificador módulo 10 `0`=Sem dígito de verificador `2`=Com dígito de verificador módulo 11 |
| CODEMPPLACTA | Integer |  | Empresa do plano de contas |  |
| PERALTQDCOM | String |  | Permitir alteração por outras empresas quando compartilhado | `N`=Não `S`=Sim |
| EMPCOPPLA | Integer |  | Empresa p/ copiar o plano de contas |  |
| CTAREDAUT | String |  | Conta reduzida automática | `0`=Codificação automática `2`=Manual sem dígito de verificador `1`=Manual com dígito módulo 11 |
| ACEITARHISTZERO | String |  | Aceitar histórico zero | `N`=Não `S`=Sim |
| UTILCENCUS | String |  | Utiliza Centro de resultado | `N`=Não `S`=Sim |
| UTILPROJ | String |  | Utiliza Projeto | `S`=Sim `N`=Não |
| NUMLOTESAUT | String |  | Numeração dos Mestres de Lote | `M`=Manual `R`=Empresa/Referência `E`=Empresa |
| ULTIMONUMEROUSADO | Integer |  | Último Número Usado |  |
| SIMBVLRNEG | String |  | Símbolo para valores negativos | `2`=-100,00 `5`=(      100,00) `1`=100,00- `4`=(100,00) `3`=100,00D |
| ACEITARVLRLANC | String |  | Aceitar valor lançamento zero | `N`=Não `S`=Sim |
| TIPATUALSALDOS | String |  | Tipo de atualização de saldos | `D`=Somente contas analíticas durante a digitação `L`=Somente na liberação dos lançamentos |
| EMPCONSOLIDA | String |  | Consolida empresa |  |
| CODEMPORIG | Integer |  | Cód. Empresa Origem |  |
| PERCRATEIO | Integer |  | % Rateio |  |
| NROORDEM | Integer |  | N.º Ordem Instrumento Escrituração (G) |  |
| NROORDEM_R | Integer |  | N.º Ordem Instrumento Escrituração (R) |  |
| UFCRCCONTADOR | String |  | UF CRC |  |
| CODINSTRESP | String |  | Instituição Resp. Man. Plano Contas Referencial | `10`=10 - Financeiras - Lucro Presumido `1`=1 - PJ em Geral `8`=8 - Entidades Fechadas de Previdência Complementar `0`=Nenhuma `9`=9 - Partidos Políticos_(+6)_ |
| NROLOTEMNUALINI | Integer |  | Início do número do lote manual |  |
| TIPPERIODO | String |  | Período de Geração das Demonstrações Contábeis | `A`=Anual `S`=Semestral `T`=Trimestral `B`=Bimestral `M`=Mensal |
| NROLOTEMNUALFIM | Integer |  | Fim do número do lote manual |  |
| TPOEMPRESA | Integer |  | Tipo de Empresa | `2`=2 - SCP `1`=1 - Empresa participante de SCP como sócio ostensivo `0`=0 - Empresa não participante de SCP como sócio ostensivo |
| CABDEM | String |  | Cabeçalho das Demonstrações |  |
| CODCTACTBENCRES | Integer |  | Conta Contábil de Encerramento de Resultado |  |
| OPTREFIS | String |  | Optante pelo REFIS | `N`=Não `S`=Sim |
| OPTPAES | String |  | Optante pelo PAES | `N`=Não `S`=Sim |
| FORMATRIB | Integer |  | Forma de Tributação | `3`=3 - Lucro Presumido/Real `8`=8 - Imune do IRPJ `7`=7 - Lucro Presumido/Arbitrado `6`=6 - Lucro Arbitrado `5`=5 - Lucro Presumido_(+4)_ |
| FORMAAPUR | String |  | Indicador do Período de Apuração de IRPJ e da CSLL | `T`=T - Trimestral `A`=A - Anual |
| TIPESCPRE | String |  | Escrituração | `C`=C - Contábil (Lucro Presumido, Imunes ou Isentas) `L`=L - Livro Caixa ou Lucro Presumido ou Sem Escrituração ou Não obrigada a entregar a ECD |
| TIPENT | String |  | Tipo de Pessoa Jurídica Imune ou Isenta | `11`=11 - Associação de Poupança e Empréstimo `10`=10 - Científica `99`=99 - Outras `15`=15 - Partidos Políticos `14`=14 - CIO Entidades Relacionadas_(+11)_ |
| FORMAAPURI | String |  | Apuração do IRPJ para Imunes ou Isentas | `D`=D - Desobrigada `T`=T - Trimestral `A`=A - Anual |
| APURCSLL | String |  | Apuração do CSLL para Imunes ou Isentas | `A`=A - Anual, se optou pela apuração da CSLL sobre a base de cálculo estimada `D`=D - Desobrigada, na hipótese de pessoa jurídica imune ou isenta da CSLL `T`=T - Trimestral, no caso de ter adotada apuração trimestral da CSLL |
| PJSUJEITACSLL | String |  | PJ Sujeita à Alíquota da CSLL de 9%, 15%, 17% ou 20% em 31/12/2015 | `3`=20% `2`=17% `1`=9% `null`=Não se aplica `4`=15% |
| OPTEXTRTT | String |  | Optante pela extinção do RTT no ano-calendário de 2014 | `S`=Sim `N`=Não |
| DIFFCONT | String |  | Existe diferenças entre a contabilidade societária e Fcont | `S`=Sim `N`=Não |
| INDALIQCSLL | String |  | PJ Sujeita à Alíquota da CSLL de 15% | `N`=Não `S`=Sim |
| INDADMFUNCLU | String |  | Administradora de Fundos e Clubes de Investimento | `N`=Não `S`=Sim |
| INDPARTCONS | String |  | Participações em Consórcios de Empresas | `N`=Não `S`=Sim |
| INDOPEXT | String |  | Operações com o Exterior | `N`=Não `S`=Sim |
| INDOPVINC | String |  | Operações com Pessoa Vinculada/Interposta Pessoa / País com Tributação Favorecida | `N`=Não `S`=Sim |
| INDPJENQUAD | String |  | PJ Enquadrada nos artigos 48 ou 49 da IN RFB no 1.312/2012 | `S`=Sim `N`=Não |
| INDPARTEXT | String |  | Participações no Exterior | `N`=Não `S`=Sim |
| INDATIVRURAL | String |  | Atividade Rural | `N`=Não `S`=Sim |
| INDLUCEXP | String |  | Existência de Lucro da Exploração | `N`=Não `S`=Sim |
| INDREDISEN | String |  | Isenção e Redução do Imposto para Lucro Presumido | `N`=Não `S`=Sim |
| INDFIN | String |  | Indicativo da Existência de FINOR/FINAM | `N`=Não `S`=Sim |
| INDDOAELEIT | String |  | Doações a Campanhas Eleitorais | `N`=Não `S`=Sim |
| INDPARTCOLIG | String |  | Participação Avaliada pelo Método de Equivalência Patrimonial | `N`=Não `S`=Sim |
| INDVENDEXP | String |  | PJ Efetuou Vendas a Empresa Comercial Exportadora com Fim Específico de Exportação | `N`=Não `S`=Sim |
| INDRECEXT | String |  | Recebimentos do Exterior ou de Não Residentes | `N`=Não `S`=Sim |
| INDATIVEXT | String |  | Ativos no Exterior | `N`=Não `S`=Sim |
| INDCOMEXP | String |  | PJ Comercial Exportadora | `N`=Não `S`=Sim |
| INDPGTOEXT | String |  | Pagamentos ao Exterior ou a Não Residentes | `N`=Não `S`=Sim |
| INDECOMTI | String |  | Comércio Eletrônico e Tecnologia da Informação | `N`=Não `S`=Sim |
| INDROYREC | String |  | Royalties Recebidos do Brasil e do Exterior | `N`=Não `S`=Sim |
| INDROYPAG | String |  | Royalties Pagos a Beneficiários do Brasil e do Exterior | `N`=Não `S`=Sim |
| INDRENDSERV | String |  | Rendimentos Relativos a Serviços, Juros e Dividendos Recebidos do Brasil e do Exterior | `N`=Não `S`=Sim |
| INDPGTOREM | String |  | Pagamentos ou Remessas a Título de Serviços, Juros e Dividendos a Beneficiários do Brasil e do Exterior | `N`=Não `S`=Sim |
| INDINOVTEC | String |  | Inovação Tecnológica e Desenvolvimento Tecnológico | `N`=Não `S`=Sim |
| INDCAPINF | String |  | Capacitação de Informática e Inclusão Digital | `N`=Não `S`=Sim |
| INDPJHAB | String |  | PJ Habilitada no Repes, Recap, Padis, PATVD, Reidi, Repenec, Reicomp, Retaero, Recine, Resíduos Sólidos, Recopa... | `N`=Não `S`=Sim |
| INDPOLOAM | String |  | Pólo Industrial de Manaus e Amazônia Ocidental | `N`=Não `S`=Sim |
| INDZONEXP | String |  | Zonas de Processamento de Exportação | `N`=Não `S`=Sim |
| INDAREACOM | String |  | Áreas de Livre Comércio | `N`=Não `S`=Sim |
| INDREPES | String |  | Regime Especial de Tributação para Plataforma de Exportação de Serviços de Tecnologia da Informação (Repes) | `N`=Não `S`=Sim |
| INDRECAP | String |  | Regime Especial de Aquisição de Bens de Capital para Empresas Exportadoras (Recap) | `N`=Não `S`=Sim |
| INDPADIS | String |  | Programa de Apoio ao Desenvolvimento Tecnológico da Indústria de Semicondutores (Padis) | `N`=Não `S`=Sim |
| INDPATVD | String |  | Programa de Apoio ao Desenvolvimento Tecnológico da Indústria de Equip. para TV Digital (PATVD) | `N`=Não `S`=Sim |
| INDREIDI | String |  | Regime Especial de Incentivos para o Desenvolvimento da Infraestrutura (Reidi) | `N`=Não `S`=Sim |
| INDREPENEC | String |  | Regime Especial de Incentivos para o Desenvolvimento da Infraestrutura da Indústria Petrolífera... | `N`=Não `S`=Sim |
| INDREICOMP | String |  | Regime Especial de Incentivo a Computadores para Uso Educacional (Reicomp) | `N`=Não `S`=Sim |
| INDRETAERO | String |  | Regime Especial para Indústria Aeronáutica Brasileira (Retaero) | `N`=Não `S`=Sim |
| INDRECINE | String |  | Regime Especial de Tributação para Desenvolvimento da Atividade de Exibição Cinematográfica (Recine) | `N`=Não `S`=Sim |
| INDRESIDUOSSOLID | String |  | Estabelecimentos industriais façam jus a crédito presumido do IPI na aquisição de resíduos sólidos | `N`=Não `S`=Sim |
| INDRECOPA | String |  | Regime Especial de Tributação para construção, ampliação, reforma ou modernização de estádios de futebol (Recopa) | `S`=Sim `N`=Não |
| INDCOPADOMUNDO | String |  | Habilitada para fins dos benefícios fiscais da Copa das Confederações e da Copa do Mundo | `S`=Sim `N`=Não |
| INDRETID | String |  | Regime Especial Tributário para Indústria de Defesa (Retid) | `N`=Não `S`=Sim |
| INDREPNBLREDES | String |  | Regime Especial de Tributação do Programa Nacional de Banda Larga para Implantação de Redes de Telecomunicações | `S`=Sim `N`=Não |
| INDREIF | String |  | Regime Especial de Incentivo ao Desenvolvimento da Infraestrutura da Indústria de Fertilizantes (REIFI) | `N`=Não `S`=Sim |
| INDOLIMPIADAS | String |  | Habilitada para fins dos benefícios fiscais dos Jogos Olímpicos de 2016 e dos Jogos Paraolímpicos de 2016 | `N`=Não `S`=Sim |
| INDRECRECEITA | Integer |  | Critério de reconhecimento de receitas (L.Presumido) | `0`=0 - Não se aplica `1`=1 - Regime de Caixa `2`=2 - Regime de Competência |
| INDPAISAPAIS | String |  | A pessoa jurídica é entidade constituinte de grupo multinacional obrigado à entrega da Declaração País a País | `N`=Não `S`=Sim |
| ARQLOGOMARCA | String |  | Caminho para o Arquivo Logomarca |  |
| DEREX | String |  | Declaração sobre utilização dos recursos em moeda estrangeira decorrentes do recebimento de exportações (DEREX) | `S`=Sim `N`=Não |
| GERREGJPERANUAL | String |  | Gerar registros J005, J100, J150 e J210 com periodicidade anual | `S`=Sim `N`=Não |
| USAEMPAUXCTBZ | String |  | Gravar Empresa de Origem nos lançamentos | `S`=Sim `N`=Não |
| OPCPTRF2023 | String |  | Opção pelas novas regras de preços de transferência no ano-calendário 2023 (Lei nº 14.956/2023) | `N`=Não `S`=Sim |
| INDOLEOBUNKER | String |  | Regime de Suspensão de Óleo Bunker | `N`=Não `S`=Sim |
| INDREPORTO | String |  | Regime Tributário para o Incentivo à Modernização e à Ampliação da Estrutura Portuária (Reporto) | `N`=Não `S`=Sim |
| INDRETII | String |  | Regime Especial de Tributação para Incorporações Imobiliárias com Patrimônio de Afetação (RET-II) | `N`=Não `S`=Sim |
| INDRETPMCMV | String |  | Regime Especial de Tributação para Construções do Programa Minha Casa, Minha Vida (RET-PMCMV) | `N`=Não `S`=Sim |
| INDRETEEI | String |  | Regime Especial de Tributação para Construções ou Reformas de Estabelecimentos de Educação Infantil (RET-EEI) | `N`=Não `S`=Sim |
| INDEBAS | String |  | Entidade Beneficente de Assistência Social (EBAS) | `N`=Não `S`=Sim |
| INDREPETROIND | String |  | Regime Especial de Industrialização para Bens na Exploração de Petróleo e Gás (REPETRO-INDUSTRIALIZAÇÃO) | `S`=Sim `N`=Não |
| INDREPETRONAC | String |  | Regime Tributário e Aduaneiro Especial para Exploração de Petróleo e Gás (REPETRO-NACIONAL) | `N`=Não `S`=Sim |
| INDREPEPER | String |  | Regime Tributário e Aduaneiro Especial para Exploração de Petróleo e Gás (REPETRO-PERMANENTE) | `N`=Não `S`=Sim |
| INDREPETROTEMP | String |  | Regime Tributário e Aduaneiro Especial para Exploração de Petróleo e Gás (REPETRO-TEMPORÁRIO) | `N`=Não `S`=Sim |
| INDMUDANCPC | Integer |  | Indicador de mudança de plano de contas: | `0`=Não houve mudança no plano de contas `1`=Houve mudança no plano de contas |
| ALIQCSLL | Integer |  | Aliquota de CSLL (Lei nº 11.727, de 2008, art. 17) | `15`=15% `9`=9% |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBEMPFIN — Empréstimos e Financiamentos
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| MODALIDADE | String |  | Modalidade |  |
| ENCARGOS | Float |  | Encargos Nominais (Ao ano) |  |
| TIPO | Integer |  | Tipo Passivo | `2`=Passivo Não Circulante `1`=Passivo Circulante |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBERR — TABLE TCBERR
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo Agendamento |  |
| DHCTZ | DateTime |  | Data da Contabilização |  |
| ORIGEM | String |  | Origem Mov. |  |
| NUNICO | Integer |  | Número Único Mov. |  |
| TIPLANC | String |  | Tipo Lançamento |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação Ctbz |  |
| SEQCTB | Integer |  | Sequência Ctbz |  |
| DESCRICAO | String |  | Descrição do Erro |  |
| CONTABILIZADO | String |  | Contabilizado |  |
| NUAGENDCTZ | Integer |  | Número Único Agend. |  |
| NUSEQERR | Integer |  | Sequência Erro |  |

## TCBEXE — Exercícios
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INICIOEXERCICIO | DateTime |  | Início do exercício |  |
| FIMEXERCICIO | DateTime |  | Fim do exercício |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCBFCT — Fato Contábil
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFATOCONTB | String |  | Código Fato Contábil |  |
| DESCFATCONTB | String |  | Desc. Fato Contábil |  |
| SITUACAO | String |  | Situação | `T`=Subtotal ou total `A`=Automático |
| TIPOFATO | String |  | Tipo | `N`=Normal `I`=Saldo inicial `F`=Saldo final |
| CODEMP | Integer |  | Código Empresa |  |

## TCBFTR — Forma de Tributação no Período
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EXERCICIO | Integer |  | Exercício |  |
| TRIMESTRE | Integer |  | Trimestre | `2`=2° - Trimestre `3`=3° - Trimestre `1`=1° - Trimestre `4`=4° - Trimestre |
| FORMATRIBPER | String |  | Forma de Tributação | `R`=R - Real `E`=E - Real Estimativa `A`=A - Arbitrado `P`=P - Presumido |
| MES1BALRED | String |  | Jan/Abr/Jul/Out | `B`=B - Balanço ou Balancete `E`=E - Receita Bruta |
| MES2BALRED | String |  | Fev/Mai/Ago/Nov | `B`=B - Balanço ou Balancete `E`=E - Receita Bruta |
| MES3BALRED | String |  | Mar/Jun/Set/Dez | `E`=E - Receita Bruta `B`=B - Balanço ou Balancete |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Cód. Emp |  |

## TCBGRU — Grupo dos demonstrativos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPOCTA | String |  | Descrição |  |
| DESCRACUM | String |  | Descrição do acumulado |  |
| CODDEMONST | Integer |  | Cód.Demonstrativo |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODGRUPOCTA | Integer |  | Cod.Grupo |  |

## TCBHCT — TABLE TCBHCT
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo do Agendamento |  |
| DHCTZ | DateTime |  | Data da Contabilização |  |
| QTDLANCTOT | Integer |  | Qtde de Lançamentos |  |
| QTDLANCCTZ | Integer |  | Qtde Contabilizados |  |
| QTDLANCNCTZ | Integer |  | Qtde  Não Contabilizados |  |
| MINUTOSCTZ | Integer |  | Tempo Gasto |  |
| TIPOEXEC | String |  | Tipo de Execução | `A`=Automático `M`=Manual |
| ERROEXEC | C |  | Mensagem |  |
| LIBERADA | String |  | Status | `S`=Liberado Sem Int. `null`=Liberado `P`=Pendente `L`=Liberado Com Int. |
| NUAGENDCTZ | Integer |  | Número Único Agend. |  |

## TCBHFC — Histórico do Fato Contábil
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFATOCONTB | String |  | Código Fato Contábil |  |
| CODHISTCTB | Integer |  | Cód. do Histórico Padrão |  |
| CODEMP | Integer |  | Código Empresa |  |

## TCBHID — Histórico de Atualização das Tabelas Dinâmicas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTEXEC | DateTime |  | Dt. Execução |  |
| MSG | String |  | Mensagem |  |
| TIPOATUALIZACAO | String |  | Tipo da Execução | `V`=Apenas Verificação `F`=Houve  Falha `A`=Houve Atualização |
| TEMPOGASTO | Integer |  | Tempo Gasto |  |
| CODHIS | Integer |  | Cód. Histórico |  |

## TCBHIS — Histórico
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| HISTORICO | String |  | Descrição |  |
| CODHISTCTB | Integer |  | Código |  |

## TCBHLT — Histórico de lotes
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| DHCTZ | DateTime |  | Data da Contabilização |  |
| NUMLOTE | Integer |  | Número do Lote |  |
| REFERENCIA | DateTime |  | Referência |  |
| CODEMP | Integer |  | Empresa |  |
| NUAGENDCTZ | Integer |  | Número Único Agend. |  |

## TCBILB — Itens Liberação Bloqueio Contábil
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NULIBERACAO | Integer |  | Nro. Liberação |  |
| TABELA | String |  | Movimento | `TGFCUS`=Calculo de Custo - Produto/Serviço `TGFCAB_CUS`=Calculo de Custo - Nota `TGFAJN`=Ajuste Apuração `TGFCAB`=Cabecalho Nota `TGFFIN`=Financeiro_(+4)_ |
| TIPO | String |  | Tipo | `E`=Entrada `R`=Receita `D`=Despesa `S`=Saída |
| NUCHAVE | Integer |  | Nro. Chave |  |

## TCBIMP — Impostos/Contribuições
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCIMP | String |  | Descrição do Imposto |  |
| BASE | Float |  | Base de Cálculo |  |
| ALIQ | Float |  | Alíquota |  |
| VALOR | Float |  | Valor |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `N`=Não `S`=Sim |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBIMPRC — Impostos sobre a renda e contribuição social
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBINT — Integração da Contabilidade com o Financeiro
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | DateTime |  | Referência |  |
| NUMLANC | Integer |  | Número do lançamento |  |
| TIPLANC | String |  | Tipo de lançamento |  |
| ORIGEM | String |  | Origem | `F`=Financeiro `E`=Estoque `B`=Baixa `M`=Banco `R`=Renegociado |
| NUNICO | Integer |  | Número único |  |
| NUMLOTE | Integer |  | Número do lote |  |
| VLRLANC | Float |  | Valor do Lançamento |  |
| SEQNOTA | Integer |  | SEQNOTA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCBIRP — Tabela da Instituição responsável pela empresa
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIRP | Integer |  | Código Interno |  |
| CODENTREF | String |  | Cód.Instituição |  |
| NOMEENTREF | String |  | Nome Instituição |  |
| CODINSCR | String |  | Código Cadastral |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODEMP | Integer |  | CODEMP |  |

## TCBIRPJ — Cálculo IRPJ - Lucro Real
Campos: 42

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CONSCRESPECPARTEA | String |  | Considerar CR’s específicos para Apuração | `S`=Sim `N`=Não |
| LUCROANTESIR | Float |  | Lucro Antes IRPJ |  |
| FORMAAPUR | String |  | Forma de Apuração | `M`=Mensal/Anual `T`=Trimestral |
| TOTALADICOES | Float |  | Total das Adições |  |
| TOTALEXCLUSOES | Float |  | Total das Exclusões |  |
| COMPPREJUFIS | Float |  | Compensação de Prejuízos Fiscais |  |
| RESLIQAJUS | Float |  | Resultado Líquido Ajustado |  |
| BASEAJUSTADA | Float |  | Base de Cálculo |  |
| IRPJ15 | Float |  | IRPJ 15% |  |
| IRPJ10 | Float |  | Adicional IRPJ 10% |  |
| IMPOSTODEVIDO | Float |  | Imposto Devido |  |
| VALORPAT | Float |  | Valor PAT |  |
| DEDUCAOPAT | Float |  | Dedução PAT |  |
| DEDUOUTINC | Float |  | Dedução Outros Incentivos |  |
| IMPOSTODEVIDOLIQ | Float |  | Imposto Devido Líquido |  |
| TOTALRECOLHIDO | Float |  | Total Recolhido Meses Ant. |  |
| SALDOARECOLHER | Float |  | Saldo do Imposto a Recolher |  |
| COMPENSACOES | Float |  | ( - ) Compensações |  |
| IRPJRETIDO | Float |  | Outras Compensações |  |
| VLRIRPJRETCOMP | Float |  | Valores IRPJ retido a compensar |  |
| IMPOSTOARECOLHERFINAL | Float |  | Imposto a Recolher |  |
| RECOLHIMENTOAVULSO | Float |  | Recolhimento Avulso |  |
| LUCROANTESIR_CSLL | Float |  | Lucro Antes CSLL |  |
| TOTALADICOES_CSLL | Float |  | Total das Adições |  |
| TOTALEXCLUSOES_CSLL | Float |  | Total das Exclusões |  |
| RESLIQAJUS_CSLL | Float |  | Resultado Líquido Ajustado |  |
| COMPBCNEG_CSLL | Float |  | Compensação BC Negativa da CSLL |  |
| BASEAJUSTADA_CSLL | Float |  | Base de Cálculo |  |
| ALIQCSLL | Float |  | Alíquota CSLL |  |
| CSLL9 | Float |  | CSLL |  |
| TOTALRECOLHIDO_CSLL | Float |  | Total Recolhido Meses Ant. |  |
| SALDOARECOLHER_CSLL | Float |  | Saldo do Imposto a Recolher |  |
| COMPENSACOES_CSLL | Float |  | ( - ) Compensações |  |
| CSLLRETIDO | Float |  | Outras Compensações |  |
| VLRCSLLRETCOMP | Float |  | Valores CSLL retido a compensar |  |
| IMPOSTOARECOLHERFINAL_CSLL | Float |  | Imposto a Recolher |  |
| DEDUZPAT10 | String |  | Deduzir PAT sobre o Adicional IRPJ 10% | `N`=Não `S`=Sim |
| RECOLHIMENTOAVULSO_CSLL | Float |  | Recolhimento Avulso |  |
| VLRIRPJCOMPPREJ | Float |  | ( - ) Compensação de Prejuizos |  |
| VLRIRPJCOMPPREJ_CSLL | Float |  | ( - ) Compensação de Prejuizos |  |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJAD — Adições
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODCTACTB | Integer |  | Conta Contábil |  |
| TIPOIMPOSTO | String |  | Tipo do Imposto | `C`=CSLL `I`=IRPJ |
| VLRLANC | Float |  | Valor Lançamento |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |
| CTACTB | String |  | Conta Contábil |  |

## TCBIRPJDARF — Darf's Recolhidos
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODREC | Integer |  | Cód. Receita |  |
| DTAPURACAO | Date |  | Data Apuração |  |
| DTVENCIMENTO | Date |  | Data Vencimento |  |
| DTRECOLHIMENTO | Date |  | Data Recolhimento |  |
| VLRPRINCIPAL | Float |  | Vlr. Principal |  |
| VLRMULTA | Float |  | Vlr. Multa |  |
| VLRJUROS | Float |  | Vlr. Juros |  |
| VLRTOT | Float |  | Vlr Total |  |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJEX — ( - )Exclusões
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODCTACTB | Integer |  | Conta Contábil |  |
| TIPOIMPOSTO | String |  | Tipo do Imposto | `I`=IRPJ `C`=CSLL |
| VLRLANC | Float |  | Valor Lançamento |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |
| CTACTB | String |  | Conta Contábil |  |

## TCBIRPJIF — Incentivos Fiscais
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODIGO | Integer |  | Código |  |
| DESCRICAO | String |  | Descrição |  |
| VLRCALC | Float |  | Valor Calculado no Período |  |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJNFRET — Notas Fiscais com Retenções
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| NUNOTA | Integer |  | Nro. Único |  |
| NUMNOTA | Integer |  | N. Nota |  |
| SERIENOTA | String |  | Série Nota |  |
| CODPARC | Integer |  | Parceiro |  |
| DTNEG | Date |  | Dt. Emissão |  |
| DTENTSAI | Date |  | Dt. Ent/Saída |  |
| VLRNOTA | Float |  | Vlr. Total NF |  |
| VLRIRPJ | Float |  | Vlr. IRPJ |  |
| VLRCSLL | Float |  | Vlr. CSLL |  |
| RETEMIRPJCSLL | String |  | Compensar retenção no IRPJ e CSLL? | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJPCOMP — PER/DCOMP
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| NUMPERD | String |  | N. PER/DCOMP |  |
| VLRPERDCOMP | Float |  | Vlr. PER/DCOMP |  |
| TIPPERDCOMP | String |  | Tipo | `null`=Pagamento Indevido ou À Maior `3`=Outros `2`=Saldo Negativo CSLL `1`=Saldo Negativo IRPJ |
| REFORIGEM | Date |  | Referência de Origem |  |
| CODDARF | Integer |  | Cód. Darf |  |
| TIPOIMPOSTO | String |  | Tipo Imposto | `I`=IRPJ `null`=CSLL |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJPTB — Cálculo IRPJ - Lucro Real - Parte B
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODCTACTB | Integer |  | Conta reduzida |  |
| CODCONTA | Integer |  | Código da Conta |  |
| DESCRCONTA | String |  | Descrição |  |
| CODCONTAPTB | String |  | Código Padrão da Parte B |  |
| DESCRCONTAPTB | String |  | Descrição |  |
| NATCONTA | String |  | Natureza da Conta | `D`=Devedora `C`=Credora |
| TIPOSALDOINICIALCSLL | String |  | Tipo de Saldo | `D`=D `C`=C |
| TIPOSALDOINICIALIRPJ | String |  | Tipo de Saldo | `D`=D `C`=C |
| DTCRIACAO | Date |  | Data de Criação |  |
| HISTORICO | String |  | Histórico |  |
| DTLIMITE | Date |  | Data limite p/ uso do saldo |  |
| SALDOINICIAL | Float |  | Saldo Inicial |  |
| ADICOES | Float |  | Adições |  |
| EXCLUSOES | Float |  | Exclusões |  |
| SALDOFINAL | Float |  | Saldo Final |  |
| CODCONTA_CSLL | Integer |  | Código da Conta |  |
| DESCRCONTA_CSLL | String |  | Descrição |  |
| CODCONTAPTB_CSLL | String |  | Código Padrão da Parte B |  |
| DESCRCONTAPTB_CSLL | String |  | Descrição |  |
| NATCONTA_CSLL | String |  | Natureza da Conta | `C`=Credora `D`=Devedora |
| TIPOSALDOFINALCSLL | String |  | Tipo de Saldo | `D`=D `C`=C |
| TIPOSALDOFINALIRPJ | String |  | Tipo de Saldo | `C`=C `D`=D |
| DTCRIACAO_CSLL | Date |  | Data de Criação |  |
| HISTORICO_CSLL | String |  | Histórico |  |
| DTLIMITE_CSLL | Date |  | Data limite p/ uso do saldo |  |
| SALDOINICIAL_CSLL | Float |  | Saldo Inicial |  |
| ADICOES_CSLL | Float |  | Adições |  |
| EXCLUSOES_CSLL | Float |  | Exclusões |  |
| SALDOFINAL_CSLL | Float |  | Saldo Final |  |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJPTBAD — Incentivos Fiscais
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODCTACTB | Integer |  | Conta reduzida |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODCONTA | Integer |  | Código da Conta |  |
| DESCRCONTA | String |  | Descrição |  |
| CODPADRAOPTB | String |  | Código padrão Parte B e-Lalur |  |
| INDTRIBPTB | String |  | Indicador tributo Parte B e-Lalur | `I`=I - Imposto de Renda Pessoa Jurídica `C`=C - Contribuição Social sobre o Lucro Líquido `A`=A - Ambos (IRPJ e CSLL) |
| VLRLANC | Float |  | Valor Lançamento |  |
| TABELA | String |  | Tabela |  |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJPTBCP — Compensações
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODCTACTB | Integer |  | Conta reduzida |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODCONTA | Integer |  | Código da Conta |  |
| DESCRCONTA | String |  | Descrição |  |
| CODPADRAOPTB | String |  | Código padrão Parte B e-Lalur |  |
| INDLANC | String |  | Indicador de Lançamento | `BC`=BC - Base de Cálculo Negativa para CSLL `CR`=CR - Crédito `PF`=PF - Prejuízo do Exercício `DB`=DB - Débito |
| CODTRIB | String |  | Código do Tributo | `C`=C - Contribuição Social sobre o Lucro Liquido `I`=I - Imposto de Renda |
| VLRLANC | Float |  | Valor Lançamento |  |
| REVATRIBDIF | String |  | Realiza Valores com Tributação Diferida | `1`=Sim `2`=Não |
| TABELA | String |  | Tabela |  |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJPTBEX — Incentivos Fiscais
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODCTACTB | Integer |  | Conta reduzida |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODCONTA | Integer |  | Código da Conta |  |
| DESCRCONTA | String |  | Descrição |  |
| CODPADRAOPTB | String |  | Código padrão Parte B e-Lalur |  |
| INDTRIBPTB | String |  | Indicador tributo Parte B e-Lalur | `I`=I - Imposto de Renda Pessoa Jurídica `A`=A - Ambos (IRPJ e CSLL) `C`=C - Contribuição Social sobre o Lucro Líquido |
| VLRLANC | Float |  | Valor Lançamento |  |
| TABELA | String |  | Tabela |  |
| CODEMP | Integer |  | Empresa |  |

## TCBIRPJREC — Recolhimentos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| MESPAGAMENTO | Date |  | Mês Recolhimento |  |
| VLRIMPOSTO | Float |  | Valor Recolhimento IRPJ |  |
| VLRIMPOSTO_CSLL | Float |  | Valor Recolhimento CSLL |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TCBISE — Indicador de Situação Especial para geração do ECD
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODISE | String |  | Situação Especial | `0`=Transferência de Sede `4`=Incorporação\Incorporadora `3`=Incorporação\Incorporada `2`=Fusão `1`=Extinção_(+5)_ |
| DTMOV | Date |  | Data |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODEMP | Integer |  | Cód. Emp |  |

## TCBITELP — Itens para Apuração do LP
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODIGO | String |  | Código |  |
| TABELA | String |  | Tabela |  |
| ALIQUOTA | Float |  | Alíquota |  |
| TIPIMP | String |  | Tipo Imposto | `C`=CSLL `I`=IRPJ |
| DTINI | Date |  | Data Início |  |
| DTFIM | Date |  | Data Fim |  |
| GRUPO | String |  | Grupo | `1`=Discriminação da Receita Bruta `2`=Receitas com Tributação Integral `3`=Cálculo para IRPJ/CSLL `4`=Deduções |
| DTALTER | Date |  | Data de alteração |  |
| DTATT | Date |  | Data da Atualização da Tabela |  |
| ITEMDESC | String |  | Descrição |  |
| CODNATLP | Integer |  | Código Natureza |  |

## TCBLAN — Lançamentos
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMDOC | Integer |  | Núm. Documento |  |
| VENCIMENTO | Date |  | Vencimento |  |
| VLRLANC | Float |  | Valor Lançamento |  |
| TIPLANC | String |  | Tip. Lançamento | `R`=Crédito `D`=Débito |
| LIBERADO | String |  | Liberado | `N`=Não `S`=Sim |
| CODHISTCTB | Integer |  | Histórico |  |
| REFERENCIA | Date |  | Referência |  |
| CODEMP | Integer |  | Empresa |  |
| CODUSU | Integer |  | Usuário |  |
| DTMOV | Date |  | Data Movimento |  |
| NUMLOTE | Integer |  | Núm. Lote |  |
| NUMLANC | Integer |  | Núm. Lançamento |  |
| CODCONPAR | Integer |  | Conta Contrapartida |  |
| COMPLHIST | String |  | Complemento |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROJ | Integer |  | Projeto |  |
| PARTLALUR_A | String |  | Parte A do e-LALUR | `S`=Sim `N`=Não |
| VLRCRED | Float |  | Valor Crédito |  |
| VLRDEB | Float |  | Valor Débito |  |
| EXTEMPORANEO | String |  | Extemporâneo? | `S`=Sim `N`=Não |
| DTEXTEMPORANEO | Date |  | Dt. Ocorrência Extem. |  |
| CODEMPORIG | Integer |  | Empresa de Origem |  |
| CHAVE | String |  | Chave |  |
| AD_CODPARC | Integer |  | Código Parceiro |  |
| CONCILIADO | String |  | Conciliado | `N`=Não `S`=Sim |
| AD_DHALTER | DateTime |  | Dh Alteração |  |
| INDESTORNADO | String |  | Estorno | `A`=Estorno e foi estornado `F`=Foi estornado `N`=Não é um estorno `S`=É um estorno |
| AD_CONCILIADO | String |  | Conciliado | `N`=Não `S`=Sim |
| CODRASTROESTORNO | Integer |  | Cód. Rastreamento Estorno |  |
| CHAVRATROESTORNO | String |  | Chave de Rastreamento do Estorno |  |
| CODCTACTB | Integer |  | Conta Contábil (Red.) |  |

## TCBLAN_CONF — Lançamentos
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMDOC | Integer |  | Núm. Documento |  |
| VENCIMENTO | Date |  | Vencimento |  |
| VLRLANC | Float |  | Valor Lançamento |  |
| TIPLANC | String |  | Tip. Lançamento | `R`=Crédito `D`=Débito |
| LIBERADO | String |  | Liberado | `S`=Sim `N`=Não |
| CODHISTCTB | Integer |  | Histórico |  |
| REFERENCIA | Date |  | Referência |  |
| CODEMP | Integer |  | Empresa |  |
| CODUSU | Integer |  | Usuário |  |
| DTMOV | Date |  | Data Movimento |  |
| NUMLOTE | Integer |  | Núm. Lote |  |
| NUMLANC | Integer |  | Núm. Lançamento |  |
| CODCONPAR | Integer |  | Conta Contrapartida |  |
| COMPLHIST | String |  | Complemento |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| NUAGENDAMENTO | String |  | Nro. Agendamento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROJ | Integer |  | Projeto |  |
| PARTLALUR_A | String |  | Parte A do e-LALUR | `S`=Sim `N`=Não |
| VLRCRED | Float |  | Valor Crédito |  |
| EXTEMPORANEO | String |  | Extemporâneo? | `S`=Sim `N`=Não |
| VLRDEB | Float |  | Valor Débito |  |
| DTEXTEMPORANEO | Date |  | Dt. Ocorrência Extem. |  |
| CODEMPORIG | Integer |  | Empresa de Origem |  |
| CODCTACTB | Integer |  | Conta Contábil (Red.) |  |

## TCBLAN_EXC — Lançamentos Excluídos
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMDOC | Integer |  | Núm. Documento |  |
| VENCIMENTO | Date |  | Vencimento |  |
| VLRLANC | Float |  | Valor Lançamento |  |
| TIPLANC | String |  | Tip. Lançamento | `D`=Débito `R`=Crédito |
| LIBERADO | String |  | Liberado | `N`=Não `S`=Sim |
| CODHISTCTB | Integer |  | Histórico |  |
| REFERENCIA | Date |  | Referência |  |
| CODEMP | Integer |  | Empresa |  |
| CODUSU | Integer |  | Usuário |  |
| DTMOV | Date |  | Data Movimento |  |
| NUMLOTE | Integer |  | Núm. Lote |  |
| NUMLANC | Integer |  | Núm. Lançamento |  |
| CODCONPAR | Integer |  | Conta Contrapartida |  |
| COMPLHIST | String |  | Complemento |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROJ | Integer |  | Projeto |  |
| PARTLALUR_A | String |  | Parte A do e-LALUR | `N`=Não `S`=Sim |
| VLRCRED | Float |  | Valor Crédito |  |
| EXTEMPORANEO | String |  | Extemporâneo? | `N`=Não `S`=Sim |
| VLRDEB | Float |  | Valor Débito |  |
| DTEXTEMPORANEO | Date |  | Dt. Ocorrência Extem. |  |
| CODEMPORIG | Integer |  | Empresa de Origem |  |
| CHAVE | String |  | Chave |  |
| CONCILIADO | String |  | Conciliado | `N`=Não `S`=Sim |
| INDESTORNADO | String |  | Estorno | `A`=Estorno e foi estornado `F`=Foi estornado `N`=Não é um estorno `S`=É um estorno |
| CODRASTROESTORNO | Integer |  | Cód. Rastreamento Estorno |  |
| CODUSUEXC | Integer |  | Cód. Usuário Exclusão |  |
| DHEXC | Date |  | Data Exclusão |  |
| DHALT | Date |  | Data Alteração |  |
| CODCTACTB | Integer |  | Conta Contábil (Red.) |  |

## TCBLAN_VCBLAN_EXC — Histórico de Lançamentos Contábeis
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODCTACTB | Integer |  | Conta Contábil (Red.) |  |
| NUMDOC | Integer |  | Núm. Documento |  |
| VENCIMENTO | Date |  | Vencimento |  |
| VLRLANC | Float |  | Valor Lançamento |  |
| TIPLANC | String |  | Tip. Lançamento | `D`=Débito `R`=Crédito |
| LIBERADO | String |  | Liberado | `N`=Não `S`=Sim |
| CODHISTCTB | Integer |  | Histórico |  |
| REFERENCIA | Date |  | Referência |  |
| CODEMP | Integer |  | Empresa |  |
| CODUSU | Integer |  | Usuário |  |
| DTMOV | Date |  | Data Movimento |  |
| NUMLOTE | Integer |  | Núm. Lote |  |
| NUMLANC | Integer |  | Núm. Lançamento |  |
| CODCONPAR | Integer |  | Conta Contrapartida |  |
| COMPLHIST | String |  | Complemento |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| CODPROJ | Integer |  | Projeto |  |
| PARTLALUR_A | String |  | Parte A do e-LALUR | `N`=Não `S`=Sim |
| VLRCRED | Float |  | Valor Crédito |  |
| VLRDEB | Float |  | Valor Débito |  |
| EXTEMPORANEO | String |  | Extemporâneo? | `N`=Não `S`=Sim |
| DTEXTEMPORANEO | Date |  | Dt. Ocorrência Extem. |  |
| CODEMPORIG | Integer |  | Empresa de Origem |  |
| CHAVE | String |  | Chave |  |
| CONCILIADO | String |  | Conciliado | `N`=Não `S`=Sim |
| INDESTORNADO | String |  | Estorno | `A`=Estorno e foi estornado `F`=Foi estornado `N`=Não é um estorno `S`=É um estorno |
| CHAVRATROESTORNO | String |  | Chave de Rastreamento do Estorno |  |
| CODRASTROESTORNO | Integer |  | Cód. Rastreamento Estorno |  |
| CODUSUEXC | Integer |  | Cód. Usuário Exclusão |  |
| DHEXC | Date |  | Data Exclusão |  |
| DHALT | Date |  | Data Alteração |  |
| STATUSATUALI | String |  | Status Atualização | `A`=Alterado `E`=Excluído `T`=Ativo |

## TCBLBC — Liberação Bloqueio Contábil
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQBLOQUEIO | Integer |  | Seq. Bloqueio |  |
| NULIBERACAO | Integer |  | Nro. Liberação |  |
| STATUSLIB | String |  | Status Liberação | `R`=Reprovada `P`=Pendente `A`=Aprovada |
| TIPOMOV | String |  | Tipo de movimento | `04`=Movimentações Financeiras `03`=Movimentações Calculo de Custo - Produto `02`=Movimentações Calculo de Custo - Nota `01`=Movimentações Estoque `10`=Movimentações Calculo de Custo - Serviço_(+5)_ |
| TIPOACAO | String |  | Tipo de ação | `R`=Rotina de geração `I`=Inclusão `D`=Deleção `A`=Alteração |
| CODUSULIB | Integer |  | Cod. Usuário Liberador |  |
| ROTINACTB | String |  | Rotina de geração | `7`=Geração ICMS/IPI `6`=Contabilização de créditos de PIS/COFINS do ativo imobilizado `5`=Importação de lotes com base no ECD `4`=Importação de lotes `3`=Recuperação de devedores duvidosos_(+4)_ |
| DTINILIB | DateTime |  | Dh. Inicio Liberação |  |
| DTFINLIB | DateTime |  | Dh. Fim Liberação |  |
| CODUSUSOLICIT | Integer |  | Cod. Usuário Solicitante |  |
| DHSOLICIT | DateTime |  | Dh. Solicitação |  |
| NUBLOQUEIO | Integer |  | Nro. Bloqueio |  |

## TCBLOT — Mestres de Lotes
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| NUMLOTE | Integer |  | Nro. Lote |  |
| REFERENCIA | Date |  | Referência |  |
| DTMOV | Date |  | Dt. Movimento |  |
| TOTLOTE | Float |  | Total do lote |  |
| SITUACAO | String |  | Situação | `F`=Fechado `A`=Aberto |
| ULTLANC | Integer |  | Últ. Lançamento |  |
| VLRDEBITO | Float |  | Débito |  |
| VLRCREDITO | Float |  | Crédito |  |
| VLRDIFERENCA | Float |  | Diferença |  |
| QTDLANC | Integer |  | Qtd. Lançamentos |  |
| CODEMPCONSOLID | Integer |  | Empresa Origem (Consolidação)] |  |
| COMENTARIOS | String |  | Observação |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCBLOT_EXC — Lotes Excluídos
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUMLOTE | Integer |  | Nro. Lote |  |
| REFERENCIA | Date |  | Referência |  |
| DTMOV | Date |  | Dt. Movimento |  |
| TOTLOTE | Float |  | Total do lote |  |
| SITUACAO | String |  | Situação | `A`=Aberto `F`=Fechado |
| ULTLANC | Integer |  | Últ. Lançamento |  |
| VLRDEBITO | Float |  | Débito |  |
| VLRCREDITO | Float |  | Crédito |  |
| VLRDIFERENCA | Float |  | Diferença |  |
| QTDLANC | Integer |  | Qtd. Lançamentos |  |
| CODEMPCONSOLID | Integer |  | Empresa Origem (Consolidação)] |  |
| COMENTARIOS | String |  | Observação |  |
| CODUSUEXC | Integer |  | Cód. Usuário Exclusão |  |
| DHEXC | Date |  | Data Exclusão |  |
| DHALT | Date |  | Data Alteração |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TCBLUCPRES — Apuração do Regime Normal - Lucro Presumido
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Integer |  | Referência |  |
| TRIMESTRE | String |  | Trimestre | `1`=1º Trimestre `2`=2º Trimestre `3`=3º Trimestre `4`=4º Trimestre |
| DTINI | Date |  | Data Início |  |
| TIPDATA | String |  | Tipo de Data | `M`=Data de Movimento `N`=Data de Negociação `null`=Data Entrada e Saída |
| DTFIM | Date |  | Data Fim |  |
| STATUSAPUR | String |  | Status Apuração | `F`=Fechado `P`=Processado `null`=Aberto |
| JSONCSLL | C |  | JsonCsll |  |
| JSONIRPJ | C |  | JsonIrpj |  |
| CODEMP | Integer |  | Empresa |  |

## TCBLUCPRESAJ — Ajustes Manuais
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Integer |  | Referência |  |
| CODNATLP | Integer |  | Item da Apuração |  |
| DTLANC | Date |  | Data de Lançamento |  |
| TRIMESTRE | String |  | Trimestre |  |
| HISTORICO | String |  | Histórico |  |
| VLRLANC | Float |  | Valor do Lançamento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Empresa |  |

## TCBLUCPRESRT — Apuração do Regime Normal - Retenções
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EMPRESAMOVIMENTO | Integer |  | Empresa |  |
| DTREF | Integer |  | Referência |  |
| TRIMESTRE | String |  | Trimestre | `1`=1º Trimestre `2`=2º Trimestre `3`=3º Trimestre `4`=4º Trimestre |
| NUDOC | Integer |  | Número Único |  |
| NUMDOC | Integer |  | Nro. Docto |  |
| DTNEG | Date |  | Data de Negociação |  |
| CODTIPOPER | Integer |  | TOP |  |
| DHTIPOPER | Date |  | Data da Operação |  |
| CODPARC | Integer |  | Parceiro |  |
| NOMEPARC | String |  | Nome do Parceiro |  |
| DTMOV | Date |  | Data de Movimento |  |
| DTENTSAI | Date |  | Data de Ent/Saida |  |
| VLRNOTA | Float |  | Vlr. Total Doc |  |
| VLRIR | Float |  | Vlr. IR Retido |  |
| VLRCSLL | Float |  | Vlr. CSLL Retido |  |
| CODNATLPIR | Integer |  | Código da Natureza do IR |  |
| DESCIRPJ | String |  | Item de Apuração IRPJ |  |
| CODNATLPCSLL | Integer |  | Código da Natureza do CSLL |  |
| DESCCSLL | String |  | Item de Apuração CSLL |  |
| CONSAPUR | String |  | Considerado na apuração? | `N`=Não `S`=Sim |
| TPMOV | String |  | Tipo de Movimento | `E`=Notas `F`=Financeiro |
| CODEMP | Integer |  | Empresa |  |

## TCBMET — Meta Contábil
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODCTACTB | Integer |  | Conta Contábil |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUS | Integer |  | Centro de Custo |  |
| NUPERIODOCTB | Integer |  | Período Contábil |  |
| DTREF | Date |  | Referência |  |
| PREVISTO | Float |  | Previsto |  |
| REALIZADO | Float |  | Realizado |  |
| DHALTER | Date |  | Referência |  |
| RECDESP | String |  | Tipo Meta |  |
| CODCCO | Integer |  | Código |  |

## TCBMOV — Movimentação da provisão para contingências
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Movimentação |  |
| ADICOES | Float |  | Adições (Baixas) |  |
| ATUMONJ | Float |  | Atualização monetária e juros |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBPCT — Período Contábil
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Código Empresa |  |
| INICIOPERIODO | Date |  | Inicio período contábil |  |
| FIMPERIODO | Date |  | Fim período contábil |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| CODUSU | Integer |  | Codigo Usuário |  |
| DESCRICAO | String |  | Descrição |  |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBPLA — Plano de contas
Campos: 52

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCTA | String |  | Descrição |  |
| CODLALURB | String |  | Código Parte B do e-LALUR |  |
| CTACTB | String |  | Conta contábil |  |
| PODELANCTOMANUAL | String |  | Aceita lançamento manual | `N`=Não `S`=Sim |
| CODCONTA | Integer |  | Código da Conta |  |
| ANALITICA | String |  | Analítica | `N`=Não `S`=Sim |
| TABELALALURB | String |  | Tabela lalurb |  |
| DESCRCONTA | String |  | Descrição |  |
| PROJOBRIG | String |  | Projeto obrigatório | `S`=Sim `N`=Não |
| CENCUSOBRIG | String |  | Centro de Resultado obrigatório | `N`=Não `S`=Sim |
| BEMORIGINAL | String |  | Bem Original | `N`=Não `S`=Sim |
| BEMRESREAV | String |  | Reserva de Reavaliação | `S`=Sim `N`=Não |
| BEMOUTROS | String |  | Outros acréscimos | `S`=Sim `N`=Não |
| ATIVA | String |  | Ativa | `S`=Sim `N`=Não |
| CODGRUPOCTA | String |  | Grupo de Conta | `04`=04 - Contas de resultado `03`=03 - Patrimônio líquido `02`=02 - Contas de passivo `01`=01 - Contas de ativo `09`=09 - Outras_(+1)_ |
| RECDESP | String |  | Tipo | `S`=Receita `N`=Despesa |
| CODCTACTBSUBST | Integer |  | Conta Substituta |  |
| DTINCLUSAO | DateTime |  | Referência de ativação |  |
| DTINATIV | DateTime |  | Referência de inativação |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Usuário |  |
| CODEMP | Integer |  | Código da empresa |  |
| GRAU | Integer |  | Grau |  |
| OBSERVACOES | String |  | Observação |  |
| PROCESSO | Integer |  | Processo |  |
| PRODUTO | Integer |  | Produto |  |
| PLANTA | Integer |  | Planta |  |
| CODCTACTBPAI | Integer |  | Cód. conta reduzida pai |  |
| CONVSALDOMOEDA | String |  | Conversão do saldo para moeda |  |
| DTBASECONVMOEDA | String |  | Data base conversão de moedas |  |
| LALUR_A | String |  | Parte A do e-LALUR |  |
| LALUR_A_CRED | String |  | Part A of e-LALUR (Saldo Credor) |  |
| TIPSALALUR | Integer |  | Tipo de Saldo e-LALUR | `1`=1 - Saldo Total `0`=0 - Buscar Lançamentos (Parcial) |
| INDTRIBLALURB | String |  | Indicador Tributos Parte B do e-LALUR | `null`=I - Imposto de Renda Pessoa Jurídica `C`=C - Contribuição Social sobre o Lucro Líquido `A`=A - Ambos (IRPJ e CSLL) |
| CODRAZAUX | Integer |  | Cód. Razão Auxiliar |  |
| TABELA | String |  | Tabela |  |
| TABELACRED | String |  | Tabela |  |
| NATUREZAEFD | Integer |  | Natureza para EFD | `9`=09 - Aquisições de bens para revenda, aquisições de insumos para industrialização `8`=08 - Estoques, Matéria prima e material de embalagem `7`=07 - Despesas de fretes contratados e despesas de comercialização `6`=06 - Despesas Diversas `5`=05 - Custos com transportes_(+8)_ |
| ESTORNO | String |  | Conta de estorno | `N`=Não `S`=Sim |
| CLASSIFIRPJ | String |  | Classificação IRPJ | `P`=PAT 4% `E`=( - ) Exclusões `C`=Conta de Resultado `A`=( + ) Adições `Z`=Zeramento de Contas de Resultado |
| CLASSIFCSLL | String |  | Classificação CSLL | `Z`=Zeramento de Contas de Resultado `C`=Conta de Resultado `A`=( + ) Adições `E`=( - ) Exclusões |
| ADICOESIRPJ | String |  | ( + ) Adições | `S`=Sim `N`=Não |
| EXCLUSOESIRPJ | String |  | ( - ) Exclusões | `S`=Sim `N`=Não |
| PAT4IRPJ | String |  | PAT 4% | `S`=Sim `N`=Não |
| CONRESULTIRPJ | String |  | Conta de Resultado | `S`=Sim `N`=Não |
| ZERACRIRPJ | String |  | Zeramento de Contas de Resultado | `S`=Sim `N`=Não |
| ADICOESCSLL | String |  | ( + ) Adições | `S`=Sim `N`=Não |
| EXCLUSOESCSLL | String |  | ( - ) Exclusões | `S`=Sim `N`=Não |
| CONRESULTCSLL | String |  | Conta de Resultado | `S`=Sim `N`=Não |
| ZERACRCSLL | String |  | Zeramento de Contas de Resultado | `S`=Sim `N`=Não |
| AD_FORNCLIE | Integer |  | Cliente/Fornecedor |  |
| CODCTACTB | Integer |  | Conta reduzida |  |

## TCBPLA_IMP — Plano de Contas com base na ECD
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CTACTB | String |  | Cód. da Conta Contábil Externa |  |
| CODCTACTBPAI | String |  | Cód. da Conta Pai Externa |  |
| GRAU | Integer |  | Grau da Conta |  |
| DESCRCTA | String |  | Descrição |  |
| ANALITICA | String |  | Analítica | `N`=Não `S`=Sim |
| CODGRUPOCTA | String |  | Grupo de Conta | `09`=09 - Outras `05`=05 - Contas de compensação `04`=04 - Contas de resultado `03`=03 - Patrimônio líquido `02`=02 - Contas de passivo_(+1)_ |
| DTINCLUSAO | DateTime |  | Dt. Inclusão |  |
| CODUSU | Integer |  | Usuário |  |
| DTPRIMIMP | DateTime |  | Data e hora primeira importação |  |
| DTALTER | DateTime |  | Data e hora alteração |  |
| CODCTACTBINTPAI | Integer |  | Cód. conta reduzida pai |  |
| CODEMP | Integer |  | Cód. da Empresa |  |
| CODCTACTB | Integer |  | Conta reduzida |  |

## TCBPLR — Plano de Contas Referencial
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTAREF | String |  | Cód. Conta Ref. |  |
| DESCRCTAREF | String |  | Descrição |  |
| GRAU | Integer |  | Grau |  |
| ANALITICA | String |  | Analítica | `N`=Não `S`=Sim |
| NATUREZA | String |  | Natureza |  |
| CTCCTBPAI | String |  | Cód. Conta Pai |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TABELA | String |  | Tabela |  |
| TIPO | Integer |  | Tipo | `10`=10 - Financeiras - Lucro Presumido ( P100B + P150B ) `4`=4 - Seguradoras ou Entidades Abertas de Previdência Complementar ( L100_C + L300_C ) `9`=9 - Partidos Políticos ( U100_E + U150_E ) `3`=3 - Financeiras ( L100_B + L300_B ) `2`=2 - PJ em Geral - Lucro Presumido ( P100 + P150 )_(+5)_ |

## TCBRAS — Rastreamento Conta Contábil Estorno
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPORIGEM | Integer |  | Cód. Empresa Origem |  |
| REFORIGEM | Date |  | Ref. Origem |  |
| TIPLANCORIGEM | String |  | Tipo Lançamento Origem |  |
| NUMLOTEORIGEM | Integer |  | Núm. Lote Origem |  |
| NUMLANCORIGEM | Integer |  | Núm. Lançamento Origem |  |
| SEQORIGEM | Integer |  | Seq. Origem |  |
| CODEMPDEST | Integer |  | Cód. Empresa Destino |  |
| REFDEST | Date |  | Ref. Destino |  |
| TIPLANCDEST | String |  | Tipo Lançamento Destino |  |
| NUMLOTEDEST | Integer |  | Núm. Lote Destino |  |
| NUMLANCDEST | Integer |  | Núm. Lançamento Destino |  |
| SEQDEST | Integer |  | Seq. Destino |  |
| INDRASTRO | String |  | Ind. Rastreamento |  |
| SEQRASTRO | Integer |  | Seq. Rastreamento |  |

## TCBRDF — Receitas e Despesas Financeiras
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| TIPO | Integer |  | Tipo Passivo | `1`=Receita `-1`=Despesa |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBRECOP — Outras receitas (despesas) operacionais
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBREL — Tabela de Relacionamento com Participantes
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód. Parceiro |  |
| DTINIREL | Date |  | Data Início |  |
| DTFIMREL | Date |  | Data Final |  |
| CODREL | Integer |  | Cód. Relacionamento | `6`=Subsidiária Integral `7`=Controlada em conjunto `3`=Coligada, inclusive equiparada `2`=Filial, inclusive agência ou dependência no exterior `1`=Matriz no exterior_(+6)_ |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODEMP | Integer |  | CODEMP |  |

## TCBRLI — Receita Líquida
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição da Conta |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBSAL — Saldo
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | Referência |  |
| CODEMP | Integer |  | Código Empresa |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODPROJ | Integer |  | Projeto |  |
| SALDOINICMES | Float |  | Saldo no início do mês |  |
| DEBMES | Float |  | Débito no mês |  |
| CREDMES | Float |  | Crédito no mês |  |
| CODCTACTB | Integer |  | Cód.Conta |  |

## TCBSALEMP — Saldo Por Empresa
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTACTB | Integer |  | Cód. Conta |  |
| CODCENCUS | Integer |  | Cód. Centro Resultado |  |
| CODPROJ | Integer |  | Projeto |  |
| CREDMES | Float |  | Crédito no mês |  |
| DEBMES | Float |  | Débito no mês |  |
| REFERENCIA | DateTime |  | Referência |  |
| SALDOINICMES | Float |  | Saldo no início do mês |  |
| CODEMP | Integer |  | Código Empresa |  |
| CODEMPDEST | Integer |  | Código Empresa Destino |  |

## TCBSAL_IMP — Saldo com base na ECD
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CTACTB | String |  | Cód. da Conta Contábil |  |
| REFERENCIA | DateTime |  | Referência |  |
| CODCENCUS | String |  | Cód. Centro Resultado |  |
| SALDOINICMES | Float |  | Saldo Inicial |  |
| INDSTINI | String |  | Ind. da Situação do Saldo Inicial | `C`=Credor `D`=Devedor |
| DEBMES | Float |  | Débito |  |
| CREDMES | Float |  | Crédito |  |
| SALDOFINMES | Float |  | Saldo Final |  |
| INDSTFIN | String |  | Ind. da Situação do Saldo Final | `C`=Credor `D`=Devedor |
| CODEMP | Integer |  | Cód. da Empresa |  |

## TCBSIG — Tabela de Signatários
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSIG | Integer |  | Cód. Signatário |  |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Final |  |
| NOMESIG | String |  | Nome |  |
| CPF | String |  | CPF/CNPJ |  |
| CRC | String |  | CRC |  |
| QUALIFICACAO | String |  | Qualificação |  |
| CODQUALIFICACAO | String |  | Cód. DNRC |  |
| GERARECD | String |  | Gerar ECD | `N`=Não `S`=Sim |
| TELEFONE | String |  | Telefone |  |
| EMAIL | String |  | E-Mail |  |
| NUMSEQCRC | String |  | Núm./Seq./CRC |  |
| DTVALCRC | Date |  | Data Validade CRC |  |
| UFCRC | String |  | UF CRC |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| RESPLEGALRF | String |  | Responsável Legal da empresa junto a RFB | `N`=Não `S`=Sim |
| GERARELATCONTABIL | String |  | Gerar nos Relatórios Contábeis? | `S`=Sim `N`=Não |
| CODEMP | Integer |  | CODEMP |  |

## TCBSPC — Sociedade em Cota de Participação
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJ | String |  | CNPJ da SCP |  |
| NOME | String |  | Nome da SCP |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TCBSPE — Substituto por Empresa
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| CODORIG | Integer |  | Origem |  |
| CODDEST | Integer |  | Destino |  |
| DESCRCODORIG | String |  | Descrição Origem |  |
| CODEMP | Integer |  | Empresa |  |
| DESCRCODDEST | String |  | Descrição Destino |  |

## TCBSVN — Custo de serviços vendidos por natureza
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCR | String |  | Descrição |  |
| VALORANO1 | Float |  | Valor Ano Referência |  |
| VALORANO2 | Float |  | Valor Ano Anterior |  |
| PARTTOTALIZACAO | String |  | Participa na Totalização? | `S`=Sim `N`=Não |
| NUPERIODOCTB | Integer |  | Nro período contábil |  |

## TCBTDM — Tipo de Demonstrativo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| SIGLA | String |  | Sigla |  |
| CODTDM | Integer |  | Cód. Tipo Demonstrativo |  |

## TCBVCA — Vinculação de Contas Contábeis Alteradas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| DESCRVINCULO | String |  | Descrição |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Empresa |  |

## TCBVCAD — Vinculação de Contas Contábeis Alteradas Detalhes
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTACTB | Integer |  | Conta reduzida |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CTACTB | String |  | Conta contábil |  |
| CODCTACTBALT | Integer |  | Conta Contábil Alterada |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODEMP | Integer |  | Empresa |  |

## TCBVCE — Vinculação de Contas Contábeis Externas
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRVINCULO | String |  | Descrição |  |
| MASCCTAEXT | String |  | Máscara da conta externa |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| GERARI157ECD | String |  | Gerar no I157 da ECD | `S`=Sim `N`=Não |
| DTMUDAPLANO | Date |  | Data Início da Mudança do Plano de Contas |  |
| CODEMP | Integer |  | Cód. Empresa da Importação |  |

## TCBVCED — Vinculação de Contas Contábeis Externas Detalhes
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTACTB | Integer |  | Conta reduzida |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CRIMPORTADO | String |  | Centro Resultado |  |
| CTACTBEXT | String |  | Conta contábil externa manual |  |
| CTACTBEXTIMP | String |  | Conta contábil externa importada |  |
| CTACTB | String |  | Conta contábil |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CRVINCULADO | String |  | Centro Resultado |  |
| SALCTACTBVINC | Float |  | Saldo da conta vinculada |  |
| INDSITINI | String |  | Indicador da situação do saldo inicial | `C`=C-Credor `D`=D-Devedor |
| CODEMP | Integer |  | Cód. Empresa da Importação |  |