# TSI — Sistema e Configurações

> Gerado do dicionário oficial TDD Sankhya. 200 tabelas.


## TSI001 — Autorização de Api
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUAUT | Integer |  | Nu.Aut |  |
| CODUSU | Integer |  | Usuário |  |
| PROVEDOR | String |  | Provedor |  |
| SERVICO | String |  | Serviço |  |
| ATRIBUTO | String |  | Atributo |  |
| TIPOATRIBUTO | String |  | Tipo Atributo | `E`=Entidade `N`=Número `S`=Sem Atributo `T`=Texto |
| CODUSUALTER | Integer |  | Usuário de alteração |  |
| TOTALACESSOS | Integer |  | Quantidade de Serviços |  |
| DHALTER | DateTime |  | Dh. Alteração |  |
| METODO | String |  | Método |  |

## TSIAAG — Ação agendada
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| NOME | String |  | Nome |  |
| DESCRICAO | String |  | Descrição |  |
| TIPOACAO | String |  | Tipo de ação | `P`=Proc. Banco de dados `J`=Java |
| CODMODULO | Integer |  | Cód. módulo |  |
| ACAO | String |  | Ação |  |
| CODUSULOGIN | Integer |  | Usuário Logado |  |
| FONTEDADOS | String |  | Fonte de dados |  |
| AUTOTRAN | String |  | Transação automática | `N`=Não `S`=Sim |
| TIPOGATILHO | String |  | Tipo de gatilho | `I`=Intervalo de tempo `C`=Expressão CRON |
| EXPGATILHO | String |  | Expressão de gatilho |  |
| NUAAG | Integer |  | Nro. único |  |

## TSIACD — TABLE TSIACD
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CODGRUPO | Integer |  | Cód. Grupo |  |
| NUDSB | Integer |  | NUDSB |  |
| CONS | String |  | Consultar | `S`=Sim `N`=Não |

## TSIACE — Sugestao Acesso Cartao EVO
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cod. Usuário |  |
| LIBERADO | String |  | Liberado | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Dt. Alteração |  |
| ALTERADOPELOUSUARIO | String |  | Acesso alterador pelo usuário | `S`=Sim `N`=Não |
| RESOURCEID | String |  | ResourceID |  |

## TSIACI — Controle de Acesso dos Relatórios
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPO | Integer |  | Cód.Grupo de Usuário |  |
| CODREL | Integer |  | Cód.Relatório |  |
| CONS | String |  | Permite Consulta ? |  |
| ALTERA | String |  | Permite Alteração? |  |
| FILTRO | String |  | Permite Alterar Filtros? |  |
| RESUMO | String |  | Permite Alterar Resumo? |  |
| SEGURANCA | String |  | Permite Outros Usuários a Alterar |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSIACIBK — Backup Controle de Acesso dos Relatórios
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODGRUPO | Integer |  | CODGRUPO |  |
| CODREL | Integer |  | CODREL |  |
| CONS | String |  | CONS |  |
| ALTERA | String |  | ALTERA |  |
| FILTRO | String |  | FILTRO |  |
| RESUMO | String |  | RESUMO |  |
| SEGURANCA | String |  | SEGURANCA |  |
| NUNICO | Integer |  | NUNICO |  |

## TSIACM — Acesso Menu
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQACESSO | Integer |  | Seq. Acesso |  |
| DHACESSO | DateTime |  | Dh. Acesso |  |
| RESOURCEID | String |  | Id da Tela |  |
| CAMINHO | String |  | Caminho do Menu |  |
| DESCRMENU | String |  | Menu |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSIACR — Acesso Remoto
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| FINALIAUTORIZACAO | String |  | Descrição |  |
| NUMOSACR | String |  | Núm. OS/Ticket |  |
| DATAHORALIMITE | DateTime |  | Limite da sessão |  |
| USUARIO | String |  | Usuário do Banco de Dados |  |
| SENHA | String |  | Senha do Banco de Dados |  |
| USUARIOOM | Integer |  | Usuário do Sankhya OM |  |
| SENHAOM | String |  | Senha do Sankhya OM |  |
| OBSERVACAO | String |  | Observação |  |
| TERMODECIENCIA | String |  | Termo de Ciência | `S`=Sim `N`=Não |
| REVOGADO | String |  | Revogar Consentimento | `S`=Sim `N`=Não |
| USUARIOQUEAUTORIZOU | String |  | Usuário que autorizou |  |
| USUARIOAUTORIZOU | Integer |  | Autorizado por |  |
| DATAAUTORIZACAO | DateTime |  | Sessão aberta em |  |
| DATADEEXPIRACAO | DateTime |  | Sessão encerrada em |  |
| IDSAS | String |  | idSas |  |
| USERSAS | String |  | userSas |  |
| URLJDBC | String |  | urlJdbc |  |
| HTTPPORT | String |  | httpPort |  |
| HASH | String |  | Chave de Acesso |  |
| TKNHASHID | String |  | Tkn Hash Id |  |
| VERSAO | Integer |  | Versão |  |
| CODACR | Integer |  | Cód da Sessão |  |

## TSIACTLPD — Log do Aceite nas Telas com Grande Vazamento de Dados.
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| RESOURCEID | String |  | Resource Id da tela |  |
| DHACEITE | Date |  | DataHora Registro |  |
| ID | Integer |  | Codigo Registro |  |

## TSIAGE — Agências Bancárias
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBCO | Integer |  | Banco |  |
| NOMEAGE | String |  | Nome da Agência |  |
| NOMEGER | String |  | Nome do Gerente |  |
| TELEFONE | String |  | Telefone |  |
| FAX | String |  | Fax |  |
| EMAIL | String |  | Email |  |
| CODEND | Integer |  | Endereço |  |
| NUMEND | String |  | Número |  |
| COMPLEMENTO | String |  | Complemento |  |
| CEP | String |  | CEP |  |
| CODBAI | Integer |  | Bairro |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CODAGE | String |  | Agência |  |

## TSIALT — Log Alterações
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHACAO | DateTime |  | Data e hora ação |  |
| CHAVE | String |  | Chave |  |
| CAMPO | String |  | Campo |  |
| CONTEUDO | String |  | Conteúdo |  |
| ALTDESCNMOVMES | String |  | Alteração do produto já foi gerada no EFD Fiscal? | `N`=Não `S`=Sim |
| NOMETAB | String |  | Nome tabela |  |

## TSIANON — Anonimização
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCANON | String |  | Descrição do tipo de anonimização |  |
| CODUSUCRIAC | Integer |  | Código usuário criação |  |
| DTCRIAC | DateTime |  | Data criação |  |
| CODUSUALTER | Integer |  | Código usuário alteração |  |
| DTALTER | DateTime |  | Data alteração |  |
| CODANON | Integer |  | Código da anonimização |  |

## TSIANX — Anexo Sistema
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEINSTANCIA | String |  | Instância |  |
| CHAVEARQUIVO | String |  | Chave arquivo |  |
| NOMEARQUIVO | String |  | Arquivo |  |
| DESCRICAO | String |  | Descrição |  |
| LINK | String |  | Link |  |
| CODUSU | Integer |  | Usuário Inclusão |  |
| DHCAD | DateTime |  | Criado em |  |
| CODUSUALT | Integer |  | Usuário Alteração |  |
| DHALTER | DateTime |  | Modificado em |  |
| TIPOAPRES | String |  | Visível | `GLO`=Qualquer tela `LOC`=Nesta tela |
| TIPOACESSO | String |  | Acesso | `GRU`=Meu grupo `ALL`=Qualquer usuário `USU`=Privado |
| RESOURCEID | String |  | ID tela |  |
| PKREGISTRO | String |  | Pk Registro |  |
| NUATTACH | Integer |  | Código |  |

## TSIAPRN — Acesso ao servidor de impressão e impressoras
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Usuário ou Grupo |  |
| NUSVP | Integer |  | Servidor de impressão |  |
| NUPRINTER | Integer |  | Impressora |  |
| TIPO | String |  | Tipo | `U`=Usuário `G`=Grupo |
| NOME | String |  | Nome usuário/grupo |  |

## TSIARF — TABLE TSIARF
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DHINI | DateTime |  | DHINI |  |
| DHFIM | DateTime |  | DHFIM |  |
| AGENDAMENTO | String |  | AGENDAMENTO |  |
| PROXEXEC | DateTime |  | PROXEXEC |  |
| EXECUNICA | String |  | EXECUNICA | `N`=Não `S`=Sim |
| DESCRICAO | String |  | DESCRICAO |  |
| ARQMODEMAIL | String |  | ARQMODEMAIL |  |
| CODUSURESP | Integer |  | Usuário responsável |  |
| CODSMTP | Integer |  | CODSMTP |  |
| NURFE | Integer |  | NURFE |  |
| EMAILMANUAL | C |  | EMAILMANUAL |  |

## TSIATA — Anexo
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo do Anexo |  |
| DESCRICAO | String |  | Descrição do Arquivo |  |
| ENDARQUI | String |  | Fim do Arquivo |  |
| ARQUIVO | String |  | Arquivo anexado |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| TIPOCONTEUDO | String |  | Tipo de Conteúdo | `P`=application/pdf `I`=image/jpeg `X`=application/vnd.ms-excel `N`=Nenhum `O`=Outro_(+1)_ |
| CONTEUDO | Boolean |  | Conteúdo |  |
| DTEXPIRA | DateTime |  | Data da expiração |  |
| EDITA | String |  | Edita |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| SEQUENCIAPR | Integer |  | SEQUENCIAPR |  |
| PUBLICO | String |  | PUBLICO |  |
| IDENTIFICACAOARQUIVO | String |  | Identificação Arquivo Físico |  |
| DTVIGOR | Date |  | Dt. Vigor |  |
| LINK | String |  | LINK |  |
| DTINCLUSAO | DateTime |  | Data inclusão |  |
| CODATA | Integer |  | Cód. Anexo |  |

## TSIATH — Configurações OAuth
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome da Configuração |  |
| PROVEDOR | String |  | Provedor | `G`=Gmail `O`=Outlook |
| NOMEDAAPI | String |  | Nome da API |  |
| CLIENTID | String |  | Client ID |  |
| CLIENTSECRET | String |  | Client Secret |  |
| URLAPIGOOGLE | String |  | URL da API do Google |  |
| URLGETACCESSTOKEN | String |  | URL para obter o Access Token |  |
| URLGOOGLEPEOPLE | String |  | URL da API do Google People |  |
| REDIRECTURI | String |  | Redirect URI |  |
| TENANT | String |  | Tenant |  |
| SCOPES | String |  | Scopes |  |
| CODATH | Integer |  | Cód. Configuração |  |

## TSIAVI — Avisos do sistema
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULO | String |  | Título |  |
| DESCRICAO | String |  | Descrição |  |
| SOLUCAO | String |  | Solução |  |
| IMPORTANCIA | Integer |  | Importância |  |
| CODUSU | Integer |  | Usuário |  |
| CODGRUPO | Integer |  | Grupo |  |
| DHCRIACAO | DateTime |  | Dh. Criação |  |
| IDENTIFICADOR | String |  | Identificador |  |
| TIPO | String |  | Tipo |  |
| CODUSUREMETENTE | Integer |  | Remetente |  |
| NUAVISOPAI | Integer |  | Aviso Pai |  |
| NUAVISO | Integer |  | Aviso |  |
| DTEXPIRACAO | Date |  | Dt. Expiração |  |
| DTNOTIFICACAO | Date |  | Dt. Notificação |  |
| ORDEM | Integer |  | Ordem |  |

## TSIBAI — Bairros
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEBAI | String |  | Nome |  |
| CODREG | Integer |  | Região |  |
| DESCRICAOCORREIO | String |  | Nome do Correio |  |
| DTALTER | DateTime |  | Data de alteração |  |
| ATUNUVERSAO | String |  | Atualizar versão |  |
| CODBAI | Integer |  | Código do Bairro |  |

## TSIBCO — Bancos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ABREVIATURA | String |  | Abreviatura |  |
| NOMEBCO | String |  | Descrição |  |
| CTACMC7INI | Integer |  | Pos. Inicial (Conta CMC7) |  |
| CTACMC7FIM | Integer |  | Pos. Final (Conta CMC7) |  |
| AD_MAXIMA | String |  | AD_MAXIMA |  |
| CODBCO | Integer |  | Cód. Banco |  |

## TSIBIAPI — Dashboards BIA
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDSB | Integer |  | Número Dashboard |  |
| SEQUENCE | Integer |  | Sequência |  |
| CODUSU | Integer |  | Código Usuário |  |
| DATA | DateTime |  | Data |  |
| METADATA | C |  | Metadados |  |

## TSIBIGDG — Gadgets por Dashboard
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDSB | Integer |  | Número DSB |  |
| NUGDG | Integer |  | Número GDG |  |

## TSIBLG — TSIBLG
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEARQ | String |  | Arquivo |  |
| URL | String |  | URL |  |
| TEMPO | Integer |  | Tempo (em segundos) |  |
| ORDEM | Integer |  | Ordem |  |
| PROFILE | String |  | Profile |  |
| EVO | String |  | Banner referente ao EVO? | `S`=Sim `N`=Não |
| NUARQUIVO | Integer |  | Cód. Arquivo |  |

## TSIBTA — Botão de Ação
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPO | String |  | Tipo | `SC`=Script (JavaScript) `RJ`=Rotina Java `SP`=Rotina no Banco de Dados `LC`=Lançador |
| NOMEINSTANCIA | String |  | Instância |  |
| RESOURCEID | String |  | Filtro de telas |  |
| CONFIG | C |  | Configuração |  |
| CODMODULO | Integer |  | Módulo Java |  |
| ORDEM | Integer |  | Ordem |  |
| CONTROLAACESSO | String |  | Controla Acesso | `N`=Não `S`=Sim |
| TECLAATALHO | String |  | Tecla de Atalho |  |
| IDBTNACAO | Integer |  | Código |  |

## TSIBTEF — BandeirasTEF
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | String |  | Código |  |
| BANDEIRA | String |  | Bandeira |  |
| TIPO | String |  | Tipo |  |

## TSICAN — Cancelamento de NFSe
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCAN | String |  | Código |  |
| CODCID | Integer |  | Cód. Cidade |  |
| MOTIVO | String |  | Motivo/Descrição |  |
| ENVIARPREFEITURA | String |  | Enviar a prefeitura | `D`=Somente o motivo/descrição `A`=Ambos `C`=Somente o código |
| TIPO | String |  | Tipo |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |

## TSICDFE — Consulta de documentos por empresa
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MDEPROXCONSULTA | DateTime |  | Próxima consulta NF-e |  |
| MDEPROXCONSCTE | DateTime |  | Próxima consulta CT-e |  |
| MDEPROXDOWNLOAD | DateTime |  | Próxima verificação de Download DF-e |  |
| ULTNSU | String |  | Último NSU |  |
| ULTNSUCTE | String |  | Último NSU CT-e |  |
| CODEMP | Integer |  | Empresa |  |

## TSICDI — Certificado Digital
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEARQUIVO | String |  | Certificado Digital |  |
| INTERNO | String |  | Senha do Certificado Digital |  |
| CGC_CPF | String |  | CNPJ / CPF do Destinatário |  |

## TSICEP — CEP
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CEP | String |  | CEP |  |
| CODBAI | Integer |  | Cód.Bairro |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CODEND | Integer |  | Cód.Endereço |  |
| INTERVALO | String |  | Intervalo de Números |  |

## TSICFA — Liberação de Filtros
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUINSTANCIA | Integer |  | Instância |  |
| NOMEFILTRO | String |  | Nome do Filtro |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| EXPRESSAO | C |  | Expressão |  |
| AUTOR | Integer |  | Autor Filtro |  |
| DTCRIACAO | DateTime |  | Data Criação |  |
| ALTERADOPOR | Integer |  | Alterado Por |  |
| DTALTERACAO | DateTime |  | Data Alteração |  |
| OBSERVACAO | String |  | Observação |  |
| CODFIL | Integer |  | Cód. Filtro |  |

## TSICFG — Configuração de recurso
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CONFIG | C |  | CONFIG |  |
| TIPO | String |  | TIPO | `Tela`=T `Filtro`=F |
| CHAVEPAI | String |  | CHAVEPAI |  |
| CHAVE | String |  | CHAVE |  |

## TSICFGBK — Backup Configuração de recurso
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CHAVE | String |  | CHAVE |  |
| TIPO | String |  | TIPO |  |
| CHAVEPAI | String |  | CHAVEPAI |  |
| CONFIG | C |  | CONFIG |  |
| NUNICO | Integer |  | NUNICO |  |

