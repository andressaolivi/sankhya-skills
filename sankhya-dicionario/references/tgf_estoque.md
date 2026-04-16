# TGF — Estoque, Produtos, Locais

> Gerado do dicionário oficial TDD Sankhya. 30 tabelas.


## TGFCAT — Categoria medicamento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTEXE | DateTime |  | DTEXE |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODCAT | Integer |  | Código |  |

## TGFCAT42 — Portaria Cat 42
Campos: 16

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| FINAPRESENTACAO | Integer |  | Finalidade de Apresentação do Arquivo | `2`=2 - Remessa de arquivo para substituição de arquivo remetido anteriormente `1`=1 - Remessa de arquivo requerido por intimação específica `0`=0 - Remessa regular de arquivo |
| VERSAOLAYOUT | Integer |  | Versão do Layout | `1`=1 - Versão 1 - Início 01/01/2018 |
| ARQCONFIRMADO | String |  | Arquivo Confirmado? | `S`=Sim `N`=Não |
| USAVLRORIGSALDEV | String |  | Usa valor da origem p/ amparar saldo das devoluções? | `S`=Sim `N`=Não |
| TEMDIVERGENCIA | String |  | Tem divergência? | `S`=Sim `N`=Não |
| CONSFILTRONATIVO | String |  | Considerar filtro nativo? | `S`=Sim `N`=Não |
| CONSMARCPROD | String |  | Considerar marcação no produto? | `S`=Sim `N`=Não |
| CONSMARCGRUPROD | String |  | Considerar marcação no grupo de produto? | `S`=Sim `N`=Não |
| FILPERSONALIZADO | String |  | Filtro Personalizado |  |
| TIPAPUR | Integer |  | Tipo de Apuração | `2`=2 - Notas p/ Ressarcimento de ST (Digitadas no Livro) `1`=1 - Rastreamento de Estoque |
| VLR_TOT_RESSARCIMENTO | Float |  | Valor total de Ressarcimento |  |
| VLR_TOT_COMPLEMENTO | Float |  | Valor total de Complemento |  |
| TOT_ICMS_CRED_OPER_PROPRIA | Float |  | Total de ICMS Crédito da Operação Própria |  |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R0000 — Portaria Cat 42 Registro 0000
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| PERIODO | Date |  | Período |  |
| NOME | String |  | Nome Empresarial |  |
| CNPJ | String |  | CNPJ |  |
| IE | String |  | Inscrição Estadual |  |
| CODMUN | Integer |  | Cód. do Município Fiscal |  |
| CODVER | Integer |  | Cód. da Versão do Layout | `1`=1 - Versão 1 - Início 01/01/2018 |
| CODFIN | Integer |  | Cód. da Finalidade do Arquivo | `2`=2 - Remessa de arquivo para substituição de arquivo remetido anteriormente `1`=1 - Remessa de arquivo requerido por intimação específica `0`=0 - Remessa regular de arquivo |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R0150 — Portaria Cat 42 Registro 0150
Campos: 12

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODPARC | Integer |  | Parceiro |  |
| NOME | String |  | Nome Empresarial (Razão Social) |  |
| CODPAISFIS | Integer |  | Cód. País Domicílio Fiscal |  |
| CNPJ | String |  | CNPJ |  |
| CPF | String |  | CPF |  |
| IE | String |  | Inscrição Estadual |  |
| CODMUNFIS | Integer |  | Cód. Município Fiscal |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R0200 — Portaria Cat 42 Registro 0200
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| DESCRITEM | String |  | Descrição do Item |  |
| CODBARRA | String |  | Cód. Barra |  |
| UNIDINV | String |  | Unidade de Medida |  |
| CODNCM | String |  | NCM |  |
| ALIQICMS | Float |  | Alíquota de ICMS |  |
| CEST | Integer |  | Cód. Especificador ST |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R1050 — Portaria Cat 42 Registro 1050
Campos: 15

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| QTDINI | Float |  | Qtd. Inicial |  |
| ICMSTOTINI | Float |  | Vlr. ICMS + ST Inicial |  |
| QTDFIM | Float |  | Qtd. Final |  |
| ICMSTOTFIM | Float |  | Vlr. ICMS + ST Final |  |
| TIPODIVERGENCIA | String |  | Tipo de Divergência | `6`=6 - Nota q/ Ampara Estoque sem Imposto Calculado `5`=5 - Saldo Inicial e/ou Final do Imposto Negativo `4`=4 - Qtd. Inicial e/ou Final Negativa `3`=3 - Saldo Final do Imposto Zerado com Qtd. Disponível `2`=2 - Saldo Inicial do Imposto Zerado com Qtd. Disponível_(+2)_ |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| NUNOTAENTREC | Float |  | Nro. Único Entrada mais Recente |  |
| DTENTREC | Date |  | Dt. Entrada mais Recente |  |
| VLRUNITENTREC | Float |  | Vlr. Unitário Entrada mais Recente |  |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R1050AJ — Produtos Ajustados Cat 42 Registro 1050
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| QTDINI | Float |  | Qtd. Inicial |  |
| ICMSTOTINI | Float |  | Vlr. ICMS Inicial |  |
| QTDFIM | Float |  | Qtd. Final |  |
| ICMSTOTFIM | Float |  | Vlr. ICMS Final |  |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R1050DEL — Produtos Descartados Cat 42 Registro 1050
Campos: 10

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| QTDINI | Float |  | Qtd. Inicial |  |
| ICMSTOTINI | Float |  | Vlr. ICMS Inicial |  |
| QTDFIM | Float |  | Qtd. Final |  |
| ICMSTOTFIM | Float |  | Vlr. ICMS Final |  |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R1050NAE — Notas q/ Amparam Estoque Cat 42 Registro 1050
Campos: 21

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| CODPROD | Integer |  | Produto |  |
| NUNOTA | Integer |  | Nro. Único da Nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| QTDNEG | Float |  | Quantidade |  |
| CODTRIB | Integer |  | Tributação |  |
| BASESUBSTIT | Float |  | Base do ST |  |
| VLRSUBST | Float |  | Vlr. ICMS + ST |  |
| VLRICMS | Float |  | Vlr. ICMS |  |
| BASESUBSTITUNIT | Float |  | Base do ST Unitário |  |
| VLRSUBSTUNIT | Float |  | Vlr. ICMS + ST Unitário |  |
| VLRICMSUNIT | Float |  | Vlr. ICMS Unitário |  |
| TIPONOTA | String |  | Tipo da Nota | `I`=Íntegra `A`=Ajustada |
| TIPMOV | String |  | Tipo de Movimento | `D`=D - Devolução de Venda `C`=C - Compra `Q`=Q - Requisição |
| VLRUNIT | Float |  | Vlr. Unitário |  |
| DTENT | Date |  | Dt. Entrada Mercadoria |  |
| VLRST | Float |  | Vlr. ST |  |
| VLRSTUNIT | Float |  | Vlr. ST Unitário |  |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R1100 — Portaria Cat 42 Registro 1100
Campos: 23

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| NUNOTA | Integer |  | Nro. Único |  |
| SEQUENCIA | Integer |  | Sequência (Nro. Item) |  |
| CHVDOC | String |  | Chave do Documento |  |
| DATA | Date |  | Dt. Entrada/Saída da Mercadoria |  |
| INDOPER | Integer |  | Ind. Tipo de Operação | `1`=1 - Saída `0`=0 - Entrada |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| CODCFO | Integer |  | CFOP |  |
| QTD | Float |  | Qtd. Item |  |
| ICMSTOT | Float |  | Vlr. ICMS Total |  |
| VLCONFR | Float |  | Vlr. Confronto das Operações |  |
| CODLEGAL | Integer |  | Cód. Enquadramento Legal | `4`=4 - Operação ensejadora de Ressarcimento ICMS-ST - Inciso IV Art. 269 RICMS `3`=3 - Operação ensejadora de Ressarcimento ICMS-ST - Inciso III Art. 269 RICMS `2`=2 - Operação ensejadora de Ressarcimento ICMS-ST - Inciso II Art. 269 RICMS `1`=1 - Operação ensejadora de Ressarcimento ou Compl. de ICMS-ST - Inciso I Art. 269 RICMS `-1`=(-1) - Operação não utiliza o Cód. Enquadramento Legal_(+1)_ |
| TIPMOV | String |  | Tipo de Movimento | `V`=V - Venda `E`=E - Devolução de Compra `D`=D - Devolução de Venda `C`=C - Compra |
| VLRPARAATUALSALDO | Float |  | Vlr. p/ atualizar saldo |  |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| BASEICMSTOT | Float |  | Base ICMS Total |  |
| VLRUNIT | Float |  | Valor Unitário |  |
| VLRICMS | Float |  | Vlr. do ICMS |  |
| TIPODIVERGENCIA | Integer |  | Tipo de Divergência | `31`=31 - Vlr. Confronto deve ser maior que zero `0`=0 - Sem divergência |
| CODEMP | Integer |  | Empresa |  |

