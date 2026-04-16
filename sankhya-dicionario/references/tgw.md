# TGW — WMS (Gestão de Armazém)

> Gerado do dicionário oficial TDD Sankhya. 108 tabelas.


## TGWAEEDOC — Análise Envio de Expedição de Documentos
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODEMP | Integer |  | Empresa |  |
| NOMEFANTASIA | String |  | Nome fantasia |  |
| ORDEMCARGA | Integer |  | Ordem de carga |  |
| CODPARCTRANSP | Integer |  | Cód. Parceiro transportadora |  |
| CODVEICULO | Integer |  | Cod. Veiculo |  |
| CODREG | Integer |  | Região |  |
| CODPARC | Integer |  | Parceiro |  |
| NOMEPARC | String |  | Nome do Parceiro |  |
| CODAEEDOC | Integer |  | Cód. Análise Envio Expedicao |  |

## TGWAGE — TABLE TGWAGE
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARCTRANSP | Integer |  | Cód.Parceiro Transportadora |  |
| DHPREVISTA | DateTime |  | DHPREVISTA |  |
| DHENTRADA | DateTime |  | DHENTRADA |  |
| DHSAIDA | DateTime |  | DHSAIDA |  |
| CODDOCA | Integer |  | CODDOCA |  |
| MOTIVO | String |  | MOTIVO |  |
| NUAGENDA | Integer |  | NUAGENDA |  |

## TGWAJE — Ajustes Estoque do WMS
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| OBSERVACAO | String |  | Observação |  |
| NUIVT | Integer |  | Nro. Inventário |  |
| NUAJUSTE | Integer |  | Nro. Ajuste |  |

## TGWARA — Área de Armazenagem
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição Área |  |
| TIPO | String |  | Tipo Armazenagem | `P`=Própria `T`=Terceiros |
| DHALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| REGRAPRODUTO | String |  | Regra Produto | `E`=Exclusivo `P`=Proibir `R`=Permitir |
| REGRAGRUPO | String |  | Regra Grupo de Produto | `P`=Proibir `R`=Permitir `E`=Exclusivo |
| REGRAPARCEIRO | String |  | Parceiros Relacionados | `E`=Exclusivo `P`=Proibir `R`=Permitir |
| NUAREA | Integer |  | Cód. Área Armazenagem |  |

## TGWARC — Áreas de Conferência
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEAREACONF | String |  | Descrição |  |
| DHALTER | DateTime |  | Data e Hora de Alteração |  |
| IMPSEP | String |  | Impressora padrão de etiquetas |  |
| CODAREACONF | Integer |  | Cód. Área |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TGWARE — Armazenamentos Expressos
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| CODENDDOCA | Integer |  | Cód. Endereço Doca |  |
| SITUACAO | String |  | Situação | `F`=Finalizada `E`=Entrega `C`=Coleta |
| CODEQUIP | Integer |  | Equipamento |  |
| CODARMAZENAGEM | Integer |  | Cód. Armazenamento Expresso |  |

## TGWARM — Armazenagem
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODENDORIG | Integer |  | End. Origem |  |
| CODENDDEST | Integer |  | End. Destino |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| NURECEBIMENTO | Integer |  | Nro Recebimento |  |

## TGWARS — Área de Separação
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEAREASEP | String |  | Descrição |  |
| CODAREACONF | Integer |  | Cód. Área Conferência |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| TIPOSEP | String |  | Tipo Separação | `L`=Por Produto `P`=Por Pedido |
| M3MAX | Float |  | Metros cúbicos máximo |  |
| PESOMAX | Float |  | Peso máximo |  |
| IMPRESSORAETQVOL | String |  | Impressora da Etiqueta de Volume |  |
| MODETQVOL | Integer |  | Modelo de Etiqueta de Volume |  |
| USASEPAGRUPROD | String |  | Utiliza separação agrupada por produto? | `N`=Não `S`=Sim |
| QTCHECKSEP | Integer |  | Quantidade máx. de checkouts por separação |  |
| VOLCHECKSEPROD | Float |  | Volumetria máx. do checkout por separação(M3) |  |
| QTDUMAPED | Integer |  | Quantidade de Checkout por Pedido |  |
| PESMAXSEPAGRU | Float |  | Peso máx. do checkout por separação |  |
| QTPEDSEPAGR | Integer |  | Quantidade de pedidos por separação |  |
| VOLCONTINUO | String |  | Volume Contínuo? | `S`=Sim `N`=Não |
| AGRUPARPEDIDOSWMS | String |  | Agrupar pedidos | `N`=Não `S`=Sim |
| POSESTEIRASEP | String |  | Posição na esteira de separação | `M`=Intermediária `I`=Inicial `T`=Terminal `N`=Nenhuma |
| IMPRESSORAETQSEP | String |  | Impressora p/ etiqueta de separação |  |
| IMPETIQFECHVOL | String |  | Imprimir etiqueta no fechamento do volume | `S`=Sim, conforme empresa `N`=Não usa `A`=Sim, conforme área de separação |
| QUEBRAPORNORMA | String |  | Quebra por Norma/Palete | `S`=Sim `N`=Não |
| QTDSKU | Integer |  | Quantidade de SKU’s por separação |  |
| TOLERANCIASKU | Integer |  | Quantidade Tolerância de SKU’s por separação |  |
| CODAREASEP | Integer |  | Cód. Área Separação |  |

## TGWAXFE — Endereço Área Armazenagem
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODENDINI | Integer |  | Cód. End. Inicial |  |
| CODENDFIM | Integer |  | Cód. End. Final |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUAREA | Integer |  | Cód. Área Arm. |  |

## TGWAXG — Grupos de Prod. Área de Arm.
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOPROD | Integer |  | Grupo |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| DTINI | DateTime |  | Data início |  |
| DTFIM | DateTime |  | Data fim |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUAREA | Integer |  | Cód. Área Arm. |  |

## TGWAXP — Prod. da Área de Arm.
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| DTINI | DateTime |  | Data início |  |
| DTFIM | DateTime |  | Data fim |  |
| CONTROLE | String |  | Controle |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUAREA | Integer |  | Cód. Área Arm. |  |

## TGWAXPAR — Endereço Área Armazenagem
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Código Parceiro |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| DTINI | DateTime |  | Data início |  |
| DTFIM | DateTime |  | Data fim |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUAREA | Integer |  | Cód. Área Arm. |  |

## TGWCCX — Caixas Flowrack
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOVOLUME | String |  | Tipo Volume |  |
| CODVOLUME | Integer |  | Volume |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUTAREFA | Integer |  | Tarefa |  |
| SEQTAREFA | Integer |  | Seq. da Tarefa |  |
| QTDE | Float |  | Quantidade |  |
| CONFERIDO | String |  | Conferido |  |
| NUSEPARACAO | Integer |  | Separação |  |

## TGWCOI — Itens de conferência
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| CODBARRA | String |  | Cód. Barra |  |
| QTDECONF | Integer |  | Qtde. Conferida |  |
| RECONTAGEM | String |  | Recontagem | `S`=Sim `N`=Não |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| IGNORAR | String |  | IGNORAR |  |
| CODVOLCOMPRA | String |  | CODVOLCOMPRA |  |
| TIPOVOLUME | String |  | TIPOVOLUME |  |
| CODVOLUME | Integer |  | Cód. Volume |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | DHALTER |  |
| CONTROLE | String |  | Controle |  |
| QTDAVARIA | Integer |  | Qtde. Avariada |  |
| RECEBERAVARIA | String |  | RECEBERAVARIA |  |
| DEVOLVER | String |  | DEVOLVER |  |
| DTVAL | Date |  | Dt. Validade |  |
| DTVALMIN | Date |  | Dt. Val. Mínima |  |
| CODUSUDIV | Integer |  | CODUSUDIV |  |
| ACEITARDIF | String |  | ACEITARDIF |  |
| QTDEDIF | Integer |  | QTDEDIF |  |
| CODMDIV | Integer |  | Cód. Divergência |  |
| QTDPECAS | Integer |  | Qtd. de Peças |  |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |

## TGWCOIVAL — Itens de conferência validade
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| CODBARRA | String |  | Cód. Barra |  |
| QTDSHELFLIFE | Integer |  | Qtde. Shelflife |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| TIPOVOLUME | String |  | TIPOVOLUME |  |
| CODVOLUME | Integer |  | Cód. Volume |  |
| CONTROLE | String |  | Controle |  |
| QTDAVARIA | Integer |  | Qtde. Avariada |  |
| DTVAL | Date |  | Dt. Validade |  |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |

## TGWCON — TABLE TGWCON
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SITUACAO | String |  | SITUACAO |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHINICIOCONF | DateTime |  | DHINICIOCONF |  |
| DHFINALCONF | DateTime |  | DHFINALCONF |  |
| TIPCONF | String |  | TIPCONF |  |
| DESTFINAL | String |  | Destino Final? |  |
| NURECEBIMENTO | Integer |  | Recebimento |  |
| PARCIAL | String |  | Conferencia parcial? |  |
| NUCONFERENCIA | Integer |  | NUCONFERENCIA |  |

## TGWCONFEMPE — Configuração do JOB de Empenho
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DHALTER | DateTime |  | Data de alteração |  |
| TOPCOMPRA | Integer |  | TOP de Compra |  |
| TOPVENDA | Integer |  | TOP de Venda |  |
| CODPARCTRANSPCOMPRA | Integer |  | Transp. de Compra |  |
| CODPARCTRANSPVENDA | Integer |  | Transp. de Venda |  |
| REGIAOCOMPRA | Integer |  | Região Compra |  |
| REGIAOVENDA | Integer |  | Região Venda |  |
| CODPARCCOMPRA | Integer |  | Parc. de Compra |  |
| CODPARCVENDA | Integer |  | Parc. de Venda |  |
| EMAIL | String |  | E-mail |  |
| TIPGATILHO | String |  | Tipo de Gatilho | `I`=Intervalo de Tempo `C`=Expressão CRON |
| TIPINTERVALO | String |  | Tipo de Intervalo | `S`=Por Segundo `M`=Por Minuto `H`=Por Hora |
| VLRINTERVALO | Integer |  | Valor |  |
| EXPGATILHO | String |  | Expressão de Gatilho |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODUSU | Integer |  | Usuário |  |
| FILTROVENDA | C |  | Filtro de Venda |  |
| FILTROCOMPRA | C |  | Filtro de Compra |  |
| NUCONF | Integer |  | Cód. Config. |  |

## TGWCSER — Séries Conferência
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| CONTROLE | String |  | Controle |  |
| NROSERIE | String |  | Nro. Série |  |
| AVARIA | String |  | Avaria | `S`=Sim `N`=Não |
| TIPO_LEITURA | String |  | Tipo Leitura | `S`=SSCC `E`=EAN `D`=DATAMATRIX |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |

## TGWCTE — TABLE TGWCTE
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLOCAL | Integer |  | CODLOCAL |  |
| CODPROD | Integer |  | CODPROD |  |
| CONTROLE | String |  | CONTROLE |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODEND | Integer |  | CODEND |  |
| ESTOQUE | Integer |  | ESTOQUE |  |
| RESERVADO | Integer |  | RESERVADO |  |
| ESTMIN | Float |  | ESTMIN |  |
| ESTMAX | Float |  | ESTMAX |  |
| ATIVO | String |  | ATIVO |  |
| CODBARRA | String |  | CODBARRA |  |
| DTVAL | DateTime |  | DTVAL |  |
| TIPO | String |  | TIPO |  |
| DTCONTAGEM | DateTime |  | DTCONTAGEM |  |
| ATUALESTOQUE | Integer |  | ATUALESTOQUE |  |
| CODVOL | String |  | CODVOL |  |
| DTATUALEST | DateTime |  | DTATUALEST |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEMP | Integer |  | CODEMP |  |

## TGWDCA — TABLE TGWDCA
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEND | Integer |  | Endereço |  |
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| SITUACAO | String |  | Situação | `L`=Livre `O`=Ocupada `R`=Reservada |
| ALTURA | Float |  | Altura |  |
| TIPDOCA | String |  | Tipo doca | `P`=Produção `A`=Entrada/Saída `E`=Entrada `S`=Saída |
| BALCAO | String |  | Balcão | `S`=Sim `N`=Não |
| IMPRESSORADOCA | String |  | Impressora da doca |  |
| CODENDCROSSDOCK | Integer |  | Endereço Crossdocking |  |
| CODDOCA | Integer |  | Cód. Doca |  |

## TGWDEV — Devolucão WMS
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro Nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| QTDDEVOLVER | Float |  | Qtd. Devolver |  |
| DHDEV | DateTime |  | Dt. Devolução |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUCONFERENCIA | Integer |  | Nro Conferência |  |
| NUDEV | Integer |  | Nro Devolução |  |

## TGWEAC — Endereço Area de Conferencia
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODENDINI | Integer |  | Cód. End. Ini. |  |
| CODENDFIM | Integer |  | Cód. End. Final |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODAREACONF | Integer |  | Cód. Área Conf. |  |

## TGWEAS — Endereço Area Separacao
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODENDINI | Integer |  | Cód. End. Ini. |  |
| CODENDFIM | Integer |  | Cód. End. Final |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ENDERECOINI | String |  | Endereço Inicial |  |
| ENDERECOFIM | String |  | Endereço Final |  |
| CODAREASEP | Integer |  | Cód. Área Sep. |  |

## TGWEAX — Endereço Auxiliar
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUSEPARACAO | Integer |  | Nro. Separação |  |
| DHINC | DateTime |  | Dt. Inicial |  |
| DHFIN | DateTime |  | Dt. Final |  |
| CODUSU | Integer |  | Cód. Usu. Checkout |  |
| CODAREASEP | Integer |  | Área de Início UMA |  |
| CODENDCHECKOUT | Integer |  | Cód. End. Checkout |  |

## TGWEGE — Executantes por Grupos de Endereços
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEXEC | Integer |  | Cód. Executante |  |
| PODESEP | String |  | Pode Separar | `N`=Não `S`=Sim |
| PODEREAB | String |  | Pode Reabastecer | `N`=Não `S`=Sim |
| PODEARM | String |  | Pode Armazenar | `S`=Sim `N`=Não |
| PODETRANSF | String |  | Pode Transferir | `N`=Não `S`=Sim |
| PODEINV | String |  | Pode Inventariar | `N`=Não `S`=Sim |
| CODGEN | Integer |  | Cód. Grupo Endereço |  |

## TGWEMPE — Empenho de Produto
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CONTROLE | String |  | Controle |  |
| DESCRSITUACAO | String |  | Situação (Recebimento) |  |
| QTDEMPENHO | Float |  | Qtd. Empenhada |  |
| CODVOL | String |  | Unidade |  |
| NUNOTA | Integer |  | Nro. Único Compra |  |
| NURECEBIMENTO | Integer |  | Nro. do Recebimento |  |
| CHAVENFE | String |  | Chave NFe |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| CODUSU | Integer |  | Cód. do Usuário |  |
| TIPO | String |  | Tipo de Empenho | `A`=Automático `M`=Manual |
| NUNOTAPEDVEN | Integer |  | Nro. Único Venda |  |
| PENDENTE | String |  | Pendente | `S`=Sim `N`=Não |
| CODPROD | Integer |  | Cód. do Produto |  |