## TSICID — Cidades
Campos: 63

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMECID | String |  | Nome |  |
| UF | Integer |  | Cód. UF |  |
| DDD | String |  | DDD |  |
| CODREG | Integer |  | Região |  |
| DISTANCIA | Integer |  | Distância |  |
| SEQENTREGA | Integer |  | Sequência de entrega |  |
| POPULACAO | Integer |  | População |  |
| CODMUNFIS | Integer |  | Mun. domicílio fiscal |  |
| CODMUNSIAFI | Integer |  | Cód. município SIAFI |  |
| CODMUNDMS | Integer |  | Cód. município DMS |  |
| DESCRICAOCORREIO | String |  | Nome do correio |  |
| DTALTER | DateTime |  | Data de alteração |  |
| VLRFRETEMIN | Float |  | Valor de frete mínimo |  |
| VLRFRETETON | Float |  | Valor de frete por tonelada |  |
| TIPOFRETE | String |  | Tipo de frete | `N`=Nota Série A `C`=CTRC |
| METARREDVLRISS | String |  | Método de arredondamento do valor ISS | `C`=Convencional `A`=ABNT NBR 5891 `B`=Truncar em duas casas decimais |
| VLRFRETEKM | Float |  | Valor de frete por KM |  |
| VLRTAXAENT | Float |  | Valor taxa de entrada |  |
| TEMSUBSTITNFSE | String |  | Tem substituição NFS-e | `N`=Não `S`=Sim |
| LINKAGUA | String |  | Link conta água |  |
| QTDSUB | Integer |  | Quantidade de substituições permitidas |  |
| LINKENERGIA | String |  | Link conta energia |  |
| QTDDIASSUB | Integer |  | Prazo para substituição de NFS-e |  |
| LINKIPTU | String |  | Link conta IPTU |  |
| LATITUDE | String |  | Latitude |  |
| LONGITUDE | String |  | Longitude |  |
| VENDAMIN | Float |  | Venda Mínima |  |
| TIPCANCNFSE | String |  | Tipo de cancelamento para NFS-e | `4`=Via prefeitura sem número de protocolo `3`=Via prefeitura com número de protocolo `2`=Via web service com valor limite de cancelamento `1`=Via web service |
| VLRLIMCANCNFSE | Float |  | Valor limite para cancelamento NFS-e |  |
| MOTCANCSUBNFSE | String |  | Motivo de cancelamento para substituição de NFS-e |  |
| MAXNOTALOTENFSE | Integer |  | Qtd. máxima de notas em um lote NFS-e |  |
| TIMPARCPREFEITURA | Integer |  | Parceiro Prefeitura |  |
| ACTCANEXNT | String |  | Permite cancelamento extemporâneo? | `S`=Sim `N`=Não |
| TIPOCNAE | Integer |  | Tipo de envio do CNAE | `null`=Normal `1`=9 dígitos com zeros a direita `2`=9 dígitos com zeros a esquerda `4`=7 dígitos com zeros a esquerda `3`=7 dígitos com zeros a direita |
| CNAEFULLNFSE | String |  | Usar CNAE completo | `S`=Sim `N`=Não |
| NOFORMATLC116 | String |  | Não formatar LC116 | `S`=Sim `N`=Não |
| NOINSCMUNPAR | String |  | Não enviar insc. mun. quando ISS não incidir no município do parceiro | `N`=Não `S`=Sim |
| GERCODNATISSJSON | String |  | Gerar Código Natureza Operação ISS no Json | `S`=Sim `N`=Não |
| ENVITENSSEPJSON | String |  | Enviar itens de NFS-e separados no Json | `S`=Sim `N`=Não |
| ENVFPJSON | String |  | Enviar forma de pagamento no Json | `S`=Sim `N`=Não |
| GERNUNFSEINFCPM | String |  | Gerar o nº da NFSe nas Inf. Complementares da Substituição | `S`=Sim `N`=Não |
| ENVMULEMAILJSON | String |  | Envia múltiplos e-mails no Json | `N`=Não `S`=Sim |
| INFQTDVLRUNIJSON | String |  | Enviar quantidade e valor unitário no Json | `S`=Sim `N`=Não |
| ENVTAGDESCONJSON | String |  | Enviar tag descontoCondicionado no metadados do Json? | `N`=Não `S`=Sim |
| JSONSEMALIDENMUN | String |  | Envia alíquota no Json apenas quando o ISS for devido a outro município | `S`=Sim `N`=Não |
| VMINRETENCAOISS | Float |  | Valor mínimo para retenção |  |
| QTDMAXENVITENSJSON | Integer |  | Quantidade Máxima p/ enviar itens NFS-e no Json |  |
| REMZEROESQUERDLC116 | String |  | Remover zero a esquerda LC116 | `S`=Sim `N`=Não |
| ENVCODIGONBSJSON | String |  | Enviar o Código NBS no JSON | `N`=Não `S`=Sim |
| DESCONVERSAONAT | String |  | Desabilitar conversão de natureza de operação? | `S`=Sim `N`=Não |
| MASCARANBS | String |  | Máscara NBS |  |
| AD_MAXIMA | String |  | Integra com a Máxima? | `N`=Não `S`=Sim |
| NFSETEMPLATESUBST | String |  | Utiliza processo específico para substituição? | `S`=Sim `N`=Não |
| PERMCANCNFSESUBSTIT | String |  | Permite cancelamento de NFS-e substituta? | `S`=Sim `N`=Não |
| OBSJSONENOTAS | String |  | Observação do Json | `null`=Padrão `G`=Obs. da nota + Obs. padrão da nota + Obs. dos itens de serv. `F`=Obs. padrão da nota + Obs. dos itens de serviços `E`=Observação da nota + Obs. dos itens de serviços `D`=Observação dos itens de serviços_(+3)_ |
| CODPARCNFSE | Integer |  | Parceiro Padrão NFSe |  |
| ATUNUVERSAO | String |  | Atualizar versão |  |
| MASCARALC116 | String |  | Máscara LC116 |  |
| GERCNAEMULTJSON | String |  | Gerar CNAE para Múltiplos Itens no JSON | `S`=Sim `N`=Não |
| REGESPTRIB | String |  | Enviar o Regime Especial de Tributação no json? | `N`=Não `S`=Sim |
| ENVTPSERVJSON | String |  | Enviar Tipo de Serviço no Json? | `N`=Não `S`=Sim |
| CODCID | Integer |  | Cód. Cidade |  |
| UFNOMECID | String |  | Cidade - UF |  |

## TSICLA — Classificação de campos proteção de dados
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCCLA | String |  | Descrição da Classificação |  |
| CODUSUCRIAC | Integer |  | Código usuário criação |  |
| DTCRIAC | DateTime |  | Data criação |  |
| CODUSUALTER | Integer |  | Código usuário alteração |  |
| DTALTER | DateTime |  | Data alteração |  |
| CODCLA | Integer |  | Código da Classificação |  |

## TSICND — TABLE TSICND
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| DESCRICAO | String |  | Descrição |  |
| TABELA | String |  | Nome da Tabela no Banco de Dados |  |
| OBSERVACAO | String |  | Observação |  |
| TIPCONSOLIDACAO | Integer |  | Início da Consolidação | `1`=Variável `0`=Fixa |
| DATAINICIAL | Date |  | Data Inicial |  |
| QTDMESESCONSOLIDAR | Integer |  | Qtd. Meses a Consolidar |  |
| QTDMESESRETROAGIR | Integer |  | Qtd. Meses a Retroagir |  |
| TIPPROCESSAMENTO | String |  | Agrupamento | `U`=Único `M`=Mensal `D`=Diário |
| TIPGATILHO | String |  | Tipo de Gatilho | `I`=Intervalo de Tempo `C`=Expressão CRON |
| EXPGATILHO | String |  | Expressão de Gatilho |  |
| TIPINTERVALO | String |  | Tipo de Intervalo | `S`=Segundos `M`=Minutos `H`=Horas |
| VLRINTERVALO | Integer |  | Valor |  |
| CONSULTA | C |  | Consulta |  |
| FONTEDADOS | String |  | Fonte Dados |  |
| DHPROXEXEC | DateTime |  | Dt. Próx. Execução |  |
| DHULTEXEC | DateTime |  | Dt. Últ. Execução |  |
| TEMPOPROCESSAMENTO | Integer |  | Tempo de Processamento (seg.) |  |
| INVALIDO | String |  | INVALIDO |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| STATUS | String |  | Status |  |
| LOG_ERRO | String |  | Log Erro |  |
| CODCONSOLIDACAO | Integer |  | Código |  |

## TSICOL — Colunas das tabelas
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTABSIS | Integer |  | Número único da tabela |  |
| CODCOLUNA | String |  | Cód.Coluna |  |
| NOMECOLUNA | String |  | Nome da Coluna |  |
| DESCRCOLUNA | String |  | Descrição da Coluna |  |
| TIPO | String |  | Tipo |  |
| TAMCAMPO | Integer |  | Tamanho do Campo |  |
| OBRIGATORIO | String |  | Campo Obrigatório |  |
| ALINHAMENTO | Integer |  | Alinhamento |  |
| VALIDACAO | String |  | Validação |  |
| FK | String |  | Foreign Key |  |
| VLRPADRAO | String |  | Valor Padrão |  |
| COLUSUARIO | String |  | Coluna do Usuário |  |
| OPCOESCOMBO | String |  | Opções do Combo |  |
| MASCARA | String |  | Máscara |  |
| GRUPO | String |  | Grupo do Campo |  |
| ORDEM | Integer |  | Ordem do campo |  |
| NUCOL | Integer |  | Número único da Coluna |  |

## TSICONF — Configurações do Usuário
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CONF | String |  | Configurações |  |
| FORM | String |  | Form |  |

## TSICONFBK — Backup Configurações do Usuário
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| FORM | String |  | FORM |  |
| CONF | String |  | CONF |  |
| NUNICO | Integer |  | NUNICO |  |

## TSICOT — Cotação de Valor para Moeda
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTMOV | Date |  | Data do movimento |  |
| COTACAO | Float |  | Cotação |  |
| INDICE2 | Float |  | Índice 2 |  |
| INDICEDESC | Float |  | Índice Desconto |  |
| CODMOEDA | Integer |  | Cód.Moeda |  |

## TSICPO — Configuração de Pedido Offline
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCONFIG | String |  | Descrição |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| PADRAO | String |  | Padrão | `S`=Sim `N`=Não |
| CAPTURAGEO | String |  | Capturar geolocalização | `S`=Sim `N`=Não |
| FOTOPRODUTO | String |  | Sincronizar fotos dos produtos | `S`=Sim `N`=Não |
| PARCEIROEXP | String |  | Parceiros |  |
| PRODUTOEXP | String |  | Produtos |  |
| TIPONEGOCIACAOEXP | String |  | Tipos de Negociação |  |
| CODCONFIG | Integer |  | Cód. Config |  |

## TSICSB — Consolidar Eventos
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORIGEM | String |  | Origem |  |
| SID | Integer |  | SID |  |
| NMEXECUTOR | String |  | Nome do Executor |  |
| DBUSERNAME | String |  | Usuário do Banco de Dados |  |
| TOKEN | String |  | Token da Tela |  |
| DATA | Date |  | Data |  |
| MD5 | String |  | MD5 |  |
| COMANDO | Boolean |  | Comando |  |
| UNIQUEID | String |  | UID |  |
| CALLID | String |  | Id da Chamada |  |
| NMTHREAD | String |  | Nome da Thread |  |
| STACKTRACE | Boolean |  | Trace |  |
| QTDVEZES | Integer |  | Quantidade de Vezes |  |
| MAIORTEMPO | Float |  | Maior Tempo |  |
| MENORTEMPO | Float |  | Menor Tempo |  |
| MEDIA | Float |  | Media |  |
| MEDIASEMMAIORMENORTEMPO | Float |  | Media Sem Maior e Menor Tempo |  |
| TOTALIZADORTEMPO | Float |  | Media Sem Maior e Menor Tempo |  |
| DTCOMMAND | Date |  | Dt. Da ultima execução |  |
| SCORE | Float |  | Score |  |
| USERID | Integer |  | ID do Usuário |  |
| TIPOCOMANDO | String |  | Tipo De Comando |  |

## TSICTA — Contas Bancárias
Campos: 119

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTABCO | String |  | Conta |  |
| DESCRICAO | String |  | Descrição |  |
| CODBCO | Integer |  | Banco |  |
| CODAGE | String |  | Agência bancária |  |
| CODEMP | Integer |  | Empresa |  |
| CODCTACTB | Integer |  | Conta contábil |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| DTIMPLANT | Date |  | Referência p/ aceitar lançamentos |  |
| SALDOBCO | Float |  | Saldo do banco na referência |  |
| SALDOREAL | Float |  | Saldo real na referência |  |
| EXCLUSIVA | String |  | Exclusiva da empresa | `N`=Não `S`=Sim |
| ATIVA | String |  | Ativa | `S`=Sim `N`=Não |
| CLASSE | String |  | Tipo de conta | `E`=Empréstimo `D`=Adiantamento `Z`=Caixa (PDV) `G`=Garantida `S`=Sócios_(+5)_ |
| NUMCHEQ | Integer |  | Último nro. cheque |  |
| CODOPEREXCL | Integer |  | Operador exclusivo |  |
| CODMOEDA | Integer |  | Moeda |  |
| CODCORRBCO | Integer |  | Correspondente bancário |  |
| CARTEIRA | Integer |  | Carteira |  |
| CONVENIO | Integer |  | Convênio |  |
| INSTRUCAOI | Integer |  | Instrução I |  |
| INSTRUCAOII | Integer |  | Instrução II |  |
| DIASPROT | Integer |  | Dias para protesto |  |
| CODCTABCOINTREM | Integer |  | Conta p/controlar a seq.de remessa |  |
| SEQREM | Integer |  | Sequência remessa |  |
| REMFINAL | Integer |  | Nro máx.p/seq.remessa |  |
| SEQREM2 | Integer |  | Sequência remessa alternativa |  |
| REMFINAL2 | Integer |  | Nro máx.p/seq.remessa alternativa |  |
| REMBCO | Integer |  | Último boleto |  |
| CODLANCBAIXABOLRAP | Integer |  | Lançamento baixa boleto |  |
| CODTIPOPERBAIXABOLRAP | Integer |  | TOP Baixa boleto |  |
| REMBCOMAX | Integer |  | Número máximo |  |
| ZERARAUT | String |  | Zerar automaticamente | `S`=Sim `N`=Não |
| EMITEBOLETA | String |  | Emite | `S`=Sim `N`=Não |
| CTADEFEMIBOL | String |  | Conta padrão para emissão | `N`=Não `S`=Sim |
| IMPBOLETA | String |  | Impressora |  |
| TIPOIMPRESSORA | String |  | Tipo impressora | `7`=XEROX LAZER `6`=DESKJET `5`=OUTRAS `2`=EPSON `1`=ELEBRA RIMA_(+2)_ |
| MODBOLETA | Integer |  | Modelo |  |
| VLRMINBOLETA | Float |  | Valor mínimo |  |
| CTAMINBOLETA | Integer |  | Alterar p/outra conta |  |
| TAXA | Float |  | Ou cobrar taxa |  |
| NURFEMODCHEQG | Integer |  | Modelo de cheque |  |
| DTALTER | Date |  | Data alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUCONTRATO | Integer |  | Nro. Contrato |  |
| CATEGLANCHQ | Integer |  | Categoria p/ lançamento de cheque |  |
| MODALIDADE | Integer |  | Modalidade |  |
| NUMCLIENTE | Integer |  | Número do cliente |  |
| CAMPOLIVRE | String |  | Campo Livre |  |
| NUMBENEFICIARIO | String |  | Número Beneficiário |  |
| NOSSONUMERO | String |  | Configuração do Nosso Número |  |
| MULTIPNOSSONUM | String |  | Multiplicadores |  |
| TIPMULTIPSOMA | String |  | Ao somar as multiplicações | `T`=Somar os totais da multiplicação `D`=Somar dígito a dígito dos totais |
| TIPMODNOSSNUM | String |  | Tipo do Módulo | `O`=Módulo 11 `D`=Módulo 10 |
| SUBRESTMODULO | String |  | Substitui resto: |  |
| RESTOSUBST1 | Integer |  | Se resto igual: |  |
| RESTOSUBST2 | Integer |  | Se resto igual: |  |
| RESTOSUBST3 | Integer |  | Se resto igual: |  |
| DIGITOSUBST1 | String |  | substitui por: |  |
| DIGITOSUBST2 | String |  | substitui por: |  |
| DIGITOSUBST3 | String |  | substitui por: |  |
| NOSSONUMATIVO | String |  | Usar geração de Nosso Número |  |
| LINHADIGATIVO | String |  | Usar geração da Linha Digitável |  |
| IDCLIENTE | String |  | ID do cliente |  |
| CODAGEBENEF | Integer |  | Agência Beneficiário |  |
| CODCTABENEF | Integer |  | Conta Beneficiário |  |
| CODCTABAIXA | Integer |  | Conta p/ baixa (Processamento de Retorno) |  |
| AD_MAXIMA | String |  | Integra com a Máxima? |  |
| INDNOSSONUM | String |  | Indicador do Nosso Número |  |
| CODCONTARURAL | String |  | Classificação da conta Produtor Rural | `000`=000 - Caixa `999`=999 - Em trânsito |
| NUMCONTARURAL | String |  | Número da conta Produtor Rural |  |
| TITINFADICPIX | String |  | Titulo Inf. Adicional Pix API |  |
| MENADICPIX | String |  | Mensagem Inf. Adicional Pix API |  |
| CHAVEAPIPIX | String |  | Chave da API Pix |  |
| NURFEMODBOLETO | Integer |  | Modelo de Boleto |  |
| SENCLIPIX | String |  | Client Secret Pix |  |
| IDCLIPIX | String |  | Client ID Pix |  |
| CHAVEPIX | String |  | Chave pix |  |
| URLPIX | String |  | URL pix |  |
| IDAPIBANCO | Integer |  | Sequência remessa alternativa |  |
| QTDDIASVALPIX | Integer |  | Qtd. Dias Val. Pix após Venc |  |
| CONCAUTRECEBPIX | String |  | Conciliar automaticamente os recebimentos via API | `S`=Sim `N`=Não |
| TIPOAPIBOLETO | String |  | Selecione o serviço | `R`=PJ Bank `B`=API do Banco |
| VARIACAO | Integer |  | Variação |  |
| ACEITATITULOVENCIDO | String |  | Aceita Titulo Vencido |  |
| UTILIZAPIXPDV | String |  | Utiliza PIX PDV | `N`=Não `S`=Sim |
| RECEBIMENTODIAS | Integer |  | Dias de recebimento |  |
| RECEBIMENTOPARCIAL | String |  | Recebimento parcial |  |
| STATUSAPI | String |  | Status Api |  |
| INDICADORPIX | String |  | Indicador pix |  |
| DTREGCONTA | Date |  | Data de registro da conta |  |
| APIBAIXAAUTOMATICA | String |  | Selecione o tipo | `R`=Realizar na data de pagamento `N`=Não realizar `C`=Realizar na data do crédito em conta |
| APICONCILIACAOAUTOMATICA | String |  | Selecione o tipo | `R`=Realizar na data de pagamento `N`=Não realizar `C`=Realizar na data do crédito em conta |
| TIPOJUROS | String |  | Selecione o tipo | `A`=Percentual anual `P`=Percentual diário `V`=Valor fixo por dia de atraso `T`=Taxa mensal `I`=Isento_(+1)_ |
| TIPOMULTA | String |  | Selecione o tipo | `V`=Valor fixo `P`=Percentual `D`=Dispensar |
| DATAMULTA | String |  | Selecione o tipo | `C`=Configurar quantidade de dias `=U`=Usar data de vencimento |
| VALORJUROS | Float |  | Valor juros |  |
| VALORMULTA | Float |  | Valor multa |  |
| DIASMULTA | Integer |  | Dias Multa |  |
| DIASPARANEGATIVACAO | Integer |  | Dias para Negativação |  |
| ORGAONEGATIVADOR | Integer |  | Orgão Negativador |  |
| DIASPROTESTO | Integer |  | Dias para protesto |  |
| INSTRUCAOPROTESTO | Integer |  | Instrução de protesto |  |
| INSTRUCAONEGATIVACAO | Integer |  | Instrução de negativação |  |
| CONTABILIZARDIAS | String |  | Contabilizar dia útil ou dias corridos |  |
| DTENVIOAPIBANCO | Date |  | Data da integração com a API de boletos |  |
| IDSEQBOL | Integer |  | Id Sequencial do boleto Liquidado |  |
| DATAJURO | String |  | Data dos juros | `C`=Configurar quantidade de dias `U`=Usar data de vencimento |
| DIASJURO | Integer |  | Dias Juros |  |
| DTDESCREDCONTA | Date |  | Data de descredenciamento da conta |  |
| DESCONSLCDPR | String |  | Desconsiderar Conta na Geração do Livro Caixa Digital do Produtor Rural | `S`=Sim `N`=Não |
| AD_FLUXODECAIXA | String |  | Participa do Fluxo de Caixa | `S`=Sim `N`=Não |
| AD_BKP_EXCLUSIVA | String |  | BKP_EXCLUSIVA |  |
| CODCTABCOINT | Integer |  | Código da conta bancária |  |
| BJBBAIBOLPAG | String |  | Baixar o tílulo quando o boleto for pago |  |
| PJBCHAVE | String |  | Chave |  |
| PJBCONBAIXCRED | String |  | Conciliar a baixa do titulo ao receber o crédito |  |
| PJBCRED | String |  | Credencial |  |
| TIPOBOLETO | String |  | Tipo Boleto | `R`=RAPIDO `A`=AVANCADO `P`=CNAB `I`=PIX |
| LOGOURL | String |  | Guarda logomarca |  |

