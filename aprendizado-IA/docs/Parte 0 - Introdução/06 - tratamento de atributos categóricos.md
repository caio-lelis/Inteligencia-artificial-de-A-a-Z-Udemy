# Tratando dados categóricos

Os dados categóricos são variáveis que contêm valores de texto em vez de números. Por exemplo, a cor de um carro ou a marca de um computador. Os algoritmos de aprendizado de máquina geralmente exigem que os dados de entrada sejam numéricos, portanto, é necessário converter os dados categóricos em dados numéricos antes de aplicar um algoritmo de aprendizado de máquina.

Existem várias maneiras de tratar dados categóricos, no curso foi ensinado a usar o LabelEncoder e o OneHotEncoder, mas existem outras maneiras de tratar esses dados.

LabelEncoder: O LabelEncoder converte cada valor categórico em um número. Por exemplo, se tivermos uma variável categórica com os valores "vermelho", "verde" e "azul", o LabelEncoder converterá esses valores em 0, 1 e 2, respectivamente.

OneHotEncoder: O OneHotEncoder converte cada valor categórico em um vetor binário. Por exemplo, se tivermos uma variável categórica com os valores "vermelho", "verde" e "azul", o OneHotEncoder converterá esses valores em [1, 0, 0], [0, 1, 0] e [0, 0, 1], respectivamente.