## TGWEND — Endereço de Armazenamento
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| POSSUICONTPEND | String |  | Contagem Pendente |  |
| ENDERECO | String |  | Endereço |  |
| DESCREND | String |  | Descrição |  |
| MULTIPROD | String |  | Multi Produto | `N`=Não `S`=Sim |
| EXPEDICAO | String |  | Permite Expedição | `N`=Não `S`=Sim |
| PICKING | String |  | Picking | `N`=Não `S`=Sim |
| FRAGMENTAEST | String |  | Permite Fragmentar Estoque | `N`=Não `S`=Sim |
| CROSSDOCK | String |  | End. de Crossdocking | `S`=Sim `N`=Não |
| ORDEM | Integer |  | Ordem |  |
| NIVEL | Integer |  | Nível |  |
| ALTURA | Float |  | Altura |  |
| LARGURA | Float |  | Largura |  |
| PROFUNDIDADE | Float |  | Profundidade |  |
| M3MAX | Float |  | Metro Cúbico Máx. |  |
| PESOMAX | Float |  | Peso Máximo |  |
| CODENDPAI | Integer |  | Endereço Pai |  |
| GRAU | Integer |  | Grau |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| PROIBIRGRUPO | String |  | Proibir Grupos relacionados | `N`=Permitir `S`=Proibir |
| PROIBIRPRODUTO | String |  | Proibir Produtos relacionados | `N`=Permitir `S`=Proibir `E`=Exclusivo |
| PROIBIRLOCAL | String |  | Proibir Local | `N`=Permitir `S`=Proibir |
| EXCLCONF | String |  | Exclusivo p/ Conferência | `S`=Sim `N`=Não |
| ENDMOVVERTICAL | String |  | Movimentação Vertical? | `N`=Não `S`=Sim |
| TIPO | String |  | Tipo | `NV`=Nível `PR`=Prédio `BL`=Bloco `RU`=Rua `DP`=Depósito_(+1)_ |
| FLOWRACK | String |  | É flowrack? |  |
| PAR | String |  | Lado | `N`=Ímpar `S`=Par |
| CODLOCAL | Integer |  | Local |  |
| PROIBIRCONTROLE | String |  | Proibir Controle | `N`=Permitir `S`=Proibir |
| BLOQUEADO | String |  | Situação do Estoque | `S`=Bloqueado `N`=Disponível |
| POSSUIESTOQUE | String |  | Possui Estoque |  |
| CODUSUTARCONTAGEM | Integer |  | Cód. Usuário Contagem |  |
| APENASCONTPORPROD | String |  | Permitir apenas contagem por produto | `S`=Sim `N`=Não |
| CODENDPREF | Integer |  | Endereço Preferencial |  |
| CODENDSEC | Integer |  | Endereço Secundário |  |
| USAPICKINGINTERMEDIARIO | String |  | Usa Picking Intermediário | `N`=Não `S`=Sim |
| PICKINGINTERMEDIARIO | String |  | Picking Intermediário | `N`=Não `S`=Sim |
| CODEMP | Integer |  | Empresa |  |
| CONEXAOSAIDA | String |  | Utiliza endereço de conexão para Saída | `N`=Não `S`=Sim |
| CONEXAOENTRADA | String |  | Utiliza endereço de conexão para Entrada | `N`=Não `S`=Sim |
| NROMAXPROD | Integer |  | Nro. máximo de produtos |  |
| REABPICK | String |  | Reabastecido por Picking | `S`=Sim `N`=Não |
| LOTEUNICO | String |  | Lote Único | `S`=Sim `N`=Não |
| UTILIZAUMA | String |  | Utiliza UMA | `S`=Sim `N`=Não |
| QTDMAXUMA | Integer |  | Qtd. máxima de UMAs permitidas no endereço |  |
| CODEND | Integer |  | End. Reduzido |  |

## TGWENP — Estoque Nota Produto
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| CODPROD | Integer |  | Cód. Produto |  |
| CONTROLE | String |  | Controle |  |
| CODEND | Integer |  | Cód. Endereço |  |
| CODVOL | String |  | Volume |  |
| ESTOQUE | Integer |  | Estoque |  |
| ESTOQUEVOLPAD | Integer |  | Est. UN. Pad. |  |
| CODLOCAL | Integer |  | Cód. Local |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| NUNOTA | Integer |  | Nota |  |

## TGWEPA — Empresa x Produto x Área
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód.Produto |  |
| CODAREASEP | Integer |  | Cód. Área Separação |  |
| CODEMP | Integer |  | Cód.Empresa |  |

## TGWEPL — Estoques por Páletes
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODLOCAL | Integer |  | Local |  |
| CONTROLE | String |  | Controle |  |
| CODEND | Integer |  | Endereço |  |
| CODPROD | Integer |  | Produto |  |
| CODVOL | String |  | Volume |  |
| CODPARC | Integer |  | Parceiro |  |
| QTD | Integer |  | Quantidade |  |
| IDPALETE | Integer |  | ID. Pálete |  |

## TGWEQP — Equipamentos do WMS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTIPEQUIP | Integer |  | Tipo Equipamento |  |
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODEQUIP | Integer |  | Equipamento |  |

## TGWEST — TABLE TGWEST
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLOCAL | Integer |  | Local |  |
| CODPROD | Integer |  | Cód.Produto |  |
| CONTROLE | String |  | Controle |  |
| CODEND | Integer |  | End. Reduzido |  |
| CODVOL | String |  | Volume |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| ENTRADASPEND | Integer |  | Entradas Pendentes |  |
| SAIDASPEND | Integer |  | Saídas Pendentes |  |
| ESTOQUE | Integer |  | Estoque |  |
| ENTRPENDVOLPAD | Integer |  | Entradas Pendentes Vol. Padrão |  |
| SAIDPENDVOLPAD | Integer |  | Saídas Pendentes Vol. Padrão |  |
| ESTOQUEVOLPAD | Integer |  | Estoque Vol. Padrão |  |
| DTREC | Date |  | Data Recebimento |  |
| DTVAL | Date |  | Data Validade |  |
| IDPALETE | Integer |  | ID. Pálete |  |
| CODEMP | Integer |  | Empresa |  |

## TGWESTVAL — Estoque Validade WMS
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLOCAL | Integer |  | Cód. Local |  |
| CODPROD | Integer |  | Cód. Produto |  |
| CONTROLE | String |  | Controle |  |
| CODEND | Integer |  | Cód. Endereço |  |
| CODVOL | String |  | Cód. Volume |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| QUANTIDADEVOLPAD | Float |  | Qtd. Un. Padrão |  |
| DTVAL | DateTime |  | Dt. Validade |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TGWEXG — Endereço x Grupo Produto
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOPROD | Integer |  | Grupo |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Fim |  |
| ORDEM | Integer |  | Ordem |  |
| CODEND | Integer |  | CODEND |  |

## TGWEXL — Endereço x Local
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODLOCAL | Integer |  | Local |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Fim |  |
| CODEND | Integer |  | CODEND |  |