## TSICTAPI — Api Monitor
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RESOURCEID | String |  | Hash |  |
| SEQUENCE | Integer |  | Cd. Usurio |  |
| CODUSU | Integer |  | Cd. Usurio |  |
| DATA | DateTime |  | Data |  |
| METADATA | C |  | Primeiro Login |  |

## TSICTDRAFT — Instâncias em Draft
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTELA | String |  | Descrição Tela |  |
| RESOURCEID | String |  | Resource Id |  |
| DRAFT | String |  | Rascunho |  |
| CODUSULIB | Integer |  | Cód. Usuário Liberação |  |
| DHLIBERACAO | DateTime |  | Data Liberação |  |
| DHALTER | DateTime |  | Data Alteração |  |

## TSICTRES — ResourceID de Instância
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RESOURCEID | String |  | Resource Id |  |
| NOMEINSTANCIA | String |  | Nome da Instância |  |

## TSICUS — Centros de Resultado
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCENCUS | Integer |  | Código |  |
| DESCRCENCUS | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CALCELALURPARTEA | String |  | CR para calculo e-LALUR (Parte A) | `S`=Sim `N`=Não |
| ANALITICO | String |  | Analítico | `S`=Sim `N`=Não |
| VEICULO | String |  | Veículo Obrigatório | `S`=Sim `N`=Não |
| CODUSURESP | Integer |  | Usuário Responsável |  |
| CODPARCRESP | Integer |  | Parceiro Responsável |  |
| AREA | Float |  | Área |  |
| CODUNN | Integer |  | Unidade de negócio |  |
| AREAREAL | Float |  | Área Real |  |
| DTINCLUSAO | DateTime |  | Dt. Inclusão |  |
| AREACONT | Float |  | Área Contábil |  |
| AREAPERM | Float |  | Área Permutada |  |
| CODTAB | Integer |  | Tabela de Preço |  |
| FRACGEREN | Float |  | Fração Real |  |
| FRACCONT | Float |  | Fração Contábil |  |
| GRAU | Integer |  | Grau |  |
| CODUNG | Integer |  | Unidade Gerencial |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODCENCUSPAI | Integer |  | Cód.Centro Resultado Pai |  |

## TSICVIEWS — TSICVIEWS
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| DHALTER | DateTime |  | Dh. Alteração |  |
| CODUSU | Integer |  | Usuário de alteração |  |
| SELECTVIEW | C |  | Select |  |
| DHSINC | DateTime |  | Dh.Sinc DB |  |
| NOME | String |  | Nome |  |
| NUVIEW | Integer |  | Nu.View |  |

## TSICVT — Consultas Variáveis por tabela
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CONSULTA | String |  | Consulta |  |
| COLRET | String |  | Coluna de retorno |  |
| COLEXIBE | String |  | Exibição no lookup |  |
| COLCON | String |  | Coluna para Consulta |  |

## TSIDAS — Documento Assinado
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVEARQUIVO | String |  | Chave Arquivo |  |
| NOMEARQUIVO | String |  | Nome Arquivo |  |
| DESCRICAO | String |  | Descrição |  |
| STATUS | String |  | Status Assinatura Digital | `A`=Assinado `T`=Tempo Excedido `S`=Assinatura Solicitada `R`=Rejeitado `P`=Pendente_(+2)_ |
| CODUSU | Integer |  | Usuário Solicitante |  |
| DHSOLIC | DateTime |  | Dh. Solicitação |  |
| DHRESP | DateTime |  | Dh. Resposta |  |
| HASHARQUIVO | String |  | Hash Arquivo |  |
| TRANSACTIONID | String |  | Transaction ID |  |
| IDSOLICITANTE | String |  | ID Solicitante |  |
| IDDESTINATARIO | String |  | ID Destinatário |  |
| TIPONOTIFIC | String |  | Tipo de Notificação |  |
| NOMESOLICITANTE | String |  | Nome Solicitante |  |
| NOMEDESTINATARIO | String |  | Nome Destinatário |  |
| DETALHESTATUS | String |  | Detalhes Status |  |
| NUDOC | Integer |  | Núm. Documento |  |

## TSIDAS_EXC — TABLE TSIDAS_EXC
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MOTIVOEXC | String |  | MOTIVOEXC |  |
| CHAVEARQUIVO | String |  | CHAVEARQUIVO |  |
| CODUSUEXC | Integer |  | CODUSUEXC |  |
| DHEXC | DateTime |  | DHEXC |  |
| NUDOC | Integer |  | NUDOC |  |

## TSIDAS_HIS — TABLE TSIDAS_HIS
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEVENTO | Integer |  | Evento | `5`=Reenvio Forçado `4`=Revogação `3`=Download `2`=Consulta `1`=Solicitação |
| STATUS_ASSINATURA | String |  | Status Assinatura | `T`=Tempo Excedido `S`=Solicitada `P`=Pendente `N`=Reenvio `E`=Erro_(+3)_ |
| TIPODOC | String |  | Tipo do Documento |  |
| DHEVENTO | DateTime |  | Dh. Evento |  |
| ERRO | C |  | Descrição do Erro |  |
| TRANSACTIONID | String |  | Transaction ID |  |
| SOLICITACAO_MANUAL | Integer |  | Solicitação Manual | `1`=Manual `0`=Automática |
| CODUSU | Integer |  | Cód. Usuário Executante |  |
| DETALHES_STATUS | String |  | Detalhes Status |  |
| MSG | String |  | Mensagem |  |
| CHAVEDOC | String |  | Chave Documento |  |
| HASHARQUIVO | String |  | Hash Arquivo |  |
| ID | Integer |  | ID |  |
| NUDOC | Integer |  | Núm. Documento |  |

## TSIDBQUERY — TABLE TSIDBQUERY
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULOQUERY | String |  | Descrição |  |
| DHALTER | DateTime |  | Dh. alteração |  |
| TEXTOQUERY | C |  | Texto SQL |  |
| CODUSU | Integer |  | Usuário |  |
| NUQUERY | Integer |  | Nro. único |  |

## TSIDIS — Rotas para Cargas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARCDEST | Integer |  | Cód. Parceiro Destino |  |
| CODCIDORIG | Integer |  | Cód. Cidade Origem |  |
| CODCIDDEST | Integer |  | Cód. Cidade Destino |  |
| DISTANCIA | Float |  | Distância em km |  |
| OBS | String |  | Observações |  |
| CODPARCORIG | Integer |  | Cód. Parceiro Origem |  |

## TSIDRF — Destinatários Relatórios Formatados
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODCON | Integer |  | CODCON |  |
| NURFE | Integer |  | NURFE |  |

## TSIDSB — Tabela de Dashboards
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULO | String |  | Título |  |
| DESCRICAO | String |  | Descrição |  |
| LAYOUT | C |  | Layout | `true`=encodedtransport |
| GRUPO | String |  | Grupo |  |
| CODUSUINC | Integer |  | Cód. Usuário Inclusão |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data/Hora Modificação |  |
| NUDSB | Integer |  | Dashboard |  |

## TSIDSBA — Tabela do Analytics
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULO | String |  | Título |  |
| DESCRICAO | String |  | Descrição |  |
| CONFIG | C |  | Config | `true`=encodedtransport |
| GRUPO | String |  | Grupo |  |
| CODUSUINC | Integer |  | Cód. Usuário Inclusão |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data/Hora Modificação |  |
| DHINC | DateTime |  | Data/Hora Inclusão |  |
| NUDSB | Integer |  | Analytics |  |

## TSIDSBADP — Modelo de Fonte de Dados
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULO | String |  | Título |  |
| CONFIG | C |  | Config | `true`=encodedtransport |
| CODUSUINC | Integer |  | Cód. Usuário Inclusão |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data/Hora Modificação |  |
| DHINC | DateTime |  | Data/Hora Inclusão |  |
| NUDSB | Integer |  | Analytics |  |

## TSIDSBAPER — Permissão do Analytics
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo | `U`=Usuário `G`=Grupo de usuário `F`=Fórmula |
| CODIGO | Integer |  | Código |  |
| DHINC | DateTime |  | Data/Hora Inclusão |  |
| NOME | String |  | Nome |  |
| NUDSB | Integer |  | Analytics |  |

## TSIDSG — Gadgets por Dashboard
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUGDG | Integer |  | NUGDG |  |
| NUDSB | Integer |  | NUDSB |  |

## TSIDSU — DataSource por Usuário
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUGDG | Integer |  | Componente de BI |  |
| DATASOURCE | String |  | Fonte de dados |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODUSU | Integer |  | Usuário |  |

## TSIEJO — Estatisticas Job
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| STATUSEXEC | String |  | Status | `W`=Aguardando `S`=Parado `P`=Pausado `E`=Erro `R`=Executando |
| DHEXEC | DateTime |  | Dt. Última Execução |  |
| DHPROXEXEC | DateTime |  | Dt. Próxima Execução |  |
| MEDIAEXEC | Integer |  | Tempo Médio |  |
| TEMPOMAXEXEC | Integer |  | Maior Tempo de Execução |  |
| TEMPOMINEXEC | Integer |  | Menor Tempo de Execução |  |
| TEMPOULIMAEXEC | Integer |  | Tempo Última Execução |  |
| TEMPOEXEC | Integer |  | Tempo Exec |  |
| QTDEXECS | Integer |  | Qtd. Execuções |  |
| MSGERRO | String |  | Mensagem de Erro |  |
| QTDFALHAS | Integer |  | Qtd. Falhas |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| TIPJOB | String |  | Tipo de Job | `U`=Usuário `I`=Interno |
| ERROTRACE | String |  | Detalhe do erro |  |
| ID | String |  | Cod. Job |  |

## TSIEMP — Empresas
Campos: 89

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| COOPERATIVA | String |  | Cooperativa | `N`=Não `S`=Sim |
| TIPOREGRA | String |  | Tipo p/ Certificação de Regra |  |
| NOMEFANTASIA | String |  | Nome Fantasia |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| RAZAOABREV | String |  | Razão Abreviada |  |
| CODEMPMATRIZ | Integer |  | Empresa Matriz |  |
| RAZAOSOCIALCOMPLETA | String |  | Razão Social Completa |  |
| NUMPROPR | Integer |  | Número de Proprietários |  |
| USARAZAOSOCIAL | String |  | Usar como Razão Social o campo | `null`=Não se aplica `R`=Razão Social `C`=Razão Social Completa |
| PRINCTITULAR | String |  | Principal Titular |  |
| CGC | String |  | CNPJ/CPF |  |
| INSCESTAD | String |  | Inscrição Estadual |  |
| INSCMUN | String |  | Inscrição Municipal |  |
| CODCNL | String |  | Código Nacional Localidade |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| EMPAGRUPARGOL | Integer |  | Empresa p/ Agrupar no GOL |  |
| LIMCURVA_B | Float |  | Limite Curva B |  |
| LIVROSFISCAIS | String |  | Livros Fiscais | `N`=Não `S`=Sim |
| CODEND | Integer |  | Endereço |  |
| NUMEND | String |  | Número |  |
| COMPLEMENTO | String |  | Complemento |  |
| CODBAI | Integer |  | Bairro |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CEP | String |  | CEP |  |
| TELEFONE | String |  | Telefone |  |
| FAX | String |  | Fax |  |
| TELEX | String |  | Telex |  |
| EMAIL | String |  | Email |  |
| HOMEPAGE | String |  | Home Page |  |
| CODMUN | Integer |  | Cód. Município |  |
| NATESTAB | Integer |  | Natureza Estabelecimento |  |
| NATJUR | Integer |  | Natureza Jurídica |  |
| RAMOATIV | String |  | Ramo de Atividade |  |
| ATIVECON | Integer |  | Atividade Econômica |  |
| CNAEPREPON | Integer |  | CNAE Preponderante |  |
| REGJUNTACOM | String |  | Reg. Junta Comercial (NIRE) |  |
| DTREGJUNTA | Date |  | Data Registro na Junta (NIRE) |  |
| DTCONVSOC | Date |  | Data Conversão (Sociedade Simples p/ Empresária) |  |
| SIMPLES | String |  | Optante pelo SIMPLES | `N`=Não `S`=Sim |
| SIMPLESNACNAUF | String |  | Tem convênio Simples Nacional no Estado | `S`=Sim `N`=Não |
| CODREGTRIB | Integer |  | Cód. Regime Tribut. | `2`=Simples Nacional - Sublimite `1`=Simples Nacional `3`=Regime Normal |
| TIPOSN | Integer |  | Tipo de Partilha/Anexo SN | `3`=Anexo III - Rec. de locação de bens/móveis e prest. de serv. não relac. no § 5o-C do art. 18 da Lei `2`=Anexo II - Indústria `4`=Anexo IV - Rec. decorrentes da prest. de serv. relacionados no § 5o-C do art. 18 da Lei `7`=Anexo V - Rec. decorrentes da prest. de serv. relacionados no § 5o-I do art. 18 da Lei `1`=Anexo I - Comércio |
| INDCOOP | Integer |  | Cooperativa | `3`=Outras Cooperativas `2`=Cooperativa de Produção `1`=Cooperativa de Trabalho `0`=Não é cooperativa |
| SERIENFDES | String |  | Série NF DES-BH |  |
| INDCONSTR | Integer |  | Construtora | `1`=Empresa Construtora `0`=Não é construtora |
| MODELONFDES | String |  | Modelo Nota Fiscal |  |
| INFOOBRA | Integer |  | Contribuição Patronal | `2`=Não substituída `1`=Substituída |
| ESTOQUE | String |  | Estoque | `N`=Não `S`=Sim |
| ACDINTISENMULTA | Integer |  | Acordo internacional Isenção | `null`=Não se Aplica `1`=Com acordo `0`=Sem acordo |
| COMISSOES | String |  | Comissões | `N`=Não `S`=Sim |
| CLASSTRIB | Integer |  | Classificação Tributária | `99`=99. Pessoas Jurídicas em geral `9`=09. Órgão Gestor de Mão de Obra - OGMO `85`=85. Administração direta da União, Estados, Distrito Federal e Municípios; autarquias e fundaçõe... `80`=80. Entidade beneficente de assistência social isenta de contribuições sociais `70`=70. Empresa de que trata o Decreto 5.436/2005_(+13)_ |
| FINANCEIRO | String |  | Financeiro | `S`=Sim `N`=Não |
| INDOPCCP | Integer |  | Tributação da Contribuição Previdenciária | `2`=Sobre a folha de pagamento `1`=Sobre a comercialização da sua produção `0`=Não se aplica |
| CONTABILIDADE | DateTime |  | Contabilidade |  |
| INDSITESP | Integer |  | Situação Especial | `4`=Incorporação `3`=Cisão `2`=Fusão `1`=Extinção `0`=Situação Normal |
| PRODUCAO | String |  | Produção | `S`=Sim `N`=Não |
| DHCONSITIMEND | DateTime |  | Última Consulta IMENDES |  |
| SUPDECISAO | String |  | Suporte a Decisão | `N`=Não `S`=Sim |
| CARGAS | String |  | Cargas | `N`=Não `S`=Sim |
| CNPJPREFEITURA | String |  | CNPJ Unidade Gestora |  |
| LIMCURVA_C | Float |  | Limite Curva C |  |
| FOLHAPAGTO | String |  | Folha de Pagamento |  |
| CPFRESP | String |  | CPF do responsável |  |
| DUPLIV | String |  | Gera duplicata do Livro para a Empresa do Parceiro | `S`=Sim `N`=Não |
| LATITUDE | String |  | Latitude |  |
| LONGITUDE | String |  | Longitude |  |
| RNTRC | String |  | RNTRC |  |
| EMPIDENOTAS | String |  | ID NFS-e |  |
| COTM | String |  | COTM - CERTIFICADO DO OPERADOR DE TRANSPORTE MULTIMODAL |  |
| NUREST | String |  | Número do Registro Estadual |  |
| NUMTAF | String |  | Termo de Autorização de Fretamento – TAF |  |
| COREMPRESA | Integer |  | Cor da empresa |  |
| QTDACESSOS | Integer |  | Quantidade de usuários logados simultaneamente |  |
| AD_MAXIMA | String |  | Integra com a Máxima? | `N`=Não `S`=Sim |
| AD_MAXIMA_VENDA_EMB | String |  | Utiliza embalagem na venda? | `N`=Não `S`=Sim |
| PRODUTORRURAL | String |  | Produtor Rural | `N`=Não `S`=Sim |
| LOGOMARCA | Boolean |  | Logomarca |  |
| AD_MOBILIDADE | String |  | Mobilidade | `S`=Sim `N`=Não |
| AD_WMWCODCENCUS | Integer |  | Centro de Custos |  |
| AD_WMWNATOPVEN | Integer |  | Natureza da Op. |  |
| AD_ICMS2022 | Float |  | Saldo de ICMS de 2022 |  |
| AD_PIS2022 | Float |  | Saldo de PIS de 2022 |  |
| AD_COFINS2022 | Float |  | Saldo de Cofins de 2022 |  |
| AD_ICMS2021 | Float |  | Saldo de icms 2021 |  |
| AD_PIS2021 | Float |  | Saldo de pis de 2021 |  |
| AD_COFINS2021 | Float |  | Saldo de cofins 2021 |  |
| AD_TELAGEN | String |  | Telefone Agendamento |  |
| AD_CATEGORIA | String |  | Categoria da empresa | `L`=Loja `C`=Centro de Distribuição |
| CODEMP | Integer |  | Cód. Empresa |  |

