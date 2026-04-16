# TIM — Indústria / Manufatura

> Gerado do dicionário oficial TDD Sankhya. 140 tabelas.


## TIMAAC — TABLE TIMAAC
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| AACNUFIN | Integer |  | Nro. Único |  |
| AACACUMULO | Integer |  | Acumulo |  |
| AACDTVENC | Date |  | Dt. Venc |  |
| AACVLRPRINCIPAL | Float |  | Vlr. Principal |  |
| AACVLRJURO | Float |  | Vlr. Juro |  |
| AACVLRMULTA | Float |  | Vlr. Multa |  |
| AACVLRCORRMONET | Float |  | Vlr. Corr. Monetária |  |
| AACVLRIRRF | Float |  | Vlr. IRRF |  |
| AACVLRDESC | Float |  | Vlr. Desc |  |
| AACVLRTOTAL | Float |  | Vlr. Total Líquido |  |
| AACREPASSEGERADO | String |  | Repasse Gerado | `S`=Sim `N`=Não |

## TIMACL — TABLE TIMACL
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ACLCONTRATO | Integer |  | Contrato |  |
| ACLESTAGIO | String |  | Estágio | `EF`=Efetivado `CN`=Cancelado `CA`=Cadastro |
| ACLDTBASE | Date |  | Dt. Base |  |
| ACLDTVENC | Date |  | Dt. Venc |  |
| ACLVLRPRINCIPAL | Float |  | Vlr. Principal |  |
| ACLVLRJURO | Float |  | Vlr. Juro |  |
| ACLVLRMULTA | Float |  | Vlr. Multa |  |
| ACLVLRCORRMONET | Float |  | Vlr. Corr. Monetária |  |
| ACLVLRIRRF | Float |  | Vlr. IRRF |  |
| ACLVLRTOTAL | Float |  | Vlr. Total Líquido |  |
| ACLVLRDESC | Float |  | Vlr. Desconto |  |
| ACLPAGADORDESC | String |  | Pagador do Desconto | `L`=Locador `A`=Administradora |
| ACLVLRHONORARIO | Float |  | Vlr. Honorários |  |
| ACLVLRFECHADO | Float |  | Vlr. Fechado |  |
| ACLDIFIRRF | Float |  | Ajuste IRRF |  |
| ACLVLRGRAVADO | Float |  | Vlr. Efetivo |  |
| ACLNURENEG | Integer |  | Nro. Reneg. SKW |  |
| ACLNUFIN | Integer |  | Nro. Único |  |
| ACLUSUINCLUIU | Integer |  | Usuário Incluíu |  |
| ACLUSUALTEROU | Integer |  | Usuário Alterou |  |
| ACLDTINCLUSAO | Date |  | Dt. Inclusão |  |
| ACLDTALTERACAO | Date |  | Dt. Alteração |  |
| ACLDTEFETIVA | Date |  | Dt. Efetivação |  |
| ACLCODIGO | Integer |  | Código |  |

## TIMACM — Acúmulo de Parcelas
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ACMCONTRATO | Integer |  | Nro. Contrato |  |
| ACMESTAGIO | String |  | Estágio | `EF`=Efetivado `CN`=Cancelado `CA`=Cadastro |
| ACMDTACUMULO | Date |  | Dt. Acúmulo |  |
| ACMDTVENC | Date |  | Dt. Vencimento |  |
| ACMVLRACUMULADO | Float |  | Vlr. Acumulado |  |
| ACMVLRDESCONTO | Float |  | Vlr. Desconto |  |
| ACMVLRTOTAL | Float |  | Vlr. Total |  |
| ACMDTCANCELADO | Date |  | Dt. Cancelado |  |
| ACMNURENEG | Integer |  | Nro. Reneg. SKW |  |
| ACMNUFIN | Integer |  | Nro. Único Parcela |  |
| ACMDHINCUSAO | DateTime |  | Dh. Inclusão |  |
| ACMDHALTER | DateTime |  | Dh. Alteração |  |
| ACMUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| ACMUSUALTER | Integer |  | Usuário Alteração |  |
| ACMSEQUENCIA | Integer |  | Código |  |

## TIMACO — Parcelas Origem
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ACOACUMULO | Integer |  | Nro. Acúmulo |  |
| ACONUFIN | Integer |  | Nro. Único |  |
| ACOTIMPARCELA | Integer |  | Nro. Parcela |  |
| ACODTVENC | Date |  | Dt. Vencimento |  |
| ACOVLRDESDOB | Float |  | Vlr. Original |  |
| ACOVLRCORRMONET | Float |  | Vlr. Corr. Monetária |  |
| ACOVLRJUROS | Float |  | Vlr. Juros |  |
| ACOVLRMULTA | Float |  | Vlr. Multa |  |
| ACOVLRATUAL | Float |  | Vlr. Atual |  |
| ACOCONTRATO | Integer |  | Nro. Contrato |  |

## TIMADM — Contrato de Administração do Imóvel
Campos: 71

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ADMNUCONTRATO | Integer |  | Nro. Contrato |  |
| ADMDATA | Date |  | Dt. Contrato |  |
| ADMLOCACAO | String |  | Imóvel para locação | `S`=Sim `N`=Não |
| ADMDATADESOCUPADO | Date |  | Dt. Baixa Locação |  |
| ADMVENDA | String |  | Imóvel para venda | `S`=Sim `N`=Não |
| ADMDATADESOCUPADOVENDA | Date |  | Dt. Baixa Venda |  |
| ADMDIASUTEISCALCPROP | String |  | Qtd. Dias Mês Proporcionalizar | `TD`=Sempre 30 dias `DI`=Qtd dias do mês pela dt. inicío do contrato `DF`=Qtd dias do mês pela dt. final do contrato |
| ADMESTAGIO | String |  | Estágio | `V`=Ativo p/ Venda `L`=Ativo p/ Locação `C`=Em Cadastro `B`=Finalizado `A`=Ativo |
| ADMCAPTADOR | Integer |  | Captador |  |
| ADMDESTINACAO | String |  | Destinação | `3`=Não Informado `2`=Ambos `1`=Residencial `0`=Comercial |
| ADMPRAZOADM | Integer |  | Vigência p/ Adm em Meses |  |
| ADMPRAZOLOC | Integer |  | Vigência p/ Locação em Meses |  |
| ADMDATALIBERACAO | Date |  | Dt. Captação |  |
| ADMIMOBILIARIA | Integer |  | Imobiliária Locação |  |
| ADMTIPOTXADM | String |  | Tipo de Tx Adm | `PC`=Percentual `ID`=Percentual/Índice `FX`=Fixo |
| ADMDFCOMISSAOADM | Float |  | Tx. Adm. (%) |  |
| ADMDFPRECOALUGUEL | Float |  | Vlr. Aluguel |  |
| ADMINDICETXADM | Integer |  | Índice para Tx Adm |  |
| ADMEXCLUSIVOLOC | String |  | Loc. Exclusiva | `S`=Sim `N`=Não |
| ADMTXADMVLR | Float |  | Tx Adm (Valor) |  |
| ADMPORQUEDESOCUPOU | String |  | Motivo Baixa Locação | `9`=Reforma `8`=Devolvido pela administradora `7`=Vendeu por conta própria `6`=Vendeu por concorrente `5`=Vendeu pela administradora_(+9)_ |
| ADMCONDLOC | String |  | Condições Locação |  |
| ADMDIASREPASSE | Integer |  | Qtd. dias até o repasse |  |
| ADMDIASUTEIS | String |  | Tipo Dias | `UT`=Úteis `CR`=Corridos `CO`=Comercial |
| ADMPRIMEIROALUGUEL | String |  | Cobrar Tx. Interm. | `S`=Sim `N`=Não |
| ADMTAXADIFERENTE | Float |  | Tx. Interm. (%) |  |
| ADMPRIPARPRI | Integer |  | Nro. parcela de início de cobrança |  |
| ADMQTDPARPRI | Integer |  | Diluído em (qtd. parc.) |  |
| ADMJUSTIFICAINTER | String |  | Justificativa Intermediação |  |
| ADMIMOB2 | Integer |  | Imobiliária Venda |  |
| ADMDFPRECODEVENDA | Float |  | Vlr. Venda |  |
| ADMDFCOMISSAO | Float |  | Comissão (%) |  |
| ADMDFQUITADO | String |  | Quitado | `S`=Sim `N`=Não |
| ADMDFFINANCIAMENTO | String |  | Financiamento | `S`=Sim `N`=Não |
| ADMDFPRESTACAO | Float |  | Vlr. Prestação Financiamento |  |
| ADMFINANCIAMENTOBCO | Integer |  | Banco Financiamento |  |
| ADMDFPOUPANCA | Float |  | Vlr. Poupança |  |
| ADMDFSALDODEVEDOR | Float |  | Vlr. saldo devedor |  |
| ADMEXCLUSIVO | String |  | Ven. Exclusiva | `S`=Sim `N`=Não |
| ADMDIASOPCAO | Integer |  | Qtd. dias exclusividade |  |
| ADMDATAFIMOPCAO | Date |  | Dt. Fim Exclusividade |  |
| ADMCORRESPBANCARIO | String |  | Correspondente Bancário | `S`=Sim `N`=Não |
| ADMDFAGENTEFINANCEIRO | Integer |  | Agente Financeiro |  |
| ADMPQDESOCUPOU | String |  | Motivo Baixa Venda | `9`=Reforma `8`=Devolvido pela administradora `7`=Vendeu por conta própria `6`=Vendeu por concorrente `5`=Vendeu pela administradora_(+9)_ |
| ADMCONDICOESDAVENDA | String |  | Condições Venda |  |
| ADMVISITAS | String |  | Visitas | `4`=Visita Acompanhada `3`=Não Informado `1`=Livre `0`=Agendar `2`=Proibida |
| ADMOBSVISITAS | String |  | Obs. sobre visitas |  |
| ADMQUANTIDADEANUNCIO | Integer |  | Qtd. Anúncios |  |
| ADMVAISITE | String |  | Anuncia no site | `S`=Sim `N`=Não |
| ADMDESTAQUE | String |  | Destaque Site | `S`=Sim `N`=Não |
| ADMSEMCHAVES | String |  | Sem Chaves | `S`=Sim `N`=Não |
| ADMSEMPLACA | String |  | Sem Placa | `S`=Sim `N`=Não |
| ADMDFTRANSFERENCIA | Float |  | Transferência (%) |  |
| ADMCHAVES | String |  | Chaves | `S`=Sim `N`=Não |
| ADMEMPRESANF | Integer |  | Empresa NF |  |
| ADMNUCHECKLIST | Integer |  | CheckList do contrato |  |
| ADMAVLPRECODEVENDA | Float |  | Vlr. Avaliação P/ Venda |  |
| ADMGARANTIDO | String |  | Garantido | `S`=Sim `N`=Não |
| ADMQTDEGARANTIDA | String |  | Garantia Total | `S`=Sim `N`=Não |
| ADMGARANTIDOPOR | Integer |  | Garantido por (meses) |  |
| ADMAVLPRECOALUG | Float |  | Vlr. Avaliação P/ Aluguel |  |
| ADMSEMTXMINADM | String |  | Não cobra adm mínima | `S`=Sim `N`=Não |
| ADMCOMPIMOVELDIFF | String |  | Compensa imóveis diferentes | `S`=Sim `N`=Não |
| ADMPERCREPMULTAPROPRIE | Integer |  | Perc. Multa Repasse Proprietário (%) |  |
| ADMDATACADASTRO | DateTime |  | Dh. Inclusão |  |
| ADMCODUSUINC | Integer |  | Usuário Inclusão |  |
| ADMDHALTER | DateTime |  | Dh. Alteração |  |
| ADMUSUARIO | Integer |  | Usuário Alteração |  |
| ADMDESCRIMOVEL | String |  | Descrição Imóvel |  |
| ADMIMOVEL | Integer |  | Nro. Imóvel |  |
| ADMCARENCIALOC | Integer |  | Dias de Carência p/ contrato |  |

## TIMANU — Anúncios do Imóvel
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANUCODIGO | Integer |  | Sequência |  |
| ANUDESCRICAO | String |  | Anúncio |  |
| ANUIMOVEL | Integer |  | Imóvel |  |

## TIMAPO — Contratos Cancelados
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| APOCONTRATO | Integer |  | Contrato |  |
| APOLOTE | String |  | Lote |  |
| APOQUADRA | String |  | Quadra |  |
| APOVLRTOTAL | Float |  | Vlr. Total |  |
| APOAPROVEITAR | Float |  | Vlr. Aproveitar |  |
| APOAPROVSALDO | Integer |  | Aproveitamento Saldo |  |

## TIMAPR — Contratos Renegociados
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| APRCONTRATO | Integer |  | Contrato |  |
| APRLOTE | String |  | Lote |  |
| APRQUADRA | String |  | Quadra |  |
| APRVLRTOTAL | Float |  | Vlr. Total |  |
| APRPENDENTE | Float |  | Vlr. Aberto |  |
| APRAPROVEITADO | Float |  | Vlr. Aproveitado |  |
| APRRESTANTE | Float |  | Vlr. Pendente |  |
| APRVLRPARCANT | Float |  | Vlr. Atual Parcela |  |
| APRAPROVSALDO | Integer |  | Aproveitamento de Saldo |  |

## TIMAPS — Registro de Aproveitamento de Saldo
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| APSDATA | Date |  | Dt. Aproveitamento |  |
| APSLOTEAMENTO | Integer |  | Loteamento |  |
| APSCOMPRADOR | Integer |  | Comprador |  |
| APSNURENEG | Integer |  | Nro. Reneg. Titulos |  |
| APSVLRTOTALCANCELADO | Float |  | Vlr. Total Cancelado |  |
| APSVLRTOTALAPROVEITAR | Float |  | Vlr. Total Aproveitar |  |
| APSVLRTOTALABERTO | Float |  | Vlr. Total Aberto |  |
| APSVLRTOTALPENDENTE | Float |  | Vlr. Total Pendente |  |
| APSVLRTOTALAPROVEITADO | Float |  | Vlr. Total Aproveitado |  |
| APSVLRTOTALRESTANTE | Float |  | Vlr. Total Restante |  |
| APSVLRTOTALRESTITUIR | Float |  | Vlr. Total Restituir |  |
| APSCODIGO | Integer |  | Código |  |

## TIMARL — Repasse Pendente
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DHERRO | DateTime |  | Dh. Ocorrência |  |
| ESTAGIO | String |  | Estágio Repasse | `G`=Gerado `P`=Pendente |
| MESSAGE | String |  | Motivo |  |
| STACKTRACE | C |  | Log do Servidor |  |
| NUFIN | Integer |  | Nro. Financeiro |  |

## TIMBAL — TIMBAL
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BALSEQ | Integer |  | Sequência |  |
| BALCONTRATO | Integer |  | Contrato |  |
| BALDTVENC | Date |  | Dt. Vencimento |  |
| BALVALOR | Float |  | Valor |  |

## TIMBAR — TIMBAR
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| BARSEQ | Integer |  | Sequência |  |
| BARRENEG | Integer |  | Renegociação |  |
| BARCONTRATO | Integer |  | Contrato |  |
| BARDTVENC | Date |  | Dt. Vencimento |  |
| BARVALOR | Float |  | Valor |  |

## TIMCAR — Cartórios
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CARPARCEIRO | Integer |  | Parceiro |  |
| CARCARTORIO | String |  | Descrição |  |
| CARCEP | String |  | CEP |  |
| CARENDFINAL | String |  | Endereço |  |
| CARCODEND | Integer |  | Endereço |  |
| CARENDERECO | String |  | Endereço |  |
| CARCOMPLEMENTO | String |  | Complemento |  |
| CARNUMEND | String |  | Número |  |
| CARBAIRRO | Integer |  | Bairro |  |
| CARCIDADE | Integer |  | Cidade |  |
| CARTELEFONES | String |  | Telefone |  |
| CAROBSERVACAO | String |  | Observação |  |
| CARCODIGO | Integer |  | Código |  |

## TIMCBL — Contas bancárias do locador
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CBLLOCADOR | Integer |  | Locador |  |
| CBLBANCO | Integer |  | Banco |  |
| CBLAGENCIA | String |  | Agência |  |
| CBLCONTACORRENTE | String |  | Conta |  |
| CBLTIPOCONTA | String |  | Tipo da conta | `X`=Poupex `P`=Poupança `C`=Conta corrente `A`=Aplicação |
| CBLCODIGO | Integer |  | Código |  |

## TIMCED — Configuração Parâmetros
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CEDCODIGO | Integer |  | Código |  |
| CEDMODULO | String |  | Modulo | `F`=Financeiro `B`=Bancário `C`=Comercial |
| CEDTITULO | String |  | Titulo |  |

## TIMCFI — Anúncios Classificado
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CFIIMOVEL | Integer |  | Imóvel |  |
| CFIANUNCIO | Integer |  | Nº Anúncio |  |
| CFIESTAGIO | String |  | Publicar | `S`=Sim `N`=Não |
| CFIVALOR | Float |  | Valor |  |
| CLAGERENTECOR | Integer |  | Gerente |  |
| CFIDESCRICAO | String |  | Anúncio Completo |  |
| CFICLASSIFICADO | Integer |  | Classificado |  |

## TIMCFP — Parâmetros
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CFPCODIGO | Integer |  | Código |  |
| CFPSEQUENCE | Integer |  | Ordem |  |
| CFPNOME | String |  | Nome |  |
| CFPDESCRICAO | String |  | Descrição |  |
| CFPTIPO | String |  | Tipo | `P`=Pesquisa `O`=Opcionado `I`=Integer `F`=Float `D`=Date_(+2)_ |
| CFPREQUERIDO | String |  | Requerido | `S`=Sim `N`=Não |
| CFPDEFAULTVALUE | String |  | Valor Padrão |  |
| CFPOPCOES | String |  | Opções |  |
| CFPINSTANCIA | String |  | Nome Instancia Dest. |  |
| CFPNUCAMPOINSTDEST | String |  | Nro. Campo Inst. Destino |  |
| CFPMODULO | String |  | Modulo |  |

## TIMCHI — TABLE TIMCHI
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHICHKNUCHECK | Integer |  | Nu. CheckList |  |
| CHINUITEM | Integer |  | Nu. Item |  |
| CHIOBIGATORIO | String |  | Obrigatório | `N`=Não `S`=Sim |
| CHIMARCADO | String |  | Check | `S`=Sim `N`=Não |
| CHIDTMARCADO | DateTime |  | Dt. de Marcação |  |
| CHIUSUARIO | Integer |  | Usuário de Alteração |  |
| CHIOBSERVACAO | String |  | Observação |  |

## TIMCHK — TABLE TIMCHK
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHKNUCHECK | Integer |  | Nu. CheckList |  |
| CHKTIPOCONTRATO | String |  | Tipo de contrato | `V`=Venda `R`=Rescisão de Locação `L`=Locação `E`=Venda de Lote `A`=Administração |
| CHKDTINC | DateTime |  | Dt. Inclusão |  |
| CHKCONTRATOADM | Integer |  | Contrato de Administração |  |
| CHKCONTRATOCLA | Integer |  | Contrato de Venda |  |
| CHKCONTRATOLOC | Integer |  | Contrato de Locação |  |
| CHKCONTRATOLTV | Integer |  | Contrato de Venda de Lote |  |
| CHKRESCISAOLOC | Integer |  | Rescisão de Locação |  |
| CHKCONCLUIDO | String |  | Concluído | `S`=Sim `N`=Não |

## TIMCHV — TABLE TIMCHV
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCHV | Integer |  | Código da Chave |  |
| DESCRCHV | String |  | Descrição da Chave |  |
| IMVCODIGO | Integer |  | Imóvel |  |
| STATCOD | Integer |  | Local da chave |  |
| IMBCODIGO | Integer |  | Imobiliária |  |
| CORCODIGO | Integer |  | Corretor |  |
| CHVOBS | String |  | Observações |  |
| FACCODIGO | Integer |  | FAC de solicitação |  |
| DHULTSOL | DateTime |  | Última Solicitação |  |
| STATCODOLD | Integer |  | STATCODOLD |  |
| CHVCODUSUINC | Integer |  | Usuário Inclusão |  |
| CHVCODUSUALT | Integer |  | Usuário Alteração |  |
| CHVDHINC | DateTime |  | Dh. Inclusão |  |
| CHVDHALT | DateTime |  | Dh. Alteração |  |
| FILTROCHAVE | Integer |  | Código da Chave |  |

