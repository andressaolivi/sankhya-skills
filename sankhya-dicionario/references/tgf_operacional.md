# TGF — Operacional (Notas, Itens, Parceiros, Vendas)

> Gerado do dicionário oficial TDD Sankhya. 19 tabelas.


## TGFCAB — Entrada e Saída de Produto
Campos: 527

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| CODPARCRETIRADA | Integer |  | Cód. Parceiro Retirada |  |
| TIPSERVCTE | Integer |  | Tipo de serviço CT-e | `0`=Normal `4`=Serviço Vinculado a Multimodal `3`=Redespacho Intermediário `2`=Redespacho `1`=Subcontratação |
| INDNEGMODAL | String |  | Indicador negociável Multimodal | `1`=Negociável `0`=Não negociável |
| TIPOCTE | String |  | Tipo do CT-e | `A`=Anulação `S`=Substituição `N`=Normal `C`=Complementar |
| VLRFRETETOTAL | Float |  | Vlr. Frete Total |  |
| CODPARCTRANSPFINAL | Integer |  | Transportadora Final |  |
| LIBPENDENTE | String |  | Liberação Pendente |  |
| NUNOTA | Integer |  | Nro. Único |  |
| PEDIDOIMPRESSO | String |  | Pedido foi impresso? |  |
| SITUACAOWMS | Integer |  | Situação WMS | `4`=Em processo conferência `16`=Concluído `15`=Enviado para armazenagem `14`=Aguardando armazenagem `13`=Parcialmente conferido_(+17)_ |
| STATUSCONFERENCIA | String |  | Status conferência | `C`=Aguardando liberação de corte `AC`=Aguardando conferência `R`=Aguardando recontagem `F`=Finalizada OK `D`=Finalizada divergente_(+6)_ |
| STATUSWMS | String |  | Status WMS | `4`=Não Controlado pelo WMS `3`=Não enviado `2`=Enviado parcialmente `0`=Pedido parcialmente cortado `1`=Enviado totalmente_(+1)_ |
| TIPLIBERACAO | String |  | Liberação | `A`=Aprovado `P`=Pendente `R`=Reprovado `S`=Sem pendência |
| VLRCOMPENSACAO | Float |  | Valor do crédito |  |
| RETORNADOAC | String |  | Entregue | `N`=Não Entregue `R`=Reentregar `D`=Devolvido `E`=Entregue |
| OBSERVACAOAC | String |  | Observação |  |
| DESCRHISTAC | String |  | Descrição histórico |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| DTNEG | Date |  | Dt. Neg. |  |
| DTESCRCONT | Date |  | Dt. Escrituração Contábil. |  |
| VLRNOTA | Float |  | Vlr. Nota |  |
| SERIENOTA | String |  | Série da nota |  |
| SERIENFSE | String |  | Série NFS-e |  |
| CODEMP | Integer |  | Empresa |  |
| CODTIPOPER | Integer |  | Tipo Operação |  |
| CODTIPVENDA | Integer |  | Tipo Negociação |  |
| CONFIRMADA | String |  | Confirmada | `Sim`=Sim `Não`=Não |
| CONTABILIZADO | String |  | Contabilizado? | `S`=Sim `N`=Não |
| CODVEND | Integer |  | Vendedor |  |
| STATUSNOTA | String |  | Status da Nota | `L`=Liberada `A`=Atendimento `P`=Pendente |
| CODNAT | Integer |  | Natureza |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| TIPMOV | String |  | Tipo de Movimento | `L`=L-Devolução de Requisição `O`=O-Pedido de compra `K`=K-Pedido de Transferência `Q`=Q-Requisição `8`=8-RD8_(+18)_ |
| CODLOCALORIG | Integer |  | Local |  |
| M3AENTREGAR | Float |  | M3 a Entregar |  |
| PESOAENTREGAR | Float |  | Peso a Entregar |  |
| PESOBRUTOITENS | Float |  | Peso bruto dos Itens |  |
| PESOLIQITENS | Float |  | Peso liq. dos Itens |  |
| CODMOEDA | Integer |  | Moeda |  |
| CODHISTAC | Integer |  | Histórico |  |
| BASESUBSTIT | Float |  | Base da Substituição |  |
| HRMOV | Text |  | Hr. do Movimento |  |
| BASEICMSFRETE | Float |  | Base do ICMS do Frete |  |
| BASEICMSSTFRETE | Float |  | Base do ICMS/ST do Frete |  |
| NUMCONTRATO | Integer |  | Contrato |  |
| BASEINSS | Float |  | Base de INSS |  |
| OBSERVACAO | String |  | Observação |  |
| DTALTER | DateTime |  | Dt. de Alteração |  |
| VLRICMS | Float |  | Vlr. do ICMS |  |
| VLRDESCTOT | Float |  | Desconto no total |  |
| VENCIPI | DateTime |  | Vencimento do IPI |  |
| VLRVENDOR | Float |  | Vlr. do Vendor |  |
| TOTALCUSTOSERV | Float |  | Custo Total do Serviço |  |
| VENCFRETE | Date |  | Vencimento do frete |  |
| VLRDESCTOTITEM | Float |  | Desconto total por item |  |
| NUMCOTACAO | Integer |  | Nro. da Cotação |  |
| PERCDESC | Float |  | Percentual de Desconto |  |
| ICMSFRETE | Float |  | ICMS sobre o frete |  |
| ICMSSTFRETE | Float |  | Vlr. ICMS/ST sobre o frete |  |
| PESO | Float |  | Peso |  |
| VLRSUBST | Float |  | Vlr. da Substituição |  |
| DTFATUR | DateTime |  | Dt. do Faturamento |  |
| LOCALENTREGA | String |  | Local de Entrega |  |
| VLRREPREDTOT | Float |  | Desconto Redução de Base |  |
| BASEISS | Float |  | Base do ISS |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| IPIEMB | Float |  | IPI da embalagem |  |
| CODPARCDEST | Integer |  | Parceiro Destinatário |  |
| LOCALCOLETA | String |  | Local de coleta |  |
| VLRFRETECPL | Float |  | Vlr. Frete Complementar |  |
| VLRISS | Float |  | Valor do ISS |  |
| VLRIRF | Float |  | Vlr. do IRF |  |
| VLRFRETE | Float |  | Vlr. do Frete |  |
| VLRMERCADORIA | Float |  | Vlr. da Mercadoria |  |
| VLREMB | Float |  | Vlr. da Embalagem |  |
| COMGER | Float |  | Comissão Gerente |  |
| VOLUME | String |  | Volume |  |
| BASEICMS | Float |  | Base do ICMS |  |
| CODPROJ | Integer |  | Projeto |  |
| IRFRETIDO | String |  | o INSS é retido? | `S`=Sim `N`=Não |
| NOTASCF | String |  | Notas do conhecimento de frete |  |
| TIPFRETE | String |  | Tipo do frete | `S`=Incluso `N`=Extra nota |
| VLRJURO | Float |  | Valor do Juro |  |
| VLRDESTAQUE | Float |  | Vlr. Destaque |  |
| BASEIPI | Float |  | Base do IPI |  |
| VLRIPI | Float |  | Vlr. do IPI |  |
| BASESUBSTSEMRED | Float |  | Base Substituição Sem Redução |  |
| NUMCF | Integer |  | Nro. Conhec. de Frete |  |
| DTENTSAI | Date |  | Dt. Entrada/Saída |  |
| DTCONTAB | DateTime |  | Dt. da Contabilização |  |
| CODPARCREDESPACHO | Integer |  | Redespacho (Recebedor) |  |
| VLRDESCSERV | Float |  | Total desc. serviços |  |
| TOTALCUSTOPROD | Float |  | Custo Total do Produto |  |
| CODOBSPADRAO | Integer |  | Observação padrão |  |
| PREMIACAOESTADUAL | String |  | Premiação Estadual |  |
| ORDEMCARGA | Integer |  | Ordem de carga |  |
| CODPARCTRANSP | Integer |  | Parceiro Transportadora |  |
| VLRINSS | Float |  | Vlr. de INSS |  |
| NUMOS | Integer |  | Nro. da OS |  |
| KMVEICULO | Integer |  | KM |  |
| CODPARCREMETENTE | Integer |  | Parceiro Remetente |  |
| COMISSAO | Float |  | Comissão |  |
| VLRSEG | Float |  | Vlr. do Seguro |  |
| VLRICMSEMB | Float |  | Valor do ICMS da embalagem |  |
| VLROUTROS | Float |  | Vlr. Outros |  |
| CODCONTATO | Integer |  | Contato |  |
| CODVEICULO | Integer |  | Veículo |  |
| AD_MAXIMA_NUMCAR | String |  | Número Carga Máxima |  |
| DH_MAXIMA_LANCAMENTO | DateTime |  | Data Fech. Pedido Máxima |  |
| DH_MAXIMA_NUVEM | DateTime |  | Dt Inclusão Máxima |  |
| AD_MAXIMA_PED_ORIGEM | Integer |  | Máxima Pedido Origem |  |
| AD_MAXIMA_IDPEDIDO | String |  | Id Pedido Máxima Nuvem |  |
| AD_MAXIMA_STATUS | Integer |  | Situação Máxima |  |
| AD_MAXIMA_PEDIDO | String |  | Nº Pedido Máxima |  |
| CODDOCARRECAD | Integer |  | Cód. Mod. Documento de arrecadação | `1`=GNRE `0`=Documento Estadual de Arrecadação |
| NUMDOCARRECAD | String |  | Número Documento de arrecadação |  |
| FRETEVLRPAGO | Float |  | Vlr. frete pago |  |
| NUCFR | Integer |  | Cód. cálculo de frete |  |
| VLRFRETECALC | Float |  | Vlr. frete calc. |  |
| CONFIRMNOTAFAT | String |  | Confirmar ao faturar | `S`=Sim `N`=Não |
| CODCIDINICTE | Integer |  | Cód. Cid. Inicio CT-e |  |
| DIRECAOVIAG | String |  | Direção da viagem | `S`=Sul `O`=Oeste `L`=Leste `N`=Norte |
| IDBALSA01 | String |  | ID da Balsa 1 |  |
| IDBALSA02 | String |  | ID da BAlsa 2 |  |
| IDBALSA03 | String |  | ID da Balsa 3 |  |
| IDNAVIO | String |  | Identificação do navio |  |
| IRINNAVIO | String |  | IRIN do navio |  |
| VLRAFRMM | Float |  | Valor AFRMM |  |
| VLRPRESTAFRMM | Float |  | Vlr. prest. AFRMM |  |
| NFEDEVRECUSA | String |  | NF-e de Devolução via Recusa | `N`=Não `S`=Sim |
| AGRUPFINNOTA | String |  | Agrupar financeiro | `S`=Sim `N`=Não |
| CODPARCDESCARGAMDFE | Integer |  | Parceiro Descarregamento (MDF-e) |  |
| TIMCONTRATOLTV | Integer |  | Contrato de Venda de Lote |  |
| TIMCONTRATOVENDA | Integer |  | Contrato de Venda de Imóvel |  |
| TIMNUNOTAMOD | Integer |  | Nota Modelo |  |
| TIMORIGEM | String |  | Origem | `PC`=Comissão Venda Lote `MF`=MFD `CP`=Comissão Cancelada |
| MODRECEBPDVWEB | String |  | Modo de recebimento PDV | `G`=Tipo de negociação `T`=Tipo de título |
| BH_METODO | String |  | Método de Envio Market Place |  |
| BH_STATUSPED | String |  | Status Pedido Market Place |  |
| BH_CODLOJA | Integer |  | Cód Loja Market Place |  |
| BH_CARRIER | String |  | Transportadora Market Place |  |
| BH_SKWJW | String |  | SankhyaW JivaW |  |
| BH_RASTREIO | String |  | Cód Rastreio Market Place |  |
| BH_SHIPPINGOPTIONID | String |  | Opção de Envio Market Place |  |
| BH_SHIPPINGID | String |  | Número envio Market Place |  |
| BH_CODMKT | String |  | Cód Remoto Market Place |  |
| BH_DTLIMEXP | Date |  | Data Limite Expedição Market Place |  |
| BH_VLRPED | Float |  | Valor Pedido Market Place |  |
| BH_LOJA | String |  | Loja de Conexão Market Place |  |
| BH_CUSTOFRETE | Float |  | Custo Frete Mkt Place |  |
| BH_ID | String |  | ID Remoto Market Place |  |
| BH_DTPEDAPROV | Date |  | Data Aprovação Pedido Market Place |  |
| BH_JUROS | Float |  | Juros Market Place |  |
| BH_DESCONTO | Float |  | Desconto Market Place |  |
| BH_MODOENVIO | String |  | Modo de Envio Market Place |  |
| CODCIDFIMCTE | Integer |  | Cód. Cid. Fim CT-e |  |
| CODCIDPREST | Integer |  | Cidade de Prestação do Serviço |  |
| TPAMBNFSE | String |  | Ambiente NFS-e | `2`=Homologação `1`=Produção |
| CODRASTREAMENTOECT | String |  | Cód. Rastreamento ECT |  |
| NULOTENFCOM | Integer |  | Lote NFCom |  |
| PERCDESCFOB | Float |  | Perc. desc. FOB |  |
| TERMACORDNOTA | String |  | Termo de Acordo  p/ CT-e na Nota |  |
| SEQCARGA | Integer |  | Sequência da carga |  |
| SERIENFDES | String |  | DES-BH Série NF |  |
| NATUREZAOPERDES | String |  | DES-BH Tipo de Negócio |  |
| MODELONFDES | String |  | DES-BH Modelo NF |  |
| STATUSNFE | String |  | Status NF-e | `I`=Enviada `R`=Aguardando Correção `null`=Não enviada `M`=Não é NF-e `T`=NF-e Terceiro_(+6)_ |
| ANTT | String |  | RNTRC |  |
| VLRICMSFCP | Float |  | Valor do ICMS Fundo de Pobreza |  |
| FUSOEMISSEPEC | String |  | Fuso Horário Emissão EPEC |  |
| CLASCONS | String |  | Cód. Classe de Cons. |  |
| CHAVENFEREF | String |  | Chave NF-e referenciada |  |
| CIOT | Integer |  | CIOT |  |
| TIMNUFINORIG | Integer |  | Financeiro Repasse |  |
| REGESPTRIBUT | String |  | DES-BH Regime Especial de Tributação |  |
| EXIGEISSQN | String |  | DES-BH Exigibilidade do ISSQN |  |
| SITESPECIALRESP | String |  | DES-BH Situação Especial de Responsabilidade |  |
| MOTNAORETERISSQN | String |  | DES-BH Motivo de não Retenção ISSQN |  |
| CODCIDORIGEM | Integer |  | Cód. Cidade de Origem |  |
| CODCIDDESTINO | Integer |  | Cód. Cidade de Destino |  |
| CLASSIFICMS | String |  | Cód. Classificação ICMS |  |
| NUODP | Integer |  | Ordem de Despacho |  |
| NUFOP | Integer |  | Finalidade da Operação |  |
| CODUFENTREGA | Integer |  | Cód. UF de Entrega |  |
| CODUFORIGEM | Integer |  | Cód. UF de Origem |  |
| CODCONTATOENTREGA | Integer |  | Contato de Entrega |  |
| CODUFDESTINO | Integer |  | Cód. UF de Destino |  |
| CODCIDENTREGA | Integer |  | Cód. Cidade de Entrega |  |
| ISSRETIDO | String |  | ISS Retido na fonte | `N`=Não `S`=Sim |
| DHTIPOPER | DateTime |  | Dt./Hr. Operação |  |
| PENDENTE | String |  | Pendente | `N`=Não `S`=Sim |
| TIPIPIEMB | String |  | Tipo do Valor Embalagem | `N`=Extra nota `I`=Incluso |
| CODFUNC | Integer |  | Funcionário |  |
| CODPARCCONSIGNATARIO | Integer |  | Consignatário (Expedidor) |  |
| DTMOV | Date |  | Dt. do Movimento |  |
| DTPREVENT | Date |  | Previsão de entrega |  |
| DHREGDPEC | DateTime |  | Dt. Reg. EPEC |  |
| INDPRESNFCE | String |  | Indicador de Presença para NF-e/NFC-e | `4`=4-NFC-e com entrega em domicílio `9`=9-Não presencial, outros `3`=3-Não presencial, teleatendimento `2`=2-Não presencial, internet `1`=1-Operação presencial_(+2)_ |
| CPFCNPJADQUIRENTE | String |  | CPF/CNPJ Adquirente |  |
| MODENTREGA | String |  | Mod. Entrega | `P`=Porta-a-Porta `F`=Multientrega Faturar Para `A`=Auto Distribuição `M`=Multientrega `N`=Entrega Direta_(+1)_ |
| PRODPRED | String |  | Produto Predominante |  |
| CHAVENFSE | String |  | Chave NFS-e |  |
| CODOBRA | String |  | Cód. da Obra |  |
| UFADQUIRENTE | String |  | UF do Adquirente | `SE`=Sergipe `SP`=São Paulo `SC`=Santa Catarina `RO`=Rondônia `RS`=Rio G. do Sul_(+22)_ |
| VIATRANSP | String |  | Tipo de Transporte | `12`=Handcarry `11`=Courier `10`=Entrada / Saída ficta `08`=Conduto / Rede Transmissão `07`=Rodoviária_(+8)_ |
| CNPJADQUIRENTE | String |  | CNPJ/CPF do Adquirente |  |
| TIPPROCIMP | String |  | Tipo Processo de Importação | `O`=Conta e Ordem `E`=Encomenda `C`=Compra e Venda |
| PRODUETLOC | String |  | Produção por Etapa e Local? | `N`=Não `S`=Sim |
| NUNOTASUB | Integer |  | Nro. Unico. Nota Substituída |  |
| VLRICMSDIFALDEST | Float |  | Valor DIFAL UF Destino |  |
| VLRICMSDIFALREM | Float |  | Valor DIFAL UF Remet. |  |
| NOTAEMPENHO | String |  | Nota de empenho |  |
| REBOQUE3 | Integer |  | Reboque 3 |  |
| SITUACAOCTE | String |  | Situação CT-e | `S`=Substituído `A`=Anulado `N`=Normal `B`=Em Substituição `L`=Em Anulação |
| LOTACAO | String |  | Lotação CT-e | `S`=Sim `N`=Não |
| TPEMISCTE | Integer |  | Tipo de emissão do CT-e | `1`=Normal `5`=Contingência FSDA `4`=EPEC pela SVC `8`=Autorização pela SVC-SP `7`=Autorização pela SVC-RS_(+1)_ |
| TPAMBCTE | String |  | Ambiente CT-e | `2`=Homologação `1`=Produção |
| NUMALEATORIOCTE | Integer |  | Nro. Aleat. CT-e |  |
| STATUSCTE | String |  | Status CT-e | `S`=Enviada EPEC `V`=Com erro de Validação `R`=Aguardando Correção `M`=Não é CT-e `E`=Aguardando Autoriz._(+5)_ |
| DTDECLARA | DateTime |  | Dt. Declaração CT-e de Anulação |  |
| REBOQUE1 | Integer |  | Reboque 1 |  |
| REBOQUE2 | Integer |  | Reboque 2 |  |
| NULOTECTE | Integer |  | Lote CT-e |  |
| NUMPROTOCCTE | String |  | Nro. Protocolo CT-e |  |
| NUMPROTOCINCTE | String |  | Nro. Protocolo Insucesso CT-e |  |
| DHPROTOCCTE | DateTime |  | Dh. Protocolo CT-e |  |
| NUMPROTOCINNFE | String |  | Nro. Protocolo Insucesso NF-e |  |
| DHEMISSEPEC | DateTime |  | Dt. Emissão Epec |  |
| CODART | String |  | Cód. Art |  |
| DTREMRET | DateTime |  | Data de Remessa/Retorno |  |
| PESOLIQUIMANUAL | String |  | Peso liquido Manual | `S`=Sim `N`=Não |
| VLRDESCTOTITEMMOE | Float |  | Desc.Total dos itens em Moeda |  |
| VLRTOTLIQITEMMOE | Float |  | Total Líq. Itens em Moeda |  |
| CTELOTACAO | String |  | Lotação | `N`=Não `S`=Sim |
| VLRICMSDIFERIDO | Float |  | Vlr. ICMS Diferido |  |
| PESOBRUTOMANUAL | String |  | Peso bruto manual | `N`=Não `S`=Sim |
| NFSEID | String |  | NFSe ID |  |
| IDIPROC | Integer |  | Nro. Ordem Produção |  |
| CHAVECTE | String |  | Chave CTe |  |
| CODVTP | Integer |  | Cód. Meio de Transporte |  |
| NUPCA | Integer |  | Núm. Planejamento de Compras |  |
| NOMEADQUIRENTE | String |  | Nome Adquirente |  |
| LOCEMBARQ | String |  | Local do Embarque |  |
| UFEMBARQ | String |  | UF Local Embarque | `SC`=Santa Catarina `TO`=Tocantins `SP`=São Paulo `SE`=Sergipe `RO`=Rondônia_(+22)_ |
| DTENTSAIINFO | Date |  | Data Extemporânea |  |
| M3 | Float |  | Metro Cúbico |  |
| INDCONSFINAL | String |  | Operação de Uso/Consumo Próprio | `N`=Não `S`=Sim |
| DTVAL | DateTime |  | Dt. da Validade |  |
| APROVADO | String |  | Aprovado | `N`=Não `S`=Sim |
| VLRICMSSEG | Float |  | Vlr. do ICMS do seguro |  |
| CODMAQ | Integer |  | Identifica impressora CF |  |
| CODEMPNEGOC | Integer |  | Empresa da negociação |  |
| CHAVENFE | String |  | Chave NF-e |  |
| CODCID | Integer |  | Cidade |  |
| CODMODDOCNOTA | Integer |  | Modelo do Documento Fiscal | `18`=18-Resumo Movimento Diário `17`=17-Despacho de Transporte `16`=16-Bilhete de Passagem Ferroviário `15`=15-Bilhete de Passagem e Nota de Bagagem `14`=14-Bilhete e Passagem Aquaviário_(+32)_ |
| CODMOTORISTA | Integer |  | Motorista |  |
| CODTPD | Integer |  | Cód. Tipo de Pedido |  |
| VLRLIQITEMNFE | String |  | VLRLIQITEMNFE |  |
| CODVENDTEC | Integer |  | Vendedor Técnico |  |
| DHTIPVENDA | DateTime |  | Dt./Hr. Tipo de negociação |  |
| LIBCONF | String |  | Liberado conferência |  |
| NUCONFATUAL | Integer |  | Nro Conferência atual |  |
| NUMPEDIDO2 | String |  | Número Pedido |  |
| PESOBRUTO | Float |  | Peso bruto |  |
| QTDVOL | Integer |  | Qtd. volumes |  |
| TPAMBNFE | String |  | Ambiente NF-e |  |
| VLRJURODIST | Float |  | Valor de juro distribuído |  |
| VLRSTEXTRANOTATOT | Float |  | Valor Total ST Extra Nota |  |
| RATEADO | String |  | Rateado | `S`=Sim `N`=Não |
| CIF_FOB | String |  | CIF / FOB | `C`=CIF - Contratação do Frete por conta do Remetente `T`=Terceiros `F`=FOB - Contratação do Frete por conta do Destinatário `S`=Sem Frete `R`=Transp. Próprio Remetente_(+1)_ |
| HRENTSAI | DateTime |  | Hr. Ent./Saída |  |
| TPFRETAMENTO | Integer |  | Tipo Fretamento | `1`=1 - Eventual `2`=2 - Contínuo |
| NUMERACAOVOLUMES | String |  | Numeração de Volumes |  |
| DHVIAGEM | DateTime |  | Data e hora da viagem |  |
| TPEMISNFE | Integer |  | Emissão NF-e | `3`=S.C.Amb.Nac. `1`=Sec. da Faz. `4`=EPEC `2`=Danfe de Segurança `7`=S.V.C.Rio Grande do Sul_(+2)_ |
| HRADIAM | Text |  | Hr. Adiamento |  |
| TIPOPTAGJNFE | Integer |  | Tipo Operação Veículos Novos | `2`=Faturamento direto `1`=Venda concessionária `3`=Venda direta `0`=Outros |
| MARCA | String |  | Marca |  |
| VLRINDENIZDIST | Float |  | Vlr. Indenização Distribuído |  |
| NUREM | Integer |  | Remessa |  |
| CODGRUPOTENSAO | String |  | Cód.Grupo de Tensão |  |
| TPLIGACAO | Integer |  | Cód.Tipo de Ligação |  |
| TPASSINANTE | Integer |  | Cód.Tipo de Assinante | `6`=Outros `5`=Semi-Público `4`=Público `3`=Residencial/Pessoa física `2`=Poder Público_(+1)_ |
| TROCO | Float |  | Troco |  |
| NROREDZ | Integer |  | Nro. Redução Z |  |
| VLRMOEDA | Float |  | Vlr. Moeda |  |
| DANFE | Integer |  | Nro. DANFE |  |
| DHPROTOC | DateTime |  | Dt. Protocolo NF-e |  |
| DTENVIOPMB | DateTime |  | Dt. de Envio à PMB |  |
| DTENVSUF | DateTime |  | Dt. de Envio Suframa |  |
| NULOTENFSE | Integer |  | Lote NFS-e |  |
| NUMNFSE | String |  | Nro. NFS-e |  |
| OCCN48 | Integer |  | Ordem de Carga CN48 |  |
| STATUSNFSE | String |  | Status NFS-e | `null`=Não é NFS-e `D`=Denegada `N`=Não enviada `L`=Lote Rejeitado `I`=Enviada_(+5)_ |
| TPEMISNFSE | Integer |  | Emissão NFS-e | `1`=Secretaria municipal da fazenda `2`=Recibo Provisório de Serviços |
| VLRINDENIZ | Float |  | Vlr. Indenização |  |
| ALIQIRF | Float |  | Alíquota IRF |  |
| BASECOFINS | Float |  | Base do COFINS |  |
| BASECOFINSST | Float |  | Base do COFINSST |  |
| BASEIRF | Float |  | Base do IRF |  |
| BASEPIS | Float |  | Base de PIS |  |
| BASEPISST | Float |  | Base do PISST |  |
| CODDOCA | Integer |  | Doca |  |
| CODEMPFUNC | Integer |  | Empresa do funcionário |  |
| CODUSUINC | Integer |  | Cód. Usuário Inclusão |  |
| DIGITAL | String |  | Digital |  |
| DTADIAM | DateTime |  | Adiamento |  |
| NROCAIXA | Integer |  | Nro. Caixa |  |
| NULOTENFE | Integer |  | Lote NF-e |  |
| NUMALEATORIO | Integer |  | Nro. Aleat. NF-e |  |
| NUMPROTOC | String |  | Nro. Protocolo NF-e |  |
| NUMREGDPEC | String |  | Nro. Reg. DPEC |  |
| NUNOTAPEDFRET | Integer |  | Nro. Único Ped. Frete |  |
| NURD8 | Integer |  | Nro. Único do RD8 |  |
| NUTRANSF | Integer |  | Nro. Transferência |  |
| TIPNOTAPMB | String |  | Tipo de Nota PMB |  |
| TOTDISPDESC | Float |  | Total Disponível p/ Desc. |  |
| VLRCOFINS | Float |  | Vlr. COFINS |  |
| VLRCOFINSST | Float |  | Vlr. COFINSST |  |
| VLRPIS | Float |  | Vlr. PIS |  |
| VLRPISST | Float |  | Vlr. PISST |  |
| VLRROYALT | Float |  | Vlr. ROYALT |  |
| CODSITE | Integer |  | Site |  |
| CODUSUCOMPRADOR | Integer |  | Cód. Usuário Comprador |  |
| PLACA | String |  | Placa |  |
| UFVEICULO | Integer |  | UF do veículo |  |
| LACRES | String |  | Lacres |  |
| CODCC | Integer |  | CODCC |  |
| NUPEDFRETE | Integer |  | Nro. Pedido Frete |  |
| FORMPGTCTE | String |  | Forma de Pagamento do CT-e | `1`=A pagar `0`=Pago `2`=Outros |
| VLRICMSFCPINT | Float |  | Valor do ICMS FCP Interno |  |
| VLRSTFCPINT | Float |  | Vlr. ST FCP Interno |  |
| VLRSTFCPINTANT | Float |  | Vlr. ST FCP Interno Anterior |  |
| CTEGLOBAL | String |  | CT-e Globalizado | `S`=Sim `N`=Não |
| VLRCARGAAVERB | Float |  | Valor da Carga Para Averbação |  |
| FISTEL | String |  | FISTEL (Nota Fiscal de Comunicação/Telecomunicação) |  |
| NUMCSTC | Integer |  | Nro. Característica Sv Tele/Comunicação |  |
| QTDUSU | Integer |  | Quantidade de usuário / login |  |
| NUMTERMTEL | String |  | Nro. Identificação do Terminal Telefônico |  |
| TIPCLIENTESERVCOM | Integer |  | Tipo Cliente de Serviços de Comunicação | `99`=99 - Outros não especificados anteriormente `8`=08 - Igrejas e Templos de qualquer natureza `7`=07 - Missões Diplomáticas, Repartições Consulares..., nos termos do Convênio ICMS 158/94 `6`=06 - Prestador de serviço de telecomunicação..., nos termos do Convênio ICMS 17/13 `5`=05 - Órgão da administração..., nos termos do Convênio ICMS 107/95_(+4)_ |
| MD5MODCOMTEL | String |  | MD5MODCOMTEL |  |
| PERMALTERCENTRAL | String |  | Permite Alteração na Central | `null`=Não se aplica `S`=Permite `N`=Não permite |
| DTREF | Date |  | Data de Referência |  |
| DTREF2 | Date |  | Data de Referência 2 |  |
| DTREF3 | Date |  | Data de Referência 3 |  |
| BH_FULLFIL | String |  | BH_FULLFIL |  |
| BH_FULFILLMENT | String |  | BH_FULFILLMENT |  |
| BH_IDANUNCIO | String |  | BH_IDANUNCIO |  |
| VLRREPREDTOTSEMDESC | Float |  | Vlr. redução total sem desconto |  |
| BH_ALIASVENDEDOR | String |  | BH_ALIASVENDEDOR |  |
| CODGUF | Integer |  | Código GNRE Unidade Federativa |  |
| LONGITUDE | String |  | Longitude |  |
| BH_EXTCODMKT | String |  | BH_EXTCODMKT |  |
| LATITUDE | String |  | Latitude |  |
| BH_ACCOUNT_NAME | String |  | BH_ACCOUNT_NAME |  |
| AD_COMBO | String |  | Explode Combo? | `S`=Sim `N`=Não |
| BASEICMSAT | Float |  | Base de ICMS AT |  |
| AD_IDENTREGA | String |  | Id Entrega Marketplace |  |
| VLRICMSAT | Float |  | Valor de ICMS AT |  |
| AD_METODO | String |  | Metodo |  |
| VLRFETHAB | Float |  | Vlr. FETHAB |  |
| AD_CUSTOFRETE | Float |  | Custo frete |  |
| VALORDESONPISCOFINS | Float |  | Valor PIS/COFINS Desonerados |  |
| VLRREPREDST | Float |  | Vlr. redução ST |  |
| QTDPRODDISTINTOS | Integer |  | Qtd. Prod. Distintos |  |
| AD_RASTREIO | String |  | Rastreio |  |
| AD_NUCONF | Integer |  | Nr. Conferencia |  |
| AD_USUARIOCONF | String |  | Usuario Conferencia |  |
| AD_DATACOLDESP | DateTime |  | Data Coleta Despacho |  |
| AD_DATAFECDESP | DateTime |  | Data Fechamento Despacho |  |
| AD_DATACONF | DateTime |  | Data Final Conferencia |  |
| AD_NUREMBKP | Integer |  | NUREMBKP |  |
| AD_QTDETIQUETAS | Integer |  | Tentativas envio Etiquetas |  |
| AD_ACEITAFIMSEMETIQ | String |  | Aceita Finalizar Conf s/ Etiqueta | `S`=Não Aceita `N`=Aceita |
| AD_DTSYNCFBITS | DateTime |  | DTSYNCFBITS |  |
| AD_SYNSHI | Integer |  | Status Fbits Retorno Status Enviado |  |
| AD_RASTREIOSHI | String |  | Cod. Rastreio Loja |  |
| AD_NUODP | Integer |  | Nro. único |  |
| AD_COLETA | String |  | Status Coleta |  |
| AD_PEDIDOWMW | Integer |  | Pedido WMW |  |
| AD_IDYAPAY | String |  | ID yapay / Protocolo |  |
| AD_CODMOTIVODEV | Integer |  | Motivo de Devolução |  |
| AD_LOJACORTEX | String |  | Loja Cortex |  |
| AD_IDPEDIDOCORTEX | String |  | ID Pedido Cortex |  |
| AD_STATUSNOTACORTEX | String |  | Status Envio de Nota Cortex | `S`=Sim `N`=Não |
| AD_IDMETODO | Integer |  | ID DO METODO DE ENVIO |  |
| AD_NUMEROAUTORIZACAO | String |  | numeroAutorizacao |  |
| AD_NUMEROCOMPROVANTEVENDA | String |  | numeroComprovanteVenda |  |
| AD_USU_CANCELOU | Integer |  | Usuário que realizou o Cancelamento |  |
| AD_VOLUMES | Integer |  | VOLUMES |  |
| AD_STATUSTRANSP | String |  | Status de Transporte |  |
| AD_NUNOTAORIGTROCSKU | Integer |  | Nota de Origem Troca SKU |  |
| NOTAPORPEDIDOPDV | String |  | Nota gerada por pedido | `S`=Sim `N`=Não |
| AD_SPLITPED | String |  | Split de Pedido |  |
| AD_PEDIDOMKTPLACE | String |  | Pedido Marketplace |  |
| AD_WAREHOUSEID | String |  | WAREHOUSEID |  |
| AD_BKPCODMKT | String |  | bkpcodmkt |  |
| AD_VLRFRETE | Float |  | Vlr Frete Cotação |  |
| AD_DATAENTREGACORRETA | DateTime |  | DATAENTREGACORRETA |  |
| AD_LINKZPL | String |  | Link do ZML  Etiqueta |  |
| AD_QTDTENTATIVAVIA | Integer |  | Qtd de Tentativas Integracao |  |
| AD_TRACKING_URL | String |  | URL Rastreio |  |
| AD_STATUSJADLOG | String |  | Status Jadlog |  |
| AD_REDESJADLOG | String |  | Redespacho Jadlog | `S`=Sim `N`=Não |
| AD_REGDELIVERY | String |  | Região Delivery |  |
| AD_PAGDELIVERY | String |  | Forma de Pagamento Delivery |  |
| AD_OBSDELIVERY | String |  | Observação Delivery |  |
| SUMVLRIIOUTNOTA | Integer |  | Tratar II em NF-e Nacionalização |  |
| NUNOTAREC | Integer |  | Numero da Nota Gerada para o Retorno |  |
| NURECEBIMENTO | Integer |  | Nro. Recebimento |  |
| RETGERWMS | String |  | Retorno Gerencial de Estoque |  |
| SOMICMSNFENAC | Integer |  | Tratar ICMS em NF-e Nacionalização |  |
| CARACAD | String |  | Característica adicional do transporte |  |
| CARACSER | String |  | Característica adicional do serviço |  |
| AD_PESOBRUTOTDB | Float |  | Peso Bruto tdb |  |
| CODAUTHVM | String |  | Cód. de Autorização Venda Mais |  |
| SOMPISCOFNFENAC | Integer |  | Tratar PIS/COFINS em NF-e Nacionalização |  |
| AD_PESOLIQTDB | Float |  | Peso Liq tdb |  |
| CHVNFEINEREF | String |  | Chave NFe Referenciada Inexistente |  |
| SOMDESPADUNFENAC | Integer |  | Somar despesas aduaneiras à NF-e de Nacionalização |  |
| AD_SITCLIENTE | String |  | Situação do Cliente |  |
| STATUSCFE | String |  | Status CF-e | `N`=Não enviada `I`=Enviada `E`=Erro de Validação `C`=Não é CF-e `A`=Aprovada |
| AD_TELEVENDASDOC | String |  | DOC |  |
| RETORNOEQUIPFISCAL | String |  | Retorno Equipamento Fiscal |  |
| AD_TELEVENDASPOS | String |  | POS |  |
| AD_TELEVENDASVENDEDOR | String |  | Vendedor - Televendas |  |
| AD_MELISHIPID | String |  | [Meli ShipID] |  |
| AD_TELEVENDASTID | String |  | TID |  |
| AD_TELEVENDASNSU | String |  | NSU |  |
| AD_TELEVENDASAUTORIZACAO | String |  | Autorização |  |
| AD_NUNOTAORIG | Integer |  | Nro Unico Origem |  |
| AD_CLIENTECATEGORIA | String |  | Categoria do Cliente | `CHURN`=Cliente Ação Churn `P`=Funcionário P2P `T`=Funcionário Tutora `A`=Cliente Amazon `C`=Cliente Externo_(+1)_ |
| AD_STATUSPEDIDOCOMPRA | String |  | Status do Pedido (Compras) |  |
| AD_PEDIDOKONCILI | String |  | Pedido Koncili |  |
| AD_PARCELASVIA | Integer |  | Parcelas Via Varejo |  |
| AD_DTCONFIRMACAONOTA | DateTime |  | Data de Confirmação NF |  |
| AD_DTCONFIRMACAONFPEDIDO | DateTime |  | Data da Confirmação da NF (Pedido) |  |
| AD_SITEMAILSPLIT | String |  | Situação Email Split |  |
| NUSESSAO | Integer |  | Número da Sessão do Aparelho Fiscal |  |
| AD_DTSTATUSINTELIP | DateTime |  | Dt Ultima Atualização Intelipost |  |
| AD_REENVIO_QTD | String |  | Quantidades de reenvio | `2`=Reenvio 2 `3`=Reenvio 3 `4`=Reenvio 4 `1`=Reenvio 1 |
| AD_RECALCULADO | String |  | Recalculado | `N`=Não `S`=Sim |
| AD_IDASSINATURA | String |  | ID da Assinatura Vtex |  |
| AD_STATUSFURO | String |  | Status Furo |  |
| AD_ENVIOMELIFULL | String |  | ID do Envio do Mercado Livre |  |
| AD_DTENVIOFULL | Date |  | Data de Envio Full |  |
| AD_RECEBIDOFULL | String |  | Recebido no MercadoLivre? | `N`=Não `S`=Sim |
| AD_STATUS_FULL_INT | String |  | Setor (Fluxo) | `C`=Compras `F`=Finalizado `V`=Vendas `L`=Logística |
| AD_PARCELASMAGALU | Integer |  | Parcelas Magazine Luiza |  |
| AD_PAGIFOOD | String |  | Pagamento Ifood |  |
| AD_DTREENENVIADO | Date |  | Data de Reenvio de status Enviado |  |
| AD_DATAATUALENVIADO | Date |  | Data para atualização manual do enviado |  |
| AD_VLRBRINDETOT | Float |  | Valor de Brinde Total |  |
| AD_QTDTOTALITENS | Integer |  | Quantidade total de itens |  |
| AD_PAGDELIVERYNOVO | String |  | Forma de Pagamento delivery | `2`=Entrega - Crédito `4`=Pago - Débito `1`=Entrega - Débito `5`=Pago - Crédito `3`=Entrega - PIX_(+1)_ |
| AD_DTINVOICEVTEX | DateTime |  | Dt envio forçado |  |
| AD_NRAUTORIZACAOZANTHUS | String |  | Nr de Autorização do Cartão Zanthus |  |
| AD_ADIMAX | String |  | é Venda adimax ? | `S`=Sim `N`=Nao |
| AD_NRPIXZANTHUS | String |  | Numero de autorizacao pix zanthus |  |
| CHAVECTEREF | String |  | Chave CT-e referenciada |  |
| STATUSVM | String |  | Status Venda Mais | `A`=Crédito aprovado `E`=Erro `N`=Não Enviada `D`=Devolução aprovada `F`=Falha no envio da devolução_(+1)_ |
| AD_NSUZANTHUS | String |  | Nr de NSU do Cartão Zanthus |  |
| HISTCONFIG | String |  | Gravar o histórico de configuração do parâmetro CONSIMPRETNOTA |  |
| AD_STATUSDEVOLUCAO | String |  | Status Devolucao |  |
| DTVALAUTVENDAMAIS | Date |  | Dt. Validade Crédito |  |
| STATUSAUTORIZACAOVM | String |  | Status Autorização Venda Mais | `A`=Autorizado `C`=Cancelado `E`=Expirado `U`=Utilizado |
| AD_ECOMMERCEZANTHUS | String |  | Codigo Ecommerce Zanthus |  |
| VLRREPTERC | Float |  | Vlr. Repasse a Terceiros (NFS-e) |  |
| AD_IDCAMPANHA | Integer |  | Id da Campanha |  |
| CHAVESINIEF1324 | String |  | Chaves de acesso AJUSTE SINIEF 13/24 |  |
| AD_OCORRENCIA | String |  | Retorno sefaz |  |
| AD_TIPOLINK | String |  | Tipo de Link | `TR`=Troca `PGE`=Pagamento pós estorno |
| AD_IDPIX | String |  | ID PIX |  |
| AD_NOMECID | String |  | Nome da Cidade Destino |  |
| TIPOGUIA | String |  | Tipo da Guia | `1`=1 - GTA - Guia de Trânsito Animal `2`=2 - TTA - Termo de Trânsito Animal `3`=3 - DTA - Documento de Transferência Animal `4`=4 - ATV - Autorização de Trânsito Vegetal `5`=5 - PTV - Permissão de Trânsito Vegetal_(+2)_ |
| AD_DATAFECHAMENTOOD | DateTime |  | Fechamento Ordem de Despacho |  |
| UFEMISS | Integer |  | UF de emissão |  |
| UFEMISSAO | String |  | UF de emissão |  |
| SERIEGUIA | String |  | Série da Guia |  |
| AD_DATA_BUFFERING | Date |  | Data de Expedição Meli |  |
| AD_MOTIVOMANUAL | String |  | Motivo conferência manual |  |
| NUMGUIA | Integer |  | Número da Guia |  |
| AD_DESCRUF | String |  | [UF Destino] |  |
| TPRETISS | String |  | Tipo de Retenção do ISS | `1`=Não Retido `2`=Retido pelo Tomador `3`=Retido pelo Intermediário |
| NUMPROTOCNFCOM | String |  | Nro. Protocolo NFCom |  |
| AD_STATUSSEP | String |  | Status Separação | `0`=A Separar `1`=Em Andamento `2`=Separado |
| SITUACAONFCOM | String |  | Situação NFCom | `B`=Em Substituição `N`=Normal `S`=Substituído |
| AD_OBSINTERNA | String |  | Observação |  |
| NFCOM | String |  | NFCom | `A`=Ajuste `C`=Complementar `D`=Devolução `M`=Convencional (Não Usa NFCom) `N`=Normal_(+2)_ |
| AD_TEMANEXO | String |  | Tem Anexo |  |
| CHAVENFCOM | String |  | Chave NFCom |  |
| AD_USUPEDCANCPLATAF | Integer |  | Usu. Alt. Ped. Pend. Can. Plataforma |  |
| STATUSNFCOM | String |  | Status NFCom | `A`=Aprovada `E`=Aguardando Autorização `I`=Enviada `M`=Não é NFCom `P`=Pendente de Retorno_(+4)_ |
| AD_FLAGPEDCANPLATF | String |  | Pedido Can. Plat | `N`=Não `S`=Sim |
| TPEMISNFCOM | Integer |  | Emissão NFCom | `1`=Sec. da Faz. `2`=Contingência Offline |
| AD_ATUALIZACAOMANUAL | String |  | Atualização Manual |  |
| TPAMBNFCOM | String |  | Ambiente NFCom | `1`=Produção `2`=Homologação |
| AD_STATUSDOOTAX | String |  | Status Dootax |  |
| AD_ID_MAGALU | String |  | [Id. Pedido MagaluV2] |  |
| VLRSERVICO | Float |  | Valor do Serviço |  |
| AD_ID_MGL_DELIVERY | String |  | [Id. Delivery MagluV2] |  |
| BCICMSRET | Float |  | Base de Cálculo da Retenção do ICMS |  |
| ALIQICMSRET | Float |  | Alíquota da Retenção |  |
| VLRICMSRET | Float |  | Valor do ICMS Retido |  |
| CODCFO | Integer |  | CFOP |  |
| CMUNFATGER | Integer |  | Código do Município do Fato Gerador |  |
| CHAVENFETERCEIROREF | String |  | Chave NF-e de Terceiro referenciada |  |
| LOCALFINALSERV | String |  | Finalização do Serviço | `1`=No País `2`=No Exterior |
| AD_COMISSAOML | Float |  | Comissão Mercado Livre |  |
| AD_VLRFRETECLI | Float |  | Valor Frete Cliente |  |
| AD_CUSTOLOG | Float |  | Custo Logístico |  |
| AD_TID | String |  | TID |  |
| TIMCODPROD | Integer |  | Serviço |  |
| TIMDESCPROD | String |  | Descrição (Serviço da Nota) |  |
| DESCTERMACORD | Float |  | Desc. ref. termo de acordo CT-e |  |
| DISDESAUTIMPEMB | String |  | Distribui desconto autom. com impostos embutidos? | `S`=Sim `N`=Não |
| CODCHECKOUT | Integer |  | Cód. Checkout |  |
| BH_DTENTREGA | Date |  | Data Prometida Market Place |  |
| BH_CODEMKT | String |  | Código Integração Market Place |  |
| BH_DTPEDIDO | Date |  | Data Pedido Market Place |  |
| CODINTERM | Integer |  | Intermediador da Transação |  |
| INTERMED | String |  | Indicador de Intermediador/Marketplace | `1`=1-Operação em site ou plataforma de terceiros (intermediadores/marketplace) `0`=0-Operação sem intermediador (em site ou plataforma própria) |
| CLIENTEIDPARCERIA | Float |  | Id do cliente no parceiro |  |
| IDDESCPARCERIA | Float |  | Id de desconto da parceria |  |
| IDPONTUACAOPARCERIA | Float |  | Id de pontuação no parceiro |  |
| VLRDESCPARCERIA | Float |  | Valor cupom desconto parceria |  |