## TSIEND — Endereços
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEEND | String |  | Nome |  |
| TIPOENDERECO | String |  | Endereço |  |
| TIPO | String |  | Tipo |  |
| DESCRICAOCORREIO | String |  | Nome do correio |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODLOGRADOURO | String |  | Cód. Logradouro p/ E-social |  |
| ATUNUVERSAO | String |  | Atualizar versão |  |
| CODEND | Integer |  | Cód.Endereço |  |

## TSIERF — Entidades Recentes e Favoritas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PKREGISTRO | String |  | Chave do registro |  |
| DHULTIMOACESSO | DateTime |  | Último acesso |  |
| FAVORITO | String |  | Favorito | `N`=Não `S`=Sim |
| NOMEINSTANCIA | String |  | Nome da Instância |  |
| CODUSU | Integer |  | Usuário |  |

## TSIESTATSERVICO — Estatísticas de chamada de serviço
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTACESSO | Date |  | Dt. Acesso |  |
| HASH | String |  | Hash |  |
| QTD | Integer |  | Qtd. acesso |  |
| RESOURCEID | String |  | ResourceID |  |
| SERVICO | String |  | Nome serviço |  |
| TEMPOTOTAL | Integer |  | Qtd. acesso |  |
| TMAIOR | Integer |  | Maior tempo |  |
| TMEDIO | Integer |  | Tempo médio |  |
| TMENOR | Integer |  | Menor tempo |  |
| CODUSU | Integer |  | Usuário |  |

## TSIETH — Estatisticas da Thread
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| STATUS | String |  | Status |  |
| DHINSERT | Date |  | Dt. Captura |  |
| IDTHREAD | String |  | Thread |  |
| ID | Integer |  | Cod. Estatistica |  |

## TSIEVE — Eventos para Cálculo de Frete
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEVENTO | Integer |  | Cód. Evento |  |
| DESCREVENTO | String |  | Descrição |  |
| GRUPO | String |  | Grupo |  |
| SINAL | Integer |  | Sinal | `1`=Receita `-1`=Despesa `0`=Neutro |
| CODSERV | Integer |  | Serviço |  |

## TSIEVP — Evento Programável
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| NOMEINSTANCIA | String |  | Instância |  |
| RESOURCEID | String |  | Filtro de telas |  |
| TIPO | String |  | Tipo | `SP`=Rotina no Banco de Dados `RJ`=Rotina Java |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CONFIG | C |  | Config |  |
| ORDEM | Integer |  | Ordem |  |
| NUEVENTO | Integer |  | Num. Evento |  |

## TSIEXC — Exceções de Campos Proteção de Dados
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMETAB | String |  | Nome tabela da instância |  |
| CODCLA | Integer |  | Código da classificação da proteção de dados |  |
| NOMECAMPO | String |  | Nome do campo dicionário de dados |  |
| CODUSU | Integer |  | Código do usuário |  |
| TIPOVISU | String |  | Tipo de visualização | `N`=Não Configurado `M`=Mostrar `A`=Anonimizar |

## TSIEXG — Exceções para Proteção de Dados
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCLA | Integer |  | Código da classificação |  |
| CODGRUPO | Integer |  | Código de grupo do usuário |  |
| TIPOVISU | String |  | Tipo de visualização | `M`=Não anonimizar `A`=Anonimizar |

## TSIEXT — Extrator de Dados
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CATEGORIA | String |  | Categoria |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| FORMATO | String |  | Formato | `XML`=XML `XLSX`=Excel (xlsx) `JSON`=JSON `CSV`=CSV |
| DESTINOARQUIVO | String |  | Destino | `REPOSITORY`=Repositório de arquivos `DOWNLOAD`=Download |
| NOMEARQUIVO | String |  | Nome do arquivo |  |
| CODIFICACAO | String |  | Codificação | `UTF-8`=UTF-8 `ISO-8859-1`=ISO-8859-1 `DEFAULT`=Automático |
| COMPACTAR | String |  | Compactar arquivo (.zip)? | `S`=Sim `N`=Não |
| INCLUIRDATA | String |  | Incluir data no nome do arquivo? | `S`=Sim `N`=Não |
| INCLUIRHORA | String |  | Incluir hora no nome do aquivo? | `S`=Sim `N`=Não |
| FONTEDADOS | String |  | Fonte de dados |  |
| CONSULTA | C |  | Consulta |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| TIPGATILHO | String |  | Tipo de gatilho | `I`=Intervalo de tempo `C`=Expressão CRON |
| EXPGATILHO | String |  | Expressão do gatilho |  |
| TIPINTERVALO | String |  | Tipo de intervalo | `M`=Minutos `H`=Horas |
| VLRINTERVALO | Integer |  | Valor |  |
| DHULTEXEC | DateTime |  | Dt. última execução |  |
| TEMPOPROCESSAMENTO | Integer |  | Tempo de processamento (seg.) |  |
| STATUS | String |  | Status |  |
| LOGERRO | C |  | Log de erro |  |
| CODEXTRACAO | Integer |  | Código |  |

## TSIEXU — Exceções para usuários LGPD
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCLA | Integer |  | Código da classificação |  |
| CODUSU | Integer |  | Código usuário |  |
| TIPOVISU | String |  | Tipo de visualização | `N`=Não Configurado `M`=Mostrar `A`=Anonimizar |

## TSIFAT — Faturamento Cruzado
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODPROJ | Integer |  | Código do Projeto |  |
| CODCTABCOINTREC | Integer |  | Conta Baixa Receita |  |
| CODCTABCOINTDESP | Integer |  | Conta Baixa Despesa |  |
| CODTIPOPERREC | Integer |  | Cód.Tipo Operação Baixa Receita |  |
| CODTIPOPERDESP | Integer |  | Cód.Tipo Operação Baixa Despesa |  |
| CODLANCREC | Integer |  | Cód. Hist. Lancto. Receita |  |
| CODLANCDESP | Integer |  | Cód. Hist. Lancto. Despesa |  |
| CODEMP | Integer |  | Código da Empresa |  |

## TSIFCM — Tabela de registro de dispositivos mobile para envio de notificação do sistema para os aplicativos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHREGISTRO | DateTime |  | Dt./Hr. Registro |  |
| PLATAFORMA | String |  | Plataforma | `IOS`=ios `Android`=android |
| CODUSU | Integer |  | Usuário |  |
| CODAPP | String |  | Aplicação |  |
| CODFCM | String |  | Código FCM |  |

## TSIFER — Feriado
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPAIS | Integer |  | País |  |
| CODUF | Integer |  | Estado |  |
| CODCID | Integer |  | Cód. Cidade |  |
| DESCRFERIADO | String |  | Descrição |  |
| DTFERIADO | Date |  | Data do feriado |  |
| OBRIGATORIO | String |  | Obrigatório | `N`=Não `S`=Sim |
| RECORRENTE | String |  | Recorrente | `S`=Sim `N`=Não |
| USANOPONTO | String |  | Usar no Ponto/Pessoal | `S`=Sim `N`=Não |
| NACIONAL | String |  | Tipo | `M`=Municipal `N`=Nacional `E`=Estadual `I`=Internacional |

## TSIFIL — Fila de Impressão de Boleto
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCTABCOINT | Integer |  | Conta |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | Date |  | Data de Alteração |  |
| REMBCO | Integer |  | Último boleto impresso |  |
| REMFINAL | Integer |  | Último boleto no formulário |  |
| TIPOIMPRESSORA | String |  | Tipo Impressora | `3`=RIMA/ITAUTEC `1`=ELEBRA/RIMA `4`=ELGIN `5`=OUTRAS `7`=XEROX LAZER_(+2)_ |
| IMPRESSORA | String |  | Impressora |  |
| NOMEFILA | String |  | Nome Fila |  |

## TSIFLP — Fluxo de Processos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODFLUXO | Integer |  | Código |  |
| FLUXO | C |  | Fluxo |  |

## TSIFMG — Feature Manager Last Status
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CONFIG | C |  | CONFIG |  |
| CHAVE | String |  | CHAVE |  |

## TSIFOP — Filtro para Cálculo de Custo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFORM | Integer |  | Cód. Fórmula |  |
| TABELA | String |  | Tabela |  |
| CODCHAVE | Integer |  | Código |  |
| TIPLANCPLA | String |  | Tip. Lançamento | `A`=Ambos `R`=Crédito `D`=Débito |
| CODEMPPLA | Integer |  | Empresa |  |
| TIPFORM | String |  | Tipo Fórmula |  |

## TSIFOR — Tabela de Formulas Generica
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRFORM | String |  | Descrição da Fórmula |  |
| TIPFORM | String |  | Tipo Fórmula |  |
| TIPDIST | String |  | Tipo distribuição | `A`=Entre parceiros ou cidades `C`=Entre cidades `N`=Não calcular Distancia `P`=Entre parceiros |
| FORMULA | String |  | Fórmula |  |
| FORMULAWEB | String |  | Fórmula Web |  |
| INDCUSTO | Float |  | Perc. do valor a ser usado no custo |  |
| CONSIDERARRATEIO | String |  | Considerar regras de rateio ao apropriar CIP | `S`=Sim `N`=Não |
| CODFORM | Integer |  | Código |  |

## TSIFSN — Repositório de Arquivos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CODGRU | Integer |  | Cód. Gru |  |
| ACESSO | Integer |  | Acesso |  |
| CODPATH | Integer |  | Cód. Caminho |  |
| PATH | String |  | Caminho |  |

## TSIFTD — SI Formatador de Detalhes
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| TIPREG | Integer |  | Tipo do Registro |  |
| MODULO | String |  | Módulo |  |
| CAMPO | String |  | Campo |  |
| TAMANHO | Integer |  | Tamanho |  |
| TIPO | String |  | Tipo |  |
| QTDDEC | Integer |  | Quantidade Decimal |  |
| CODIGO | Integer |  | Código |  |

## TSIFTM — Formatador de Master
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MODULO | String |  | Módulo |  |
| TITULO | String |  | Título |  |
| TAMREGISTRO | Integer |  | Tamanho do Registro |  |
| PROGRAMA | String |  | Programa |  |
| CODBCO | Integer |  | Código do banco |  |
| GRAU | Integer |  | Grau |  |
| CODIGO | Integer |  | Código |  |

## TSIFTP — Controlador de Arquivos enviados
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DIRECAO | String |  | Direção do Arquivo |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ARQUIVO | String |  | Nome do Arquivo |  |

## TSIGBC — Perguntas Aprendidas pela BIA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| NUDSB | Integer |  | Dashboard |  |
| RESOURCEID | String |  | ID da Tela |  |
| PERGUNTA | String |  | Pergunta |  |
| QTDUSO | Integer |  | Quantidade de uso da pergunta |  |
| CODGBC | Integer |  | Código |  |

## TSIGBI — Informações de Gadgets p/ BIA
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUGDG | Integer |  | Gadget |  |
| IDLVL | String |  | ID do Nível |  |
| IDCMP | String |  | ID do Componente |  |
| IDINFOBIA | String |  | ID da Informação |  |
| DESCRGBI | String |  | Descrição |  |
| CAMPOVALOR | String |  | Campo para Valor |  |
| CAMPOAGRUP | String |  | Campo para Agrupamento |  |
| CODGBI | Integer |  | Código |  |

## TSIGBP — Parâmetros de Gadgets p/ BIA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave |  |
| TIPO | String |  | Tipo | `VA`=Vazio `UL`=Usuário da Execução `T`=Texto `NU`=Nulo `NN`=Não Nulo_(+3)_ |
| VLRTXT | String |  | Texto |  |
| VLRDEC | Float |  | Numérico |  |
| VLRDAT | DateTime |  | Data/Hora |  |
| CODGBI | Integer |  | Informação |  |

## TSIGBV — Informações Vinculada à BIA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGBI | Integer |  | Informação |  |
| CODGBC | Integer |  | Pergunta |  |

## TSIGDG — Tabela de Gadgets
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TEMHTML5 | String |  | Possui HTML5 | `N`=Não `S`=Sim |
| TITULO | String |  | Título |  |
| DESCRICAO | String |  | Descrição |  |
| CONFIG | C |  | Configuração (XML) |  |
| THUMBNAIL | Boolean |  | Thumbnail |  |
| CATEGORIA | String |  | Categoria |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODUSUINC | Integer |  | Cód. Usuário Inclusão |  |
| CODUSU | Integer |  | Cód. Usuário Modificação |  |
| DHALTER | DateTime |  | Dt./Hora Modificação |  |
| URLCOMPONENTE | String |  | URL do Componente |  |
| QTDANALISESUTILIZADAS | Integer |  | Quantidade de Análises |  |
| HTML5 | Boolean |  | HTML5 |  |
| LAYOUT | String |  | Layout |  |
| EVOCARD | String |  | Cartão Inteligente |  |
| GDGASSINADO | String |  | Assinado? | `S`=Sim `N`=Não |
| APVNC | String |  | Atualiza Preço pela Nota de compra | `N`=Não `S`=Sim |
| NUGDG | Integer |  | Código |  |

## TSIGEL — Gadget por Evento de Liberação
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EVENTO | Integer |  | Evento Liberação |  |
| NUGDG | Integer |  | Componente BI |  |

## TSIGPU — Grupos Adicionais
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPO | Integer |  | Codigo Grupo |  |
| CODUSU | Integer |  | Codigo Usuario |  |
| DATAFIM | Date |  | Data limite de acesso |  |
| DATAINICIO | Date |  | Data inicial de acesso |  |
| REPASSAR | String |  | Permissão de Repasse do Grupo | `N`=Não `S`=Sim |
| SEQUENCIA | Integer |  | Sequencia de Registros |  |

## TSIGRA — Formatador de Gráficos
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | DateTime |  | Data inicial |  |
| DTFINAL | DateTime |  | Data final |  |
| RESUMO | String |  | Resumo |  |
| FILTROS | String |  | Filtros |  |
| ESCOLHIDOS | String |  | Escolhidos |  |
| ORDEM | String |  | Ordem |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| ORIGEM | Integer |  | Origem |  |
| NOME | String |  | Nome |  |

## TSIGRE — Grupo de Relatórios
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRGRUPOREL | String |  | Descrição |  |
| CODGRUPORELPAI | Integer |  | Cód.Grupo Relatório Pai |  |
| GRAU | Integer |  | Grau |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| CODGRUPOREL | Integer |  | Cód.Grupo Relatório |  |

## TSIGRU — Grupos de usuários
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUNN | Integer |  | Unidade de negócio |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODGRUPO | Integer |  | Código |  |
| EMAIL | String |  | Email |  |
| NOMEGRUPO | String |  | Nome |  |
| USER_NAME | String |  | Nome do Usuário |  |

