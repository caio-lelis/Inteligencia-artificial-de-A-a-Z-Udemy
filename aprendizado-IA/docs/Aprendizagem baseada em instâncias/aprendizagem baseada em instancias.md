## Aprendizado baseado em instâncias

O aprendizado baseado em instâncias é uma técnica de aprendizado de máquina que consiste em armazenar os exemplos de treinamento e fazer previsões com base na similaridade entre os novos exemplos e os exemplos de treinamento. A ideia é que exemplos semelhantes tenham rótulos semelhantes, ou seja, pertençam à mesma classe.

## KNN (K-Nearest Neighbors)

https://didatica.tech/o-que-e-e-como-funciona-o-algoritmo-knn/

É um dos algoritmos mais populares de aprendizado baseado em instâncias. Ele classifica um exemplo de teste com base na classe da maioria dos k exemplos mais próximos a ele. A distância entre os exemplos é calculada usando uma métrica de distância, como a distância euclidiana.


A maioria dos métodos de aprendizado constroem um modelo após o treinamento (árvore de decisão , tabela de probabilidade e etc) e os dados são descartados após a criação do modelo. No entanto, o aprendizado baseado em instâncias mantém os dados de treinamento e faz previsões com base na similaridade entre os exemplos de treinamento e os exemplos de teste. Logo o algoritmo efetivamente não treina , ele pega os dados de treinamento e com o cálculo de distância entre os dados de treinamento e os dados de teste ele faz a previsão.

A generalização / previsão é feita somente quando uma nova instância precisa ser classificada (lazy) , métodos preguiçosos -> aqueles que não constroem um modelo a partir dos dados de treinamento, mas fazem previsões com base na similaridade entre os exemplos de treinamento e os exemplos de teste.

## Cálculo da Distância

### Euclidiana - Distância entre dois pontos em um plano cartesiano. Fórmula:  


### Normalização e padronização dos dados

A normalização e a padronização dos dados são técnicas usadas para transformar os dados em uma escala comum, a fim de facilitar a comparação entre eles. A normalização é usada para transformar os dados em uma escala de 0 a 1, enquanto a padronização é usada para transformar os dados em uma escala com média 0 e desvio padrão 1.

Características do KNN:

- Algoritmo Simples e Poderoso;
- Indicado quando o relacionamento entre as características é complexo;
- Valor de K pequeno: Dados com ruídos ou outliers podem prejudicar
- Valor de K grande: Tendência a classificar a classe com mais elementos (overfitting) - Valor default é 3 ou 5
- Lento para fazer previsões

- Além da Distância Euclidiana, podem ser usadas outras como :
    - Coeficiente de Pearson
    - Índice de Tanimoto
    - City Block