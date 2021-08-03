# Classificação de _issues_ de repositórios do _GitHub_

## Análise Exploratória dos Dados (EDA)

### Introdução
<hr>

>* Descrição geral do que deve ser feito, quais dados devem ser minerados, de onde, etcs
>* O que os alunos devem alcançar? Pode ser em formato de perguntas, por exemplo

### Dataset
<hr>

Para realização do projeto, utilizaremos o dataset [GitHub Bugs Prediction](https://www.kaggle.com/anmolkumar/github-bugs-prediction/version/1),
disponibilizado na plataforma da comunidade [Kaggle](https://www.kaggle.com/).

O dataset é composto por três colunas:

* **Title** - O título da Issue do GitHub
* **Body**  - O corpo da Issue do GitHub  
* **Label** - Representa o rótulo daquela issue (0 - Bug; 1 - Feature; 2 - Question)

No arquivo _zip_ disponibilizado no repositório, encontra-se o arquivo:

* **Issues.json** - 150000 linhas x 3 colunas

Este arquivo contém a amostra do dataset que deverá ser utilizada para a realização desta tarefa.

### Objetivo
<hr>

O objetivo desta etapa é obter um melhor entendimento dos dados, extraindo informações relevantes através da
utilização de técnicas e ferramentas de análise descritiva. Esta fase inclui, por exemplo, a construção de visualizações
e o cálculo de medidas de tendência central. Essas informações serão posteriormente utilizadas na fase de Desenvolvimento do Modelo. 

A partir da sua análise, você deverá responder:

RQ 01: Como os diferentes rótulos das _issues_ estão distribuídos no dataset de treinamento? Mostre os valores em porcentagem.

RQ 02: Qual é a mediana do número de palavras das issues de cada um dos rótulos presentes no dataset de treinamento?

RQ 03: Dado o resultado da RQ 02, é possível observar diferenças claras entre o número de palavras das issues de cada rótulo?

RQ 04: Quais são as 20 palavras mais comuns nas issues de cada um dos rótulos presentes no dataset de treinamento?

RQ 05: Dado o resultado da RQ 03, é possível diferenciar o rótulo de uma issue pelas palavras presentes em seu texto?

## Entregáveis
<hr>

Deverá ser entregue o arquivo contendo o caderno do Jupyter Notebook (.ipynb) desenvolvido, ou um link para acessá-lo
através do GitHub.

## Critérios de Avaliação
<hr>

1. Respostas corretas às perguntas de pesquisa
2. Riqueza da análise realizada nas perguntas de pesquisa que são discursivas