## TSIGUF — GNRE Unidade Federativa
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODSTGNRE | String |  | Código da Receita (GNRE) |  |
| CODRECDIME | Integer |  | Código da Receita (DIME) |  |
| CODCLSVENCDIME | Integer |  | Código Classe Vencimento (DIME) |  |
| CODDETGNRE | Integer |  | Código Detalhamento Receita (GNRE) |  |
| CODPRODGNRE | Integer |  | Código do Produto (GNRE) |  |
| CODUF | Integer |  | Cód. Unidade Federativa |  |
| PROTOCOLOCONVENIO | String |  | Protocolo/Convênio (GNRE) |  |
| CODCAMPOEXTRAGNRE | Integer |  | Código (Campos Extras GNRE) |  |
| CODCAMPOEXTRAGNRE2 | Integer |  | Código (Campos Extras GNRE 2) |  |
| VALORCAMPOEXTRA | String |  | Valor para Campo Extra GNRE | `null`=Chave NF-e/CT-e e Observação `O`=Observação `C`=Chave NF-e/CT-e `D`=Data de Emissão |
| VLRPERSGNRE | String |  | Valor personalizado GNRE |  |
| VERSAOGNRE | String |  | Versão GNRE | `200`=2.0 `100`=1.0 |
| TIPODOC | Integer |  | Tipo de documento |  |
| CODFCPSTGNRE | Integer |  | Código da Receita (GNRE) p/ FCP ST |  |
| CODRECDIMEFCPST | Integer |  | Código da Receita (DIME) para FCP ST |  |
| CODCLSVENCDIMEFCPST | Integer |  | Código Classe Vencimento (DIME) p/ FCP ST |  |
| TIPOINFO | String |  | Tipo da Informação | `N`=Nota Fiscal (Número da nota) `C`=Chave do documento |
| GERINFCAMPADICGNRE | String |  | Gera Informação dos Campos Adicionais na GNRE | `S`=Sim `N`=Não |
| TIPAPURACAO | String |  | Tipo Apuração | `T`=ICMS ST FCP `S`=ICMS ST `F`=ICMS FCP `D`=ICMS DIFAL `C`=ICMS_(+2)_ |
| CODOBR | Integer |  | Código | `999`=ICMS da substituição tributária pelas saídas para outro Estado `90`=Outras obrigações do ICMS `6`=ICMS resultante da alíquota adicional dos itens incluídos no Fundo de Combate à Pobreza `5`=Antecipação tributária `4`=Antecipação do ICMS da importação_(+4)_ |
| CODGUF | Integer |  | Código GNRE Unidade Federativa |  |

## TSIHAB — TABLE TSIHAB
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODHAB | Integer |  | CodHab |  |
| CAMPOALTER | String |  | Campo alterado |  |
| VLRANT | C |  | Valor anterior |  |
| VLRPOS | C |  | Valor posterior |  |
| DTALTER | DateTime |  | Dt. alteração |  |
| CODUSU | Integer |  | Alterado por |  |
| MOTIVO | String |  | Motivo |  |
| NOMEREGRA | String |  | Nome Regra |  |
| TABELA | String |  | Tabela |  |
| CODRGB | Integer |  | CodRgb |  |

## TSIHCF — Histórico de Cópia de Configuração
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data Criação |  |
| TIPO | String |  | Tipo | `C`=Tela/Filtros `X`=Personalizações/Acessos `A`=Acessos `P`=Personalizações `T`=Tela_(+2)_ |
| ABASEG | String |  | Conf. Segurança | `N`=Não `S`=Sim |
| REMOVEANT | String |  | Remover Conf. Atuais | `S`=Sim `N`=Não |
| CHAVE | String |  | Chave |  |
| SELECAOTELAS | String |  | Seleção de telas |  |
| CONFTOP | String |  | Configurações de Top | `N`=Não `S`=Sim |
| NUNICO | Integer |  | Núm. Único |  |

## TSIHCU — Histórico de Cópia de Configuração Usu
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| NUNICO | Integer |  | NUNICO |  |

## TSIILA — Acessos - Importador de Dados
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODITA | Integer |  | Tabelas de Acessos Importador de Dados |  |
| CODUSU | Integer |  | Usuário |  |
| CODGRUPO | Integer |  | Grupo de Usuário |  |
| CODILA | Integer |  | Id acesso |  |

## TSIILD — Importação legacy detalhe
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLIL | Integer |  | Id importação |  |
| DHEVENTO | DateTime |  | Data evento |  |
| TABELA | String |  | Nome template |  |
| EVENTO | String |  | Evento |  |
| NROLINHA | Integer |  | Número da linha |  |
| IDEXTERNO | String |  | Id do sistema de origem |  |
| DESCRICAO | String |  | Mensagem |  |
| CODILD | Integer |  | Id importação filha |  |

## TSIIMD — Tabela para registro dos campos usados em relatórios
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODUNI | Integer |  | Cód.Unidade do Campo |  |
| DESCRICAO | String |  | Descrição |  |
| TAMANHO | Integer |  | Tamanho |  |
| LINHA | Integer |  | Linha |  |
| COLUNA | Integer |  | Coluna |  |
| SUBLINHADO_BAIXO | String |  | Sublinhado à Baixo |  |
| SUBLINHADO_ALTO | String |  | Sublinhado à Cima |  |
| SUBLINHADO_ESQUERDA | String |  | Sublinhado à Esquerda |  |
| SUBLINHADO_DIREITA | String |  | Sublinhado à Direita |  |
| NROQUERY | Integer |  | Número da Query |  |
| CODREL | Integer |  | Cód.Relatório |  |

## TSIIMF — Tabela para registro dos campos utilizados como filtro em relatórios
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUNI | Integer |  | Cód.Unidade |  |
| NROQUERY | Integer |  | Número da Query |  |
| CODREL | Integer |  | Cód.Relatório |  |

## TSIIMG — Imagem
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FOTO | Boolean |  | Foto |  |
| CODIMG | Integer |  | Cód. Imagem |  |

## TSIIMP — Formatador de Relatórios
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TEMLAYOUTSW | String |  | Usa modelo IReport |  |
| TIPO | String |  | Tipo |  |
| CODREL | Integer |  | Cód.Relatório |  |
| NOME | String |  | Nome |  |
| CODGRUPOREL | Integer |  | Grupo Relatório |  |
| ESCOLHIDOS | String |  | Escolhidos |  |
| ORDEM | String |  | Ordem |  |
| RESUMO | String |  | Resumo |  |
| FILTROS | String |  | Filtros |  |
| CONTASBCO | String |  | Contas Bancárias |  |
| FILTROS2 | String |  | Filtros2 |  |
| PARAMSGEN | String |  | ParamsGen |  |
| LISTA1 | String |  | Lista1 |  |
| LISTA2 | String |  | Lista2 |  |
| LISTA3 | String |  | Lista3 |  |
| LISTA4 | String |  | Lista4 |  |
| ORIENTACAO | String |  | Orientação do relatório |  |
| TIPOFONTE | String |  | Tipo da Fonte |  |
| TAMFONTE | Integer |  | Tamanho da fonte |  |
| PERSONALIZADO | String |  | Personalizado |  |
| LAYOUT | Boolean |  | Layout |  |
| GRAFIC | Boolean |  | Gráfico |  |
| DTINICIAL | DateTime |  | Data inicial |  |
| DTFINAL | DateTime |  | Data final |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| ORIGEM | Integer |  | Origem |  |
| NIVEL | Integer |  | Nivel |  |
| SANKHYA | String |  | Modelo | `N`=Não `S`=Sim |
| OBSERVACAO | String |  | Observação |  |
| LAYOUTSW | Boolean |  | Arquivo IReport |  |
| FASTSERVICE | String |  | Fast Service | `N`=Não `S`=Sim |
| QTDVISUALIZACOES | Integer |  | Qtd. visualizações |  |
| ACESSOCUBO | String |  | Acessos do cubo |  |

## TSIIMQ — Tabela para registro dos campos das quebras em relatórios
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QUEBRA | Integer |  | Quebra |  |
| NROQUERY | Integer |  | Número da Query |  |
| CODUNI | Integer |  | Cód.Unidade |  |
| DESCRICAO | String |  | Descrição |  |
| TAMANHO | Integer |  | Tamanho |  |
| CONDICAO | String |  | Condição |  |
| LINHA | Integer |  | Linha |  |
| COLUNA | Integer |  | Coluna |  |
| ORDEM | Integer |  | Ordem |  |
| SALTAPAGINA | String |  | Salta Pagina? |  |
| REIMPRIMIR | String |  | Reimprimir |  |
| CODREL | Integer |  | Cód.Relatório |  |

## TSIIMS — Informação Modulos Sistema
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | Chave |  |
| VALOR | C |  | Valor |  |
| MODULO | String |  | Módulo |  |

## TSIIMV — Tabela para registro das variáveis utilizadas em relatórios
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEVAR | String |  | Nome da variável |  |
| TIPO | String |  | Tipo |  |
| VALORPADRAO | String |  | Valor Padrão |  |
| CODREL | Integer |  | Cód.Relatório |  |

## TSIIPQ — Instância Pesquisa Inteligente
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INSTANCIA | String |  | Instância |  |
| TABELA | String |  | Tabela |  |
| STATUS | String |  | Status | `W`=Configurado `I`=Inativo `A`=Ativo |
| CODCFG | Integer |  | Código CFG |  |
| QTDLINHASPROC | Integer |  | Número de líneas procesadas |  |
| STACKTRACE | C |  | Stack trace |  |
| DTINIULTSINC | DateTime |  | Dt. Início Últ. Sincronização |  |
| CODINST | Integer |  | Código da Instância |  |

## TSIIRE — Formatador Bancos Ítens
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo do Campo | `null`=Filtro `G`=Inicialização `F`=Alfanumérico com zeros à esquerda `E`=Alfanumérico `D`=Inteiro com brancos à esquerda_(+3)_ |
| CAMPO | String |  | Conteúdo |  |
| TAMANHO | Integer |  | Tamanho |  |
| MODULO | String |  | Módulo |  |
| QTDDEC | Integer |  | Quantidade Decimal |  |
| POSINI | Integer |  | Posição Inicial |  |
| POSFIM | Integer |  | Posição Final |  |
| CODIGO | Integer |  | Código |  |
| SEQUENCIA | Integer |  | Sequência |  |

## TSIIRT — SI Detalhes do Retorno Movimento Bancário com Hierarquia
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NOME | String |  | Nome do Campo |  |
| QTDDEC | Integer |  | Decimais |  |
| POSINI | Integer |  | Início |  |
| POSFIM | Integer |  | Fim |  |
| IDLINHA | String |  | Identificador | `N`=Não `S`=Sim |
| IDVALOR | String |  | Conteúdo p/Identificação |  |
| CODIGO | Integer |  | Código |  |

## TSIITA — Acessos - Importador de Dados Tabelas
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODITA | Integer |  | Id tabela acesso |  |

## TSIIUF — Inscrição de Unidade Federativa
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INSCRICAO | String |  | Inscrição Estadual |  |
| CODEMP | Integer |  | Empresa |  |
| DTINIVALIDADE | Date |  | Data Início Validade |  |
| DTFIMVALIDADE | Date |  | Data Fim Validade |  |
| CODUF | Integer |  | Cod. UF |  |

## TSIJAR — Arquivo Módulo (JAR)
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODJAR | Integer |  | Identificador |  |
| DESCRICAO | String |  | Nome do Arquivo |  |
| ARQUIVO | Boolean |  | Conteúdo |  |
| AD_DTINCLUSAO | DateTime |  | Data de Inclusão |  |
| AD_DTINCLUSAO2 | DateTime |  | Data de Inclusão2 |  |
| AD_USUARIO | Integer |  | Usuário Inclusão |  |
| AD_USUARIO2 | Integer |  | Usuário Inclusão2 |  |
| CODMODULO | Integer |  | Módulo |  |

## TSIJPR — Trabalho de impressão
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| JOBSTATUS | String |  | Status |  |
| DESCRIPTION | String |  | Descrição |  |
| COPIES | Integer |  | Cópias |  |
| TIPODOC | String |  | Tipo de documento |  |
| IDDOC | String |  | Número Documento |  |
| MIMETYPE | String |  | Tipo de arquivo |  |
| ORIGINALPRINTER | String |  | Nome da impressora |  |
| DHINC | DateTime |  | Dt. Inclusão |  |
| MSGERRO | String |  | Mensagem de erro |  |
| DHULTENV | DateTime |  | Dt. Último envio |  |
| NUMTENTATIVAS | Integer |  | Número de tentativas |  |
| PRINTERURI | String |  | Endereço da impressora |  |
| PRINTSERVERURI | String |  | Endereço do servidor de impressão |  |
| FILENAME | String |  | Arquivo |  |
| CODUSU | Integer |  | Usuário |  |
| JOBID | String |  | Código no Servidor de impressão |  |
| IDGRUPOJOB | String |  | Transação |  |
| NUJPR | Integer |  | Código |  |

## TSIJPS — Status de trabalho de impressão
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRIPTION | String |  | Status |  |
| JOBSTATUS | String |  | Código |  |

## TSIKIT — Configuração de Kit
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCONFKIT | String |  | Descrição |  |
| CALCIMPKIT | String |  | Calcula imposto do componente | `S`=Sim `N`=Não |
| SOMACUSTOCOMPKIT | String |  | Soma custo do componente ao kit | `N`=Não `S`=Sim |
| SOMAPRECOCOMPKIT | String |  | Soma preço do componente ao kit | `S`=Sim `N`=Não |
| DISTRIBUIKITCOMP | String |  | Distribuir preço do kit nos componentes | `S`=Sim `N`=Não |
| DISTDESCKITCOMP | String |  | Distribuir desconto do kit nos componentes | `N`=Não `S`=Sim |
| UTILPRECOABACOMP | String |  | Utiliza preço sugerido na aba 'Componentes' | `S`=Sim `N`=Não |
| EXPLODCOMP | String |  | Explodir componentes na grade de matéria prima da central | `N`=Não `S`=Sim |
| SOMAICMSCOMPKIT | String |  | Soma ICMS do componente ao kit (Art. 42 do RICMS/2002-MG) | `S`=Sim `N`=Não |
| FAKITESTCOMP | String |  | Faturar apenas KIT com estoque de todos os componentes | `N`=Não `S`=Sim |
| CODCONFKIT | Integer |  | Código |  |

## TSIKPC — Keep Connection (mantenha logado)
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| KEEPID | String |  | KEEPID |  |
| CODUSU | Integer |  | CODUSU |  |
| INTERNO | String |  | INTERNO |  |
| DTVALIDADE | DateTime |  | DTVALIDADE |  |
| APARELHO | String |  | APARELHO |  |
| APARELHOID | String |  | APARELHOID |  |
| APPNAME | String |  | APPNAME |  |
| APS | String |  | APS |  |
| NUKEEP | Integer |  | NUKEEP |  |

## TSILAC — Log de Acessos
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| USUARIO | String |  | Usuário |  |
| HOSTNAME | String |  | Hostname |  |
| SID | Integer |  | Sid |  |
| IP | String |  | IP |  |
| TERMINAL | String |  | Terminal |  |
| MODULO | String |  | Módulo |  |
| CODPROD | Integer |  | Cód.Produto |  |
| SUCESSO | String |  | SUCESSO |  |
| DHACESSO | DateTime |  | Data e Hora |  |

## TSILBA — Liberação de acesso por PC
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PCSOLIC | String |  | Local Solicitação |  |
| DTSOLIC | DateTime |  | Data Solicitação |  |
| CODUSUSOLIC | Integer |  | Cód. Usuário Solicitante |  |
| CODUSULIBER | Integer |  | Cód. Usuário Liberador |  |
| DTLIBER | Date |  | Data Liberação |  |
| OBSERVACAO | String |  | Observação |  |
| STATUS | String |  | Status Solicitação | `P`=Pendente `D`=Denegado `L`=Liberado |
| DTVALIDADE | Date |  | Validade Liberação |  |
| IPLOCAL | String |  | IP Local |  |
| IPREQUISICAO | String |  | IP Requisição |  |
| MACREQUISICAO | String |  | MAC |  |
| NOMEPCSOLIC | String |  | Hostname Solicitação |  |
| NUSOLIC | Integer |  | Núm. Solicitação |  |

## TSILBF — Liberação de Filtros
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TELA | String |  | Tela |  |
| DESCRICAO | String |  | Descrição |  |
| EXPRESSAO | String |  | Expressão |  |
| NOMEFILTRO | String |  | Nome do Filtro |  |
| DTCRIACAO | DateTime |  | Data de Criação |  |
| AUTOR | Integer |  | Autor |  |
| STATUS | String |  | Status | `A`=Aprovado `P`=Pendente `R`=Reprovado `E`=Excluído |
| MOTIVO | String |  | Motivo na Reprovação |  |
| APROVADOPOR | Integer |  | Aprovado por |  |
| DTLIBERACAO | DateTime |  | Data de Liberação |  |
| REPROVADOPOR | Integer |  | Reprovado por |  |
| DTREPROVACAO | DateTime |  | Data de Reprovação |  |
| CHAVE | String |  | CHAVE |  |
| CODFILTRO | Integer |  | Cod. Filtro |  |
| CODSOL | Integer |  | Cód. Solicitação |  |

## TSILBO — Limite de liberação de bonificação
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| DTINICIAL | Date |  | Data Inicial |  |
| DTFINAL | Date |  | Data Final |  |
| VLRLIMITE | Float |  | Limite Bonificação |  |
| EVENTO | Integer |  | Evento |  |
| NULBO | Integer |  | Número liberação de bonificação |  |

## TSILIB — Liberacao de Limites
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VLRLIMITE | Float |  | Valor limite |  |
| VLRTOTAL | Float |  | Valor Total |  |
| VLRATUAL | Float |  | Valor atual |  |
| CODUSULIB | Integer |  | Usuário Liberador |  |
| CODUSUSOLICIT | Integer |  | Usuário Solicitante |  |
| OBSERVACAO | String |  | Observação solicitante |  |
| NUCHAVE | Integer |  | Número chave |  |
| TABELA | String |  | Tabela |  |
| SEQUENCIA | Integer |  | Sequência |  |
| DHLIB | DateTime |  | Data e hora da liberação |  |
| PERCANTERIOR | Float |  | Percentual Anterior |  |
| VLRANTERIOR | Float |  | Valor Anterior |  |
| NULBO | Integer |  | Número do limite de bonificação |  |
| DHSOLICIT | DateTime |  | Data e hora da solicitação |  |
| VLRLIBERADO | Float |  | Valor liberado |  |
| OBSLIB | String |  | Observação liberador |  |
| PERCLIMITE | Float |  | Percentual limite |  |
| CODMETA | Integer |  | Meta |  |
| OBSCOMPL | String |  | Observação Complementar |  |
| REPROVADO | String |  | Reprovado | `S`=Sim `N`=Não |
| SUPLEMENTO | String |  | Suplemento |  |
| ANTECIPACAO | String |  | Antecipação |  |
| TRANSF | String |  | Transferência |  |
| SEQCASCATA | Integer |  | Seq. Cascata |  |
| VLRDESDOB | Float |  | Valor Desdobramento |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| CODTIPOPER | Integer |  | Tipo Operação |  |
| ORDEM | Integer |  | Ordem |  |
| NUCLL | Integer |  | Número Laudo Classificação Produto |  |
| NURNG | Integer |  | Regra de negócio |  |
| EVENTO | Integer |  | Evento |  |

