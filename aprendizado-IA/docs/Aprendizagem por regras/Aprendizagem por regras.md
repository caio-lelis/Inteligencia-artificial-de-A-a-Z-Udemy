# Aprendizagem por Regras

## Introdução

A aprendizagem por regras é uma técnica de aprendizado de máquina que consiste em extrair regras a partir de um conjunto de dados. Essas regras são utilizadas para fazer previsões sobre novos dados, com base nas relações identificadas nos dados de treinamento. A aprendizagem por regras é uma técnica de aprendizado supervisionado, ou seja, ela requer um conjunto de dados rotulados para treinar o modelo.

As regras extraídas pela aprendizagem por regras são geralmente expressas na forma de "se-então", onde as condições são baseadas nos atributos dos dados e as ações são as previsões feitas pelo modelo. Por exemplo, uma regra extraída de um conjunto de dados de clientes de um banco pode ser "se o saldo da conta for maior que 1000, então o cliente é um bom pagador".

## Algoritmos de Aprendizagem por Regras

### OneR (One Rule)

Tem como premissa fazer o teste de coisas simples primeiro; é um algoritmo de aprendizado de regras que tenta encontrar uma única regra que seja capaz de fazer previsões precisas sobre um conjunto de dados. O algoritmo OneR é baseado em uma abordagem de força bruta, onde todas as combinações possíveis de regras são testadas e a melhor regra é selecionada com base em critérios de avaliação, como a acurácia das previsões.

- Um atributo é selecionado como o atributo de decisão, e para cada valor desse atributo, é calculada a classe mais frequente. A regra final é aquela que tem a menor taxa de erro.
 
Aplicação do Algoritmo OneR:

    - Passo 1: Para cada atributo, calcule a regra que minimiza o erro.
    - Passo 2: Selecione a regra com o menor erro.
    - Passo 3: Aplique a regra ao conjunto de teste.
    - Passo 4: Calcule a taxa de erro.
    - Passo 5: Repita os passos 1 a 4 para cada atributo.

### Algoritmo PRISM

