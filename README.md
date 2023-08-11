# Previsão de Custos de Seguros de Saúde

<sub>TAGS: Auto Machine Learning; Pandas; Numpy; Matplotlib; Seaborn; Scikit-learn; PyCaret; Bayesian Ridge; Lasso Regression; Cross-Validation; Grid Search; Pipelines.

<p align="center">
  <img src="capa_p5.png" >
</p>

> **Acesse o projeto completo aqui: [Notebook do Projeto](https://github.com/gabrielrflopes/Health_Insurance_Prediction/blob/main/AutoML_aplicado_%C3%A0_previs%C3%A3o_de_custo_de_seguro_de_vida.ipynb)**

Diante dos desafios que muitas pessoas enfrentam ao se comprometerem com os custos de um plano de saúde, a emergência de modelos de aprendizado de máquina oferece uma esperança tanto para os indivíduos quanto para a indústria de saúde como um todo.

Ao aproveitar o poder da análise de dados e algoritmos preditivos, esses modelos podem oferecer insights sobre os potenciais encargos financeiros associados aos serviços de saúde.

Esse tipo de inovação permite que formuladores de políticas e provedores de saúde criem soluções que mitiguem os efeitos adversos dos altos custos dos planos.

Além disso, o potencial de modelos capazes de prever os custos de seguros de saúde está associado à possibilidade de tornar os cuidados médicos mais acessíveis. Armados com o conhecimento sobre os custos, pessoas poderão tomar decisões informadas à respeito dos planos, deixando de lado o dilema de adiar os tratamentos necessários ou arriscar-se com dívidas exorbitantes.

## Objetivos

Os objetivos deste projeto consistem na análise exploratória e visualização de dados, visando conhecer as circunstâncias e fatores que influenciam no aumento ou diminuição do custo dos seguros de saúde. Para isso, serão analisados dados demográficos e relacionados a estilos de vida, como o hábito do cigarro e obesidade. A partir disto, serão construídos os modelos de regressão para prever o valor anual do plano de saúde para determinado indivíduo.

A estrutura do projeto consiste em:

* Realizar uma análise exploratória dos dados, com visualização de padrões e tendências;
* Aplicar feature engineering para aumentar o poder preditivo dos modelos e ampliar a consciência situacional sobre o problema;
* Processamento dos dados para aplicação nos modelos de machine learning;
* Aplicar técnicas de AutoML para montar modelos de baseline, comparar as performances, criar pipelines de processamento, ajustar os dados e realizar previsões;
* Avaliar as métricas de desempenho dos modelos mais promissores e realizar previsões em novos dados;
* Escolher o modelo com o menor erro e salvá-lo para uso posterior em dados inéditos.

Em suma, neste projeto iremos utilizar o AutoML baseado no PyCaret para criar modelos de regressão e aplicar as técnicas de otimização de desempenho, até termos, ao final, um modelo com a melhor performance na previsão de custos de seguros de saúde.

## Resultados

Utilizando um pipeline para pré-processamento, comparação, construção e otimização de modelos de regressão linear, foram escolhidos três modelos para testes: **Bayesian Ridge**, **Lasso Lars** e **Lasso Regression**. A média de desempenho destes três modelos após otimização de hiperparâmetros via *Grid Search* foi de um R2 igual a 0,8779 e um RMSE de 4161. Dentre os três, se destacou o **Bayesian Ridge** com R2 de 0,878 e RMSE de 4159. Este modelo foi capaz de prever os custos anuais de um plano de saúde para novos indivíduos com um boa aproximação, dentro de um intervalo de 13% do valor real tabelado.

[Acesse o Notebook do Projeto](https://github.com/gabrielrflopes/Health_Insurance_Prediction/blob/main/AutoML_aplicado_%C3%A0_previs%C3%A3o_de_custo_de_seguro_de_vida.ipynb)

## Links Importantes

* [Medium](https://medium.com/@grflopes)
* [LinkedIn](https://www.linkedin.com/in/gabrielrflopes/)

