# Análise de Óbitos por Acidentes de Trânsito em Fortaleza (2010–2019)

Este projeto analisa a evolução do número de óbitos por acidentes de trânsito em Fortaleza, com base em dados públicos do Ministério da Saúde / DATASUS.

## Objetivo

Visualizar tendências e padrões temporais entre os anos de 2010 e 2019, com foco em transformar dados brutos em insights visuais.

## Estrutura do Projeto

```
analise-obitos-fortaleza/
├── dados/                # Dados limpos
│   └── fortaleza_obitos_transito.csv
├── imagens/              # Gráficos gerados
│   └── grafico_colunas.png
├── notebooks/            # Código em Python (Google Colab)
│   └── analise_fortaleza.ipynb
└── README.md             # Descrição do projeto
```

## Gráficos Criados

* Gráfico de colunas: Número de óbitos por ano
* Gráfico de linha: Tendência temporal (opcional)
* Cálculo de média, mínimo e máximo (com `describe()`)

## Ferramentas e Tecnologias

* Python (Pandas, Seaborn, Matplotlib)
* Google Colab
* Dataset CSV com dados limpos

## Fonte dos Dados

Ministério da Saúde - SIM/DATASUS
[https://datasus.saude.gov.br/](https://datasus.saude.gov.br/)

---

Projeto desenvolvido por **Zara Takion** como parte do portfólio de Análise de Dados.