## TGFCABLIG — Auto relacionamentos da TGFCAB
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTAORIG | Integer |  | Número da Nota de Origem |  |
| TIPO | String |  | Tipo |  |
| NUNOTA | Integer |  | Número único Nota |  |

## TGFCABVM — Cabecalho Nota Venda Mais
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODAUTORIZACAOVENDAMAIS | String |  | Código de Autorização Venda Mais |  |
| CODOPERACAOVENDAMAIS | String |  | Código de Operação Venda Mais |  |
| TIPMOV | String |  | Tipo de Movimento | `P`=P-Pedido de venda `V`=V-Venda |
| DHAPROVACAO | DateTime |  | Dt. Aprovação |  |
| DTVALIDADE | Date |  | Dt. Validade Crédito |  |
| ESTORNADO | String |  | ESTORNADO | `N`=Não `S`=Sim |
| NUNOTA | Integer |  | Número único Nota |  |

## TGFCAB_EXC — Cabeçalho da Nota Excluídas
Campos: 108

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARCTRANSPFINAL | Integer |  | Transportadora Final |  |
| NUMNOTA | Integer |  | Número da Nota |  |
| DTNEG | DateTime |  | Data de Negociação |  |
| VLRNOTA | Float |  | Valor da Nota |  |
| TIPMOV | String |  | Tipo do Movimento |  |
| NT_USERNAME | String |  | Nt_username |  |
| HOSTNAME | String |  | HostName |  |
| DHEXCLUSAO | DateTime |  | Data e Hora da Exclusão |  |
| CODPARC | Integer |  | Cód. Parceiro Nota |  |
| CODVEND | Integer |  | Vendedor |  |
| CODEMP | Integer |  | CODEMP |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| SERIENOTA | String |  | SERIENOTA |  |
| DTFATUR | DateTime |  | DTFATUR |  |
| DTENTSAI | DateTime |  | DTENTSAI |  |
| DTVAL | DateTime |  | DTVAL |  |
| DTMOV | DateTime |  | DTMOV |  |
| DTCONTAB | DateTime |  | DTCONTAB |  |
| HRMOV | Integer |  | HRMOV |  |
| CODEMPNEGOC | Integer |  | CODEMPNEGOC |  |
| CODCONTATO | Integer |  | CODCONTATO |  |
| RATEADO | String |  | RATEADO |  |
| CODVEICULO | Integer |  | CODVEICULO |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| DHTIPOPER | DateTime |  | DHTIPOPER |  |
| CODTIPVENDA | Integer |  | CODTIPVENDA |  |
| DHTIPVENDA | DateTime |  | DHTIPVENDA |  |
| NUMCOTACAO | Integer |  | NUMCOTACAO |  |
| COMISSAO | Float |  | COMISSAO |  |
| CODMOEDA | Integer |  | CODMOEDA |  |
| CODOBSPADRAO | Integer |  | CODOBSPADRAO |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| VLRSEG | Float |  | VLRSEG |  |
| VLRICMSSEG | Float |  | VLRICMSSEG |  |
| VLRDESTAQUE | Float |  | VLRDESTAQUE |  |
| VLRJURO | Float |  | VLRJURO |  |
| VLRVENDOR | Float |  | VLRVENDOR |  |
| VLROUTROS | Float |  | VLROUTROS |  |
| VLREMB | Float |  | VLREMB |  |
| VLRICMSEMB | Float |  | VLRICMSEMB |  |
| VLRDESCSERV | Float |  | VLRDESCSERV |  |
| IPIEMB | Float |  | IPIEMB |  |
| TIPIPIEMB | String |  | TIPIPIEMB |  |
| VLRDESCTOT | Float |  | VLRDESCTOT |  |
| VLRDESCTOTITEM | Float |  | VLRDESCTOTITEM |  |
| VLRFRETE | Float |  | VLRFRETE |  |
| ICMSFRETE | Float |  | ICMSFRETE |  |
| VLRFRETETOTAL | Float |  | Vlr. Frete Total |  |
| BASEICMSFRETE | Float |  | BASEICMSFRETE |  |
| TIPFRETE | String |  | TIPFRETE |  |
| CIF_FOB | String |  | CIF_FOB |  |
| VENCFRETE | DateTime |  | VENCFRETE |  |
| VENCIPI | DateTime |  | VENCIPI |  |
| ORDEMCARGA | Integer |  | ORDEMCARGA |  |
| SEQCARGA | Integer |  | SEQCARGA |  |
| KMVEICULO | Integer |  | KM |  |
| CODPARCTRANSP | Integer |  | Cód.Parceiro Transportadora |  |
| QTDVOL | Integer |  | QTDVOL |  |
| PENDENTE | String |  | PENDENTE |  |
| BASEICMS | Float |  | BASEICMS |  |
| VLRICMS | Float |  | VLRICMS |  |
| BASEIPI | Float |  | BASEIPI |  |
| VLRIPI | Float |  | VLRIPI |  |
| ISSRETIDO | String |  | ISSRETIDO |  |
| BASEISS | Float |  | BASEISS |  |
| VLRISS | Float |  | VLRISS |  |
| APROVADO | String |  | APROVADO |  |
| STATUSNOTA | String |  | STATUSNOTA |  |
| IRFRETIDO | String |  | IRFRETIDO |  |
| COMGER | Float |  | COMGER |  |
| VLRIRF | Float |  | VLRIRF |  |
| DTALTER | DateTime |  | DTALTER |  |
| VOLUME | String |  | VOLUME |  |
| CODPARCDEST | Integer |  | Cód. Parceiro Dest |  |
| VLRSUBST | Float |  | VLRSUBST |  |
| BASESUBSTIT | Float |  | BASESUBSTIT |  |
| CODPROJ | Integer |  | CODPROJ |  |
| NUMCONTRATO | Integer |  | NUMCONTRATO |  |
| BASEINSS | Float |  | BASEINSS |  |
| VLRINSS | Float |  | VLRINSS |  |
| VLRREPREDTOT | Float |  | VLRREPREDTOT |  |
| PERCDESC | Float |  | PERCDESC |  |
| CODPARCREMETENTE | Integer |  | Cód. Parceiro Remetente |  |
| CODPARCCONSIGNATARIO | Integer |  | Cód. Parceiro Consignatário |  |
| CODPARCREDESPACHO | Integer |  | Cód. Parceiro Credespacho |  |
| LOCALCOLETA | String |  | LOCALCOLETA |  |
| LOCALENTREGA | String |  | LOCALENTREGA |  |
| VLRMERCADORIA | Float |  | VLRMERCADORIA |  |
| PESO | Float |  | PESO |  |
| NOTASCF | String |  | NOTASCF |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NROREDZ | Integer |  | Número Redução Z |  |
| CODMAQ | Integer |  | Máquina |  |
| VLRICMSDIFALREM | Float |  | Valor DIFAL UF Remet. |  |
| VLRICMSDIFALDEST | Float |  | Valor DIFAL UF Destino |  |
| VLRICMSFCP | Float |  | Vlr. ICMS Fundo Comb. Pobreza |  |
| NUMNFSE | String |  | NUMNFSE |  |
| VLRSTFCPINT | Float |  | Vlr. ST FCP Interno |  |
| VLRSTFCPINTANT | Float |  | Vlr. ST FCP Interno Anterior |  |
| VLRICMSFCPINT | Float |  | Vlr. ICMS FCP Interno |  |
| FISTEL | String |  | FISTEL |  |
| NUMCSTC | Integer |  | Número da Característica de Serviço de Tele/Comunicação |  |
| QTDUSU | Integer |  | Quantidade de usuário / login |  |
| NUMTERMTEL | String |  | Número de Identificação do Terminal Telefônico |  |
| TIPCLIENTESERVCOM | Integer |  | Tipo Cliente de Serviços de Comunicação | `99`=99 - Outros não especificados anteriormente `8`=08 - Igrejas e Templos de qualquer natureza `7`=07 - Missões Diplomáticas, Repartições Consulares..., nos termos do Convênio ICMS 158/94 `6`=06 - Prestador de serviço de telecomunicação..., nos termos do Convênio ICMS 17/13 `5`=05 - Órgão da administração..., nos termos do Convênio ICMS 107/95_(+4)_ |
| MD5MODCOMTEL | String |  | MD5MODCOMTEL |  |
| NUNOTA | Integer |  | Número Único da Nota |  |

