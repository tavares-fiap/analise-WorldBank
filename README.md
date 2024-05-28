# Análise de IXPs Globais

Este repositório contém uma análise gráfica do dataset `ixps_global_geocoded.csv`, que contém informações sobre Pontos de Troca de Internet (IXPs) em todo o mundo.

## Dataset

O dataset `ixps_global_geocoded.csv` contém informações sobre IXPs coletadas de diversas fontes, como o [PeeringDB](https://www.peeringdb.com/), [Peering.ch](https://www.peering.ch/) e [CAIDA](https://www.caida.org/).

As colunas do dataset incluem:

* **country:** País do IXP
* **total_by_country:** Total de IXPs no país
* **city:** Cidade do IXP
* **ixpname:** Nome do IXP
* **alternatenames:** Nomes alternativos do IXP
* **prefixes:** Prefixos de endereço IP usados no IXP
* **sources:** Fontes das informações do IXP
* **url:** URL do IXP
* **participants_pch:** Número de participantes no IXP
* **peak_pch:** Pico de tráfego no IXP
* **avg_pch:** Tráfego médio no IXP
* **status_pch:** Status do IXP
* **only_in:** Se o IXP é exclusivo para uma determinada região
* **region:** Região do IXP
* **year:** Ano de criação do IXP
* **lmic:** Se o IXP está localizado em um país de baixa renda
* **Lat:** Latitude do IXP
* **Lon:** Longitude do IXP

## Análise Gráfica

Este repositório inclui análises gráficas do dataset usando a biblioteca `matplotlib` do Python, que geram os seguintes gráficos:

* **Gráfico de Barras:** Mostra o número de IXPs em cada país.
* **Gráfico de Pizza:** Mostra a proporção de IXPs em cada região do mundo.
* **Histograma:** Mostra a distribuição de IXPs por ano de criação.
* **Gráfico de Dispersão:** Mostra a relação entre o pico de tráfego e o número de participantes em um IXP.
* **Mapa de Dispersão:** Mostra a localização geográfica dos IXPs no mundo.

## Conclusões

A análise gráfica deste dataset fornece insights valiosos sobre a distribuição global de IXPs, incluindo:

* A concentração de IXPs em países desenvolvidos.
* O crescimento da indústria de IXPs ao longo dos anos.
* A correlação entre o pico de tráfego e o número de participantes em um IXP.
* A localização geográfica dos IXPs no mundo.

## Observações

Este é apenas um exemplo simples de análise de dados sobre IXPs. O dataset pode ser usado para explorar diversos outros insights sobre a indústria de IXPs, incluindo:

* A influência dos IXPs na conectividade de internet em diferentes países.
* A relação entre os IXPs e o crescimento econômico.
* As tendências futuras da indústria de IXPs.

## Próximos Passos

Para aprofundar a análise, você pode:

* Explorar outras colunas do dataset para obter insights adicionais.
* Analisar a correlação entre diferentes colunas do dataset.
* Usar técnicas de machine learning para prever o crescimento da indústria de IXPs.
