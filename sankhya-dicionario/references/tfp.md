# TFP — Fiscal (módulo complementar)

> Gerado do dicionário oficial TDD Sankhya. 395 tabelas.


## TFPACA — Agentes Causadores CAT
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODAGENTECAUSADOR | String |  | Código |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| NUCAT | Integer |  | NUCAT |  |

## TFPACESSOSNKPASS — Tabela de Usuários Sankhya Pass
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| USERIDSNKPASS | String |  | USERSNKPASS |  |
| CPF | String |  | CPF |  |
| EMAIL | String |  | Email |  |
| ID | Integer |  | ID |  |

## TFPACU — Acumulados do Ano
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Cód.Funcionário |  |
| CODEVENTO | Integer |  | Cód.Evento |  |
| TIPEVENTO | Integer |  | Tipo de evento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| ANO | Integer |  | Ano de Referência |  |
| DTALTER | DateTime |  | Data de alteração |  |
| VLRJANEIRO | Float |  | Janeiro |  |
| VLRFEVEREIRO | Float |  | Fevereiro |  |
| VLRMARCO | Float |  | Março |  |
| VLRABRIL | Float |  | Abril |  |
| VLRMAIO | Float |  | Maio |  |
| VLRJUNHO | Float |  | Junho |  |
| VLRJULHO | Float |  | Julho |  |
| VLRAGOSTO | Float |  | Agosto |  |
| VLRSETEMBRO | Float |  | Setembro |  |
| VLROUTUBRO | Float |  | Outubro |  |
| VLRNOVEMBRO | Float |  | Novembro |  |
| VLRDEZEMBRO | Float |  | Dezembro |  |
| INDJANEIRO | Float |  | Índice de janeiro |  |
| INDFEVEREIRO | Float |  | Índice de fevereiro |  |
| INDMARCO | Float |  | Índice de março |  |
| INDABRIL | Float |  | Índice de abril |  |
| INDMAIO | Float |  | Índice de maio |  |
| INDJUNHO | Float |  | Índice de junho |  |
| INDJULHO | Float |  | Índice de julho |  |
| INDAGOSTO | Float |  | Índice de agosto |  |
| INDSETEMBRO | Float |  | Índice de setembro |  |
| INDOUTUBRO | Float |  | Índice de outubro |  |
| INDNOVEMBRO | Float |  | Índice de novembro |  |
| INDDEZEMBRO | Float |  | Índice de dezembro |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TFPADV — Advogados e Escritórios
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Código |  |
| TIPOINSCRICAO | Integer |  | Tipo de inscrição |  |
| NROINSCRICAO | String |  | Número da inscrição |  |
| DESCRICAO | String |  | Descrição |  |

## TFPAEVE — Alteracao Eventos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEVENTO | Integer |  | Código do evento |  |
| PADRONIZAR | String |  | Padronizar |  |
| REVERTER | String |  | Reverter |  |
| CODEVENTOANT | Integer |  | Código do evento Anterior |  |
| TROCACTX | String |  | TROCACTX |  |
| CARACTERISTICA | String |  | Caracteristica |  |

## TFPAFA — Códigos de Afastamento
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRAFAST | String |  | Descrição |  |
| DIRFERMENANO | String |  | Direito a férias com menos de um ano | `N`=Não `S`=Sim |
| CODGOVERNO | String |  | Código Governamental |  |
| DIRAVISOPREVIO | String |  | Direito ao aviso prévio | `N`=Não `S`=Sim |
| TIPTAB | String |  | Tipo de tabela | `F`=FGTS `R`=Rais `C`=Causa do afastamento |
| ABATEMESMEDIA | String |  | Abate nos Meses das Médias | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Data da Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DIRDECTERC | String |  | Direito ao décimo terceiro | `N`=Não `S`=Sim |
| DIRMULTAFGTS | String |  | Direito a multa do FGTS | `N`=Não `S`=Sim |
| CODAFAHOMOLOGNET | String |  | Código HomologNet | `___`=___ Acordo Empregado Empregador `SJ2`=SJ2 Despedida sem justa causa, pelo empregador `SJ1`=SJ1 Rescisão contratual a pedido do empregado `RI2`=RI2 Rescisão Indireta `RA1`=RA1 Rescisão antecipada, pelo empregado_(+9)_ |
| CODAFAST | String |  | Cód.Afastamento |  |

## TFPAFDT — TABLE TFPAFDT
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | CODFUNC |  |
| DTMOV | DateTime |  | DTMOV |  |
| HORA | Integer |  | HORA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TIPREGISTRO | String |  | TIPREGISTRO |  |
| TIPMARCACAO | String |  | TIPMARCACAO |  |
| SEQTIPMARCACAO | Integer |  | SEQTIPMARCACAO |  |
| NURELOGIO | String |  | NURELOGIO |  |
| NUOCOR | Integer |  | NUOCOR |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| FECHADO | String |  | FECHADO |  |
| DIGITADO | String |  | DIGITADO |  |
| DTINIJORNADA | DateTime |  | DTINIJORNADA |  |
| DTFECHAMENTO | DateTime |  | DTFECHAMENTO |  |
| CRCEMP | String |  | CRCEMP |  |
| CRCFUNC | String |  | CRCFUNC |  |
| GEOLOC | String |  | GEOLOC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPAFG — Alteração Função Gratificada
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATOADMIN | String |  | Ato Administrativo |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODGRAT | Integer |  | Gratificação |  |
| DTPROM | Date |  | Data da promoção |  |
| TIPREG | String |  | Tipo de registro |  |

## TFPAGC — Agentes Causadores
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRAGENTECAUSADOR | String |  | Descrição do agente causador |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODAGENTECAUSADOR | Integer |  | Código |  |

## TFPAGE — Agendamento de Folhas de Pgto
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | CODFUNC |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| PARAMETROS | Boolean |  | PARAMETROS |  |
| CODUSU | Integer |  | CODUSU |  |
| DTAGEND | DateTime |  | DTAGEND |  |
| DTPRONTO | DateTime |  | DTPRONTO |  |
| CONCLUIDO | String |  | CONCLUIDO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPAGNOC — TABLE TFPAGNOC
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DSCAGNOC | String |  | DSCAGNOC |  |
| ATIVO | String |  | ATIVO |  |
| CODAGNOC | String |  | CODAGNOC |  |

## TFPAGNOCATR — TABLE TFPAGNOCATR
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NRPROCJUD | String |  | Número Processo Adm/Judicial |  |
| INTCONC | Float |  | Intensidade ou concentração da exposição |  |
| LIMTOT | Float |  | Limite de Tolerância |  |
| UNMED | Integer |  | Unidade de medida intensidade ou concentração | `9`=09 - Fibra por centímetro cúbico (f/cm3) `8`=08 - Miligrama por metro cúbico de ar (mg/m3) `7`=07 - Parte de vapor ou gás por milhão de partes de ar contaminado (ppm) `6`=06 - Metro por segundo elevado a 1,75 (m/s1,75) `5`=05 - Metro por segundo ao quadrado (m/s2)_(+25)_ |
| DHALTER | DateTime |  | DHALTER |  |
| TECMEDICAO | String |  | Técnica Medição da intensidade ou concentração |  |
| CODUSU | Integer |  | CODUSU |  |
| USAEPC | Integer |  | Utiliza EPC | `2`=2 - Implementa `1`=1 - Não implementa `0`=0 - Não se aplica |
| EFICEPC | String |  | Os EPCs são eficazes na neutralização do risco ao trabalhador? | `S`=1 - Sim `N`=0 - Não |
| CODAMB | Integer |  | CODAMB |  |
| USAEPI | Integer |  | Utiliza EPI | `2`=2 - Utilizado `1`=1 - Não utilizado `0`=0 - Não se aplica |
| CODAGNOC | String |  | Cód. Agente Nocivo |  |
| TPAVAL | Integer |  | Tipo de avaliação | `2`=2 - Critério qualitativo `1`=1 - Critério quantitativo |

## TFPALTCPF — TABLE TFPALTCPF
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPORIG | Integer |  | CODEMPORIG |  |
| CODFUNCORIG | Integer |  | CODFUNCORIG |  |
| CODEMPDEST | Integer |  | CODEMPDEST |  |
| CODFUNCDEST | Integer |  | CODFUNCDEST |  |

## TFPALUNO — TABLE TFPALUNO
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| NROUNICO | Integer |  | NROUNICO |  |

## TFPAMB — Ambiente de Trabalho
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODAMB | Integer |  | Código |  |
| INIVALID | DateTime |  | INIVALID |  |
| NMAMB | String |  | Nome do Ambiente |  |
| FIMVALID | DateTime |  | FIMVALID |  |
| CODEMP | Integer |  | Empresa |  |
| LOCALAMB | Integer |  | Local | `2`=2 - Estabelecimento de Terceiros `1`=1 - Estabelecimento do próprio empregador |
| TPINSC | Integer |  | Tipo | `4`=CNO `3`=CAEPF `1`=CNPJ |
| CODPARC | Integer |  | Parceiro Tomador |  |
| NRINSCR | String |  | Número Inscrição |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| USADOESOCIAL | String |  | USADOESOCIAL |  |
| DSCAMB | String |  | Descrição do Ambiente |  |
| OBSERVACAO | String |  | Observação(ões) periculosa(s), insalubre(s) ou especial(is) desempenhada(s) |  |
| METERG | String |  | Metodologia utilizada para o levantamento dos riscos ergonômicos |  |
| DSCATIVDES | String |  | Descrição das Atividades desempenhadas |  |

## TFPAMBR — TABLE TFPAMBR
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CPFRESP | String |  | CPF Responsável |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODAMB | Integer |  | CODAMB |  |

## TFPAMF — TABLE TFPAMF
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| DTINICONDICAO | Date |  | Data Início da Condição |  |
| DTFIMCONDICAO | Date |  | Data Fim da Condição |  |
| CODAMB | Integer |  | Ambiente de Trabalho |  |

## TFPANA — Análises Folha
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEANALISE | String |  | NOMEANALISE |  |
| SCORE | Integer |  | SCORE |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| SQLCONSULTA | Boolean |  | SQLCONSULTA |  |
| DETALHEANALISE | String |  | DETALHEANALISE |  |
| CHARTTYPE | String |  | CHARTTYPE |  |
| AVISO | String |  | AVISO |  |
| CODANA | Integer |  | CODANA |  |

## TFPANX — Tabela de anexos das requisições
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REQID | Integer |  | REQID |  |
| ANEXO | Boolean |  | ANEXO |  |
| FILETYPE | String |  | FILETYPE |  |
| FILENAME | String |  | FILENAME |  |
| TIPOORIGEM | String |  | Origem do documento | `D`=Dependente `U`=Usuário |
| DOCORIGEM | String |  | Documento | `1`=Anexo RG `2`=Anexo CPF `3`=Anexo CNH `4`=Anexo Título Eleitor `5`=Anexo do Comprovante de Residência_(+3)_ |
| ID | Integer |  | ID |  |

## TFPANXDPD — Tabela de anexos do dependente
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REQID | Integer |  | REQID |  |
| ANEXO | Boolean |  | ANEXO |  |
| FILETYPE | String |  | FILETYPE |  |
| FILENAME | String |  | FILENAME |  |
| DOCORIGEM | String |  | Documento | `1`=Anexo RG `2`=Anexo CPF `3`=Anexo CNH |
| ID | Integer |  | ID |  |
| IDDPD | Integer |  | Sequencia do Dependente |  |

## TFPANXURL — Tabela de URL de anexos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| URL | String |  | URL |  |
| TENTATIVAS | Integer |  | Tentativas |  |
| STATUS | Integer |  | Status |  |
| DHALTER | DateTime |  | Data de Alteração |  |
| ID | Integer |  | ID |  |

## TFPANXURL_ASSOC — Tabela de Associação de URL de anexos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID_URL | Integer |  | ID da URL |  |
| TIPO_ENTIDADE | Integer |  | Tipo da Entidade | `0`=TFPANX `1`=TFPANXDPD |
| ID_ENTIDADE | Integer |  | ID da Entidade |  |
| ID_REQUISICAO_ENTIDADE | Integer |  | ID de Requisição da Entidade |  |
| ID | Integer |  | ID |  |

## TFPARQIMPHIST — Histórico importação crédito trabalhador
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEARQ | String |  | Nome do arquivo importado |  |
| CONTEUDO | Boolean |  | Conteúdo do arquivo importado |  |
| TAMANHO | Float |  | Tamanho do arquivo importado |  |
| DHIMPORT | DateTime |  | Data e hora da importação |  |
| CODUSU | Integer |  | Código do usuário |  |
| NROUNICO | Integer |  | Nro. único |  |

## TFPASO — Atestado de Saúde Ocupacional
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| DTASO | DateTime |  | DTASO |  |
| DTVENCASO | DateTime |  | DTVENCASO |  |
| TIPASO | Integer |  | TIPASO |  |
| RESULTADOASO | Integer |  | RESULTADOASO |  |
| MEDICOASO | String |  | MEDICOASO |  |
| TELMEDICOASO | String |  | TELMEDICOASO |  |
| CRMMEDICOASO | String |  | CRMMEDICOASO |  |
| UFCRMMEDASO | String |  | UFCRMMEDASO |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODCNES | String |  | CODCNES |  |
| FRMCTTUNIDATEND | String |  | FRMCTTUNIDATEND |  |
| EMAILUNIDATEND | String |  | EMAILUNIDATEND |  |
| TPEXAME | Integer |  | TPEXAME |  |
| CPFMED | String |  | CPFMED |  |
| NISMED | String |  | NISMED |  |
| INDRECUSA | String |  | INDRECUSA |  |
| MEDICOASOMON | String |  | MEDICOASOMON |  |
| TELMEDICOASOMON | String |  | TELMEDICOASOMON |  |
| CRMMEDICOASOMON | String |  | CRMMEDICOASOMON |  |
| UFCRMMEDASOMON | String |  | UFCRMMEDASOMON |  |
| CPFMEDMON | String |  | CPFMEDMON |  |
| NUASO | Integer |  | NUASO |  |

## TFPATIV — TABLE TFPATIV
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODATIV | String |  | Cód. Atividade |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODAMB | Integer |  | CODAMB |  |

## TFPATR — TABLE TFPATR
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| DTATRASO | Date |  | Data do Atraso |  |
| MINUTOS | Integer |  | Atrasos / Saídas Antecipadas (hrs) |  |
| ORIGEM | String |  | Origem | `P`=Ponto `M`=Manual |
| HORAATRASO | Text |  | Atrasos / Saídas Antecipadas (hrs) |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| PERDEDSR | String |  | Perde DSR | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TFPATV — TABLE TFPATV
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRATIV | String |  | DESCRATIV |  |
| DESCRCOMPLETA | String |  | DESCRCOMPLETA |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODATIV | String |  | CODATIV |  |

## TFPAUD — Auditoria E-Social
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODAVISO | Integer |  | CODAVISO |  |
| DTREF | Date |  | DTREF |  |
| DHALTER | DateTime |  | DTALTER |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEVENTO | String |  | CODEVENTO |  |
| INFOAVISO | String |  | INFOAVISO |  |
| INFOPESQ | String |  | INFOPESQ |  |
| GRUPO | String |  | GRUPO |  |
| CODAUDLOG | Integer |  | CODAUDLOG |  |

## TFPAUDAVI — Avisos Auditoria E-Social
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRAVISO | String |  | DESCRAVISO |  |
| ATIVO | String |  | CODAVISO |  |
| CODAVISO | Integer |  | CODAVISO |  |

## TFPAUDLOG — Log Auditoria E-Social
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODAVISO | Integer |  | CODAVISO |  |
| DTREF | Date |  | DTREF |  |
| DHAUD | DateTime |  | DTAUD |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODAUDLOG | Integer |  | CODAUDLOG |  |

## TFPAUT — Eventos Padrões
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave |  |
| SEQUENCIA | Integer |  | Seqüência |  |
| DESCRPAR | String |  | Descrição |  |
| CODEVENTO | Integer |  | Cód.Evento |  |
| TIPREG | String |  | Tipo do registro |  |

## TFPAVI — Tabela de Aviso Prévio
Campos: 30

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| CODTPR | Integer |  | Tipo Rescisão |  |
| PVD | String |  | Programa de Demissão Voluntária | `N`=Não `S`=Sim |
| DTNOTIFICACAO | Date |  | Data Notificação Aviso Prévio |  |
| TIPAVISO | Integer |  | Tipo Aviso | `3`=Dispensado `2`=Indenizado `1`=Trabalhado |
| ATVPREEMANUAL | String |  | Ativar Preenchimento Manual | `N`=Não `S`=Sim |
| DTAVISO | Date |  | Data Início Aviso Prévio |  |
| INICIATIVA | String |  | Iniciativa do Aviso | `F`=Colaborador `E`=Empresa |
| TIPREDUCAO | String |  | Opção p/ Red. Jornada | `J`=Reduzir a Jornada `A`=Abater Quant. Dias de Aviso `R`=Reduz 1 dia por semana conf. Lei nº 5889/73 `N`=Não se aplica |
| DIASAVISO | Integer |  | Dias Aviso |  |
| DTFIMAVISO | Date |  | Fim das Atividades |  |
| DTHOMOLOGA | Date |  | Data Homologação |  |
| DTQUITACAO | Date |  | Quitação Rescisão (Data Prevista) |  |
| INDCUMPRPARC | Integer |  | Indicador de cumprimento de Aviso Prévio | `4`=Aviso prévio indenizado ou não exigível `3`=Outras hipóteses de cumprimento parcial do aviso `2`=Cumprimento parcial por iniciativa da empresa `1`=Cumprimento parcial em razão de novo emprego `0`=Cumprimento total |
| DIASAVITRABIND | Integer |  | Dias de Aviso a serem indenizados pelo Empregador |  |
| DTALTER | Date |  | Data Alteração |  |
| NRPROCESSO | String |  | Nº Processo Trabalhista |  |
| OBSERVACAODET | String |  | Observação |  |
| FGTSSALDO | Float |  | Saldo FGTS |  |
| FGTSMESANTERIOR | String |  | Calcula mês Anterior | `S`=Sim `N`=Não |
| INDSITREMUNDESLIG | Integer |  | Indicativo de situação de remuneração após desligamento | `1`=Quarentena `2`=Desligamento/Termino legal com data anterior a competências com remunerações informadas no eSocial |
| DTFIMREMUN | Date |  | Data fim remuneração |  |
| NUPRT | Integer |  | Nro. Único Processo |  |
| DTCANCEL | Date |  | Data |  |
| CODUSU | Integer |  | Código do Usuário |  |
| CODREL | Integer |  | CODREL |  |
| MOTIVOCANCEL | Integer |  | Motivo | `9`=Outros `3`=Cumprimento de norma legal `2`=Determinação Judicial `1`=Reconsideração Prevista no artigo 489 da CLT |
| OBSERVACAOCANC | String |  | Observação |  |
| CODEMP | Integer |  | Empresa |  |

## TFPBAS — Tabela para Base de cálculo da folha
Campos: 45

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cód.Funcionário |  |
| TIPFOLHA | String |  | Tipo de Folha |  |
| DIASTRAB | Integer |  | Dias Trabalhados |  |
| SALBRUTO | Float |  | Salário Bruto |  |
| SALLIQ | Float |  | Salário Líquido |  |
| SALBASE | Float |  | Salário base |  |
| CODBCO | Integer |  | Cód.Banco |  |
| NUMCHEQ | Integer |  | Número do cheque |  |
| STATUS | Integer |  | Status | `0`=Pronto para a integração financeira `1`=Fechadas `3`=Com erro `4`=Com avisos `5`=Pronto para a integração contábil_(+2)_ |
| DTALTER | DateTime |  | Data de Alteração |  |
| DIGITADO | String |  | Define cálculo automático ou digitado |  |
| DTPAGAMENTO | DateTime |  | Data Pagamento |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUFIN | Integer |  | Número Único Financeiro |  |
| RECALCULA | String |  | Recalcular |  |
| PARAMETROS | C |  | Parâmetros |  |
| SEFIP650 | String |  | SEFIP650 |  |
| NUFINIRRF | Integer |  | NUFINIRRF |  |
| NUFINFGTS | Integer |  | NUFINFGTS |  |
| NUFINGRCSAVA | Integer |  | NUFINGRCSAVA |  |
| NUFINGRCSSIN | Integer |  | NUFINGRCSSIN |  |
| NUFINGRCSAAAL | Integer |  | NUFINGRCSAAAL |  |
| NUFINGRCSCON | Integer |  | NUFINGRCSCON |  |
| NUFINIRRFPLR | Integer |  | NUFINIRRFPLR |  |
| DISSIDIO | String |  | DISSIDIO |  |
| BLOQUEIAPORTALRH | String |  | BLOQUEIAPORTALRH |  |
| PARCDECTERC | Integer |  | PARCDECTERC |  |
| CODCONV | Integer |  | CODCONV |  |
| CODLOG | Integer |  | CODLOG |  |
| BLOQUEIAPORTALPTO | String |  | BLOQUEIAPORTALPTO |  |
| INDMV | Integer |  | INDMV |  |
| CODSIND | Integer |  | CODSIND |  |
| DSC | String |  | DSC |  |
| LIBESOCIAL | String |  | LIBESOCIAL |  |
| GERARPARESCISAO | String |  | GERARPARESCISAO |  |
| RESCISAODEFINITIVA | String |  | RESCISAODEFINITIVA |  |
| CODFUNCPRINC | Integer |  | CODFUNCPRINC |  |
| LOGCALC | C |  | LOGCALC |  |
| CODEMPCTB | Integer |  | CODEMPCTB |  |
| NUMLOTECTB | Integer |  | NUMLOTECTB |  |
| REFERENCIACTB | DateTime |  | REFERENCIACTB |  |
| EVENTOSINC | C |  | EVENTOSINC |  |
| REFERENCIA | DateTime |  | Referência |  |
| NAORECALCULA | String |  | NAORECALCULA |  |

## TFPBASTESTE — TABLE TFPBASTESTE
Campos: 41

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| DIASTRAB | Integer |  | DIASTRAB |  |
| SALBRUTO | Float |  | SALBRUTO |  |
| SALLIQ | Float |  | SALLIQ |  |
| SALBASE | Float |  | SALBASE |  |
| CODBCO | Integer |  | CODBCO |  |
| NUMCHEQ | Integer |  | NUMCHEQ |  |
| STATUS | Integer |  | STATUS |  |
| DTALTER | DateTime |  | DTALTER |  |
| DIGITADO | String |  | DIGITADO |  |
| DTPAGAMENTO | DateTime |  | DTPAGAMENTO |  |
| CODUSU | Integer |  | CODUSU |  |
| NUFIN | Integer |  | NUFIN |  |
| NAORECALCULA | String |  | NAORECALCULA |  |
| SEFIP650 | String |  | SEFIP650 |  |
| NUFINIRRF | Integer |  | NUFINIRRF |  |
| NUFINFGTS | Integer |  | NUFINFGTS |  |
| NUFINGRCSAVA | Integer |  | NUFINGRCSAVA |  |
| NUFINGRCSSIN | Integer |  | NUFINGRCSSIN |  |
| NUFINGRCSAAAL | Integer |  | NUFINGRCSAAAL |  |
| NUFINGRCSCON | Integer |  | NUFINGRCSCON |  |
| NUFINIRRFPLR | Integer |  | NUFINIRRFPLR |  |
| DISSIDIO | String |  | DISSIDIO |  |
| BLOQUEIAPORTALRH | String |  | BLOQUEIAPORTALRH |  |
| PARCDECTERC | Integer |  | PARCDECTERC |  |
| CODCONV | Integer |  | CODCONV |  |
| CODLOG | Integer |  | CODLOG |  |
| BLOQUEIAPORTALPTO | String |  | BLOQUEIAPORTALPTO |  |
| INDMV | Integer |  | INDMV |  |
| PARAMETROS | C |  | PARAMETROS |  |
| RECALCULA | String |  | RECALCULA |  |
| LOGCALC | C |  | LOGCALC |  |
| CODFUNCPRINC | Integer |  | CODFUNCPRINC |  |
| RESCISAODEFINITIVA | String |  | RESCISAODEFINITIVA |  |
| GERARPARESCISAO | String |  | GERARPARESCISAO |  |
| CODSIND | Integer |  | CODSIND |  |
| DSC | String |  | DSC |  |
| EVENTOSINC | C |  | EVENTOSINC |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |

## TFPBEN — Benefício
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEN | Integer |  | Código |  |
| CODCENCUS | Integer |  | Centro de Resultado |  |
| CODCENCUSDIF | Integer |  | Centro de Custo Diferença |  |
| CODCTABCOINT | Integer |  | Conta |  |
| CODEVENTO | Integer |  | Evento Beneficiário |  |
| CODEVENTOEMP | Integer |  | Evento Empresa |  |
| CODNAT | Integer |  | Natureza |  |
| CODPARCEMP | Integer |  | Parceiro Empresa |  |
| CODPROJ | Integer |  | Projeto |  |
| CODTIPOPER | Integer |  | Tipo Operação |  |
| CODTIPTIT | Integer |  | Tipo de Título |  |
| VALIDAAFASTAMENTO | String |  | Desconta Afastamento? | `S`=Sim `N`=Nao |
| FORMULA | String |  | Formula |  |
| FORMULAIND | String |  | Fórmula de Índice |  |
| VLRPARTEEMPRESA | Float |  | Valor Parte Empresa |  |
| DESCRICAO | String |  | Descrição |  |
| CODTBE | Integer |  | Tipo de Benefício |  |
| CODEMP | Integer |  | Empresa |  |
| CODPARC | Integer |  | Fornecedor |  |
| DESCHRCARGA | String |  | Desconsidera dia com carga < 6h | `S`=Sim `N`=Não |
| TIPOBENEFICIO | Integer |  | Tipo Benefício |  |
| CODBCO | Integer |  | Banco |  |

## TFPBHM — Movimento
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Cód.Funcionário |  |
| REFERENCIA | DateTime |  | Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| HORAS | Integer |  | Horas |  |
| MINUTOS | Integer |  | Minutos |  |
| CREDDEBBCH | Integer |  | Crédito ou Débito Banco de Horas |  |
| AUTORIZADO | String |  | AUTORIZADO |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TFPBHS — FP Tabela de Saldo
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cód.Funcionário |  |
| CREDITOSHOR | Integer |  | Créditos Horas |  |
| CREDITOSMIN | Integer |  | Créditos Minutos |  |
| DEBITOSHOR | Integer |  | Débitos Horas |  |
| DEBITOSMIN | Integer |  | Débitos Minutos |  |
| REFERENCIA | Date |  | Referência |  |
| SALDOINICMESHOR | Integer |  | Saldo Inicial do Mês Horas |  |
| SALDOINICMESMIN | Integer |  | Saldo Inicial do Mês Minutos |  |
| ACRESCIMOMIN | Integer |  | ACRESCIMOMIN |  |
| AUTORIZADO | String |  | AUTORIZADO |  |
| BAIXAACRESCMIN | Integer |  | BAIXAACRESCMIN |  |
| COMPACRESCIMOMIN | Integer |  | COMPACRESCIMOMIN |  |
| DTPERIODOFIM | Date |  | DTPERIODOFIM |  |
| DTPERIODOINI | Date |  | DTPERIODOINI |  |
| FALTASHOR | Integer |  | FALTASHOR |  |
| FALTASMIN | Integer |  | FALTASMIN |  |
| PAGAMENTOHOR | Integer |  | PAGAMENTOHOR |  |
| PAGAMENTOMIN | Integer |  | PAGAMENTOMIN |  |
| SALDOINIACRESCMIN | Integer |  | SALDOINIACRESCMIN |  |

## TFPBSU — Tabela para Base de cálculo da folha suplementar
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | REFERENCIA |  |
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| SEQFOLHA | Integer |  | SEQFOLHA |  |
| DIASTRAB | Integer |  | DIASTRAB |  |
| SALBRUTO | Float |  | SALBRUTO |  |
| SALLIQ | Float |  | SALLIQ |  |
| SALBASE | Float |  | SALBASE |  |
| DTALTER | Date |  | DTALTER |  |
| DIGITADO | String |  | DIGITADO |  |
| DTPAGAMENTO | Date |  | DTPAGAMENTO |  |
| CODUSU | Integer |  | CODUSU |  |
| NUFIN | Integer |  | NUFIN |  |
| NUMRPA | Integer |  | NUMRPA |  |
| LIBESOCIAL | String |  | LIBESOCIAL |  |
| GERARPARESCISAO | String |  | GERARPARESCISAO |  |
| STATUS | Integer |  | STATUS |  |
| NAORECALCULA | String |  | NAORECALCULA |  |
| DISSIDIO | String |  | DISSIDIO |  |
| DSC | String |  | DSC |  |
| CODCONV | Integer |  | CODCONV |  |
| PARAMETROS | C |  | PARAMETROS |  |
| VALIDADO | String |  | VALIDADO |  |
| CODLOG | Integer |  | CODLOG |  |

## TFPCAB — Cabeçalho do ESocial
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Data de Referência |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| CONTROLE | String |  | Controle de Alteração |  |
| SEQUENCIAATUAL | Integer |  | Sequência Atual de Geração |  |
| EVTPENDENTE | Integer |  | Eventos Pendentes p/ Sequência Atual |  |
| EVTENVIADO | Integer |  | Eventos Enviados  p/ Sequência Atual |  |
| EVTAGUARCORRECAO | Integer |  | Eventos Aguard. Correção  p/ Sequência Atual |  |
| EVTFINALIZADO | Integer |  | Eventos Finalizados  p/ Sequência Atual |  |
| FINALIZADOSUCESSO | Integer |  | Finalizado com Sucesso |  |
| EMPROCESSAMENTO | Integer |  | Em Processamento |  |
| FINALIZADOERRO | Integer |  | Finalizado com Erro |  |
| CODEMP | Integer |  | Empresa |  |

## TFPCAR — Cargos
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCARGO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Data de Alteração |  |
| POSSUINIVEL | String |  | Possui nivelamento | `S`=Sim `N`=Não |
| CODCBO | Integer |  | CBO |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ORIGATIV | Integer |  | Origem das Atividades p/ E-Social | `1`=Procedimentos `0`=Tarefas |
| TEMPOASO | Integer |  | Tempo Val. ASO |  |
| CODGRUPOCARGO | Integer |  | Cód. Grupo Cargo |  |
| CONTAGEMTEMPO | String |  | Contagem Tempo |  |
| TECNICOCIENTIFICO | String |  | Técnico científico | `1`=Sim `0`=Não |
| CODESCALA | Integer |  | Cód. Escala |  |
| SITCARGO | Integer |  | Situação |  |
| USADOESOCIAL | String |  | Compõe E-Social | `S`=Sim `N`=Não |
| APOSENTAESP | String |  | Aposentad. Esp. | `S`=Sim `N`=Não |
| OBS | String |  | Descrição do Cargo |  |
| RESPONSABILIDADES | String |  | Responsabilidades |  |
| CODCARREIRA | Integer |  | Cód. Carreira |  |
| CODNIVELINI | Integer |  | Nível Inicial |  |
| CODNIVELFIM | Integer |  | Nível Final |  |
| DEDICACAOEXC | String |  | Dedicação Exc. | `S`=Sim `N`=Não |
| ACUMCARGO | Integer |  | Acum. Cargo |  |
| CONTAGEMESP | Integer |  | Contagem Esp. |  |
| NRLEI | String |  | Número da Lei |  |
| DTLEI | Date |  | Data da Lei |  |
| CODCARGO | Integer |  | Cargo |  |

## TFPCAT — Categoria
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCATEG | Integer |  | Cód.Categoria |  |
| DESCRCATEG | String |  | Descricao da categoria |  |

## TFPCATR — Comunicação de Acidente de Trabalho
Campos: 57

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTCAT | Date |  | Data da CAT |  |
| TIPCAT | Integer |  | Tipo de CAT | `3`=Comunicação de Óbito `2`=Reabertura `1`=Inicial |
| NUCATORIG | Integer |  | CAT Origem |  |
| NUMEROCAT | String |  | Número da CAT |  |
| TIPACIDENTE | Integer |  | Tipo de Acidente | `3`=Trajeto `2`=Doença `1`=Tipico |
| INICIATCAT | Integer |  | Iniciativa da CAT | `3`=Determinação do órgão fiscalizador `2`=Ordem judicial `1`=Iniciativa do empregador |
| DTACIDENTE | Date |  | Data do Acidente |  |
| HRACIDENTE | Integer |  | Hora do Acidente |  |
| HORASTRAB | Integer |  | Horas Trabalhadas |  |
| DTULTDIATRAB | Date |  | Último dia Trabalhado |  |
| HOUVEAFAST | String |  | Houve Afastamento? | `N`=Não `S`=Sim |
| INDCATOBITO | String |  | Indica Óbito | `S`=Sim `N`=Não |
| COMUNPOLICIAL | String |  | Houve Comunicação Policial? | `S`=Sim `N`=Não |
| CODSITGERADORA | String |  | Situação Geradora do Acidente |  |
| DESCLESAO | String |  | Descrição complementar / natureza da lesão |  |
| CODAGENTECAUSADOR | String |  | Agente Causador |  |
| DESCRLOCALCAT | String |  | Especificação do Local |  |
| TIPLOCALCAT | Integer |  | Tipo de Local | `9`=9 - Outros `8`=8 - Embarcação `5`=5 - Área rural `4`=4 - Via pública `3`=3 - Estab. de terceiros onde presta serviço_(+2)_ |
| CEP | String |  | CEP |  |
| CODENDLOCALCAT | Integer |  | Endereço |  |
| NUMENDLOCALCAT | String |  | Número |  |
| CODBAI | Integer |  | Bairro |  |
| COMPLEMENTO | String |  | Complemento |  |
| CODCIDLOCALCAT | Integer |  | Cidade |  |
| CODPAIS | Integer |  | País |  |
| CODPOSTAL | String |  | Código Postal |  |
| DTATENDIMENTO | Date |  | Data de Atendimento |  |
| HRATENDIMENTO | Integer |  | Hora Atendimento |  |
| INDINTERNACAO | String |  | Houve internação? | `S`=Sim `N`=Não |
| DURTRATAMENTO | Integer |  | Duração do tratamento (em dias) |  |
| CODNATLESAO | String |  | Descrição da lesão |  |
| CODCIDATESTADO | String |  | CID |  |
| DESCLESAOCOMP | String |  | Descrição complementar / natureza da lesão |  |
| NOMEEMITENTE | String |  | Médico/Dentista |  |
| CPFEMITENTE | String |  | Médico / Dentista |  |
| NROC | String |  | Inscrição no Órgão de Classe/Registro do MS(RMS) |  |
| IDEOC | Integer |  | Órgão de Classe | `3`=3 - Registro do Ministério da Saúde - RMS `2`=2 - Conselho Regional de Odontologia - CRO `1`=1 - Conselho Regional de Medicina - CRM |
| INDAFASTAMENTO | String |  | Indicativo de repouso durante o tratamento? | `S`=Sim `N`=Não |
| DIAGPROVAVEL | String |  | Diagnóstico Provável |  |
| UFOC | String |  | UF Órgão de classe | `TO`=TO - Tocantins `SP`=SP - São Paulo `SE`=SE - Sergipe `SC`=SC - Santa Catarina `RS`=RS - Rio Grande do Sul_(+22)_ |
| TPINSC | Integer |  | Tipo de Inscrição | `2`=CNPJ `1`=CAEPF `3`=CNO |
| NRINSC | String |  | Número da Inscrição |  |
| DTOBITO | Date |  | Data do Óbito |  |
| CODAMB | Integer |  | Ambiente de Trabalho |  |
| CNPJTOMADOR | String |  | CNPJTOMADOR |  |
| CODCNES | Integer |  | Código da Unidade de Atendimento |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| EMITENTE | Integer |  | Emitente | `9`=Dependente do empregado `8`=Entidade sindical competente `7`=Órgão gestor de mão de obra `6`=Cooperativa `5`=Autoridade pública_(+4)_ |
| INDCATPARCIAL | String |  | CAT Parcial? | `S`=Sim `N`=Não |
| NUCAT | Integer |  | NUCAT |  |
| OBSERVACAOCAT | String |  | Observações |  |
| OBSERVACOES | String |  | Observações |  |
| TPACID | String |  | Tipo de Acidente de Trabalho (Versão eSocial 2.5) |  |
| NRORECIBO | String |  | Número do Recibo eSocial/CAT |  |

## TFPCBE — Central Benefício
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCBE | Integer |  | Nro. Único |  |
| CODBEN | Integer |  | Benefício |  |
| REFERENCIA | Date |  | Referência |  |
| VLRNOTA | Float |  | Vlr. Nota |  |
| VLRBEN | Float |  | Vlr. Beneficiários |  |
| VLREMP | Float |  | Vlr. Empresa |  |
| VLRFECHAMENTO | Float |  | Vlr. Fechamento |  |
| DTINI | Date |  | Dt. Início Referência |  |
| DTFIM | Date |  | Dt. Fim Referência |  |
| VLREXTRABEN | Float |  | Valor Extra Beneficiário |  |
| VLREXTRAEMP | Float |  | Valor Extra Empresa |  |
| TIPOBENEFICIO | Integer |  | Tipo Benefício |  |
| DTFIMAPUBEN | Date |  | Data de fim da Apuração dos Benefícios |  |
| DTINIAFASTFAL | Date |  | Data de início da Apuração de Faltas, Atestados e Afastamentos |  |
| DTFIMAFASTFAL | Date |  | Data de fim da Apuração de Faltas, Atestados e Afastamentos |  |
| DTINIAPUBEN | Date |  | Data de início da Apuração dos Benefícios |  |
| DESCRICAO | String |  | Descrição |  |
| DTVENC | Date |  | Dt. Vencimento |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| STATUS | String |  | Status | `PE`=Pendente `CO`=Concluído |
| VLRDIF | Float |  | Vlr. Diferença |  |

## TFPCBO — CBO Código Brasileiro de Ocupação
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCBO | String |  | Descrição |  |
| TIPHORANOTURNA | String |  | Tipo do Horário Noturno | `U`=Urbano `P`=Rural (Pecuária) `L`=Rural (Lavoura) |
| CODCBO | Integer |  | Código |  |

## TFPCERT — Certificados Digitais
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ARQUIVO | String |  | Arquivo |  |
| CERTIFICADO | Boolean |  | Certificado |  |
| CNPJ | String |  | CNPJ |  |
| SENHA | String |  | Senha |  |
| NOME | String |  | Nome |  |
| EMISSOR | String |  | Emissor |  |
| CIDADE | String |  | Cidade |  |
| ESTADO | String |  | Estado |  |
| DTVALINI | Date |  | Data Inicial de Validade |  |
| DTVALFIM | Date |  | Data Final de Validade |  |
| ALIAS | String |  | Alias |  |
| APLICACAO | String |  | Aplicação | `S`=Sanesocial `W`=SankhyaOm |
| CODEMP | Integer |  | Código da Empresa |  |
| NROUNICO | Integer |  | Número Único |  |

## TFPCEV — Cargos Eventos
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCARGO | Integer |  | Cód.Cargo |  |
| CODEVENTO | Integer |  | Cód.Evento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| VLRMOV | Float |  | Valor do Movimento |  |
| INDICE | Float |  | Índice |  |
| UNIDADE | String |  | Unidade |  |
| OBS | String |  | Observações |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TFPCGH — Identificação da Carga Horária
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCARGAHOR | String |  | Descrição |  |
| TIPCARGAHOR | String |  | Tipo Carga Horária | `C`=Carga Horária `J`=Jornada de Trabalho |
| ATIVO | String |  | Ativa | `S`=Sim `N`=Não |
| ESCALONAR | String |  | Escalonar Dias de Trabalho | `S`=Sim `N`=Não |
| DIASTRAB | Integer |  | Dias de Trabalho |  |
| DIASFOLGA | Integer |  | Dias de Folga |  |
| QTDTURNO | Integer |  | Qtde de Turnos | `4`=4 `3`=3 `2`=2 `1`=1 |
| USAROCORRENCIA | String |  | Ocorrência |  |
| CONSIDERAFERIADOS | String |  | Considera Ocorrências nos Feriados | `S`=Sim `N`=Não |
| ALTERNAJORNADA | String |  | Alternar Jornadas | `S`=Sim `N`=Não |
| ALTERNATIVA | Integer |  | C.Hor. Alternativa |  |
| NAOCONFORMAFDT | String |  | Não Conform. Afdt | `S`=Sim `N`=Não |
| FOLGAPERCDSR | String |  | Considerar Folga com percentual de DSR/Feriado | `S`=Sim `N`=Não |
| TIPINTERVALO | Integer |  | Tipo | `2`=Intervalo Variável `1`=Intervalo Fixo `0`=Sem intervalo |
| DURINTERVALO | Integer |  | Duração em minutos |  |
| SUMULA444 | String |  | Considera Súmula nº444 TST | `S`=Sim `N`=Não |
| RECESSO | String |  | Dias de Recesso | `S`=Sim `N`=Não |
| TPJORNADA | Integer |  | Tipo de Jornada | `2`=2 - Jornada 12 x 36 (12 horas de trabalho seguidas de 36 horas ininterruptas de descanso) `9`=9 - Demais tipos de jornada `7`=7 - Turno ininterrupto de revezamento `6`=6 - Jornada hr/diário fixo e folga fixa(outro dia da semana), c/ folga adicional periódica domingo `5`=5 - Jornada com horário diário fixo e folga fixa (exceto no domingo)_(+2)_ |
| USAHRNOTURNA | String |  | Possui Horário Noturno (Total ou Parcial) | `S`=Sim `N`=Não |
| PERHORFLEXIVEL | String |  | Permite flexibilidade de horário | `S`=Sim `N`=Não |
| USAPAUSA | String |  | Possui pausa nos turnos | `S`=Sim `N`=Não |
| TOLERANCIANAPAUSA | String |  | Aplica Tolerância | `S`=Sim `N`=Não |
| USAEXTRAPAUSA | String |  | Aplica Extra | `S`=Sim `N`=Não |
| USAATRASOPAUSA | String |  | Aplica Atraso | `S`=Sim `N`=Não |
| INIINTERV | Integer |  | Início intervalo |  |
| TERMINTERV | Integer |  | Témino Intervalo |  |
| REDHRSNOT | String |  | Considera redução de horas noturnas para cálculo de jornada | `S`=Sim `N`=Não |
| USADOESOCIAL | String |  | Compõe E-Social | `S`=Sim `N`=Não |
| COMPRAVAVTFERIADO | String |  | Considerar feriado VA e VT | `S`=Sim `N`=Não |
| TOLERANCIANOINTERV | String |  | Aplica Tolerância | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODCARGAHOR | Integer |  | Cód.Carga Horária |  |

## TFPCHQ — FP Cheques Cancelados
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBCO | Integer |  | Banco |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| NUMCHEQ | Integer |  | Número do cheque |  |
| VLRCHEQ | Float |  | Valor do cheque |  |

## TFPCMS — Confirma Mensagem do Portal RH
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | CODFUNC |  |
| CODMENSAGEM | Integer |  | CODMENSAGEM |  |
| CODCONFMENSAGEM | Integer |  | CODCONFMENSAGEM |  |

## TFPCMV — Beneficiário
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODCBE | Integer |  | Central |  |
| VLRBEN | Float |  | Valor. Beneficário |  |
| CODCMV | Integer |  | Cód. CMV |  |
| VLREMP | Float |  | Valor. Empresa |  |
| MANUAL | String |  | Lançamento Manual? | `G`=Grupo `S`=Sim `N`=Não |
| CODEVENTO | Integer |  | Evento |  |
| VLREXTRAEMP | Float |  | Valor. Extra Empresa |  |
| VLREXTRABEN | Float |  | Valor. Extra Beneficiário |  |
| QTDITE | Float |  | Quantidade |  |
| INDBEN | Float |  | Índice Beneficiário |  |
| INDEMP | Float |  | Índice Empresa |  |
| DEPENDENTE | String |  | Dependente | `S`=Sim `N`=Não |

## TFPCNV — TABLE TFPCNV
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROCESSO | String |  | Processo |  |
| TPACCONV | String |  | Tipo | `D`=D - Sentença Normativa - Dissídio `C`=C - Convenção coletiva de Trabalho `A`=A - Acordo Coletivo de Trabalho |
| VARA | String |  | Vara/JCJ |  |
| ANO | Integer |  | Ano |  |
| DTDATABASE | Date |  | Data Base |  |
| DTASSINATURA | Date |  | Data Assinatura |  |
| PERCCNV | Float |  | Percentual |  |
| DTREAJUSTE | Date |  | Ref. Reajuste |  |
| REAJSINDICAL | String |  | Reaj. Sindical | `S`=Sim `N`=Não |
| DTREFFAIXA | Date |  | Ref. Tab. Faixa |  |
| CODTABFAIXA | Integer |  | Cód. Tab. Faixa |  |
| DTEFACCONV | Date |  | Data de Entrada em Vigor |  |
| USATABMISTA | String |  | Tab. Perc. e Valor | `S`=Sim `N`=Não |
| DTCALCDIFERENCASFIM | Date |  | Considerar diferenças final: |  |
| DTCALCDIFERENCASINI | Date |  | Considerar diferenças inicial: |  |
| DTREFSALBASE | Date |  | Ref. Salário Base |  |
| DSC | String |  | Descrição do Instrumento |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| PERCANTECIPACAO | Float |  | Perc. Antecipação |  |
| DTANTECIPACAO | Date |  | Data Ref. Antecipação |  |
| CODHISTANTECIPA | Integer |  | Cód. Hist. Antecipação |  |
| CODSIND | Integer |  | CODSIND |  |
| SEQUENCIA | Integer |  | Sequência |  |
| VALORLIMITETETO | Float |  | Valor limite do teto: |  |
| VALORAPLICADOTETO | Float |  | Valor aplicado a partir do limite do teto: |  |
| TIPOPROCESSORRA | Integer |  | Tipo de Processo | `1`=Administrativo `2`=Judicial |
| NROPROCESSORRA | String |  | Número do Processo para eSocial |  |
| DESCRICAORRA | String |  | Descrição dos Rendimentos Recebidos Acumuladamente - RRA |  |
| VLRDESPESAJUD | Float |  | Valor das Despesas de Custas Judiciais |  |
| VLRDESPESAADV | Float |  | Valor Total das Despesas com Advogado(s) |  |
| CARACTERISTICA | String |  | Característica |  |

## TFPCNVADV — Convenção Coletiva Advogados e Escritórios
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSIND | Integer |  | Código Sindicato |  |
| PROCESSO | String |  | Processo |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODADV | Integer |  | Advogado |  |
| VLRADV | Float |  | Valor das Despesas com Advogado |  |

## TFPCON — TABLE TFPCON
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJ | String |  | CNPJ |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| REGANS | Integer |  | Reg. Ag. Nac. Saúde |  |
| DESCRCONVENIO | String |  | Tipo |  |
| CODEVENTO | Integer |  | Cód. Evento |  |
| LISEVENTOS | String |  | Evento |  |
| LISEVEREEMBOLSO | String |  | Eventos Reemb. |  |
| LISEVEREEMBANTERIOR | String |  | Eventos Reemb. Anterior |  |
| CODCONVENIO | Integer |  | Código |  |

## TFPCRE — Critério de Rateio
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRRATEIO | String |  | Descrição |  |
| CODCRIRATEIO | Integer |  | Código |  |

## TFPCRR — TABLE TFPCRR
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCARREIRA | String |  | Descrição da carreira |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| LEICARR | String |  | Lei Carreira |  |
| DTLEICARR | Date |  | Dt. Lei Carreira |  |
| SITCARR | String |  | Sit. Carreira |  |
| USADOESOCIAL | String |  | eSocial? | `S`=Sim `N`=Não |
| CODCARREIRA | Integer |  | Código |  |

## TFPCTA — FP Contas
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTACTB | Integer |  | Cód.Conta Contábil |  |

## TFPCTB — FP Contas Contábeis na Folha
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| HISTORICOCREDITO | Integer |  | Histórico do crédito |  |
| CONTACREDITO | Integer |  | Conta de crédito |  |
| HISTORICODEBITO | Integer |  | Histórico do Débito |  |
| CONTADEBITO | Integer |  | Conta do Débito |  |
| CODREGFIS | Integer |  | Cód.Registro Fiscal |  |
| FORMULA | String |  | Fórmula |  |
| TIPCONTABIL | String |  | Tipo de Contabilização | `N`=Normal `F`=Provisão de férias `D`=Provisão de décimo terceiro |
| SEQUENCIA | Integer |  | Sequência |  |
| FORMULAID | Integer |  | Fórmula Contábil |  |
| CODEVENTO | Integer |  | Cód.Evento |  |
| CODGRUPOCTBZ | Integer |  | Cód.Grupo Contabilização |  |

## TFPCTBFOR — Fórmulas Contábeis
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCR | String |  | DESCR |  |
| INCORPORACAO | String |  | INCORPORACAO |  |
| TERCOFERIAS | String |  | TERCOFERIAS |  |
| MULTIPLICADOR | Integer |  | MULTIPLICADOR |  |
| PERFGTS | String |  | PERFGTS |  |
| PERINSS | String |  | PERINSS |  |
| PERINSS13 | String |  | PERINSS13 |  |
| PERGRPS | String |  | PERGRPS |  |
| PERSEGU | String |  | PERSEGU |  |
| PERFAP | String |  | PERFAP |  |
| PERRAT | String |  | PERRAT |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| PERPIS | String |  | PERPIS |  |
| PERPIS_2 | String |  | PERPIS_2 |  |
| FORMID | Integer |  | FORMID |  |

## TFPCTG — TABLE TFPCTG
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCATEGESOCIAL | String |  | Descrição |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODCATEGESOCIAL | Integer |  | Código |  |

## TFPCTI — TABLE TFPCTI
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCONV | String |  | Descrição |  |
| CODEMP | Integer |  | Empresa |  |
| CODEND | Integer |  | Endereço |  |
| NUMEND | String |  | Número |  |
| COMPLEMENTO | String |  | Complemento |  |
| CODBAI | Integer |  | Bairro |  |
| CODCID | Integer |  | Cidade |  |
| CEP | String |  | CEP |  |
| DTPREVPGTO | DateTime |  | DTPREVPGTO |  |
| CODCONV | Integer |  | Código |  |

## TFPDDE — Deduções com exigibilidade suspensa
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDDE | Integer |  | No. único Dedução |  |
| NURNE | Integer |  | No. único Retenção |  |
| INDTPDEDUCAO | String |  | Tipo de dedução | `1`=1 - Previdência oficial `2`=2 - Previdência privada `3`=3 - Fundo de Aposentadoria Programada Individual - FAPI `4`=4 - Fundação de Previdência Complementar do Servidor Público - Funpresp `5`=5 - Pensão alimentícia_(+1)_ |
| VLRDEDSUSP | Float |  | Valor da dedução |  |
| CNPJENTIDPC | String |  | CNPJ Entidade de Previdência Complementar |  |

## TFPDDES — Detalhamento das deduções com exigibilidade suspensa
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDDES | Integer |  | Número Único TFPDDES |  |
| NUIVRDJ | Integer |  | Número Único TFPIVRDJ |  |
| INDTPDEDUCAO | String |  | Indicativo de dedução | `1`=1 - Previdência Oficial `5`=5 - Pensão alimentícia `7`=7 - Dependente |
| VLRDEDSUSP | Float |  | Valor da dedução suspensa |  |

## TFPDDESD — Informação das deduções suspensas por dependentes e beneficiários da pensão alimentícia
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDDESD | Integer |  | Número Único TFPDDESD |  |
| NUDDES | Integer |  | Número Único TFPDDES |  |
| CPFDEP | String |  | CPF do Dependente |  |
| VLRDEPENSUSP | Float |  | Valor da dedução ou pensão suspensa |  |
| NMDEP | String |  | Nome do Dependente |  |

## TFPDEP — Departamentos
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRDEP | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `S`=Sim `N`=Não |
| GRAU | Integer |  | Grau |  |
| CODEND | Integer |  | Endereço |  |
| CODDEPPAI | Integer |  | Departamento Pai |  |
| NUMEND | String |  | Número |  |
| COMPLEMENTO | String |  | Complemento |  |
| CODCENCUS | Integer |  | Centro de Resultado |  |
| CODREGFIS | Integer |  | Registro fiscal |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| TIPLOTACAO | Integer |  | Tipo Lotação |  |
| TPINSCPROP | Integer |  | Tip. Inscr. Prop | `2`=CPF `1`=CNPJ |
| NRINSCPROP | String |  | Código |  |
| NRINSCCONTRAT | String |  | Código |  |
| DHALTER | DateTime |  | Data de alteração |  |
| TPINSCCONTRAT | Integer |  | Tip. Inscr. Contratante | `2`=CPF `1`=CNPJ |
| CODDEP | Integer |  | Departamento |  |
| CODPROJ | Integer |  | Projeto |  |

## TFPDETDESCFOL — Detalhes do empréstimo em folha
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| DTINICONTRATO | Date |  | Data de início do contrato |  |
| DTFIMCONTRATO | Date |  | Data de término do contrato |  |
| COMPINIDESC | String |  | Competência inicial de desconto |  |
| COMPFIMDESC | String |  | Competência final de desconto |  |
| OBSERVACAO | String |  | Observação |  |
| TOTALPARCELAS | Integer |  | Total de parcelas |  |
| VALORPARCELA | Float |  | Valor da parcela |  |
| VALOREMPRESTIMO | Float |  | Valor do empréstimo |  |
| VALORLIBERADO | Float |  | Valor liberado |  |
| QTDPAGAMENTOS | Integer |  | Quantidade de pagamentos |  |
| QTDESCRITURACOES | Integer |  | Quantidade de escrituras |  |
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| TIPMOV | String |  | TIPMOV |  |
| NROUNICO | Integer |  | Nro. único |  |

## TFPDFB — Dependente Benefício
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DESCRDEPENDENTE | String |  | Nome Dependente |  |
| CODFUNC | Integer |  | Funcionario |  |
| CODBEN | Integer |  | Benefício |  |
| SEQUENCIA | Integer |  | Dependente |  |

## TFPDIV — Divisões
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODDIV | Integer |  | Código da divisão |  |
| DESCRDIV | String |  | Descrição |  |

## TFPDOCSIGN — Assinatura Digital Folha
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| FILENAME | String |  | Nome do Arquivo |  |
| FILETYPE | String |  | Tipo do Arquivo |  |
| ANEXO | Boolean |  | Anexo |  |
| DHALTER | Date |  | Data de Alteracao |  |
| CODEMP | Integer |  | Empresa |  |
| ID | Integer |  | ID |  |

## TFPDPD — Dependentes
Campos: 55

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| NOMEDEPEND | String |  | Nome |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CPF | String |  | CPF |  |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| DTNASC | Date |  | Data de nascimento |  |
| ADOTIVO | String |  | Filho Adotivo | `S`=Sim `N`=Não |
| GRAUPARENTESCO | Integer |  | Grau de parentesco | `1`=Filho(a) `7`=Outros `6`=Inválido(a) `5`=Sobrinho(a) `3`=Pai/Mãe_(+13)_ |
| DESCRDPD | String |  | Descrição da Dependência |  |
| NACIONALIDADE | Integer |  | Nacionalidade | `10`=Brasileiro `20`=Naturalizado Brasileiro `21`=Argentino `22`=Boliviano `23`=Chileno_(+31)_ |
| CODCID | Integer |  | Naturalidade |  |
| RACAETNIA | Integer |  | Raça/Etnia | `10`=Indígena `20`=Branca `30`=Preta `40`=Parda `50`=Amarela_(+1)_ |
| DEPENDIRF | String |  | Dependente de IRRF | `N`=Não `S`=Sim |
| NOMEMAE | String |  | Nome da Mãe |  |
| DEPRPPS | String |  | Dependente de Fins Previdenciários | `N`=Não `S`=Sim |
| CONVENIO | String |  | Dependente de Convênio Médico | `N`=Não `S`=Sim |
| AUXCRE | String |  | Tem Auxílio Creche | `N`=Não `S`=Sim |
| INCTRAB | String |  | Possui Incapacidade Física ou Mental para o Trabalho | `N`=Não `S`=Sim |
| CARTORIO | String |  | Cartório |  |
| OBSDEFICIENCIA | String |  | Observação da Deficiência | `N`=Não `S`=Sim |
| NROFOLHAREG | Integer |  | Número da Folha do Livro de Registro |  |
| PENSIONISTA | String |  | Pensionista | `N`=Não `S`=Sim |
| NROLIVROREG | String |  | Número do Livro de Registro |  |
| NROREG | String |  | Número do Registro |  |
| DTINICDEPEND | Date |  | Data Inicial da Dependência |  |
| DTFIMDEPEND | Date |  | Data Final da Dependência |  |
| SALFAM | String |  | Dependente de Salário família | `S`=Sim `N`=Não |
| DTLIMAUXCRE | Date |  | Data Limite do Auxílio Creche |  |
| DTLIMIRF | Date |  | Data limite do IRRF |  |
| DTLIMSALFAM | Date |  | Data Limite do Salário Família |  |
| MOTIVOINICIO | Integer |  | Motivo do Início da Dependência | `19`=Designação expressa pelo Servidor `18`=Tutela do menor `17`=Filho póstumo `16`=Dependência econômica `15`=Decisão judicial_(+5)_ |
| MOTIVOFIM | Integer |  | Motivo do Fim da Dependência | `59`=Exclusão expressa pelo Servidor `58`=Revogação de Tutela `57`=Independência econômica `56`=Cessação de invalidez `55`=Decisão judicial_(+5)_ |
| IDADEESCOLAR | String |  | Possui Idade Escolar | `N`=Não `S`=Sim |
| DTALTER | DateTime |  | Data de alteração |  |
| MESDIA | Integer |  | Mês e dia do nascimento |  |
| PERCHNETFGTS | Float |  | Percentual do FGTS |  |
| VLRPENSAOFGTS | Float |  | Valor do FGTS |  |
| SEMATESTADO | String |  | Não Apresentou Atestado | `S`=Sim `N`=Não |
| SEMATESTCRECHE | String |  | Não Apresentou Atestado | `N`=Não `S`=Sim |
| VLRPENSAO | Float |  | Valor da Pensão |  |
| PERCPENSAO | Float |  | Percentual da Pensão |  |
| DNV | String |  | DNV |  |
| PERCHOMOLOGNET | Float |  | Percentual do Homolognet |  |
| PERCREPASSEPENSIONISTA | Float |  | Percentual de Repasse ao Pensionista |  |
| CODFUNCPENS | Integer |  | Código do Pensionista |  |
| CODPARC | Integer |  | Parceiro Responsável pelo recebimento da Pensão |  |
| REPSALPENSIONISTA | String |  | Repassa Salário Família ao Pensionista | `N`=Não `S`=Sim |
| TIPOPENSAO | String |  | Tipo da Pensão | `B`=Bruto `L`=Líquido `P`=Personalizado `S`=Salário Mínimo |
| CODEVEDESCM | Integer |  | Evento de Desconto - Mensal |  |
| CODEVEDESCD | Integer |  | Evento de Desconto - 13º Salário |  |
| CODEVEDESCF | Integer |  | Evento de Desconto - Férias |  |
| CODEVEDESCI | Integer |  | Evento de Desconto - Férias Indenizadas |  |
| CODEVEDESCU | Integer |  | Evento de Desconto - PLR |  |
| DTFIMPENSAO | Date |  | Referência limite da pensão |  |
| CODEMP | Integer |  | Empresa |  |

## TFPDPEN — Deduções suspensas por dependentes e beneficiários da pensão alimentícia
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDPEN | Integer |  | No único dependente pensão alimentícia |  |
| NUDDE | Integer |  | No. único Dedução |  |
| SEQUENCIA | Integer |  | Beneficiário |  |
| VLRDEPENSUSP | Float |  | Valor da dedução |  |
| CODEMP | Integer |  | Código da empresa |  |
| CODFUNC | Integer |  | Código do funcionário |  |

## TFPDPT — Timeline do DP
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULO | String |  | TITULO |  |
| DESCRICAO | String |  | DESCRICAO |  |
| TIPO | String |  | TIPO |  |
| PKS | String |  | PKS |  |
| DHCRIACAO | DateTime |  | DHCRIACAO |  |
| CODUSU | Integer |  | CODUSU |  |
| ID | Integer |  | ID |  |

## TFPDRTD — Dedução do rendimento tributável relativa a dependentes
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDRTD | Integer |  | NUDRTD |  |
| NUITCR | Integer |  | NUITCR |  |
| NMDEP | String |  | Dependente |  |
| TPREND | String |  | Tipo de rendimento | `11`=11 - Remuneração mensal `12`=12 - 13º salário |
| CPFDEP | String |  | CPF |  |
| VLRDEDUCAO | Float |  | Valor da Dedução |  |

## TFPEBA — Bases de Cálculo
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEVENTOACUM | Integer |  | Evento Acumulador |  |
| CODEVENTOCOMP | Integer |  | Evento Componente |  |
| DTALTER | DateTime |  | Data de atleração |  |

## TFPECL — Eventos de Cálculo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | DateTime |  | DTREF |  |
| TIPOFOL | String |  | TIPOFOL | `S`=Semanal `R`=Rescisão `P`=Pensionista `N`=Normal `L`=Resilição_(+3)_ |
| STATUSFOL | String |  | STATUSFOL | `P`=Pendente `C`=Confirmada `A`=Agendada |
| CODCALC | Integer |  | CODCALC |  |

## TFPELTDEP — Vínculo de Lotação Tributária da Empresa com Departamento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODELTDEP | Integer |  | Número único |  |
| CODEMPLOT | Integer |  | Lotação Tributária da Empresa |  |
| CODDEP | Integer |  | Departamento |  |
| DTINIVINC | Date |  | Início do vínculo |  |
| DTFIMVINC | Date |  | Fim do vínculo |  |

## TFPELTFUNC — Vínculo de Lotação Tributária da Empresa com Funcionário
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODELTFUNC | Integer |  | Número Único |  |
| CODEMPLOT | Integer |  | Lotação Tributária da Empresa |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| DTINIVINC | Date |  | Início do vínculo |  |
| DTFIMVINC | Date |  | Fim do vínculo |  |

## TFPEMP — Empresa Pessoal
Campos: 167

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREGFIS | Integer |  | Reg.Fiscal Apro/Guia |  |
| USADOESOCIAL | String |  | Compõe eSocial | `S`=Sim `N`=Não |
| CONTPCD | String |  | Contratação de PCD | `9`=Obrigado `2`=Exigibilidade suspensa virtude Termo firmado c/ MTE `1`=Dispensado em virtude de processo judicial `0`=Dispensado de acordo com a lei |
| TPAMBESOCIAL | String |  | Ambiente | `P`=Produção `T`=Teste |
| CODPREF | Integer |  | Regra de Cálculo |  |
| NUPROCESSOPCD | Integer |  | Processo Judicial PCD |  |
| DEBSUSESOCIAL | String |  | Possui débitos suspensos no eSocial | `S`=Sim `N`=Não |
| CGCANT | String |  | CNPJ Anterior |  |
| GRUPOESOCIAL | String |  | Grupo do eSocial | `4`=4º Grupo - Entes públicos e organizações internacionais `3`=3ºGrupo-Optantes do Simples,pessoa física(exc.doméstico),prod.rural PF e entid. sem fins lucrativos `2`=2º Grupo - Faturamento 2016 de até R$ 78.000.000,00 não optantes do Simples `1`=1º Grupo - Faturamento 2016 acima de R$ 78.000.000,00 |
| CONTAPR | String |  | Contratação de Aprendiz | `2`=Obrigado `1`=Dispensado em virtude de processo judicial `0`=Dispensado de acordo com a lei |
| SUGEREDATPAG | String |  | Sugerir data de pagamento | `N`=Não `S`=Sim |
| DTINICIOESOCIAL | Date |  | Implantação Primeira Fase E-Social |  |
| TIPDIAPAG | String |  | Tipo Dia Pagamento | `P`=Dia Fixo (quando não útil postergar) `A`=Dia Fixo (quando não útil antecipar) `U`=Dias Úteis |
| DTCARGAINICIAL | Date |  | Implantação Segunda Fase E-Social |  |
| CONTENTED | String |  | Contratação por intermédio de Entidade Educativa | `S`=Sim `N`=Não |
| DIAPAGMENSAL | Integer |  | Mensal |  |
| DTTERCEIRAFASE | Date |  | Implantação Terceira Fase E-Social |  |
| INDENTED | String |  | Inscrição Entidade Educativa | `S`=Sim `N`=Não |
| DIAPAGSEM | Integer |  | Semanal |  |
| DTSESMT | Date |  | Data do SESMT |  |
| NMENTE | String |  | Nome da Entidade Educativa |  |
| DIAPAGQUINZ | Integer |  | Quinzenal 1 |  |
| IMPORTAPONTO | String |  | Realiza Importação Automática | `S`=Sim `N`=Não |
| NUPROCESSOAPR | Integer |  | Processo Judicial Aprendiz |  |
| DIAPAGQUINZ_2 | Integer |  | Quinzenal 2 |  |
| PASTADOPONTO | String |  | Diretório de Origem |  |
| CODCTABCOINT | Integer |  | Conta Bancária Intercâmbio |  |
| PERIODOIMPPONTO | Integer |  | Periodicidade | `2`=Quinzenal `1`=Semanal `0`=Diário |
| NUMCONVINT | Integer |  | Número Convênio para Intercâmbio |  |
| DHULTIMAIMPPTO | Date |  | Data Ultima Execução |  |
| CTAFGTS | Integer |  | Conta do FGTS |  |
| INDETT | String |  | Empresa de Trabalho Temporario | `S`=Sim `N`=Não |
| CATEGFGTS | Integer |  | Categoria FGTS |  |
| NRREGETT | String |  | Número de registro ETT |  |
| MODHOLLERIT | Integer |  | Modelo hollerit |  |
| MODPONTO | Integer |  | Modelo ponto |  |
| REFERENCIA | Date |  | Data Referência |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| EMPDESTINOCTB | Integer |  | Empresa Contabilidade |  |
| DHALTER | DateTime |  | Data de alteração |  |
| ATIVO | String |  | Ativa | `N`=Não `S`=Sim |
| CENTRALIZADORA | String |  | Centralizadora | `N`=Não centraliza `S`=Centralizadora `D`=Centralizada |
| SINDICALIZADA | String |  | Sindicalizada | `N`=Não `S`=Sim |
| ALTEROUEND | String |  | Alterou endereço | `N`=Não `S`=Sim |
| CODEMPMODHOL | Integer |  | Utilizar como padrão Modelos da Empresa |  |
| CTACTBREVERSAO | Integer |  | Conta |  |
| HISTCTBREVERSAO | Integer |  | Histórico |  |
| CODCTACTBREVER13 | Integer |  | Conta |  |
| CODHISTCTBREVER13 | Integer |  | Histórico |  |
| DIAPAGFERIAS | Integer |  | Férias |  |
| EMPDESTINOGRELHA | Integer |  | Empresa para atualização da Grelha Salarial |  |
| PROGALIMTRAB | String |  | Possui PAT? |  |
| PERCSERVICO | Float |  | Serviço Próprio (%) |  |
| PERCCOZINHA | Float |  | Administração de Cozinha (%) |  |
| PERCREFEICAO | Float |  | Refeição Convênio (%) |  |
| PERCTRANSPO | Float |  | Refeição Transportada (%) |  |
| PERCCESTALIM | Float |  | Cesta de Alimento (%) |  |
| PERCALIMCONV | Float |  | Alimentação Convênio (%) |  |
| DTATUAL | Date |  | Data Atual |  |
| MESDISSIDIO | Integer |  | Mês do Dissídio |  |
| CODEMPORG | Integer |  | Código Empresa Organograma |  |
| EMATIVIDADE | String |  | Em Atividade no Ano-Base | `N`=Não `S`=Sim |
| VLRCONFEDERATIVA | Float |  | Contribuição Confederativa |  |
| VLRASSISTENCIAL | Float |  | Contribuição Assistencial |  |
| VLRSINDICAL | Float |  | Contribuição Sindical |  |
| VLRASSOCIATIVA | Float |  | Contribuição Associativa |  |
| DTVIRADA | Date |  | Data da Virada |  |
| CGCSINDPATRONAL | String |  | CNPJ Sindicato Patronal |  |
| ISMATRIZ | String |  | ISMATRIZ |  |
| POSSUIS1000 | String |  | POSSUIS1000 |  |
| PORTE | Integer |  | Porte da Empresa | `4`=4 - Micro Empreendedor Individual `2`=2 - Empresa de Pequeno Porte `1`=1 - Microempresa `3`=3 - Empresa Não Classificada nos Itens Anteriores |
| TIPPONTO | String |  | Tipo de ponto | `S`=Sim `N`=Não |
| PAGAEXTERIOR | String |  | Pagou rendimentos a residentes ou domiciliados no exterior | `N`=Não `S`=Sim |
| DIAAPURAPONTO | Integer |  | Dia de apuração de ponto |  |
| SITUACAOESP | String |  | Situação Especial | `S`=Sim `N`=Não |
| DTEVENTO | Date |  | Data do Evento |  |
| TIPEVENTOESP | Integer |  | Evento | `2`=Saída Definitiva do País `1`=Encerramento ou Espólio |
| CPFRESPCNPJ | String |  | CPF |  |
| SOCIOOSTENSIVO | String |  | Sócio Ostensivo | `N`=Não `S`=Sim |
| DEPOSITOJUD | String |  | É depositário de crédito decorrente de depósito judicial | `N`=Não `S`=Sim |
| CLUBEINVEST | String |  | É instituição administradora/intermediadora de fundo/clube de investimento | `N`=Não `S`=Sim |
| DIRFCPF | String |  | CPF |  |
| DIRFNOME | String |  | Nome |  |
| DIRFDDD | String |  | DDD |  |
| DIRFFONE | String |  | Telefone |  |
| DIRFRAMAL | String |  | Ramal |  |
| DIRFFAX | String |  | Fax |  |
| DIRFEMAIL | String |  | E-mail |  |
| GERAMATRICULA | String |  | Gera Matrícula do Funcionário automaticamente | `N`=Gerar Matrícula manualmente `S`=Gerar Matrícula do Funcionário automaticamente com seu código `A`=Gerar Matrícula do Funcionário automaticamente (Matriz/Filial) |
| INIBEHOLLERIT | String |  | Inibe impressão/visualização/envio e-mail hollerit | `S`=Sim `N`=Não |
| INIBEPONTO | String |  | Inibe impressão/visualização/envio e-mail ponto | `N`=Não `S`=Sim |
| IMPPORTALRH | String |  | Impressora |  |
| CODBCOFIN | Integer |  | Código banco financeiro |  |
| ARQMODEMAIL | String |  | Modelo de e-mail p/ Seleção |  |
| CODCTABCOFIN | Integer |  | Código conta banco financeiro |  |
| CODGRELHA | Integer |  | Código da grelha |  |
| INTEGRAEMPPORTALRH | String |  | Integra o Portal RH | `N`=Não `S`=Sim |
| FERIASINTEGRAL | String |  | Férias integral | `S`=Sim `N`=Não |
| LOGOFOLHA | String |  | Logo da folha |  |
| CONTROLEPONTO | Integer |  | Controle de ponto | `6`=06 - Sistema eletrônico alternativo previsto na Portaria 373/2011 `5`=05 - Sistema não eletrônico alternativo previsto no art.1º da Portaria 373/2011 `4`=04 - Sistema de Registro Eletrônico de Ponto - SREP (Portaria 1.510/2009) `3`=03 - Sistema mecânico `2`=02 - Sistema manual_(+2)_ |
| CODEMPFIN | Integer |  | Empresa Financeiro |  |
| CODNATSALDORET | Integer |  | Código de natureza de saldo |  |
| DTINC_ESOCIAL | Date |  | Data do primeiro envio ao eSocial |  |
| DTULTENV_ESOCIAL | Date |  | Data do último envio ao eSocial |  |
| SIGLAMIN | String |  | Identificação Ministério/Lei |  |
| NROCERTIF | String |  | Número do certificado |  |
| DTEMICERTIF | Date |  | Data de emissão do certificado |  |
| DTVENCCERTIF | Date |  | Data de vencimento do certificado |  |
| NROPROTRENOV | String |  | Número de protocolo de renovação |  |
| DTPROTRENOV | Date |  | Data do protocolo de renovação |  |
| DTDOU | Date |  | Data da Publicação no Diário Oficial |  |
| PAGDOU | Integer |  | Página Publicação no DOU |  |
| NUPROCESSORAT | Integer |  | Processo alteração da RAT |  |
| NUPROCESSOFAP | Integer |  | Processo Alteração da FAP |  |
| CODEMPLOTACAO | Integer |  | Empresa de Lotação |  |
| TIPLOTACAO | Integer |  | Tipo de lotação |  |
| VALIDABASEIMP | String |  | Valida base Importação | `S`=Sim `N`=Não |
| APROVADP | String |  | Aprovação de requisições somente pelo DP? | `S`=Sim `N`=Não |
| INDDESFOLHA | Integer |  | Indicativo Desoneração da Folha | `0`=Não aplicável `1`=Empresa enquadrada nos critérios da legislação vigente |
| NRSIAFI | Integer |  | Número SIAFI |  |
| INDSITPJ | Integer |  | Situação Pessoa Jurídica | `4`=Incorporação `3`=Cisão `2`=Fusão `1`=Extinção `0`=Normal |
| INDRPPS | String |  | Índice RPPS | `S`=Sim `N`=Não |
| PERCSEG | Float |  | Percentual de segurança |  |
| PERMABONOPEC | String |  | Permite requisitar abono pecuniário? | `N`=Não `S`=Sim |
| PERCENTE | Float |  | Porcentagem |  |
| PERMFRACIONARFER | String |  | Permite fracionar férias? | `S`=Sim `N`=Não |
| PERCSUPL | Float |  | Percentual de suplemento |  |
| ENVESOCIAL | String |  | Enviar dados desta empresa para eSocial | `S`=Sim `N`=Não |
| ENVIAEMP | String |  | Envia empresa | `S`=Sim `N`=Não |
| FIMVALESOCIAL | Date |  | Fim da validade do eSocial |  |
| HISTCTBCRATOCOOP | Integer |  | Histórico de Crédito |  |
| HISTCTBDBATOCOOP | Integer |  | Histórico de Débito |  |
| IDEEFR | String |  | Identificador EFR | `S`=Sim `N`=Não |
| IDESUBTETO | Integer |  | Identificador SUBTETO |  |
| IDMAIOR | Integer |  | ID maior |  |
| INDOPTREGELETRON | Integer |  | Índice de optante de registro eletrônico | `1`=1 - Optou pelo registro eletrônico `0`=0 - Não optou pelo registro eletrônico |
| INDSIMPLES | Integer |  | Indicador de Contribuição Substituída | `3`=3 - Contribuição não substituída concomitante com contribuição substituída `2`=2 - Contribuição não substituída `1`=1 - Contribuição Substituída Integralmente `0`=0 - Não se aplica |
| INIVALESOCIAL | Date |  | Início da validade do eSocial |  |
| NUPROCALTOUTENT | Integer |  | Processo alt. outras entidades |  |
| REGIMERETIRRFCX | String |  | Regime de Retenção do IRRF da Folha | `S`=Caixa `N`=Competência |
| VALSUBTETO | Float |  | Valor SUBTETO |  |
| JESPON | String |  | Permite batida de ponto online | `S`=Sim `N`=Não |
| ALIQUOTAFAP | Float |  | Alíquota FAP |  |
| ALIQUOTARAT | Float |  | Alíquota RAT |  |
| CNPJEFR | String |  | CNPJ EFR |  |
| CNPJPROCURADOR | String |  | CNPJ/CPF do Outorgado (Procuração Eletrônica) |  |
| CODCENCUSATOCOOP | Integer |  | Centro de Resultado |  |
| CODINFFISC | Integer |  | Cad. Inform. Fiscal |  |
| CODNATFPAS | Integer |  | Natureza para saldo FPAS |  |
| CODPROJATOCOOP | Integer |  | Projeto |  |
| CPFPRODRURAL | String |  | CPF de produtor rural |  |
| CTACTBCRATOCOOP | Integer |  | Conta de Crédito |  |
| CTACTBDBATOCOOP | Integer |  | Conta de Débito |  |
| PORTALAPONTO | String |  | Exibe Extrato de Ponto no Portal RH? | `S`=Sim `N`=Não |
| PORTALEVOLUCAO | String |  | Exibe Evolução Salarial no Portal RH? | `S`=Sim `N`=Não |
| PORTALPROGFERIAS | String |  | Exibe Programação de Férias no Portal RH? | `S`=Sim `N`=Não |
| APURACOMPETENCIA | DateTime |  | Apuração do DSR para competência |  |
| PERMAPURACOMPET | String |  | Alterar a forma de apuração do DSR/HORISTA para competência | `S`=Sim `N`=Não |
| PORTALALTCARGAHORARIA | String |  | Exibe Requisição de Alteração de Carga Horária. no Portal RH / APP? | `S`=Sim `N`=Não |
| PERMFERIASANTECIP | String |  | Permite Férias Antecipadas | `S`=Sim `N`=Não |
| FAPNAOPUBLICADA | String |  | Estabelecimento com FAP não publicada no eSocial | `S`=Sim `N`=Não |
| INAPTAPINEXIST | String |  | Empresa considerada inapta por inexistência de fato | `S`=Sim `N`=Não |
| BLOQACESSORH | String |  | Bloqueia acesso ao Portal RH a partir da Data de Desligamento | `N`=Não `S`=Sim |
| BLOQACESSOSNK | String |  | Bloqueia acesso ao Sankhya a partir da Data de Desligamento | `N`=Não `S`=Sim |
| BLOQEXIBANIV | String |  | Bloqueia exibição de Aniversariantes | `N`=Não `S`=Sim |
| RECIBOESOCIAL | String |  | RECIBOESOCIAL |  |
| CODEMP | Integer |  | Empresa |  |

## TFPEMPLOT — Lotação Tributária da Empresa
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPLOT | Integer |  | Número Único |  |
| CODLOTACAO | String |  | Código da Lotação |  |
| CODEMP | Integer |  | Empresa |  |
| CODREGFIS | Integer |  | Registro Fiscal |  |
| TIPLOTACAO | Integer |  | Tipo de Lotação |  |
| DTINIVAL | Date |  | Início da validade |  |
| DTFIMVAL | Date |  | Fim da validade |  |

## TFPEP — TABLE TFPEP
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TPEP | Integer |  | Tipo de Proteção | `2`=2 - Equipamento de Proteção Coletiva (EPC) `1`=1 - Equipamento de Proteção Individual (EPI) |
| DSCEP | String |  | Descrição do Equipamento |  |
| EFICEP | String |  | É eficaz na neutralização dos riscos ao trabalhador? | `S`=Sim `N`=Não |
| CAEPI | String |  | Certificado de Aprovação do EPI |  |
| MEDPROTECAO | String |  | Foram implementadas medidas coletiva, optando-se pelo EPI por inviabilidade técnica, insuficiência ou interinidade? | `S`=Sim `N`=Não |
| CONDFUNCTO | String |  | Observadas condições de funcionamento e uso ininterrupto do EPI, ajustada às condições do tempo? | `S`=Sim `N`=Não |
| PRZVALID | String |  | Observado prazo de validade, conforme CA do MTE? | `S`=Sim `N`=Não |
| PERIODICTROCA | String |  | Observada a periodicidade de troca, comprovada mediante recibo assinado pelo usuário em época própria? | `S`=Sim `N`=Não |
| HIGIENIZACAO | String |  | Observada a higienização? | `S`=Sim `N`=Não |
| MANUTENCAO | String |  | Observada a manutenção ? | `S`=Sim `N`=Não |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODEP | Integer |  | Código |  |

## TFPEPI — TABLE TFPEPI
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CAEPI | String |  | Certificado de aprovação |  |
| CODEP | Integer |  | Código Equipamento |  |
| EFICACIAEPI | String |  | É eficaz na neutralização do risco ao trabalhador | `S`=Sim `N`=Não |
| MEDPROTECAO | String |  | Foram implementadas medidas coletiva, optando-se pelo EPI por inviabilidade técnica, insuficiência ou interinidade? | `S`=Sim `N`=Não |
| CONDFUNCTO | String |  | Observadas condições de funcionamento ao longo do tempo? | `S`=Sim `N`=Não |
| PRZVALID | String |  | Observado prazo de validade, conforme CA do MTE? | `S`=Sim `N`=Não |
| PERIODICTROCA | String |  | Observada a periodicidade de troca, comprovada mediante recibo assinado pelo usuário em época própria? | `S`=Sim `N`=Não |
| HIGIENIZACAO | String |  | Observada a higienização? | `S`=Sim `N`=Não |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODAMB | Integer |  | CODAMB |  |
| MANUTENCAO | String |  | Manutenção | `S`=Sim `N`=Não |
| USOININT | String |  | Observado uso ininterrupto ao longo do tempo? | `S`=Sim `N`=Não |
| CODFATRISCO | String |  | CODFATRISCO |  |

## TFPEPIAGNOC — TABLE TFPEPIAGNOC
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEP | Integer |  | Código Equipamento |  |
| CAEPI | String |  | Certificado de aprovação |  |
| EFICACIAEPI | String |  | É eficaz na neutralização do risco ao trabalhador | `S`=Sim `N`=Não |
| MEDPROTECAO | String |  | Foram implementadas medidas coletiva, optando-se pelo EPI por inviabilidade técnica, insuficiência ou interinidade? | `S`=Sim `N`=Não |
| CONDFUNCTO | String |  | Observadas condições de funcionamento ao longo do tempo? | `S`=Sim `N`=Não |
| PRZVALID | String |  | Observado prazo de validade, conforme CA do MTE? | `S`=Sim `N`=Não |
| PERIODICTROCA | String |  | Observada a periodicidade de troca, comprovada mediante recibo assinado pelo usuário em época própria? | `S`=Sim `N`=Não |
| HIGIENIZACAO | String |  | Observada a higienização? | `S`=Sim `N`=Não |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODAMB | Integer |  | CODAMB |  |
| MANUTENCAO | String |  | Manutenção | `S`=Sim `N`=Não |
| USOININT | String |  | Observado uso ininterrupto ao longo do tempo? | `S`=Sim `N`=Não |
| CODAGNOC | String |  | CODAGNOC |  |

## TFPEPR — TABLE TFPEPR
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEVENTO | Integer |  | Evento |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| NUPROCESSO | Integer |  | NUPROCESSO |  |

## TFPEQP — TABLE TFPEQP
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DESCREQP | String |  | Descrição |  |
| MARCA | Integer |  | Marca/Modelo | `3`=Orion 6 - Henry `2`=Control ID - iDClass REP `1`=Henry - Hexa / Hexa Adv. / Prisma SF / Prisma SF Adv. / Compacto S |
| IP | String |  | Endereço IP / DDNS |  |
| PORTA | Integer |  | Porta TCP |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| SERIAL | String |  | Nro Fabricação |  |
| NSR | Integer |  | NSR Próx. Coleta |  |
| AUTH | String |  | Requer autenticação? | `S`=Sim `N`=Não |
| USUARIO | String |  | Usuário |  |
| SENHA | String |  | Senha |  |
| HRVERAO | String |  | HRVERAO |  |
| DTINICHRVERAO | DateTime |  | DTINICHRVERAO |  |
| DTFINALHRVERAO | DateTime |  | DTFINALHRVERAO |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| DATAINI | DateTime |  | DATAINI |  |
| CODEQP | Integer |  | Código |  |

## TFPEST — Dados estagiários
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NATESTAGIO | String |  | Natureza de Estágio | `O`=Obrigatório `N`=Não Obrigatório |
| DTPREVTERM | Date |  | Data Prevista de Término |  |
| AREAATUACAO | String |  | Área de Atuação |  |
| NRAPOL | String |  | Número da Apólice |  |
| VLRBOLSA | Float |  | Valor da Bolsa |  |
| DHALTER | DateTime |  | Data de Alteração |  |
| NMRAZAOINSTENS | String |  | Razão Social da Instituição de Ensino |  |
| CNPJINSTENSINO | String |  | CNPJ da Instituição de Ensino |  |
| CEPINSTENS | String |  | CEP |  |
| CODENDINSTENS | Integer |  | Endereço |  |
| NRLOGRADINSTENS | String |  | Número |  |
| CODBAIINSTENS | Integer |  | Bairro |  |
| CODCIDINSTENS | Integer |  | Cidade |  |
| NMRAZAOAGTINTEG | String |  | Razão Social do Agente de Integração |  |
| CNPJAGTINTEG | String |  | CNPJ do Agente de Integração |  |
| CEPAGTINTEG | String |  | CEP |  |
| CODENDAGTINTEG | Integer |  | Endereço |  |
| NRLOGRADAGTINTEG | String |  | Número |  |
| CODBAIAGTINTEG | Integer |  | Bairro |  |
| CODCIDAGTINTEG | Integer |  | Cidade |  |
| NMSUPERVISOR | String |  | Nome do Supervisor |  |
| CPFSUPERVISOR | String |  | CPF do Supervisor |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODFUNC | Integer |  | Cód. Funcionário |  |
| NIVESTAGIO | String |  | Nível do Estágio | `1`=Fundamental `2`=Médio `3`=Formação Profissional `4`=Superior `8`=Especial_(+1)_ |

## TFPEVE — Eventos
Campos: 105

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCREVENTO | String |  | Descrição |  |
| TIPEVENTO | Integer |  | Tipo | `1`=Provento `0`=Neutro `-1`=Desconto |
| UNIDADE | String |  | Unidade | `Q`=Quantidade `D`=Dias `V`=Valor `H`=Horas |
| DTALTER | DateTime |  | Data de alteracao |  |
| INCSOBREMEDIAS | String |  | Incide sobre médias | `N`=Não incide `E`=Evento de falta `S`=Incide nas médias pelo valor `I`=Incide nas médias pelo índice `C`=Incorpora ao salário |
| PROTEGIDO | String |  | Protegido | `N`=Não `S`=Sim |
| BASEINFREND | String |  | Base informe rendimentos | `B`=Dividendos, bonificações em dinheiro `N`=Não entra no Informe Rendimentos `C`=Informações complementares `A`=Aposentadoria, reserva, reforma. (>=65 anos) `Q`=Dependentes_(+29)_ |
| VLREVENTO | Float |  | Valor do evento |  |
| BASEMARGCONSIG | String |  | Base Margem Consignável | `N`=Não incide `O`=Obrigatório `F`=Facultativo |
| SEQCALCULO | Float |  | Sequência para cálculo |  |
| ADIANTAMENTO | String |  | Adiantamento | `S`=Sim `N`=Não |
| CODFORM | Integer |  | Fórmula |  |
| ACUMULADOR | String |  | Acumulador | `N`=Não `S`=Sim |
| FERIAS | String |  | É Folha de Férias | `N`=Não `S`=Sim |
| BASERAIS | String |  | Base da rais | `N`=Não `S`=Sim |
| IMPHOLLERIT | String |  | Imprime hollerit | `N`=Não imprime em nenhum hollerit `M`=Somente folha normal e rescisão `F`=Somente no recibo de férias `S`=Em todos os hollerits |
| DECTERC | String |  | É Folha de Décimo Terceiro? | `N`=Não `S`=Sim |
| TEMCOMPLEMENTO | String |  | Tem Complementar | `S`=Sim `N`=Não |
| BASELIQUIDO | String |  | Base Liquida | `N`=Não `S`=Sim |
| INDICE | Float |  | Índice |  |
| INDICEADMEDIAS | Float |  | INDICEADMEDIAS |  |
| FOLHA | String |  | É Folha Normal? | `N`=Não `S`=Sim |
| RESCISAO | String |  | É Folha de Rescisão? | `N`=Não `S`=Sim |
| SEMANAL | String |  | É Folha Semanal? | `N`=Não `S`=Sim |
| REGCALCULO | String |  | Reg. Cálculo |  |
| DOCUMENTACAO | String |  | Documentação |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| PENSAO | String |  | Pensão |  |
| PROVISAOFIN | Integer |  | Como Participa de Provisão do Financeiro |  |
| INCORPORA | String |  | Incorpora |  |
| COMPLEMENTORESC | String |  | Complemento Resilição |  |
| CODEVERESILICAO | Integer |  | Cód. Eve. Resilição |  |
| RESILICAO | String |  | Resilição |  |
| ATIVO | String |  | ATIVO |  |
| SANKHYA | String |  | SANKHYA |  |
| IDENTIFICACAO | Integer |  | IDENTIFICACAO |  |
| PROVIFERIAS | String |  | PROVIFERIAS |  |
| PROVIDECTERSAL | String |  | PROVIDECTERSAL |  |
| GRRFMES | String |  | Mês da Rescisão |  |
| GRRFMESANTERIOR | String |  | Mês Anterior à Rescisão |  |
| GRRFINDENIZACAO | String |  | Indenizações |  |
| GRUPOMEDIAS | String |  | GRUPOMEDIAS |  |
| CODINCCP | String |  | CODINCCP |  |
| CODINCIRRF | String |  | CODINCIRRF |  |
| CODINCFGTS | String |  | CODINCFGTS |  |
| CODINCSIND | String |  | CODINCSIND |  |
| GRUPOEVENTO | Integer |  | Grupo | `9`=13º `8`=Rescisão `7`=Férias `6`=Sócio `5`=Prestador de Serviços_(+7)_ |
| CHECKSUM | String |  | Soma de Verificação |  |
| EVENTORRA | String |  | É Evento de RRA? | `N`=Não `S`=Sim |
| CODEVERRACPL | Integer |  | Evento de Diferença - RRA |  |
| CRIAEVTATUALIZACAO | String |  | Cria evento na atualização |  |
| CARACTERISTICA | String |  | CARACTERISTICA |  |
| BASEAUXILIAR | String |  | Base auxiliar | `N`=Não `S`=Sim |
| INFCOMPLRAIS1 | Float |  | INFCOMPLRAIS1 |  |
| CODOUTRASMTE | Float |  | CODOUTRASMTE |  |
| CODCRIRATEIO | Float |  | Cód. Critério de Rateio |  |
| ATIVOW | String |  | ATIVOW |  |
| CODMOEDA | Float |  | Cód. Moeda |  |
| USACODMOEDA | String |  | Usa código de moeda | `N`=Não `S`=Sim |
| IGPMCOMISSAO | Integer |  | IGPMCOMISSAO |  |
| CODEVEFLRES | String |  | CODEVEFLRES |  |
| INPCCOMISSAO | Integer |  | INPCCOMISSAO |  |
| EVENTOFALTA | String |  | É evento de falta? |  |
| EVENTODSR | String |  | É evento de DSR? |  |
| UTSALBASEARED | String |  | UTSALBASEARED |  |
| CONSPROGFER | String |  | CONSPROGFER |  |
| DIASCPROGFER | Integer |  | DIASCPROGFER |  |
| DTINATAPARDE | Date |  | DTINATAPARDE |  |
| USALEI10820 | String |  | Usa lei 10820 | `N`=Não `S`=Sim |
| CRIADOW | String |  | Criado pelo sistema |  |
| HASH | String |  | Hash do cadastro padrão |  |
| DTATUALIZACAO | Date |  | Data de atualização pelo sistema |  |
| AVULSO | String |  | Avulso | `N`=Não `S`=Sim |
| CODEVENTO | Integer |  | Código do evento |  |
| CODEVECORRELATO | Integer |  | CODEVECORRELATO |  |
| DSCSALVAR | String |  | DSCSALVAR |  |
| INTEGRACTB | String |  | INTEGRACTB |  |
| BASESEFIP | Integer |  | Base SEFIP | `2`=Base SEFIP 13º salário `1`=Base SEFIP `0`=Não é base para SEFIP |
| CODEVECOMPLEMENTO | Integer |  | CODEVECOMPLEMENTO |  |
| CODNATRUBRICA | String |  | CODNATRUBRICA |  |
| COMPLEMENTAR | String |  | COMPLEMENTAR |  |
| CONTRIBSIND | String |  | CONTRIBSIND |  |
| FGTS | String |  | FGTS |  |
| FGTSDECTERCEIRO | String |  | FGTSDECTERCEIRO |  |
| FGTSRESCISAO | String |  | FGTSRESCISAO |  |
| FGTSSEFIP | String |  | FGTSSEFIP |  |
| INFCOMPLRAIS2 | Float |  | INFCOMPLRAIS2 |  |
| INSSSEFIP | String |  | INSSSEFIP |  |
| ISS | String |  | ISS |  |
| PENSAOSALBRUTO | String |  | PENSAOSALBRUTO |  |
| PENSAOSALLIQUIDO | String |  | PENSAOSALLIQUIDO |  |
| PENSAOSALMINIMO | String |  | PENSAOSALMINIMO |  |
| PLR | String |  | PLR |  |
| REFLEXIVOS | String |  | REFLEXIVOS |  |
| TIPOINSS | Integer |  | INSS | `9`=INSS Férias Competência `8`=INSS Adiantamento Férias `7`=INSS Sal. Maternidade 13º `6`=INSS Sal. Maternidade `5`=INSS Transp. Rodoviário_(+5)_ |
| TIPOIRRF | Integer |  | IRRF | `8`=IRRF RRA `7`=IRRF PLR `6`=IRRF Férias `5`=IRRF Transp. Rodoviário `4`=IRRF Prest. Serviços_(+4)_ |
| USADOESOCIAL | String |  | USADOESOCIAL |  |
| INDENIZACAOAPI | String |  | Evento de indenização integrante do Aviso Prévio Indenizado | `S`=Sim `N`=Não |
| CODINCPIS | String |  | Código incidencia pis |  |
| PIS | String |  | PIS |  |
| PISDECTERCEIRO | String |  | PIS 13° |  |
| INTERMITENTE | String |  | INTERMITENTE |  |
| CODEVEFLFER | String |  | CODEVEFLFER |  |

## TFPEXA — Exames Periódicos
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| SEQEXAME | Integer |  | Sequência do Exame |  |
| CODFUNC | Integer |  | Funcionário |  |
| DESCREXAME | String |  | Descrição Exame |  |
| DTEXAME | Date |  | Data do exame |  |
| CNPJLAB | String |  | CNPJ do laboratório |  |
| CODUSU | Integer |  | Código Usuário |  |
| CODEXAME | String |  | Cód. do exame |  |
| DHALTER | DateTime |  | Data de Alteração |  |
| DTVENCIMENTO | DateTime |  | Data Vencimento |  |
| NMMED | String |  | Nome do médico |  |
| CRM | String |  | Número do CRM |  |
| UFCRM | String |  | UF do CRM |  |
| TOXICOLOGICO | String |  | Toxicológico |  |
| CNPJBASE36 | String |  | Prefixo Cód. Exame |  |
| SERIALSEQ | String |  | Serial da Sequência |  |
| CODEXAMEESOCIAL | Integer |  | Cód. Exame e-Social |  |
| ORDEXAME | Integer |  | Ordem do Exame |  |
| INDRESULT | Integer |  | Resultado Indiciativo |  |
| DIASVENC | Integer |  | Dia do Vencimento |  |
| DESCREXAMEESOCIAL | String |  | Descrição Exame e-Social |  |
| RECIBOESOCIAL | String |  | Nro. Recibo eSocial |  |
| NUASO | Integer |  | Número ASO |  |

## TFPFAI — FP Tabela de Faixas
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTAB | String |  | Descrição da Tabela |  |
| TIPOTAB | String |  | Tipo da tabela |  |
| REFERENCIA | Date |  | Referência |  |
| LIMFAIXA | Float |  | Limite da faixa |  |
| VALOR1 | Float |  | Valor 1 |  |
| VALOR2 | Float |  | Valor 2 |  |
| VALOR3 | Float |  | Valor 3 |  |
| VALOR4 | Float |  | Valor 4 |  |
| VALOR5 | Float |  | Valor 5 |  |
| VALOR6 | Float |  | Valor 6 |  |
| DTALTER | DateTime |  | Data de alteração |  |
| VALOR7 | Float |  | Valor 7 |  |
| VALOR8 | Float |  | Valor 8 |  |
| VALOR9 | Float |  | Valor 9 |  |
| VALOR10 | Float |  | Valor 10 |  |
| VALOR11 | Float |  | Valor 11 |  |
| CODTAB | Integer |  | Código da Tabela |  |

## TFPFAIP — Tabela de Faixas - Identificação Padrão
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDENTIFICACAO | String |  | Identificação | `INSS`=Tabela de INSS `IRRF`=Tabela de IRRF `IRRFPLR`=Tabela de IRRF para PLR `NENHUMA`=Sem identificação `SALARIOFAMILIA`=Tabela de Salário Família_(+1)_ |
| CODTAB | Integer |  | Código da Tabela de Faixa |  |
| EXECUCAO | String |  | Execução | `A`=Automática `M`=Manual |
| DTINCLUSAO | DateTime |  | Data de Inclusão |  |
| ID | Integer |  | Código de Identificação |  |

## TFPFAL — Faltas
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| DTFALTA | DateTime |  | Data da Falta |  |
| TIPREG | Integer |  | Tipo de Registro | `1`=Restituição `-1`=Falta |
| CODHIS | Integer |  | Código do Histórico |  |
| NUFALTA | Integer |  | Nro Lançamento |  |
| DESCRHISTOCOR | String |  | Descrição do Histórico |  |
| DTALTER | DateTime |  | Data da Alteração |  |
| CODUSU | Integer |  | Código Usuário |  |
| ORIGEM | String |  | Origem |  |
| PERDEDSR | String |  | Perde DSR | `S`=Marcado `N`=Desmarcado |
| SUSPDISCIPLINAR | String |  | Suspensão Disciplinar | `S`=Marcado `N`=Desmarcado |
| HORAS | Float |  | Quantidade de Horas |  |
| CODEMP | Integer |  | Empresa |  |

## TFPFATR — TABLE TFPFATR
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TECMEDICAO | String |  | Técnica Medição da intensidade ou concentração |  |
| UTILIZAEPI | Integer |  | Utilização de EPI | `2`=Utilizado `1`=Não utilizado `0`=Não se aplica |
| UTILIZAEPC | Integer |  | Utilização de EPC | `2`=Implementa `1`=Não implementa `0`=Não se aplica |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| TIPOFATOR | Integer |  | TIPOFATOR |  |
| CODAMB | Integer |  | CODAMB |  |
| TPAVAL | Integer |  | Tipo de avaliação | `2`=2 - Critério qualitativo `1`=1 - Critério quantitativo |
| UNMED | Integer |  | Unidade de medida intensidade ou concentração | `9`=09 - Metro por segundo ao quadrado (m/s2) `8`=08 - Quilograma-força por centímetro quadrado (kgf/cm2) `7`=07 - Sievert (Sv) `6`=06 - Gray (Gy) `5`=05 - Quilocaloria por hora (kcal/h)_(+42)_ |
| INSALUBRIDADE | String |  | Insalubridade | `S`=Sim `N`=Não |
| PERICULOSIDADE | String |  | Periculosidade | `S`=Sim `N`=Não |
| HIERUSO | String |  | Usa Hierarquia | `S`=Sim `N`=Não |
| APOSENTESP | String |  | Aposentadoria Especial | `S`=Sim `N`=Não |
| LIMTOT | Float |  | Limite de Tolerância |  |
| EFICEPC | String |  | Os EPCs são eficazes na neutralização dos riscos? | `S`=Sim `N`=Não |
| INTCONC | Float |  | Intensidade ou concentração da exposição |  |
| DSCFATRISC | String |  | Descrição complementar do Fator de Risco |  |
| CODFATRISCO | String |  | Cód. Fator de Risco |  |

## TFPFBE — Funcionario Benefício
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBEN | Integer |  | Código Benefício |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| NOMEFUNC | String |  | Nome Funcionário |  |

## TFPFCA — Tabela de Funções para Cargos
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNCAO | Integer |  | Função |  |
| CODCARGO | Integer |  | Cargo |  |

## TFPFCO — Funções
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRFUNCAO | String |  | Descrição |  |
| CODCBO | Integer |  | CBO |  |
| DTALTER | DateTime |  | Data de alteração |  |
| PODESUPEMP | String |  | Pode ser supervisor de turma | `N`=Não `S`=Sim |
| PODEENCEMP | String |  | Pode ser encarregado de turma | `N`=Não `S`=Sim |
| INCAPONT | String |  | Incluir no apontamento | `S`=Sim `N`=Não |
| CODFUNCAO | Integer |  | Código da função |  |

## TFPFCR — Função e Curso
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCUR | String |  | Código Curso |  |
| CODFUNCAO | Integer |  | Função e Curso |  |
| PERCAPROV | Integer |  | Percentual de Aproveitamento |  |
| PERCREVISAO | Integer |  | Percentual de Revisão |  |

## TFPFCTI — TABLE TFPFCTI
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | Código Funcionário |  |
| DTINICIO | Date |  | Início |  |
| DTFIM | Date |  | Fim |  |
| COMPARECEU | String |  | Compareceu ao trabalho | `S`=Sim `N`=Não |
| TIPLOCALTRAB | String |  | Local de prestação do trabalho |  |
| DTPREVPGTO | Date |  | Previsão de Pagamento |  |
| CODCONV | Integer |  | CODCONV |  |

## TFPFDEF — Dados das deficiências dos funcionários
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Código Empresa |  |
| CODFUNC | Integer |  | Código Funcionário |  |
| TIPODEFICIENCIA | Integer |  | Deficiência | `6`=Reabilitado `5`=Intelectual `4`=Mental `3`=Auditiva `2`=Visual_(+1)_ |

## TFPFER — Tabela de Férias
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DTINIAQUI | Date |  | Data Inicial do Período Aquisitivo |  |
| DTFINAQUI | Date |  | Data Final do Período Aquisitivo |  |
| SALDODIAS | Integer |  | Saldo de Dias de Férias |  |
| DTPREVISTA | Date |  | Data Prevista das Férias |  |
| DTSAIDA | Date |  | Data de Saída das Férias |  |
| FALTPER | Integer |  | Faltas no Período Aquisitivo |  |
| ABONOPEC | Integer |  | Dias de Abono Pecuniário |  |
| NUMDIASFER | Integer |  | Quantidade de Dias de Férias |  |
| ADIANTA13SAL | String |  | Adianta 13º Salário | `N`=Não `S`=Sim |
| ATUALFERGOZ | String |  | Atualiza Férias Gozadas | `N`=Não `S`=Sim |
| ABONOINICIO | String |  | Dias de Abono no Início das Férias | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Data de Alteração |  |
| QTDPARCELAS | Integer |  | Quantidade de Parcelas do Empréstimo |  |
| NUMDIASLICREM | Integer |  | Dias de Licença Remunerada |  |
| NUMDIASFERCOL | Integer |  | Dias férias coletivas |  |
| NUOCOR | Integer |  | Número da Ocorrência |  |
| REFERENCIA | Date |  | Referência das Férias |  |
| DIGITADO | String |  | Digitado Manualmente | `N`=Não `S`=Sim |
| APROVADO | String |  | Requisição Aprovada | `N`=Não `S`=Sim |
| QTDDIASSOLFERIAS | Integer |  | Dias de Férias Solicitados |  |
| DTLIMGOZFER | Date |  | Data Limite para Gozo de Férias |  |
| PERQUITADO | String |  | Período Aquisitivo Quitado | `N`=Não `S`=Sim |
| CODFERVINC | Integer |  | Código de Vinculação de Dois Cálculos |  |
| NUMDIASFERREAL | Float |  | Dias de Férias Real |  |
| NUMDIASLICREMREAL | Float |  | Dias de Licença Remunerada Real |  |
| DTINTERROMPEFER | Date |  | Data de interrpção das férias] |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cód.Funcionário |  |

## TFPFGHT — Fila para geração do histórico de alterações do trabalhador
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHINC | DateTime |  | Data e hora de inclusão |  |
| NOMETAB | String |  | Nome da tabela de origem da alteração |  |
| CHAVE | C |  | Chave do registro que gerou a alteração |  |
| DTESOCIAL | Date |  | Data da alteração |  |
| TIPO | String |  | Tipo do gatilho que incluiu o item na fila | `A`=Alteração `E`=Exclusão `I`=Inclusão |
| EVENTO | String |  | Evento afetado pela alteração |  |
| CAMPOS | C |  | Lista de campos alterados |  |
| SITUACAO | String |  | Situação | `E`=Erro `P`=Pendente |
| QTDTENTATIVAPROC | Integer |  | Quantidade de tentativas de processamento |  |

## TFPFHO — Tabela de carga horária histórica
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINIESCALA | Date |  | Data de Inicio |  |
| DTFOLGA | Date |  | Data da Folga |  |
| TIPCONTROLE | String |  | Tipo controle | `C`=Carga horária `E`=Escala |
| CODCARGAHOR | Integer |  | Carga Horária |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cód.Funcionário |  |
| DHALTER | DateTime |  | Data |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TFPFIN — Cadastro de Integração com Financeiro
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCENCUS | Integer |  | Cod. Centro Resultado |  |
| CODCTABCOINT | Integer |  | conta banco |  |
| CODNAT | Integer |  | codigo natureza |  |
| CODPARC | Integer |  | cód. Parceiro |  |
| CODPROJ | Integer |  | codigo projeto |  |
| CODTFPFIN | Integer |  | cód. tfpfin |  |
| CODTIPOPER | Integer |  | cód top. |  |
| CODTIPTIT | Integer |  | tipo titulo |  |
| DHALTER | Date |  | data top |  |
| HISTORICO | String |  | hitorico |  |
| TIPOMARCCH | String |  | tipo marc. |  |

## TFPFIS — Registro fiscal
Campos: 53

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODCID | Integer |  | Cidade |  |
| CGCOUCEI | String |  | Tipo CNPJ/CEI | `E`=CEI `C`=CNPJ `F`=CNO `A`=CAEPF |
| CGC_CEI | String |  | CNPJ/CEI |  |
| ATIVIBGE | Integer |  | CNAE/IBGE |  |
| OBRAPROPRIA | String |  | Obra Própria? | `N`=Não `S`=Sim |
| AD_CEI | String |  | AD_CEI |  |
| ATIVIRF | Integer |  | IRF |  |
| CNPJRESP | String |  | CNPJ Responsável |  |
| ATIVINSS | Integer |  | Cód. FPAS |  |
| CODGRPS | Integer |  | INSS Terceiros |  |
| CODSAT | Integer |  | SAT |  |
| CODPAGGPS | Integer |  | GPS |  |
| RAT15 | Float |  | 15 Anos |  |
| RAT20 | Float |  | 20 Anos |  |
| RAT25 | Float |  | 25 Anos |  |
| OPTSIMPLES | Integer |  | Código das opções pelo Simples | `1`=1 - Não Optante `2`=2 - Optante `5`=5 - Não Optante Empresa Com Liminar Impetrada Para Não Recolhimento da Contribuição Social - LC n.11 `3`=3 - Optante com faturamento anual superior a R$ 1.200.000,00 `6`=6 - Optante com faturamento anual superior a R$ 1.200.000,00 e Empresa Com Liminar Impetrada Para Nã_(+1)_ |
| INDCONTSIMPLES | Integer |  | Indicador de contribuição Simples Nacional | `3`=3 - Contribuição não substituída concomitante com contribuição substituída `2`=2 - Contribuição não substituída `1`=1 - Contribuição Substituída Integralmente |
| INDSUBSTPATR | Integer |  | Indicativo de substituição da Contribuição Previd. Patronal | `2`=2 - Parcialmente substituída `1`=1 - Integralmente substituída |
| TPCAEPF | String |  | Tipo de CAEPF | `3`=Segurado Especial `2`=Produtor Rural `1`=Contribuinte Individual |
| TAXAGRPS | Float |  | Taxa Terceiros - INSS |  |
| PERCINSS | Float |  | Percentual de INSS |  |
| TAXASEG | Float |  | Taxa de seguro |  |
| PERPAGTOFGTS | Float |  | Percentual FGTS |  |
| PERFGTSMENOR | Float |  | Percentual do FGTS para Menor Aprendiz |  |
| PERCISEFIL | Float |  | Percentual Isenção Filantropia |  |
| FATORFAP | Float |  | Fator Acidentário de Prevenção (FAP) |  |
| ISSAUTONOMO | Integer |  | ISS Autônomo-Responsável pela retenção | `2`=2 - Empresa Tomadora `1`=1 - Prestador de serviço |
| PERCRECBRUTAINSS | Float |  | Percentual da  Receita Bruta para INSS |  |
| VLRINSSRECBRUTA | Float |  | Valor do INSS da Receita Bruta |  |
| FATORMES | Float |  | Fator Mês |  |
| PERCRECBRUTAINSS13 | Float |  | Percentual da Receita Bruta para INSS |  |
| PERCINSSPATRONAL | Float |  | Percentual de INSS |  |
| DTALTER | Date |  | Referência do Enquadramento |  |
| VLRINSSRECBRUTA13 | Float |  | Valor do INSS da Receita Bruta |  |
| FATOR13 | Float |  | Fator 13º |  |
| CODRECOLHIMENTO | Integer |  | Código de  Recolhimento |  |
| SIMPLES | String |  | Optante pelo Simples | `S`=Sim `N`=Não |
| DTENQUADRAMENTO | Date |  | Data Enquadramento |  |
| CALCINSSEMPFUNC | String |  | INSS Emp. Func | `S`=Sim `N`=Não |
| CALCINSSEMPINDIV | String |  | INSS Emp. C. Indiv. | `S`=Sim `N`=Não |
| PERENCGER | Float |  | PERENCGER |  |
| CTAEVENTOS | String |  | CTAEVENTOS |  |
| PERFGTRESCISAO | Float |  | Percentual Fundo Garantia Rescisão |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| PERFGTSCVA | Float |  | Percentual do FGTS Verde Amarelo |  |
| PROVISIONAREVENTOSMEDIA | String |  | Provisionar Eventos pela Média | `S`=Sim `N`=Não |
| SALMINVIGE | Float |  | Salário mínimo vigente |  |
| BAIXAFERIASANTECIPADAS | String |  | Em caso de Férias Antecipadas, realizar a baixa antecipada | `S`=Sim `N`=Não |
| ISEMPRESACONTRIBUINTE | String |  | Empresa contribuinte | `S`=Sim `N`=Não |
| PERCPISFOLHA | Float |  | Alíquota |  |
| CODRECEITASOBFOLHA | Integer |  | Cód. da Receita |  |
| CODREGFIS | Integer |  | Cód.Registro |  |

## TFPFOL — FP Eventos da Folha
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUFIN | Integer |  | NUFIN |  |
| NUOCOR | Integer |  | NUOCOR |  |
| REFERENCIAORIG | DateTime |  | REFERENCIAORIG |  |
| TIPFOLHAORIG | String |  | TIPFOLHAORIG |  |
| SEQUENCIAORIG | Integer |  | SEQUENCIAORIG |  |
| CODEVENTOORIG | Integer |  | CODEVENTOORIG |  |
| VLRORIGINAL | Float |  | VLRORIGINAL |  |
| INDORIGINAL | Float |  | INDORIGINAL |  |
| DHALTER | DateTime |  | DHALTER |  |
| DIGITADO | String |  | DIGITADO |  |
| CODUSU | Integer |  | CODUSU |  |
| PROTEGIDO | String |  | PROTEGIDO |  |
| USADOESOCIAL | String |  | USADOESOCIAL |  |
| EHCOMPLEMENTAR | String |  | É COMPLEMENTAR | `N`=Não `S`=Sim |
| CODMOV | Integer |  | Código Movimento |  |
| CODMOVORIG | Integer |  | Código Movimento Origem |  |
| CODEMP | Integer |  | Empresa |  |
| CODEVENTO | Integer |  | Evento |  |
| CODFUNC | Integer |  | Funcionário |  |
| INDICE | Float |  | Índice |  |
| OBS | String |  | Observação |  |
| PRAZO | Integer |  | Prazo |  |
| REFERENCIA | DateTime |  | Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPEVENTO | Integer |  | Tipo de evento |  |
| TIPFOLHA | String |  | Tipo de folha | `L`=Resilição `A`=Adiantamento `P`=Pensionista `R`=Rescisão `S`=Semanal_(+3)_ |
| UNIDADE | String |  | Unidade |  |
| VLRCALCULO | Float |  | Valor do cálculo |  |
| VLREVENTO | Float |  | Valor do evento |  |
| SEQROE | Integer |  | SEQROE |  |
| CODPARCPENS | Integer |  | ParceiroPensao |  |
| NROINFODESCFOL | Integer |  | Informação do empréstimo em folha |  |

## TFPFOLTESTE — TABLE TFPFOLTESTE
Campos: 30

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| VLREVENTO | Float |  | VLREVENTO |  |
| INDICE | Float |  | INDICE |  |
| UNIDADE | String |  | UNIDADE |  |
| PRAZO | Integer |  | PRAZO |  |
| VLRCALCULO | Float |  | VLRCALCULO |  |
| OBS | String |  | OBS |  |
| NUFIN | Integer |  | NUFIN |  |
| TIPEVENTO | Integer |  | TIPEVENTO |  |
| NUOCOR | Integer |  | NUOCOR |  |
| REFERENCIAORIG | DateTime |  | REFERENCIAORIG |  |
| TIPFOLHAORIG | String |  | TIPFOLHAORIG |  |
| SEQUENCIAORIG | Integer |  | SEQUENCIAORIG |  |
| CODEVENTOORIG | Integer |  | CODEVENTOORIG |  |
| VLRORIGINAL | Float |  | VLRORIGINAL |  |
| DHALTER | DateTime |  | DHALTER |  |
| INDORIGINAL | Float |  | INDORIGINAL |  |
| DIGITADO | String |  | DIGITADO |  |
| CODUSU | Integer |  | CODUSU |  |
| PROTEGIDO | String |  | PROTEGIDO |  |
| USADOESOCIAL | String |  | USADOESOCIAL |  |
| EHCOMPLEMENTAR | String |  | É COMPLEMENTAR | `N`=Não `S`=Sim |
| SEQROE | Integer |  | SEQROE |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |
| NROINFODESCFOL | Integer |  | Informação do empréstimo em folha |  |
| CODPARCPENS | Integer |  | ParceiroPensao |  |

## TFPFOR — FP Fórmulas de Cálculo
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CODFORM | Integer |  | Código |  |
| CODFORMIND | String |  | Cód.Fórmula IND |  |
| DESCRFORM | String |  | Descrição |  |
| DTALTER | DateTime |  | Data de alteração |  |
| FORMULA | String |  | Fórmula |  |
| FORMULANTERIOR | String |  | Fórmula anterior |  |
| SANKHYA | String |  | SANKHYA | `S`=Sim `N`=Não |

## TFPFRE — TABLE TFPFRE
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREINT | Integer |  | Código da Reintegração |  |
| DTREFERENCIA | Date |  | Referência da Reintegração |  |
| DTRETORNO | Date |  | Data de Retorno |  |
| DTDEM | Date |  | Data do Desligamento |  |
| AFASTFGTS | String |  | Motivo do Afastamento para FGTS |  |
| TIPFOLHA | String |  | Tipo de Folha |  |
| SALLIQ | Float |  | Salário Líquido |  |
| SALBRUTO | Float |  | Salário Bruto |  |
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |

## TFPFSU — Eventos da Folha Suplementar
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFERENCIA | Date |  | REFERENCIA |  |
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TIPFOLHA | String |  | TIPFOLHA |  |
| SEQFOLHA | Integer |  | SEQFOLHA |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TIPEVENTO | Integer |  | TIPEVENTO |  |
| VLREVENTO | Float |  | VLREVENTO |  |
| INDICE | Float |  | INDICE |  |
| UNIDADE | String |  | UNIDADE |  |
| PRAZO | Integer |  | PRAZO |  |
| VLRCALCULO | Float |  | VLRCALCULO |  |
| OBS | String |  | OBS |  |
| NUFIN | Integer |  | NUFIN |  |
| NUOCOR | Integer |  | NUOCOR |  |
| REFERENCIAORIG | Date |  | REFERENCIAORIG |  |
| TIPFOLHAORIG | String |  | TIPFOLHAORIG |  |
| SEQUENCIAORIG | Integer |  | SEQUENCIAORIG |  |
| CODEVENTOORIG | Integer |  | CODEVENTOORIG |  |
| INSCONSIG | String |  | INSCONSIG |  |
| NRCONTR | String |  | NRCONTR |  |
| CODFUNCORIG | Integer |  | CODFUNCORIG |  |
| CODEMPORIG | Integer |  | CODEMPORIG |  |
| SEQROE | Integer |  | SEQROE |  |
| NROINFODESCFOL | Integer |  | NROINFODESCFOL |  |
| CODMOV | Integer |  | CODMOV |  |

## TFPFTR — TABLE TFPFTR
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRFATRISCO | String |  | DESCRFATRISCO |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODFATRISCO | String |  | CODFATRISCO |  |

## TFPFTRC — Treinamento e Capacitação Esocial
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cód.Funcionário |  |
| CODTREICAP | Integer |  | Código do Treinamento/Capacitação no eSocial |  |
| DHALTER | Date |  | Data de Alteracao |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TFPFUN — Funcionários
Campos: 358

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Código |  |
| NOMEFUNC | String |  | Nome |  |
| CODEMP | Integer |  | Empresa |  |
| MATRICULA | Integer |  | Matrícula |  |
| SITUACAO | String |  | Situação | `1`=Atividade normal `8`=Transferido `0`=Demitido `5`=Afastado por licença maternidade `2`=Afastado sem remuneração_(+5)_ |
| SITUACAOANT | String |  | Situação Anterior | `0`=Demitido `1`=Atividade normal `2`=Afastado sem remuneração `3`=Afastado por acidente de trabalho `4`=Afastado para serviço militar_(+5)_ |
| IMAGEM | Boolean |  | Imagem |  |
| DEPENDCONVMED | Integer |  | Quantidade de dependentes de convênio médico |  |
| SINDICALIZADO | String |  | Filiado ao Sindicato de Classe | `N`=Não `S`=Sim |
| AFASTFGTSANT | String |  | AFASTFGTSANT |  |
| AFASTRAISANT | Integer |  | AFASTRAISANT |  |
| CAUSAAFASTANT | Integer |  | CAUSAAFASTANT |  |
| DTSENTPROCTRAB | Date |  | DTSENTPROCTRAB |  |
| MOTDESLIGESOCIALANT | String |  | MOTDESLIGESOCIALANT |  |
| MOTDESLIGESOCIAL | String |  | Motivo de desligamento E-Social |  |
| NRPROCTRABDESLIG | String |  | Nº Processo Trabalhista (desligamento) |  |
| TRAVESTITRANSEXUAL | String |  | Travesti ou Transexual? | `N`=Não `S`=Sim |
| DSCATIVDES | String |  | Descrição Atividades |  |
| DTVENCEXP1OR | Date |  | DTVENCEXP1OR |  |
| DTVENCEXP2OR | Date |  | DTVENCEXP2OR |  |
| IDCONSIG | String |  | ID Consignado | `S`=Sim `N`=Não |
| INSCONSIG | String |  | Matrícula consignatária |  |
| NMSOCIAL | String |  | Nome Social |  |
| NRCONTR | String |  | Contrato Consig.FGTS |  |
| NUPROCESSOJUD | Integer |  | Nro. Processo Jurídico |  |
| NUPROCESSOTRAB | Integer |  | Nro. Processo Trabalhista |  |
| NUREQUISICAO | Integer |  | Nro. Requisição |  |
| SALAJUSTADOSIND | Float |  | Salário ajustado Sindicato |  |
| SALBASEANTERIOR | Float |  | Salário Base Anterior |  |
| CAGEDADM | String |  | Gerou CAGED | `S`=Sim `N`=Não |
| CODCONVENIO | Integer |  | Cód. Convênio |  |
| CODMADDEM | Integer |  | Motivos de Admissão/Demissão |  |
| DTDEMJUD | Date |  | Data demissão (Decisão Judicial) |  |
| HORASSEMCPU | Float |  | Qtd Horas Semanais sem redução |  |
| INDADMISSAOANT | Integer |  | Indicativo de Admissão (Anterior à decisão judicial) |  |
| NRPROCTRABANT | String |  | N° do processo p/ admissão por decisão judicial (Anterior) |  |
| OBSERVACAOMP | String |  | Observação MP |  |
| REPLIDER | String |  | Substituto de Líder | `N`=Não `S`=Sim |
| SALBASECPU | Float |  | Salário Base sem redução |  |
| DEPENDSALFAM | Integer |  | Quantidade de dependentes de salário família |  |
| DTNASC | Date |  | Data de Nascimento |  |
| APRENDCONTRIND | String |  | Contratação Indireta de Aprendiz | `N`=Não `S`=Sim |
| CODTPRJUD | Integer |  | Tipo de Rescisão (Decisão Judicial) |  |
| MATANOTJUD | String |  | Matrícula Anotação Judicial |  |
| PVD | String |  | Programa de Demissão Voluntária | `N`=Não `S`=Sim |
| SEXO | String |  | Sexo | `M`=Masculino `F`=Feminino |
| TPINSCAPREND | Integer |  | Tipo de Inscrição | `1`=1 - CNPJ `2`=2 - CPF |
| RACAFUNCIONARIO | Integer |  | Raça/Etnia | `4`=Preta `0`=Indígena `8`=Parda `2`=Branca `6`=Amarela_(+1)_ |
| IDENTIDADEGENERO | String |  | Identidade de Gênero | `C`=Cisgênero `N`=Não-binário `T`=Transgênero `U`=Não informado |
| NRINSCAPREND | String |  | Número de Inscrição |  |
| ORIENTACAOSEXUAL | String |  | Orientação Sexual | `A`=Assexual `B`=Bissexual `E`=Heterossexual `H`=Homossexual `N`=Não informado_(+1)_ |
| POSSUIFILHOS | String |  | Possui Filhos | `N`=Não `S`=Sim `U`=Não informado |
| ESTADOCIVIL | Integer |  | Estado Civil | `3`=Viúvo(a) `1`=Solteiro(a) `7`=União Estável `2`=Casado(a) `4`=Separado(a) judicialmente_(+2)_ |
| NIVESC | Integer |  | Escolaridade | `11`=Doutorado Completo `10`=Mestrado Completo `9`=Superior Completo `8`=Superior Incompleto `7`=Ensino Médio Completo_(+7)_ |
| CNPJENTQUAL | String |  | CNPJ Entidade Qualificadora |  |
| CODPAISNAC | Integer |  | Pais de Nascimento |  |
| CNPJPRAT | String |  | CNPJ Entidade Prática |  |
| MESDIA | Integer |  | Mês e dia nascimento |  |
| NACIONALIDADE | Integer |  | Nacionalidade | `34`=34-Canadense `32`=32-Britânico `36`=36-Norte Americano (EUA) `35`=35-Espanhol `31`=31-Belga_(+31)_ |
| APRENDIZGRAVIDA | String |  | Aprendiz Grávida | `S`=Sim `N`=Não |
| CIDNASC | Integer |  | Naturalidade |  |
| CODTOMADOR | Integer |  | Tomador |  |
| TELEFONE | String |  | Telefone |  |
| CELULAR | String |  | Celular |  |
| DIACADPIS | Integer |  | Dia de cadastro no PIS |  |
| EMAIL | String |  | Email |  |
| DEFICIENTEFISICO | String |  | PCD - Pessoa Com Deficiência | `N`=Não `S`=Sim |
| TIPDEFICIENCIA | Integer |  | Tipo de Deficiência | `8`=Mental `0`=Não é portador `1`=Física `7`=Mobilidade reduzida `6`=Reabilitado_(+4)_ |
| OBSDEFICIENCIA | String |  | Observações da Deficiência |  |
| STEP | String |  | STEP |  |
| IDENTIDADE | String |  | Número da Identidade |  |
| ORGAORG | String |  | Órgão Expedidor |  |
| DTRG | Date |  | Data de Emissão da Identidade |  |
| UFRG | Integer |  | UF da Identidade |  |
| NOMEMAE | String |  | Nome da Mãe |  |
| NACIONALPAIS | Integer |  | Naturalidade da Mãe |  |
| NOMEPAI | String |  | Nome do Pai |  |
| COMPLEMENTORG | String |  | Complemento da Identidade |  |
| CTPSDIGITAL | String |  | CTPS Digital | `S`=Sim `N`=Não |
| NUMCPS | Integer |  | Número da CTPS |  |
| SERIECPS | String |  | Série da CTPS |  |
| UFCPS | Integer |  | UF da CTPS |  |
| DTCPS | Date |  | Data de Emissão da CTPS |  |
| PIS | String |  | Número do PIS |  |
| DTCADPIS | Date |  | Data de Cadastro |  |
| CODEMPRESPNIS | Integer |  | Empresa Responsável pelo NIS |  |
| NISENVIADO | String |  | NIS Enviado | `S`=Sim `N`=Não |
| NUMLOTENIS | Integer |  | Número do Lote do NIS |  |
| DTLOTENIS | Date |  | Data do Lote do NIS |  |
| NROCNH | String |  | Número da CNH |  |
| CATEGORIACNH | String |  | Categoria da CNH |  |
| PRIMEIRACNH | Date |  | Data da 1° CNH |  |
| VENCIMENTOCNH | Date |  | Data de Validade da CNH |  |
| ORGAOCNH | String |  | Órgão Emissor da CNH |  |
| UFCNH | Integer |  | UF da CNH |  |
| DTEXPCNH | Date |  | Data de Emissão da CNH |  |
| TITELEITORAL | String |  | Número do Título Eleitoral |  |
| SECAOELEITORAL | Integer |  | Seção Eleitoral |  |
| ZONAELEITORAL | Integer |  | Zona Eleitoral |  |
| NRORESERVISTA | String |  | Número de Reservista |  |
| METERG | String |  | METERG |  |
| NROPASSAPORTE | String |  | Número do Passaporte |  |
| EMISSORPPORTE | String |  | Órgão Emissor do Passaporte |  |
| UFPPORTE | Integer |  | UF do Passaporte | `9`=BRASIL - PA PARÁ `8`=BRASIL - PR PARANÁ `7`=BRASIL - RJ RIO DE JANEIRO `6`=BRASIL - BA BAHIA `5`=BRASIL - MT MATO GROSSO_(+25)_ |
| DTEMIPPORTE | Date |  | Data de Emissão do Passaporte |  |
| DTVALPPORTE | Date |  | Data de Validade do Passaporte |  |
| NRORIC | String |  | Número do RIC |  |
| ORGAORIC | String |  | Órgão Expedidor do RIC |  |
| DTEMIRIC | Date |  | Data de Emissão do RIC |  |
| CODCIDRIC | Integer |  | Cidade |  |
| NROC | String |  | Número do Registro de Órgão da Classe |  |
| ORGAOOC | String |  | Órgão Emissor do Registro de Órgão da Classe |  |
| DTEXPOC | Date |  | Data de Expedição do Registro de Órgão da Classe |  |
| DTVALOC | Date |  | Data de Validade do Registro de Órgão da Classe |  |
| TIPCERTIDAO | String |  | Tipo da Certidão Civil | `O`=Certidão de Óbito `N`=Certidão de Nascimento `I`=Certidão Administrativa de Nascimento do Indígena `C`=Certidão de Casamento |
| NROCERTCIVIL | String |  | Número da Certidão Civil |  |
| NROLIVROREG | String |  | Número do Livro de Registro |  |
| NROFOLHAREG | String |  | Número da Folha de Registro |  |
| CARTORIO | String |  | Cartório |  |
| DTEMICERTCIVIL | Date |  | Data de Emissão da Certidão Civil |  |
| CODCIDCERTCIVIL | Integer |  | Cidade do Certificado Civil |  |
| CPFANT | String |  | CPF Anterior |  |
| DTALTCPF | Date |  | Data de Alteração do CPF |  |
| OBSALTCPF | String |  | Observação de Alteração do CPF |  |
| DTCARTEIRASAUDE | Date |  | Data de Emissão da Carteira Saúde |  |
| INDNIF | String |  | Identificação Fiscal | `3`=País não exige NIF `1`=Beneficiário com NIF `2`=Beneficiário dispensado do NIF |
| NIFBENEF | String |  | Número do NIF |  |
| CEP | String |  | CEP |  |
| DTADM | Date |  | Data de Admissão |  |
| CODEND | Integer |  | Endereço |  |
| PRIMEMPREGO | String |  | Tipo de Admissão | `O`=Outros encerramentos `T`=Transf.de outro estabelec. da mesma empresa com ônus `N`=Adm.Com emprego anterior `S`=Adm.Primeiro emprego `R`=Reintegração_(+3)_ |
| DIRRECIPROCO | String |  | Possui Cláusula de Direito Recíproco | `N`=Não `S`=Sim |
| NUMEND | String |  | Número |  |
| DTADMJUD | Date |  | Data admissão (Decisão Judicial) |  |
| COMPLEMENTO | String |  | Complemento |  |
| OBJDET | String |  | Objeto determ. contratação por prazo determinado (obra, serv., safra, etc) |  |
| INDADMISSAO | Integer |  | Indicativo de Admissão | `3`=Decorrente Decisão Judicial `2`=Decorrente Ação Fiscal `1`=Normal |
| CODBAI | Integer |  | Bairro |  |
| NRPROCTRAB | String |  | Nº do Processo de Admissão por Decisão Judicial |  |
| CODCID | Integer |  | Cidade |  |
| TEMPOPARCIAL | String |  | Tempo Parcial | `S`=Sim `N`=Não |
| INFOCOTA | String |  | Preenche Cota de PCD's | `S`=Sim `N`=Não |
| CAIXAPOSTAL | String |  | Código Postal |  |
| TRABAPOSENT | String |  | Trabalhador Aposentado | `S`=Sim `N`=Não |
| SEGDESEMPREGO | String |  | Possui Requerimento de Seguro Desemprego | `S`=Sim `N`=Não |
| TRABOUTRAEMP | String |  | Trabalha em Outra Empresa | `S`=Sim `N`=Não |
| INDMV | Integer |  | Indicativo de Desconto do INSS em Outra Empresa | `3`=Contribuição descontada por outra Empresa sobre valor do teto `2`=Contribuição descontada por outra Empresa sobre valor menor que o teto `1`=Contribuição descontada pela Empresa `0`=Não se aplica |
| MATRICANT | Integer |  | Matricula Anterior |  |
| CODCATEGESOCIAL | Integer |  | Código de Categoria para o eSocial |  |
| SITESOCIAL | String |  | Situação no eSocial | `T`=Oficial: S-2205, S-2206 e S-2306 `S`=Não sujeito a admissão no eSocial `P`=Provisório: S-2190 `O`=Oficial: S-2200 e S-2300 `6`=Oficial: S-2206 e S-2306_(+1)_ |
| VINCULO | Integer |  | Vínculo | `02`=02 - Estagiário `15`=15 - Prazo indeterminado pessoa física `60`=60 - Prazo determinado urbano (jurídica) `75`=75 - Prazo determinado rural (física) `50`=50 - Contrato temporário_(+12)_ |
| NATATIVIDADE | String |  | Natureza da Atividade | `P`=Rural `U`=Urbano |
| REGIMETRAB | Integer |  | Regime Trabalhista | `3`=RJP - Regime Jurídico Próprio `2`=RJU - Regime Jurídico Único `1`=CLT - Consolidação das Leis de Trabalho |
| REGIMEJOR | Integer |  | Regime de Jornada | `4`=Teletrabalho, previsto Inciso III Art. 62 CLT `3`=Funções conf.Inciso II Art. 62 CLT `2`=Atividade Externa conf.Inciso I Art. 62 CLT `1`=Submetidos Horário Trabalho (Cap. II CLT) |
| REGIME | Integer |  | Regime Previdenciário | `2`=RGPS - Regime Geral Previdência Social `4`=RPPE - Regime Próprio Prev. Social Exterior `3`=RPPS em extinção `1`=RPPS - Regime Próprio de Previdência Social, Reg. Parlamentares e Sist. de Proteção de Militares |
| MEI | String |  | Equivalente a MEI | `S`=Sim `N`=Não |
| DISPPEREXP | String |  | Dispensado da Experiência | `S`=Sim `N`=Não |
| SUSPEXPAFAST | String |  | Possui Cláusula de Suspensão da Experiência por Afastamento | `S`=Sim `N`=Não |
| DIASPERIODO1 | Integer |  | Dias para vencimento do 1º Período |  |
| DTVENCEXP1 | Date |  | Data de Vencimento do 1° Periodo de Experiência |  |
| DIASPERIODO2 | Integer |  | Dias para vencimento do 2º Período |  |
| TPREFDTVENCEXP2 | String |  | Referência para vencimento do 2º período | `A`=Data de admissão `P`=Data de vencimento do 1º período de experiência |
| DTVENCEXP2 | Date |  | Data de Vencimento do 2° Periodo de Experiência |  |
| DTTERMINO | Date |  | Data Término do Contrato |  |
| OPTFGTS | Integer |  | Optante pelo FGTS | `1`=Sim `0`=Não |
| DTOPTFGTS | Date |  | Data de Opção de FGTS |  |
| CODADMFGTSII | String |  | Tabela de Categoria [FGTS] | `25`=25 Contrib individ transportador cooperado que presta serviços à entidade  beneficente isenta cota `21`=21 Servidor público titular de cargo efetivo, magistrado, membro do minist. publico e do tribunal e `20`=20 Servidor público ocupante, exclusivamente, de cargo em comissão, serv. público ocupante de cargo `23`=23 Contribuinte individual transportador autônomo contratado por contrib ind., por produtor rur. `22`=22 Contrib Individ contratado por contrib individ, por prod rural PF, por missão diplomática/consul._(+18)_ |
| CODADMFGTS | String |  | Tabela de Ocorrência [FGTS] | `03`=03 Exposição a agente nocivo (aposentadoria aos 20) `02`=02 Exposição a agente nocivo (aposentadoria aos 15) `06`=06 Exposição a agente nocivo (apos. aos 15) mult.vinculo `07`=07 Exposição a agente nocivo (apos. aos 20) mult.vinculo `00`=00 Não exposição a agente nocivo_(+4)_ |
| PERCCONV | Float |  | Percentual convênio |  |
| SALBASE | Float |  | Salário Base |  |
| HORASSEM | Float |  | Qtd Horas Semanais |  |
| REMUMINIMA | Float |  | Remuneração Mínima Assegurada |  |
| REMUNBASE | Float |  | Bolsa Estágio / Pró-Labore |  |
| TIPSAL | String |  | Tipo de Salário | `2`=Quinzenal `3`=Semanal `1`=Mensal `4`=Diarista `5`=Horista_(+1)_ |
| COMPSALARIO | Integer |  | Tipo de Remuneração | `3`=Sal. Fixo + Variável `2`=Variável `1`=Salário Fixo |
| OBSVARIAVEL | String |  | Observação da Remuneração Variável |  |
| TIPRECEB | String |  | Tipo de Recebimento | `D`=Dinheiro `B`=Banco `C`=Cheque |
| PERCADIANTAMENTO | Float |  | % Adiantamento |  |
| PERCINSAL | Float |  | % Insalubridade |  |
| PERCPERIC | Float |  | % Periculosidade |  |
| DEPENDIRF | Integer |  | Quantidade de Dependentes de IRRF |  |
| DTFIMCONTRINT | Date |  | Data Final do Contrato de Intermitente |  |
| SEMANASPORMES | Float |  | Semanas por mês |  |
| CONVMED | String |  | Possui Plano de Saúde | `S`=Sim `N`=Não |
| PARTPAT | String |  | Participa do Programa de Alimentação do Trabalhador | `2`=Não `1`=Sim |
| CONTRATOSUSP | String |  | Contrato de Trabalho Suspenso | `S`=Sim `N`=Não |
| ADERIMP927 | String |  | Bloqueia Suspensão do 1/3 de Férias | `N`=Não `S`=Sim |
| DTINICIORED | Date |  | Data de Início da Redução |  |
| DTFIMRED | Date |  | Data Final da Redução |  |
| HORASSEMRED | Float |  | Qtd Horas Semanais com Redução |  |
| PERREDCPU | Float |  | % Redução |  |
| SALBASERED | Float |  | Salário Base com Redução |  |
| JORNADAESPPROF | String |  | Professor possui Jornada Especial | `S`=Sim `N`=Não |
| JORNADAPROF | Float |  | Jornada Semanal Professor |  |
| SALPROFESSOR | Float |  | Salário Professor |  |
| OBSERVACAO | String |  | Observação |  |
| DTLAUDORRA | Date |  | Data do Laudo de Moléstia Grave |  |
| SUSPCONTRATO | String |  | Suspensão de Contrato | `N`=Não `S`=Sim |
| AJUDACOMP | String |  | Ajuda Compensatória | `N`=Não `S`=Sim |
| CODDEP | Integer |  | Departamento |  |
| CODCARGO | Integer |  | Cargo |  |
| CODFUNCAO | Integer |  | Função |  |
| CODCATEG | Integer |  | Categoria |  |
| CODNIVEL | Integer |  | Nível |  |
| CODCARREIRA | Integer |  | Carreira |  |
| CODLOCALPONTO | Integer |  | Local de Trabalho |  |
| CODCIDTRAB | Integer |  | Cidade de Trabalho |  |
| CODSIND | Integer |  | Sindicato |  |
| TEMDESCASSIST | String |  | Se Opõe ao Desconto da Contribuição Assistencial | `S`=Sim `N`=Não |
| TEMCONTRIBSINDICAL | String |  | Autoriza Desconto da Contribuição Sindical | `S`=Sim `N`=Não |
| SITSIND | String |  | Situação Sindical | `N`=Não Pago `P`=Pago |
| CODEMPFUNCSUP | Integer |  | Empresa do Líder Substituto |  |
| CODFUNCSUP | Integer |  | Líder Substituto |  |
| USUVPJSUP | Integer |  | Líder Pessoa Jurídica |  |
| DISPENSAPONTO | String |  | Dispensado do Ponto | `S`=Sim `N`=Não |
| DTDISPENSAPONTO | Date |  | Dispensa ponto válido a partir de |  |
| SENHA | String |  | Senha do ponto |  |
| NUMCARTAOPONTO | Integer |  | Número do Cartão de Ponto |  |
| BLOQUEIABATIDAONLINE | String |  | Bloqueia Batida de Ponto Online | `N`=Não `S`=Sim |
| TIPPONTO | String |  | Utiliza Ponto Manual / Mecânico | `S`=Sim `N`=Não |
| DIAAPURAPONTO | Integer |  | Dia de Início da Apuração |  |
| CODGRUPOHORARIO | Integer |  | Grupo de Horário |  |
| ORDEMGRUPOHR | Integer |  | Ordem do Grupo de Horário |  |
| DTINIGRUPOHR | Date |  | Data de Início do Grupo de Horário |  |
| DIASEMGRUPOHR | Integer |  | Dias sem Grupo de Horário |  |
| CODCARGAHOR | Integer |  | Carga Horária |  |
| CODBCO | Integer |  | Banco |  |
| CODAGE | String |  | Agência Bancária |  |
| CODCTABCO | String |  | Conta Bancária |  |
| TIPCONTA | String |  | Tipo de Conta |  |
| CTAFGTS | String |  | Conta do FGTS |  |
| TPINCLCONTR | Integer |  | Tipo de Inclusão Contratual | `3`=Contratação superior a 3 meses `2`=Estudo de mercado `1`=Locais sem filiais |
| CONTTRABTEMP | Integer |  | Contrato de Trabalho Temporário | `2`=Acréscimo extraordinário de serviços `1`=Necessidade transitória de substituição de pessoal regular `0`=Não se aplica |
| CODEMPFUNCSUBST | Integer |  | Empresa do Funcionário Substituído |  |
| CODFUNCSUBST | Integer |  | Funcionário Substituído |  |
| CPFSUBSTITUIDO | String |  | CPF do Substituído |  |
| TPINSCTOMADOR | Integer |  | Tipo de Inscrição do Estabelecimento Tomador | `2`=CPF `1`=CNPJ |
| NRINSCTOMADOR | String |  | Inscrição do Estabelecimento Tomador |  |
| TPINSCESTABVINC | Integer |  | Tipo de Inscrição do Estabelecimento Vinculado | `1`=CNPJ `2`=CPF |
| NRINSCESTABVINC | String |  | Inscrição do Estabelecimento Vinculado |  |
| JUSTCONTR | String |  | Justificativa de Contratação |  |
| JUSTPRORR | String |  | Justificativa de Prorrogação do Contrato |  |
| CNPJEMPCED | String |  | CNPJ da Empresa Cedente |  |
| MATRICULAEMPCED | String |  | Matricula do Trabalhador Cedido |  |
| DTADMEMPCED | Date |  | Data de Admissão do Trabalhador Cedido |  |
| CODCATEGTRABCEDIDO | Integer |  | Categoria do Trabalhador Cedido |  |
| INFOONUS | Integer |  | Informações sobre o Ônus | `1`=Ônus do Cedente `3`=Ônus do Cedente e Cessionário `2`=Ônus do Cessionário |
| TPREGTRABCED | Integer |  | Tipo de Regime de Trabalho do Trabalhador Cedido | `2`=Estatuário `1`=CLT e Legislações trabalhistas específicas |
| TPREGPREVCED | Integer |  | Tipo de Regime da Previdência do Trabalhador Cedido | `3`=Regime de Previdência Social no Exterior `1`=Regime Geral da Previdência Social - RGPS `2`=RPPS - Regime Próprio de Previdência Social, Reg. Parlamentares e Sist. de Proteção de Militares |
| DTCHEGPAIS | Date |  | Data de Chegada ao País |  |
| ANOCHEGPAIS | Integer |  | Ano de Chegada ao País |  |
| DTVALPAIS | Date |  | Data de Validade do Visto |  |
| SITPAIS | String |  | Situação no País | `P`=Permanente `T`=Temporário |
| CLASSTRABESTRANG | Integer |  | Situação Estrangeira | `8`=Com residência provisória e anistiado, em situação irregular `7`=Deficiente físico e com mais de 51 anos `6`=Residente fora do Brasil `5`=Solicitante de Refúgio `4`=Refugiado_(+7)_ |
| TMPRESIDTRABESTRANG | String |  | Tempo de Residência do Trabalhador Imigrante | `2`=2 - Prazo Determinado `1`=1 - Prazo Indeterminado |
| CONDINGESTRANG | String |  | Condição de Ingresso do Trabalhador Imigrante | `7`=7 - Outra condição `6`=6 - Beneficiado pelo Tratado de Amizade, Cooperação e Consulta entre o Brasil e Portugal `5`=5- Dependente de agente diplomático e/ou consular com acordo de reciprocidade e atividade remunerada `4`=4 - Beneficiado pelo acordo entre países do Mercosul `3`=3 - Permanência no Brasil em razão de reunião familiar_(+2)_ |
| CASADOBR | String |  | Casado com Brasileiro | `S`=Sim `N`=Não |
| FILHOSBR | String |  | Possui Filhos Brasileiros | `S`=Sim `N`=Não |
| NRONATURAL | String |  | Número da Naturalização |  |
| DTNATURAL | Date |  | Data da Naturalização |  |
| ENDFISCEXT | String |  | Endereço Fiscal no Exterior | `N`=Não `S`=Sim |
| FORMTRIBU | Integer |  | Forma de Tributação | `10`=Retenção do IRRF - Alíquota padrão `11`=Retenção do IRRF - Alíquota da tabela progressiva `12`=Retenção do IRRF - Alíquota diferenciada (países com tributação favorecida) `13`=Retenção do IRRF - Alíquota limitada conforme cláusula em convênio `30`=Retenção do IRRF - Outras hipóteses_(+6)_ |
| RNE | String |  | Registro Nacional de Estrangeiro |  |
| ORGAORNE | String |  | Órgão Expedidor do RNE |  |
| DTEXPRNE | Date |  | Data de Validade do RNE |  |
| RECIBOESOCIAL | String |  | Recibo eSocial |  |
| RECIBOESOCIAL2200 | String |  | Recibo do eSocial S-2200/S-2300 |  |
| RECIBOESOCIAL2205 | String |  | Recibo do eSocial S-2205 |  |
| RECIBOESOCIAL2206 | String |  | Recibo do eSocial S-2206/S-2306 |  |
| CADINI | String |  | Cadastro Inicial do Vínculo | `S`=Sim `N`=Não |
| DTESOCIAL2205 | Date |  | Data de Alteração - S-2205 |  |
| MATRICULAOLD | String |  | Matrícula Alternativa |  |
| DTESOCIAL2206 | Date |  | Data de Alteração - S-2206/2306 |  |
| ENVESOCIAL | String |  | Envia ao eSocial | `S`=Sim `N`=Não |
| DTINC_ESOCIAL | Date |  | Data de Início no eSocial |  |
| DTULTENV_ESOCIAL | Date |  | Data do Último Envio ao eSocial |  |
| INIVALESOCIAL | Date |  | Data de Início da validade ao eSocial |  |
| FIMVALESOCIAL | Date |  | Data Fim da Validade ao eSocial |  |
| RECIBOESOCIAL2220 | String |  | Recibo do eSocial S-2220 |  |
| DTESOCIAL2220 | Date |  | Data evento S-2220 |  |
| DTENVIOESOCIAL2220 | Date |  | Data envio S-2220 |  |
| ESOCIALINTEGR2220 | String |  | Origem por Integração - S-2220 | `N`=Eventos enviados para o eSocial via Pessoas+ `S`=Eventos enviados para o eSocial via Integração |
| RECIBOESOCIAL2221 | String |  | Recibo do eSocial S-2221 |  |
| DTESOCIAL2221 | Date |  | Data evento S-2221 |  |
| DTENVIOESOCIAL2221 | Date |  | Data envio S-2221 |  |
| ESOCIALINTEGR2221 | String |  | Origem por Integração - S-2221 | `N`=Eventos enviados para o eSocial via Pessoas+ `S`=Eventos enviados para o eSocial via Integração |
| RECIBOESOCIAL2240 | String |  | Recibo do eSocial S-2240 |  |
| DTESOCIAL2240 | Date |  | Data evento S-2240 |  |
| DTENVIOESOCIAL2240 | Date |  | Data envio S-2240 |  |
| ESOCIALINTEGR2240 | String |  | Origem por Integração - S-2240 | `N`=Eventos enviados para o eSocial via Pessoas+ `S`=Eventos enviados para o eSocial via Integração |
| RECIBOESOCIAL2210 | String |  | Recibo do eSocial S-2210 |  |
| DTESOCIAL2210 | Date |  | Data evento S-2210 |  |
| DTENVIOESOCIAL2210 | Date |  | Data envio S-2210 |  |
| ESOCIALINTEGR2210 | String |  | Origem por Integração - S-2210 | `N`=Eventos enviados para o eSocial via Pessoas+ `S`=Eventos enviados para o eSocial via Integração |
| DTALTS2200 | Date |  | Data de alteração S-2200 |  |
| DTALTS2299 | Date |  | Data de Alteração - S-2299 |  |
| VALIDADO | String |  | Validado | `N`=Não `S`=Sim |
| TRANSFEXTERNA | String |  | Transferência Externa | `S`=Sim `N`=Não |
| MOTEXPATRIADO | Integer |  | Motivo da Expatriação | `3`=Contratado por empresa sediada no Brasil para trabalhar a seu serviço no exterior `2`=Cedido à empresa sediada no estrangeiro, para trabalhar no exterior, desde que mantido o vínculo... `1`=Removido para o exterior, cujo contrato estava sendo executado no território brasileiro |
| DTTRANSFDEST | Date |  | Data da Transferência |  |
| CODEMPDEST | Integer |  | Empresa de Destino |  |
| CNPJDESTTRANSF | String |  | CNPJ da Empresa de Destino |  |
| CODFUNCDEST | Integer |  | Funcionário de Destino |  |
| CODMOTDESLIGTRANSF | String |  | Motivo do Desligamento |  |
| DTTRANSFERENCIA | Date |  | Data da Transferência |  |
| CODEMPORIG | Integer |  | Empresa de Origem |  |
| CODFUNCORIG | Integer |  | Funcionário Origem |  |
| DTVINCEMPANT | Date |  | Data de Início do Vínculo |  |
| CNPJEMPANT | String |  | CNPJ da Empresa Anterior |  |
| MATRICULAEMPANT | String |  | Matricula na Empresa Anterior |  |
| OBSEMPANT | String |  | Observação da Empresa Anterior |  |
| TRANSFSEMONUSCEDENTE | String |  | Transferência feita sem ônus para empresa cedente? | `N`=Não `S`=Sim |
| DTAFASTAMENTO | Date |  | Data do Afastamento |  |
| CAUSAAFAST | Integer |  | Causa do Afastamento |  |
| AFASTFGTS | String |  | Motivo do Afastamento para FGTS |  |
| AFASTRAIS | Integer |  | Motivo do Afastamento para RAIS |  |
| CODTPR | Integer |  | Tipo de Rescisão |  |
| DTQUITACAO | Date |  | Data da Quitação |  |
| DTDEM | Date |  | Data de Desligamento |  |
| CODSAQ | Integer |  | Código do Saque de FGTS |  |
| REMUNERAMESANT | Float |  | Remuneração do Mês Anterior ao Desligamento |  |
| NOVOEMPREGO | String |  | Novo Emprego | `S`=Sim `N`=Não |
| SEMINTEGRAL | String |  | Semana Integral | `S`=Sim `N`=Não |
| COMPENSASABADO | String |  | Compensa Sábado | `S`=Sim `N`=Não |
| DTAVISOPREVIO | Date |  | Data do Aviso Prévio |  |
| DIASAVISOPREVIO | Integer |  | Dias de Aviso Prévio |  |
| INDCUMPRPARC | Integer |  | Indicativo de Cumprimento de Aviso Prévio | `4`=Aviso prévio indenizado ou não exigível `3`=Outras hipóteses de cumprimento parcial do aviso `2`=Cumprimento parcial por iniciativa do empregador `1`=Cumprimento parcial em razão de novo emprego `0`=Cumprimento total |
| NRCERTOBITO | String |  | Número da Certidão de Óbito |  |
| NUMPROCTSVE | String |  | Número do TSVE |  |
| MTVDESLIGTSV | Integer |  | Motivo Do Desligamento | `99`=Outros `6`=Exoneração por falência, encerramento ou supressão de parte da empresa `4`=Exoneração do Diretor Não Empregado por culpa recíproca ou força maior `3`=Exoneração a pedido de Diretor Não Empregado `2`=Término de Mandato que não tenha sido reconduzido ao cargo_(+2)_ |
| NOMEARQHOMOLOGNET | String |  | Arquivo Homolognet |  |
| DTFIMQUARENTENA | Date |  | Data Final da Quarentena |  |
| INDSITREMUNDESLIG | Integer |  | Indicativo de Situação de Remuneração após Desligamento | `1`=Quarentena `2`=Desligamento/Termino legal com data anterior a competências com remunerações informadas no eSocial |
| TIPTAB | String |  | Tipo de Tabela de INSS/IRRF/SAL.FAM |  |
| CODPARC | Integer |  | Parceiro |  |
| DIASFERIAS | Integer |  | Dias de Férias por Ano |  |
| PERTENCEDP | String |  | Pertence ao DP/RH | `S`=Sim `N`=Não |
| ACESSOPORTALRH | String |  | Possui acesso ao PortalRH | `N`=Não `S`=Sim |
| ACESSOSANKHYAPASS | String |  | Possui Sankhya Pass | `N`=Não `S`=Sim |
| CODGRUPOCTBZ | Integer |  | Grupo de Contabilização |  |
| PROVISAOFERIAS | String |  | Provisiona Férias | `S`=Sim `N`=Não |
| PROVISAO13 | String |  | Provisiona 13º Salário | `S`=Sim `N`=Não |
| POSSUIRRA | String |  | Possui RRA | `S`=Sim `N`=Não |
| QUEMPAGARRA | Integer |  | Quem Paga RRA | `2`=Pago pela Justiça `1`=Pago pelo Declarante |
| NROPROCESSORRA | String |  | Número de Processo/Recibo de RRA |  |
| TEMUSUSNK | String |  | Possui Usuário Om | `N`=Não `S`=Sim |
| CODUSUSNK | Integer |  | Usuário SankhyaOm |  |
| DTASO | Date |  | Data do ASO |  |
| MEDICOASO | String |  | Médico do ASO |  |
| TELMEDICOASO | String |  | Telefone do Médico do ASO |  |
| UFCRMMEDASO | String |  | UF do CRM do Médico do ASO |  |
| CRMMEDICOASO | String |  | Médico Responsável pelo ASO |  |
| DTALTER | DateTime |  | Data de alteração |  |
| CODUSU | Integer |  | Cód. Usuário Alteração |  |
| CPF | String |  | CPF |  |
| DTFIMREMUN | Date |  | Data fim remuneração |  |
| CODCATEGESOCIALANT | Integer |  | CODCATEGESOCIALANT |  |
| NATATIVIDADEANT | String |  | NATATIVIDADEANT |  |

## TFPGCA — TABLE TFPGCA
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPOCARGO | String |  | DESCRGRUPOCARGO |  |
| ATIVO | String |  | ATIVO |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODGRUPOCARGO | Integer |  | CODGRUPOCARGO |  |

## TFPGCB — TABLE TFPGCB
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPOCTBZ | String |  | Descrição |  |
| CODGRUPOCTBZ | Integer |  | Código |  |

## TFPGHO — Grupos de Históricos de Ocorrências
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPOOCO | String |  | Descrição do Grupo de Ocorrências |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| CODGRUPOOCOPAI | Integer |  | Cód.Grupo de Ocorrência Pai |  |
| GRAU | Integer |  | Grau |  |
| MODULO | String |  | Modulo |  |
| CODGRUPOOCO | Integer |  | Cód.Grupo de Ocorrência |  |

## TFPGHR — TABLE TFPGHR
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPOHR | String |  | DESCRGRUPOHR |  |
| DTINICIO | DateTime |  | DTINICIO |  |
| QTDDIAS | Integer |  | QTDDIAS |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODGRUPOHORARIO | Integer |  | CODGRUPOHORARIO |  |

## TFPGPS — Guia de Recolhimento do PIS
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| CREDITO | Float |  | Crédito |  |
| SALDO | Float |  | Saldo |  |
| DEBITO | Float |  | Débito |  |
| VLRDIGITADO | Float |  | Valor do crédito digitado na GPS |  |
| REFERENCIA | DateTime |  | Referência |  |

## TFPGRA — Gratificações
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNCAO | Integer |  | Código da função |  |
| CODGRAT | Integer |  | Cód.Gratificação |  |
| DESCRGRAT | String |  | Descrição |  |
| PERCENTUAL | Float |  | Percentual |  |

## TFPGRD — Gratificações por Departamento
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODDEP | Integer |  | Departamento |  |
| CODGRAT | Integer |  | Gratificação |  |
| TOTDISP | Float |  | Total disponível |  |
| TOTGERAL | Float |  | Total geral |  |

## TFPGRUEVE — Grupo de Eventos
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | DESCRICAO |  |
| ID | Integer |  | ID |  |

## TFPHASH — Hash Arquivos Folha
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | NOME |  |
| HASH_VALUE | String |  | HASH VALUE |  |
| DATA_ATUALIZACAO | Date |  | DATA DE ATUALIZACAO |  |

## TFPHCP — tab faixa hora extra
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCOMPHR | Integer |  | NUCOMPHR |  |
| DESCRCOMPHR | String |  | DESCRCOMPHR |  |
| EXTRA | String |  | EXTRA |  |
| EXCEDENTE | String |  | EXCEDENTE |  |
| DOMFER | String |  | DOMFER |  |
| EXTRANOT | String |  | EXTRANOT |  |
| EXCEDENTENOT | String |  | EXCEDENTENOT |  |
| DOMFERNOT | String |  | DOMFERNOT |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| NULIMITEHR | Integer |  | NULIMITEHR |  |

## TFPHFE — Tabela de Férias
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Cód.Funcionário |  |
| DTINIAQUI | Date |  | Data início aquisição |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DTFINAQUI | Date |  | Data final aquisição |  |
| DTPREVISTA | Date |  | Data prevista |  |
| DTSAIDA | Date |  | Data da saída |  |
| FALTPER | Integer |  | Faltas no período |  |
| ABONOPEC | Integer |  | Abono pecuniário |  |
| NUMDIASFER | Integer |  | Número de dias de férias |  |
| ADIANTA13SAL | String |  | Adianta 13 salário | `N`=Não `S`=Sim |
| ATUALFERGOZ | String |  | Atualiza férias gozadas | `N`=Não `S`=Sim |
| ABONOINICIO | String |  | Dias  abono início ou fim | `N`=Não `S`=Sim |
| QTDPARCELAS | Integer |  | Quantidade de parcelas do empréstimo |  |
| REFERENCIA | Date |  | Referência |  |
| DIGITADO | String |  | Digitado | `N`=Não `S`=Sim |
| APROVADO | String |  | Aprovado | `N`=Não `S`=Sim |
| QTDDIASSOLFERIAS | Integer |  | Qtd. dias solicitação férias |  |
| DTLIMGOZFER | Date |  | Data limite para gozo de férias |  |
| PERQUITADO | String |  | Periodo quitado | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Cód.Empresa |  |

## TFPHFI — TABLE TFPHFI
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREGFIS | Integer |  | CODREGFIS |  |
| CODSAT | Integer |  | Cód. Sat |  |
| PERCINSS | Float |  | Perc.INSS |  |
| CODGRPS | Integer |  | Cód. GRPS |  |
| TAXAGRPS | Float |  | Taxa GRPS |  |
| TAXASEG | Float |  | Taxa Seguro |  |
| ATIVIRF | Integer |  | Ativ.IRF |  |
| ATIVIBGE | Integer |  | Ativ.IBGE |  |
| ATIVINSS | Integer |  | Ativ.INSS |  |
| PERPAGTOFGTS | Float |  | Perc.FGTS |  |
| CODPAGGPS | Integer |  | Cód.Pagto GPS |  |
| PERCISEFIL | Float |  | Perc.Isencão Filantropia |  |
| OPTSIMPLES | Integer |  | Opt. Simples |  |
| PERFGTSMENOR | Float |  | Perc.FGTS Menor Aprendiz |  |
| RAT15 | Float |  | Rat15 |  |
| RAT20 | Float |  | Rat20 |  |
| RAT25 | Float |  | Rat25 |  |
| FATORFAP | Float |  | Fator FAP |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| VLRINSSRECBRUTA | Float |  | Vlr INSS Rec. Bruta |  |
| PERCINSSPATRONAL | Float |  | Perc. INSS Patronal 13 |  |
| VLRINSSRECBRUTA13 | Float |  | Vlr INSS Rec. Bruta 13 |  |
| PERCRECBRUTAINSS | Float |  | Percentual da  Receita Bruta para INSS |  |
| PERCRECBRUTAINSS13 | Float |  | Percentual da Receita Bruta para INSS 13 |  |
| CODRECOLHIMENTO | Integer |  | Código de  Recolhimento |  |
| PERCPISFOLHA | Float |  | Perc. PIS Sobre a Folha |  |
| FATORMES | Float |  | Fator Mês |  |
| ISEMPRESACONTRIBUINTE | String |  | Empresa contribuinte | `N`=Não `S`=Sim |
| FATOR13 | Float |  | Fator 13º |  |
| CODRECEITASOBFOLHA | Integer |  | Cód. Receita Sobre Folha |  |
| REFERENCIA | Date |  | Referência |  |

## TFPHFU — Histórico do funcionário
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cod.Funcionário |  |
| TIPSAL | String |  | Tipo sálario |  |
| SALBASE | Float |  | Salário base |  |
| REMUMINIMA | Float |  | Remuneração minima |  |
| SITSIND | String |  | Situação Sindicato |  |
| CODSIND | Integer |  | Cód.Sindicato |  |
| CODDEP | Integer |  | Cód.Departamento |  |
| CODCARGO | Integer |  | Cód.Cargo |  |
| CODFUNCAO | Integer |  | Cód.Função |  |
| CODCATEG | Integer |  | Cód.Categoria |  |
| HORASSEM | Float |  | Horas Semanais |  |
| CODADMFGTS | String |  | Tabela de ocorrência [FGTS] |  |
| CODADMFGTSII | String |  | Tabela de categoria [FGTS] |  |
| TRABOUTRAEMP | String |  | Trabalha em Outra Empresa |  |
| PARTPAT | String |  | Progr. de Alimentação do Trab. |  |
| CODCBO | Integer |  | Cód.Banco |  |
| NIVESC | Integer |  | Escolaridade |  |
| ESTADOCIVIL | Integer |  | Estado Civil |  |
| TIPDEFICIENCIA | Integer |  | Deficiência |  |
| CODCIDTRAB | Integer |  | Cód. Cidade Trabalho |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de alteração |  |
| SITUACAO | String |  | Situação |  |
| TPINSCAPREND | Integer |  | Tipo de Inscrição |  |
| NRINSCAPREND | String |  | Número de Inscrição |  |
| CNPJENTQUAL | String |  | CNPJ Entidade Qualificadora |  |
| CNPJPRAT | String |  | CNPJ Entidade Prática |  |
| REGIMEJOR | Integer |  | Regime de Jornada |  |
| DTTERMINO | Date |  | Data Término do Contrato |  |
| OBSVARIAVEL | String |  | Observação da Remuneração Variável |  |
| APRENDCONTRIND | String |  | Contratação Indireta de Aprendiz |  |
| REFERENCIA | DateTime |  | Referência |  |

## TFPHIS — Históricos Ocorrências
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRHISTOCOR | String |  | Descrição |  |
| TIPTAB | String |  | Tipo de tabela |  |
| AFASTAMENTO | String |  | Afastamento | `S`=Sem remuneração `G`=Licença maternidade `A`=Acidente de trabalho `P`=Licença paternidade `M`=Serviço militar_(+30)_ |
| CODAFAST | String |  | Código de afastamento |  |
| CODAFARAIS | Integer |  | Código Afastamento RAIS |  |
| CODAFACAUSA | Integer |  | Código Afastamento Causa |  |
| DTALTER | DateTime |  | Data de alteração |  |
| FALTA | String |  | Falta | `S`=Sim `N`=Não |
| CODGRUPOOCO | Integer |  | CODGRUPOOCO |  |
| BAIXAPROVISAO | String |  | BAIXAPROVISAO |  |
| ABSENTEISMO | String |  | ABSENTEISMO |  |
| TIPREG | String |  | TIPREG |  |
| OCORRENCIAAFDT | String |  | OCORRENCIAAFDT |  |
| DIREITOADN | String |  | DIREITOADN |  |
| QUITAFERLICREM | String |  | QUITAFERLICREM |  |
| REDUZDIASTRAB | String |  | REDUZDIASTRAB |  |
| ABATEAVISOPREVIO | String |  | ABATEAVISOPREVIO |  |
| APELIDO | String |  | APELIDO |  |
| COR | String |  | COR |  |
| UTILIZAMOTIVO | String |  | UTILIZAMOTIVO |  |
| CODMOTAFAST | String |  | CODMOTAFAST |  |
| DEDUZDIASAVISO | String |  | Deduz dias de Aviso prévio lei 12.506/2011 |  |
| INDENIZAESTAB | String |  | INDENIZAESTAB |  |
| QTDMESESESTAB | Integer |  | QTDMESESESTAB |  |
| APARECEPORTAL | String |  | APARECEPORTAL |  |
| REAJSALSIND | String |  | REAJSALSIND |  |
| ANEXOOBRIGATORIO | String |  | ANEXOOBRIGATORIO |  |
| DESCARTAOPONTO | String |  | DESCARTAOPONTO |  |
| SUSPCOMRESIDUO | String |  | SUSPCOMRESIDUO |  |
| COMPNPROG | String |  | COMPNPROG |  |
| HRCOMPL | Integer |  | HRCOMPL |  |
| QFERAFART133 | String |  | QFERAFART133 |  |
| CODHISTOCOR | Integer |  | Histórico |  |

## TFPHLM — TABLE TFPHLM
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRLIMITEHR | String |  | DESCRLIMITEHR |  |
| TIPOLIMITE | Integer |  | TIPOLIMITE |  |
| USAHORADIARIA | String |  | USAHORADIARIA |  |
| USALIMITEMENSAL | String |  | USALIMITEMENSAL |  |
| SOMAACRESCLIMITE | String |  | SOMAACRESCLIMITE |  |
| NULIMITEHR | Integer |  | NULIMITEHR |  |

## TFPHOR — Carga Horária
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TURNO | Integer |  | Turno | `3`=3 `2`=2 `1`=1 `4`=4 |
| ENTRADA | Integer |  | Entrada turno |  |
| SAIDA | Integer |  | Saída turno |  |
| VALENTRADA | String |  | Valida entrada | `N`=Não `S`=Sim |
| VALSAIDA | String |  | Valida saída | `N`=Não `S`=Sim |
| DESCANSOSEM | String |  | Descanso semanal | `N`=Não `S`=Sim |
| CODCARGAHOR | Integer |  | Cód.Carga horária |  |
| CARGAHORARIA | Text |  | Carga |  |
| DURJORNADAESOCIAL | Integer |  | Duração da Jornada para o E-Social |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| DIASEM | Integer |  | Dia da semana - Sequência | `A`=1 |

## TFPHTR — Histórico de Transferências
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| AFASTFGTS | String |  | Motivo do Afastamento para FGTS |  |
| AFASTRAIS | String |  | Motivo do Afastamento para RAIS |  |
| CAUSAAFAST | String |  | Causa do Afastamento |  |
| SITUACAO | String |  | Situação | `0`=Demitido `1`=Atividade normal `2`=Afastado sem remuneração `3`=Afastado por acidente de trabalho `4`=Afastado para serviço militar_(+5)_ |
| DTTRANSFERENCIA | Date |  | Data da Transferência |  |
| CODEMPDEST | Integer |  | Empresa de Destino |  |
| CODFUNCDEST | Integer |  | Código funcionário de destino |  |
| ID | Integer |  | Identificador |  |

## TFPIBPA — Informação dos beneficiários da pensão alimentícia
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUIBPA | Integer |  | NUIBPA |  |
| NUITCR | Integer |  | NUITCR |  |
| NMDEP | String |  | Dependente |  |
| TPREND | String |  | Tipo de rendimento |  |
| CPFDEP | String |  | CPF |  |
| VLRPENSAO | Float |  | Valor da Pensão |  |

## TFPICRT — Informações complementares Rendimentos Tributáveis
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCRT | Integer |  | NUCRT |  |
| NUITCR | Integer |  | NUITCR |  |
| VRRENDTRIB | Float |  | Rendimento tributável mensal do Imposto de Renda |  |
| VRRENDTRIB13 | Float |  | Rendimento tributável do IR de 13 - Tributação exclusiva |  |
| VRRENDMOLEGRAVE | Float |  | Rendimento isento para portador de moléstia grave com laudo. |  |
| VRRENDISEN65 | Float |  | Parcela isenta de aposentadora - Benef. com 65 anos ou mais |  |
| VRJUROSMORA | Float |  | Juros de mora por atraso de pagamento de salário |  |
| VRRENDISENNTRIB | Float |  | Outros rendimentos isentos ou não tributáveis |  |
| DESCISENNTRIB | String |  | Descrição de rendimentos isentos ou não tributáveis |  |
| VRPREVOFICIAL | Float |  | Previdência Oficial |  |
| VRRENDMOLEGRAVE13 | Float |  | Rendimento isento, portador moléstia grave c/ laudo - 13º salário |  |
| VRRENDISEN65DEC | Float |  | Parcela isenta de aposentadoria - Benef. com 65 anos ou mais - 13º salário |  |
| VRJUROSMORA13 | Float |  | Juros de mora por atraso de pagamento de salário - 13º salário |  |
| VLRABONOPEC | Float |  | Valor relativo ao abono pecuniário |  |
| VLRAJUDACUSTO | Float |  | Valor relativo a ajuda de custo |  |
| VLRAUXMORADIA | Float |  | Valor relativo ao auxílio moradia |  |
| VLRDIARIAS | Float |  | Valor relativo a diárias |  |
| VLRINDRESCONTRATO | Float |  | Valor relativo a indenização e rescisão de contrato, PDV e acidentes de trabalho |  |
| VRPREVOFICIAL13 | Float |  | Previdência oficial - 13º salário |  |

## TFPINC — Incidências da Pensão
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Cód.Funcionário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEVENTO | Integer |  | Cód.Evento |  |
| DTALTER | DateTime |  | Data de alteração |  |
| ORIGPENS | String |  | ORIGPENS |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TFPINCCP — PREVIDENCIA
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | DESCRICAO |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODIGO | String |  | CODIGO |  |

## TFPINCFGTS — FGTS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | DESCRICAO |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODIGO | String |  | CODIGO |  |

## TFPINCIRRF — IRFF
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | DESCRICAO |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODIGO | String |  | CODIGO |  |

## TFPINCONS — Inconsistências de Integração
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODINCONS | Integer |  | Cód. Inconsistência |  |
| CODEMP | Integer |  | Código da Empresa |  |
| CODFUNC | Integer |  | Código do Funcionário |  |
| MATRICULA | String |  | Matrícula |  |
| NOMEFUNC | String |  | Nome do Colaborador |  |
| CPFFUNC | String |  | CPF do Colaborador |  |
| CODINCONSISTENCIA | Integer |  | Mensagem da Inconsistência | `1`=Possui mais de um líder cadastrado. Verifique a necessidade de ajuste. `2`=Possui mais de um usuário vinculado. Verifique a necessidade de ajuste. |

## TFPINCPIS — PIS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| DHALTER | DateTime |  | Data de alteração |  |
| CODUSU | Integer |  | Código usuário |  |
| CODIGO | String |  | Código |  |

## TFPINCSIND — INCIDENCIA SINDICAL
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | DESCRICAO |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODIGO | String |  | CODIGO |  |

## TFPINF — Informações Fiscais
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| CODCENCUS | Integer |  | C.R: |  |
| NUMNOTA | Integer |  | Númera lista |  |
| HISTORICO | String |  | Histórico |  |
| CODTIPOPER | Integer |  | T.Op |  |
| CODNAT | Integer |  | Natureza |  |
| CODPROJ | Integer |  | Projeto |  |
| CODTIPTIT | Integer |  | Tipo de Título |  |
| CODCTABCOINT | Integer |  | Conta |  |
| TIPOCHEQUE | String |  | Tipo Marc. Ch. | `K`=Agrupar nominal à empresa `J`=Nominal à empresa `I`=Sem emitir cheque `H`=Agrupar nominal ao histórico `G`=Nominal ao histórico_(+6)_ |
| DTNEG | Date |  | Dt. Negociação |  |
| DTVENC | Date |  | Dt. Vencimento |  |
| DTENTSAI | Date |  | Dt. Entrada e Saída |  |
| CODINFFISC | Integer |  | Código |  |

## TFPINFODESCFOL — Informações do empréstimo em folha
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPODESCONTO | String |  | Tipo de desconto | `1`=1 - Crédito do Trabalhador |
| CODBCO | Integer |  | Banco |  |
| NROCONTRATO | String |  | Número do contrato |  |
| OBSERVACAO | String |  | Observação |  |
| NROUNICO | Integer |  | Nro. único |  |

## TFPIPA — Inconsistências do Processo de Auditoria da Folha
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave |  |
| TIPO | String |  | Tipo |  |
| NOMEFUNC | String |  | Nome do Funcionário |  |
| DETALHES | String |  | Detalhes |  |
| ARTIGO | String |  | Artigo |  |
| CODUSU | Integer |  | Código de usuário |  |
| DTALTER | DateTime |  | Data de alteração |  |
| ID | String |  | ID |  |

## TFPIPRRDJ — Informações de processos relacionados a não retenção de tributos ou a depósitos judiciais
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUIPRRDJ | Integer |  | Número Único TFPIPRRDJ |  |
| NUITCR | Integer |  | Número Único TFPITCR |  |
| TPPROCRET | String |  | Tipo de Processo | `1`=1 - Administrativo `2`=2 - Judicial |
| NRPROCRET | String |  | Número do Processo |  |
| CODSUSP | String |  | Código Indicativo de Suspensão |  |
| DESCPROCRET | String |  | Descrição do Processo |  |

## TFPIRRA — Informações complementares relativas a Rendimentos Recebidos Acumuladamente - RRA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NURRA | Integer |  | NURRA |  |
| NUITCR | Integer |  | NUITCR |  |
| DESCRRA | String |  | Descrição dos Rendimentos Recebidos Acumuladamente |  |
| QTDMESESRRA | Integer |  | Quantidade de meses relativos ao RRA |  |
| VLRDESPCUSTAS | Float |  | Valor das custas judiciais |  |
| VLRDESPADVOGADOS | Float |  | Valor total das despesas com advogados |  |

## TFPITADV — Identificação dos advogados
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUITADV | Integer |  | NUITADV |  |
| NURRA | Integer |  | NURRA |  |
| TIPOINSCR | String |  | Tipo Inscrição | `1`=1 - CNPJ `2`=2 - CPF |
| CNPJCPF | String |  | Número de Inscrição |  |
| VLRDESP | Float |  | Valor da despesa |  |
| NMADV | String |  | Nome Adv/Empresa |  |

## TFPITCR — Valor por Receita dos Tributos do Processo Trabalhista
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUITCR | Integer |  | Nro. Único |  |
| NUITPBC | Integer |  | Nro. Único Informações Base Cálculo de Tributo |  |
| NUITPRT | Integer |  | Nro. Único Informações de Tributos |  |
| TPVALOR | String |  | Tipo | `1`=Previdenciária/Outras Bases `2`=Redimento Tributável |
| CODRECEITA | Integer |  | Código da Receita |  |
| VALOR | Float |  | Valor - Remuneração |  |
| VALOR13 | Float |  | Valor - 13º Salário |  |

## TFPITPBC — Identificação Base Cálculo dos Tributos do Processo Trabalhista
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUITPBC | Integer |  | Nro. Único |  |
| NUITPRT | Integer |  | Nro. Único Informações de Tributos |  |
| DTREFCALC | Date |  | Referência da informação |  |
| VLRBASCALCPREV | Float |  | Base de Cálculo Contribuição Previdenciária - Remuneração |  |
| VLRBASCALCPREV13 | Float |  | Base de Cálculo Contribuição Previdenciária - 13º Salário |  |
| VLRREDTRIB | Float |  | Rendimento Tributável |  |
| VLRREDTRIB13 | Float |  | Rendimento tributável - 13º Salário |  |

## TFPITPRT — Informações dos Tributos do Processo Trabalhista
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUITPRT | Integer |  | Nro. Único |  |
| IDESEQPROC | Integer |  | Número do grupo processo coletivo |  |
| NUPRT | Integer |  | Nro. Único do Processo Trabalhista |  |
| DTREFPGTO | Date |  | Referência de pagamento |  |
| INCPORTALESOCIAL | String |  | Inclusão realizada via Portal do eSocial? | `N`=Não `S`=Sim |
| OBSERVACAO | String |  | Observação |  |
| CONFIRMADO | String |  | Confirmado | `N`=Não `S`=Sim |
| NRORECIBOESOCIAL | String |  | Número do Recibo eSocial (S-2501) |  |
| REGPASSIVO13 | String |  | REGPASSIVO13 |  |

## TFPIVRDJ — Informações de valores relacionados a não retenção de tributos ou a depósitos judiciais
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUIVRDJ | Integer |  | Número Único TFPIVRDJ |  |
| NUIPRRDJ | Integer |  | Número Único TFPIPRRDJ |  |
| INDAPURACAO | String |  | Período de apuração | `1`=1 - Mensal `2`=2 - Anual |
| VLRNRETIDO | Float |  | Valor de IR que deixou de ser retido |  |
| VLRDEPJUD | Float |  | Valor do depósito judicial |  |
| VLRCMPANOCAL | Float |  | Valor de compensação - ano calendário |  |
| VLRCMPANOANT | Float |  | Valor compensação - anos anteriores |  |
| VLRRENDSUSP | Float |  | Valor rendimento com exigibilidade suspensa |  |

## TFPLBE — Lançamento Beneficio
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Cod. Funcionário |  |
| NOMEFUNC | String |  | Nome Funcionário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NOMEDEPEND | String |  | Nome Dependente |  |
| CODEVENTO | Integer |  | Cod. Evento |  |
| CODEMP | Integer |  | Cod. Empresa |  |
| DTREFEMP | DateTime |  | Referência Emp |  |
| VLRTITULAR | Float |  | Vlr. Titular |  |
| VLRDEPEN | Float |  | Vlr. Dependente |  |
| CODCBE | Integer |  | Cod. Central Beneficio |  |
| CODBEN | Integer |  | Cod. Beneficio |  |
| CODDEP | Integer |  | Cod. Departamento |  |
| CODCARGO | Integer |  | Cod. Cargo |  |
| CODFUNCAO | Integer |  | Cod. Função |  |
| CODLBE | Integer |  | Cod. Lançamento Beneficio |  |
| SITUACAOFUNC | Integer |  | Situação Funcionario | `9`=Aposentadoria por invalidez `8`=Transferido `7`=Outros `6`=Afastado por doença acima de 15 dias `5`=Afastado por licença maternidade_(+5)_ |

## TFPLFU — Lotação Funcionário
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| DTENTRADA | DateTime |  | DTENTRADA |  |
| DTSAIDA | DateTime |  | DTSAIDA |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | DHALTER |  |
| NUNO | Integer |  | NUNO |  |

## TFPLGR — Logradouro
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRLOGRADOURO | String |  | Descrição |  |
| CODUSU | Integer |  | Usuário |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| CODLOGRADOURO | String |  | Código |  |

## TFPLIDER — Lideres
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Código da Empresa do Funcionário |  |
| CODFUNC | Integer |  | Código do Funcionário |  |
| NOMEFUNC | String |  | Nome do Funcionário |  |
| CPFFUNC | String |  | CPF do Funcionário |  |
| CODEMPLIDER | Integer |  | Código da Empresa Líder |  |
| CODFUNCLIDER | Integer |  | Código do Funcionário Líder |  |
| NOMEFUNCLIDER | String |  | Nome do Líder |  |
| CPFLIDER | String |  | CPF do Líder |  |
| CODIGOPJ | Integer |  | Código do Vinculo a PJ |  |
| EMAILLIDER | String |  | Email do Líder |  |

## TFPLIN — Linhas de Ônibus
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo de Vale | `T`=Transporte `A`=Alimentação |
| DESCRLINHA | String |  | Descrição |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| VLRTARIFA | Float |  | Valor da Tarifa |  |
| CODLINHA | Integer |  | Código |  |

## TFPLOGCALC — Logs do cálculo da folha
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLOG | Integer |  | Código Log |  |
| LOG | C |  | LOG |  |
| REFERENCIA | Date |  | Referência |  |

## TFPLOT — Lotações
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Cód.Funcionário |  |
| CODCARGO | Integer |  | Cod.Cargo |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| DTPOSSE | DateTime |  | Data da Posse |  |
| DTSAIDA | DateTime |  | Data de Saída |  |
| NUOCOR | Integer |  | Número da Ocorrência |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TFPMAD — TABLE TFPMAD
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRMAD | String |  | DESCRMAD |  |
| UTILIZAEM | Integer |  | UTILIZAEM |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODMAD | Integer |  | CODMAD |  |

## TFPMEN — FP Mensagens do Hollerit
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRMENS | String |  | Descrição |  |
| MENSWGE | String |  | Utilizada mensagem no Sankhya-W | `S`=Sim `N`=Nao |
| CODMENS | Integer |  | Cód.Mensagem |  |

## TFPMOV — Movimentos e Fixos
Campos: 42

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODEVENTO | Integer |  | Evento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPEVENTO | Integer |  | Tipo de evento | `-1`=Desconto `0`=Neutro `1`=Provento |
| VLRMOV | Float |  | Valor |  |
| INDICE | Float |  | Índice |  |
| UNIDADE | String |  | Unidade | `H`=Horas `V`=Valor `Q`=Quantidade `D`=Dias |
| DIGITADO | String |  | Origem lançamento | `N`=Não `S`=Sim |
| ORIGEMLANCAMENTO | String |  | Origem lançamento | `W`=Importador Crédito do Trabalhador WebService `C`=Importador Crédito do Trabalhador `F`=Fechamento da referência `I`=Importador genérico `M`=Lançamento manual |
| PRAZO | Integer |  | Prazo |  |
| CODBCO | Integer |  | Banco |  |
| NUMCHEQ | Integer |  | Número do cheque |  |
| PRAZOTOTAL | Integer |  | Prazo total |  |
| DTALTER | DateTime |  | Data de alteração |  |
| OBS | String |  | Observação |  |
| CODUSU | Integer |  | Código de Usuário |  |
| NUFIN | Integer |  | NUFIN |  |
| NUOCOR | Integer |  | Número de Ocorrência |  |
| PROVISAO | String |  | PROVISÃO |  |
| NUFALTA | Integer |  | Número de Faltas |  |
| DIASUTEIS | Integer |  | Dias Úteis |  |
| DIASNAOUTEIS | Integer |  | Dias Não Úteis |  |
| TIPMOV | String |  | Tipo de movimento | `O`=Dissídio `P`=Produção `M`=Mensal `E`=Férias `A`=Adiantamento_(+8)_ |
| SEQFOLHA | Integer |  | Sequência Folha |  |
| MANTEMPROXIMAREF | String |  | Mantém Próxima Referência | `N`=Não `S`=Sim |
| CODCBE | Integer |  | Acerto Benefício |  |
| INSCONSIG | String |  | Matrícula consignatária |  |
| NRCONTR | String |  | Contrato Consig.FGTS |  |
| INDICEHORA | Float |  | Índice Hora |  |
| ORIGEM | String |  | Origem |  |
| SEQFER | Integer |  | Seq. Férias |  |
| REFERENCIAORIG | DateTime |  | Referência de Origem |  |
| TIPFOLHAORIG | String |  | Tipo Folha Origem |  |
| SEQUENCIAORIG | Integer |  | Sequência Origem |  |
| CODPARCPENS | Integer |  | ParceiroPensao |  |
| TIPFOLHAFIXO | String |  | Tipo Folha Fixo |  |
| REFCOMPLEMENTAR | DateTime |  | Data da Referência de Origem |  |
| CODMOV | Integer |  | Código Movimento |  |
| REFERENCIA | DateTime |  | Data e hora de Referência |  |
| NROINFODESCFOL | Integer |  | Informação do empréstimo em folha |  |
| NROHISTORICOIMPORT | Integer |  | Histórico importação credito trabalhador |  |

## TFPMOVANT — Movimentos fixos anteriores
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cód.Funcionário |  |
| TIPMOV | String |  | Tipo de movimento |  |
| CODEVENTO | Integer |  | Cód.Evento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPEVENTO | Integer |  | Tipo de evento |  |
| VLRMOV | Float |  | Valor |  |
| INDICE | Float |  | Índice |  |
| UNIDADE | String |  | Unidade |  |
| PRAZO | Integer |  | Prazo |  |
| CODBCO | Integer |  | Cód.Banco |  |
| NUMCHEQ | Integer |  | Número do cheque |  |
| REFERENCIA | DateTime |  | Data e hora de Referência |  |

## TFPMRH — Mensagens Portal RH
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODDEP | Integer |  | Departamento |  |
| CODFUNC | Integer |  | Funcionário |  |
| DTENVIO | DateTime |  | Dt. de Alteração |  |
| TITULO | String |  | Título |  |
| DESCRICAO | String |  | Mensagem |  |
| CODUSU | Integer |  | Usuário |  |
| CODMENSAGEM | Integer |  | Código |  |

## TFPMTA — Motivos de Afastamento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMOTAFAST | String |  | Código do Motivo de Afastamento |  |
| CODUSU | Integer |  | Código do Usuário que Alterou por último |  |
| DESCRMOTAFAST | String |  | Descrição do Motivo do Afastamento |  |
| DHALTER | Date |  | Data da Última Alteração |  |
| DTFIMVALIDADE | Date |  | Data Fim Validade |  |

## TFPMTD — Motivos Desligamento (eSocial)
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMOTDESLIG | String |  | Código do Motivo de Desligamento |  |
| CODUSU | Integer |  | Código do Usuário da Última Alteração |  |
| DESCRMOTDESLIG | String |  | Descrição do Motivo de Desligamento |  |
| DHALTER | Date |  | Data Hora da Última Alteração |  |

## TFPNCO — TABLE TFPNCO
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRNATCOMP | String |  | Descrição |  |
| CODNATCOMP | Integer |  | Código |  |

## TFPNEWFORM — TABLE TFPNEWFORM
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PSEUDOCODFORM | Integer |  | PSEUDOCODFORM |  |
| DESCRFORM | String |  | DESCRFORM |  |
| FORMULA | Boolean |  | FORMULA |  |
| INDICE | Boolean |  | INDICE |  |
| DTALTER | DateTime |  | DTALTER |  |
| PKG | Integer |  | PKG |  |
| CODFORM | Integer |  | CODFORM |  |

## TFPNEWMED — Nova Tabela de Medias
Campos: 53

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | CODFUNC |  |
| REFERENCIA | DateTime |  | REFERENCIA |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| ORIGEM | String |  | ORIGEM |  |
| TIPOMEDIA | String |  | TIPOMEDIA |  |
| SALBASEMEDIA | Float |  | SALBASEMEDIA |  |
| VLR01 | Float |  | VLR01 |  |
| VLR02 | Float |  | VLR02 |  |
| VLR03 | Float |  | VLR03 |  |
| VLR04 | Float |  | VLR04 |  |
| VLR05 | Float |  | VLR05 |  |
| VLR06 | Float |  | VLR06 |  |
| VLR07 | Float |  | VLR07 |  |
| VLR08 | Float |  | VLR08 |  |
| VLR09 | Float |  | VLR09 |  |
| VLR10 | Float |  | VLR10 |  |
| VLR11 | Float |  | VLR11 |  |
| VLR12 | Float |  | VLR12 |  |
| MESANO01 | String |  | MESANO01 |  |
| MESANO02 | String |  | MESANO02 |  |
| MESANO03 | String |  | MESANO03 |  |
| MESANO04 | String |  | MESANO04 |  |
| MESANO05 | String |  | MESANO05 |  |
| MESANO06 | String |  | MESANO06 |  |
| MESANO07 | String |  | MESANO07 |  |
| MESANO08 | String |  | MESANO08 |  |
| MESANO09 | String |  | MESANO09 |  |
| MESANO10 | String |  | MESANO10 |  |
| MESANO11 | String |  | MESANO11 |  |
| MESANO12 | String |  | MESANO12 |  |
| IND01 | Float |  | IND01 |  |
| IND02 | Float |  | IND02 |  |
| IND03 | Float |  | IND03 |  |
| IND04 | Float |  | IND04 |  |
| IND05 | Float |  | IND05 |  |
| IND06 | Float |  | IND06 |  |
| IND07 | Float |  | IND07 |  |
| IND08 | Float |  | IND08 |  |
| IND09 | Float |  | IND09 |  |
| IND10 | Float |  | IND10 |  |
| IND11 | Float |  | IND11 |  |
| IND12 | Float |  | IND12 |  |
| TOTAL | Float |  | TOTAL |  |
| MEDIA | Float |  | MEDIA |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| DOISPERIODOS | String |  | DOISPERIODOS |  |
| MELHOR | String |  | MELHOR |  |
| REFLEXIVOS | String |  | REFLEXIVOS |  |
| DTINIAQUISITIVO | DateTime |  | DTINIAQUISITIVO |  |
| DTFIMAQUISITIVO | DateTime |  | DTFIMAQUISITIVO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPNIV — Níveis de Referência
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODNIVELREF | Integer |  | Código do nível |  |
| DESCRNIV | String |  | Descrição |  |

## TFPNTL — Descrição de lesões
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRNATLESAO | String |  | Descrição |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODNATLESAO | Integer |  | Código |  |

## TFPOCO — FP Registros de Ocorrências
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICOCOR | DateTime |  | Data Inicial da Ocorrência |  |
| DTINTERROMPEFER | DateTime |  | Data Interrupção Período Férias |  |
| DTPREVRET | DateTime |  | Data Final Prevista da Ocorrência |  |
| DTFINALOCOR | DateTime |  | Data Final da Ocorrência |  |
| RECORRENTE | String |  | Recorrente | `S`=Sim `N`=Não |
| NUREINCID | Integer |  | Número Único da Ocorrência Reincidente |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODUSU | Integer |  | Usuário |  |
| DIASPREVRET | Integer |  | Dias previsto |  |
| DIGITADO | String |  | Digitado Manualmente |  |
| SEQUENCIACNV | Integer |  | Sequencia CNV |  |
| DESCROCOR | String |  | Descrição da Ocorrência |  |
| NUOCOR | Integer |  | Número Único |  |
| NUMANEJO | Integer |  | Número de Manejo |  |
| NUOCORORIG | Integer |  | Número da Ocorrência de Origem |  |
| INDEFEITORETRO | String |  | Indicador Efeito Retroativo | `N`=Não `S`=Sim |
| REAJUSTECCT | String |  | Reajuste CCT | `N`=Não `S`=Sim |
| NUFALTA | Integer |  | Numero Falta |  |
| ORIGRETIF | Integer |  | Origem da Retificação |  |
| CODSIND | Integer |  | Código Sindicato |  |
| NUPROCESSO | Integer |  | Número do Processo |  |
| ENVESOCIAL | String |  | Envia pro Esocial | `N`=Não `S`=Sim |
| ESPECIALIDADE | String |  | Especialidade |  |
| FORCADTFIM | String |  | Força Data Fim | `N`=Não `S`=Sim |
| CID | String |  | CID |  |
| PROCESSOCNV | String |  | Processo CNV |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODHISTOCOR | Integer |  | Código da Ocorrência |  |

## TFPORG — Órgãos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CATEGORIA | String |  | Categoria |  |
| CODORGAO | Integer |  | Órgão |  |
| NOMEORGAO | String |  | Nome |  |

## TFPPAA — Partes do Corpo Lesionadas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARTEATINGIDA | String |  | Cód. Parte do Corpo |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| LATERALIDADE | Integer |  | Lateralidade | `3`=3 - Ambas `2`=2 - Direita `1`=1 - Esquerda `0`=0 - Não aplicável |
| NUCAT | Integer |  | NUCAT |  |

## TFPPCA — Padrões de Cadastro de Funcionario
Campos: 57

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRPADRAO | String |  | Descrição |  |
| INDADMISSAO | Integer |  | Indicativo de Admissão | `1`=Normal `2`=Decorrente Ação Fiscal `3`=Decorrente Descisão Judicial |
| CODBAI | Integer |  | Bairro |  |
| CODCATEGESOCIAL | Integer |  | Categoria para o eSocial |  |
| CODCID | Integer |  | Cidade |  |
| SITESOCIAL | String |  | Situação no eSocial | `5`=Oficial e S-2205 `6`=Oficial, S-2206 e S-2306 `O`=Oficial (S-2200 / S-2300) `P`=Provisório (S-2190) `S`=Não sujeito a admissão no eSocial_(+1)_ |
| SEXO | String |  | Sexo | `M`=Masculino `F`=Feminino |
| VINCULO | Integer |  | Vínculo | `99`=99 - Pensionista `90`=90 - Autônomo `80`=80 - Diretor sem vínculo empregatício `70`=70 - Prazo determinado rural (jurídica) `65`=65 - Prazo determinado urbano (física)_(+12)_ |
| ESTADOCIVIL | Integer |  | Estado Civil | `7`=Outros `6`=Divorciado(a) `5`=Desquitado(a) `4`=Separado(a) judicialmente `3`=Viúvo(a)_(+2)_ |
| REGIMETRAB | Integer |  | Regime Trabalhista | `1`=CLT - Consolidação das Leis de Trabalho `2`=RJU - Regime Jurídico Único `3`=RJP - Regime Jurídico Próprio |
| NACIONALIDADE | Integer |  | Nacionalidade | `49`=49 - Outros `48`=48 - Outros Latinos `45`=45 - Português `43`=43 - Coreano `42`=42 - Chinês_(+17)_ |
| REGIMEJOR | Integer |  | Regime de Jornada | `1`=Submetidos Horário Trabalho (Cap. II CLT) `2`=Atividade Externa conf.Inciso I Art. 62 CLT `3`=Funções conf.Inciso II Art. 62 CLT `4`=Teletrabalho, previsto Inciso III Art. 62 CLT |
| NIVESC | Integer |  | Escolaridade | `9`=Superior Completo `8`=Superior Incompleto `7`=Colegial Completo `6`=Colegial Incompleto `5`=Ginasial Completo_(+6)_ |
| REGIME | Integer |  | Regime Previdenciário | `3`=RPPS - em extinção `2`=RGPS - Regime Geral da Previdência Social `1`=RPPS - Regime Próprio da Previdência Social |
| TIPDEFICIENCIA | Integer |  | Deficiência | `6`=Reabilitado `5`=Múltipla `4`=Mental `3`=Visual `2`=Auditiva_(+2)_ |
| RACAFUNCIONARIO | Integer |  | Raça | `8`=Parda `6`=Amarela `4`=Negra `2`=Branca `0`=Indígena |
| SALBASE | Float |  | Salário Base |  |
| DIASEXPER1 | Integer |  | Dias para vencimento do 1º Período |  |
| HORASSEM | Float |  | Horas Semanais |  |
| CONVMED | String |  | Convênio Médico | `S`=Sim `N`=Não |
| PERCCONV | Float |  | Percentual Convênio |  |
| REMUMINIMA | Float |  | Remuneração Mínima Assegurada |  |
| TPREFDTVENCEXP2 | String |  | Referência para vencimento do 2º período | `A`=Data de admissão `P`=Data de vencimento do 1º período de experiência |
| DIASEXPER2 | Integer |  | Dias para vencimento do 2º Período |  |
| REMUNBASE | Float |  | Bolsa Estágio / Pró-Labore |  |
| TIPSAL | String |  | Tipo de Salário | `1`=Mensal `2`=Quinzenal `3`=Semanal `4`=Diarista `5`=Horista_(+1)_ |
| COMPSALARIO | Integer |  | Tipo de Remuneração | `1`=Salário Fixo `2`=Variável `3`=Sal. Fixo + Variável |
| CODADMFGTSII | String |  | Tabela de Categoria (FGTS) | `26`=26 Dirig sind, em rel ao adic pago pelo sind; mag classista temporário da Justiça do Trabalho `25`=25 Contrib ind transp coop que presta serv à ent benef isent cota patronal por interm da coop trab `24`=24 Contrib ind coop que presta serv à ent benef  isenta da cota patronal, por int da coop de trab `23`=23 Contrib. ind transp autôn contratado por contrib ind, produtor rural PF, por missão diplomát `22`=22 Contrib Ind. contratado por contrib ind, prod rural PF, por missão diplomática e dirig sind_(+19)_ |
| TIPRECEB | String |  | Tipo de Recebimento | `B`=Banco `C`=Cheque `D`=Dinheiro |
| CODADMFGTS | String |  | Tabela de Ocorrências (FGTS) | `08`=08 Exposição a agente nocivo (apos. aos 25) mult. vínculo `07`=07 Exposição a agente nocivo (apos. aos 20) mult. vínculo `06`=06 Exposição a agente nocivo (apos. aos 15) mult. vínculo `05`=05 Não exposição a agente nocivo, já esteve mult. vínculo `04`=04 Exposição a agente nocivo (aposentadoria aos 25)_(+4)_ |
| PERCADIANTAMENTO | Float |  | % Adiantamento |  |
| OPTFGTS | Integer |  | Optante pelo FGTS | `0`=Não `1`=Sim |
| PERCINSAL | Float |  | % Insalubridade |  |
| PERCPERIC | Float |  | % Periculosidade |  |
| CODDEP | Integer |  | Departamento |  |
| PARTPAT | String |  | Participa do Programa de Alimentação do Trabalhador | `2`=Não `1`=Sim |
| CODCARGO | Integer |  | Cargo |  |
| CODFUNCAO | Integer |  | Função |  |
| CODCATEG | Integer |  | Categoria |  |
| SINDICALIZADO | String |  | Filiado ao Sindicato de Classe | `S`=Sim `N`=Não |
| CODCIDTRAB | Integer |  | Cidade de Trabalho |  |
| CODSIND | Integer |  | Sindicato |  |
| CODBCO | Integer |  | Banco |  |
| CODAGE | String |  | Agência |  |
| TIPTAB | String |  | Tipo de Tabela de INSS/IRRF/SAL. FAM. |  |
| DIASFERIAS | Integer |  | Dias de Férias por Ano |  |
| PROVISAOFERIAS | String |  | Provisiona Férias | `N`=Não `S`=Sim |
| PROVISAO13 | String |  | Provisiona 13º Salário | `N`=Não `S`=Sim |
| TIPCONTA | String |  | TIPCONTA |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| TIPPONTO | String |  | Utiliza Ponto Manual / Mecânico | `S`=Sim `N`=Não |
| DIAAPURAPONTO | Integer |  | Dia de início da Apuração |  |
| CODCARGAHOR | Integer |  | Carga Horária |  |
| NUPADRAO | Integer |  | Código |  |
| SANKHYA | String |  | Padrão do Sistema | `N`=Não `S`=Sim |
| TIPOCAD | String |  | Tipo de Cadastro | `V`=Verde e Amarelo `A`=Aprendiz `C`=Funcionário CLT `D`=Diretor `E`=Estagiário_(+2)_ |

## TFPPCAT — Partes do corpo lesionadas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRPARTEATINGIDA | String |  | Descrição da Parte do Corpo |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODPARTEATINGIDA | Integer |  | Código |  |

## TFPPCG — Perfil do Cargo
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OBS | String |  | Observação |  |
| CODCARGO | Integer |  | Cód.Cargo |  |
| CODPERFIL | Integer |  | Cód.Perfil |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| DTFIM | Date |  | Data Final |  |
| DTINICIO | Date |  | Data de Início |  |
| IMPRESCINDIVEL | String |  | Imprescindível | `S`=Sim `N`=Não |
| PERIODICIDADE | Integer |  | Periodicidade |  |
| PESO | Integer |  | Peso |  |
| TIPOPERIODO | String |  | Tipo de Período | `A`=Anual `M`=Mensal |

## TFPPER — Perfil para Folha de Pagamento
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRPERFIL | String |  | Descrição do Perfil |  |
| CODPERFILPAI | Integer |  | Cód.Perfil Pai |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| REQUISITO | String |  | Requisito | `S`=Sim `N`=Não |
| EXAME | String |  | Exame | `N`=Não `S`=Sim |
| NIVELHIER | String |  | Nível Hierárquico | `N`=Não `S`=Sim |
| AREAPROF | String |  | Área Profissional | `N`=Não `S`=Sim |
| CODHISTOCOR | Integer |  | Cód.Histórico de Ocorrencia |  |
| OBS | String |  | Observação |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| GRAU | Integer |  | Grau |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODPERFIL | Integer |  | Cód.Perfil |  |

## TFPPKGFORM — TABLE TFPPKGFORM
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RAIZCNPJ | String |  | RAIZCNPJ |  |
| FINALCNPJ | String |  | FINALCNPJ |  |
| DESCRPKG | String |  | DESCRPKG |  |
| CODPKG | Integer |  | CODPKG |  |

## TFPPLS — Plano de Saúde
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REFERENCIA | Date |  | Referência Inicial |  |
| REFERENCIAFIM | Date |  | Referência Final |  |
| TABFAIXA | Integer |  | Tabela de Faixa |  |
| CODFAIXA | Integer |  | Código da Faixa |  |
| PARTICIPACAO | Float |  | Percentual da Empresa |  |
| CODUSU | Integer |  | Código Usuário |  |
| DHALTER | Date |  | Data de Alteração |  |
| CODFAIXAPROVENTO | Integer |  | Faixa do Provento |  |
| CODCONVENIO | Integer |  | Código do Convênio |  |
| CODEMP | Integer |  | Empresa |  |

## TFPPON — FP Controle de Ponto
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUMOS | Integer |  | NUMOS |  |
| NUMITEM | Integer |  | NUMITEM |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODHISTOCOR | Integer |  | Histórico de ocorrências |  |
| DTMOV | DateTime |  | Data do movimento |  |
| ENTRADA | Integer |  | Entrada |  |
| FALTA | String |  | Falta | `N`=Não `S`=Sim |
| NUOCOR | Integer |  | Ponto |  |
| SAIDA | Integer |  | Saída |  |
| TURNO | Integer |  | Turno | `3`=Noite `2`=Tarde `4`=Madrugada `1`=Manha |

## TFPPONRAIO — Locais Ponto Pessoal Mais
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Código do local |  |
| DESCRICAO | String |  | Descrição |  |
| GEOLOC | String |  | Geolocalização |  |
| CODDEP | Integer |  | Departamento |  |
| DESCRDEP | String |  | Descrição do departamento |  |
| CODEMP | Integer |  | Empresa |  |
| RAIO | Integer |  | Raio |  |
| CEP | String |  | Cep |  |
| CODEND | Integer |  | Código do endereço |  |
| NUMEND | String |  | Número do Endereço |  |
| COMPLEMENTO | String |  | Complemento do endereço |  |
| CODBAI | Integer |  | Código do bairro |  |
| UFENDERECO | Integer |  | Unidade Federativa Endereço |  |
| CODCID | Integer |  | Código da cidade |  |
| CODPAIS | Integer |  | Código do país |  |
| DTCRIACAO | DateTime |  | Data de Criação |  |
| TEMCONTROLEPONTO | String |  | Tem controle de Ponto | `N`=Não `S`=Sim |
| DHALTER | DateTime |  | Data de alteração |  |

## TFPPPRG — Paradas Programadas
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INICIO | Text |  | Hora Início |  |
| FIM | Text |  | Hora Fim |  |
| DURACAO | Integer |  | Duração (Min) |  |
| CODCARGAHOR | Integer |  | Cód.Carga horária |  |
| DIASEM | Integer |  | Dia da semana - Sequência |  |
| TURNO | Integer |  | Turno |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DESCRICAO | String |  | Descrição |  |

## TFPPRE — Regras de Cálculo
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEVENPADRAO | Integer |  | Evento Padrão |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ARREDSALLIQ | Float |  | Arredondamento do salário líquido |  |
| ATUMOVMEN | String |  | Atualiza Movimentação Mensal? | `N`=Nenhum `F`=Folha `B`=Banco de Horas |
| CALCFERPERAQUI | String |  | Calcular médias de férias sobre perído aquisitivo | `N`=Não `S`=Sim |
| CALCPARCFER | String |  | Aceitar cálculo parcial de férias | `N`=Não `S`=Sim |
| CALCRESIDUO | String |  | Calcular resíduo quando mês com 31 ou 28 dias | `N`=Não `S`=Sim |
| CENTIRF | String |  | Centavos no IRF | `S`=Sim `N`=Não |
| CENTVALORES | String |  | Centavos nos valores | `S`=Sim `N`=Não |
| CODEVENBHORAS | Integer |  | Evento para Banco de Horas |  |
| CODEVENCRED | Integer |  | Evento para credito |  |
| CODEVENDEB | Integer |  | Evento para Débito |  |
| CODEVENDOMIN | Integer |  | Código Evento Domingo |  |
| CODEVENNOTUR | Integer |  | Código Evento Noturno |  |
| CODEVENPOSPRI | Integer |  | Código Evento Após Primeiras |  |
| CODEVENPRI | Integer |  | Código Evento Primeiras |  |
| CODPREF | Integer |  | Cód.Preferência |  |
| COMPENSACAO | String |  | Compensação | `S`=Sim `N`=Não |
| DESCRICAO | String |  | Descrição |  |
| DIARETIRADPD | Integer |  | Dia limite para retirar dependentes |  |
| FERPROPERAQUI | String |  | Calcula Férias Proporcionais por Período Aquisitivo | `N`=Não `S`=Sim |
| FORMACALCMEDIAS | String |  | Forma de cálculo de médias | `V`=Considerar apenas meses com valores `T`=Considerar todos os meses para cálculo `D`=Considerar a maior média entre 2 períodos `M`=Considerar meses com maior valor |
| IRFMIN | Float |  | IRF Mínimo |  |
| LANCFERADIANT | String |  | Lançar parte das férias como adiatamento | `P`=Sim e debitar dois meses depois `S`=Sim e debitar no mês seguinte `N`=Não |
| LIMMINHEXTRA | Integer |  | Limite Mínimo de Hora Extra |  |
| LIMMINTOLATR | Integer |  | Limite Mínimo de Tolerância de Atraso |  |
| MEDIAARITIM13 | String |  | Calcular médias aritiméticas | `N`=Não `S`=Sim |
| MEDIAPERFERIAS | String |  | Média Período Férias |  |
| MESCARENCIA | Integer |  | Mês de Carência |  |
| MESDATABASE | Integer |  | Mês Data Base |  |
| MESESMEDIA13S | Integer |  | Número de meses para média no 13 salário |  |
| MESESMEDIA13S2 | Integer |  | Meses para médias de 13 2 período |  |
| MESESMEDIAFER | Integer |  | Número de meses para média nas férias |  |
| MESESMEDIAFER2 | Integer |  | Meses para médias de férias 2 período |  |
| MESESMEDIARESC | Integer |  | Número de meses para média na rescisão |  |
| MESESMEDIARESC2 | Integer |  | Meses para médias de rescisão 2 período |  |
| PAGATRASO | Integer |  | Pagamento em Atraso | `0`=Inteiros `2`=Frações `1`=Meias |
| PAGHSEXTRA | Integer |  | Pagamento Hora Extra | `0`=Inteiros `2`=Frações `1`=Meias |
| PROVFERMEDIAS | String |  | Provisionar férias e 13º salário com médias |  |
| QTDMAIORES | Integer |  | Quantidade para considerar os maiores valores |  |
| REMUMINIMA | Float |  | Remuneração Mínima Assegurada |  |
| RESPFOLHA | String |  | Responsável pela folha |  |
| TIPARRED | String |  | Tipo de arredondamento | `A`=Para maior `M`=Para menor |
| TIPMES | String |  | Tipo de mês | `C`=Comercial (30 dias) `R`=Real (30, 31 e 28) |
| TIPMOVMEDIAS | String |  | Tipo de incidência do movimento nas médias | `M`=Incide nas médias se dias trabalhados for maior que 14 dias `N`=Não incide nas médias `S`=Incide nas médias |

## TFPPROF — TABLE TFPPROF
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NMPROF | String |  | Nome |  |
| TPPROF | Integer |  | Tipo | `2`=2 - Profissional sem vínculo emprego/estatutário com o declarante `1`=1 - Profissional empregado  do declarante |
| MATRICULA | String |  | Matricula |  |
| FORMPROF | String |  | Formação Profissional |  |
| CODCBO | String |  | CBO |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| NACPROF | Integer |  | Nacionalidade | `2`=2 - Estrangeiro `1`=1 - Brasileiro |
| CPFPROF | String |  | CPF |  |

## TFPPRT — Processo Trabalhista
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPRT | Integer |  | Nro. Único |  |
| IDESEQTRAB | Integer |  | Número sequencial |  |
| CODEMP | Integer |  | Código da Empresa |  |
| RESPINDIRETA | String |  | Há responsabilidade indireta? | `N`=Não `S`=Sim |
| INCPORTALESOCIAL | String |  | Inclusão realizada via Portal do eSocial? | `N`=Não `S`=Sim |
| TPINSCEMPREGADOR | Integer |  | Tipo de inscrição | `1`=CNPJ `2`=CPF |
| NRINSCEMPREGADOR | String |  | Número de inscrição |  |
| NRPROCESSO | String |  | Número do processo |  |
| OBSPROCESSO | String |  | Obs. Processo Trabalhista |  |
| ORIGPROCESSO | Integer |  | Origem do processo | `1`=Processo Judicial `2`=Demanda submetida à CCP ou NINTER |
| DTADMRESPDIR | Date |  | Data de admissão do trabalhador no empregador de origem |  |
| MATRESPDIR | String |  | Matrícula no empregador de origem |  |
| NRORECIBOESOCIAL | String |  | Número do Recibo eSocial (S-2500) |  |
| DTSENTENCA | Date |  | Data da sentença |  |
| UFVARA | String |  | UF da Vara |  |
| CODCID | Integer |  | Código da Cidade |  |
| IDVARA | Integer |  | Identificação da Vara |  |
| DTCONCILIACAO | Date |  | Data da conciliação |  |
| DTLAUDOMOLESTIA | Date |  | Data da moléstia grave atribuída pelo laudo |  |
| AMBITOCELEBRACAO | Integer |  | Âmbito de celebração do acordo | `1`=CCP no âmbito de empresa `2`=CCP no âmbito de sindicato `3`=NINTER |
| CNPJSINDCATO | String |  | CNPJ do sindicato |  |
| TRABCONTRATDECL | String |  | Trabalhador contratado pelo declarante | `N`=Não `S`=Sim |
| CODEMPTRAB | Integer |  | Código Empresa do Trabalhador |  |
| CODFUNCTRAB | Integer |  | Código do Trabalhador |  |
| CPFTRAB | String |  | CPF do Trabalhador |  |
| NOMETRAB | String |  | Nome do Trabalhador |  |
| DTNASCTOTRAB | Date |  | Data de nascimento |  |
| CONFIRMADO | String |  | Confirmado | `N`=Não `S`=Sim |

## TFPPRTABONO — TFPPRTABONO
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUABONO | Integer |  | Número único Abono Salarial |  |
| NUICT | Integer |  | Nro. Único Info. Contrato Trabalho |  |
| ANOBASE | Date |  | Ano base indenização substitutiva abono salarial |  |

## TFPPRTC — TABLE TFPPRTC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREGFIS | Integer |  | CODREGFIS |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| NUPROCESSO | Integer |  | Número único |  |

## TFPPRTDPD — Dependente do Trabalhador
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDPD | Integer |  | Nro. Único |  |
| NUPRT | Integer |  | Nro. Único Processo |  |
| TIPODPD | Integer |  | Tipo de Dependente | `1`=Cônjuge `10`=Menor pobre do qual detenha a guarda judicial `11`=A pessoa absolutamente incapaz, da qual seja tutor ou curador `12`=Ex-cônjuge `2`=Companheiro(a) com o(a) qual tenha filho ou viva há mais de 5 (cinco) anos_(+6)_ |
| CPFDPD | String |  | CPF do Dependente |  |
| NOMEDPD | String |  | Nome do Dependente |  |
| DESCDPD | String |  | Descrição da Dependência |  |
| DTNASC | DateTime |  | Data de nascimento |  |
| DEPENDIRF | String |  | É Dependente IRRF | `N`=Não `S`=Sim |
| IDADEESCOLAR | String |  | Idade Escolar | `N`=Não `S`=Sim |
| DTLIMIRF | DateTime |  | Data limite IRRF |  |

## TFPPRTIBC — Informações Base de Cálculo
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUIBC | Integer |  | Nro. Único |  |
| NUICT | Integer |  | Nro. Único Info. Contrato Trabalho |  |
| DTREF | Date |  | Período |  |
| VLRBASECONTPREV | Float |  | Base de cálculo da contribuição previdenciária - Remuneração |  |
| VLRBASECONTPREV13 | Float |  | Base de cálculo da contribuição previdenciária - 13º salário |  |
| VLRBASECALCFGTS | Float |  | Base de cálculo do FGTS - Remuneração |  |
| VLRBASECALCFGTS13 | Float |  | Base de cálculo do FGTS - 13º salário |  |
| GRAUEXPAGNOC | Integer |  | Grau de exposição aos agentes nocivos | `1`=Não ensejador de aposentadoria especial `2`=Ensejador de aposentadoria especial - FAE15_12% (15 anos de contribuição e alíquota de 12%) `3`=Ensejador de aposentadoria especial - FAE20_09% (20 anos de contribuição e alíquota de 9%) `4`=Ensejador de aposentadoria especial - FAE25_06% (25 anos de contribuição e alíquota de 6%) |
| VLRBASECALCGUIAFGTS | Float |  | Base de cálculo guia do FGTS - Remuneração |  |
| VLRBASECALCGUIAFGTS13 | Float |  | Base de cálculo guia do FGTS - 13º salário |  |
| FGTSPAGOTRAB | String |  | FGTS transacionado pago diretamente ao trabalhador? | `N`=Não `S`=Sim |
| CODCATEG | Integer |  | Código categoria do trabalhador |  |
| VLRREMUNPREVGFIP | Float |  | Valor da remuneração para fins previdenciários declarada em GFIP ou em S-1200 |  |
| VRBCFGTSPROCTRAB | Float |  | FGTS não declarado em SEFIP/eSocial reconhecido no proc. trabalhista |  |
| VRBCFGTSSEFIP | Float |  | FGTS declarado apenas em SEFIP (não em eSocial) e não recolhido |  |
| VRBCFGTSDECANT | Float |  | FGTS declarado anteriormente no eSocial e não recolhido |  |

## TFPPRTICT — Informações do Contrato de Trabalho
Campos: 59

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUICT | Integer |  | Nro. Único |  |
| NUPRT | Integer |  | Nro. Único Processo |  |
| TIPOCONTRATO | Integer |  | Tipo de Contrato | `2`=2- Trabalhador com vínculo formalizado, com alteração na data de admissão `3`=3- Trabalhador com vínculo formalizado, com inclusão ou alteração de data de desligamento `4`=4- Trab. com vínc. formalizado, alteração na data de admissão e inclusão/alteração data de demissão `5`=5- Empregado com reconhecimento de vínculo `6`=6- Trabalhador sem vínculo de emprego/estatutário (TSVE), sem reconhecimento de vínculo empregatício_(+4)_ |
| INFOCONTENVESOCIAL | String |  | Informações sobre o contrato de trabalho enviados ao eSocial? | `N`=Não `S`=Sim |
| DTADMJUD | Date |  | Data admissão (Decisão Judicial) |  |
| DTDEMJUD | Date |  | Data desligamento (Decisão Judicial) |  |
| DTADMORIG | Date |  | Data admissão original |  |
| HOUVEREINT | String |  | Houve reintegração? | `N`=Não `S`=Sim |
| HOUVERECCATEG | String |  | Houve reconhecimento de categoria do trabalhador diferente do eSocial/GFIP? | `N`=Não `S`=Sim |
| HOUVERECNATATIV | String |  | Houve reconhecimento de natureza de atividade diferente da informada pelo declarante? | `N`=Não `S`=Sim |
| CODTPRJUD | Integer |  | Tipo de Rescisão (Decisão Judicial) |  |
| HOUVERECMOTDESLIG | String |  | Houve reconhecimento de motivo de desligamento diferente da informada pelo declarante? | `N`=Não `S`=Sim |
| HOUVERECUNCONTR | String |  | Houve reconhecimento de unicidade contratual? | `N`=Não `S`=Sim |
| MATRICULATRAB | String |  | Matrícula do trabalhador |  |
| CODCATEGTRABJUD | Integer |  | Código de categoria do trabalhador (Decisão judicial) |  |
| CODCATEGTRAB | Integer |  | Código de categoria do trabalhador |  |
| DTINICIOTSVE | Date |  | Data de início do TSVE |  |
| CODCBO | Integer |  | CBO |  |
| CODNATATIVIDADEJUD | String |  | Natureza da atividade (Decisão Judicial) | `1`=Trabalho urbano `2`=Trabalho rural |
| CODNATATIVIDADE | Integer |  | Natureza da atividade | `1`=Trabalho urbano `2`=Trabalho rural |
| TIPOREGTRAB | Integer |  | Tipo de regime trabalhista | `1`=CLT - Consolidação das Leis de Trabalho e legislações trabalhistas específicas `2`=Estatutário/legislações específicas (servidor temporário, militar, agente político, etc.) |
| DTADM | Date |  | Data de admissão |  |
| TIPOREGPREV | Integer |  | Tipo de regime previdenciário | `1`=Regime Geral de Previdência Social - RGPS `2`=RPPS - Regime Próprio de Previdência Social, Reg. Parlamentares e Sist. de Proteção de Militares `3`=Regime de Previdência Social no exterior |
| TIPOCONTRPARC | Integer |  | Tipo de contrato em tempo parcial | `0`=Não é contrato em tempo parcial `1`=Limitado a 25 horas semanais `2`=Limitado a 30 horas semanais `3`=Limitado a 26 horas semanais |
| TIPOCONTRTRAB | Integer |  | Tipo de contrato de trabalho | `1`=Prazo indeterminado `2`=Prazo determinado, definido em dias `3`=Prazo determinado, vinculado à ocorrência de um fato |
| DTTERMCONTR | Date |  | Data de término (prazo determinado) |  |
| CONTRPRAZOTERM | String |  | Contrato por prazo determinado com cláusula assecuratória? | `N`=Não `S`=Sim |
| OBJDETCONTRTERM | String |  | Objeto determinante da contratação por prazo determinado |  |
| OBSCONTRTRAB | String |  | Observações do contrato de trabalho |  |
| TIPOINSC | Integer |  | Tipo de inscrição | `1`=CNPJ `2`=CPF `5`=CGC `6`=CEI |
| NROINSC | String |  | Número de inscrição |  |
| CODMATRICULAANT | String |  | Matrícula anterior |  |
| DTTRANSF | Date |  | Data de transferência |  |
| DTDESLIG | Date |  | Data de desligamento |  |
| MTVDESLIG | String |  | Motivo de desligamento |  |
| PENSALIM | String |  | Indicativo de pensão alimentícia para fins de retenção de FGTS | `0`=Não existe pensão alimentícia `1`=Percentual de pensão alimentícia `2`=Valor de pensão alimentícia `3`=Percentual e valor de pensão alimentícia |
| PERCALIMENT | Float |  | Percentual a ser destinado a pensão alimentícia |  |
| VRALIM | Float |  | Valor da pensão alimentícia |  |
| DTFIMAVISOPREV | Date |  | Data fim do Aviso Prévio Indenizado |  |
| DTTERM | Date |  | Data de término |  |
| MTVTERM | String |  | Motivo do término do diretor não empregado com FGTS | `01`=Exoneração do diretor não empregado sem justa causa, por deliberação `02`=Término de mandato do diretor não empregado que não tenha sido reconduzido ao cargo `03`=Exoneração a pedido de diretor não empregado `04`=Exoneração do diretor não empregado por culpa recíproca ou força maior `05`=Morte do diretor não empregado_(+2)_ |
| COMPFIM | Date |  | Competência final |  |
| RESPPGTOVLR | String |  | Responsável pelo pagamento dos valores |  |
| TPINSCESTAB | Integer |  | Tipo de inscrição | `1`=CNPJ `2`=CPF `5`=CGC `6`=CEI |
| NRINSCESTAB | String |  | Número de inscrição |  |
| COMPINI | Date |  | Competência inicial |  |
| INDREPERC | String |  | Indicativo de repercussão do processo trabalhista ou de demanda submetida à CCP ou ao NINTER | `1`=Decisão com repercussão tributária e/ou FGTS com rendimentos informados em S-2501 `2`=Decisão sem repercussão tributária ou FGTS `3`=Decisão c/ repercussão exclusiva p/ declaração de rendimentos de IR com informações em 2501 `4`=Decisão c/ repercussão exclusiva p/ declaração de rendimentos de IR, pago via depósito judicial `5`=Decisão com repercussão tributária e/ou FGTS com pagamento através de depósito judicial |
| INDENSD | String |  | Decisão p/ pgto da indenização do seguro-desemprego? | `S`=Sim |
| INDENABONO | String |  | Decisão p/ pgto da indenização de abono salarial? | `S`=Sim |
| VLRTOTRENUM | Float |  | Valor total das verbas remuneratórias |  |
| REPERCPROC | Integer |  | Repercussão do processo ou demanda CCP ou NINTER | `1`=Decisão com pagamento de verbas de natureza remuneratória `2`=Decisão sem pagamento de verbas de natureza remuneratória |
| VLRAVISOPREV | Float |  | Valor Aviso Prévio Indenizado |  |
| VLR13AVISOPREV | Float |  | Valor 13º salário Aviso Prévio Indenizado |  |
| VLRTOTVERBIND | Float |  | Valor total das demais verbas indenizatórias |  |
| VLRBASEMULTFGTS | Float |  | Base de cálculo da multa rescisória do FGTS |  |
| MULTPAGATRAB | String |  | Multa rescisória paga diretamente ao trabalhador | `N`=Não `S`=Sim |
| INCLUIDTDESLIG | String |  | Incluir data de desligamento | `N`=Não `S`=Sim |
| DTDESLIGRESC | Date |  | Data de desligamento |  |
| TIPORECISCAO | Integer |  | Tipo de Rescisão |  |

## TFPPRTINTERM — Informações relativas ao trabalho intermitente
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DIA | Integer |  | Dia |  |
| HORASTRAB | String |  | Horas trabalhadas |  |
| NUIBC | Integer |  | Número único da Base de Cálculo |  |
| NUINTERM | Integer |  | Número único do Intermitente |  |

## TFPPRTIVI — Informações Vínculos/Contratos Incorporados do Trabalhador
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUIVI | Integer |  | Nro. Único |  |
| NUICT | Integer |  | Nro. Único Info. Contrato Trabalho |  |
| CODMATINC | String |  | Matricula Incorporada |  |
| CODCATEG | Integer |  | Código categoria do trabalhador |  |
| DTINITSVE | Date |  | Data de início (TSVE) |  |

## TFPPRTMCA — Mudança Categoria do Trabalhador
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMCA | Integer |  | Nro. Único |  |
| NUICT | Integer |  | Nro. Único Info. Contrato Trabalho |  |
| CODCATEG | Integer |  | Código categoria do trabalhador |  |
| NATATIVIDADE | Integer |  | Natureza da atividade | `1`=Trabalho urbano `2`=Trabalho rural |
| DTINIMUDCATEG | Date |  | Data início da categoria ou natureza |  |

## TFPPRTR — TABLE TFPPRTR
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CPFPROF | String |  | CPF |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| NROUNICO | Integer |  | NROUNICO |  |

## TFPPRTREM — Remunerações do Trabalhador
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUREM | Integer |  | Nro. Único |  |
| NUICT | Integer |  | Nro. Único Info. Contrato Trabalho |  |
| DTINIREMUN | Date |  | Data início da remuneração |  |
| VLRSALBASE | Float |  | Salário base |  |
| UNDPGTO | Integer |  | Unidade de pagamento | `1`=Por hora `2`=Por dia `3`=Por semana `4`=Por quinzena `5`=Por mês_(+2)_ |
| DSCSALVAR | String |  | Descrição do salário variável |  |

## TFPPRV — TABLE TFPPRV
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RAZAOSOCIAL | String |  | Razão Social |  |
| CNPJ | String |  | CNPJ |  |
| LISEVENTOS | String |  | Evento |  |
| CODUSU | Integer |  | Código do usuário |  |
| DHALTER | Date |  | Data de alteração |  |
| CODPREVIDENCIA | Integer |  | Código |  |

## TFPPSC — Tabela de Perfil por cargo
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPERFIL | Integer |  | Cód.Perfil |  |
| CODCARGO | Integer |  | Cód.Cargo |  |

## TFPPSF — TABLE TFPPSF
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| NUPROCESSO | Integer |  | Código do Processo |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPPSS — TABLE TFPPSS
Campos: 35

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| TIPOPROCESSO | String |  | Tipo | `J`=Judicial `A`=Administrativo `4`=Processo FAP `3`=Número de Benefício (NB) do INSS |
| INDAUTORIA | Integer |  | Autor da Ação | `2`=Outra Entidade, empresa ou empregado `1`=Próprio Contribuinte |
| NUMPROCESSO | String |  | Número do Processo |  |
| DESCRPROCESSO | String |  | Descrição |  |
| IDVARA | Integer |  | Código da Vara |  |
| INDMATPROC | Integer |  | Matéria do Processo ou Alvará Judicial (E-Social) | `99`=99 - Outros assuntos `8`=8 - Contribuição sindical `7`=7 - Exclusiv. FGTS e/ou Contribuição Social Rescisória (Lei Comp. 110/2001) `6`=6 - Conversão de Licença Saúde em Acidente de Trabalho `5`=5 - Segurança e Saúde do Trabalho_(+4)_ |
| RECIBOESOCIAL | String |  | Nro. recibo eSocial |  |
| DTINICIO | DateTime |  | DTINICIO |  |
| DTFIM | DateTime |  | DTFIM |  |
| DTDESCISAO | Date |  | Data Decisão |  |
| DCCONTRPATR | String |  | Contrib. Patronais | `S`=Sim `N`=Não |
| DCCONTRPATRSEG | String |  | Contrib. Patronais - Segurados | `S`=Sim `N`=Não |
| DCNFSERVTOMADO | String |  | DCNFSERVTOMADO |  |
| DCNFSERVPRESTADO | String |  | DCNFSERVPRESTADO |  |
| INDDESCISAO | Integer |  | INDDESCISAO |  |
| INDDEPINTEGRAL | String |  | Depósito de Montante Integral | `S`=Sim `N`=Não |
| CODCIDSECAOJUD | Integer |  | Município |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| TIPINSS | Integer |  | INSS | `4`=Licença Maternidade 13º `2`=13º Salário `1`=Normal `3`=Licença Maternidade |
| TIPIRRF | Integer |  | TIPIRRF |  |
| USADOESOCIAL | String |  | USADOESOCIAL |  |
| TPTRIB | Integer |  | TPTRIB |  |
| EXCLUSIVOEMP | String |  | Exclusivo do Empregador | `S`=Sim `N`=Não |
| USALIMITESALMIN | String |  | Contribuição a Outras Entidades limitada a base de 20 salários mínimos | `S`=Sim `N`=Não |
| INSSEMPRESA | String |  | INSS Empresa | `S`=Sim `N`=Não |
| VLRSALMINIMO | Float |  | Salário Mínimo Vigente |  |
| FGTS | String |  | FGTS | `S`=Sim `N`=Não |
| CONTRIBSINDICAL | String |  | Contribuição Sindical | `S`=Sim `N`=Não |
| INSSTRABALHADOR | String |  | INSS Retido (Trabalhador) | `S`=Sim `N`=Não |
| IRRF | String |  | IRRF | `S`=Sim `N`=Não |
| PISPASEP | String |  | PIS/PASEP | `N`=Não `S`=Sim |
| ABRANPROCESSO | Integer |  | Identificação do Processo | `9`=Contratação de aprendiz (4 - Dispensa de contratação de aprendiz) `8`=Outras Entidades/Fundos (1 - Exclusivamente tributária) `7`=Contratação Menor (2 - Autorização de trabalho de menor) `6`=Contribuição Sindical (8 - Contribuição Sindical) `5`=IRRF (1 - Exclusivamente tributária)_(+12)_ |
| NUPROCESSO | Integer |  | Número único |  |

## TFPPTANP — Pagamento de Trabalhador Avulso Não Portuário
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUPTANP | Integer |  | Nro. Único |  |
| CODEMP | Integer |  | Código da Empresa |  |
| DTREF | Date |  | Data de Referência |  |
| VLRBASEREMUN | Float |  | Base Remuneração |  |
| VLRBASEREMUN13 | Float |  | Base 13º Salário |  |
| VLRBASEFGTS | Float |  | Base Cálculo FGTS |  |
| VLRTOTDESCINSS | Float |  | Total Descontos INSS |  |
| VLRBASEAPOS15 | Float |  | Base Após 15 Anos |  |
| VLRBASEAPOS20 | Float |  | Base Após 20 Anos |  |
| VLRBASEAPOS25 | Float |  | Base Após 25 Anos |  |

## TFPPTPR — TABLE TFPPTPR
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| NUPROCESSO | Integer |  | NUPROCESSO |  |

## TFPPUB — Dados Funcionários Públicos
Campos: 53

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANUENIO | Integer |  | Anuênio |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CARTEIRAFUNC | String |  | Carteira funcional |  |
| CATEGORIA | String |  | Categoria | `S`=Servidor `J`=Juiz |
| CEDIDOREQ | String |  | Cedido ou requisitado | `R`=Requisitado `L`=Lotado `C`=Cedido |
| CLT_ESTAT | String |  | CLT ou estatutário | `C`=CLT `E`=Estatuário |
| CODDEC_1 | Integer |  | Décimo 1 |  |
| CODDEC_10 | Integer |  | Décimo 10 |  |
| CODDEC_2 | Integer |  | Décimo 2 |  |
| CODDEC_3 | Integer |  | Décimo 3 |  |
| CODDEC_4 | Integer |  | Décimo 4 |  |
| CODDEC_5 | Integer |  | Décimo 5 |  |
| CODDEC_6 | Integer |  | Décimo 6 |  |
| CODDEC_7 | Integer |  | Décimo 7 |  |
| CODDEC_8 | Integer |  | Décimo 8 |  |
| CODDEC_9 | Integer |  | Décimo 9 |  |
| CODDEP | Integer |  | Departamento de origem |  |
| CODDIV | Integer |  | Divisão |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODGRAT | Integer |  | Gratificação |  |
| CODNIVELREF | Integer |  | Nível de referência |  |
| CODORGAO | Integer |  | Órgão |  |
| CODORGORIGGRAT | Integer |  | Órgão de origem da gratificação |  |
| CODSITESTAT | Integer |  | Situação estatutário |  |
| DEPENDACIMA65A | Integer |  | Dependentes acima de 65 A |  |
| DEPENDACIMA65B | Integer |  | Dependentes acima de 65 B |  |
| DEPENDCONVMED | Integer |  | DEPENDCONVMED calculado |  |
| DTAPOSENTADORIA | DateTime |  | Data da aposentadoria |  |
| DTDESIGNACAO | DateTime |  | Data da designação |  |
| DTEXERC | DateTime |  | Data do exercício |  |
| DTINICREQ | DateTime |  | Início da requisição |  |
| DTPOSSE | DateTime |  | Data da posse |  |
| DTREDIST | DateTime |  | Data da redistribuição |  |
| DTTERMREQ | DateTime |  | Término da requisição |  |
| DTVACANCIA | DateTime |  | Data da vacância |  |
| FIMREQ | String |  | Fim da requisição | `S`=Sim `N`=Não |
| INDDEC_1 | Float |  | Índice de Décimos |  |
| INDDEC_10 | Float |  | Índice de Décimos10 |  |
| INDDEC_2 | Float |  | Índice de Décimos2 |  |
| INDDEC_3 | Float |  | Índice de Décimos3 |  |
| INDDEC_4 | Float |  | Índice de Décimos4 |  |
| INDDEC_5 | Float |  | Índice de Décimos5 |  |
| INDDEC_6 | Float |  | Índice de Décimos6 |  |
| INDDEC_7 | Float |  | Índice de Décimos7 |  |
| INDDEC_8 | Float |  | Índice de Décimos8 |  |
| INDDEC_9 | Float |  | Índice de Décimos9 |  |
| OPCAOGRAT | String |  | Opção da gratificação | `N`=Não `S`=Sim |
| SITUACAO | String |  | Situação | `A`=Ativo `I`=Inativo |
| AGREGACIMA65A | Integer |  | Agregados acima de 65 A |  |
| AGREGACIMA65B | Integer |  | Agregados acima de 65 B |  |
| AGREGPLANOA | Integer |  | Agregados plano A |  |
| AGREGPLANOB | Integer |  | Agregado plano B |  |

## TFPRCT — Receita Reclamatória Trabalhista
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODRECEITA | Integer |  | Código da Receita |  |
| DESCRECEITA | String |  | Descrição |  |
| ALIQUOTA | String |  | Alíquota |  |
| TPRECEITA | String |  | Tipo | `1`=Previdenciária/Outras Bases `2`=Redimento Tributável |

## TFPRDEF — Dados das deficiências dos funcionários na requisição de admissão
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDREQADM | Integer |  | Identificador da requisição de admissão |  |
| TIPODEFICIENCIA | Integer |  | Deficiência | `6`=Reabilitado `5`=Intelectual `4`=Mental `3`=Auditiva `2`=Visual_(+1)_ |

## TFPREGCALC — Nova Tabela de Regras para Cálculo
Campos: 216

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ABATECOMPEXTRA | String |  | ABATECOMPEXTRA |  |
| ABATPERTOLER | String |  | ABATPERTOLER |  |
| APIPORPERIODOAQUI | String |  | APIPORPERIODOAQUI |  |
| APLICALEIAPI | String |  | APLICALEIAPI |  |
| ARREDSALLIQ | Float |  | ARREDSALLIQ |  |
| ATRASODSRFER | String |  | ATRASODSRFER |  |
| ATRASODSRFERNOT | String |  | ATRASODSRFERNOT |  |
| ATRASOEXCEDENTE | String |  | ATRASOEXCEDENTE |  |
| ATRASOEXCEDENTENOT | String |  | ATRASOEXCEDENTENOT |  |
| ATRASOEXTRA | String |  | ATRASOEXTRA |  |
| ATRASOEXTRANOT | String |  | ATRASOEXTRANOT |  |
| ATRASOSUM444 | String |  | ATRASOSUM444 |  |
| ATRASOSUM444NOT | String |  | ATRASOSUM444NOT |  |
| ATUALATRASODSR | Integer |  | ATUALATRASODSR |  |
| ATUMOVMEN | String |  | ATUMOVMEN |  |
| AVOPCPORFALTAR | String |  | AVOPCPORFALTAR |  |
| BAIXAACRESCIMO | String |  | BAIXAACRESCIMO |  |
| CALCFERPERAQUI | String |  | CALCFERPERAQUI |  |
| CALCPARCFER | String |  | CALCPARCFER |  |
| CALCRESIDUO | String |  | CALCRESIDUO |  |
| CALCRESIDUOADM | String |  | CALCRESIDUOADM |  |
| CALCRESIDUOFER | String |  | CALCRESIDUOFER |  |
| CENTIRF | String |  | CENTIRF |  |
| CENTVALORES | String |  | CENTVALORES |  |
| CODEVEINDENIZA | Integer |  | CODEVEINDENIZA |  |
| CODEVENATRASO | Integer |  | CODEVENATRASO |  |
| CODEVENBHORAS | Integer |  | CODEVENBHORAS |  |
| CODEVENCRED | Integer |  | CODEVENCRED |  |
| CODEVENDEB | Integer |  | CODEVENDEB |  |
| CODEVENDFCNOT | Integer |  | CODEVENDFCNOT |  |
| CODEVENDOMIN | Integer |  | CODEVENDOMIN |  |
| CODEVENEXCNOT | Integer |  | CODEVENEXCNOT |  |
| CODEVENEXTNOT | Integer |  | CODEVENEXTNOT |  |
| CODEVENFALTAS | Integer |  | CODEVENFALTAS |  |
| CODEVENFERIADO | Integer |  | CODEVENFERIADO |  |
| CODEVENFERIADONOT | Integer |  | CODEVENFERIADONOT |  |
| CODEVENNOTUR | Integer |  | CODEVENNOTUR |  |
| CODEVENNOTURLAV | Integer |  | CODEVENNOTURLAV |  |
| CODEVENNOTURPEC | Integer |  | CODEVENNOTURPEC |  |
| CODEVENPADRAO | Integer |  | CODEVENPADRAO |  |
| CODEVENPOSPRI | Integer |  | CODEVENPOSPRI |  |
| CODEVENPRI | Integer |  | CODEVENPRI |  |
| CODEVESUM444 | Integer |  | CODEVESUM444 |  |
| CODEVESUM444NOT | Integer |  | CODEVESUM444NOT |  |
| COMPENSACAO | String |  | COMPENSACAO |  |
| COMPDSRFER | String |  | COMPDSRFER |  |
| COMPDSRFERNOT | String |  | COMPDSRFERNOT |  |
| COMPEXCEDENTE | String |  | COMPEXCEDENTE |  |
| COMPEXCEDENTENOT | String |  | COMPEXCEDENTENOT |  |
| COMPEXTRA | String |  | COMPEXTRA |  |
| COMPEXTRANOT | String |  | COMPEXTRANOT |  |
| COMPLETAUMANO | Integer |  | COMPLETAUMANO |  |
| COMPSUM444 | String |  | COMPSUM444 |  |
| COMPSUM444NOT | String |  | COMPSUM444NOT |  |
| CONSIDERAMESRESC | String |  | CONSIDERAMESRESC |  |
| CPFRESPFOLHA | String |  | CPFRESPFOLHA |  |
| DECTERCPROJETADEZ | String |  | DECTERCPROJETADEZ |  |
| DESCHRNEGJUSTAC | String |  | DESCHRNEGJUSTAC |  |
| DESCHRNEGSEMJUSTAC | String |  | DESCHRNEGSEMJUSTAC |  |
| DIARETIRADPD | Integer |  | DIARETIRADPD |  |
| DIARETIRADPDSF | Integer |  | DIARETIRADPDSF |  |
| DSRMOTORISTA | String |  | DSRMOTORISTA |  |
| DTINICIOAPURABH | DateTime |  | DTINICIOAPURABH |  |
| DTNASCRESP | DateTime |  | DTNASCRESP |  |
| ENVIADOMFERMOV | String |  | ENVIADOMFERMOV |  |
| ENVIADSRMOV | String |  | ENVIADSRMOV |  |
| ENVIAHEFALTAFOL | String |  | ENVIAHEFALTAFOL |  |
| ENVIASABMOV | String |  | ENVIASABMOV |  |
| ESTENDEADN | String |  | ESTENDEADN |  |
| EVECREDLIMSEM | Integer |  | EVECREDLIMSEM |  |
| EVEJUSTACDOMFER | Integer |  | EVEJUSTACDOMFER |  |
| EVEJUSTACFAIXA1 | Integer |  | EVEJUSTACFAIXA1 |  |
| EVEJUSTACFAIXA2 | Integer |  | EVEJUSTACFAIXA2 |  |
| EVESEMJUSTACDOMFER | Integer |  | EVESEMJUSTACDOMFER |  |
| EVESEMJUSTACFAIXA1 | Integer |  | EVESEMJUSTACFAIXA1 |  |
| EVESEMJUSTACFAIXA2 | Integer |  | EVESEMJUSTACFAIXA2 |  |
| EXCECAODUODECIMAL | String |  | EXCECAODUODECIMAL |  |
| FALTADESCDSR | String |  | FALTADESCDSR |  |
| FEVEREIRO30 | String |  | FEVEREIRO30 |  |
| HORASSEMCCT | Float |  | HORASSEMCCT |  |
| HRDIARIABCOHR | Integer |  | HRDIARIABCOHR |  |
| HREXTRAATE | Integer |  | HREXTRAATE |  |
| HRFAIXA1 | Integer |  | HRFAIXA1 |  |
| HRFAIXA2 | Integer |  | HRFAIXA2 |  |
| HRLAVOURAFIM | Integer |  | HRLAVOURAFIM |  |
| HRLAVOURAINICIO | Integer |  | HRLAVOURAINICIO |  |
| HRLIMITEDIABH | Integer |  | HRLIMITEDIABH |  |
| HRPECUARIAFIM | Integer |  | HRPECUARIAFIM |  |
| HRPECUARIAINICIO | Integer |  | HRPECUARIAINICIO |  |
| HRSEMANAL | Integer |  | HRSEMANAL |  |
| HRURBANAFIM | Integer |  | HRURBANAFIM |  |
| HRURBANAINICIO | Integer |  | HRURBANAINICIO |  |
| INCLUIREFEICAOADNOT | String |  | INCLUIREFEICAOADNOT |  |
| INDENIZADESCANSO | Integer |  | INDENIZADESCANSO |  |
| INDENIZAINTERVALO | Integer |  | INDENIZAINTERVALO |  |
| INICIOSEMANA | Integer |  | INICIOSEMANA |  |
| IRFMIN | Float |  | IRFMIN |  |
| LANCFERADIANT | String |  | LANCFERADIANT |  |
| LIMATRASODSR | Integer |  | LIMATRASODSR |  |
| LIMMINHEXTRA | Integer |  | LIMMINHEXTRA |  |
| LIMMINTOLATR | Integer |  | LIMMINTOLATR |  |
| MANTEMPERAQUIS | String |  | MANTEMPERAQUIS |  |
| MESCARENCIA | Integer |  | MESCARENCIA |  |
| MESCARENCIAATRASO | Integer |  | MESCARENCIAATRASO |  |
| MESDATABASE | Integer |  | MESDATABASE |  |
| MESESMEDIAFER | Integer |  | MESESMEDIAFER |  |
| MESPROPAVISO | String |  | MESPROPAVISO |  |
| METODOAPURABH | Integer |  | METODOAPURABH |  |
| MINDIASFER | Integer |  | MINDIASFER |  |
| NUFAIXAPGTOBH | Integer |  | NUFAIXAPGTOBH |  |
| NUFAIXARECESSO | Integer |  | NUFAIXARECESSO |  |
| NULIMITEHR | Integer |  | NULIMITEHR |  |
| PAGATRASO | Integer |  | PAGATRASO |  |
| PAGHSEXTRA | Integer |  | PAGHSEXTRA |  |
| PERCDOMFER | Float |  | PERCDOMFER |  |
| PERCHRFAIXA1 | Float |  | PERCHRFAIXA1 |  |
| PERCHRFAIXA2 | Float |  | PERCHRFAIXA2 |  |
| PRAZOMAXDIASEXP | Integer |  | PRAZOMAXDIASEXP |  |
| PROVFERMEDIAS | String |  | PROVFERMEDIAS |  |
| QUITABCOHORAS | String |  | QUITABCOHORAS |  |
| QUITAFERMENORQ10 | String |  | QUITAFERMENORQ10 |  |
| REAJUSTEPROP | String |  | REAJUSTEPROP |  |
| REGRACLTCCT | Integer |  | REGRACLTCCT |  |
| REMUMINIMA | Float |  | REMUMINIMA |  |
| SEMANASPORMES | Float |  | SEMANASPORMES |  |
| TIPARRED | String |  | TIPARRED |  |
| TIPMES | String |  | TIPMES |  |
| USAATRASOBH | String |  | USAATRASOBH |  |
| USAAVISOANOTRAB | String |  | USAAVISOANOTRAB |  |
| USACOMPENSABH | String |  | USACOMPENSABH |  |
| USACOMPSEMANAL | String |  | USACOMPSEMANAL |  |
| USAFAIXAHREXTRA | String |  | USAFAIXAHREXTRA |  |
| USAFALTABH | String |  | USAFALTABH |  |
| USAREFANTPAGTOBH | String |  | USAREFANTPAGTOBH |  |
| VERTOLERANOTOTAL | String |  | VERTOLERANOTOTAL |  |
| CODEVEINT | Integer |  | CODEVEINT |  |
| INTERVALOSEMEXTRA | String |  | INTERVALOSEMEXTRA |  |
| USAINTERVALOCARGAHR | String |  | USAINTERVALOCARGAHR |  |
| CODEVEINTRA | Integer |  | CODEVEINTRA |  |
| CODTAB | Integer |  | CODTAB |  |
| LIMMAXATRBAT | Integer |  | LIMMAXATRBAT |  |
| LIMMAXHEXTBAT | Integer |  | LIMMAXHEXTBAT |  |
| DIASPERCADSR | Integer |  | DIASPERCADSR |  |
| BATIDAEXCECAO | String |  | BATIDAEXCECAO | `S`=Sim `N`=Não |
| TIPMOVMEDIAS | String |  | TIPMOVMEDIAS |  |
| MAIORVALQTD13SRESC | Integer |  | MAIORVALQTD13SRESC |  |
| MAIORVALQTDFERRESC | Integer |  | MAIORVALQTDFERRESC |  |
| CODEVESOBREAVISO | Integer |  | CODEVESOBREAVISO |  |
| CONSIDERAMESADM | String |  | CONSIDERAMESADM |  |
| TIPOARRD | String |  | TIPOARRD |  |
| FATORARRD | Integer |  | FATORARRD |  |
| PERCHEIOCOMP | String |  | PERCHEIOCOMP |  |
| TIPOARRDMEN | String |  | TIPOARRDMEN |  |
| FATORARRDMEN | Integer |  | FATORARRDMEN |  |
| CALCCOMPPERC | String |  | CALCCOMPPERC |  |
| CALCCOMPPERCMEN | String |  | CALCCOMPPERCMEN |  |
| CONVSDOSALDIAHOR | String |  | CONVSDOSALDIAHOR |  |
| CALCLICENCAREMUNERADA | String |  | Calcula Licenca Remunerada |  |
| EXIBEVALORZERO | String |  | Imprime em branco as Rubricas obrigatórias sem valores calculados |  |
| DECTERCPROJEXCADM | String |  | Excluir os admitidos no ano da projeção do 13º salário |  |
| FPABONOLIMITADO | String |  | FPABONOLIMITADO |  |
| FERIASABONO | String |  | Possibilidade de cálculo de férias apenas com pagamento de abono pecuniário | `N`=Não `S`=Sim |
| PER13SRESC | String |  | PER13SRESC |  |
| PERFERRESC | String |  | PERFERRESC |  |
| QTDULTMESPER13S2 | Integer |  | QTDULTMESPER13S2 |  |
| QTDULTMESPER13S3 | Integer |  | QTDULTMESPER13S3 |  |
| QTDULTMESPERFER2 | Integer |  | QTDULTMESPERFER2 |  |
| QTDULTMESPERFER3 | Integer |  | QTDULTMESPERFER3 |  |
| QTDULTMESPERRESC2 | Integer |  | QTDULTMESPERRESC2 |  |
| QTDULTMESPERRESC3 | Integer |  | QTDULTMESPERRESC3 |  |
| QTDULTMESRESD | Integer |  | QTDULTMESRESD |  |
| QTDULTMESRESD2 | Integer |  | QTDULTMESRESD2 |  |
| QTDULTMESRESD3 | Integer |  | QTDULTMESRESD3 |  |
| QTDULTMESRESF | Integer |  | QTDULTMESRESF |  |
| QTDULTMESRESF2 | Integer |  | QTDULTMESRESF2 |  |
| QTDULTMESRESF3 | Integer |  | QTDULTMESRESF3 |  |
| TIPODIVD13SRESC | String |  | TIPODIVD13SRESC |  |
| TIPODIVDFERRESC | String |  | TIPODIVDFERRESC |  |
| TIPODIVS13SRESC | String |  | TIPODIVS13SRESC |  |
| TIPODIVSFERRESC | String |  | TIPODIVSFERRESC |  |
| TRESPER13S | String |  | TRESPER13S |  |
| TRESPERFER | String |  | TRESPERFER |  |
| TRESPERRESC | String |  | TRESPERRESC |  |
| USAPRIMEIROMES | String |  | USAPRIMEIROMES |  |
| FERPROPERAQUI | String |  | FERPROPERAQUI |  |
| ABATEACRESCCRED | String |  | ABATEACRESCCRED |  |
| ABATEFERDIVD | String |  | ABATEFERDIVD |  |
| ABATEFERDIVS | String |  | ABATEFERDIVS |  |
| CODREGCALC | Integer |  | Código |  |
| CODUSU | Integer |  | CODUSU |  |
| CONSIDERAMEDIAPROV | String |  | CODUSU |  |
| DESCRICAO | String |  | DESCRICAO |  |
| DOISPER13S | String |  | DOISPER13S |  |
| DOISPERFER | String |  | DOISPERFER |  |
| DOISPERRESC | String |  | DOISPERRESC |  |
| MAIORVALQTD13S | Integer |  | MAIORVALQTD13S |  |
| MAIORVALQTDFER | Integer |  | MAIORVALQTDFER |  |
| MAIORVALQTDRESC | Integer |  | MAIORVALQTDRESC |  |
| MOVMEDIAS | String |  | MOVMEDIAS |  |
| PER13S | String |  | PER13S |  |
| PERFER | String |  | PERFER |  |
| PERRESC | String |  | PERRESC |  |
| QTDULTMESPER13S | Integer |  | QTDULTMESPER13S |  |
| QTDULTMESPERFER | Integer |  | QTDULTMESPERFER |  |
| QTDULTMESPERRESC | Integer |  | QTDULTMESPERRESC |  |
| RESPFOLHA | String |  | RESPFOLHA |  |
| TIPODIVD13S | String |  | TIPODIVD13S |  |
| TIPODIVDFER | String |  | TIPODIVDFER |  |
| TIPODIVDRESC | String |  | TIPODIVDRESC |  |
| TIPODIVS13S | String |  | TIPODIVS13S |  |
| TIPODIVSFER | String |  | TIPODIVSFER |  |
| TIPODIVSRESC | String |  | TIPODIVSRESC |  |
| DIVHOMOLOGNET | String |  | DOISPER13S |  |
| CALCRESIDUORESC | String |  | CALCRESIDUORESC |  |
| SUSPCONTDEC | String |  | SUSPCONTDEC | `S`=Sim `N`=Não |
| SUSPCONTFER | String |  | SUSPCONTFER | `S`=Sim `N`=Não |

## TFPREGCALCHIST — Tabela de histórico de regras de calculo
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FERIASABONO | String |  | Possibilidade de cálculo de férias apenas com pagamento de abono pecuniário | `N`=Não `S`=Sim |
| CODEVESOBREAVISO | Integer |  | CODEVESOBREAVISO |  |
| CALCRESIDUO | String |  | CALCRESIDUO |  |
| CALCRESIDUOADM | String |  | CALCRESIDUOADM |  |
| CALCRESIDUOFER | String |  | CALCRESIDUOFER |  |
| CODREGCALC | Integer |  | CODREGCALC |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | Date |  | DHALTER |  |
| DOISPER13S | String |  | DOISPER13S |  |
| DOISPERFER | String |  | DOISPERFER |  |
| DOISPERRESC | String |  | DOISPERRESC |  |
| FEVEREIRO30 | String |  | FEVEREIRO30 |  |
| MAIORVALQTD13S | Integer |  | MAIORVALQTD13S |  |
| MAIORVALQTDFER | Integer |  | MAIORVALQTDFER |  |
| MAIORVALQTDRESC | Integer |  | MAIORVALQTDRESC |  |
| MOVMEDIAS | String |  | MOVMEDIAS |  |
| PER13S | String |  | PER13S |  |
| PERFER | String |  | PERFER |  |
| PERRESC | String |  | PERRESC |  |
| QTDULTMESPER13S | Integer |  | QTDULTMESPER13S |  |
| QTDULTMESPERFER | Integer |  | QTDULTMESPERFER |  |
| QTDULTMESPERRESC | Integer |  | QTDULTMESPERRESC |  |
| TIPMES | String |  | TIPMES |  |
| TIPODIVD13S | String |  | TIPODIVD13S |  |
| TIPODIVDFER | String |  | TIPODIVDFER |  |
| TIPODIVDRESC | String |  | TIPODIVDRESC |  |
| TIPODIVS13S | String |  | TIPODIVS13S |  |
| TIPODIVSFER | String |  | TIPODIVSFER |  |
| TIPODIVSRESC | String |  | TIPODIVSRESC |  |
| ABATEFERDIVD | String |  | ABATEFERDIVD |  |
| ABATEFERDIVS | String |  | ABATEFERDIVS |  |
| CALCRESIDUORESC | Integer |  | CALCRESIDUORESC |  |

## TFPREI — Reintegração de funcionários
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| TPREINT | Integer |  | Tipo de Reintegração | `9`=9 - Outros `5`=5 - Reinclusão de Militar `4`=4 - Recondução de Servidor Público `3`=3 - Resersão de Servidor Público `2`=2 - Reintegração por Anistia Legal_(+1)_ |
| PROCJUD | String |  | Número do Processo Judicial |  |
| LEIANISTIA | Integer |  | Lei de Anistia | `6`=6 - LEI 11.282/2006 `5`=5 - LEI 10.790/2003 `4`=4 - LEI 10.559/2002 `3`=3 - LEI 8.878/1994 `2`=2 - LEI 8.632/1993_(+1)_ |
| DTEFETRETORNO | Date |  | Data do Efetivo Retorno |  |
| DTEFEITO | Date |  | Data do Efeito |  |
| INDPAGTOJUIZO | String |  | Pagamento das remunerações e contribuições em juízo | `S`=Sim `N`=Não |
| CODHISTOCOR | Integer |  | Histórico de Ocorrência |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODREINT | Integer |  | Código |  |

## TFPRELRUBAGT — TFPRELRUBAGT
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODRUBXML | String |  | Código Rubrica e-Social |  |
| DSCRUBRXML | String |  | Descrição Rubrica e-Social |  |
| CODEVENTO | Integer |  | Evento Sistema |  |

## TFPREQ — Tabela das requisições
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTCRIACAO | DateTime |  | DTCRIACAO |  |
| CODFUNC | Integer |  | CODFUNC |  |
| CODEMP | Integer |  | CODEMP |  |
| STATUS | Integer |  | STATUS |  |
| PRIORIDADE | Integer |  | PRIORIDADE |  |
| DTLIMITE | DateTime |  | DTLIMITE |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| ORIGEMTIPO | String |  | ORIGEMTIPO |  |
| ORIGEMID | Integer |  | ORIGEMID |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| ID | Integer |  | ID |  |

## TFPREQACS — Requisição de alteração de cargo e sálario
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Código da Empresa do Funcionário |  |
| CODFUNC | Integer |  | Código do Funcionário |  |
| DHSOLICIT | DateTime |  | Data e Hora da Solicitação |  |
| STATUS | String |  | Status |  |
| CARGO | Integer |  | Código do Cargo do Funcionário |  |
| CARGOANTIGO | Integer |  | Código antigo do Cargo do Funcionário |  |
| CODHISTOCORCAR | Integer |  | Código Histórico Ocorrência Cargo |  |
| DESCRHISTOCORCAR | String |  | Descrição Histórico Ocorrência Cargo |  |
| SALARIO | Float |  | Salário |  |
| SALARIOANTIGO | Float |  | Salário Antigo |  |
| CODHISTOCORSAL | Integer |  | Código Histórico Ocorrência Salário |  |
| DESCRHISTOCORSAL | String |  | Descrição Histórico Ocorrência Salário |  |
| DTEFETIVACAO | DateTime |  | Data de Efetivação |  |
| EFETIVADO | String |  | Efetivado |  |
| FUNCAO | Integer |  | Código da Função do Funcionário |  |
| FUNCAOANTIGA | Integer |  | Código da Função Antiga do Funcionário |  |
| CODHISTOCORFUN | Integer |  | Código Histórico Ocorrência Função |  |
| DESCRHISTOCORFUN | String |  | Descrição Histórico Ocorrência Função |  |
| ID | Integer |  | ID |  |

## TFPREQADM — Requisição de admissão
Campos: 126

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Código da Empresa do Funcionário |  |
| CODDEP | Integer |  | Código do Departamento |  |
| CODCARGO | Integer |  | Código do Cargo do Funcionário |  |
| DTADM | Date |  | Data da Admissão do Funcionário |  |
| SALBASE | Float |  | Salário Base do Funcionário |  |
| NOMEFUNC | String |  | Nome do Funcionário |  |
| CPF | String |  | CPF do Funcionário |  |
| EMAIL | String |  | Email pessoal do Funcionário |  |
| OBSERVACAO | String |  | Observação Livre |  |
| ID | Integer |  | ID |  |
| TMPRESIDTRABESTRANG | String |  | Tempo de Residência do Trabalhador Estrangeiro | `1`=Prazo Indeterminado `2`=Prazo Determinado |
| CASADOBR | String |  | Casado no Brasil | `N`=Não `S`=Sim |
| FILHOSBR | String |  | Filhos no Brasil | `N`=Não `S`=Sim |
| CATEGORIACNH | String |  | Categoria CNH |  |
| CELULAR | String |  | Celular |  |
| CEP | String |  | Cep |  |
| CIDNASC | Integer |  | Cidade Nascimento |  |
| CLASSTRABESTRANG | Integer |  | Classificação de trabalhadores estrangeiros | `1`=1 - Refugiado `2`=2 - Solicitante de refúgio `3`=3 - Permanência no Brasil em razão de reunião familiar `4`=4 - Beneficiado pelo acordo entre países do Mercosul `5`=5- Dependente de agente diplomático e/ou consular com acordo de reciprocidade e atividade remunerada_(+2)_ |
| CODADMFGTS | String |  | Tabela de Ocorrência FGTS | `00`=Não exposição a agente nocivo `01`=Não exposição a agente nocivo, mas já esteve `02`=Exposição a agente nocivo (aposentadoria aos 15) `03`=Exposição a agente nocivo (aposentadoria aos 20) `04`=Exposição a agente nocivo (aposentadoria aos 25)_(+4)_ |
| CODADMFGTSII | String |  | Tabela de Categoria FGTS | `00`=Estagiários `01`=Empregados `02`=Trabalhador avulso `03`=Trabalhador sem RGPS mas com direito ao FGTS `04`=Empregado com contrato temporário ou intermitente_(+14)_ |
| CODAGE | String |  | Código da agência |  |
| CODBAI | Integer |  | Código do bairro |  |
| CODBCO | Integer |  | Código do banco |  |
| CODCARGAHOR | Integer |  | Código de identificação da carga horária |  |
| CODCATEG | Integer |  | Código da categoria |  |
| CODCATEGESOCIAL | Integer |  | Código de Categoria eSocial |  |
| CODCID | Integer |  | Código da cidade |  |
| CODCIDTRAB | Integer |  | Código da cidade de trabalho |  |
| CODCTABCO | Integer |  | Número da conta bancária |  |
| CODEND | Integer |  | Código do endereço |  |
| CODFUNCAO | Integer |  | Código da função |  |
| CODGRUPOCTBZ | Integer |  | Código do grupo contábil |  |
| CODPAIS | Integer |  | Código do país |  |
| CODSIND | Integer |  | Código do sindicato |  |
| COMPLEMENTO | String |  | Complemento do endereço |  |
| COMPLEMENTORG | String |  | Complemento RG |  |
| CTPSDIGITAL | String |  | CTPS Digital | `N`=Não `S`=Sim |
| DEFICIENTEFISICO | String |  | Deficiente físico | `N`=Não `S`=Sim |
| DISPPEREXP | String |  | Dispensa período de experiência | `N`=Não `S`=Sim |
| DTCHEGPAIS | Date |  | Data de chegada ao país |  |
| DTCPS | Date |  | Data da CTPS |  |
| DTEXPCNH | Date |  | Data de expiração da CNH |  |
| DTEXPRNE | Date |  | Data de expiração do RNE |  |
| DTNASC | Date |  | Data de nascimento |  |
| DTRG | Date |  | Data de emissão do RG |  |
| DTVENCEXP1 | Date |  | Data de vencimento do período de experiência 1 |  |
| DTVENCEXP2 | Date |  | Data de vencimento do período de experiência 2 |  |
| EINTEGRACAO | String |  | Lançado via integração | `N`=Não `S`=Sim |
| ESTADOCIVIL | Integer |  | Estado Civil | `1`=Solteiro(a) `2`=Casado(a) `3`=Viúvo(a) `4`=Separado(a) Judicialmente `5`=Desquitado(a)_(+2)_ |
| POSSUIFILHOS | String |  | Possui Filhos | `N`=Não `S`=Sim |
| HORASSEM | Float |  | Horas semanais |  |
| IDENTIDADE | String |  | Identidade |  |
| IDENTIDADEGENERO | String |  | Identidade de gênero | `C`=Cisgênero `N`=Não-binário `T`=Transgênero `U`=Não informado |
| IMAGEM | Boolean |  | Imagem |  |
| IMPACTO | Integer |  | Impacto |  |
| INDADMISSAO | Integer |  | Indicador de Admissão | `1`=Normal `2`=Decorrente Ação Fiscal `3`=Decorrente Decisão Judicial |
| MEI | String |  | Microempreendedor Individual (MEI) | `N`=Não `S`=Sim |
| NACIONALIDADE | Integer |  | Nacionalidade | `10`=10 - Brasileiro `20`=20 - Naturalizado Brasileiro `21`=21 - Argentino `22`=22 - Boliviano `23`=23 - Chileno_(+31)_ |
| NIVESC | Integer |  | Escolaridade | `1`=Analfabeto `10`=Mestrado Completo `11`=Doutorado Completo `12`=Pós-Graduação Completa `2`=Até 5º Ano Incompleto_(+7)_ |
| NOMEMAE | String |  | Nome da Mãe |  |
| NOMEPAI | String |  | Nome do Pai |  |
| NOMESOCIAL | String |  | Nome Social |  |
| NOVATOFINALIZOU | String |  | Novato Finalizou | `N`=Não `S`=Sim |
| NROCNH | String |  | Número da CNH |  |
| NRORESERVISTA | String |  | Número da Reservista |  |
| NUMCPS | Integer |  | Número da CTPS |  |
| NUMEND | String |  | Número do Endereço |  |
| NUPADRAO | Integer |  | Código do padrão de cadastro |  |
| OBSDEFICIENCIA | String |  | Observação sobre Deficiência |  |
| OPTFGTS | Integer |  | Optante pelo FGTS? | `0`=Não `1`=Sim |
| ORGAORG | String |  | Órgão emissor RG |  |
| ORGAORNE | String |  | Órgão emissor RNE |  |
| ORIENTACAOSEXUAL | String |  | Orientação Sexual | `A`=Assexual `B`=Bissexual `E`=Heterossexual `H`=Homossexual `N`=Não informado_(+1)_ |
| PERCADIANTAMENTO | Float |  | Percentual de Adiantamento |  |
| PERCINSAL | Float |  | Percentual de Insalubridade |  |
| PERCPERIC | Float |  | Percentual de Periculosidade |  |
| PIS | String |  | Programa de Integração Social (PIS) |  |
| PRIMEMPREGO | String |  | Tipo de admissão | `A`=Transferência de outro estabelecimento da mesma empresa sem ônus `H`=Admissão por sucessão, incorporação e cisão/fusão `N`=Admissão com emprego anterior `O`=Outros encerramentos `R`=Reintegração_(+3)_ |
| RACAFUNCIONARIO | Integer |  | Raça do Funcionário | `0`=Indígena `2`=Branca `4`=Preta `6`=Amarela `8`=Parda_(+1)_ |
| REGIME | Integer |  | Regime de Previdência | `1`=RPPS - Regime Próprio de Previdência Social, Reg. Parlamentares e Sist. de Proteção de Militares `2`=RGPS - Regime Geral Previdência Social `3`=RPPS em extinção `4`=RPPE - Regime Próprio Prev. Social Exterior |
| REGIMEJOR | Integer |  | Regime de Jornada de Trabalho | `1`=Submetidos Horário Trabalho (Cap. II CLT) `2`=Atividade Externa conf.Inciso I Art. 62 CLT `3`=Funções conf.Inciso II Art. 62 CLT `4`=Teletrabalho, previsto Inciso III Art. 62 CLT |
| REGIMETRAB | Integer |  | Regime de Trabalho | `1`=CLT - Consolidação das Leis de Trabalho `2`=RJU - Regime Jurídico Único `3`=RJP - Regime Jurídico Próprio |
| REMUNBASE | Float |  | Remuneração Base |  |
| RNE | String |  | RNE (Registro Nacional de Estrangeiro) |  |
| SECAOELEITORAL | String |  | Seção Eleitoral |  |
| SERIECPS | String |  | Série CPS |  |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| SINDICALIZADO | String |  | Filiado ao sindicato de classe? | `N`=Não `S`=Sim |
| TELEFONE | String |  | Telefone |  |
| TIPCONTA | String |  | Tipo de conta bancária | `A`=Aplicação `C`=Corrente `P`=Poupança `S`=Salário |
| TIPOREMUNERACAO | String |  | Tipo de Remuneração | `1`=Salário Fixo `2`=Variável `3`=Sal. Fixo + Variável |
| TIPSAL | String |  | Tipo de Salário | `1`=Mensal `2`=Quinzenal `3`=Semanal `4`=Diarista `5`=Horista_(+1)_ |
| TIPTAB | String |  | Tipo de Tabela |  |
| TITELEITORAL | String |  | Título Eleitoral |  |
| UFCNH | Integer |  | Unidade Federativa (CNH) |  |
| UFCPS | Integer |  | Unidade Federativa (CPS) |  |
| UFENDERECO | Integer |  | Unidade Federativa Endereço |  |
| UFRG | Integer |  | Unidade Federativa (RG) |  |
| VENCIMENTOCNH | Date |  | Vencimento da CNH |  |
| VINCULO | Integer |  | Tipo de vínculo | `02`=Estagiário `10`=Prazo indeterminado pessoa jurídica `15`=Prazo indeterminado pessoa física `20`=Prazo indeterminado rural (jurídica) `25`=Prazo indeterminado rural (física)_(+16)_ |
| ZONAELEITORAL | String |  | Zona Eleitoral |  |
| CADINI | String |  | Cadastro Inicial | `N`=Não `S`=Sim |
| CODIGOFILA | String |  | Código da fila de envio de e-mails |  |
| CODVAGA | String |  | Código da Vaga |  |
| DTCADPIS | Date |  | Data de Cadastro no PIS |  |
| DTEMIPPORTE | Date |  | Data de Emissão do Passaporte |  |
| DTOPTFGTS | Date |  | Data de Opção pelo FGTS |  |
| DTTERMINO | Date |  | Data de Término |  |
| DTVALPPORTE | Date |  | Data de Validade do Passaporte |  |
| EMISSORPPORTE | String |  | Emissor do Passaporte |  |
| INFOCOTA | String |  | Preenche Cota de PCD's? | `N`=Não `S`=Sim |
| NOVOEMPREGO | String |  | Novo Emprego | `N`=Não `S`=Sim |
| NROPASSAPORTE | String |  | Número do Passaporte |  |
| OPCIONAIS | String |  | Opcionais |  |
| ORGAOCNH | String |  | Órgão Emissor da CNH |  |
| POSSUICONVMED | String |  | Possui Convênio Médico | `N`=Não `S`=Sim |
| POSSUICONVODO | String |  | Possui Convênio Odontológico | `N`=Não `S`=Sim |
| POSSUISEGVIDA | String |  | Possui Seguro de Vida | `N`=Não `S`=Sim |
| POSSUITRANS | String |  | Possui vale transporte | `N`=Não `S`=Sim |
| POSSUIVAVR | String |  | Possui Vale Alimentação/Vale Refeição | `N`=Não `S`=Sim |
| PRIMEIRACNH | Date |  | Data da primeira CNH |  |
| TIPDEFICIENCIA | Integer |  | Tipo de Deficiência |  |
| TRABOUTRAEMP | String |  | Trabalha em Outra Empresa | `N`=Não `S`=Sim |
| UFNASC | Integer |  | Unidade Federativa de Nascimento |  |
| UFPPORTE | Integer |  | Unidade Federativa do Passaporte |  |
| CODLOCALPONTO | Integer |  | Código do Local de Trabalho |  |

## TFPREQADMDPD — Dependente da Requisição de Admissão
Campos: 45

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ADOTIVO | String |  | Filho Adotivo | `N`=Não `S`=Sim |
| AUXCRE | String |  | Tem Auxílio Creche | `N`=Não `S`=Sim |
| CODEMPFUNCRESPONSAVEL | Integer |  | Código de empresa do funcionário responsável |  |
| CONVENIO | String |  | Dependente de Convênio Médico | `N`=Não `S`=Sim |
| CPF | String |  | CPF |  |
| CPFFUNCRESPONSAVEL | String |  | CPF do responsável |  |
| DEPENDIRF | String |  | Dependente de IRRF | `N`=Não `S`=Sim |
| DESCRDPD | String |  | Descrição da Dependência |  |
| DTNASC | Date |  | Data de nascimento |  |
| GRAUPARENT | Integer |  | Grau de parentesco | `1`=Filho(a) `10`=Irmão(ã), Neto(a) ou Bisneto(a) Incapaz `11`=Menor (Até 21 Anos) sem Condições Financeiras `12`=Companheiro(a) com filho ou mais de 5 (cinco) anos em união `13`=Ex-cônjuge que Receba Pensão de Alimentos_(+13)_ |
| IDADEESCOLAR | String |  | Em idade escolar | `N`=Não `S`=Sim |
| IDREQADM | Integer |  | Código da requisição de admissão |  |
| INCTRAB | String |  | Possui Incapacidade Física ou Mental para o Trabalho | `N`=Não `S`=Sim |
| NOME | String |  | Nome |  |
| NOMEMAE | String |  | Nome da Mãe |  |
| PENSIONISTA | String |  | Pensionista | `N`=Não `S`=Sim |
| PERCPENSAO | Float |  | Percentual da Pensão |  |
| RACAETNIA | Integer |  | Raça/Etnia | `10`=Indígena `20`=Branca `30`=Preta `40`=Parda `50`=Amarela_(+1)_ |
| REPSALPENSIONISTA | String |  | Repassa Salário Família ao Pensionista | `N`=Não `S`=Sim |
| SALFAM | String |  | Dependente de Salário família | `N`=Não `S`=Sim |
| SEQUENCIA | Integer |  | Sequência |  |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| VLRPENSAO | Float |  | Valor da Pensão |  |
| CARTORIO | String |  | Nome do cartório |  |
| CODCID | Integer |  | Naturalidade |  |
| CODFUNCPENS | Integer |  | Código do Pensionista |  |
| CODPARC | Integer |  | Parceiro Responsável pelo recebimento da Pensão |  |
| DNV | String |  | DNV |  |
| DTFIMDEPEND | Date |  | Data Final da Dependência |  |
| DTINICDEPEND | Date |  | Data Inicial da Dependência |  |
| DTLIMAUXCRE | Date |  | Data Limite do Auxílio Creche |  |
| DTLIMIRF | Date |  | Data limite do IRRF |  |
| DTLIMSALFAM | Date |  | Data Limite do Salário Família |  |
| MOTIVOFIM | Integer |  | Motivo do Fim da Dependência | `50`=Maioridade `51`=Óbito `52`=Separação judicial `53`=Divórcio `54`=Emancipação_(+5)_ |
| MOTIVOINICIO | Integer |  | Motivo do Início da Dependência | `10`=Nascimento `11`=Invalidez `12`=Casamento `13`=União estável `14`=Adoção_(+5)_ |
| NACIONALIDADE | Integer |  | Nacionalidade | `10`=Brasileiro `20`=Naturalizado Brasileiro `21`=Argentino `22`=Boliviano `23`=Chileno_(+31)_ |
| NROFOLHAREG | Integer |  | Número da Folha do Livro de Registro |  |
| NROLIVROREG | String |  | Número do Livro de Registro |  |
| NROREG | String |  | Número do Registro |  |
| PERCHNETFGTS | Float |  | Percentual do FGTS |  |
| PERCHOMOLOGNET | Float |  | Percentual do Homolognet |  |
| PERCREPASSEPENSIONISTA | Float |  | Percentual de Repasse ao Pensionista |  |
| SEMATESTADO | String |  | Não Apresentou Atestado | `N`=Não `S`=Sim |
| SEMATESTCRECHE | String |  | Não Apresentou Atestado | `N`=Não `S`=Sim |
| TIPOPENSAO | String |  | Tipo da Pensão | `B`=Bruto `L`=Líquido `P`=Personalizado `S`=Salário Mínimo |

## TFPRGPR — TABLE TFPRGPR
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODREGPRELIMINAR | Integer |  | Código |  |
| CODEMP | Integer |  | Empresa |  |
| MATRICULA | Integer |  | Matrícula |  |
| NOMEFUNC | String |  | Nome do Funcionário |  |
| CPF | String |  | CPF |  |
| DTADM | Date |  | Data de Admissão |  |
| DTNASC | Date |  | Data de Nascimento |  |
| VINCULO | Integer |  | Vínculo | `99`=99 - Pensionista `90`=90 - Autônomo `80`=80 - Diretor sem vínculo empregatício `75`=75 - Prazo determinado rural (física) `70`=70 - Prazo determinado rural (jurídica)_(+12)_ |
| CODCATEGESOCIAL | Integer |  | Código de Categoria para o eSocial |  |
| CODCAR | Integer |  | Código do Cargo do Funcionário |  |
| CODFCO | Integer |  | Código de Função do Funcionário |  |
| DTTERMINO | Date |  | Data Término Contrato |  |
| NATATIVIDADE | String |  | Natureza da Atividade | `P`=Rural `U`=Urbano |
| TIPSAL | String |  | Tipo de salário | `6`=Tarefa `5`=Horista `4`=Diarista `3`=Semanal `2`=Quinzenal_(+1)_ |
| SALBASE | Float |  | Salário base |  |
| SALPROFESSOR | Float |  | Salário Professor |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODFUNC | Integer |  | Código do funcionário |  |

## TFPRNE — Processos- Tributos (S-1210)
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NURNE | Integer |  | No. único Retenção |  |
| NUPROCESSO | Integer |  | Nro. único processo |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| DTPAGAMENTO | Date |  | Data de Pagamento |  |
| REFERENCIA | Date |  | Referência |  |
| INDAPURACAO | String |  | Indicativo de período de apuração | `1`=1 - Mensal `2`=2 - Anual (13° salário) |
| VLRNAORETIDO | Float |  | Imposto de Renda não retido |  |
| VLRDEPJUD | Float |  | Depósito Judicial |  |
| VLRCMPANOCAL | Float |  | Compensação Ano Atual |  |
| VLRCMPANOANT | Float |  | Compensação Anos Anteriores |  |
| VLRRENDSUSP | Float |  | Rendimento com exigibilidade suspensa |  |
| INDDEPOSITO | String |  | Depósito de montante integral |  |
| TIPOPROCESSO | String |  | Tipo do Processo |  |

## TFPROE — TABLE TFPROE
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CGCCPF | String |  | CNPJ / CPF |  |
| CODCATEG | Integer |  | Categoria do eSocial |  |
| CODUSU | Integer |  | Usuário |  |
| DTDEM | Date |  | Data do Desligamento |  |
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| DHALTER | DateTime |  | DHALTER |  |

## TFPRPO — TABLE TFPRPO
Campos: 77

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | CODFUNC |  |
| DTMOV | DateTime |  | DTMOV |  |
| ENTRADA1 | Integer |  | ENTRADA1 |  |
| SAIDA1 | Integer |  | SAIDA1 |  |
| ENTRADA2 | Integer |  | ENTRADA2 |  |
| SAIDA2 | Integer |  | SAIDA2 |  |
| ENTRADA3 | Integer |  | ENTRADA3 |  |
| SAIDA3 | Integer |  | SAIDA3 |  |
| ENTRADA4 | Integer |  | ENTRADA4 |  |
| SAIDA4 | Integer |  | SAIDA4 |  |
| NORMAL | Integer |  | NORMAL |  |
| FALTAS | Integer |  | FALTAS |  |
| ATRASOS | Integer |  | ATRASOS |  |
| EXTRA | Integer |  | EXTRA |  |
| EXCEDENTE | Integer |  | EXCEDENTE |  |
| DOMFER | Integer |  | DOMFER |  |
| NOTURNA | Integer |  | NOTURNA |  |
| EXTRANOT | Integer |  | EXTRANOT |  |
| EXCEDENTENOT | Integer |  | EXCEDENTENOT |  |
| DOMFERNOT | Integer |  | DOMFERNOT |  |
| ATESTADO | Integer |  | ATESTADO |  |
| LICENCA | Integer |  | LICENCA |  |
| COMPENSACAO | Integer |  | COMPENSACAO |  |
| FERIAS | Integer |  | FERIAS |  |
| FERIADO | Integer |  | FERIADO |  |
| AFASTAMENTO | Integer |  | AFASTAMENTO |  |
| BONIFICADO | Integer |  | BONIFICADO |  |
| TRABALHADO | Integer |  | TRABALHADO |  |
| ABSENTEISMO | Integer |  | ABSENTEISMO |  |
| TOTAL | Integer |  | TOTAL |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| PREVISTO | Integer |  | PREVISTO |  |
| MOVFOLHA | Integer |  | MOVFOLHA |  |
| APONTAMENTOS | String |  | APONTAMENTOS |  |
| CODCARGAHOR | Integer |  | CODCARGAHOR |  |
| NUOCOR | Integer |  | NUOCOR |  |
| SUMULA444 | Integer |  | SUMULA444 |  |
| ATUALIZADO | String |  | ATUALIZADO |  |
| SEQCARGAHORARIA | Integer |  | SEQCARGAHORARIA |  |
| EHFERIADO | String |  | EHFERIADO |  |
| DESCANSOSEM | String |  | DESCANSOSEM |  |
| BHFALTA | String |  | BHFALTA |  |
| BHATRASOS | Integer |  | BHATRASOS |  |
| ENTRADA5 | Integer |  | ENTRADA5 |  |
| SAIDA5 | Integer |  | SAIDA5 |  |
| ENTRADA6 | Integer |  | ENTRADA6 |  |
| SAIDA6 | Integer |  | SAIDA6 |  |
| ENTRADA7 | Integer |  | ENTRADA7 |  |
| SAIDA7 | Integer |  | SAIDA7 |  |
| ENTRADA8 | Integer |  | ENTRADA8 |  |
| SAIDA8 | Integer |  | SAIDA8 |  |
| NUOCOR1 | Integer |  | NUOCOR1 |  |
| NUOCOR2 | Integer |  | NUOCOR2 |  |
| NUOCOR3 | Integer |  | NUOCOR3 |  |
| NUOCOR4 | Integer |  | NUOCOR4 |  |
| NUOCOR5 | Integer |  | NUOCOR5 |  |
| NUOCOR6 | Integer |  | NUOCOR6 |  |
| NUOCOR7 | Integer |  | NUOCOR7 |  |
| NUOCOR8 | Integer |  | NUOCOR8 |  |
| NUOCOR9 | Integer |  | NUOCOR9 |  |
| NUOCOR10 | Integer |  | NUOCOR10 |  |
| NUOCOR11 | Integer |  | NUOCOR11 |  |
| NUOCOR12 | Integer |  | NUOCOR12 |  |
| NUOCOR13 | Integer |  | NUOCOR13 |  |
| NUOCOR14 | Integer |  | NUOCOR14 |  |
| NUOCOR15 | Integer |  | NUOCOR15 |  |
| NUOCOR16 | Integer |  | NUOCOR16 |  |
| DTFECHAMENTO | DateTime |  | DTFECHAMENTO |  |
| PORTALRH | String |  | PORTALRH |  |
| QTDPREV | Integer |  | QTDPREV |  |
| QTDPBAT | Integer |  | QTDPBAT |  |
| BATIDAS | String |  | BATIDAS |  |
| SOBREAVISO | Integer |  | SOBREAVISO |  |
| TEMSOBREAVISO | String |  | TEMSOBREAVISO |  |
| INTRAJORNADA | Integer |  | INTRAJORNADA |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPRRA — TABLE TFPRRA
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NISRESP | String |  | NIS Responsável |  |
| NMRESP | String |  | Nome Responsável |  |
| IDEOC | Integer |  | Órgão de Classe | `9`=9 - Outros `1`=1 - Conselho Regional de Medicina (CRM) `3`=3 - Registro do Ministério da Saúde (RMS) `2`=2 - Conselho Regional de Odontologia (CRO) `4`=4 - Conselho Regional de Engenharia e Agronomia (CREA) |
| DSCOC | String |  | Descrição do Órgão de Classe |  |
| NROC | String |  | Inscrição no Órgão de Classe |  |
| UFOC | String |  | UF Órgão de Classe | `TO`=TO - Tocantins `SP`=SP - São Paulo `SE`=SE - Sergipe `SC`=SC - Santa Catarina `RS`=RS - Rio Grande do Sul_(+23)_ |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CPFRESP | String |  | CPF Responsável |  |

## TFPRTE — Composição Rateio
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEVENTO | Integer |  | Evento Base |  |
| CODUSU | Integer |  | CODUSU |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODCRIRATEIO | Integer |  | CODCRIRATEIO |  |

## TFPRTF — Rateio por Funcionário
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Cód.Funcinário |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODPROJ | Integer |  | Cód.Projeto |  |
| DHALTER | DateTime |  | Data e hora da alteração |  |
| PERCRATEIO | Float |  | Percentual de Rateio |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TFPRTM — Rateio na TFPMOV
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODFUNC | Integer |  | CODFUNC |  |
| CODEVENTO | Integer |  | CODEVENTO |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODPROJ | Integer |  | CODPROJ |  |
| PERCRATEIO | Float |  | PERCRATEIO |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| REFERENCIA | DateTime |  | Referência |  |

## TFPRUB — Natureza Rubrica
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMENATRUBRICA | String |  | NOMENATRUBRICA |  |
| INCCPEXCLUSIVOSEGURADO | String |  | Incidência para Previdência Exclusiva do Segurado |  |
| DESCRNATRUBRICA | String |  | DESCRNATRUBRICA |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| DTFIMVALIDADERUB | DateTime |  | Data Fim da Validade da Rúbrica |  |
| CODNATRUBRICA | Integer |  | CODNATRUBRICA |  |

## TFPS1000 — S-1000 - Empregador
Campos: 47

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr de Inscrição do Empregador |  |
| NMRAZAO | String |  | Razão Social |  |
| CLASSTRIB | String |  | Classificação Tributária |  |
| NATJURID | Integer |  | Natureza Jurídica do Contribuinte |  |
| INDCOOP | Integer |  | Ind. Cooperativa |  |
| INDCONSTR | Integer |  | Ind. Construtora |  |
| INDDESFOLHA | Integer |  | Ind. Desoneração da Folha |  |
| INDOPTREGELETRON | Integer |  | Ind. Opção Registro Eletrônico |  |
| INDENTED | String |  | Ind. Entidade Educativa |  |
| INDETT | String |  | Ind. Emp. Trabalho Temporário |  |
| NRREGETT | String |  | Nr. Reg. Empresa de Trabalho |  |
| IDEMINLEI | String |  | ID. Ministério ou Lei |  |
| NRCERTIF | String |  | Nr. Certificado |  |
| DTEMISCERTIF | DateTime |  | Dt. Emissão do Certificado |  |
| DTVENCCERTIF | DateTime |  | Dt. Vencimeto do Certificado |  |
| NRPROTRENOV | String |  | Nr. Protocolo de Renovação |  |
| DTPROTRENOV | DateTime |  | Dt. Protocolo de Renovação |  |
| DTDOU | DateTime |  | Dt. Diário Oficial da União |  |
| PAGDOU | Integer |  | Pág. Diário Oficial da União |  |
| NMCTT | String |  | Contato na Empresa |  |
| CPFCTT | String |  | CPF - Contato |  |
| FONEFIXO | String |  | Telefone Fixo |  |
| EMAIL | String |  | Email |  |
| NRSIAFI | Integer |  | Nr. SIAFI |  |
| IDEEFR | String |  | ID. Ente Federativo Responsável |  |
| CNPJEFR | String |  | CNPJ - Ente Federativo Responsável |  |
| NMENTE | String |  | Ente Federativo |  |
| UF | String |  | UF |  |
| CODMUNIC | Integer |  | Cód. Município |  |
| INDRPPS | String |  | Ind. Regime Proprio Previdência Social |  |
| SUBTETO | Integer |  | Subteto |  |
| VRSUBTETO | Float |  | Vr. Subteto |  |
| INDACORDOISENMULTA | Integer |  | Ind. Acordo Isenção de Multa |  |
| INDSITPJ | Integer |  | Ind. Situação PJ |  |
| INDSITPF | Integer |  | Ind. Situação PF |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1005 — S-1005 - Estabelecimentos
Campos: 34

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| TPINSCESTABELECIMENTO | Integer |  | Tipo Inscrição do Estabelecimento |  |
| NRINSCESTABELECIMENTO | String |  | Nr. Inscrição do Estabelecimento |  |
| CNAEPREP | Integer |  | CNAE Preponderante |  |
| ALIQRAT | Integer |  | Alíquota do RAT |  |
| ALIQRAT2 | Integer |  | ALIQRAT2 |  |
| FAP | Float |  | Fator Acidentário de Prevenção |  |
| ALIQRATAJUST | Float |  | Alíquota do RAT após ajuste |  |
| TPPROCRAT | Integer |  | Tipo Processo RAT |  |
| NRPROCRAT | String |  | Nr. Processo RAT |  |
| CODSUSPRAT | Integer |  | Cód. Suspensão RAT |  |
| TPPROCFAP | Integer |  | Tipo Processo FAP |  |
| NRPROCFAP | String |  | Nr. Processo FAP |  |
| CODSUSPFAP | Integer |  | Cód. Suspensão FAP |  |
| TPCAEPF | Integer |  | Tipo de CAEPF |  |
| INDSUBSTPATROBRA | Integer |  | Ind. Substituição Patronal de Obra |  |
| REGPT | Integer |  | Registro de Ponto |  |
| CONTAPR | Integer |  | Contratação de Aprendiz |  |
| NUPROCJUDAPR | String |  | Nr. Processo Judicial Aprendiz |  |
| CONTENTED | String |  | Entidade Educativa |  |
| CONTPCD | Integer |  | Contratação de PCD |  |
| NUPROCJUDPCD | String |  | Nr. Processo Judicial PCD |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1005_INFOENTEDUC — Estabelecimento - Informativo Entidade Educacional
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| FILIAL | String |  | Filial |  |
| NRINSC | String |  | Nr. Inscrição |  |
| CHAVE | String |  | Chave |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1010 — S-1010 - Rubricas
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| CODRUBR | String |  | Cód Rúbrica |  |
| IDETABRUBR | String |  | ID. Rúbrica |  |
| DSCRUBR | String |  | Descrição da Rúbrica |  |
| NATRUBR | Integer |  | Natureza das Rúbricas |  |
| TPRUBR | Integer |  | Tipo de Rúbrica |  |
| CODINCCP | String |  | Cód. Incidência CP |  |
| CODINCIRRF | String |  | Cód. Incidência IRRF |  |
| CODINCFGTS | String |  | Cód. Incidência FGTS |  |
| CODINCSIND | String |  | Cód. Incidência Sindical |  |
| REPDSR | String |  | Rubrica DSR |  |
| REP13 | String |  | Rubrica 13° |  |
| REPFERIAS | String |  | Rubrica Férias |  |
| REPAVISO | String |  | Rubrica Aviso Prévio |  |
| OBSERVACAO | String |  | Observações |  |
| CODEVENTO | Integer |  | Cód. Evento |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1010_CP — Rúbricas - Contribuição Previdênciária
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| TPPROCCP | Integer |  | Tipo Processo CP |  |
| NRPROCCP | String |  | Nr. Processo CP |  |
| EXTDESCISAOCP | Integer |  | Decisão Extrajudiciária CP |  |
| CODSUSPCP | Integer |  | Cód. Suspensão CP |  |
| CODEVENTO | Integer |  | Cód. Evento |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1010_FGTS — Rúbricas - FGTS
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRPROCFGTS | String |  | Nr. Processo do FGTS |  |
| CODSUSPFGTS | Integer |  | Cód. Suspensão do FGTS |  |
| CODEVENTO | Integer |  | Cód. Evento |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1010_IRRF — Rúbricas - IRRF
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRPROCIRRF | String |  | Nr. Processo do IRRF |  |
| CODSUSPIRRF | Integer |  | Cód. Suspensão do IRRF |  |
| CODEVENTO | Integer |  | Cód. Evento |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1010_SIND — Rúbrica - Sindicato
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVE | String |  | Chave |  |
| NRPROCSIND | String |  | Nr. Processo do Sindicato |  |
| CODSUSPSIND | Integer |  | Cód. Suspensão do Sindicato |  |
| CODEVENTO | Integer |  | Cód. Evento |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1020 — S-1020 - Lotações Tributárias
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| CODLOTACAO | String |  | Cód. Lotação |  |
| TPLOTACAO | String |  | Tipo de Lotação |  |
| TPLOTACAO_2 | Integer |  | Tipo de Lotação 2 |  |
| TPINSCLOTACAO | Integer |  | Tipo Inscrição da Lotação |  |
| NRINSCLOTACAO | String |  | Inscrição da Lotação |  |
| FPAS | Integer |  | Cód Relativo ao FPAS |  |
| CODTERCS | String |  | Cód. de Terceiros |  |
| CODTERCSSUSP | String |  | Cód. de Terceiros Suspenso |  |
| TPINSCCONTRAT | Integer |  | Tipo Inscrição do Contratante |  |
| NRINSCCONTRAT | String |  | Nr. Inscrição do Contratante |  |
| TPINSCPROP | Integer |  | Tipo Inscrição do Proprietário |  |
| NRINSCPROP | String |  | Nr. Inscrição do Proprietário |  |
| CODREGFIS | Integer |  | Cód. Registro Fiscal |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| TIPOREGISTRO | String |  | Tipo do Registro |  |
| CODIGO | Integer |  | Código |  |
| DESCRLOTACAO | String |  | Descrição da Lotação |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1020_PROCJUD — Lotações Tributárias - Processo Judicial
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODTERC | String |  | Cód. de Terceiros |  |
| NRPROCJUD | String |  | Nr. Processo Judicial |  |
| CODSUSP | Integer |  | Cód. de Suspensão |  |
| CODREGFIS | Integer |  | Cód. Registro Fiscal |  |
| CODLOTACAO | String |  | Cód. Lotação |  |
| CHAVE | String |  | Chave |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1030 — S-1030 - Cargos
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| CODCARGO | String |  | Cód Cargo |  |
| NMCARGO | String |  | Nome Cargo |  |
| CODCBO | String |  | Cód. CBO |  |
| ACUMCARGO | Integer |  | Acumulação de Cargos |  |
| CONTAGEMESP | Integer |  | Contagem Especial |  |
| DEDICEXCL | String |  | Dedicação Exclusiva |  |
| NRLEI | String |  | Nr. Lei |  |
| DTLEI | DateTime |  | Dt. da Lei |  |
| SITCARGO | Integer |  | Situação do Cargo |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo de Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1035 — S-1035 - Carreiras Públicas
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| CODCARREIRA | String |  | Cód. da Carreira |  |
| DSCCARREIRA | String |  | Descrição da Carreira |  |
| LEICARR | String |  | Lei da Carreira |  |
| DTLEICARR | DateTime |  | Dt. Lei da Carreira |  |
| SITCARR | Integer |  | Situação da Carreira |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1040 — S-1040 - Funções/Cargos em Comissão
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| CODFUNCAO | String |  | Cód. da Função |  |
| DSCFUNCAO | String |  | Descrição da Função |  |
| CODCBO | String |  | Cód CBO |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterios |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1050 — S-1050 - Horários
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| CODHORCONTRAT | String |  | Cód. Horário Contratual |  |
| HRENTR | String |  | Hora de Entrada |  |
| HRSAIDA | String |  | Hora de Saída |  |
| DURJORNADA | Integer |  | Duração da Jornada |  |
| PERHORFLEXIVEL | String |  | Permitido Horário Flexivel |  |
| TPINTERV | Integer |  | Tipo Intervalo da Jornada |  |
| DURINTERV | Integer |  | Duração do Intervalo |  |
| INIINTERV | String |  | Início do Intervalo |  |
| TERMINTERV | String |  | Termino do Intervalo |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CODCARGAHOR | Integer |  | Cód. Carga Horária |  |
| DESCRCARGAHOR | String |  | Descrição da Carga Horária |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1050_INTERVALO — Horários - Intervalo
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODCARGAHORESOCIAL | String |  | Cód. Carga Horária ESocial |  |
| INIINTERV | String |  | Início do Intervalo |  |
| TERMINTERV | String |  | Termino do Intervalo |  |
| DURINTERV | Integer |  | Duração do Intervalo |  |
| CHAVE | String |  | Chave |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1060 — S-1060 - Ambientes de Trabalho
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| CODAMB | String |  | Cód. Ambiente |  |
| DSCAMB | String |  | Descrição Ambiente de Trabalho |  |
| LOCALAMB | Integer |  | Local do Ambiente |  |
| TPINSC | Integer |  | Tipo de Inscrição |  |
| NRINSC | String |  | Nr. Inscrição |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1070 — S-1070 - Processos Adm/Jud
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição do Empregador |  |
| NRINSCEMPREGADOR | String |  | Nr. de Inscrição do Empregador |  |
| TPPROC | Integer |  | Tipo de Processo |  |
| NRPROC | String |  | Nr. do Processo |  |
| INDAUTORIA | Integer |  | Ind. Autoria da Ação Judicial |  |
| INDMATPROC | Integer |  | Ind. Matéria do Processo |  |
| UFVARA | String |  | ID. UF Seção Judiciária |  |
| CODMUNIC | Integer |  | Cód. Município |  |
| IDVARA | String |  | ID. Vara |  |
| STATUS | String |  | Status |  |
| NRORECIBO | String |  | Nr. Recibo |  |
| NRORECIBO_ANT | String |  | Nr. Recibo Anterior |  |
| ACAO | String |  | Ação |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle |  |
| TPAMB | String |  | Tipo Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1070_INFOSUSP — Processos - Informativo de Suspensão
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Dt. Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODSUSP | Integer |  | Cód. Suspensão |  |
| INDSUSP | String |  | Ind. Suspensão |  |
| DTDECISAO | DateTime |  | Dt. Decisão |  |
| INDDEPOSITO | String |  | Ind. Deposito |  |
| NUPROCESSO | String |  | Nr. Processo |  |
| CHAVE | String |  | Chave |  |
| TPAMB | String |  | Tipo Ambiente |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1200 — TABLE TFPS1200
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| INDAPURACAO | Integer |  | INDAPURACAO |  |
| PERAPUR | String |  | PERAPUR |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| INDMV | Integer |  | INDMV |  |
| NMTRAB | String |  | NMTRAB |  |
| DTNASCTO | DateTime |  | DTNASCTO |  |
| CODCBO | String |  | CODCBO |  |
| NATATIVIDADE | Integer |  | NATATIVIDADE |  |
| QTDDIASTRAB | Integer |  | QTDDIASTRAB |  |
| CNPJEMPREGANT | String |  | CNPJEMPREGANT |  |
| MATRICANT | String |  | MATRICANT |  |
| DTADM | DateTime |  | DTADM |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| QTDDIASINTERM | Integer |  | QTDDIASINTERM |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| TPAMB | String |  | TPAMB |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| TPINSCANT | Integer |  | TPINSCANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV — TABLE TFPS1200_DMDEV
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| CHAVE | String |  | CHAVE |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODCATEG | Integer |  | CODCATEG |  |
| CODCBO | String |  | CODCBO |  |
| NATATIVIDADE | Integer |  | NATATIVIDADE |  |
| QTDDIASTRAB | Integer |  | QTDDIASTRAB |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_ADC — TABLE TFPS1200_DMDEV_ADC
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE | String |  | CHAVE |  |
| DTACCONV | DateTime |  | DTACCONV |  |
| TPACCONV | String |  | TPACCONV |  |
| COMPACCONV | String |  | COMPACCONV |  |
| DTEFACCONV | DateTime |  | DTEFACCONV |  |
| DSC | String |  | DSC |  |
| REMUNSUC | String |  | REMUNSUC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_DDRPA — TABLE TFPS1200_DMDEV_DDRPA
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CNPJOPER | String |  | CNPJOPER |  |
| CHAVE | String |  | CHAVE |  |
| TPDEP | String |  | TPDEP |  |
| CPFDEP | String |  | CPFDEP |  |
| NMDEP | String |  | NMDEP |  |
| DTNASCTO | DateTime |  | DTNASCTO |  |
| VLRPGDEP | Float |  | VLRPGDEP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_DRPA — TABLE TFPS1200_DMDEV_DRPA
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CHAVE | String |  | CHAVE |  |
| CNPJOPER | String |  | CNPJOPER |  |
| REGANS | String |  | REGANS |  |
| VRPGTIT | Float |  | VRPGTIT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_EL — TABLE TFPS1200_DMDEV_EL
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| QTDDIASAV | Integer |  | QTDDIASAV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_IPADC — TABLE TFPS1200_DMDEV_IPADC
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE1200_PA_ADC | String |  | CHAVE1200_PA_ADC |  |
| PERREF | String |  | PERREF |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_IRPA — TABLE TFPS1200_DMDEV_IRPA
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_IRPADC — TABLE TFPS1200_DMDEV_IRPADC
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE1200_PA_ADC | String |  | CHAVE1200_PA_ADC |  |
| PERREF | String |  | PERREF |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_PADC — TABLE TFPS1200_DMDEV_PADC
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE1200_PA_ADC | String |  | CHAVE1200_PA_ADC |  |
| CHAVE | String |  | CHAVE |  |
| PERREF | String |  | PERREF |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_RPA — TABLE TFPS1200_DMDEV_RPA
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| MATRICULA | String |  | MATRICULA |  |
| INDSIMPLES | Integer |  | INDSIMPLES |  |
| GRAUEXP | Integer |  | GRAUEXP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_RPADC — TABLE TFPS1200_DMDEV_RPADC
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE1200_PA_ADC | String |  | CHAVE1200_PA_ADC |  |
| PERREF | String |  | PERREF |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| MATRICULA | String |  | MATRICULA |  |
| INDSIMPLES | Integer |  | INDSIMPLES |  |
| GRAUEXP | Integer |  | GRAUEXP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_DMDEV_TRPA — TABLE TFPS1200_DMDEV_TRPA
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CHAVE | String |  | CHAVE |  |
| CODCONV | String |  | CODCONV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_PROCJUD — TABLE TFPS1200_PROCJUD
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| CHAVE | String |  | CHAVE |  |
| TPTRIB | Integer |  | TPTRIB |  |
| NRPROCJUD | String |  | NRPROCJUD |  |
| CODSUSP | String |  | CODSUSP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1200_REMOUTREMPRE — TABLE TFPS1200_REMOUTREMPRE
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE1200 | String |  | CHAVE1200 |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODCATEG | Integer |  | CODCATEG |  |
| VLRREMUNOE | Float |  | VLRREMUNOE |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210 — Pagamentos de Rendimentos do Trabalho
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Referência |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Ambiente |  |
| CHAVE | String |  | Chave |  |
| INDAPURACAO | Integer |  | INDAPURACAO |  |
| PERAPUR | String |  | Período de apuração |  |
| TPINSC | Integer |  | Tipo de inscrição |  |
| NRINSC | String |  | Nro. de inscrição |  |
| CPFBENEF | String |  | CPF Beneficiário (Trabalhador) |  |
| VRDEDDEP | Float |  | VRDEDDEP |  |
| STATUS | String |  | Situação |  |
| DESCREVT | String |  | Descrição do evento |  |
| NRORECIBO | String |  | Nº Recibo Original |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | Ação |  |
| CONTROLE | String |  | Controle |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1210_ANT — Pagamentos de Rendimentos do Trabalho - Histórico
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Referência |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| SEQUENCIA | Integer |  | Sequência |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| TPAMB | String |  | Ambiente |  |
| CHAVE | String |  | Chave |  |
| INDAPURACAO | Integer |  | INDAPURACAO |  |
| PERAPUR | String |  | Período de apuração |  |
| TPINSC | Integer |  | Tipo de inscrição |  |
| NRINSC | String |  | Nro. de inscrição |  |
| CPFBENEF | String |  | CPF Beneficiário (Trabalhador) |  |
| VRDEDDEP | Float |  | VRDEDDEP |  |
| STATUS | String |  | Situação |  |
| DESCREVT | String |  | Descrição do evento |  |
| NRORECIBO | String |  | Nº Recibo Original |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | Ação |  |
| CONTROLE | String |  | Controle |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS1210_ANT_CHANGEID — TFPS1210_ANT_CHANGEID
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TABELA | String |  | TABELA |  |
| CHANGEID | String |  | CHANGEID |  |
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| DTREFRET | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| SEQUENCIARET | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |

## TFPS1210_BENEFPEN — TFPS1210_BENEFPEN
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVEINFOPROCRET | String |  | CHAVEINFOPROCRET |  |
| CHAVEINFOVALORES | String |  | CHAVEINFOVALORES |  |
| CHAVEDEDSUSP | String |  | CHAVEDEDSUSP |  |
| CHAVE | String |  | CHAVE |  |
| CPFDEP | String |  | CPF dependente |  |
| VLRDEPENSUSP | Float |  | Valor da dedução |  |

## TFPS1210_BENEFPEN_ANT — TFPS1210_BENEFPEN_ANT
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVEINFOPROCRET | String |  | CHAVEINFOPROCRET |  |
| CHAVEINFOVALORES | String |  | CHAVEINFOVALORES |  |
| CHAVEDEDSUSP | String |  | CHAVEDEDSUSP |  |
| CHAVE | String |  | CHAVE |  |
| CPFDEP | String |  | CPF dependente |  |
| VLRDEPENSUSP | Float |  | Valor da dedução |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_DAIPGTO — TABLE TFPS1210_DAIPGTO
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| CODCATEG | String |  | CODCATEG |  |
| CHAVE | String |  | CHAVE |  |
| TPBCIRRF | String |  | TPBCIRRF |  |
| VRBCIRRF | Float |  | VRBCIRRF |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_DEDDEPEN — TFPS1210_DEDDEPEN
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPREND | String |  | Tipo de rendimento | `11`=11 - Remuneração mensal `12`=12 - 13º salário `13`=13 - Férias |
| CPFDEP | String |  | CPF do dependente |  |
| VLRDEDDEP | Float |  | Valor da dedução |  |

## TFPS1210_DEDDEPEN_ANT — TFPS1210_DEDDEPEN_ANT
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPREND | String |  | Tipo de rendimento | `11`=11 - Remuneração mensal `12`=12 - 13º salário `13`=13 - Férias |
| CPFDEP | String |  | CPF do dependente |  |
| VLRDEDDEP | Float |  | Valor da dedução |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_DEDSUSP — TFPS1210_DEDSUSP
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVEINFOPROCRET | String |  | CHAVEINFOPROCRET |  |
| CHAVEINFOVALORES | String |  | CHAVEINFOVALORES |  |
| CHAVE | String |  | CHAVE |  |
| INDTPDEDUCAO | String |  | Indicativo do tipo de dedução |  |
| VLRDEDSUSP | Float |  | Valor da dedução |  |
| CNPJENTIDPC | String |  | CNPJ Entidade de previdência |  |
| VLRPATROCFUNP | Float |  | Valor da contribuição |  |

## TFPS1210_DEDSUSP_ANT — TFPS1210_DEDSUSP_ANT
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVEINFOPROCRET | String |  | CHAVEINFOPROCRET |  |
| CHAVEINFOVALORES | String |  | CHAVEINFOVALORES |  |
| CHAVE | String |  | CHAVE |  |
| INDTPDEDUCAO | String |  | Indicativo do tipo de dedução |  |
| VLRDEDSUSP | Float |  | Valor da dedução |  |
| CNPJENTIDPC | String |  | CNPJ Entidade de previdência |  |
| CHANGEID | String |  | CHANGEID |  |
| VLRPATROCFUNP | Float |  | Valor da contribuição |  |

## TFPS1210_DETREEMBDEP — TFPS1210_DETREEMBDEP
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEINFOREEMBMED | String |  | CHAVEINFOREEMBMED |  |
| CHAVEINFOREEMBDEP | String |  | CHAVEINFOREEMBDEP |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | Tipo de inscrição | `1`=CNPJ `2`=CPF |
| NRINSC | String |  | Número de inscrição |  |
| VLRREEMB | Float |  | Valor do reembolso |  |
| VLRREEMBANT | Float |  | Valor do Reembolso dos anos anteriores |  |

## TFPS1210_DETREEMBDEP_ANT — TFPS1210_DETREEMBDEP_ANT
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEINFOREEMBMED | String |  | CHAVEINFOREEMBMED |  |
| CHAVEINFOREEMBDEP | String |  | CHAVEINFOREEMBDEP |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | Tipo de inscrição | `1`=CNPJ `2`=CPF |
| NRINSC | String |  | Número de inscrição |  |
| VLRREEMB | Float |  | Valor do reembolso |  |
| VLRREEMBANT | Float |  | Valor do Reembolso dos anos anteriores |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_DETREEMBTIT — TFPS1210_DETREEMBTIT
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEINFOREEMBMED | String |  | CHAVEINFOREEMBMED |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | Tipo de inscrição | `1`=CNPJ `2`=CPF |
| NRINSC | String |  | Número de inscrição |  |
| VLRREEMB | Float |  | Valor do reembolso |  |
| VLRREEMBANT | Float |  | Valor do Reembolso dos anos anteriores |  |

## TFPS1210_DETREEMBTIT_ANT — TFPS1210_DETREEMBTIT_ANT
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEINFOREEMBMED | String |  | CHAVEINFOREEMBMED |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | Tipo de inscrição | `1`=CNPJ `2`=CPF |
| NRINSC | String |  | Número de inscrição |  |
| VLRREEMB | Float |  | Valor do reembolso |  |
| VLRREEMBANT | Float |  | Valor do Reembolso dos anos anteriores |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_DFIPGTO — TABLE TFPS1210_DFIPGTO
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| CHAVEPAI | String |  | CHAVEPAI |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_DIPGTO — TABLE TFPS1210_DIPGTO
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| CHAVE | String |  | CHAVE |  |
| PERREF | String |  | PERREF |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| INDPGTOTT | String |  | INDPGTOTT |  |
| VRLIQ | Float |  | VRLIQ |  |
| NRRECARQ | String |  | NRRECARQ |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_FIPGTO — TABLE TFPS1210_FIPGTO
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| CHAVE | String |  | CHAVE |  |
| CODCATEG | Integer |  | CODCATEG |  |
| MATRICULA | String |  | MATRICULA |  |
| DTINIGOZ | DateTime |  | DTINIGOZ |  |
| QTDIAS | Integer |  | QTDIAS |  |
| VRLIQ | Float |  | VRLIQ |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_INFODEP — TFPS1210_INFODEP
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIR | String |  | CHAVEINFOIR |  |
| CHAVE | String |  | CHAVE |  |
| CPFDEP | String |  | CPF Dependente |  |
| DTNASCTO | Date |  | Data de nascimento |  |
| NOME | String |  | Nome |  |
| DEPIRRF | String |  | Dependente IRRF | `N`=Não `S`=Sim |
| TPDEP | String |  | Tipo de dependente | `1`=Cônjuge `10`=Menor pobre do qual detenha a guarda judicial `11`=A pessoa absolutamente incapaz, da qual seja tutor ou curador `12`=Ex-cônjuge `2`=Companheiro(a) com filho ou vivendo há mais de 5 anos ou em união estável_(+6)_ |
| DESCRDEP | String |  | Descrição da dependência |  |

## TFPS1210_INFODEPSAU — TFPS1210_INFODEPSAU
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEPLANSAUDE | String |  | CHAVEPLANSAUDE |  |
| CHAVE | String |  | CHAVE |  |
| CPFDEP | String |  | CPF Dependente |  |
| VLRSAUDEDEP | Float |  | Valor Plano de Saúde Dependente |  |

## TFPS1210_INFODEPSAU_ANT — TFPS1210_INFODEPSAU_ANT
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEPLANSAUDE | String |  | CHAVEPLANSAUDE |  |
| CHAVE | String |  | CHAVE |  |
| CPFDEP | String |  | CPF Dependente |  |
| VLRSAUDEDEP | Float |  | Valor Plano de Saúde Dependente |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_INFODEP_ANT — TFPS1210_INFODEP_ANT
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIR | String |  | CHAVEINFOIR |  |
| CHAVE | String |  | CHAVE |  |
| CPFDEP | String |  | CPF Dependente |  |
| DTNASCTO | Date |  | Data de nascimento |  |
| NOME | String |  | Nome |  |
| DEPIRRF | String |  | Dependente IRRF | `N`=Não `S`=Sim |
| TPDEP | String |  | Tipo de dependente | `1`=Cônjuge `10`=Menor pobre do qual detenha a guarda judicial `11`=A pessoa absolutamente incapaz, da qual seja tutor ou curador `12`=Ex-cônjuge `2`=Companheiro(a) com filho ou vivendo há mais de 5 anos ou em união estável_(+6)_ |
| DESCRDEP | String |  | Descrição da dependência |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_INFOIRCOMPLEM — TFPS1210_INFOIRCOMPLEM
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVE | String |  | CHAVE |  |
| DTLAUDO | Date |  | Data da moléstia grave |  |

## TFPS1210_INFOIRCOMPLEM_ANT — TFPS1210_INFOIRCOMPLEM_ANT
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVE | String |  | CHAVE |  |
| DTLAUDO | Date |  | Data da moléstia grave |  |
| DTREFREAJUSTE | Date |  | Referência de ajuste |  |
| NRORECIBOORI | Date |  | Número do recibo original |  |

## TFPS1210_INFOIRCR — TFPS1210_INFOIRCR
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVE | String |  | CHAVE |  |
| TPCR | String |  | Código de Receita |  |

## TFPS1210_INFOIRCR_ANT — TFPS1210_INFOIRCR_ANT
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVE | String |  | CHAVE |  |
| TPCR | String |  | Código de Receita |  |

## TFPS1210_INFOPROCRET — TFPS1210_INFOPROCRET
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPPROCRET | String |  | Tipo de processo |  |
| NRPROCRET | String |  | Número do processo |  |
| CODSUSP | String |  | Código do indicativo da suspensão |  |

## TFPS1210_INFOPROCRET_ANT — TFPS1210_INFOPROCRET_ANT
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPPROCRET | String |  | Tipo de processo |  |
| NRPROCRET | String |  | Número do processo |  |
| CODSUSP | String |  | Código do indicativo da suspensão |  |

## TFPS1210_INFOREEMBDEP — TFPS1210_INFOREEMBDEP
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEINFOREEMBMED | String |  | CHAVEINFOREEMBMED |  |
| CHAVE | String |  | CHAVE |  |
| CPFBENEF | String |  | CPF Dependente |  |

## TFPS1210_INFOREEMBDEP_ANT — TFPS1210_INFOREEMBDEP_ANT
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVEINFOREEMBMED | String |  | CHAVEINFOREEMBMED |  |
| CHAVE | String |  | CHAVE |  |
| CPFBENEF | String |  | CPF Dependente |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_INFOREEMBMED — TFPS1210_INFOREEMBMED
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVE | String |  | CHAVE |  |
| INDORGREEMB | String |  | Indicativo de Origem do Reembolso |  |
| CNPJOPER | String |  | CNPJ Operadora |  |
| REGANS | String |  | Registro ANS |  |

## TFPS1210_INFOREEMBMED_ANT — TFPS1210_INFOREEMBMED_ANT
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVE | String |  | CHAVE |  |
| INDORGREEMB | String |  | Indicativo de Origem do Reembolso |  |
| CNPJOPER | String |  | CNPJ Operadora |  |
| REGANS | String |  | Registro ANS |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_INFOVALORES — TFPS1210_INFOVALORES
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVEINFOPROCRET | String |  | CHAVEINFOPROCRET |  |
| CHAVE | String |  | CHAVE |  |
| INDAPURACAO | String |  | Indicativo de período de apuração |  |
| VLRNAORETIDO | Float |  | Valor da retenção |  |
| VLRDEPJUD | Float |  | Valor do depósito judicial |  |
| VLRCMPANOCAL | Float |  | Valor da compensação |  |
| VLRCMPANOANT | Float |  | Valor da compensação relativa a anos anteriores |  |
| VLRRENDSUSP | Float |  | Valor do rendimento com exigibilidade suspensa |  |

## TFPS1210_INFOVALORES_ANT — TFPS1210_INFOVALORES_ANT
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVEINFOPROCRET | String |  | CHAVEINFOPROCRET |  |
| CHAVE | String |  | CHAVE |  |
| INDAPURACAO | String |  | Indicativo de período de apuração |  |
| VLRNAORETIDO | Float |  | Valor da retenção |  |
| VLRDEPJUD | Float |  | Valor do depósito judicial |  |
| VLRCMPANOCAL | Float |  | Valor da compensação |  |
| VLRCMPANOANT | Float |  | Valor da compensação relativa a anos anteriores |  |
| VLRRENDSUSP | Float |  | Valor do rendimento com exigibilidade suspensa |  |

## TFPS1210_IPGTO — TABLE TFPS1210_IPGTO
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| CHAVE | String |  | CHAVE |  |
| DTPGTO | DateTime |  | Data de pagamento |  |
| TPPGTO | Integer |  | Origem do pagamento |  |
| INDRESBR | String |  | INDRESBR |  |
| PERREF | String |  | Competência |  |
| IDEDMDEV | String |  | Identificador |  |
| INDPGTOTT | String |  | INDPGTOTT |  |
| VRLIQ | Float |  | Valor líquido |  |
| CODPAIS | String |  | CODPAIS |  |
| INDNIF | Integer |  | Indicativo do Número de Identificação Fiscal |  |
| NIFBENEF | String |  | Número de Identificação Fiscal |  |
| FRMTRIBUT | Integer |  | Forma de tributação |  |
| DSCLOGRAD | String |  | DSCLOGRAD |  |
| NRLOGRAD | String |  | Número do logradouro |  |
| COMPLEM | String |  | COMPLEM |  |
| BAIRRO | String |  | Nome do bairro/distrito |  |
| NMCID | String |  | Nome da cidade |  |
| CODPOSTAL | String |  | Código de Endereçamento Postal |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_IPGTO_ANT — TABLE TFPS1210_IPGTO_ANT
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| CHAVE | String |  | CHAVE |  |
| DTPGTO | DateTime |  | Data de pagamento |  |
| TPPGTO | Integer |  | Origem do pagamento |  |
| INDRESBR | String |  | INDRESBR |  |
| PERREF | String |  | Competência |  |
| IDEDMDEV | String |  | Identificador |  |
| INDPGTOTT | String |  | INDPGTOTT |  |
| VRLIQ | Float |  | Valor líquido |  |
| CODPAIS | String |  | CODPAIS |  |
| INDNIF | Integer |  | Indicativo do Número de Identificação Fiscal |  |
| FRMTRIBUT | Integer |  | Forma de tributação |  |
| NIFBENEF | String |  | Número de Identificação Fiscal |  |
| DSCLOGRAD | String |  | DSCLOGRAD |  |
| NRLOGRAD | String |  | Número do logradouro |  |
| COMPLEM | String |  | COMPLEM |  |
| BAIRRO | String |  | Nome do bairro/distrito |  |
| NMCID | String |  | Nome da cidade |  |
| CODPOSTAL | String |  | Código de Endereçamento Postal |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_PDFIPGTO — TABLE TFPS1210_PDFIPGTO
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| CHAVEAVO | String |  | CHAVEAVO |  |
| CODRUBR | String |  | CODRUBR |  |
| CHAVE | String |  | CHAVE |  |
| CPFBENEFPENSAO | String |  | CPFBENEFPENSAO |  |
| DTNASCTOBENEF | DateTime |  | DTNASCTOBENEF |  |
| NMBENEFIC | String |  | NMBENEFIC |  |
| VLRPENSAO | Float |  | VLRPENSAO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_PENALIM — TFPS1210_PENALIM
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPREND | String |  | Tipo de rendimento | `11`=11 - Remuneração mensal `12`=12 - 13º salário `13`=13 - Férias |
| CPFDEP | String |  | CPF |  |
| VLRDEDPENALIM | Float |  | Valor relativo à dedução do rendimento tributável |  |

## TFPS1210_PENALIM_ANT — TFPS1210_PENALIM_ANT
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPREND | String |  | Tipo de rendimento | `11`=11 - Remuneração mensal `12`=12 - 13º salário `13`=13 - Férias |
| CPFDEP | String |  | CPF |  |
| VLRDEDPENALIM | Float |  | Valor relativo à dedução do rendimento tributável |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_PLANSAUDE — TFPS1210_PLANSAUDE
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVE | String |  | CHAVE |  |
| CNPJOPER | String |  | CNPJ Operadora |  |
| REGANS | String |  | Registro ANS |  |
| VLRSAUDETIT | Float |  | Valor Plano de Saude Titular |  |

## TFPS1210_PLANSAUDE_ANT — TFPS1210_PLANSAUDE_ANT
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEM | String |  | CHAVEINFOIRCOMPLEM |  |
| CHAVE | String |  | CHAVE |  |
| CNPJOPER | String |  | CNPJ Operadora |  |
| REGANS | String |  | Registro ANS |  |
| VLRSAUDETIT | Float |  | Valor Plano de Saude Titular |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_PRDIPGTO — TABLE TFPS1210_PRDIPGTO
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| PER_IDEDMDEV | String |  | PER_IDEDMDEV |  |
| CODRUBR | String |  | CODRUBR |  |
| CHAVE | String |  | CHAVE |  |
| CPFBENEFPENSAO | String |  | CPFBENEFPENSAO |  |
| DTNASCTOBENEF | DateTime |  | DTNASCTOBENEF |  |
| NMBENEFIC | String |  | NMBENEFIC |  |
| VLRPENSAO | Float |  | VLRPENSAO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_PREVIDCOMPL — TFPS1210_PREVIDCOMPL
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPPREV | String |  | Tipo de previdência complementar | `1`=1 - Privada `2`=2 - FAPI |
| CNPJENTIDPC | String |  | Número de inscrição da entidade de previdência |  |
| VLRDEDPC | Float |  | Valor da dedução mensal |  |

## TFPS1210_PREVIDCOMPL_ANT — TFPS1210_PREVIDCOMPL_ANT
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| DTREFRET | DateTime |  | Referência Ret |  |
| DTREF | Date |  | DTREF |  |
| SEQUENCIARET | Integer |  | Sequência Ret |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1210 | String |  | CHAVE1210 |  |
| CHAVEINFOIRCOMPLEN | String |  | CHAVEINFOIRCOMPLEN |  |
| CHAVEINFOIRCR | String |  | CHAVEINFOIRCR |  |
| CHAVE | String |  | CHAVE |  |
| TPPREV | String |  | Tipo de previdência complementar | `1`=1 - Privada `2`=2 - FAPI |
| CNPJENTIDPC | String |  | Número de inscrição da entidade de previdência |  |
| VLRDEDPC | Float |  | Valor da dedução mensal |  |
| CHANGEID | String |  | CHANGEID |  |

## TFPS1210_RDIPGTO — TABLE TFPS1210_RDIPGTO
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| PER_IDEDMDEV | String |  | PER_IDEDMDEV |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1210_RIPGTO — TABLE TFPS1210_RIPGTO
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CPFBENEF | String |  | CPFBENEF |  |
| DT_TPPGTO | String |  | DT_TPPGTO |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1250 — TABLE TFPS1250
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| TPINSCADQ | Integer |  | TPINSCADQ |  |
| NRINSCADQ | String |  | NRINSCADQ |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1250_IDEPRODUTOR — TABLE TFPS1250_IDEPRODUTOR
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1250 | String |  | CHAVE1250 |  |
| INDAQUIS | String |  | INDAQUIS |  |
| CHAVE | String |  | CHAVE |  |
| TPINSCPROD | Integer |  | TPINSCPROD |  |
| NRINSCPROD | String |  | NRINSCPROD |  |
| VLRBRUTO | Float |  | VLRBRUTO |  |
| VRCPDESCPR | Float |  | VRCPDESCPR |  |
| VRRATDESCPR | Float |  | VRRATDESCPR |  |
| VRSENARDESC | Float |  | VRSENARDESC |  |
| INDOPCCP | Integer |  | INDOPCCP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1250_NFS — TABLE TFPS1250_NFS
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1250 | String |  | CHAVE1250 |  |
| INDAQUIS | String |  | INDAQUIS |  |
| CHAVEIDEPROD | String |  | CHAVEIDEPROD |  |
| CHAVE | String |  | CHAVE |  |
| SERIE | String |  | SERIE |  |
| NRDOCTO | String |  | NRDOCTO |  |
| DTEMISNF | DateTime |  | DTEMISNF |  |
| NUNOTA | Integer |  | NUNOTA |  |
| VLRBRUTO | Float |  | VLRBRUTO |  |
| VRCPDESCPR | Float |  | VRCPDESCPR |  |
| VRRATDESCPR | Float |  | VRRATDESCPR |  |
| VRSENARDESC | Float |  | VRSENARDESC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1250_PROCJUD — TABLE TFPS1250_PROCJUD
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1250 | String |  | CHAVE1250 |  |
| INDAQUIS | String |  | INDAQUIS |  |
| CHAVEIDEPROD | String |  | CHAVEIDEPROD |  |
| CHAVE | String |  | CHAVE |  |
| NUPROCESSO | Integer |  | NUPROCESSO |  |
| NRPROCJUD | String |  | NRPROCJUD |  |
| CODSUSP | String |  | CODSUSP |  |
| VRCPNRET | Float |  | VRCPNRET |  |
| VRRATNRET | Float |  | VRRATNRET |  |
| VRSENARNRET | Float |  | VRSENARNRET |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1250_TPAQUIS — TABLE TFPS1250_TPAQUIS
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE1250 | String |  | CHAVE1250 |  |
| CHAVE | String |  | CHAVE |  |
| INDAQUIS | Integer |  | INDAQUIS |  |
| VLRTOTAQUIS | Float |  | VLRTOTAQUIS |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1260 — TABLE TFPS1260
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| NRINSCESTABRURAL | String |  | NRINSCESTABRURAL |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1270 — TABLE TFPS1270
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| INDRETIF | Integer |  | INDRETIF |  |
| INDAPURACAO | Integer |  | INDAPURACAO |  |
| PERAPUR | String |  | PERAPUR |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1270_REMUNAVNP — TABLE TFPS1270_REMUNAVNP
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| VRBCCP00 | Float |  | VRBCCP00 |  |
| VRBCCP15 | Float |  | VRBCCP15 |  |
| VRBCCP20 | Float |  | VRBCCP20 |  |
| VRBCCP25 | Float |  | VRBCCP25 |  |
| VRBCCP13 | Float |  | VRBCCP13 |  |
| VRBCFGTS | Float |  | VRBCFGTS |  |
| VRDESCCP | Float |  | VRDESCCP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1280 — TABLE TFPS1280
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| INDAPURACAO | Integer |  | INDAPURACAO |  |
| PERAPUR | String |  | PERAPUR |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| INDSUBSTPATR | Integer |  | INDSUBSTPATR |  |
| PERCREDCONTRIB | Float |  | PERCREDCONTRIB |  |
| FATORMES | Float |  | FATORMES |  |
| FATOR13 | Float |  | FATOR13 |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1300 — TABLE TFPS1300
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| INDRETIF | Integer |  | INDRETIF |  |
| INDAPURACAO | Integer |  | INDAPURACAO |  |
| PERAPUR | String |  | PERAPUR |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS1300_CONTRIBSIND — TABLE TFPS1300_CONTRIBSIND
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| PERAPUR | String |  | PERAPUR |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CNPJSINDIC | String |  | CNPJSINDIC |  |
| TPCONTRIBSIND | Integer |  | TPCONTRIBSIND |  |
| VLRCONTRIBSIND | Float |  | VLRCONTRIBSIND |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2190 — TABLE TFPS2190
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| STATUS | String |  | STATUS |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CPFTRAB | String |  | CPFTRAB |  |
| DTNASCTO | DateTime |  | DTNASCTO |  |
| DTADM | DateTime |  | DTADM |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2200 — TABLE TFPS2200
Campos: 179

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Período |  |
| DTALTERACAO | Date |  | Data da Ocorrência |  |
| STATUS | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio |
| STATUSENVIO | String |  | Status envio eSocial |  |
| STATUSEVENTO | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio `S`=Pendente de envio - erro no envio |
| ACAO | String |  | Ação | `A`=Retificação `E`=Exclusão `I`=Inclusão |
| NRORECIBO | String |  | N° do Recibo |  |
| NMTRAB | String |  | Nome do trabalhador |  |
| CPFTRAB | String |  | CPF |  |
| DTNASCTONASCIMENTO | Date |  | Data de nascimento |  |
| DTADM | Date |  | Data de início (data de admissão) |  |
| CODCATEG | Integer |  | Categoria eSocial |  |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| RACACOR | Integer |  | Raça/Etnia | `1`=Branca `2`=Preta `3`=Parda `4`=Amarela `5`=Indígena_(+1)_ |
| ESTCIV | Integer |  | Estado Civil | `1`=Solteiro(a) `2`=Casado(a) `3`=Divorciado(a) `4`=Separado(a) `5`=Viúvo(a) |
| GRAUINSTR | String |  | Escolaridade | `1`=Analfabeto `10`=Pós-Graduação Completa `11`=Mestrado Completo `12`=Doutorado Completo `2`=Ate 5º Ano Incompleto_(+7)_ |
| NMSOC | String |  | Nome Social |  |
| PAISNASCTONASCIMENTO | Integer |  | Cód. Nacionalidade (Tabela 06 - Países) |  |
| PAISNACNASCIMENTO | Integer |  | Cód. País de Nascimento (Tabela 06 - Países) |  |
| TPLOGRADBRASIL | String |  | Tipo de Logradouro |  |
| DSCLOGRADBRASIL | String |  | Descrição do logradouro |  |
| NRLOGRADBRASIL | String |  | Número |  |
| COMPLEMENTOBRASIL | String |  | Complemento |  |
| UFBRASIL | String |  | UF |  |
| BAIRROBRASIL | String |  | Bairro |  |
| CEPBRASIL | String |  | CEP |  |
| CODMUNICBRASIL | String |  | Cód. do Município Brasil (Tabela do IBGE) |  |
| DEFFISICA | String |  | Deficiência física | `N`=Não `S`=Sim |
| TMPRESID | String |  | Tempo de residência do Trabalhador Imigrante | `1`=1 - Prazo Indeterminado `2`=2 - Prazo Determinado |
| DEFVISUAL | String |  | Deficiência visual | `N`=Não `S`=Sim |
| CONDING | String |  | Condição de ingresso do trabalhador imigrante | `1`=1 - Refugiado `2`=2 - Solicitante de refúgio `3`=3 - Permanência no Brasil em razão de reunião familiar `4`=4 - Beneficiado pelo acordo entre países do Mercosul `5`=5- Dependente de agente diplomático e/ou consular com acordo de reciprocidade e atividade remunerada_(+2)_ |
| DEFAUDITIVA | String |  | Deficiência auditiva | `N`=Não `S`=Sim |
| DEFMENTAL | String |  | Deficiência mental | `N`=Não `S`=Sim |
| DEFINTELECTUAL | String |  | Deficiência intelectual | `N`=Não `S`=Sim |
| REABREADAP | String |  | Reabilitado/Readaptado | `N`=Não `S`=Sim |
| INFOCOTA | String |  | Cota | `N`=Não `S`=Sim |
| FONEPRINC | String |  | Fone principal |  |
| EMAILPRINC | String |  | Email Principal |  |
| CADINI | String |  | Cadastramento inicial | `N`=Não `S`=Sim |
| MATRICULA | String |  | Matrícula |  |
| TPREGTRAB | Integer |  | Regime Trabalhista | `1`=CLT - Consolidação das Leis de Trabalho `2`=Estatutário/legislações específicas (servidor temp., militar, agente polít., etc.) |
| TPREGPREV | Integer |  | Regime previdenciário | `1`=Regime Geral de Previdência Social - RGPS `2`=Regime Próprio de Previdência Social - RPPS `3`=Regime de Previdência Social no exterior `4`=Sistema de Proteção Social dos Militares das Forças Armadas - SPSMFA |
| TPADMISSAO | Integer |  | Tipo de Admissão | `1`=Admissão `2`=Transf. de emp. consórcio ou órgãos Ente Federa. `3`=Transferência de empresa consorciada ou de consórcio `4`=Transf. por motivo de sucessão, incorporação, cisão ou fusão `5`=Transf. empre. domés.outro repre. mesma unidade familiar_(+2)_ |
| INDADMISSAO | Integer |  | Indicativo de admissão | `1`=Normal `2`=Decorrente de ação fiscal `3`=Decorrente de decisão judicial |
| NRPROCTRAB | String |  | N° Processo Trabalhista |  |
| TPREGJOR | Integer |  | Regime de Jornada | `1`=Submetido a horário de trabalho (Capítulo II do Título II da CLT) `2`=Atividade externa especificada no inciso I do art. 62 da CLT `3`=Função especificada no inciso II do art. 62 da CLT `4`=Teletrabalho, previsto no inciso III do art. 62 da CLT |
| NATATIVIDADE | Integer |  | Natureza da Atividade | `1`=Trabalho urbano `2`=Trabalho rural |
| DTBASE | Integer |  | Data Base | `1`=Janeiro `10`=Outubro `11`=Novembro `12`=Dezembro `2`=Fevereiro_(+7)_ |
| CNPJSINDTRAB | String |  | CNPJ do Sindicato |  |
| MATANOTJUD | String |  | Matrícula Anotação Judicial |  |
| DTOPCFGTS | Date |  | Data da opção FGTS |  |
| HIPLEG | Integer |  | Hipótese Legal Trabalho Temporário |  |
| CPFTRABSUBST | String |  | CPF Substituto |  |
| INDAPREND | Integer |  | Indicativo de Contratação | `1`=Contratação direta: contrat. do aprendiz efetivada pelo estab. cumpridor da cota de aprendizagem `2`=Contratação indi. apren. por enti. sem fins lucra. ou prática despor. servi. estab. cumpridor cota |
| CNPJENTQUAL | String |  | CNPJ da Entidade Qualificadora |  |
| TPINSCAPREND | Integer |  | Tipo de Inscrição Contratante | `1`=CNPJ `2`=CPF |
| NRINSCAPREND | String |  | N° de inscrição Contratante |  |
| CNPJPRAT | String |  | CNPJ Entidade Prática |  |
| DESCRCARGO | String |  | Nome do Cargo |  |
| CBOCARGO | String |  | CBO do Cargo |  |
| DESCRFUNCAO | String |  | Nome da Função |  |
| CBOFUNCAO | String |  | CBO da função |  |
| DTINGRCARR | Date |  | Data de Ingresso no Cargo |  |
| VRSALFX | Float |  | Salário Base |  |
| UNDSALFIXO | Integer |  | Unidade de Pagamento | `1`=Por Hora `2`=Por dia `3`=Por semana `4`=Por quinzena `5`=Por mês_(+2)_ |
| DSCSALVAR | String |  | Descrição do salário |  |
| TPCONTR | Integer |  | Contrato de Trabalho | `1`=Prazo indeterminado `2`=Prazo determinado, definido em dias `3`=Prazo determinado, vinculado à ocorrência de um fato |
| DTTERM | DateTime |  | Data de término |  |
| CLAUASSEG | String |  | Cláusula assecuratória | `N`=Não `S`=Sim |
| OBJDET | String |  | Objeto determinante |  |
| TPLOGRADLOCALTRABDOM | String |  | Tipo de Logradouro |  |
| DSCLOGRADLOCALTRABDOM | String |  | Descrição do logradouro |  |
| NRLOGRADLOCALTRABDOM | String |  | Número |  |
| COMPLEMENTOLOCALTRABDOM | String |  | Complemento |  |
| UFLOCALTRABDOM | String |  | UF |  |
| QTDHRSSEM | Float |  | Horas Semanais |  |
| TPJORNADA | Integer |  | Tipo de Jornada | `2`=2 - Jornada 12x36 (12h trabalho 36h descanso ininterrupto) `3`=3 - Jornada com horário diário fixo e folga variável `4`=4 - Jornada com horário diário fixo e folga fixa (no domingo) `5`=5 - Jornada com horário diário fixo e folga fixa (exceto no domingo) `6`=6 - Jornada hr/diário fixo e folga fixa(outro dia da sem.), c/ folga adi. periódica domingo_(+2)_ |
| TMPPARC | String |  | Contrato em Tempo Parcial | `0`=Não é contrato em tempo parcial `1`=Limitado a 25 horas semanais `2`=Limitado a 30 horas semanais `3`=Limitado a 26 horas semanais |
| HRNOTURNO | String |  | Horário Noturno | `N`=Não `S`=Sim |
| DSCTPJORN | String |  | Descrição da Jornada Semanal |  |
| NRPROCJUDALVARAJUDICIAL | String |  | N° Processo Trabalhista (Alvara Judícial) |  |
| DTADMJUD | Date |  | Data admissão (Decisão Judicial) |  |
| JUSTCONTR | String |  | Observação (contrato de trabalho) |  |
| CNPJEMPREGANT | String |  | Empresa |  |
| MATRICANT | String |  | Matrícula Anterior |  |
| DTINIVINCULO | Date |  | Data da Transferência |  |
| OBSERVACAOSUCESSAOVINC | String |  | Observação |  |
| DTINIAFAST | Date |  | Data início afastamento |  |
| CODMOTAFAST | String |  | Motivo de afastamento |  |
| OPCFGTS | Integer |  | Optante FGTS |  |
| TPINCLCONTR | Integer |  | Tipo de Inclusão Contratual |  |
| TPINSCIDETOMADORSERV | Integer |  | TPINSCIDETOMADORSERV |  |
| NRINSCIDETOMADORSERV | String |  | NRINSCIDETOMADORSERV |  |
| TPINSCIDEESTABVINC | Integer |  | TPINSCIDEESTABVINC |  |
| NRINSCIDEESTABVINC | String |  | NRINSCIDEESTABVINC |  |
| INDPROVIM | Integer |  | Indicativo de Provimento |  |
| TPPROV | Integer |  | Tipo de Provimento |  |
| DTNOMEACAO | DateTime |  | Data Nomeação |  |
| DTPOSSE | DateTime |  | Data da Posse |  |
| TRAVESTITRANSEXUAL | String |  | Travesti ou Transexual? | `N`=Não `S`=Sim |
| NISTRAB | String |  | N° de inscrição do segurado - NIS |  |
| NMCIDEXTERIOR | String |  | Nome da Cidade Exterior |  |
| NMMAENASCIMENTO | String |  | Nome da Mãe |  |
| NMPAINASCIMENTO | String |  | Nome do Pai |  |
| NRCTPS | String |  | N° CTPS |  |
| NRINSCEMPREGADOR | String |  | N° de inscrição Contratante |  |
| NRLOGRADEXTERIOR | String |  | N° do logradouro Exterior |  |
| NROC | String |  | N° do Registro de Órgão da Classe |  |
| NRRECINFPRELIM | String |  | NRRECINFPRELIM |  |
| NRREGCNH | String |  | N° RG |  |
| NRRG | String |  | N° RG |  |
| NRRIC | String |  | N° RIC |  |
| NRRNE | String |  | N° RNE |  |
| OBSERVACAO | String |  | Observação |  |
| ORGAOEMISSOROC | String |  | Órgão Emissor OC |  |
| ORGAOEMISSORRG | String |  | Órgão Emissor RG |  |
| ORGAOEMISSORRIC | String |  | Órgão Emissor RIC |  |
| ORGAOEMISSORRNE | String |  | Órgão Emissor RNE |  |
| PAISRESID | String |  | País de Residência |  |
| SERIECTPS | String |  | Série CTPS |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição Contratante | `1`=CNPJ `2`=CPF |
| TRABAPOSENT | String |  | Trabalhador Aposentado |  |
| UFCNH | String |  | UF CNH |  |
| UFCTPS | String |  | UF CTPS |  |
| UFNASCIMENTO | String |  | UF do Nascimento |  |
| BAIRROEXTERIOR | String |  | Bairro Exterior |  |
| CASADOBR | String |  | Casado com Brasileiro |  |
| CATEGORIACNH | String |  | Categoria da CNH |  |
| CLASSTRABESTRANG | Integer |  | Situação Estrangeira |  |
| CNPJSINDCATEGPROF | String |  | CNPJ do Sindicato |  |
| CODCARGO | String |  | Cargo |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNCAO | String |  | Função |  |
| CODPOSTALEXTERIOR | String |  | Código Postal Exterior |  |
| COMPLEMENTOEXTERIOR | String |  | Complemento Exterior |  |
| DSCLOGRADEXTERIOR | String |  | Descrição do logradouro Exterior |  |
| DTCHEGADA | DateTime |  | Data de chegada no País |  |
| DTDESLIG | Date |  | Data desligamento |  |
| DTEXERCICIO | DateTime |  | Data da Entrada em Exercício |  |
| DTEXPEDCNH | DateTime |  | Data de Expedição CNH |  |
| DTEXPEDRG | DateTime |  | Data de Expedição RG |  |
| DTEXPEDRIC | DateTime |  | Data de Expedição Registro de Identidade Civil |  |
| DTEXPEDRNE | DateTime |  | Data de Expedição RNE |  |
| DTPRIHAB | DateTime |  | Data Primeira Habilitação |  |
| DTVALIDCNH | DateTime |  | Data de Validade CNH |  |
| DTVALIDOC | DateTime |  | Data de Validade Documento |  |
| FILHOSBR | String |  | Possui Filhos Brasileiros |  |
| FONEALTERNAT | String |  | Fone Alternativo |  |
| INDPRIEMPR | String |  | Indicativo Primeiro Emprego |  |
| DTEXPEDOC | DateTime |  | Data de Expedição Documento |  |
| CODMUNICNASCIMENTO | Integer |  | Código do Município do Nascimento |  |
| TPPLANRP | Integer |  | Tipo de Plano de Segregação da Massa |  |
| NRPROCJUDINFODECJUD | String |  | NRPROCJUDINFODECJUD |  |
| CODCATEG2 | Integer |  | Cód. Categoria 2 |  |
| CODCARREIRA | String |  | Código Carreira |  |
| TPINSCLOCALTRABGERAL | Integer |  | Tipo Inscrição Local de Trabalho |  |
| NRINSCLOCALTRABGERAL | String |  | N° de Inscrição do Trabalhador |  |
| BAIRROLOCALTRABDOM | String |  | Bairro |  |
| CEPLOCALTRABDOM | String |  | CEP |  |
| CODMUNICLOCALTRABDOM | Integer |  | Código do Município |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NRORECIBO_ANT | String |  | N° do Recibo Anterior |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle de Alteração |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| DTREF_ANT | DateTime |  | Período Anterior |  |
| SEQUENCIA_ANT | Integer |  | Sequência Anterior |  |
| MODIFICOUCPF | String |  | Modificou CPF |  |
| CPFANT | String |  | CPF Anterior |  |
| MATRICULAANT | Integer |  | Matrícula anterior |  |
| DTALTCPF | DateTime |  | Data de Alteração do CPF |  |
| OBSALTCPF | String |  | Observação Alteração do CPF |  |
| TPINSCANT | Integer |  | Tipo de Inscrição Anterior |  |
| TPINSCINFOCELETISTA | Integer |  | Tipo de Inscrição | `1`=CNPJ `2`=CPF |
| NRINSCINFOCELETISTA | String |  | N° da Inscrição |  |
| CODTREICAP | String |  | Cód. do Treinamento/Capacitação |  |
| DESCREVT | String |  | Descrição |  |
| EXCLMANUAL | String |  | Exclusão manual |  |

## TFPS2200_DEPENDENTE — TABLE TFPS2200_DEPENDENTE
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | Período |  |
| TPDEP | String |  | Tipo de Dependente | `1`=Cônjuge `10`=Menor pobre do qual detenha a guarda judicial `11`=A pessoa absolutamente incapaz, da qual seja tutor ou curador `12`=Ex-cônjuge `2`=Companheiro(a) com filho ou vivendo há mais de 5 anos ou em união estável_(+6)_ |
| NMDEP | String |  | Nome do Dependente |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DTNASCTO | Date |  | Data de nascimento |  |
| CPFDEP | String |  | CPF Dependente |  |
| SEXODEP | String |  | Sexo do Dependente | `F`=Feminino `M`=Masculino |
| DEPIRRF | String |  | Dependente Constam no IRRF | `N`=Não `S`=Sim |
| DEPSF | String |  | Dependente Salário-Família | `N`=Não `S`=Sim |
| INCTRAB | String |  | Incapacidade Física/Mental | `N`=Não `S`=Sim |
| CHAVEPAI | String |  | Chave |  |
| CHAVE | String |  | Chave |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| DESCRDPD | String |  | Descrição da Dependência |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS2200_HORARIO — TABLE TFPS2200_HORARIO
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DIA | Integer |  | DIA |  |
| CODHORCONTRAT | String |  | CODHORCONTRAT |  |
| CHAVEPAI | String |  | CHAVEPAI |  |
| CHAVE | String |  | CHAVE |  |
| TPAMB | String |  | TPAMB |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2200_TFPFTRC — TABLE TFPS2200_TFPFTRC
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Período |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| CHAVEPAI | String |  | Chave Pai |  |
| CHAVE | String |  | Chave |  |
| CODTREICAP | Integer |  | Cód. do Treinamento/Capacitação |  |

## TFPS2205 — TABLE TFPS2205
Campos: 93

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTALTERACAO | Date |  | Data de alteração |  |
| STATUS | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio |
| STATUSENVIO | String |  | Status envio eSocial |  |
| STATUSEVENTO | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio `S`=Pendente de envio - erro no envio |
| ACAO | String |  | Ação | `A`=Retificação `E`=Exclusão `I`=Inclusão |
| NRORECIBO | String |  | Número do Recibo |  |
| NMTRAB | String |  | Nome do trabalhador |  |
| CPFTRAB | String |  | CPF |  |
| DTNASCTONASCIMENTO | Date |  | Data de nascimento |  |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| RACACOR | Integer |  | Raça/Etnia | `1`=Branca `2`=Preta `3`=Parda `4`=Amarela `5`=Indígena_(+1)_ |
| ESTCIV | Integer |  | Estado Civil | `1`=Solteiro(a) `2`=Casado(a) `3`=Divorciado(a) `4`=Separado(a) `5`=Viúvo(a) |
| GRAUINSTR | String |  | Escolaridade | `1`=Analfabeto `10`=Pós-Graduação Completa `11`=Mestrado Completo `12`=Doutorado Completo `2`=Ate 5º Ano Incompleto_(+7)_ |
| NMSOC | String |  | Nome Social |  |
| PAISNASCTONASCIMENTO | String |  | Cód. Nacionalidade (Tabela 06 - Países) |  |
| PAISNACNASCIMENTO | String |  | Cód. País de Nascimento (Tabela 06 - Países) |  |
| TPLOGRADBRASIL | String |  | Tipo de Logradouro |  |
| DSCLOGRADBRASIL | String |  | Descrição do logradouro |  |
| NRLOGRADBRASIL | String |  | Número |  |
| COMPLEMENTOBRASIL | String |  | Complemento |  |
| UFBRASIL | String |  | UF |  |
| BAIRROBRASIL | String |  | Bairro |  |
| CEPBRASIL | String |  | CEP |  |
| TMPRESID | String |  | Tempo de residência do Trabalhador Imigrante | `1`=1 - Prazo Indeterminado `2`=2 - Prazo Determinado |
| DEFFISICA | String |  | Deficiência física | `N`=Não `S`=Sim |
| CODMUNICBRASIL | Integer |  | Cód. do Município Brasil (Tabela do IBGE) |  |
| CONDING | String |  | Condição de Ingresso do Trabalhador Imigrante | `1`=1 - Refugiado `2`=2 - Solicitante de refúgio `3`=3 - Permanência no Brasil em razão de reunião familiar `4`=4 - Beneficiado pelo acordo entre países do Mercosul `5`=5- Dependente de agente diplomático e/ou consular com acordo de reciprocidade e atividade remunerada_(+2)_ |
| DEFVISUAL | String |  | Deficiência visual | `N`=Não `S`=Sim |
| DEFAUDITIVA | String |  | Deficiência auditiva | `N`=Não `S`=Sim |
| DEFMENTAL | String |  | Deficiência mental | `N`=Não `S`=Sim |
| DEFINTELECTUAL | String |  | Deficiência intelectual | `N`=Não `S`=Sim |
| REABREADAP | String |  | Reabilitado/Readaptado | `N`=Não `S`=Sim |
| INFOCOTA | String |  | Cota | `N`=Não `S`=Sim |
| OBSERVACAO | String |  | Observação |  |
| FONEPRINC | String |  | Telefone principal |  |
| EMAILPRINC | String |  | Email Principal |  |
| PAISRESID | String |  | País de Residência |  |
| DSCLOGRADEXTERIOR | String |  | Descrição do logradouro Exterior |  |
| NRLOGRADEXTERIOR | String |  | Número do logradouro Exterior |  |
| COMPLEMENTOEXTERIOR | String |  | Complemento Exterior |  |
| BAIRROEXTERIOR | String |  | Bairro Exterior |  |
| NMCIDEXTERIOR | String |  | Nome da Cidade Exterior |  |
| CODPOSTALEXTERIOR | String |  | Código Postal Exterior |  |
| DTCHEGADA | DateTime |  | Data de chegada no País |  |
| CLASSTRABESTRANG | Integer |  | Situação Estrangeira |  |
| CASADOBR | String |  | Casado com Brasileiro |  |
| FILHOSBR | String |  | Possui Filhos Brasileiros |  |
| TRABAPOSENT | String |  | Trabalhador Aposentado |  |
| FONEALTERNAT | String |  | Fone Alternativo |  |
| NRORECIBO_ANT | String |  | Número do Recibo Anterior |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle de Alteração |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| EMAILALTERNAT | String |  | Email Alternativo |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| CODMUNICNASCIMENTO | Integer |  | Código do Município do Nascimento |  |
| UFNASCIMENTO | String |  | UF do Nascimento |  |
| NMMAENASCIMENTO | String |  | Nome da Mãe |  |
| NMPAINASCIMENTO | String |  | Nome do Pai |  |
| DTREF_ANT | DateTime |  | Período Anterior |  |
| SEQUENCIA_ANT | Integer |  | Sequência Anterior |  |
| TPREGPREV | Integer |  | Regime previdenciário |  |
| DESCREVT | String |  | Descrição |  |
| TRAVESTITRANSEXUAL | String |  | Travesti ou Transexual? | `N`=Não `S`=Sim |
| CATEGORIACNH | String |  | Categoria da CNH |  |
| DTEXPEDCNH | DateTime |  | Data de Expedição CNH |  |
| DTEXPEDOC | DateTime |  | Data de Expedição Documento |  |
| DTEXPEDRG | DateTime |  | Data de Expedição RG |  |
| DTEXPEDRNE | DateTime |  | Data de Expedição RNE |  |
| DTPRIHAB | DateTime |  | Data Primeira Habilitação |  |
| DTREF | DateTime |  | Período |  |
| DTVALIDCNH | DateTime |  | Data de Validade CNH |  |
| DTVALIDOC | DateTime |  | Data de Validade Documento |  |
| NISTRAB | String |  | Número de inscrição do segurado - NIS |  |
| NRCTPS | String |  | Número CTPS |  |
| NROC | String |  | Número do Registro de Órgão da Classe |  |
| NRREGCNH | String |  | Número RG |  |
| NRRG | String |  | Número RG |  |
| NRRIC | String |  | Número RIC |  |
| NRRNE | String |  | Número RNE |  |
| ORGAOEMISSOROC | String |  | Órgão Emissor OC |  |
| ORGAOEMISSORRG | String |  | Órgão Emissor RG |  |
| ORGAOEMISSORRIC | String |  | Órgão Emissor RIC |  |
| ORGAOEMISSORRNE | String |  | Órgão Emissor RNE |  |
| SEQUENCIA | Integer |  | Sequência |  |
| SERIECTPS | String |  | Série CTPS |  |
| UFCNH | String |  | UF CNH |  |
| UFCTPS | String |  | UF CTPS |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição Empregador |  |
| DTEXPEDRIC | DateTime |  | Data de Expedição Registro de Identidade Civil |  |
| NRINSCEMPREGADOR | String |  | Número de inscrição empregador |  |
| EXCLMANUAL | String |  | Exclusão manual |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS2205_DEPENDENTE — TABLE TFPS2205_DEPENDENTE
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TPDEP | String |  | Tipo de Dependente | `1`=Cônjuge `10`=Menor pobre do qual detenha a guarda judicial `11`=A pessoa absolutamente incapaz, da qual seja tutor ou curador `12`=Ex-cônjuge `2`=Companheiro(a) com filho ou vivendo há mais de 5 anos ou em união estável_(+6)_ |
| NMDEP | String |  | Nome do Dependente |  |
| DTNASCTO | Date |  | Data de nascimento |  |
| CPFDEP | String |  | CPF Dependente |  |
| SEXODEP | String |  | Sexo do Dependente | `F`=Feminino `M`=Masculino |
| DEPIRRF | String |  | Dependente Constam no IRRF | `N`=Não `S`=Sim |
| DEPSF | String |  | Dependente Salário-Família | `N`=Não `S`=Sim |
| INCTRAB | String |  | Incapacidade Física/Mental | `N`=Não `S`=Sim |
| CHAVEPAI | String |  | Chave Pai |  |
| CHAVE | String |  | Chave |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| DESCRDPD | String |  | Descrição da Dependência |  |
| DTREF | DateTime |  | Período |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS2206 — TABLE TFPS2206
Campos: 77

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTALTERACAO | Date |  | Data de alteração |  |
| STATUS | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio |
| STATUSENVIO | String |  | Status envio eSocial |  |
| STATUSEVENTO | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio `S`=Pendente de envio - erro no envio |
| ACAO | String |  | Ação | `A`=Retificação `E`=Exclusão `I`=Inclusão |
| NRORECIBO | String |  | Número do Recibo |  |
| CPFTRAB | String |  | CPF |  |
| CODCATEG | Integer |  | Categoria eSocial |  |
| TPREGPREV | Integer |  | Regime previdenciário | `1`=Regime Geral de Previdência Social - RGPS `2`=Regime Próprio de Previdência Social - RPPS `3`=Regime de Previdência Social no exterior `4`=Sistema de Proteção Social dos Militares das Forças Armadas - SPSMFA |
| TPREGJOR | Integer |  | Regime de Jornada | `1`=Submetido a horário de trabalho (Capítulo II do Título II da CLT) `2`=Atividade externa especificada no inciso I do art. 62 da CLT `3`=Função especificada no inciso II do art. 62 da CLT `4`=Teletrabalho, previsto no inciso III do art. 62 da CLT |
| NATATIVIDADE | Integer |  | Natureza da Atividade | `1`=Trabalho urbano `2`=Trabalho rural |
| DTBASE | Integer |  | Data Base | `1`=Janeiro `10`=Outubro `11`=Novembro `12`=Dezembro `2`=Fevereiro_(+7)_ |
| CNPJSINDTRAB | String |  | CNPJ do Sindicato |  |
| DTEF | Date |  | Data dos efeitos remuneratórios da alteração contratual |  |
| DSCALT | String |  | Descrição da Alteração |  |
| JUSTPRORR | String |  | Justificativa para a Prorrogação |  |
| INDAPREND | Integer |  | Indicativo de Contratação Aprendiz | `1`=Contratação direta: contrat. do aprendiz efetivada pelo estab. cumpridor da cota de aprendizagem `2`=Contratação indi. apren. por enti. sem fins lucra. ou prática despor. servi. estab. cumpridor cota |
| CNPJENTQUAL | String |  | CNPJ Entidade Qualificadora |  |
| TPINSCAPREND | Integer |  | Tipo de Inscrição Aprendiz | `1`=CNPJ `2`=CPF |
| CNPJPRAT | String |  | CNPJ Atividades Práticas |  |
| DESCRCARGO | String |  | Cargo |  |
| CBOCARGO | String |  | CBO Cargo |  |
| DESCRFUNCAO | String |  | Função |  |
| CBOFUNCAO | String |  | CBO Função |  |
| VRSALFX | Float |  | Salário base |  |
| UNDSALFIXO | Integer |  | Unidade de Pagamento | `1`=Por Hora `2`=Por dia `3`=Por semana `4`=Por quinzena `5`=Por mês_(+2)_ |
| DSCSALVAR | String |  | Descrição do salário |  |
| TPCONTR | Integer |  | Tipo de Contrato | `1`=Prazo indeterminado `2`=Prazo determinado, definido em dias `3`=Prazo determinado, vinculado à ocorrência de um fato |
| DTTERM | Date |  | Data de término |  |
| OBJDET | String |  | Objeto determinante |  |
| TPINSCLOCALTRABGERAL | Integer |  | Tipo de Inscrição | `1`=CNPJ `2`=CPF |
| DSCLOGRADLOCALTRABDOM | String |  | Logradouro |  |
| NRLOGRADLOCALTRABDOM | String |  | Número |  |
| COMPLEMENTOLOCALTRABDOM | String |  | Complemento |  |
| BAIRROLOCALTRABDOM | String |  | Bairro |  |
| CEPLOCALTRABDOM | String |  | CEP |  |
| CODMUNICLOCALTRABDOM | Integer |  | Cidade |  |
| UFLOCALTRABDOM | String |  | UF |  |
| QTDHRSSEM | Float |  | Horas Semanais |  |
| TPJORNADA | Integer |  | Tipo de Jornada | `2`=2 - Jornada 12x36 (12h trabalho 36h descanso ininterrupto) `3`=3 - Jornada com horário diário fixo e folga variável `4`=4 - Jornada com horário diário fixo e folga fixa (no domingo) `5`=5 - Jornada com horário diário fixo e folga fixa (exceto no domingo) `6`=6 - Jornada hr/diário fixo e folga fixa(outro dia da sem.), c/ folga adi. periódica domingo_(+2)_ |
| TMPPARC | String |  | Tempo Parcial |  |
| HRNOTURNO | String |  | Horário Noturno | `N`=Não `S`=Sim |
| DSCTPJORN | String |  | Descrição da Jornada |  |
| NRPROCJUDALVARAJUDICIAL | String |  | Nº do Processo Judicial |  |
| MTVALTER | Integer |  | Motivo da Alteração |  |
| NRORECIBO_ANT | String |  | Número do Recibo Anterior |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle de Alteração |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| DTREF_ANT | DateTime |  | Período Anterior |  |
| SEQUENCIA_ANT | Integer |  | Sequência Anterior |  |
| TPINSCINFOCELETISTA | Integer |  | Tipo de Inscrição |  |
| NRINSCINFOCELETISTA | String |  | Número da Inscrição |  |
| INDRETIF | Integer |  | Indicativo de Retificação |  |
| OBSERVACAO | String |  | Observação |  |
| CODTREICAP | String |  | Cód. do Treinamento/Capacitação |  |
| NRINSCAPREND | String |  | Número de Inscrição Aprendiz |  |
| DESCREVT | String |  | Descrição |  |
| CNPJSINDCATEGPROF | String |  | CNPJ do Sindicato |  |
| CODCARGO | String |  | Cargo |  |
| CODCARREIRA | String |  | Código Carreira |  |
| CODCATEG2 | Integer |  | Código de categoria eSocial 2 |  |
| CODFUNCAO | String |  | Função |  |
| DTINGRCARR | DateTime |  | Data de Ingresso do Servidor no Cargo |  |
| DTREF | DateTime |  | Período |  |
| MATRICULA | String |  | Matrícula |  |
| NISTRAB | String |  | Número de inscrição do segurado - NIS |  |
| NRINSCEMPREGADOR | String |  | Número de inscrição empregador |  |
| NRINSCLOCALTRABGERAL | String |  | Número de Inscrição do Trabalhador |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição | `1`=CNPJ `2`=CPF |
| TPLOGRADLOCALTRABDOM | String |  | Logradouro |  |
| TPPLANRP | Integer |  | Tipo de Plano de Segregação da Massa |  |
| TPREGTRAB | Integer |  | Tipo de Regime Trabalhista |  |
| EXCLMANUAL | String |  | Exclusão manual |  |
| CODEMP | Integer |  | Empresa |  |

## TFPS2206_HORARIO — TABLE TFPS2206_HORARIO
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DIA | Integer |  | DIA |  |
| CODHORCONTRAT | String |  | CODHORCONTRAT |  |
| CHAVEPAI | String |  | CHAVEPAI |  |
| CHAVE | String |  | CHAVE |  |
| TPAMB | String |  | TPAMB |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2206_TFPFTRC — TABLE TFPS2206_TFPFTRC
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Período |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| CHAVEPAI | String |  | Chave Pai |  |
| CHAVE | String |  | Chave |  |
| CODTREICAP | Integer |  | Cód. do Treinamento/Capacitação |  |

## TFPS2210 — TABLE TFPS2210
Campos: 66

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| STATUS | String |  | STATUS |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | Número da Inscrição |  |
| CODEMPFUNC | Integer |  | CODEMPFUNC |  |
| CODFUNC | Integer |  | CODFUNC |  |
| CPFTRAB | String |  | CPF |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCATEG | Integer |  | Categoria e-Social |  |
| DTACID | DateTime |  | Data do Acidente |  |
| TPACID | String |  | Tipo de Acidente | `1`=Tipico `2`=Doença `3`=Trajeto |
| HRACID | String |  | Hora do Acidente |  |
| HRSTRABANTESACID | String |  | Horas Trabalhadas |  |
| TPCAT | Integer |  | Tipo de CAT | `1`=Inicial `2`=Reabertura `3`=Comunicação de Óbito |
| INDCATOBITO | String |  | Indica Óbito |  |
| DTOBITO | DateTime |  | Data Óbito |  |
| INDCOMUNPOLICIA | String |  | Houve Comunicação Policial? |  |
| CODSITGERADORA | Integer |  | Situação Geradora do Acidente |  |
| INICIATCAT | Integer |  | Iniciativa da CAT |  |
| OBSERVACAO | String |  | Observações |  |
| TPLOCAL | Integer |  | Tipo de Local | `1`=1 - Estab. do empregador no Brasil `2`=2 - Estab. do empregador no Exterior `3`=3 - Estab. de terceiros onde presta serviço `4`=4 - Via pública `5`=5 - Área rural_(+2)_ |
| DSCLOCAL | String |  | Especificação do Local |  |
| CODAMB | String |  | Ambiente de Trabalho |  |
| DSCLOGRAD | String |  | Logradouro |  |
| NRLOGRAD | String |  | Número Endereço |  |
| COMPLEMENTO | String |  | Complemento |  |
| BAIRRO | String |  | Bairro |  |
| CEP | String |  | CEP |  |
| CODMUNIC | Integer |  | Cidade |  |
| UF | String |  | UF |  |
| PAIS | String |  | País |  |
| CODPOSTAL | String |  | Cod. Postal] |  |
| TPINSCLOCALACID | Integer |  | Tipo Inscrição Local Acidente |  |
| NRINSCLOCALACID | String |  | Número da Inscrição |  |
| CODCNES | String |  | CNES |  |
| DTATENDIMENTO | DateTime |  | Data de Atendimento |  |
| HRATENDIMENTO | String |  | Hora Atendimento |  |
| INDINTERNACAO | String |  | Houve internação? |  |
| DURTRAT | Integer |  | Duração do tratamento (em dias) |  |
| INDAFAST | String |  | Indicativo de repouso durante o tratamento? |  |
| DSCLESAO | Integer |  | Descr. compl. / natureza da lesão |  |
| DSCCOMPLESAO | String |  | Descr. compl. / natureza da lesão - Atestado Médico |  |
| DIAGPROVAVEL | String |  | Diagnóstico Provável |  |
| CODCID | String |  | CID |  |
| OBSERVACAOATESTADO | String |  | Observações - Atestado Médico |  |
| NMEMIT | String |  | Médico/Dentista |  |
| IDEOC | Integer |  | Órgão de Classe | `1`=1 - Conselho Regional de Medicina - CRM `2`=2 - Conselho Regional de Odontologia - CRO `3`=3 - Registro do Ministério da Saúde - RMS |
| NROC | String |  | Inscrição no Órgão de Classe/Registro do MS(RMS) |  |
| UFOC | String |  | UF Órgão de classe |  |
| DTCATORIG | DateTime |  | Data de Atendimento CAT Original |  |
| NRRECCATORIG | String |  | Nº CAT Origem |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| TPLOGRAD | String |  | Tipo Logradouro |  |
| ULTDIATRAB | Date |  | Último dia Trabalhado |  |
| HOUVEAFAST | String |  | Houve Afastamento? |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2210_AC — TABLE TFPS2210_AC
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2210 | String |  | CHAVE2210 |  |
| CHAVE | String |  | CHAVE |  |
| CODAGNTCAUSADOR | Integer |  | Agente Causador |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2210_PA — TABLE TFPS2210_PA
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2210 | String |  | CHAVE2210 |  |
| CHAVE | String |  | CHAVE |  |
| CODPARTEATING | Integer |  | Parte Atingida |  |
| LATERALIDADE | Integer |  | Lateralidade | `0`=0 - Não aplicável `1`=1 - Esquerda `2`=2 - Direita `3`=3 - Ambas |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2220 — TABLE TFPS2220
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| STATUS | String |  | STATUS |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODEMPFUNC | Integer |  | CODEMPFUNC |  |
| CODFUNC | Integer |  | CODFUNC |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCATEG | Integer |  | CODCATEG |  |
| TPEXAMEOCUP | Integer |  | TPEXAMEOCUP |  |
| DTASO | DateTime |  | DTASO |  |
| RESASO | Integer |  | RESASO |  |
| CPFMED | String |  | CPFMED |  |
| NISMED | String |  | NISMED |  |
| NMMED | String |  | NMMED |  |
| NRCRM | String |  | NRCRM |  |
| UFCRM | String |  | UFCRM |  |
| CPFRESP | String |  | CPFRESP |  |
| NMRESP | String |  | NMRESP |  |
| NRCRMRESPMONIT | String |  | NRCRMRESPMONIT |  |
| UFCRMRESPMONIT | String |  | UFCRMRESPMONIT |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2220_EXAME — TABLE TFPS2220_EXAME
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2220 | String |  | CHAVE2220 |  |
| CHAVE | String |  | CHAVE |  |
| DTEXM | DateTime |  | DTEXM |  |
| PROCREALIZADO | Integer |  | PROCREALIZADO |  |
| OBSPROC | String |  | OBSPROC |  |
| ORDEXAME | Integer |  | ORDEXAME |  |
| INDRESULT | Integer |  | INDRESULT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2221 — TABLE TFPS2221
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| STATUS | String |  | STATUS |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODEMPFUNC | Integer |  | CODEMPFUNC |  |
| CODFUNC | Integer |  | CODFUNC |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCATEG | Integer |  | CODCATEG |  |
| DTEXAME | DateTime |  | DTEXAME |  |
| CNPJLAB | String |  | CNPJLAB |  |
| CODSEQEXAME | String |  | CODSEQEXAME |  |
| NMMED | String |  | NMMED |  |
| NRCRM | String |  | NRCRM |  |
| UFCRM | String |  | UFCRM |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| INDRECUSA | String |  | INDRECUSA |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2230 — TABLE TFPS2230
Campos: 34

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| STATUS | String |  | STATUS |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCATEG | Integer |  | CODCATEG |  |
| DTINIAFAST | DateTime |  | DTINIAFAST |  |
| CODMOTAFAST | String |  | CODMOTAFAST |  |
| INFOMESMOMTV | String |  | INFOMESMOMTV |  |
| TPACIDTRANSITO | Integer |  | TPACIDTRANSITO |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| CNPJCESS | String |  | CNPJCESS |  |
| INFONUS | Integer |  | INFONUS |  |
| CNPJSIND | String |  | CNPJSIND |  |
| INFONUSREMUN | Integer |  | INFONUSREMUN |  |
| ORIGRETIF | Integer |  | ORIGRETIF |  |
| TPPROC | String |  | TPPROC |  |
| NRPROC | String |  | NRPROC |  |
| TEM2300 | Integer |  | TEM2300 |  |
| DTTERMAFAST | DateTime |  | DTTERMAFAST |  |
| CHAVE2200 | String |  | CHAVE2200 |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2230_ATESTADO — TABLE TFPS2230_ATESTADO
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUOCOR | String |  | NUOCOR |  |
| CHAVE | String |  | CHAVE |  |
| CODCID | String |  | CODCID |  |
| QTDDIASAFAST | Integer |  | QTDDIASAFAST |  |
| NMEMIT | String |  | NMEMIT |  |
| IDEOC | Integer |  | IDEOC |  |
| NROC | String |  | NROC |  |
| UFOC | String |  | UFOC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2240 — TABLE TFPS2240
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| STATUS | String |  | STATUS |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| CODEMPFUNC | Integer |  | CODEMPFUNC |  |
| CODFUNC | Integer |  | CODFUNC |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCATEG | Integer |  | CODCATEG |  |
| DTINICONDICAO | DateTime |  | DTINICONDICAO |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2240_FATRISCO — TABLE TFPS2240_FATRISCO
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2240 | String |  | CHAVE2240 |  |
| CHAVE | String |  | CHAVE |  |
| CODFATRIS | String |  | CODFATRIS |  |
| TPAVAL | Integer |  | TPAVAL |  |
| INTCONC | Float |  | INTCONC |  |
| LIMTOT | Float |  | LIMTOT |  |
| UNMED | Integer |  | UNMED |  |
| TECMEDICAO | String |  | TECMEDICAO |  |
| INSALUBRIDADE | String |  | INSALUBRIDADE |  |
| PERICULOSIDADE | String |  | PERICULOSIDADE |  |
| APOSENTESP | String |  | APOSENTESP |  |
| UTILIZEPC | Integer |  | UTILIZEPC |  |
| UTILIZEPI | Integer |  | UTILIZEPI |  |
| EFICEPC | String |  | EFICEPC |  |
| DSCFATRISC | String |  | DSCFATRISC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2240_FATRISCO_EPI — TABLE TFPS2240_FATRISCO_EPI
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2240 | String |  | CHAVE2240 |  |
| CHAVERISCO | String |  | CHAVERISCO |  |
| CHAVE | String |  | CHAVE |  |
| CAEPI | String |  | CAEPI |  |
| DSCEPI | String |  | DSCEPI |  |
| EFICEPI | String |  | EFICEPI |  |
| MEDPROTECAO | String |  | MEDPROTECAO |  |
| CONDFUNCTO | String |  | CONDFUNCTO |  |
| PRZVALID | String |  | PRZVALID |  |
| PERIODICTROCA | String |  | PERIODICTROCA |  |
| HIGIENIZACAO | String |  | HIGIENIZACAO |  |
| USOININT | String |  | USOININT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2240_INFOAMB — TABLE TFPS2240_INFOAMB
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2240 | String |  | CHAVE2240 |  |
| CHAVE | String |  | CHAVE |  |
| CODAMB | String |  | CODAMB |  |
| DSCATIVDES | String |  | DSCATIVDES |  |
| METERG | String |  | METERG |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2240_INFOAMB_AP — TABLE TFPS2240_INFOAMB_AP
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2240 | String |  | CHAVE2240 |  |
| CHAVEINFOAMB | String |  | CHAVEINFOAMB |  |
| CHAVE | String |  | CHAVE |  |
| CODATIV | String |  | CODATIV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2240_RESPREG — TABLE TFPS2240_RESPREG
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2240 | String |  | CHAVE2240 |  |
| CHAVE | String |  | CHAVE |  |
| CPFRESP | String |  | CPFRESP |  |
| NISRESP | String |  | NISRESP |  |
| NMRESP | String |  | NMRESP |  |
| IDEOC | Integer |  | IDEOC |  |
| DSCOC | String |  | DSCOC |  |
| NROC | String |  | NROC |  |
| UFOC | String |  | UFOC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2245 — TABLE TFPS2245
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| STATUS | String |  | STATUS |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODEMPFUNC | Integer |  | CODEMPFUNC |  |
| CODFUNC | Integer |  | CODFUNC |  |
| NROUNICOTREIN | Integer |  | NROUNICOTREIN |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCATEG | Integer |  | CODCATEG |  |
| CODTREICAP | String |  | CODTREICAP |  |
| DTTREICAP | DateTime |  | DTTREICAP |  |
| DURTREICAP | Float |  | DURTREICAP |  |
| MODTREICAP | Integer |  | MODTREICAP |  |
| TPTREICAP | Integer |  | TPTREICAP |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| INDTREINANT | String |  | INDTREINANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2245_IDEPROFRESP — TABLE TFPS2245_IDEPROFRESP
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2245 | String |  | CHAVE2245 |  |
| CHAVE | String |  | CHAVE |  |
| CPFPROF | String |  | CPFPROF |  |
| NMPROF | String |  | NMPROF |  |
| TPPROF | Integer |  | TPPROF |  |
| MATRICULA | String |  | MATRICULA |  |
| FORMPROF | String |  | FORMPROF |  |
| CODCBO | String |  | CODCBO |  |
| NACPROF | Integer |  | NACPROF |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2250 — TABLE TFPS2250
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| STATUS | String |  | STATUS |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| DTAVPRV | DateTime |  | DTAVPRV |  |
| DTPREVDESLIG | DateTime |  | DTPREVDESLIG |  |
| TPAVPREVIO | Integer |  | TPAVPREVIO |  |
| OBSERVACAODET | String |  | OBSERVACAODET |  |
| DTCANCAVPRV | DateTime |  | DTCANCAVPRV |  |
| OBSERVACAOCANC | String |  | OBSERVACAOCANC |  |
| MTVCANCAVPREVIO | Integer |  | MTVCANCAVPREVIO |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2260 — TABLE TFPS2260
Campos: 35

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMPFUNC | Integer |  | CODEMPFUNC |  |
| CODFUNC | Integer |  | CODFUNC |  |
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCONV | String |  | CODCONV |  |
| DTINICIO | DateTime |  | DTINICIO |  |
| DTFIM | DateTime |  | DTFIM |  |
| CODHORCONTRAT | String |  | CODHORCONTRAT |  |
| DSCJORNADA | String |  | DSCJORNADA |  |
| INDLOCAL | String |  | INDLOCAL |  |
| TPLOGRAD | String |  | TPLOGRAD |  |
| DSCLOGRAD | String |  | DSCLOGRAD |  |
| NRLOGRAD | String |  | NRLOGRAD |  |
| COMPLEMENTO | String |  | COMPLEMENTO |  |
| BAIRRO | String |  | BAIRRO |  |
| CEP | String |  | CEP |  |
| CODMUNIC | String |  | CODMUNIC |  |
| UF | String |  | UF |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CHAVE | String |  | CHAVE |  |
| CONTROLE | String |  | CONTROLE |  |
| TPAMB | String |  | TPAMB |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTPREVPGTO | DateTime |  | DTPREVPGTO |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2298 — TABLE TFPS2298
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| TPREINT | String |  | TPREINT |  |
| NRPROCJUD | String |  | NRPROCJUD |  |
| NRLEIANISTIA | String |  | NRLEIANISTIA |  |
| DTEFETRETORNO | DateTime |  | DTEFETRETORNO |  |
| DTEFEITO | DateTime |  | DTEFEITO |  |
| INDPAGTOJUIZO | String |  | INDPAGTOJUIZO |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CHAVE | String |  | CHAVE |  |
| CONTROLE | String |  | CONTROLE |  |
| TPAMB | String |  | TPAMB |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299 — TABLE TFPS2299
Campos: 40

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| MATRICULA | String |  | MATRICULA |  |
| MTVDESLIG | String |  | MTVDESLIG |  |
| DTDESLIG | DateTime |  | DTDESLIG |  |
| INDPAGTO | String |  | INDPAGTO |  |
| DTPROJFIMAPI | DateTime |  | DTPROJFIMAPI |  |
| PENSALIM | String |  | PENSALIM |  |
| PERCALIM | Float |  | PERCALIM |  |
| VRALIM | Float |  | VRALIM |  |
| NRCERTOBITO | String |  | NRCERTOBITO |  |
| PRPROCTRAB | String |  | PRPROCTRAB |  |
| INDCUMPRPARC | String |  | INDCUMPRPARC |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| CNPJSUCESSORA | String |  | CNPJSUCESSORA |  |
| CPFSUBSTITUTO | String |  | CPFSUBSTITUTO |  |
| DTNASCTOSUBSTITUTO | DateTime |  | DTNASCTOSUBSTITUTO |  |
| IDCONSIG | String |  | IDCONSIG |  |
| INSCONSIG | String |  | INSCONSIG |  |
| NRCONTR | String |  | NRCONTR |  |
| DTFIMQUAR | DateTime |  | DTFIMQUAR |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CHAVE | String |  | CHAVE |  |
| CONTROLE | String |  | CONTROLE |  |
| TPAMB | String |  | TPAMB |  |
| QTDDIASINTERM | String |  | QTDDIASINTERM |  |
| INDMV | Integer |  | INDMV |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| NOVOCPF | String |  | NOVOCPF |  |
| TPINSCSUC | Integer |  | TPINSCSUC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_CONSIGFGTS — TABLE TFPS2299_CONSIGFGTS
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| CHAVE | String |  | CHAVE |  |
| INSCONSIG | String |  | INSCONSIG |  |
| NRCONTR | String |  | NRCONTR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV — TABLE TFPS2299_DMDEV
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| CHAVE | String |  | CHAVE |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_ADC — TABLE TFPS2299_DMDEV_ADC
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE | String |  | CHAVE |  |
| DTACCONV | DateTime |  | DTACCONV |  |
| TPACCONV | String |  | TPACCONV |  |
| COMPACCONV | String |  | COMPACCONV |  |
| DTEFACCONV | DateTime |  | DTEFACCONV |  |
| DSC | String |  | DSC |  |
| REMUNSUC | String |  | REMUNSUC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_DDRPA — TABLE TFPS2299_DMDEV_DDRPA
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CNPJOPER | String |  | CNPJOPER |  |
| CHAVE | String |  | CHAVE |  |
| TPDEP | String |  | TPDEP |  |
| CPFDEP | String |  | CPFDEP |  |
| NMDEP | String |  | NMDEP |  |
| DTNASCTO | DateTime |  | DTNASCTO |  |
| VLRPGDEP | Float |  | VLRPGDEP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_DRPA — TABLE TFPS2299_DMDEV_DRPA
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| CNPJOPER | String |  | CNPJOPER |  |
| REGANS | String |  | REGANS |  |
| VRPGTIT | Float |  | VRPGTIT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_EL — TABLE TFPS2299_DMDEV_EL
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| GRAUEXP | Integer |  | GRAUEXP |  |
| INDSIMPLES | Integer |  | INDSIMPLES |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_IPADC — TABLE TFPS2299_DMDEV_IPADC
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE2299_PA_ADC | String |  | CHAVE2299_PA_ADC |  |
| PERREF | String |  | PERREF |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_IRPA — TABLE TFPS2299_DMDEV_IRPA
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_IRPADC — TABLE TFPS2299_DMDEV_IRPADC
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE2299_PA_ADC | String |  | CHAVE2299_PA_ADC |  |
| PERREF | String |  | PERREF |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_PADC — TABLE TFPS2299_DMDEV_PADC
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE2299_PA_ADC | String |  | CHAVE2299_PA_ADC |  |
| CHAVE | String |  | CHAVE |  |
| PERREF | String |  | PERREF |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_RPA — TABLE TFPS2299_DMDEV_RPA
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| MATRICULA | String |  | MATRICULA |  |
| INDSIMPLES | Integer |  | INDSIMPLES |  |
| GRAUEXP | Integer |  | GRAUEXP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_RPADC — TABLE TFPS2299_DMDEV_RPADC
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE2299_PA_ADC | String |  | CHAVE2299_PA_ADC |  |
| PERREF | String |  | PERREF |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| MATRICULA | String |  | MATRICULA |  |
| INDSIMPLES | Integer |  | INDSIMPLES |  |
| GRAUEXP | Integer |  | GRAUEXP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_TRPA — TABLE TFPS2299_DMDEV_TRPA
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CHAVE | String |  | CHAVE |  |
| CODCONV | String |  | CODCONV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_DMDEV_TRPADC — TABLE TFPS2299_DMDEV_TRPADC
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE2299_PA_ADC | String |  | CHAVE2299_PA_ADC |  |
| PERREF | String |  | PERREF |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| MATRICULA | String |  | MATRICULA |  |
| CHAVE | String |  | CHAVE |  |
| CODCONV | String |  | CODCONV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_PROCJUD — TABLE TFPS2299_PROCJUD
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| CHAVE | String |  | CHAVE |  |
| TPTRIB | Integer |  | TPTRIB |  |
| NRPROCJUD | String |  | NRPROCJUD |  |
| CODSUSP | String |  | CODSUSP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2299_REMOUTREMPRE — TABLE TFPS2299_REMOUTREMPRE
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2299 | String |  | CHAVE2299 |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODCATEG | Integer |  | CODCATEG |  |
| VLRREMUNOE | Float |  | VLRREMUNOE |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2300 — TABLE TFPS2300
Campos: 152

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTALTERACAO | Date |  | Data da Ocorrência |  |
| STATUS | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio |
| STATUSENVIO | String |  | Status envio eSocial |  |
| STATUSEVENTO | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio `S`=Pendente de envio - erro no envio |
| ACAO | String |  | Ação | `A`=Retificação `E`=Exclusão `I`=Inclusão |
| NRORECIBO | String |  | N° do Recibo |  |
| NMTRAB | String |  | Nome do trabalhador |  |
| CPFTRAB | String |  | CPF |  |
| DTNASCTONASCIMENTO | Date |  | Data de nascimento |  |
| CODCATEG | Integer |  | Categoria eSocial |  |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| RACACOR | Integer |  | Raça/Etnia | `1`=Branca `2`=Preta `3`=Parda `4`=Amarela `5`=Indígena_(+1)_ |
| ESTCIV | Integer |  | Estado Civil | `1`=Solteiro(a) `2`=Casado(a) `3`=Divorciado(a) `4`=Separado(a) `5`=Viúvo(a) |
| GRAUINSTR | String |  | Escolaridade | `1`=Analfabeto `10`=Pós-Graduação Completa `11`=Mestrado Completo `12`=Doutorado Completo `2`=Ate 5º Ano Incompleto_(+7)_ |
| PAISNASCTONASCIMENTO | Integer |  | Cód. Nacionalidade (Tabela 06 - Países) |  |
| PAISNACNASCIMENTO | Integer |  | Cód. País de Nascimento (Tabela 06 - Países) |  |
| TPLOGRADBRASIL | String |  | Tipo de Logradouro |  |
| DSCLOGRADBRASIL | String |  | Descrição do logradouro |  |
| NRLOGRADBRASIL | String |  | Número |  |
| COMPLEMENTOBRASIL | String |  | Complemento |  |
| UFBRASIL | String |  | UF |  |
| BAIRROBRASIL | String |  | Bairro |  |
| CEPBRASIL | String |  | CEP |  |
| CODMUNICBRASIL | Integer |  | Cód. do Município Brasil (Tabela do IBGE) |  |
| DEFFISICA | String |  | Deficiência física | `N`=Não `S`=Sim |
| DEFVISUAL | String |  | Deficiência visual | `N`=Não `S`=Sim |
| TMPRESID | String |  | Tempo de residência do Trabalhador Imigrante | `1`=1 - Prazo Indeterminado `2`=2 - Prazo Determinado |
| DEFAUDITIVA | String |  | Deficiência auditiva | `N`=Não `S`=Sim |
| CONDING | String |  | Condição de ingresso do trabalhador imigrante | `1`=1 - Refugiado `2`=2 - Solicitante de refúgio `3`=3 - Permanência no Brasil em razão de reunião familiar `4`=4 - Beneficiado pelo acordo entre países do Mercosul `5`=5- Dependente de agente diplomático e/ou consular com acordo de reciprocidade e atividade remunerada_(+2)_ |
| DEFMENTAL | String |  | Deficiência mental | `N`=Não `S`=Sim |
| DEFINTELECTUAL | String |  | Deficiência intelectual | `N`=Não `S`=Sim |
| REABREADAP | String |  | Reabilitado/Readaptado | `N`=Não `S`=Sim |
| FONEPRINC | String |  | Fone principal |  |
| EMAILPRINC | String |  | Email Principal |  |
| CADINI | String |  | Cadastramento inicial | `N`=Não `S`=Sim |
| MATRICULA | String |  | Matrícula |  |
| NRPROCTRAB | String |  | N° Processo Trabalhista |  |
| NATATIVIDADE | Integer |  | Natureza da Atividade | `1`=Trabalho urbano `2`=Trabalho rural |
| DESCRCARGO | String |  | Nome do Cargo |  |
| CBOCARGO | String |  | CBO do Cargo |  |
| DESCRFUNCAO | String |  | Nome da Função |  |
| CBOFUNCAO | String |  | CBO da função |  |
| DTOPCFGTS | Date |  | Data da opção FGTS |  |
| VRSALFX | Float |  | Salário Base |  |
| UNDSALFIXO | Integer |  | Unidade de Pagamento | `1`=Por Hora `2`=Por dia `3`=Por semana `4`=Por quinzena `5`=Por mês_(+2)_ |
| DSCSALVAR | String |  | Descrição do salário |  |
| NATESTAGIO | String |  | Natureza do estágio | `N`=Não Obrigatório `O`=Obrigatório |
| NIVESTAGIO | String |  | Nível do estágio | `1`=Fundamental `2`=Médio `3`=Formação Profissional `4`=Superior `8`=Especial_(+1)_ |
| AREAATUACAO | String |  | Área de atuação |  |
| NRAPOL | String |  | Número da apólice de seguro |  |
| DTPREVTERM | Date |  | Data prevista término do estágio |  |
| CNPJINSTENSINO | String |  | CNPJ Instituição de Ensino |  |
| NMRAZAOINSTENS | String |  | Razão Social |  |
| DSCLOGRADINSTENS | String |  | Endereço |  |
| NRLOGRADINSTENS | String |  | Número |  |
| BAIRROINSTENS | String |  | Bairro |  |
| CEPINSTENS | String |  | CEP |  |
| CODMUNICINSTENS | Integer |  | Cidade |  |
| UFINSTENS | String |  | UF |  |
| CNPJAGNTINTEG | String |  | CNPJ Agente de Integração |  |
| CPFSUPERVISOR | String |  | CPF Supervisor do estágio |  |
| CATEGORIGCED | Integer |  | Categoria Origem |  |
| CNPJCED | String |  | CNPJ Cedente |  |
| MATRICCED | String |  | Matrícula Origem |  |
| DTADMCED | Date |  | Data Admissão de Origem |  |
| TPREGTRABCED | Integer |  | Tipo de Regime Trabalhista |  |
| TPREGPREVCED | Integer |  | Tipo de Regime Previdenciário |  |
| DTINIAFAST | Date |  | Data início afastamento |  |
| CODMOTAFAST | String |  | Motivo de afastamento |  |
| DTTERM | Date |  | Data desligamento |  |
| CODEMP | Integer |  | Empresa |  |
| DTREF | DateTime |  | Período |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição Empregador |  |
| NRINSCEMPREGADOR | String |  | Número de inscrição empregador |  |
| NISTRAB | String |  | Número de inscrição do segurado - NIS |  |
| OBSERVACAO | String |  | Observação |  |
| EXCLMANUAL | String |  | Exclusão manual |  |
| NMSOC | String |  | Nome Social |  |
| CODMUNICNASCIMENTO | Integer |  | Código do Município do Nascimento |  |
| UFNASCIMENTO | String |  | UF do Nascimento |  |
| NMMAENASCIMENTO | String |  | Nome da Mãe |  |
| NMPAINASCIMENTO | String |  | Nome do Pai |  |
| NRCTPS | String |  | Número CTPS |  |
| SERIECTPS | String |  | Série CTPS |  |
| UFCTPS | String |  | UF CTPS |  |
| NRRIC | String |  | Número RIC |  |
| ORGAOEMISSORRIC | String |  | Órgão Emissor RIC |  |
| DTEXPEDRIC | DateTime |  | Data de Expedição Registro de Identidade Civil |  |
| NRRG | String |  | Número RG |  |
| ORGAOEMISSORRG | String |  | Órgão Emissor RG |  |
| DTEXPEDRG | DateTime |  | Data de Expedição RG |  |
| NRRNE | String |  | Número RNE |  |
| ORGAOEMISSORRNE | String |  | Órgão Emissor RNE |  |
| DTEXPEDRNE | DateTime |  | Data de Expedição RNE |  |
| NROC | String |  | Número do Registro de Órgão da Classe |  |
| ORGAOEMISSOROC | String |  | Órgão Emissor OC |  |
| DTEXPEDOC | DateTime |  | Data de Expedição Documento |  |
| DTVALIDOC | DateTime |  | Data de Validade Documento |  |
| NRREGCNH | String |  | Número CNH |  |
| DTEXPEDCNH | DateTime |  | Data de Expedição CNH |  |
| UFCNH | String |  | CNH Brasil |  |
| DTVALIDCNH | DateTime |  | Data de Validade CNH |  |
| DTPRIHAB | DateTime |  | Data Primeira Habilitação |  |
| CATEGORIACNH | String |  | Categoria da CNH |  |
| PAISRESID | String |  | País de Residência |  |
| DSCLOGRADEXTERIOR | String |  | Descrição do logradouro Exterior |  |
| NRLOGRADEXTERIOR | String |  | Número do logradouro Exterior |  |
| COMPLEMENTOEXTERIOR | String |  | Complemento Exterior |  |
| BAIRROEXTERIOR | String |  | Bairro Exterior |  |
| NMCIDEXTERIOR | String |  | Nome da Cidade Exterior |  |
| CODPOSTALEXTERIOR | String |  | Código Postal Exterior |  |
| DTCHEGADA | DateTime |  | Data de chegada no País |  |
| CLASSTRABESTRANG | Integer |  | Situação Estrangeira |  |
| CASADOBR | String |  | Casado com Brasileiro |  |
| FILHOSBR | String |  | Possui Filhos Brasileiros |  |
| FONEALTERNAT | String |  | Fone Alternativo |  |
| EMAILALTERNAT | String |  | Email Alternativo |  |
| DTINICIO | DateTime |  | Data de Início |  |
| CODCARGO | String |  | Cargo |  |
| CODFUNCAO | String |  | Função |  |
| OPCFGTS | Integer |  | Optante FGTS |  |
| CATEGORIGDIRSIND | Integer |  | Categoria de Origem Dirigente Sindical |  |
| CNPJORIGDIRSIND | String |  | CNPJ Dirigente Sindical |  |
| DTADMORIGDIRSIND | DateTime |  | Data de Admissão do Dirigente Sindical |  |
| MATRICORIGDIRSIND | String |  | Matrícula de Origem Dirigente Sindical |  |
| INFONUSCED | Integer |  | Ônus da Cessão/Requisição |  |
| VLRBOLSA | Float |  | Valor da Bolsa |  |
| NMRAZAOAGNTINTEG | String |  | Razão Social Agente de Integração |  |
| DSCLOGRADAGNTINTEG | String |  | Descrição do logradouro Agente Integrador |  |
| NRLOGRADAGNTINTEG | String |  | Número do logradouro agente de integração |  |
| BAIRROAGNTINTEG | String |  | Bairro Agente de Integração |  |
| CEPAGNTINTEG | String |  | CEP Agente de Integração |  |
| CODMUNICAGNTINTEG | Integer |  | Código do Município Agente de Integração |  |
| UFAGNTINTEG | String |  | UF Agente de Integração |  |
| NMSUPERV | String |  | Nome do Supervisor |  |
| NRORECIBO_ANT | String |  | Número do Recibo Anterior |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle de Alteração |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| DTREF_ANT | DateTime |  | Período Anterior |  |
| SEQUENCIA_ANT | Integer |  | Sequência Anterior |  |
| MODIFICOUCPF | String |  | Modificou CPF |  |
| CPFANT | String |  | CPF Anterior |  |
| DTALTCPF | DateTime |  | Data de Alteração do CPF |  |
| OBSALTCPF | String |  | Observação Alteração do CPF |  |
| TPREGPREVS2306 | String |  | Regime previdenciário |  |
| MONTALOCALTRAB | String |  | Local de Trabalho |  |
| TPINSCLOCALTRABGERAL | Integer |  | Tipo Inscrição Local de Trabalho |  |
| NRINSCLOCALTRABGERAL | String |  | Número Inscrição Local de Trabalho |  |
| DESCREVT | String |  | Descrição |  |

## TFPS2300_DEPENDENTE — TABLE TFPS2300_DEPENDENTE
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TPDEP | String |  | Tipo de Dependente | `1`=Cônjuge `10`=Menor pobre do qual detenha a guarda judicial `11`=A pessoa absolutamente incapaz, da qual seja tutor ou curador `12`=Ex-cônjuge `2`=Companheiro(a) com filho ou vivendo há mais de 5 anos ou em união estável_(+6)_ |
| NMDEP | String |  | Nome do Dependente |  |
| DTNASCTO | Date |  | Data de nascimento |  |
| CPFDEP | String |  | CPF Dependente |  |
| DEPIRRF | String |  | Dependente Constam no IRRF | `N`=Não `S`=Sim |
| DEPSF | String |  | Dependente Salário-Família | `N`=Não `S`=Sim |
| INCTRAB | String |  | Incapacidade Física/Mental | `N`=Não `S`=Sim |
| DESCRDPD | String |  | Descrição da Dependência |  |
| CODEMP | Integer |  | Empresa |  |
| DTREF | DateTime |  | Período |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CHAVEPAI | String |  | Chave Pai |  |
| CHAVE | String |  | Chave |  |
| TPAMB | String |  | Identificação do Ambiente |  |

## TFPS2306 — TABLE TFPS2306
Campos: 64

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTALTERACAO | Date |  | Data de alteração |  |
| STATUS | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio |
| STATUSENVIO | String |  | Status envio eSocial |  |
| STATUSEVENTO | String |  | Status eSocial | `F`=Finalizado `I`=Enviando para o e-Social `P`=Pendente de envio `S`=Pendente de envio - erro no envio |
| ACAO | String |  | Ação | `A`=Retificação `E`=Exclusão `I`=Inclusão |
| NRORECIBO | String |  | Número do Recibo |  |
| CPFTRAB | String |  | CPF |  |
| CODCATEG | Integer |  | Categoria eSocial |  |
| NATATIVIDADE | Integer |  | Natureza da Atividade | `1`=Trabalho urbano `2`=Trabalho rural |
| DESCRCARGO | String |  | Cargo |  |
| CBOCARGO | String |  | CBO Cargo |  |
| DESCRFUNCAO | String |  | Função |  |
| CBOFUNCAO | String |  | CBO Função |  |
| VRSALFX | Float |  | Salário base |  |
| UNDSALFIXO | Integer |  | Unidade de Pagamento | `1`=Por Hora `2`=Por dia `3`=Por semana `4`=Por quinzena `5`=Por mês_(+2)_ |
| DSCSALVAR | String |  | Descrição do salário |  |
| NATESTAGIO | String |  | Natureza do estágio | `N`=Não Obrigatório `O`=Obrigatório |
| NIVESTAGIO | String |  | Nível do estágio | `1`=Fundamental `2`=Médio `3`=Formação Profissional `4`=Superior `8`=Especial_(+1)_ |
| AREAATUACAO | String |  | Área de atuação |  |
| NRAPOL | String |  | Número da apólice de seguro |  |
| DTPREVTERM | DateTime |  | Data prevista término do estágio |  |
| CNPJINSTENSINO | String |  | CNPJ Instituição de Ensino |  |
| NMRAZAOINSTENS | String |  | Razão Social |  |
| DSCLOGRADINSTENS | String |  | Endereço |  |
| NRLOGRADINSTENS | String |  | Número |  |
| BAIRROINSTENS | String |  | Bairro |  |
| CODMUNICINSTENS | Integer |  | Cidade |  |
| UFINSTENS | String |  | UF |  |
| CNPJAGNTINTEG | String |  | CNPJ Agente de Integração |  |
| CPFSUPERVISOR | String |  | CPF Supervisor do estágio |  |
| TPREGPREV | Integer |  | Regime previdenciário |  |
| CODEMP | Integer |  | Empresa |  |
| DTREF | DateTime |  | Período |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição Empregador |  |
| NRINSCEMPREGADOR | String |  | Número de inscrição empregador |  |
| NISTRAB | String |  | Número de inscrição do segurado - NIS |  |
| DTEF | DateTime |  | Data dos efeitos remuneratórios da alteração contratual |  |
| EXCLMANUAL | String |  | Exclusão manual |  |
| CODCARGO | String |  | Cargo |  |
| CODFUNCAO | String |  | Função |  |
| VLRBOLSA | Float |  | Valor da Bolsa |  |
| CEPINSTENS | String |  | CEP Instituição de Ensino |  |
| NMRAZAOAGNTINTEG | String |  | Razão Social Agente de Integração |  |
| DSCLOGRADAGNTINTEG | String |  | Descrição do logradouro Agente Integrador |  |
| NRLOGRADAGNTINTEG | String |  | Número do logradouro agente de integração |  |
| BAIRROAGNTINTEG | String |  | Bairro Agente de Integração |  |
| CEPAGNTINTEG | String |  | CEP Agente de Integração |  |
| CODMUNICAGNTINTEG | Integer |  | Código do Município Agente de Integração |  |
| UFAGNTINTEG | String |  | UF Agente de Integração |  |
| NMSUPERV | String |  | Nome do Supervisor |  |
| NRORECIBO_ANT | String |  | Número do Recibo Anterior |  |
| CHAVE | String |  | Chave |  |
| CONTROLE | String |  | Controle de Alteração |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| DTREF_ANT | DateTime |  | Período Anterior |  |
| SEQUENCIA_ANT | Integer |  | Sequência Anterior |  |
| INDRETIF | Integer |  | Indicativo de Retificação |  |
| MATRICULA | String |  | Matrícula |  |
| MONTALOCALTRAB | String |  | Local de Trabalho |  |
| TPINSCLOCALTRABGERAL | Integer |  | Tipo Inscrição Local de Trabalho |  |
| NRINSCLOCALTRABGERAL | String |  | Número Inscrição Local de Trabalho |  |
| DESCREVT | String |  | Descrição |  |

## TFPS2399 — TABLE TFPS2399
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NISTRAB | String |  | NISTRAB |  |
| CODCATEG | Integer |  | CODCATEG |  |
| DTTERMINO | DateTime |  | DTTERMINO |  |
| MTVDESLIG | String |  | MTVDESLIG |  |
| DTFIMQUAR | DateTime |  | DTFIMQUAR |  |
| INDMV | Integer |  | INDMV |  |
| STATUS | String |  | STATUS |  |
| NRORECIBO | String |  | NRORECIBO |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| ACAO | String |  | ACAO |  |
| CHAVE | String |  | CHAVE |  |
| CONTROLE | String |  | CONTROLE |  |
| TPAMB | String |  | TPAMB |  |
| DATACHANGE | C |  | DATACHANGE |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| NOVOCPF | String |  | NOVOCPF |  |
| PENSALIM | String |  | PENSALIM |  |
| PERCALIM | Float |  | PERCALIM |  |
| VRALIM | Float |  | VRALIM |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2399_DMDEV — TABLE TFPS2399_DMDEV
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2399 | String |  | CHAVE2399 |  |
| CHAVE | String |  | CHAVE |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2399_DMDEV_DRPA — TABLE TFPS2399_DMDEV_DRPA
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2399 | String |  | CHAVE2399 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| CNPJOPER | String |  | CNPJOPER |  |
| REGANS | String |  | REGANS |  |
| VRPGTIT | Float |  | VRPGTIT |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2399_DMDEV_EL — TABLE TFPS2399_DMDEV_EL
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2399 | String |  | CHAVE2399 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| GRAUEXP | Integer |  | GRAUEXP |  |
| INDSIMPLES | Integer |  | INDSIMPLES |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2399_DMDEV_IRPA — TABLE TFPS2399_DMDEV_IRPA
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2399 | String |  | CHAVE2399 |  |
| IDEDMDEV | String |  | IDEDMDEV |  |
| CODLOTACAO | String |  | CODLOTACAO |  |
| CHAVE | String |  | CHAVE |  |
| CODRUBR | String |  | CODRUBR |  |
| IDETABRUBR | String |  | IDETABRUBR |  |
| QTDRUBR | Float |  | QTDRUBR |  |
| FATORRUBR | Float |  | FATORRUBR |  |
| VRUNIT | Float |  | VRUNIT |  |
| VRRUBR | Float |  | VRRUBR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2399_PROCJUD — TABLE TFPS2399_PROCJUD
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2399 | String |  | CHAVE2399 |  |
| CHAVE | String |  | CHAVE |  |
| TPTRIB | Integer |  | TPTRIB |  |
| NRPROCJUD | String |  | NRPROCJUD |  |
| CODSUSP | String |  | CODSUSP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2399_REMOUTREMPRE — TABLE TFPS2399_REMOUTREMPRE
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE2399 | String |  | CHAVE2399 |  |
| CHAVE | String |  | CHAVE |  |
| TPINSC | Integer |  | TPINSC |  |
| NRINSC | String |  | NRINSC |  |
| CODCATEG | Integer |  | CODCATEG |  |
| VLRREMUNOE | Float |  | VLRREMUNOE |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2500 — TABLE TFPS2500
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| STATUS | String |  | STATUS |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| INDRETIF | Integer |  | INDRETIF |  |
| NRORECIBO | String |  | NRORECIBO |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| TPINSCCONTRIBUINTE | Integer |  | TPINSCCONTRIBUINTE |  |
| NRINSCCONTRIBUINTE | String |  | NRINSCCONTRIBUINTE |  |
| ORIGEM | Integer |  | ORIGEM |  |
| NRPROCTRAB | String |  | NRPROCTRAB |  |
| OBSPROCTRAB | String |  | OBSPROCTRAB |  |
| DTSENT | DateTime |  | DTSENT |  |
| UFVARA | String |  | UFVARA |  |
| CODMUNIC | Integer |  | CODMUNIC |  |
| IDVARA | Integer |  | IDVARA |  |
| DTCCP | DateTime |  | DTCCP |  |
| TPCCP | Integer |  | TPCCP |  |
| CNPJCCP | String |  | CNPJCCP |  |
| CPFTRAB | String |  | CPFTRAB |  |
| NMTRAB | String |  | NMTRAB |  |
| DTNASCTO | DateTime |  | DTNASCTO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2500_BASECALCULO — TABLE TFPS2500_BASECALCULO
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2500 | String |  | CHAVE2500 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVEINFOCONTRATO | String |  | CHAVEINFOCONTRATO |  |
| CHAVE | String |  | CHAVE |  |
| PERREF | String |  | PERREF |  |
| VRBCCPMENSAL | Float |  | VRBCCPMENSAL |  |
| VRBCCP13 | Float |  | VRBCCP13 |  |
| VRBCFGTS | Float |  | VRBCFGTS |  |
| VRBCFGTS13 | Float |  | VRBCFGTS13 |  |
| GRAUEXP | Integer |  | GRAUEXP |  |
| VRBCFGTSGUIA | Float |  | VRBCFGTSGUIA |  |
| VRBCFGTS13GUIA | Float |  | VRBCFGTS13GUIA |  |
| PAGDIRETO | String |  | PAGDIRETO |  |
| CODCATEG | Integer |  | CODCATEG |  |
| VRBCCPREV | Float |  | VRBCCPREV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2500_DEPENDENTE — TABLE TFPS2500_DEPENDENTE
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2500 | String |  | CHAVE2500 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| CPFDEP | String |  | CPFDEP |  |
| TPDEP | String |  | TPDEP |  |
| DESCDEP | String |  | DESCDEP |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2500_INFOCONTRATO — TABLE TFPS2500_INFOCONTRATO
Campos: 48

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2500 | String |  | CHAVE2500 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| TPCONTR | Integer |  | TPCONTR |  |
| INDCONTR | String |  | INDCONTR |  |
| DTADMORIG | DateTime |  | DTADMORIG |  |
| INDREINT | String |  | INDREINT |  |
| INDCATEG | String |  | INDCATEG |  |
| INDNATATIV | String |  | INDNATATIV |  |
| INDMOTDESLIG | String |  | INDMOTDESLIG |  |
| INDUNIC | String |  | INDUNIC |  |
| MATRICULA | String |  | MATRICULA |  |
| CODCATEG | Integer |  | CODCATEG |  |
| DTINICIO | DateTime |  | DTINICIO |  |
| CODCBOCOMPL | String |  | CODCBOCOMPL |  |
| NATATIVIDADECOMPL | Integer |  | NATATIVIDADECOMPL |  |
| TPREGTRABVINC | Integer |  | TPREGTRABVINC |  |
| TPREGPREVVINC | Integer |  | TPREGPREVVINC |  |
| DTADMVINC | DateTime |  | DTADMVINC |  |
| TMPPARCVINC | Integer |  | TMPPARCVINC |  |
| TPCONTRDURACAO | Integer |  | TPCONTRDURACAO |  |
| DTTERMDURACAO | DateTime |  | DTTERMDURACAO |  |
| CLAUASSECDURACAO | String |  | CLAUASSECDURACAO |  |
| OBJDETDURACAO | String |  | OBJDETDURACAO |  |
| TPINSCSUCESSAO | Integer |  | TPINSCSUCESSAO |  |
| NRINSCSUCESSAO | String |  | NRINSCSUCESSAO |  |
| MATRICANTSUCESSAO | String |  | MATRICANTSUCESSAO |  |
| DTTRANSFSUCESSAO | DateTime |  | DTTRANSFSUCESSAO |  |
| DTDESLIG | DateTime |  | DTDESLIG |  |
| MTVDESLIG | String |  | MTVDESLIG |  |
| DTPROJFIMAPI | DateTime |  | DTPROJFIMAPI |  |
| DTTERMTSVE | DateTime |  | DTTERMTSVE |  |
| MTVDESLIGTSVE | String |  | MTVDESLIGTSVE |  |
| TPINSCESTAB | Integer |  | TPINSCESTAB |  |
| NRINSCESTAB | String |  | NRINSCESTAB |  |
| COMPINI | String |  | COMPINI |  |
| COMPFIM | String |  | COMPFIM |  |
| REPERCPROC | Integer |  | REPERCPROC |  |
| VRRENUM | Float |  | VRRENUM |  |
| VRAPI | Float |  | VRAPI |  |
| VR13API | Float |  | VR13API |  |
| VRINDEN | Float |  | VRINDEN |  |
| VRBASEINDENFGTS | Float |  | VRBASEINDENFGTS |  |
| PAGDIRETORESC | String |  | PAGDIRETORESC |  |
| OBSERVACAOVINC | String |  | OBSERVACAOVINC |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2500_MUDCATEGATIV — TABLE TFPS2500_MUDCATEGATIV
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2500 | String |  | CHAVE2500 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVEINFOCONTRATO | String |  | CHAVEINFOCONTRATO |  |
| CHAVE | String |  | CHAVE |  |
| CODCATEG | Integer |  | CODCATEG |  |
| NATATIVIDADE | Integer |  | NATATIVIDADE |  |
| DTMUDCATEGATIV | DateTime |  | DTMUDCATEGATIV |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2500_REMUNERACAO — TABLE TFPS2500_REMUNERACAO
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2500 | String |  | CHAVE2500 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVEINFOCONTRATO | String |  | CHAVEINFOCONTRATO |  |
| CHAVE | String |  | CHAVE |  |
| DTREMUN | DateTime |  | DTREMUN |  |
| VRSALFX | Float |  | VRSALFX |  |
| UNDSALFIXO | Integer |  | UNDSALFIXO |  |
| DSCSALVAR | String |  | DSCSALVAR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2500_UNICCONTR — TABLE TFPS2500_UNICCONTR
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2500 | String |  | CHAVE2500 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVEINFOCONTRATO | String |  | CHAVEINFOCONTRATO |  |
| CHAVE | String |  | CHAVE |  |
| MATUNIC | String |  | MATUNIC |  |
| CODCATEG | Integer |  | CODCATEG |  |
| DTINICIO | DateTime |  | DTINICIO |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2501 — TABLE TFPS2501
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE | String |  | CHAVE |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NRORECIBO_ANT | String |  | NRORECIBO_ANT |  |
| SEQUENCIA_ANT | Integer |  | SEQUENCIA_ANT |  |
| DTREF_ANT | DateTime |  | DTREF_ANT |  |
| STATUS | String |  | STATUS |  |
| ACAO | String |  | ACAO |  |
| CONTROLE | String |  | CONTROLE |  |
| DATACHANGE | C |  | DATACHANGE |  |
| INDRETIF | Integer |  | INDRETIF |  |
| NRORECIBO | String |  | NRORECIBO |  |
| TPINSCEMPREGADOR | Integer |  | TPINSCEMPREGADOR |  |
| NRINSCEMPREGADOR | String |  | NRINSCEMPREGADOR |  |
| NRPROCTRAB | String |  | NRPROCTRAB |  |
| PERAPURPGTO | String |  | PERAPURPGTO |  |
| OBS | String |  | OBS |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2501_CALCTRIB — TABLE TFPS2501_CALCTRIB
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2501 | String |  | CHAVE2501 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVEIDETRAB | String |  | CHAVEIDETRAB |  |
| CHAVE | String |  | CHAVE |  |
| PERREF | String |  | PERREF |  |
| VRBCCPMENSAL | Float |  | VRBCCPMENSAL |  |
| VRBCCP13 | Float |  | VRBCCP13 |  |
| VRRENDIRRF | Float |  | VRRENDIRRF |  |
| VRRENDIRRF13 | Float |  | VRRENDIRRF13 |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2501_IDETRAB — TABLE TFPS2501_IDETRAB
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2501 | String |  | CHAVE2501 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| CPFTRAB | String |  | CPFTRAB |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2501_INFOCRCONTRIB — TABLE TFPS2501_INFOCRCONTRIB
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2501 | String |  | CHAVE2501 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVEIDETRAB | String |  | CHAVEIDETRAB |  |
| CHAVECALCTRIB | String |  | CHAVECALCTRIB |  |
| CHAVE | String |  | CHAVE |  |
| TPCR | Integer |  | TPCR |  |
| VRCR | Float |  | VRCR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2501_INFOCRIRRF — TABLE TFPS2501_INFOCRIRRF
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | DateTime |  | DTREF |  |
| TPAMB | String |  | TPAMB |  |
| CHAVE2501 | String |  | CHAVE2501 |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVEIDETRAB | String |  | CHAVEIDETRAB |  |
| CHAVE | String |  | CHAVE |  |
| TPCR | Integer |  | TPCR |  |
| VRCR | Float |  | VRCR |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPS2555 — TABLE TFPS2555
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Período |  |
| SEQUENCIA | Integer |  | Sequência |  |
| STATUS | String |  | Status eSocial |  |
| TPAMB | String |  | Identificação do Ambiente |  |
| CHAVE | String |  | Chave |  |
| ACAO | String |  | Ação |  |
| CONTROLE | String |  | Controle de Alteração |  |
| DATACHANGE | C |  | Mudança de Dados |  |
| NRORECIBO | String |  | Número do Recibo |  |
| NRORECIBO_ANT | String |  | Número do Recibo Anterior |  |
| DTREF_ANT | Date |  | Período Anterior |  |
| SEQUENCIA_ANT | Integer |  | Sequência Anterior |  |
| TPINSCEMPREGADOR | Integer |  | Tipo de Inscrição Empregador |  |
| NRINSCEMPREGADOR | String |  | Número de inscrição empregador |  |
| NRPROCTRAB | String |  | Nº do processo trabalhista |  |
| PERAPURPGTO | String |  | Período de Apuração do Pagamento |  |
| CODEMP | Integer |  | Empresa |  |

## TFPSAL — FP Saldos de Provisão
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTACTB | Integer |  | Conta Contábil |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CREDITO | Float |  | Valor de Crédito |  |
| DEBITO | Float |  | Valor de Débito |  |
| REFERENCIA | DateTime |  | Referência |  |
| SALDO | Float |  | Saldo |  |
| CODCENCUS | Integer |  | Centro de Custo |  |
| CODPROJ | Integer |  | Projeto |  |
| NUMLOTE | Integer |  | Número do Lote |  |
| TIPPROVISAO | String |  | Tipo da Provisão |  |

## TFPSFE — Solicitacao de férias
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| NUSOLICIT | Integer |  | Solicitação |  |
| DHSOLICIT | Date |  | Data da solicitação |  |
| STATUS | String |  | Situação | `N`=Não Aprovado `A`=Aprovado `P`=Pendente |
| PREVINICIO | Date |  | Início da férias |  |
| DIASSOLICITADOS | Integer |  | Qtd. dias |  |
| ADIANTADECTERC | String |  | Adiantar 13º | `S`=Sim `N`=Não |
| ABONOPECUNIARIO | String |  | Vender 10 dias | `S`=Sim `N`=Não |
| DTINIAQUI | Date |  | Início per. aquisitivo |  |
| OBSERVACAO | String |  | Observação |  |
| SEQFER | Integer |  | Seq. Programação |  |
| DIASABONOPEC | Integer |  | Dias de abono |  |
| ID | Integer |  | ID |  |
| CODEMP | Integer |  | Empresa |  |

## TFPSGA — Situação Geradora
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRSITUACAOGERADORA | String |  | Descrição |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODSITUACAOGERADORA | Integer |  | Código |  |

## TFPSIN — Sindicatos
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMESIND | String |  | Nome |  |
| CODPREF | Integer |  | Regra de Cálculo |  |
| CGC | String |  | CNPJ |  |
| CODSINDICAL | String |  | Cód. Sindical |  |
| CODPARC | Integer |  | Parceiro |  |
| EVENTOCONTASSOC | String |  | Evento Contrib. Associativa |  |
| EVENTOCONTSIND | String |  | Evento Contrib. Sindical |  |
| EVENTOCONTASSIS | String |  | Evento Contrib. Assistencial |  |
| EVENTOCONTCONF | String |  | Evento Contrib. Confederativa |  |
| PONTOALTERNATIVO | String |  | Utiliza Registro Eletrônico de Ponto Alternativo | `S`=Sim `N`=Não |
| REGRAADNOTURNO | String |  | Regra Ad. Noturno | `S`=Sim `N`=Não |
| TIPHORANOTURNA | String |  | Tipo Hor. Noturno | `U`=Urbano `P`=Rural(Pecuária) `L`=Rural(Lavoura) |
| DHALTER | DateTime |  | Data de alteração |  |
| CODSIND | Integer |  | Código do sindicato |  |

## TFPSIT — Situação Estatutária
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSITESTAT | Integer |  | Código da situação |  |
| DESCRSIT | String |  | Descrição |  |
| PARCELA1_13SAL | Integer |  | 1 Parcela 13 salario |  |
| PARCELA2_13SAL | Integer |  | 2 Parcela 13 salario |  |
| PARCUNICA13SAL | Integer |  | Parcela única 13 salario |  |

## TFPSUB — Tabela de substituição de funcionário
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa substituta |  |
| CODEMPSUB | Integer |  | Empresa substituída |  |
| CODFUNC | Integer |  | Funcionário substituto |  |
| CODFUNCSUB | Integer |  | Funcionário substituído |  |
| CONTRACHQ | String |  | Apresentou contra cheque | `N`=Não `S`=Sim |
| DTFIM | DateTime |  | Data Final da substituição |  |
| DTINICIO | DateTime |  | Data inicial da substituição |  |
| REFERENCIA | DateTime |  | Referência |  |

## TFPSUSP — TABLE TFPSUSP
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSUSP | String |  | Código Indicativo de Suspensão |  |
| INDSUSP | String |  | Indicativo de suspensão de exigibilidade | `12`=Acórdão do STF em recurso extraordinário favorável ao contribuinte `13`=Sentença 1ª instância não transitada em julgado com efeito suspensivo `14`=Contestação administrativa FAP `90`=Decisão definitiva a favor do contribuinte `92`=Sem suspensão da exigibilidade_(+9)_ |
| DTDESCISAO | Date |  | Data de decisão |  |
| INDDEPOSITO | String |  | Depósito de Montante Integral | `S`=Sim `N`=Não |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| NUPROCESSO | Integer |  | NUPROCESSO |  |

## TFPTAT — Testemunhas CAT
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NOMETESTEMUNHA | String |  | Nome da Testemunha |  |
| CODEND | Integer |  | Endereço |  |
| NUMEND | String |  | Número Endereço |  |
| CODBAI | Integer |  | Bairro |  |
| CODCID | Integer |  | Cidade |  |
| CEP | String |  | CEP |  |
| TELEFONE | String |  | Telefone |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| NUCAT | Integer |  | NUCAT |  |

## TFPTBE — Tipo de Benefício
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPO | Integer |  | Tipo | `4`=Plano de Saúde `3`=Vale Combustível `2`=Vale Transporte `1`=Vale Refeição `0`=Vale Alimentação_(+1)_ |
| CODTBE | Integer |  | Código |  |

## TFPTERC — TABLE TFPTERC
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTERC | String |  | Código de Terceiro | `0001`=0001 - Salário- Educação `0002`=0002 - INCRA `0004`=0004 - SENAI `0008`=0008 - SESI `0016`=0016 - SENAC_(+8)_ |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| PERCENTUAL | Float |  | Percentual |  |
| NUPROCESSO | Integer |  | NUPROCESSO |  |

## TFPTLT — TABLE TFPTLT
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRRESUMIDA | String |  | DESCRRESUMIDA |  |
| DESCRLOTACAO | String |  | Descrição Tipo de Lotação |  |
| USADO | String |  | USADO |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODLOTACAO | Integer |  | Cód. Lotação |  |

## TFPTOM — Tomador
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | CODFUNC |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| DTINICIO | DateTime |  | DTINICIO |  |
| DTFIM | DateTime |  | DTFIM |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODEMP | Integer |  | CODEMP |  |

## TFPTPA — Tipo de Acidente de Trabalho
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTIPACIDENTE | String |  | Descrição |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| TIPACIDENTE | String |  | TIPACIDENTE |  |

## TFPTPR — Tipo de Rescisão
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTIPRESC | String |  | Descrição |  |
| CODAFASTRAIS | String |  | Cód.Afastamento da RAIS |  |
| CODAFASTFGTS | String |  | Cód.Afastamento FGTS |  |
| CODAFASTCAGED | String |  | Cód.Causa do Afastamento |  |
| CODSAQUEFGTS | Integer |  | Cód.Saque |  |
| GERAPREVISAO | String |  | Permite gerar previsão | `S`=Sim `N`=Não |
| CODMOTDESLIGESOCIAL | String |  | Motivo desligamento E-Social |  |
| CODTPR | Integer |  | Cód.Tipo Rescisão |  |

## TFPTRC — TABLE TFPTRC
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTREICAP | String |  | DESCRTREICAP |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| ATIVO | String |  | Ativo |  |
| CODTREICAP | Integer |  | CODTREICAP |  |

## TFPTREI — TABLE TFPTREI
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTTREIN | Date |  | Data de início do treinamento |  |
| CODTREICAP | Integer |  | Código do Treinamento/Capacitação no eSocial |  |
| DURTREICAP | Float |  | Duração em horas |  |
| MODTREICAP | Integer |  | Modalidade | `3`=3 - Mista `2`=2 - Educação à Distância (EAD) `1`=1 - Presencial |
| TPTREICAP | Integer |  | Tipo de treinamento | `5`=5 - Outros `4`=4 - Eventual `3`=3 - Reciclagem `2`=2 - Periódico `1`=1 - Inicial |
| OBSERVACAO | String |  | Observação |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| NROUNICO | Integer |  | Número único do treinamento |  |

## TFPTTB — Tipo de tabelas
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTAB | String |  | Descrição da tabela |  |
| CATEGTAB | String |  | Categoria da tabela | `P`=Privada `U`=Pública |
| CODEVEINSS | Integer |  | Código do evento de INSS |  |
| CODEVEDEBADIAN | Integer |  | Código do evento de adiantamento |  |
| REGFISCAL | Integer |  | Região fiscal |  |
| DTALTER | DateTime |  | Data de alteração |  |
| PERCINSS | Float |  | Percentual de INSS |  |
| TIPOTAB | String |  | Tipo da tabela |  |

## TFPVAL — Tabela de Vale Transporte
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | Funcionário |  |
| TIPO | String |  | Tipo | `T`=Transporte `A`=Alimentação |
| REFERENCIA | Date |  | Referência |  |
| CODLINHA | Integer |  | Descrição |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| PASSESDIA | Integer |  | Vales por dia |  |
| QTDDIAS | Float |  | Quantidade de dias |  |
| VALOR | Float |  | Valor da Tarifa |  |
| MANTEMPROXIMAREF | String |  | Mantém Próxima Referência | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TFPVCA — Variável de Cálculo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODFUNC | Integer |  | Cód.Funcionário |  |
| TIPFOLHA | String |  | Tipo de Folha |  |
| VARIAVEIS | String |  | Variáveis |  |
| REFERENCIA | DateTime |  | Referência |  |

## TFPVGR — Variação de Gratificação
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATOADMIN | String |  | Ato Administrativo |  |
| CODGRAT | Integer |  | Gratificação |  |
| COMPLEMENTO | Float |  | Complemento |  |
| DTMOV | DateTime |  | Data do movimento |  |
| REDUCAO | Float |  | Redução |  |
| REDUCAO2 | Float |  | Redução 2 |  |
| TIPREG | String |  | Tipo de registro | `G`=Gratificação `N`=Nível de Referência `D`=Décimos |
| VLRGRAT | Float |  | Valor da Gratificação |  |
| VLROPCIONAL | Float |  | Valor Opcional |  |

## TFPVPJ — TABLE TFPVPJ
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | CODEMP |  |
| CODDEP | Integer |  | CODDEP |  |
| NOME | String |  | NOME |  |
| CODUSU | Integer |  | Código Usuário |  |
| CPF | String |  | CPF |  |
| CNPJ | String |  | CNPJ |  |
| SEXO | String |  | Sexo | `M`=Masculino `F`=Feminino |
| EMAIL | String |  | EMAIL |  |
| TELEFONE | String |  | TELEFONE |  |
| IMAGEM | Boolean |  | IMAGEM |  |
| DTNASC | DateTime |  | DTNASC |  |
| DTINICIO | DateTime |  | DTINICIO |  |
| DTFIM | DateTime |  | DTFIM |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| MODIFPOR | Integer |  | MODIFPOR |  |
| DHALTER | DateTime |  | DHALTER |  |
| PERTENCEDP | String |  | Pertence ao DP/RH | `N`=Não `S`=Sim |
| CODVPJ | Integer |  | CODVPJ |  |

## TFPVPS — TABLE TFPVPS
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFUNC | Integer |  | CODFUNC |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODCONVENIO | Integer |  | Cód. Convênio |  |
| REFERENCIA | Date |  | Referência |  |
| VALOR | Float |  | Valor do Plano |  |
| DIGITADO | String |  | DIGITADO |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| VALORPROVENTO | Float |  | Valor Provento |  |
| TIPFOLHA | String |  | Tipo de Folha | `R`=Rescisão `N`=Mensal `F`=Férias `D`=Dec. Terceiro `2`=Férias 2_(+1)_ |
| CODEMP | Integer |  | CODEMP |  |