## TGFCON — Conferência de Pedidos
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência única de conferência de Pedido |  |
| CODBARRA | String |  | Código de Barras |  |
| QTD | Float |  | Quantidade do pedido |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHCONF | Date |  | Dt. Conferência |  |
| TIPOCONF | String |  | Tipo |  |
| NUCONF | Integer |  | Número único de conferência de Pedido |  |

## TGFCON2 — Cabecalho conferência
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTAORIG | Integer |  | Nro nota conferência |  |
| STATUS | String |  | Status |  |
| NUCONFORIG | Integer |  | Nro conferência origem |  |
| DHINICONF | DateTime |  | Data hora início |  |
| DHFINCONF | DateTime |  | Data hora final |  |
| CODUSUCONF | Integer |  | Cód. Conferente |  |
| QTDVOL | Integer |  | Qtd. volume da conferência |  |
| NUPEDCOMP | Integer |  | Núm. pedido complementar |  |
| NUNOTADEV | Integer |  | Núm. nota de devolução |  |
| AD_ACEITAFIMSEMETIQ | String |  | AD_ACEITAFIMSEMETIQ | `S`=Sim `N`=Não |
| AD_NURELETIQ | Integer |  | NURELETIQ |  |
| NUCONF | Integer |  | Nro conferência |  |

## TGFCONSER — Série Conferência
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| SEQCONF | Integer |  | Sequência |  |
| SERIE | String |  | Série |  |
| ATUALESTOQUE | Integer |  | Atualiza estoque |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data/Hora da alteração |  |
| SMARTCARD | String |  | SmartCard |  |
| SERIEFAB | String |  | Série do fabricante |  |
| AVARIADO | String |  | Avariado | `S`=Sim `N`=Não |
| NUCONF | Integer |  | Nro conferência |  |

## TGFCONT — Containers
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDCONTAINERS | String |  | ID Container |  |
| NUNOTA | Integer |  | Nº Nota |  |

## TGFCONTR — Contratante MDF-e
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQMDFE | Integer |  | Sequência do manifesto |  |
| CODPARCCONTR | Integer |  | Cód. Parceiro Contratante |  |
| NUVIAG | Integer |  | Nro. Viagem |  |

