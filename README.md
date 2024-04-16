Atividade para a disciplina de big data com o professor Marco Mialaret

A base de dados analisada é disponibilizada pela Agência Nacional do Petróleo, Gás natural e Biocombustíveis(ANP) e abrange os períodos
de Maio 2004 à Maio de 2021.

A Agência divulga semanalmente relatórios sobre os preços do gás, diesel e outros combustíveis utilizados nos transportes em todo o país. Esses conjuntos de dados trazem o valor médio por litro, número de postos de gasolina analisados ​​e outras informações agrupadas por regiões e estados do Brasil.


Os valores NULOS estão representados pelo valor -99999


A análise de variações nos preços dos combustíveis é importante devido ao impacto econômico significativo que ele causa no bolso dos consumidores brasileiros e que afeta custos de produção e o custo de transporte de bens e serviços, além disso, o constante aumento dos preços pode impulsionar uma crescente transição para fontes de energias sustentáveis e carros elétricos.






---------------------------------------------------------------------------------------------------------------------------------------------------

DICIONÁRIO DE VARIÁVEIS

-DATA INICIAL - Data de início da coleta de dados (Dtype - datetime)
-DATA FINAL - Data final da coleta de dados(neste dataset as datas inicial e final correspondem ao período de uma semana) (Dtype - datetime)
-REGIÂO - Região brasileira onde foi feita a coleta de dados (Dtype - Object)
-ESTADO - Estado brasileiro onde foi feito a coleta de dados (Dtype - Object)
-PRODUTO - Tipo de combustível analisado (Dtype - Object)
-NÚMERO DE POSTOS PESQUISADOS - Quantidade de postos pesquisados durante o período de coleta(uma semana) (Dtype - int64)
-UNIDADE DE MEDIDA - Unidade de medida utilizada para representar o combustível e método de venda (ex: R$/Litro) (Dtype - Object)
-PREÇO MÉDIO REVENDA - Média do preço final cobrado ao consumidor nos postos de combustíveis (Dtype - float64)
-DESVIO PADRÃO REVENDA - Calculo do grau de variação nos preços de revenda (Dtype - float64)
-PREÇO MÍNIMO REVENDA - Menor preço encontrado nos postos de combustíveis durante o período pesquisado (Dtype - float64)
-PREÇO MÁXIMO REVENDA - Maior preço encontrado nos postos de combustíveis durante o período pesquisado (Dtype - float64)
-MARGEM MÉDIA REVENDA - Média da margem de lucro obtida na revenda durante o período pesquisado (Dtype - object)
-COEFICIENTE DE VARIAÇÃO REVENDA - Variabilidade do preço de distribuição em relação média observada (Dtype - float64)
-PREÇO MÉDIO DISTRIBUIÇÃO - Média do preço de venda dos combustíveis para os postos  (Dtype - object)
-DESVIO PADRÃO DISTRIBUIÇÃO - Calculo do grau de variação do preço pago pelos postos nas distribuidoras (Dtype - object)
-PREÇO MÍNIMO DE DISTRIBUIÇÃO - Preço mínimo pago pelos postos nos combustíveis (Dtype - object)
-PREÇO MÁXIMO DE DISTRIBUIÇÃO - Preço máximo pago pelos postos nos combustíveis (Dtype - object)
-COEFICIENTE DE VARIAÇÃO DISTRIBUIÇÃO - Variabilidade do preço de distribuição em relação média observada (Dtype - object)

---------------------------------------------------------------------------------------------------------------------------------------------------