## TSILIG — Ligação entre Instâncias
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEINSTDEST | String |  | NOMEINSTDEST |  |
| CODUSU | Integer |  | CODUSU |  |
| DHALTER | DateTime |  | DHALTER |  |
| EXPRESSAO | String |  | Expressão da condição de filtro |  |
| NOMEINSTORIG | String |  | NOMEINSTORIG |  |
| RELATIONNAME | String |  | Nome da Relação das Instâncias |  |

## TSILIL — Log importação legacy
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHEVENTO | DateTime |  | Data importação |  |
| NOMEARQUIVO | String |  | Arquivo processado |  |
| EVENTO | String |  | Evento |  |
| TOTREG | Integer |  | Total de registros |  |
| TOTREGPROC | Integer |  | Registros inseridos |  |
| TOTATUALIZADO | Integer |  | Registros atualizados |  |
| TOTREJEITADO | Integer |  | Registros rejeitados |  |
| TEMPOTOTAL | String |  | Tempo de execução |  |
| ATUALIZAR | String |  | Atualizar registros existentes |  |
| REGRAS | String |  | Validação de regras de negócio |  |
| LOGFINAL | String |  | Processo de importação |  |
| REGRAENDERECO | String |  | Regra de Importação de Endereço |  |
| CODUSU | Integer |  | Usuário |  |
| CODLIL | Integer |  | Id importação |  |

## TSILIM — Limites
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRU | Integer |  | Cód.Grupo |  |
| EVENTO | Integer |  | Evento |  |
| TIPOEVENTO | String |  | Tipo evento | `V`=Valor `P`=Percentual |
| LIMITE | Float |  | Limite |  |
| TIPOLIMITE | String |  | Tipo limite | `M`=Mensal `E`=Evento |
| ENVIAREMAIL | String |  | Enviar E-Mail | `N`=Não `S`=Sim |
| ENVIARSMS | String |  | Enviar SMS | `N`=Não `S`=Sim |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSILOG — Log do Sistema
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHEVENTO | DateTime |  | Data e Hora do Evento |  |
| DESCRICAO | String |  | Descrição do Evento |  |
| COMPUTADOR | String |  | Nome do Computador |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSILOGCJM — Log de cálculo de juro e multa
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHPROCESSAMENTO | DateTime |  | Data/hora do processamento |  |
| MENSAGEM | String |  | Título do erro |  |
| STACKTRACE | C |  | Informações do erro |  |
| NUFIN | Integer |  | Nro. Único |  |

## TSILOGFTC — Log de fatura do cartão
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Cód. Parceiro |  |
| DHFAT | DateTime |  | Data/hora da fatura |  |
| ERROFAT | C |  | Mensagem da geração da fatura do cartão |  |
| NULOG | Integer |  | Nro único do log |  |

## TSILOR — Limites Orçamentário
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| VALOR | Float |  | Valor excedido |  |
| SUPLEMENTACAO | String |  | Permite Suplementação | `N`=Não `S`=Sim |
| TIPOLIMITE | String |  | Tipo limite | `M`=Mensal `E`=Evento |
| ANTECIPACAO | String |  | Permite Antecipação | `S`=Sim `N`=Não |
| TRANSFERENCIA | String |  | Permite Transferência | `N`=Não `S`=Sim |
| CODCENCUS | Integer |  | Centro Resultado |  |

## TSILPD — Log de Proteção de Dados.
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOLOG | Integer |  | Tipo do Log |  |
| CODUSU | Integer |  | Usuário |  |
| DESCRICAO | String |  | Descrição do Evento |  |
| DHREGISTRO | Date |  | DataHora Registro |  |
| ID | Integer |  | Codigo Registro |  |

## TSILRE — Log de Relatórios
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CLASSNAME | String |  | Classe do Formulário |  |
| DTALTER | DateTime |  | Data da alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TIPO | String |  | Tipo |  |
| CONSULTA | String |  | Consulta |  |
| IMPRESSORA | String |  | Impressora |  |
| NUREL | Integer |  | Número do Relatório |  |

## TSIMAP — Api Monitor
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| HASH | String |  | Hash |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DATA | Date |  | Data |  |
| PRIMEIROLOGIN | DateTime |  | Primeiro Login |  |
| ULTIMOLOGIN | DateTime |  | Ultimo Login |  |
| QTDLOGIN | Integer |  | Qtd. Login |  |
| IP | String |  | Endereço IP |  |
| ORIGEM | String |  | Origem | `G`=API Gateway `D`=API Direta `A`=App `S`=App Sankhya |
| IDENTIFICADOR | String |  | Identificador |  |
| USERAGENT | String |  | UserAgent |  |

## TSIMAPS — Api Monitor Serviço
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| HASHMASTER | String |  | Hash Pai |  |
| HASH | String |  | Hash |  |
| SERVICO | String |  | Serviço |  |
| DETALHE | String |  | Detalhe |  |
| METODO | String |  | Método |  |
| TEMPOTOTAL | Integer |  | Tempo Total |  |
| TEMPOMEDIO | Integer |  | Tempo Médio |  |
| QTD | Integer |  | Quantidade |  |
| QTDERROS | Integer |  | Qtd. Erros |  |

## TSIMASANO — Máscara de anonimização
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCMASC | String |  | Descrição da máscara de aninimização |  |
| TIPOCAMPO | String |  | Tipo do campo |  |
| CODUSUCRIAC | Integer |  | Código usuário criação |  |
| DTCRIAC | DateTime |  | Data criação |  |
| CODUSUALTER | Integer |  | Código usuário alteração |  |
| DTALTER | DateTime |  | Data alteração |  |
| CODMASANO | Integer |  | Código máscara e anonimização |  |

## TSIMEM — Modelo e-mail
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPO | String |  | Tipo de modelo |  |
| CODSMTP | Integer |  | Conta SMTP |  |
| ASSUNTO | String |  | Assunto |  |
| CONTEUDO | C |  | Conteúdo |  |
| RESPONDERPARA | String |  | Responder para |  |
| CODUSUREMET | Integer |  | Cód. Usuário Remetente |  |
| CODMODELO | Integer |  | Código |  |

## TSIMOD — Módulo Adicional
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RESOURCEID | String |  | Identificador |  |
| DESCRMODULO | String |  | Descrição |  |
| AD_DTALTER | DateTime |  | Data de alteracao |  |
| AD_USUALTER | Integer |  | Cod Usuario Alteracao |  |
| CODMODULO | Integer |  | Módulo |  |

## TSIMOE — Moedas
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEMOEDA | String |  | Nome |  |
| TIPMOEDA | String |  | Tipo | `I`=Índice `V`=Valor |
| CODINTMOEDA | Integer |  | Código tabela internacional |  |
| CODTABBCB | Integer |  | Cód. tabela BCB |  |
| TIPCALC | String |  | Tipo do Acúmulo | `S`=Simples `C`=Composto |
| TIPOTAXA | String |  | Tipo de taxa | `V`=Venda `C`=Compra |
| CODMOEDA | Integer |  | Código |  |

## TSIMPA — Manutenção Programada
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| DHPARADA | DateTime |  | Data/Hora da Parada |  |
| HRINDISP | Integer |  | Tempo indisponivel |  |
| MSGMP | String |  | Mensagem |  |
| NUMPA | Integer |  | Nro Parada |  |

## TSINGG — Notificação gaps de gestão
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODFILA | Integer |  | Código da fila |  |
| ROTINA | String |  | Rotina |  |
| IGNORARPROXIMAS | String |  | Ignorar proximo aviso |  |
| NUAVISO | Integer |  | Número do aviso |  |

## TSIOBC — Ocorrências Bancárias
Campos: 30

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODOCORRENCIA | String |  | Cód.Ocorrência |  |
| DESCRICAO | String |  | Descrição |  |
| REPORTAR | String |  | Reportar | `S`=Sim `N`=Não |
| INTERROMPER | String |  | Interromper | `N`=Não `S`=Sim |
| BAIXAR | String |  | Baixar | `S`=Sim `N`=Não |
| CONCILIAR | String |  | Conciliar | `N`=Não `S`=Sim |
| REGISTRARNOSSONUM | String |  | Registrar Nosso Número | `S`=Sim `N`=Não |
| REGISTRARLOG | String |  | Registrar Log | `N`=Não `S`=Sim |
| BAIXAPARCIAL | String |  | Baixa Parcial | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODPARC | Integer |  | Cód.Parceiro |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODTIPTIT | Integer |  | Tipo de título |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| INSERIR | String |  | Inserir | `S`=Sim `N`=Não |
| ALTERAR | String |  | Alterar | `S`=Sim `N`=Não |
| TRATAROCORRENCIA | String |  | Tratar Ocorrência | `N`=Não `S`=Sim |
| CODOCOREMESSA | String |  | Cód.Ocorrência Remessa |  |
| ATUALIZACAOREMESSA | String |  | Atualização Ocorrência Remessa | `R`=Rejeitada `P`=Processada |
| CODCTABCOINT | Integer |  | Conta Bancária |  |
| CODBCO | Integer |  | Banco |  |
| REMOVERMONCOB | String |  | Remover título do monitoramento de cobrança | `S`=Sim `N`=Não |
| CAMPOSAJUSTAR | C |  | Campos a serem ajustados |  |
| REGISTRARQRCODE | String |  | Gravar QR Code Pix | `S`=Sim `N`=Não |
| CODIGO | Integer |  | Codigo |  |
| CODMODELO | Integer |  | Código Modelo |  |
| ENVPIXEMAIL | String |  | Enviar E-mail PIX | `S`=Sim `N`=Não |
| NURFE | Integer |  | Número |  |

## TSIOBCLOG — Log de ocorrências bancárias
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NROLINHA | Integer |  | Nro Linha |  |
| NUFIN | Integer |  | Nro Único |  |
| NOSSONUM | String |  | Nosso Nro |  |
| CARTEIRA | Integer |  | Carteira |  |
| CODCTABCO | String |  | Cta. Bancária |  |
| CODAGE | String |  | Agência |  |
| CODBCO | Integer |  | Banco |  |
| CODMSGERRO | Integer |  | Status da Mensagem | `7`=E007 - ENTRADA REJEITADA `37`=E037 - ERRO NO CORRESPONDENTE BANCÁRIO `36`=E036 - ERRO NA STORED PROCEDURE `35`=E035 - ERRO NA BAIXA `34`=E034 - ERRO AO CONCILIAR TÍTULO_(+38)_ |
| DTCREDITO | DateTime |  | Dt. Crédito |  |
| DTBAIXA | DateTime |  | Dt. Baixa |  |
| DTVENCIMENTO | DateTime |  | Dt. Vencimento |  |
| VLRBAIXA | Float |  | Vlr. Baixa |  |
| VLRTITULO | Float |  | Vlr. Título |  |
| VLRDESC | Float |  | Vlr. Desc. |  |
| VLRMULTA | Float |  | Vlr. Multa |  |
| VLRJURO | Float |  | Vlr. Juro |  |
| VLRTXADM | Float |  | Vlr. Adm. |  |
| VLRVENDOR | Float |  | Vlr. Vendor |  |
| CODUSU | Integer |  | Usuário |  |
| DATOCORRENCIA | DateTime |  | Dt. Ocorrência |  |
| NOMEARQ | String |  | Nome do Arquivo |  |
| ALTERADO | String |  | Alterado |  |
| INTERROMPIDO | String |  | Interrompido |  |
| CONCILIADO | String |  | Conciliado |  |
| DESCRICAO | String |  | Desc. Ocorrência |  |
| CODOCORRENCIA | String |  | Ocorrência |  |
| TRATAROCORRENCIA | String |  | Tratar Ocorrência |  |
| REGISTRADONOSSONUM | String |  | Registra Nosso Num |  |
| REPORTADO | String |  | Reportado |  |
| BAIXADO | String |  | Baixado |  |
| OBSERVACAO | String |  | Detalhe da Mensagem |  |
| NUOBCLOG | Integer |  | Nro Único Proc/Prev. |  |
| TIPO | String |  | Tipo | `O`=Processado `E`=Prévia |

## TSIOEM — Tarefas OEM
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| APPID | String |  | App ID |  |
| SEQUENCIA | Integer |  | Sequencia Exec |  |
| CODPARC | Integer |  | Parceiro |  |
| URLDOWNLOAD | String |  | URL Download |  |
| DHEXEC | DateTime |  | D/H Execução |  |
| STATUS | String |  | Status | `F`=Falha `S`=Atualizado `N`=Não Atualizado |
| MENSAGEM | C |  | Mensagem |  |

## TSIOPM — Configuração de Opções Longas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo |  |
| CODUSU | Integer |  | Código Usuário] |  |
| HRINIT | Text |  | Hora Inicial Do Monitoramento |  |
| HRFIN | Text |  | Hora Final Do Monitoramento |  |
| CONFIGS | C |  | Configurações |  |
| CODCFG | Integer |  | Código CFG |  |

## TSIPAH — Log de parâmetros alterados pelo HUB
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OLDVALUE | String |  | Valor antigo do parâmetro |  |
| NEWVALUE | String |  | Novo valor do parâmetro |  |
| DATA | Date |  | Data de alteração |  |
| ID | Integer |  | Código |  |
| CHAVE | String |  | Chave do parâmetro |  |

## TSIPAI — Países
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ABREVIATURA | String |  | Abreviatura |  |
| CODPAISFIS | Integer |  | País Domicílio Fiscal |  |
| TIMNACIONALIDAD | String |  | Nacionalidade |  |
| CODPAIS | Integer |  | Código do país |  |

## TSIPAR — Parâmetros
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TIPO | String |  | Tipo |  |
| MODULO | String |  | Módulo do Sistema |  |
| CLASSE | String |  | Classe |  |
| ABA | String |  | Aba |  |
| LOGICO | String |  | Lógico |  |
| INTEIRO | Integer |  | Inteiro |  |
| NUMDEC | Float |  | Número decimal |  |
| DATA | DateTime |  | Data |  |
| TEXTO | String |  | Texto |  |
| CHAVE | String |  | Chave |  |

## TSIPER — Permissão de acesso
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PERMISSAO | String |  | Permissão |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TIPOACESSO | Integer |  | Tipo de acesso |  |
| CODGRUPO | Integer |  | Cód.Grupo |  |

## TSIPNZ — TABLE TSIPNZ
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | CODUSU |  |
| CODSANKHYAID | Integer |  | CODSANKHYAID |  |
| DEVID | String |  | DEVID |  |
| DTCRIACAO | DateTime |  | DTCRIACAO |  |
| DTALTERACAO | DateTime |  | DTALTERACAO |  |
| TIPPERSONALIZACAO | String |  | TIPPERSONALIZACAO | `RE`=Relatórios Formatados `RC`=Layout Processamento Arquivo `PN`=Processo de Negócio `PC`=Processamento Cartão `MJ`=Módulo Java_(+11)_ |
| IDPERSONALIZACAO | String |  | IDPERSONALIZACAO |  |
| NOMEPERSONALIZACAO | String |  | NOMEPERSONALIZACAO |  |
| COMPANYID | Integer |  | COMPANYID |  |
| CODSEQ | Integer |  | CODSEQ |  |

## TSIPOM — Pedido Offline Modelo
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único do Pedido |  |
| DESCRNOTA | String |  | Descrição do Modelo |  |
| PADRAO | String |  | Padrão | `S`=Sim `N`=Não |
| CODCONFIG | Integer |  | Cód. Config |  |

## TSIPRN — Impressoras
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| PRINTERURI | String |  | Endereço |  |
| ALIASLOCAL | String |  | Nome Local |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| STATUS | String |  | Status | `PROCESSING`=Disponível `UNKNOWN`=Indisponível `STOPPED`=Indisponível `IDLE`=Disponível |
| DHSTATUS | DateTime |  | Data de Verificação |  |
| NUSVP | Integer |  | Servidor de impressão |  |
| NUPRINTER | Integer |  | Código |  |

## TSIPRP — Nomes de impressoras
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEIMPLOCAL | String |  | Nome local da impressora |  |
| CAMINHOSPS | String |  | Caminho da impressora no servidor de impressão |  |
| NUNIP | Integer |  | Código |  |

## TSIPSQ — Pesquisa Inteligente
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| URI | String |  | URL |  |
| PORTA | Integer |  | Porta |  |
| USUARIO | String |  | Usuário |  |
| SENHA | String |  | Senha |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CRON | String |  | Expressão de Gatilho |  |
| STATUS | String |  | Status | `W`=Configurado `P`=Parcialmente Ativo `I`=Inativo `A`=Ativo |
| CODCFG | Integer |  | Código CFG |  |

## TSIPSQFILA — Log de Modificações
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | String |  | CHAVE |  |
| TIPO | String |  | TIPO |  |
| DHALTER | DateTime |  | Data e hora alteração |  |
| CONTROLE | String |  | Controle |  |
| NOMEINSTANCIA | String |  | Nome da Instância |  |

## TSIPUE — Pefil Usuario EVO
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PERFIL | String |  | Tipo de Perfil |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSIPVI — Personalizações de Usuários Internalização Store
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| CONFIG | Integer |  | CONFIG |  |

## TSIRAV — Respostas de Avisos de Sistema
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | CODUSU |  |
| NUAVISO | Integer |  | NUAVISO |  |
| NURESPAVISO | Integer |  | NURESPAVISO |  |