## TGFCAT42R1200 — Portaria Cat 42 Registro 1200
Campos: 28

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Dt. Inicial |  |
| DTFINAL | Date |  | Dt. Final |  |
| REG | String |  | Registro |  |
| NUNOTA | Integer |  | Nro. Único |  |
| SEQUENCIA | Integer |  | Sequência (Nro. Item) |  |
| CODPARC | Integer |  | Parceiro |  |
| CGC_CPF | String |  | CNPJ / CPF |  |
| CODMOD | String |  | Cód. Modelo do Documento | `8B`=8B - Conhecimento de Transporte de Cargas Avulso `65`=65 - Nota Fiscal Eletrônica para Consumidor Final `63`=63 - Bilhete de Passagem Eletrônico `59`=59 - Cupom Fiscal Eletrônico `57`=57 - Conhecimento Transporte Rodoviário Eletrônico_(+33)_ |
| ECFFAB | String |  | Nro. Série Equip. ECF |  |
| SER | String |  | Série do Documento |  |
| NUMDOC | Integer |  | Nro. do Documento |  |
| INDOPER | Integer |  | Ind. Tipo de Operação | `1`=1 - Saída `0`=0 - Entrada |
| DATA | Date |  | Dt. Entrada/Saída da Mercadoria |  |
| CODCFO | Integer |  | CFOP |  |
| CODPROD | Integer |  | Produto |  |
| CODITEM | String |  | Cód. Item |  |
| QTD | Float |  | Qtd. Item |  |
| ICMSTOT | Float |  | Vlr. ICMS Total |  |
| VLCONFR | Float |  | Vlr. Confronto das Operações |  |
| CODLEGAL | Integer |  | Cód. Enquadramento Legal | `3`=3 - Operação ensejadora de Ressarcimento ICMS-ST - Inciso III Art. 269 RICMS `2`=2 - Operação ensejadora de Ressarcimento ICMS-ST - Inciso II Art. 269 RICMS `1`=1 - Operação ensejadora de Ressarcimento ou Compl. de ICMS-ST - Inciso I Art. 269 RICMS `0`=0 - Operação não ensejadora de Ressarcimento ou Compl. ICMS-ST `-1`=(-1) - Operação não utiliza o Cód. Enquadramento Legal_(+1)_ |
| TIPMOV | String |  | Tipo de Movimento | `V`=V - Venda `E`=E - Devolução de Compra `D`=D - Devolução de Venda `C`=C - Compra |
| VLRPARAATUALSALDO | Float |  | Vlr. p/ atualizar saldo |  |
| TIPODIVERGENCIA | Integer |  | Tipo de Divergência | `31`=31 - Vlr. Confronto deve ser maior que zero `0`=0 - Sem divergência |
| DIGITADO | String |  | Digitado | `S`=Sim `N`=Não |
| BASEICMSTOT | Float |  | Base ICMS Total |  |
| VLRUNIT | Float |  | Valor Unitário |  |
| VLRICMS | Float |  | Vlr. do ICMS |  |
| CODEMP | Integer |  | Empresa |  |

## TGFCPR — Classificação do medicamento
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTEXE | DateTime |  | DTEXE |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODCPR | Integer |  | Código |  |

## TGFCPRB — Tabela Atividades, Prods. e Sers. p/ CPRB
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTINICIAL | Date |  | Data Inicial |  |
| DTFINAL | Date |  | Data Final |  |
| CODRECOLHIMENTO | Integer |  | Código de Recolhimento |  |
| ALIQUOTA | Float |  | Alíquota |  |
| CODCTACTB | Integer |  | Conta contábil |  |
| DESCATIVIDADE | String |  | Desc. Atividade (Prest. Serviços e Produtos) |  |
| CODCPRB | String |  | Cód. Atividade (Prest. Serviços e Produtos) |  |

## TGFCTE — GF Contagem de Estoque
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODVOL | String |  | Unidade |  |
| QTDEST | Float |  | Estoque |  |
| DTCONTAGEM | Date |  | Data contagem |  |
| CONTROLE | String |  | Controle |  |
| CODLOCAL | Integer |  | Local |  |
| TIPO | String |  | Tipo | `T`=Terceiros `P`=Próprio |
| CODPARC | Integer |  | Cód. Parceiro |  |
| CODEMP | Integer |  | Empresa |  |
| DTVAL | Date |  | Dt. Validade |  |
| NOMEARQBOMI | String |  | NOMEARQBOMI |  |
| DHCONFBOMI | DateTime |  | DHCONFBOMI |  |
| ERROCONFBOMI | String |  | ERROCONFBOMI |  |
| SEQUENCIA | Integer |  | Sequência |  |
| QTDESTUNCAD | Float |  | Qtd. Unidade Padrão |  |
| NUIVT | Integer |  | Inventário WMS |  |
| DTFABRICACAO | Date |  | Dt. Fabricação |  |
| CODPROD | Integer |  | Produto |  |

## TGFCTENT — Nota Técnica CTe
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ATIVONT | String |  | Ativo | `N`=Nao `S`=Sim |
| VERSAONT | String |  | Versão Nota Técnica | `0`=Anterior `1`=Nota Técnica 2024.001 - v1.00 `2`=Nota Técnica 2024.004 - v1.04 `3`=Nota Técnica 2025.001_RTC |
| DTENTHOMOLOG | DateTime |  | Data de Homologação |  |
| DTENTPROD | DateTime |  | Data de Produção |  |
| CODEMP | Integer |  | Empresa |  |

## TGFCUS — Custos
Campos: 26

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTATUAL | Date |  | Data Atualização |  |
| CUSMEDICM | Float |  | Custo Médio com ICMS |  |
| CUSSEMICM | Float |  | Custo Médio sem ICMS |  |
| CUSREP | Float |  | Custo de Reposição |  |
| CUSVARIAVEL | Float |  | Custo Variável |  |
| CUSGER | Float |  | Custo Gerencial |  |
| CUSMED | Float |  | Custo Médio Gerencial |  |
| VLRVENDAFIXO | Float |  | Valor de Venda Fixo |  |
| ENTRADACOMICMS | Float |  | Entrada com ICMS |  |
| ENTRADASEMICMS | Float |  | Entrada sem ICMS |  |
| CODLOCAL | Integer |  | Local |  |
| CONTROLE | String |  | Controle |  |
| CODEMP | Integer |  | Empresa |  |
| QTDNEG | Float |  | Quantidade Negociada |  |
| AUTOMATICO | String |  | Automático | `N`=Não `S`=Sim |
| ALTPRECO | String |  | Altera Preço? | `N`=Não `S`=Sim |
| NUNOTA | Integer |  | Nro. Nota |  |
| SEQUENCIA | Integer |  | Sequência |  |
| TOTALCOMICMS | Float |  | Total com ICMS |  |
| TOTALSEMICMS | Float |  | Total sem ICMS |  |
| TOTALCOMICMSANT | Float |  | Total com ICMS Antigo |  |
| TOTALSEMICMSANT | Float |  | Total sem ICMS Antigo |  |
| CUSMEDCALC | String |  | Custo Médio Calculado | `N`=Não `S`=Sim |
| PROCESSO | String |  | Processo |  |
| AD_CODUSU | Integer |  | Usuário Alteração |  |
| CODPROD | Integer |  | Produto |  |

## TGFCUSITE — Custo Item
Campos: 18

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | Sequencia |  |
| CODPROD | Integer |  | Produto |  |
| CODEMP | Integer |  | Empresa |  |
| CODLOCAL | Integer |  | Local |  |
| CONTROLE | String |  | Controle |  |
| DTATUAL | DateTime |  | DTATUAL |  |
| CUSGER | Float |  | CUSGER |  |
| CUSVARIAVEL | Float |  | Custo variável |  |
| CUSREP | Float |  | CUSREP |  |
| ENTRADACOMICMS | Float |  | ENTRADACOMICMS |  |
| ENTRADASEMICMS | Float |  | ENTRADASEMICMS |  |
| QTDNEG | Float |  | Qtd. Negociada |  |
| FAMILIA | String |  | FAMILIA |  |
| ALTPRECO | String |  | Alt. Preço Igual |  |
| TIPONOTA | String |  | TIPONOTA |  |
| SINAL | Integer |  | SINAL |  |
| COMPLCUST | Integer |  | Complemento de Custo |  |
| NUNOTA | Integer |  | Nro. Nota |  |

## TGFCUSTAR — Custo de Tarifa CIP
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPROD | Integer |  | Cód. Produto |  |
| DTATUAL | DateTime |  | Dt. Atual |  |
| CUSAPURADO | Float |  | Custo Apurado |  |
| CODEMP | Integer |  | Cód. Empresa |  |

## TGFEST — Estoque
Campos: 20

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| CODLOCAL | Integer |  | Local |  |
| CODPROD | Integer |  | Cód. Prod. |  |
| CONTROLE | String |  | Controle |  |
| ESTOQUE | Float |  | Estoque |  |
| RESERVADO | Float |  | Reservado |  |
| ESTMIN | Float |  | Estoque Mínimo |  |
| ESTMAX | Float |  | Estoque Máximo |  |
| CODBARRA | String |  | Cód. de Barras |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| DTVAL | Date |  | Data de Validade |  |
| CODPARC | Integer |  | Parceiro |  |
| TIPO | String |  | Tipo | `P`=Próprio `T`=Terceiro |
| PERCPUREZA | Float |  | % Pureza |  |
| PERCGERMIN | Float |  | % Germinação |  |
| DTFABRICACAO | Date |  | Data de Fabricação |  |
| STATUSLOTE | String |  | Status Lote |  |
| WMSBLOQUEADO | Float |  | Bloqueado no WMS |  |
| CODAGREGACAO | String |  | Cód. de Agregação |  |
| ESTDOCAWMS | Integer |  | Estoque em docas de entrada do WMS |  |

