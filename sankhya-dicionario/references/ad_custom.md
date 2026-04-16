# AD_ — Customizações / Campos adicionais

> Gerado do dicionário oficial TDD Sankhya. 271 tabelas.


## AD_ACOMPINTEGRACAO — Acompanhamento diário Integrações
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATA | Date |  | Data |  |
| EMPRESA | String |  | Empresa |  |
| STATUSAMAZON | String |  | Integração Status Amazon | `S`=Sim `N`=Não |
| PEDIDOAMAZON | String |  | Integração Pedido Amazon | `N`=Não `S`=Sim |
| PEDIDOVTEX | String |  | Integração Pedido Vtex | `S`=Sim `N`=Não |
| STATUSVTEX | String |  | Integração Status Vtex | `S`=Sim `N`=Não |
| OBSERVACAOAMAZON | String |  | Observação Amazon |  |
| OBSERVACAOVTEX | String |  | Observação Vtex |  |
| STATUSVIA | String |  | Integração Status Via | `S`=Sim `N`=Não |
| PEDIDOVIA | String |  | Integração Pedido Via | `S`=Sim `N`=Não |
| OBSERVACAOVIA | String |  | Observação Via |  |
| PEDIDOB2W | String |  | Integração Pedido B2W | `S`=Sim `N`=Não |
| STATUSB2W | String |  | Integração Status B2W | `S`=Sim `N`=Não |
| OBSERVACAOB2W | String |  | Observação B2W |  |
| STATUSMAGALU | String |  | Integração Status Magalu | `S`=Sim `N`=Não |
| PEDIDOMAGALU | String |  | Integração Pedido Magalu | `S`=Sim `N`=Não |
| OBSERVACAOMAGALU | String |  | Observação Magalu |  |
| STATUSMELI | String |  | Integração Status Meli | `S`=Sim `N`=Não |
| PEDIDOMELI | String |  | Integração Pedido Meli | `S`=Sim `N`=Não |
| OBSERVACAOMELI | String |  | Observação Meli |  |
| STATUSCARREFOUR | String |  | Integração Status Carrefour | `S`=Sim `N`=Não |
| PEDIDOCARREFOUR | String |  | Integração Pedido Carrefour | `S`=Sim `N`=Não |
| OBSERVACAOCARREFOUR | String |  | Observação Carrefour |  |
| STATUSSHOPEE | String |  | Integração Status Shopee | `S`=Sim `N`=Não |
| PEDIDOSHOPEE | String |  | Integração Pedido Shopee | `S`=Sim `N`=Não |
| OBSERVACAOSHOPEE | String |  | Observação Shopee |  |

## AD_ADADMKTPLCMGL — AD_ADMKTPLCMGL
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| CODPROD | Integer |  | Código |  |
| IDMGL | Integer |  | IDMGL |  |
| CODVEND | Integer |  | Vendedor |  |

## AD_ADADMKTPLCMGLPROD — AD_ADMKTPLCMGLPROD
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| CODPROD | Integer |  | Código |  |
| IDMGL | Integer |  | IDMGL |  |
| IDPRODUCT | Integer |  | ID |  |
| NAME | String |  | Nome do Produto |  |
| STATUS | String |  | Ativo? | `S`=SIM `N`=NAO |
| STATUSENVIO | String |  | Status da integração do produto |  |
| WARRANTYTIME | String |  | Tempo de Garantia em Meses |  |
| CODECATEGORIA | Integer |  | Cod. Categoria |  |
| CODE | String |  | Código do produto |  |

## AD_ADADMKTPLCMGLSKU — AD_ADMKTPLCMGLSKU
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| IDSKU | Integer |  | IDSKU |  |
| IDMGL | Integer |  | IDMGL |  |
| CODPROD | Integer |  | Código |  |
| LISTPRICE | Float |  | Preço de |  |
| MAINIMAGEURL | String |  | URL da Imagem como Principal (NÃO usar HTTPS) |  |
| NAME | String |  | Nome do SKU |  |
| PERCESTOQUE | Float |  | % Estoque |  |
| SALEPRICE | Float |  | Preço Fixo |  |
| STATUS | String |  | Ativo? | `S`=SIM `N`=NAO |
| STATUSENVIO | String |  | Status de Integração SKU |  |
| UPDPRICE | String |  | Enviar Alterações SKU? | `S`=SIM `N`=NAO |
| VARIATION | String |  | Variação do Produto |  |
| CODLOCAL | Integer |  | Cód. Local Estoque |  |
| PORLOCAL | String |  | Por Local? | `S`=Sim `N`=Não |
| ESTOQUE | Integer |  | EstoqueFixo |  |
| CODTAB | Integer |  | Código Tab. Preço |  |
| TABPRECO | String |  | Por Tabela de Preço?: | `S`=Sim `N`=Não |
| CODPRODVAR | Integer |  | Cód. Produto Variação |  |
| CODSKUMKTP | String |  | Cód. Sku No Magalu |  |
| UPDATESTK | String |  | Atualiza Estoque? | `N`=Não `S`=Sim |
| DESCRIPTION | C |  | Descrição do SKU |  |

## AD_ADMKTPLCMGLIMGVAR — Imagens Variação Magalu
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDSKU | Integer |  | IDSKU |  |
| IDMGL | Integer |  | IDMGL |  |
| CODPROD | Integer |  | Código |  |
| IDVAR | Integer |  | ID |  |
| ID | Integer |  | ID |  |
| URLIMAGES | C |  | Url das imagens do Sku (USAR HTTP e NÃO HTTPS) |  |

## AD_ADTDBASSINATURA — Assinatura TDB
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDCONTRATO | String |  | ID Contrato |  |
| CUSTOMERDID | String |  | Codigo do Cliente |  |
| CUSTOMEREMAIL | String |  | Email do Cliente |  |
| TITLE | String |  | Titulo da Assinatura |  |
| STATUS | String |  | Status de Operacao |  |
| ISSKIPPED | String |  | Esta Pausado? |  |
| NEXTPYRCHASEDATE | DateTime |  | Proxima Data de Compra |  |
| LASTPURCHASEDAT | DateTime |  | Ultima Data de Compara |  |
| PLAN_ID | String |  | Id do Plano |  |
| PLAN_FREQUENCY_PERIODICITY | String |  | Periodicidade |  |
| PLAN_PERIODICITY_INTERVAL | Integer |  | Intervalo do Periodo |  |
| PLAN_VALIDITY_BEGIN | DateTime |  | Inicio |  |
| PLAN_VALIDITY_END | DateTime |  | Fim |  |
| CYCLECOUNT | Integer |  | Contagem de Ciclo |  |
| CREATEDAT | DateTime |  | Data de Criação |  |
| LASTUPDATE | DateTime |  | Ultima Atualização |  |
| SHIPPINGADDRESS_ID | String |  | ID do Endereço do Envio |  |
| SIPPINGADDRESS_TYPE | String |  | Tipo de Endereço de Envio |  |
| PLAN_PURCHSETTINGS_PGMETOD_SY | String |  | Sistema de Pagamento |  |
| PLAN_PURCHSET_PGMETOD_INSTALLM | Integer |  | Prestações |  |
| PLAN_PURCHSET_CURRENCYCODE | String |  | Código da Moeda |  |
| PLAN_PURCHSET_PGMETOD_AC | String |  | Conta de Pagamento |  |
| PLAN_PURCHASEDAY | String |  | Dia da Compra |  |
| CAMPANHAASSINANTE | String |  | Cliente ja recebeu o brinde? | `S`=Sim `N`=Não |
| AD_TRATATIVA | String |  | Tratativa Realizada | `S`=Sim `N`=Não |
| AD_DTTRATATIVA | Date |  | Data da tratativa realizada |  |
| MOTIVOTRATATIVA | String |  | Motivo da Tratativa | `T`=ECOM - Transferência loja pendente `C`=SAC - Assinatura cancelada `S`=SAC - Contato em andamento `CP`=SAC - Contato pendente `PC`=SAC - Próximo ciclo_(+2)_ |
| OBSERVACAO | String |  | Observação |  |
| CODASSIN | Integer |  | Código |  |

## AD_ADTDBASSINATURAITE — Items
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDCONTRATO | String |  | ID Contrato |  |
| IDITEMS | String |  | Item |  |
| QUANTITY_ITEMS | Integer |  | Quantidade de Itens |  |
| ISSKIPPED_ITEMS | String |  | Item Pausado |  |
| STATUS_ITEMS | String |  | Statuso do Item |  |
| ORIGINALORDERID | String |  | ID original do pedido |  |
| MAUALPRICE | Float |  | Preço Manual |  |
| STATUSRESERVA | String |  | Status Reserva | `R`=Reservado |
| SKU_ID_ITEMS | Integer |  | SKU ID do Item |  |

## AD_ANALISECICLOPED — Analise Ciclo do Pedido
Campos: 52

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| PEDIDO | String |  | Pedido |  |
| NUNOTAPRE | Integer |  | Nr Unico Pre Pedido |  |
| DHPRE | DateTime |  | Dh. Pre Pedido |  |
| NUNOTANOTA | Integer |  | Nr Unico Nota |  |
| DHNOTA | DateTime |  | Dh Nota |  |
| NUNOTADEV | Integer |  | Nr Unico Devolução |  |
| DHDEV | DateTime |  | Dh Devolução |  |
| DHCONFINI | DateTime |  | Dh. Conferencia Inic |  |
| DHCONFFIN | DateTime |  | Dh. Conferencia Fin |  |
| ORDEMCARGA | Integer |  | Ordem de Carga |  |
| NUODP | Integer |  | Nr. Ordem de Despacho |  |
| DHINCNUODP | DateTime |  | Dh Inclusão Ordem de Despacho |  |
| DHFECNUODP | DateTime |  | Dh Fechamento Ordem de Despacho |  |
| DHCOLNUODP | DateTime |  | Dh Coleta Ordem de Despacho |  |
| DTPREVENT | Date |  | Previsao de Entrega Pedido |  |
| TEMFURO | String |  | Tem Furo | `S`=Sim `N`=Não |
| CODVEND | Integer |  | Vendedor |  |
| QTDVOL | Integer |  | Qtd de Volume |  |
| NUCONF | Integer |  | Nr. Conferencia |  |
| USUCONF | Integer |  | Usuario Conferencia |  |
| FALTOUITENS | String |  | Faltou Item para o Cliente | `S`=Sim `N`=Não |
| CHAVENF | String |  | Chave Nota |  |
| NUMNOTA | String |  | Nr da Nota Fiscal |  |
| SERIENOTA | String |  | Serie Nota Fiscal |  |
| DHORDEMDECARGA | DateTime |  | Dh Ordem de Carga |  |
| METODO | String |  | Metodo de Envio |  |
| STATUSTRANSP | String |  | Status Transporte |  |
| DHSTATUSTRANSP | DateTime |  | DH Status Transporte |  |
| RASTREIO | String |  | Rastreio |  |
| URLRASTREIO | String |  | URLRASTREIO |  |
| CONTDEVOL | String |  | Controle de Devolução | `S`=Sim `N`=Não |
| CODPARC | Integer |  | Parceiro |  |
| TELEFONE | String |  | Telefone |  |
| STATUSCONF | String |  | Status Conferencia |  |
| CODEND | Integer |  | Endereço |  |
| CODCID | Integer |  | Cidade |  |
| NUMEND | String |  | Nr Endereço |  |
| CONTATO | Integer |  | Contato |  |
| EMAIL | String |  | Email |  |
| CODPARCTRANSP | Integer |  | Codigo do Parceiro Transportadora |  |
| UF | Integer |  | UF |  |
| DHULTSTATUSTRANSP | DateTime |  | Ultima Atualização do Status Transp |  |
| WAREHOUSEID | String |  | Transportadora Shopee |  |
| PREVENTREGACOTACAO | Date |  | Prev de Entrega Cotaçao |  |
| DTENTSAI | Date |  | Data de Prev saida |  |
| PERFORMACECD | String |  | Performace CD |  |
| CODTIPOPERPED | Integer |  | Tipo de Operação do Pedido |  |
| DTPREVENTTRANSP | Date |  | Dt. Prev. Ent.Transp. |  |
| EMAILNPSENVIADO | String |  | Email NPS foi enviado? | `S`=Sim `N`=Não |
| NUNOTAPED | Integer |  | Nr Unico Pedido |  |
| DHPED | DateTime |  | Dh. Pedido |  |

## AD_ATRIBUITO — ATRIBUTO
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Codigo do Atributo |  |
| OBRIGATORIO | String |  | Obrigatorio | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Data Alteração |  |
| ANIMAL | String |  | Animal |  |
| DESCRICAOLONGA | String |  | Descrição Longa |  |
| TITULO | String |  | Titulo |  |
| TIPO | String |  | Tipo de Atributo | `checkbox`=check box `combo`=combo `TEXTO`=Texto `Radio`=Radio `HTML`=HTML |
| CODWAKE | Integer |  | Cod Wake |  |
| DESCRICAO | String |  | Descrição |  |

