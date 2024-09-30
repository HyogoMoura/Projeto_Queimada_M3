# Projeto Final - Técnicas de Programação (Python)
> *Turma 11080 - Santander Coders 2024 - Engenharia de Dados*

Desenvolvimento do projeto "Acompanhamento de Quimadas Brasil 2023-2024" com o intuito de extrair e manipular dados utilizando a biblioteca PANDAS, por fim, gerar insights através da plotagem de gráficos.

**Todo projeto foi desenvolvido com a linguagem de programação Python.**

## ✒️Autores 
- [Alessandra Cruz](https://github.com/alessandracruz)
- [Álex Buracosky](https://github.com/aburacosk)
- [Diana Osorio](https://github.com/diana468)
- [Diogo Moura](https://github.com/HyogoMoura)
- [Felipe Zanardo](https://github.com/FelipeBZanardo)
- [Thiago Silva](https://github.com/thiagodemedeiros)

## 📋Enunciado do Projeto

Descrição
- Este notebook contém a descrição do projeto prático do módulo: Técnicas de programação I. Neste projeto aplicaremos as técnicas aprendidas em aula para criarmos uma análise exploratória sobre um conjunto de dados.

Objetivo
- Realizar uma análise exploratória de dados utilizando datasets relacionados ao Brasil. Estruture sua análise criando um storytelling: Uma história contada com informações, gráficos e imagens (opcional) e medidas estatísticas, associando dados a fatos em uma linha do tempo. Você está livre para incluir quantas bases considerar necessário e filtrar as informações mais relevantes para sua história.

Dados
- Esta é uma lista de fontes que vocês podem utilizar. Você está livre para utilizar esta e outras fontes de dados, desde que haja uma concordância prévia com o professor.

Fontes de dados sugeridas:
- Covid19br (https://github.com/wcota/covid19br/)
- Agência Nacional de Petróleo e Gás (https://bit.ly/3hf8rbZ)
- DataSUS (ftp.datasus.gov.br)*
- Dados.gov.br (https://bit.ly/3fPA1MO)
- Kaggle (https://www.kaggle.com/)
*Obs: pode ser acessado por um cliente FTP (Ex.: Filezilla)

Organização e entregáveis:
- O projeto completo (Notebook, código-fonte, link para fontes, bases e demais artefatos) deve ser publicado conforme instruções do LMS.

Critérios de avaliação
**A avaliação será feita com base nos artefatos entregues e na sua apresentação.**
**A estrutura abaixo lista sugestões do que pode conter no seu trabalho.**

- Apresentação da análise
- Storytelling;
- Insights (padrões que descrevam os elementos da base);
- Descrição do problema;
- Proposta de solução;

Entregáveis
- Relatório com análise exploratória de dados;
- Descrição das variáveis (Dados faltantes, tipos de dados, informações relacionadas e fontes);
- Limpeza da base
- Análise Univariada e Multivariada
- Medidas estatísticas;
- Comparações;
- Tendências de crescimento ou queda;
- Gráficos (opcional)

Critérios:
- Análise (O nível de exploração dos dados, quantidade de bases e variáveis);
- Reprodutibilidade (O código será executado e o resultados precisam ser reproduzidos);
- Comunicação (Explique o problema e como a equipe explorou os dados);
- Tempo de apresentação: A depender da quantidade de grupos. (Aproximadamente de 15 ~ 20 minutos)

## 📋 Descrição do Projeto

**1) Extração de Dados:**
- [Programa-de-Quimadas-INPE](https://terrabrasilis.dpi.inpe.br/queimadas/portal/)

**2) Manipulação de Dados:** 
- Formatacao das tabelas e indices;
- limpeza dos dados;
- Verificação e conversão dos tipos de dados de cada coluna;
- Merge de DataFrames;

**3) Geração de gráficos:**
- 3.1Mapa de calor (Heatmap) de Risco de Fogo
- 3.2. Mapa de precipitação
- 3.3. Gráfico de Linha para Número de Dias sem Chuva
- 3.4. Gráfico de Dispersão (Scatter Plot) Risco de fogo x Precipitacao
- 3.5. Análise Temporal
- 3.6. Gráfico de Barras por Série Temporal Precipitação por Regiao
- 3.6.1 Número de queimadas por região Versus Precipitação (Impacto)
- 3.7. Gráfico de Barras Comparativo
- 3.8. Gráficos de Satélites #N dados coletados

## Demonstração
<p align="center">
  <img src="./_captures/Demonstracao.gif">
</p>

## 📋  Pré-requisitos
- Ter instalado o **[Python](https://www.python.org/)**;
- Ter instalado todas as bibliotecas Python listadas ao decorrer desse Readme;
- Ter instalado uma IDE de sua preferencia:
    - **[Visual Studio Code](https://code.visualstudio.com/)**, por exemplo.
    - **[Google Colab](https://colab.research.google.com/notebook)** (Não é necessário instalação).

## ⚙️ Executar o projeto:
- Fazer o clone do repositório do projeto [Projeto_Queimadas_M3](https://github.com/HyogoMoura/Projeto_Queimada_M3);
- Abrir o arquivo **main.ipynb** na IDE;
- Selecionar a opção "Run All" para iniciar todas as funções;
- Pronto! Veja toda a manipulação de dados presente no notebook e a criação de gráficos.

## 🧾 Bibliotecas Python utilizadas
Clique sobre o link para instalar cada biblioteca utilizada.

- [Pandas](https://pypi.org/project/pandas/):
`import pandas as pd`

- [Numpy](https://numpy.org/)
`import numpy as np`

- [OS](https://pypi.org/project/os-sys/):
`import os`

- Plotagem de gráficos com [Matplotlib](https://pypi.org/project/matplotlib/):
`import matplotlib.pyplot as plt`
`import matplotlib.ticker as mticker`

- Plotagem de gráficos com [Seaborn](https://pypi.org/project/seaborn/):
`import seaborn as sns`

- Plotagem em Mapas interativos com [Folium](https://pypi.org/project/folium/):
`import folium`

## 🛠️ Tecnologias Utilizadas
Python

* [Visual Studio Code](https://code.visualstudio.com/) - IDE 
* [Python](https://www.python.org/) - Linguagem de Programação

## 📈 Melhorias futuras

- Aumentar a base de dados com todos os meses de 2024;
- Fazer uma análise com mais países além do Brasil;
- Análise da perda de área com as queimadas.

