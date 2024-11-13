# Previsão de vendas com séries temporais
Os dados de treino vão de fevereiro de 1990 a setembro de 2023, e os dados de treino vão de outubro de 2023 a setembro de 2024.

<img width="950px" align="center" src="https://raw.githubusercontent.com/Lud-lud/previsao_vendas_series_temporais/refs/heads/main/previsao_vendas.png" />

Este projeto foi desenvolvido com dados de unidades comercializadas de veículos, obtidos pelo [Portal de Dados Abertos](https://dados.gov.br/dados/conjuntos-dados/7384-vendas-de-veiculos-pelas-concessionarias-automoveis).

As vendas são contabilizadas quando os veículos são emplacados, o que gera uma Nota Fiscal de venda. As vendas podem ser diretas (com Nota Fiscal emitida por CNPJ de fabricante de veículos) ou a varejo (todos os outros casos).

A fonte original dos dados é a Fenabrave [Federação Nacional da Distribuição de Veículos Automotores].

O objetivo deste projeto é treinar alguns modelos preditivos simples para séries temporais e selecionar aquele que resultará em menor erro de previsão.

Os valores previstos pelo modelo podem ser visualizados no gráfico acima juntamente com as margens de erro.

Foi feita uma previsão para os meses seguintes de 2024 e para todos os meses de 2025 com base no modelo treinado.

Veja o desenvolvimento completo do projeto [aqui](https://github.com/Lud-lud/previsao_vendas_series_temporais/blob/main/previsao_vendas_automoveis.ipynb).