## TSIREG — Regiões
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEREG | String |  | Nome |  |
| ATIVA | String |  | Ativa | `N`=Não `S`=Sim |
| ANALITICA | String |  | Analítica | `N`=Não `S`=Sim |
| CODTAB | Integer |  | Tabela Preço |  |
| CODTABMIN | Integer |  | Tabela Preço Mínimo |  |
| FRETEMIN | Float |  | Frete mínimo |  |
| PERCCUSVAR | Float |  | % Custo Variável |  |
| PERCDESCFOB | Float |  | % Desc. FOB |  |
| CODVEND | Integer |  | Vendedor |  |
| PERCADICIONAL | Float |  | Perc. Adicional |  |
| PERCPREMIO | Float |  | Perc. Prêmio |  |
| GERARRECEITA | String |  | Tipo | `S`=Adiantamento `N`=Ajuda de Custo |
| VLRANTECIPACAO | Float |  | Valor |  |
| GRAU | Integer |  | Grau |  |
| CODREGPAI | Integer |  | Cód.Região Pai |  |
| SEMANA1_DOM | Float |  | % Domingo |  |
| SEMANA1_SEG | Float |  | % Segunda |  |
| SEMANA1_TER | Float |  | % Terça |  |
| SEMANA1_QUA | Float |  | % Quarta |  |
| SEMANA1_QUI | Float |  | % Quinta |  |
| SEMANA1_SEX | Float |  | % Sexta |  |
| SEMANA1_SAB | Float |  | % Sábado |  |
| SEMANA2_DOM | Float |  | % Domingo |  |
| SEMANA2_SEG | Float |  | % Segunda |  |
| SEMANA2_TER | Float |  | % Terça |  |
| SEMANA2_QUA | Float |  | % Quarta |  |
| SEMANA2_QUI | Float |  | % Quinta |  |
| SEMANA2_SEX | Float |  | % Sexta |  |
| SEMANA2_SAB | Float |  | % Sábado |  |
| VENDAMIN | Float |  | Venda Mínima |  |
| AD_MAXIMA | String |  | Integra com a Máxima? | `N`=Não `S`=Sim |
| CODREG | Integer |  | Cód.Região |  |

## TSIREGMOD — Registro de Modificações
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INSTANCIA | String |  | Instância |  |
| TABELA | String |  | Tabela |  |
| DHALTER | DateTime |  | Data/hora |  |
| CHAVE | String |  | Chave |  |
| TIPO | String |  | Tipo | `U`=Edição `I`=Inserção `D`=Remoção |
| USERNAME | String |  | Nome Usuário |  |
| CODUSU | Integer |  | Código Usuário |  |
| CONTEUDO | String |  | Conteúdo |  |
| NOMECAT | String |  | Nome da Instância |  |

## TSIREM — Formatador de Remessa
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MODULO | String |  | Módulo |  |
| TITULO | String |  | Título |  |
| TAMREGISTRO | Integer |  | Tamanho do Registro |  |
| CODPAI | Integer |  | Cód.Formatador pai |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Detalhe | `N`=Não `S`=Sim |
| GRAU | Integer |  | Grau |  |
| FILTRO | String |  | Filtro |  |
| COMGROUPBY | String |  | Com Group By |  |
| COMHAVING | String |  | Com Having |  |
| NOMEARQ | String |  | Nome do arquivo |  |
| COMSELECT | String |  | Com Select |  |
| COMORDERBY | String |  | Com Order By |  |
| UTILIZASEQALT | String |  | Utiliza Sequência Alternativa | `S`=Sim `N`=Não |
| UTILIZASEQINFO | String |  | Utiliza Sequência Informada | `N`=Não `S`=Sim |
| SEQINFO | Integer |  | Sequência Informada |  |
| ORDENAR | String |  | Ordenar | `N`=Não `S`=Sim |
| FICHA | String |  | Primeira coluna somente p/ ordenação | `N`=Não `S`=Sim |
| ARQPORLINHA | String |  | Gerar um arquivo p/cada linha | `N`=Não `S`=Sim |
| ARQPORLAYOUTDETALHE | String |  | Gerar um arquivo p/cada detalhe do layout | `S`=Sim `N`=Não |
| INICARQREM | String |  | Iniciais do arquivo p/ nome automático |  |
| CONF | String |  | Configuração |  |
| CONSULTASQLLOTE | String |  | Consulta SQL |  |
| CODIGO | Integer |  | Código |  |

## TSIRET — Retorno Movimento Bancário com Hierarquia
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TITULO | String |  | Título do Layout |  |
| SP_CHAMADA | String |  | Stored Chamada |  |
| CODPAI | Integer |  | Cód.Pai |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| GRAU | Integer |  | Grau |  |
| USASQLNUFIN | String |  | Usa SQL Para Número Único | `N`=Não `S`=Sim |
| CONCEXTBANC | String |  | Conciliação Extrato Bancário | `S`=Sim `N`=Não |
| CONFIGTAXAADMIN | String |  | Taxa Administrativa | `D`=Destacar `-`=Subtrair do valor recebido `+`=Somar ao valor recebido `N`=Nada a fazer `G`=Considerar configuração global |
| CODIGO | Integer |  | Cód.Layout |  |

## TSIRFA — Arquivos de Relatórios
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NOME | String |  | NOME |  |
| ARQUIVO | C |  | ARQUIVO |  |
| ARQUIVOBIN | Boolean |  | Arquivo em bytes |  |
| NURFE | Integer |  | NURFE |  |

## TSIRFE — Relatórios
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CATEGORIA | String |  | Categoria |  |
| DHALTER | DateTime |  | Data/Hora alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUINSTANCIA | Integer |  | Instância |  |
| IDTELA | String |  | IDTELA |  |
| NURFEDEPENDENTE | Integer |  | Nro relatório dependente |  |
| FORMATO | String |  | Formato de arquivo | `P`=PDF `X`=Excel (.xls) `W`=Word (.docx) `E`=Excel (.xlsx) |
| DSNAME | String |  | Fonte de Dados |  |
| PREFIXOANEXO | String |  | Nome do anexo para e-mail |  |
| TIPO | String |  | Tipo |  |
| NURFE | Integer |  | Número |  |
| NOMEIMPRESSORA | String |  | Impressora |  |
| EXPFILTROINSTANCIA | String |  | Mostrar na Tela/Instância quando |  |
| CONFIG | C |  | Configuração |  |

## TSIRGB — TABLE TSIRGB
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TABELA | String |  | Tabela Relacionada |  |
| NOMEREGRA | String |  | Nome Regra |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| GRUPOREGRA | String |  | Grupo |  |
| STATUSPUBLI | String |  | Status Publicação | `1`=Erro na Publicação `0`=Publicado |
| DESCRREGRA | String |  | Descrição |  |
| INSERIR | String |  | Insert | `S`=Sim `N`=Não |
| ATUALIZAR | String |  | Update | `S`=Sim `N`=Não |
| DELETAR | String |  | Delete | `S`=Sim `N`=Não |
| MOMENTOEXEC | String |  | Momento de Execução | `B`=Before `A`=After |
| TIPOREGRA | String |  | Tipo | `P`=Personalizada `N`=Nativa |
| ABRANGENCIA | String |  | Abrangência |  |
| DOCUMENTACAO | String |  | Documentação |  |
| ORDEM | Integer |  | ORDEM |  |
| REGRA | C |  | Regra |  |
| PUBLICADO | String |  | Publicado |  |
| DTULTPUBLI | DateTime |  | Dt. Última Publicação |  |
| CODUSU | Integer |  | Criado por |  |
| CODRGB | Integer |  | CODRGB |  |

## TSIRHI — Relatórios Hierárquicos
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROGRAMA | String |  | Programa |  |
| CODCAMPO | Integer |  | Cód.Campo |  |
| CODCAMPOPAI | Integer |  | Cód.Campo Pai |  |
| SOHIERARQUIA | String |  | Só Hierarquia | `N`=Não `S`=Sim |
| DESCRICAO | String |  | Descrição |  |
| TAMANHO | Integer |  | Tamanho |  |
| TIPO | String |  | Tipo | `L`=Lista `I`=Inteiro `B`=Imagem `$`=Dinheiro `T`=Data/Hora_(+5)_ |
| ALINHAMENTO | Integer |  | Alinhamento | `2`=Centro `1`=Direita `0`=Esquerda |
| TOTALIZA | String |  | Totaliza/Filtro | `X`=Não filtra `N`=Não Totaliza `S`=Totaliza |
| MASCARA | String |  | Máscara |  |
| EXPRESSAO | String |  | Expressão |  |
| TABELAS | String |  | Tabelas |  |
| LIGACAO | String |  | Ligação |  |
| SANKHYA | String |  | Modelo Sankhya | `N`=Não `S`=Sim |
| ZERARNAQUEBRA | String |  | Zerar na quebra | `N`=Não `S`=Sim |
| CODUNI | Integer |  | Cód.Único |  |

## TSIRIM — Roteamento de impressão
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMESAIDA | String |  | Nome de saída |  |
| TIPOCODIGO | String |  | TIPOCODIGO |  |
| CODIGO | Integer |  | CODIGO |  |
| NOMEENTRADA | String |  | Nome de entrada |  |

## TSIRLG — log acessos
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQACESSO | Integer |  | Sessão |  |
| LOGIN | DateTime |  | Dh. Entrada |  |
| LOGOUT | DateTime |  | Dh. Saída |  |
| IP | String |  | Endereço IP |  |
| AGENTE | String |  | Navegador |  |
| EVENTO | String |  | Evento | `L`=Login `F`=Falha de login `D`=Desbloqueado `B`=Bloqueado |
| SESSIONID | String |  | SESSIONID |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSIRMU — Tabela criada para quantificar o número de vezes que um registro é utilizado.
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ENTIDADE | String |  | ENTIDADE |  |
| RESOURCEID | String |  | RESOURCEID |  |
| CODUSU | Integer |  | CODUSU |  |
| QTD | Integer |  | QTD |  |
| CHAVE | String |  | CHAVE |  |
| DTINIPERIODO | Date |  | DTINIPERIODO |  |

## TSIROT — Tabela de Rotinas
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| COMANDO | String |  | Camando a ser executado |  |
| CODROT | Integer |  | Cód.Rotina |  |

## TSIRTD — Detalhe de Retorno
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPREG | String |  | Tipo do Registro |  |
| SEQUENCIA | Integer |  | Sequência da Coluna |  |
| NOME | String |  | Nome Coluna |  |
| TIPO | String |  | Tipo Coluna |  |
| QTDDEC | Integer |  | Quantidade Decimais |  |
| POSINI | Integer |  | Posição inicial da variável |  |
| POSFIM | Integer |  | Posição final da variável |  |
| CODIGO | Integer |  | Cód.Layout |  |

## TSIRTEF — RedesTEF
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REDE | String |  | Rede |  |
| DESCRICAO | String |  | Descrição |  |

## TSIRTM — Mestre de Retorno
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPREG | String |  | Tipo de Registro |  |
| TITULO | String |  | Título do Layout |  |
| TAMREG | Integer |  | Tamanho Registro |  |
| POSINITIPREG | Integer |  | Pos Ini Tipo Registo |  |
| SP_CHAMADA | String |  | Stored Chamada |  |
| CODIGO | Integer |  | Cód.Layout |  |

## TSISBP — Impressora substituta
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPODOC | String |  | Tipo de documento |  |
| ORIGINALPRINTERNAME | String |  | Nome da impressora |  |
| PRINTERURI | String |  | Caminho da impressora |  |
| CODUSU | Integer |  | Usuário |  |

## TSISCI — TSISCI
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EXECUCAO | String |  | EXECUCAO |  |
| DTEXECUCAO | DateTime |  | DTEXECUCAO |  |
| NOME | String |  | Nome do Script |  |

## TSISESSAOITERACAO — Sessão de iteração
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHINICIO | DateTime |  | Dh. Início |  |
| DHULTIMAATIVIDADE | DateTime |  | Última atividade |  |
| QTDITERACOES | Integer |  | Qtd. acesso |  |
| RESOURCEID | String |  | ResourceID |  |
| CODUSU | Integer |  | Usuário |  |

## TSISMS — Conta SMS
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| PLATAFORMA | String |  | Plataforma | `INFOBIP`=Infobip `EMBARCADO`=Nativo (Modem SMS) |
| USUARIO | String |  | Usuário |  |
| SENHA | String |  | Senha |  |
| NOMEREMETENTE | String |  | Nome Remetente |  |
| CODCONTASMS | Integer |  | Código |  |

## TSISMTP — tabela servidor smtp
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SERVIDOR | String |  | Servidor SMTP |  |
| PORTA | Integer |  | Porta |  |
| TIPO | String |  | Tipo de Conexão | `T`=Segura com TLS `P`=Comum `S`=Segura com SSL |
| IGNORACERTIFICADO | String |  | Ignorar validação do certificado do servidor ? | `N`=Não `S`=Sim |
| REMETENTE | String |  | Remetente |  |
| USUARIO | String |  | Usuário |  |
| SENHA | String |  | Senha |  |
| UTILDOWNXML | String |  | Utilizar para download de XML de DF-e? | `S`=Sim `N`=Não |
| SERVIDORPOP | String |  | Servidor |  |
| PORTAPOP | Integer |  | Porta |  |
| PADRAO | String |  | Conta padrão | `N`=Não `S`=Sim |
| USEOAUTH | String |  | Autenticar com OAuth | `S`=Sim `N`=Não |
| CODATH | Integer |  | Configurações OAuth |  |
| REFRESHTOKEN | String |  | Refresh Token |  |
| REFRESHTOKENV2 | C |  | Refresh Token V2 |  |
| ACCESSTOKEN | String |  | Refresh Token |  |
| ACCESSTOKENV2 | C |  | Refresh Token V2 |  |
| EXPIRESIN | String |  | Expira em |  |
| CODSMTP | Integer |  | Cód. Conta |  |

## TSISRH — Usuário Portal Rh
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SENHA | String |  | SENHA |  |
| DTALT | DateTime |  | DTALT |  |
| CPF | String |  | CPF |  |

## TSISUPL — Usuário Suplementar
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSUSUPL | Integer |  | Cód. Usuário |  |
| DTINICIO | Date |  | Data de Início |  |
| DTFIM | Date |  | Data Final |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSISVP — Servidores de Impressão
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| URL | String |  | Nome ou IP |  |
| PORTA | Integer |  | Porta |  |
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODUSUINC | Integer |  | Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| NUSVP | Integer |  | Código |  |

## TSITAB — Tabelas do Sistema
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTABELA | String |  | Cód.Tabela |  |
| NOMETAB | String |  | Nome da Tabela |  |
| DESCRTAB | String |  | Descrição da Tabela |  |
| CODCHAVE | String |  | Cód.Chave |  |
| NUTABSIS | Integer |  | Número único da Tabela |  |

## TSITAO — Tokens OAuth Outlook
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REFRESHTOKEN | C |  | Refresh Token |  |
| ACCESSTOKEN | C |  | Refresh Token |  |
| CODTAO | Integer |  | Cód. Configuração |  |

## TSITAR — Tarefas Agendadas
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODROT | Integer |  | Cód.Rota |  |
| ATIVO | String |  | Ativo |  |
| PARAMETRO | String |  | Parâmetro da Tarefa |  |
| FREQUENCIA | String |  | Frenquência de Execução |  |
| DTEXEC | DateTime |  | Data de Execução |  |
| HREXEC | DateTime |  | Hora de Execução |  |
| MINUTOS | Integer |  | Tempo de Execução |  |
| STATUS | String |  | Status |  |
| DTULTIMA | DateTime |  | Data da Última Execução |  |
| HRULTIMA | DateTime |  | Hora da Última Execução |  |
| PROGRAMACAO | String |  | Programação |  |
| CODREL | Integer |  | Cód.Relatório |  |
| FILTROS | String |  | Filtro |  |
| DESCRTAR | String |  | Descrição da Tarefa |  |
| CODTAR | Integer |  | Cód.Tarefa |  |

## TSITCM — Telemetria de Customizações
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo | `ACAO_AGEN`=Ações Agendadas `BTN_BD`=Botão de Ação de Banco de Dados `BTN_JAVA`=Botão de Ação Java `BTN_JAVASCRIPT`=Botão de Ação Javascript `CAMP_CALC`=Campos Calculados SQL_(+14)_ |
| DESCRICAO | String |  | Descrição |  |
| PROCESSO | String |  | Processo |  |
| QTDCOLETA | Integer |  | Qtd. Execuções |  |
| TEMPOTOTAL | Integer |  | Total Exec. (ms) |  |
| TEMPOMEDIO | Integer |  | Tempo Médio (ms) |  |
| DHEXECUCAO | Date |  | Dt. Execução |  |
| QTDERROS | Integer |  | Qtd. Erros |  |
| IDTIPO | String |  | ID |  |
| SERVERID | String |  | Hash Info. Server |  |
| IPSERVER | String |  | IP |  |
| PORTASERVER | String |  | Porta |  |
| PATHSERVER | String |  | Caminho Absoluto |  |
| ENTIDADE | String |  | Entidade |  |
| DETALHES | String |  | Detalhes |  |

## TSITCMT — Telemetria de Transações de Customizações
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GLOBALID | String |  | ID Global |  |
| SESSIONID | String |  | ID de Sessão |  |
| TEMPOTOTAL | Integer |  | Tempo Total |  |
| TEMPDBNATIVO | Integer |  | Tempo DB Nativo |  |
| TEMPDBCUTOMIZACAO | Integer |  | Tempo DB Customização |  |
| TEMPOTOTALCUSTOMIZACAO | Integer |  | Tempo Total Customização |  |
| DHEXECUCAO | Date |  | Data/Hora de Execução |  |
| DETALHES | String |  | Detalhes |  |
| THREADNAME | String |  | Nome da Thread |  |
| RESOURCEID | String |  | ID de Recurso |  |
| CODUSU | Integer |  | Código de Usuário |  |
| SERVICENAME | String |  | Nome do Serviço |  |