## TIMCIL — Contas Compensáveis
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CILIMOVEL | Integer |  | Nro. Imóvel |  |
| CILFORMAPAGTO | String |  | Forma Pagamento | `R`=Prop. pagou - Cobrar e repassar `P`=Por conta do proprietário `I`=Inquilino paga - Adm. acompanha `B`=Adm. paga - Cobrar no boleto `A`=Adm. paga - Cobrar do locador |
| CILCONTA | String |  | Tipo Conta | `T`=Taxas Adm. `O`=Outros `I`=IPTU `E`=Energia `C`=Condomínio_(+1)_ |
| CILORIGEM | Integer |  | Tipo Detalhamento |  |
| CILREGISTRO | String |  | Registro |  |
| CILANO | Integer |  | Ano Referência |  |
| CILDATAINICIO | Date |  | Dt. Inicio Referencia |  |
| CILVLORIGEM | Float |  | Vlr. Total |  |
| CILPARCELAS | Integer |  | Qtd. Parcelas |  |
| CILRECEBEDE | String |  | Recebe de | `L`=Locador `I`=Inquilino `A`=Administradora |
| CILREPASSAPARA | String |  | Repassa para | `L`=Locador `I`=Inquilino `A`=Administradora |
| CILPARCRESPONSAVEL | Integer |  | Parceiro Responsável |  |
| CILCODIGO | Integer |  | Código |  |

## TIMCIM — Taxas
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CIMDESCRICAO | String |  | Descrição |  |
| CIMTIPODECONTA | Integer |  | Tipo Conta | `5`=GÁS `4`=Outros `3`=IPTU `2`=Energia `1`=Condomínio_(+2)_ |
| CIMRESPONSAVEL | String |  | Responsável quando ocupado | `LO`=Locador `IN`=Inquilino `AD`=Administradora |
| CIMCONTRATO | String |  | Contrato |  |
| CIMDIAVENCTO | Integer |  | Dia de Vcto. |  |
| CIMDTULTAPRESENTACAO | Date |  | Dt. Última Apresentação |  |
| CIMIMOVEL | Integer |  | Imóvel |  |
| CIMVALORFIXO | Float |  | Valor Fixo |  |
| CIMPARCDESP | Integer |  | Cód. Parc. Despesa |  |
| CIMHISTORICO | Integer |  | Tipo de Detalhamento |  |
| CIMCODIGO | Integer |  | Código |  |

## TIMCIP — Parcelas
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CIPIMOVEL | Integer |  | Cod. Imóvel |  |
| CIPCODCIL | Integer |  | Cod. Conta |  |
| CIPREGISTRO | String |  | Registro |  |
| CIPPARCELA | Integer |  | Parcela |  |
| CIPVLORIGEM | Float |  | Valor |  |
| CIPVENCIMENTO | Date |  | Dt. Vcto. |  |
| CIPREFINICIO | Date |  | Inicio Referência |  |
| CIPREFFINAL | Date |  | Término Referência |  |
| CIPVLPAGO | Float |  | Vlr. Pago |  |
| CIPPAGAMENTO | Date |  | Dt. Pagamento |  |
| CIPNUFIN | Integer |  | Nu. Financeiro |  |
| CIPDETALHAMENTO | Integer |  | Cód. Detalhamento |  |
| CIPCODIGO | Integer |  | Código |  |

## TIMCIT — TABLE TIMCIT
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CITCODIGO | Integer |  | Cod. Comissionamento |  |
| CITVIGENCIA | Date |  | Dt. Limite |  |
| CITCOMAVISTA | Float |  | Comissão a vista |  |
| CITINCORPAOVALOR | String |  | Incorporada ao valor | `S`=Sim `N`=Não |

## TIMCLA — Contratos de Venda
Campos: 38

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CLADESCRICAO | String |  | Descrição |  |
| CLAIMOVEL | Integer |  | Imóvel |  |
| CLACONTRATOADM | Integer |  | Contrato de Adm. |  |
| CLAEMPREENDIMENTO | Integer |  | Empreendimento |  |
| CLATIPO | String |  | Tipo do Contrato | `VE`=Venda `TT`=Taxa de Transferência `TC`=Taxa de Despachante `PR`=Proposta `PL`=Parceria Loteamento_(+3)_ |
| CLAINVESTIMENTO | String |  | Finalidade | `MO`=Moradia `IN`=Investimento `FA`=Uso Família `AL`=Aluguel |
| CLAESTAGIO | String |  | Estágio | `RE`=Registro `PR`=Proposta Assinada `PE`=Pendente `HA`=Habite-se `FZ`=Finalizado_(+4)_ |
| CLAVALORTOTAL | Float |  | Vlr. Total |  |
| CLACOMISSAO | Float |  | Comissão (%) |  |
| CLACOMISSAOVALOR | Float |  | Vlr. Comissão Recebida |  |
| CLACORRETOR | Integer |  | Corretor |  |
| CLACORRBANCARIO | Float |  | Vlr. Corresp. Bancário |  |
| CLAGERENTECOR | Integer |  | Supervisor |  |
| CLAGERGERCOR | Integer |  | Gerente |  |
| CLAPERCENTUALPARCERIA | Float |  | Parceria (%) |  |
| CLAVALORMETA | Float |  | Vlr. Final |  |
| CLAVGV | Float |  | Valor Geral de Venda |  |
| CLADATAMOTIFICADAO | Date |  | Dt. Notificação |  |
| CLANAOCOBRAR | String |  | Não Cobrar | `S`=Sim `N`=Não |
| CLANC | String |  | Notif. Cartorial | `S`=Sim `N`=Não |
| CLAPE | String |  | Por Edital | `S`=Sim `N`=Não |
| CLAPROTOCOLO | Integer |  | Protocolo |  |
| CLAJUSTICACOMUN | String |  | Justiça Comum | `S`=Sim `N`=Não |
| CLAACC | String |  | Ação de Conciliação | `SO`=Sobrestamento `SE`=Sentença `OU`=Outros `HO`=Homologação de Acordo `AU`=Audiência_(+2)_ |
| CLAIMOBILIARIA | Integer |  | Imobiliária |  |
| CLACONDICOESDAVENDA | String |  | Condições Venda |  |
| CLACONDICOESDAPOSSE | String |  | Condições Posse |  |
| CLAENTREGACHAVES | Date |  | Dt. Entrega de Chaves |  |
| CLADATAASSINATURA | Date |  | Dt. Assinatura |  |
| CLADATADAPROPOSTA | Date |  | Dt. Proposta |  |
| CLADATACANCELAMENTO | Date |  | Dt. Cancelamento |  |
| CLADATADIGITACAO | DateTime |  | Dh. Cadastro |  |
| CLADHALTER | DateTime |  | Dh. Alteração |  |
| CLAVALORDOSINAL | Float |  | Vlr. Sinal |  |
| CLANUCHECKLIST | Integer |  | CheckList do contrato |  |
| CLACODIGO | Integer |  | Código |  |
| FILTROCOMPRADOR | Integer |  | Comprador |  |
| FILTROVENDEDOR | Integer |  | Vendedor |  |

## TIMCLC — TimCompradorVenda
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CLCCOMPRADOR | Integer |  | Comprador |  |
| CLCPERCENTUALDACOMPRA | Float |  | Percentual da Compra |  |
| CLCESTAGIO | String |  | Ativo | `S`=Sim `N`=Não |
| CLCRESPBOL | String |  | Responsável pelo Bolelo | `S`=Sim `N`=Não |
| CLCCONTRATO | Integer |  | Contrato |  |

## TIMCLF — Classificados
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CLFDESCRICAO | String |  | Descrição |  |
| CLFVEICULO | Integer |  | Veículo |  |
| CLFOBSERVACAO | String |  | Observações |  |
| CLFESTAGIO | String |  | Estágio | `P`=Publicado `I`=Impresso `G`=Gerado |
| CLFPARAQUE | String |  | Utilizado para | `V`=Venda `L`=Locação |
| CLFDATAINI | Date |  | Dt. Início Publicação |  |
| CLFDATAFIM | Date |  | Dt. Fim Publicação |  |
| CLFMOSTRAPRECO | String |  | Apresenta Valor | `S`=Sim `N`=Não |
| CLFCODIGO | Integer |  | Código |  |

## TIMCNF — Tim Modelo Nota
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNFDESCRICAO | String |  | Descrição |  |
| CNFCONFIRMARNOTA | String |  | Confirmar | `S`=Sim `N`=Não |
| CNFPROJCORRBANC | String |  | Projeto Corresp. Bancário | `S`=Sim `N`=Não |
| CNFCODPROD | Integer |  | Serviço |  |
| CNFCODCFO | Integer |  | CFOP |  |
| CNFCODCTABCOINT | Integer |  | Conta Bancária |  |
| CNFNUNOTA | Integer |  | Modelo NF. |  |

## TIMCNI — Tim Modelo Nota Criterio
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNINUNOTA | Integer |  | Modelo de Nota |  |
| CNITIPO | String |  | Utilizado Para | `VL`=Venda de Lote `VE`=Venda `PR`=Proposta `MF`=MFD `CB`=Correspondente Bancário_(+2)_ |
| CNILANCAMENTO | String |  | Lançamento | `S`=Sim `N`=Não |
| CNIPRODUTO | String |  | Produto | `VI`=Venda de Imóvel `LT`=Loteamento `LO`=Locação `CB`=Corresp. Bancário `AD`=Administração |
| CNISEQUENCIA | Integer |  | Código |  |

## TIMCOL — TIMCOL
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODMODULO | Integer |  | Cód. Módulo |  |
| CLASSNAME | String |  | Class Name |  |
| NUCOL | Integer |  | Nro. Único |  |

## TIMCOR — Corretores
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CORNOMECARTAOVISITA | String |  | Nome Cartão |  |
| COREMAILCARTAOVISITA | String |  | E-mail Cartão |  |
| CORPARCEIRO | Integer |  | Parceiro |  |
| CORIMOBILIARIA | Integer |  | Imobiliária |  |
| CORESTAGIO | String |  | Ativo | `S`=Sim `N`=Não |
| CORGERENTE | Integer |  | Superior Imediato |  |
| CORCENTROCUSTO | Integer |  | Centro de Resultado |  |
| CORDATAADMISSAO | Date |  | Dt. Admissão |  |
| CORDATADESLIGAMENTO | Date |  | Dt. Desligamento |  |
| CORREGIAO | Integer |  | Região | `9`=Bahia `8`=Distrito Federal `7`=Pernambuco `6`=Paraná `5`=Goiás_(+19)_ |
| CORCRECI | Integer |  | CRECI |  |
| COREXPIRACRECI | Date |  | Dt. Expiração |  |
| CORLOCACAO | String |  | Locação | `S`=Sim `N`=Não |
| CORVENDA | String |  | Venda | `S`=Sim `N`=Não |
| CORECOLABORADOR | String |  | Colaborador | `S`=Sim `N`=Não |
| COREGERENTE | String |  | Gerente | `S`=Sim `N`=Não |
| CORSUPERVISOR | String |  | Supervisor | `S`=Sim `N`=Não |
| CORADMINISTRATIVO | String |  | Administrativo | `S`=Sim `N`=Não |
| CORCAPTADOR | String |  | Captador | `S`=Sim `N`=Não |
| CORCORRETOR | String |  | Corretor | `N`=Não `S`=Sim |
| CORESTAGIARIO | String |  | Estagiário | `S`=Sim `N`=Não |
| COREXTERNO | String |  | Externo | `S`=Sim `N`=Não |
| CORINDICADOR | String |  | Indicador | `S`=Sim `N`=Não |
| CORPASTA | Integer |  | Nro. Pasta Física |  |
| CORPROCESSO | Integer |  | Nro. Processo |  |
| CORPERIODO | String |  | Período Atuação | `V`=Vespertino `N`=Não informado `M`=Matutino `A`=Ambos |
| CORDTINICIOCONT | Date |  | Dt. Início Contrato |  |
| CORFIMCONTRATO | Date |  | Dt. Fim Contrato |  |
| COREPAUNIDGER | Integer |  | Unidade gerencial |  |
| COREPAINDICVENDA | String |  | Indicador de venda |  |
| COREPAVLRMETAIND | String |  | Vlr. da meta individual |  |
| COREPAVLRMETAGERENTE | String |  | Vlr. da meta do gerente |  |
| CORUSUARIO | Integer |  | Usuário Inclusão |  |
| CORUSUARIOALT | Integer |  | Usuário Alteração |  |
| CORDTINCLUSAO | Date |  | Dt. Inclusão |  |
| CORCODIGO | Integer |  | Código |  |

## TIMCTR — TABLE TIMCTR
Campos: 19

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CTRCONTRATO | Integer |  | Contrato |  |
| CTRESTAGIO | String |  | Estágio | `RE`=Renovado `PE`=Pendente `CN`=Cancelado |
| CTRAPROVADO | String |  | Aprovado | `S`=Sim `N`=Não |
| CTRQTDMESES | Integer |  | Qtd. Meses Acumulados |  |
| CTRTXCORRECAO | Float |  | Tx. Correção |  |
| CTRINDICE | Integer |  | Índice |  |
| CTRQTDMESESRENOVAR | Integer |  | Qtd. Meses Renovar |  |
| CTRVALORALUGUEL | Float |  | Vlr. Aluguel Novo |  |
| CTRDIAVENCIMENTO | Integer |  | Dia de Vencimento |  |
| CTRNEGOCIACAO | Integer |  | Negociação |  |
| CTRSACNEGOCIACAO | Integer |  | SAC Negociação |  |
| CTRLOG | String |  | Detalhes |  |
| CTRCODUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| CTRCODUSUALTERACAO | Integer |  | Usuário Alteração |  |
| CTRDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| CTRDHALTERACAO | DateTime |  | Dh. Alteração |  |
| CTRHAPENDENCIAS | String |  | Pendências | `S`=Sim `N`=Não |
| CTRRENOVACAO | Integer |  | Renovação |  |
| CTRVLRALUGUELATUAL | Float |  | Vlr. Aluguel Atual |  |

## TIMDLV — TimRecisao
Campos: 49

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DLVBENFEITORIAS | String |  | Descr. Benfeitorias |  |
| DLVVALORENERGIA | Float |  | Vlr. Energia (-) |  |
| DLVVALORAGUA | Float |  | Vlr. Água (-) |  |
| DLVVALOROUTROS | Float |  | Vlr. Outros Gastos (-) |  |
| DLVVALORHONORARIOS | Float |  | Vlr. Honorários (-) |  |
| DLVVALORCEXTRA | Float |  | Vlr. Custas Extra Jud (-) |  |
| DLVVALORCEDITAL | Float |  | Vlr. Custas  Edital (-) |  |
| DLVVALORCJUSTICA | Float |  | Vlr. Custas Justiça Comum (-) |  |
| DLVVALORBENFEITORIA | Float |  | Vlr. Benfeitorias (+) |  |
| DLVVALORIMPOSTOS | Float |  | Vlr. Impostos (-) |  |
| DLVVALORDESCONTADO | Float |  | Vlr. Descontado |  |
| DLVVALORATUALIZACAO | Float |  | Vlr. Atualização |  |
| DLVPROVISAO | String |  | Estágio Devolução | `PR`=Provisão `ND`=Nada a Devolver `FD`=Ficou Devendo `DC`=Devolução Concluída `CS`=Depósito Consignado_(+1)_ |
| DLVPRIMEIRAPARCELA | Date |  | Dt. Primeira Parcela |  |
| DLVQTDPARCELAS | Integer |  | Qtd. Parcelas |  |
| DLVVALORPAGO | Float |  | Vlr. Pago |  |
| DLVDATA | Date |  | Data |  |
| DLVESTAGIO | String |  | Estágio | `CN`=Cancelada `CA`=Cadastro `EF`=Efetivada |
| DLVTIPORESCISAO | String |  | Tipo | `SJ`=Sentença Judicial `NI`=<Não Informado> `IT`=Inadimplência Total `HO`=Homologatória ____ CCA `DA`=Distrato amigável_(+4)_ |
| DLVAPROVEITHASALDO | String |  | Aproveita Saldo | `S`=Sim `N`=Não |
| DLVDESCRICAO | String |  | Descrição |  |
| DLVCONTRATO | Integer |  | Contrato |  |
| DLVCODIGO | Integer |  | Código |  |
| DLVLRPARCELA | Float |  | Vlr. Parcela |  |
| DLVVLRPERCDESCONTADO | Float |  | Vlr. Descontado % |  |
| DLVVALORTOTAL | Float |  | Vlr. Total |  |
| DLVVALOREMATRASO | Float |  | Vlr. Em Atraso |  |
| DLVPARCELASEMATRASO | Integer |  | Qtd. Parc's. Atraso |  |
| DLVTXRECISAO | Float |  | Vlr. Taxa Rescisão (-) |  |
| DLVQTDPARCABERTO | Integer |  | Qtd. Parc's. Aberto |  |
| DLVQTDPARPAGAS | Integer |  | Qtd. Parc's. Pagas |  |
| DLVVALOREMABERTO | Float |  | Vlr. Em Aberto |  |
| DLVSMJURMUL | Float |  | Vlr. Soma Juros Multa |  |
| DLVCORRECAO | Float |  | Vlr. Correção |  |
| DLVDESCAP | Float |  | Vlr. Descaptalização |  |
| DLVVLRSALDO | Float |  | Vlr. Saldo |  |
| DLVNUACERTO | Integer |  | Nro. Acerto |  |
| DLVNURENEG | Integer |  | Nro. Negociação. Skw |  |
| DLVUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| DLVDHALTERACAO | DateTime |  | Dh. Alteração |  |
| DLVDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| DLVUSUALTERACAO | Integer |  | Usuário. Alteração |  |
| DLVDHEFETIVADA | DateTime |  | Dh. Efetivada |  |
| DLVGEROUPARCS | String |  | Gerou Parcelas | `N`=Não `S`=Sim |
| DLVTXADMRESCISAO | Float |  | Vlr. Tx. Adm.  - Lei Distrato |  |
| DLVVLRRESTCONTRATO | Float |  | Vlr. Contrato Atualizado |  |
| DLVUSUARIO | Integer |  | Usuário Efetivou |  |
| DLVVLRTXFRUICAO | Float |  | Vlr. Tx. Fruição - Lei Distrato |  |
| DLVAPLICARFRUICAO | String |  | Rescisão Conforme Lei do Distrato (nº 13.786/2018) | `S`=Sim `N`=Não |

