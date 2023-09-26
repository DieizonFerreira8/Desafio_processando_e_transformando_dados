# Processamento de Dados Simplificado com Power BI

Foi criado o seguinte conjunto de Dados

```csv
ID, Nome do Produto, Preço Unitário, Quantidade Vendida, Data da Venda
1, Camiseta, 20.0, 15, 2023-01-01
2, Calça Jeans,, 10, 2023-01-02
3, Tênis, 50.0, ,2023-01-03
4, Camiseta, vinte, 5, 2023-01-04
5, , 30.0, 7, 2023-01-05
6, Calça Jeans, 40.0, 8,
7, Camiseta, 20.0, 12, 2023-01-06
8, Calça Jeans, 35.0, 8, 2023-01-07
9, Tênis, 50.0, 10,2023-01-08
10, Camiseta, 20.0, 5, 2023-01-09
11, Calça Jeans,, 7, 2023-01-10
12, Tênis, 50.0, ,2023-01-11
13, Camiseta,, 5, 2023-01-12
14, , 30.0, 7, 2023-01-13
15, Calça Jeans,, ,2023-01-14
16, Tênis,, ,2023-01-15
```
Este conjunto de dados tem alguns dos seguintes problemas:
- Valores ausentes
- Tipos de dados incorretos
- Dados inconsistentes
- Dados ausentes
- Dados em branco

# Usei o Power Query da seguinte forma para limpar esses dados:
- 1 - Para lidar com valores ausentes, preenchi os preços unitários ausentes com a média dos preços unitários existentes.
- 2 - Para corrigir tipos de dados incorretos, selecionei as colunas desejada, cliquei em transformar e mudei seu tipo, para os erros que ficaram eu substitui por nullo e apliquei o passo 1.
- 3 - Para lidar com dados inconsistentes, um exemplo é o campo ```nome_produto``` que tinha um espaço em branco, foi substituido para ```'N/A'```.

# Criação de Dashboard
Após a finalização da transformação, os dados foram carregados e foi criado um Dashboard com as visualizações.

# Observações
Criei um dataset, pois não encontrei o arquivo que a instrutora demonstrou na apresentação do desafio, apesar do dataset simples do meu projeto, acredito que ultilizei uma boa parte dos processos de transformações mais comuns e que cabia para o cenário em questão.