## TGWEXP — Tabela Endereço x Produto WMS
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| CODEND | Integer |  | Endereço |  |
| ESTMIN | Integer |  | Estoque mínimo |  |
| ESTMAX | Integer |  | Estoque máximo |  |
| CODVOL | String |  | Unidade (Est. Min/Max) |  |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Fim |  |
| ORDEM | Integer |  | Ordem |  |
| ESTMINVOLPAD | Integer |  | Est. Mínimo Un Padrão |  |
| ESTMAXVOLPAD | Integer |  | Est. Máximo Un Padrão |  |
| CONTROLE | String |  | Controle |  |
| UNDPAD | String |  | Unidade Padrão |  |
| PICKING | String |  | Picking | `N`=Não `S`=Sim |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| VINCULOPROD | String |  | Vínculo Produto |  |

## TGWEXPL — Explosão de Lote
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODPROD | Integer |  | CODPROD |  |
| CONTROLE | String |  | CONTROLE |  |
| QUANTIDADE | Float |  | QUANTIDADE |  |
| CODENDORIGEM | Integer |  | CODENDORIGEM |  |
| DTALTER | DateTime |  | DTALTER |  |
| NUTAREFA | Integer |  | NUTAREFA |  |

## TGWEXU — Endereço Unidade
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVOL | String |  | Unidade |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| DTINICIO | Date |  | Data Início |  |
| DTFIM | Date |  | Data Fim |  |
| CODEND | Integer |  | Cod. Endereço |  |

## TGWFATAUTO — Faturamento automático WMS
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| SERIENOTA | String |  | Série para Faturamento da Nota |  |
| SITUACAO | String |  | Situação da Separação para Faturamento do Pedido | `9`=Conferência validada `17`=Aguardando conferência volumes `16`=Concluído `98`=Aguardando formação de volumes |
| DTULTFATCONFSEP | DateTime |  | Dt. Último Faturamento Automático |  |
| ENVNOTAFAT | String |  | Receber Relatório de Notas Faturadas | `S`=Sim `N`=Não |
| ENVPEDNAOFAT | String |  | Receber Relatório de Pedidos Não Faturados | `N`=Não `S`=Sim |
| FILTROFATAUTO | C |  | Filtro Faturamento Automático |  |
| EMAIL | String |  | E-mail |  |
| CODEMP | Integer |  | Empresa |  |

## TGWFEG — Faixas de Endereços por Grupo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODENDINI | Integer |  | Cód. End. Inicial |  |
| CODENDFIN | Integer |  | Cód. End. Final |  |
| CODUSU | Integer |  | Usuário Alteração |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| CODGEN | Integer |  | Cód. Grupo Endereço |  |

## TGWGEN — Grupos de Endereço
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODGEN | Integer |  | Cód. Grupo Endereço |  |

## TGWHAD — Tabela para historico de divergencias WMS
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODHAD | Integer |  | Cod. HAD |  |
| NUAGENDAMENTOID | Integer |  | Nr. único Agend. |  |
| DTINIEXEC | DateTime |  | Dh. In. Execução |  |
| DTFIMEXEC | DateTime |  | Dh. Fim Execução |  |
| QTDPROD | Integer |  | Qtd. de Registros |  |
| QTDPRODAJUST | Integer |  | Qtd. Reajustados |  |
| QTDPRODNAOAJUST | Integer |  | Qtd. Não Reajustados |  |

## TGWHAJ — Histórico de Ajustes WMS
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Cód. Empresa |  |
| CODEND | Integer |  | Cód. Endereço |  |
| CODLOCAL | Integer |  | Cód. Local |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODPROD | Integer |  | Cód. Produto |  |
| CODVOL | String |  | Cód. Volume |  |
| CONTROLE | String |  | Controle |  |
| DTVAL | DateTime |  | Dt. Validade |  |
| DTVALATU | DateTime |  | Data de Validade Atual |  |
| DTAJUSTE | DateTime |  | Dt. Ajuste |  |
| QTDAJUST | Float |  | Qtd. Ajuste |  |
| ERRO | String |  | Motivo Não Correção |  |
| TIPAJUSTE | String |  | Tipo de Ajuste |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODAJU | Integer |  | Nro. Ajuste |  |

## TGWHCT — Historico de Corte
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODMOTCORTE | Integer |  | CODMOTCORTE |  |
| QTDCORTE | Float |  | QTDCORTE |  |
| DHCORTE | DateTime |  | DHCORTE |  |
| CODUSU | Integer |  | CODUSU |  |
| NUCORTE | Integer |  | NUCORTE |  |

## TGWICC — Itens Conferidos no Coletor
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODUSU | Integer |  | Usuário |  |
| CODBARRA | String |  | Cód. Barras |  |
| CONTROLE | String |  | Controle |  |
| QUANTIDADE | Integer |  | Quantidade |  |
| QTDAVARIA | Integer |  | Qtd. Avariada |  |
| DTVAL | Date |  | Dt. Validade |  |
| NUMVOL | Integer |  | Nro. Volume |  |
| CONFUSUFINAL | String |  | Conf. Finalizada pelo Usuário | `S`=Sim `N`=Não |
| QTDPECAS | Integer |  | Qtd. de Peças |  |
| SERIESNCM | String |  | Série NCM |  |
| TIPO_LEITURA | String |  | Tipo Leitura | `S`=SSCC `E`=EAN `D`=DATAMATRIX |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |

## TGWIES — Impressão Etiquetas de Separação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODAREASEP | Integer |  | CODAREASEP |  |
| CODUSU | Integer |  | CODUSU |  |
| DHIMPRESSAO | DateTime |  | DHIMPRESSAO |  |
| NUSEPARACAO | Integer |  | NUSEPARACAO |  |

## TGWITE — Itens de Nota no WMS
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUNOTA | Integer |  | NUNOTA |  |
| SEQNOTA | Integer |  | SEQNOTA |  |
| QTDWMS | Float |  | QTDWMS |  |
| NUSEPARACAO | Integer |  | NUSEPARACAO |  |

## TGWITER — Itens Nota Recebimento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NUNOTA | Integer |  | Nro. Nota |  |
| SEQNOTA | Integer |  | Sequência Nota |  |
| QTDWMS | Float |  | Qtde. WMS |  |
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |

## TGWITT — Itens de Tarefa
Campos: 34

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |
| CODPROD | Integer |  | Cód.Produto |  |
| CODENDORIGEM | Integer |  | Cód.End.Origem |  |
| CODENDDESTINO | Integer |  | Cód.End.Destino |  |
| QTDORIG | Integer |  | Qtd. Origem |  |
| CODVOLORIG | String |  | Un. Origem |  |
| QTDDEST | Integer |  | Qtd. Destino |  |
| CODVOLDEST | String |  | Un. Destino |  |
| SITUACAO | String |  | Situação | `A`=Aberta `F`=Fechada `C`=Cancelada `E`=Em execução |
| CODUSUEXEC | Integer |  | Cód.Executante |  |
| DHINICIALEXEC | DateTime |  | Dh.Inicial |  |
| DHFINALEXEC | DateTime |  | Dh.Final |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| CODLOCAL | Integer |  | Local |  |
| CONTROLE | String |  | Controle |  |
| CODEQUIP | Integer |  | Equipamento |  |
| TIPTAREFA | String |  | Tipo |  |
| QTDVOLCOMPRA | Float |  | Qtd. Vol. Compra |  |
| CODVOLCOMPRA | String |  | Un. Compra |  |
| CODBARRAVOLCOMPRA | String |  | Cód. Barras Vol. Compra |  |
| FASETAREFA | Integer |  | Fase |  |
| CODAREASEP | Integer |  | Área de Separação |  |
| IDPALETE | Integer |  | ID. Pálete |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| OCORRENCIA | String |  | Alterado via Ocorrência? |  |
| QTDVOLPAD | Float |  | Qtd. Vol. Padrão |  |
| CODARMAZENAGEM | Integer |  | Armazenamento Expresso |  |
| TRIADO | String |  | TRIADO |  |
| IDMAPA | Integer |  | Nro. Mapa |  |
| DHIMPMAPA | DateTime |  | Dh. Imp. Mapa |  |
| DHINICIOMAPA | DateTime |  | Dh. Inicio Mapa |  |
| DHFIMMAPA | DateTime |  | Dh. Fim Mapa |  |
| NUTAREFA | Integer |  | Nro. Tarefa |  |

