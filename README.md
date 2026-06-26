# Trabalho-final-de-Topicos-em-Engenharia-de-Software

Para replicar este trabalho, execute environment.yml

Os datasets com informações das corridas de taxi não foram enviadas ao github pois são muito grandes, mas podem ser encontradas nos links abaixo:

Dados taxi 2022:
- Fonte: https://data.cityofnewyork.us/Transportation/2022-Green-Taxi-Trip-Data/8nfn-ifaj/about_data

Dados taxi 2023:
- Fonte: https://data.cityofnewyork.us/Transportation/2023-Green-Taxi-Trip-Data/peyi-gg4n/about_data


Para o correto funcionamento do projeto, é necessário que os seguintes datasets estejam em uma mesma pasta:
Datasets:
- 2022_Green_Taxi_Trip_Data_20260530.csv
- 2023_Green_Taxi_Trip_Data_20260519.csv
- Clima2022.csv
- Clima2023.csv
- ClimaTreino.csv

Os datasets foram detalhados na dissertação e também consta explicação em Tratamento.ipynb

Notebooks:
- Tratamento.ipynb
- TreinamentoModelo.ipynb

Deve ser realizado a execução primeiramente de Tratamento.ipynb. Quando terminar de rodar, será possível executar TreinamentoModelo.ipynb

Os notebooks GridSearch.ipynb e BayesianOptimization.ipynb foram utilizados para realizar a procura por melhores hiperparâmetros, não será necessária sua execução.