## TGFGRU — Grupos de Produtos
Campos: 45

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODGRUPOPROD | Integer |  | Cód. do Grupo Produto |  |
| DESCRGRUPOPROD | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| APRPRODVDA | String |  | Apresenta produtos desse grupo na venda consultiva? | `N`=Não `S`=Sim |
| VISIVELAPPOS | String |  | Apresentar produtos no aplicativo de Ordem de Serviço | `N`=Não `S`=Sim |
| GRUPOICMS | Integer |  | Grupo de ICMS |  |
| PERCCMTNAC | Float |  | % Carga Média Trib. Nacional |  |
| PERCCMTFED | Float |  | % Carga Média Trib. Federal |  |
| PERCCMTEST | Float |  | % Carga Média Trib. Estadual |  |
| PERCCMTMUN | Float |  | % Carga Média Trib. Municipal |  |
| PERCCMTIMP | Float |  | % Carga Média Trib. Importação |  |
| VALEST | String |  | Valida estoque | `G`=Pela soma de todas as Empresas `E`=Pela Empresa `S`=Pelo Grupo de Empresas `A`=Pela Empresa, mas aceita `N`=Não valida_(+1)_ |
| SOLCOMPRA | String |  | Solicita Compra | `N`=Não `S`=Sim |
| PEDIRLIB | String |  | Pedir confirmação de liberação | `S`=Sim `N`=Não |
| AGRUPALOCVALEST | String |  | Agrupar local na validação de estoque | `N`=Não `S`=Sim |
| CODNAT | Integer |  | Cód. Natureza |  |
| CODPROJ | Integer |  | Projeto |  |
| CODCENCUS | Integer |  | Cód.Centro Resultado |  |
| CODRFA | Integer |  | Regra armazenagem |  |
| PARTICMETA | Float |  | Participação na meta |  |
| LIMCURVA_C | Float |  | Limite Curva C |  |
| PERCMETA | Float |  | Meta percentual |  |
| IMAGEM | Boolean |  | Imagem |  |
| PERCMETACONTRIB | Float |  | Meta contribuição |  |
| QTDEXPOSICAO | Float |  | Quantidade em exposição |  |
| COMCURVA_B | Float |  | Comissão curva B |  |
| AREAOCUPUNID | Integer |  | Área ocupada por unidade |  |
| METAQTD | Float |  | Meta quantitativa |  |
| COMCURVA_A | Float |  | Comissão curva A |  |
| LIMCURVA_B | Float |  | Limite Curva B |  |
| GRAU | Integer |  | Grau |  |
| COMCURVA_C | Float |  | Comissão curva C |  |
| CODCTACTBEFD | Integer |  | Conta Contábil para EFD |  |
| BH_ID | Integer |  | BH_ID |  |
| CONSGRUPRODCAT42 | String |  | Considerar grupo de produto/serviço na geração da Cat 42? | `S`=Sim `N`=Não |
| AD_CUSTOFRETEPREC | Float |  | Custo Frete Precificação |  |
| DHALTER | DateTime |  | Dt. Alteração |  |
| CODUSU | Integer |  | Cód. Usuário Alteração |  |
| CALRUPTURAESTOQUE | String |  | Calcula Ruptura de Estoque? | `N`=Não `S`=Sim |
| AD_MAXIMA | String |  | INTEGRA COM A MÁXIMA? | `N`=NÃO `S`=SIM |
| AD_COMPRADOR | Integer |  | Comprador |  |
| AD_BKPVALEST | String |  | bkpVALEST |  |
| CODGRUPAI | Integer |  | Grupo pai |  |
| TIPOIMPOSTO | String |  | Tipo de Imposto |  |

## TGFLOC — Locais
Campos: 24

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRLOCAL | String |  | Descrição |  |
| ATIVO | String |  | Ativo | `S`=Sim `N`=Não |
| ANALITICO | String |  | Analítico | `N`=Não `S`=Sim |
| CODTAB | Integer |  | Tabela de preço |  |
| VLRCUS | Float |  | Valor de custo |  |
| VLRVENDA | Float |  | Valor de venda |  |
| INCSOBREIRF | String |  | Incide sobre IRF | `S`=Sim `N`=Não |
| CODLOCALPAI | Integer |  | Local Pai |  |
| GRAU | Integer |  | Grau |  |
| VALESTINDEP | String |  | Val.Est.Independente | `S`=Sim `N`=Não |
| DIASPRODUCAO | Integer |  | Prazo de entrega (em dias) |  |
| CAPACIDADEPRODUCAO | Float |  | Capacidade de Produção |  |
| DOMINGO | String |  | Domingo | `S`=Sim `N`=Não |
| SEGUNDA | String |  | Segunda | `N`=Não `S`=Sim |
| TERCA | String |  | Terça | `N`=Não `S`=Sim |
| QUARTA | String |  | Quarta | `N`=Não `S`=Sim |
| QUINTA | String |  | Quinta | `S`=Sim `N`=Não |
| SEXTA | String |  | Sexta | `S`=Sim `N`=Não |
| SABADO | String |  | Sábado | `S`=Sim `N`=Não |
| CODPARC | Integer |  | Cód. Parceiro |  |
| ACEITANOVAPROD | String |  | Aceita Novas Produções | `S`=Sim `N`=Não |
| UTILIZAWMS | String |  | Controlado pelo WMS | `S`=Sim `N`=Não |
| AD_MAXIMA | String |  | Integra com a Máxima | `S`=Sim `N`=Não |
| CODLOCAL | Integer |  | Cód. Local |  |

## TGFPAT — Princípio ativo
Campos: 5

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DESCRICAO | String |  | Descrição |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTEXE | DateTime |  | DTEXE |  |
| DTALTER | DateTime |  | DTALTER |  |
| CODPAT | Integer |  | Código |  |

## TGFPLA — Planejamento de Garantia
Campos: 2

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NOMEPLANO | String |  | Descrição |  |
| CODPLANO | Integer |  | Plano |  |

## TGFPLAC — Cabeçalho do Planejamento de Entrega
Campos: 13

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODPARCFAT | Integer |  | Parceiro |  |
| CODCONTATO | Integer |  | Contato |  |
| GRUPO | Integer |  | Grupo |  |
| NUNOTA | Integer |  | N.Único Nota |  |
| CODREG | Integer |  | Região |  |
| CODCID | Integer |  | Cidade |  |
| CODBAI | Integer |  | Bairro |  |
| CODEND | Integer |  | Endereço |  |
| NUMEND | Integer |  | Nro. Endereço |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| DTALTER | DateTime |  | Data de Alteração |  |
| DISTRIBUICAOCONTATO | Integer |  | Verifica se Houve Distribuição para o Contato |  |
| NUPLAN | Integer |  | Nro. Planejamento |  |

## TGFPLAI — Itens do Planejamento de Entrega
Campos: 7

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| QTDNEG | Integer |  | Quantidade |  |
| NUNOTAORIG | Integer |  | Nro. Único Pedido Orig. |  |
| SEQUENCIAORIG | Integer |  | Sequência Pedido Orig. |  |
| NUPLAN | Integer |  | Nro. Planejamento |  |
| CODPARCFAT | Integer |  | Cód. Parceiro |  |
| CODCONTATO | Integer |  | Contato |  |
| CODPROD | Integer |  | Produto |  |

## TGFPLAN — Planejamento de Entrega
Campos: 17

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| NUNOTAORIG | Integer |  | Nro. Único Pedido Origem |  |
| DHALTERTOP | DateTime |  | Data de Alteração da TOP |  |
| CODPARC | String |  | Parceiro |  |
| NUMNOTAORIG | Integer |  | Nro. Pedido Origem |  |
| NUNOTADEST | Integer |  | Nro. Único Nota Destino |  |
| NUMNOTADEST | Integer |  | Nro. Nota Destino |  |
| CODEMP | String |  | Empresa |  |
| CODTIPOPER | String |  | Tipo de Operação |  |
| DTNEG | Date |  | Data de Negociação |  |
| MODENTREGA | String |  | Modalidade de Entrega | `A`=Auto Distribuição `N`=Entrega Direta `S`=Sem Entrega `M`=Multientrega `P`=Porta-a-porta_(+1)_ |
| SITUACAO | String |  | Situação | `D`=Pendente `A`=Aprovado |
| CODUSU | Integer |  | Usuário Responsável |  |
| DTALTER | Date |  | Data de Alteração |  |
| GRUPO | Integer |  | Último Grupo |  |
| TOTALCESTASCONTATO | Integer |  | Total de Cestas dos Contatos |  |
| TOTALITENS | Integer |  | Total de Itens do Planejamento |  |
| NUPLAN | Integer |  | Nro. Planejamento |  |