## TGWIVL — Itens de Volume
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cód. Produto |  |
| CONTROLE | String |  | Controle |  |
| QTDUNPAD | Float |  | Qtd. Un. Padrão |  |
| NUMVOL | Integer |  | Nro. Volume |  |
| IDREV | Integer |  | ID. Etiqueta Volume |  |
| CODCAIXA | Integer |  | CODCAIXA |  |
| CODUSU | Integer |  | Usuário |  |
| VOLCONTINUO | String |  | Volume Continuo |  |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |

## TGWIVR — Inventários Rotativos do WMS
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| CODVOL | String |  | Volume |  |
| CONTROLE | String |  | Controle |  |
| QTDESTCONTADA | Float |  | Qtd. Contada |  |
| QTDESTLOGICA | Float |  | Qtd. Lógica |  |
| QTDESTLOGICAUMA | Float |  | Qtd. Lógica UMA |  |
| QTDESTLOGICAUMAPAD | Float |  | Qtd. Lógica UMA Vol. Padrão |  |
| DIVERGENCIA | Float |  | Divergência |  |
| DHCONTAGEM | DateTime |  | Data da Contagem |  |
| CODEMP | Integer |  | Empresa |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ATIVA | String |  | Ativa | `N`=Não `S`=Sim |
| NUIVT | Integer |  | Nro. Inventário |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUAJUSTE | Integer |  | Nro. Ajuste |  |
| CODLOCAL | Integer |  | Local |  |
| QTDESTCONTADAPAD | Float |  | Qtd. Contada Vol. Padrão |  |
| QTDESTLOGICAPAD | Float |  | Qtd. Lógica Vol. Padrão |  |
| DIVERGENCIAPAD | Float |  | Divergência Vol. Padrão |  |
| IDPALETE | Integer |  | Id. Palete |  |
| DTREC | Date |  | Dt. FIFO |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| DTVAL | Date |  | Dt. Validade |  |
| CODEND | Integer |  | Endereço |  |
| TIPODIVERGENCIA | String |  | Tipo de Divergência |  |

## TGWIVRSER — Inventário por série
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQTAREFA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cód.Produto |  |
| CONTROLE | String |  | Controle |  |
| SERIE | String |  | Série |  |
| TIPOCOD | String |  | Tipo código | `S`=SSCC `E`=EAN `D`=DATAMATRIX |
| NUTAREFA | Integer |  | Nro. Tarefa |  |

## TGWIVT — Inventários do WMS
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIO | DateTime |  | Dt. Inicial |  |
| DTFINAL | DateTime |  | Dt. Final |  |
| TIPO | String |  | Tipo | `I`=Implantação `R`=Rotativo `G`=Global |
| CODEMP | Integer |  | Empresa |  |
| CODUSURESP | Integer |  | Cód. Usuário Responsável |  |
| OBSERVACAO | String |  | Observação |  |
| NUIVT | Integer |  | Nro. Inventário |  |

## TGWLBO — Liberações de Ocorreências
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQTAREFA | Integer |  | Seq. da Tarefa |  |
| SITUACAO | String |  | Situação | `N`=Negada `L`=Liberada `P`=Pendente |
| CODUSUSOLICIT | Integer |  | Operador |  |
| DHSOLICITACAO | DateTime |  | Dh. Solicitação |  |
| CODPROD | Integer |  | Produto |  |
| QTDENDERECO | Float |  | Qtd. no Endereço (na ocorrência) |  |
| QTDOUTROSEND | Float |  | Qtd. Outros Endereços |  |
| CODUSULIB | Integer |  | Usuário liberador |  |
| DHLIBERACAO | DateTime |  | Dh. Liberação |  |
| QTDFALTA | Float |  | Qtd. Falta Informada |  |
| NUTAREFA | Integer |  | Nro. Tarefa |  |
| QTDSAIDASPEND | Float |  | Total de saídas Pendentes |  |
| QTDENDATUAL | Float |  | Qtd. no Endereço (atualmente) |  |
| NUSEPARACAO | Integer |  | Nro. Separação |  |
| NUMNOTA | Integer |  | Nro. Pedido |  |

## TGWLCE — Lastro x Camada por Empresa
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| LASTRO | Integer |  | Lastro |  |
| CAMADA | Integer |  | Camada |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Nao |
| CODEMP | Integer |  | Cód.Empresa |  |

## TGWLCN — Log da Confirmação de Nota WMS
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| MENSAGEM | C |  | MENSAGEM |  |
| CODLOG | Integer |  | CODLOG |  |

## TGWLOGFATAUTO — Log faturamento automático WMS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único Pedido |  |
| LOG | C |  | Log |  |
| DHALTER | DateTime |  | Data de Alteração |  |
| NUMNOTA | Integer |  | Nro. Único Nota |  |

## TGWMCT — Motivos de Corte (WMS)
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODMOTCORTE | Integer |  | Código |  |

## TGWMDIV — Motivo de Divergência
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| TIPOCONF | String |  | Tipo Conferência | `S`=Saída `E`=Entrada |
| CODMDIV | Integer |  | Cód. Divergência |  |

## TGWMOC — Movimento de Ocorrências de WMS
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHMOV | DateTime |  | Dt. Movimento |  |
| CODOCO | Integer |  | Cód. Ocorrência |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODEND | Integer |  | Cód. Endereço |  |
| CODPROD | Integer |  | Produto |  |
| CONTROLE | String |  | Controle |  |
| CODVOL | String |  | Volume |  |
| QTD | Integer |  | Quantidade |  |
| NUTAREFA | Integer |  | Nro. Tarefa |  |
| SEQUENCIA | Integer |  | Seq. Tarefa |  |
| CODMOC | Integer |  | Cód. Mov. de Ocorrência |  |

## TGWMPR — Motivos de parada
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODMOTPAR | Integer |  | Código |  |

## TGWNCP — Conferência que não consta no pedido
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Código do produto |  |
| QTDCONFERIDA | Float |  | Qtd. Conferida |  |
| TRATADO | String |  | Tratado | `S`=Sim `N`=Não |
| NUCONFERENCIA | Integer |  | Nro. da Conferência |  |

## TGWOCO — Ocorrências de WMS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPO | String |  | Tipo | `A`=Avaria `E`=Estoque Insuficiente |
| ATIVO | String |  | Ativa? | `N`=Não `S`=Sim |
| CODOCO | Integer |  | Cód. Ocorrência |  |

## TGWOND — Onda Separação
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHALTER | DateTime |  | DHALTER |  |
| CODUSU | Integer |  | CODUSU |  |
| CODONDA | Integer |  | CODONDA |  |

## TGWPEM — TABLE TGWPEM
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CAMADAS | Integer |  | Camadas |  |
| CODRFA | Integer |  | Regra de Armazenagem |  |
| LASTRO | Integer |  | Lastro |  |
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Produto |  |