## TIMDTL — Detalhamentos
Campos: 48

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DLTRECALCIRRF | String |  | Recalcular IRRF | `S`=Sim `N`=Não |
| DTLCODIGO | Integer |  | Código |  |
| DTLCOMPLEMENTO | String |  | Complemento |  |
| DTLCONTRATOLOC | Integer |  | Contrato de Locação |  |
| DTLDATAALTERACAO | DateTime |  | Dh. Alteração |  |
| DTLDATAINCLUSAO | DateTime |  | Dh. Inclusão |  |
| DTLDATAMOV | Date |  | Dt. Atual |  |
| DTLDETALHAMENTO | Integer |  | Detalhamento de origem |  |
| DTLDTFIM | Date |  | Dt. Fim Período |  |
| DTLDTINIC | Date |  | Dt. Início Período |  |
| DTLESTAGIO | Integer |  | DTLESTAGIO |  |
| DTLHISTORICO | Integer |  | Tipo do Detalhamento |  |
| DTLIDENTIFICADOR | Integer |  | DTLIDENTIFICADOR |  |
| DTLIRRF | String |  | Incide no IRRF | `S`=Sim `N`=Não |
| DTLJUROSMULTA | String |  | Incide em juros e multa | `S`=Sim `N`=Não |
| DTLNEGOCIACAO | Integer |  | Negociação |  |
| DTLORIGEM | String |  | Tipo Parcela | `RP`=Repasse `RB`=Repasse ao Beneficiário `LT`=Lotemento `FC`=Fechamento `EA`=Extinta Aluguel_(+3)_ |
| DTLPARCELA | Integer |  | ID Parcela |  |
| DTLPROPORCIONAL | String |  | Proporcional | `S`=Sim `N`=Não |
| DTLRATEADO | Integer |  | DTLRATEADO | `0`=Não `1`=Sim |
| DTLREAJUSTE | Integer |  | Nro. Reajuste |  |
| DTLRECEBEDE | String |  | Recebe de | `I`=Inquilino `A`=Administradora `L`=Locador |
| DTLREPASSAPARA | String |  | Repassa para | `L`=Locador `I`=Inquilino `A`=Administradora |
| DTLSERVICO | Integer |  | Código da OS |  |
| DTLTAXAADM | String |  | Incide na tx. adm. | `S`=Sim `N`=Não |
| DTLUSUARIO | Integer |  | Usuário Inclusão |  |
| DTLUSUARIOALT | Integer |  | Usuário Alteração |  |
| DTLVALOR | Float |  | Valor |  |
| DTLDESVINCULADO | Integer |  | Fin. Desvinculado |  |
| DTLGARANTIDO | String |  | Garantido | `S`=Sim `N`=Não |
| DTLCODIPTU | Integer |  | Cod. IPTU |  |
| DTLDHGERREPASSE | DateTime |  | Dh. Ger. Repasse |  |
| DTLCODORIGEM | Integer |  | Dtl. Origem |  |
| DTLIMOVEL | Integer |  | Imóvel |  |
| DTLPARCELAIPTU | Integer |  | Cod. Parcela IPTU |  |
| DTLFINDESP | Integer |  | Despesa Gerada |  |
| DTLCOMISSAOIPTU | Float |  | Vlr. Comissão Iptu |  |
| DTLORIGCOMISSAO | Integer |  | Dtl Origem Comissão |  |
| DTLCOMPADM | String |  | Compensação Adm | `S`=Sim `N`=Não |
| DTLORIGRENEG | String |  | Repactuação | `N`=Não `S`=Sim |
| DTLPARCDESP | Integer |  | Parceiro para despesa |  |
| DTLDTVENCDESP | Date |  | Dt. Vencimento Despesa |  |
| DTLRENEG | Integer |  | Detalhamento Origem Reneg. |  |
| DTLNUFINRENEG | Integer |  | Financeiro Origem Reneg. |  |
| DTLCONTATO | Integer |  | Contato (Beneficiário) |  |
| DTLNUACERTO | Integer |  | Nro. Acerto Compensação |  |
| DTLINCTXMINIMA | String |  | Incide tx. mínima adm. | `S`=Sim `N`=Não |
| DTLPARCEIRO | Integer |  | Parceiro (Proprietário) |  |

## TIMECR — Custos p/ Condomínio
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ECRREFERENCIA | Date |  | Referência |  |
| ECRTIPO | String |  | Tipo | `SEG`=Seguro(m²) `IPT`=IPTU(m²) `H2O`=Água(m³) `GAS`=Gás(m³) `ENE`=Energia(Kwh) |
| ECRVALOR | Float |  | Valor |  |
| ECREMPREENDIMENTO | Integer |  | Empreendimento |  |

## TIMEDG — Edifícios e Galerias
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EDGEDIFICIO | String |  | Edifício / Galeria |  |
| EDGCONSTRUTORA | Integer |  | Construtora |  |
| EDGEMPREENDIMENTO | Integer |  | Empreendimento |  |
| EDGPODEANIMAIS | String |  | Pode animais | `S`=Sim `N`=Não |
| EDGANDARES | Integer |  | Andares |  |
| EDGPAVIMENTOS | Integer |  | Pavimentos |  |
| EDGAPTOPORANDAR | Integer |  | Aptos por Andar |  |
| EDGELEVADORES | Integer |  | Elevadores |  |
| EDGTORRES | Integer |  | Torres |  |
| EDGSUBSOLO | Integer |  | Sub-solos |  |
| EDGANOCONSTRUCAO | Integer |  | Ano Construção |  |
| EDGIFEAREACONSTRUIDA | Float |  | Área Construída Total (m²) |  |
| EDGCEP | String |  | CEP |  |
| EDGENDFINAL | String |  | Endereço |  |
| EDGENDERECO | String |  | Endereço |  |
| EDGCODEND | Integer |  | Endereço |  |
| EDGCOMPL | String |  | Complemento |  |
| EDGNUMERO | Integer |  | Numero |  |
| EDGBAIRRO | Integer |  | Bairro |  |
| EDGCIDADE | Integer |  | Cidade |  |
| EDGSINDICO | String |  | Nome |  |
| EDGTELEFONES | String |  | Telefone |  |
| EDGEMAIL | String |  | E-Mail |  |
| EDGADMNOME | String |  | Nome |  |
| EDGADMFONE | String |  | Telefone |  |
| EDGADMEMAIL | String |  | E-Mail |  |
| EDGCTBNOME | String |  | Nome |  |
| EDGCTBFONE | String |  | Telefone |  |
| EDGCTBEMAIL | String |  | E-mail |  |
| EDGRATEARPARA | Integer |  | Ratear para |  |
| EDGSEGINCTPCOB | Integer |  | Tipo de cobrança do Seguro Incêndio |  |
| EDGGASNOME | String |  | Fornecedor |  |
| EDGGASFONE | String |  | Telefone |  |
| EDGGASEMAIL | String |  | E-Mail |  |
| EDGCODPARCEIRO | Integer |  | Parceiro |  |
| EDGCODIGO | Integer |  | Código |  |

## TIMEPR — Empreendimentos
Campos: 50

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EPREMPREENDIMENTO | String |  | Empreendimento |  |
| EPRDATADELANCAMENTO | Date |  | Dt. Lançamento |  |
| EPRDATADEENTREGA | Date |  | Dt. Entrega |  |
| EPREDIFICIO | Integer |  | Edifício |  |
| EPRENDERECO | String |  | Endereço |  |
| EPRCODEND | Integer |  | Endereço |  |
| EPRCOMPLEMENTO | String |  | Complemento |  |
| EPRNUMERO | String |  | Numero |  |
| EPRCEP | String |  | C.E.P. |  |
| EPRBAIRRO | Integer |  | Bairro |  |
| EPRCIDADE | Integer |  | Cidade |  |
| EPRTIPO | String |  | Tipo do empreendimento | `SH`=Shopping `PA`=Predio de Apartamentos `CX`=Caixa Economica Federal `CF`=Condominio Fechado `CA`=Casas_(+3)_ |
| EPRAREA | Float |  | Área |  |
| EPRTORRES | Integer |  | Torres |  |
| EPRPAVIMENTOS | Integer |  | Pavimentos por torre |  |
| EPRANDARES | Integer |  | Andares |  |
| EPRAPTOPORANDAR | Integer |  | Apartamentos por andar |  |
| EPRSUBSOLO | Integer |  | Sub-solo |  |
| EPRELEVADORES | Integer |  | Elevadores por torre |  |
| EPRCOMISSAOVENDA | Float |  | Comissão de venda |  |
| EPRCOMISSAOCAPTACAO | Float |  | Comissão de captação |  |
| EPRRESUMIDO | String |  | Nome resumido |  |
| EPRIVV | Integer |  | Índice de Velocidade de Vendas |  |
| EPRMAXPARCELAS | Integer |  | Máximo de parcelas |  |
| EPRTIPOCOMISSAO | Integer |  | Tipo de comissão | `2`=Ambos `0`=Rateio `1`=Lançamento |
| EPRESTAGIO | String |  | Estágio | `SE`=<SEM ESTÁGIO> `CC`=Cancelado `CA`=Cadastro `AP`=Aprovação `SU`=Suspenso_(+1)_ |
| EPRUNIDADES | Integer |  | Unidades |  |
| EPRLANCAMENTO | String |  | Lançamento | `S`=Sim `N`=Não |
| EPRCOMISSAOGERENTE | Float |  | Comissão do gerente |  |
| EPRCOMISSAOSUPERVIS | Float |  | Comissão do supervisor |  |
| EPRGERENTEEMP | Integer |  | Gerente do empreendimento |  |
| EPRPROJETO | Integer |  | Projeto |  |
| EPRCONTACORRENTE | Integer |  | Conta corrente |  |
| EPRUSUARIO | Integer |  | Usuário Inclusão |  |
| EPRUSUARIOALT | Integer |  | Usuário Alteração |  |
| EPRINDICEATECHAVES | Integer |  | Índice até as chaves |  |
| EPRINDICEAPOSCHAVES | Integer |  | Índice após as chaves |  |
| EPRJUROSATECHAVES | Integer |  | Juros até as chaves |  |
| EPRJUROSAPOSCHAVES | Integer |  | Juros após as chaves |  |
| EPRPERIODICIDADEATE | Integer |  | Periodicidade até as chaves |  |
| EPRPERIODICIDADEAPOS | Integer |  | Periodicidade após as chaves |  |
| EPRPROJCORBANCARIO | Integer |  | Projeto Correspondente Bancário |  |
| EPRNUFINMODCCV | Integer |  | Financeiro Mod. CCV |  |
| EPRNUFINMODCE | Integer |  | Financeiro Mod. CE |  |
| EPRNUFINMODCCF | Integer |  | Financeiro Mod. CCF |  |
| EPRNUFINMODFPPF | Integer |  | Financeiro Mod. FPPF |  |
| EPRNUFINMODFPPP | Integer |  | Financeiro Mod. FPPP |  |
| EPRNUFINMODAP | Integer |  | Financeiro Mod. AP |  |
| EPRNUFINMODCDU | Integer |  | Financeiro Mod. CDU |  |
| EPRCODIGO | Integer |  | Código |  |

## TIMFAC — Ficha de Atendimento ao Cliente
Campos: 27

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FACNOMEPPROSPECT | String |  | Nome Prospect |  |
| FACPROSPECT | Integer |  | Prospect |  |
| FACBUSCAPOR | String |  | Interesse em | `VE`=Captação para Venda `LO`=Alugar `CO`=Comprar `CL`=Captação para locação `CB`=Corresp. Bancário_(+2)_ |
| FACCORRETOR | Integer |  | Corretor |  |
| FACESTAGIO | String |  | Estágio | `R`=Retorno Futuro `P`=Prospecção `N`=Negociação `I`=Em Visita `F`=Com Sucesso_(+3)_ |
| FACORIGEM | String |  | Origem | `B`=Parceria `X`=Feirão Caixa `V`=Visita `S`=Internet `R`=Prospecção Telefone_(+5)_ |
| FACVEICULO | Integer |  | Veículo de Comunicação |  |
| FACCAPTACAO | String |  | Captação |  |
| FACCODPARC | Integer |  | Parceiro |  |
| FACRETORNAR | DateTime |  | Dt. Retorno |  |
| FACOBSERVACAO | String |  | Observação |  |
| FACTIPOIMOVEL | Integer |  | Tipo de imóvel |  |
| FACVALORPEDIDO | Float |  | Valor pedido |  |
| FACQUARTOS | Integer |  | Quartos |  |
| FACBAIRROIMOVEL | Integer |  | Bairro do imóvel |  |
| FACEMPREENDIMENTO | Integer |  | Empreendimento |  |
| FACEDIFICIO | Integer |  | Edifício |  |
| FACUSUARIO | Integer |  | Usuário Inclusão |  |
| FACLANCAMENTO | DateTime |  | Dh. Inclusão |  |
| FACUSUALTER | Integer |  | Usuário Alteração |  |
| FACDHALTER | DateTime |  | Dh. Alteração |  |
| FACSITUACAOCHAVE | String |  | Situação Chaves | `R`=Reservou `E`=Entregue `D`=Desistiu |
| FACDOCCHAVE | String |  | Doc. Entrega Chaves |  |
| FACDHENTCHAVE | DateTime |  | Dh. Entrega Chaves |  |
| FACDHDEVCHA | DateTime |  | Dh. Dev. Chaves |  |
| FACMEDIAALUGFAC | Float |  | Média Vlr. Aluguéis Imóveis Fac |  |
| FACCODIGO | Integer |  | Código |  |

## TIMFAI — Itens Fechamento Aluguel
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FAICONTRATOLOC | Integer |  | Contrato de Locação |  |
| FAIREFFORMAPGTO | Date |  | Ref. Forma Pgto. |  |
| FAITOTVENDA | Float |  | Total de Vendas |  |
| FAIFECHAMENTO | Integer |  | Fechamento |  |

## TIMFCI — TABLE TIMFCI
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FCICOMISSAO | Integer |  | Cod. Comissionamento |  |
| FCIMAXVALOR | Float |  | Limite superior |  |
| FCIPERCENTUAL | Float |  | Comissão (%) |  |

## TIMFEA — Fechamento Aluguel
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FEAEMPREENDIMENTO | Integer |  | Empreendimento |  |
| FEAREFERENCIA | Date |  | Referência |  |
| FEAGEROUPARC | String |  | Parcelas geradas | `S`=Sim `N`=Não |
| FEACODIGO | Integer |  | Código |  |

## TIMFEC — Fechamento Condomínio
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FECEMPREENDIMENTO | Integer |  | Empreendimento |  |
| FECREFERENCIA | Date |  | Referência |  |
| FECDESPRATEAVEL | Float |  | Despesa Rateável |  |
| FECPRECOIPTU | Float |  | Preço IPTU |  |
| FECPRECOSEGURO | Float |  | Preço Seguro |  |
| FECGEROUPARC | String |  | Parcelas Geradas | `S`=Sim `N`=Não |
| FECCODIGO | Integer |  | Código |  |
| FECPRECOAGUA | Float |  | Preço Água |  |
| FECPRECOENERGIA | Float |  | Preço Energia |  |
| FECPRECOGAS | Float |  | Preço Gás |  |

## TIMFEI — Itens Fechamento
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FEICONTRATOLOC | Integer |  | Contrato Locação |  |
| FEIVLRIPTU | Float |  | Vlr. IPTU |  |
| FEIVLRSEG | Float |  | Vlr. Seguro |  |
| FEICONSUMOAGUA | Float |  | Consumo Água (m³) |  |
| FEIVLRAGUA | Float |  | Vlr. Água |  |
| FEICONSUMOENERGIA | Integer |  | Consumo Energia (Kwh) |  |
| FEIVLRENERGIA | Integer |  | Vlr. Energia |  |
| FEICONSUMOGAS | Float |  | Consumo Gás (m³) |  |
| FEIVLRGAS | Integer |  | Vlr. Gás |  |
| FEIREFFORMAPGTO | Date |  | Dt. Forma Pagamento |  |
| FEIFECHAMENTO | Integer |  | Fechamento |  |

## TIMFID — TIMFID
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| SQLWHERE | C |  | WHERE |  |
| NUFID | Integer |  | Nro. Único |  |

## TIMFILCHV — TABLE TIMFILCHV
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FILSEQ | Integer |  | Sequência |  |
| FILIMOVEL | Integer |  | Imóvel |  |
| FILFAC | Integer |  | FAC |  |
| FILDHENT | DateTime |  | Data de Entrada |  |
| FILDHEXPIRACAO | DateTime |  | Dt. Expiração |  |

## TIMFPC — Forma Pagamento Condomínio
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FPCREFERENCIA | Date |  | Referência |  |
| FPCTIPO | String |  | Tipo C.C. | `V`=Variável `F`=Fixo |
| FPCVLRFIXO | Float |  | Valor |  |
| FPCPERCPA | Float |  | % Aluguel Percentual |  |
| FPCPERCPE | Float |  | % Ponto Equilíbrio |  |
| FPCBASECALCAP | String |  | Base Cálc. Aluguel Percentual | `CTO`=Custo Total de Ocupação `CMM`=Custo Mínimo Mensal `AMM`=Aluguel Mensal Mínimo |
| FPCCONTRATOLOC | Integer |  | Contrato |  |

## TIMFTC — Faixas de Taxas Cartoriais
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FTCVALOR | Float |  | Valor Limite |  |
| FTCTAXA | Float |  | Taxa % |  |
| FTCFIXO | Float |  | Fixo |  |
| FTCCODIGO | Integer |  | Código |  |

## TIMHCB — Tipo de Detalhamento
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| HCBHISTORICO | String |  | Descrição |  |
| HCBADM | String |  | Incide na tx. adm. | `N`=Não `S`=Sim |
| HCBIRRF | String |  | Incide no IRRF | `N`=Não `S`=Sim |
| HCBJUROS | String |  | Incide em juros e multa | `S`=Sim `N`=Não |
| HCBNATUREZA | Integer |  | Natureza |  |
| HCBRECEBEDE | String |  | Recebe de | `A`=Administradora `L`=Locador / Proprietário `I`=Inquilino / Comprador |
| HCBREPASSAPARA | String |  | Repassa para | `L`=Locador / Proprietário `I`=Inquilino / Comprador `A`=Administradora |
| HCBINCIDEVLRPGO | String |  | Incide Valor Principal | `S`=Sim `N`=Não |
| HCBINCIDEFPP | String |  | Incidde no FPP? | `N`=Não `S`=Sim |
| HCBGARANTIDO | String |  | Garantido | `S`=Sim `N`=Não |
| HCBINCTXMINIMA | String |  | Incide tx mínima adm | `S`=Sim `N`=Não |
| HCBGERADESP | String |  | Gera Despesa | `N`=Não `S`=Sim |
| HCBCODIGO | Integer |  | Código |  |

## TIMHIS — Motivo de SAC
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| HISDESCRICAO | String |  | Descrição |  |
| HISCODIGO | Integer |  | Código |  |

## TIMICK — TABLE TIMICK
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ICKNUITEM | Integer |  | Nu. Item |  |
| ICKDESCRITEM | String |  | Descrição do Item |  |

## TIMIEO — Caracterização do objeto
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IEOLOTEAMEN | Integer |  | Loteamento |  |
| IEOINFRAESTRUTURA | Integer |  | Infraestrutura |  |
| IEOOBSERVACAO | String |  | Observação |  |
| IEOEMPREEND | Integer |  | Empreendimento |  |
| IEOIMOVEL | Integer |  | Imóvel |  |
| IEOEDIFICIO | Integer |  | Edificio |  |
| IEOCODIGO | Integer |  | Código |  |

## TIMIFE — Caracterizações
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IFEINFRAESTRUTURA | String |  | Descrição |  |
| IFECARACTERISTICA | String |  | Característica no Imóvel |  |
| IFECODIGO | Integer |  | Código |  |

## TIMILC — Imóveis do Lugar Certo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ILCIMOVEL | Integer |  | Imóvel |  |
| ILCDATA | Date |  | Data |  |
| ILCINICIO | Date |  | Dt. Início |  |
| ILCQTDDIAS | Integer |  | Qtd. Dias |  |
| ILCUSUARIO | Integer |  | Usuário Alteração |  |
| ILCCODIGO | Integer |  | Código |  |

## TIMIMB — Imobiliárias
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IMBIMOBILIARIA | String |  | Descrição |  |
| IMBCODEMP | Integer |  | Empresa |  |
| IMBESTAGIO | String |  | Ativo | `S`=Sim `N`=Não |
| IMBGERENTE | Integer |  | Gerente |  |
| IMBIMOBILIARIAMATRIZ | Integer |  | Imobiliária Matriz |  |
| IMBOBSERVACAO | C |  | Observação |  |
| IMBREGIAO | Integer |  | Região | `9`=Bahia `8`=Distrito Federal `7`=Pernambuco `6`=Paraná `5`=Goiás_(+19)_ |
| IMBCRECI | Integer |  | CRECI |  |
| IMBEXPIRACRECI | Date |  | Dt. Expiração |  |
| IMBCODCENCUSADM | Integer |  | Administrativo |  |
| IMBCODCENCUSLOCACAO | Integer |  | Locação |  |
| IMBCODCENCUSVENDA | Integer |  | Venda |  |
| IMBCODCENCUSREVENDA | Integer |  | Revenda |  |
| IMBCODCENCUSLOTEAMENTO | Integer |  | Loteamento |  |
| IMBCODCENCUSCORBANCARIO | Integer |  | Corresp. Bancário |  |
| IMBCODCENCUSINCORPORA | Integer |  | Incorporadora |  |
| IMBCODSERVTXADM | Integer |  | Cód. Serviço Tx. Adm |  |
| IMBCODSERVTXINTER | Integer |  | Cód. Serviço Tx. Intermed. |  |
| IMBSERIENOTATXADM | String |  | Série Nota Tx. Adm. |  |
| IMBSERIENOTATXINTER | String |  | Série Nota Tx. Intermed. |  |
| IMBTXMINADM | Float |  | Taxa Mínima Adm |  |
| IMBTXALUPROP | String |  | Tx. mínima s/ aluguel proporcional | `NC`=Não Cobrar `CP`=Cobrar Proporcional `CI`=Cobrar Integral |
| IMBIDWIMOVEIS | String |  | Cód. Wimoveis |  |
| IMBIDIMOVELWEB | String |  | Cód. Imovelweb |  |
| IMBCODIGO | Integer |  | Código |  |
| IMBPARCEIRO | Integer |  | Parceiro Imobiliária |  |

