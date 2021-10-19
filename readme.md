Projeto de estudo
 Detecção de doença cardiovascular com modelo de classificação 

DATA PREP

-idade de dias para anos
-altura de centímetro para metro
-distribuição das variáveis numéricas
-dados nulos
-dados duplicados
-distribuição dos dados categóricos 
-distribuição dos dados categóricos em relação a ter ou não DC
-quantidade de homens e mulheres na  base de dados
-proporção de homens e mulheres fumantes
-proporção de homens e mulheres com DC
-estatísticas dos dados
-valores inconsistentes da altura e substituídos pela mediana
-valores inconsistentes de peso e substituídos pela mediana
-casos que distólica > sistólica
-casos que que a distólica e sistólica estão maiores que 97.5% dos dados e menores que 2.5% dos dados
-correlação entre os dados


MODELO

- treineinamento do modelo com a decision tree classifier com critério entropy
- validação com a matriz de confusão
- accuracy, f1, recall e precision
- treinamento novamente com o cross validate

- as melhores métricas foram proferidas no primeiro modelo.

RESPOSTAS

O modelo atingiu pouco mais de 60% de precisão

Para uma empresa fictícia se o preço do diagnóstico, pago pelo cliente, variar de acordo com a precisão e o cliente pagar R$500,00 a cada 5% de acurácia acima de 50% a empresa poderá cobrar até o valor de R$1000 por diagnóstico.