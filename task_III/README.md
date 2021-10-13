# Classificação de _issues_ de repositórios do _GitHub_

## Integração do Modelo

### Introdução
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

O objetivo desta tarefa é encapsular o modelo desenvolvido em uma aplicação, para que os resultados deste possam ser consumidos por outros usuários.

O seu programa deverá receber como parâmetro o Título e o Corpo de uma _issue_ (ou os dois), e deverá retornar para o usuário uma mensagem informando se aquela _issue_
se trata de um BUG ou não.

**OBS 1:** a escolha da aplicação a ser desenvolvida cabe inteiramente à dupla.

**OBS 2:** a sua aplicação deverá ser desenvolvida fora do ambiente do Google Colab.

**[Dica: Como carregar um modelo pré-treinado](https://simpletransformers.ai/docs/usage/#loading-a-local-save)**

```python
"""
* Para executar o código abaixo, é necessário ter tantoo SimpleTransformers quanto o Torch instalados
* pip install simpletransformers torch
"""
from simpletransformers.classification import ClassificationModel

model = ClassificationModel(
    "roberta", "outputs/checkpoint-1313-epoch-1",
    use_cuda=False
)
```

### Entregáveis
<hr>

Deverá ser entregue no Canvas um arquivo ZIP contendo o código e um README contendo as informações de como executá-lo.

### Critérios de Avaliação
<hr>

1. Conformidade da solução desenvolvida com o que foi especificado no objetivo
2. Assertividade das instruções para execução do programa
3. Execução correta do programa

### Como foi a experiência?
<hr>

Responda esse [questionário de percepção](https://forms.gle/xeQ9MzEtw8rxQ1caA) sobre o desenvolvimento desta tarefa até a próxima aula