## TGFITE — Itens de Entrada e Saída de Produto
Campos: 245

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| OPERATUAL | String |  | Operação Atual da Produção |  |
| NROPROCESSO | String |  | Nro do Processo Judicial/Adm (ISS) |  |
| CODPROD | Integer |  | Produto |  |
| CODVOLPAD | String |  | Unidade padrão |  |
| COMPLDESC | String |  | Complemento |  |
| CODEMP | Integer |  | Cód.Empresa |  |
| NUNOTA | Integer |  | Nro único |  |
| SEQUENCIA | Integer |  | Sequência |  |
| REFFORN | String |  | Referência do Fornecedor |  |
| REFERENCIA | String |  | Referência do produto |  |
| ESTOQUE | Float |  | Estoque |  |
| QTDPENDENTE | Float |  | Qtd. pendente |  |
| CODNATREND | Integer |  | Código Natureza de Rendimento |  |
| QTDNEG | Float |  | Quantidade |  |
| QTDFORMULA | Float |  | Qtd. fórmula |  |
| QTDCONFERIDA | Float |  | Qtd. corte |  |
| VLRUNIT | Float |  | Vlr. unitário |  |
| VLRTOT | Float |  | Vlr. total |  |
| VLRTOTMOE | Float |  | Vlr. Tot. Moeda |  |
| PERCDESC | Float |  | % desconto |  |
| CODVOL | String |  | Unidade |  |
| CODVEND | Integer |  | Vendedor |  |
| CODLOCALORIG | Integer |  | Local origem |  |
| CODLOCALDEST | Integer |  | Local destino |  |
| CONTROLE | String |  | Controle |  |
| CONTROLEDEST | String |  | Controle destino |  |
| BASEICMS | Float |  | Base ICMS |  |
| ALIQICMS | Float |  | Alíq. ICMS |  |
| VLRICMS | Float |  | Vlr. ICMS |  |
| BASEIPI | Float |  | Base do IPI |  |
| ALIQIPI | Float |  | Alíq. IPI |  |
| VLRIPI | Float |  | Vlr. IPI |  |
| BASESUBSTIT | Float |  | Base substituição |  |
| VLRSUBST | Float |  | Vlr. substituição |  |
| CODTRIB | Integer |  | Tributação | `40`=40-Isenta `60`=60-ICMS cobrado anteriormente por substituição `50`=50-Suspensão `41`=41-Não tributada `30`=30-Isenta e não tribut.e c/cobrança por subst._(+10)_ |
| CODEXEC | Integer |  | Executante |  |
| ATUALESTOQUE | Integer |  | Atualiza estoque |  |
| DTVIGOR | Date |  | Última Dt. Vigor |  |
| VLRSUGERIDO | Float |  | Vlr. Sugerido |  |
| CODCFO | Integer |  | CFOP |  |
| CODOBSPADRAO | Integer |  | Obs Padrão |  |
| CUSTO | Float |  | Custo |  |
| FATURAR | String |  | Faturar | `N`=Não `S`=Sim |
| M3 | Float |  | Metro Cúbico |  |
| NUTAB | Integer |  | Tabela |  |
| OBSERVACAO | String |  | Observação |  |
| PENDENTE | String |  | Pendente | `N`=Não `S`=Sim |
| QTDENTREGUE | Float |  | Qtd. entregue |  |
| RESERVA | String |  | Reserva |  |
| STATUSNOTA | String |  | Status da Nota |  |
| PERCREDVLRIPI | Float |  | % Redução de Vlr. IPI |  |
| USOPROD | String |  | Uso do Produto | `4`=Demonstração `O`=Outros insumos `2`=Prod.Intermediário `E`=Embalagem `1`=Subproduto_(+11)_ |
| VLRCUS | Float |  | Vlr. custos |  |
| VLRDESC | Float |  | Vlr. desconto |  |
| VLRDESCMOE | Float |  | Vlr. Desc. Moeda |  |
| VLRDESCBONIF | Float |  | Bonificação |  |
| VLRREPRED | Float |  | Vlr. redução |  |
| VLRTOTLIQ | Float |  | Total líq. |  |
| VLRTOTLIQMOE | Float |  | Total líq. Moeda |  |
| VLRUNITLIQ | Float |  | Preço líq. |  |
| VLRUNITMOE | Float |  | Vlr. Unit. Moeda |  |
| VLRUNITLIQMOE | Float |  | Preço Líq. Moeda |  |
| ALIQICMSRED | Float |  | Alíq. ICMS Reduzida |  |
| CODPARCEXEC | Integer |  | Cód. Parceiro Exec |  |
| CODMOTDESONERAST | Integer |  | Cód. Mot. Desoneração do ICMS ST | `9`=Outros `3`=Uso na agropecuária `12`=Fomento agropecuário |
| BASESUBSTSEMRED | Float |  | Base ST S/Redução |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Dt. Alteração |  |
| SOLCOMPRA | String |  | Solic. compra | `N`=Não `S`=Sim |
| CODTRIBISS | Integer |  | Cód. trib. ISS |  |
| CODCFPS | Integer |  | Cód. CFPS |  |
| ALIQISS | Float |  | Alíq. ISS |  |
| ATUALESTTERC | String |  | Estoque terc. |  |
| TERCEIROS | String |  | Terceiros | `N`=Não `S`=Sim |
| PERCDESCBONIF | Float |  | % desc. bonif. |  |
| ENDIMAGEM | String |  | End. imagem |  |
| ALTURA | Float |  | Altura |  |
| LARGURA | Float |  | Largura |  |
| ESPESSURA | Float |  | Espessura |  |
| CODCAV | Integer |  | Cód. cavalete |  |
| CODPROC | Integer |  | Cód. processo |  |
| QTDPECA | Float |  | Qtd. peça |  |
| PRECOBASE | Float |  | Preço base |  |
| VLRACRESCDESC | Float |  | Vlr. acresc./desc. |  |
| VLRRETENCAO | Float |  | Vlr. retenção |  |
| CSTIPI | Integer |  | C.S.T IPI | `49`=49-Outras Entradas `-1`=(-1)-Não sujeita ao IPI `4`=04-Entrada Imune `3`=03-Entrada Não Tributada `55`=55-Saída c/Suspensão_(+10)_ |
| CODENQIPI | Integer |  | Cód. Enq. Legal IPI |  |
| PERCCOM | Float |  | % comissão |  |
| VLRCOM | Float |  | Vlr. comissão |  |
| ALTPRECO | String |  | Alt. Preço Igual | `M`=Atualiza maior `N`=Não Atualiza `B`=Atualiza menor |
| QTDFIXADA | Float |  | Qtd. fixada |  |
| PERCCOMGER | Float |  | % comiss. Gerente |  |
| VLRCOMGER | Float |  | Comiss. gerente |  |
| QTDWMS | Float |  | Qtd. WMS |  |
| BASICMMOD | Integer |  | Mod. Base ICMS |  |
| BASICMSTMOD | Integer |  | Mod. Base ICMS ST |  |
| CODPROMO | Integer |  | Cód. promoção |  |
| QTDFAT | Float |  | Qtd. faturada |  |
| VLRPROMO | Float |  | Vlr. Promoção |  |
| BASESTUFDEST | Float |  | Base ST UF Destino |  |
| QTDVOL | Integer |  | Base Cálc. Amostragem |  |
| VLRLIQPROM | Float |  | Vlr. liq. promoção |  |
| PERCPUREZA | Float |  | % Pureza |  |
| AD_MAXIMA_CODCOMBO | Integer |  | Cód. Combo Máxima |  |
| CODDOCARRECAD | Integer |  | Cód. Mod. Documento de arrecadação | `1`=GNRE `0`=Documento Estadual de Arrecadação |
| NUMDOCARRECAD | String |  | Número Documento de arrecadação |  |
| PERCDESCFORNECEDOR | Float |  | % Desconto Fornecedor |  |
| QTDTRIBEXPORT | Float |  | Qtd. tributação para exportação |  |
| ALIQSTFCPSTANT | Float |  | Alíquota da ST de oper. ant. |  |
| ORIGEMBUSCA | String |  | Origem da busca | `S`=Produto sugerido `G`=Busca Geral `A`=Produto alternativo |
| PRODUTOPESQUISADO | Integer |  | Produto pesquisado |  |
| ALIQSTEXTRANOTA | Float |  | Alíquota ST Extra Nota |  |
| BASESTEXTRANOTA | Float |  | Base ST Extra Nota |  |
| TIPOSEPARACAO | String |  | Tipo de separação | `S`=Separa na mesma empresa `N`=Não separa |
| TIPENTREGA | String |  | Tipo entrega | `C`=Retirar no caixa `B`=Retirar no estoque `E`=Encomenda |
| BH_TIPOANUNCIO | String |  | Tipo Anúncio Market Place |  |
| BH_IDANUNCIO | String |  | ID Venda Market Place |  |
| BH_ORIGINALPRICE | Float |  | Vlr Original Mkt Place |  |
| PERCGERMIN | Float |  | % Germinação |  |
| VLRICMSUFDEST | Float |  | Vlr. ICMS UF Destino |  |
| CODESPECST | Integer |  | Código Especificador ST |  |
| VLRSUBSTUNITORIG | Float |  | Vlr. ST unitário do pedido de origem |  |
| CODLOCALTERC | Integer |  | Local terceiros |  |
| GERAPRODUCAO | String |  | Necessidade de Produção | `S`=Sim `N`=Não |
| NUMEROOS | Integer |  | Número OS Gub. |  |
| NUFOP | Integer |  | Finalidade da Operação |  |
| PRECOBASEQTD | Float |  | Preço base qtd. |  |
| BASESTANT | Float |  | Base ST ant. |  |
| CODVOLPARC | String |  | Cód. Volume Parceiro |  |
| GRUPOTRANSG | Integer |  | Grupo transg. |  |
| IDALIQICMS | Integer |  | Cód. Alíq. ICMS |  |
| VLRUNITLOC | Float |  | Vlr. Unit. Locação |  |
| PRODUTONFE | String |  | Produto para NF-e |  |
| VLRICMSDIFERIDO | Float |  | Vlr. ICMS Diferido |  |
| VLRPTOPUREZA | Float |  | Vlr.Ponto Pureza |  |
| IDALIQICMSDIFICMS | Integer |  | Cód. Alíq. Dif. ICMS |  |
| GTINNFE | String |  | GTINNFE |  |
| GTINTRIBNFE | String |  | GTINTRIBNFE |  |
| STATUSLOTE | String |  | Status do Lote | `R`=Reprovado `Q`=Quarentena `N`=Nenhum `P`=Aprovado `A`=Aguardando Aprovação |
| NUPROMOCAO | Integer |  | Nro. Promoção |  |
| CODANTECIPST | String |  | Cód.Antecipação ST | `N`=N-(Não Usa) Operação não envolve ST `4`=4-Antecip. tribut. com MVA efetuada pelo destinatário encerrando a fase de tributação `3`=3-Antecip. tribut. com MVA efetuada pelo destinatário sem encerrar a fase de tributação `2`=2-Antecip. tribut. efetuada pelo destinatário apenas como complemento do diferencial de alíquota `1`=1-Pgto de ST efetuado pelo destinatário quando não efetuado ou efetuado a menor pelo substituto_(+3)_ |
| NUMCONTRATO | Integer |  | Contrato |  |
| DTINICIO | Date |  | Dt.Prev.Entrega |  |
| PERCDESCPROM | Float |  | % desc. promoção |  |
| VLRUNITDOLAR | Float |  | Vlr.Unitário em Dólar |  |
| BASEISS | Float |  | Base do ISS |  |
| VLRISS | Float |  | Vlr. ISS |  |
| VARIACAOFCP | Integer |  | Variação da Fórmula |  |
| VLRTROCA | Float |  | Vlr. Troca |  |
| VLRSTEXTRANOTA | Float |  | Valor ST Extra Nota |  |
| PERCDESCDIGITADO | Float |  | % desc. digitado |  |
| BASEICMSSTFRETE | Float |  | Base do ICMS/ST do Frete |  |
| PERCDESCTGFDES | Float |  | % desc. promoção |  |
| ICMSSTFRETE | Float |  | Vlr. ICMS/ST sobre o frete |  |
| VLRDESCDIGITADO | Float |  | Vlr. desc. digitado |  |
| NUMPEDIDO2 | String |  | Número Pedido |  |
| SEQPEDIDO2 | String |  | Seq. no Pedido |  |
| CODMOTDESONERAICMS | Integer |  | Cód.Mot.Desoneração ICMS | `3`=Produtor Agropecuário `5`=Diplomático/Consular `4`=Frotista/Locadora `2`=Deficiente Físico `1`=Táxi_(+6)_ |
| PERCDESCBASE | Float |  | Desc. p/ Preço Base |  |
| VLRSUBSTANT | Float |  | Vlr. do ICMS da  ST da oper. ant. |  |
| BASESUBSTITANT | Float |  | Base de Cálc. da ST de oper. ant. |  |
| VLRICMSANT | Float |  | Vlr ICMS destacado da oper. própria de oper. ant. |  |
| ORIGPROD | String |  | Origem do Produto | `3`=3-Nacional, mercadoria ou bem com conteúdo de importação superior a 40% e inferior ou igual a 70% `2`=2-Estrangeira, adquirida no mercado interno, exceto a indicada no código 7 `0`=0-Nacional, exceto as indicadas nos códigos 3, 4, 5 e 8 `1`=1-Estrangeira, importação direta, exceto a indicada no código 6 `8`=8-Nacional, mercadoria ou bem com Conteúdo de Importação superior a 70%_(+4)_ |
| CODTPA | Integer |  | Tipo Atendimento |  |
| CSOSN | Integer |  | Cód. situação op. Simples nacional (CSON) | `102`=102-Tributada pelo Simples Nacional sem permissão de crédito `101`=101-Tributada pelo Simples Nacional com permissão de crédito `500`=500-ICMS cobrado anteriormente por substituição tributária (substituído) ou por antecipação `400`=400-Não tributada pelo Simples Nacional `300`=300-Imune_(+5)_ |
| NRSERIERESERVA | String |  | Nro série |  |
| QTDUNIDPAD | Float |  | Qtd. unid. padrão |  |
| VLRUNIDPAD | Float |  | Vlr. unid. padrão |  |
| MARCA | String |  | Marca |  |
| NCM | String |  | NCM |  |
| CODIGONFCOM | String |  | Cod. Item NFCom |  |
| INDDEVOLUCAONFCOM | String |  | Indicador de devolução | `N`=Não `S`=Sim |
| PESOBRUTO | Float |  | Peso bruto |  |
| VITEM_IBSCBS | Float |  | Valor Total do Item da NF-e |  |
| PESOLIQ | Float |  | Peso líq. |  |
| INDTOT | String |  | Não compõe total NF-e | `N`=Não `S`=Sim |
| BASESUBSTITUNITORIG | Float |  | Base ST unitária do pedido de origem |  |
| SEQUENCIAFISCAL | Integer |  | Sequência Fiscal |  |
| CODAGREGACAO | String |  | Cód. de Agregação |  |
| INDESCALA | String |  | Indicador de Escala Relevante | `S`=Produzido em Escala Relevante `N`=Produzido em Escala NÃO Relevante `null`=Não se aplica |
| CNPJFABRICANTE | String |  | CNPJ do Fabricante da Mercadoria |  |
| CODBENEFNAUF | String |  | Cód. de Benefício Fiscal na UF |  |
| BASESTFCPINTANT | Float |  | Base ST FCP Interno Anterior |  |
| PERCSTFCPINTANT | Float |  | % ST FCP Interno Anterior |  |
| VLRSTFCPINTANT | Float |  | Vlr. ST FCP Interno Anterior |  |
| VLRTOTLIQREF | Float |  | Vlr. Tot.Líq. Desejado |  |
| VLRVENDAPROMO | Float |  | Vlr. Venda Promoção |  |
| VLRREPREDSEMDESC | Float |  | Vlr. redução sem desconto |  |
| AD_QTDBONIF | Integer |  | Qtd Bonificada |  |
| AD_VLRBONIF | Float |  | Valor Bonificado |  |
| AD_CODDEBARRAS | String |  | Código de Barras |  |
| BASECALCSTEXTRANOTA | Float |  | Base de Cálculo ST Extra Nota |  |
| REDBASEST | Float |  | Redução da Base ST |  |
| MARGLUCRO | Float |  | Margem de Lucro |  |
| IDALIQICMSAT | Integer |  | Cod. Aliq. ICMS AT |  |
| BASEICMSAT | Float |  | Base de ICMS AT |  |
| ALIQICMSAT | Float |  | Alíquota ICMS AT |  |
| ALIQINTERICMSAT | Float |  | Alíquota ICMS Interna AT |  |
| VLRICMSAT | Float |  | Valor de ICMS AT |  |
| ALIQFETHAB | Float |  | Alíquota FETHAB |  |
| VLRFETHAB | Float |  | Vlr. FETHAB |  |
| PERCUSAQUDECPE | Float |  | Percentual/Coeficiente sobre Custo Aquisição - PE |  |
| VLRCUSAQUDECPE | Float |  | Valor Custo Aquisição - PE |  |
| VLRREPREDST | Float |  | Vlr. redução ST |  |
| CODSIT08EFD | String |  | Considerar a situação do documento '08' nos EFDs | `S`=Sim `N`=Não |
| PERCUSAQUDECPEEST | Float |  | Percentual/Coeficiente sobre Custo Aquisição - PE - Origem Estrangeira |  |
| TIPUTILCOM | Integer |  | Tipo de Utilização | `6`=6 - Outros `5`=5 - Multimídia `4`=4 - Provimento de acesso à Internet `3`=3 - TV por Assinatura `2`=2 - Comunicação de dados_(+2)_ |
| AD_REFFORNEC | String |  | Referencia do Fornecedor |  |
| UNIDADE | String |  | Unidade do Parceiro |  |
| AD_BASEREDICMS | Float |  | Base Reduzida ICMS |  |
| CODFCI | String |  | Código da FCI |  |
| IDALIQISS | Integer |  | Código Alíquota ISS |  |
| AD_BKPCONTROLE | String |  | BKPCONTROLE |  |
| AD_PESOBRUTOTDB | Float |  | Peso Bruto TDB |  |
| CODIPI | Integer |  | Código do IPI |  |
| AD_PESOLIQTDB | Float |  | Peso liquido TDB |  |
| INDREPDES | String |  | Indicador Repasse Desoneração | `0`=Valor do ICMS desonerado não deduz do valor do item  / total da NF-e. `1`=Valor do ICMS desonerado deduz do valor do item / total da NF-e |
| AD_DOCAVTEX | String |  | Docas Vtex |  |
| VLRCREDPRES | Float |  | Valor do Crédito Presumido de ICMS no CT-e (vCred) |  |
| VLROUTROITEM | Float |  | Vlr. Outros |  |
| CODEND | Integer |  | Endereço WMS |  |
| AD_ESTIMATIVATRANSP | String |  | Estimativa da Transportadora |  |
| AD_FRETETRANSP | Float |  | Frete do produto pela transp |  |
| AD_NOMETRANSP | String |  | Nome da Transp do produto |  |
| AD_IDVTEX | Integer |  | ID do Sku na Vtex |  |
| AD_VLRLIQUNITVTEX | Float |  | Vlr Unit Vtex |  |
| AD_QTDEST | Integer |  | Historico de Estoque |  |
| AD_PERCVERBA | Float |  | Percentual Verba |  |
| AD_DTINIVERBA | Date |  | Data Inicio Verba |  |
| AD_DTFIMVERBA | Date |  | Data Fim Verba |  |
| AD_SEQORIGSPLIT | Integer |  | Sequencia Origem Split |  |
| AD_STATUSSEP | String |  | Status Separação | `0`=A Separar `1`=Separado |
| AD_NAOIMPACTACUSTOGER | String |  | Não Impacta Custo Gerencial | `S`=Sim `N`=Não |
| AD_COMISSAOMLITEM | Float |  | Comissão Mercado Livre Item |  |
| RESERVADO | Float |  | Qtd. Reservada |  |
| STATUSPROC | String |  | Situação Atual da Produção | `P2`=Planejado `S2`=Suspendendo `S`=Suspenso `C`=Cancelado `A`=Em Andamento_(+4)_ |
| ALIQFUNTTEL | Float |  | Alíquota FUNTTEL |  |
| ALIQFUST | Float |  | Alíquota FUST |  |
| BASEFUNTTEL | Float |  | Base FUNTTEL |  |
| BASEFUST | Float |  | Base FUST |  |
| VLRFUNTTEL | Float |  | Valor FUNTTEL |  |
| VLRFUST | Float |  | Valor FUST |  |
| CODBARRAPDV | String |  | Cód. de Barras |  |
| IDDESCPARCERIA | Float |  | Id de desconto da parceria |  |
| VLRDESCPARCERIA | Float |  | Valor cupom desconto parceria |  |

## TGFITE_EXC — Itens de Notas Excluídas
Campos: 69

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODEMP | Integer |  | CODEMP |  |
| CODPROD | Integer |  | Produto |  |
| CODLOCALORIG | Integer |  | Local de Origem |  |
| CONTROLE | String |  | Controle |  |
| USOPROD | String |  | USOPROD |  |
| CODCFO | Integer |  | CODCFO |  |
| QTDNEG | Float |  | Qtd. Negociada |  |
| QTDENTREGUE | Float |  | QTDENTREGUE |  |
| QTDCONFERIDA | Float |  | QTDCONFERIDA |  |
| VLRUNIT | Float |  | Vlr. Unitário |  |
| VLRTOT | Float |  | Vlr. Total |  |
| VLRCUS | Float |  | Vlr. Custo |  |
| BASEIPI | Float |  | BASEIPI |  |
| VLRIPI | Float |  | VLRIPI |  |
| BASEICMS | Float |  | BASEICMS |  |
| VLRICMS | Float |  | VLRICMS |  |
| VLRDESC | Float |  | VLRDESC |  |
| BASESUBSTIT | Float |  | BASESUBSTIT |  |
| VLRSUBST | Float |  | VLRSUBST |  |
| ALIQICMS | Float |  | ALIQICMS |  |
| ALIQIPI | Float |  | ALIQIPI |  |
| PENDENTE | String |  | PENDENTE |  |
| CODVOL | String |  | Volume |  |
| CODTRIB | Integer |  | CODTRIB |  |
| ATUALESTOQUE | Integer |  | ATUALESTOQUE |  |
| OBSERVACAO | String |  | OBSERVACAO |  |
| RESERVA | String |  | RESERVA |  |
| STATUSNOTA | String |  | STATUSNOTA |  |
| CODOBSPADRAO | Integer |  | CODOBSPADRAO |  |
| CODVEND | Integer |  | CODVEND |  |
| CODEXEC | Integer |  | CODEXEC |  |
| FATURAR | String |  | FATURAR |  |
| NT_USERNAME | String |  | NT_USERNAME |  |
| HOSTNAME | String |  | HOSTNAME |  |
| DHEXCLUSAO | DateTime |  | Dt. Exclusão |  |
| USUARIO | String |  | USUARIO |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| VLRREPRED | Float |  | VLRREPRED |  |
| VLRDESCBONIF | Float |  | VLRDESCBONIF |  |
| PERCDESC | Float |  | PERCDESC |  |
| PROGRAMA | String |  | PROGRAMA |  |
| CODCFPS | Integer |  | CODCFPS |  |
| PRODUTONFE | String |  | PRODUTONFE |  |
| GTINNFE | String |  | GTINNFE |  |
| GTINTRIBNFE | String |  | GTINTRIBNFE |  |
| CODESPECST | Integer |  | Código Especificador ST |  |
| CODAGREGACAO | String |  | Cód. de Agregação |  |
| INDESCALA | String |  | Indicador de Escala Relevante | `S`=Produzido em Escala Relevante `N`=Produzido em Escala NÃO Relevante `null`=Não se aplica |
| CNPJFABRICANTE | String |  | CNPJ do Fabricante da Mercadoria |  |
| CODBENEFNAUF | String |  | Cód. de Benefício Fiscal na UF |  |
| BASESTFCPINTANT | Float |  | Base ST FCP Interno Anterior |  |
| PERCSTFCPINTANT | Float |  | % ST FCP Interno Anterior |  |
| VLRSTFCPINTANT | Float |  | Vlr. ST FCP Interno Anterior |  |
| BASECALCSTEXTRANOTA | Float |  | Base de Cálculo ST Extra Nota |  |
| REDBASEST | Float |  | Redução da Base ST |  |
| MARGLUCRO | Float |  | Margem de Lucro |  |
| CODMOTDESONERAST | Integer |  | Cód. Mot. Desoneração do ICMS ST |  |
| QTDTRIBEXPORT | Float |  | Qtd. Tributação para Exportação |  |
| VLRREPREDSEMDESC | Float |  | VLRREPREDSEMDESC |  |
| ALIQSTFCPSTANT | Float |  | Alíquota ST/FCP ST Ant. |  |
| PERCUSAQUDECPE | Float |  | Percentual/Coeficiente sobre Custo Aquisição - PE |  |
| VLRCUSAQUDECPE | Float |  | Valor Custo Aquisição - PE |  |
| TIPUTILCOM | Integer |  | Tipo de Utilização | `6`=6 - Outros `5`=5 - Multimídia `4`=4 - Provimento de acesso à Internet `3`=3 - TV por Assinatura `2`=2 - Comunicação de dados_(+1)_ |
| CODFCI | String |  | Código da FCI |  |
| NUTAB | Integer |  | NUTAB |  |
| IDDESCPARCERIA | Float |  | Id de desconto da parceria |  |
| VLRDESCPARCERIA | Float |  | Valor cupom desconto parceria |  |