## TIMIMK — TABLE TIMIMK
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IMKITEM | Integer |  | Nu.Item |  |
| IMKMODELOCHK | Integer |  | Nu. Modelo |  |
| IMKOBRIGATORIO | String |  | Obrigatório | `S`=Sim `N`=Não |

## TIMIMP — Proprietários dos imóveis
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IMPCONTRATO | Integer |  | Contrato |  |
| IMPPROPRIETARIO | Integer |  | Proprietário |  |
| IMPCODTIPTIT | Integer |  | Tipo Título p/ Repasse |  |
| IMPPERCENTUAL | Float |  | Posse (%) |  |
| IMPPERCENTUALRETIDO | Float |  | Retido (%) |  |
| IMPCONTACORRENTE | Integer |  | Conta Corrente p/ repasse |  |
| IMPPROCURADOR | Integer |  | Procurador |  |
| IMPDHINC | DateTime |  | Dh. Inclusão |  |
| IMPCODUSUINC | Integer |  | Usuário Inclusão |  |
| IMPDHALTER | DateTime |  | Dh. Alteração |  |
| IMPUSUARIO | Integer |  | Usuário Alteração |  |
| IMPIMOVEL | Integer |  | Cod. Imóvel |  |

## TIMIMV — Imóveis
Campos: 112

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IMVGARAGEMDESCOBERTA | Integer |  | Garagens Descobertas |  |
| IMVCONDFECHADO | String |  | Condomínio Fechado | `S`=Sim `N`=Não |
| IMVCOZINHA | String |  | Cozinha | `N`=Não `S`=Sim |
| IMVPORTARIA | String |  | Portaria | `S`=Sim `N`=Não |
| IMVENDFINAL | String |  | Endereço |  |
| IMVUNIDADEMEDIDA | Integer |  | Unidade de medida |  |
| IMVBAIRRO | Integer |  | Bairro |  |
| IMVIFEMURO | String |  | Muro | `S`=Sim `N`=Não |
| IMVESTAGIO | String |  | Estágio | `VE`=Vendido `ST`=Suspenso Temporariamente `SD`=Suspenso Definitivamente `RE`=Reservado `RC`=Reserva de chaves_(+15)_ |
| IMVCODEND | Integer |  | Endereço |  |
| IMVINTMAPA | String |  | Mostrar Mapa | `S`=Sim `N`=Não |
| IMVIFESOL | String |  | Sol | `S`=Não informado `P`=Poente `I`=Indefinido `N`=Nascente |
| IMVCIDADE | Integer |  | Cidade |  |
| IMVEDIFICIO | Integer |  | Edifício |  |
| IMVIFEDIVARMCOZINHA | String |  | Armários Cozinha | `S`=Sim `N`=Não |
| IMVIFEDIVQTCOMARMARIO | Integer |  | Quartos com armário |  |
| IMVEDICULA | String |  | Edícula | `S`=Sim `N`=Não |
| IMVIFEDIVESTADO | String |  | Estado Conservação | `NV`=Novo `MC`=Mal conservado `CO`=Conservado `BC`=Bem conservado `NI`=Não informado |
| IMVEMPREENDIMENTO | Integer |  | Empreendimento |  |
| IMVDTFIMRESERVA | Date |  | Fim Reserva |  |
| IMVOBSERVACAO | String |  | Ponto Referência |  |
| IMVREGISTROIPTU | String |  | Registro IPTU |  |
| IMVIFEDIVVAGASGARAGEM | Integer |  | Vagas Garagem |  |
| IMVIFEDIVPISCINA | String |  | Piscina | `S`=Sim `N`=Não |
| IMVASSINATURA | String |  | Assinatura Anúncio |  |
| IMVIFEDIVSUITES | Integer |  | Suítes |  |
| IMVAPTO | Integer |  | Apartamento |  |
| IMVURLGOOGLEMAP | String |  | URL Google Map |  |
| IMVIFEGABARITO | String |  | Gabarito | `S`=Sim `N`=Não |
| IMVIFEDIVSALATV | String |  | Sala de TV / Home Teather | `S`=Sim `N`=Não |
| IMVIFEDIVQUARTOS | Integer |  | Quartos |  |
| IMVIFEESQUINA | String |  | Esquina | `S`=Sim `N`=Não |
| IMVIFEDIVEMPREGADA | String |  | Dep. Empregada | `3`=Não informado `2`=Sem dependência `1`=Dependência completa `0`=Quarto |
| IMVIFEDIVREVERSIVEL | Integer |  | Quartos Reversíveis |  |
| IMVAREACONSTRUIDA | Float |  | Área construída (m²) |  |
| IMVIFEFRENTE | String |  | Frente | `S`=Sim `N`=Não |
| IMVFRACAOIDEAL | String |  | Fração Ideal |  |
| IMVAREAPRIVTOTAL | Float |  | Área privativa interna (m²) |  |
| IMVDOCUMENTACAO | Integer |  | Documentação |  |
| IMVIFEAREACONSTRUIDA | Float |  | Área Construída (m²) |  |
| IMVIFEDIVSALAS | Integer |  | Salas |  |
| IMVDFVLCONDOMINIO | Float |  | Vlr. Condomínio |  |
| IMVUSUARIO | Integer |  | Usuário Alteração |  |
| IMVIFEGRADE | String |  | Grade | `S`=Sim `N`=Não |
| IMVDATAENVREDE | Date |  | Dt. Envio Rede Imobiliária |  |
| IMVIFEDIVQTCOMARMARIOS | Integer |  | Quartos com armários |  |
| IMVESTADO | String |  | Estado | `4`=Não informado `3`=Novo `2`=Mal conservado `1`=Conservado `0`=Bem conservado |
| IMVCOMPLEMENTO | String |  | Complemento |  |
| IMVLONGITUDEGPS | Float |  | Longitude |  |
| IMVAREAINTERNA | Float |  | Área Interna (m²) |  |
| IMVANDAR | Integer |  | Andar |  |
| IMVIFEPORTAO | String |  | Portão | `S`=Sem `N`=Não informado `L`=Elétrico `E`=Eletrônico `M`=Manual |
| IMVIFEAREAPRIVATIVA | Float |  | Área Privativa (m²) |  |
| IMVDTVISITA | Date |  | Dt. Visita |  |
| IMVDESCRICAO | String |  | Descrição |  |
| IMVLEMBRETE | String |  | Lembrete de Problema |  |
| IMVESTATISTICA | String |  | Influência em Indicadores | `S`=Sim `N`=Não |
| IMVIFEPISOS | String |  | Pisos | `U`=Único `T`=Três `N`=Não informado `D`=Dois `M`=Mais de três |
| IMVVLRIPTU | Float |  | Vlr. IPTU |  |
| IMVNUMERO | String |  | Número |  |
| IMVIFEAREATERRENO | Float |  | Área Terreno (m²) |  |
| IMVIFEDIVBANHEIROS | Integer |  | Banheiros |  |
| IMVPASTA | Integer |  | Pasta Física |  |
| IMVIFEESGOTO | String |  | Esgoto | `S`=Sim `N`=Não |
| IMVCODIGO | Integer |  | Código |  |
| IMVDATAALTERACAO | DateTime |  | Dh. Alteração |  |
| IMVOCUPACAO | Integer |  | Ocupação | `2`=Desocupado `1`=Inquilino `0`=Proprietário `3`=Não informado |
| IMVIFEDIVCHURRASQEIRA | String |  | Churrasqueira | `S`=Sim `N`=Não |
| IMVIFEDIVMASTER | Integer |  | Suíte Master |  |
| IMVIFEFORRO | String |  | Forro | `SF`=Sem forro `PV`=PVC `PA`=Paulista `NI`=Não informado `MA`=Madeira_(+3)_ |
| IMVDFTABELADEPRECOS | Integer |  | Tabela de preços |  |
| IMVTIPODOIMOVEL | Integer |  | Tipo Imóvel |  |
| IMVDESCRICAOATUAL | String |  | Descrição Completa |  |
| IMVDTPROXCONTATO | Date |  | Próximo Contato |  |
| IMVIFEDIVBOXGARAGEM | String |  | Box Garagens |  |
| IMVGARPARQTD | Integer |  | Qtd. Garagens |  |
| IMVIFEANO | Integer |  | Ano Construção |  |
| IMVCARTORIO | Integer |  | Cartório de Registro |  |
| IMVMOBILIADO | String |  | Mobiliado | `S`=Sim `N`=Não |
| IMVIFEASFALTO | String |  | Asfalto | `S`=Sim `N`=Não |
| IMVEXIBEPRECOSITE | String |  | Exibe Preço no Site | `S`=Sim `N`=Não |
| IMVEXIBECOMDOMINIOSITE | String |  | Exibe Preço Condomínio no Site | `S`=Sim `N`=Não |
| IMVVLRVENDA | Float |  | Vlr. Venda |  |
| IMVANUNCIOJORNAL | String |  | Anúncios Jornal |  |
| IMVVLRALUGUEL | Float |  | Vlr. Aluguel |  |
| NUPEV | Integer |  | Caminho FTP |  |
| IMVENDERECO | String |  | Endereço |  |
| IMVVISIVELSITE | String |  | Publicado no site | `S`=Sim `N`=Não |
| IMVIFELADO | String |  | Lado | `N`=Não informado `E`=Esquerda `D`=Direita |
| IMVCEP | String |  | CEP |  |
| IMVLATITUDEGPS | Float |  | Latitude |  |
| IMVULTADM | Integer |  | Contrato Adm. Locação |  |
| IMVULTADMVENDA | Integer |  | Contrato Adm. Venda |  |
| IMVFACCHAVE | Integer |  | Fac Solicitação Chave |  |
| IMVULTANU | Integer |  | Último Anun. |  |
| IMVCHAVES | String |  | Chaves |  |
| IMVCODUSUINC | Integer |  | Usuário Inclusão |  |
| IMVDHINC | DateTime |  | Dh. Inclusão |  |
| IMVATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| IMVLOCALCHAVES | String |  | Local Chaves | `IM`=Imobiliária `PR`=Proprietário |
| IMVQUINTAL | String |  | Quintal | `S`=Sim `N`=Não |
| IMVAREAGARAGEM | Float |  | Área garagem (m²) |  |
| IMVAVLCONSTRUCAO | Integer |  | Vlr. avaliação construção |  |
| IMVINTENDERECO | String |  | Divulgar Endereço | `S`=Sim `N`=Não `A`=Aproximado |
| IMVCAPTADORLOC | Integer |  | Captador de Locação |  |
| IMVCAPTADORVENDA | Integer |  | Captador para Venda |  |
| IMVCARTDTREGISTRO | Date |  | Data de Registro no Cartório |  |
| IMVCARTFOLHA | String |  | Folha do Livro de Registro |  |
| IMVCARTLIVRO | String |  | Livro de Registro no Cartório |  |
| IMVCARTMATRICULA | String |  | Matrícula do Imóvel |  |
| IMVCARTREGISTRO | String |  | Registro do Imóvel |  |
| IMVGARAGEMCOBERTA | Integer |  | Garagens Cobertas |  |

## TIMINP — TIMINP
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INPCODIGO | Integer |  | Código |  |
| INPNOMEINTEGRACAO | String |  | Descrição |  |
| INPMODULOJAVA | Integer |  | Módulo Java |  |
| INPVIEW | String |  | Nome da View |  |

## TIMINR — TIMINR
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INRSEQ | Integer |  | Sequência |  |
| INRRENEG | Integer |  | Renegociação |  |
| INRCONTRATO | Integer |  | Contrato |  |
| INRDTVENC | Date |  | Dt. Vencimento |  |
| INRTIPOINTERMED | Integer |  | Tipo de Intermediária |  |
| INRVALOR | Float |  | Valor |  |

## TIMINT — TIMINT
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INTSEQ | Integer |  | Sequência |  |
| INTCONTRATO | Integer |  | Contrato |  |
| INTDTVENC | Date |  | Dt. Vencimento |  |
| INTTIPOINTERMED | Integer |  | Tipo de Intermediária |  |
| INTVALOR | Float |  | Valor |  |

## TIMIPO — TIMIPO
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IPOCODIGO | Integer |  | Código |  |
| IPOINTEGRACAO | Integer |  | Integração |  |
| IPONOMEPORTAL | String |  | Nome Portal |  |
| IPOCLASSNAME | String |  | Class Name |  |

## TIMIPR — Imóveis com interesse
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IPRIMOVEL | Integer |  | Imóvel |  |
| IPRCHAVE | String |  | Chaves Entregues | `S`=Sim `N`=Não |
| IPROBSDEVOLUCAO | String |  | Observação |  |
| IPRCODUSUENT | Integer |  | Usu. Resp. Entrega |  |
| IPRDHENTCHAVES | DateTime |  | Dh. Entrega |  |
| IPRUSUARIO | Integer |  | Usuário Inclusão |  |
| IPRDATA | DateTime |  | Dh. Inclusão |  |
| IPRMOTIVO | Integer |  | Motivo Devolução |  |
| IPRPROPESTAGIO | String |  | Proposta | `R`=Rejeitada `P`=Pendente `C`=Cancelada `A`=Aceita |
| IPRPROPPARA | String |  | Proposta para | `V`=Venda `L`=Locação |
| IPRPROPVLRMIN | Float |  | Vlr. Mín. |  |
| IPRPROPVLRMAX | Float |  | Vlr. Máx |  |
| IPRPROPDTLIM | Date |  | Dt. Limite |  |
| IPRCODUSUDEV | Integer |  | Usu. Resp. Devolução |  |
| IPRDHDEVCHAVES | DateTime |  | Dh. Devolução |  |
| IPRCODUSUPROP | Integer |  | Usu. Resp. Proposta |  |
| IPRDHPROP | DateTime |  | Dh. Proposta |  |
| IPRCHVENTREGUE | Integer |  | Chave |  |
| IPRIMOBDEV | Integer |  | Imobiliária de Devolução |  |
| IPRMTVDESIST | Integer |  | Motivo de Desistência |  |
| IPRVLRALUGUEL | Float |  | Valor Aluguel |  |
| IPRESTAGIO | String |  | Estágio | `V`=Em Visita `P`=Em proposta `I`=Vinculado `F`=Fila de Reserva `A`=Proposta Aprovada |
| IPRFAC | Integer |  | FAC |  |
| IPRPOSFILA | Integer |  | Posição na Fila |  |

## TIMIPT — TABLE TIMIPT
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IPTCODIGO | Integer |  | Cód. IPTU |  |
| IPTINSCRICAO | String |  | Inscrição Municipal |  |
| IPTREFERENCIA | Date |  | Referência |  |
| IPTTIPO | String |  | Tipo | `IM`=Imóvel `ED`=Edifício/Galeria |
| IPTREFINICOBRANCA | Date |  | Referência p/ cobrança |  |
| IPTIMOVEL | Integer |  | Imóvel |  |
| IPTEDIFICIO | Integer |  | Edifício/Galeria |  |
| IPTVLRTOT | Float |  | Vlr. Total |  |
| IPTQTDPARC | Integer |  | Qtd. Parcelas |  |
| IPTTXEXPEDIENTE | Float |  | Tx. Expediente |  |
| IPTPERCDESC | Float |  | Desconto % |  |
| IPTCARNENAIMOB | String |  | Carnê na Imobiliária | `S`=Sim `N`=Não |
| IPTOBSERVACAO | String |  | Observação |  |
| IPTREPASSAPARA | String |  | Repassa para | `I`=Inquilino `A`=Administradora `L`=Locador |
| IPTREFINIPAGTO | Date |  | Referência p/ pagamento |  |
| IPTGERAAVULSO | String |  | Gera avulso | `S`=Sim `N`=Não |
| IPTRECEBEDE | String |  | Recebe de | `L`=Locador `I`=Inquilino |
| IPTVLRAVISTA | Float |  | Vlr. previsto à vista |  |
| IPTVLRPARCELADO | Float |  | Vlr. Previsto parcelado |  |
| IPTMULTIIMOVEIS | String |  | Múltiplos imóveis por conta | `S`=Sim `N`=Não |

## TIMIRB — Beneficiarios dos proprietários dos imóveis
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IRBPROPIMOVEL | Integer |  | Proprietário do imóvel |  |
| IRBBENEFICIARIO | Integer |  | Beneficiário |  |
| IRBCODTIPTIT | Integer |  | Tipo título p/ repasse |  |
| IRBCONTRATO | Integer |  | Contrato |  |
| IRBTIPOREPASSE | String |  | Tipo de repasse | `FX`=Fixo `PC`=Percentual |
| IRBPERCENTUAL | Float |  | Percentual que tem direito |  |
| IRBVLRREPASSE | Float |  | Valor fixo para repasse |  |
| IRBIMOVEL | Integer |  | Imóvel |  |

## TIMIVI — TABLE TIMIVI
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IVIIMOVEL | Integer |  | Imóvel |  |
| IVIPERCENTUAL | Float |  | Percentual |  |
| IVIISENTACOMISSAO | String |  | Isenta Comissão | `N`=Não `S`=Sim |
| IVIISENTAIPTU | String |  | Isenta IPTU | `S`=Sim `N`=Não |
| IVIGEROUPARCELAS | String |  | Gerou Parcelas | `S`=Sim `N`=Não |
| IVIIPTU | Integer |  | Cod. IPTU |  |

## TIMLBF — Benfeitorias do Lote
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LBFCONTRATO | Integer |  | Contrato |  |
| LBFUSUARIO | Integer |  | Usuário Criador |  |
| LBFDTBENFT | Date |  | Dt. Inclusão |  |
| LBFDESCRICAO | String |  | Descrição |  |
| LBFVALOR | Float |  | Valor |  |
| LBFCODIGO | Integer |  | Código |  |

## TIMLBL — Detalhes Geração EDI Loteamento
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LBLDHOCORR | DateTime |  | Dh. Ocorrência |  |
| LBLLOG | String |  | Detalhes |  |
| LBLTIPO | String |  | Tipo | `SU`=Sucesso `ER`=Erro `AV`=Aviso |
| LBLSEQUENCIA | Integer |  | Código |  |

## TIMLCF — Fiadores das locações
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LCFFIADOR | Integer |  | Fiador |  |
| LCFESTAGIO | Integer |  | Estágio | `0`=Ativo `1`=Exonerado |
| LCFCANCELAMENTO | Date |  | Dt. Exoneração |  |
| LCFLOCACAO | Integer |  | Locação |  |

## TIMLCL — Locatários
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LCLLOCATARIO | Integer |  | Inquilino |  |
| LCLPERCENTUAL | Integer |  | LCLPERCENTUAL |  |
| LCLBOLETO | String |  | Responsável pelo boleto | `S`=Sim `N`=Não |
| LCLLOCACAO | Integer |  | Locação |  |

