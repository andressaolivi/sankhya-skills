# TPR — Produção

> Gerado do dicionário oficial TDD Sankhya. 118 tabelas.


## TPRACCQ — Amostras por Ciclo de Controle de Qualidade
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NURAM | Integer |  | Nro. Amostra |  |
| CODPRODPA | Integer |  | Cód. Produto |  |
| CONTROLEPA | String |  | Controle |  |
| IDEFX | Integer |  | Cód. Atividade |  |
| IDICCQ | Integer |  | Nro. item |  |

## TPRAMP — Apontamento de Materiais
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQAPA | Integer |  | Sequência |  |
| CODPRODMP | Integer |  | Cód. Produto (MP) |  |
| REFERENCIA | String |  | Referência do Produto |  |
| CONTROLEMP | String |  | Controle (MP) |  |
| QTD | Float |  | Qtd. apontada |  |
| CODVOL | String |  | UN. |  |
| TIPOUSO | String |  | Tipo de Uso | `C`=Material Consumido `R`=Material Reaproveitado |
| SEQMP | Integer |  | Sequência MP |  |
| VINCULOSERIEPA | String |  | VINCULOSERIEPA |  |
| QTDPERDA | Float |  | Qtd. Total de Perda |  |
| CODMPE | Integer |  | Motivo de perda |  |
| QTDMPE | Integer |  | Qtd. de Motivos de Perda |  |
| CODLOCALBAIXA | Integer |  | Local de Baixa |  |
| NUAPO | Integer |  | Nro. único |  |

## TPRAPA — Apontamento de PA
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQAPA | Integer |  | Sequência |  |
| CODPRODPA | Integer |  | Cód. Produto (PA) |  |
| REFERENCIA | String |  | Referência do Produto |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| QTDAPONTADA | Float |  | Qtd. apontada |  |
| QTDPERDA | Float |  | Qtd. Total de Perda |  |
| QTDFAT | Float |  | Qtd. Baixada (PA) |  |
| QTDFATSP | Float |  | Qtd. Baixada (SP) |  |
| QTDMPE | Integer |  | Qtd. de Motivos de Perda |  |
| CODMPE | Integer |  | Motivo de perda |  |
| NUAPO | Integer |  | Nro. único |  |

## TPRAPF — Faturamento de Apontamento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQAPA | Integer |  | SEQAPA |  |
| NUNOTA | Integer |  | Nro. Único |  |
| SEQITE | Integer |  | SEQITE |  |
| QTD | Float |  | Quantidade |  |
| NUAPO | Integer |  | Apontamento |  |

## TPRAPO — Cabeçalho de Apontamento
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIATV | Integer |  | Atividade |  |
| CODUSU | Integer |  | Usuário responsável |  |
| DHAPO | DateTime |  | Dh. Apontamento |  |
| SITUACAO | String |  | Situação | `P`=Pendente `C`=Confirmado |
| OBSERVACAO | String |  | Observação |  |
| NUAPO | Integer |  | Nro. único |  |

## TPRARW — Apontamento Recursos de Work Center
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQAPA | Integer |  | SEQAPA |  |
| CODWCP | Integer |  | Centro de Trabalho |  |
| CODCRE | Integer |  | Categoria de Recurso |  |
| CODVOL | String |  | Unidade |  |
| QTDAPONTADA | Float |  | Qtd. apontada |  |
| QTDRECAPONTAR | Integer |  | QTDRECAPONTAR |  |
| QTDUTILIZADA | Float |  | Qtd. utilizada (total) |  |
| NUAPO | Integer |  | NUAPO |  |
| QTDITENSREC | Integer |  | Qtd. itens Recursos |  |

## TPRASP — Apontamento de Sub-produto
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQAPA | Integer |  | Sequência |  |
| CODPRODSP | Integer |  | Cód. Produto (SP) |  |
| REFERENCIA | String |  | Referência do Produto |  |
| CONTROLESP | String |  | Controle (SP) |  |
| QTD | Float |  | Qtd. apontada |  |
| CODVOL | String |  | UN. |  |
| NUAPO | Integer |  | Nro. único |  |

## TPRAST — Atributo de setup
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODWCP | Integer |  | Centro de Trabalho |  |
| TIPO | String |  | Tipo | `R`=Referência `M`=Texto longo `T`=Texto curto `D`=Decimal `I`=Inteiro_(+1)_ |
| ESTADOWC | String |  | Considerar como Estado do CT | `S`=Sim `N`=Não |
| PESORELATIVO | Float |  | Peso Relativo |  |
| NOMEINSTANCIAREF | String |  | Instância de Referência |  |
| ITENSLISTA | String |  | Lista |  |
| EXPVALIDACAO | String |  | Expressão |  |
| DESCRATRIBUTO | String |  | Descrição |  |
| NUAST | Integer |  | Código |  |

## TPRATV — Atividade do processo produtivo
Campos: 47

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OPERCQ | String |  | Operação a ser realizada | `T`=Amostragem + Laudo `L`=Laudo `A`=Amostragem `N`=Nenhuma |
| SUBAPOPORCONF | String |  | Tipo de Apontamento | `N`=Apontamento de PA/MP `P`=Pesagem de Volumes `S`=Conferência |
| IDRPADEST | Integer |  | Repositório de destino |  |
| DATAHORAAPONTAMENTO | String |  | Data/Hora de Apontamento | `N`=Automático Sem edição `P`=Automático Com edição `S`=Manual Com edição (Vazio) |
| IDRPAOPER | Integer |  | Repositório da operação |  |
| IDAWC | Integer |  | Alocação de C. Trabalho |  |
| PERMITEPARCIAL | String |  | Permite fluxo parcial | `N`=Não `S`=Sim |
| TIPOTEMPO | String |  | Tipo de tempo | `Q`=Por Quantidade `L`=Por Lote `F`=Fixo |
| TEMPOATIVIDADE | Float |  | Tempo da atividade |  |
| UNTEMPO | String |  | Unidade de tempo | `D`=Dias `H`=Horas `M`=Minutos |
| QTDBASEAPON | String |  | Quantidade base para apontamento | `A`=Qtd. apontada de PA `R`=Qtd. atual de PA no repositório de trabalho `L`=Qtd. do lote a produzir `N`=Não sugere |
| APONTAMP | String |  | Aponta matéria-prima | `O`=Aponta as MPs da OP `A`=Aponta as MPs da Atividade `N`=Não aponta MP |
| APONTAPA | String |  | Exige apontamento de PA | `S`=Sim `N`=Não |
| APONTACOMP | String |  | Aponta componente de manufatura | `N`=Não `S`=Sim |
| APONTASP | String |  | Aponta subproduto | `N`=Não aponta Subprodutos `O`=Aponta os Subprodutos da OP `A`=Aponta os Subprodutos da Atividade |
| PERMITENOVOPA | String |  | Apontar PA diferente em relação ao inicio do processo | `N`=Não `S`=Sim |
| TIPOREPROCESSO | String |  | Tipo de reprocesso | `T`=Reprocesso c/ quantidade total `N`=Não inicia reprocesso `P`=Reprocesso c/ quantidade parcial |
| PROIBEAPONT | String |  | Proibir apontamento à maior | `S`=Sim `N`=Não |
| ALTSTATUSPROC | String |  | Status do processo | `M`=Mantém o status atual `A`=Em andamento `C`=Cancelado `S`=Suspenso |
| CODUSULOGON | Integer |  | Usuário para logon |  |
| LISTAMPPADRAO | String |  | Lista de matéria-prima padrão | `N`=Não `S`=Sim |
| LIBERARWCFINAL | String |  | Libera centro de trabalho no final da atividade | `N`=Não `S`=Sim |
| LIBERARWCMANUAL | String |  | Libera centro de trabalho manualmente | `N`=Não `S`=Sim |
| INICIALIZARPA | String |  | Inicializa repositório de produtos acabados | `N`=Não `S`=Sim |
| CODPRCSUB | Integer |  | Subprocesso |  |
| IDCCQ | Integer |  | Ciclo controle de qualidade |  |
| VALIDACQ | String |  | Validar ciclo de controle de qualidade | `N`=Não `S`=Sim |
| IDPROC | Integer |  | IDPROC |  |
| EXECTERCEIRO | String |  | Execução Terceirizada | `S`=Sempre `O`=Opcional `N`=Nunca |
| CONCLUICQ | String |  | Conclui Ciclo de Controle de Qualidade | `N`=Não `S`=Sim |
| CONTCUMULATIVA | String |  | Contagem Cumulativa | `N`=Não `S`=Sim |
| TIPOCONFERENCIA | String |  | Tipo de Conferência | `CI`=Exige Conferências Iguais `RE`=Exige Recontagem |
| QTDCONFIGUAIS | Integer |  | Qtd. de conferências iguais |  |
| QTDRECONTAGENS | Integer |  | Qtd. de recontagens |  |
| USASEQCODBAR | String |  | Usar seq. lote no cód. barras | `N`=Não `S`=Sim |
| SEPSEQCODBAR | String |  | Separador |  |
| APONTARECWC | String |  | Aponta Recursos do Centro de Trabalho | `O`=Aponta os Recursos de CT da OP `N`=Não aponta `A`=Aponta os Recursos de CT da Atividade |
| MULTITURNO | String |  | Multi-turno | `S`=Sim `N`=Não |
| CODMTPFINTURNO | Integer |  | Motivo de parada (fim de turno) |  |
| SETUP | String |  | Considerar atividades de Setup no OEE | `N`=Não `S`=Sim |
| DESCRICAO | String |  | Descrição |  |
| PERMITEALTLOCMP | String |  | Permite alterar local de baixa da MP | `N`=Não `S`=Sim |
| PERMITEPERDATOTAL | String |  | Permitir apontamento de 100% de perda | `S`=Sim `N`=Não |
| SEQEXECUCAO | String |  | Sequencia de Execução |  |
| APROVARSTATUSLOTE | String |  | Aprova/Reprova 'Status do Lote' no Final do Ciclo | `S`=Sim `N`=Não |
| GERAMLAUDO | String |  | Gerar registro de Amostra e Laudo. | `S`=Sim `N`=Não |
| IDEFX | Integer |  | Código |  |

## TPRAUD — Auditoria
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDORIG | Integer |  | Codigo do cadastro responsavel |  |
| IDORIGAUX | Integer |  | Codigo do cadastro responsavel 2 |  |
| IDORIGAUXSUP | Integer |  | Codigo do cadastro responsavel 3 |  |
| TABACAO | String |  | Tipo de acao na tabela |  |
| COLREG | String |  | Coluna alterada |  |
| DHACAO | DateTime |  | Data e Hora ação |  |
| CODUSU | Integer |  | Usuário manipulador do registro |  |
| TABREG | String |  | Tabela alterada |  |
| CODAUT | Integer |  | Codigo Auditoria |  |

