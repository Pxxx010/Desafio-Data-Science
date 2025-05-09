# Desafio Data Science - Análise do INSE 2021

Este projeto tem como objetivo analisar e visualizar os dados do Indicador de Nível Socioeconômico (INSE) das escolas brasileiras em 2021, utilizando Python e bibliotecas de ciência de dados.

## Sobre o Projeto

O notebook `Desafio_Data.ipynb` realiza:

- **Carregamento e tratamento dos dados**: Limpeza, renomeação de colunas, remoção de dados desnecessários e padronização de valores categóricos.
- **Análise exploratória**: Estatísticas descritivas e identificação de valores faltantes.
- **Visualizações**: Geração de gráficos para explorar a distribuição do INSE por estado, tipo de rede, localização e classificação socioeconômica das escolas.
- **Exportação dos dados tratados**: Geração de um novo arquivo Excel com os dados prontos para análise.

## Principais Gráficos Gerados

- **Média do INSE por Unidade da Federação (UF)**
- **Distribuição da Média do INSE por Tipo de Rede (Federal, Estadual, Municipal, Privada)**
- **Média do INSE por Localização da Escola (Urbana/Rural)**
- **Distribuição de Escolas por Classificação do INSE (Muito Baixo, Baixo, Médio Baixo, Médio, Médio Alto, Alto, Muito Alto)**

> **Obs.:** Os gráficos são salvos automaticamente em uma pasta chamada `results` durante a execução do notebook.

## Como Executar

1. **Pré-requisitos**:
   - Python 3.x
   - Jupyter Notebook ou Google Colab
   - Bibliotecas: `pandas`, `matplotlib`, `seaborn`, `requests`, `openpyxl`

2. **Execução**:
   - Abra o arquivo `Desafio_Data.ipynb` em seu ambiente preferido.
   - Execute as células sequencialmente para baixar, tratar, analisar e visualizar os dados.

3. **Dados**:
   - O arquivo de dados original está disponível como `INSE_2021_escolas.xlsx`.
   - O notebook faz o download automático do arquivo, mas você pode utilizar o arquivo local se preferir.

## Estrutura do Projeto

```
.
├── Desafio_Data.ipynb
├── INSE_2021_escolas.xlsx
└── results/
    ├── media_inse_por_uf.png
    ├── distribuicao_inse_por_rede.png
    ├── media_inse_por_localizacao.png
    └── distribuicao_classificacao_inse_geral.png
```

## Licença

Este projeto é apenas para fins educacionais. 