## TIMLCR — Negociações
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LCRCONTRATO | Integer |  | Contrato |  |
| LCRCONTADOR | Integer |  | Nro. Negociação |  |
| LCRESTAGIO | String |  | Estágio | `VE`=Vencido `SU`=Suspenso `RE`=Renegociado `JU`=Ativo - No jurídico `EX`=Extinto_(+5)_ |
| LCRDIAVENC | Integer |  | Dia de Vcto. |  |
| LCRDTPRIVENC | Date |  | Dt. Primeiro Venc. |  |
| LCRDATAINICIO | Date |  | Dt. Início Vigência |  |
| LCRPRAZOLOCACAO | Integer |  | Qtd. meses de locação |  |
| LCRDATATERMINO | Date |  | Dt. Término Vigência |  |
| LCRVALORALUGUEL | Float |  | Vlr. Aluguel Negociado |  |
| LCRISENTATARIFABOL | String |  | Isenta tarifa do boleto | `S`=Sim `N`=Não |
| LCRAPOLICE | String |  | Apólice |  |
| LCRVALORSEGURO | Float |  | Vlr. Seguro |  |
| LCRINICIOSEGURO | Date |  | Dt. Início Seguro |  |
| LCRTERMINOSEGURO | Date |  | Dt. Término Seguro |  |
| LCRSEGADM | String |  | Feito com a administradora | `S`=Sim `N`=Não |
| LCROBSERVACAO | String |  | Observação |  |
| LCRGEROUPARCELAS | String |  | Gerou parcelas | `S`=Sim `N`=Não |
| LCRSEGURADORA | String |  | Seguradora |  |
| LCRDATARENEGOCIACAO | DateTime |  | Dh. Inclusão |  |
| LCRCODUSUINC | Integer |  | Usuário Inclusão |  |
| LCRDHALTER | DateTime |  | Dh. Alteração |  |
| LCRUSUARIO | Integer |  | Usuário Alteração |  |
| LCRQTDMPRO | Integer |  | Qtd. Meses Prorrogados |  |
| LCRVALORALUGUELATUAL | Float |  | Vlr. Aluguel Atualizado |  |
| LCRCODIGO | Integer |  | Código |  |

## TIMLDT — TimDetalhamentoLoteamento
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LDTVALOR | Float |  | Valor |  |
| LDTHISTORICO | Integer |  | Tipo do Detalhamento |  |
| LDTRECEBEDE | String |  | Recebe de | `I`=Comprador `L`=Proprietário `A`=Administradora |
| LDTREPASSAPARA | String |  | Repassa para | `A`=Administradora `L`=Proprietário `I`=Comprador |
| LDTPARCELA | Integer |  | ID Parcela |  |
| LDTJUROSMULTA | String |  | Incide em juros e multa | `S`=Sim `N`=Não |
| LDTDATAMOV | Date |  | Dt. Atual |  |
| LDTCOMPLEMENTO | String |  | Complemento |  |
| LDTDTINIC | Date |  | Dt. Início Período |  |
| LDTDTFIM | Date |  | Dt. Fim Período |  |
| LDTREAJUSTE | Integer |  | Nro. Reajuste |  |
| LDTDATAINCLUSAO | DateTime |  | Dh. Inclusão |  |
| LDTUSUARIO | Integer |  | Usuário Inclusão |  |
| LDTDATAALTERACAO | DateTime |  | Dh. Alteração |  |
| LDTUSUARIOALT | Integer |  | Usuário Alteração |  |
| LDTCODIGO | Integer |  | Código |  |

## TIMLFI — TimLogFotosImoveis
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LFIDATA | DateTime |  | Data |  |
| LFITIPO | String |  | Tipo |  |
| LFIPATH | String |  | Path Arquivo |  |
| LFIIMOVEL | Integer |  | Imóvel |  |

## TIMLGP — TABLE TIMLGP
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LGPCODIGO | Integer |  | Código |  |
| LGPCONTRATO | Integer |  | Cod. Contrato |  |
| LGPDATADEPOSITO | Date |  | Dt. Depósito |  |
| LGPDATAVENCTO | Date |  | Dt. Vencimento |  |
| LGPBANCO | Integer |  | Banco |  |
| LGPAGENCIA | String |  | Agência |  |
| LGPVALORDEPOSITO | Float |  | Vlr. Depósito |  |
| LGPVLRCORRIGIDO | Float |  | Vlr. Corrigido |  |
| LGPCONTA | String |  | Conta |  |
| LGPDHCORRECAO | DateTime |  | Dh. Correção |  |

## TIMLGS — TABLE TIMLGS
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LGSCODIGO | Integer |  | Código |  |
| LGSCONTRATO | Integer |  | Cod. Contrato |  |
| LGSVLRSEGURO | Float |  | Vlr. Seguro |  |
| LGSSEGURADORA | Integer |  | Seguradora |  |
| LGSAPOLICE | String |  | Apólice |  |
| LGSCOMISSAO | Float |  | Comissão % |  |
| LGSCORRETORA | Integer |  | Corretora |  |
| LGSDTINIVIGENCIA | Date |  | Dt. Início Vigência |  |
| LGSDTFINVIGENCIA | Date |  | Dt. Término Vigência |  |
| LGSVLRCOBERTURA | Float |  | Vlr. Cobertura |  |
| LGSVLRPREMIO | Float |  | Vlr. Prêmio |  |
| LGSDTCANCELAMENTO | Date |  | Dt. Cancelamento |  |

## TIMLGT — Log Registros
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMETAB | String |  | Tabela |  |
| CAMPO | String |  | Campo |  |
| ACAO | String |  | Ação |  |
| DHACAO | DateTime |  | Dh. Alter |  |
| USUBANCO | String |  | Usuário (Banco) |  |
| USUREDE | String |  | Usuário (Máquina) |  |
| USUSIS | String |  | Usuário (Sistema) |  |
| NOMEMAQUINA | String |  | Máquina |  |
| IPMAQUINA | String |  | IP |  |
| PROGRAMA | String |  | Software |  |
| CHAVE | String |  | Chave Primaria |  |
| VALOR_NOVO | String |  | Valor Novo |  |
| VALOR_VELHO | String |  | Valor Antigo |  |

## TIMLIC — Locação - Garantia imóvel caução
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LICLOCACAO | Integer |  | Locação |  |
| LICIMOVEL | Integer |  | Imóvel |  |
| LICCARTORIO | Integer |  | Cartório |  |
| LICLIVRO | String |  | Livro |  |
| LICFOLHAS | String |  | Folhas |  |
| LICDATALAVRATURA | Date |  | Dt. Lavratura |  |
| LICCARTORIOAVERBACAO | Integer |  | Cartório de averbação |  |
| LICNUMEROAVERBACAO | String |  | Nro. Averbação |  |
| LICDATAAVERBACAO | Date |  | Dt. Averbação |  |
| LICCIRCUNSCRICAO | String |  | Circunscrição |  |
| LICIDENTIFICADOR | Integer |  | Código |  |

## TIMLOC — Locações
Campos: 77

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LOCRENEGOCIACAO | Integer |  | Renegociação Ativa |  |
| LOCTIPOIRRF | String |  | Tipo do IRRF | `0`=Correta (Aluguel - Tx Adm) `1`=Alternativa (Aluguel) |
| LOCAPRESENTACAO | String |  | Descr. Contrato |  |
| LOCESTAGIO | String |  | Estágio | `SU`=Suspenso `RE`=Renegociado `JU`=Ativo - No jurídico `EX`=Extinto `EJ`=Não Utilizar Este Estágio_(+3)_ |
| LOCDATAENCERRAMENTO | Date |  | Dt. Encerr. Contrato |  |
| LOCIMOVEL | Integer |  | Nro. Imóvel |  |
| LOCCONTRATOADM | Integer |  | Nro. Contrato Adm. |  |
| LOCPASTA | Integer |  | Pasta Física |  |
| LOCGARJUSTIFICATIVA | String |  | Lembrete de Problema |  |
| LOCIMOBILIARIA | Integer |  | Imobiliária |  |
| LOCCONTACORRENTE | Integer |  | Conta Corrente |  |
| LOCCORRETOR | Integer |  | Ger. de Carteira |  |
| LOCATENDENTE | Integer |  | Atendente |  |
| LOCSEMBOLETO | String |  | Bloquear Boleto | `S`=Sim `N`=Não |
| LOCMOTIVOBLOQUEIO | String |  | Motivo Bloqueio |  |
| LOCTRANSFERENCIA | String |  | É Transferência | `S`=Sim `N`=Não |
| LOCULTIMAAPRES | Date |  | Dt. última apres. de contas |  |
| LOCDHINC | DateTime |  | Dh. Inclusão |  |
| LOCCODUSUINC | Integer |  | Usuário Inclusão |  |
| LOCDHALTER | DateTime |  | Dh. Alteração |  |
| LOCUSUARIO | Integer |  | Usuário Alteração |  |
| LOCTIPOFPP | String |  | Tipo FPP | `P`=Percentual `F`=Fixo |
| LOCVLRFPP | Float |  | Vlr. FPP |  |
| LOCPERCFPP | Float |  | % FPP |  |
| LOCCRD | Float |  | CRD |  |
| LOCDIAVENCCE | Integer |  | Dia Venc. Condomínio Específico |  |
| LOCDIAVENCCC | Integer |  | Dia Venc. Condomínio Comum |  |
| LOCDIAVENCFPP | Integer |  | Dia Venc. FPP |  |
| LOCDIAVENCAP | Integer |  | Dia Venc. AP |  |
| LOCCRDAREA | Float |  | Área |  |
| LOCCRDLOCAL | Float |  | Localização |  |
| LOCCRDFORMATO | Float |  | Formato |  |
| LOCCRDVITRINE | Float |  | Tamanho Vitrine |  |
| LOCCRDATIVIDADE | Float |  | Atividade |  |
| LOCPRAZODELOCACAO | Integer |  | Qtd. meses de locação |  |
| LOCVALORMERCADO | Float |  | Vlr. Aluguel |  |
| LOCAVENCER | String |  | Pagamento Antecipado | `S`=Sim `N`=Não |
| LOCDIADEPAGAMENTO | Integer |  | Dia de Vcto. |  |
| LOCINDEXADOR | Integer |  | Índice de Correção |  |
| LOCREAJUSTE | String |  | Periodicidade Reajuste | `TR`=Trimestral `SE`=Semestral `ME`=Mensal `BI`=Bimestral `AN`=Anual_(+2)_ |
| LOCGARANTIA | String |  | Tipo Garantia | `SF`=Sem Fiança `SE`=Seguro `PO`=Caução/Poupança `OU`=Outros `IM`=Imóvel Caução_(+2)_ |
| LOCDESTINACAO | String |  | Destinação | `0`=Comercial `2`=Misto `1`=Residencial |
| LOCATIVIDADE | String |  | Atividade |  |
| LOCDTINICPRIREAJUSTE | Date |  | Dt. Início. Primeiro Reajuste |  |
| LOCULTIMOREAJUSTE | Date |  | Dt. Último Reajuste |  |
| LOCDATABASE | Date |  | Dt. Próximo Reajuste |  |
| LOCVALORALUGUEL | Float |  | Vlr. Aluguel Negociado |  |
| LOCDATALOCACAO | Date |  | Dt. início primeira neg. |  |
| LOCDATAINICIO | Date |  | Dt. início última neg. |  |
| LOCDATATERMINO | Date |  | Dt. fim última neg. |  |
| LOCTIPOTXADM | String |  | Tipo de Tx Adm | `PC`=Percentual `ID`=Percentual/Índice `FX`=Fixo |
| LOCPERCENTUALADM | Float |  | Tx. Adm. (%) |  |
| LOCPARCINIADM | Integer |  | Cobrar Tx. Adm. a partir da parcela |  |
| LOCTXADMVLR | Float |  | Tx Adm (Valor) |  |
| LOCINDICETXADM | Integer |  | Índice para Tx Adm |  |
| LOCPRIMEIRO | String |  | Cobrar Tx. Interm. | `S`=Sim `N`=Não |
| LOCPAPERCENTUAL | Float |  | Tx. Interm. (%) |  |
| LOCPAPRIPARC | Integer |  | Cobrar Tx. Interm. a partir da parcela |  |
| LOCPAQTDPARC | Integer |  | Cobrar Tx. Interm. até a parcela: |  |
| LOCGARANTIDO | String |  | Garantido | `S`=Sim `N`=Não |
| LOCDIAS | Integer |  | Qtd. dias até o repasse |  |
| LOCVLRCDU | Float |  | Vlr. Parcela CDU |  |
| LOCQTDPARCCDU | Integer |  | Qtd. Parc. CDU |  |
| LOCCODMOEDACDU | Integer |  | Índice Corr. CDU |  |
| LOCGEROUCDU | String |  | CDU Gerada | `S`=Sim `N`=Não |
| LOCDTREAJUSTECDU | Date |  | Dt. Prox. Reajuste CDU |  |
| LOCDTVENCINICDU | Date |  | Dt. Ini. Venc. CDU |  |
| LOCNUCHECKLIST | Integer |  | CheckList do contrato |  |
| LOCQTDEGARANTIDA | String |  | Garantia Total | `N`=Não `S`=Sim |
| LOCGARANTIDOPOR | Integer |  | Garantido por (meses) |  |
| LOCMESESISENTA | Integer |  | Meses Para Isenção |  |
| LOCMESESMULTA | Integer |  | Meses de Multa |  |
| LOCDESCPONTUAL | Float |  | % Desconto Pontualidade |  |
| LOCCODIGO | Integer |  | Número |  |
| LOCENVIAJUR | String |  | Envia Jurídico Fech. aberto | `S`=Sim `N`=Não |
| LOCCARCORMONE | Integer |  | Carência p/ correção monetária |  |
| LOCCARENCIA | Integer |  | Dias de Carência p/ contrato |  |

## TIMLOT — TimLoteamento
Campos: 74

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LOTLOTEAMENTE | String |  | Descrição |  |
| LOTABREVIADO | String |  | Descr. Abreviada |  |
| LOTPROJETO | Integer |  | Projeto |  |
| LOTPODEESCRITURAR | String |  | Pode escriturar | `S`=Sim `N`=Não |
| LOTESTAGIO | String |  | Estágio | `SU`=Suspenso `NI`=<Não informado> `CO`=Comercialização `CA`=Cancelado `AT`=Alteração de tabela_(+1)_ |
| LOTIMOBILIARIA | Integer |  | Imobiliária |  |
| LOTAVULSO | String |  | Loteamento | `NI`=<Não informado> `FE`=Fechado `AV`=Avulso |
| LOTGERENTE | Integer |  | Gerente |  |
| LOTEMPRESA | Integer |  | Empresa p/ NF |  |
| LOTPROPRIO | String |  | Tipo de Contrato | `SN`=Sociedade - Não Contabiliza `SC`=Sociedade - Contabiliza `PS`=Prestação de serviços `PR`=Próprios `PN`=Parceria - Não Contabiliza_(+2)_ |
| LOTPERCFRUICAO | Float |  | Fruição % |  |
| LOTDATADECADASTRO | Date |  | Dt. Cadastro |  |
| LOTCIDADE | Integer |  | Cidade |  |
| LOTBAIRRO | Integer |  | Bairro |  |
| LOTLOCALIZACAO | String |  | Localização |  |
| LOTCARTORIOSUGE | Integer |  | Cartório Sugerido |  |
| LOTMDLIVRO | String |  | Livro |  |
| LOTDATADECRETO | Date |  | Dt. Decreto |  |
| LOTDECRETO | String |  | Decreto |  |
| LOTMDREGISTRO | String |  | Registro |  |
| LOTMDDATA | Date |  | Dt. Registro |  |
| LOTMDCARTORIO | Integer |  | Cartório |  |
| LOTMDFOLHA | String |  | Folha |  |
| LOTARQARQUIVO | Integer |  | Arquivo |  |
| LOTARQPASTA | String |  | Pasta |  |
| LOTARQGAVETA | Integer |  | Gaveta |  |
| LOTDTNAOCOBRAR | DateTime |  | Definido Em |  |
| LOTSEMBOLETO | String |  | Bloquear Boleto | `S`=Sim `N`=Não |
| LOTNAOCOBRAR | String |  | Não cobrar | `S`=Sim `N`=Não |
| LOTPQNAOCOBRAR | String |  | Motivo |  |
| LOTTOTALDAAREA | Float |  | Total da Área |  |
| LOTQUANTIDADEDELOTES | Integer |  | Qtd. lotes |  |
| LOTSOMACOMISSOES | Float |  | Soma Comissões % |  |
| LOTENTRADA | Float |  | Total Comissões % |  |
| LOTRECAADM | Float |  | Comissão Adminis. % |  |
| LOTSINAL | Float |  | Comissão Corretor % |  |
| LOTGERARECA | String |  | Comissionar por | `S`=Nota de Comissão RECA `N`=Parcelas Diferenciadas |
| LOTRECAPARCEIRO | Float |  | Comissão Franqueada % |  |
| LOTENTRADACOMPOE | String |  | Compõe o preço | `S`=Sim `N`=Não |
| LOTPREMIO | Float |  | Prêmio % |  |
| LOTDESCPARCELA | Float |  | Desconto por Pontualidade % |  |
| LOTPLANOS | String |  | Planos |  |
| LOTTAXAPARTIC | Float |  | Participação % |  |
| LOTRECPARCELAS | String |  | Onde Receber Parc. |  |
| LOTTAXAADM | Float |  | Tx. de Administração % |  |
| LOTCONTACOMP | String |  | Compartilhada | `S`=Sim `N`=Não |
| LOTPREVISAODEINFLACAO | Float |  | Previsão de inflação % |  |
| LOTIPTUNAPARCELA | String |  | ITU na parcela | `S`=Sim `N`=Não |
| LOTEMPPARCERIA | Integer |  | Parceira |  |
| LOTDATADELANCAMENTO | Date |  | Dt. Lançamento |  |
| LOTTAXALIMITADO | Float |  | Limitado a % |  |
| LOTJUROSDOFINANCIAMENTO | Float |  | Tx. Juros % |  |
| LOTPERIODICIDADE | Integer |  | Periodicidade |  |
| LOTATRASOJUROS | Float |  | Juros (mora) % |  |
| LOTATRASOMULTA | Float |  | Multa % |  |
| LOTINDEXADOR | Integer |  | Indexador |  |
| LOTCONTACORRENTE | Integer |  | Conta Bancária |  |
| LOTMINIMODEPARCELAS | Integer |  | Mínimo de parcelas |  |
| LOTMAXIMODEPARCELAS | Integer |  | Máximo de parcelas |  |
| LOTARRAS | Float |  | ARRAS % |  |
| LOTCCENTRADA | Integer |  | Conta Bancária p/ Comissão |  |
| LOTDATABASE | String |  | Data base | `V9`=Venda + 90 `V6`=Venda + 60 `V3`=Venda + 30 `DV`=Data da venda |
| LOTMODFINRENEGPARC | Integer |  | Mod. Parcela Renegociação |  |
| LOTMODFINPARC | Integer |  | Mod. Parcela Financiamento |  |
| LOTDESCONTO | Float |  | Desconto % |  |
| LOTCIRCLESIZE | Integer |  | Tamanho do Círculo |  |
| LOTREGIAO | Integer |  | Região |  |
| LOTBASEPRIJUROS | String |  | Juros Inicia | `PP`=Desde Primeira Parcela `DV`=Desde Data da Venda |
| LOTBASEPRICORR | String |  | Primeira Correção | `VP`=Entre Venda e Primeira Parcela `PP`=Desde Primeira Parcela `DV`=Desde Data da Venda |
| LOTTABELAPRICE | String |  | Price | `S`=Sim `N`=Não |
| LOTCARENCIA | Integer |  | Dias de Carência p/ contrato |  |
| LOTAPLICARFRUICAO | String |  | Aplicar taxas de fruição | `S`=Sim `N`=Não |
| LOTCODIGO | Integer |  | Código |  |
| LOTESTAGIOAPRES | String |  | Estágio de Lote após rescisão | `VE`=Vendido `RV`=Reserva de Validação `RT`=Reserva Técnica `RS`=Reserva Supervisão `RP`=Reserva Proprietário_(+11)_ |

## TIMLPO — Locação - Garantia poupança/outros
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LPOLOCACAO | Integer |  | Locação |  |
| LPODATADEPOSITO | Date |  | Dt. Depósito |  |
| LPODATAVENCTO | Date |  | Dt. Vcto. |  |
| LPOBANCO | Integer |  | Banco |  |
| LPOAGENCIA | String |  | Agência |  |
| LPOVALORDEPOSITO | Float |  | Vlr. Depósito |  |
| LPONUMPROPOSTA | String |  | Nro. Documento |  |
| LPOVLRCORRIGIDO | Float |  | Vlr. Corrigido |  |
| LPODHCORRECAO | Date |  | Dt. Última Correção |  |
| LPOSEGURADORA | Integer |  | Seguradora associada |  |
| LPOAPOLICE | String |  | Apólice |  |
| LPOCOMISSAO | Integer |  | Vlr. Comissão |  |
| LPOCORRETORA | Integer |  | Corretora de Seguros |  |
| LPOIDENTIFICADOR | Integer |  | Código |  |