## TGFPRO — Produtos
Campos: 468

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| ARMAZELOTE | String |  | Armazena por Lote | `S`=Sim `N`=Não |
| ONEROSO | String |  | Oneroso | `N`=Não `S`=Sim |
| CORFUNDOCONSPRECO | Integer |  | Cor do Fundo |  |
| CODFAB | Integer |  | Cód. Fabricante |  |
| CORFONTCONSPRECO | Integer |  | Cor da Fonte |  |
| CONTROLADO | String |  | Controlado | `N`=Não `S`=Sim |
| TIPO | String |  | Tipo |  |
| IDENCOSME | String |  | Identificação de Cosmecêutico | `N`=Não `S`=Sim |
| DESCRPROD | String |  | Descrição |  |
| IDENCORRELATO | String |  | Identificação de Correlato | `N`=Não `S`=Sim |
| DESCRPRODNFE | String |  | Descrição para NFE |  |
| CODPAT | Integer |  | Princ. Ativo Medicamento |  |
| ATIVO | String |  | Ativo | `N`=Não `S`=Sim |
| PRODFALTA | String |  | Produto em Falta | `S`=Sim `N`=Não |
| DTALTER | DateTime |  | Data de Alteração |  |
| REFMERCMED | String |  | Referência no Mercado de Medicamento | `N`=Não `S`=Sim |
| RENDIMENTO | String |  | Rendimento |  |
| IDENOTC | String |  | Identificação de OTC | `N`=Não `S`=Sim |
| COMPLDESC | String |  | Complemento |  |
| IDENPORTARIA | String |  | Identificação de Portaria |  |
| CODGRUPOPROD | Integer |  | Grupo |  |
| STATUSMED | Integer |  | Status do produto | `1`=Retirado do Mercado `0`=Não classificado `3`=Não Faz Mais Parte do Mix `2`=Descontinuado |
| CODVOL | String |  | Unidade padrão |  |
| LISTALPM | String |  | Lista de Procedimentos Médicos | `S`=Sim `N`=Não |
| CODPARCFORN | Integer |  | Parceiro Fornecedor preferencial |  |
| TERMOLABIL | String |  | Termolábil | `N`=Não `S`=Sim |
| REFFORN | String |  | Referência do Fornecedor |  |
| TEMPMINIMA | Integer |  | Temperatura Mínima em ºC |  |
| FABRICANTE | String |  | Fabricante |  |
| TEMPMAXIMA | Integer |  | Temperatura Máxima em ºC |  |
| REFERENCIA | String |  | Referência |  |
| CODCPR | Integer |  | Classificação |  |
| LOCALIZACAO | String |  | Localização |  |
| SEQSPR | Integer |  | Sub-Classificação |  |
| SELECIONADO | String |  | Seleção |  |
| CODCAT | Integer |  | Categoria |  |
| TEMPOSERV | DateTime |  | Tempo Estimado |  |
| SEQSCA | Integer |  | Sub-Categoria |  |
| MARCA | String |  | Marca |  |
| CODMARCA | Integer |  | Marca |  |
| CODTER | Integer |  | Classe Terapêutica |  |
| SEQSTE | Integer |  | Sub-Terapêutica |  |
| LOCAL | String |  | Local | `N`=Não `S`=Sim |
| USALOCAL | String |  | Usa local | `S`=Sim `N`=Não |
| ESTMIN | Float |  | Estoque Mínimo |  |
| ESTMAX | Float |  | Estoque Máximo |  |
| PROMOCAO | String |  | Promoção | `N`=Não `S`=Sim |
| DESCMAX | Float |  | % Desconto Máximo |  |
| GRUPODESCPROD | String |  | Grupo Desconto |  |
| TEMCOMISSAO | String |  | Calcular comissão | `N`=Não `S`=Sim |
| COMVEND | Float |  | % Comissão vendedor |  |
| COMGER | Float |  | % Comissão gerente |  |
| CODMOEDA | Integer |  | Moeda p/ preço |  |
| TIPLANCNOTA | String |  | Digitação na nota | `U`=Valor Unitário `V`=Quant. e Valor Total `Q`=Quantidade `T`=Valor Total `A`=Quant. e Valor Unitário |
| PESOBRUTO | Float |  | Peso bruto |  |
| ARREDPRECO | Float |  | Múltiplo p/ Preço |  |
| HOMEPAGE | String |  | Home Page |  |
| DECVLR | Integer |  | Decimais para o valor |  |
| DECQTD | Integer |  | Decimais para quantidade |  |
| ORIGPROD | String |  | Origem do produto | `3`=3-Nacional, mercadoria ou bem com conteúdo de importação superior a 40% e inferior ou igual a 70% `0`=0-Nacional, exceto as indicadas nos códigos 3, 4, 5 e 8 `8`=8-Nacional, mercadoria ou bem com Conteúdo de Importação superior a 70% `7`=7-Estrangeira, adquirida no mercado interno, sem similar nacional, constante em lista da CAMEX `6`=6-Estrangeira, importação direta, sem similar nacional, constante em lista da CAMEX_(+4)_ |
| ENDIMAGEM | String |  | Endereço da Imagem |  |
| CODUSU | Integer |  | Cód. Usuário |  |
| MULTIPVENDA | Float |  | Multiplicador para venda |  |
| DECCUSTO | Integer |  | Decimais para o custo |  |
| CODFORMPREC | Integer |  | Fórmula de precificação |  |
| CODFILTRO | Integer |  | Filtro p/ Cálc.Custo baseado no Financeiro |  |
| CODFILTROREQ | Integer |  | Filtro p/ Cálc.Custo baseado na Requisição |  |
| MEDAUX | Float |  | Medida auxiliar |  |
| HRDOBRADA | String |  | Hora Dobrada | `S`=Sim `N`=Não |
| TEMISS | String |  | Tem ISS | `I`=Isento `N`=Não tributado `S`=Tributado |
| TEMIRF | String |  | Tem IRF | `N`=Não `S`=Sim |
| PERCIRF | Float |  | % IRF |  |
| REDBASEIRF | Float |  | % Red. Base IRF |  |
| PRAZOVAL | Integer |  | Prazo validade/tolerância |  |
| MARGLUCRO | Float |  | % Margem de lucro |  |
| TIPCONTEST | String |  | Tipo de controle de estoque | `N`=Sem controle adicional `S`=Lista `V`=Data da validade `E`=Série `L`=Número do lote_(+3)_ |
| USOPROD | String |  | Usado como | `V`=Venda (fabricação própria) `I`=Imobilizado `D`=Revenda (por fórmula) `B`=Brinde `F`=Brinde (NF)_(+10)_ |
| PERCAUMENTCUSTO | Float |  | % Aviso Var. Custo |  |
| TIPOITEMSPED | String |  | Tipo do item p/ SPED | `null`=Utilizar do "Usado como" `99`=Outras `10`=Outros Insumos `06`=Produto Intermediário `05`=Subproduto_(+8)_ |
| CALCFUNTTELPRO | String |  | Calcular FUNTTEL? | `S`=Sim `N`=Não |
| BLOQVENDAFRAC | String |  | Bloquear venda fracionada? | `S`=Sim `N`=Não |
| TITCONTEST | String |  | Título Controle de estoque |  |
| CALCFUSTPRO | String |  | Calcular FUST? | `S`=Sim `N`=Não |
| SERVPRESTTER | String |  | Serviço prestado por terceiro? | `S`=Sim `N`=Não |
| SERVDESPNTRIB | String |  | Tratar serviço como despesa não tributável no JSON? | `N`=Não `S`=Sim |
| ALERTAESTMIN | String |  | Alerta estoque mínimo | `S`=Sim `N`=Não |
| ALIQFETHAB | Float |  | Alíquota FETHAB |  |
| CODPRODROI | String |  | Número do Item (Portaria 384/01) |  |
| CODVOLCOMPRA | String |  | Unid. Compra |  |
| AGRUPMIN | Float |  | Agrupamento mínimo |  |
| CODGENERO | Integer |  | Gênero |  |
| CODCENCUS | Integer |  | Centro Resultado |  |
| CODVOLFETHAB | String |  | Unidade Padrão p/ FETHAB |  |
| CARACTERISTICAS | String |  | Características |  |
| PRODINTERNO | String |  | Considerar na Integração Impostos | `S`=Código do produto `N`=Código de barras |
| IMAGEM | Boolean |  | Imagem |  |
| CODPROJ | Integer |  | Projeto |  |
| GERIMPNRETREINFAQ | String |  | Gera Imposto não-retido evento 2055 da EFD-Reinf? | `S`=Sim `N`=Não |
| PERCINSSESPECIAL | Float |  | % INSS Especial |  |
| TIPOINSSESPECIAL | String |  | Tipo de INSS Especial | `3`=INSS 25 anos `2`=INSS 20 anos `1`=INSS 15 anos |
| AD_MAXIMA_TIPO | String |  | Tipo Produto Máxima | `R`=Refrigerado `N`=Normal |
| AD_MAXIMA | String |  | Integra com a Maxima? | `N`=Não `S`=Sim |
| PERCENTSEPPUL | Float |  | Percentual para separação pulmão(0-100) |  |
| BH_MKTCROSSDOCKING | Float |  | Cross Docking |  |
| BH_MKTGARANTIA | String |  | Tempo de Garantia (Meses) |  |
| BH_MKTMODELO | String |  | Modelo |  |
| BH_MKTDESCWEB | String |  | Descrição Web |  |
| TEMCIAP | String |  | Atualizar CIAP? | `N`=Não `S`=Sim |
| CODFILTROCTA | Integer |  | Filtro p/ Cálc.Custo baseado em Lanç. Contábeis |  |
| DESVIOMAXTOLCONFSEP | Integer |  | Desvio máximo tolerado na conferência da separação |  |
| DESVIOMINTOLCONFSEP | Integer |  | Desvio mínimo tolerado na conferência da separação |  |
| REGISTRARPESO | String |  | Registrar peso | `N`=Não Registrar `M`=Manualmente `AM`=Balança/manual `A`=Pela balança |
| FRAGMENTALOTE | String |  | Fragmenta lote no envio para separação | `S`=Sim `N`=Não |
| INCPESOBRUTO | Float |  | Incremento de peso bruto |  |
| INCPESOLIQUIDO | Float |  | Incremento de peso líquido |  |
| NURFE | Integer |  | Modelo de etiqueta |  |
| ATUNUVERSAO | String |  | Atualizar versão |  |
| INTEGRAFOX | Integer |  | Integra com Sankhya Checkout |  |
| NUVERSAO | Integer |  | Versão |  |
| GRADEPADRAO | C |  | Grade Pradão |  |
| TAMANHOMEDIOPECA | Integer |  | Tamanho médio por peça (metros) |  |
| ORDEMMEDIDA | Float |  | Ordem medida |  |
| TIPOCONTAGEM | String |  | Tipo de Contagem | `Q`=Contagem cumulativa com qtd `P`=Contagem única por produto `D`=Considerar configuração `C`=Contagem cumulativa |
| QTDEMB | Integer |  | Quantidade de embalagens |  |
| M3 | Float |  | Metros Cúbicos |  |
| PESOLIQ | Float |  | Peso líquido |  |
| CODNAT | Integer |  | Natureza |  |
| APRESDETALHE | String |  | Apresenta tela de detalhes | `S`=Sim `N`=Não |
| INTEGRAECONECT | String |  | Integrar com EConect | `N`=Não `S`=Sim |
| CODVTP | Integer |  | Meio de transporte |  |
| COMERCIALIZACAOAGRI | String |  | Comercialização Agrícola? | `S`=Sim `N`=Não |
| MODETIQSEPWMS | Integer |  | Modelo de etiqueta para separação |  |
| IMPETIQSEPWMS | String |  | Imprime etiqueta para separação | `P`=Sim (por produto) `S`=Sim (por unidade) `N`=Não |
| MOTIVOINCEXC | String |  | Filtro para motivos SubOS | `N`=Nenhum `E`=Exceção (Não pode ser usado com) `I`=Restrição (Só pode ser usado com) |
| UTILIZAENDFLUT | String |  | Utiliza endereço flutuante | `S`=Sim `N`=Não |
| MAXMULTECONECT | Integer |  | Máx. Multiplicador |  |
| UTILSMARTCARD | String |  | Utiliza SmartCard? | `S`=Sim `N`=Não |
| QTDIDENTIF | Integer |  | Qtd. identificadores |  |
| TIPOIDENTIF | String |  | Tipo identificador | `SERIAL`=Número serial `IMEI`=IMEI |
| LISCONTEST | String |  | Lista Controle de estoque |  |
| IMPLAUDOLOTE | String |  | Imprime laudo por lote | `N`=Não `S`=Sim |
| CODGAR | Integer |  | Extensão de garantia |  |
| TEMMEDICAO | String |  | Realiza controle por medição | `N`=Não `S`=Sim |
| DESCMAXFLEX | Float |  | % Desconto Máximo Flex |  |
| VISIVELAPPOS | String |  | Apresentar no aplicativo de Ordem de Serviço | `N`=Não `S`=Sim |
| DIMENSOES | String |  | Informar dimensões | `S`=Sim `N`=Não |
| CODPRODSUBKIT | Integer |  | Código do Produto Substituto do Kit |  |
| PERCQUEBRATEC | Float |  | % Quebra Técnica |  |
| TIPOKIT | String |  | Tipo de Kit | `D`=Composição Padrão `P`=Composição Personalizada |
| CODCONFKIT | Integer |  | Código Configuração Kit |  |
| DESCVENCONSUL | String |  | Desconsiderar nos result. venda consultiva | `S`=Sim `N`=Não |
| PERCTOLPESOMENORSEP | Float |  | % de tolerância de peso a menor na separação |  |
| CODLST | Integer |  | Tipo de Serviço |  |
| OBRACONSTCIVIL | Integer |  | Obra de Construção Civil | `2`=2 - Empreitada Parcial `1`=1 - Empreitada Total |
| CODLOCALPADRAO | Integer |  | Local Padrão |  |
| CLASSIFCESSAOOBRA | Integer |  | Classificação Cessão M.d.Obra | `100000008`=Embalagem `100000007`=Acabamento `100000006`=Preparação de dados para processamento `100000005`=Digitação `100000004`=Serviços de natureza rural_(+26)_ |
| CODGPROD | Integer |  | Grupo Produção |  |
| FIXOAGENDA | String |  | Fixar na agenda | `N`=Não `S`=Sim |
| SERFATURCON | String |  | Série para faturamento em contratos |  |
| TOPFATURCON | Integer |  | TOP para faturamento em contratos |  |
| EXIGELASTROCAMADAS | String |  | Exige Lastro e Camadas | `N`=Não `S`=Sim |
| USALOTEDTFAB | String |  | Utiliza data de Fabricação | `N`=Não `S`=Sim |
| USALOTEDTVAL | String |  | Utiliza data de Validade | `N`=Não `S`=Sim |
| CONTROLMEDIC | String |  | Realiza controle por medição | `N`=Não `S`=Sim |
| DTSUBST | DateTime |  | Data da Substituição do Produto |  |
| CODPRODSUBST | Integer |  | Código do Produto Substituto |  |
| USACONTPESOVAR | String |  | Produto controlado por peso variável | `N`=Não `S`=Sim |
| PERCTOLPESOMAIOR | Float |  | % de tolerância de peso a maior no recebimento |  |
| PERCTOLPESOMAIORSEP | Float |  | % de tolerância de peso a maior na separação |  |
| PERCTOLPESOMENOR | Float |  | % de tolerância de peso a menor no recebimento |  |
| CODPARCCONSIG | Integer |  | Parceiro Consignante |  |
| CODCOMP | Integer |  | Componente do Serviço |  |
| CODVOLPESOVAR | String |  | Unidade de separação para produtos com peso variável |  |
| DESVIOMAX | Float |  | % Desvio Máximo |  |
| LOTECOMPMINIMO | Float |  | Compra Mínima |  |
| ESTSEGQTD | Float |  | Estoque de Segurança |  |
| ESTSEGDIAS | Integer |  | Estoque de Segurança (dias úteis) |  |
| DTALTERESQ | DateTime |  | Data de Alteração (Estoque de Segurança) |  |
| LOTECOMPRAS | Integer |  | Lote de Compra (dias úteis) |  |
| AGRUPCOMPMINIMO | Float |  | Agrupamento Mínimo |  |
| ARREDAGRUP | Float |  | Arredondamento para Agrupamento |  |
| ESTMAXQTD | Float |  | Estoque Máximo |  |
| ESTMAXDIAS | Integer |  | Estoque Máximo (dias úteis) |  |
| DTALTEREMQ | DateTime |  | Data de Alteração (Estoque Máximo) |  |
| APLICASAZO | String |  | Aplica Sazonalidade | `N`=Não `S`=Sim |
| PADRAO | String |  | Produto padrão | `S`=Sim `N`=Não |
| ACRESCMAX | Float |  | % Acréscimo Máximo |  |
| APLICACAO | Integer |  | Aplicações |  |
| APRESFORM | String |  | Apresenta em fórmulas de composição | `S`=Sim `N`=Não |
| BALANCA | String |  | Utiliza balança | `S`=Sim `N`=Não |
| CALCULOGIRO | String |  | Calcular giro pelo agendador | `E`=Não `G`=Sim |
| CARENCIA | Integer |  | Carência (dias) |  |
| CLASSEAGT | Integer |  | Classe do agrotóxico |  |
| CLASSETOX | Integer |  | Classe tóxica |  |
| CODBARBALANCA | String |  | Cód.Barras Balança por Unidade | `N`=Não `S`=Sim |
| CODBARCOMP | String |  | Conferência por Codigo de Barras Composto | `S`=Sim `N`=Não |
| CODFORMAPONTA | Integer |  | Fórmula Apontamento |  |
| CODPAIS | Integer |  | País de origem |  |
| CODPRODAGRUPAPT | Integer |  | Produto/Serviço p/ agrupar apontamento |  |
| CODPRODAGRUPAPTENC | Integer |  | Produto/Serviço p/ agrupar apontamento de encarregado |  |
| CODREGMAPA | String |  | Registro no M.A.P.A |  |
| CODRFA | Integer |  | Regra armazenagem |  |
| CODTRIBMUNISS | String |  | Cód. Trib. Município NFS-e |  |
| CODVOLPLAN | String |  | Unid. Planejamento |  |
| CODVOLRES | String |  | Unidade para Resumo de Entrega |  |
| CODVOLKANBAN | String |  | Unidade de movimentação padrão |  |
| COMPONOBRIG | String |  | Validação de componentes | `S`=Obrigatório `I`=Qtd.Iguais `N`=Opcional |
| CONCENTRACAO | String |  | Concentração |  |
| CONFCEGAPESO | String |  | Conferência cega por peso | `N`=Não `S`=Sim |
| CONFERE | String |  | Confere por Cód. Barra | `N`=Não `S`=Sim |
| CONVERVOL | Float |  | Conversão de Volume |  |
| DIASEXPEDICAO | Integer |  | Dias para Expedição |  |
| DOSAGEM | Float |  | Dosagem indicada |  |
| DOSAGEMPOR | Float |  | Qtd.Hectares/dosagem |  |
| DTVALDIF | String |  | Dt.Val. diferentes na armazenagem | `X`=Aceitar datas diferentes `M`=Apenas datas dentro do mesmo mês `S`=Apenas datas dentro da mesma semana `N`=Nunca aceitar datas diferentes `Q`=Apenas datas dentro da mesma quinzena |
| ENDMODROTULO | String |  | Endereço do Modelo do Rótulo |  |
| EXCLUIRCONF | String |  | Excluir do processo de conferência | `S`=Sim `N`=Não |
| EXIGEBENEFIC | String |  | Exige beneficiamento |  |
| FATTOTAL | String |  | Faturar Total | `S`=Sim `N`=Não |
| FLEX | String |  | FLEX |  |
| CODNBS | Integer |  | Código NBS |  |
| CODCLASTRIBNAC | String |  | Código Classificação Tributária Nacional |  |
| FORMULACAO | String |  | Formulação |  |
| GERAPLAPROD | String |  | Plan. Produção pelo Est. Mínimo | `S`=Sim `N`=Não |
| GRUPOQUIMICO | Integer |  | Grupo químico |  |
| GRUPOTRANSG | Integer |  | Grupo transg. |  |
| IMPETIQCONF | String |  | Imprime etiqueta de volumes na conferência | `S`=Sim `N`=Não |
| IMPORDEMCORTE | String |  | Imprime ordem de corte | `N`=Não `S`=Sim |
| INFPUREZA | String |  | Informa % Pureza e % Germinação | `N`=Não `S`=Sim |
| INTERVALO | Integer |  | Intervalo (dias) |  |
| LARGURA | Float |  | Largura |  |
| LASTRO | Integer |  | Lastro |  |
| LEADTIME | Integer |  | Lead time de compra |  |
| MANEJOINT | String |  | Manejo integrado |  |
| MODOAPLIC | String |  | Modo de aplicação |  |
| NOTIFCONF | String |  | Notificação para conferência |  |
| OBSETIQUETA | String |  | Observação |  |
| PERMCOMPPROD | String |  | Permite comprar este produto? | `S`=Sim `N`=Não |
| QTDNFLAUDOSINT | Integer |  | Qtd. Notas entre laudos internos |  |
| RASTRESTOQUE | String |  | Rastreamento de Estoques | `O`=Rastrear com Local `C`=Rastrear com Controle `S`=Rastrear `N`=Sem rastreamento `L`=Rastrear com Controle e Local |
| RECEITUARIO | String |  | Exige receituário agronômico |  |
| CONESTORIGPROD | String |  | Controla estoque por origem de produto | `S`=Sim `N`=Não |
| RECUPAVARIA | String |  | Recuperação de Avaria? | `N`=Não `S`=Sim |
| REGRAWMS | String |  | Regras de WMS | `O`=Ordem `F`=FIFO |
| REMETER | String |  | Remeter? | `N`=Não `S`=Sim `D`=Dependente |
| RENDIMENTOHA | Float |  | Dosagem/Ha Planejamento |  |
| SHELFLIFE | Integer |  | Shelf life |  |
| SHELFLIFEMIN | Integer |  | Shelf life mín. em recebimentos |  |
| SOLCOMPRA | String |  | Solicita compra? | `N`=Não `S`=Sim |
| TAMLOTE | Integer |  | Tamanho Lote |  |
| TAMSERIE | Integer |  | Tamanho Série |  |
| TIPCONTESTWMS | String |  | Usa controle adicional no WMS ? |  |
| TIPSERNFE | String |  | Tipo de série para NF-e | `F`=Fabricante `P`=Padrão |
| UNIDADE | String |  | Unid. de Medida | `CM`=CM `MM`=MM `M`=M |
| UNIDMINARMAZ | String |  | Unid. Min. Armazenagem WMS |  |
| USACODBARRASQTD | String |  | Cód.Barras com quantidade | `N`=Não `S`=Sim |
| USAIMPAGRUPMIN | String |  | Imprimir Etiqueta de Volume por Agrupamento Mínimo | `N`=Não `S`=Sim |
| USASERIEFAB | String |  | Exige Nro de Série do Fabricante | `S`=Sim `N`=Não |
| ALIQNAC | Float |  | ALIQNAC |  |
| USASERIESEPWMS | String |  | Coletar Série na Conferência de Expedição do WMS? | `S`=Sim `N`=Não |
| ALIQIMP | Float |  | ALIQIMP |  |
| USASTATUSLOTE | String |  | Usa Status de Lote | `S`=Sim `N`=Não |
| UTILIZAWMS | String |  | Controlado pelo WMS | `N`=Não `S`=Sim |
| VOLDOSAGEM | String |  | Unidade dosagem |  |
| VALCAPM3 | String |  | Validar capac.produção diária em M3 |  |
| VALCBGLOBAL | String |  | Valida Cód. Barra de Nro Série Global | `S`=Sim `N`=Não |
| VENCOMPINDIV | String |  | Aceitar venda fora do KIT | `N`=Não `S`=Sim |
| VOLDOSAGEMPOR | String |  | Volume dosagem por |  |
| QTDAGRUPAMENTOMTZ | Float |  | Qtd. multiplicador Compra |  |
| NATUREZAOPERDES | String |  | Natureza da Operação de Declaração Eletrônica de Serviços |  |
| CODAREASEP | Integer |  | Cód.Área Separação |  |
| CNAE | Integer |  | CNAE |  |
| AD_TEMPOEXPEDICAO | Integer |  | Tempo de Expedição |  |
| NROPROCESSO | String |  | Nro do Processo Judicial/Adm (ISS) |  |
| CAMADAS | Integer |  | Camadas |  |
| AD_CODLEGADO | String |  | Codigo Legado |  |
| ESPESSURA | Float |  | Espessura/Profundidade |  |
| AD_ZERARSALDO | String |  | Zerar Saldo? | `S`=Sim `N`=Não |
| AD_DESCRICAOWEB | String |  | Descrição WEB Site |  |
| ALTURA | Float |  | Altura |  |
| CIENTIFICO | String |  | Nome científico |  |
| CODAUTCODIF | String |  | Autorização CODIF |  |
| CODCOS | Integer |  | Status OS |  |
| CULTURA | String |  | Nome da cultura |  |
| CODANP | Integer |  | Código ANP |  |
| EPOCAAPLIC | String |  | Época de aplicação |  |
| PRINCATIVO | Integer |  | Princípio ativo |  |
| NOMETAB | String |  | Nome da tabela |  |
| STATUSINCEXC | String |  | Filtro para status SubOS | `E`=Exceção (Não pode ser usado com) `N`=Nenhum `I`=Restrição (Só pode ser usado com) |
| TEMRASTROLOTE | String |  | Tem Rastro do Lote | `S`=Sim `N`=Não |
| CODANVISA | String |  | Cód. ANVISA |  |
| DESCRANP | String |  | Descrição ANP |  |
| PERCMISTGLP | Float |  | Percentual de mistura GLP |  |
| PERCINDMISTURA | Float |  | Percentual do Índice de Mistura |  |
| PERCMISTGNN | Float |  | Percentual de mistura de Gás Natural Nacional |  |
| PERCMISTGNI | Float |  | Percentual de mistura de Gás Natural Importado |  |
| VLRPARTIDAGLP | Float |  | Valor de Partida GLP |  |
| CODIDCNAE | Integer |  | Código ID CNAE |  |
| CODSERVTELECOM | Integer |  | Cód. Serviço de Telecomunicação |  |
| MOTISENCAOANVISA | String |  | Motivo Isenção Anvisa |  |
| CODIGONFCOM | String |  | Cód. Item NFCom |  |
| IDGRADE | Integer |  | Modelo de Grade |  |
| STATUSNCM | String |  | NCM Válido | `S`=Sim `N`=Não |
| TIPUTILCOM | Integer |  | Tipo de Utilização | `6`=6 - Outros `5`=5 - Multimídia `4`=4 - Provimento de acesso à Internet `3`=3 - TV por Assinatura `2`=2 - Comunicação de dados_(+2)_ |
| INDTIPREFBCICMSST | String |  | Indicador de Tipo de Referência da BC do ICMS ST | `0`=0 - Base de cálculo referente ao preço tabelado ou preço máximo sugerido `1`=1 - Base cálculo – Margem de valor agregado `2`=2 - Base de cálculo referente à Lista Negativa `3`=3 - Base de cálculo referente à Lista Positiva `4`=4 - Base de cálculo referente à Lista Neutra |
| AD_PERCPREOPREM | Float |  | Percentual Preço Premiun |  |
| AD_GRUPOCURVA | String |  | Grupo Curva ABC | `A`=Grupo A `C`=Grupo c `B`=Grupo B |
| AD_QTMINIMAMKTPLACE | Integer |  | Qt minima para envio para marketplace |  |
| CODCTACTB | Integer |  | Conta contábil 1 |  |
| AD_PERCBONIFICACAO | Float |  | Percentual de bonificação |  |
| CODCTACTB2 | Integer |  | Conta contábil 2 |  |
| CODCTACTB3 | Integer |  | Conta contábil 3 |  |
| AD_DESCRFORN | String |  | Descrição do Fornecedor |  |
| CODCTACTB4 | Integer |  | Conta contábil 4 |  |
| AD_DEPOSITO | String |  | Deposito Picking |  |
| AD_RUA_PICKING | String |  | Rua Picking |  |
| AD_PREDIO_PICKING | Integer |  | Predio Picking |  |
| AD_NIVEL_PICKING | Integer |  | Nivel Picking |  |
| AD_APARTAMENTO_PICKING | Integer |  | Apartamento Picking |  |
| AD_TIPBONIFICACAO | String |  | Tipo da Bonificação Quantidade ou Valor | `V`=Bonificação em Valor `Q`=Bonificação em Quantidade |
| AD_MAIORPRECO90DIAS | Float |  | Preço DE para MKT |  |
| APURAPRODEPE | String |  | Cód. Apur. Inc. PRODEPE/FUNCRESCE | `01`=Sem incentivo `02`=Com incentivo |
| WMSPRODRASTSERMED | String |  | Produto rastreado por série e controle de medicamento | `S`=Sim `N`=Não |
| INDESPPRODEPE | String |  | Indicador Esp. Inc. PRODEPE/FUNCRESCE | `02`=Com incentivo `01`=Sem incentivo |
| IDENTIMOB | Integer |  | Identificação do Imobilizado | `5`=Equipamentos `1`=Edif.e Benfeitorias em Imóveis Próprios `2`=Edif.e Benfeitorias em Imóveis de Terceiros `99`=Outros `3`=Instalações_(+2)_ |
| UTILIMOB | Integer |  | Utilização do Imobilizado | `2`=Prestação de Serviços `9`=Outros `3`=Locação a Terceiros `1`=Produção de Bens Destinados a Venda |
| AD_DESCRANUNCIO | String |  | Descrição para Anuncio |  |
| AD_TESTEURL | String |  | TESTE URL |  |
| AD_LOJACONCORRENTE | String |  | LOJACONCORRENTE |  |
| CODNATREND | Integer |  | Código Natureza Rendimento |  |
| TPIRRFEXT | Integer |  | Tributação IRRF - Exterior REINF | `10`=10 - Retenção do IRRF - alíquota padrão `11`=11 - Retenção do IRRF - alíquota da tabela progressiva `12`=12 - Retenção do IRRF - alíquota diferenciada (países com tributação favorecida) `13`=13 - Retenção do IRRF - alíquota limitada conforme cláusula em convênio `30`=30 - Retenção do IRRF - outras hipóteses |
| AD_SKUB2W | String |  | SKU NA B2W |  |
| AD_ATUALIZAPRECOAUTO | String |  | Atualiza Preço Automatico MKP | `S`=Sim `N`=Não |
| TEMICMS | String |  | Calcular ICMS? | `S`=Sim `N`=Não |
| AD_MCPRECOMKP | Float |  | Margem de contruibuição MKP ( Precificação) |  |
| CALCDIFAL | String |  | Calcular DIFAL ? | `S`=Sim `N`=Não |
| AD_DTCADASTRO | Date |  | Data de Cadastro |  |
| ICMSGERENCIA | String |  | Considerar débito ICMS nas consultas gerenciais? | `N`=Não `S`=Sim |
| AD_BKPGRUPO | String |  | Bkp Grupo |  |
| OBTSTANTMEDENT | String |  | Obtém ST Anterior pela média das entradas? | `S`=Sim `N`=Não |
| AD_CASHBACK | Float |  | cashback em % |  |
| TEMINSS | String |  | Tem INSS? | `N`=Não `S`=Sim |
| AD_IMPOSTOMEDIO | Float |  | Imposto Medio |  |
| ALIQGERAL | Float |  | Alíquota Geral |  |
| AD_SKUAMAZON | String |  | Sku Amazon |  |
| CODICMSFAST | Float |  | Alíquota ICMS do Fast Service |  |
| AD_SKUCONCORRENTE1 | String |  | Sku Concorrete 1 |  |
| ALIQICMSINTEFD | Float |  | Alíquota Interna de ICMS |  |
| AD_CAMPOTESTE | String |  | Criação de campo para teste  |  |
| GRUPOICMS | Integer |  | Grupo ICMS |  |
| AD_ESTLOJANOSITE | String |  | Estoque da Loja no Site | `S`=Sim `N`=Não |
| GRUPOICMS2 | Integer |  | Grupo de ICMS 2 |  |
| AD_DIASEST | Integer |  | DIAS DE ESTOQUE IDEAL |  |
| MVAPADRAO | Float |  | MVA Padrão |  |
| AD_CODCOMPRADOR | Integer |  | Código Comprador |  |
| PERCREDBASEICMSEFET | Float |  | Perc. Red. Base Icms Efetivo |  |
| AD_REVISADOSAI | String |  | Imposto revisado na saída? | `S`=Sim `N`=Não |
| PERCINSS | Float |  | % INSS |  |
| AD_REVISADOENT | String |  | Imposto revisado na Entrada? | `S`=Sim `N`=Não |
| MVAAJUSTADO | Float |  | % MVA Ajustado |  |
| AD_CODUSUPROD | Integer |  | COD. USUÁRIO |  |
| REDBASEINSS | Float |  | % Red. Base INSS |  |
| AD_HORAINI | Integer |  | Horario inicial |  |
| NUMITEMREA | Integer |  | Nro.Item REA/ICMS |  |
| AD_HORAFIM | Integer |  | Hora final |  |
| CODTAB | Integer |  | Tabela c/ base p/ substituição na venda |  |
| AD_BKPSKUPRECO | String |  | BKP SKU Preco |  |
| CLASSUBTRIB | Integer |  | Classificação Substituição Tributária | `3`=Cerveja/chope/refr., água mineral/pot. envasada e gelo `12`=Outros `11`=Veículos automotores `13`=Lâmina de Barbear, Aparelho de Barbear Descart.e Isqueiro `4`=Cigarros e outros produtos derivados do fumo_(+15)_ |
| AD_ESTEXTREMANOSITE | String |  | Estoque de Extrema no Site | `N`=Não `S`=Sim |
| TIPOSN | Integer |  | Tipo de Partilha/Anexo | `7`=Anexo V - Rec. decorrentes da prest. de serv. relacionados no § 5o-I do art. 18 da Lei `6`=Serviços da Atividade Intelectual como Medicina, Consultorias, Engenharia, Outros `5`=Serviços de Atividades Físicas, Computação, Adm. e Loc. de Imóveis de Terceiros, Outros `4`=Anexo IV - Rec. decorrentes da prest. de serv. relacionados no § 5o-C do art. 18 da Lei `3`=Anexo III - Rec. de locação de bens/móveis e prest. de serv. não relac. no § 5o-C do art. 18 da Lei_(+2)_ |
| AD_SERVAPP | String |  | Serviço Para o App | `S`=Sim `N`=Não |
| TIPSUBST | String |  | Tipo de substituição | `A`=Subst. na compra e na venda `C`=Revenda com subst. tributária (cálculo de Subst. na compra) `P`=Venda com subst. tributária (cálculo de Subst. na venda) `N`=Não tem |
| AD_GARANTIA | Integer |  | [Garantia em meses] |  |
| CODESPECST | Integer |  | CEST - Código Especificador ST |  |
| AD_ATIVOAMAZON | String |  | Ativo na Amazon | `S`=Sim `N`=Não |
| CODAGREGACAO | String |  | Cód. de Agregação |  |
| AD_SKUSKYHUB | String |  | Sku Skyhub |  |
| CODBENEFNAUF | String |  | Cód. de Benefício Fiscal na UF |  |
| AD_REFFORN2 | String |  | Referência do Fornecedor 2 |  |
| CODEXNCM | Integer |  | Cód. Exceção NCM |  |
| AD_REFERENCIA2 | String |  | Referência 2 |  |
| AD_DESCRVTEX | String |  | Descrição VTEX |  |
| CODBARTRIBDIFGTIN | String |  | Código de Barras da Un. Trib. diferente do padrão GTIN |  |
| AD_CODIGOPAI | Integer |  | Código do pai VTEX |  |
| CODBARDIFGTIN | String |  | Código de Barras diferente do padrão GTIN |  |
| CNPJFABRICANTE | String |  | CNPJ do Fabricante da Mercadoria |  |
| AD_DTAUTFOC | Date |  | Data de atualizacao forçada |  |
| PERCCMTEST | Float |  | % Carga Média Trib. Estadual |  |
| PERCCMTFED | Float |  | % Carga Média Trib. Federal |  |
| AD_TIPASSINATURA | Integer |  | Tipo de assinatura |  |
| PERCCMTIMP | Float |  | % Carga Média Trib. Importação |  |
| AD_ASSINAVEL | String |  | Assinavel | `S`=Sim `N`=Não |
| PERCCMTMUN | Float |  | % Carga Média Trib. Municipal |  |
| PERCCMTNAC | Float |  | % Carga Média Trib. Nacional |  |
| NCM | String |  | NCM |  |
| PRODUTONFE | Integer |  | Cód. Produto p/ NF-e/NFC-e/CF-e | `0`=Código do Produto `1`=Referência |
| TIPGTINNFE | Integer |  | EAN/GTIN Produto p/ NF-e | `0`=Não Informar `2`=Referência `3`=Código de Barras Estoque `1`=Código do Produto `4`=Cód.Barras da Unid.Alternativa ou a Referência |
| INDESCALA | String |  | Indicador de Escala Relevante | `null`=Não se aplica `S`=Produzido em Escala Relevante `N`=Produzido em Escala NÃO Relevante |
| DESDESCCALCPIS | String |  | Desconsiderar desconto no cálculo de PIS/COFINS? | `S`=Sim `N`=Não |
| TEMCREDPISCOFINSDEPR | String |  | Tem Créd. PIS/COFINS sobre Deprec. mensal? | `N`=Não `S`=Sim |
| CALRUPTURAESTOQUE | String |  | Calcula Ruptura de Estoque? | `N`=Não `S`=Sim |
| NATEFDCONTM410M810 | Integer |  | Cód. Natureza (PIS/COFINS M410/M810) |  |
| TEMCREDPISCOFINSAQUI | String |  | Tem Créd. PIS/COFINS sobre Aquisição? | `N`=Não `S`=Sim |
| GRUPOCOFINS | String |  | Grupo COFINS |  |
| CREDPISCOFINSAQUIPAR | Integer |  | Parcelas Créd. PIS/COFINS sobre Aquisição | `12`=12 Parcelas `48`=48 Parcelas |
| GRUPOPIS | String |  | Grupo PIS |  |
| GRUPOCSSL | String |  | Grupo CSLL |  |
| TEMIPICOMPRA | String |  | Tem IPI na compra? | `N`=Não `S`=Sim |
| TEMIPIVENDA | String |  | Tem IPI na venda? | `S`=Sim `N`=Não |
| CODENQIPIENT | Integer |  | Código Enq. Legal IPI Entrada |  |
| CODENQIPISAI | Integer |  | Código Enq. Legal IPI Saída |  |
| CODIPI | Integer |  | IPI |  |
| CSTIPIENT | Integer |  | Código Sit.Trib.IPI Entrada | `-1`=(-1)-Não sujeita ao IPI `49`=49-Outras Entradas `4`=04-Entrada Imune `3`=03-Entrada Não Tributada `2`=02-Entrada Isenta_(+3)_ |
| CSTIPISAI | Integer |  | Código Sit.Trib.IPI Saída | `-1`=(-1)-Não sujeita ao IPI `53`=53-Saída Não Tributada `55`=55-Saída c/Suspensão `99`=99-Outras Saídas `54`=54-Saída Imune_(+3)_ |
| PARTICIPAADRCST | String |  | Considerar geração da ADRC-ST (PR)? | `S`=Sim `N`=Não |
| PRODALIADRCST | String |  | Produto alimentício conforme art. 119 do Anexo IX do RICMS/2017 PR? | `S`=Sim `N`=Não |
| PRODSUJFECOP | String |  | Produto sujeito ao FECOP? | `N`=Não `S`=Sim |
| ALIQFECOP | Float |  | Alíquota FECOP |  |
| MVAORIGINALADRCST | Float |  | MVA Original para ADRC-ST (PR) |  |
| DESCPRODDRCST | String |  | Desconsiderar produto na geração da DRCST? | `S`=Sim `N`=Não |
| MVAORIGINALDRCST | Float |  | MVA Original para DRCST |  |
| CONSPRODCAT42 | String |  | Considerar produto na geração da Cat 42? | `S`=Sim `N`=Não |
| CAT1799SPRES | String |  | Ressarcimento de ST (CAT-17/99)? | `S`=Sim `N`=Não |
| ALIQINTERNACAT42 | Float |  | Alíquota interna para CAT42 |  |
| ENQREINTEGRA | String |  | Enquadrado no Reintegra/Prev.? | `S`=Sim `N`=Não |
| AP1RCTEGO | String |  | Produto constante no apêndice I do RCTE/GO? | `N`=Não `S`=Sim |
| CODATIVREINTEGRA | String |  | Código Atividade Reintegra |  |
| CODCPRB | String |  | Cód. Atividade CPRB (Reintegra/Prev.) |  |
| CODCTACTBEFD | Integer |  | Conta Contábil para EFD |  |
| CODFCI | String |  | Código da FCI |  |
| CODFCICALC | String |  | Código da FCI |  |
| VLRPARCIMPEXT | Float |  | Valor da Parcela Importada do Exterior - (R$) |  |
| VLRPARCIMPEXTCALC | Float |  | Valor da Parcela Importada do Exterior - (R$) |  |
| VLRCOMERC | Float |  | Valor de Comercialização - (R$) |  |
| VLRCOMERCCALC | Float |  | Valor de Comercialização - (R$) |  |
| OPEINTFETHAB | String |  | Resp. pelo Recolhimento em Operações Internas | `D`=Destinatário `R`=Remetente |
| OPEINTESTFETHAB | String |  | Resp. pelo Recolhimento em Operações Interestaduais | `D`=Destinatário `R`=Remetente |
| AD_URLVTEX | C |  | Url da Vtex |  |
| OPEEXPFETHAB | String |  | Resp. pelo Recolhimento em Operações de Exportação | `D`=Destinatário `R`=Remetente |
| AD_NOMEPAI | String |  | Nome do Produto Pai |  |
| GRUPOIBSCBS | Integer |  | Grupo IBS/CBS |  |
| GRUPOIS | Integer |  | Grupo IS |  |
| AD_DESCRSEO | String |  | Descrição de SEO |  |
| AD_TITULOVTEX | String |  | Titulo da vtex |  |
| AD_LINKCOMPL | String |  | Link Complementar |  |
| AD_LINKVIDEO | String |  | Link de Video |  |
| AD_ULTIMAATUALPRECO | Date |  | Ultima Data de Atualização de preço |  |
| AD_VALIDAAMZ | String |  | Validacao Amazon | `S`=Sim `N`=Não |
| AD_VALIDAB2W | String |  | Validacao B2w | `N`=Nao `S`=Sim |
| AD_VALIDAAMZEX | String |  | Validacao Amazon Extrema | `S`=sim `n`=nao |
| AD_VALIDAB2WEX | String |  | Validacao B2w Extrema | `N`=Nao `S`=Sim |
| AD_VALIDASHOPEE | String |  | Validacao Shopee | `S`=sim `N`=nao |
| AD_VALIDASHOPEEEX | String |  | Validacao Shopee Extrema | `S`=sim `N`=nao |
| AD_VALIDAMAGALU | String |  | Validacao Magazine luiza | `N`=nao `S`=sim |
| AD_VALIDAMAGALUEX | String |  | Validacao Magazine luiza Extrema | `S`=sim `N`=nao |
| AD_VALIDAVIA | String |  | Validacao Via Varejo | `N`=nao `S`=sim |
| AD_VALIDAVIAEX | String |  | Validacao Via Varejo Extrema | `S`=sim `N`=nao |
| AD_VALIDAMELI | String |  | Validacao Mercado Livre | `N`=nao `S`=sim |
| AD_VALIDAMELIEX | String |  | Validacao Mercado Livre Extrema | `S`=sim `N`=nao |
| AD_VALIDACARR | String |  | Validacao Carrefour | `N`=nao `S`=Sim |
| AD_VALIDACARREX | String |  | Validacao Carrefour Extrema | `N`=nao `S`=sim |
| AD_VISIVEL | String |  | É visivel na vtex? | `S`=Sim `N`=Não |
| AD_CODANATEL | String |  | Cod. Anatel |  |
| AD_LISTAVCAMEX | String |  | Lista Camex |  |
| AD_DEPARALOJA | Float |  | Preço DE para Lojas |  |
| AD_GRANEL | String |  | É granel? | `S`=Sim `N`=Não |
| CODPROD | Integer |  | Código |  |
| BH_MKTSYNC | String |  | Sincroniza? |  |