## TSITCMTITEM — Detalhes de Telemetria de Transações de Customizações
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GLOBALID | String |  | ID Global |  |
| SESSIONID | String |  | ID de Sessão |  |
| SEQUENCIA | Integer |  | Sequência |  |
| IDTIPO | String |  | ID do Tipo |  |
| TIPO | String |  | Tipo |  |
| ERRO | String |  | Erro |  |
| TEMPO | Integer |  | Tempo |  |
| DHEXECUCAO | Date |  | Data/Hora de Execução |  |
| DETALHES | String |  | Detalhes |  |
| ENTIDADE | String |  | Entidade |  |
| DESCRICAO | String |  | Descrição |  |
| TEMPDBCUTOMIZACAO | Integer |  | Tempo DB Customização |  |

## TSITELE — Telemetria da Aplicação
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MONITORCPU | String |  | Monitorar CPU |  |
| MONITORMEMORY | String |  | Monitorar Memoria |  |
| MONITORGC | String |  | Monitorar GC |  |
| MONITORLIVETHREADS | String |  | Monitorar Live Threads |  |
| LONGOPSATIVE | String |  | Long Ops Ative |  |
| CODTELE | Integer |  | Código da Telemetria |  |

## TSITEND — Tipo de Endereço
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPO | String |  | Tipo |  |

## TSITHD — Threads do Sistema
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NAME | String |  | Descrição |  |
| DHINSERT | Date |  | Dt. Captura |  |
| STACKTRACE | Boolean |  | Trace |  |
| ID | String |  | Cod. Thread |  |

## TSITLM — TABLE TSITLM
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEREGRA | String |  | Nome Regra |  |
| TABELA | String |  | Tabela |  |
| DTEXEC | DateTime |  | Dt. Execução |  |
| QTDEXEC | Integer |  | Quant. Execuções |  |
| TEMPOTOT | Float |  | Tempo Total (seg) |  |
| TEMPOMED | Float |  | Tempo Médio (seg) |  |
| CODRGB | Integer |  | CodRgb |  |

## TSITMF — TopsMaisFiltradas
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | CODUSU |  |
| QTDFILT | Integer |  | QTDFILT |  |
| CODTIPOPER | Integer |  | CODTIPOPER |  |

## TSITPA — Tipo de arquivo
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRIPTION | String |  | Tipo de arquivo |  |
| DOCTASTE | String |  | Código |  |

## TSITPD — Tipo de documento
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRIPTION | String |  | Tipo de documento |  |
| DOCTYPE | String |  | Código |  |

## TSITVP — DashboardPlayer
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTV | Integer |  | Cód. Slide player |  |
| NUGDG | Integer |  | Gadget |  |
| NUGDGINT | Integer |  | Gadget interno |  |
| URL | String |  | URL da página |  |
| ORDEM | Integer |  | Ordem de apresentação |  |
| TEMPO | Integer |  | Tempo de apresentação (em segundos) |  |
| URLRSS | String |  | URL do feed rss |  |
| URLVIDEOYOUTUBE | String |  | URL do vídeo do Youtube |  |
| CODUSU | Integer |  | Usuário |  |

## TSIUCT — Contas por Usuário
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód.Empresa |  |
| CODCTABCOINT | Integer |  | Cód.Conta |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSIUFA — Usuário Filtro API
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EMAIL | String |  | Email |  |
| CODFIL | Integer |  | Cód. Filtro |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSIUFI — Fila de Impressão por TOP e Usuário
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| ARQUIVO | String |  | Arquivo |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TSIUFS — Unidade Federativa
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| UF | String |  | Sigla |  |
| DESCRICAO | String |  | Descrição |  |
| CODPAIS | Integer |  | País |  |
| CODPARCSECRECEST | Integer |  | Cód. Parceiro Secretaria da Receita Estadual |  |
| CODIBGE | Integer |  | Código IBGE |  |
| CODSTGNRE | String |  | Código da Receita (GNRE) |  |
| CODRECDIME | Integer |  | Código da Receita (DIME) |  |
| CODCLSVENCDIME | Integer |  | Código Classe Vencimento (DIME) |  |
| CODDETGNRE | Integer |  | Código Detalhamento Receita (GNRE) |  |
| CODPRODGNRE | Integer |  | Código do Produto (GNRE) |  |
| PROTOCOLOCONVENIO | String |  | Protocolo/Convênio (GNRE) |  |
| VLRPERSGNRE | String |  | Valor personalizado GNRE |  |
| BH_ESTADO | String |  | BH_ESTADO |  |
| CODCAMPOEXTRAGNRE | Integer |  | Código (Campos Extras GNRE) |  |
| CODCAMPOEXTRAGNRE2 | Integer |  | Código (Campos Extras GNRE 2) |  |
| ESTORNONFE | String |  | Permite Estorno de NF-e | `S`=Sim `N`=Não |
| GERINFCAMPADICGNRE | String |  | Gera Informação dos Campos Adicionais na GNRE | `S`=Sim `N`=Não |
| VALORCAMPOEXTRA | String |  | Valor para Campo Extra GNRE | `null`=Chave NF-e/CT-e e Observação `O`=Observação `C`=Chave NF-e/CT-e |
| VERSAOGNRE | String |  | Versão GNRE | `200`=2.0 `100`=1.0 |
| TIPODOC | Integer |  | Tipo de documento |  |
| CODFCPSTGNRE | Integer |  | Código da Receita (GNRE) p/ FCP ST |  |
| CODRECDIMEFCPST | Integer |  | Código da Receita (DIME) para FCP ST |  |
| CODCLSVENCDIMEFCPST | Integer |  | Código Classe Vencimento (DIME) p/ FCP ST |  |
| TIPOINFO | String |  | Tipo da Informação | `N`=Nota Fiscal (Número da nota) `C`=Chave do documento |
| TIPTITGNREFCPST | Integer |  | Tipo de Título p/ indicar GNRE p/ FCP S.T. |  |
| USAWEBSERVICEGNRE | String |  | Utiliza webservice para GNRE | `S`=Sim `N`=Não |
| AD_CODTAB11 | String |  | Cod UF na tabela 11 da GIA |  |
| TABPRECPMC | Integer |  | Tabela de Preço PMC |  |
| TABPRECOPF | Integer |  | Tabela de Preço PF |  |
| DHALTREG | DateTime |  | Dt. Alteração |  |
| CODUSUALTREG | Integer |  | Cód. Usuário Alteração |  |
| CODUF | Integer |  | Cód. Unidade Federativa |  |

## TSIUFU — Unidades Fiscais por UF
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| DTINIVALID | Date |  | Data início validade |  |
| DTFIMVALID | Date |  | Data final validade |  |
| VLRUNID | Float |  | Valor |  |
| QTDDECIMAIS | Integer |  | Quantidade de casas decimais |  |
| CODUF | Integer |  | Código Unidade Federativa |  |

## TSIUSU — Usuários
Campos: 113

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEUSU | String |  | Nome |  |
| ACESSOPDVCANCITENS | String |  | Cancelamento de itens | `S`=Sim `N`=Não |
| ACCOUNTEMAIL | String |  | Sankhya ID |  |
| DTLIMACESSO | Date |  | Data limite de acesso |  |
| ACESSOPDVSANG | String |  | Sangria | `S`=Sim `N`=Não |
| INTERNO | String |  | Senha |  |
| ACESSOPDVSUPR | String |  | Suprimento | `S`=Sim `N`=Não |
| CODGRUPO | Integer |  | Grupo |  |
| DESCTOTALNOTAPDV | String |  | Desconto no Total | `N`=Não `S`=Sim |
| ACESSOPDVSANGPDESP | String |  | Sangria para despesas | `S`=Sim `N`=Não |
| EMAIL | String |  | Email |  |
| CODEMP | Integer |  | Empresa |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODCENCUSPAD | Integer |  | Cód.Centro Resultado Padrão |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| NOMEFILA | String |  | Nome Fila p/ num. boleto |  |
| NUVERSAO | Integer |  | NUVERSAO |  |
| TOPBAIXARECEITA | Integer |  | Tipo Operação Baixa Receita |  |
| TOPBAIXADESPESA | Integer |  | Tipo Operação Baixa Despesa |  |
| RENDIASVALJUR | Integer |  | Dias tol. juros reneg |  |
| EMAILSOLLIB | String |  | Email p/ solicitação liberação |  |
| TIPENVNOTSOL | String |  | Notificar solicitante de liberações | `S`=Por Notificação no SankhyaOm `E`=Por e-mail `A`=Ambos |
| NOMEUSUCPLT | String |  | Nome Completo |  |
| ATUNUVERSAO | String |  | ATUNUVERSAO |  |
| DTNASC | Date |  | Data Nascimento |  |
| CPF | String |  | CPF |  |
| RG | String |  | RG |  |
| CODVEND | Integer |  | Vendedor |  |
| CAIXA | String |  | Caixa | `N`=Não `S`=Sim |
| TEMECF | String |  | Tem ECF | `S`=Sim `N`=Não |
| BAIXAREC | String |  | Baixa Receita | `N`=Não `S`=Sim |
| SENHANOVA | String |  | Senha Nova |  |
| SENHASMTP | String |  | Senha SMTP |  |
| SENHAREPETE | String |  | Senha Repetir |  |
| USUARIOSMTP | String |  | Usuário SMTP |  |
| SERVIDORSMTP | String |  | Servidor de SMTP |  |
| VLRMAXAUT | Float |  | Valor Máximo de autorização |  |
| SENHAANTIGA | String |  | Senha Antiga |  |
| CONTACESSO | String |  | Controle |  |
| DTULTIMASENHA | DateTime |  | Data da Última senha |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| NIVEL | Integer |  | Nível |  |
| BAIXADESP | String |  | Baixa Despesa | `N`=Não `S`=Sim |
| ALTCTAFAT | String |  | Altera conta bancária no faturamento? | `N`=Não `S`=Sim |
| ALTCTAIMPBOL | String |  | Altera conta bancária na impressão de boleto? | `N`=Não `S`=Sim |
| IMP2SANSUPCAI | String |  | Imprime segunda via sangria suprimento e fechamento de caixa | `N`=Não `S`=Sim |
| ABREGAVETA | String |  | Abre Gaveta | `N`=Não `S`=Sim |
| TIPOSMTP | String |  | Tipo de SMTP | `L`=Meu Servidor Requer Autorização `C`=Autorização Digest MD5 `P`=Autorização Simples `N`=Não Requer Autorização |
| CODCTABCOINT | Integer |  | Conta |  |
| SENHANUNCAEXPIRA | String |  | Senha expira |  |
| CODCTABCOINT2 | Integer |  | Conta 2 |  |
| VERCABPROPRIA | String |  | Ver as Próprias Notas | `N`=Não `S`=Sim |
| PORTASMTP | Integer |  | Porta SMTP |  |
| SEGURANCASMTP | String |  | Conexão segura? | `S`=SSL `N`=Não `T`=TLS `D`=TLS, se disponível |
| APROVCOT | String |  | Aprovar cotação | `N`=Não aprova `M`=Melhor Resultado `Q`=Qualquer Resultado |
| ALTORDCFECH | String |  | Altera Ordem de Carga fechada? | `N`=Não `S`=Sim |
| CODETAPA | Integer |  | Etapa |  |
| EXIBIRVALANALRENT | String |  | Exibir valores na Análise de Rentabilidade? | `N`=Não `S`=Sim |
| DTULTACESSO | DateTime |  | Data Último Acesso |  |
| CONTAGOL | String |  | Controle GOL |  |
| NOTSLAFILA | String |  | Notifica Fila SLA | `T`=Todos `R`=Responsável |
| ACESSOVISUALCAB | String |  | Ver Pedidos/Notas | `C`=Do mesmo C.R. do vendedor/comprador `S`=Desse vendedor/Comprador e subordinados `V`=Desse vendedor/comprador `T`=De todos |
| IMPNFCENTRAL | String |  | Imprimir/Reimprimir Nota nas Centrais | `N`=Não `S`=Sim |
| MINUTOSFIN | Integer |  | Finaliza se Inativo em (minutos) |  |
| RESTRINGECART | String |  | Restringir carteira? | `N`=Não `S`=Sim |
| CODPARCPERFIL | Integer |  | Cód. Parceiro Perfil |  |
| CODCONTATOPERFIL | Integer |  | Contato Perfil |  |
| EXCLIBORC | String |  | Pode excluir liberações/negações de orçamento | `S`=Sim `N`=Não |
| LOCALE | String |  | Idioma | `es_ES`=Espanhol `en_US`=Inglês (Estados Unidos) `pt_BR`=Português (Brasil) `fr_FR`=Francês |
| FOTO | Boolean |  | Foto |  |
| PERMEXPREL | String |  | Permite exportar relatórios ? | `N`=Não `S`=Sim |
| CODCARGAACESSO | Integer |  | Carga horária para acesso |  |
| TOLERANCIAACESSO | Integer |  | Tolerância acesso fora horário |  |
| VISACESOUTUSU | String |  | Visualiza acesso de outros Usuários | `S`=Sim `N`=Não |
| APENASCOMPLIB | String |  | Acessar apenas por computadores liberados? | `S`=Sim `N`=Não |
| INFRECSEN | String |  | Informação de Recuperação de Senha |  |
| ACESSAFORMULAREL | String |  | Acessa fórmulas relacionadas | `N`=Não `S`=Sim |
| INTEGRAECONECT | String |  | Integrar com EConect | `N`=Não `S`=Sim |
| NIVELACESSO | String |  | Nível de Acesso | `G`=Diretor `D`=Diretor Comercial |
| AVISAVARPRECO | String |  | Acompanha alteração de custo(WMS) | `N`=Não `S`=Sim |
| PERMALTMOEDA | String |  | Permite alterar valor de moeda na baixa? | `N`=Não `S`=Sim |
| PERMIMPRIMEREL | String |  | Permite imprimir relatórios? | `N`=Não `S`=Sim |
| IGNORAHORASCRUZ | String |  | Ignora Horas Cruzadas | `S`=Sim `N`=Não |
| SELECTWCAPO | String |  | Seleciona Centro de Trabalho em Apontamento de Produção | `S`=Sim `N`=Não |
| CORCODIGO | Integer |  | Corretor |  |
| TIMVERTODASFACS | String |  | Visualizar todas as FACs? | `S`=Sim `N`=Não |
| AD_MAXIMA | String |  | Integra com a máxima? | `N`=Não `S`=Sim |
| SENHAECONECT | Integer |  | Senha |  |
| CODIDECONECT | String |  | Cód. Ident. |  |
| CODPERFIL | Integer |  | Cód. Perfil |  |
| IDPERFILECONECT | String |  | Cód. Perfil |  |
| PERMREPERRO | String |  | Permite reportar erros ? | `N`=Não `S`=Sim |
| PROPRIETARIO | String |  | Proprietário | `S`=Sim `N`=Não |
| TIMPATHSCANNER | String |  | Path Scanner |  |
| ACCOUNTID | String |  | Account ID |  |
| IMPLANTADOR | String |  | Implantador | `S`=Sim `N`=Não |
| GESTOR | String |  | Gestor | `S`=Sim `N`=Não |
| TIMBAIXAWORD | String |  | Permitir Baixar Word | `S`=Sim `N`=Não |
| OPERACIONAL | String |  | Operacional | `S`=Sim `N`=Não |
| ACCOUNTTOKEN | C |  | Account TOKEN |  |
| ACCOUNTDHEXPIRA | DateTime |  | Data de expiração do Account TOKEN |  |
| ACCOUNTNOMEFOTO | String |  | Nome da foto do Account |  |
| TOKENCHECKOUT | String |  | Token de Identificação do Checkout |  |
| ACCOUNTPARTNER | Integer |  | Cód. Parceiro |  |
| AD_TECNICO | String |  | TECNICO SD | `S`=Sim `N`=Não |
| TIPOUSU | Integer |  | Tipo do Usuário | `0`=Interface `1`=Integração |
| INSTALAPACOTESS | String |  | Permite instalar pacote Sankhya Store? | `N`=Não `S`=Sim |
| CODUSU | Integer |  | Cód. Usuário |  |
| TIMBAIXTITRECABE | String |  | Baixar tít. reg. lote c/tít. entrada/comissão em aberto | `S`=Sim `N`=Não |
| GRUPOREDE | String |  | Grupo de Rede |  |
| IGNORALDAP | String |  | Ignorar login via LDAP | `S`=Sim `N`=Não |
| USUREDE | String |  | Usuário de Rede |  |
| CODEQUIP | Integer |  | Equipamento Fiscal |  |

## TSIUSUBK — Backup Usuários
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| BAIXAREC | String |  | BAIXAREC |  |
| BAIXADESP | String |  | BAIXADESP |  |
| VERCABPROPRIA | String |  | VERCABPROPRIA |  |
| SENHANUNCAEXPIRA | String |  | SENHANUNCAEXPIRA |  |
| ALTCTAFAT | String |  | ALTCTAFAT |  |
| ALTCTAIMPBOL | String |  | ALTCTAIMPBOL |  |
| ALTORDCFECH | String |  | ALTORDCFECH |  |
| EXIBIRVALANALRENT | String |  | EXIBIRVALANALRENT |  |
| IMPNFCENTRAL | String |  | IMPNFCENTRAL |  |
| MINUTOSFIN | Integer |  | MINUTOSFIN |  |
| APROVCOT | String |  | APROVCOT |  |
| ACESSOVISUALCAB | String |  | ACESSOVISUALCAB |  |
| RESTRINGECART | String |  | RESTRINGECART |  |
| CONTACESSO | String |  | CONTACESSO |  |
| CONTAGOL | String |  | CONTAGOL |  |
| NUNICO | Integer |  | NUNICO |  |