## TIMLPP — TABLE TIMLPP
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LPPBUSCA | Integer |  | Cod. Busca |  |
| LPPUSUARIO | Integer |  | Usuário Logado |  |
| LPPDHINC | DateTime |  | Dh. Inclusão |  |
| LPPRESULTADOS | Integer |  | Resultados |  |
| LPPXML | C |  | Filtros |  |

## TIMLTC — TABLE TIMLTC
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LTCCODIGO | Integer |  | Código |  |
| LTCCONTRATO | Integer |  | Contrato |  |
| LTCBANCO | Integer |  | Banco |  |
| LTCAGENCIA | String |  | Agência |  |
| LTCVLRTITULO | Float |  | Vlr. Título |  |
| LTCNRODOC | String |  | Nro. Documento |  |
| LTCSEGURADORA | Integer |  | Seguradora |  |
| LTCAPOLICE | String |  | Apólice |  |
| LTCCOMISSAO | Float |  | % Comissão |  |
| LTCDTINIVIGENCIA | Date |  | Início Vigência |  |
| LTCDTRESGATE | Date |  | Dt. Resgate |  |
| LTCCORRETORA | Integer |  | Corretora |  |
| LTCVLRPREMIO | Float |  | Vlr. Prêmio |  |

## TIMLTE — Lotes
Campos: 51

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LTEDESCRICAO | String |  | Descrição |  |
| LTEQUADRA | String |  | Quadra |  |
| LTELOTE | String |  | Lote |  |
| LTELOTEAMENTO | Integer |  | Loteamento |  |
| LTEDHALTERACAO | DateTime |  | Dh. Alteração |  |
| LTEUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| LTEUSUALTERACAO | Integer |  | Usuário Alteração |  |
| LTEDATADECADASTRO | DateTime |  | Dt. Cadastro |  |
| LTEBENFEITORIAS | String |  | Benfeitorias |  |
| LTEENERGIA | String |  | Energia |  |
| LTESITUACAO | String |  | Situação | `S`=Sim `RR`=Reserva de Proposta `N`=Não `VE`=Vendido `RV`=Reserva de Validação_(+15)_ |
| LTETIPOZONA | Integer |  | Zona de uso |  |
| LTEOBS | String |  | Observação |  |
| LTEREGISTROITUIPTU | String |  | Registro ITU/IPTU |  |
| LTEULTIMOIPTU | DateTime |  | Dh. Último IPTU |  |
| LTEBENFEITORIA | String |  | Benfeitoria | `S`=Sim `N`=Não |
| LTEAGUA | String |  | Água |  |
| LTECOMPLEMENTO | String |  | Complemento |  |
| LTECEP | String |  | C.E.P |  |
| LTERUA | String |  | Rua |  |
| LTENUMERO | String |  | Numero |  |
| LTECODEND | Integer |  | Endereço |  |
| LTEBAIRRO | Integer |  | Bairro |  |
| LTECIDADE | Integer |  | Cidade |  |
| LTEX | Integer |  | X |  |
| LTEY | Integer |  | Y |  |
| LTEAREA | Float |  | Área (m²) |  |
| LTEPRECODOMETRO | Float |  | Vlr. M2 |  |
| LTEVALORCOMPRA | Float |  | Vlr. Compra |  |
| LTEDESCPARCELA | Float |  | Vlr. Desc. Parcelas |  |
| LTEVLRLOTE | Float |  | Vlr. Lote |  |
| LTECNFFRENTE | String |  | Conf. Frente |  |
| LTECNFFUNDO | String |  | Conf. Fundo |  |
| LTECNFESQUERDA | String |  | Conf. Esquerda |  |
| LTECNFDIREITA | String |  | Conf. Direita |  |
| LTECNFCHANFRO | String |  | Conf. Chanfro |  |
| LTECNFVARIANTE | String |  | Conf. Variante |  |
| LTEMEDFRENTE | String |  | Med. Frente |  |
| LTEMEDFUNDO | String |  | Med. Fundo |  |
| LTEMEDESQUERDA | String |  | Med. Esquerda |  |
| LTEMEDDIREITA | String |  | Med. Direita |  |
| LTEMEDCHANFRO | String |  | Med. Chanfro |  |
| LTEMEDVARIANTE | String |  | Med. Variante |  |
| LTELIVRO | String |  | Livro |  |
| LTECARTORIO | Integer |  | Cartório |  |
| LTEDATAREGISTRO | Date |  | Dt. Registro |  |
| LTEREGISTRO | String |  | Registro |  |
| LTEESQUINA | String |  | Esquina | `S`=Sim `N`=Não |
| LTEFOLHA | String |  | Folha |  |
| LTEMATRICULA | String |  | Matrícula |  |
| LTECODIGO | Integer |  | Código |  |

## TIMLTP — TimLoteamentoProprietarios
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LTPPROPRIETARIO | Integer |  | Proprietario |  |
| LTPPERCENTUAL | Float |  | Percentual |  |
| LTPFORMADEREPASSE | String |  | Forma de repasse | `OU`=Outros `DP`=Depósito `DI`=Dinheiro |
| LTPREPBANCO | Integer |  | Banco |  |
| LTPREPAGENCIA | String |  | Agência |  |
| LTPREPCONTA | String |  | Conta |  |
| LTPESTAGIO | String |  | Estagio | `C`=Cancelado `A`=Ativo |
| LTPPROCURADOR | Integer |  | Procurador |  |
| LTPLOTEAMENTO | Integer |  | Loteamento |  |

## TIMLTV — Contrato de Venda de Lote
Campos: 85

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FILTROCAMPRADOR | Integer |  | Comprador |  |
| FILTROCPFPARCEIRO | String |  | CPF Comprador |  |
| FILTROLOTE | String |  | Lote |  |
| FILTROLOTEAMENTO | Integer |  | Loteamento |  |
| FILTROOLDCOMPRADOR | Integer |  | Antigo Comprador |  |
| FILTROQUADRA | String |  | Quadra |  |
| LTVGEROUPARCS | String |  | Gerou Parcelas | `S`=Sim `N`=Não |
| LTVCONTRATO | Integer |  | Contrato |  |
| LTVLOTE | Integer |  | Lote |  |
| LTVESTAGIO | String |  | Estágio | `SU`=Suspenso `SP`=Sem Parcelas `QI`=Quitado `PV`=Pré-Venda `PR`=Proposta_(+10)_ |
| LTVDESCRICAO | String |  | Descrição |  |
| LTVLEGADO | String |  | Legado | `S`=Sim `N`=Não |
| LTVCODIGOSISLOTE | Integer |  | Código SISLOTE |  |
| LTVIMVESTIMENTO | String |  | Comprou Para | `UF`=Uso de família `NI`=<Não informado> `MO`=Moradia `LZ`=Lazer `IN`=Investimento_(+1)_ |
| LTVUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| LTVUSUALTERACAO | Integer |  | Usuário Alteração |  |
| LTVDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| LTVDHALTERACAO | DateTime |  | Dh. Alteração |  |
| LTVDATANOTIFICACAO | Date |  | Dt. Notificação |  |
| LTVPROTOCOLO | String |  | Protocolo |  |
| LTVSITUACAO | String |  | Sit. (Situação) | `VI`=Vistoria `TM`=Telefone - Mensagem `SJ`=Sentença Judicial `RE`=Rescisão `PE`=Pendências_(+12)_ |
| LTVIMOBILIARIA | Integer |  | Imobiliária |  |
| LTVPRAZOESCRITURA | String |  | Prazo de Escrituração | `NI`=<Não informado> `6M`=6 Meses `5M`=5 Meses `4M`=4 Meses `3M`=3 Meses_(+2)_ |
| LTVDATACADASTRO | Date |  | Dt. Cadastro |  |
| LTVASSINADOPROPRIETARIO | Date |  | Dt. Ass. Proprietário |  |
| LTVCCA | String |  | Corte Concil. Arbitragem | `ST`=Sentença `SB`=Sobrestamento `OU`=Outros `NI`=<Não informado> `HA`=Homologação de Acordo_(+3)_ |
| LTVPE | String |  | Por. Edital | `S`=Sim `N`=Não |
| LTVNC | String |  | Notif. Cartorial | `S`=Sim `N`=Não |
| LTVURGENCIA | String |  | Urgência | `S`=Sim `N`=Não |
| LTVNAOCOBRAR | String |  | Não cobrar | `S`=Sim `N`=Não |
| LTVVISTORIA | String |  | Vistoria | `S`=Sim `N`=Não |
| LTVEMISSAOCONTRATO | Date |  | Dt. Emissão escritura |  |
| LTVJUSTICACOMUM | String |  | Justiça Comum | `S`=Sim `N`=Não |
| LTVDTOCUPADO | Date |  | Dt. Ocupação |  |
| LTVDATADAVENDA | Date |  | Dt. Venda |  |
| LTVPRECODOLOTE | Float |  | Vlr. Lote |  |
| LTVDESCONTO | Float |  | Vlr. Desconto |  |
| LTVPERCDESCONTO | Float |  | Vlr. Desconto % |  |
| LTVPQDESCONTO | String |  | Justif. Desconto |  |
| LTVPRECOVENDIDO | Float |  | Vlr. Venda |  |
| LTVVALORFECHAMENTO | Float |  | Vlr. Fechamento |  |
| LTVTIPORECA | String |  | Tipo Comissão | `PR`=Promissória `OU`=Outros `NI`=<Não informado> `CH`=Cheques `BO`=Boleto_(+1)_ |
| LTVGERARECA | String |  | Comissionar por | `S`=Nota de Comissão RECA `N`=Parcelas Diferenciadas |
| LTVRECAADM | Float |  | Vlr. Comissão Adminis. |  |
| LTVRECAFRANQUIA | Float |  | Vlr. Comissão Franquia |  |
| LTVRECACORRETOR | Float |  | Vlr. Comissão Corretor |  |
| LTVCOMADMRECA | Float |  | Comissão Adminis. % |  |
| LTVCOMCORRECA | Float |  | Comissão Corretor % |  |
| LTVCOMFRARECA | Float |  | Comissão Franquia % |  |
| LTVCOREXTERNO | String |  | Corretor externo | `S`=Sim `N`=Não |
| LTVGERENTECOR | Integer |  | Ger. Sup. |  |
| LTVSUPERVISORCOR | Integer |  | Supervisor |  |
| LTVCORRETOR | Integer |  | Corretor |  |
| LTVQTPPARDIF | Integer |  | Qtd. Parcela Diferenciada |  |
| LTVTOTALDIFER | Float |  | Vlr. Total Diferenciada |  |
| LTVADIANTAMENTO | Float |  | Vlr. Total Arras |  |
| LTVPARCARRAS | Integer |  | Qtd. Parcela Arras |  |
| LTVPRIPARARRAS | Date |  | Dt. Primeira Arras |  |
| LTVENTRADA | Float |  | Vlr. Total Entrada/Sinal |  |
| LTVQTPPARENTRADA | Integer |  | Qtd. Parcela Entrada/Sinal |  |
| LTVVENCPARENTRADA | Date |  | Dt. Primeira Entrada/Sinal |  |
| LTVDTINICFINANC | Date |  | Dt. Juros Carência |  |
| LTVVLRFINANC | Float |  | Vlr. Financiar |  |
| LTVTABELAPRICE | String |  | Price | `S`=Sim `N`=Não |
| LTVMAISJUROS | Float |  | Tx. Juros % |  |
| LTVPARCELAS | Integer |  | Qtd. Parcelas |  |
| LTVVALORPARCELA | Float |  | Vlr. Parcela |  |
| LTVPRIMEIRAPARCELA | Date |  | Dt. Primeira Parcela |  |
| LTVDTULTREAJUSTE | Date |  | Dt. Últ. Reajuste |  |
| LTVPROXREAJUSTE | Date |  | Dt. Próx. Reajuste |  |
| LTVPERIODICIDADE | Integer |  | Periodicidade |  |
| LTVINDICECORRECAO | Integer |  | Índice Correção |  |
| LTVVLRFINANCBANCO | Float |  | Vlr. Financ. Banco |  |
| LTVPOUPANCA | Float |  | Vlr. Poupança % |  |
| LTVDTFINANCBANCO | Date |  | Dt. Financ. Banco |  |
| LTVPOUPPARCELASVL | Float |  | Vlr. Poupança Parcelas |  |
| LTVPOUPPARCELAS | Integer |  | Parc. Poupança |  |
| LTVPOUPPRICE | String |  | Poup. Price | `S`=Sim `N`=Não |
| LTVOLDJUROS | Float |  | Tx. Juros Original % |  |
| LTVTXCOMMANUAL | String |  | Tx/Comiss. manualmente | `S`=Sim `N`=Não |
| LTVVLRTOTALINTERMED | Float |  | Vlr. Total Intermediárias |  |
| LTVVLRTOTALBALAO | Float |  | Vlr. Total Balões |  |
| LTVAPLICARFRUICAO | String |  | Rescisão Conforme Lei do Distrato (nº 13.786/2018) | `S`=Sim `N`=Não |
| LTVCARENCIA | Integer |  | Dias de Carência p/ contrato |  |
| LTVCODIGO | Integer |  | Código |  |

## TIMLVC — Comprador do Lote
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LVCCONTRATO | Integer |  | Contrato |  |
| LVCCLIENTE | Integer |  | Cliente |  |
| LVCCONTABANC | Integer |  | Conta Bancária |  |
| LVCBOLETO | String |  | Resp. Boleto | `S`=Sim `N`=Não |
| LVCENDERECO | Integer |  | Endereço |  |
| LVCPROCURADOR | Integer |  | Procurador |  |
| LVCDESCRICAO | String |  | Descrição |  |

## TIMLVR — Renegociações de Saldo
Campos: 42

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LVRRENEGOCIACAO | String |  | Renegociação |  |
| LVRTXRENEG | Float |  | Vlr. Tx. Juros Reneg. |  |
| LVRCODIGO | Integer |  | Código |  |
| LVRCONTRATO | Integer |  | Contrato |  |
| LVRALTERATABELA | String |  | Altera para Price | `N`=Não `S`=Sim |
| LVRDATA | Date |  | Dt. Reneg. |  |
| LVRSMJURMUL | Float |  | Vlr. Soma Juros Multa |  |
| LVRMAXDESC | Float |  | Vlr. Limite Desconto |  |
| LVRVALORPAGO | Float |  | Vlr. Pago |  |
| LVRVLPAGORENEGOC | Float |  | Vlr. Amort. Saldo Dev. |  |
| LVRQTDPARPAGAS | Integer |  | Qtd. Parc's. Pagas |  |
| LVRVALOREMATRASO | Float |  | Vlr. Em Atraso |  |
| LVRPARCELASEMATRASO | Integer |  | Qtd. Parc's. Atraso |  |
| LVRVLRTOTALINTERMED | Float |  | Vlr. Total Intermediárias |  |
| LVRDESCONTO | Float |  | Vlr. Desconto |  |
| LVRPQDESCONTO | String |  | Justificativa Desconto |  |
| LVRJUROS | Float |  | Tx. Reneg. % |  |
| LVRAPROVEITASALDO | String |  | Aproveit. Saldo | `N`=Não `S`=Sim |
| LVRVALOREMABERTO | Float |  | Vlr. Em Aberto |  |
| LVRMAISJUROS | Float |  | Tx. Juros % |  |
| LVRVALORPARCELA | Float |  | Vlr. Parcela |  |
| LVRDTPRIPARCELA | Date |  | Dt. Primeira Parc. |  |
| LVRPRIPARCELA | Integer |  | Nro. Primeira Parc. |  |
| LVRESTAGIO | String |  | Estágio | `EF`=Efetivada `AB`=Aberta `CP`=Com Parcelas `CA`=Cancelada |
| LVRNUACERTO | Integer |  | Nro. Acerto |  |
| LVRFINCOMPENSAMORT | Integer |  | Nro. Fin. Compensar |  |
| LVROLDPROXREAJUSTE | DateTime |  | Dt. Old Prox. Reajuste |  |
| LVRCORRECAO | Float |  | Vlr. Correção |  |
| LVRDESCAP | Float |  | Vlr. Descaptalização |  |
| LVRDTAMORTSALDO | Date |  | Dt. Amort. Saldo Dev. |  |
| LVRFINBANCODEVOLVER | Integer |  | Nro. Fin. Devolver Banco |  |
| LVRNURENEG | Integer |  | Nro. Reneg. Skw |  |
| LVRVLRBANCOFECHADO | Float |  | Vlr. Fechado Banco |  |
| LVRFECHAMENTOBANCO | String |  | Fechamento Banco | `S`=Sim `N`=Não |
| LVRVLRBANCODIFER | Float |  | Vlr. Diferença Banco |  |
| LVRVLRBANCOATUAL | Float |  | Vlr. Atual Banco |  |
| LVRVLRBANCODEVOLVER | Float |  | Vlr. Devolver Banco |  |
| LVRQTDPARCELAS | Integer |  | Qtd. Parcelas |  |
| LVROLDJUROS | Float |  | Tx. Juros Anterior % |  |
| LVRVLAPARCELAR | Float |  | Vlr. Refinanciar |  |
| LVRVLRTOTALBALAO | Float |  | Vlr. Total Balões |  |
| LVRQTDPARCABERTO | Integer |  | Qtd. Parc's. Aberto |  |

## TIMMCA — TABLE TIMMCA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MCACODIGO | Integer |  | Código |  |
| MCACMOTIVO | String |  | Motivo de Cancelamento |  |

## TIMMCK — TABLE TIMMCK
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MCKNUMODELO | Integer |  | Nu. Modelo |  |
| MCKTIPOMODELO | String |  | Tipo de Contrato | `R`=Rescisão de Locação `L`=Locação `E`=Venda de Lote `A`=Administração `V`=Venda |
| MCKDTALTER | Date |  | Dt. Alteração |  |
| MCKDTINC | Date |  | Dt. Inclusão |  |

## TIMMDA — Mídias
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MDAMIDIA | String |  | Descrição |  |
| MDACODIGO | Integer |  | Código |  |

## TIMMDS — TABLE TIMMDS
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MDSCODIGO | Integer |  | Código |  |
| MDSMOTIVO | String |  | Motivo |  |

## TIMMFD — Registro MFD
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MFDPRODUTO | String |  | Produto | `VI`=Venda de Imóvel `LT`=Loteamento `LO`=Locação `CB`=Corresp. Bancário `AD`=Administração |
| MFDSEQUENCE | Integer |  | Código |  |
| MFDMODNOTA | Integer |  | Nota Modelo |  |
| MFDNUNOTA | Integer |  | Nro. Nota |  |
| MFDCONTRATOCLA | Integer |  | Contrato Venda Imóvel |  |
| MFDCONTRATOLOC | Integer |  | Contrato Locação |  |
| MFDCONTRATOLTV | Integer |  | Contrato Venda Lote |  |
| MFDCONTRATOADM | Integer |  | Contrato Administração |  |
| MFDCORRESPBANC | Integer |  | Corresp. Bancário |  |
| MFDVLRNOTA | Float |  | Vlr. Nota |  |
| MFDPARCEIRO | Integer |  | Parceiro |  |
| MFDDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| MFDDHALTER | DateTime |  | Dh. Alteração |  |
| MFDUSUINCLUIU | Integer |  | Usuário Inclusão |  |
| MFDUSUALTEROU | Integer |  | Usuário Alteração |  |
| MFDDESCRICAO | String |  | Descrição |  |

## TIMMTD — Motivos de devolução
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MTDMOTIVO | String |  | Descrição |  |
| MTDDESISTENCIA | String |  | Desistiu | `S`=Sim `N`=Não |
| MTDCODIGO | Integer |  | Código |  |

