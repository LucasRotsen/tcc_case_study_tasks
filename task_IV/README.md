# Classificação de _issues_ de repositórios do _GitHub_

## [BÔNUS] Operacionalização do Modelo

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
