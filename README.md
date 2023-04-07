# olist-ml-models

Projeto de Machine Learning no contexto de um e-commerce.

Nosso objetivo será, a priori, criar um modelo de Machine Learning para ajudar o negócio da empresa Olist. Dentre as possibilidades temos:

1. Predição de Churn dos vendedores
2. Predição de ativação dos vendedores
3. Predição de atraso no pedido
4. Clustering de vendedores

## Índice
- [Como vamos nos organizar](#como-vamos-nos-organizar)
  - [Cronograma](#cronograma)
  - [Ementa](#ementa)
  - [Pré requisitos](#pre-requisitos)
- [Sober o Instituto Aaron Swartz](#sobre-o-instituto-aaron-swartz)
- [Sobre o instrutor](#sobre-o-instrutor)

## Como vamos nos organizar?

Passaremos por todas etapas do ciclo analítico, desde ETL das fontes de dados, criação de `feature store`, criação da `ABT` (_Analytical Base Table_), treinamento dos algoritmos, implementação do algoritmo campeão para novas predições. Utilizaremos ainda o `MLFlow` para gestão de nossos modelos.


### Ementa

#### 1 - Introdução à ML + Definição do problema

No primeiro dia de curso, conheceremos o ciclo básico de desenvolvimento de um modelo (aplicação) de Machine Learning. Além disso, juntos, de forma colaborativa, definiremos qual será o problema de negócio que gostaríamos de resolver utilizando técnicas preditivas.

#### 2 - Brainstorm de variáveis + Criação Feature Store Pt. 1

Com o problema bem definido, podemos discutir quais são as variáveis (características, atributos, etc) que ajudarão a prever o evento de interesse. isto é, qual conjunto de informações podemos criar para ajudar na solução de nosso problema. Ainda neste momento, as primeiras variáveis serão criadas em suas tabelas de `Feature Stores`.

#### 3 - Criação Feature Store Pt. 2

Continuação da criação das variáveis relevantes para nosso estudo. É importante que ao final deste dia, todas as variáveis estejam devidamente construídas e disponíveis para consulta.

#### 4 - Criação da ABT

Com todas as nossas variáveis criadas e disponíveis, temos condições de processar a nossa tabela definitiva para treinamento de uma algoritmo de Machine Learning. O nome desta tabela é `ABT - *Analytical Base Table*`, onde possui todas informações necessária para solução de nosso problema de negócios, i.e. features (variáveis, características, etc.) e target (variáveis resposta, alvo).

#### 5 - Treinando algoritmos com MLflow

Chegou o momento de treinar nossos primeiros algoritmos de Machine Learning. Utilizaremos a biblioteca MLFlow para realizar a gestão do ciclo de vida de nossos modelos. Desta forma, conseguimos identificar a performance, métricas, parâmetros e variáveis de cada modelo, facilitando assim a tomada de decisão do modelo campeão.

#### 6 - Escolhendo melhor algoritmo + Deploy

Ao definirmos o modelo campeão, podemos realizar novas predições e criar um novos script para fazer este processo de forma automática. Isto é, usar o nosso modelo para ajudar o negócio com novas possibilidades.