## TGWPTR — Peso Varialvel na Tarefa
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | CODPROD |  |
| CONTROLE | String |  | CONTROLE |  |
| PESO | Float |  | PESO |  |
| NUSEPARACAO | Integer |  | NUSEPARACAO |  |

## TGWPVOL — Peso do Volume
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUMVOL | Integer |  | Nro. Volume |  |
| PESO | Integer |  | Peso |  |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |

## TGWPXN — Páletes por Nota
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único Nota |  |
| SEQUENCIA | Integer |  | Sequência Nota |  |
| IDPALETE | Integer |  | Id. Pálete |  |

## TGWQCS — Quantidade de Checkouts na Separação
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDCHECKOUTS | Integer |  | QTDCHECKOUTS |  |
| NUSEPMAE | Integer |  | NUSEPMAE |  |
| NUNOTA | Integer |  | NUNOTA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUSEPARACAO | Integer |  | NUSEPARACAO |  |

## TGWQTR — Quantidade de Recontagem
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| QTDRECONTAGEM | Integer |  | QTDRECONTAGEM |  |
| NUTAREFA | Integer |  | NUTAREFA |  |

## TGWRAEE — Resultado Análise Envio Expedição
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| DESCRPROD | String |  | Descrição Produto |  |
| REFERENCIA | String |  | Referência |  |
| CONTROLE | String |  | Controle |  |
| UNIDADE | String |  | Unidade |  |
| SITUACAO | String |  | Situação da Análise |  |
| SOLUCAO | String |  | Solução |  |
| ROTINA | String |  | Rotina da Solução |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| NUNOTA | Integer |  | Número da Nota |  |
| QTDNEG | Float |  | Qtd. Negociada |  |
| ORDEMCARGA | Integer |  | Ordem de carga |  |
| CHAVEROTINA | String |  | Chave da Rotina |  |
| CODRAEE | Integer |  | Cód. Análise Envio Expedicao |  |

## TGWRAG — Reabastecimentos Agendados
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVOL | String |  | Unidade |  |
| CODEND | Integer |  | Endereço Reduzido |  |
| CONTROLE | String |  | Controle |  |
| DHINC | DateTime |  | Dt. Inclusão |  |
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Produto |  |

## TGWRARM — Relacionamento Armazenagem
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD1 | Integer |  | Cód. Produto (Origem) |  |
| CODGRUPOPROD1 | Integer |  | Cód. Grupo (Origem) |  |
| MARCA1 | String |  | Marca (Origem) |  |
| CODPROD2 | Integer |  | Cód. Produto (Destino) |  |
| CODGRUPOPROD2 | Integer |  | Cód. Grupo (Destino) |  |
| MARCA2 | String |  | Marca (Destino) |  |
| TIPO | String |  | Tipo | `P`=Permitido `N`=Negado |
| CODLIGACAO | Integer |  | Cód. Ligação |  |

## TGWRCON — Registro de Conferência
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| CODBARRA | String |  | Cód. Barras |  |
| CONTROLE | String |  | Controle |  |
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |
| QTDRECEBIDAVOLPAD | Integer |  | Qtd. Recebida Un. Padrão |  |
| QTDAVARIAVOLPAD | Integer |  | Qtd. Avaria Un. Padrão |  |
| DHINI | DateTime |  | Dt. Inicial |  |
| DHFIM | DateTime |  | Dt. Final |  |
| CODUSUCONF | Integer |  | Cód. Conferente |  |
| FECHADO | String |  | Fechado |  |
| RECONTAGEM | String |  | Recontagem |  |
| NUTAREFA | Integer |  | Nro. Tarefa |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CONFFINALIZADA | String |  | Reg. de Conf. Finalizado | `S`=Sim `N`=Não |
| DTVAL | DateTime |  | Data de Validade |  |
| UMA | String |  | U.M.A. |  |

## TGWRCS — Registro de Corte na Separação
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTAREFA | Integer |  | NUTAREFA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| NUSEPARACAO | Integer |  | NUSEPARACAO |  |

## TGWREC — Recebimentos
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SITUACAO | Integer |  | Situação | `5`=Armazenado `4`=Enviado para armazenagem `3`=Aguardando armazenagem `1`=Em processo de conferência `6`=Concluído_(+2)_ |
| DESCRSITUACAO | String |  | Situação |  |
| CODDOCA | Integer |  | Cód. Doca |  |
| CODENDDOCA | Integer |  | End. Doca |  |
| DTRECEBIMENTO | Date |  | Dt. Recebimento |  |
| NUCONFERENCIA | Integer |  | Conferência |  |
| CODPARC | Integer |  | Parceiro |  |
| NOMEPARC | String |  | Descr. Parceiro |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| NUTAREFA | Integer |  | Nro. Tarefa |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |
| NUTAREFACAN | Integer |  | Nro. Tarefa Cancelada |  |
| NUMPEDIDO2 | String |  | Nro. Pedido |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| OBSERVACAO | String |  | Observação |  |
| STATUSCONF | Integer |  | Status Conferência |  |
| CONFFINAL | String |  | Conferência Final | `N`=Não `S`=Sim |
| USACONFPARCIAL | String |  | Usa conferência parcial? | `S`=Sim `N`=Não |
| TIPONOTA | Integer |  | Tipo de Nota | `1`=Normal `2`=Retorno Devolução de Compra `3`=Retorno Cancelamento de Venda |
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |

## TGWREP — Reabastecimento Picking
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODENDCEDE | Integer |  | Cód.End.Cedente |  |
| CODENDRECEP | Integer |  | Cód.End.Receptor |  |

## TGWREV — Registros de Etiquetas de Volume
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUSEPARACAO | Integer |  | Nro. Separação |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |
| SEQETIQUETA | Integer |  | Sequência Etiqueta |  |
| DHINC | DateTime |  | Dh. Inclusão |  |
| EXIGECONF | String |  | Exige Conferência | `N`=Não `S`=Sim |
| CODUSUCONF | Integer |  | Cód.Usu.Conferente |  |
| DHINICONF | DateTime |  | Dh. Início Conferência |  |
| DHFINCONF | DateTime |  | Dh. Final Conferência |  |
| DHIMPRESSAO | DateTime |  | Dh. Impressão |  |
| SEQUENCIA | Integer |  | Sequência |  |
| PESO | Float |  | Peso |  |
| NOMEIMPRESSORA | String |  | Nome da impressora |  |
| IDREV | Integer |  | Id. Etiqueta |  |
| TOTVOLUMES | Integer |  | Tot. Volumes |  |
| CODPROD | Integer |  | Cód. Produto |  |
| DESCRPROD | String |  | Descr. Produto |  |

## TGWRFA — TABLE TGWRFA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| PADRAO | String |  | Padrão | `N`=Não `S`=Sim |
| CONFIG | C |  | Configuração |  |
| USAENDMANUAL | String |  | Endereçamento manual | `N`=Não `S`=Sim |
| CODRFA | Integer |  | Regra |  |

## TGWROM — Romaneio
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBARRACONCAT | String |  | Cód. Barras Concatenado |  |
| QTDUNPAD | Float |  | Qtd. Unid. Padrão |  |
| CODPROD | Integer |  | Cód. Produto |  |
| CODBARRA | String |  | Cód. Barras |  |
| CONTROLE | String |  | Controle |  |
| SEQUENCIA | Integer |  | Seq. Cód. Barras Concatenado |  |
| RECONTADO | String |  | Recontado |  |
| NUSEPARACAO | Integer |  | Nro. Separação |  |

