## Escalonamento de Atributos

O escalonamento de atributos é uma técnica de pré-processamento de dados que visa normalizar os dados de forma que todos os atributos tenham a mesma escala. Isso é importante porque muitos algoritmos de aprendizado de máquina são sensíveis à escala dos atributos, e o desempenho do modelo pode ser prejudicado se os atributos tiverem escalas muito diferentes. Tornando o algoritmo enviesado para os atributos com maior escala.

Existem várias técnicas de escalonamento de atributos, e as mais comuns são a padronização e a normalização.

### Normalização (Normalization)

A normalização é uma técnica de escalonamento que visa transformar os valores dos atributos para um intervalo específico, geralmente entre 0 e 1. Isso é feito subtraindo o valor mínimo do atributo e dividindo pelo intervalo de valores do atributo.

A fórmula para normalização é a seguinte:


<img style="border-radius: 25%" src="../assets/formula_normalizacao.png" width=400px>


### Padronização (Standardization)

A padronização é uma técnica de escalonamento que visa transformar os valores dos atributos de forma que eles tenham média zero e desvio padrão um. Isso é feito subtraindo a média do atributo e dividindo pelo desvio padrão.

A fórmula para padronização é a seguinte:

<img style="border-radius: 25%" src="../assets/formula_padronizacao.png" width=400px>

### Quando usar normalização ou padronização?

A escolha entre normalização e padronização depende do algoritmo de aprendizado de máquina que será utilizado. Alguns algoritmos, como o K-means, são sensíveis à escala dos atributos e funcionam melhor com a padronização. Outros algoritmos, como as redes neurais, são menos sensíveis à escala dos atributos e podem funcionar bem com a normalização.

Em geral, a padronização é uma técnica mais robusta e é recomendada quando não se sabe qual técnica usar. No entanto, é importante testar ambas as técnicas e verificar qual delas produz os melhores resultados para o seu problema específico.

Dica do curso: 

- Padronização é mais considerada quando temos outliers na base de dados.

### Aplicação

Com o avanço das bibliotecas de aprendizado de máquina, como o Scikit-learn, a aplicação de escalonamento de atributos é muito simples. Basta utilizar a classe `StandardScaler` para padronização ou `MinMaxScaler` para normalização.
