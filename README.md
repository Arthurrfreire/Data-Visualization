## Criação de Gráficos de Pizza (Pie Charts) em Python com Seaborn e Pandas

Este projeto demonstra como criar gráficos de pizza (pie charts) em Python utilizando as bibliotecas Seaborn e Pandas. Os gráficos de pizza são úteis para visualizar a distribuição de dados categóricos, mostrando a proporção de cada categoria em relação ao todo.
Seaborn (Visualização Estatística de Dados)

O Seaborn simplifica a criação de gráficos de pizza com seu alto nível de abstração e integração com o Matplotlib.

## Explicação:

* `labels:` Lista com os rótulos das categorias.
* `sizes:` Lista com os valores de cada categoria.
* `autopct='%1.1f%%':` Formata os valores das fatias como porcentagens com uma casa decimal.
* `startangle=140:` Define o ângulo inicial do gráfico (opcional).

## Pandas (Biblioteca de Análise de Dados)

O Pandas oferece uma maneira conveniente de criar gráficos de pizza diretamente a partir de um DataFrame.

## Explicação:

* Um DataFrame é criado a partir dos dados.
* A coluna `Categorias` é definida como índice do DataFrame.
* O método `df.plot.pie()` é usado para criar o gráfico, especificando a coluna `Tamanhos` como os valores das fatias.

## Observações

* Ambas as bibliotecas oferecem opções de personalização para cores, legendas, estilos, etc.

* Experimente diferentes combinações de dados e configurações para criar gráficos de pizza que melhor se adaptem às suas necessidades de visualização.

* Consulte a documentação oficial do Seaborn e do Pandas para obter mais informações sobre as opções de personalização disponíveis.