## TPRAVO — Apontamento de Volumes
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| CONTROLE | String |  | Controle |  |
| IDIPROC | Integer |  | Nro. OP |  |
| NROLOTE | String |  | Nro. Lote |  |
| IDIATV | Integer |  | IDIATV |  |
| PESOBRUTO | Float |  | Peso Bruto |  |
| PESOLIQ | Float |  | Peso Líquido |  |
| TIPO | String |  | Tipo | `P`=Perda `N`=Normal |
| NUAPO | Integer |  | Nro. Apontamento |  |
| ID | Integer |  | ID Volume |  |

## TPRAWC — Alocação de Centro de Trabalho por Processo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDAWC | Integer |  | Cód. Alocação |  |
| CODCWC | Integer |  | Categoria do Centro de Trabalho |  |
| TIPALOCACAO | String |  | Tipo Alocação | `P`=Usar CT Padrão `O`=Na inclusão manual da O.P `S`=Sugere CT Padrão (+OP no MPS) `E`=Especificar CT |
| DESCRICAO | String |  | Descrição |  |
| CODWCP | Integer |  | Centro de Trabalho |  |
| IDPROC | Integer |  | Processo |  |

## TPRBOM — Lista de Materiais p/ MRP
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQIMPS | Integer |  | Seq. IMPS |  |
| CODPRODMP | Integer |  | Matéria Prima |  |
| CONTROLEMP | String |  | Controle MP |  |
| QTDMISTURA | Float |  | Qtd. Mistura |  |
| TIPOQTD | String |  | Tipo Qtd. | `V`=Variável `F`=Fixa |
| QTDTOTAL | Float |  | Qtd. Total |  |
| TIPOPI | String |  | Tipo do PI | `O`=Sub-ordem `E`=Estoque |
| PRODINTERM | String |  | É Produto Intermediário | `S`=Sim `N`=Não |
| TIPOSUBOP | String |  | Tipo de sub-ordem | `U`=Sempre usar uma em aberto `I`=Sempre iniciar uma nova `E`=Iniciar quando não existir em aberto |
| NUMPS | Integer |  | Código MPS |  |

## TPRCAP — TPRCAP
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| UNIDADE | String |  | Unidade |  |
| UNTMP | String |  | Tempo | `H`=Hora `S`=Semana `E`=Mês `D`=Dia `M`=Minutos |
| CODCAP | Integer |  | Cód. Capacidade |  |

## TPRCCQ — Ciclo Controle de Qualidade
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCICLO | String |  | Descrição |  |
| IDPROC | Integer |  | Processo |  |
| APROVARCOMRESSALVAS | String |  | Permite aprovar laudos com ressalvas | `N`=Não `S`=Sim |
| IDCCQ | Integer |  | Cód. Controle de Qualidade |  |

## TPRCHR — TPRCHR
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCARGAHOR | Integer |  | Carga Horária |  |
| DTINICIOVIGOR | DateTime |  | Data Inicial Vigor |  |
| DTFINALVIGOR | DateTime |  | Data Final Vigor |  |
| CODRHP | Integer |  | Colaborador |  |

## TPRCMPS — Configuração para MPS
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição Configuração |  |
| DHINC | DateTime |  | Dh. Inclusão |  |
| CODUSU | Integer |  | Usuário |  |
| CONFIG | C |  | Configuração Efetiva |  |
| CODCMPS | Integer |  | Configuração MPS |  |

## TPRCOI — Item Conferencia Producao
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODBARRA | String |  | Cód. Barras |  |
| CODPROD | Integer |  | Produto |  |
| CONTROLE | String |  | Controle |  |
| QTDCONF | Integer |  | Quantidade |  |
| NUCONF | Integer |  | Conferência |  |

## TPRCONF — Cabeçalho Conferência Produção
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIATV | Integer |  | Atividade |  |
| DHINICONF | DateTime |  | Dh. Início |  |
| DHFINCONF | DateTime |  | Dh. Fim |  |
| CODUSUCONF | Integer |  | Usuário |  |
| STATUS | String |  | Status | `A`=Em Andamento `F`=Finalizada |
| NUAPO | Integer |  | NUAPO |  |
| NUCONF | Integer |  | Conferência |  |

## TPRCOP — Grupo Co-produtos
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRCOP | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODPRODMP | Integer |  | MP Compartilhada |  |
| CONTROLEMP | String |  | Controle (MP) |  |
| QTDPROCESS | Float |  | Qtd. de processamento (padrão) |  |
| CODVOL | String |  | Unidade |  |
| IDCOP | Integer |  | Código |  |

## TPRCOPLOP — Co-produtos Lançamento de OP
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQCOP | Integer |  | SEQCOP |  |
| IDCOP | Integer |  | IDCOP |  |
| QTDCONSUMIDA | Float |  | Quantidade Consumida |  |
| NULOP | Integer |  | NULOP |  |

## TPRCPM — TPRCPM
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODCPMPAI | Integer |  | Cód. Componente Pai |  |
| QTDCOMP | Integer |  | Quantidade |  |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| GRAU | Integer |  | Grau |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODCPM | Integer |  | Cód. Componente |  |

## TPRCPMP — TPRCPMP
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCPM | Integer |  | Componente de Manufatura |  |
| QTDCOMP | Integer |  | Quantidade |  |
| CODPROD | Integer |  | Produto |  |

## TPRCPR — TPRCPR
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCRE | Integer |  | Categoria de Recurso |  |
| CODCAP | Integer |  | Capacidade |  |
| CODPRODPA | Integer |  | Produto |  |
| CONTROLEPA | String |  | Controle |  |
| CODWCP | Integer |  | Centro de Trabalho |  |
| QTDCAPACIDADEMIN | Float |  | Capacidade Mínima |  |
| QTDCAPACIDADEPAD | Float |  | Capacidade Padrão |  |
| QTDCAPACIDADEMAX | Float |  | Capacidade Máxima |  |
| TIPOCAPACIDADE | String |  | Tipo da Capacidade | `A`=Adicionar/Subtrair `E`=Total |
| NUCPR | Integer |  | Núm. da Regra |  |

## TPRCRE — Categoria de recursos de work center
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCREPAI | Integer |  | Cód. Recurso Pai |  |
| NOME | String |  | Nome |  |
| TIPO | String |  | Tipo | `M`=Máquina `E`=Equipamento `O`=Mão de obra |
| CODSERVAPONTA | Integer |  | Serviço |  |
| TIPOAPONTAUSO | String |  | Tipo Apontamento | `N`=Não aponta `M`=Apontamento manual |
| PARAMSETUP | String |  | Parâmetro de Setup | `O`=Opcional `S`=Obrigatório `N`=Não |
| GRAU | Integer |  | Grau |  |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODVOL | String |  | Unidade apontamento |  |
| DECQTD | Integer |  | Qtd. decimais |  |
| CODCRE | Integer |  | Código |  |

## TPRCUSPREVP — Custo Previsto de Produção
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| NUNOTA | Integer |  | Nro. Único |  |
| CUSGER | Float |  | Custo Gerencial |  |
| CUSREP | Float |  | Custo de Reposição |  |
| CUSVAR | Float |  | Custo Variável |  |
| ENTRADACOMICMS | Float |  | Entrada com ICMS |  |
| ENTRADASEMICMS | Float |  | Entrada sem ICMS |  |
| QTDPA | Float |  | Quantidade |  |
| DTNEG | Date |  | Dt. Neg. |  |
| CODEMP | Integer |  | Empresa |  |
| CODLOCAL | Integer |  | Local |  |
| CONTROLE | String |  | Controle |  |

## TPRCWC — TPRCWC
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| TIPO | String |  | Tipo | `X`=Máquina e Mão de Obra `O`=Mão de Obra `M`=Máquina |
| TEMPOSETUP | Integer |  | Tempo de Setup |  |
| TEMPOCLEANUP | Integer |  | Tempo de Cleanup |  |
| CODCAP | Integer |  | Capacidade |  |
| QTDCAPACIDADEMIN | Float |  | Capacidade Mínima |  |
| QTDCAPACIDADEPAD | Float |  | Capacidade Padrão |  |
| QTDCAPACIDADEMAX | Float |  | Capacidade Máxima |  |
| CAPACIDADEHORA | Float |  | Capacidade por Hora |  |
| CODWCPPADRAO | Integer |  | Centro de Trabalho Padrão |  |
| CODCWC | Integer |  | Cód. Categoria |  |

## TPRDGIR — Detalhes de giro
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQIMPS | Integer |  | Seq. IMPS |  |
| PERINI | Date |  | Período Inicial |  |
| PERFIN | Date |  | Período Final |  |
| QTDGIRO | Float |  | Qtd. Giro |  |
| NUMPS | Integer |  | Cód. MPS |  |

## TPRDLOP — Dependências no Lançamento de OP
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | SEQOP |  |
| CODPRODPA | Integer |  | CODPRODPA |  |
| CONTROLEPA | String |  | CONTROLEPA |  |
| SEQOPPI | Integer |  | Sequência OP |  |
| QTDESTOQUE | Float |  | Qtd. Estoque |  |
| CODPRODPI | Integer |  | Cód.Produto |  |
| QTDNECESSARIO | Float |  | Necessidade (OP) |  |
| CONTROLEPI | String |  | Controle |  |
| NECESSIDADETOTAL | Float |  | Necessidade (Global) |  |
| QTDPI | Float |  | Qtd. Dependência |  |
| CONSIDERAESTOQUE | String |  | Considera Estoque | `N`=Não `S`=Sim |
| TIPONROLOTE | String |  | TIPONROLOTE | `I`=PA usa o mesmo lote do PI `A`=PI usa o mesmo lote do PA `L`=Nro. de lote independente |
| TIPOSUBOP | String |  | Tipo da Sub OP | `U`=Sempre usar OP em aberto `I`=Sempre iniciar nova OP `E`=Iniciar nova OP quando não existir em aberto |
| NULOP | Integer |  | NULOP |  |

## TPRDTSMP — Histórico de Substituição de MP
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDPROC | Integer |  | Cód. Composição Produto |  |
| IDEFX | Integer |  | Cód. Atividade |  |
| CODPROD | Integer |  | Cód. Produto Acabado |  |
| CONTROLE | String |  | Controle Produto Acabado |  |
| CODDTSMP | Integer |  | CODDTSMP |  |
| CODHSMP | Integer |  | CODHSMP |  |

## TPRECD — Executante Candidato
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQECD | Integer |  | Código sequencial |  |
| TIPO | String |  | Tipo | `F`=Fórmula `G`=Grupo de usuário `U`=Usuário |
| CODIGO | Integer |  | Código |  |
| FORMULA | String |  | Fórmula |  |
| NOME | String |  | Nome |  |
| IDEFX | Integer |  | Código do elemento |  |