## TGFPRO0200 — 0200 do EFD
Campos: 3

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| DTREF | Date |  | Data Referência |  |
| ALIQICMS | Float |  | Alíquota Interna de ICMS |  |
| CODPROD | Integer |  | Produto |  |

## TGFPRO0200EMP — Empresa
Campos: 4

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| CODEMP | Integer |  | Empresa |  |
| DTREF | Date |  | Data Referência |  |
| ALIQICMS | Float |  | Alíquota Interna de ICMS |  |
| CODPROD | Integer |  | Produto |  |

## TGFPRORVM — Prorrogação Venda Mais
Campos: 9

| Campo | Tipo | Tam | Descrição | Opções |
|-------|------|-----|-----------|--------|
| SEQUENCIA | Integer |  | SEQUENCIA |  |
| PRORROGADO | String |  | Prorrogado VM |  |
| NVDTVENC | DateTime |  | Nova data de vencimento |  |
| DTPROR | DateTime |  | Prorrogado em |  |
| CODUSUPROR | Integer |  | Prorrogado por |  |
| CODPROR | String |  | Cód. Prorrogação VM |  |
| NUFINDESP | Integer |  | Nro Único Despesa |  |
| PENDENTECRIARDESP | String |  | Pendente de Criar Despesa |  |
| NUFIN | Integer |  | Nro Único |  |