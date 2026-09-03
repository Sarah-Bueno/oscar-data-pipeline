# Oscar Data Pipeline

Projeto de integração e enriquecimento de dados utilizando Python, Pandas, web scraping e API REST.

## Objetivo

Construir um pipeline de dados integrando informações dos indicados ao Oscar de Melhor Filme Internacional com dados geográficos da API de países do IBGE.

![grafico_subregioes[(grafico_suregioes.png)

## Tecnologias

- Python
- Pandas
- Requests
- API REST
- JSON
- Web Scraping
- ETL
- Data Cleaning
- Data Integration
- Matplotlib

## Pipeline

1. Extração dos dados do Oscar via Wikipédia
2. Coleta de dados da API do IBGE
3. Normalização do JSON
4. Limpeza e padronização dos dados
5. Tratamento de países históricos e nomenclaturas diferentes
6. Merge entre as bases
7. Validação das correspondências
8. Análise dos indicados por sub-região

## Principais resultados

A análise mostrou forte concentração das indicações em sub-regiões europeias.

- Europa Ocidental: 80 indicações
- Europa Meridional: 63
- Europa Setentrional: 46
- Europa Oriental: 34
- América Latina e Caribe: 30

## Desafios de integração

Durante o merge foram identificadas diferenças de nomenclatura entre as fontes, além de países históricos e casos especiais como União Soviética, Iugoslávia, Alemanha Ocidental, Taiwan e Palestina.

Esses registros foram tratados separadamente para evitar associações incorretas.

## Projeto completo

O notebook contém todas as etapas de extração, transformação, integração, validação e análise dos dados.

## Autor

Sarah Bueno