## TPREFX — Elemento Básico de fluxo
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDPROC | Integer |  | Processo |  |
| TIPO | Integer |  | Tipo | `3101`=Evento de início `4101`=Pool `3304`=Evento intermed. sinal(Catch) `3201`=Evento final `3104`=Evento de sinal inicial_(+31)_ |
| DESCRICAO | String |  | Descrição |  |
| X1POS | Float |  | X1POS |  |
| Y1POS | Float |  | Y1POS |  |
| X2POS | Float |  | X2POS |  |
| Y2POS | Float |  | Y2POS |  |
| CORPREENCHIMENTO | String |  | CORPREENCHIMENTO |  |
| TAMFONTE | Integer |  | TAMFONTE |  |
| CORFONTE | String |  | CORFONTE |  |
| IDEFXLANE | Integer |  | IDEFXLANE |  |
| WAYPOINTS | C |  | WAYPOINTS |  |
| IDEFX | Integer |  | Código |  |

## TPREIATV — Execução de Atividade
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIATV | Integer |  | Cód. Inst. Atividade |  |
| CODEXEC | Integer |  | Cód. Executante |  |
| CODUSU | Integer |  | Cód. Responsável |  |
| DHINICIO | DateTime |  | Dh. Início |  |
| DHFINAL | DateTime |  | Dh. Final |  |
| TIPO | String |  | Tipo | `S`=Suspenso `T`=Fim de turno `P`=Parada `N`=Normal |
| CODMTP | Integer |  | Motivo Parada |  |
| OBSERVACAO | String |  | Observação |  |
| IDEIATV | Integer |  | Código |  |

## TPREQP — TPREQP
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| CODCRE | Integer |  | Categoria de Recurso |  |
| CODPLP | Integer |  | Planta de Manufatura |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| NUEQP | Integer |  | Cód. Equipamento |  |

## TPRESR — Estoque por repositório de PA
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDRPA | Integer |  | Cód. Repositório |  |
| IDIPROC | Integer |  | Nro. OP |  |
| CODPRODPA | Integer |  | Cód. Produto |  |
| CONTROLEPA | String |  | Controle |  |
| CODCPM | Integer |  | Cód. Componente |  |
| STATUSEXEC | String |  | Status | `R`=Reprocesso `N`=Normal |
| ESTOQUE | Float |  | Estoque |  |
| ESTOQUEPERDA | Float |  | Qtd. Perdida |  |
| REFERENCIA | String |  | Referência do Produto |  |

## TPRESTSMP — Histórico de Substituição de MP
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODMP | Integer |  | Cód. Produto |  |
| CONTROLE | String |  | Controle Produto Acabado |  |
| CODLOCAL | Integer |  | Cód. Local |  |
| DTVAL | Date |  | Data de Validade |  |
| ESTOQUE | Float |  | Estoque |  |
| TIPO | String |  | Tipo | `T`=Terceiro `P`=Próprio |
| CODESTSMP | Integer |  | CODESTSMP |  |
| CODHSMP | Integer |  | CODHSMP |  |

## TPREVPI — Evento de Produto Intermediario
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODPRODPI | Integer |  | Produto (PI) |  |
| CONTROLEPI | String |  | Controle (PI) |  |
| IDEFX | Integer |  | Elemento |  |

## TPREVT — Evento de Fluxo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFXANEXADO | Integer |  | Atividade Anexada |  |
| IDENTIFICADOR | String |  | Identificador |  |
| IDRPAINICIALIZA | Integer |  | Repositório de Inicialização |  |
| INTERROMPE | String |  | Interrompe Atividade | `S`=Sim `N`=Não |
| IDEFX | Integer |  | Código |  |

## TPRFORM — TPRFORM
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDPROC | Integer |  | Processo |  |
| DESCRICAO | String |  | Descrição |  |
| NOMEINSTANCIAREF | String |  | Formulário de Referência |  |
| CARDINALIDADE | String |  | Cardinalidade | `N`=1 x N `1`=1 x 1 |
| ESCOPO | String |  | Escopo | `P`=Processo `A`=Atividade |
| TIPOFORM | String |  | Tipo de Formulário | `A`=Formulário de atividade `I`=Formulário de inicialização |
| ORDEMINICIA | Integer |  | Ordem |  |
| OBRIGATORIOINICIA | String |  | Obrigatório | `N`=Não `S`=Sim |
| IDFORM | Integer |  | Cód. Formulário |  |

## TPRFPA — Formulário Produto Acabado
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDFORM | Integer |  | Cód. Formulário |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| IDPROC | Integer |  | IDPROC |  |

## TPRFRME — Formulário por elemento de fluxo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDFORM | Integer |  | Formulário |  |
| ORDEM | Integer |  | Ordem |  |
| TIPOACESSO | String |  | Tipo de acesso | `0`=Somente leitura `1`=Leitura e gravação |
| OBRIGATORIO | String |  | Obrigatório | `S`=Sim `N`=Não |
| IDEFX | Integer |  | Código |  |

## TPRFTL — Fórmula para tamanho de lote
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCFORMULA | String |  | Descrição |  |
| EXPRESSAO | String |  | Expressão |  |
| IDFORMULA | Integer |  | Id Fórmula |  |

## TPRFXT — Filtros a serem avaliados na transição
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOFILTRO | String |  | Tipo | `W`=Necessidade de Setup para Centro de Trabalho `S`=Condição personalizada `E`=Estoque disponível de MP `P`=Produto Acabado em Processamento |
| SEQUENCIA | Integer |  | Código |  |
| IDEFXBASE | Integer |  | Atividade Base |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODPRODMP | Integer |  | Matéria-prima |  |
| CONTROLEMP | String |  | Controle (MP) |  |
| CODEMP | Integer |  | Empresa |  |
| CODLOCAL | Integer |  | Local |  |
| EXPSQL | String |  | Expressão |  |
| IDEFX | Integer |  | Elemento |  |

## TPRGTW — Gateway de fluxo
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFX | Integer |  | IDEFX |  |

## TPRHMRP — TPRHMRP
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| CONTROLE | String |  | Controle |  |
| SEQIMRP | Integer |  | SEQIMRP |  |
| DTMOV | DateTime |  | Data de Solicitação |  |
| QTDMOV | Float |  | Quantidade |  |
| CODUSU | Integer |  | Usuário Responsável |  |
| CANCELADO | String |  | Cancelado | `S`=Sim `N`=Não |
| DTCANC | DateTime |  | Data de Cancelamento |  |
| CODUSUCANC | Integer |  | Usuário do Cancelamento |  |
| NUMPS | Integer |  | MPS |  |

## TPRHSMP — Histórico de Substituição de MP
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMPSUBS | Integer |  | Cód. MP Substituída |  |
| DESCRMPSUBS | String |  | Descr. MP Substituída |  |
| CODMPNOVA | Integer |  | Cód. MP Nova |  |
| DESCRMPNOVA | String |  | Descr. MP Nova |  |
| DHSUBS | DateTime |  | Dh. Substituição |  |
| CODUSU | Integer |  | Código do Usuário |  |
| CODHSMP | Integer |  | CODHSMP |  |

## TPRHWXA — Historico de Uso Work Center por Atividade
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIPROC | Integer |  | Nro. OP |  |
| IDIATV | Integer |  | Atividade |  |
| DESCRATV | String |  | Descrição Atividade |  |
| DHALOC | DateTime |  | Dh. Alocação |  |
| CODUSUALOC | Integer |  | Usuário Alocação |  |
| DHLIBALOC | DateTime |  | Dh. Liberação |  |
| CODUSULIBALOC | Integer |  | Usuário Liberação |  |
| CODWCP | Integer |  | Centro Trabalho |  |

## TPRIARW — Itens Apontamento Recurso de Work Center
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQAPA | Integer |  | SEQAPA |  |
| CODWCP | Integer |  | Centro de Trabalho |  |
| CODCRE | Integer |  | Categoria de Recurso |  |
| CODMQP | Integer |  | Cód. Máquina |  |
| NUEQP | Integer |  | Cód. Equipamento |  |
| CODRHP | Integer |  | Cód. Colaborador |  |
| NUAPO | Integer |  | NUAPO |  |

## TPRIATV — Mantem dados sobre uma instância de atividade de usuário.
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SITUACAO | String |  | Situação | `G`=Aguardando aceite `A`=Aceita `I`=Iniciada `F`=Finalizada `P`=Parada |
| STATUSINSTCICLOCONTQUAL | String |  | Status Instância Ciclo Controle de Qualidade | `R`=Reprovado `E`=Aprovado com Ressalvas `A`=Aprovado `I`=Não Iniciado `P`=Em Andamento |
| DESCRGRUPOPRODPA | String |  | Descr. Grupo do Produto |  |
| DESCRPRODPA | String |  | Descrição do Produto |  |
| REFERENCIA | String |  | Referência do Produto |  |
| IDIATV | Integer |  | Código |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| NROLOTE | String |  | Nro. Lote |  |
| CODPRODPA | Integer |  | Cód. Produto |  |
| CONTROLEPA | String |  | Controle |  |
| CODGRUPOPRODPA | Integer |  | Grupo do Produto |  |
| COMPLDESCPA | String |  | Complemento do Produto |  |
| CODVOLPA | String |  | Un. Lote |  |
| QTDPRODUZIR | Float |  | Tam. Lote |  |
| MULTIPRODUTO | String |  | Multi-produto | `N`=Não `S`=Sim |
| DHINCLUSAO | DateTime |  | Dh. Entrada Atividade |  |
| DHACEITE | DateTime |  | Dh. Aceite Atividade |  |
| CODPARCTERC | Integer |  | Cód. Parceiro Terceiro |  |
| DHINICIO | DateTime |  | Dh. Inicio Atividade |  |
| CODUSU | Integer |  | Cód. Usuário Inicial |  |
| DHFINAL | DateTime |  | Dh. Fim Atividade |  |
| DHINIPREV | DateTime |  | Dt./Hr. Início Prev. |  |
| DHFINPREV | DateTime |  | Dt./Hr. Final Prev. |  |
| IDEFX | Integer |  | Atividade |  |
| CODWCP | Integer |  | Centro de Trabalho |  |
| IDEXECWFLOW | String |  | Token |  |
| CODEXEC | Integer |  | Executante |  |
| TEMPOGASTOMIN | Integer |  | Tempo Gasto em Minutos |  |
| CODUSUFIN | Integer |  | Cód. Usuário Final |  |
| CODULTEXEC | Integer |  | Último Executante |  |
| CODMTP | Integer |  | Motivo Parada |  |
| IDIPROC | Integer |  | Nro. OP |  |