## TIMODA — TIMODA
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRODA | String |  | Descrição |  |
| CAMPOIMOVEL | String |  | Coluna Id. Imóvel |  |
| SQLSELECT | C |  | SELECT |  |
| NUODA | Integer |  | Nro. Único |  |

## TIMOEC — Opções Estagio
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OECOPCAOORIG | String |  | Opção Origem | `SU`=Suspenso `SP`=Sem Parcelas `QI`=Quitado `PV`=Pré-Venda `PR`=Proposta_(+10)_ |
| OECOPCAODEST | String |  | Opção Destino | `PV`=Pré-Venda `PR`=Proposta `PC`=Proposta Cancelada `JU`=Jurídico `HI`=Histórico_(+10)_ |
| OECCODIGO | Integer |  | Código |  |

## TIMORD — TIMORD
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| SQLORDERBY | C |  | ORDER BY |  |
| NUORD | Integer |  | Nro. Único |  |

## TIMPEI — TABLE TIMPEI
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PEIORDEM | Integer |  | PEIORDEM |  |
| PEIESTAGIO | String |  | PEIESTAGIO |  |
| PEIIMOVEL | Integer |  | PEIIMOVEL |  |

## TIMPGT — Armazena informações de financeiros gerados pela imobiliário e loteamento.
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| VLRDESDOB | Float |  | VLRDESDOB |  |
| DTVENC | DateTime |  | DTVENC |  |
| DTCAD | DateTime |  | DTCAD |  |
| PGTCODIGO | Integer |  | PGTCODIGO |  |

## TIMPIN — TIMPIN
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| NUPOR | Integer |  | Portal a utilizar |  |
| NUODA | Integer |  | Fonte a utilizar |  |
| NUFID | Integer |  | Filtro a utilizar |  |
| NUORD | Integer |  | Ordenador a utilizar |  |
| NUCOL | Integer |  | Coletor a utilizar |  |
| NUTRA | Integer |  | Tradutor a utilizar |  |
| NURND | Integer |  | Gerador a utilizar |  |
| DHULTIMAEXEC | DateTime |  | Data e hora |  |
| FILEULTIMAEXEC | String |  | Arquivo gerado |  |
| URLULTIMAEXEC | String |  | Link de acesso |  |
| NUPIN | Integer |  | Nro. Único |  |

## TIMPIP — TABLE TIMPIP
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PIPIPTU | Integer |  | Cod. IPTU |  |
| PIPIMOVEL | Integer |  | Imóvel |  |
| PIPCODIGO | Integer |  | Cod. Único |  |
| PIPVLRPAGO | Float |  | Vlr. Pago |  |
| PIPVLRPARCELA | Float |  | Vlr. Parcela |  |
| PIPVLRPAGOINQ | Float |  | Vlr. p/ inquilino |  |
| PIPDTINIPERIODO | Date |  | Dt. Início Período |  |
| PIPVLRPAGOPROP | Float |  | Vlr. p/ Proprietário |  |
| PIPDTFINPERIODO | Date |  | Dt. Fim Período |  |
| PIPGEROUPARCELAS | String |  | Gerou Parcelas | `S`=Sim `N`=Não |
| PIPPAGO | String |  | Pago | `S`=Sim `N`=Não |
| PIPINCORPAOVALOR | String |  | Incorpora comissão ao valor | `S`=Sim `N`=Não |
| PIPCOMISSAO | Float |  | Comissão |  |

## TIMPOI — Relatorios Doc e Docx
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRPOI | String |  | Descrição |  |
| NOMEARQUIVO | String |  | Arquivo Word |  |
| ARQUIVO | Boolean |  | Arquivo |  |
| SINGLEQUERY | C |  | NativeSQL Query |  |
| JAVACLASS | String |  | Classe Java |  |
| CODPOI | Integer |  | Código |  |

## TIMPOR — TIMPOR
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PORDESCRICAO | String |  | Descrição |  |
| PORCODIGO | Integer |  | Nro. Único |  |

## TIMPOT — TimTelasPoi
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| RESOURCEID | String |  | Resouce ID |  |
| EXPRESSAO | String |  | Expressão |  |
| CODPOI_BKP | Integer |  | Cód. POI |  |
| SEQUENCIA_BKP | Integer |  | Sequencia |  |
| CODPOI | Integer |  | Cód. POI |  |

## TIMPPR — Prospect
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PPRNOME | String |  | Nome |  |
| PPRSEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| PPRTELEFONES | String |  | Telefone |  |
| PPRRAMAL | String |  | Ramal |  |
| PPREMAIL | String |  | E-Mail |  |
| PPRDATADENASCIMENTO | Date |  | Data de nascimento |  |
| PPRTIPO | String |  | Tipo Pessoa | `J`=Jurídica `F`=Física |
| PPRTIPOCLIENTE | String |  | Cliente potencial | `S`=Sim `N`=Não |
| PPRCEP | String |  | CEP |  |
| PPRCIDADE | Integer |  | Cidade |  |
| PPRBAIRRO | Integer |  | Bairro |  |
| PPRCODEND | Integer |  | Cód. Endereço |  |
| PPRENDERECO | String |  | Endereço |  |
| PPRCOMPLEMENTO | String |  | Complemento |  |
| PPRPROFISSAO | Integer |  | Profissão |  |
| PPRPOUPANCA | Float |  | Valor em poupança |  |
| PPRRENDA | Float |  | Renda |  |
| PPRRENDAFORMAL | String |  | Renda formal | `S`=Sim `N`=Não |
| PPRPROFCONJUGE | Integer |  | Profissão do conjuge |  |
| PPRRENDACONJUGE | Float |  | Renda do conjuge |  |
| PPRRENDACNJFORMAL | String |  | Renda do conjuge é formal | `N`=Não `S`=Sim |
| PPROBSERVACAO | String |  | Observação |  |
| PPRFACINI | Integer |  | FAC Inicial |  |
| PPRCPFCNPJ | String |  | CPF/CNPJ |  |
| PPRUSUARIO | Integer |  | Usuário Inclusão |  |
| PPRDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| PPRUSUALTER | Integer |  | Usuário Alteração |  |
| PPRDHALTER | DateTime |  | Dh. Alteração |  |
| PPRCODIGO | Integer |  | Código |  |

## TIMPPV — Proposta de Venda
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PPVPROSPECT | String |  | Nome Prospect |  |
| PPVCPFCNPJ | String |  | CPF |  |
| PPVEMAIL | String |  | E-Mail |  |
| PPVTELEFONE1 | String |  | Telefone |  |
| PPVLOTE | Integer |  | Lote |  |
| PPVVALORPROPOSTA | Float |  | Vlr. Proposta |  |
| PPVOBSERVACAO | String |  | Observação |  |
| PPVORIGEM | String |  | Origem | `ST`=Stand `LX`=Feirão Caixa `LV`=Visita `LR`=Prospecção Telefone `LP`=Plano Piloto_(+5)_ |
| PPVESTAGIO | String |  | Estágio | `NE`=Negociação `FE`=Efetivada `CA`=Cancelada `EX`=Expirada |
| PPVDTPROPOSTA | Date |  | Dt. Proposta |  |
| PPVDHDES | DateTime |  | Dh. Desistência |  |
| PPVMOTIVODES | String |  | Motivo Desistência | `TX`=Taxa `SR`=Sem Retorno `PR`=Preço `PI`=Perda de Interesse `PA`=Parcelamento_(+2)_ |
| PPVIMOBILIARIA | Integer |  | Imobiliária |  |
| PPVCORRETOR | Integer |  | Corretor |  |
| PPVCORSUPERVISOR | Integer |  | Corretor Supervisor |  |
| PPVCORGERENTE | Integer |  | Corretor Gerente |  |
| PPVDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| PPVDHALTERACAO | DateTime |  | Dh. Alteração |  |
| PPVUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| PPVUSUALTERACAO | Integer |  | Usuário Alteração |  |
| PPVDHEXPIRACAO | DateTime |  | Dt. Expiração |  |
| PPVCELULAR | String |  | Celular |  |
| PPVSEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| PPVCIDADE | Integer |  | Cidade |  |
| PPVCODIGO | Integer |  | Código |  |

## TIMPRF — Profissões e Ramos de Atividade
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PRFTIPO | Integer |  | Tipo | `1`=Profissão/ramo de atividade `0`=Agrupador |
| PRFAGRUPADOR | Integer |  | Agrupador |  |
| PRFPROFISSAO | String |  | Profissão |  |
| PRFCODIGO | Integer |  | Código |  |

## TIMPTP — Telefones Prospect
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PTPPROSPECT | Integer |  | Prospect |  |
| PTPTELEFONE | String |  | Telefone |  |
| PTPCOMENTARIO | String |  | Comentário |  |
| PTPCODIGO | Integer |  | Sequencia |  |

## TIMPVD — Pasta Documentos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PVDPASTA | String |  | Pasta |  |
| PVDPRODUTO | String |  | Produto | `VL`=Venda de Lote `RI`=Venda de Imóvel - Revenda `PE`=Pessoa `LT`=Lote `LO`=Loteamento_(+12)_ |
| PVDCODIGO | Integer |  | Código |  |

## TIMQPV — Parcelamento
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QPVIDENTIFICADOR | Integer |  | Sequencia |  |
| QPVTIPO | String |  | Periodiciadade Parcelas | `UN`=Única `TR`=Trimestral `SE`=Semestral `QU`=Quadrimestral `OU`=Outros_(+4)_ |
| QPVTIPOPARCELA | String |  | Tipo | `PO`=Poupança `OU`=Outras taxas `FI`=Financiamento `DI`=Diferença de financiamento `CO`=Parcela de comissão |
| QPVDATAPRIMEIRA | Date |  | Dt. Venc. Primeira Parc. |  |
| QPVQUANTIDADE | Integer |  | Qtd. Parcelas |  |
| QPVVALORPARCELA | Float |  | Vlr Parcela |  |
| QPVVALORPARCELADO | Float |  | Vlr. Total |  |
| QPVINDICE | Integer |  | Índice até chaves |  |
| QPVINDICEAPCHV | Integer |  | Índice após chaves |  |
| QPVFORMAPAGAMENTO | String |  | Forma de Pagamento |  |
| QPVPLANO | Integer |  | Plano |  |
| QPVCONTRATO | Integer |  | Contrato de Venda |  |

## TIMRCL — Rateio das Comissões
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RCLIDENTIFICADOR | Integer |  | Sequencia |  |
| RCLCORRETOR | Integer |  | Corretor |  |
| RCLPESSOA | String |  | Atuação | `IC`=Indicador do Cliente `GE`=Ger. Empreendimento `CO`=Corretor `CI`=Captador do Imóvel `CB`=Corresp. Bancário_(+3)_ |
| RCLORIGEM | String |  | Tipo Pgto. | `FU`=Futura `FO`=Folha `RE`=Reca |
| RCLAPLICARSOBRE | String |  | Base Cálculo | `VV`=Valor Total `VM`=Vlr. Final `VG`=Valor Geral de Venda `VB`=Valor Corresp. Bancário `CA`=Comissão Acertada_(+2)_ |
| RCLPERCENTUAL | Float |  | Percentual |  |
| RCLVALOR | Float |  | Valor |  |
| RCLDTPAGAMENTO | Date |  | Dt. Pagamento |  |
| RCLDTPREVISTO | Date |  | Dt. Previsão Pgto. |  |
| RCLNOTAFISCAL | Integer |  | Nota Fiscal |  |
| RCLEMITENTE | Integer |  | Emitente |  |
| RCLOBSERVACAO | String |  | Observação |  |
| RCLCONTRATO | Integer |  | Contrato de Venda |  |

## TIMRCM — TABLE TIMRCM
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RCMRESCISAO | Integer |  | Cod. Rescisão |  |
| RCMCODIGO | Integer |  | Código |  |
| RCMHISTORICO | Integer |  | Tipo de detalhamento |  |
| RCMREPASSAPARA | String |  | Repassa para | `L`=Locador `I`=Inquilino `A`=Administradora |
| RCMVALOR | Float |  | Valor |  |
| RCMCOMPLEMENTO | String |  | Complemento |  |
| RCMDTINICIO | Date |  | Dt. Início |  |
| RCMDTFIM | Date |  | Dt. Fim |  |
| RCMRECEBEDE | String |  | Recebe de | `L`=Locador `A`=Administradora `I`=Inquilino |
| RCMCODIPTU | Integer |  | Cod. Iptu |  |
| RCMIMOVEL | Integer |  | Imóvel Iptu |  |
| RCMPARCELAIPTU | Integer |  | Parcela Iptu |  |
| RCMGERADESP | String |  | Gera contas a pagar | `S`=Sim `N`=Não |
| RCMPARCDESP | Integer |  | Parceiro |  |
| RCMDTVENCDESP | Date |  | Dt. Vencimento |  |
| RCMFINDESP | Integer |  | Nro. Único Despesa |  |
| RCMGERAALUG | String |  | Gera em parcela avulsa | `S`=Sim `N`=Não |
| RCMNUFINORIGEM | Integer |  | Nro. Único Origem |  |
| RCMORIGEMDESPESA | String |  | Origem Despesa | `S`=Sim `N`=Não |
| RCMDTLORIGEM | Integer |  | Detalhamento Origem |  |

## TIMRCT — TABLE TIMRCT
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RCTDTBASE | Date |  | Dt. Base |  |
| RCTESTAGIO | String |  | Estágio | `CN`=Cancelada `CA`=Cadastro `EP`=Efetivada com Pendências `EF`=Efetivada |
| RCTCODUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| RCTCODUSUALTERACAO | Integer |  | Usuário Alteração |  |
| RCTDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| RCTDHALTERACAO | DateTime |  | Dh. Alteração |  |
| RCTCODIGO | Integer |  | Código |  |

## TIMRCV — Reajuste Contratos
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RCVESTAGIO | String |  | Estágio | `RE`=Reajustado `PE`=Pendente `CN`=Cancelado |
| RCVTXINDICEACM | Float |  | Vlr. Tx. Índice Acum %. |  |
| RCVTXJUROACM | Float |  | Vlr. Tx. Juros Acum %. |  |
| RCVQTDMESES | Integer |  | Qtd. Meses Reajustar |  |
| RCVINDICE | Integer |  | Índice |  |
| RCVTABELAPRICE | String |  | Price | `S`=Sim `N`=Não |
| RCVREAJUSTE | Integer |  | Reajuste |  |
| RCVDTULTREAJUSTE | Date |  | Dt. Últ. Reajuste |  |
| RCVDTREAJUSTE | Date |  | Dt. Reajuste |  |
| RCVLOG | String |  | Detalhes |  |
| RCVCONTRATO | Integer |  | Contrato |  |

## TIMREC — TABLE TIMREC
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RECCODIGO | Integer |  | Código |  |
| RECDTRESCISAO | Date |  | Dt. Rescisão |  |
| RECDTPAGAMENTO | Date |  | Dt. Pagamento |  |
| RECCONTRATOLOC | Integer |  | Contrato de Locação |  |
| RECGEROURESCISAO | String |  | Efetivou Rescisão | `S`=Sim `N`=Não |
| RECNUCHECKLIST | Integer |  | Check List da Rescisão |  |
| RECLOCESTAGIO | String |  | Estágio do Contrato | `SU`=Suspenso `RE`=Renegociado `JU`=Ativo - No jurídico `EX`=Extinto `EF`=Ativo_(+2)_ |

## TIMREL — TABLE TIMREL
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RELDTVENC | Date |  | Dt. Vencimento |  |
| RELVLRDESDOB | Float |  | Vlr. Fechado |  |
| RELDIFIRRF | Float |  | Ajuste IRRF |  |
| RELVLRGRAVADO | Float |  | Vlr. Efetivo |  |
| RELNUFIN | Integer |  | Nro. Único |  |
| RELDTREPASSE | Date |  | Dt. Repasse |  |
| RELDTREPPARCIAL | Date |  | Dt. Repasse Parcial |  |
| RELDHGERREPASSE | DateTime |  | Dh. Ger. Repasse |  |
| RELDHGERREPPARCIAL | DateTime |  | Dh. Ger. Rep. Parcial |  |
| RELACUMULO | Integer |  | Acúmulo |  |
| RELCODIGO | Integer |  | Código |  |

## TIMREN — Renegociação de Parcelas
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RENCONTRATO | Integer |  | Contrato |  |
| RENESTAGIO | String |  | Estágio | `EF`=Efetivada `CA`=Cadastro `CN`=Cancelada |
| RENDTBASE | Date |  | Dt. Base |  |
| RENVLRJUROS | Float |  | Vlr. Juros |  |
| RENVLRMULTA | Float |  | Vlr. Multa |  |
| RENVLRCORR | Float |  | Vlr. Corr. |  |
| RENVLRDESCAP | Float |  | Vlr. Descap |  |
| RENVLRDESC | Float |  | Vlr. Desconto |  |
| RENVLRTOTAL | Float |  | Vlr. Total |  |
| RENVLRENTRADA | Float |  | Vlr. Entrada/Sinal |  |
| RENQTDENTRADA | Integer |  | Qtd. Entrada/Sinal |  |
| RENDTENTRADA | Date |  | Dt. Entrada/Sinal |  |
| RENVLRPARCELAR | Float |  | Vlr. Parcelar |  |
| RENQTDPARCELA | Integer |  | Qtd. Parcela |  |
| RENDTPARCELA | Date |  | Dt. Parcela |  |
| RENVLRBALAO | Float |  | Vlr. Balão |  |
| RENMESBALAO | Integer |  | Mês de Balão | `9`=Setembro `6`=Junho `5`=Maio `4`=Abril `2`=Fevereiro_(+7)_ |
| RENUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| RENDHALTERACAO | DateTime |  | Dh. Alteração |  |
| RENDHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| RENUSUALTERACAO | Integer |  | Usuário Alterou |  |
| RENNURENEG | Integer |  | Nro. Reneg. SKW |  |
| RENCODIGO | Integer |  | Código |  |

## TIMREO — Parcelas Origem Reneg
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REORENEG | Integer |  | Renegociação |  |
| REONUFIN | Integer |  | Nro. Único Parcela |  |
| REODTVENC | Date |  | Dt. Vencimento |  |
| REOVLRJUROS | Float |  | Vlr. Juros |  |
| REOVLRMULTA | Float |  | Vlr. Multa |  |
| REOVLRCORR | Float |  | Vlr. Corr. |  |
| REOVLRDESCAP | Float |  | Vlr. Descap |  |
| REOVLRDESDOB | Float |  | Vlr. Principal |  |
| REOVLRTOTAL | Float |  | Vlr. Total |  |

## TIMREP — Parcelamento Reneg
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REPRENEG | Integer |  | Renegociação |  |
| REPDTVENC | Date |  | Dt. Vencimento |  |
| REPVLRSALDODEV | Float |  | Vlr. Saldo. Dev. |  |
| REPVLRJUROS | Float |  | Vlr. Juros |  |
| REPVLRAMORT | Float |  | Vlr. Amort |  |
| REPVLRBALAO | Float |  | Vlr. Balão |  |
| REPVLRDESDOB | Float |  | Vlr. Parcela |  |
| REPNUFIN | Integer |  | Nro. Único Parcela |  |
| REPTIMORIGEM | String |  | Tipo Parcela | `EN`=Entrada `FI`=Financiamento |
| REPCODIGO | Integer |  | Código |  |

## TIMRET — Reajuste
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RETCODIGO | Integer |  | Nro. Reajuste |  |
| RETDTREAJUSTE | Date |  | Dt. Reajuste |  |
| RETSTART | DateTime |  | Dh. Início |  |
| RETSTOP | DateTime |  | Dh. Termíno |  |
| RETDTCADASTRO | DateTime |  | Dh. Cadastro |  |
| RETDTUSUINCLIU | Integer |  | Usuário Inclusão |  |
| RETDTUSUALTEROU | Integer |  | Usuário Alteração |  |
| RETDETALHES | String |  | Detalhes |  |
| RETESTAGIO | String |  | Estágio | `EP`=Efetivada com Pendências `EF`=Efetivada `CA`=Cadastro `CN`=Cancelada |