## TGWRPL — Registros de Páletes
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Produto |  |
| CONTROLE | String |  | Controle |  |
| CODVOL | String |  | Volume |  |
| SEQPALETE | Integer |  | Sequência Pálete |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| IMPRESSO | String |  | Impresso | `N`=Não `S`=Sim |
| IDPALETE | Integer |  | ID. Pálete |  |

## TGWRPR — Registro de Parada
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMOTPAR | Integer |  | Motivo da Parada |  |
| DHINICIO | DateTime |  | Data Início |  |
| DHFIM | DateTime |  | Data Fim |  |
| OBSERVACAO | String |  | Observação |  |
| CODEQUIP | Integer |  | Equipamento |  |

## TGWRUMA — Registro de UMA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDPALETE | Integer |  | ID. Pálete |  |
| TIPO | String |  | Tipo |  |
| UMAAUTOMATICA | String |  | UMA Automática | `S`=Sim `N`=Não |
| CODUSU | Integer |  | Código do Usuário |  |
| DTREGISTRO | DateTime |  | Data de Registro |  |
| UMA | String |  | UMA |  |

## TGWRXN — Notas por Recebimento
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |
| STATUSNOTA | String |  | Status da Nota | `C`=Cancelada `N`=Normal |
| NUTAREFACAN | Integer |  | Nro. Tarefa de Cancelamento |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |

## TGWSEP — Separações
Campos: 39

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único |  |
| DESCRSITUACAO | Integer |  | Situação | `17`=Aguardando conferência volumes `99`=Cancelada-Possui Retorno Merc. `16`=Concluído `15`=Enviado para armazenagem `14`=Aguardando armazenagem_(+19)_ |
| CODDOCA | Integer |  | Cód. Doca |  |
| CODENDDOCA | Integer |  | Cód. End. Doca |  |
| ORDEMCARGA | Integer |  | O.C |  |
| TIPOSEP | String |  | Tipo Separação | `P`=Pedido `B`=Balcão `O`=Ordem Carga |
| PESOBRUTO | Float |  | Peso Bruto |  |
| M3BRUTO | Float |  | M3 Bruto |  |
| QTDTAREFAS | Integer |  | Qtd. Tarefas |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODAREACONF | Integer |  | Área |  |
| SITUACAO | Integer |  | Situação | `8`=Pedido totalmente cortado `7`=Aguardando conferência de volumes `6`=Concluído `5`=Conferência validada `3`=Em processo de conferência_(+3)_ |
| DTSEPARACAO | DateTime |  | Dt. Separação |  |
| NUTAREFA | Integer |  | Nro Tarefa |  |
| NUCONFERENCIA | Integer |  | Conferência |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dh. Alteração |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| STATUSCONF | Integer |  | Status Conferência |  |
| FLOWRACK | String |  | Flow Rack |  |
| QTDCXSFLOWRACK | Integer |  | Qtd. Cxs. Flow Rack |  |
| CODEMPOC | Integer |  | Cód. Emp OC |  |
| CODAREASEP | Integer |  | Cód. Área Sep |  |
| LIBERADA | String |  | Liberada |  |
| TIPOSPLIT | Integer |  | Tipo de Split de Tarefas |  |
| NROPALETE | Integer |  | Nro. Pálete |  |
| LIBERAREAB | String |  | Reabastecimento Liberado |  |
| QTDCHECKOUTS | Integer |  | Qtd. Checkouts |  |
| NUSEPMAE | Integer |  | Nro. Separação Mãe |  |
| CODONDA | Integer |  | Cód. Onda |  |
| TRIADO | String |  | Triagem Realizada | `N`=Não `S`=Sim |
| CANCELADA | String |  | Cancelada | `N`=Não `S`=Sim |
| OBSERVACAO | String |  | Observação |  |
| CODUSUCONF | Integer |  | Cod. Conferente |  |
| NOMEUSUCONF | String |  | Conferente |  |
| CODPARC | Integer |  | Cód. Parceiro Destino |  |
| SITUACAOANT | Integer |  | Situação Cancelamento Sep | `8`=Aguardando recontagem `7`=Aguardando conferência de volumes `5`=Conferência validada `4`=Conferência com divergência `3`=Em processo de conferência_(+3)_ |
| NUSEPARACAO | Integer |  | Nro. Sep. |  |
| ENVIADODOCA | String |  | Enviado p/ Doca | `S`=Sim `N`=Não |

## TGWSVAR — Ligação Separações Agrupadas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQITTFILHA | Integer |  | SEQITTFILHA |  |
| NUSEPMAE | Integer |  | NUSEPMAE |  |
| SEQITTMAE | Integer |  | SEQITTMAE |  |
| QTDFILHA | Integer |  | QTDFILHA |  |
| NUSEPFILHA | Integer |  | NUSEPFILHA |  |

## TGWSXN — Notas por separações
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUSEPARACAO | Integer |  | Nro. Separação |  |
| STATUSNOTA | String |  | Situação da Nota |  |
| NUTAREFACAN | Integer |  | Nro. Tarefa Cancelada |  |
| NUNOTA | Integer |  | Nro. Único Nota |  |

## TGWTAR — TABLE TGWTAR
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAREFA | Integer |  | Cód.Tarefa |  |
| SITUACAO | String |  | Situação | `F`=Concluído `E`=Em execução `A`=Em aberto `C`=Cancelada |
| NUTAREFAORIGEM | Integer |  | Nro. Tarefa Origem |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUCONFERENCIA | Integer |  | Nro. Conferência |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| CODPARC | Integer |  | Parceiro |  |
| DTTAREFA | DateTime |  | Dh.Geração Tarefa |  |
| SEQUENCIADEP | Integer |  | Sequência Dependente |  |
| NUTAREFADEP | Integer |  | Nro. Tarefa Dependente |  |
| NUIVT | Integer |  | Nro.Inventário |  |
| CODEMPOC | Integer |  | Empresa OC |  |
| ORDEMCARGA | Integer |  | Ordem de carga |  |
| PROATIVA | String |  | Pró-ativa |  |
| NUTAREFA | Integer |  | Nro. Tarefa |  |

## TGWTCX — Tipos de Caixa
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| NOMEABREV | String |  | Descr. Abreviada |  |
| ATIVO | String |  | Ativo? | `S`=Sim `N`=Não |
| UNIDADE | String |  | Unid. de Medida | `MM`=MM `CM`=CM `M`=M |
| ALTURA | Float |  | Altura |  |
| LARGURA | Float |  | Largura |  |
| COMPRIMENTO | Float |  | Comprimento |  |
| M3 | Float |  | Metros Cúbicos |  |
| PESOCXVAZIO | Float |  | Peso da Caixa Vazia |  |
| CODBARRA | String |  | Código de Barra |  |
| CODCAIXA | Integer |  | Cód. Caixa |  |

## TGWTDP — TABLE TGWTDP
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIADEP | Integer |  | Seq.Tarefa |  |
| NUTAREFA | Integer |  | Tarefa |  |
| SEQUENCIA | Integer |  | Sequência |  |
| QTDDEP | Integer |  | Qtde Dependente |  |
| NUTAREFADEP | Integer |  | Tarefa |  |

