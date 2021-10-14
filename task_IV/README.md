# Classificação de _issues_ de repositórios do _GitHub_

## [BÔNUS] Operacionalização do Modelo
<hr>

Segundo pesquisa conduzida em 2019 pela [VentureBeat](https://venturebeat.com/2019/07/19/why-do-87-of-data-science-projects-never-make-it-into-production/), 87% dos modelos de Machine Learning desenvolvidos não passam da fase de experimentação, ou seja, nunca entregam valor real ao cliente. 

Embora seja possível fazer predições em tempo real com o nosso modelo através do _Jupyter Notebook_, ele ainda não é particularmente útil até que outros usuários e aplicações possam consumir os seus resultados. 

Existem diversas estratégias para "servir" modelos de Machine Learning, dentre elas:
* Embutir o modelo em uma aplicação
* Servir o modelo através de uma API
* Utilizar o modelo salvo de forma padronizada como uma biblioteca

A escolha e a implementação dessa estratégia é parte do que chamamos de [MLOps](https://towardsdatascience.com/what-is-mlops-everything-you-must-know-to-get-started-523f2d0b8bd8), que consiste em um conjunto de práticas que têm como objetivo implantar e manter modelos de Machine Learning em produção de maneira confiável e eficiente.

### Objetivo
<hr>

O objetivo desta tarefa é operacionalizar o modelo desenvolvido na etapa de Desenvolvimento do Modelo através de uma API REST. 
A API desenvolvida deverá conter um único endpoint, que receberá dois parâmetros:

* **nameWithOwner** - O nome do usuário / organização seguido do nome do repositório (Ex: freeCodeCamp/freeCodeCamp)
* **issueNumber**  - O número da _issue_ dentro do repositório do GitHub

A partir desses parâmetros, a sua aplicação deverá fazer uma consulta à [API do GitHub](https://docs.github.com/pt/graphql) para retornar o Título (title) e o Corpo (body)
da _issue_ pesquisada. Com esses dados em mãos, a sua API deverá utilizar o modelo desenvolvido para retornar para o usuário a classificação da _issue_ em questão (BUG ou NÃO BUG).

Finalizada a implementação da API, você deverá torná-la acessível para outros usuários e aplicações através do deploy em uma plataforma de nuvem ou outra abordagem de sua escolha.

### Entregáveis
<hr>

Deverá ser entregue um arquivo ZIP contendo o código desenvolvido, bem como o link para acesso à aplicação publicada.

### Critérios de Avaliação
<hr>

1. Conformidade da solução desenvolvida com o que foi especificado no objetivo
2. Execução correta da API no link indicado
