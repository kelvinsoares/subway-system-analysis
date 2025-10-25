# Análise de Dados — Estações do Sistema de Metrô e Trens de São Paulo

Estudo analítico e exploratório sobre as linhas e estações do metrô paulistano (e sistema da CPTM): modernização, ritmo de expansão e indicadores executivos.

## Objetivo
Explorar e visualizar informações do dataset metro_sp2_ordenado_por_linha.csv, incluindo:
  
  - Quantidade de estações por linha;
  - Distribuição da idade (modernização);
  - Estações mais antigas e mais novas;
  - Ritmo de expansão por linha;
  - Linha do tempo das inaugurações;
  - Indicadores executivos (% > 40 anos, média de idade, etc.).

## Estrutura
 ```bash
  ├── subway_system_analysis/
  │   └── subway_system_analysis.ipynb
  │   └── train_stations.csv
  ├── README.md
 ```

## Dados
O notebook utiliza o arquivo CSV com as seguintes colunas principais:

  - Linha → nome ou código da linha do metrô
  - Nome → nome da estação
  - Inauguração → data de inauguração
  - Construção → por quem a estação foi construída
  - Idade → calculada automaticamente se não existir

## Para executar:
  ```bash
  python -m venv .venv

  # Windows
  .venv\Scripts\activate

  # macOS/Linux
  source .venv/bin/activate
  ```
  ```bash
  pip install pandas numpy matplotlib jupyter
  ```
  ```bash
  ./analise_metro_sp.ipynb
  ```

## Requisitos
  ```bash
  pandas >= 2.0.0
  numpy >= 1.24.0
  matplotlib >= 3.7.0
  jupyter >= 1.0.0
  ```
