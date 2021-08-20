# Classificação de _issues_ de repositórios do _GitHub_

### Introdução
<hr>

Repositórios do GitHub possuem um espaço dedicado às issues. Issues são tópicos submetidos por usuários finais ou pessoas que contribuem com um repositório e podem reportar problemas encontrados, fazer perguntas, reportar vulnerabilidades etc.
Um exemplo que podemos analisar é a página de issues do repositório do React (https://github.com/facebook/react/issues). Algumas issues possuem uma label 'Type: Bug', mas elas são adicionadas apenas nas issues de categoria "DevTools bug report". Se a issue for referente a um bug e submetida em outra categoria ela não recebe a label, então podem existir diversas issues de bugs no GitHub não categorizadas corretamente.
O objetivo deste projeto é criar um mecanismo que identifique se uma issue reporta um bug ou não, para que futuramente, as issues possam ser classificadas automaticamente.

### Dataset
<hr>

Para realização do projeto, utilizaremos o dataset [GitHub Bugs Prediction](https://www.kaggle.com/anmolkumar/github-bugs-prediction/version/1),
disponibilizado na plataforma da comunidade [Kaggle](https://www.kaggle.com/).

O dataset é composto por três colunas:

* **Title** - O título da Issue do GitHub
* **Body**  - O corpo da Issue do GitHub  
* **Label** - Representa o rótulo daquela issue (0 - Bug; 1 - Feature; 2 - Question)

No [arquivo _zip_](data/tcc_sample.zip) disponibilizado no repositório, encontra-se o arquivo:

* **tcc_sample.csv** - 150000 linhas x 3 colunas

Este arquivo contém a amostra do dataset que deverá ser utilizada para a realização desta tarefa.

### Etapas
<hr>

* [Análise Exploratória dos Dados](task_I/README.md)
* [Desenvolvimento do Modelo](task_II/README.md)
* [Integração do Modelo](task_III/README.md)
* [[Bônus] Operacionalização do Modelo](task_IV/README.md)
