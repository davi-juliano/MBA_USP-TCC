# TCC - MBA USP ESALQ (Influência Meteorológica em Colheitas dos Estados do Brasil – Um Estudo de Previsão de Demandas)

## Contexto

O estudo tem como objetivo uma análise das cadeias de suprimento de recursos agráveis (milho, soja e cana de açúcar) dos estados brasileiros, havendo uma base de produção e consumo desses bens de acordo com determinado tempo. Os dados foram extraídos por meio de um órgão governamental que estuda e regulamenta toda a produção de recursos agráveis: a Empresa Brasileira de Pesquisa Agropecuária [EMBRAPA]

## Métricas Abordadas

* Base de dados de área colhida: é a base de dados que descreve a área colhida total de um determinado insumo por uma determinada quantidade de tempo (ou seja, ano, mês e dia) e região (UF).
* Base de dados de média de produtividade (Área Colhida): é a base de dados que descreve a média de área colhida de um determinado insumo por uma determinada quantidade de tempo (ou seja, ano, mês e dia) e região (UF). Essa média de área colhida é denominada média de produtividade.
* Base de dados de área plantada: é a base de dados que descreve a área plantada total de um determinado insumo por uma determinada quantidade de tempo (ou seja, ano, mês e dia) e região (UF).
* Base de dados de quantidade produzida: é a base de dados que descreve a quantidade produzida total de um determinado insumo por uma determinada quantidade de tempo (ou seja, ano, mês e dia) e região (UF).

## Métodos Utilizados

* Facebook Prophet: O Facebook Prophet é uma implementação de um previsor voltada a ter parâmetros que podem ser ajustados sem conhecer os detalhes do modelo subjacente. A estratégia de implementação que é utilizada é a de um modelo de série temporal divisível em três principais componentes de modelo: a tendência, a sazonalidade e os feriados.
* ARIMA: O ARIMA é um método clássico utilizado para ajustar dados de séries temporais e fazer previsões. Akaike Information Criterion [AIC] e Bayesian Information Criterion [BIC] são usados para comparar os diferentes modelos. Ele considera os valores de AIC e BIC para encontrar a melhor combinação de parâmetros.
* VAR: VAR é um modelo de séries temporais multivariadas que pode ser usado para prever mais de uma variável em conjunto. Ele pode ser aplicado em cenários onde múltiplas variáveis têm dependência entre si. No modelo VAR, cada variável é modelada como uma combinação linear de observações passadas de si mesma e de outras variáveis.