## TIMRIC — TABLE TIMRIC
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RICREAJUSTE | Integer |  | Cod. Reajuste |  |
| RICIPTU | Integer |  | Cod. IPTU |  |
| RICIMOVEL | Integer |  | Imóvel |  |
| RICPERCENTUAL | Float |  | Percentual de IPTU |  |
| RICVALOR | Float |  | Valor |  |
| RICPARCELA | Float |  | Vlr. Parcela |  |
| RICQTDEPARC | Integer |  | Qtde. Parcelas |  |
| RICNOVOIPTU | Integer |  | Novo IPTU |  |

## TIMRIP — TABLE TIMRIP
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RIPCODIGO | Integer |  | Cod. Reajuste |  |
| RIPESTAGIO | String |  | Estágio | `PE`=Pendente `CP`=Concluído com Pendências `CC`=Cancelado `CA`=Cadastro `CN`=Concluído |
| RIPREFERENCIA | Date |  | Ano de referência |  |
| RIPREFINICOBRANCA | Date |  | Mês de referência p/ cobrança |  |
| RIPREFINIPAGTO | Date |  | Referência p/ pagamento |  |
| RIPTXEXPEDIENTE | Float |  | Tx Expediente |  |
| RIPDESCONTO | Float |  | Desconto (%) |  |
| RIPPERCREAJUSTE | Float |  | Reajuste (%) |  |
| RIPUSUINC | Integer |  | Usuário de Inclusão |  |
| RIPDHINC | DateTime |  | Dh. Inclusão |  |
| RIPUSUALTER | Integer |  | Usuário de Alteração |  |
| RIPDHALTER | DateTime |  | Dh. Alteração |  |

## TIMRLC — Reajuste Contrato Locação
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RLCREAJUSTE | Integer |  | Nro Reajuste |  |
| RLCESTAGIO | String |  | Estágio | `RE`=Reajustado `CN`=Cancelado `PE`=Pendente |
| RLCINDICE | Integer |  | Índice Correção |  |
| RLCQTDMESES | Integer |  | Qtd. Meses |  |
| RLCTXCORR | Float |  | Tx. Correção Acm. % |  |
| RLCLOG | String |  | Detalhes |  |
| RLCBLOQUEADO | String |  | Canc. Bloq. | `N`=Não `S`=Sim |
| RLCCONTRATO | Integer |  | Nro Contrato |  |

## TIMRLO — Reajuste Locação
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RLOCODIGO | Integer |  | Nro. Reajuste |  |
| RLODHALTERACAO | DateTime |  | Dh. Alteração |  |
| RLODHINCLUSAO | DateTime |  | Dh. Inclusão |  |
| RLOESTAGIO | String |  | Estágio | `EF`=Efetivada `CN`=Cancelada `CA`=Cadastro `EP`=Efetivada com Pendências |
| RLOUSUALTERACAO | Integer |  | Usuário Alteração |  |
| RLOUSUINCLUSAO | Integer |  | Usuário Inclusão |  |
| RLODHREAJUSTE | Date |  | Dt. Reajuste |  |

## TIMRND — TIMRND
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODMODULO | Integer |  | Cód. Módulo |  |
| CLASSNAME | String |  | Class Name |  |
| ENCODING | String |  | Codificação |  |
| TIPOLINGUA | String |  | Linguagem | `JS`=Javascript `JA`=Java |
| DIRNAME | String |  | Nome da Pasta |  |
| FILENAME | String |  | Nome do Arquivo |  |
| OUTPUTTYPE | String |  | Extensão do Arquivo | `XML`=XML `JSO`=JSON |
| LAYOUTXML | C |  | Layout (XML) |  |
| JAVASCRIPT | C |  | Javascript (JSON) |  |
| NURND | Integer |  | Nro. Único |  |

## TIMSAC — Atendimento ao Cliente SAC
Campos: 42

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SACATENDSTATUS | String |  | Status do Atendimento |  |
| SACDATA | DateTime |  | Dt. Inclusão |  |
| SACORIGCHAMADA | String |  | Origem Chamada | `TE`=Telefone `PR`=Presencial `PI`=Processos Internos `OU`=Ouvidoria `ON`=Online_(+4)_ |
| SACTIPO | String |  | Finalidade | `RE`=Reclamação `PR`=Protocolo `OC`=Ocorrência `MP`=Melhoria de processos `EL`=Elogio_(+2)_ |
| SACORIGEM | String |  | Produto | `LE`=Lote `IM`=Imóvel `EP`=Empreendimento `CO`=Corretor `CL`=Contrato de locação_(+6)_ |
| SACCORRETOR | Integer |  | Corretor |  |
| SACLOCACAO | Integer |  | Contrato Locação |  |
| SACVENDAIMV | Integer |  | Contrato de Venda |  |
| SACVENDALOTE | Integer |  | Venda de Lote |  |
| SACFAC | Integer |  | FAC |  |
| SACLOTE | Integer |  | Lote |  |
| SACLOTEAMENTO | Integer |  | Loteamento |  |
| SACIMOVEL | Integer |  | Imóvel |  |
| SACPARCEIRO | Integer |  | Parceiro |  |
| SACEMPREENDIMENTO | Integer |  | Empreendimento |  |
| SACEHOS | String |  | É solicitação de serviços | `S`=Sim `N`=Não |
| SACTIPOHIST | Integer |  | Tipo SAC |  |
| SACOCORRENCIA | String |  | Ocorrência |  |
| SACINTERNET | String |  | Internet | `S`=Sim `N`=Não |
| SACPROMETIDO | Date |  | Dt. Prevista |  |
| SACUSUARIO | Integer |  | Usuário Alteração |  |
| SACDATARES | DateTime |  | Dt. Resultado |  |
| SACDTCONCLUSAO | DateTime |  | Dt. Conclusão |  |
| SACTIPOCOMUNICACAO | String |  | Tipo Comunicação | `T`=Telefone `P`=Pessoalmente `E`=E-Mail `C`=Correspondência `S`=SMS |
| SACRESULTADO | String |  | Resultado |  |
| SACCOMOCONCLUIU | String |  | Estágio | `C`=Concluído `R`=Concluído com reclamação `N`=Não concluído |
| SACCOMSUCESSO | String |  | Com sucesso | `S`=Satisfeito `E`=Elogio `I`=Insatisfeito |
| SACCOMRECLAMACAO | String |  | Motivo Ressalvas | `SE`=Serviço `PR`=Preço `IM`=Imóvel `EM`=Empresa `CR`=Corretor_(+3)_ |
| SACSEMSUCESSO | String |  | Sem sucesso por | `CA`=Cliente ausente `IA`=Impossibilidade de atender `DC`=Deficiência no cadastro |
| SACTIPOOS | String |  | Tipo Serviço | `CF`=Conferência `CB`=Cobrança `AV`=Avaliação `AD`=Adendo de vistoria `VL`=Vistoria - Loteamento_(+10)_ |
| SACCODPARCPREST | Integer |  | Prestador Serviço |  |
| SACQUEMPAGA | String |  | Responsável Pagamento | `L`=Locador `A`=Administradora `I`=Inqulino |
| SACESTAGIOOS | String |  | Estágio Solicitação | `EX`=Executado `AC`=Acertado `SO`=Solicitado `CA`=Cancelado |
| SACVALORSERVICO | Float |  | Vlr. Serviço |  |
| SACSOLICITANTEOS | String |  | Solicitante | `L`=Locador `I`=Inquilino `A`=Administradora |
| SACCONTESTACAO | String |  | Contestação |  |
| SACESTAGIOFAC | String |  | Estágio da FAC | `P`=Prospecção `F`=Com Sucesso `C`=Com Proposta `N`=Negociação `I`=Pegou Chaves_(+1)_ |
| SACDTINIOS | DateTime |  | Dh. Início Execução |  |
| SACDTFINOS | DateTime |  | Dh. Fim Execução |  |
| SACMTVCANCELADO | Integer |  | Motivo de Cancelamento |  |
| SACDHCANCELOS | DateTime |  | Dh. Cancelamento |  |
| SACCODIGO | Integer |  | Código |  |

## TIMSCA — Acompanhamento SAC
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SCACODIGO | Integer |  | Código |  |
| SCADATARES | DateTime |  | Dh. Inclusão |  |
| SCAPROMETIDO | Date |  | Dt. Prevista |  |
| SCASOLICITACAO | String |  | Solicitação |  |
| SCAHORAINICIO | DateTime |  | Dt. Início |  |
| SCAHORAFIM | DateTime |  | Dt. Término |  |
| SCARESULTADO | String |  | Acompanhamento |  |
| SCAUSUARIO | Integer |  | Usuário Inclusão |  |
| SCAUSUDEST | Integer |  | Usuário Destino |  |
| SCASAC | Integer |  | SAC |  |

## TIMSGI — TABLE TIMSGI
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SGICONTRATOLOC | Integer |  | Cod. Contrato |  |
| SGICODIGO | Integer |  | Código |  |
| SGIAPOLICE | String |  | Apólice |  |
| SGIVLRSEGURO | Float |  | Vlr. Seguro |  |
| SGIDTINICIO | Date |  | Dt. Início Seguro |  |
| SGIDTFIM | Date |  | Dt. Término Seguro |  |
| SGIFEITOADM | String |  | Feito com a administradora | `S`=Sim `N`=Não |
| SGISEGURADORA | Integer |  | Seguradora |  |
| SGITIPOSEGURO | String |  | Tipo de seguro | `IM`=Imobiliário `ID`=Individual |
| SGICORRETORA | Integer |  | Corretora |  |
| SGIPERCCOMISSAO | Float |  | Comisssão % |  |
| SGIDTCANCELAMENTO | Date |  | Dt. Cancelamento |  |

## TIMSTATCHV — TABLE TIMSTATCHV
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| STATCOD | Integer |  | Código |  |
| STATDESCRICAO | String |  | Descrição |  |
| STATDISP | String |  | Disponível | `N`=Não `S`=Sim |

## TIMTHI — Tipo de SAC
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| THICODHISTORICO | Integer |  | Motivo |  |
| THIORIGEM | String |  | Produto | `VL`=Venda de Lote `PA`=Parceiro `LO`=Loteamento `LE`=Lote `IN`=Informação_(+8)_ |
| THICODIGO | Integer |  | Código |  |
| THIDESCRICAO | String |  | Descrição Motivo |  |

## TIMTIN — TIMTIN
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TINCODIGO | Integer |  | Código |  |
| TINDESCRICAO | String |  | Descrição |  |

## TIMTIP — TIMTIP
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPIMOVEL | Integer |  | Imóvel |  |
| TIPDESCRESUMO | String |  | Descrição resumida |  |
| TIPDESCRICAOCOMPLETA | String |  | Descrição completa |  |
| TIPQUARTOS | Integer |  | Quartos |  |
| TIPSUITE | Integer |  | Suítes |  |
| TIPBANHEIROS | Integer |  | Banheiros |  |
| TIPGARAGENS | Integer |  | Garagens |  |
| TIPMOBILIA | String |  | Mobiliado | `S`=Sim `N`=Não |
| TIPPISCINA | String |  | Piscina | `S`=Sim `N`=Não |
| TIPCHURRASQUEIRA | String |  | Churrasqueira | `S`=Sim `N`=Não |
| TIPQUINTAL | String |  | Quintal | `S`=Sim `N`=Não |
| TIPMOSTRARMAPA | String |  | Divulgar Mapa | `S`=Sim `N`=Não |
| TIPMOSTRAREND | String |  | Divulgar Endereço |  |
| TIPPLANO | Integer |  | Plano |  |

## TIMTLV — Tranferências
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TLVSEQUENCIA | Integer |  | Sequência |  |
| TLVESTAGIO | String |  | Estágio | `CN`=Cancelada `CA`=Cadastro `EF`=Efetivada |
| TLVDATAEFETIVACAO | Date |  | Dt. Efetivação |  |
| TLVVLTRANSF | Float |  | Vlr. Acertado |  |
| TLVTXTRANSF | Integer |  | Vlr. Tx. Transferência |  |
| TLVCOMENTARIO | String |  | Comentário |  |
| TLVDATA | Date |  | Dt. Cadastro |  |
| TLVNURENEG | Integer |  | Nro. Reneg. SKW |  |
| TLVCONTRATO | Integer |  | Cod. Contrato |  |

## TIMTNP — Novo Comprador
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TNPCONTRATO | Integer |  | Cod. Contrato |  |
| TNPTRANSFERENCIA | Integer |  | Cod. Transferência |  |
| TNPPESSOA | Integer |  | Pessoa |  |
| TNPENDERECO | Integer |  | Endereço |  |
| TNPPROCURADOR | Integer |  | Procurador |  |
| TNPBOLETO | String |  | Resp. Boleto | `S`=Sim `N`=Não |

## TIMTPI — Tipos de Imóveis
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TPITIPODEIMOVEL | String |  | Descrição |  |
| TPITIPO | String |  | Tipo do Imóvel | `SO`=Sobrado `SL`=Sala `RU`=Rural `PR`=Prédio `OU`=Outros_(+6)_ |
| TPIEXIGESEGIND | String |  | Exige Seguro Incêndio | `S`=Sim `N`=Não |
| TPIVIVAREAL | String |  | Tipo | `RSO`=Sobrado `RPE`=Cobertura `RLA`=Lote/Terreno Residencial `RKI`=Kitnet `RHO`=Casa_(+13)_ |
| TPIZAPTIPOIMOVEL | String |  | Tipo | `TRI`=Apartamento Triplex `TER`=Terreno `SOB`=Sobrado `SIT`=Sítio `KIT`=Kitnet_(+9)_ |
| TPIZAPSUBTIPOIMOVEL | String |  | Subtipo | `TRI`=Apartamento Triplex Residencial `TER`=Terreno Padrão `SOB`=Sobrado Residencial `SIT`=Sítio Rural `PRE`=Prédio Inteiro_(+21)_ |
| TPIZAPCATEGRIAIMOVEL | String |  | Categoria | `TRI`=Triplex `TER`=Térrea `STR`=Sobrado/Triplex `SDU`=Sobrado/Duplex `PAD`=Padrão_(+4)_ |
| TPIWIMOVEISTIPO | String |  | Tipo | `TER`=Terreno `RUR`=Rural `COM`=Comercial `CAS`=Casa `APE`=Apartamento |
| TPIWIMOVEISSUBTIPO | String |  | Subtipo | `TRI`=Triplex `TER`=Terreno Padrão `SOB`=Sobrado `QUA`=Quarto `PRE`=Prédio Inteiro_(+28)_ |
| TPICQMTIPO | String |  | Tipo | `9`=Residencial - Terreno `8`=Residencial - Kitnet `7`=Residencial - Flats `5`=Residencial - Chácara `4`=Residencial - Casa em condomínio_(+13)_ |
| TPICODIGO | Integer |  | Código |  |

## TIMTPL — TIMTPL
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TPLDESCRICAO | String |  | Descrição |  |
| TPLPORTAL | Integer |  | Portal |  |
| TPLSIGLA | String |  | Cód. de Integração |  |
| TPLQTDCONTRATADO | Integer |  | Qtd. Contratada |  |
| TPLQTDINSERIDA | Integer |  | Qtd. Incluída |  |
| TPLCODIGO | Integer |  | Código |  |

## TIMTRA — TIMTRA
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODMODULO | Integer |  | Cód. Módulo |  |
| CLASSNAME | String |  | Class Name |  |
| NUTRA | Integer |  | Nro. Único |  |

## TIMTVP — Antigo Comprador
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TVPCONTRATO | Integer |  | Cod. Contrato |  |
| TVPTRANSFERENCIA | Integer |  | Cod. Transferência |  |
| TVPPESSOA | Integer |  | Pessoa |  |
| TVPENDERECO | Integer |  | Endereço |  |
| TVPPROCURADOR | Integer |  | Procurador |  |

## TIMTXC — Taxas e Comissões de Venda de Lt.
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TXCCODIGO | Integer |  | Código |  |
| TXCDESCRICAO | String |  | Descrição |  |
| TXCNROPARCELA | Integer |  | Nro. Parcela |  |
| TXCTIPO | String |  | Tipo | `TR`=Taxa Registro `CO`=Comissão |
| TXCQTDPARCELA | Integer |  | Qtd. Mínima Parcelas |  |
| TXCQTDPARCELAMAX | Integer |  | Qtd. Máxima Parcelas |  |
| TXCPORFAIXA | String |  | Taxa Por Faixa | `S`=Sim `N`=Não |
| TXCTAXASOBRE | String |  | Taxa Sobre | `VL`=Valor do Lote `VF`=Valor Financiado |
| TXCTAXAVALOR | Float |  | Valor Taxa |  |
| TXCTAXALOTE | Float |  | Taxa % |  |
| TXCRECDESP | Integer |  | Receita/Despesa | `1`=Receita `-1`=Despesa |
| TXCORIGEMPARCEIRO | String |  | Origem Parceiro | `PI`=Parceiro Imobiliária `PB`=Parceiro Boleto `GC`=Corretor Gerente `CC`=Corretor `DQ`=Fixo_(+1)_ |
| TXCPARCEIRO | Integer |  | Parceiro |  |
| TXCCODEMP | Integer |  | Empresa |  |
| TXCCODCTABCOINT | Integer |  | Conta |  |
| TXCCODTIPOPER | Integer |  | Tipo de Operação |  |
| TXCCODTIPTIT | Integer |  | Tipo de Título |  |
| TXCCODNAT | Integer |  | Natureza |  |
| TXCCODCENCUS | Integer |  | Centro de Resultado |  |
| TXCCODPROJ | Integer |  | Projeto |  |
| TXCLOTEAMENTO | Integer |  | Loteamento |  |

## TIMTZL — Zonas de Uso
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TZLABREVIACAO | String |  | Abreviação |  |
| TZLZONADEUSO | String |  | Zona de uso |  |
| TZLCODIGO | Integer |  | Código |  |

## TIMVCO — Veículos de comunicação
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VCONOMEDOVEICULO | String |  | Descrição |  |
| VCOMIDIA | Integer |  | Mídia |  |
| VCOCODIGO | Integer |  | Código |  |

## TIMVDO — Vinculo de documentos
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VDODESCRICAO | String |  | Descrição |  |
| VDOPATHSCANNER | String |  | Pasta Documentos |  |
| VDOPRODUTO | String |  | Origem | `PE`=Pessoa `LC`=Locação `IR`=Imóvel - Revenda `IL`=Imóvel - Lançamento `CB`=Corresp. Bancário_(+12)_ |
| VDOCONTRATOCLAVENREV | Integer |  | Venda de Imóvel - Revenda |  |
| VDOCONTRATOCLAIMVREV | Integer |  | Imóvel Revenda |  |
| VDOCONTRATOCLAVENLAN | Integer |  | Venda de Imóvel - Lançamento |  |
| VDOCONTRATOCLAIMVLAN | Integer |  | Imóvel Lançamento |  |
| VDOCONTRATOCLAIMVLOC | Integer |  | Imóvel Locação |  |
| VDOCONTRATOCLAAVAVEN | Integer |  | Avaliação Venda |  |
| VDOCONTRATOCLACORBAN | Integer |  | Correspondente Bancário |  |
| VDOCONTRATOCLAAVALOC | Integer |  | Avaliação Locação |  |
| VDOFICHAATEND | Integer |  | Ficha de Atendimento |  |
| VDOCONTRATOLTV | Integer |  | Contrato Venda de Lote |  |
| VDOCONTRATOLOC | Integer |  | Contrato de Locação |  |
| VDOLOTEAMENTO | Integer |  | Loteamento |  |
| VDOLOTE | Integer |  | Lote |  |
| VDOIMOVEL | Integer |  | Imóvel |  |
| VDOEMPREENDIMENTO | Integer |  | Empreendimento |  |
| VDOCORRETOR | Integer |  | Corretor |  |
| VDOPARCEIRO | Integer |  | Pessoa |  |
| VDODETALHES | String |  | Detalhes p/ Conf. |  |
| VDOPASTA | Integer |  | Pasta |  |
| VDOPROCESSADO | String |  | Processado | `S`=Sim `N`=Não |
| VDOUSUINC | Integer |  | Usuário Incluíu |  |
| VDOUSUALT | Integer |  | Usuário Alterou |  |
| VDODHINC | DateTime |  | Dh. Inclusão |  |
| VDODHALT | DateTime |  | Dh. Alteração |  |
| VDOCODIGO | Integer |  | Código |  |