## TGFPAR — Parceiros
Campos: 279

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRROTA | String |  | Descrição da Rota |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| RAZAOSOCIAL | String |  | Razão social |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| TIPPESSOA | String |  | Tipo de pessoa | `J`=Jurídica `F`=Física |
| CLIENTE | String |  | Cliente | `S`=Sim `N`=Não |
| FORNECEDOR | String |  | Fornecedor | `S`=Sim `N`=Não |
| VENDEDOR | String |  | Vendedor | `S`=Sim `N`=Não |
| USUARIO | String |  | Usuário | `S`=Sim `N`=Não |
| TRANSPORTADORA | String |  | Transportadora | `S`=Sim `N`=Não |
| AGENCIA | String |  | Agência | `N`=Não `S`=Sim |
| CTAADIANT | String |  | Conta Adiantamento | `N`=Não `S`=Sim |
| MOTORISTA | String |  | Motorista | `N`=Não `S`=Sim |
| MEDICO | String |  | Médico | `N`=Não `S`=Sim |
| AGRONOMO | String |  | Agrônomo | `N`=Não `S`=Sim |
| CODPARCGRUECONOMICO | Integer |  | Cód. Grupo Econômico |  |
| CODPARCMATRIZ | Integer |  | Matriz |  |
| CODVEND | Integer |  | Vend. Preferencial |  |
| CODGRUPO | Integer |  | Grupo Cobrança |  |
| CODASSESSOR | Integer |  | Assessor do Parceiro |  |
| CODBCO | Integer |  | Banco |  |
| CODAGE | String |  | Agência bancária |  |
| NOMEAGE | String |  | Nome da agência |  |
| CODCTABCO | String |  | Conta bancária parceiro |  |
| AGRUPAR | String |  | Agrupar Pagamentos na geração p/Banco | `N`=Não `S`=Sim |
| CODCTABCOINT | Integer |  | Conta bancária empresa |  |
| CGC_CPF | String |  | CNPJ / CPF |  |
| CODTIPPARC | Integer |  | Perfil Principal |  |
| IDENTINSCESTAD | String |  | Insc. Estadual / Identidade |  |
| INSCESTADNAUF | String |  | Insc. Estadual na UF |  |
| TIMDATACI | Date |  | Dt. Cart. Identidade |  |
| CEI | String |  | Cad. Específico do INSS - CEI |  |
| TIMMAE | String |  | Mãe |  |
| DIASEM | Integer |  | Dia Visita | `null`=Indefinido `5`=Quinta `4`=Quarta `3`=Terça `1`=Domingo_(+3)_ |
| TIMPAI | String |  | Pai |  |
| SELECIONADO | String |  | Seleção | `P`=P `G`=G `R`=R |
| TIMPROFISSAO | Integer |  | Prof. / Ramo Atividade |  |
| INSCMUN | String |  | Cad.Mun.Contribuintes |  |
| TIMSENHASITE | String |  | Senha do Site |  |
| CODUNIMED | String |  | Cód. Unimed |  |
| TIMSENHADESC | String |  | Conf. Senha |  |
| CEP | String |  | CEP |  |
| TIMREFERENCIA01 | String |  | Referência 01 |  |
| CODEND | Integer |  | Endereço |  |
| TIMREFERENCIA02 | String |  | Referência 02 |  |
| NUMEND | String |  | Número |  |
| COMPLEMENTO | String |  | Complemento |  |
| CODBAI | Integer |  | Bairro |  |
| CODCID | Integer |  | Cód. Cidade |  |
| CODREG | Integer |  | Região |  |
| CAIXAPOSTAL | String |  | Caixa Postal |  |
| TELEFONE | String |  | Telefone |  |
| RAMAL | Integer |  | Ramal |  |
| ENVIPEDEMAILTOP | String |  | Envio email de pedido / nota | `M`=Manual `A`=Automático |
| FAX | String |  | Celular/Fax |  |
| EMAIL | String |  | Email |  |
| EVENDA | String |  | Email p/ pedido de venda | `P`=Parceiro `C`=Contato `N`=Não envia |
| ECOMPRA | String |  | Email p/ pedido de compra | `C`=Contato `P`=Parceiro `N`=Não envia |
| DTCAD | Date |  | Data cadastramento |  |
| CODUSU | Integer |  | Cód. Usuário Alteração |  |
| DTALTER | DateTime |  | Data alteração |  |
| DTNASC | Date |  | Data nascimento/Fundação |  |
| IMPLAUDOLOTE | String |  | Imprime laudo lote | `N`=Não `S`=Sim |
| SITUACAO | String |  | Situação | `E`=Excelente `O`=Ótimo `B`=Bom `R`=Regular `P`=Péssimo |
| TIMTELEFONE01 | String |  | Telefone 01 |  |
| DTULTCONTATO | DateTime |  | Dt. Último contato |  |
| TIMTELEFONE02 | String |  | Telefone 02 |  |
| PRAZOCONTATO | Integer |  | Prazo p/ contato |  |
| PRAZOPAG | Integer |  | Prazo médio pagamento |  |
| TOLERINADIMP | Integer |  | Tolerância p/ inadimplência |  |
| CODTAB | Integer |  | Tabela de Preço |  |
| GRUPOAUTOR | String |  | Grupo de autorização |  |
| LIMCRED | Float |  | Limite de crédito |  |
| LIMCREDMENSAL | Float |  | Limite crédito mensal |  |
| BLOQUEAR | String |  | Bloquear venda a prazo | `N`=Não `S`=Sim |
| MOTBLOQ | String |  | Motivo de Bloqueio |  |
| DESCBONIF | String |  | Desconto bonificado | `P`=Proibido `S`=Em separado `J`=Na Nota/Pedido `L`=Livre |
| DESCFIN | Float |  | % Desc. Financeiro |  |
| TIPOFATUR | String |  | Tipo de faturamento | `L`=Livre `S`=Semanal `Q`=Quinzenal `M`=Mensal |
| PERCCUSVAR | Float |  | % de Custo Variável |  |
| DIASVARPAGTO | Integer |  | Antecipação/Atraso recebimento(em dias) |  |
| CONTACESSO | String |  | Informações adicionais |  |
| QTDMAXTITVENCIDOS | Integer |  | Qtd. máx. de títulos vencidos |  |
| CLASSIFICMS | String |  | Classificação ICMS | `I`=Isento de ICMS `X`=Consumidor Final Contribuinte `P`=Produtor Rural `C`=Consumidor Final Não Contribuinte `T`=Usar a da TOP_(+1)_ |
| CSTIPIENT | Integer |  | Código Sit.Trib.IPI Entrada | `-1`=(-1)-Não sujeita ao IPI `49`=49-Outras Entradas `3`=03-Entrada Não Tributada `4`=04-Entrada Imune `0`=00-Entrada c/Recuperação de Crédito_(+3)_ |
| CSTIPISAI | Integer |  | Código Sit.Trib.IPI Saída | `99`=99-Outras Saídas `-1`=(-1)-Não sujeita ao IPI `53`=53-Saída Não Tributada `52`=52-Saída Isenta `50`=50-Saída Tributada_(+3)_ |
| CODENQIPIENT | Integer |  | Código Enq. Legal IPI Entrada |  |
| CODENQIPISAI | Integer |  | Código Enq. Legal IPI Saída |  |
| INDNATRET | String |  | Natureza da Retenção na Fonte | `01`=01 - Retenção por Órgãos, Autarquias e Fundações Federais `02`=02 - Retenção por outras Entidades Adm.Pública Federal `99`=99 - Outras Retenções `05`=05 - Retenção por Fabricante de Máquinas e Veículos `04`=04 - Recolhimento por Sociedade Cooperativa_(+1)_ |
| CODCTACTB | Integer |  | Conta contábil 1 |  |
| CODCTACTB2 | Integer |  | Conta contábil 2 |  |
| CODCTACTB3 | Integer |  | Conta contábil 3 |  |
| CODCTACTB4 | Integer |  | Conta contábil 4 |  |
| CODTABST | Integer |  | Tabela c/base p/S.T.na venda |  |
| MODELONFDES | String |  | Modelo da nota fiscal |  |
| SERIENFDES | String |  | Série da Nota Fiscal |  |
| NATUREZAOPERDES | String |  | Tipo de Negócio |  |
| IPIINCICMS | String |  | IPI incide no cálculo do ICMS | `N`=Não `S`=Sim |
| TEMIPI | String |  | Tem IPI | `N`=Não `S`=Sim |
| CALCINSS | String |  | Calcula FUNRURAL/INSS | `N`=Não `S`=Sim |
| PERCREDINSS | Float |  | % a ser subtraído da Alíquota do FUNRURAL/INSS |  |
| INDCOMERCIALIZACAO | String |  | Indicador de Comercialização | `7`=Com. da Produção com Isenção de Contrib. Prev., de acordo com a Lei n° 13.606/2018 `9E`=Comercialização da Produção no Mercado Externo `9`=Comercialização direta da Produção no Mercado Externo `8E`=Com. da Produção de PF/Seg. Especial a Entidade no PAA `8`=Com. da Produção para Entidade do Programa de Aquisição de Alimentos - PAA_(+3)_ |
| RETEMINSS | String |  | Calcula IRF | `N`=Não `S`=Sim |
| INDAQUISICAO | String |  | Indicador de Aquisição | `3`=3-Aquisição da produção de produtor rural pessoa jurídica por Entidade do PAA `2`=2-Aquisição da produção de produtor rural PF ou segurado especial em geral por Entidade do PAA `1`=1-Aquisição da produção de produtor rural pessoa física ou segurado especial em geral `7`=7-Aquisição de produção de produtor rural pessoa física ou segurado especial para fins de exportação `6`=6-Aquisição de produção de produtor rural pessoa jurídica por entidade do PAA - Produção isenta_(+2)_ |
| RETEMISS | String |  | Retém ISS | `N`=Não `S`=Sim |
| TARE | String |  | Tare | `N`=Não `S`=Sim |
| INTEGRAECONECT | String |  | Integração EConect | `N`=Não `S`=Sim |
| CALCFETHAB | String |  | Calcular FETHAB | `N`=Não `S`=Sim |
| INAPLICPRODEPE | String |  | Parceiro elegível à inaplicabilidade do PRODEPE? | `N`=Não `S`=Sim |
| DESCSTIVA | String |  | Considera desconto no cálculo de ST por IVA | `N`=Não `S`=Sim |
| SENHAECONECT | String |  | Senha |  |
| PRODUTORTEMNF | String |  | Produtor tem NF | `N`=Não `S`=Sim |
| PRAZOPARCECONECT | String |  | Prazos |  |
| CODEMP | Integer |  | Empresa |  |
| TIPGERBOLCENT | String |  | Geração de boleto nas centrais | `A`=Imprimir e Enviar e-mail `I`=Imprimir `E`=Enviar e-mail |
| TIPANEXONFE | String |  | Tipo do anexo | `Z`=Arquivo compactado (Extensão ZIP) `X`=Arquivo normal (Extensão XML) |
| AD_MAXIMA_MOTORISTA | String |  | Enviar motorista para Máxima | `S`=Sim `N`=Não |
| AD_MAXIMA_TRANSPORTADORA | String |  | Enviar transportadora para Máxima | `S`=Sim `N`=Não |
| AD_MAXIMA_FORNECEDOR | String |  | Enviar fornecedor para Máxima? | `S`=Sim `N`=Não |
| AD_MAXIMA_CLIENTE | String |  | Enviar cliente para Máxima? | `S`=Sim `N`=Não |
| AD_SERIENOTA | String |  | Serie Nota |  |
| TIMPROPRIETA | String |  | Proprietário | `S`=Sim `N`=Não |
| PARCSUBSTISS | String |  | Substituto Tributário - ISS | `S`=Sim `N`=Não |
| CODCONTATOPADCOT | Integer |  | Contato padrão para cotação |  |
| TRUNCPARCELA | String |  | Truncar valores no parcelamento | `S`=Sim `N`=Não |
| EXIGENOMEPARC | String |  | Usar razão social no Boleto Rápido | `S`=Sim `N`=Não |
| AD_CODTIPOPER | Integer |  | Top Pronta Entrega |  |
| VENDAMIN | Float |  | Venda Mínima |  |
| INTERVANALISCRED | Integer |  | Intervalo p/ análise de crédito |  |
| ARREDPRIMEIRAPARC | String |  | Ajusta arredondamento na 1ª parcela | `S`=Sim `N`=Não |
| NUFOP | Integer |  | Finalidade da Operação |  |
| ENQART227 | String |  | Enquadro no Art. 227. para cálculo de IPI? | `S`=Sim `N`=Não |
| ATUNUVERSAO | String |  | Atualizar versão |  |
| NUVERSAO | Integer |  | Versão |  |
| TIPLOTACAO | String |  | Tipo de Lotação | `9`=Contratante de trabalhadores avulsos não portuários por intermédio de Sindicato `8`=Operador Portuário tomador de serviços de trabalhadores avulsos `7`=PF tomadora de Serv prest por Cooperados por intermédio de Cooperativa de Trabalho `6`=Entidade beneficente/isenta Tom de Serv prest por cooperados por intermédio de cooperativa de trab `5`=PJ Tomadora Serv prest por cooperados intermédio cooperativa de trab, exceto ent beneficente/isenta_(+3)_ |
| DESCONSIDESCBASE | String |  | Desconsiderar desconto da nota/item na base de cálculo dos impostos ISS e IRF | `S`=Sim `N`=Não |
| TIMCARTREGIMEBENSV | String |  | Regime de Casamento | `STB`=Separação total de bens `PFA`=Participação final nos aquestos `OU`=Outros `CUB`=Comunhão universal de bens `CPB`=Comunhão parcial de bens |
| TIMCORRESPBANCARIO | String |  | Corr. Bancário | `S`=Sim `N`=Não |
| TIMFAIXASALARIAL | String |  | Faixa Salarial | `NI`=Não informado `AT10A20`=De 10 a 20 Salários Mínimos `AT05A10`=De 05 a 10 Salários Mínimos `AT02A03`=De 02 a 03 Salários Mínimos `AT01`=Até 01 Salário Mínimo_(+1)_ |
| AD_TROCABONIFICADA | String |  | Troca bonificada | `N`=Não `S`=Sim |
| BASEPRAZOECONECT | Integer |  | Partir de | `6`=Fora Mês `5`=Fora Quinzena `4`=Fora Dezena `3`=Fora Semana `2`=Próximo dia útil_(+2)_ |
| TRANSPPROPRIA | String |  | Transportadora própria | `S`=Sim `N`=Não |
| DTULTNEGOC | DateTime |  | Última negociação |  |
| PARCELAMECONECT | String |  | Parcelamentos |  |
| RETEMCOFINS | String |  | Retém COFINS | `N`=Não `S`=Sim |
| EMAILNOTIFENTREGA | String |  | E-mail p/ notificação de entrega |  |
| BASEPARCELECONECT | Integer |  | Partir de | `6`=Fora Mês `5`=Fora Quinzena `4`=Fora Dezena `3`=Fora Semana `2`=Próximo dia útil_(+2)_ |
| OBSERVACOES | String |  | Observações |  |
| VLRLIQITEMNFE | String |  | Considera valor líquido do item na NF-e (geração do XML e imp.Danfe) | `S`=Sim `N`=Não `E`=Conforme empresa |
| DIAFECHAECONECT | Integer |  | Dia Fechamento |  |
| RETEMCSL | String |  | Retém CSL | `N`=Não `S`=Sim |
| VLRLIQITEMNFCE | String |  | Considera valor líquido do item na NFC-e (geração do XML e imp.Danfe) | `S`=Sim `N`=Não `E`=Conforme empresa |
| DIAPAGTOECONECT | Integer |  | Dia Pagamento |  |
| RETEMPIS | String |  | Retém PIS | `N`=Não `S`=Sim |
| TIMCORRETOR | String |  | Corretor | `S`=Sim `N`=Não |
| PERFILECONECT | String |  | Perfil | `C`=Cliente sem limite `B`=Somente até limite `A`=Pode ultrapassar limite |
| TIMTIPOMORADIA | String |  | Tipo de Moradia | `SR`=Sem Resposta `PR`=Própria `OU`=Outros `NI`=Não Informada `FI`=Financiada_(+1)_ |
| TIPOSPARC | String |  | Tipo |  |
| TIMFIADOR | String |  | Fiador | `S`=Sim `N`=Não |
| MOTNAORETERISSQN | String |  | Motivo de não Retenção ISSQN |  |
| TIMQUERCOMPRAR | String |  | Quer Comprar | `S`=Sim `N`=Não |
| SITESPECIALRESP | String |  | Situação Especial de Responsabilidade |  |
| DTEMISNFEFORN | Date |  | Data de Inicio para Emissão de NFe |  |
| TIMCOMPRADOR | String |  | Comprador | `S`=Sim `N`=Não |
| CODANT | Integer |  | Código no SGE |  |
| TIMPROPVENDA | String |  | Prop. Venda | `S`=Sim `N`=Não |
| EMAILDANFE | String |  | Enviar DANFE por e-mail? | `S`=Sim `N`=Não |
| TIMINQUILINO | String |  | Inquilino | `S`=Sim `N`=Não |
| ENVIADANFEREDESPACHO | String |  | Enviar DANFE/XML por e-mail para Redespacho (Recebedor)? | `S`=Sim `N`=Não |
| HOMEPAGE | String |  | HomePage |  |
| TIMCARTORIO | Integer |  | Cartório |  |
| ALUNO | String |  | Aluno | `N`=Não `S`=Sim |
| TIMBAIRROCOMPRA | Integer |  | Bairro da Compra |  |
| PROFESSOR | String |  | Professor | `S`=Sim `N`=Não |
| TIMORGAO | String |  | Orgão |  |
| TERMACORD | String |  | Tem Termo de Acordo p/ CT-e? | `S`=Sim `N`=Não |
| EMAILNFE | String |  | E-mail p/ envio NF-e/NFS-e/CT-e |  |
| CONSIDTOTITENSTRIB | String |  | Considerar valor total dos itens mais valor total tributado para tags vTprest e vRec? | `N`=Não `S`=Sim |
| IDESTRANGEIRO | String |  | Identificação de Estrangeiro |  |
| TIMESTADOCIVIL | String |  | Estado Civil | `VI`=Viuvo(a) `UE`=União Estável `SO`=Solteiro(a) `SJ`=Sep. Judicialmente `OU`=Outros(as)_(+4)_ |
| CHAVEPIX | String |  | Chave Pix |  |
| SITCADSEFAZ | Integer |  | Situação Cadastral SEFAZ | `1`=Habilitado `0`=Não Habilitado |
| DHCADSEFAZ | DateTime |  | Data/Hora da Última Consulta SEFAZ |  |
| COMOCONHECEU | String |  | Como nos conheceu |  |
| TIMAINVESTIR | Float |  | Investimento |  |
| CODCRED | Integer |  | Crédito |  |
| TIMOUTTELS | String |  | Outras Informações de Contato |  |
| QTDMAXPEDCPA | Integer |  | Qtd máx itens por pedido |  |
| TIMNACIONALIDAD | Integer |  | Nacionalidade |  |
| CODROTA | Integer |  | Rota |  |
| SIMPLES | String |  | Optante pelo Simples Nacional? | `N`=Não `S`=Sim |
| SEXO | String |  | Sexo | `F`=Feminino `M`=Masculino |
| VALDESCGRDCAR | String |  | Validar Desc. Grande Carga? | `N`=Não `S`=Sim |
| FLEX | String |  | Usar Créd.Flex? | `N`=Não `S`=Sim |
| SALDODISP | Float |  | Saldo Disponível |  |
| RETSTVENDA | String |  | Retirar ST do preço de venda do item | `N`=Não `S`=Sim `A`=Sim e considerar despesas acessórias |
| CODEMPPREF | Integer |  | Empresa Preferencial |  |
| VLRMINPEDCPA | Float |  | Vlr mín por pedido |  |
| ENTREGAENDCONTATO | String |  | Utiliza endereço de entrega do contato | `N`=Não `S`=Sim |
| CODLOCALPADRAO | Integer |  | Local padrão para produtos |  |
| CPFPRODRURAL | String |  | CPF Prod. Rural |  |
| EXIGCONTATOENTCAB | String |  | Exigir Contato de Entrega no cabeçalho | `S`=Sim `N`=Não |
| TIPJURO | String |  | Tipo de juro | `C`=Composto `S`=Simples |
| USATABCRFORN | String |  | Usa Tabela p/ compra por CR? | `N`=Não `S`=Sim |
| PERCMULTA | Float |  | % de multa |  |
| PERCJURO | Float |  | % de juro (diário) |  |
| TIPOGERBOLETO | String |  | Tipo geração boleto | `E`=Enviar e-mail `I`=Imprimir `P`=Preparar |
| ALIQISSRETSIMPLES | Float |  | Alíquota ISS Ret/Simples |  |
| POTENCIALNEG | Float |  | Potencial de compra |  |
| LATITUDE | String |  | Latitude |  |
| IMPAGRUPFIN | String |  | Impedir agrupamento de boletos | `S`=Sim `N`=Não |
| LONGITUDE | String |  | Longitude |  |
| PERCDESCESPECIAL | Float |  | % Desc. Especial |  |
| MEIRJ | String |  | Micro empresário individual | `S`=Sim `N`=Não |
| SITCCF | String |  | Situação no CCF | `I`=Indefinida `B`=Restrição `A`=Regular |
| SITRECEITA | String |  | Situação na Receita Federal | `A`=Regular `I`=Indefinida `B`=Restrição |
| SITSINTEGRA | String |  | Situação no Sintegra | `B`=Restrição `I`=Indefinida `A`=Regular |
| STATUSEDZ | String |  | Status envio EDZ | `R`=Recebido `E`=Enviado `P`=Pendente |
| OPERLOGIST | String |  | Operador logístico | `N`=Não `S`=Sim |
| CODUSUCOBR | Integer |  | Cód. Usuário Cobrador |  |
| APLICLEITRANSP | String |  | Aplicar a lei da transparência | `N`=Não `S`=Sim |
| ESTABTRANSP | String |  | Estabelecimento para conversão de CFOP | `G`=Geradora/Distribuidora de Energia Elétrica `I`=Industrial `T`=Prestador de Serviço de Transporte `S`=Prestador de Serviço de Comunicação `N`=Não contribuinte_(+2)_ |
| SITCADRF | Integer |  | Situação Cadastral ReceitaWS | `1`=Habilitado `0`=Não Habilitado |
| DHCADRF | DateTime |  | Data/Hora da Última Consulta ReceitaWS |  |
| UNIDIMPORT | Integer |  | Unidade para considerar na importação | `2`=Unidade Tributável `1`=Unidade Comercial |
| ORGPUBLNFSE | String |  | Orgão público (NFS-e) | `S`=Sim `N`=Não |
| ASSOCIACAODESP | String |  | Associação Desportiva | `S`=Sim `N`=Não |
| MODELONOTACOMPRA | Integer |  | Modelo para Importação de XML Compra |  |
| PARCINTER | String |  | Parceiro com Interdependência | `S`=Sim `N`=Não |
| PROVACRESC | Float |  | Provisão acréscimo |  |
| EMAILNFSE | String |  | E-mail específico p/ envio NFS-e |  |
| EMAILCTE | String |  | E-mail específico p/ envio CT-e |  |
| CNAE | String |  | CNAE principal do contribuinte |  |
| INDCREDNFE | Integer |  | Contribuinte credenciado a emitir NF-e | `4`=A SEFAZ não fornece a informação `3`=Credenciado com obrigatoriedade parcial `2`=Credenciado com obrigatoriedade para todas operações `1`=Credenciado `0`=Não credenciado para emissão da NF-e |
| INDCREDCTE | Integer |  | Contribuinte credenciado a emitir CTe | `4`=A SEFAZ não fornece a informação `3`=Credenciado com obrigatoriedade parcial `2`=Credenciado com obrigatoriedade para todas operações `1`=Credenciado `0`=Não credenciado para emissão da CT-e |
| DTINIATIV | Date |  | Início da Atividade do Contribuinte |  |
| DTULTSIT | Date |  | Última mod. da situação cadastral |  |
| DTBAIXA | Date |  | Data da baixa do contribuinte |  |
| INDOPCCP | Integer |  | Tributação Contr.Previdenciária (Prod.Rural) | `2`=Sobre a folha de pagamento `1`=Sobre a comercialização da produção `0`=Não se aplica |
| REGAPUR | String |  | Regime de apuração |  |
| AD_METODOSDEENVIO | String |  | Metodos de Envio |  |
| CODIDENTCONS | String |  | Código de identificação do consumidor ou assinante |  |
| AD_METODO | Integer |  | ID Método de Envio(Intelipost) |  |
| UTILIZANUCADPARC | String |  | Utilizar código de identificação do consumidor ou assinante? | `S`=Sim `N`=Não |
| AD_DATAINISALDO | Date |  | Data inicial controle C/C Fornecedor |  |
| DESCONSDESCINSS | String |  | Desconsiderar desconto da nota/item na base de cálculo do INSS | `S`=Sim `N`=Não |
| TIPCLIENTESERVCOM | Integer |  | Tipo Cliente de Serviços de Comunicação | `99`=99 - Outros não especificados anteriormente `8`=08 - Igrejas e Templos de qualquer natureza `7`=07 - Missões Diplomáticas, Repartições Consulares..., nos termos do Convênio ICMS 158/94 `6`=06 - Prestador de serviço de telecomunicação..., nos termos do Convênio ICMS 17/13 `5`=05 - Órgão da administração..., nos termos do Convênio ICMS 107/95_(+4)_ |
| AD_VLRINISALDO | Float |  | Valor inicial saldo C/C Fornecedor |  |
| CONSPARCADRCST | String |  | Considerar parceiro no registro 1210 e 1220 da ADRC-ST (PR) | `S`=Sim `N`=Não |
| DEDUZIPIBCPISCF | String |  | Deduzir valor de IPI da BC do PIS e COFINS | `N`=Não `S`=Sim |
| AD_CODVEND2 | Integer |  | Cod. Vendedor Secundário |  |
| AD_CODRFV | String |  | Código RFV do Cliente |  |
| GRUPOPISCOFINS | Integer |  | Grupo PIS/COFINS |  |
| REGISTROANS | Integer |  | Registro ANS |  |
| REDE | String |  | Nome da Rede na operação com TEF |  |
| AD_NOMERFV | String |  | CLASSIFICADO COMO:  |  |
| AD_NUMBKP | String |  | NUMBKP |  |
| ORGAOPUB | String |  | Órgão Público | `N`=Não `S`=Sim |
| AD_LEADTIME | Integer |  | LEAD TIME DE ENTREGA |  |
| AD_INFLUENCIADOR | String |  | Parceiro Influenciador? | `S`=Sim `N`=Não |
| TPCOMPRAGOV | String |  | Tipo de Ente Governamental | `1`=União `2`=Estado `3`=DF `4`=Município |
| AD_NOMEARQZEBRA | String |  | NOMEARQZEBRA |  |
| TIPTRANSP | String |  | Tipo de Transportador | `1`=ETC `2`=TAC `3`=CTC |
| AD_NURELETIQ | Integer |  | NURELETIQ |  |
| AD_PROCESSADO | String |  | processado | `S`=Sim `N`=Não |
| AD_PERIODOANALISE | Integer |  | Período em dias para Análise de Giro |  |
| AD_NOMEPARC_BKP | String |  | BKP_NOMEPARC |  |
| AD_EMAIL_BKP | String |  | BKP_EMAIL |  |
| AD_TELEFONE_BPK | String |  | BKP_TELEFONE |  |
| AD_CLIENTEDETRATOR | String |  | Detrator | `N`=Não `S`=Sim |
| AD_TELEFONE_TRAY | String |  | Telefone Tray |  |
| AD_CELULAR_TRAY | String |  | Telefone Celular Tray |  |
| AD_IDMETODOCOTACAOREL | String |  | ID metodo Para relatorio |  |
| AD_CLIENTEASSINANTE | String |  | Cliente Assinante | `N`=Não `S`=Sim |
| AD_TIPOCHAVE | String |  | Tipo Chave PIX | `04`=Chave Aleatória `01`=Telefone `02`=E-mail `03`=CNPJ/CPF |
| AD_CHAVEPIXEDI | String |  | Chave PIX EDI |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| PROVACRESCCAC | Float |  | Provisão do carrinho |  |
| SALDODISPCAC | Float |  | Saldo disponivel do carrinho |  |