## TGWTEC — Tarefas em Execução no Coletor
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIATAREFA | Integer |  | SEQUENCIATAREFA |  |
| CODUSU | Integer |  | CODUSU |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODPROD | Integer |  | CODPROD |  |
| ORDEMCARGA | Integer |  | ORDEMCARGA |  |
| NUMNOTA | Integer |  | NUMNOTA |  |
| NUSEPARACAO | Integer |  | NUSEPARACAO |  |
| IDPALETE | Integer |  | IDPALETE |  |
| QTDORIGEM | Integer |  | QTDORIGEM |  |
| PRODUTO_CONTAGEM | Integer |  | PRODUTO_CONTAGEM |  |
| QTDDESTINO | Integer |  | QTDDESTINO |  |
| QTDVOLCOMPRA | Integer |  | QTDVOLCOMPRA |  |
| PESOBRUTO | Float |  | PESOBRUTO |  |
| ENDVAZIO | String |  | ENDVAZIO |  |
| TIPOIVT | String |  | TIPOIVT |  |
| CODVOLORIGEM | String |  | CODVOLORIGEM |  |
| CODVOLDESTINO | String |  | CODVOLDESTINO |  |
| ENDORIG_MULTIPROD | String |  | ENDORIG_MULTIPROD |  |
| CODVOLCOMPRA | String |  | CODVOLCOMPRA |  |
| COMPLDESC | String |  | COMPLDESC |  |
| DESCRPROD | String |  | DESCRPROD |  |
| ENDORIGEM | String |  | ENDORIGEM |  |
| DESCRENDORIGEM | String |  | DESCRENDORIGEM |  |
| ENDDESTINO | String |  | ENDDESTINO |  |
| DESCRENDDESTINO | String |  | DESCRENDDESTINO |  |
| CODBARRAORIGEM | String |  | CODBARRAORIGEM |  |
| CODBARRADESTINO | String |  | CODBARRADESTINO |  |
| CODBARRAVOLCOMPRA | String |  | CODBARRAVOLCOMPRA |  |
| CODBARRAPRODLIDO | String |  | CODBARRAPRODLIDO |  |
| PARCELAS | String |  | PARCELAS |  |
| CONTROLE | String |  | CONTROLE |  |
| SITUACAO | String |  | SITUACAO |  |
| DTVAL | Date |  | DTVAL |  |
| NUTAREFAPICKINT | Integer |  | NUTAREFAPICKINT |  |
| ENDECKTINDEF | String |  | ENDECKTINDEF |  |
| PESOSEPARADO | Integer |  | PESOSEPARADO |  |
| QTDCHECKOUTS | Integer |  | QTDCHECKOUTS |  |
| NUTAREFA | Integer |  | NUTAREFA |  |

## TGWTEQ — TABLE TGWTEQ
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| NIVELMIN | Integer |  | Nível Mínimo |  |
| NIVELMAX | Integer |  | Nível Máximo |  |
| PESOMIN | Float |  | Peso Mínimo |  |
| PESOMAX | Float |  | Peso Máximo |  |
| M3MAX | Float |  | M3 Máximo |  |
| TIPO | String |  | Tipo | `P`=Pessoa `M`=Manual `A`=Automática |
| CODTIPEQUIP | Integer |  | Cód. Tipo Equipamento |  |

## TGWTRA — Transferências do WMS
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SITUACAO | String |  | Situação | `E`=Em execução `A`=Aberta `F`=Fechada `C`=Cancelada |
| NUTAREFA | Integer |  | Nro Tarefa |  |
| CODUSU | Integer |  | Cód. Usuário Transferência |  |
| DTALTER | DateTime |  | Data Transferência |  |
| NURECEBIMENTO | Integer |  | NURECEBIMENTO |  |
| NUTRANSFERENCIA | Integer |  | Nro Transferência |  |

## TGWTRAN — Tarefas em Trânsito
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NUTAREFA | Integer |  | Número da Tarefa |  |
| QTDDIVERGCONEX | Integer |  | Qtde Divergente Conexão |  |

## TGWTRCD — Triagem Crossdocking
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBARRA | String |  | Cód. de Barra |  |
| CONTROLE | String |  | Controle |  |
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |
| QTDTRIADAVOLPAD | Integer |  | Qtd. Triada Padrão |  |
| QTDTRIADA | Integer |  | Qtd. Triada |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| CODUSUCONF | Integer |  | Cód. Usuário |  |
| CROSSDOCKING | String |  | Crossdocking | `S`=Sim `N`=Não |
| SEQUENCIA | Integer |  | Sequencia |  |
| CODPROD | Integer |  | Cód. Produto |  |

## TGWTTE — TABLE TGWTTE
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAREFA | Integer |  | Cód. Tarefa |  |
| CODTIPEQUIP | Integer |  | Cód. Equipamento |  |

## TGWTTR — Tipos de Tarefa
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRTAREFA | String |  | Descrição |  |
| CODTAREFA | Integer |  | Cod. Tarefa |  |

## TGWTUN — Tipos de Unitizador
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| DESCRABREV | String |  | Descr. Abreviada |  |
| ATIVO | String |  | Ativo? | `N`=Não `S`=Sim |
| UNIDADE | String |  | Unid. de Medida | `CM`=CM `M`=M `MM`=MM |
| ALTURA | Float |  | Altura |  |
| LARGURA | Float |  | Largura |  |
| COMPRIMENTO | Float |  | Espessura/Produndidade |  |
| M3 | Float |  | Volume (m³) |  |
| PESOMAX | Float |  | Peso (Kg) |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NUTUN | Integer |  | Nro. Unitizador |  |

## TGWUAC — Conferente
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSUCONF | Integer |  | Cód. Conferente |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODAREACONF | Integer |  | Cód. Área Conf. |  |

## TGWUAS — Separador
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSUSEP | Integer |  | Cód. Separador |  |
| DHALTER | DateTime |  | Dta. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| CODAREASEP | Integer |  | Cód. Área Sep. |  |

## TGWUSU — TABLE TGWUSU
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAREFA | Integer |  | Tarefa |  |
| ORDEM | Integer |  | Ordem tarefa |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TGWUTE — TABLE TGWUTE
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVOL | String |  | Cód. Volume |  |
| CODTIPEQUIP | Integer |  | Cód. Equipamento |  |

## TGWUTOK — Usuário Token
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TOKEN | String |  | Token |  |
| CODUSUALT | Integer |  | Usuário Alteração |  |
| DHALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Usuário |  |

## TGWUXT — TABLE TGWUXT
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVE | Integer |  | CHAVE |  |
| CODUSUEXEC | Integer |  | Cód. Usuário Executante |  |
| NUTAREFA | Integer |  | NUTAREFA |  |
| SITTAREFA | String |  | SITTAREFA |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | DTALTER |  |
| TIPTAREFA | String |  | TIPTAREFA |  |

## TGWUXU — TABLE TGWUXU
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVOL | String |  | Volume |  |
| CODUSU | Integer |  | Cód. Usuário |  |

## TGWVAE — Validação Armazenamento Expresso
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCONCATENADO | String |  | CODCONCATENADO |  |
| NUTAREFA | Integer |  | NUTAREFA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |

## TGWVCC — Volume Conferido no Coletor
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDREV | Integer |  | Nro. Etiqueta |  |
| CODUSUCONF | Integer |  | Cód. Usuário |  |
| NUSEPARACAO | Integer |  | Nro. Separação |  |

## TGWXMLS — Importação XML Série Medicamento
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único |  |
| CODPROD | Integer |  | Código do Produto |  |
| GTIN | String |  | Código GTIN |  |
| SERIE | String |  | Série |  |
| SERIEPAI | String |  | Série Pai |  |
| VALIDADE | Date |  | Data de Validade |  |
| LOTE | String |  | Lote |  |
| DTIMPORTACAO | DateTime |  | Data de Importação |  |