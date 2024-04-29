# Análise de Cluster de Clientes de Operadora de Cartão de Crédito

Este repositório contém uma análise detalhada dos clientes de uma operadora de cartão de crédito, com a utilização da técnica de clusterização k-means para identificar diferentes segmentos de clientes e analisar sua lealdade à marca. O conjunto de dados comtém 660 registro e (7) sete colunas e para realizar as análises e exploração dos dados foi utilizada a linguagem R.

-------------------------------------------------------------------------------------------------

## Metodologia
Antes da aplicação da técnica em foco, foi realizado um pré-processamento simples, pois o banco de dados estava bem estruturado, em seguida uma exploração minuciosa dos dados para compreender melhor as características dos clientes e preparar os dados para o processo de clusterização.
Seguem abaixo alguns resutados das análises realizadas individualmente nas variáveis.

-------------------------------------------------------------------------------------------------

#### Histograma da variável (Média de limite d crédito)
![image](https://github.com/AurelianoGon/An-lise_cluster_banco/assets/106711467/6649de3f-f539-47dd-a7f9-ccd700d4e64c)

-------------------------------------------------------------------------------------------------

#### Histograma da variável (Total de visitas ao banco)
![image](https://github.com/AurelianoGon/An-lise_cluster_banco/assets/106711467/08e18f3d-8100-4b20-b69b-ba782020d671)

-------------------------------------------------------------------------------------------------

#### Histograma da variável ( Total de chamadas realizadas)
![image](https://github.com/AurelianoGon/An-lise_cluster_banco/assets/106711467/a6283ab0-4e15-41e7-96fa-1a19729cc48e)

-------------------------------------------------------------------------------------------------

#### Após a análise individual das variáveis foram feitas algumas Análises de Relação entre algumas variáveis.
#### Realizada toda a análise exploratória e descritiva, foi aplicada uma padronização dos dados e a partir disso aplicamos o método Elbow para identificação de números de clusters e tivemos o seguinte resultado.

![image](https://github.com/AurelianoGon/An-lise_cluster_banco/assets/106711467/1de55f77-234f-4b35-8502-7f73a9b14d33)

-------------------------------------------------------------------------------------------------

#### A técnica de clusterização k-means foi aplicada aos dados pré-processados para identificar diferentes grupos de clientes. Logo, foram realizadas outra análises dos resultados obtidos. Seguem os resultados abaixo.

![image](https://github.com/AurelianoGon/An-lise_cluster_banco/assets/106711467/eec8fcd5-db6e-4d68-83e3-15b7f5b88eb1)

-------------------------------------------------------------------------------------------------

## Resultados Principais:
1. Categorizar os clientes de uma operadora de cartão de crédito.
2. Analisar os grupos de clientes mais e menos leais à marca (por meio do uso).
3. Métricas de avaliação da qualidade dos clusters.

### Próximos Passos:
Refinamento da análise utilizando técnicas de clusterização mais avançadas.


### Como Contribuir:
Se você tem sugestões de melhorias ou deseja contribuir com este projeto, fique à vontade para abrir uma issue ou enviar um pull request. Sua contribuição é muito bem-vinda!

### Contato:
brunnamian@gmail.com

### Agradecimentos:
Agradecemos a todos os colaboradores e aos desenvolvedores de bibliotecas de código aberto que tornaram este projeto possível.
