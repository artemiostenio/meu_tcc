# Trabalho de conclusão de curso (TCC)- Previsão Geração de Energia Fotovoltaico

A previsão de geração de energia fotovoltaica é um campo promissor que combina as tecnologias de energia renovável com o poder do machine learning. Utilizando a linguagem Python, é possível desenvolver modelos preditivos que analisam dados históricos e variáveis ambientais para estimar a geração de energia. Algoritmos como redes neurais artificiais e máquinas de vetores de suporte podem ser treinados para identificar padrões e melhorar a precisão das previsões, otimizando assim a gestão e a eficiência dos sistemas fotovoltaicos. Inicialmente toda atividade será feita localmente no notebook Samsung Book 11th Gen Intel® Core™ i5-1135G7 @ 2.40GHz, Intel® Iris® Xe Graphics e memória 8GB.

![license](https://img.shields.io/badge/Licença-MIT-green) ![jupyter](https://img.shields.io/badge/-Jupyter-FF6F00?logo=jupyter&logoColor=white) ![python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![numpy](https://img.shields.io/badge/-Numpy-013243?logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white) ![seaborn](https://img.shields.io/badge/-Seaborn-black?logo=seaborn&logoColor=white) ![matplotlib](https://img.shields.io/badge/-Mtplotlib-black?logo=matplotlib&logoColor=white) ![plotly](https://img.shields.io/badge/-Plotly-3F4F75?logo=plotly&logoColor=white) ![sklearn](https://img.shields.io/badge/-Sklearn-F7931E?logo=scikitlearn&logoColor=white) ![boruta](https://img.shields.io/badge/-Boruta-FF6F00?logo=boruta&logoColor=white)

## Índice 

*[Preparando ambiente venv](#Preparando-ambiente-venv)
*[Coleta de dados](#Coleta-de-dados)
*[Preparação dos dados](#Preparação-dos-dados)
*[Analise exploratória dos dados](#Analise-exploratória-dos-dados)
*[Seleção de algoritmo](#Seleção-de-algoritmo)
*[Treinamento de modelo](#Treinamento-de-modelo)
*[Validação de modelo](#Validação-de-modelo)
*[Implementação de modelo](#Implementação-de-modelo)
*[Monitoramento e manutenção](#Monitoramento-e-manutenção)

### Preparando ambiente venv

Primeiro a ser criado foi o ambiente virtual venv, isolando de todo resto do sistema ao final da conclusão do projeto não havendo necessite se exclui liberando espaço.

` python -m venv /coloque/aqui/o/caminho/do/arquivo `

Apos criar o ambiente venv é preciso invocar, substituindo `<venv>` pelo caminho de invocação. Para ambientes Windows a necessidade de instalar o seu kernel virtual no `jupyter lab`, caso seu foco for laboratório jupyter, se não, ative o ambiente e use algum editor como VScode já roda no ambiente. Use o coamndo a baixo para instalar o novo kernel no windows:

`.\nome\do\venv\Scripts\python.exe -m ipykernel install --name nome_do_venv` 

Abaixo temos alguns exemplos de caminhos de invocações usuais para acessar o ambiente virtual:

|Plataforma|Shell|Comando para ativar o ambiente virtual|
|:----:|:----:|:----:|
|POSIX|bash/zsh|`$ source <venv>/bin/activate`|
|^^|fish|`$ source <venv>/bin/activate.fish`|
|^^|csh/tcsh|`$ source <venv>/bin/activate.csh`|
|^^|PowerShell|`$ <venv>/bin/Activate.ps1`|
|Windows|cmd.exe|`C:\> <venv>\Scripts\activate.bat`|
|^^|PowerShell|`PS C:\> <venv>\Scripts\Activate.ps1`|
Fonte: https://docs.python.org/3/library/venv.html

### Coleta de dados

Coleta de dados da usina/sistema fotovoltaico. Fontes utilizadas para a coleta de dados são dados dos próprios inversores e do site da NASA contendo dados meterológicos.

### Preparação dos dados

Preprocessar os dados para limpar, normalizar e transformar em dados brutos.

### Analise exploratória dos dados

Análise estatística e visualizações dos dados para entender as relações entre as variáveis e identificar padrões e Tendência.

### Seleção de algoritmo

Selecionar o algoritmo de previsão que contém regressão linear, redes neurais, árvores de decisão ou algoritmo de séries temporais.

### Treinamento de modelo

Usar n históricos para treinar o modelo de previsão.

### Validação de modelo

Usar dados de validação para avaliar o desempenho do modelo de previsão treinamento.

### Implementação de modelo

Implementar o modelo de previsão e treinamento em um ambiente de produção.

### Monitoramento e manutenção

Monitorar regularmente o desempenho do modelo de previsão em um ambiente de produção, fazer ajuste e atualizar conforme a necessidade.