## AD_ATRIBUTOSSHOPEE — Atributos
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| CODPROD | Integer |  | Código |  |
| IDATRIBUTO | Integer |  | IdAtributo |  |
| IDSHOPEE | Integer |  | IdShopee |  |
| VALUE | String |  | Valor do Atributo |  |
| ATRIBUTOSLIST | C |  | Listagem dos Atributos(Passar uma opção no campo Valor do Atributo |  |
| ENVATRIBUTO | String |  | Status Download Atributo |  |
| ATRIBUTOLISTID | C |  | Lista de IDs Retornado da Shopee (Passar no campo Id Atributo) |  |
| ATRIBUTONAME | String |  | Nome do Atributo |  |
| TYPE | String |  | Tipo do Campo |  |
| STATUSERRO | C |  | Status Retorno com Erro |  |
| IDATRIBUTOSHOPEE | Integer |  | Id do Atributo |  |

## AD_ATRIBVALOR — Opções
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Codigo do Atributo |  |
| CODVALOR | Integer |  | Cod Valor |  |
| DESCRICAO | String |  | Descricao |  |

## AD_ATRIPROD — ATRIPROD
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCAT | Integer |  | Cod Categoria |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| ATRIBUTO | Integer |  | Atributo |  |
| CODPROD | Integer |  | Código |  |

## AD_ATRIPRODVALOR — Valor Atributo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODCAT | Integer |  | Cod Categoria |  |
| CODIGO | Integer |  | Codigo do valor do atributo |  |
| ATRIBUTOS | Integer |  | Atributos do produto |  |
| DESCRICAO | String |  | Descrição |  |
| CODPROD | Integer |  | Código |  |

## AD_B2WENTREGASNUETIQ — AD_B2WENTREGASNUETIQ
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| MEGAROTA | String |  | Identificador da base de Entrega ao Cliente |  |
| NUNOTA | String |  | Numero da Nota Fiscal |  |
| CLIENTE | String |  | Nome do Cliente |  |
| DTPR | String |  | Data Prometida |  |
| CODAWB | String |  | Trackingcode |  |
| ROTA | String |  | Informação Interna da Direct |  |
| NUETIQB2W | String |  | Numero da Etiqueta |  |
| DATAHORAATUAL | DateTime |  | Data de Entrada do Pedido |  |
| IDPLP | Integer |  | Número da PLP |  |

## AD_BACKUPPARCEIRO — Backup Parceiros
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | id |  |
| NOMEPARC | String |  | NOME |  |
| EMAIL | String |  | EMAIL |  |
| TELEFONE | String |  | TELEFONE |  |
| CODPARC | Integer |  | Cód. Parceiro |  |

## AD_BAIXASGETNET — Baixas
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODIGOEC | String |  | Código EC |  |
| VENCIMENTO | String |  | Vencimento |  |
| VENCIMENTOORIG | String |  | Vencimento Original |  |
| PRODUTO | String |  | Produto |  |
| LANCAMENTO | String |  | Lançamento |  |
| PLANOVENDA | String |  | Plano de Venda |  |
| PARCELA | String |  | Parcela |  |
| QTDPARCELA | String |  | Total de Parcelas |  |
| CARTAO | String |  | Cartão |  |
| AUTORIZACAO | String |  | Autorização |  |
| NUMEROCV | String |  | Número do CV |  |
| TERMINAL | String |  | Terminal |  |
| DATAVENDA | String |  | Data da Venda |  |
| VALORORIG | String |  | Valor Original |  |
| VALORBRUTO | String |  | Valor Bruto |  |
| DESCONTOS | String |  | Descontos |  |
| LIQUIDO | String |  | Líquido  |  |
| PEDIDO | String |  | Pedido |  |
| DTPROCESSAMENTO | DateTime |  | Data do Processamento |  |
| LIBERACAO | String |  | Liberação |  |
| TIPODEPROCESSAMENTO | String |  | Tipo de processamento |  |
| VLRDESDOB | Float |  | Valor desdobramento |  |
| VLRDIF | Float |  | Valor diferença |  |
| NUFIN | Integer |  | Número Financeiro |  |
| NUFINNOVO | Integer |  | Novo Número Financeiro |  |
| CODCTABCOINT | Integer |  | Conta de Baixa |  |
| NUNOTA | Integer |  | Número Único Nota |  |
| NUMNOTA | Integer |  | Número da Nota |  |
| NUFINSPLIT | Integer |  | Número Financeiro Split |  |
| TID | String |  | TID |  |
| ECCENTRALIZADOR | String |  | Cód. EC Centralizador |  |

## AD_BAIXASGETNETLOJA — Baixas
Campos: 32

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODIGOEC | String |  | Código EC |  |
| VENCIMENTO | String |  | Vencimento |  |
| VENCIMENTOORIG | String |  | Vencimento Original |  |
| PRODUTO | String |  | Produto |  |
| LANCAMENTO | String |  | Lançamento |  |
| PLANOVENDA | String |  | Plano de Venda |  |
| PARCELA | String |  | Parcela |  |
| QTDPARCELA | String |  | Total de Parcelas |  |
| CARTAO | String |  | Cartão |  |
| AUTORIZACAO | String |  | Autorização |  |
| NUMEROCV | String |  | Número do CV |  |
| TERMINAL | String |  | Terminal |  |
| DATAVENDA | String |  | Data da Venda |  |
| VALORORIG | String |  | Valor Original |  |
| VALORBRUTO | String |  | Valor Bruto |  |
| DESCONTOS | String |  | Descontos |  |
| LIQUIDO | String |  | Líquido |  |
| PEDIDO | String |  | Pedido |  |
| DTPROCESSAMENTO | DateTime |  | Data do Processamento |  |
| LIBERACAO | String |  | Liberação |  |
| TIPODEPROCESSAMENTO | String |  | Tipo de processamento |  |
| VLRDESDOB | Float |  | Valor desdobramento |  |
| VLRDIF | Float |  | Valor diferença |  |
| NUFIN | Integer |  | Número Financeiro |  |
| NUFINNOVO | Integer |  | Novo Número Financeiro |  |
| CODCTABCOINT | Integer |  | Conta de Baixa |  |
| NUNOTA | Integer |  | Número Único Nota |  |
| NUMNOTA | Integer |  | Número da Nota |  |
| NUFINSPLIT | Integer |  | Número Financeiro Split |  |
| ECCENTRALIZADOR | String |  | Cód. EC Centralizador |  |

## AD_BAIXASIFOOD — Baixas Ifood
Campos: 64

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODIGO | Integer |  | Código |  |
| DATA | Date |  | Data de Inserção |  |
| UUIDPEDIDO | String |  | Identificador Único Universal |  |
| STATUSPEDIDO | String |  | Status do Pedido |  |
| EDICAOCESTA | String |  | Edição da Cesta |  |
| PEDIDOINICIAL | Float |  | Pedido Inicial |  |
| ITEMADICIONADO | Integer |  | Item Adicionado  |  |
| PESOADICIONADO | Integer |  | Peso Adicionado  |  |
| PESOREMOVIDO | Float |  | Peso Removido |  |
| RUPTURA | Integer |  | Ruptura |  |
| DESISTENCIA | Integer |  | Desistência |  |
| VLREDICAOCESTA | Integer |  | Valor Edição Cesta |  |
| CESTAFINAL | Float |  | Cesta Final |  |
| TXENTREGAPEDIDO | Float |  | Taxa de Entrega do Pedido |  |
| PAGOCLIENTE | Float |  | Pago Cliente |  |
| SUBSIDIO | Float |  | Subsidio |  |
| TAXAEXTRAENTREGA | Float |  | Taxa Extra Entrega |  |
| TAXAENTREGAIFOOD | Float |  | Taxa Entrega Ifood |  |
| TAXAANTECIPACAO | Float |  | Taxa Antecipação |  |
| TAXAADQUIRENCIA | Float |  | Taxa Adquirencia |  |
| TAXAADQUIRENCIABENEFICIOS | Float |  | Taxa Adquirencia Beneficios |  |
| TOTALTAXAADQUIRENCIA | Float |  | Total Taxa Adquirencia |  |
| PCTCOMISSAO | Integer |  | PCT Comissão |  |
| COMISSAOPEDIDO | Float |  | Comissão Pedido |  |
| COMISSAOENTREGAFACIL | Integer |  | Comissão Entrega Fácil |  |
| COMISSAOCATALOGODIGITAL | Float |  | Comissão Catalogo Digital |  |
| COMISSAOTAKEOUT | Float |  | Comissão Takeout |  |
| TOTALCOMISSAO | Float |  | Total Comissão |  |
| REEMBOLSOIFOODBENEFICIOS | Float |  | Reembolso Ifood Beneficios |  |
| TAXAEXTRAPEDIDO | Float |  | Taxa Extra Pedido |  |
| CARREGAMENTO | Integer |  | Carregamento |  |
| REEMBOLSOTAXAADQUIRENTE | Float |  | Reembolso Taxa Adquirente |  |
| REEMBOLSOTAXAANTECIPACAO | Float |  | Reembolso Taxa Antecipação |  |
| REEMBOLSOTAXAPEDIDO | Float |  | Reembolso Taxa Pedido |  |
| TOTALREEMBOLSOCOMISSAO | Float |  | Total Reembolso Comissao |  |
| TOTALVALORREPASSE | Float |  | Total Valor Repasse |  |
| TOTALCANCELAMENTOPARCIAL | Integer |  | Total Cancelamento Parcial |  |
| MOTIVOCANCPARCIALABERTO | String |  | Motivo Cancelamento Parcial Aberto |  |
| TOTALCANCELAMENTO | Integer |  | Total Cancelamento |  |
| MOTIVOCANCTOTALABERTO | String |  | Motivo Cancelamento Total Aberto |  |
| TOTALREEMBOLSO | Float |  | Total Reembolso |  |
| MOTIVOREEMBOLSO | String |  | Motivo Reembolso |  |
| TOTALOCORRENCIA | Integer |  | Total Ocorrencia |  |
| MOTIVOOCORRENCIA | String |  | Motivo Ocorrência |  |
| TOTALLOGISTICA | Integer |  | Total Logistíca |  |
| TOTALCARREGAMENTO | Integer |  | Total Carregamento |  |
| TOTALREBILLAGEMMANUAL | Integer |  | Total Rebillagem Manual |  |
| CODIGOINTERNOLOJA | String |  | Código Interno Loja |  |
| CODFICHA | String |  | Código Ficha |  |
| PEDIDOIFOOD | Integer |  | Pedido Ifood |  |
| LINKSMR | String |  | Link Smr |  |
| EMISSAO | String |  | Emissão |  |
| ENTREGA | String |  | Entrega |  |
| LOJAIFOOD | Integer |  | Loja Ifood |  |
| IDGRUPOLOJA | String |  | Id Grupo Loja |  |
| DOCLOJA | String |  | Doca Loja |  |
| LOJA | String |  | Loja |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| DATAPREVISTA | String |  | Data Prevista |  |
| PERIODID | Integer |  | Periodid |  |
| EMAILLIST | String |  | Email List |  |
| DT | String |  | DATA |  |
| MERCHANTID | String |  | Comerciante Id |  |

## AD_BAIXASKOIN — Baixas Koin
Campos: 31

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |
| NUFINNOVO | Integer |  | Novo Número Único Financeiro |  |
| CODCTABCOINT | Integer |  | Conta de Baixa |  |
| TIPTRANS | String |  | Tipo de Transação |  |
| LIBERACAO | String |  | Liberação |  |
| NUFINSPLIT | Integer |  | NUFINSPLIT |  |
| NROPEDIDO | String |  | Pedido |  |
| VLRORIG | String |  | Valor Original |  |
| NUNOTA | Integer |  | Número Único |  |
| MSGTIPTRANS | String |  | Mensagem do Tipo de Transação |  |
| TIPODEPROCESSAMENTO | String |  | Tipo de Processamento |  |
| IDREFTRANSACAO | String |  | Id Referência da Transação |  |
| MOEDA | String |  | Moeda |  |
| VLRDESDOB | Float |  | Valor do Desdobramento |  |
| SERVKOIN | String |  | Serviços Koin |  |
| DTCRIACAO | String |  | Data Criação |  |
| PARCELA | String |  | Parcela |  |
| DTTRANSF | String |  | Data de Transferência |  |
| CNPJ | String |  | CNPJ |  |
| NUMNOTA | Integer |  | Número Nota |  |
| DTPROCESSAMENTO | DateTime |  | Data do Processamento |  |
| TOTALPARCELA | String |  | Total de Parcelas |  |
| IDTRANSACAO | String |  | Id da Transação |  |
| DTOPERACAO | String |  | Data Operação |  |
| NUFIN | Integer |  | Número Único Financeiro |  |
| COMERCIO | String |  | Comércio |  |
| VLRDIF | Float |  | Valor da Diferença |  |
| VLRPARCELA | String |  | Valor da Parcela |  |
| VLRTOTAL | String |  | Valor Total |  |
| CODTIPTRANS | String |  | Código do Tipo de Transação |  |

## AD_BAIXASPAGARME — Baixas Pagarme
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPOPERACAO | String |  | Tipo da Operação |  |
| IDOPERACAO | String |  | ID da Operação |  |
| DESCROPERACAO | String |  | Descrição da Operação |  |
| IDTRANSACAO | String |  | ID da Transação |  |
| PARCELA | String |  | Parcela |  |
| METODODEPAGAMENTO | String |  | Método de Pagamento |  |
| ENTRADABRUTA | String |  | Entrada Bruta |  |
| SAIDABRUTA | String |  | Saída Bruta |  |
| TAXAOPERACAO | String |  | Taxa de Operação |  |
| TAXAANTECIPACAO | String |  | Taxa de Antecipação |  |
| TAXATOTAL | String |  | Taxa Total da Operação |  |
| ENTRADALIQUIDA | String |  | Entrada Líquida |  |
| SAIDALIQUIDA | String |  | Saída Líquida |  |
| NROPEDIDO | String |  | Pedido |  |
| LIBERACAO | String |  | Liberação |  |
| DTPROCESSAMENTO | DateTime |  | Data do Processamento |  |
| TIPODEPROCESSAMENTO | String |  | Tipo de Processamento |  |
| NUNOTA | Integer |  | Número Único |  |
| NUMNOTA | Integer |  | Número Nota |  |
| CODCTABCOINT | Integer |  | Conta de Baixa |  |
| VLRDIF | Float |  | Valor da Diferença |  |
| VLRDESDOB | Float |  | Valor do Desdobramento |  |
| NUFIN | Integer |  | Número Único Financeiro |  |
| NUFINNOVO | Integer |  | Novo Número Único Financeiro |  |
| NUFINSPLIT | Integer |  | NUFINSPLIT |  |
| DTOPERACAO | String |  | Data da Operação |  |

## AD_BIBONIFAJUSTES — BI - Bonificação / Ajustes
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| ENTSAI | String |  | Entrada / Saida |  |
| CODEMP | Integer |  | Empresa |  |
| NUNICO | Integer |  | Nro. Unico |  |
| CODTIPOPER | Integer |  | Cód. Top |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| CODPROD | Integer |  | Cód. Produto |  |
| DESCRPROD | String |  | Descrição Produto |  |
| DTLANC | Date |  | Dt. Lançamento |  |
| DEBITO | Float |  | Débito |  |
| CREDITO | Float |  | Crédito |  |
| DESCRCTA | String |  | Descrição da Conta |  |
| VALOR_TOTAL | Float |  | Valor Total |  |
| DTNEG | Date |  | Dt Negociação |  |
| QTDE | Float |  | Quantidade |  |
| TIPO | String |  | Tipo |  |

## AD_BICUSTOFIXOMARKETING — BI Custo Fixo Marketing
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODNAT | Integer |  | Cód. Natureza |  |
| DESCRNAT | String |  | Natureza |  |
| DTNEG | Date |  | Dt. Negociação |  |
| VLRNOTA | Float |  | Vlr. Nota |  |
| CODTIPOPER | Integer |  | Cód. Top |  |
| DESCROPER | String |  | Decrição da TOP |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## AD_BIGASTOEMBALAGENS — BI - Gastos com Embalagem
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| NUNOTA | Integer |  | Nro. Unico |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODTIPOPER | Integer |  | Cód. Top |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| CODPROD | Integer |  | Cód. Produto |  |
| DESCRPROD | String |  | Descrição Produto |  |
| DTENTSAI | Date |  | Dt. Entrada ou Saida |  |
| VALOR_TOTAL | Float |  | Vlr. Total |  |
| DESCROPER | String |  | Descrição da TOP |  |
| DTNEG | Date |  | Dt. Negociação |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## AD_BIOUTRASRECDESP — Bi - Outras Rec / Desp
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| NUNICO | Integer |  | Nro. Único |  |
| CODTIPOPER | Integer |  | Cód. TOP |  |
| CONTA | String |  | Conta Contábil |  |
| DTMOV | Date |  | Dt. Movimento |  |
| DOCUMENTO | Integer |  | Documento |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| DEBITO | Float |  | Débito |  |
| CREDITO | Float |  | Crédito |  |
| SALDO | Float |  | Saldo |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| HISTORICO | String |  | Historico |  |
| DESCRCONTA | String |  | Descrição da Conta |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODCTACTB | Integer |  | Cód. Reduzido |  |
| NUMLANC | Integer |  | Nro. Lançamento |  |
| SALDOINICIAL | Float |  | Saldo Inicial |  |
| NUMLOTE | Integer |  | Num. Lote |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| SERIENOTA | String |  | Serie Nota |  |
| CONCILIADO | String |  | Conciliado |  |

## AD_BIREALIZADOCONTRIB — Realizado Contribuição
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| CODCTACTB | Integer |  | Conta Contábil |  |
| CODTIPOPER | Integer |  | Cód. Top |  |
| CODTIPOPERCONT | Integer |  | Cód. Top Cont |  |
| SERIENOTA | String |  | Serie Nota |  |
| CODEMP | Integer |  | Cód. Empresa |  |
| NUMNOTA | Integer |  | Num. Nota |  |
| CONTA | String |  | Conta |  |
| DESCRICAOCONTA | String |  | Descr. Conta |  |
| REFERENCIA | Date |  | Referencia |  |
| NUMLANC | Integer |  | Nro. Lançamento |  |
| NUMDOC | Integer |  | Nro. Documento |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| NUMLOTE | Integer |  | Nro. Lote |  |
| PARCEIRO | Integer |  | Parceiro |  |
| NOMEPARCEIRO | String |  | Nome Parceiro |  |
| RAZAOSOCIAL | String |  | Razão Social |  |
| HISTORICO | String |  | Historico |  |
| DTMOV | Date |  | Dt. Movimento |  |
| TIPLANC | String |  | Tipo Lançamento |  |
| CONCILIADO | String |  | Conciliado |  |
| SALDOINICIAL | Float |  | Saldo Inicial |  |
| DEBITO | Float |  | Debito |  |
| CREDITO | Float |  | Credito |  |
| SALDO | Float |  | Saldo |  |
| NUNICO | Integer |  | Nro. Unico |  |

## AD_CADASTROPET — Cadastro de Pets
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| EMAIL | String |  | Email |  |
| CODPET | Integer |  | Código do Pet |  |
| RACA | String |  | Raça |  |
| NOMEPET | String |  | Nome do Pet |  |
| SEXO | String |  | Sexo | `M`=Macho `F`=Fêmea |
| CASTRADO | String |  | Castrado? | `S`=Sim `N`=Não |
| NASCIMENTO | Date |  | Data do Nascimento |  |
| PORTE | String |  | Porte Físico | `M`=Magro `I`=Ideal `S`=Sobrepeso |
| PESO | Float |  | Peso |  |
| ESPECIE | String |  | Espécie | `C`=Cachorro `G`=Gato `A`=Ave `R`=Roedor |

## AD_CADPETS — Cadastro de Pets
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPET | Integer |  | Codigo |  |
| NOME | String |  | Nome |  |
| PESO | Float |  | Peso |  |
| CODRACA | Integer |  | Raça |  |
| NASCIMENTO | Date |  | Nascimento |  |
| PORTE | String |  | Porte do pet |  |
| OBSERVACAO | String |  | Observação e cuidados especiais |  |
| ESPECIE | Integer |  | Especie do pet |  |
| GENERO | String |  | Gereno do animal | `Masculino`=MASCULINO `Feminino`=FEMININO |
| PELO | String |  | Pelagem do animal | `Curto`=CURTO `Longo`=LONGO `Medio`=MEDIO |
| CASTRADO | String |  | Animal é castrado? | `S`=Sim `N`=Não |
| OBITO | String |  | Óbito? | `S`=Sim `N`=Não |
| COR | String |  | Cor do Animal | `Bicolor`=Bicolor `Tricolor`=Tricolor `Tigrado`=Tigrado `Areia`=Areia `Marrom`=Marrom_(+14)_ |
| CODPARC | Integer |  | Cód. Parceiro |  |

## AD_CADRACA — Cadastro de Raça
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODRACA | Integer |  | Raça |  |
| TIPO | String |  | Tipo | `1`=Cachorro `2`=Gato `4`=Peixe `5`=Roedor `6`=Coelho_(+3)_ |
| DESCRICAO | String |  | Descrição |  |

## AD_CAIXA_MAX — TABLE AD_CAIXA_MAX
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DATAABERTURA | DateTime |  | Max. Dt. Abertura |  |
| DATAFECHAMENTO | DateTime |  | Max. Dt. Fechamento |  |
| DHACAO | DateTime |  | Dt. Ação |  |
| CODUSUR | Integer |  | Vendedor |  |
| NUMCARMANIF | String |  | Nr. Carregamento |  |
| NUMLACRE | Integer |  | Nr. Lacre |  |
| TOTALDESPESAS | Integer |  | Max. Tot. Despesas |  |
| TOTALRECEBIMENTOS | Integer |  | Max. Tot. Receitas |  |
| TOTALDEPOSITOS | Integer |  | Max. Tot. Depositos |  |
| NUCAIXA | Integer |  | Nr. Caixa Sankhya |  |
| ACAO | Integer |  | Ação | `Exclusão`=3 `Iserção`=1 `Atualização`=2 |
| CODPRESTACAOCONTAC | String |  | Max. Id Caixa |  |
| ID | Integer |  | ID |  |
| DTFECHAMENTO | DateTime |  | Dt. Fechamento Sk. |  |
| DTABERTURA | DateTime |  | Dt. Abertura Sk. |  |

## AD_CAMPANHA — Cadastro de campanhas
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINI | Date |  | Data de Início |  |
| DTFIM | Date |  | Data final |  |
| VENDEDOR | Integer |  | Código de Local de Venda |  |
| ATIVO | String |  | Campanha Ativa? | `S`=Sim `N`=Não |
| SITUACAOCAMPANHA | String |  | Situação da Campanha |  |
| CODIGO | C |  | Código da Campanha |  |
| CODPROD | Integer |  | Código do Produto da Campanha |  |
| DESCRCAMPANHA | String |  | Descrição da Campanha |  |
| CODCAMPANHA | Integer |  | ID da Campanha |  |

## AD_CASHBACK — CASHBACK
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Numero Unico |  |
| VISIVEL | String |  | VISIVEL | `S`=Sim `N`=Não |
| TIPOLANCAMENTO | String |  | TIPO DE LANCAMENTO | `C`=CREDITO `D`=DEBITO |
| EMAIL | String |  | EMAIL |  |
| STATUS | String |  | STATUS |  |
| PEDIDOMKT | String |  | Pedido Mkt |  |
| QTDTENTATIVA | Integer |  | Qtd. Tentativa |  |
| VALOR | Float |  | VALOR |  |

## AD_CATATRIBUTOS — Atributos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCAT | Integer |  | Codigo |  |
| CODIGO | Integer |  | Codigo Atributo |  |
| DTALTER | DateTime |  | Dt Alteração |  |

## AD_CATEGORIEMGL — CATEGORIEMGL
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCATEGORIA | Integer |  | Cod. Categoria |  |
| CODCATEGORIAPAI | Integer |  | CODCATEGORIA pai |  |
| GRAU | Integer |  | Grau |  |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| INTEGRADO | String |  | Integrado Magalu? | `S`=Sim `N`=Não |
| INTEGRADOEXT | String |  | Integrado Magalu Extrema? | `N`=Não `S`=Sim |
| DESCRICAO | String |  | Descrição |  |

## AD_CATEGORIES — Categorias Mestras (Espécies)
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCATEG | String |  | Cód. Categoria |  |
| DESCRCATEG | String |  | Descrição |  |

## AD_CATEGPROD — Categorias (Produto)
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCATEG | String |  | Cód. Categoria |  |
| CODPROD | Integer |  | Código |  |

## AD_CATSITE — Categoria Site
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCAT | Integer |  | Codigo |  |
| DESCRICAO | String |  | Descrição |  |
| GRAU | Integer |  | Grau |  |
| ANALITICO | String |  | Analítico | `S`=Sim `N`=Não |
| GOOGLEPRODUCT | Integer |  | Google Product |  |
| DTALTER | DateTime |  | Dt Alteração |  |
| ANIMAL | String |  | Animal |  |
| DECRVTEX | String |  | Descrição Vtex |  |
| TITULOVTEX | String |  | Titulo Vtex |  |
| CODCATPAI | Integer |  | CODCAT pai |  |

## AD_CATSITEPROD — Categoria de Site
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODCAT | Integer |  | Cod Categoria |  |
| CODPROD | Integer |  | Código |  |

## AD_CAUSARESPONSAVEL — CAUSARESPONSAVEL
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Código |  |
| RESPONSAVEL | String |  | Responsável | `1`=SAC `2`=Logística `3`=Comercial `4`=Compras |
| CAUSA | String |  | Causa |  |

## AD_CENTRALPRECO — Central de Precificação
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODUSU | Integer |  | Usuário de Inserção |  |
| DTVIGOR | Date |  | Data Vigor |  |
| DTALTER | DateTime |  | Data Alteração |  |

## AD_CENTRALPRECOV2 — Central de Precificação V2
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DTALTER | DateTime |  | Data Alteração |  |
| CODUSU | Integer |  | Usuário de Inserção |  |
| DTVIGOR | Date |  | Data Vigor |  |

## AD_CHARGEBACK — Controle de Chargeback
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro. Único |  |
| NOMEPARC | String |  | Nome do Cliente |  |
| CPF | String |  | CPF |  |
| NUMNOTA | Integer |  | Nro. Nota Fiscal |  |
| DTNEG | DateTime |  | Data da Compra |  |
| TERMINAL | Integer |  | Terminal |  |
| RO | Integer |  | RO |  |
| CARTAO | String |  | Cartão |  |
| VALOR | Float |  | Valor |  |
| AUT | String |  | Aut. |  |
| NSU | Integer |  | NSU |  |
| TID | String |  | TID |  |
| DEFCIELO | String |  | Defesa Apresentada a Cielo | `S`=Sim `N`=Não |
| CONCLIENTE | String |  | Concedido ao Cliente | `N`=Não Concedido `S`=Concedido |
| RECCLEARSALE | String |  | Recorrido na Clearsale | `N`=Não `S`=Sim |
| REEMCLEARSALE | String |  | Reembolso Realizado pela Clearsale? | `N`=Não `S`=Sim |
| STATUS | String |  | Status | `C`=Pendente CX `F`=Pendente Financeiro `S`=Sem Pendência |
| PEDIDOMKTPLACE | String |  | Pedido |  |

## AD_CICLODOCADD — Documentos Adicionais
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| PEDIDO | String |  | Pedido |  |
| NUNOTA | Integer |  | Nr Unico |  |
| CODVEND | Integer |  | Vendedor |  |
| CODEMPDOC | Integer |  | Empresa Documento |  |
| MOTIVO | String |  | Motivo |  |
| LIBERACAO | String |  | Liberação | `L`=Liberado `N`=Negado `P`=Pendente |
| CODUSUINC | Integer |  | Usuario Inclusão |  |
| CODUSULIB | Integer |  | Usuario Liberação |  |
| DTINC | DateTime |  | Dh Inclusão |  |
| VALOR | Float |  | Valor |  |
| TIPMOV | String |  | Tipo de Movimento | `V`=Venda `P`=Pedido `D`=Devolução |
| CODTIPOPER | Integer |  | Tipo de Operação |  |

## AD_CICLOITENS — Itens
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| PEDIDO | String |  | Pedido |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODVEND | Integer |  | Vendedor |  |
| CODPROD | Integer |  | Produto |  |
| CODPRODSUB | Integer |  | Produto Substituto |  |
| QTDNEGSUB | Integer |  | Qtd Neg Substituto |  |
| QTDNEG | Float |  | Qtd Ned |  |

## AD_CICLOPEDSTATUSTRANSP — Status de Transporte
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| PEDIDO | String |  | Pedido |  |
| NUNOTA | Integer |  | NUNOTA |  |
| CODVEND | Integer |  | Vendedor |  |

## AD_CLASSIFICARFV — Conf. Código RFV
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CANAL | String |  | CANAL |  |

## AD_CONCILIACKONCILI — Conciliação Koncili
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| OBSERVACAO | C |  | Observação |  |

## AD_CONFCOMPRA — Configurações para Compra
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| LEADTIME | Integer |  | Leadtime |  |
| FORALINHA | String |  | Fora de Linha | `S`=Sim `N`=Não |
| DIAESTOQ | Integer |  | Dias de Estoque |  |
| PERIODOANALISE | Integer |  | Periodo em dias para Análise de Giro |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| CADENCIA | Integer |  | Cadencia |  |
| VALIDAR_WMS | String |  | Validação WMS | `S`=Sim `N`=Não |
| OBSERVACAO | String |  | Observação |  |
| CODPROD | Integer |  | Código |  |

## AD_CONFIGMELI — Configuração MELIazine
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| RECDESP | Integer |  | Receita/Despesa |  |
| CODTIPOPER | Integer |  | Cód.Tipo Operação |  |
| CODCTABCOINT | Integer |  | Código da conta bancária |  |
| CODCENCUS | Integer |  | Código |  |
| CODBCO | Integer |  | Cód. Banco |  |
| CODNAT | Integer |  | Cód. Natureza |  |

## AD_CONFKONCILI — Configuração Koncili
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODEMP | Integer |  | CODIGO EMPRESA |  |
| MARKETPLACE | String |  | MARKETPLACE |  |
| CODNAT | Integer |  | NATUREZA |  |
| CODCTACTB | Integer |  | CONTA BANCARIA |  |
| CODTIPOPER | Integer |  | TIPO OPERAÇÃO |  |
| CODTIPOPERBAIXA | Integer |  | TIPO OPERAÇÃO BAIXA |  |
| RECDESP | String |  | RECEITA DESPESA | `1`=RECEITA `-1`=DESPESA `0`=AMBOS |
| ACAO | String |  | AÇÃO | `D`=Baixa Devolução `B`=Baixa Venda Integral `P`=Venda Integral ou Parcial `V`=Compoe Venda `N`=Nada_(+4)_ |
| CODPARC | Integer |  | Parceiro |  |
| CLASSIFICACAO | String |  | Classificação |  |
| CODCENCUS | Integer |  | Centro de Resultado |  |
| DESCRICAO | String |  | Descrição |  |
| DATABAIXA | String |  | Data da Baixa | `1`=Busca Data RELEASEDDATE `2`=Busca Data de Baixa Informada |
| CODTIPTIT | Integer |  | Tipo de Titulo |  |
| TIPO | String |  | TIPO |  |

## AD_CONFMKP — Configuração de Vendedor Marketplace
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAB | Integer |  | Código Tabela de Preço |  |
| TAXA | Float |  | Taxa Fixa (R$) |  |
| CODEMP | Integer |  | Código Empresa |  |
| CODVEND | Integer |  | Vendedor |  |
| PROMOCAO | Float |  | Promoção do Canal de Venda (%) |  |
| REBATE | Float |  | Rebate Canal de Venda (%) |  |
| COMISSAO | Float |  | Comissão Canal Venda (%) |  |

## AD_CONFMKPPROD — Comissão Produto
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAB | Integer |  | Código Tabela de Preço |  |
| CODPROD | Integer |  | Código do Produto |  |
| PROMOCAO | Float |  | Promoção do Produto |  |
| REBATE | Float |  | Rebate do Produto (%) |  |
| COMISSAO | Float |  | Comissão do Produto (%) |  |

## AD_CONTROLETESOURARIA — Controle de tesouraria da loja
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTESOURARIA | Integer |  | Numero do relatorio de tesouraria |  |
| CENTAVOS5 | Float |  | R$0,05 |  |
| CENTAVOS10 | Float |  | R$0,10 |  |
| CENTAVOS25 | Float |  | R$0,25 |  |
| CENTAVOS50 | Float |  | R$0,50 |  |
| REAL1 | Float |  | R$1,00 |  |
| REAL2 | Float |  | R$2,00 |  |
| REAL5 | Float |  | R$5,00 |  |
| REAL10 | Float |  | R$10,00 |  |
| REAL20 | Float |  | R$20,00 |  |
| DEBITO | Float |  | Transações de débito |  |
| CREDITO | Float |  | Transações de Crédito |  |
| REMESSADODIA | Float |  | Remessa do dia |  |
| DIAANTERIOR | Float |  | Saldo do dia Anterior |  |
| FINALPARABANCO | Float |  | Saldo final para Banco |  |
| OBS | C |  | Observações Gerais |  |
| DATAFECHAMENTO | Date |  | Data de Fechamento |  |

## AD_COTACAOINTELIPOST — Cotação Intelipost
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nr. Unico |  |
| IDCOTACAO | Integer |  | ID Cotação |  |
| IDMETODO | Integer |  | Id Metodo |  |
| VLRFRETE | Float |  | Valor Frete |  |
| DIAS_ENTREGA | Integer |  | Dias Para Entrega |  |
| METODO | String |  | Metodo |  |

## AD_CREDENCIALSHOPEE — CREDENCIALSHOPEE
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| PARTNERID | String |  | PARTNERID |  |
| SECRETKEY | String |  | Secretkey |  |
| SHOPID | String |  | ShopId |  |

## AD_CUSTOMKP — Custo Marketplace
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAB | Integer |  | Código Tabela de Preço |  |
| REFERENCIA | DateTime |  | Referência |  |
| COMISSAO | Float |  | Comissão do Canal de Venda |  |
| TAXA | Float |  | Taxa Fixa |  |

## AD_CUSTOPROD — Custo do Produto
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CUSTOGERENCIAL | Float |  | Custo Médio Gerencial |  |
| CUSTOCOMICMS | Float |  | Custo Médio Com ICMS |  |
| CUSTOSEMICMS | Float |  | Custo Médio Sem ICMS |  |
| CODEMP | Integer |  | Código Empresa |  |
| VENDEDOR | String |  | Vendedor |  |
| CUSTOMEDIO | Float |  | Custo Médio |  |
| CODPROD | Integer |  | Código |  |

## AD_CX — Customer Experience
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUREF | Integer |  | Referencia |  |
| CPF | String |  | CPF |  |
| EMAIL | String |  | EMAIL |  |
| TELEFONE | String |  | TELEFONE |  |
| LOGRADOURO | String |  | LOGRADOURO |  |
| NUMERO | String |  | NUMERO |  |
| BAIRRO | String |  | BAIRRO |  |
| CIDADE | String |  | CIDADE |  |
| DTCADASTRO | Date |  | DATA CADASTRO |  |
| TICKET | Float |  | TICKET MÉDIO |  |
| ULTCOMPRA | Date |  | ULTIMA COMPRA |  |
| RECENCIA | Integer |  | RECENCIA |  |
| FREQUENCIA | Integer |  | FREQUENCIA |  |
| VALOR | Float |  | VALOR |  |
| CODRFV | String |  | CÓDIGO RFV |  |
| SEGMENTO | String |  | SEGMENTAÇÃO |  |
| CODPARC | Integer |  | CODPARC |  |
| NOME | String |  | NOME |  |

## AD_DEMATE — Interações de atendimento
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUATEND | Integer |  | Número do atendimento |  |
| NUDEMANDA | Integer |  | Número único da demanda |  |
| CODTEC | Integer |  | Técnico |  |
| DHATEND | DateTime |  | Data/Hora |  |
| ACOES | C |  | Ações realizadas |  |
| NOMETEC | String |  | Técnico |  |

## AD_DEMCAB — Demandas e Projetos (cab)
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUDEMANDA | Integer |  | Número único da demanda |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| STATUS | Integer |  | Status da demanda | `2`=Em Análise `3`=Aguardando Validação `1`=Não analisada `4`=Suspenso `5`=Concluída_(+1)_ |
| TITULO | String |  | Título da demanda |  |
| DESCRICAO | String |  | Descrição detalhada |  |
| CODTEC | Integer |  | Código do técnico |  |
| DTPRAZO | Date |  | Prazo proposto |  |
| OBS | String |  | Observações |  |
| PRIORIDADE | Integer |  | Prioridade | `2`=Média `0`=Não definida `1`=Alta `5`=Urgente `3`=Baixa_(+1)_ |
| ANEXO | Boolean |  | Anexo |  |
| USUARIODISC | String |  | Canal Discord |  |
| TIPO | String |  | Tipo: | `2`=REQUER DESENVOLVIMENTO `0`=INCIDENTE `1`=REQUISIÇÃO |
| AUTOR | String |  | Autor |  |
| LOCAL | String |  | Local |  |
| CATEGORIA | String |  | Categoria |  |
| URGENCIA | String |  | Urgência |  |
| SETOR | String |  | Setor |  |
| DTVALIDACAO | DateTime |  | Data Liberação p Validação |  |
| DTSUSPENSO | DateTime |  | Data de Suspensão |  |
| DTANALISE | DateTime |  | Data de Analise |  |
| DTENTREGA | DateTime |  | Data de Entrega |  |
| DTSOLICITACAO | DateTime |  | Data da Solicitação |  |
| CODUSUAGVALID | Integer |  | Cod. Usu. Ag. Validação |  |
| CODUSUFINALIZA | Integer |  | Cod. Usu. Finaliza. |  |
| DTREABERTURA | DateTime |  | Data de Reabertura |  |
| DTSLA | DateTime |  | Data Limite SLA |  |

## AD_DEMSAS — PesquisaSatisfacao
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RESOLVIDO | String |  | resolvido |  |
| SATISFACAO | String |  | satisfacao |  |
| SUGESTAO | String |  | sugestao |  |
| NUDEMANDA | Integer |  | Número único da demanda |  |

## AD_DEMTEC — Técnicos de TI
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTEC | Integer |  | Código do técnico |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| NOME | String |  | Nome |  |

## AD_DESCRRFV — DESCRICAO RFV
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| INDICE | Integer |  | INDICE |  |
| CANAL | String |  | CANAL |  |
| LEGENDA | String |  | LEGENDA | `RENTABILIZAÇÃO`=RENTABILIZAÇÃO `RETENÇÃO`=RETENÇÃO `RECONQUISTA`=RECONQUISTA `ATIVAÇÃO`=ATIVAÇÃO `FIDELIZAÇÃO`=FIDELIZAÇÃO |
| CODIGO | String |  | CODIGO |  |

## AD_DETALHEPRODMKP — Detalhe por Produto
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Produto |  |
| VENDEDOR | Integer |  | Vendedor |  |
| METAMARGEM | Float |  | Meta Margem |  |

## AD_DETDESTRATOR — Detalhe
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| SEQUENCIA | Integer |  | Sequencia |  |

## AD_DEVITE — Produtos Devolução
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTADEV | Integer |  | Nr. Unico Devolução |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| NUNOTA | Integer |  | Nro. Único |  |
| CODLOCAL | Integer |  | Local |  |
| DESCRPROD | String |  | Descrição Produto |  |
| QTDNEG | Integer |  | Qtd  |  |

## AD_DEVOLUCOES — Controle de Devoluções
Campos: 106

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| VENDEDOR | String |  | Vendedor |  |
| PEDIDOMKTPLACE | String |  | Pedido Marketplace |  |
| NUNOTA | Integer |  | Nro. Único |  |
| NUMNOTA | Integer |  | Nro. Nota |  |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CLIENTE | String |  | Nome do Cliente |  |
| CPF | String |  | CPF |  |
| TELEFONE | String |  | Telefone |  |
| EMAIL | String |  | E-mail |  |
| UF | String |  | Estado |  |
| CEP | String |  | CEP |  |
| CIDADE | String |  | Cidade |  |
| MOTIVODEV | String |  | Motivo da Devolução | `D`=Devolucao `C`=Cancelamento `T`=Troca |
| OBSDEVOLUCAO | String |  | Detalhamento da Devolução |  |
| RESARCTRANSP | String |  | Solicitado Ressarcimento da Transportadora | `N`=Não Aplicável `S`=Sim |
| ANEXO | Boolean |  | Foto |  |
| ESTORNO | String |  | Forma de Estorno | `M`=Estorno Marketplace `P`=Pix `B`=Boleto Bancário `C`=Cartão de Crédito `S`=Crédito no Site_(+1)_ |
| TIPREVERS | String |  | Tipo de Reversa | `D`=Domiciliar `T`=Coleta Transportadora `P`=Postagem `N`=Não aplicável |
| CODRASTREIO | String |  | Código de Postagem ou Coleta |  |
| SITESTORNO | String |  | Estorno Realizado | `S`=Sim `N`=Não |
| DTESTORNO | Date |  | Data do Estorno |  |
| COMPROVANTE | Boolean |  | Comprovante (Imagem) |  |
| SITRESARCTRANSP | String |  | Ressarcimento Realizado Pela Transportadora | `A`=Não Aplicável `S`=Sim `N`=Não |
| DESCRPROD | String |  | Descrição do Produto |  |
| VLRNOTA | Float |  | Valor Total do Pedido |  |
| VLRDEVOL | Float |  | Valor da Devolução |  |
| NUMDEVOL | Integer |  | NF Devolução |  |
| NUDEVOL | Integer |  | Nro. Único Devolução |  |
| DTFATURDEV | DateTime |  | Data Emissão NF Devolução  |  |
| DTDEV | DateTime |  | Data Solicitação da Devolução |  |
| ENDERECO | String |  | Endereço |  |
| BAIRRO | String |  | Bairro |  |
| STATUSREENVIO | String |  | Reenvio Realizado? | `S`=Sim `N`=Não |
| DETALHEESTORNO | String |  | Detalhamento do Estorno |  |
| COMPLEMENTO | String |  | Complemento |  |
| NUMEND | String |  | Número |  |
| NUMDEVOLREENVIO | Integer |  | NF Devolução Reenvio |  |
| NUDEVOLREENVIO | Integer |  | Nro. Único Devolução Reenvio |  |
| DTFATURDEVREENVIO | DateTime |  | Data Emissão NF Devolução Reenvio |  |
| STATUSDEVOL | String |  | Devolução Realizada? | `S`=Sim `N`=Não |
| VLRDEVOLREENVIO | Float |  | Valor da Devolução Reenvio |  |
| VLRNOTAREENVIO | Float |  | Valor Total do Reenvio |  |
| VLRESTORNO | Float |  | Valor Estorno |  |
| NFREENVIO | Integer |  | NF Reenvio |  |
| DESCRPRODREENVIO | String |  | Descrição do Reenvio |  |
| STATUSPENDENTE | String |  | Status | `S`=Pendente CX `D`=Pendente Logística / Estorno `L`=Pendente Logística `F`=Pendente Estorno `C`=Pendente CX / Logística_(+2)_ |
| VLRNFREENVIO | Float |  | Valor da NF de Reenvio |  |
| SITVLRESTORNO | Float |  | Valor para Estorno |  |
| RETORNOPRODUTO | String |  | Haverá Retorno do Produto? | `N`=Não `S`=Sim |
| SITVLRNOTA | Float |  | Valor da Nota |  |
| NUREENVIO | Integer |  | Nro. Único Reenvio |  |
| SEGSTATUSREENVIO | String |  | Segundo Reenvio Realizado? | `S`=Sim `N`=Não |
| NUSEGDEVOLREENVIO | Integer |  | Nro. Único Segunda Devolução Reenvio |  |
| NUMSEGDEVOLREENVIO | Integer |  | NF Devolução Segundo Reenvio |  |
| VLRSEGDEVOLREENVIO | Float |  | Valor da Segunda Devolução Reenvio |  |
| VLRNOTASEGREENVIO | Float |  | Valor Total do Segundo Reenvio |  |
| DTFATURDEVSEGREENVIO | DateTime |  | Data Emissão NF Devolução Segundo Reenvio |  |
| DESCRPRODSEGREENVIO | String |  | Descrição do Segundo Reenvio |  |
| DEVPARCIAL | String |  | Devolução Parcial? | `S`=Sim `N`=Não |
| NUSEGREENVIO | Integer |  | Nro. Único Segundo Reenvio |  |
| NFSEGREENVIO | Integer |  | NF Segundo Reenvio |  |
| VLRNFSEGREENVIO | Float |  | Valor da NF de Segundo Reenvio |  |
| TRANSPORTADORA | String |  | Transportadora |  |
| CODUSUALTER | Integer |  | Código Usuário Alteração |  |
| COMPROVANTEANEXO | Boolean |  | Comprovante (Anexo) |  |
| PAGAMENTOVIALINK | String |  | Pagamento Via Link de Pagamento | `N`=Não `S`=Sim |
| CODINSERUSU | Integer |  | Código Usuário Inserção  |  |
| NRFATURA | Integer |  | Número de Fatura |  |
| VLRRESSARC | Float |  | Valor para Ressarcimento  |  |
| SITCLIENTE | String |  | Situação Cliente |  |
| CODEMP | Integer |  | Codigo da empresa |  |
| DTLIMITEDEV | Date |  | Data limite da devolução |  |
| STATUSDEV | String |  | Status Devolução |  |
| CONTDEV | Integer |  | Contagem de dias  |  |
| DTALTER | Date |  | Data e Hora de alteração |  |
| COLETAREALIZADA | String |  | Coleta Realizada | `Sim`=Sim `Não`=Não |
| DEVOLUCAOCANCELADA | String |  | Devolução Cancelada | `Sim`=Sim `Não`=Não |
| SKUTRATADOS | String |  | Sku Tratados |  |
| RESSARCIMENTOPARCIAL | String |  | Ressarcimento Parcial | `S`=Sim `N`=Não |
| SKUDEVOLVIDOS | String |  | Skus ja devolvidos |  |
| VLRRESSARCIMENTOPARCIAL | Float |  | Valor do Ressarcimento Parcial |  |
| TIPMOV | String |  | Tipo de movimentação | `V`=Venda `P`=Pedido |
| CAUSA | String |  | Causa da devolucao | `6`=Causas Naturais `7`=Cliente não Localizado `10`=Devolução sem Especificação da Transportadora `11`=Divergente do Anunciado `21`=Garantia de Satisfacao_(+31)_ |
| REIVINDICACAOAMAZON | String |  | Reivindicação Amazon | `S`=Sim `N`=Não |
| SETORRESPONSAVEL | String |  | Setor responsável pela tratativa | `LOGISTICA`=Logistica `COMPRAS`=Compras `CX/SAC`=CX/SAC `VENDAS`=Vendas `TRANSPORTE`=Transporte |
| REIVINDICAOAAZ | String |  | Reivindicação de A a Z | `NA`=Não aplicavel `S`=sim |
| BLOQUEIOTRANSP | String |  | Solicitado Bloqueio Transportadora? | `S`=Sim `N`=Não |
| MOTIVORECUSARESSARC | String |  | Motivo Recusa Ressarcimento |  |
| RESPONSAVEL | String |  | Setor Responsável 1 |  |
| CODMOTIVO | Integer |  | Cód. Motivo |  |
| RESPONSAVELMOT | String |  | Responsável Motivo |  |
| STATUSFINALIZADOR | String |  | Status Finalizador | `6`=Abertura de chamado marketplace `1`=Perda financeira `2`=Ressarcimento pendente `3`=Ressarcimento em negociação `4`=Ressarcimento agendado_(+10)_ |
| DEPACAO | String |  | Departamento ação | `CM`=Comercial `CT`=Controladoria `T`=Transportes `CP`=Compras `F`=Financeiro_(+2)_ |
| FINALIZADOR | String |  | Status Validação (Campo do Lindolfo) | `S`=Sim `N`=Não |
| METODO | String |  | Metodo |  |
| STATUSTRASNP | String |  | Status Transporte |  |
| PROTOCOLOFOR | String |  | Protocolo Fornecedor |  |
| NOTAREEMBOLSOTRANSP | Integer |  | Nota de Reembolso Transportadora |  |
| DEVBAIXAFIN | String |  | Devolução com Financeiro Baixado | `S`=Sim `N`=Não |
| TIPOENTREGA | String |  | Tipo de Entrega | `F`=Entrega Full `P`=Entrega Própria |
| PERDAFINANCEIRA | String |  | Perda Financeira? | `S`=Sim `N`=Não |
| IMPORTADOFINAN | String |  | Importado Financeiro | `S`=Sim `N`=Não |
| GARANTIASATISF | String |  | Garantia de Satisfação? | `S`=Sim `N`=Não |
| ANEXOGARANTIA | Boolean |  | Anexo Garantia de Satisfação |  |
| DETLIBERACAO | String |  | Detalhe da Liberação |  |
| NROFATURASATISF | Integer |  | Número da Fatura |  |

## AD_DOCAEMPTRANF — Empresa Transferencia
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Codigo |  |
| CODEMP | Integer |  | Empresa |  |
| PRIORIDADE | Integer |  | Prioridade |  |

## AD_DOCASPLIT — Docas do Split Vtex
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Codigo |  |
| CODEMP | Integer |  | Empresa |  |
| GERATRANF | String |  | Gera Transferencia | `S`=Sim `N`=Não |
| ESTOQUEMIN | Integer |  | Estoque Minimo |  |
| CENTRODISTRIBUICAO | String |  | Centro de Distribuição Wake |  |
| DOCA | String |  | Doca |  |

## AD_DTDETRATORES — Detalhe
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | CODPARC |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| VALOR | Float |  | VALOR |  |
| TICKET | Float |  | TICKET |  |
| PERIODO | Integer |  | PERIODO |  |
| PEDIDOS | Integer |  | PEDIDOS |  |

## AD_EMAILS — Configurador de Emails
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| ASSUNTO | String |  | Assunto |  |
| EMAIL | String |  | Email |  |
| DESCREMAIL | String |  | Descrição |  |

## AD_ENDERECOEST — Endereço de Estoque
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| DESCRICAO | String |  | Descrição |  |
| ENDERECO | String |  | Endereço |  |

## AD_ENDERECOESTOQUE — Endereço de Estoque
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| CODPROD | Integer |  | SKU |  |
| PREDIO | Integer |  | PREDIO |  |
| ANDAR | Integer |  | ANDAR |  |
| APARTAMENTO | Integer |  | APARTAMENTO |  |
| DTALTER | DateTime |  | Data de alteração |  |
| DEPARTAMENTO | String |  | DEPARTAMENTO | `F`=Farmacia `M`=Mezanino `P`=Porta Palet `C`=Cestos |
| RUA | String |  | RUA |  |
| REFERENCIA | String |  | EAN |  |
| DTATUALIZACAO | DateTime |  | Data de atualização |  |

## AD_ESTOQUEAMAZON — View Estoque Amazon
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Prod |  |
| QUANTIDADE | Integer |  | Quantidade |  |

## AD_ESTOQUEAMAZONEXTREMA — ESTOQUEAMAZONEXTREMA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Prod |  |
| QUANTIDADE | Integer |  | Quantidade |  |

## AD_ESTOQUEAMERICANAS — ESTOQUEAMERICANAS
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Prod |  |
| QUANTIDADE | Integer |  | Quantidade |  |

## AD_ESTOQUECOMPONENTES — Estoque/Componente
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPRODFILHO | Integer |  | Cód. Componente |  |
| DESCRPRODFILHO | String |  | Descrição Produto  |  |
| CODEMP | Integer |  | Empresa |  |
| LOCAL | Integer |  | Cód. Local |  |
| ESTOQUE | Integer |  | Estoque |  |
| RESERVADO | Integer |  | Reservado |  |
| CODPROD | Integer |  | Código |  |

## AD_ESTOQUEEX — Estoque EX
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| ESTOQUE | Integer |  | Estoque |  |

## AD_ESTOQUESJC — Estoque SJC
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |

## AD_ESTOQUESKYHUB — ESTOQUESKYHUB
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| ESTOQUE | Integer |  | ESTOQUE |  |

## AD_ESTOQUESKYHUBEXTREMA — ESTOQUESKYHUBEXTREMA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| ESTOQUE | Integer |  | Estoque |  |

## AD_EXPCPU — AD_EXPCPU
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | nunota |  |

## AD_EXPSUP — AD_EXPSUP
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIAORIG | Integer |  | SEQUENCIAORIG |  |
| CODPRODORIG | Integer |  | CODPRODORIG |  |
| USOPROD | String |  | USOPROD |  |
| ORIGPROD | String |  | ORIGPROD |  |
| CODPROD | Integer |  | CODPROD |  |
| QTDNEG | Float |  | QTDNEG |  |
| NUNOTA | Integer |  | NUNOTA |  |
| CODVOL | String |  | CODVOL |  |
| RESERVA | String |  | RESERVA |  |
| ATUALESTOQUE | Integer |  | ATUALESTOQUE |  |
| QTDN | Integer |  | QTDN |  |
| CODLOCALPADRAO | Integer |  | CODLOCALPADRAO |  |
| CUSMEDICM | Float |  | CUSMEDICM |  |
| VLRTOT | Float |  | VLRTOT |  |
| CUSTO_PRINC | Float |  | CUSTO_PRINC |  |
| VLRUNIT | Float |  | VLRUNIT |  |
| VLRTOT_SUG | Float |  | VLRTOT_SUG |  |

## AD_FECHBENEFICIO — Fechamento Beneficio
Campos: 14

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| REFERENCIA | Date |  | Referecia |  |
| DTFIM | Date |  | Periodo Final |  |
| NUNOTA | Integer |  | Nr. Unico Apuração |  |
| VLRBASECRED | Float |  | Vlr. Icms a Pagar (Apuração Normal) |  |
| VLRCREDITO | Float |  | Vlr. Crédito |  |
| VLRDEBITO | Float |  | Vlr. Débito |  |
| VLRCREDAPUR | Float |  | Crédito a Estornar - NFE |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DHALTER | DateTime |  | Data Alteração |  |
| VLRBENEFDEV | Float |  | Beneficio Devolução Venda |  |
| VLRCREDPRESUM | Float |  | Vlr. Credito Presumido |  |
| VLRICMSAGARBENEF | Float |  | Vlr. ICMS a Pagar c/ Beneficio |  |
| DTINI | Date |  | Periodo Inicial |  |

## AD_FINPEDIDO — Detalhamento Financeiro Integração
Campos: 34

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| NUNOTA | Integer |  | Nro. Único |  |
| ID | String |  | id |  |
| PAYMENTSYSTEM | String |  | paymentSystem |  |
| PAYMENTSYSTEMNAME | String |  | paymentSystemName |  |
| VALUE | Float |  | value |  |
| INSTALLMENTS | Integer |  | installments |  |
| REFERENCEVALUE | Float |  | referenceValue |  |
| CARDHOLDER | String |  | cardHolder |  |
| CARDNUMBER | String |  | cardNumber |  |
| FIRSTDIGITS | String |  | firstDigits |  |
| LASTDIGITS | String |  | lastDigits |  |
| CVV2 | String |  | cvv2 |  |
| EXPIREMONTH | String |  | expireMonth |  |
| EXPIREYEAR | String |  | expireYear |  |
| URL | String |  | url |  |
| GIFTCARDID | String |  | giftCardId |  |
| GIFTCARDNAME | String |  | giftCardName |  |
| GIFTCARDCAPTION | String |  | giftCardCaption |  |
| REDEMPTIONCODE | String |  | redemptionCode |  |
| GROUP1 | String |  | group1 |  |
| TID | String |  | tid |  |
| DUEDATE | String |  | dueDate |  |
| CONNECTORRESPONSES | String |  | connectorResponses |  |
| GIFTCARDPROVIDER | String |  | giftCardProvider |  |
| GIFTCARDASDISCOUNT | String |  | giftCardAsDiscount |  |
| KOINURL | String |  | koinUrl |  |
| ACCOUNTID | String |  | accountId |  |
| PARENTACCOUNTID | String |  | parentAccountId |  |
| BANKISSUEDINVIDENTNUMBER | String |  | bankIssuedInvIdentNumber |  |
| BANKISSUEDINVIDENTNUMBFORM | String |  | bankIssuedInvIdentNumbForm |  |
| BANKISSUEDINVOICEBARCODENUMBER | String |  | bankIssuedInvoiceBarCodeNumber |  |
| BANKISSUEDINVOICEBARCODETYPE | String |  | bankIssuedInvoiceBarCodeType |  |
| BILLINGADDRESS | String |  | billingAddress |  |

## AD_FREQUENCIA — FREQUENCIA
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | CODIGO |  |
| CANAL | String |  | CANAL |  |
| VLRMAX | Integer |  | VLR. MAXIMO |  |
| VLRMIN | Integer |  | VLR. MINIMO |  |

## AD_FURO — Controle de Furo e Ruptura de Estoque
Campos: 54

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| ACAO | String |  | Ação | `V`=Cancelamento Direcionado por Vendas `X`=Compra Externa/Concorrente `C`=Cancelamento Total da Compra `E`=Envio Parcial `T`=Troca por Produto Similar_(+1)_ |
| CONTATOCLIENTE | String |  | Contato com o Cliente | `S`=Sim `N`=Não |
| CODPROD | Integer |  | Código Produto |  |
| CODVEND | Integer |  | Código Vendedor |  |
| DTINCLUSAO | DateTime |  | Data de Inclusao |  |
| DTPREVCHEGADA | DateTime |  | Data de Previsão de Chegada |  |
| DTNEG | DateTime |  | Data Negociação |  |
| DETALHAMENTOCX | String |  | Detalhamento CX |  |
| CODEMP | Integer |  | Empresa |  |
| ENTREGAPRODUTO | String |  | Entrega do Produto Agendado? | `N`=Não `S`=Sim |
| ESTOQUE | Integer |  | Estoque |  |
| MOTIVOFURO | String |  | Motivo |  |
| SITUACAOCONF | String |  | NF de Devolução Emitida ou Cancelamento da NF Realizada? | `D`=NF de Devolução Emitida `C`=Cancelamento da NF Realizada |
| NUMNOTA | Integer |  | Nota Fiscal |  |
| NUNOTA | Integer |  | Número Único |  |
| NUNOTACOMPRA | Integer |  | Nro Único Entrega Pendente |  |
| PEDIDOMKTPLACE | String |  | Pedido Marketplace |  |
| PENDENTEENTREGA | String |  | Pendente de Entrega? | `N`=Não `S`=Sim |
| QTDNEG | Integer |  | Quantidade Negociada |  |
| RESERVA | Integer |  | Reserva |  |
| SKUSIMILAR | Integer |  | SKU Similar |  |
| DETALHAMENTOCOMPRAS | String |  | Detalhamento Compras |  |
| ACAOREALIZADA | String |  | Ação Realizada | `S`=Sim `N`=Não |
| STATUS | String |  | Pendente | `LC`=Logística/Compras `C`=Compras `LS`=Logística/CX `L`=Logística `F`=Sem Pendencia_(+1)_ |
| CODUSUINSERC | Integer |  | Usuário de Inserção |  |
| CODUSUALTER | Integer |  | Usuário de Alteração |  |
| SITUACAOCLIENTE | String |  | Situação do Cliente |  |
| ACAOCOMPRAS | String |  | Ação Compras | `I`=Ruptura Indústria `S`=Sem Previsão de Compra `P`=Compra Planejada `O`=Outros `R`=Compra Realizada_(+1)_ |
| PENDENTEFATURAMENTO | String |  | Pendente Faturamento |  |
| HISTORICOEST | Integer |  | Historico estoque |  |
| DTDOWNSTK | DateTime |  | Data de download de estoque sankhya |  |
| DTUPSTK | DateTime |  | Data de upload de estoque plataforma |  |
| DTDOWNSTKVTEX | DateTime |  | Data de download de estoque Vtex extrema sankhya |  |
| DTDOWNSTKVTEX2 | DateTime |  | Data de download de estoque Vtex sjc sankhya |  |
| DTDOWNSTKVTEX3 | DateTime |  | Data de download de estoque Vtex loja fisica sankhya |  |
| DTUPSTKVTEX1 | DateTime |  | Data de upload de estoque vtex extrema |  |
| DTUPSTKVTEX2 | DateTime |  | Data de upload de estoque vtex sjc |  |
| DTUPSTKVTEX3 | DateTime |  | Data de upload de estoque vtex loja fisica |  |
| QTDSTKVTEX2 | Integer |  | Quantidade de estoque Vtex sjc |  |
| QTDSTKVTEX1 | Integer |  | Quantidade de estoque Vtex extrema |  |
| QTDSTKVTEX3 | Integer |  | Quantidade de estoque vtex loja fisica |  |
| QTDSTK | Integer |  | Quantidade de estoque temapi |  |
| ASSINATURA | String |  | Id contrato da assinatura |  |
| ESTOQUETESTE | Integer |  | Estoque Teste Paola |  |
| DTSTATUSTRANSPORTE | String |  | Dh. Status Transporte |  |
| STATUSTRANSPORTE | String |  | Status Transporte |  |
| AD_QTDEST | Integer |  | Qtd. Est. Momento |  |
| VLRTOTITEM | Float |  | Vlr. Total Item |  |
| ENVIADOCADASTRO | String |  | Enviado p/ Cadastro | `SIM`=Sim `NAO`=Não |
| DHALTER | DateTime |  | Dh Alteração |  |
| VALIDADOTI | String |  | Validado T.I | `S`=Sim `N`=Não |
| TIPOOCORRENCIA | String |  | Tipo Ocorrência |  |
| AJUSTEREALIZADO | String |  | Ajuste de Estoque Realizado | `N`=Não `S`=Sim |

## AD_GENERALIZACAOCOMPONENTE — Generalização Item
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODPRODPAI | Integer |  | Código Produto (Fórmula) |  |
| DESCRPRODPAI | String |  | Descrição do Produto |  |
| CODPROD | Integer |  | Código |  |

## AD_GERACAOGIA — Gerar GIA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDGIA | Integer |  | Nro.unico |  |
| OBSERVACAO | String |  | Descrição |  |

## AD_GESTAOINTEGRACAO — Gestão de integração
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| TIPO | String |  | Tipo de integracao | `S`=Status `P`=Pedidos `R`=Produtos |
| CATEGORIA | String |  | Categoria de Integração | `F`=Faturado `P`=Preço `R`=Entregue `T`=Estoque `E`=Enviado_(+1)_ |
| NOMEVIEW | String |  | View |  |
| TABELA | String |  | Tabela |  |
| CODEMP | Integer |  | Código da Empresa |  |
| TIPOTEMAPI | String |  | Tipo TemApi | `2`=Dispatched Vtex `3`=Delivered Vtex `5`=GetNuetiq `6`=SentCnova `1`=Tracking Vtex_(+2)_ |
| CONSULTATEMAPI | C |  | Consulta na TemApi |  |
| CODEMKTP | Integer |  | Codigo Vendedor da TemApi |  |
| CANAL | String |  | Canal de venda |  |

## AD_GESTAOPROJETOS — Gestão de projetos
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Código do Projeto |  |
| STATUS | String |  | Status Atual | `S`=TAP Não enviada `N`=Não Iniciado `A`=Alteração de Escopo `T`=Em andamento (Terceiros) `E`=Em Andamento_(+4)_ |
| DESCRICAO | C |  | Descrição do Projeto |  |
| SETOR | String |  | Setor Solicitante | `COMPRAS`=Compras `ADMINISTRATIVO`=Administrativo `CADASTRO`=Cadastro `TI`=TI `ECOMMERCE`=E-commerce_(+13)_ |
| PRIORIDADE | String |  | Prioridade | `A`=Alta `B`=Baixa `M`=Média `U`=Urgente |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| HORASPREVISTAS | Integer |  | Horas Previstas |  |
| DTINI | Date |  | Data Inicio |  |
| DTPREVISTA | Date |  | Data Prevista de Conclusão |  |
| DTFIM | Date |  | Data de Conclusão |  |
| RESPONSAVEL | String |  | Responsável de Execução |  |
| RESPONSAVELAPR | String |  | Responsável Aprovação |  |
| ANEXO | Boolean |  | Anexo do Processo |  |
| ANEXOTAP | Boolean |  | Anexo TAP |  |
| OBS | C |  | Observações |  |
| ANEXOESCOPO | Boolean |  | Anexo Escopo |  |
| TIPOPROJ | String |  | Tipo | `E`=Erro `N`=Novo `M`=Melhoria |
| MES | String |  | Mês | `05`=Maio `03`=Março `04`=Abril `06`=Junho `10`=Outubro_(+7)_ |
| ANO | Integer |  | Ano | `2023`=2023 `2024`=2024 `2025`=2025 |
| HORASEXECUTADAS | Integer |  | Horas Executadas |  |
| GUT | Boolean |  | Matriz GUT |  |
| TITULOPROJETO | String |  | Titulo do Projeto |  |

## AD_GESTAOPROJETOSATIVIDADES — Cronograma e Atividades
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID da Atividade |  |
| CODIGO | Integer |  | Código do Projeto |  |
| REGISTRO | Integer |  | Registro de Horas |  |
| RESPONSAVEL | String |  | Responsável |  |
| DTPREVISAO | Date |  | Data de Previsão |  |
| DTCONCLUSAO | Date |  | Data de Conclusão |  |
| CODIGOS | C |  | Códigos Atrelados |  |
| OBS | C |  | Observações |  |
| ATIVIDADE | String |  | Atividade |  |
| DEPENDENCIA | Integer |  | Dependência |  |
| TIPO | String |  | Tipo de Atividade | `T`=Treinamento `E`=Ação ERP `A`=Arquitetura `D`=Desenvolvimento `V`=Validação_(+3)_ |

## AD_GIASP — GIA - SP
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| CODEMP | Integer |  | Empresa |  |
| ARQTXT | C |  | Arquivo Texto da GIA-SP |  |

## AD_GIASPREG01 — GIA - SP - REG 01
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| REF | Date |  | Referencia |  |
| SEQ | Integer |  | SEQ |  |
| TIPODOCTO | String |  | 02 - Tipo do Documento |  |
| DATAGERACAO | String |  | 03 - Data da Geração do Arquivo (AAAAMMDD) |  |
| HORAGERACAO | String |  | 04 - Hora da Geração do Arquivo (HHMMSS) |  |
| VERSAOFRONTEND | String |  | 05 - Versão do sistema GIA |  |
| VERSAOPREF | String |  | 06 - Versão do Layout do Pré-Formatado NG |  |
| Q05 | String |  | 07 - Quantidade de Registros 05 |  |
| TXT | String |  | Pré visulização do texto da Linha |  |
| CR | String |  | 01 - Código do registro |  |

## AD_GIASPREG05 — GIA - SP - REG 05
Campos: 25

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| CODEMP | Integer |  | Empresa |  |
| SEQ | Integer |  | SEQ |  |
| IE | String |  | 2 - Inscrição Estadual |  |
| CNPJ | String |  | 3 - CNPJ |  |
| CNAE | String |  | 4 - CNAE |  |
| REGTRIB | String |  | 5 - Regime Tributário |  |
| REFERENCIA | String |  | 6 - Referência Ano e Mês da GIA |  |
| REFINIC | String |  | 7 - Referência Inicial |  |
| TIPO | String |  | 8 - Tipo da GIA |  |
| MOVIMENTO | String |  | 9 - Indica se Houve movimento |  |
| TRANSMITIDA | String |  | 10 - Indica se o Documento Fiscal já foi transmitido |  |
| SALDOCREDPERIODOANT | String |  | 11 - Saldo credor do período anterior |  |
| SALDOCREDPERIODOANTST | String |  | 12 - Saldo credor do período anterior ST |  |
| ORIGEMSOFTWARE | String |  | 13 - Identificação do Software |  |
| ORIGEMPREDIG | String |  | 14 - Origem do arquivo NG |  |
| ICMSFIXPER | String |  | 16 - ICMS Fixado para o Período |  |
| CHAVEINTERNA | String |  | 17 - Chave Interna |  |
| Q07 | String |  | 18 - Quantidade de Registros Q07 |  |
| Q10 | String |  | 19 - Quantidade de Registros Q10 |  |
| Q20 | String |  | 20 - Quantidade de Registros Q20 |  |
| Q30 | String |  | 21 - Quantidade de Registros Q30 |  |
| Q31 | String |  | 22 - Quantidade de Registros Q31 |  |
| TXT | String |  | Pré visulização do texto da Linha |  |
| CR | String |  | 1 - Código do registro |  |

## AD_GIASPREG07 — GIASPREG07
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| ID | Integer |  | ID |  |
| CODEMP | Integer |  | Empresa |  |
| TXT | String |  | TXT |  |
| PROPRIAOUST | String |  | PropriaOuST |  |
| DATA | String |  | Data |  |
| IMPOSTO | String |  | Imposto |  |

## AD_GIASPREG10 — GIA - SP - REG 10
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| SEQ | Integer |  | SEQ |  |
| CODEMP | Integer |  | Empresa |  |
| VALORCONTABIL | String |  | 3 - Valor Contábil |  |
| BASECALCULO | String |  | 4 - Base de Cálculo |  |
| IMPOSTO | String |  | 5 - Imposto |  |
| ISENTASNAOTRIB | String |  | 6 - Isentas e não Trib. |  |
| OUTRAS | String |  | 7 - Outras |  |
| IMPOSTORETIDOST | String |  | 8 - Imposto Retido por ST |  |
| IMPOSTOSUBSTITUTOST | String |  | 9 - Imposto Retido Substituto |  |
| IMPRETSUBSTITUIDO | String |  | 10 - Imposto Retido por substituição |  |
| OUTROSIMPOSTOS | String |  | 11 - Outros Impostos |  |
| Q14 | String |  | 12 - Quantidade de registros 14 |  |
| TXT | String |  | Pré visulização do texto da Linha |  |
| CR | String |  | 1 - Código do Registro |  |
| CFOP | String |  | 2 - CFOP |  |

## AD_GIASPREG14 — GIA - SP - REG 14
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| CODEMP | Integer |  | Empresa |  |
| SEQ14 | Integer |  | SEQ14 |  |
| SEQ | Integer |  | SEQ |  |
| BASECALCULO | String |  | 2 - Base de Cálculo |  |
| VALORCONTABIL2 | String |  | 3 - Valor Contábil2 |  |
| BASECALCULO2 | String |  | 4 - Base de Cálculo2 |  |
| IMPOSTO | String |  | 5 - Imposto |  |
| OUTRAS | String |  | 6 - Outras |  |
| ICMSCOBRADOST | String |  | 8 - ICMS Cobrado por SubstituiçãoTributária |  |
| PETROLEOENERGIA | String |  | 9 - Petróleo e Energia quando ICMScobrado por Substituição Tributária |  |
| OUTROSPRODUTOS | String |  | 10 - Outros Produtos quando ICMScobrado por Substituição Tributária |  |
| BENEF | String |  | 11 - Indica se há alguma operaçãoBeneficiada por isenção de ICMS(ZFM/ALC) |  |
| Q18 | String |  | 12 - Quantidade de Registros 18 |  |
| UF | String |  | UF |  |
| TXT | String |  | Arquivo para TXT |  |
| VALORCONTABIL | String |  | 1 - Valor Contábil |  |

## AD_GIASPREG18 — GIA - SP - REG 18
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| SEQ18 | Integer |  | SEQ18 |  |
| CODEMP | Integer |  | Empresa |  |
| SEQ | Integer |  | SEQ |  |
| SEQ14 | Integer |  | SEQ14 |  |
| DATA | String |  | Data |  |
| VALOR | String |  | Valor |  |
| CNPJDEST | String |  | CNPJ DESTIN. |  |
| MUNICIPIODEST | String |  | MUNICIPIO DESTIN. |  |
| TXT | String |  | Texto para Arquivo |  |
| NF | String |  | Nota fiscal |  |

## AD_GIASPREG20 — GIA - SP - REG 20
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| CODEMP | Integer |  | Empresa |  |
| SEQ | Integer |  | SEQ |  |
| VALOR | String |  | Valor |  |
| PROPRIAOUST | String |  | PROPRIA ou ST |  |
| FLEGAL | String |  | Fundamentação legal |  |
| OCORRENCIA | String |  | Ocorrência |  |
| Q25 | String |  | Q25 |  |
| Q26 | String |  | Q26 |  |
| Q27 | String |  | Q27 |  |
| Q28 | String |  | Q28 |  |
| TXT | String |  | Texto para arquivo |  |
| CODSUBITEM | String |  | Código do SubItem |  |

## AD_GIASPREG25 — GIA - SP - REG 25
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| REF | Date |  | Referencia |  |
| SEQ | Integer |  | SEQ |  |
| CODEMP | Integer |  | Empresa |  |
| SEQ25 | Integer |  | SEQ25 |  |
| VALOR | String |  | Valor |  |
| TXT | String |  | Texto para arquivo |  |
| IE | String |  | IE |  |

## AD_GRUPOICMS — Grupo de ICMS
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GRUPOICMS | String |  | Grupo de ICMS |  |
| ORIGEM | String |  | Origem | `1`=Produto `2`=Parceiro `3`=Grupo de produto |
| DETALHE | String |  | Detalhe |  |
| DESCRICAO | String |  | Descrição |  |

## AD_GRUPOICMSDETALHE — Detallhe Registros
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| GRUPOICMS | String |  | Grupo de ICMS |  |
| CODIGO | Integer |  | Codigo |  |
| ORIGEM | String |  | Origem | `1`=Produto `2`=Parceiro `3`=Grupo de produto |
| NCM | String |  | NCM |  |
| DESCRPROD | String |  | Descrição |  |

## AD_HISTCOMUN — Historico de Comunicacão
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| PEDIDO | String |  | Pedido |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| CODVEND | Integer |  | Vendedor |  |

## AD_HISTESTOQ — Historico Estoque
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DATA | Date |  | Data |  |
| DHALTER | DateTime |  | Dh Alteração |  |
| HISTORICO | String |  | Historico |  |

## AD_HISTVENDA — Historico de Venda
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | Parceiro |  |
| DATAPRIMEIRA | Date |  | Data Primeira Venda |  |
| RAZAOSOCIAL | String |  | Razão Social |  |

## AD_HORASPROJETOS — Horas Projeto
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MES | String |  | Mês | `03`=Março `10`=Outubro `07`=Julho `09`=Setembro `02`=Fevereiro_(+7)_ |
| INICIOMES | Date |  | Data início |  |
| FINALMES | Date |  | Data final |  |
| DIASUTEIS | Integer |  | Dias úteis |  |

## AD_IMAGENS — SHOPEEIMG
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIMG | Integer |  | Id Imagem |  |
| IDSHOPEE | Integer |  | IDSHOPEE |  |
| ID | Integer |  | ID |  |
| CODPROD | Integer |  | Código |  |
| URLSHOPEE | C |  | Url retorno (Shopee) |  |
| REQUESTID | String |  | REQUESTID |  |
| ERRORDESC | String |  | Erro Upload Imagem Shopee |  |
| URL | C |  | Url |  |

## AD_IMAGENSDOOZY — Imagens Doozy
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| CODPROD | Integer |  | Código |  |

## AD_IMOBILIZADO — Controle de Imobilizado
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIMOB | Integer |  | Codigo do Imobilizado |  |
| CODUSU | Integer |  | Codigo do Usuario |  |
| DTCOMPRA | DateTime |  | Data da Compra |  |
| NOTARELACIONADA | Integer |  | NF Relacionada à compra |  |
| OBS | C |  | Obs do Equipamento |  |
| DTATUALIZACAO | DateTime |  | Ultima Atualizacao |  |
| LOCAL | String |  | Local do aparelho | `Loja Aquarius`=Loja Aquarius `Extrema`=Extrema `Outro`=Outro `Pet2Pet`=Pet2Pet `Eldorado`=Eldorado_(+3)_ |
| CANAL | String |  | Canal da Compra |  |
| SETOR | String |  | Setor |  |
| MARCA | String |  | Marca  |  |
| MODELO | String |  | Modelo |  |
| USUALTERCAO | Integer |  | Usuario Alteracao |  |
| MAC | String |  | Endereço de Mac |  |
| SERIAL | String |  | Serial Number |  |
| STATUS | String |  | Status do equipamento | `USADO`=USADO `QUEBRADO`=QUEBRADO `OBSOLETO`=OBSOLETO `DANIFICADO`=DANIFICADO `NOVO`=NOVO |
| VLR | Float |  | Valor do imobilizado |  |
| PROCESSADOR | String |  | Processador |  |
| MEMORIA | String |  | Memoria |  |
| HD | String |  | HD |  |
| EQUIPAMENTO | String |  | Equipamento | `Impressora`=Impressora `Notebook`=Notebook `Leitor de Preco`=Leitor de Preco `Celular`=Celular `Monitor`=Monitor_(+5)_ |

## AD_IMOBILIZADOSTATUS — Status de Imobilizado
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDSTATUS | Integer |  | Id do Status |  |
| CODIMOB | Integer |  | Codigo do Imobilizado |  |
| CODUSUFINAL | Integer |  | Cod Usuario Final |  |
| DTTROCA | DateTime |  | Data da Troca do equipamento |  |
| DTMANUTENCAO | DateTime |  | Data de envio manutencao |  |
| MOTIVO | String |  | Motivo Manutencao |  |
| RESOLVIDO | String |  | Foi resolvido? | `S`=Sim `N`=Não |
| OBSMANUTENCAO | C |  | Obs da Manutencao |  |
| LOCALMANUTENCAO | String |  | Local da Manutencao |  |
| CODUSUINI | Integer |  | Cod Usuario Inicial |  |

## AD_IMPMELI — Importação Repasse Meli
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| ROWNUMBER | Integer |  | Rownumber |  |
| SOURCE | String |  | Source_ID |  |
| CODMKT | String |  | Cód. Integração |  |
| TIPO | String |  | Tipo |  |
| STATUS | String |  | Status |  |
| VLRCRED | Float |  | Valor Crédito |  |
| VLRDEB | Float |  | Valor Débito |  |
| VLRBRUTO | Float |  | Valor Bruto |  |
| VLRCOMISSAO | Float |  | Valor Comissão |  |
| VLRCUSFIN | Float |  | Valor Custo Financeiro |  |
| VLRCUSENVIO | Float |  | Valor Custo Envio |  |
| VLRIMPOSTO | Float |  | Valor Impostos |  |
| VLRDESC | Float |  | Valor Desconto |  |
| TOTPARCELA | Integer |  | Total Parcelas |  |
| TIPPAG | String |  | Método de Pagamento |  |
| DHIMPORT | DateTime |  | Dt/Hr Importação |  |
| NUNOTA | Integer |  | N° Único Nota |  |
| PENDENCIA | String |  | Pendência | `S`=Sim `N`=Não |
| LIQUIDADO | String |  | Liquidado | `S`=Sim `N`=Não |
| RESOLVIDO | String |  | Resolvido | `S`=Sim `N`=Não |
| DTPREV | Date |  | Data Prevista Pgto. |  |

## AD_IMPMELICAB — Importação MELI Cabeçalho
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| DHIMPORT | DateTime |  | Dt/Hr Importação |  |

## AD_IMPMELICAN — Importação MELI Cancelados
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ROWNUMBER | Integer |  | Rownumber |  |
| ID | String |  | ID |  |
| DTPED | Date |  | Dt. Pedido |  |
| VALOR | Float |  | Valor |  |
| TIPO | String |  | Tipo |  |
| CODMKT | String |  | Cód. Integração |  |

## AD_IMPMELIDESP — Importarção Meli Despesa
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ROWNUMBER | Integer |  | ROWNUMBER |  |
| ID | String |  | ID |  |
| NUNOTA | Integer |  | NUNOTA |  |
| TIPO | String |  | TIPO |  |
| CODNAT | Integer |  | CODNAT |  |
| RECDESP | Integer |  | RECDESP |  |
| CODCTABCOINT | Integer |  | CODCTABCOINT |  |
| CODCENCUS | Integer |  | CODCENCUS |  |
| CODBCO | Integer |  | CODBCO |  |
| VALOR | Float |  | VALOR |  |
| CODMKT | String |  | CODMKT |  |

## AD_IMPMELIDEV — Importação MELI Devoluções
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMKT | String |  | CODMKT |  |
| ID | String |  | ID |  |
| DTPED | Date |  | Dt. Pedido |  |
| NUFIN | Integer |  | N° Único Fin. |  |
| VALOR | Float |  | Valor |  |
| VLRDESDOB | Float |  | Vlr. Financeiro |  |
| PENDENCIA | String |  | Pendência | `S`=Sim `N`=Não |
| DIFERENCA | Float |  | Diferença |  |
| LIQUIDADO | String |  | Liquidado | `S`=Sim `N`=Não |
| STATUS | String |  | Status |  |
| DHBAIXA | Date |  | Dt. Baixa |  |

## AD_IMPMELIDIS — Importação MELI Disputa
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| ROWNUMBER | Integer |  | Rownumber |  |
| DTPED | Date |  | Dt. Pedido |  |
| DTPREV | Date |  | Dt. Prevista |  |
| VALOR | Float |  | Valor |  |
| RESOLVIDO | String |  | Resolvido | `S`=Sim `N`=Não |
| CODMKT | String |  | Cód. Integração |  |

## AD_IMPMELIPEN — Importação MELI Pendências
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| ROWNUMBER | Integer |  | Rownumber |  |
| DTPED | Date |  | Dt. Pedido |  |
| DTPREV | Date |  | Dt. Prevista |  |
| VALOR | Float |  | Valor |  |
| TIPO | String |  | Tipo |  |
| RESOLVIDO | String |  | Resolvido | `S`=Sim `N`=Não |
| CODMKT | String |  | Cód. Integração |  |

## AD_IMPMELIVEN — Importação MELI Vendas
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| CODMKT | String |  | Cód. Integração |  |
| VALOR | Float |  | Valor |  |
| NUFIN | Integer |  | N° Único Fin. |  |
| VLRDESDOB | Float |  | Vlr. Financeiro |  |
| DHBAIXA | Date |  | Dt. Baixa |  |
| PENDENCIA | String |  | Pendência | `S`=Sim `N`=Não |
| LIQUIDADO | String |  | Liquidado? | `S`=Sim `N`=Não |
| DIFERENCA | Float |  | Diferença |  |
| STATUS | String |  | Status |  |
| VLRBAIXA | Float |  | Vlr. Baixa |  |
| ROWNUMBER | Integer |  | Rownumber |  |

## AD_IMPNSUCIELO — NSU - Financeiro e Contabil Cielo
Campos: 43

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUUNICO | Integer |  | Nr. Unico |  |
| TIPODELANCAMENTO | String |  | Tipo de Lançamento |  |
| DESCRICAO | String |  | Descrição |  |
| BANCO | String |  | Banco |  |
| AGENCIA | String |  | Agência |  |
| CONTA | String |  | Conta |  |
| ESTABELECIMENTO | String |  | Estabelecimento |  |
| DATADEPAGAMENTO | String |  | Dt. de Pagamento |  |
| DATADAVENDA | String |  | Dt. da venda |  |
| BANDEIRA | String |  | Bandeira |  |
| FORMADEPAGAMENTO | String |  | Forma de Pagamento |  |
| NUMERODAPARCELA | String |  | Número da parcela |  |
| QUANTIDADEDEPARCELAS | String |  | Quantidade de parcelas |  |
| NUMERODOCARTAO | String |  | Número do cartão |  |
| CODIGODATRANSACAO | String |  | Código da transação |  |
| TID | String |  | TID |  |
| CODIGODEAUTORIZACAO | String |  | Código de autorização |  |
| NSU | String |  | NSU |  |
| VALORBRUTO | String |  | Valor bruto |  |
| VALORLIQUIDO | String |  | Valor líquido |  |
| VALORCOBRADO | String |  | Valor cobrado |  |
| VALORPENDENTE | String |  | Valor pendente |  |
| VALORTOTAL | String |  | Valor total |  |
| RESUMODEOPERACAO | String |  | Resumo de Operação |  |
| CODIGODAVENDA | C |  | Código da venda |  |
| NUMERODAMAQUINA | String |  | Número da Máquina |  |
| PERIODOCONSIDERADO | String |  | Período considerado |  |
| NUMERODAOPERACAO | String |  | Número da operação |  |
| TAXADEANTECIPACAO | String |  | Taxa de antecipação |  |
| DHIMPORT | DateTime |  | Dt/H. Importação |  |
| NUNOTA | Integer |  | Nr. Unico da Nota |  |
| NRPEDIDO | String |  | Nr. Pedido |  |
| NUFIN | Integer |  | Nr. Unico Financeiro |  |
| LIBERACAO | String |  | Liberado |  |
| VLRDESDOB | Float |  | Valor Desdobramento |  |
| CODCTABCOINT | Integer |  | Conta Bancaria Baixada |  |
| NUFINNOVO | Integer |  | Nr. Unico Financeiro Criado |  |
| VLRDIF | Float |  | Vlr Diferença |  |
| DTPROCESSAMENTO | DateTime |  | Data de processamento |  |
| TIPODEPROCESSAMENTO | String |  | Tipo de processamento |  |
| NUMNOTA | Integer |  | Número da Nota |  |
| NUFINSPLIT | Integer |  | Número Financeiro Split |  |
| STATUS | String |  | Status |  |

## AD_IMPNSUPAGARME — NSU - Financeiro e Contábil
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUUNICO | Integer |  | Nr. Unico |  |
| STATUS | String |  | Status |  |
| AMOUNT_IN_CENTS | String |  | Amount_In_Cents |  |
| PAID_AMOUNT_IN_CENTS | String |  | Paid_Amount_In_Cents |  |
| INSTALLMENTS | String |  | Installments |  |
| REFUNDED_AMOUNT | String |  | Refunded_Amount |  |
| PAID_DATE | String |  | Paid_Date |  |
| CODE | String |  | Code |  |
| CURRENCY | String |  | Currency |  |
| PAYMENT_METHOD | String |  | Payment_Method |  |
| CREATED_DATE | String |  | Created_Date |  |
| CANCELED_DATE | String |  | Canceled_Date |  |
| NSU | String |  | NSU |  |
| TID | String |  | TID |  |
| ACQUIRER | String |  | Acquirer |  |
| ACQUIRER_RETURN_CODE | String |  | Acquirer_Return_Code |  |
| ACQUIRER_MESSAGE | String |  | Acquirer_Message |  |
| ACQUIRER_AUTHORIZATION_CODE | String |  | Acquirer_Authorization_Code |  |
| CARD_BRAND | String |  | Card_Brand |  |
| MASKED_CARD | String |  | Masked_Card |  |
| HOLDER_NAME | String |  | Holder_Name |  |
| EXPIRATION_DATE | String |  | Expiration_Date |  |
| NOSSO_NUMERO | String |  | Nosso_Numero |  |
| BAR_CODE | String |  | Bar_code |  |
| BOLETO_CREDIT_DATE | String |  | Boleto_Credit_Date |  |
| CUSTOMER_NAME | String |  | Customer_Name |  |
| CUSTOMER_DOCUMENT | String |  | Customer_Document |  |
| CUSTOMER_EMAIL | String |  | Customer_Email |  |
| METADATA | C |  | Metadata |  |
| PLATFORM | String |  | Platform |  |
| ANTIFRAUD_STATUS | String |  | Antifraud_Status |  |
| QR_CODE_URL | String |  | QR_Code_Url |  |
| EXPIRES_AT | String |  | Expires_At |  |
| TRANSACTION_ID | String |  | Transaction_Id |  |
| DHIMPORT | DateTime |  | Dt./H Importação |  |
| CHARGE_ID | String |  | Charge_Id |  |

## AD_IMPORTACAOPRECO — Importação de Preço
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPOIMPORTACAO | String |  | Tipo de Importação | `V`=Vendas `C`=Compras `E`=Ecommerce (Preço De) |
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |

## AD_IMPORTACAOPRECOV2 — Importação de Preço
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPOIMPORTACAO | String |  | Tipo de Importação | `V`=Vendas `C`=Compras `E`=Ecommerce (Preço De) |

## AD_IMPPEDCOMP — Importador de Pedido de Compra
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| DTALTER | Date |  | Data de Criação |  |
| NUNOTA | Integer |  | Número da Nota |  |
| CODUSU | Integer |  | Usuário Alteração |  |

## AD_IMPPLA — Importador Planilha
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| DATA | Date |  | Data |  |
| NUINSTANCIA | Integer |  | Núm. da Instância |  |
| ACAO | String |  | Ação | `I`=I - Insert `U`=U - Update |
| ARQUIVO | Boolean |  | Planilha (.XLS) |  |

## AD_IMPPLALOG — Log Planilha
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQLOG | Integer |  | Sequencia Log |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| STATUSLINHA | String |  | Status |  |
| OBSERVACAO | String |  | Observação |  |
| PK | String |  | Pk |  |
| LINHA | Integer |  | Linha |  |

## AD_IMPTXT — IMPTXT
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| ACAO | String |  | Ação | `U`=U - Update `I`=I - Insert |
| ARQUIVO | Boolean |  | Arquivo |  |
| DATA | Date |  | Data |  |

## AD_IMPZANTHUS — Impostos Zanthus
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| COFINS | Float |  | COFINS |  |
| COFINSCST | Integer |  | COFINSCST |  |
| PIS | Float |  | PIS |  |
| PISCST | Integer |  | PISCST |  |
| ICMS | Float |  | ICMS |  |
| ICMSCST | Integer |  | ICMSCST |  |
| ICMSBASE | Float |  | ICMSBASE |  |
| ICMSIVA | Float |  | ICMSIVA |  |
| CODPROD | Integer |  | Produto |  |

## AD_INSTANCIAS_MAXIMA — TABLE AD_INSTANCIAS_MAXIMA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| ID | Integer |  | ID |  |

## AD_INSTANCIA_ACAO_MAXIMA — TABLE AD_INSTANCIA_ACAO_MAXIMA
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUAAG | Integer |  | Ação Agendada |  |
| ID_INSTANCIA | Integer |  | Processo a ser executado |  |
| ID_LIGACAO | Integer |  | ID |  |

## AD_INTDDA — Interface DDA
Campos: 22

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CNPJEMP | String |  | CNPJ Empresa |  |
| NOMEEMP | String |  | Nome Empresa |  |
| VLRABATIM | Float |  | Vl Abatimento |  |
| CNPJSACADOR | String |  | CNPJ Sacador |  |
| CODBARRA | String |  | Codigo de Barra |  |
| DTARQUIVO | Date |  | Data Arquivo |  |
| CODEMP | Integer |  | Empresa |  |
| CNPJ | String |  | CNPJ Cedente |  |
| NOMECEDENTE | String |  | Nome Cedente |  |
| CODPARC | Integer |  | Parceiro |  |
| DTVENC | Date |  | Data Vencimento |  |
| VALOR | Float |  | Vl Título |  |
| NUMDOCTO | String |  | Nro Docto |  |
| DHINCLUSAO | DateTime |  | Dt Inclusão |  |
| CODUSUINC | Integer |  | Usuario Inclusão |  |
| DHALTER | DateTime |  | Dt Alteração |  |
| CODUSUALT | Integer |  | Usuario Alteração |  |
| ATUALIZADO | String |  | Atualizado | `S`=Sim `N`=Não |
| NUFIN | Integer |  | Nro Financeiro |  |
| DTEMISSAO | Date |  | Data Emissão |  |
| OBSERVACAO | String |  | Observaçao |  |
| SACADOR | String |  | Sacador |  |

## AD_INTSHI — INTELIPOSTSHIPMENT
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| VLRFRETE | Float |  | VLRFRETE |  |
| APELIDO | String |  | APELIDO |  |
| BH_CODEMKT | String |  | BH_CODEMKT |  |
| METODO | Integer |  | METODO |  |
| NOMECLIENTE | String |  | NOMECLIENTE |  |
| TELCLIENTE | String |  | TELCLIENTE |  |
| CPFCLIENTE | String |  | CPFCLIENTE |  |
| ENDERECOCLIENTE | String |  | ENDERECOCLIENTE |  |
| NUMEROCLIENTE | String |  | NUMEROCLIENTE |  |
| COMPLEMENTOCLIENTE | String |  | COMPLEMENTOCLIENTE |  |
| BAIRROCLIENTE | String |  | BAIRROCLIENTE |  |
| CIDADECLIENTE | String |  | CIDADECLIENTE |  |
| ESTADOCLIENTE | String |  | ESTADOCLIENTE |  |
| CEPCLIENTE | String |  | CEPCLIENTE |  |
| DEPOSITO | String |  | DEPOSITO |  |
| DEPOSITO_CPF | String |  | DEPOSITO_CPF |  |
| DEPOSITO_TEL | String |  | DEPOSITO_TEL |  |
| SERIE | String |  | SERIE |  |
| NUMNOTA | String |  | NUMNOTA |  |
| DTMOV | String |  | DTMOV |  |
| DTNEG | String |  | DTNEG |  |
| VLRNOTA | String |  | VLRNOTA |  |
| AD_DTPROMETIDA | String |  | AD_DTPROMETIDA |  |
| AD_DTPEDIDO | String |  | Data Entrega |  |
| EMAILCLIENTE | String |  | EMAILCLIENTE |  |
| DEPOSITO_CIDADE | String |  | DEPOSITO_CIDADE |  |
| DEPOSITO_ENDERECO | String |  | DEPOSITO_ENDERECO |  |
| DEPOSITO_CEP | String |  | DEPOSITO_CEP |  |
| DEPOSITO_ESTADO | String |  | DEPOSITO_ESTADO |  |
| DEPOSITO_NUMERO | String |  | DEPOSITO_NUMERO |  |
| PESOBRUTO | String |  | Peso Bruto |  |
| ESPESSURA | Float |  | Espessura |  |
| ALTURA | Float |  | Altura |  |
| LARGURA | Float |  | Largura |  |
| DIAMETRO | Float |  | Diametro |  |
| MAOPROPRIA | String |  | Mão Própria |  |
| VLRDECLARADO | Float |  | Valor Declarado |  |
| AVISORECEBIMENTO | String |  | Aviso Recebimento |  |
| USUARIOSIGEP | String |  | Usuário |  |
| SENHASIGEP | String |  | Senha |  |
| CDSERVICO | String |  | Cód Serviço | `40010`=SEDEX sem contrato `40045`=SEDEX a Cobrar, sem contrato `40126`=SEDEX a Cobrar, com contrato |
| INSCESTAD | String |  | INSCESTAD |  |
| DADOSNOTA | String |  | DADOSNOTA |  |
| EXTNUNOTA | String |  | EXTNUNOTA |  |
| CHAVENFE | String |  | CHAVENFE |  |

## AD_INTSHIITE — Intelipost Itens
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| SEQVOL | Integer |  | SEQVOL |  |
| PESOBRUTO | Float |  | PESOBRUTO |  |
| LARGURA | Float |  | LARGURA |  |
| ALTURA | Float |  | ALTURA |  |
| ESPESSURA | Float |  | ESPESSURA |  |
| QTDNEG | Integer |  | QTDNEG |  |
| VLRTOT | Float |  | VLRTOT |  |
| CODCFO | Integer |  | CODCFO |  |
| DESCRPROD | String |  | DESCRPROD |  |

## AD_INVOICESHOPEE — INVOICESHOPEE
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| NUNOTA | Integer |  | NUNOTA |  |
| ORDERID | String |  | ORDERID |  |
| DATAHORAOPERACAO | DateTime |  | DATAHORAOPERACAO |  |
| RESPONSEBODY | C |  | RESPONSEBODY |  |
| TYPE | String |  | TYPE |  |
| PICKUPTIMEID | String |  | PICKUPTIMEID |  |
| INITIENV | C |  | INITIENV |  |
| CODVEND | Integer |  | CODVEND |  |

## AD_ITEIMP — Itens Importados
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| NUNOTA | String |  | Número da Nota |  |
| ID | Integer |  | ID |  |
| UNIDADE | String |  | Tipo de Unidade |  |
| SALDOESTOQUE | Integer |  | Saldo do Estoque Atual |  |
| VLRUNIT | String |  | Valor Unitário |  |
| CODPROD | String |  | Código do Produto |  |
| QTDPROD | String |  | Quantidade de Produtos |  |

## AD_LAYOUTEMAIL — Layout de Email
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| DESCRICAO | String |  | Descrição do Email |  |
| CORPOEMAIL | C |  | Corpo do Email |  |

## AD_LOCALPROMO — Local Promocional
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODLOCAL | Integer |  | Locais |  |
| CODPROD | Integer |  | Código |  |

## AD_LOG — LOG
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQ | Integer |  | SEQ |  |

## AD_LOGALTERPRECO — log de Alteração de Preço
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| CODTAB | Integer |  | Tabela de Preço |  |
| CODPROD | Integer |  | Produto |  |
| PRECOANT | Float |  | Preço Anterior |  |
| PRECO | Float |  | Preço Atualizado |  |
| NUTAB | Integer |  | Nr. Tabela |  |
| DHATLTER | DateTime |  | Data Alteração |  |

## AD_LOGATUALIZAPRECO — LOG DE ATUALIZACAO DE PRECO
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTAB | Integer |  | NUMERO DA TABELA DE PRECO |  |
| DTVIGOR | Date |  | DATA DE VIGOR |  |
| DTALTER | DateTime |  | DATA DE ALTERACAO |  |
| CODUSU | Integer |  | CODIGO DO USUARIO |  |
| CODTAB | Integer |  | CODIGO DA TABELA |  |

## AD_LOGPRECO — Log de Preços
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | id |  |
| PRECO | String |  | Preco |  |
| LOJA | String |  | Loja |  |
| VENDEDOR | String |  | Vendedor |  |
| FRETE | String |  | Frete |  |
| PRAZO | String |  | Prazo |  |
| ERRO | String |  | Erro |  |
| CODPROD | String |  | codigo do produto |  |
| CODLOG | String |  | codigo Log |  |
| DESCONTO | String |  | desconto |  |
| PROCESSADO | String |  | Processado |  |
| DTALTER | DateTime |  | Data Alteração |  |
| MARGEM | Float |  | Margem |  |
| POSICAO | String |  | Posição |  |
| URL | String |  | URL dos marketplaces |  |

## AD_LOGPRECOPRECIF — Log Preço Precifica
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| SKU | Integer |  | SKU |  |
| DOMINIO | String |  | Dominio |  |
| DHALTER | DateTime |  | Data Alteração |  |
| PRECOBRUTO | Float |  | Preço bruto |  |
| PRECOPROMOCAO | Float |  | Preço Promocional |  |
| RANK | Integer |  | Rank |  |
| GANHADOR | String |  | Ganhador |  |
| MARGEM | Float |  | Margem |  |
| LOJA | String |  | Loja |  |
| CODPROD | Integer |  | Produto |  |

## AD_LOGSPLIT — Log Split de Pedidos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| NUNOTAORIG | Integer |  | Nro. Unico Origem |  |
| DHINCLUSAO | DateTime |  | Dh. Inclusao |  |
| STATUSPROCESSAMENTO | String |  | Status Processamento | `E`=E - Erro `S`=S - Sucesso |
| MSGSTATUS | String |  | Msg. Status |  |
| DESCRICAO | C |  | Descrição |  |

## AD_LOGTABPRECO — Log da Tabela preco
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUTAB | Integer |  | nr unico |  |
| DTVIGOR | Date |  | DATA DE VIGOR |  |
| DTALTERACAO | Date |  | DATA DE ALTERACAO |  |
| CODTAB | Integer |  | TABELA ORIGEM |  |

## AD_LOGTXT — LOGTXT
Campos: 77

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQLOG | Integer |  | Sequencia Log |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| HEADERDTEMI | Date |  | Data de Emissão (DDMMAAAA) |  |
| HEADEREXTVEN | String |  | Extrato Eletrônico de Vendas |  |
| HEADERNOMECOM | String |  | Nome comercial (grupo/matriz) |  |
| HEADERSEQMOV | Integer |  | Sequênciado movimento |  |
| HEADERPVMATRIZ | Integer |  | NºPVgrupo oumatriz |  |
| HEADERTIPMOV | String |  | Tipo de movimento |  |
| HEADERVERSAOARQ | String |  | Versão do arquivo |  |
| HEADERLIVRE | String |  | Livre |  |
| HMTIPREG | Integer |  | Tipo de registro (“004”) |  |
| HMPVMATRIZ | String |  | Nº-PVmatriz |  |
| HMNOMECOM | String |  | Nome comercial da matriz |  |
| RV10TIPREG | Integer |  | Tipo de registro (“010”) |  |
| RV10NUMRV | Integer |  | Número do RV |  |
| RV10NUMPV | Integer |  | Número do PV |  |
| RV10NUMBCO | Integer |  | Nº do banco |  |
| RV10NUMAGE | Integer |  | Nº da Agência |  |
| RV10NUMCC | Integer |  | Nºda conta-corrente |  |
| RV10DTRV | Date |  | Datado RV(DDMMAAAA) |  |
| RV10QTDCVNSU | Integer |  | Quantidade de CV/NSUs |  |
| RV10VLRBRUTO | Float |  | Valor Bruto |  |
| RV10VLRGOR | Float |  | Valor da Gorjeta |  |
| RV10VLRRE | Float |  | Valor Rejeitado |  |
| RV10VLRDESC | Float |  | Valor do Desconto |  |
| RV10VLRLIQ | Float |  | Valor Líquido |  |
| RV10DTCRED | Date |  | Datade créditoda1ªparcela(DDMMAAAA) |  |
| RV10BANDEIRA | String |  | Bandeira(2) |  |
| RV12TIPREG | Integer |  | Tipo de registro (“012”) |  |
| RV12NUMPV | Integer |  | Número do PV |  |
| RV12NUMRV | Integer |  | Número do RV |  |
| RV12CVNSU | Date |  | Data do CV/NSU(DDMMAAAA) |  |
| R12CVNSU | Float |  | Reg 12 -  Valor do CV/NSU |  |
| R12VLRGOR | Float |  | Reg 12 - Valor da Gorjeta |  |
| R12NUMCARTAO | String |  | R12 - Número Cartão |  |
| R12STATUSCVNSU | String |  | R12 - Status do CV/NSU(1) |  |
| R12NUMPAR | Integer |  | R12 - Número de Parcelas |  |
| R12NUMCVNSU | Integer |  | R12 - Número do CV/NSU |  |
| R12NUMREF | String |  | Número de Referência |  |
| R12VLRDESC | Float |  | R12 - Valor Desconto Total |  |
| R12NUMAUT | String |  | R12 - Num Autorização |  |
| R12HRTRAN | Integer |  | R12 - Horadatransação(HHMMSS) |  |
| R12NUMBILHETE | String |  | Nº do Bilhete |  |
| R12TIPCAP | String |  | Tipo de Captura |  |
| R12VLRLIQCVNSU | Float |  | R12 - Valor Líquido do CV/NSU |  |
| R12VLRPRIMEIRAPAR | Float |  | R12 - Valor líquido da primeira parcela |  |
| R12VLRLIQDEMAIS | Float |  | R12 - Valor líquido das demais parcelas |  |
| R12NUMTERMINAL | String |  | R12 - Número do Terminal |  |
| R12SIGLAPAIS | String |  | R12 - Sigla do País |  |
| R12BANDEIRA | String |  | R12 - Bandeira |  |
| R12VLRDESCTAXAFLEX | Float |  | R12 - Valor desconto - Taxa Flex |  |
| R12VLRDESCTAXAMDR | Float |  | R12 - Valor desconto - Taxa MDR |  |
| R12CODIGOSERVICO | Integer |  | R12 - Código de Serviço |  |
| R14TIPREG | Integer |  | R14 - Tipo de registro (“014”) |  |
| R14NUMPV | Integer |  | R14 - Número do PV |  |
| R14NUMRV | Integer |  | R14 - Número do RV |  |
| R14DTRV | Date |  | Datado RV(DDMMAAAA) |  |
| R14NUMPARCELA | Integer |  | R14 - Número da Parcela |  |
| R14VLRPARCTOT | Float |  | R14 - Valor da parcela bruto |  |
| R14VLRDESCPAR | Float |  | R14 - Valor do desconto sobre a parcela |  |
| R14VLRPARLIQ | Float |  | R14 - Valor da parcela líquida |  |
| R14DTCRED | Date |  | R14 - Data do crédito(DDMMAAAA) |  |
| R26TIPREG | Integer |  | R26 - Tipo de registro (“026”) |  |
| R26PVMATRIZ | String |  | Nº PV matriz |  |
| R26VLRTOTBRU | Float |  | R26 - Valor total bruto |  |
| R26QTDCVNSU | Integer |  | R26 - Quantidade de CV/NSUs rejeitados |  |
| R26VLRRE | Float |  | R26 - Valor total rejeitado |  |
| R26VLRTOTROT | Float |  | R26 - Valor total rotativo |  |
| R26VLRTOTPARSEMJUROS | Float |  | R26 - Valor Total parcelado sem juros |  |
| R26VLRTOTIATA | Float |  | R26 - Valor Total Parcelado IATA |  |
| R26VLRTOTDOLAR | Float |  | R26 - Valor Total Dólar |  |
| R26VLRTOTDESC | Float |  | R26 - Valor total Desconto |  |
| R26VLRTOTLIQ | Float |  | R26 - Valor Total Líquido |  |
| R26VLRTOTGOR | Float |  | R26 - Valor Total da Gorjeta |  |
| R26VLRTOTTAXEMBARQ | Float |  | R26 - Valor Total da taxa de embarque |  |
| R26QTDCVNSUACA | Integer |  | R26 - Quantidade CV/NSU acatados |  |
| HEADERTIPREG | Integer |  | Tipo de Registro |  |

## AD_MARKETPLACE — Marketplace
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| CODPROD | Integer |  | Código |  |
| LENGTH | Float |  | Comprimento do produto (centímetro) |  |
| WIDTH | Float |  | Largura do produto (centímetro) |  |
| WEIGHT | Float |  | Peso do Produto (KG) |  |
| BRAND | String |  | Marca |  |
| COMPLEMENTO | String |  | Complemento |  |
| HEIGHT | Float |  | Altura do produto (centímetro) |  |

## AD_MAXCONF — TABLE AD_MAXCONF
Campos: 34

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MODELORETORNO | Integer |  | Modelo Retorno Pronta Entrega |  |
| ID | Integer |  | ID |  |
| AD_URLAPI | String |  | Url da Api |  |
| AD_URLAPIPDV | String |  | Url da Api PDV |  |
| AD_USUARIO | String |  | Usuario de Acesso a Api |  |
| AD_SENHA | String |  | Senha de Acesso a Api |  |
| MAXFINMODELO | Integer |  | Financeiro Modelo |  |
| LOCAL_TRANSITO | Integer |  | Local Mercadorias em Trânsito |  |
| AD_CODLOCALORIG | Integer |  | Local Produto Pré-Venda |  |
| MAXTOPBAIXA | Integer |  | TOP Baixa de Títulos Recebidos |  |
| TIT_CARTORIO | Integer |  | Tipo de Título Cartório |  |
| TIT_PROTESTO | Integer |  | Tipo de Título Protesto |  |
| NOTMODPREVENDA | Integer |  | Modelo Pedidos Pré-Venda |  |
| MODELOPRONTAENTREGA | Integer |  | Modelo Pronta Entrega (Pedidos) |  |
| QTD_DIAS_COMPRAS_PENDENTE | Integer |  | Qtd Dias Compras Pendentes |  |
| MODELOPRONTAENTREGA_NOTA | Integer |  | Modelo Pronta Entrega (Notas) |  |
| TOP_ENTREGA_BALCAO | Integer |  | TOP Entrega Balcão |  |
| QTD_DIAS_CARREGAMENTO | Integer |  | Quantidade Dias Carregamento |  |
| QTD_DIAS_NOTAS | Integer |  | Qtd Dias Notas |  |
| QTD_DIAS_HIST_VENDAS | Integer |  | Dias Histórico Vendas |  |
| QTD_DIAS_CAIXAS | Integer |  | Quantidade Dias Caixas |  |
| QTD_DIAS_ROTEIRIZAR | Integer |  | Dias Pedidos à Roteirizar |  |
| ENVIA_PD_PENDENTE | String |  | Envia Pedidos Pendentes à Roteirizar? | `S`=Sim `N`=Não |
| MAXTOPTRANSFBANCARIA | Integer |  | TOP para Transferência Bancária |  |
| QTD_DIAS_PONTO | Integer |  | Qtd. Dias Ponto Vendedor |  |
| TOP_NF_RETORNO | Integer |  | TOP NF Retorno Remessa |  |
| TOP_ORCAMENTO | Integer |  | TOP Orçamento Pré-Venda |  |
| LOCAL_EMPRESA | Integer |  | Local Estoque Empresa |  |
| TOP_RETORNO_DESCARGA | Integer |  | TOP Retorno Descarga |  |
| MAXRETORNOPARCIAL | Integer |  | Modelo Retorno Parcial |  |
| LOC_RETORNO_PARCIAL | Integer |  | Local Retorno Parcial |  |
| ENVIA_GERENTE | String |  | Enviar Gerentes de Vendas? | `S`=Sim `N`=Não |
| MAXGRAVALOG | String |  | Gravar Log? | `N`=Não `S`=Sim |
| MODELOREMESSA | Integer |  | Modelo Remessa Pronta Entrega |  |

## AD_MAXIMALOG — LogMaxima
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| OPERACAO | String |  | Operação |  |
| SENTIDO | String |  | Sentido |  |
| TIPO_RETORNO | String |  | Tipo de Retorno |  |
| MENSAGEM | C |  | Mensagem |  |
| STACKTRACE | C |  | STACKTRACE |  |
| CHAVE | String |  | Chave |  |
| DH_LOG | DateTime |  | Data/Hora do Log |  |
| TIPO_REGISTRO | Integer |  | Tipo de registro processado. | `75`=Código de Barras `74`=Retorno Crítica Pedidos `73`=Mensagens Vendedores `72`=Lotes de Estoque `71`=Transportadoras_(+70)_ |
| TIPO_LOG | Integer |  | Tipo de Log | `1`=Erro `3`=Monitoramento `2`=Alerta |

## AD_MAXIMA_MENSAGENS — TABLE AD_MAXIMA_MENSAGENS
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | Integer |  | Usuário |  |
| CODVEND | Integer |  | Vendedor |  |
| STATUSMENSAGEM | String |  | Status | `0`=Enviada `1`=Lida |
| DTMENSAGEM | DateTime |  | Data de Envio |  |
| MENSAGEM | C |  | Mensagem |  |
| CODMENSAGEM | Integer |  | Cód. Mensagem |  |

## AD_MAXIMA_PROCESSOS — TABLE AD_MAXIMA_PROCESSOS
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Processo a ser executado |  |
| ID_ACAO | Integer |  | Ação Agendada |  |
| ID | Integer |  | ID |  |

## AD_MAXIMA_PRODFILIAL — TABLE AD_MAXIMA_PRODFILIAL
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODPROD | Integer |  | Produto |  |

## AD_MAXLOGROTEIRIZACAO — LogMaximaRoteirizacao
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Identificação |  |
| NUNOTA | Integer |  | Nro Nota |  |
| DHMOV | DateTime |  | Data/Hora movimento |  |
| STATUS | Integer |  | Status |  |
| MOTERRO | C |  | Mensagem de erro |  |

## AD_MKTPFAIXPRECO — Faixa de Preço
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAB | Integer |  | Código Tabela de Preço |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| VALORFIN | Float |  | Valor Final |  |
| TAXAFIXA | Float |  | Valor Taxa Fixa |  |
| PERCCOMISSAO | Float |  | Percentual Comissão |  |
| SUBSIDIO | Float |  | Subsídio |  |
| VALORINI | Float |  | Valor Inicial |  |

## AD_MKTPIFOOD — MKTPIFOOD
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIFOOD | Integer |  | IDIFOOD |  |
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | Id |  |
| NOME | String |  | NOME |  |
| DESCPROD | C |  | DESCPROD |  |
| PRODENV | String |  | PRODENV | `S`=Sim `N`=Não |
| ATIVO | String |  | ATIVO | `S`=Sim `N`=Não |
| CODLOCAL | Integer |  | Cód. Local Estoque |  |
| ESTOQUE | Integer |  | Estoque Fixo |  |
| PORLOCAL | String |  | PORLOCAL | `S`=Sim `N`=Não |
| CODTAB | Integer |  | Código Tab. Preço |  |
| TABPRECO | String |  | Por Tabela de Preço? | `S`=Sim `N`=Não |
| UNIT_PRICE | Float |  | Preço Fixo |  |
| PERCENTSTK | Integer |  | % Estoque |  |
| IDLOJA | Integer |  | idLoja |  |
| MARCA | String |  | marca |  |
| VOLUME | String |  | volume |  |
| ENVSTK | String |  | ENVSTK | `N`=Não `S`=Sim |
| CODBARRA | String |  | Código de Barras |  |
| CODVEND | Integer |  | CODVEND |  |

## AD_MKTPLCATRIBUTTECRF — Atributte Carrefour
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| CODPROD | Integer |  | Código |  |
| IDAT | Integer |  | IDAT |  |
| IDCRF | Integer |  | Id. Carrefour |  |
| ATRIBUTO | String |  | Atributo |  |

## AD_MKTPLCCRF — AD_MKTPLCCRF
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDCRF | Integer |  | Id. Carrefour |  |
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | ID |  |
| PRODUCTSKU | String |  | product-sku |  |
| PRODUCTTITLE | C |  | Titulo do Produto |  |
| VARIANTCOLOR | String |  | Variant Color |  |
| VARIANTVOLTAGE | String |  | Variant Voltage |  |
| VARIANTSIZE | String |  | Variant Size |  |
| VARIANTSECONDCOLOR | String |  | Variant Second Color |  |
| SKU | String |  | Sku |  |
| DESCRIPTION | C |  | Descrição |  |
| SELLERATRIBUTTE | C |  | Seller Atributo |  |
| PRICE | Float |  | Preço Fixo |  |
| VARIANTIMAGE1 | String |  | Imagem 1 |  |
| VARIANTIMAGE2 | String |  | Imagem 2 |  |
| VARIANTIMAGE3 | String |  | Imagem 3 |  |
| VARIANTIMAGE4 | String |  | Imagem 4 |  |
| VARIANTIMAGE5 | String |  | Imagem 5 |  |
| IMPORT | String |  | Importado? | `S`=Sim `N`=Não |
| STATUSPROD | String |  | ID Import |  |
| HAS_ERROR_REPORT | String |  | Linhas Com Erro |  |
| HAS_NEW_PRODUCT_REPORT | String |  | Linhas Com Sucesso |  |
| PERCESTOQUE | Float |  | % Estoque |  |
| STATUS | String |  | Produto Enviado a Integração? | `S`=Sim `N`=Não |
| ENVPRICE | String |  | Preço Enviado | `S`=SIM `N`=NÃO |
| STATUS_IMPORT | String |  | Status Importação | `SENT`=Enviado `COMPLETE`=Finalizado |
| PORLOCAL | String |  | Por Local? | `S`=Sim `N`=Não |
| CODLOCAL | Integer |  | Local |  |
| TABPRECO | String |  | Por Tabela de Preço? | `S`=Sim `N`=Não |
| NUTAB | Integer |  | Nro. Único |  |
| CODTAB | Integer |  | Cód. Tab Preço |  |
| ESTOQUE | Integer |  | Estoque Fixo |  |
| CATEGORYCODE | Integer |  | Cod. Categoria |  |

## AD_MKTPLCGPA — Grupo Pão de Açucar
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDGPA | Integer |  | Id. Grupo Pão de Açucar |  |
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | Id |  |
| PRODUCTSKU | String |  | product-sku |  |
| PRODUCTTITLE | C |  | Titulo do Produto |  |
| VARIANTCOLOR | String |  | Variant Color |  |
| VARIANTVOLTAGE | String |  | Variant Voltage |  |
| VARIANTSIZE | String |  | Marca |  |
| VARIANTSECONDCOLOR | String |  | Variant Second Color |  |
| SKU | String |  | Sku |  |
| DESCRIPTION | C |  | Descrição |  |
| SELLERATRIBUTTE | C |  | Seller Atributo |  |
| PRICE | Float |  | Preço Fixo |  |
| VARIANTIMAGE2 | C |  | Imagem 2 |  |
| VARIANTIMAGE3 | C |  | Imagem 3 |  |
| VARIANTIMAGE4 | C |  | Imagem 4 |  |
| VARIANTIMAGE5 | C |  | Imagem 5 |  |
| IMPORT | String |  | Importado? | `S`=Sim `N`=Não |
| STATUSPROD | String |  | ID Import |  |
| HAS_ERROR_REPORT | String |  | Linhas Com Erro |  |
| HAS_NEW_PRODUCT_REPORT | String |  | Linhas Com Sucesso |  |
| PERCESTOQUE | Float |  | % Estoque |  |
| STATUS | String |  | Produto Enviado a Integração? | `S`=Sim `N`=Não |
| ENVPRICE | String |  | Preço Enviado |  |
| STATUS_IMPORT | String |  | Status Importação | `SENT`=Enviado `COMPLETE`=Finalizado |
| PORLOCAL | String |  | Por Local? | `S`=Sim `N`=Não |
| CODTAB | Integer |  | Cód. Tab Preço |  |
| CODLOCAL | Integer |  | Cód Local Estoque |  |
| TABPRECO | String |  | Por Tabela de Preço? | `S`=Sim `N`=Não |
| ESTOQUE | Integer |  | Estoque Fixo |  |
| VARIANTIMAGE1 | C |  | Imagem 1 |  |
| PESOBRUTO | Float |  | Peso |  |
| ESPESSURA | Float |  | Espessura |  |
| LARGURA | Float |  | Largura |  |
| ALTURA | Float |  | Altura |  |
| CATEGORYCODE | Integer |  | Cod. Categoria |  |

## AD_MKTPLCMERCLIVCATEGORIA — MKTPLCMERCLIVCATEGORIA
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Código |  |
| MLB | String |  | MLB |  |
| DESCRICAO | String |  | Descrição |  |
| CODCATEGORIA | String |  | Cód. Categoria |  |
| ESTRUTURA | String |  | Estrutura |  |
| SHIPMODE | String |  | Ship Mode |  |

## AD_MKTPLCMGLATRIBVAR — Atributos Variação Magalu
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDVAR | Integer |  | ID |  |
| CODPROD | Integer |  | Código |  |
| IDMGL | Integer |  | IDMGL |  |
| IDSKU | Integer |  | IDSKU |  |
| ID | Integer |  | ID |  |
| VALUE | String |  | Valor |  |
| NAME | String |  | Caracteristica |  |

## AD_MKTPMELI — Mercado Livre
Campos: 56

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Código |  |
| IDANUNCIO | Integer |  | Id Anuncio |  |
| ID | Integer |  | Id |  |
| CATEGORY_ID | String |  | Id de Categoria |  |
| PRICE | Float |  | Preço |  |
| CURRENCY_ID | String |  | Região | `BRL`=BRL |
| AVAILABLE_QUANTITY | Integer |  | Estoque |  |
| BUYING_MODE | String |  | Modo de Compra | `buy_it_now`=buy_it_now |
| CONDITION | String |  | Condição | `new`=new |
| LISTING_TYPE_ID | String |  | Tipo de Publicação | `gold_pro`=Premium `gold_special`=Clássico |
| SUBTITLE | String |  | Sub Título |  |
| DESCRIPTION | String |  | Descrição |  |
| VIDEO_ID | String |  | Video |  |
| OFFICIAL_STORE_ID | String |  | Id Loja |  |
| WARRANTY | String |  | warranty |  |
| BASE_PRICE | Float |  | Base de Preço |  |
| ORIGINAL_PRICE | Float |  | Preço Original |  |
| PERMALINK | String |  | permalink |  |
| ENVIARMKTPLACE | String |  | Envia Mktplace | `S`=Sim `N`=Não |
| IDVARIACAO | String |  | Id Variação |  |
| MLB_ANUNCIO | String |  | MLB Anuncio |  |
| ENVDESCR | String |  | Atualiza Descrição | `S`=Sim `N`=Não |
| ENVPICTURE | String |  | Atualiza Imagens | `S`=Sim `N`=Não |
| ENVATRIB | String |  | Atualiza Atributos | `N`=Não `S`=Sim |
| SHIPPING | String |  | Modo de Envio | `me2`=Mercado de Envios 2 |
| PERCENTSTK | Float |  | % Estoque |  |
| ITEM_CONDITION | String |  | Condição de um item | `2230284`=Novo `2230581`=Usado `2230582`=Recondicionado |
| ATTRIBUTE_COMBINATIONS | String |  | Com Combinações? | `S`=Sim `N`=Não |
| ACTIVE | String |  | Ativo | `active`=Ativo `paused`=Pausado |
| CATEGORY_SEARCH_DATA | String |  | CATEGORY_SEARCH_DATA |  |
| SHIPMODEVW | String |  | Modos de Envios |  |
| STATUSENVIO | Integer |  | Status Envio |  |
| ENVME | String |  | Atualiza Modo Envios | `S`=Sim `N`=Não |
| STATUSENVIOS | String |  | Status Envios |  |
| ENVAVAR | String |  | Atualiza Variações | `S`=Sim `N`=Não |
| TABPRECO | String |  | Por Tabela de Preço | `S`=Sim `N`=Não |
| CODTAB | Integer |  | Código Tabela de Preços |  |
| CODLOCAL | Integer |  | Cód. Local de Estoque |  |
| PORLOCAL | String |  | Por Local | `S`=Sim `N`=Não |
| BODYRETORNOANUNCIO | String |  | Body Retorno Anunico |  |
| POREMPRESA | String |  | Por Empresa | `S`=Sim `N`=Não |
| ENVIASTATUS | String |  | Envia Status | `S`=Sim `N`=Não |
| STATUSATIVOS | String |  | Resultado de Alteração de Status |  |
| STATUSANUNCIO | String |  | Status de Publicação de Anuncio |  |
| STATUSDESCR | String |  | Reposta sobre Atulização de Descrição |  |
| STATUSATRIBUTOS | String |  | Atualização de Atributos |  |
| ENVATAULIZACAO | String |  | Atualiza Imagens S/ Variações | `S`=Sim `N`=Não |
| STATUSATUALANUNC | String |  | Atualização de Imagens S/ Variações |  |
| ENVSTK | String |  | Envia Estoque/Price | `S`=Sim `N`=Não |
| ENVPRICE | String |  | Envia Preço | `S`=Sim `N`=Não |
| MULTIPLICADOR | Integer |  | Multiplicador |  |
| CODIGOCAT | Integer |  | Cód. de Categoria |  |
| ESTRUTURA | String |  | Árvore de Categoria |  |
| TIPANUNCIO | String |  | Envios Full? | `S`=Sim `N`=Não |
| CODLOJA | String |  | Cód. Loja | `1`=Loja Oficial `2`=Loja Cabo Frio |
| TITLE | String |  | Título |  |

## AD_MKTPMELIATRIB — MKTPMELIATRIB
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDATRIBUTO | String |  | Id Atributo |  |
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | Id |  |
| IDANUNCIO | Integer |  | Id Anuncio |  |
| CONSULTE | String |  | Consulte |  |
| OPTIONS | String |  | Opções |  |
| DESCRATRIB | String |  | Descrição de Atributo |  |
| ACTIVE | String |  | Ativo | `S`=Sim `N`=Não |
| TAGS | String |  | Tags |  |
| CODMELIATRIB | String |  | Código Atributo |  |
| OBIRGATORIO | String |  | Requerido |  |
| VALUE_ID | String |  | Id Valor |  |
| VALUE_NAME | String |  | Nome Valor |  |
| HIERARCHY | String |  | Hierarquia |  |
| DERCATRIB | String |  | Descrição Atributo |  |

## AD_MKTPMELIATRIBCOMB — MKTPMELIATRIBCOMB
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODVAR | Integer |  | SKU |  |
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | Id |  |
| IDANUNCIO | Integer |  | Id Anuncio |  |
| IDATRIBUTOCOMB | String |  | Id Atributo Combinação |  |
| DESCRATRIB | String |  | Descrição de Atributo |  |
| ACTIVE | String |  | Ativo | `S`=Sim `N`=Não |
| TAGS | String |  | Tags |  |
| VALUE_ID_VAR | String |  | Id Valor |  |
| VALUE_NAME_VAR | String |  | Nome Valor |  |
| HIERARCHY | String |  | Hierarquia |  |
| OPTIONS | String |  | Opções |  |

## AD_MKTPMELIIMAGE — Imagens Mercado Livre
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDIMAGE | Integer |  | Id Image |  |
| ID | Integer |  | Id |  |
| IDANUNCIO | Integer |  | Id Anuncio |  |
| CODPROD | Integer |  | Código |  |
| TEXT | String |  | Texto |  |

## AD_MKTPMELISALETERMS — MKTPMELISALETERMS
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SALETERMSID | String |  | Id |  |
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | Id |  |
| IDANUNCIO | Integer |  | Id Anuncio |  |
| VALUE_ID | String |  | Id Valor |  |
| VALUE_NAME | String |  | Nome Valor |  |
| OPTIONS | String |  | Opções |  |
| ACTIVE | String |  | Ativo | `S`=Sim `N`=Não |
| NAME | String |  | Nome |  |

## AD_MKTPMELISKUVAR — Sku Variação
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRODVAR | Integer |  | SKU |  |
| ID | Integer |  | Id |  |
| IDANUNCIO | Integer |  | Id Anuncio |  |
| CODPROD | Integer |  | Código |  |
| PERCQUANTITY | Float |  | % Estoque |  |
| AVAILABLE_QUANTITY_VAR | Integer |  | Estoque |  |
| ACTIVE | String |  | Ativo | `S`=Sim `N`=Não |
| PORLOCAL | String |  | Por Local | `S`=Sim `N`=Não |
| TABPRECO | String |  | Por Tabela de Preço | `S`=Sim `N`=Não |
| IDVARICAO | String |  | Id Variação |  |
| ENVSTK | String |  | Envia Estoque | `S`=Sim `N`=Não |
| ENVPRICE | String |  | Envia Preço | `S`=Sim `N`=Não |
| STATUS | String |  | Status Variação | `active`=Ativo `paused`=Pausado |
| STATUSSTKVAR | String |  | Retorno de Estoque |  |
| STATUSPRICEVAR | String |  | Retorno de Preço |  |
| STATUSVAR | String |  | Retorno de Status |  |
| ENVSTATUS | String |  | Envia Status | `S`=Sim `N`=Não |
| PRICEVAR | Float |  | Preço |  |

## AD_MKTPMELISKUVARIMAGE — MKTPMELISKUVARIMAGE
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDVARIMAGE | Integer |  | Id Image Variação |  |
| CODPRODVAR | Integer |  | SKU |  |
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | Id |  |
| IDANUNCIO | Integer |  | Id Anuncio |  |
| TEXT | String |  | Texto Url |  |

## AD_MKTPORDERSSHOPEE — MKTPORDERSSHOPEE
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| DATAHORAORDER | DateTime |  | DATAHORA |  |
| CODVEND | Integer |  | codvend |  |
| ORDERID | String |  | ORDERID |  |

## AD_MKTPSHOPATRIBVAR — Atributo Var. Shopify
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDATRIBUTOVAR | Integer |  | Id Atributo Var. |  |
| IDSHOPVAR | Integer |  | Id Variação |  |
| CODPROD | Integer |  | Código Produto |  |
| ID | Integer |  | Id |  |
| IDSHOPIFY | Integer |  | Id Shopify |  |
| VALORATRIBVAR | String |  | Valor Atributo Var. | `P`=P `M`=M `G`=G `GG`=GG `Azul`=Azul_(+3)_ |
| NAMEATRIBVAR | String |  | Nome Atributo Var. | `Tamanho`=Tamanho `Cor`=Cor |

## AD_MKTPSHOPIFY — Shopify
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDSHOPIFY | Integer |  | Id Shopify |  |
| ID | Integer |  | Id |  |
| CODPROD | Integer |  | Código Produto |  |
| DESCRIPTION | String |  | Descrição Completa (HTML) |  |
| HANDLE | String |  | Temas Shopify |  |
| PRODUCTTYPE | String |  | Categoria Produto |  |
| DTPUBLICACAO | DateTime |  | Data de Publicação |  |
| TPPUBLICACAO | String |  | Tipo de Publicação | `web`=Web `global`=Global |
| STATUS | String |  | Status | `active`=Ativo `archived`=Arquivado `draft`=Rascunho |
| TAG | String |  | Tag de Pesquisa |  |
| SUFIXO | String |  | Sufixo Modelo |  |
| COMPAREPRICE | Float |  | Comparar Preço |  |
| PESO | Float |  | Peso |  |
| TABPRECO | String |  | Por Tabela de Preço? | `S`=Sim `N`=Não |
| CODTAB | Integer |  | Cód. Tab Preço |  |
| PRICE | Float |  | Preço Fixo |  |
| PORLOCAL | String |  | Por Local? | `S`=Sim `N`=Não |
| CODLOCAL | Integer |  | Cód. Local Estoque |  |
| ESTOQUE | Integer |  | Estoque Fixo |  |
| PERCESTOQUE | Float |  | % Estoque |  |
| ENVIASHOPIFY | String |  | Envia Shopify | `S`=Sim `N`=Não |
| IDANUNCIO | String |  | Id Anúncio |  |
| IDVARIACAO | String |  | Id Variação |  |
| BARCODE | String |  | Cód. de Barras |  |
| CONTROLE | String |  | Controle |  |
| INVENTORYITEMID | String |  | Id Estoque |  |
| STATUSSTK | String |  | Status Estoque |  |
| STATUSPRICE | String |  | Status Preço |  |
| TITLE | String |  | Título |  |

## AD_MKTPSHOPIFYATRIB — Atributo Shopify
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDATRIBUTO | Integer |  | Id Atributo |  |
| ID | Integer |  | Id |  |
| IDSHOPIFY | Integer |  | Id Shopify |  |
| CODPROD | Integer |  | Código Produto |  |
| VALORATRIB | String |  | Valor Atributo | `P`=P `M`=M `G`=G `GG`=GG `Rosa`=Rosa_(+3)_ |
| NAMEATRIB | String |  | Nome Atributo | `Tamanho`=Tamanho `Cor`=Cor |

## AD_MKTPSHOPIFYIMAGE — Imagem Shopify
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDSHOPIFY | Integer |  | Id Shopify |  |
| ID | Integer |  | Id |  |
| CODPROD | Integer |  | Código Produto |  |
| IDIMAGEM | Integer |  | Id Imagem |  |
| ALTURA | Integer |  | Altura |  |
| SOURCE | String |  | URL |  |
| SINCSHOP | String |  | Imagem Enviada? | `S`=Sim `N`=Não |
| IDIMAGEMSHOP | String |  | Id Imagem Shopify |  |
| CODPRODIMAGE | Integer |  | Cód. Prod. Imagem |  |
| LARGURA | Integer |  | Largura |  |

## AD_MKTPSHOPSKUVARIACAO — Shopify Variação
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDSHOPVAR | Integer |  | Id Variação |  |
| CODPROD | Integer |  | Código Produto |  |
| ID | Integer |  | Id |  |
| IDSHOPIFY | Integer |  | Id Shopify |  |
| COMPAREPRICE | Float |  | Comparar Preço |  |
| TABPRECO | String |  | Por Tabela de Preço? | `S`=Sim `N`=Não |
| CODTAB | Integer |  | Cód. Tab Preço |  |
| PRICE | Float |  | Preço Fixo |  |
| PORLOCAL | String |  | Por Local? | `S`=Sim `N`=Não |
| CODLOCAL | Integer |  | Cód. Local Estoque |  |
| PERCESTOQUE | Float |  | % Estoque |  |
| ESTOQUE | Integer |  | Estoque Fixo |  |
| IDVARIACAO | String |  | Id Var. Shopify |  |
| INVENTORYITEMID | String |  | Id Estoque |  |
| CODPRODVAR | Integer |  | Cód. Prod. Variação |  |
| CONTROLE | String |  | Controle |  |
| TITLE | String |  | Título |  |
| STATUSSTK | String |  | Status Estoque |  |
| STATUSPRICE | String |  | Status Preço |  |
| BARCODE | String |  | Cód. de Barras |  |

## AD_MOTIVDEV — Motivo de Devolução
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Codigo |  |
| DESCRICAO | String |  | Descrição |  |

## AD_MOTIVORESPONSAVEL — Motivo x Responsável
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | Código |  |
| RESPONSAVEL | String |  | Responsável | `1`=SAC `2`=Logística `3`=Compras `4`=Comercial `5`=Controladoria_(+2)_ |
| MOTIVO | String |  | Motivo |  |

## AD_MOVIMENTOCX_MAX — TABLE AD_MOVIMENTOCX_MAX
Campos: 29

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPRESTACAOCONTAI | String |  | Max. Id Movimento |  |
| ID_CAIXA_MAX | Integer |  | ID_CAIXA_MAX |  |
| DATALANCAMENTO | DateTime |  | Max. Dt. Lançamento |  |
| NUMTRANSVENDA | Integer |  | Nr. Pedido Maxima |  |
| DHACAO | DateTime |  | Dt. Ação |  |
| TIPO | Integer |  | Tipo Movimento | `Despesa`=1 `Receita`=2 `Transferencia`=3 `Malote`=5 |
| VALOR | Integer |  | Max. Vr. Movimento |  |
| VLJUROS | Integer |  | Max. Vr. Juros |  |
| VLDESCONTO | Integer |  | Max. Vr. Desconto |  |
| NUMPEDRCA | Integer |  | Nr. Pedido Sk |  |
| EXCLUIDO | String |  | Max. Excluído |  |
| ID_ERP | Integer |  | Max. Nr Financeiro Sk. |  |
| FORMAPAGAMENTO | Integer |  | Max. Forma Pagamento |  |
| NUFIN | Integer |  | Nr. Financeiro Sk. |  |
| NUBCO | Integer |  | Nr. Mov. Bancaria Sk. |  |
| ID | Integer |  | ID |  |
| ACAO | Integer |  | Ação | `Inserção`=1 `Atualização`=2 `Exclusão`=3 |
| DTNEG | DateTime |  | Dt. Negociação Sk. |  |
| DTVENC | DateTime |  | Dt. Vencimento Sk. |  |
| DHMOV | DateTime |  | Dt. Mov. Sk |  |
| DTALTER | DateTime |  | Dt. Alter. Sk |  |
| RECDESP | Integer |  | Receita/Despesa |  |
| CODCTABCOINT | Integer |  | Cod. Conta Bancaria Sk |  |
| CODTIPTIT | Integer |  | Tipo Título Sk. |  |
| DESDOBRAMENTO | Integer |  | Desdobramento Sk. |  |
| VLRDESDOB | Integer |  | Desdobramento Sk. |  |
| VLRDESC | Integer |  | Vlr. Desc. Sk. |  |
| VLRJUROS | Integer |  | Vlr. Juros Sk. |  |
| CODPRESTACAOCONTAC | String |  | Max. Id Caixa |  |

## AD_NFEXCTE — NFe x CTe Importado
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CHAVECTE | String |  | Chave CTe |  |
| CHAVENFECTE | String |  | Chave NFe CTe |  |
| NUARQUIVO | Integer |  | Nro. Único Arquivo CTe |  |
| VLRCTE | Float |  | Vlr. CTe |  |
| NUNOTA | Integer |  | Nro. Único CTe |  |

## AD_NOTFISJADLOG — Shipment Jadlog
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| CODJADLOG | String |  | Cód. Jadlog |  |
| SHIPMENTID | String |  | Shipment ID |  |
| STATUS | String |  | Status |  |
| NUNOTA | Integer |  | Nro. Único |  |

## AD_OCORRECIALINCROS — Ocorrencias Lincros
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDOCORRENCIA | Integer |  | IDOCORRENCIA |  |

## AD_OPERADORTES — Operador/saldo/tesouraria
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODUSU | String |  | Código do Usuário |  |
| NUTESOURARIA | Integer |  | Numero do relatorio de tesouraria |  |
| SALDOFINAL | Float |  | Saldo Final |  |
| DIFERENCA | Float |  | Diferença |  |
| TROCO | Float |  | Troco |  |
| TROCAS | Float |  | Trocas R$ |  |
| SANGRIA | Float |  | Sangria |  |
| SALDOINICIAL | Float |  | Saldo Inicial |  |

## AD_ORDEMCARGADESP — Ordem de Carga
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEMCARGA | Integer |  | Ordem de carga |  |
| NUODP | Integer |  | Nro. único |  |

## AD_PAGCARTAOTELEVENDAS — Detalhes Pagamento Televendas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro Único Nota de Venda |  |
| TELEVENDASPOS | String |  | POS |  |
| TELEVENDASTID | String |  | TID |  |
| TELEVENDASNSU | String |  | NSU |  |
| TELEVENDASAUTORIZACAO | String |  | Autorização |  |
| TELEVENDASDOC | String |  | DOC |  |

## AD_PEDCANMKTPLACE — Pedido Cancelado Mktplace
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| STATUS | String |  | Status |  |
| DATA | DateTime |  | Data |  |
| CODVEND | Integer |  | Código Vendedor |  |
| PEDIDOMKTPLACE | String |  | Pedido Marketplace |  |

## AD_PEDIDOBLOQ — Pedido Bloqueado
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nr. Unico |  |
| MOTIVO | String |  | Motivo | `O`=Pedido de Ostensiva `C`=Cancelamento do Pedido |
| NUODP | Integer |  | Nr. Ordem Despacho |  |
| CODUSU | Integer |  | Código Usuário Inclusão |  |

## AD_PLANEJAMENTOHORAS — Planejamento de Horas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| RESPONSAVEL | Integer |  | Responsável |  |
| MES | String |  | Mês | `01`=Janeiro `02`=Fevereiro `03`=Março `04`=Abril `05`=Maio_(+7)_ |
| DISPPROJETO | Float |  | Disponibilidade de Projeto |  |
| PERDA | Float |  | Perda |  |
| SALDO | Float |  | Saldo |  |
| CARGO | String |  | Cargo | `A1`=Analista 1 `A2`=Analista 2 `DV`=Desenvolvedor `SR`=Senior |

## AD_PLANIMPFULL — Gerador de Planilha impostos full
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| DHGER | DateTime |  | Data Hora Geração |  |
| CODUSU | Integer |  | Usuario |  |
| CODEMP | Integer |  | Empresa |  |
| UFORIGEM | Integer |  | UF |  |
| CANAL | String |  | Canal | `ML`=Mercado Livre `AMZ`=Amazon |

## AD_POLITICACOMERCIAL — AD_POLITICA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| POLITICA | String |  | Politica Comercial | `3`=Drogaria SP `2`=BemMePet `1`=Principal |
| CODPROD | Integer |  | Código |  |

## AD_PRECOAMERICANAS — PRECOAMERICANAS
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |

## AD_PRECOAMERICANASEXTREMA — PRECOAMERICANASEXTREMA
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |

## AD_PRECOPORTABELA — Precificação por Tabela
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CATEGORIA | Integer |  | Categoria |  |
| CODGRUPOPROD | Integer |  | Cód. do Grupo Produto |  |
| MARCA | Integer |  | Marca |  |
| CODTAB | Integer |  | Código da Tabela |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARCFORN | Integer |  | Fornecedor |  |

## AD_PRECOPORTABELAV2 — Precificação por Tabela
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODTAB | Integer |  | Código da Tabela |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPARCFORN | Integer |  | Fornecedor |  |
| CATEGORIA | Integer |  | Categoria |  |
| MARCA | Integer |  | Marca |  |
| CODGRUPOPROD | Integer |  | Cód. do Grupo Produto |  |

## AD_PRECOSHOPTIME — PRECOSHOPTIME
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód Produto |  |

## AD_PRECOSHOPTIMEEXTREMA — PRECOSHOPTIMEEXTREMA
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |

## AD_PRECOSUBMARINO — PRECOSUBMARINO
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód Produto |  |

## AD_PRECOSUBMARINOEXTREMA — PRECOSUBMARINOEXTREMA
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |

## AD_PRELANCONT — Pré Lançamento Contábil
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LANCAMENTO | Integer |  | Lançamento |  |
| DESCRLANC | String |  | Descrição Lançamento |  |
| CODEMP | Integer |  | Empresa |  |
| NUMDOC | Integer |  | Núm. Documento |  |
| NUMLANC | Integer |  | Núm. Lançamento |  |
| NUMLOTE | Integer |  | Núm. Lote |  |

## AD_PRELANCONTDET — Pré Lançamento Detalhes
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LANCAMENTO | Integer |  | Lançamento |  |
| CODEMP | Integer |  | Empresa |  |
| NUMLOTE | Integer |  | Núm. Lote |  |
| NUMDOC | Integer |  | Núm. Documento |  |
| NUMLANC | Integer |  | Núm. Lançamento |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TIPLANC | String |  | Tipo Lançamento | `D`=Débito `R`=Crédito |
| CODHIST | Integer |  | Cód. Histórico |  |
| COMPLEMENTO | String |  | Complemento |  |
| VALOR | Float |  | Valor |  |
| CENTRORESULTADO | Integer |  | Centro de Resultado |  |
| CODCTACTB | Integer |  | Conta Contábil |  |

## AD_PREVCHEGADAPROD — Previsão de Compra
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| NUNOTA | Integer |  | Número Único |  |
| APELIDO | String |  | Comprador |  |
| CODEMP | Integer |  | Empresa |  |
| QTDNEG | Integer |  | Quantidade Negociada |  |
| DTPREVENT | String |  | Data Prevista para Entrega |  |
| CODPROD | Integer |  | Código |  |

## AD_PRODLIST — Produtos
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTPRN | Integer |  | Inst. processo |  |
| IDINSTTAR | Integer |  | Inst. tarefa |  |
| CODREGISTRO | Integer |  | Código |  |
| CODPROD | Integer |  | Produto |  |
| QTDNEG | Float |  | Qtd. Negociada |  |
| VLRUNIT | Float |  | Valor Unitário |  |
| VLRTOT | Float |  | Valor Total |  |
| QTDREV | Float |  | Qtd. Reenvio |  |
| IDTAREFA | String |  | Tarefa |  |

## AD_PRODPROC — Relação Produto/Processo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| DESCRPROD | String |  | Descrição Produto |  |
| CODPRC | Integer |  | Processo |  |
| DESCRABREV | String |  | Descrição do Processo |  |
| CODPROD | Integer |  | Produto |  |

## AD_PRODUTOIMPORTADO — Produtos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| PROCESSADO | String |  | Processado | `P`=Pendente `F`=Finalizado |
| VALOR | Float |  | Valor |  |
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Código do Produto |  |
| CODTAB | Integer |  | Código Tabela |  |

## AD_PRODUTOIMPORTADOV2 — Produtos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ORDEM | Integer |  | Ordem |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Código do Produto |  |
| CODTAB | Integer |  | Código Tabela |  |
| VALOR | Float |  | Valor |  |
| PROCESSADO | String |  | Processado | `P`=Pendente `F`=Finalizado |

## AD_PRODUTOPORTABELA — Produtos
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ENTRADACOMICMS | Float |  | Custo de Entrada Cheio |  |
| IMPENTRADA | Float |  | Imposto Entrada % |  |
| IMPFRETECTE | Float |  | Imposto Frete Médio Abs Cte |  |
| CODUSULIBERACAO | Integer |  | Cód. Usuário Liberação |  |
| FRETEGRATIS | String |  | Frete Grátis? | `S`=Sim `N`=Não |
| COMISSAO | Float |  | Comissão Canal Venda (%) |  |
| CODUSUINSERCAO | Integer |  | Cód. Usuário Inserção |  |
| MARGEM | Float |  | Margem de Contribuição (%) |  |
| VALORFINAL | Float |  | Preço Consumidor Final (R$) |  |
| FRETECTEABSO | Float |  | Frete Médio Cte  Absoluto |  |
| PROMOCAO | Float |  | Promoção (%) |  |
| DIFAL | Float |  | DIFAL (%) |  |
| QUANTIDADE | Integer |  | Quantidade |  |
| VLRCOMISSAO | Float |  | Comissão Canal Venda (R$) |  |
| MARGEMBRUTAASSINATURA | Float |  | Margem Bruta Assinatura (%) |  |
| PROCESSADO | String |  | Processado | `P`=Pendente `F`=Processado `E`=Promoção Agendada |
| VLRIMPOSTOMEDIO | Float |  | Imposto Médio (R$) |  |
| VLRFRETEMEDIO | Float |  | Frete Médio Nota Fiscal (R$) |  |
| MARGEMASSINATURA | Float |  | Margem de Contribuição Assinatura (%) |  |
| CUSTOPROD | Float |  | Custo Médio de Produto (R$) |  |
| IMPOSTOMEDIO | Float |  | Imposto Médio (%) |  |
| TAXA | Float |  | Taxa Fixa (R$) |  |
| VLRPROMOCAO | Float |  | Promoção (R$) |  |
| CUSTOPOREMPRESA | String |  | Custo a ser Considerado | `M`=Maior Custo `E`=Extrema `S`=São José dos Campos |
| ESTOQUEEX | Integer |  | Estoque EX |  |
| ESTOQUESJC | Integer |  | Estoque SJC |  |
| GERENCIAL | Float |  | Custo de Entrada Gerencial |  |
| FRETECTE | Float |  | Frete Médio Cte |  |
| VALORFINALASSINATURA | Float |  | Preço Assinatura Final  (R$) |  |
| LIBERADO | String |  | Liberado | `P`=Pendente `S`=Sem solicitação `L`=Liberado `N`=Não Autorizado |
| CODTAB | Integer |  | Código da Tabela |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Cód. Produto |  |
| VALOR | Float |  | Preço (R$) |  |
| MARGEMBRUTA | Float |  | Margem Bruta (%) |  |
| ENTRADASEMICMS | Float |  | Custo de Entrada Creditado |  |
| CUSTOFRETE | Float |  | Frete do Cliente / Custo do Frete (R$) |  |
| VLRCUSTOFRETE | Float |  | Custo de Frete (R$) |  |
| VLRREBATE | Float |  | Rebate (R$) |  |
| CODUSUALTERACAO | Integer |  | Cód. Usuário Alteração |  |
| REBATE | Float |  | Rebate (%) |  |
| CMV | Float |  | C.M.V (R$) |  |
| DESCASSINATURA | String |  | Desconto Assinatura (%) | `10`=10% `15`=15% `20`=20% |
| PRECODEMKT | Float |  | Preço De |  |
| VLRBRINDE | Float |  | Valor Brinde (R$) |  |
| TELEVENDAS | String |  | Comissão Televendas? | `S`=Sim `N`=Não |

## AD_PRODUTOPORTABELAV2 — Produtos
Campos: 46

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODTAB | Integer |  | Código da Tabela |  |
| CODPROD | Integer |  | Cód. Produto |  |
| CODUSUALTERACAO | Integer |  | Cód. Usuário Alteração |  |
| CODUSULIBERACAO | Integer |  | Cód. Usuário Liberação |  |
| PROCESSADO | String |  | Processado | `E`=Promoção Agendada `P`=Pendente `F`=Processado |
| LIBERADO | String |  | Liberado | `L`=Liberado `S`=Sem solicitação `P`=Pendente `N`=Não Autorizado |
| VALOR | Float |  | Preço (R$) |  |
| FRETEGRATIS | String |  | Frete Grátis? | `S`=Sim `N`=Não |
| ESTOQUESJC | Integer |  | Estoque SJC |  |
| ESTOQUEEX | Integer |  | Estoque EX |  |
| VALORFINAL | Float |  | Preço Consumidor Final (R$) |  |
| MARGEM | Float |  | Margem de Contribuição (%) |  |
| MARGEMBRUTA | Float |  | Margem Bruta (%) |  |
| CUSTOFRETE | Float |  | Frete do Cliente / Custo do Frete (R$) |  |
| PROMOCAO | Float |  | Promoção (%) |  |
| QUANTIDADE | Integer |  | Quantidade |  |
| REBATE | Float |  | Rebate (%) |  |
| CUSTOPROD | Float |  | Custo Médio de Produto (R$) |  |
| IMPOSTOMEDIO | Float |  | Imposto Médio (%) |  |
| COMISSAO | Float |  | Comissão Canal Venda (%) |  |
| TAXA | Float |  | Taxa Fixa (R$) |  |
| CMV | Float |  | C.M.V (R$) |  |
| VLRCOMISSAO | Float |  | Comissão Canal Venda (R$) |  |
| VLRIMPOSTOMEDIO | Float |  | Imposto Médio (R$) |  |
| VLRCUSTOFRETE | Float |  | Custo de Frete (R$) |  |
| VLRFRETEMEDIO | Float |  | Frete Médio Nota Fiscal (R$) |  |
| VLRPROMOCAO | Float |  | Promoção (R$) |  |
| VLRREBATE | Float |  | Rebate (R$) |  |
| DIFAL | Float |  | DIFAL (%) |  |
| PRECODEMKT | Float |  | Preço De |  |
| VLRBRINDE | Float |  | Valor Brinde (R$) |  |
| DESCASSINATURA | String |  | Desconto Assinatura (%) | `10`=10% `15`=15% `20`=20% |
| VALORFINALASSINATURA | Float |  | Preço Assinatura Final  (R$) |  |
| MARGEMASSINATURA | Float |  | Margem de Contribuição Assinatura (%) |  |
| MARGEMBRUTAASSINATURA | Float |  | Margem Bruta Assinatura (%) |  |
| CUSTOPOREMPRESA | String |  | Custo a ser Considerado | `E`=Extrema `S`=São José dos Campos `M`=Maior Custo |
| TELEVENDAS | String |  | Comissão Televendas? | `S`=Sim `N`=Não |
| GERENCIAL | Float |  | Custo de Entrada Gerencial |  |
| ENTRADASEMICMS | Float |  | Custo de Entrada Creditado |  |
| ENTRADACOMICMS | Float |  | Custo de Entrada Cheio |  |
| IMPENTRADA | Float |  | Imposto Entrada % |  |
| FRETECTE | Float |  | Frete Médio Cte |  |
| FRETECTEABSO | Float |  | Frete Médio Cte  Absoluto |  |
| IMPFRETECTE | Float |  | Imposto Frete Médio Abs Cte |  |
| CODUSUINSERCAO | Integer |  | Cód. Usuário Inserção |  |

## AD_PROMOCAOTABELA — Produtos - Promoção Agendada
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINI | Date |  | Início da Promoção |  |
| PROCESSADO | String |  | Processado | `N`=Pausado `F`=Finalizado `E`=Em execução `P`=Pendente |
| CODUSUINSERCAO | Integer |  | Código Usuário Inserção |  |
| VLRPROMOCAO | Float |  | Valor Promoção |  |
| DTFIN | Date |  | Final da Promoção |  |
| CODUSU | Integer |  | Código Usuário Alteração |  |
| VLRVENDA | Float |  | Valor Venda |  |
| CODTAB | Integer |  | Código da Tabela |  |
| SEQUENCIA | Integer |  | Sequência |  |
| CODPROD | Integer |  | Código do Produto |  |

## AD_PROMOCAOTABELAV2 — Produtos - Promoção Agendada
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| CODTAB | Integer |  | Código da Tabela |  |
| CODPROD | Integer |  | Código do Produto |  |
| DTFIN | Date |  | Final da Promoção |  |
| VLRVENDA | Float |  | Valor Venda |  |
| VLRPROMOCAO | Float |  | Valor Promoção |  |
| PROCESSADO | String |  | Processado | `P`=Pendente `E`=Em execução `F`=Finalizado `N`=Pausado |
| CODUSUINSERCAO | Integer |  | Código Usuário Inserção |  |
| CODUSU | Integer |  | Código Usuário Alteração |  |
| DTINI | Date |  | Início da Promoção |  |

## AD_RECENCIA — RECENCIA
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | CODIGO |  |
| CANAL | String |  | CANAL |  |
| VLRMAX | Integer |  | VLR. MAXIMO |  |
| VLRMIN | Integer |  | VLR. MINIMO |  |

## AD_REFPAYMEE — ReferenciaPaymee
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| CODUSU | Integer |  | Usuário |  |

## AD_REGDETRATOR — Registro de Detrator
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| DTINICIO | Date |  | Data Inicio |  |
| DTFIM | Date |  | Data Fim |  |
| ENVIAMENSAGEM | String |  | Envia Mensagem | `S`=Sim `N`=Não |
| MOTIVO | String |  | Motivo |  |
| IDEMAIL | Integer |  | Ultimo Email de Compra |  |
| CODPARC | Integer |  | Parceiro |  |

## AD_REPASSESKONCILICAB — Repasses Koncili
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NROCONCILIACAO | Integer |  | Número Conciliação |  |
| NROPEDIDO | String |  | Núm. Pedido |  |
| DHCONCILIACAO | DateTime |  | Data Conciliação |  |
| EMPRESA | Integer |  | Empresa |  |
| NUNOTA | Integer |  | Nr. Unico |  |
| STATUS | String |  | Status |  |
| DTPROCESSAMENTO | Date |  | Dt Processamento |  |
| TESTE | String |  | TESTE |  |
| ORDERID | String |  | ORDERID |  |
| DATABAIXACONC | Date |  | Data de Baixa para Konciliação |  |
| JOB | String |  | Job | `4`=4 `2`=2 `3`=3 `1`=1 |
| MARKETPLACE | String |  | MarketPlace |  |

## AD_REPASSESKONCILIDET — Repasses Koncili Detalhe
Campos: 51

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NROPEDIDO | String |  | Núm. Pedido |  |
| ID | Integer |  | Id Koncili |  |
| NROCONCILIACAO | Integer |  | Número Conciliação |  |
| CHANNELSTATUS | String |  | channelStatus |  |
| INTERNALSTATUS | String |  | internalStatus |  |
| ORDERCODE | String |  | orderCode |  |
| ORDERDATE | DateTime |  | orderDate |  |
| PAIDDATE | DateTime |  | paidDate |  |
| INVOICENUMBER | String |  | invoiceNumber |  |
| INVOICEDATE | Date |  | invoiceDate |  |
| SENTDATE | DateTime |  | sentDate |  |
| ORDERID | String |  | orderId |  |
| ORIGIN | String |  | origin |  |
| PLOTVALUE | Float |  | plotValue |  |
| TOTALVALUE | Float |  | totalValue |  |
| PLOTSQUANTITY | Integer |  | plotsQuantity |  |
| PLOTNUMBER | Integer |  | plotNumber |  |
| EXTRACTTYPE | String |  | extractType |  |
| EXPECTEDVALUE | Float |  | expectedValue |  |
| RELEASEDVALUE | Float |  | releasedValue |  |
| EXPECTEDPERCENTUALCOMISSION | Float |  | expectedPercentualComission |  |
| EXPECTEDDATE | Date |  | expectedDate |  |
| RELEASEDDATE | Date |  | releasedDate |  |
| SITUATION | String |  | situation |  |
| CONCILIED | String |  | concilied |  |
| OBSERVATION | C |  | observation |  |
| CHANNEL | String |  | channel |  |
| RESOLVEDINERP | String |  | resolvedInERP |  |
| ORDERIDHUBORIGIN | String |  | orderIdHubOrigin |  |
| ACCOUNTNAME | String |  | accountName |  |
| CUSTOMERNAME | String |  | customerName |  |
| CUSTOMERDOCUMENTNUMBER | String |  | customerDocumentNumber |  |
| CONCILIATIONINITDATE | Date |  | conciliationInitDate |  |
| CONCILIATIONENDDATE | Date |  | conciliationEndDate |  |
| CONCILIATIONCLOSEDATE | DateTime |  | conciliationCloseDate |  |
| PARTIALCONCILIED | String |  | partialConcilied |  |
| ORIGINALVALUE | Float |  | originalValue |  |
| PAYMENTMETHOD | String |  | paymentMethod |  |
| CONCILIATIONID | Integer |  | conciliationId |  |
| RELEASEDPERCENTUALCOMISSION | Float |  | ReleasedPercentualComission |  |
| NUFIN | Integer |  | Nr. Unico |  |
| LIBERACAO | String |  | Liberação |  |
| VLRDESDOB | Float |  |  Vlr Desdobramento Titulo |  |
| CODCTABCOINT | Integer |  | Conta de Baixa |  |
| NUFINNOVO | Integer |  | Nr. Unico Fin Novo |  |
| VLRDIF | Float |  | Valor Diferença |  |
| DTPROCESSAMENTO | Date |  | Dt Processamento |  |
| NUNOTA | Integer |  | Nr. Unico Nota |  |
| MARKETPLACE | String |  | MARKETPLACE |  |
| TIPODEPROCESSAMENTO | String |  | Tipo de Processamento |  |
| OI | String |  | oi |  |

## AD_RETITAUPIXCAB — Retorno Itau - Pix
Campos: 39

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |
| TIPOREGISTRO | String |  | Tipo Registro |  |
| IDENTIFICADOR | String |  | Identificador |  |
| IBSPARTICIPANTE | String |  | Ibs Participante |  |
| TIPOPESSOA | String |  | Tipo Pessoa |  |
| CPFCNPJ | String |  | Cpf Cnpj |  |
| AGENCIA | String |  | Agencia |  |
| CONTA | String |  | Conta |  |
| TIPOCONTA | String |  | Tipo Conta |  |
| CHAVEPIX | String |  | Chave Pix |  |
| TIPOCOBRANCA | String |  | Tipo Cobranca |  |
| CODMOVIMENTO | String |  | Cod Movimento |  |
| DTMOVIMENTO | String |  | Dt Movimento |  |
| DTVENCIMENTO | String |  | Dt. Vencimento |  |
| DHPAGAMENTO | String |  | Dh. Pagamento |  |
| VALORORIGINAL | String |  | Valor Original |  |
| VALORJUROS | String |  | Valor Juros |  |
| VALORMULTA | String |  | Valor Multa |  |
| VALORABATIMENTO | String |  | Valor Abatimento |  |
| VALORDESCONTO | String |  | Valor Desconto |  |
| VALORFINAL | String |  | Valor Final |  |
| VALORPAGO | String |  | Valor Pago |  |
| TIPOPESSOADEVEDOR | String |  | Tipo Pessoa Devedor |  |
| CPFCNPJDEVEDOR | String |  | Cpf Cnpj Devedor |  |
| TIPOPESSOAPAGADORFINAL | String |  | Tipo Pessoa Pagador Final |  |
| CPFCNPJPAGADORFINAL | String |  | Cpf Cnpj Pagador Final |  |
| NOMEPAGADORFINAL | String |  | Nome Pagador Final |  |
| MENSAGEMPAGADORFINAL | String |  | Mensagem Pagador Final |  |
| BRANCO | String |  | Branco |  |
| ENDTOENDID | String |  | End To End Id |  |
| REVISAO | String |  | Revisao |  |
| EXCLUSIVOPSPRECEBEDOR | String |  | Exclusivo Psp Recebedor |  |
| ZEROS | String |  | Zeros |  |
| NROSEQUENCIAL | String |  | Nro Sequencial |  |
| STATUSPIX | String |  | Status Pix | `P`=P - Conciliação Pendente `B`=B - Baixado |
| LOG | String |  | Log |  |
| NUFIN | Integer |  | Nro. Unico Financeiro |  |
| VALORAJUSTADO | Float |  | Valor Ajustado |  |
| DHPROCESSAMENTO | DateTime |  | Dh. Processamento |  |

## AD_RGESTETICA — Resgistro do centro de estetica
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | PK |  |
| EMAIL | String |  | Email do Usuario |  |
| TELEFONE | String |  | Telefone do Usuario |  |
| DTREGISTRO | DateTime |  | Data do Registro |  |
| NVACESSO | Integer |  | Nivel de Acesso |  |
| SENHA | String |  | Senha do Usuario |  |
| NOME | String |  | Nome Completo |  |

## AD_SALDOIMPOSTOS — Saldos de impostos das empresas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ANO | Integer |  | ANO |  |
| ICMS | Float |  | Saldo de ICMS no fim do ano |  |
| PIS | Float |  | Saldo de PIS no fim do ano |  |
| COFINS | Float |  | Saldo de Cofins no fim do ano |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## AD_SEPARPED — Separação de Pedido
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nr Unico |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| QTDCONFERIDA | Float |  | Qtd Conferida |  |
| STATUS | String |  | Status |  |

## AD_SHOPEE — SHOPEE
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Código |  |
| ID | Integer |  | ID |  |
| IDSHOPEE | Integer |  | IDSHOPEE |  |
| NAME | String |  | Nome do Produto |  |
| DESCRIPTION | C |  | Descrição do Produto |  |
| DAYS_TO_SHIP | Integer |  | Dias para entrega |  |
| IS_PRE_ORDER | String |  | Pré Venda | `true`=Sim `false`=Não |
| CATEGORY_ID | Integer |  | Código da Categoria |  |
| PRICEMIN | Float |  | Preço Mínimo (Faixa de Preço) |  |
| PRICEMAX | Float |  | Preço Máximo (Faixa de Preço) |  |
| ACTIVE | String |  | Produto Ativo | `S`=Sim `N`=Não |
| ENVPRICE | String |  | Preço Enviado | `S`=Sim `N`=Não |
| ENVSTK | String |  | Estoque Enviado | `S`=Sim `N`=Não |
| STATUSENVPROD | C |  | Status Envio do Item |  |
| ENABLEDLOGISTIC | String |  | Status Transportadora | `true`=Ativo `false`=Inativo |
| UNIT_PRICE | Float |  | Preço Produto |  |
| PERCENTSTK | String |  | % Estoque |  |
| ENVPROD | String |  | Produto Enviado | `S`=Sim `N`=Nao |
| RESPONSEPROD | C |  | Retorno cadastro Produto |  |
| ITEM_ID | String |  | Id Produto Shopee |  |
| ITEMID | Integer |  | Id Produto na Shopee |  |
| LOGISTICID | Integer |  | Transportadora | `90003`=Correios `96109075`=Sequoia BR `90005`=Total Express BR `91003`=Shopee Xpress |
| MULTIPLICADOR | Integer |  | Multiplicador |  |
| CODLOCAL | Integer |  | Cód. Local Estoque |  |
| PORLOCAL | String |  | Por Local? | `S`=Sim `N`=Não |
| ESTOQUE | Integer |  | Estoque Fixo |  |
| CODTAB | Integer |  | Código Tab. Preço |  |
| TABPRECO | String |  | Por Tabela de Preço? | `S`=Sim `N`=Não |
| STATUS | String |  | Produto Enviado para Integração | `S`=Sim `N`=Não |
| ALTURA | Float |  | ALTURA |  |
| LARGURA | Float |  | LARGURA |  |
| ESPESSURA | Float |  | ESPESSURA |  |
| PESOBRUTO | Float |  | PESOBRUTO |  |
| CODVEND | Integer |  | Código Vendedor |  |
| UPDATESTK | String |  | Estoque Enviado | `S`=Sim `N`=Não |
| ITEM_SKU | Integer |  | Código do Produto |  |

## AD_SHOPEECOLETAS — SHOPEECOLETAS
Campos: 8

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | id |  |
| CODVEND | Integer |  | CODVEND |  |
| DATAHORAATUALTUAL | DateTime |  | DATA DE SOLICITAÇÃO COLETA |  |
| NUNOTA | Integer |  | NUNOTA |  |
| TRACKINGSHOPEE | String |  | Tracking Number Shopee |  |
| TYPE | String |  | type |  |
| DROPOFF | String |  | DROPOFF |  |
| ORDERID | String |  | orderid |  |

## AD_SLA — Configuração SLA
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DIASEMANA | Integer |  | DIA DA SEMANA |  |
| FIM | Text |  | Hora de Fim |  |
| INICIO | Text |  | Hora de Inicio |  |

## AD_STATUSTRANSP — Status de Transporte
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | id |  |
| STATUS | String |  | Status |  |
| DTDESPACHO | DateTime |  | Data Despacho |  |
| DTSAIUENTREGA | DateTime |  | Data Saida Entrega |  |
| DTTRANSITO | DateTime |  | Data em Trânsito |  |
| DTENTREGA | DateTime |  | Data de Entrega |  |
| DTCANCELADO | DateTime |  | Data de Cancelamento |  |
| NUNOTA | String |  | Numero Unico |  |
| DATAALTER | DateTime |  | Data Alteração |  |

## AD_STOKKICAB — Cab Pedido Stokke
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nr. Unico |  |
| RAZAOSOCIALEMP | String |  | Razao Social Empresa |  |
| TIPPESSOA | String |  | Tipo de documento pessoa fisica/juridica |  |
| NOMECLIENTE | String |  | Nome do Cliente |  |
| CODPARC | Float |  | Codigo do Parceiro |  |
| DOC | Float |  | cpf/cnpj |  |
| EMAIL | String |  | Email |  |
| TELEFONE | Float |  | Telefone |  |
| CEP | Integer |  | Cep |  |
| LOGRADOURO | String |  | Logradouro |  |
| NUMEND | Integer |  | Nomero do endereço |  |
| BAIRRO | String |  | Bairro |  |
| CIDADE | String |  | Cidade |  |
| UF | String |  | Uf |  |
| SKU | Integer |  | Sku do produto |  |
| SEQUENCIA | Integer |  | sequencia do item |  |
| QUANTIDADE | Integer |  | Quantidade dos itens/sku |  |
| DESCRICAO | String |  | Descrição da sku |  |
| XMLNOTA | C |  | xml da nota  |  |
| TRACKING | Integer |  | Códgo de rastreio |  |
| PARCTRANSP | String |  | nome do parceiro transportador |  |
| CNPJTRANSP | Integer |  | Cnpj da transportadora |  |
| CNPJEMP | Integer |  | CNPJ Empresa |  |

## AD_SYNCINTELIPOST — Sincronização Intelipost
Campos: 36

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Numero Unico |  |
| VLRFRETE | Float |  | Valor do Frete |  |
| CANAL | String |  | canal |  |
| IDMETODO | Integer |  | ID do metodo de Envio |  |
| NOMEPARC | String |  | Nome Parceiro |  |
| EMAIL | String |  | Email |  |
| TELEFONE | String |  | telefone |  |
| CPF | String |  | CPF |  |
| UF | String |  | uf |  |
| NOMECID | String |  | Cidade |  |
| NOMEEND | String |  | Endereço |  |
| NUMEND | String |  | Numero Endereço |  |
| NOMEBAI | String |  | Bairro |  |
| COMPLEMENTO | String |  | complemento |  |
| CEP | String |  | CEP |  |
| SERIENOTA | String |  | serie nota |  |
| CHAVENFE | String |  | chave nfe |  |
| VLRNOTA | Float |  | Valor Nota |  |
| BH_DTENTREGA | Date |  | Previsao de Entrega |  |
| NUMNOTA | Float |  | Numero da Nota |  |
| STATUS | Integer |  | Status |  |
| QTDTENTATIVAS | Integer |  | Qtd Tentativas |  |
| RESPONSE | String |  | Resposta de Erro Intelipost |  |
| TRACKING | String |  | Tracking |  |
| CODEMP | Integer |  | Cod Empresa |  |
| BH_CODMKT | String |  | BH_CODMKT |  |
| DATAENTREGACORRETA | DateTime |  | DATAENTREGACORRETA |  |
| DTPEDIDO | Date |  | Data do Pedido |  |
| VOLUME | Integer |  | Volume |  |
| STATUSDESP | String |  | Status Despachado |  |
| QTDTENTATIVASDESP | Integer |  | Qtd tentaivas Despac |  |
| RESPONSEDESP | String |  | Resposta integração despachado |  |
| JSON | String |  | json |  |
| URLETIQUETA | String |  | Url Etiqueta |  |
| DTPREVENTTRANSP | Date |  | Dt. Prev. Ent.Transp. |  |
| DTNEG | Date |  | Data de Negociação |  |

## AD_T1 — t1
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID1 | Integer |  | id1 |  |
| ID2 | Integer |  | id2 |  |

## AD_TABELAGETNET — Baixas GetNet
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| TIPO | String |  | Tipo | `1`=e-commerce `3`=Link de Pagamento `2`=Loja - TEF `4`=Planilha |
| ADQUIRENTE | String |  | Adquirente | `GETNET`=GETNET `REDE`=REDE `PAGARME`=PAGARME `CIELO`=CIELO |
| DATA | Date |  | Data de Inserção |  |

## AD_TABELAGETNETLOJA — Baixas GetNet Loja
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DATA | Date |  | Data de Inserção |  |

## AD_TABELAIFOOD — Ifood - Importador
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DATA | Date |  | Data de Inserção |  |

## AD_TABELAKOIN — Koin - Importador
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |

## AD_TABELAPAGARME — Pagarme - Importador
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequência |  |
| DATA | Date |  | Data de Inserção |  |

## AD_TDBASSINATURASTATUS — Status Ciclo
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | String |  | ID |  |
| IDCONTRATO | String |  | ID Contrato |  |
| DATEASS | DateTime |  | date |  |
| MESSAGE | String |  | message |  |
| DATA | DateTime |  | DATA |  |
| STATUS | String |  | status |  |

## AD_TDBBFC — Fechamento Cont/Fislc. Tudo Bicho
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Referência |  |
| TIPO | String |  | Tipo | `F`=Financeiro `C`=Contábil `I`=Fiscal `M`=Movimentações |
| CODUSU | Integer |  | Cód Usuário |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |

## AD_TDBFECHACTE — Fechamento CTE
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| DTVENC | Date |  | Data de Vencimento |  |
| DATAINICIO | Date |  | Data Inicio |  |
| DATAFIM | Date |  | Data Fim |  |
| NRCTE | String |  | Nr CTE |  |
| NUNOTAFECHAMENTO | Integer |  | Nr. Unico Nota de Fechamento |  |
| VLRFECHAMENTO | Float |  | Vlr Fechamento |  |
| VLRAPURACAO | Float |  | Valor Apuração |  |
| NRCTENAOENCONTRADO | String |  | Nr. CTE Não encontrado |  |
| CODPARC | Integer |  | Transportadora |  |

## AD_TDBWMSFIFO — Controle WMS FIFO
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOTA | Integer |  | Numero Único da Nota |  |
| CODEMP | Integer |  | Código da Empresa |  |

## AD_TDBWMSFIFOITENS — Itens
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| LOTE | String |  | Lote da Compra |  |
| NOTA | Integer |  | Numero da Nota |  |
| SKU_ID_ITENS | Integer |  | SKU do Produto |  |
| QTDPRODUTO | Integer |  | Quantidade de Produto |  |
| VALIDADE_PRODUTO | Date |  | Validade do Produto |  |

## AD_TDBXMLFULL — XML Full
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| XML2 | C |  | xml2 |  |
| LOG | String |  | LOG |  |
| DHALTER | DateTime |  | Data Alteração |  |
| NUMNOTA | String |  | Nr. Nota |  |
| XML | C |  | XML |  |

## AD_TELEVENDASDIARIO — Diário - Televendas
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIOSEMANA | Date |  | Data Início da Semana |  |
| DTDIARIO | Date |  | Data |  |
| DTINICIOMES | Date |  | Data Início do Mês |  |
| CLIENTESATENDIDOS | Integer |  | Clientes Atendidos |  |

## AD_TELEVENDASSEMANAL — Semanal - Televendas
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIOSEMANA | Date |  | Data Início da Semana |  |
| DTINICIOMES | Date |  | Data Início do Mês |  |
| METASEMANAL | Float |  | Meta Semanal |  |
| TAXASEMANAL | Float |  | Taxa Semanal (%) |  |
| NUMSEMANA | Integer |  | Numeração Semanal |  |

## AD_TELSERV — Serviços
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Serviço |  |
| RECORRENCIA | String |  | Recorrencia | `S`=Sim `N`=Não |
| VALOR | Float |  | valor |  |
| PRAZOREC | Integer |  | Prazo Recorrencia (Dias) |  |
| NUREL | Integer |  | Nro. Único |  |

## AD_TEMPOSLA — TEMPOSLA
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| URGENCIA | String |  | Urgencia |  |
| TEMPO | Integer |  | Tempo |  |

## AD_TEMPPRODMAGALU — TEMPPRODMAGALU
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | sequencia |  |
| CODPROD | Integer |  | Código |  |

## AD_TGFCAB — Acompanhamento de Pedido
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| FURO | String |  | Informações de Furo |  |
| NUNOTA | Integer |  | Nro. Único |  |

## AD_TGFMAR — Marca
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| MARCA | String |  | Marca |  |
| CODMARCA | Integer |  | Codigo da marca |  |

## AD_TGFPRO — Produtos Produzidos
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Código |  |
| USOPROD | String |  | Usado Como |  |
| DESCRPROD | String |  | Descrição |  |

## AD_TGFVALFISCAL — Validação Fiscal de Impostos/Cadastro
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| CHAVE | String |  | CHAVE |  |
| STATUS | String |  | Status | `P`=Pendente `C`=Concluido |
| CODUSULIB | Integer |  | Usuario Liberador |  |
| CODUSUSOL | Integer |  | Usuario Solicitante |  |
| DATASOL | DateTime |  | Data Solicitação |  |
| DATALIB | DateTime |  | Data Liberação |  |
| OBSERVACAO | String |  | Observação |  |
| MOTIVO | String |  | Motivo |  |
| TABELA | String |  | TABELA |  |

## AD_TGFVAR — Ligação Varios Produtos
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | NUNOTA |  |
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| CODPROD | Integer |  | CODPROD |  |
| SEQUENCIAORIG | Integer |  | SEQUENCIAORIG |  |
| CODPRODORIG | Integer |  | CODPRODORIG |  |
| NUNOTAORIG | Integer |  | NUNOTAORIG |  |

## AD_TIPNSUCIELO — Tipo de Lançamento NSU
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| CODEMP | Integer |  | Empresa |  |
| ACAO | String |  | Ação | `C`=Criar e Baixa `B`=Baixar a Venda Integral `D`=Baixa Devolução `P`=Baixar a Venda Parcela `N`=Nada |
| RECDESP | String |  | Receita ou Despesa | `1`=Receita `-1`=Despesa |
| CODCTACTB | Integer |  | Conta de Baixa |  |
| CODNAT | Integer |  | Natureza |  |
| CODTIPOPERBAIXA | Integer |  | Tipo de Operação Baixa |  |
| CODPARC | Integer |  | Parceiro |  |
| CODTIPOPER | Integer |  | Tipo de Operação Lançamento |  |

## AD_TIPOASSINATURA — Tipo de assinatura
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDTIPO | Integer |  | Id do tipo de assinatura |  |
| OBRIGATORIO | String |  | Obrigatório | `S`=sim `N`=nao |
| STATUS | String |  | Status | `INACTIVE`=Inativo `ACTIVE`=Ativo |
| NOME | String |  | Nome do tipo de Assinatura |  |

## AD_TIPOGETNET — GetNet - Tipo de Lançamento
Campos: 11

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| CODEMP | Integer |  | Empresa |  |
| ACAO | String |  | Ação | `B`=Baixar a Venda Integral `P`=Baixar a Venda Parcela `C`=Criar e Baixa `D`=Baixa Devolução `N`=Nada_(+1)_ |
| RECDESP | String |  | Receita ou Despesa | `-1`=Despesa `1`=Receita |
| CODCTACTB | Integer |  | Conta de Baixa |  |
| CODNAT | Integer |  | Natureza |  |
| CODTIPOPERBAIXA | Integer |  | Tipo de Operação Baixa |  |
| CODPARC | Integer |  | Parceiro |  |
| TIPOARQ | String |  | Tipo de Arquivo | `1`=e-commerce `2`=Loja - TEF `3`=Link de Pagamento |
| ADQUIRENTE | String |  | Adquirente | `REDE`=REDE `GETNET`=GETNET `PAGARME`=PAGARME |
| CODTIPOPER | Integer |  | Tipo de Operação Lançamento |  |

## AD_TIPOPAGARME — Pagarme - Tipo de Lançamento
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| TIPO | String |  | Tipo |  |
| CODEMP | Integer |  | Empresa |  |
| CODNAT | Integer |  | Natureza |  |
| CODPARC | Integer |  | Parceiro |  |
| CODTIPOPER | Integer |  | Tipo de Operação Lançamento |  |
| CODTIPOPERBAIXA | Integer |  | Tipo de Operação Baixa |  |
| RECDESP | String |  | Receita ou Despesa | `1`=Receita `-1`=Despesa |
| ACAO | String |  | Ação | `B`=Baixar a Venda Integral `D`=Baixa Devolução `P`=Parcial `N`=Nada |
| CODCTACTB | Integer |  | Conta de Baixa |  |

## AD_TITPAYMEE — TitulosPaymee
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Referência |  |
| NROUNICO | Integer |  | Nro. Unico Integração |  |
| SITUATION | String |  | Situação |  |
| VLRDISCOUNTS | Float |  | Vlr. Descontos |  |
| VLRTOTAL | Float |  | Vlr. Total |  |
| VLRAPPLIEDRATE | Float |  | Vlr. Taxa |  |
| REFERENCECODE | String |  | Cód. Referência Paymee |  |
| DTCREATION | DateTime |  | Data Criação |  |
| PROCESSINGDATE | DateTime |  | Data de Processamento |  |
| NAME | String |  | Nome |  |
| EMAIL | String |  | E-mail |  |
| DOCUMENT | String |  | Documento |  |
| BANK | String |  | Banco |  |
| BRANCH | String |  | Agencia |  |
| ACCOUNT | String |  | Conta |  |
| PEDIDOMKT | String |  | Pedido |  |
| NUFIN | Integer |  | Nro. Único Financeiro |  |
| TYPE | String |  | Tipo |  |
| LIBERACAO | String |  | Liberação |  |
| NUFIN2 | Integer |  | Nro Único Vlr. Excedente |  |
| VLRDESDOB | Float |  | Vlr. Título Sankhya |  |
| CODCTABCOINT | Integer |  | Cód. Conta Sankhya |  |
| ID | Integer |  | Id Paymee |  |

## AD_TRANSFASSINATURA — Transferencia de pedidos de assinatura
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| DTTRANSF | Date |  | Dt. Transferência |  |
| NEXTPURCHASEDATE | Date |  | Dt. Proximo Ciclo |  |
| NUNOTATRANF | Integer |  | Nro. Unico. Transferência |  |

## AD_TRANSFASSINATURADET — Pedidos de Transferencia Detalhe
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDDETALHE | Integer |  | IDDETALHE |  |
| ID | Integer |  | ID |  |
| CUSTOMEREMAIL | String |  | Email do cliente |  |
| STATUS | String |  | Status |  |
| IDCONTRATO | String |  | Id Contrato |  |

## AD_TRANSP — Transportadoras
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| METODO | String |  | Metodo |  |
| DESCRAMAZON | String |  | Descrição Amazon |  |
| CODPARC | Integer |  | Parceiro |  |

## AD_TXTREDECAB — TXTREDECAB
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| ARQUIVO | Boolean |  | Arquivo |  |
| TIPOARQUIVO | String |  | Tipo de Arquivo | `E`=Modelo em Excel `T`=Modelo de Texto |
| DATA | Date |  | Data |  |

## AD_TXTREDEDET — LOGTXT
Campos: 158

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQLOG | Integer |  | Sequencia Log |  |
| SEQUENCIA | Integer |  | Sequencia |  |
| HEADERDTEMI | Date |  | Data de Emissão |  |
| HEADEREXTVEN | String |  | Extrato Eletronico de Vendas |  |
| HEADERNOMECOM | String |  | Nome comercial (grupo/matriz) |  |
| HEADERSEQMOV | Integer |  | Seq. Movimento |  |
| HEADERPVMATRIZ | Integer |  | Nro. PV grupo ou matriz |  |
| HEADERTIPMOV | String |  | Tipo Mov. |  |
| HEADERVERSAOARQ | String |  | Versão do arquivo |  |
| HEADERLIVRE | String |  | Livre |  |
| HMTIPREG | Integer |  | 004 - Tipo Registro |  |
| HMPVMATRIZ | String |  | Nro PV matriz |  |
| HMNOMECOM | String |  | Nome comercial da matriz |  |
| RV10TIPREG | Integer |  | R10 - Tipo de registro |  |
| RV10NUMPV | Integer |  | R10 - Nro. PV |  |
| RV10NUMRV | Integer |  | R10 - Nro. RV |  |
| RV10NUMBCO | Integer |  | R10 - Nro. Banco |  |
| RV10NUMAGE | Integer |  | R10 - Nro. Agencia |  |
| RV10NUMCC | Integer |  | R10 - Nro. CC |  |
| RV10DTRV | Date |  | R10 - Dt. RV |  |
| RV10QTDCVNSU | Integer |  | R10 - Qtd. CV/NSU |  |
| RV10VLRBRUTO | Float |  | R10 - Valor Bruto |  |
| RV10VLRGOR | Float |  | R10 - Vlr. Gorjeta |  |
| RV10VLRRE | Float |  | R10 - Vlr. Rejeitado |  |
| RV10VLRDESC | Float |  | R10 - Vlr. Desconto |  |
| RV10VLRLIQ | Float |  | R10 - Vlr. Liq. |  |
| RV10DTCRED | Date |  | R10 - Dt. Créd. Parcela 1 |  |
| RV10BANDEIRA | String |  | R10 - Bandeira |  |
| RV12TIPREG | Integer |  | R12 - Tipo de registro |  |
| RV12NUMPV | Integer |  | R12 - Nro. PV |  |
| RV12NUMRV | Integer |  | R12 - Nro. RV |  |
| RV12CVNSU | Date |  | R12 - Dt. CV/NSU |  |
| R12CVNSU | Float |  | R12 - Vlr. CV/NSU |  |
| R12VLRGOR | Float |  | R12 - Vlr. Gorjeta |  |
| R12NUMCARTAO | String |  | R12 - Nro. Cartao |  |
| R12STATUSCVNSU | String |  | R12 - Status do CV/NSU |  |
| R12NUMPAR | Integer |  | R12 - Nro. Parcelas |  |
| R12NUMCVNSU | Integer |  | R12 - Nro. CV/NSU |  |
| R12NUMREF | String |  | R12 - Nro. Ref. |  |
| R12VLRDESC | Float |  | R12 - Vlr Des. Total |  |
| R12NUMAUT | String |  | R12 - Num Autorizacao |  |
| R12HRTRAN | Integer |  | R12 - Hr. Transacao |  |
| R12NUMBILHETE | String |  | R12 - Nro. Bilhete |  |
| R12TIPCAP | String |  | R12 - Tipo de Captura |  |
| R12VLRLIQCVNSU | Float |  | R12 - Vlr. Liq. CV/NSU |  |
| R12VLRPRIMEIRAPAR | Float |  | R12 - Vlr. Liq. Parcela 1 |  |
| R12VLRLIQDEMAIS | Float |  | R12 - Vlr. Liq. Demais Parcelas |  |
| R12NUMTERMINAL | String |  | R12 - Nro. Terminal |  |
| R12SIGLAPAIS | String |  | R12 - Sigla País |  |
| R12BANDEIRA | String |  | R12 - Bandeira |  |
| R12VLRDESCTAXAFLEX | Float |  | R12 - Vlr. Desc. - Taxa Flex |  |
| R12VLRDESCTAXAMDR | Float |  | R12 - Vlr. Desc. - Taxa MDR |  |
| R12CODIGOSERVICO | Integer |  | R12 - Cód. Servico |  |
| R14TIPREG | Integer |  | R14 - Tipo de registro |  |
| R14NUMPV | Integer |  | R14 - Nro. PV |  |
| R14NUMRV | Integer |  | R14 - Nro. RV |  |
| R14DTRV | Date |  | R14 - Dt. RV |  |
| R14NUMPARCELA | Integer |  | R14 - Nro. Parcela |  |
| R14VLRPARCTOT | Float |  | R14 - Vlr. Parcela Bruto |  |
| R14VLRDESCPAR | Float |  | R14 - Vlr. Desc. s/ Parcela |  |
| R14VLRPARLIQ | Float |  | R14 - Vlr. Parcela Liq. |  |
| R14DTCRED | Date |  | R14 - Dt. Cred. |  |
| R26TIPREG | Integer |  | R26 - Tipo Registro |  |
| R26PVMATRIZ | String |  | R26 - Nro. PV matriz |  |
| R26VLRTOTBRU | Float |  | R26 - Vlr. Tot. Bruto |  |
| R26QTDCVNSU | Integer |  | R26 - Qtd. CV/NSU Rej. |  |
| R26VLRRE | Float |  | R26 - Vlr. Tot. Rej |  |
| R26VLRTOTROT | Float |  | R26 - Vlr. Tot. Rotativo |  |
| R26VLRTOTPARSEMJUROS | Float |  | R26 - Vlr. Tot. Parc. s/ juros |  |
| R26VLRTOTIATA | Float |  | R26 - Vlr Tot. Parc. IATA |  |
| R26VLRTOTDOLAR | Float |  | R26 - Vlr. Total Dolar |  |
| R26VLRTOTDESC | Float |  | R26 - Vlr. Tot. Desc. |  |
| R26VLRTOTLIQ | Float |  | R26 - Vlr. Tot. Liq |  |
| R26VLRTOTGOR | Float |  | R26 - Vlr Tot. Gorjeta |  |
| R26VLRTOTTAXEMBARQ | Float |  | R26 - Vlr Tot Tx Embarque |  |
| R26QTDCVNSUACA | Integer |  | R26 - Qtd CV/NSU acatados |  |
| HEADERREDE | String |  | Rede |  |
| R35DTCVNSU | Date |  | R35 - Dt CV / NSU |  |
| R35VLRCVNSU | Float |  | R35 - Vlr. CV / NSU |  |
| R18HRTRAN | Integer |  | R18 - Hora da transação |  |
| R16NROCC | Integer |  | R16 - Nro da conta-corrente |  |
| R16VLRLIQ | Float |  | R16 - Valor líquido |  |
| R17DTCONSULTA | Date |  | R17 - Data da consulta |  |
| R18TIPREG | Integer |  | R18 - Tipo de registro |  |
| R18NROCARTAO | String |  | R18 - Número do cartão |  |
| R18STATUSCVNSU | String |  | R18 - Status CV/NSU |  |
| R18NROCVNSU | Integer |  | R18 - Número do CV/NSU |  |
| R18VLRDESC | Float |  | R18 - Valor do desconto |  |
| R18NROREF | String |  | R18 - Número de referência |  |
| R35NRORV | Integer |  | R35 - Nro. RV |  |
| R16DTRV | Date |  | R16 - Dt. RV |  |
| R16VLRBRUTO | Float |  | R16 - Valor bruto |  |
| R16DTCREDITO | Date |  | R16 - Data de crédito |  |
| R16BANDCARTAO | String |  | R16 - Identifica a bandeira cartão utilizado |  |
| R17TIPOREG | Integer |  | R17 - Tipo de registro |  |
| R18NROAUT | String |  | R18 - Nro autorização |  |
| R18NROBILHETE2 | String |  | R18 - Nro. Bilhete 2 |  |
| R16NROPV | Integer |  | R16 - Número do PV |  |
| R35NROCARTAO | String |  | R35 - Número do cartão |  |
| R16VLRTXEMB | Float |  | R16 - Valor da taxa de embarque |  |
| R16VLRREJEITADO | Float |  | R16 - Valor rejeitado |  |
| R16QTDCVNSU | Integer |  | R16 - Qtd. CV/NSUs |  |
| R16NRORV | Integer |  | R16 - Número do RV |  |
| R35NROAUTORIZACAO | String |  | R35 - Nro. Autorização |  |
| R16NROBANCO | Integer |  | R16 - Nro do banco |  |
| R18SIGLAPAIS | String |  | R18 - Sigla do país |  |
| R35NROPEDIDO | String |  | R35 - Número Pedido |  |
| R18NROBILHETE1 | String |  | R18 - Nro. Bilhete 1 |  |
| R18VLRLIQPARCX | Float |  | R18 - Vlr. Líquido demais Parcelas |  |
| R18NROTERMINAL | String |  | R18 - Nro. Terminal |  |
| R18NROPARCELAS | Integer |  | R18 - Número de parcelas |  |
| R18NROBILHETE3 | String |  | R18 - Nro. Bilhete 3 |  |
| R18BANDEIRA | String |  | R18 - Bandeira |  |
| R35TIPREG | Integer |  | Tipo de Registro (R35) |  |
| R35NROPV | Integer |  | R35 - Nro. PV |  |
| R18NRORV | Integer |  | R18 - Número do RV |  |
| R18DTCVNSU | Integer |  | R18 - Dt. CV/NSU |  |
| R18CODSERV | Integer |  | R18 - Código de serviço |  |
| R18NROPV | Integer |  | R18 - Número do PV |  |
| R18VLRLIQ | Float |  | R18 - Valor líquido |  |
| R35TID | String |  | R35 - TID |  |
| R17QTDCONSULTA | Integer |  | R17 - Qtd. consultas realizadas |  |
| R16NROAGENCIA | Integer |  | R16 - Nro  da agência |  |
| R18VLRTXEMB | Float |  | R18 - Vlr. Tx embarque |  |
| R16TIPOREG | Integer |  | R16 - Tipo de registro |  |
| R18TIPOCAP | Integer |  | R18 - Tipo de captura |  |
| R18VLRCVNSU | Float |  | R18 - Valor do CV/NSU |  |
| R18NROBILHETE4 | String |  | R18 - Nro. Bilhete 4 |  |
| R18VLRLIQPARC1 | Float |  | R18 - Vlr. Líquido da Parcela 1 |  |
| R17NROPV | Integer |  | R17 - Número do PV |  |
| R35NROCVNSU | Integer |  | R35 - Número do CV / NSU |  |
| R16VLRDESC | Float |  | R16 - Valor do desconto |  |
| R20NROPV | Integer |  | R20 - Nro. PV |  |
| R20NRORV | Integer |  | R20 - Nro. RV |  |
| R20VLRPARCLIQ | Float |  | R20 - Vlr. Parc. Liq. |  |
| R20DTCRED | Date |  | R20 - Dt. Créd. |  |
| R20DTRV | Date |  | R20 - Dt. RV |  |
| R20VLRPARCBRRUTO | Float |  | R20 - Vlr. Parc. Bruto |  |
| R20NROPARC | Integer |  | R20 - Nro. Parcela |  |
| R20VLRDESCPARC | Float |  | R20 - Vlr. Desc. s/ Parc. |  |
| R20TIPREG | Integer |  | R20 - Tipo Registro |  |
| R21BANDEIRA | String |  | R21 - Bandeira |  |
| R21QTDCONSULTA | Integer |  | R21 - Qtd. consulta |  |
| R21DTCONSULTA | Date |  | R21 - Dt. Consulta |  |
| R21TIPREG | Integer |  | R21 - Tipo Registro |  |
| R21NROPV | Integer |  | R21 - Nro. PV |  |
| R29MODENTCARD | Integer |  | R29 - Modo Entrada Cartão |  |
| R29MCCTRAN | Integer |  | R29 - MCC Trans. |  |
| R29TIPREG | Integer |  | R29 - Tipo Registro |  |
| R29NROPV | Integer |  | R29 - Nro. PV |  |
| R29TIPCARTAO | String |  | R29 - Tipo Cartão |  |
| R29NRORVORIG | Integer |  | R29 - Nro. RV Original |  |
| R29NRONSU | Integer |  | R29 - Nro. NSU |  |
| R29VLRPLUS | Float |  | R29 - Vlr. Plus |  |
| R29VLRINTERCHARGE | Float |  | R29 - Vlr. Intercharge Bandeira |  |
| R29DTTRANCVNSU | Date |  | R29 - Dt. Tran. CV/NSU |  |
| R29DTRVORIG | Date |  | R29 - Dt. RV Original |  |
| HEADERTIPREG | Integer |  | Tipo de Registro |  |

## AD_UNIDADEALTERNATIVA — Unidades Alternativas
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDINSTPRN | Integer |  | Inst. processo |  |
| IDINSTTAR | Integer |  | Inst. tarefa |  |
| CODREGISTRO | Integer |  | Código |  |
| CODVOL | String |  | Sigla da Unidade |  |
| DIVIDEMULTIPLICA | String |  | Operação | `M`=MULTIPLICA `D`=DIVIDE |
| QUANTIDADE | Float |  | Quantidade |  |
| IDTAREFA | String |  | Tarefa |  |

## AD_UPDSITE — updsite
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SKUNOVO | String |  | SKUNOVO |  |
| ESTOQUE | String |  | ESTOQUE |  |
| STATUS | String |  | STATUS |  |
| SKUANTIGO | String |  | SKUANTIGO |  |

## AD_VALOR — VALOR
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODIGO | Integer |  | CODIGO |  |
| CANAL | String |  | CANAL |  |
| VLRMAX | Float |  | VLR. MAXIMO |  |
| VLRMIN | Float |  | VLR. MINIMO |  |

## AD_VARISHOPEE — Sku Variação
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| IDVAR | Integer |  | Id variação |  |
| IDSHOPEE | Integer |  | IDSHOPEE |  |
| ID | Integer |  | ID |  |
| CODPROD | Integer |  | Código |  |
| PRECOVAR | Float |  | Preço Variação |  |
| RETORNOVAR | C |  | Retorno Status |  |
| SKUVAR | Integer |  | Sku Variação |  |
| NAMEVAR | String |  | Nome Variação (cor, tamanho) |  |
| TIPOVAR | String |  | Nome Variação (Azul, Amarelo) |  |
| ENVPRODVAR | String |  | Produto Enviado |  |
| IDVARIATIONSHOPEE | Integer |  | IDVARIATIONSHOPEE |  |
| ESTOQUE | Integer |  | Estoque |  |

## AD_VENDACAMPANHA — Vendas das Campanhas
Campos: 6

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |
| IDCAMPANHA | Integer |  | Id da Campanha |  |
| IDCONTRATO | String |  | ID Assinatura |  |
| CODEMP | Integer |  | Código da empresa |  |
| PEDIDOMKTPLACE | String |  | Pedido do Marketplace |  |
| NUNOTA | Integer |  | Numero Único da Nota |  |

## AD_VENDAKONCILI — Venda Koncili
Campos: 33

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Float |  | Sequencia |  |
| REF_PEDIDO | String |  | REF_PEDIDO |  |
| ID | String |  | ID |  |
| TP_LANCAMENTO | String |  | TP_LANCAMENTO |  |
| ETAPA | String |  | ETAPA |  |
| STATUS | String |  | STATUS |  |
| CANAL | String |  | CANAL |  |
| CONTA | String |  | CONTA |  |
| NOME_CLIENTE | String |  | NOME_CLIENTE |  |
| DOC_CLIENTE | String |  | DOC_CLIENTE |  |
| SKU | String |  | SKU |  |
| N_PARCELA | String |  | N_PARCELA |  |
| QT_PARCELAS | String |  | QT_PARCELAS |  |
| COMISSAO_PREVISTO | String |  | COMISSAO_PREVISTO(%) |  |
| COMISSAO_REPASSE | String |  | COMISSAO_REPASSE(%) |  |
| METODO_PGTO | String |  | METODO_PGTO |  |
| TP_LOGISTICA | String |  | TP_LOGISTICA |  |
| TP_COMISSAO | String |  | TP_COMISSAO |  |
| CONCIL_PARCIAL | String |  | CONCIL_PARCIAL |  |
| CRITICA | String |  | CRITICA |  |
| JUSTIFICATIVAS | String |  | JUSTIFICATIVAS |  |
| ORIGEM_PEDIDO | String |  | ORIGEM_PEDIDO |  |
| CONCILIACAO | String |  | CONCILIACAO |  |
| DATA_PREVISTA | String |  | DATA_PREVISTA |  |
| DATA_IMPORTACAO | String |  | DATA_IMPORTACAO |  |
| DATA_PEDIDO | String |  | DATA_PEDIDO |  |
| DATA_REPASSE | String |  | DATA_REPASSE |  |
| DATA_NF | String |  | DATA_NF |  |
| VALOR_PREVISTO | String |  | VALOR_PREVISTO |  |
| VALOR_REPASSE | String |  | VALOR_REPASSE |  |
| NUM_NF | String |  | NUM_NF |  |
| NUNOTA | Integer |  | NUNOTA |  |
| CLASSIFICACAO | String |  | CLASSIFICACAO |  |

## AD_VENSITETELEVENDAS — Vendas Site Realizadas Pelo Televendas
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODMKT | String |  | Código Marketplace |  |
| VENDEDOR | String |  | Vendedor | `K`=Kemelly `S`=Sabrina |

## AD_VIPCLIENTE — VipCliente
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARC | Integer |  | CODPARC |  |
| PEDIDOS | Integer |  | PEDIDOS |  |
| VALOR | Float |  | VALOR |  |
| TICKET | Float |  | TICKET |  |
| PERIODO | Float |  | PERIODO |  |

## AD_VWB2WFATXML — VWB2WFATXML
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTA | Integer |  | Nro Unico |  |
| CODVEND | Integer |  | Cod. Vendedor |  |
| PEDIDOEXTERNO | String |  | Pedido Externo |  |

## AD_VWDETALHESORDER — VWDETALHESORDER
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |

## AD_VWINITSHOPEETRANSPORTADORA — VWINITSHOPEETRANSPORTADORA
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |

## AD_VWINITSHOPEETRANSPORTADORAS — VWINITSHOPEETRANSPORTADORAS
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |

## AD_VWINVOICEVTEX — View Invoice Vtex
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |

## AD_VWOCORRENJADLOG — Ocorrências JadLog
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |

## AD_VWORGANIZARSHOPEE — VWORGANIZARSHOPEE
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |

## AD_VWPEDJADLOG — View Pedido Jadlog
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | Id |  |

## AD_VWPRODMKTPSHOPEE — VWPRODMKTPSHOPEE
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |

## AD_VWSTATUSORDERSHOPEE — VWSTATUSORDERSHOPEE
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |

## AD_VWSTKSHOPEEV2 — VWSTKSHOPEEV2
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |

## AD_VWSTKVARSHOPEE — VWSTKVARSHOPEE
Campos: 1

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ID | Integer |  | ID |  |