## TGFREG — Regras
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRREGRA | String |  | Descrição |  |
| INSTPRINC | String |  | Instância Principal |  |
| INSTSEC | String |  | Instância Secundária |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data da Alteração |  |
| TIPO | String |  | Permissão | `P`=Permitido `R`=Proibido |
| CODREGRA | Integer |  | Regra |  |

## TGFROT — Rota
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Cód. Usuário |  |
| DISTANCIA | Integer |  | Distância (Km) |  |
| DTALTER | DateTime |  | Data/Hora |  |
| CODROTA | Integer |  | Código da rota |  |
| DESCRROTA | String |  | Descrição |  |
| OBS | String |  | Observação |  |
| CODROTAANTERIOR | Integer |  | Cód. Rota Anterior |  |
| CODROTAPOSTERIOR | Integer |  | Cód. Rota Posterior |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |

## TGFROTCAT — Categorias Rota
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CATEGORIA | String |  | Categoria do veículo |  |
| VALOR | Float |  | Valor |  |
| OBSERVACAO | String |  | Observação |  |
| ATIVO | String |  | Ativo |  |
| CODROTA | Integer |  | Rota |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de Alteração |  |

## TGFSEG — Seguros de Transporte
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQSEG | Integer |  | Sequência do Responsável pelo Seguro |  |
| RESPSEG | String |  | Responsável pelo Seguro | `4`=Emitente do CT-e `3`=Destinatário `0`=Remetente `5`=Tomador de Serviço |
| NOMESEG | String |  | Nome da Seguradora |  |
| NUMAPO | String |  | Nro. Apólice |  |
| NUMAVE | String |  | Nro. Averbação |  |
| VLRCARGA | Float |  | Valor da Carga |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |

## TGFTOP — Tipos de Operação
Campos: 371

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NATEFDCONTM410M810 | Integer |  | Cód. Natureza (PIS/COFINS M410/M810) |  |
| DESCROPER | String |  | Descrição |  |
| TIPMOV | String |  | Tipo de movimento | `M`=M-Devolução de Transf. `K`=K-Pedido de Transferência `J`=J-Pedido de Requisição `T`=T-Transferência `V`=V-Venda_(+18)_ |
| ORCAMENTO | String |  | Orçamento | `N`=Não `S`=Sim |
| DHALTER | DateTime |  | Data e hora alteração |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| GRUPO | String |  | Grupo |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| ATUALFIN | Integer |  | Financeiro | `0`=Não atualizar `-1`=Despesas `1`=Receitas |
| TIPATUALFIN | String |  | Atualização do financeiro | `I`=Incluir `P`=Provisionar |
| ATUALEST | String |  | Atualização do Estoque | `N`=Nenhuma `B`=Baixar `E`=Entrar `R`=Reservar |
| ATUALESTMP | Integer |  | Atualiza estoque MP | `1`=Entrar `0`=Nenhuma `2`=Reservar `-1`=Baixar |
| ATUALBEM | String |  | Atualização do Bem | `C`=Compra `E`=Dev. Venda de Bens `N`=Não Atualizar `D`=Transf.Entrada/Retorno `1`=Dev. Compra de Bens_(+2)_ |
| ATUALCOM | String |  | Comissão | `P`=Calc.Vend.do Parc.na Confirmação `N`=Não calcular `L`=Calc.Vend.da Nota na Confirmação `C`=Calcular |
| PRECIFICA | String |  | Precifica | `A`=Atualiza custo pelo agendador `N`=Não atualiza custo nem preço de venda `S`=Atualiza custo e preço de venda `C`=Atualiza somente custo |
| MOVENDFLUTUANTE | String |  | Movimentação de Endereços Flutuantes? | `N`=Não `S`=Sim |
| ARMTIPAPU | String |  | Tipo de Movimento Armazenagem | `8`=Serviços Avulsos `7`=Armazenagem `6`=Expedição/Recepção `4`=Devoluções de Armazenagem `3`=Impurezas_(+10)_ |
| IGNORAMPPVPA | String |  | Ignora MP no preço de venda do PA | `S`=Sim `N`=Não |
| PENDENTE | String |  | A nota fica como pendente | `N`=Não `S`=Sim |
| ALTNFCONF | String |  | Permitir Alteração após confirmar | `S`=Sim `N`=Não |
| SALVARCONFSEMPERG | String |  | Salvar doc. confirmado sem perguntar | `N`=Não `S`=Sim |
| ATUALPRECOFAT | String |  | Recalcular preço prod. ao faturar | `N`=Não `S`=Sim |
| CUPOMFISCAL | String |  | TOP de Cupom Fiscal | `S`=Sim `N`=Não |
| BONIFICACAO | String |  | Bonificação | `N`=Não `S`=Sim |
| ADIARATUALEST | String |  | Atualizar Estoq.a partir da Confirmação | `N`=Não `S`=Sim |
| OPERACAOAMOSTRA | String |  | TOP de Amostra Grátis | `S`=Sim `N`=Não |
| RATAUTPROD | String |  | Ratear automaticamente por produto | `N`=Não `S`=Sim |
| OBTERVLRMOEDAFAT | String |  | Obter valor da moeda ao faturar | `S`=Sim `N`=Não |
| CODTIPOPERDESTINO | Integer |  | Cód.Tipo Operação Faturamento |  |
| CODTIPOPERSEPARACAO | Integer |  | Tipo Operação Separação |  |
| USOPRODSEPARACAO | String |  | Uso da Separação | `R`=Revenda `B`=Brinde `M`=Matéria Prima `I`=Imobilizado `F`=Brinde (NF)_(+5)_ |
| GOLDEV | Integer |  | Identificador de Devolução | `1`=Não `-1`=Sim |
| GOLSINAL | Integer |  | Tipo para análise | `-1`=Venda `0`=Nada `1`=Compra |
| GOLMPSINAL | Integer |  | Tipo para análise de MP | `0`=Nada `1`=Compra `-1`=Venda |
| USARPRECOCUSTO | String |  | Usar como Preço | `O`=Média das notas de origem `Q`=Valor Líquido da origem `S`=Último Custo de Entrada Sem ICMS `G`=Último Custo Médio Gerencial `D`=Preço em Moeda_(+8)_ |
| ATUALULTIMACOMP | String |  | Atualizar Última Compra | `E`=Dt.Entrada `M`=Dt.Movimento `G`=Dt.Negociação `N`=Não Atualizar |
| ATUALULTIMAVEND | String |  | Atualizar Última Venda | `G`=Dt.Negociação `F`=Dt.Faturamento `S`=Dt.Saída `N`=Não Atualizar |
| ANALISEGIRO | Integer |  | Análise de Giro | `-1`=Venda (Saída) `1`=Devolução de venda (Entrada) `0`=Desconsiderar |
| ATUALACDC | String |  | Atualizar Acréscimos/Decréscimos | `S`=Saldo Disponível `P`=Provisão de Acréscimo `N`=Não Atualizar |
| FATENTPROD | String |  | Na Entrada de Produtos | `S`=Abrir seleção de pedidos para faturar `A`=Faturar automaticamente `N`=Não faturar |
| INFCONTRATO | String |  | Informar Contrato na Nota | `S`=Obrigatório `O`=Opcional `N`=Proibido |
| VALIDAATRASO | String |  | Atraso | `N`=Não validar `A`=Validar e avisar `V`=Validar e bloquear |
| PRODREP | String |  | Aceitar Produto Repetido | `S`=Sim `N`=Não `null`=Usar o Parâmetro Global |
| OC | String |  | Tipo de Ordem de Carga | `A`=Ambos `S`=Saída `E`=Entrada `P`=Proibido |
| ATUALTRANSG | Integer |  | Saldo de Transgênico | `0`=Não atualizar `-1`=Subtrair `1`=Somar |
| EXIGECOTACAO | String |  | Exige Cotação | `C`=Exigir completo `N`=Não Exigir `S`=Exigir algum item |
| PODEPESAGEM | String |  | Tipo de Pesagem | `P`=Permite `S`=Exige `N`=Não pesa |
| EXIGETRANSP | String |  | Exige Transportadora | `S`=Sim `N`=Não |
| VENDITE | String |  | Exige vendedor nos itens | `S`=Sim `N`=Não |
| EXECITE | String |  | Exige executante nos itens | `N`=Não `S`=Sim |
| EXIGECONF | String |  | Exige conferência | `S`=Sim `N`=Não |
| VALIDAAGRUPMIN | String |  | Valida agrupamento mínimo | `S`=Valida e bloqueia `N`=Não valida `L`=Valida e exige liberação |
| EXIGELIB | String |  | Exigir Liberação antes da Confirmação | `S`=Sim `N`=Não |
| EXIGELAUDO | String |  | Exige Laudo de análise | `S`=Sim `N`=Não |
| LAUDOITEM | String |  | Laudo por item | `N`=Não `S`=Sim |
| VALIDAMEDIANEGOC | String |  | Validar Média de Negociações Mensais | `N`=Não `S`=Sim |
| VLRMINAP | Float |  | Valor mínimo p/Autorização de Pagamento |  |
| FATESTCONF | String |  | Fatura Produtos com Estoque na Confirmação | `N`=Não `S`=Sim |
| SOLCOMPRA | String |  | Gera Solicitação de Compra na Confirmação | `S`=Sim `N`=Não |
| EDITANALISERENTAB | String |  | Permite edição de análise de rentabilidade | `S`=Sim `N`=Não |
| EXIGEGAR | String |  | Exige garantia | `S`=Sim `N`=Não |
| EXIGEDTVAL | String |  | Exige data de validade | `N`=Não `S`=Sim |
| USARCONFCEGA | String |  | Usa conferência Cega | `N`=Não `S`=Sim |
| EXIGEPEDFRET | String |  | Exige Pedido de Frete p/Frete Extra Nota | `S`=Sim `N`=Não |
| PEDFRETE | String |  | Pedido de Frete | `S`=Sim `N`=Não |
| GERAGNRE | String |  | Gerar GNRE? | `N`=Não `S`=Sim |
| PODETRANSFENT | String |  | Pode Transformar Entradas | `N`=Não `S`=Sim |
| PODEFIXAR | String |  | Pode Fixar Preço | `N`=Não `S`=Sim |
| REFNFE | String |  | Buscar NF de origem p/ referenciar na NFe | `S`=Sim `N`=Não |
| MPNUMAUTLOTE | String |  | Numerar automaticamente MP por Lote | `N`=Não `S`=Matéria Prima `E`=Embalagem `A`=Ambos |
| EMPFUNCDIF | String |  | Permitir Req. Func. de outra Empresa | `N`=Não `S`=Sim |
| GERARTAGJNFE | String |  | Gerar tag na NFe para Negociação de Veículos Novos | `N`=Não `S`=Sim |
| EXIGANALITENS | String |  | Exigir liberação com análise dos itens antes da confirmação | `N`=Não `S`=Sim |
| ENVIARWMSCONF | String |  | Enviar automaticamente para o WMS na Confirmação | `N`=Não `S`=Sim |
| VALEST | String |  | Validar Estoque p/ Reservar | `S`=Sim `N`=Não |
| EXIGELIBSEMPRE | String |  | Sempre exigir Liberação | `N`=Não `S`=Sim |
| TEMFINORIGEM | String |  | Permite Atualização de Financeiro na TOP de Origem | `S`=Sim `N`=Não |
| AUTDIGITAL | String |  | Autorização por Digital | `N`=Não `S`=Sim |
| DIGINFIMPORTA | String |  | Digitar informações sobre Importação | `N`=Não `S`=Sim |
| CODCONTARURAL | String |  | Classificação da conta Produtor Rural | `999`=999 - Em trânsito `000`=000 - Caixa |
| NFESEMDTENTSAI | String |  | Imprimir NF-e sem Data de Entrada/Saída | `N`=Não `S`=Sim |
| CONTLAUDOSINT | String |  | Participa da contagem de laudos internos | `N`=Não `S`=Sim |
| AVISARCOMP | String |  | Avisar sobre componentes | `N`=Não `S`=Sim |
| CONFIMPOSTO | String |  | Exige Conferência de Impostos | `N`=Não `S`=Sim |
| CONFCFOP | String |  | Exige Conferência de CFOP | `N`=Não `S`=Sim |
| TOPPISCOFREDAQUIS | String |  | Calcula PIS/COFINS red. pela aquisição | `null`=Usa do parâmetro `S`=Usa da TOP `N`=Não calcula |
| CALCFUNTTELTOP | String |  | Calcular FUNTTEL? | `S`=Sim `P`=Usar do Cadastro de Produto `N`=Não |
| CALCFUSTTOP | String |  | Calcular FUST? | `S`=Sim `P`=Usar do Cadastro de Produto `N`=Não |
| NAOINCCONF | String |  | Nunca incluir Confirmada | `N`=Não `S`=Sim |
| PROVISENTREGA | String |  | Exige previsão de entregas | `N`=Não `S`=Sim |
| COPIARLIBER | String |  | Copiar liberações quando faturando individualmente | `N`=Não `S`=Sim |
| PESAITEM | String |  | Pesagem por item | `N`=Não `S`=Sim |
| DIGPUREZA | String |  | Digitar % Pureza e % Germinação | `N`=Não `S`=Sim |
| BLOQESTVENC | String |  | Bloqueia saída de estoque vencido | `N`=Não `S`=Sim |
| VALVCTLAUDOEST | String |  | Valida laudo vencido na baixa de estoque | `N`=Não `S`=Sim |
| GERABONPRE | String |  | Gera Bonificação/Premiação | `N`=Não `S`=Sim |
| FATCONTPORPESO | String |  | Faturar contrato por peso | `N`=Não `S`=Sim |
| TEMINDEX | String |  | Utiliza Indexação | `N`=Não `S`=Sim |
| CODTIPOPERREM | Integer |  | Tipo Operação Remessa |  |
| NUNOTAMODELO | Integer |  | Nro único modelo |  |
| GERARPARCDEST | String |  | Gerar se parc.destinatário preenchido | `N`=Não `S`=Sim |
| STATUSBAIXAEST | String |  | Status para Baixa no estoque | `P`=Aprovado `R`=Reprovado `N`=Nenhum `Q`=Quarentena `A`=Aguardando Aprovação |
| ATUALLIVFIS | String |  | Atualização de Livro ICMS | `A`=Ambos `N`=Não atualiza `E`=Livro de entrada `S`=Livro de saída |
| DENTROESTADO | String |  | Top trabalha com CFOP para | `F`=Fora do Estado `D`=Dentro do Estado `A`=Ambos |
| ATUALLIVISS | String |  | Atualização livros de ISS | `S`=Prestações `N`=Não Atualiza `E`=Aquisições |
| TIPIPI | String |  | Tipo de IPI | `3`=Sem créd/déb - Outras `2`=Sem créd/déb - Isentas `1`=Com créd/déb de imposto |
| TIPICMS | String |  | Tipo de ICMS | `5`=Com créd/déb - Outras `4`=Com créd/déb - Isentas `3`=Sem créd/déb - Outras `2`=Sem créd/déb - Isentas `1`=Com créd/déb de imposto |
| AD_MAXIMA_TIPOVENDA | Integer |  | Tipo de Venda Máxima | `24`=Bonificação (Pronta Entrega) `14`=Venda (Pronta Entrega) `13`=Estoque Veículo (Prontra Entrega) `11`=Troca (Pré-Venda) `7`=Venda Futura (Pré Venda)_(+3)_ |
| DATARETROFAT | String |  | Permitir Data Retroativa no Faturamento | `S`=Sim `N`=Não |
| DESCONSIDNFEORIGEM | String |  | Desconsidera Nfe de orig. referenciada? (Importação de XML) | `S`=Sim `N`=Não |
| PERMDESTVBATPREBCUS | String |  | Permite destinação de Verba do tipo de Rebaixa de Custo | `N`=Não `S`=Sim |
| CODCTACTBEFD | Integer |  | Conta Contábil para EFD |  |
| DESCQTDGRUDESCPRO | String |  | Aplica Desc. Promocional por Qtd/Grupo de Desc. Prod? | `S`=Sim `N`=Não |
| FORMRECISS | String |  | Forma de Recolhimento ISS | `07`=Fixo Mensal `06`=Devido a Outro Município `05`=Sem Recolhimento `04`=Fixo/Anual `01`=Retido na Fonte_(+2)_ |
| IGNORARAGRUPMINDEV | String |  | Ignorar agrupamento mínimo de compra | `S`=Sim `N`=Não |
| TIPMODALCTE | String |  | Modal CT-e | `3`=Aquaviário `2`=Aéreo `6`=Multimodal `1`=Rodoviário |
| EXIGEANALISECRED | String |  | Exige análise de crédito | `S`=Sim `N`=Não |
| RESERVASEMLOTE | String |  | Permitir reserva de estoque sem lote? | `S`=Sim `N`=Não |
| CALCPESOCONFIRM | String |  | Calcular Peso na Confirmação? | `S`=Sim `N`=Não |
| SIMULACAUTOFRETE | String |  | Simulação de frete automática | `S`=Sim `N`=Não |
| CODMODDOCISS | String |  | Modelo Documento ISS | `3B`=3B-Nota Fiscal de Serviços - Modelo Avulso `03`=03-Nota Fiscal de Serviços (modelo 3) `2D`=2D-Cupom Fiscal emitido por ECF `3A`=3A-Nota Fiscal de Serviços - Modelo Simplificado |
| CODCFPS | Integer |  | Código. CFPS |  |
| VALVARIACVLRUNIT | String |  | Validar variações do vlr. unit. orig./dest. | `S`=Sim `N`=Não |
| CODMODDOC | Integer |  | Modelo do Documento | `11`=11-Conhecimento de Transporte Ferroviário de Cargas `22`=22-Nota Fiscal de Serviço de Telecomunicações `14`=14-Bilhete e Passagem Aquaviário `57`=57-Conhecimento Transporte Rodoviário Eletrônico `55`=55-Nota Fiscal Eletrônica_(+32)_ |
| ACEITAFATACIMA | String |  | Aceitar faturar quantidade maior que a da origem? | `N`=Não `S`=Sim |
| CALCICMSREGTTS | String |  | Calcular ICMS Regime TTS E-Commerce Vinculado? | `N`=Não `S`=Sim |
| ENVGARANTIA | String |  | Envio em Garantia? | `S`=Sim `N`=Não |
| GERAR1400SPED | String |  | Gerar Registro 1400 no SPED Fiscal ? | `N`=Não `S`=Sim |
| USAALIQNATRATF100 | String |  | Usar Alíq.da Nat. do Rateio p/registro F100 do SPED PIS/COFINS ? | `N`=Não `S`=Sim |
| VALTOTNOTAGERLIV | String |  | Validar Totais da Nota na Geração do Livro? | `N`=Não `S`=Sim |
| CALCDIFALPART | String |  | Calcular DIFAL Partilhado | `S`=Sim `N`=Não |
| EXIGECONFIRMACAOMDE | String |  | Exigir confirmação do MD-e antes da confirmação | `N`=Não `S`=Sim |
| PRODUETLOC | String |  | Produção por Etapa e Local? | `S`=Sim `N`=Não |
| USATABALTEMP | String |  | Usar tabela de preço alternativa da empresa? | `N`=Não `S`=Sim |
| INDPRESNFCE | String |  | Indicador de Presença para NF-e/NFC-e/CF-e | `4`=4-NFC-e com entrega em domicílio `0`=0-Não se aplica `9`=9-Não presencial, outros `3`=3-Não presencial, teleatendimento `2`=2-Não presencial, internet_(+2)_ |
| GERAENDENTRNFE | String |  | Gerar endereço de entrega no XML da NF-e | `P`=Parceiro principal `N`=Nenhum `D`=Parceiro destinatário |
| CONFVALEVENT68 | Integer |  | Validar diferença para | `1`=Maior `0`=Ambos `2`=Menor |
| PERMFINMENORVLRNOTA | String |  | Permite financeiro menor que o valor total da nota | `S`=Sim `N`=Não |
| FATFORAPLANENT | String |  | Permitir faturamento fora do planejamento de entrega | `N`=Não `S`=Sim |
| PERCTOLVARVLRUNIT | Float |  | % Tolerância na variação do Vlr. unitário |  |
| VLRLIQITEMNFE | String |  | Considera valor líquido do item na NF-e ou NFC-e ou CF-e(geração do XML e imp.Danfe) | `S`=Sim `N`=Não `E`=Conforme empresa |
| DESCONSIDPEDXML | String |  | Desconsiderar pedido na geração do XML? | `S`=Sim `N`=Não |
| CODCFO_SAIDA_FORA | Integer |  | Saída |  |
| CTE | String |  | CT-e | `N`=Normal `M`=Convencional (Não usa CT-e) `E`=Import. Doc. (Emissão Própria) `T`=Terceiros |
| TIPSERVCTE | Integer |  | Tipo de serviço CT-e | `7`=Transporte de Valores `3`=Redespacho Intermediário `2`=Redespacho `1`=Subcontratação `0`=Normal_(+2)_ |
| CODTOPDENEGCTE | Integer |  | Tipo Operação CT-e Denegado |  |
| TIPOCTE | String |  | Tipo de emissão CT-e | `A`=4 - CTe de Anulação `S`=3 - CTe de Substituição `C`=1 - CTe de Complemento de Valores `N`=0 - CTe Normal `P`=5 - CT-e Simplificado_(+1)_ |
| CODMOEDAVP | Integer |  | Cód. Moeda Ajusta Valor Presente |  |
| AJUSTAVP | String |  | Ajusta Valor Presente | `F`=Fim do Período `A`=Anual `M`=Mensal `V`=Vencimento `N`=Não Ajusta |
| TIPALTDTVENC | String |  | Tipo de Alteração da Data de Vencimento | `M`=Manter `R`=Recalcular `P`=Perguntar |
| GERAAMOSTRALAUDO | String |  | Gerar amostras para laudo | `N`=Não `S`=Sim |
| TOPBACKORDER | Integer |  | Top Back Order |  |
| TOPATENDIMENTO | Integer |  | Top de Atendimento |  |
| VALSITCADSEFAZ | String |  | Valida situação cadastro na SEFAZ ? | `N`=Não `S`=Sim |
| CAT1799SPCCO | Integer |  | Cód.Complem.Oper. (CAT-17/99) | `4`=04 - Complemento de saída para consumidor final, amparada por isenção ou não incidência `6`=06 - Complemento de saída sujeita a ST, para comercialização subsequente `5`=05 - Comp. saída suj. a ST, p. com. subsequente ou transferência, amparada p. isenção/não incidência `0`=00 - Operação Normal `8`=08 - Fato gerador não realizado_(+5)_ |
| ENVWMSCONFIRMADA | String |  | Permite confirmação antes do envio para o WMS? | `N`=Não `P`=Parâmetro global `S`=Sim |
| PERMCONFPARCIALWMS | String |  | Permite conferência parcial no WMS? | `S`=Sim `N`=Não |
| ARMAZENAGEM | String |  | Armazenagem |  |
| CALCICMS | String |  | Cálculo de ICMS, IPI, ISS, IBS, CBS e IS | `G`=Calcula na confirmação `D`=Calcula e digita `C`=Calcula e não digita `B`=Não calcula e digita `A`=Não calcula e não digita |
| CODCFO_ENTRADA_FORA | Integer |  | Entrada |  |
| REDICMSBCPISCONFINS | String |  | Deduzir valor do ICMS na BC do PIS e COFINS? | `S`=Sim `N`=Não |
| CODCFO_ENTRADA | Integer |  | Entrada |  |
| CODCFO_SAIDA | Integer |  | Saída |  |
| TEMCSL | String |  | Tem CSLL | `N`=Não `S`=Sim |
| ATUALESTTERC | String |  | Estoque com/de Terceiros | `N`=Não controla `T`=Somar ao Estoque de terceiros em poder da empresa `R`=Subtrair do estoque próprio em poder de terceiros `D`=Subtrair do Estoque de terceiros em poder da empresa `P`=Somar ao estoque próprio em poder de terceiros |
| ESTOQUEMPTERCEIRO | String |  | Estoque MP de Terceiros | `T`=Somar ao estoque de terceiros em poder da empresa `N`=Não controla `D`=Subtrair do estoque de terceiros em poder da empresa |
| ATUALINDENIZ | Integer |  | Saldo de Indenização | `-1`=Subtrair `0`=Não Atualizar `1`=Somar |
| CODMODRPS | Integer |  | Mod. Imp. RPS |  |
| CODMODNFSE | Integer |  | Mod. Imp. NFS-e |  |
| NFSEPORNAT | String |  | NFS-e por natureza | `N`=Não `S`=Sim |
| TEMII | String |  | Tem II | `N`=Não `S`=Sim |
| TEMVAVTCON | String |  | Tem VA e/ou VT no contrato | `N`=Não `S`=Sim |
| PODEAJUSTARORIGPRODWMS | String |  | Permite Ajustar Nota Origem quando ligada a Produção | `N`=Não `S`=Sim |
| TRANSFWMS | String |  | Transferência no WMS | `O`=Considerar Origem `D`=Considerar Destino |
| VALTBCOMPCR | String |  | Validar Tabela de compra por CR? | `N`=Não `S`=Sim |
| STATUSLOTE | String |  | Exige Status para o Lote na Compra | `N`=Não `S`=Sim |
| TEMREAICMS | String |  | Tem Convênio REA/ICMS | `N`=Não `S`=Sim |
| NATOPERSPED | String |  | Natureza da Operação (SPED) |  |
| GERAPLANPROD | String |  | Gerar plano de produção | `N`=Não `S`=Sim |
| INTEGRAEVENTO | String |  | Integra evento | `S`=Sim `N`=Não |
| SEPBALCAO | String |  | Separação em Balcão | `S`=Sim `N`=Não |
| TRANSFCBGLOBAL | String |  | Número de Série Global - Transferência | `S`=Sim `N`=Não |
| AGRUPASERVFAT | String |  | Agrupa serviços faturamento | `S`=Sim `N`=Não |
| MARCARNAOPENDENTE | String |  | Deixar pedido como NÃO pendente quando faturar com corte | `S`=Sim `N`=Não |
| DESTOPADRCST1400 | String |  | Desconsiderar TOP na geração da ADRC-ST no R1400? | `S`=Sim `N`=Não |
| NUCCO | Integer |  | Configuração p/ conferência |  |
| SUGERELOCALPARC | String |  | Sugerir local padrão do parceiro? | `S`=Sim `N`=Não |
| CODLOCALIMPXML | Integer |  | Local padrão para importar XML |  |
| USACUSMEDBASEST | String |  | Usa Cus. Méd. Base ST? | `N`=Não `S`=Sim |
| ALTITEMPARCFAT | String |  | Permite alterar itens após faturar parcialmente | `S`=Sim `N`=Não |
| GRAHISALTPED | String |  | Gravar histórico de alterações do pedido | `S`=Sim `N`=Não |
| AGRUPAPRODNFE | String |  | Agrupar produtos semelhantes na NF-e? | `N`=Não `S`=Sim |
| NFE | String |  | NF-e | `T`=Terceiros `C`=Complementar `M`=Convencional (Não Usa NF-e) `A`=Ajuste `N`=Normal_(+4)_ |
| NFCOM | String |  | NFCom | `M`=Convencional (Não Usa NFCom) `N`=Normal `T`=Terceiros |
| TPNFDEB | String |  | Tipo de Nota Fiscal de Débito | `01`=Transferência de créditos para Cooperativas `02`=Anulação de Crédito por Saídas Imunes/Isentas `03`=Débitos de notas fiscais não processadas na apuração `04`=Multa e juros `05`=Transferência de crédito de sucessão_(+3)_ |
| TPNFCRED | String |  | Tipo de Nota Fiscal de Crédito | `01`=Multa e juros `02`=Apropriação de crédito presumido de IBS sobre o saldo devedor na ZFM (art. 450, § 1°, LC 214/25) `04`=Redução de valores `05`=Transferência de crédito na sucessão `03`=Retorno |
| TIPOIMPKIT | String |  | Kit/Componentes - Impressão e Livro Fiscal | `C`=Componentes `K`=Kit `T`=Kit e Componentes |
| TPOPERGOV | String |  | Tipo de operação com o ente governamental | `1`=1 - Fornecimento `2`=2 - Recebimento do pagamento, conforme fato gerador do IBS/CBS definido no Art. 10 § 2º |
| CODNATOPERISS | String |  | Cód. Natureza Oper. ISS (NFS-e) | `1`=1 - Tributação no Município `2`=2 - Tributação fora do Município `6`=6 - Exigibilidade suspensa por procedimento administrativo `5`=5 - Exigibilidade suspensa por decisão judicial `4`=4 - Imune/Exportação_(+32)_ |
| CODINDOPER | String |  | Código Indicador de Operação de Fornecimento |  |
| CODREMEDI | Integer |  | Modelo p/geração de EDI na confirmação |  |
| CODTIPOPERDENEG | Integer |  | Tipo Operação NF-e Denegada |  |
| COPIADTPREVORIG | String |  | Copiar prev. entrega da origem | `N`=Não `S`=Sim |
| NUMPROCESSO | String |  | Número do processo |  |
| INDCONSFINAL | String |  | Operação de Uso/Consumo Próprio | `N`=Não `S`=Sim |
| CODTIPOPERPENRET | Integer |  | Tipo Operação NF-e Pendente de Retorno |  |
| TIPMOVBEMSPED | String |  | Tipo de Mov. do  Bem (SPED) | `PE`=PE-Perecimento, Extravio ou Deterioração `OT`=OT-Outras Saídas do Imobilizado `AT`=AT-Alienação ou Transferência `MC`=MC-Imobilização oriunda de Ativo Circulante |
| CODCFO_TERC | Integer |  | CFOP p/Produtos de Terceiros |  |
| CODCFO_COMBUST_LUBRIF | Integer |  | CFOP p/Combustíveis e Lubrificantes |  |
| TEMIPI | String |  | Tem IPI | `S`=Sim `N`=Não |
| IPIEMBUT | String |  | IPI Embutido | `S`=Sim `N`=Não |
| SOMARIPI | String |  | Somar IPI ao total da nota | `S`=Sim `N`=Não |
| IPIINCICMS | String |  | IPI Incide na base de ICMS | `A`=Usar do Parceiro `N`=Não Incide `S`=Incide |
| CSTIPIENT | Integer |  | Código Sit.Trib.IPI Entrada | `-1`=(-1) Não sujeita ao IPI `0`=00-Entrada c/Recuperação de Crédito `49`=49-Outras Entradas `5`=05-Entrada c/Suspensão `4`=04-Entrada Imune_(+3)_ |
| CSTIPISAI | Integer |  | Código Sit.Trib.IPI Saída | `53`=53-Saída Não Tributada `-1`=(-1) Não sujeita ao IPI `52`=52-Saída Isenta `51`=51-Saída c/Alíquota zero `50`=50-Saída Tributada_(+3)_ |
| CODENQIPIENT | Integer |  | Código Enq. Legal IPI Entrada |  |
| CODENQIPISAI | Integer |  | Código Enq. Legal IPI Saída |  |
| CALCDIFICMS | String |  | Calcular diferença de ICMS | `S`=Sim `N`=Não |
| SOMASUBST | String |  | Soma ST no total da nota | `S`=Sim `N`=Não |
| TEMICMS | String |  | Tem ICMS | `N`=Não `S`=Sim |
| TEMFUNRURAL | String |  | Tem FUNRURAL/INSS | `S`=Sim `N`=Não |
| TEMIRF | String |  | Tem IRF | `N`=Não `S`=Sim |
| TEMPIS | String |  | Tem PIS | `N`=Não `S`=Sim |
| TEMCOFINS | String |  | Tem COFINS | `S`=Sim `N`=Não |
| TEMISS | String |  | Tem ISS | `N`=Não `S`=Sim |
| CALCFETHAB | String |  | Calcular FETHAB | `N`=Não `S`=Sim |
| CLASSIFICMS | String |  | Classificação ICMS | `A`=Usar do Parceiro `I`=Isento de ICMS `X`=Consumidor Final Contribuinte `C`=Consumidor Final Não Contribuinte `R`=Revendedor_(+1)_ |
| PERCMINBASEINSS | Float |  | % Mín. da Base de INSS sobre o Total da Nota |  |
| ATUSALDOCONT | String |  | Atualização do saldo dos contratos | `E`=Entrar `null`=Não atualiza `B`=Baixar |
| COMPLEMENTO | String |  | Tipo de Emissão | `A`=de Ajuste `S`=Complementar `N`=Normal |
| TIPOEMISSAONFCOM | String |  | Tipo de Emissão | `A`=de Ajuste `N`=Normal `S`=Substituição |
| INDNATFRT | String |  | Indicador da Natureza do Frete Contratado | `9`=9 - Outras `4`=4 - Transferência de produtos acabados entre estabelecimentos da pessoa jurídica `3`=3 - Operações de compras(bens p/ revenda, matéria-prima e outros produtos, não geradores de crédito) `5`=5 - Transferência de produtos em elaboração entre estabelecimentos da pessoa jurídica `2`=2 - Operações de compras(bens para revenda, matérias-prima e outros produtos, geradores de crédito)_(+2)_ |
| NATBCCRED | String |  | Natureza da Base de Cálculo do Crédito de Pis/Cofins | `01`=01-Aquisição de bens para revenda `05`=05-Aluguéis de prédios `18`=18-Estoque de abertura de bens `17`=17-Ativ. Prestação Serv. de Limp., Conservação e Manut. - V.T., V.R. ou V.A., fardamento ou uniforme `08`=08-Contraprestações de arrendamento mercantil_(+13)_ |
| BASENUMERACAO | String |  | Base numeração | `D`=Devolução de Venda `A`=DAV cupom fiscal `S`=Manual (Informada pelo Usuário) `I`=Impressora `V`=Venda_(+6)_ |
| NUMSOMAUT | String |  | Numeração somente automática | `N`=Não `S`=Sim |
| TRAVAFIMIMP | String |  | Travar até terminar a impressão | `N`=Não `S`=Sim |
| TIPONUMERACAO | String |  | Tipo de Numeração | `M`=Matriz `U`=Única `S`=Empresa / Série `Z`=Matriz / Série `F`=Empresa |
| EMITENOTA | String |  | Imprimir | `S`=Na Confirmação `P`=Proibido `O`=Opcional `N`=Manual |
| EMITEBOLETA | String |  | Imprimir Pix/Boleto/Duplicata | `S`=Na Confirmação `P`=Proibido `N`=Manual |
| IMPNOTAADICIONAL | String |  | Imprimir Nota Adicional | `N`=Não `S`=Sim |
| VALIDADATA | String |  | Reiniciar numeração por data | `N`=Não `S`=Sim |
| VALESTMAXIMO | String |  | Valida Estoque Máximo | `S`=Sim `N`=Não |
| IMPNAOCONF | String |  | Imprimir nota adicional antes de confirmada | `N`=Não `S`=Sim |
| CODMODNF | Integer |  | Modelo de impressão de nota fiscal |  |
| CODMODDAD | Integer |  | Modelo para Dados Adicionais de NF-e |  |
| CODMODRO | Integer |  | Modelo de impressão de romaneio |  |
| VALNUM | String |  | Valida Numeração por | `5`=Número / Tipo Movimento `E`=Parceiro / Número / Série `3`=PROIBIR - Parceiro / Número / Série `U`=Parceiro / Número / Tipo Movimento `S`=Parceiro / Número / Tipo Movimento / Série_(+5)_ |
| CODMODCFECANC | Integer |  | Modelo de impressão de cancelamento CF-e |  |
| NFSE | String |  | NFS-e | `M`=Convencional (Não usa NFS-e) `N`=Normal |
| CAMGEREDICONF | String |  | Caminho para geração de EDI na confirmação |  |
| ICMSPROPFRETE | String |  | ICMS proporcional para Frete | `S`=Sim `N`=Não |
| ICMSPROPSEG | String |  | ICMS proporcional para Seguro | `S`=Sim `N`=Não |
| ICMSPROPDESTAQUE | String |  | ICMS proporcional para Destaque | `N`=Não `S`=Sim |
| ICMSPROPJURO | String |  | ICMS proporcional para Juro | `N`=Não `S`=Sim |
| ICMSPROPEMBALAGEM | String |  | ICMS proporcional para Embalagem | `N`=Não `S`=Sim |
| PISPROPFRETE | String |  | PIS proporcional para Frete | `S`=Sim `N`=Não |
| PISPROPSEG | String |  | PIS proporcional para Seguro | `N`=Não `S`=Sim |
| PISPROPDESTAQUE | String |  | PIS proporcional para Destaque | `S`=Sim `N`=Não |
| PISPROPEMBALAGEM | String |  | PIS proporcional para Embalagem | `S`=Sim `N`=Não |
| PISPROPJURO | String |  | PIS proporcional para Juro | `N`=Não `S`=Sim |
| IPIPROPFRETE | String |  | IPI proporcional para Frete | `N`=Não `S`=Sim |
| IPIPROPSEG | String |  | IPI proporcional para Seguro | `N`=Não `S`=Sim |
| IPIPROPDESTAQUE | String |  | IPI proporcional para Destaque | `N`=Não `S`=Sim |
| IPIPROPEMBALAGEM | String |  | IPI proporcional para Embalagem | `N`=Não `S`=Sim |
| IPIPROPJURO | String |  | IPI proporcional para Juro | `N`=Não `S`=Sim |
| COFINSPROPFRETE | String |  | COFINS proporcional para Frete | `S`=Sim `N`=Não |
| COFINSPROPSEG | String |  | COFINS proporcional para Seguro | `N`=Não `S`=Sim |
| COFINSPROPDESTAQUE | String |  | COFINS proporcional para Destaque | `N`=Não `S`=Sim |
| COFINSPROPEMBALAGEM | String |  | COFINS proporcional para Embalagem | `S`=Sim `N`=Não |
| COFINSPROPJURO | String |  | COFINS proporcional para Juro | `N`=Não `S`=Sim |
| STPROPFRETE | String |  | S.T.proporcional para Frete | `S`=Sim `N`=Não |
| STPROPFRETEEXT | String |  | para Frete Extra | `S`=Sim `N`=Não |
| STPROPSEG | String |  | S.T.proporcional para Seguro | `S`=Sim `N`=Não |
| STPROPDESTAQUE | String |  | S.T.proporcional para Destaque | `S`=Sim `N`=Não |
| STPROPEMBALAGEM | String |  | S.T.proporcional para Embalagem | `S`=Sim `N`=Não |
| STPROPJURO | String |  | S.T.proporcional para Juro | `S`=Sim `N`=Não |
| TIPIVASUBST | String |  | Tipo de Calculo IVA ponderado | `1`=Soma Base S.T. / Soma Base ICMS sem Redução `null`=Soma Base S.T. / Soma Base ICMS Reduzida |
| BASEICMSFRETECALCST | String |  | Usar base ICMS Frete Extra Nota p/calc.ST | `S`=Sim `N`=Não |
| CALCSTFRTXTNOTPROP | String |  | Calc. ICMS/ST extra nota p/ frete extra nota proporcional aos itens | `S`=Sim `N`=Não |
| EXPGRS | Integer |  | Exportação para GRS | `0`=Não exportar `2`=Cancelamento `1`=Inclusão |
| EXPTES | String |  | Exportação para tesouraria | `R`=Reclamação Cobrança Indevida - RI `A`=Arrecadação `N`=Não exportar |
| ATUALCOMOS | String |  | Calcular comissão para O.S. | `N`=Não `S`=Sim |
| TIPFATSERV | String |  | Faturamento relacionado a Ordem de Serviço | `F`=Pelo Mód. Serviço para O.S. Fechadas `U`=Pelo Mód. Serviço ou pela Central (todas Parcelas) `S`=Pelo Mód. Serviço todas as Parcelas do Financeiro `P`=Pelo Mód. Serviço pelas Parcelas do Financeiro `N`=Não Faturar_(+2)_ |
| BUSCMPTERC | String |  | Apoio p/Devolução de Produtos de Terceiros | `N`=Não busca `S`=Busca com local da Nota `E`=Busca com Local de Entrada `P`=Busca com Local de Produção |
| ATUALFINTERC | String |  | Soma itens com/de Terceiros ao Financeiro | `N`=Não `S`=Sim |
| UTILIZAWMS | String |  | Endereçamento no WMS | `M`=Manual `A`=Automática `N`=Não Utiliza |
| TIPATUALWMS | String |  | Atualização no WMS | `B`=Baixar `E`=Entrar |
| ATUALDATRECWMS | String |  | Atualização Data Rec. no WMS | `M`=Mensal `N`=Não Utiliza `S`=Semanal `D`=Diário |
| EXIGEAGENDAWMS | String |  | Exige agendamento p/Carga e Descarga no WMS | `S`=Sim `N`=Não |
| EXPORTA | String |  | Exporta Replicação | `N`=Não `S`=Sim |
| CODTRIB | Integer |  | Tributação |  |
| ATUALIZARATEIO | String |  | Atualiza Rateio | `N`=Não `S`=Sim |
| CONSIGNACAO | String |  | Consignação | `S`=Sim `N`=Não |
| VLRBASEPGTO | Float |  | Valor Base Pagamento |  |
| COFINSSTPROPFRETE | String |  | COFINS ST Prop. Frete | `N`=Não `S`=Sim |
| PISSTPROPEMBALAGEM | String |  | PIS ST Prop. Embalagem | `N`=Não `S`=Sim |
| SOMARCOFINSST | String |  | Somar COFINS ST ao Total da Nota | `N`=Não `S`=Sim |
| COFINSSTPROPSEG | String |  | COFINS ST Prop. Seguro | `N`=Não `S`=Sim |
| COFINSSTPROPEMBALAGEM | String |  | COFINS ST Prop. Embalagem | `N`=Não `S`=Sim |
| COFINSSTPROPDESTAQUE | String |  | COFINS ST Prop. Destaque | `N`=Não `S`=Sim |
| SOMARPISST | String |  | Somar PIS ST ao Total da Nota | `N`=Não `S`=Sim |
| PISSTPROPFRETE | String |  | PIS ST Prop. Frete | `N`=Não `S`=Sim |
| PISSTPROPJURO | String |  | PIS ST Prop. Juro | `S`=Sim `N`=Não |
| INTEGSERCON | String |  | Integ. Série ao Contrato | `N`=Não atualizar `E`=Entrada `B`=Baixa |
| COFINSSTPROPJURO | String |  | COFINS ST Prop. Juro | `N`=Não `S`=Sim |
| PISSTPROPDESTAQUE | String |  | PIS ST Prop. Destaque | `N`=Não `S`=Sim |
| PISSTPROPSEG | String |  | PIS ST Prop. Seguro | `N`=Não `S`=Sim |
| NULAYOUT | Integer |  | Nro. Layout |  |
| NULAYOUTCVR | Integer |  | Nro. Layout CVR |  |
| ATUALCTB | String |  | Atualiza Contabilidade | `N`=Não `S`=Sim |
| OPERCOMMOEDA | String |  | Operação em Moeda | `N`=Não `S`=Sim |
| SEMMOEDAFIN | String |  | Não preencher moeda para Financeiro | `S`=Sim `N`=Não |
| NFEESTORNO | String |  | NF-e de estorno | `S`=Sim `N`=Não |
| DESCREMAIL | String |  | Descrição do e-mail |  |
| APLICLEITRANSP | String |  | Aplicar a lei da transparência | `S`=Aplicar sempre `P`=Usar do parceiro `N`=Nunca aplicar |
| APLICTABIRFINSS | String |  | Aplicar tabela de IRPF/INSS | `S`=Sim `N`=Não |
| USASERVTABIRFINSS | String |  | Usar serviço p/ cálculo com tabela de IRPF/INSS | `S`=Sim `N`=Não |
| INDTERC | String |  | Industrialização efetuada por terceiros | `N`=Não `S`=Sim |
| DESCONNFSE | String |  | Desconto Condicionado para NFS-e | `N`=Não usa `S`=Financeiro `A`=Ambos `C`=Nota |
| NUFOP | Integer |  | Finalidade da Operação |  |
| CONSAUXILIAR | String |  | Consultas Auxiliares |  |
| DISTSTVLRUNITFAT | String |  | Distribuir valor do ST no preço unitário ao faturar | `N`=Não `S`=Sim |
| CALCFCPINT | String |  | Calcular FCP (ICMS/ST) Interno? | `S`=Sim `N`=Não |
| ICMSORIGESTPED | String |  | Calcular ICMS de Origem Estrangeira | `S`=Sim `N`=Não |
| INDTIPREC | String |  | Indicador do Tipo de Receita | `9`=9 - Outras receitas `8`=8 - Outras receitas de terceiros `7`=7 - Outras receitas próprias de natureza não-cumulativa `6`=6 - Receita própria - serviços a faturar em período futuro `5`=5 - Receita própria - co-faturamento_(+5)_ |
| GERADEMANDAMPS | String |  | Gerar demanda para MPS | `S`=Sim `N`=Não |
| LIGORIGORIG | String |  | Ligar com a Origem da Origem com quantidade negativa? | `S`=Sim `N`=Não |
| USARECPARCIAL | String |  | Utiliza recebimento parcial? | `S`=Sim `N`=Não |
| ATUALESTWMSTERC | String |  | Atualiza Estoque de Terceiros WMS? | `S`=Sim `N`=Não |
| IGNEXPAUTLOT | String |  | Ignorar explosão automática de lotes nesta TOP | `S`=Sim `N`=Não |
| VALSITCADRF | String |  | Valida situação cadastro na ReceitaWS ? | `S`=Sim `N`=Não |
| GERCORAPON | String |  | Gerar Correção de Apontamento (K280) | `S`=Sim `N`=Não |
| CONSVLRREMRETIND | Integer |  | Considerar o valor da remessa, no retorno de industrialização como | `null`=Considerar como Desconto e Sem Pagamento (tipo de pagamento = 90) `1`=Considerar apenas como Desconto |
| INTERMED | String |  | Indicador de Intermediador/Marketplace | `1`=1-Operação em site ou plataforma de terceiros (intermediadores/marketplace) `0`=0-Operação sem intermediador (em site ou plataforma própria) |
| DEVSEMDESTAQUEST | String |  | Devolver sem destacar ST | `S`=Sim `N`=Não |
| CODINTERM | Integer |  | Intermediador da Transação |  |
| DEVSEMDESTAQUEIPI | String |  | Devolver sem destacar IPI | `N`=Não `S`=Sim |
| IGNORACOMPLITEM | String |  | Ignorar complemento dos itens nas informações adicionais dos produtos? | `S`=Sim `N`=Não |
| SEMCREDIPIST | String |  | Operação sem direito a crédito IPI/ST | `null`=Não `S`=Sim |
| PERMITECNAEDIFNOTA | String |  | Possibilita emissão de NFS-e com múltiplos CNAEs | `S`=Sim `N`=Não |
| OUTDESPSTEXTNOTA | String |  | Frete/Seguro/Outras Despesas para ST extra nota | `S`=Sim `N`=Não |
| IMPXMLMANTDESPACES | String |  | Importar o XML mantendo as despesas acessórias com os valores do XML | `N`=Não `S`=Sim |
| REDPISBCPISCOFINS | String |  | Deduzir valor do PIS/COFINS da BC do PIS e COFINS? | `S`=Sim `N`=Não |
| CALCPISCFSFIN | String |  | Calcula PIS/COFINS por percentual das notas | `S`=Sim `N`=Não |
| CONSNFERELCANCEFD | String |  | Considerar NFe relacionada como cancelada no EFD Contribuições | `N`=Não `S`=Sim |
| VALDISPESTDEV | String |  | Valida disponibilidade de estoque na devolução? | `N`=Não `S`=Sim |
| DESCCSTBCPISCF | String |  | Desconsiderar CST’s de ICMS da BC do PIS/COFINS? |  |
| USAVENDAMAIS | String |  | Utilizar no Sankhya Venda Mais | `N`=Não `S`=Sim |
| PERMTRANSGALPAO | String |  | Permite transferência entre galpões | `S`=Sim `null`=Não |
| REDSTBCPISCOFINS | String |  | Deduzir valor do ICMS/ST na BC do PIS e COFINS? | `S`=Sim `N`=Não |
| DESCONSLCDPR | String |  | Desconsiderar Top na Geração do Livro Caixa Digital do Produtor Rural | `N`=Não `S`=Sim |
| IGNOBSORIGREM | String |  | Ignorar Observação da Nota de Origem | `N`=Não `S`=Sim |
| CONSTOPAPURSIMP | String |  | Considerar na Apuração do Simples? | `S`=Sim `N`=Não |
| AD_MOBILIDADE | String |  | Mobilidade | `N`=Não `S`=Sim |
| DEDFCPBCPISCOFINS | String |  | Deduzir valor de FCP na BC do PIS e COFINS? | `S`=FCP-ST `N`=Não Deduz `F`=FCP `A`=Ambos |
| CONFVLREVENT68 | String |  | Valor para validar o evento 68 | `null`=Valor do produto `L`=Valor líquido do produto |
| AD_PADRAOMOB | String |  | TOP Padrão | `S`=Sim `N`=Não |
| GERINFOEFDPAG | String |  | Gerar informações do EFD Reinf Grupo 4000? | `N`=Não `S`=Sim |
| TIPCOMPLCUST | Integer |  | Tipo complemento custo | `null`=Não se aplica `1`=Positivo `-1`=Negativo |
| RECBRUTACIAP | String |  | Receita Bruta p/ CIAP | `N`=Não afeta `S`=Soma `T`=Subtrai |
| AD_USANATPADGLOBDEV | String |  | Utiliza Natureza Global p/ Devolução de Compra (NATPADDEVCPA) | `S`=Sim `N`=Não |
| ARREDQTDUNALT | String |  | Arredonda Qtd. unid. alternativa? | `N`=Não `S`=Sim |
| AD_USANATPADGLOBDEVVENDA | String |  | Utiliza Natureza Global p/ Devolução de Venda (NATPADDEV) | `S`=Sim `N`=Não |
| AD_CRIAPARCIXN | String |  | [Cria parceiro via importação XML da nota?] | `S`=Sim `N`=Não |
| TEMCBS | String |  | Tem CBS | `N`=Não `S`=Sim |
| TEMIBS | String |  | Tem IBS | `N`=Não `S`=Sim |
| TEMIS | String |  | Tem IS | `N`=Não `S`=Sim |
| OPERESSACOMP | String |  | Operação com Ressarcimento/Complemento de ST | `N`=Não `S`=Sim |
| TEMIBSCBSMONO | String |  | Tem IBS/CBS Monofásico | `N`=Não `S`=Sim |
| CONSDISBAIXEST | String |  | Considerar estoque real na baixa de estoque | `N`=Não `S`=Sim |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |

## TGFVEN — Vendedores Representantes
Campos: 58

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| APELIDO | String |  | Apelido |  |
| TIPOCERTIF | String |  | Tipo p/ certificação |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CODREG | Integer |  | Região |  |
| COMVENDA | Float |  | Comissão venda |  |
| COMGER | Float |  | Comissão gerência |  |
| VLRHORA | Float |  | Valor hora p/ comissão de O.S. |  |
| CODFORM | Integer |  | Fórmula Comissão |  |
| CODCARGAHOR | Integer |  | Carga Horária |  |
| DIACOM | Integer |  | Dia inicial p/período de comissão |  |
| CODEMP | Integer |  | Empresa |  |
| CODGER | Integer |  | Gerente |  |
| CODPARC | Integer |  | Parceiro |  |
| CODFUNC | Integer |  | Funcionário |  |
| CODCENCUSPAD | Integer |  | Centro Resultado Padrão |  |
| PERCCUSVAR | Float |  | % Custo Variável |  |
| EMAIL | String |  | Email |  |
| SALDODISP | Float |  | Saldo Disponível |  |
| PROVACRESC | Float |  | Provisão acréscimo |  |
| DESCMAX | Float |  | Desconto máximo |  |
| ACRESCMAX | Float |  | Acréscimo máximo |  |
| TIPVALOR | String |  | Usar valor p/ comissão de OS | `N`=da Negociação `U`=do Vendedor |
| TIPVEND | String |  | Tipo | `E`=Executante `T`=Técnico `C`=Comprador `G`=Gerente `V`=Vendedor_(+2)_ |
| GRUPORETENCAO | String |  | Grupo de retenção |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de alteração |  |
| PARTICMETA | Float |  | Participação na meta |  |
| SENHA | Integer |  | Senha |  |
| ATUACOMPRADOR | String |  | Atua também como comprador | `S`=Sim `N`=Não |
| TIPCALC | String |  | Pagamento de Comissão por data de | `B`=Baixa `N`=Negociação |
| GRUPODESCVEND | String |  | Grupo Desc. Vendedor |  |
| COMCM | String |  | Recebe comissão em CM | `N`=Não `S`=Sim |
| RECHREXTRA | String |  | Recebe Hora Dobrada | `N`=Não `S`=Sim |
| BH_CODTIPVENDA | Integer |  | Tipo de Negociação Market Place |  |
| TIPFECHCOM | String |  | Tipo de fechamento de comissão | `N`=Nenhuma `F`=Financeiro `P`=Folha |
| BH_CONSIDESC | String |  | Considerar Desconto Mkt Place? | `N`=Não `S`=Sim |
| AD_MAXIMA | String |  | Integra com a Máxima? | `N`=Não `S`=Sim |
| AD_MAXIMA_LOCAL | Integer |  | Local do Vendedor |  |
| BH_CONSIJUR | String |  | Considerar Juros Mkt Place? | `S`=Sim `N`=Não |
| AD_CODCTABCOINT | Integer |  | Conta Bancária Vendedor (Boletos) |  |
| BH_CODTAB | Integer |  | Cód Tabela de Preços Mkt Place |  |
| AD_GERARPLP | String |  | Gerar PLP B2W | `S`=Sim `N`=Não |
| BH_APELIDO | String |  | Apelido Market Place |  |
| AD_USATRANSP | String |  | Usa Transportadora Propria? | `S`=Sim `N`=Não |
| BH_ALIASVENDEDOR | String |  | Alias Integração Vendedor |  |
| AD_MOBILIDADE | String |  | Mobilidade | `S`=Sim `N`=Não |
| AD_EMPADI | Integer |  | Empresa Adicional |  |
| AD_PROMOCANAL | Float |  | % Promoção Canal MTP |  |
| AD_PROMOCANALTEB | Float |  | % Reembolso MTP |  |
| AD_NOMEARQZEBRA | String |  | NOMEARQZEBRA |  |
| AD_NURELETIQ | Integer |  | NURELETIQ |  |
| AD_CONTAPENDENCIA | Integer |  | Conta bancaria Pendencia |  |
| AD_CODEMKTPTEM | Integer |  | Codigo mktp temapi |  |
| AD_CODECOMPANY | Integer |  | Empresa temapi |  |
| AD_CANAL | String |  | Canal | `2`=Loja Fisica `3`=Marketplace `1`=Digital |
| CODVEND | Integer |  | Código |  |
| PROVACRESCCAC | Float |  | Provisão do carrinho |  |
| SALDODISPCAC | Float |  | Saldo Diponivel do Carrinho |  |

## TGFVOL — Volumes
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRVOL | String |  | Descrição |  |
| UTILIREGVOLWMS | String |  | Utiliza no Registro de Volumes WMS | `N`=Não `S`=Sim |
| DECQTD | Integer |  | Decimais para quantidade |  |
| CODVOLFCI | String |  | Unidade para FCI |  |
| UTILICONFPESO | String |  | Utiliza Conferência por peso | `S`=Sim `N`=Não |
| ATUNUVERSAO | String |  | Atualizar versão |  |
| NUVERSAO | Integer |  | Versão |  |
| CODVOL | String |  | Sigla da Unidade |  |