## TPRICCQ — Item do Ciclo de Controle de Qualidade
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIPROC | Integer |  | Nro. OP |  |
| IDCCQ | Integer |  | Cód.C.Qualidade |  |
| STATUSCICLO | String |  | Status do Ciclo | `A`=Em andamento `C`=Concluído |
| DHINICIO | DateTime |  | Dh. Início |  |
| DHFINAL | DateTime |  | Dh. Final |  |
| RESULTADO | String |  | Resultado | `E`=Aprovado Com Ressalvas `R`=Reprovado `A`=Aprovado |
| IDSUBFLUXO | String |  | IDSUBFLUXO |  |
| IDICCQ | Integer |  | Nro. único |  |

## TPRICOP — Instância Co-produtos na OP
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDICOP | Integer |  | Nro. OP Conjunta |  |
| IDCOP | Integer |  | Grupo Co-produto |  |
| QTDCONSUMIDA | Float |  | Quantidade Consumida |  |
| IDIPROC | Integer |  | Ordem Producão |  |

## TPRIDEP — Dependencia entre OPs
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIPROCPA | Integer |  | Nro. OP dependente |  |
| CODPRODPI | Integer |  | Produto (PI) |  |
| REFERENCIAPI | String |  | Referência do Produto(PI) |  |
| CONTROLEPI | String |  | Controle (PI) |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| REFERENCIAPA | String |  | Referência do Produto(PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| DHINC | DateTime |  | Data e hora da inclusão |  |
| QTDDEP | Float |  | Qtd. do PI da qual depende o PA |  |
| IDIPROCPI | Integer |  | Nro. OP principal |  |

## TPRILOP — Item de lançamento de OP
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | Sequência |  |
| SEQCOP | Integer |  | Seq. Produção Conjunta |  |
| CODPLP | Integer |  | Cód. Planta |  |
| TIPOOP | String |  | Tipo de Ordem | `PC`=Produção Conjunta `R`=Reprocessamento/Reparo `P`=Produção `D`=Desmonte |
| ORDEM | Integer |  | ORDEM |  |
| COMPARTILHA | String |  | COMPARTILHA | `S`=Sim `N`=Não |
| IDPROC | Integer |  | IDPROC |  |
| NUNOTA | Integer |  | Nro. Pedido |  |
| SEQNOTA | Integer |  | Sequência do Item |  |
| TEMPOATRAVESS | Float |  | Tempo de Atravessamento (min) |  |
| CODPROD | Integer |  | Cód.Produto |  |
| CODPARCTERC | Integer |  | Cód. Parceiro |  |
| DESCRPROD | String |  | Produto Acabado |  |
| REFERENCIA | String |  | Referência do Produto |  |
| TAMLOTE | Float |  | Tam.Lote |  |
| DTINICIOMAX | DateTime |  | Dh. Inicialização (máx) |  |
| DTPREVENT | DateTime |  | Previsão de Entrega |  |
| QTDPA | Integer |  | Qtd. Produtos |  |
| CONTROLE | String |  | Controle |  |
| NULOP | Integer |  | NULOP |  |

## TPRIMPA — Item Materia Prima Alternativa
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto(PA) |  |
| CONTROLEPA | String |  | Controle(PA) |  |
| CODPRODMP | Integer |  | Máteria Prima |  |
| CONTROLEMP | String |  | Controle(MP) |  |
| CODPRODMPALT | Integer |  | Máteria Prima Alternativa |  |
| CONTROLEMPALT | String |  | Controle(MP Alternativa) |  |
| ORDEM | Integer |  | Ordem |  |
| QTDMISTURA | Float |  | Qtd. Mistura |  |
| QTDFATNOTA | Float |  | QTDFATNOTA |  |
| IDIPROC | Integer |  | OP |  |

## TPRIMPS — Itens Plano Mestre de Produção
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDPROC | Integer |  | Processo Produtivo |  |
| CODPROD | Integer |  | Produto |  |
| CONTROLE | String |  | Controle |  |
| CODPRC | Integer |  | Processo Produtivo |  |
| VERSAO | Integer |  | Versão Processo |  |
| CODVOL | String |  | Un. |  |
| QTDGIROMEDIOCALC | Float |  | Qtd. Giro Médio Calc. |  |
| DTPREVENT | DateTime |  | Previsão de Entrega |  |
| TEMPOATRAVESS | Float |  | Tempo de Atravessamento (min) |  |
| DTINICIOMAX | DateTime |  | Dh. Inicialização (máx) |  |
| DTPREVENTPAI | Date |  | DTPREVENTPAI |  |
| QTDGIRMEDIO | Float |  | Giro Médio |  |
| QTDDEMBRUTA | Float |  | Demanda Bruta |  |
| QTDDEMINDIRETA | Float |  | Demanda Indireta |  |
| QTDDEMAJUSTADA | Float |  | Demanda Ajustada |  |
| QTDESTOQUE | Float |  | Estoque |  |
| QTDOUTROSPLAN | Float |  | Qtd. Outros Planos |  |
| QTDOPPENDENTE | Float |  | Outras OPs Pendentes |  |
| QTDPRODUZIRCALC | Float |  | À Produzir Calc. |  |
| QTDPRODUZIRAD | Float |  | À Produzir Ad. |  |
| QTDPEDCOMPRA | Float |  | Pedido de Compra |  |
| QTDPRODUZIRLIQ | Float |  | À Produzir Liq. |  |
| QTDEMOP | Float |  | Qtd. em OPs |  |
| QTDEMPROGRAMACAO | Float |  | Qtd. em Programação |  |
| QTDSALDOPRODUZIR | Float |  | Saldo a Produzir |  |
| PERCESTSOBDEMANDA | Float |  | % Estoque x Demanda |  |
| QTDBASEMRP | Float |  | Qtd. Base MRP |  |
| FIXADO | String |  | Fixado | `S`=Sim `N`=Não |
| PRODINTERM | String |  | Produto Intermediário | `S`=Sim `N`=Não |
| QTDDEMANDALIQ | Float |  | Demanda Líquida |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| SEQIMPSPAI | Integer |  | SEQIMPSPAI |  |
| SEQIMPS | Integer |  | Seq. Itens MPS |  |
| NUNOTA | Integer |  | Número da Nota |  |
| SEQNOTA | Integer |  | Sequência da Nota |  |
| NUMPS | Integer |  | Cód. MPS |  |

## TPRIMRP — Itens resultado do MRP
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODMP | Integer |  | Produto |  |
| CONTROLEMP | String |  | Controle |  |
| NECESSCOMPRA | String |  | Necessidade de Compra | `S`=Sim `N`=Não |
| QTDMRP | Float |  | Qtd. MRP |  |
| QTDCOT | Float |  | Qtd. Cotação |  |
| QTDPEDCOMPRA | Float |  | Qtd. Ped. Compra |  |
| QTDESTOQUE | Float |  | Estoque |  |
| QTDSALDO | Float |  | Saldo |  |
| SEQIMRP | Integer |  | SEQIMRP |  |
| PRODINTERM | String |  | Prod. Itermediário | `S`=Sim `N`=Não |
| QTDSALDOTOTAL | Float |  | Saldo Total |  |
| DATAPDC | DateTime |  | Ponto de Pedido |  |
| NUMPS | Integer |  | Código |  |

## TPRINOTA — Instância Item Nota
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| SEQNOTA | Integer |  | SEQNOTA |  |
| DTPREVENT | DateTime |  | DTPREVENT |  |
| IDIPROC | Integer |  | IDIPROC |  |

## TPRIPA — PAs a serem produzidos na instância
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| REFERENCIA | String |  | Referência do Produto |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| QTDPRODUZIR | Float |  | Qtd. |  |
| SALDOOP | Float |  | Saldo a Produzir |  |
| NROLOTE | String |  | Nro.Lote |  |
| CONCLUIDO | String |  | Concluído | `N`=Não `S`=Sim |
| DTVAL | Date |  | Data de Validade |  |
| DTFAB | Date |  | Data de Fabricação |  |
| QTDPRODUZIR_ORIGINAL | Float |  | Qtd. Sem Ajuste |  |
| IDIPROC | Integer |  | Código do Cabeçalho |  |

## TPRIPROC — Manter dados de tempo de execução de uma ordem
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DECQTD | Integer |  | Qtd. Casas Decimais |  |
| NROLOTE | String |  | Nro. Lote |  |
| QTDPRODUZIR | Float |  | Tam. Lote |  |
| SALDOOP | Float |  | Saldo a Produzir |  |
| STATUSPROC | String |  | Status | `S2`=Suspendendo `S`=Suspenso `C`=Cancelado `A`=Em andamento `F`=Finalizado_(+5)_ |
| CODPRODPA | Integer |  | Cód. Produto |  |
| REFERENCIA | String |  | Referência do Produto |  |
| DESCRPRODPA | String |  | Descr. Produto |  |
| CONTROLEPA | String |  | Controle |  |
| COMPLDESCPA | String |  | Compl. Produto |  |
| DHINC | DateTime |  | Dh. Inclusão |  |
| DHINST | DateTime |  | Dh. Inicialização |  |
| DHTERMINO | DateTime |  | Dh. Finalização |  |
| DESCRICAO | String |  | Operação Atual |  |
| CODPARCTERC | Integer |  | Parceiro Terceiro |  |
| DTPREVENT | DateTime |  | Previsão de Entrega |  |
| TEMPOATRAVESS | Float |  | Tempo de Atravessamento (min) |  |
| DTINICIOMAX | DateTime |  | Dh. Inicialização (máx) |  |
| NUNOTA | Integer |  | Nro. Pedido |  |
| CODUSUFINAL | Integer |  | Usuário Finalizante |  |
| CODEXEC | Integer |  | Executante Atual |  |
| NUMPS | Integer |  | NUMPS |  |
| SEQNOTA | Integer |  | Sequência do Item Nota/Pedido |  |
| NOMEEXEC | String |  | Nome do Exec. |  |
| NOMERPA | String |  | Fase do processo |  |
| IDICOP | Integer |  | Nro. OP Conjunta |  |
| QTDRPA | Float |  | Qtd. na Fase |  |
| PRIORIDADE | Integer |  | Prioridade |  |
| IDPROC | Integer |  | Processo |  |
| MULTIPRODUTO | String |  | Multi-produtos | `S`=Sim `N`=Não |
| CODPLP | Integer |  | Planta |  |
| CODPARC | Integer |  | Parceiro |  |
| IDWFLOW | String |  | Código do Workflow |  |
| CODUSUINC | Integer |  | Usuário |  |
| IDIPROCPAI | Integer |  | Nro. OP Principal |  |
| CODGRUPOPRODPA | Integer |  | Grupo do Produto (PA) |  |
| IDIPROC | Integer |  | Nro. OP |  |
| PERIODOMPS | String |  | Periodo MPS |  |

## TPRIRPA — Inicialização de Repositório
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle |  |
| TIPO | String |  | Tipo do item inicializado | `P`=Produto Acabado `S`=Componente de manufatura |
| CODCPM | Integer |  | Componente de manufatura |  |
| IDEFX | Integer |  | Código |  |

## TPRISP — Tabela Instancia Subproduto
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFX | Integer |  | Atividade |  |
| SEQLSP | Integer |  | Sequência |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| CODPRODSP | Integer |  | Subproduto |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CONTROLESP | String |  | Controle (SP) |  |
| NROLOTE | String |  | Nro.Lote |  |
| DTVAL | Date |  | Data de Validade |  |
| DTFAB | Date |  | Data de Fabricação |  |
| IDIPROC | Integer |  | IDIPROC |  |

## TPRITECOP — Co-produtos
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| PERCQTDREND | Float |  | Rendimento Previsto (%) |  |
| PERCDESVIOINF | Float |  | Desvio Inferior |  |
| PERCDESVIOSUP | Float |  | Desvio Superior |  |
| CODVOL | String |  | CODVOL |  |
| IDCOP | Integer |  | IDCOP |  |

## TPRITELOP — Item Lançamento OP Item Nota
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | SEQOP |  |
| NUNOTA | Integer |  | NUNOTA |  |
| SEQNOTA | Integer |  | SEQNOTA |  |
| DTPREVENT | DateTime |  | DTPREVENT |  |
| NULOP | Integer |  | NULOP |  |

## TPRITE_PERDA — Registro de Perda em Notas de Produção
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único Nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| QTDPERDA | Float |  | Qtd. Perda |  |

## TPRIWC — Indisponibilidade de Work Center
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODWCP | Integer |  | Centro de Trabalho |  |
| MOTIVO | String |  | Motivo | `M`=Manutenção Preventiva `P`=Parada `S`=Setup `C`=Manutenção Corretiva |
| DHINCIAL | DateTime |  | Data/Hora Inicial |  |
| DHFINAL | DateTime |  | Data/Hora Final |  |
| SITUACAO | String |  | Situação | `P`=Pendente `C`=Cancelada `F`=Finalizada |
| DHALTER | DateTime |  | Data/Hora Alteração |  |
| CODUSU | Integer |  | Usuário Alteração |  |
| OBSERVACAO | String |  | Observação |  |
| NUIWC | Integer |  | NUIWC |  |

## TPRLCCQ — Laudo por Ciclo de controle de qualidade
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUCLL | Integer |  | Nro. Laudo |  |
| IDEFX | Integer |  | Cód. Atividade |  |
| IDICCQ | Integer |  | Cód.C.Qualidade |  |

## TPRLMP — ListaMateriaisAtividade
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| IDEFX | Integer |  | Elemento |  |
| CODPRODMP | Integer |  | Matéria-prima |  |
| CONTROLEMP | String |  | Controle (MP) |  |
| TIPOCONTROLEMP | String |  | Tipo de Controle (MP) | `H`=Herdar do PA `L`=Literal `I`=Automático |
| REFERENCIA | String |  | Referência do Produto |  |
| FIXAQTDAPO | String |  | Fixar qtd. apontada da MP ao editar qtd. apontada do PA | `N`=Não `S`=Sim |
| TIPOUSOMP | String |  | Tipo de Uso do Material | `A`=Usada em Ajustes `N`=Usada na Operação Normal `R`=Reaproveitamento em Desmonte |
| TIPOQTD | String |  | Tipo de Quantidade | `F`=Fixa `V`=Variável |
| QTDMISTURA | Float |  | Quantidade |  |
| CODVOL | String |  | Unidade |  |
| VERIFICAEST | String |  | Verifica Estoque | `N`=Não `S`=Sim |
| GERAREQUISICAO | String |  | Gera Requisição | `N`=Não `S`=Sim |
| CODLOCALORIG | Integer |  | Local de Origem |  |
| CODLOCALBAIXA | Integer |  | Local de Baixa |  |
| PERCDESVIOINF | Float |  | % Desvio inferior |  |
| PERCDESVIOSUP | Float |  | % Desvio superior |  |
| CONSUREFUGO | String |  | Material consumido por refugo | `S`=Sim `N`=Não |
| VINCULOSERIEPA | String |  | Vínculo direto com série do PA | `S`=Sim `N`=Não |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| LIBERADESVIO | String |  | Solicitar liberação ao exceder desvio | `S`=Sim `N`=Não |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| ESTOQUETERCEIRO | String |  | Estoque de terceiro | `S`=Sim `N`=Não |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| PROPMPFIXA | String |  | Proporcionalizar matéria-prima do tipo Fixa | `N`=Não `S`=Sim |
| SEQMP | Integer |  | Sequência |  |

## TPRLND — Lane de Diagrama
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDRPAPADRAO | Integer |  | IDRPAPADRAO |  |
| IDEFXPOOL | Integer |  | IDEFXPOOL |  |
| IDEFX | Integer |  | IDEFX |  |

## TPRLOP — Lançamento de OP
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | DESCRICAO |  |
| DHINC | DateTime |  | DHINC |  |
| CODUSU | Integer |  | CODUSU |  |
| REUTILIZAR | String |  | REUTILIZAR | `N`=Não `S`=Sim |
| NUMPS | Integer |  | NUMPS |  |
| NULOP | Integer |  | NULOP |  |

## TPRLPA — Produto Acabado
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VALIDAVERSAO | String |  | VALIDAVERSAO | `S`=Sim `N`=Não |
| CODPRODPA | Integer |  | Produto |  |
| REFERENCIA | String |  | Referência do Produto |  |
| TAMLOTEPAD | Float |  | Tamanho de Lote Padrão |  |
| CONTROLEPA | String |  | Controle |  |
| MULTIDEAL | Float |  | Múltiplo Ideal |  |
| QTDPRODMIN | Float |  | Qtd. Mínima |  |
| TIPOTEMPO | String |  | Tipo de Tempo | `Q`=Por Quantidade `L`=Por Lote |
| TEMPOATRAVESS | Float |  | Tempo de Atravessamento |  |
| TEMPOFIXO | Float |  | Tempo de Atravessamento (parte fixa) |  |
| UNTEMPOATRAVESS | String |  | Un. Tempo | `M`=Minutos `H`=Horas `D`=Dias |
| BASCALCDTVAL | String |  | Base para cálculo da Dt.Validade | `I`=Data de inicialização da OP `N`=Não calcula `M`=Menor Dt.Validade das MPs `F`=Data da primeira nota de produção do lote |
| TIPOGERASERIE | String |  | Tipo de geração do Nro. de Série | `P`=Manual (apontamento) `A`=Automática `L`=Manual (lançamento) `G`=Automático (Série Global) |
| MASCSERIE | String |  | Máscara do Nro. Série |  |
| CODLOCDEST | Integer |  | Local de Destino |  |
| IDFORMULA | Integer |  | Fórmula p/ Ajuste Tamanho de Lote |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| IDPROC | Integer |  | Cód. Composição |  |

## TPRLPI — Produto Intermediário Processo
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODPRODPI | Integer |  | Produto (PI) |  |
| REFERENCIA | String |  | Referência do Produto |  |
| CONTROLEPI | String |  | Controle (PI) |  |
| CONSIDERAQTDEST | String |  | Considerar quantidade em estoque | `S`=Sim `N`=Não |
| TIPOPI | String |  | Tipo do PI | `E`=Estoque `O`=Sub-ordem |
| TIPOSUBOP | String |  | Tipo de sub-ordem | `U`=Sempre usar uma em aberto `E`=Iniciar quando não existir em aberto `I`=Sempre iniciar uma nova |
| AGUARDARSUBOP | String |  | Aguardar a sub-ordem | `S`=Sim `N`=Não |
| TIPONROLOTE | String |  | Tipo de numeração de lote | `A`=PI usa o mesmo lote do PA `L`=Nro. de lote independente `I`=PA usa o mesmo lote do PI |
| REDIMENSIONAPA | String |  | Redimensionar PA | `O`=Opcional `E`=Sempre `U`=Nunca |
| BLOQINITPA | String |  | Bloquear Inicialização do (PA) manual | `S`=Sim `N`=Não |
| REDIMENSIONAPAPERDA | String |  | Redimensionar PA na Perda | `O`=Opcional `E`=Sempre `U`=Nunca |
| CONSIDERALOTEPI | String |  | Considerar o lote da sub-ordem nas mov. acessórias | `S`=Sim `N`=Não |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| IDPROC | Integer |  | Processo |  |

## TPRLSP — Lista de Subprodutos
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQLSP | Integer |  | Sequência |  |
| CODPRODPA | Integer |  | Produto |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODPRODSP | Integer |  | Subproduto |  |
| TIPOCONTROLESP | String |  | Tipo de Controle | `L`=Literal `H`=Herdar do PA |
| REFERENCIA | String |  | Referência do Produto |  |
| CONTROLESP | String |  | Controle |  |
| TIPOQTD | String |  | Tipo de Quantidade | `F`=Fixa `V`=Variável |
| QTDMISTURA | Float |  | Quantidade |  |
| CODVOL | String |  | Unidade |  |
| EXIGEAPONTAMENTO | String |  | Exige Apontamento | `S`=Sim `N`=Não |
| CODLOCAL | Integer |  | Local de Destino |  |
| BASCALCDTVALSP | String |  | Base para cálculo da Dt.Validade | `N`=Não calcula `I`=Data de inicialização da OP `F`=Data da primeira nota de produção do lote `M`=Menor Dt.Validade das MPs |
| SUBPRODUTOPERDA | String |  | Subproduto por Perda/Refugo | `S`=Sim `N`=Nao |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| IDEFX | Integer |  | Elemento |  |

## TPRLTA — TPRLTA
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQTAC | Integer |  | Sequência |  |
| CODCLT | Integer |  | Padrão de Classificação |  |
| OBRIGATORIO | String |  | Obrigatório | `N`=Não `S`=Sim |
| IDCCQ | Integer |  | Controle de Qualidade |  |

## TPRMER — Registro das movientações entre repositórios de PA
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQMER | Integer |  | Sequência |  |
| IDRPA | Integer |  | Repositório |  |
| IDIPROC | Integer |  | Instância de Processo |  |
| IDIATV | Integer |  | Instância de Atividade |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| QTD | Float |  | Qtd. movimentada |  |
| QTDPERDA | Float |  | Qtd. Perdida |  |
| SINAL | Integer |  | Sinal da Operação | `-1`=Saída `1`=Entrada |
| DHMOV | DateTime |  | Dh. Movimentação |  |
| STATUSEXEC | String |  | Status |  |
| CODCPM | Integer |  | Componente de Manufatura |  |
| IDMER | Integer |  | Código |  |

## TPRMPA — Material Alternativo
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQMPA | Integer |  | Sequência |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODPRODMP | Integer |  | Matéria-prima |  |
| REFERENCIAMP | String |  | Referência do Produto(MP) |  |
| CONTROLEMP | String |  | Controle (MP) |  |
| CODPRODMPALT | Integer |  | Material Alternativo |  |
| REFERENCIAMPALT | String |  | Referência do Produto(Alternativo) |  |
| CONTROLEMPALT | String |  | Controle |  |
| QTDMISTURA | Float |  | Quantidade |  |
| CODVOL | String |  | Unidade |  |
| USOMPA | String |  | Tipo de Uso | `P`=Preferencial `A`=Alternativo |
| CONJUNTO | Integer |  | Conjunto |  |
| CODLOCALORIG | Integer |  | Local de Origem |  |
| CODLOCALBAIXA | Integer |  | Local de Baixa |  |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| IDEFX | Integer |  | Elemento |  |

## TPRMPALOP — TABLE TPRMPALOP
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | Seq. OP |  |
| CODPRODPA | Integer |  | Produto Acabado(PA) |  |
| CONTROLEPA | String |  | Controle(PA) |  |
| CODPRODMP | Integer |  | Máteria Prima |  |
| CONTROLEMP | String |  | Controle(MP) |  |
| CODPRODMPALT | Integer |  | Máteria Prima Alternativa |  |
| CONTROLEMPALT | String |  | Controle (MP Alternativa) |  |
| ORDEM | Integer |  | Ordem |  |
| QTDMISTURA | Float |  | Qtd. Mistura |  |
| SEQMPA | Integer |  | Sequência |  |
| NULOP | Integer |  | Lancamento |  |

## TPRMPE — TABLE TPRMPE
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| MOTIVOPERDA | String |  | Motivo de perda | `S`=Subprodutos/Refugos `R`=Descarte |
| CODMPE | Integer |  | Código |  |

## TPRMPEAMP — Motivo de Perda de Apontamento de PA
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUAPO | Integer |  | Nro. Único |  |
| SEQAPA | Integer |  | Sequência |  |
| CODMPE | Integer |  | Motivo de Perda |  |
| QTDPERDA | Float |  | Qtd. Perda |  |
| CODPRODMP | Integer |  | Cód. Produto (MP) |  |
| CONTROLEMP | String |  | Controle (MP) |  |
| CODMPEAMP | Integer |  | Cód. Detalhamento Perda |  |

## TPRMPEAPA — Motivo de Perda de Apontamento de PA
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUAPO | Integer |  | Nro. Único |  |
| SEQAPA | Integer |  | Sequência |  |
| CODMPE | Integer |  | Motivo de Perda |  |
| QTDPERDA | Float |  | Qtd. Perda |  |
| CODMPEAPA | Integer |  | Cód. Detalhamento Perda |  |

## TPRMPS — Plano Mestre de produção
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCMPS | Integer |  | Configuração MPS |  |
| DHGERMRP | DateTime |  | Dh. Geração MRP |  |
| CODPLANTA | Integer |  | Planta de Manufatura |  |
| CODUSU | Integer |  | Usuário |  |
| DESCRICAO | String |  | Descrição |  |
| DHALTER | DateTime |  | Dh. Alteração |  |
| DTINICMPS | DateTime |  | Período MPS |  |
| DTFINMPS | DateTime |  | Período MPS |  |
| DTINIPED | DateTime |  | Período dos pedidos |  |
| DTFINPED | DateTime |  | Período dos pedidos |  |
| SITUACAO | String |  | Situação | `C`=Confirmado `P`=Pendente |
| PERCAJUSTEDEM | Float |  | % Ajuste Demanda |  |
| OBSERVACOES | String |  | Observações |  |
| NUMPS | Integer |  | Código |  |

## TPRMQP — TPRMQP
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| CODPLP | Integer |  | Planta de Manufatura |  |
| CODCRE | Integer |  | Categoria de Recurso |  |
| NUMEQ | Integer |  | Núm. Equipamento |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| DECQTD | Integer |  | DECQTD |  |
| CODMQP | Integer |  | Cód. Máquina |  |

## TPRMTP — Motivos de Parada
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| PLANEJADA | String |  | Considerar paradas planejadas no cálculo do OEE | `N`=Não `S`=Sim |
| MOTIVOPARADA | String |  | Motivo de parada | `S`=Setup `C`=Manutenção Corretiva |
| CODMTP | Integer |  | Código |  |

## TPROEE — OEE
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODWCP | Integer |  | Cod Centro de Trabalho |  |
| DATAHORA | DateTime |  | Data |  |
| TIPO | String |  | Tipo | `T`=TURNO `M`=Mensal `D`=Diário |
| DHALTER | DateTime |  | Data Atualização |  |
| TEMPOPROGRAMADO | Float |  | Tempo Programado |  |
| TEMPOPRODUZINDO | Float |  | Tempo Produzindo |  |
| DISPONIBILIDADE | Float |  | Indicador Disponibilidade |  |
| QTDPRODTEORICA | Float |  | Qtd Produzida Teorica |  |
| QTDPRODREAL | Float |  | Qtd Produzida Real |  |
| QTDTOTALAPONTADA | Float |  | Qtd Total Apontada |  |
| QTDPECASBOAS | Float |  | Qtd Peças Boas |  |
| PERFORMANCE | Float |  | Indicador Performance |  |
| QUALIDADE | Float |  | Indicador Qualidade |  |
| OEE | Float |  | Indicador OEE |  |

## TPROEST — Operações com Estoque
Campos: 48

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOPER | Integer |  | Código |  |
| ORDEM | Integer |  | Ordem |  |
| DESCRICAO | String |  | Descrição da Operação |  |
| TIPOOPER | String |  | Tipo de Execução da Operação | `T`=Ambas `M`=Manual `A`=Automática |
| TIPOPRODUCAO | String |  | Tipo de Produção | `T`=Para terceiros `E`=Para estoque próprio `A`=Ambas |
| OBRIGATORIO | String |  | Obrigatória | `S`=Sim `N`=Não |
| QUANDO | String |  | Quando | `SA`=Saída `PF`=Ao preencher um formulário `IN`=Quando o usuário iniciar a atividade `AJ`=Ao apontar materiais de ajustes `PA`=Ao apontar PA_(+2)_ |
| NUNOTAMODELO | Integer |  | Modelo de Nota |  |
| IDEFXBASE | Integer |  | Atividade Base |  |
| CODPARC | Integer |  | Parceiro |  |
| CODCENCUS | Integer |  | Centro de Resultado |  |
| CODPROJ | Integer |  | Projeto |  |
| CODNAT | Integer |  | Natureza |  |
| CODTIPVENDA | Integer |  | Tipo de Negociação |  |
| CODTIPOPER | Integer |  | Tipo de Operação |  |
| CODTIPOPERPERDA | Integer |  | Tipo de Operação para Perda |  |
| UTILIZALOCALORIG | String |  | Sempre utilizar Local de Origem da Operação | `S`=Sim `N`=Não |
| CODLOCALORIG | Integer |  | Local de Origem |  |
| CODLOCALDEST | Integer |  | Local de Destino |  |
| CODLOCALDESTPERDA | Integer |  | Local de Destino para Perda |  |
| CODLOCALBAIXAMP | Integer |  | Local para baixa de MPs |  |
| CODEMPORIG | Integer |  | Empresa de Origem |  |
| TIPOITENS | String |  | Tipo dos Itens | `MT`=Lista de materiais de todas as atividades `MA`=Materiais de ajuste `MB`=Lista de materiais da atividade base `PA`=Produto acabado apontado na atividade `SP`=Subproduto da Atividade |
| CODEMPDEST | Integer |  | Empresa de Destino |  |
| TIPOMATERIAL | String |  | Tipo Material | `PI`=Somente PIs `AB`=Ambos `MP`=Somente MPs |
| SELIMPRESSORA | String |  | Selecionar Impressora | `W`=Usar impressora padrão do Centro de Trabalho `T`=Conforme a TOP `E`=Específica |
| CONSUMIRESTOQUE | String |  | Quantidade de PI | `T`=Total `FS`=Fabricada em sub-ordem `CE`=Consumida do estoque |
| NOMEIMPRESSORA | String |  | Impressora |  |
| STATUSEXEC | String |  | Status da Execução | `R`=Reprocesso `N`=Normal `T`=Todos |
| IDFORM | Integer |  | Formulário |  |
| CONFIRMAR | String |  | Confirmar Operação | `S`=Sim `N`=Não |
| BAIXARESERVAEST | String |  | Baixar reserva na nota de produção | `S`=Sim `N`=Não |
| TIPOEXEC | String |  | Execução da Atividade | `E`=Terceiros `T`=Todos `P`=Própria |
| USARPARCTERC | String |  | Usar o Parceiro Terceiro da OP | `S`=Sim `N`=Não |
| ANULAOPEREST | String |  | Anular operação ao cancelar OP | `N`=Não `S`=Sim |
| USARPARCTERCENCAD | String |  | Usar o Parceiro Terceiro da OP (Encad) | `N`=Não `S`=Sim |
| TIPOOPERENCAD | String |  | Tipo de Execução | `M`=Manual `A`=Automática |
| OBRIGENCAD | String |  | Obrigatória | `S`=Sim `N`=Não |
| CONFIRMENCAD | String |  | Confirmar Operação | `S`=Sim `N`=Não |
| NUMODELOENCAD | Integer |  | Modelo de Nota |  |
| CODTIPOPERENCAD | Integer |  | Tipo de Operação |  |
| CODPARCENCAD | Integer |  | Parceiro |  |
| CODEMPDESTENCAD | Integer |  | Empresa de Destino |  |
| CODLOCALDESTENCAD | Integer |  | Local de Destino |  |
| KANBAN | String |  | Utilizar Kanban | `N`=Não `S`=Sim |
| NUNOTAMODELOKANBAN | Integer |  | Modelo de Nota (Pedido de Requisição) |  |
| CODTIPOPERKANBAN | Integer |  | Tipo de Operação (Pedido de Requisição) |  |
| IDEFX | Integer |  | Código |  |

## TPRPEFX — TPRPEFX
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | NOME |  |
| TIPO | String |  | TIPO |  |
| INTVAL | Integer |  | INTVAL |  |
| DECVAL | Float |  | DECVAL |  |
| DATVAL | DateTime |  | DATVAL |  |
| TEXTVAL | String |  | TEXTVAL |  |
| IDEFX | Integer |  | IDEFX |  |

## TPRPIPROC — TPRPIPROC
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFX | Integer |  | Atividade |  |
| IDAWC | Integer |  | Alocação de C. Trabalho |  |
| CODCWC | Integer |  | Categoria Centro de Trabalho |  |
| CODWCP | Integer |  | Centro de Trabalho |  |
| DHINIPREV | DateTime |  | Data Ini. Previsto |  |
| DHFINPREV | DateTime |  | Data Fin. Previsto |  |
| JSONPROG | C |  | JSONPROG |  |
| IDIPROC | Integer |  | Nro. OP |  |

## TPRPLOP — Produtos para lançamento de OP
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | Sequência |  |
| CODPRODPA | Integer |  | Cód.Produto |  |
| CODFORMULA | Integer |  | Cód.Fórmula |  |
| CONTROLEPA | String |  | Controle |  |
| ESTOQUE | Float |  | Qtd.Estoque |  |
| NROLOTE | String |  | Nro. Lote |  |
| TAMLOTE | Float |  | Tam. Lote |  |
| CALCTAMLOTE | Float |  | Tam. Lote Ajustado |  |
| MULTLOTE | Float |  | Múltiplo de Lote |  |
| MINLOTE | Float |  | Lote Mínimo |  |
| TAMLOTEPAD | Float |  | TAMLOTEPAD |  |
| TIPOGERASERIE | String |  | TIPOGERASERIE |  |
| EDITADO | String |  | EDITADO | `N`=Não `S`=Sim |
| QTDPRODMIN | Float |  | Qtd. Mínima |  |
| NULOP | Integer |  | Lançamento |  |

## TPRPLP — Planta de manufatura
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOME | String |  | Nome |  |
| CODEMP | Integer |  | Empresa |  |
| CODCARGAHOR | Integer |  | Carga Horária Padrão |  |
| CODCENCUS | Integer |  | Centro de Resultado |  |
| CODPLP | Integer |  | Cód. Planta |  |

## TPRPMP — Apontamento Peso Materia Prima
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OPNRO | Integer |  | Nro Op |  |
| CODPROD | Integer |  | Cód Produto |  |
| QTDAPONTADA | Float |  | Qtd Apontada |  |
| QTDPERDA | Float |  | Qtd Perda |  |
| PRODDESCRICAO | String |  | Descrição |  |
| PRODCONTROLE | String |  | Controle |  |
| PERDA | String |  | Perda | `N`=Não `S`=Sim |
| CODAPPRDOPESO | Integer |  | Id |  |

## TPRPPA — TABLE TPRPPA
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OPNRO | Integer |  | Nro Op |  |
| CODPROD | Integer |  | Cód Produto |  |
| QTDAPONTADA | Float |  | Qtd Apontada |  |
| QTDPERDA | Float |  | Qtd Perda |  |
| PRODDESCRICAO | String |  | Descrição |  |
| PRODREF | String |  | Referência |  |
| PRODCONTROLE | String |  | Controle |  |
| PERDA | String |  | Perda | `S`=SIM |
| CODAPPRDOPESO | Integer |  | Id |  |

## TPRPRC — Metainformações sobre um processo produtivo.
Campos: 49

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VALIDAVERSAO | String |  | VALIDAVERSAO | `S`=Sim `N`=Não |
| CODPRC | Integer |  | Código |  |
| TIPOPROC | String |  | Tipo de Processo | `S`=Sub-Processo `M`=Processo mestre |
| DESCRABREV | String |  | Descrição |  |
| DESCRLONGA | String |  | Descrição Completa |  |
| IDRPAINICIAL | Integer |  | Repositório Inicial |  |
| VERSAO | Integer |  | Versão |  |
| VERSAOANT | Integer |  | Versão Anterior |  |
| CODPLP | Integer |  | Planta de Manufatura |  |
| CODLOCALALMOXARIFE | Integer |  | Local de Almoxarifado |  |
| CODLOCALMANUFATURA | Integer |  | Local de Manufatura |  |
| MULTIPA | String |  | Aceita Múltiplos PAs | `S`=Sim `N`=Não |
| MULTICONTROLE | String |  | Aceita Múltiplos Controles de PA | `S`=Sim `N`=Não |
| TIPOINICIA | String |  | Tipo de inicialização | `I`=Imediato `C`=Após confirmação |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| XMLBPMN | C |  | XMLBPMN |  |
| IDWFLOW | String |  | IDWFLOW |  |
| XMLBPMNUI | C |  | XMLBPMNUI |  |
| TIPONROLOTE | String |  | Tipo do Nro. Lote | `AE`=Automático (por Empresa) `AG`=Automático (Global) `MN`=Manual `AP`=Automático (por Produto) `AX`=Automático (por Empresa + Produto) |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| MASCNROLOTE | String |  | Máscara Nro. Lote |  |
| PRODPARATERCEIRO | String |  | Produção para Terceiro | `S`=Sempre `O`=Opcional `N`=Nunca |
| PROCDESMONTE | String |  | Desmonte | `N`=Não `S`=Sim |
| PROCREPARO | String |  | Reprocessamento/reparo | `S`=Sim `N`=Não |
| CODPRCPRODUCAO | Integer |  | Processo de Produção Relacionado |  |
| USATERCEIRO | String |  | Produção terceirizada | `S`=Sempre `O`=Opcional `N`=Nunca |
| TIPOFRAGNROLOTE | String |  | Reiniciar numeração | `N`=Não reiniciar `A`=Anualmente `D`=Diariamente `M`=Mensalmente |
| DEFTERCEIRO | String |  | Definição de Terceiro | `A`=Por Operação `O`=Por OP |
| EXIGEPEDIDO | String |  | Exige pedido de venda | `O`=Opcional `N`=Nunca `S`=Sempre |
| PADRAO | String |  | Padrão | `S`=Sim `N`=Não |
| LOTECURINGA | String |  | Lote Curinga |  |
| PERCDESVIOINF | Float |  | % Desvio Inferior |  |
| PERCDESVIOSUP | Float |  | % Desvio Superior |  |
| LIBERADESVIO | String |  | Solicitar liberação ao exceder desvio | `S`=Sim `N`=Não |
| USALOTECURINGA | String |  | Usa Lote Curinga | `S`=Sim `N`=Não |
| IDFORMULA | Integer |  | Fórmula p/ Ajuste Tamanho de Lote |  |
| ROTEIROHTML5 | String |  | Editado em HTML5 | `N`=Não `S`=Sim |
| USACONFNROLOTESP | String |  | Utilizar essa configuração para Subproduto | `S`=Sim `N`=Não |
| TIPONROLOTESP | String |  | Tipo do Nro. Lote | `MN`=Manual `AX`=Automático (por Empresa + Produto) `AG`=Automático (Global) `AE`=Automático (por Empresa) `AP`=Automático (por Produto) |
| MASCNROLOTESP | String |  | Máscara Nro. Lote |  |
| TIPEXECATV | String |  | Tipo de Execução das Atividades | `A`=Automático sem edição `E`=Automático com edição `M`=Manual |
| TIPOFRAGNROLOTESP | String |  | Reiniciar numeração | `N`=Não reiniciar `M`=Mensalmente `A`=Anualmente |
| PEREDICAO | String |  | Período permitido para realizar a edição | `L`=Livre `M`=Mês `Q`=Quinzena `S`=Semana |
| QTDDIAS | Integer |  | Qtd. Dias |  |
| PADRAOPRODUTO | String |  | Padrão por Produto | `S`=Sim `N`=Não |
| IDPROC | Integer |  | Número Único |  |

## TPRPSP — TABLE TPRPSP
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODSP | Integer |  | Cód Subprod |  |
| OPNRO | Integer |  | Nro Op |  |
| QTD | Float |  | Qtd |  |
| PRODDESCRICAO | String |  | Descrição |  |
| PRODREF | String |  | Referência |  |
| PRODCONTROLE | String |  | Controle |  |
| ID | Integer |  | Id |  |

## TPRRHP — TPRRHP
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPLP | Integer |  | Planta de Manufatura |  |
| NOME | String |  | Nome |  |
| CODCRE | Integer |  | Categoria de Recurso |  |
| CODPARC | Integer |  | Parceiro |  |
| CODUSU | Integer |  | Usuário |  |
| CODFUNC | Integer |  | Funcionário |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| CODRHP | Integer |  | Cód. Colaborador |  |

## TPRROPE — Registro de operações com estoque
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQROPE | Integer |  | Sequência |  |
| IDEFX | Integer |  | Elemento |  |
| SEQOPER | Integer |  | Seq. Conf. Operação |  |
| CODPRODPA | Integer |  | Cód. Produto |  |
| CONTROLEPA | String |  | Controle |  |
| QTDBASE | Float |  | Qtd. base |  |
| STATUSEXEC | String |  | Status |  |
| NUNOTA | Integer |  | Nro. Nota |  |
| NUAPO | Integer |  | Nro. Apontamento |  |
| TIPOOPER | String |  | Tipo de Execução da Operação | `T`=Ambas `M`=Manual `A`=Automática |
| CODUSU | Integer |  | Usuário |  |
| IDIATV | Integer |  | Instância da Atividade |  |

## TPRRPA — Repositorio de PA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| IDRPA | Integer |  | Cód. Repositório |  |

## TPRRWA — Recursos de Work Center x Atividade
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQREC | Integer |  | Sequência |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODCRE | Integer |  | Categoria de Recurso |  |
| QTDUTILIZACAO | Float |  | Quantidade de Utilização |  |
| MULTUTILIZACAO | Float |  | Múltiplo para Utilização | `1`=1 |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| IDEFX | Integer |  | Elemento |  |

## TPRRXP — TPRRXP
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODWCP | Integer |  | Centro de Trabalho |  |
| CODCRE | Integer |  | Categoria de Recurso |  |
| CONTROLEPA | String |  | Controle |  |
| QTDALOCADA | Float |  | Quantidade |  |
| MODCAPACIDADE | String |  | Modificador de Capacidade | `F`=Fator capacidade `P`=Proporcional `N`=Neutra |
| FATORCAPACIDADE | Float |  | Fator Capacidade |  |
| CODPRODPA | Integer |  | Produto |  |

## TPRRXW — Recursos por work center
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCRE | Integer |  | Cat. de Recurso |  |
| QTDALOCADA | Float |  | Quantidade |  |
| MODCAPACIDADE | String |  | Modificação de Capacidade | `N`=Neutra `P`=Proporcional `F`=Fator de capacidade |
| FATORCAPACIDADE | Float |  | Fator Capacidade |  |
| CODWCP | Integer |  | Centro de Trabalho |  |

## TPRSERLOP — Série Lançamento OP
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | SEQOP |  |
| CODPRODPA | Integer |  | CODPRODPA |  |
| SERIEPA | String |  | Nro. Série (PA) |  |
| NULOP | Integer |  | NULOP |  |

## TPRSERMP — Série Matéria Prima
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SERIEMP | String |  | Nro. Série (MP) |  |
| NUAPO | Integer |  | Nro. Apontamento |  |
| IDIPROC | Integer |  | Nro. OP |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| SERIEPA | String |  | Nro. Série (PA) |  |
| LIBERADO | String |  | Liberado | `N`=Não `S`=Sim |
| CODPRODMP | Integer |  | Produto (MP) |  |

## TPRSERMP_TEMP — Série Matéria Prima temporário
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODMP | Integer |  | Produto (MP) |  |
| SERIEMP | String |  | Nro. Série (MP) |  |
| CODPRODPA | Integer |  | Produto (PA) |  |
| SERIEPA | String |  | Nro. Série (PA) |  |
| LIBERADO | String |  | Liberado |  |
| IDIPROC | Integer |  | Nro. OP |  |

## TPRSERPA — Série Produto Acabado
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| SERIEPA | String |  | Nro. Série (PA) |  |
| PERDA | String |  | Perda | `S`=Sim `N`=Não |
| LIBERADO | String |  | Liberado | `N`=Não `S`=Sim |
| NUAPO | Integer |  | NUAPO |  |
| IDIPROC | Integer |  | Nro. OP |  |

## TPRSPLOP — SubProdutos para lançamento de OP
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | Sequência |  |
| IDEFX | Integer |  | Elemento |  |
| SEQLSP | Integer |  | Sequência |  |
| CODPRODPA | Integer |  | Produto |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODPRODSP | Integer |  | Cód.Produto |  |
| CONTROLESP | String |  | Controle |  |
| NROLOTE | String |  | Nro. Lote |  |
| NULOP | Integer |  | Lançamento |  |

## TPRSTE — Status por Linha de Execução
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| STATUSEXEC | String |  | STATUSEXEC |  |
| IDATVSTATUSNORMAL | Integer |  | IDATVSTATUSNORMAL |  |
| IDEXECWFLOW | String |  | IDEXECWFLOW |  |

## TPRSWXP — Setup de work center por PA
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto |  |
| CONTROLEPA | String |  | Controle |  |
| VALINTEIRO | Integer |  | Valor |  |
| VALDECIMAL | Float |  | Valor |  |
| VALTEXTO | String |  | Valor |  |
| VALMEMO | String |  | Valor |  |
| NUAST | Integer |  | Atributo |  |
| VAL | String |  | Valor |  |

## TPRTAC — TPRTAC
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQTAC | Integer |  | Sequência |  |
| CODTIPAMOSTRA | Integer |  | Tipo da Amostra |  |
| CODPRODPA | Integer |  | Produto |  |
| CONTROLEPA | String |  | Controle |  |
| QTDAMOSTRA | Float |  | Quantidade |  |
| OBRIGATORIO | String |  | Amostra Obrigatória | `N`=Não `S`=Sim |
| IDCCQ | Integer |  | Controle de Qualidade |  |

## TPRTCA — TPRTCA
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFX | Integer |  | Atividade |  |
| CODPRODPA | Integer |  | Produto |  |
| CONTROLEPA | String |  | Controle |  |
| CODPRODTAR | Integer |  | Tarifa |  |
| TIPOINDICE | String |  | Tipo de Índice | `V`=Variável (Execução de atividades) `F`=Fixo |
| TIPOEXEC | String |  | Tipo de Execução | `T`=Todos `P`=Parada `N`=Normal |
| QTD | Float |  | Índice |  |
| CODVOL | String |  | UN. Consumo |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| IDPROC | Integer |  | Processo |  |

## TPRTFX — Transição do fluxo
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFXORIG | Integer |  | Elemento de Origem |  |
| IDEFXDEST | Integer |  | Elemento de Destino |  |
| PRIORITARIO | String |  | Prioritário | `N`=Não `S`=Sim |
| PADRAO | String |  | Padrão | `N`=Não `S`=Sim |
| EXPCONDICAO | String |  | Expressão |  |
| DEFSTATUSEXEC | String |  | Status da Execução | `R`=Reprocesso `A`=Mantém o status atual `N`=Normal |
| ORDEMAVAL | Integer |  | Ordem |  |
| IDEFX | Integer |  | Código |  |

## TPRTLOP — Terceiros por Lançamento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | SEQOP |  |
| IDEFX | Integer |  | IDEFX |  |
| DESCATV | String |  | Operação |  |
| CODPARCTERC | Integer |  | Cód. Parceiro |  |
| NULOP | Integer |  | NULOP |  |

## TPRTPP — TPRTPP
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto |  |
| CONTROLEPA | String |  | Controle |  |
| CODPRODTAR | Integer |  | Tarifa |  |
| TIPOINDICE | String |  | Tipo de Índice | `F`=Fixo `V`=Variável (Execução de atividades) |
| TIPOEXEC | String |  | Tipo de Execução | `T`=Todos `P`=Parada `N`=Normal |
| QTD | Float |  | Índice |  |
| CODVOL | String |  | UN. Consumo |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| IDPROC | Integer |  | Processo |  |

## TPRTXAT — Terceiro por Atividade
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFX | Integer |  | Atividade |  |
| CODPARCTERC | Integer |  | Cód. Parceiro |  |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Cod. Usuário |  |
| IDIPROC | Integer |  | Nro. OP |  |

## TPRTXP — TPRTXP
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto (PA) |  |
| CONTROLEPA | String |  | Controle (PA) |  |
| CODCWC | Integer |  | Categoria do Centro de Trabalho |  |
| TIPOTEMPO | String |  | Tipo de tempo | `F`=Fixo `Q`=Por Quantidade `L`=Por Lote |
| CODWCP | Integer |  | Centro de Trabalho |  |
| TEMPOATIVIDADE | Float |  | Tempo da atividade |  |
| UNTEMPO | String |  | Unidade de tempo | `M`=Minutos `H`=Horas `D`=Dias |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| USARCTPADRAO | String |  | Padrão | `N`=Não `S`=Sim |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| IDEFX | Integer |  | Elemento |  |

## TPRTXPP — Terceiro por Processo Produtivo
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDEFX | Integer |  | Atividade |  |
| CODPRODPA | Integer |  | Cód. Produto |  |
| CODPARCTERC | Integer |  | Cód. Parceiro |  |
| PREFERENCIAL | String |  | Preferencial | `S`=Sim `N`=Não |
| DHCAD | DateTime |  | Data e Hora Inclusão |  |
| CODUSUCAD | Integer |  | Usuário Resp. Cadastro |  |
| DHALTER | DateTime |  | Data e Hora Alteração |  |
| CODUSUALT | Integer |  | Usuário Última Alteração |  |
| IDPROC | Integer |  | Processo Produtivo |  |

## TPRVFTL — Variáveis para Fórmula
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEVAR | String |  | Nome |  |
| EXPRESSAO | String |  | Expressão |  |
| ORDEM | Integer |  | "ORDEM" |  |
| IDFORMULA | Integer |  | Id Fórmula |  |

## TPRWCP — Work Center de produção
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODWCP | Integer |  | Código |  |
| DISPONIBILIDADE | String |  | Disponibilidade |  |
| CODCWC | Integer |  | Categoria |  |
| NOME | String |  | Descrição |  |
| CODPLP | Integer |  | Planta |  |
| CODCAP | Integer |  | Capacidade |  |
| QTDCAPACIDADEMIN | Float |  | Capacidade Mínima |  |
| QTDCAPACIDADEPAD | Float |  | Capacidade Padrão |  |
| QTDCAPACIDADEMAX | Float |  | Capacidade Máxima |  |
| QTDCARGAMIN | Float |  | Carga Mínima |  |
| CAPACIDADEHORA | Float |  | Capacidade por Hora |  |
| QTDCARGAMAX | Float |  | Carga Máxima |  |
| CODVOL | String |  | Unidade |  |
| RESTRINGECARGA | String |  | Restringir uso pela Capacidade de Carga | `N`=Não `S`=Sim |
| CODUSURESP | Integer |  | Usuário Responsável |  |
| CODCENCUS | Integer |  | Centro de Resultado |  |
| CODCARGAHOR | Integer |  | Carga Horária |  |
| TIPOSETUP | String |  | Tipo de Setup | `C`=Condicional `S`=Sempre `N`=Nunca |
| EXIGECLEANUP | String |  | Exige Cleanup | `S`=Sim `N`=Não |
| TEMPOSETUP | Integer |  | Tempo Padrão de Setup |  |
| TEMPOCLEANUP | Integer |  | Tempo Padrão de Cleanup |  |
| INDICEOEE | Float |  | OEE |  |
| NOMEIMPRESSORA | String |  | Nome da Impressora |  |
| NUMQP | Integer |  | Máquina Principal |  |
| SETUPPRONTO | String |  | SETUPPRONTO |  |
| CODLOCALWC | Integer |  | Local de Estoque |  |
| OPERACAO | String |  | Operação | `C`=Compartilhado `E`=Exclusivo |
| QTDALOCADA | Integer |  | Quantidade de Alocações |  |

## TPRWLOP — Alocacao de Work Center no Lançamento de OP
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQOP | Integer |  | SEQOP |  |
| IDPROC | Integer |  | IDPROC |  |
| IDAWC | Integer |  | IDAWC |  |
| CODWCP | Integer |  | Centro de Trabalho |  |
| DESCRATV | String |  | Atividade |  |
| NULOP | Integer |  | NULOP |  |
| CODCWC | Integer |  | Cód. Categoria |  |
| DESCRCWC | String |  | Descrição (Categoria) |  |

## TPRWXIP — Work center por instância de processo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDAWC | Integer |  | IDAWC |  |
| CODWCP | Integer |  | CODWCP |  |
| IDEFX | Integer |  | IDEFX |  |
| PRIORIDADE | Integer |  | PRIORIDADE |  |
| IDIPROC | Integer |  | IDIPROC |  |

## TPRWXP — Work center por PA
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODPA | Integer |  | Produto |  |
| SEQ | Integer |  | SEQ |  |
| CONTROLEPA | String |  | Controle |  |
| CODCAP | Integer |  | Capacidade |  |
| QTDCAPACIDADEMIN | Float |  | Capacidade Mínima |  |
| QTDCAPACIDADEPAD | Float |  | Capacidade Padrão |  |
| QTDCAPACIDADEMAX | Float |  | Capacidade Máxima |  |
| TEMPOSETUP | Integer |  | Tempo de Setup |  |
| TEMPOCLEANUP | Integer |  | Tempo de Cleanup |  |
| CODWCP | Integer |  | Código |  |