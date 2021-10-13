# Classificação de _issues_ de repositórios do _GitHub_

### Introdução
<hr>

Repositórios do GitHub possuem um espaço dedicado às _Issues_. _Issues_ são tópicos submetidos por usuários e pessoas que contribuem com um repositório, e servem para reportar problemas encontrados, fazer perguntas, reportar vulnerabilidades e etc.

Um exemplo que podemos analisar é a página de issues do [Repositório do React](https://github.com/facebook/react/issues). Note que algumas _issues_ estão rotuladas com um _label_ (exemplo: 'Type: Bug'), porém, muitas vezes, esse _label_ precisa ser colocado manualmente pelo usuário que está submetendo a _issue_. Uma vez que as _issues_ não são rotuladas da forma correta, muitos dos _bugs_ reportados pelos usuários e contribuidores não são identificados pelos mantenedores do repositório.

O objetivo deste projeto é criar um mecanismo que identifique se uma _issue_ reporta um bug ou não, para que futuramente, possam ser classificadas automaticamente. Deste modo, os desenvolvedores responsáveis pelo repositório serão capazes de filtrar de forma mais eficaz os bugs reportados.

### Dataset
<hr>

Para realização do projeto, utilizaremos uma amostra pré-processada do dataset [GitHub Bugs Prediction](https://www.kaggle.com/anmolkumar/github-bugs-prediction/version/1),
disponibilizado na plataforma da comunidade [Kaggle](https://www.kaggle.com/).

O dataset é composto por três colunas:

* **Title** - O título da Issue do GitHub
* **Body**  - O corpo da Issue do GitHub  
* **Label** - Representa o rótulo daquela issue (Bug; Feature; Question)

No [arquivo](data/task_sample.csv) disponibilizado no repositório, encontra-se o arquivo:

* **task_sample.csv** - contendo 15000 linhas e 3 colunas

Este arquivo contém a amostra do dataset que deverá ser utilizada para a realização desta tarefa.

### Etapas
<hr>

* [Análise Exploratória dos Dados](task_I/README.md)
* [Desenvolvimento do Modelo](task_II/README.md)
* [Integração do Modelo](task_III/README.md)
* [[Bônus] Operacionalização do Modelo]()
