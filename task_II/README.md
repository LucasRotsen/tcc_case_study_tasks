# Classificação de _issues_ de repositórios do _GitHub_

## Desenvolvimento do modelo

### Introdução
<hr>

Reconhecida como a etapa mais "excitante" do dia-a-dia de um Cientista de Dados, a fase de Desenvolvimento do Modelo é comumente a mais curta do projeto. Nesta etapa, todo o conhecimento adquirido durante a Análise Exploratória dos Dados é utilizado para construção de modelos preditivos, bem como o seu treinamento e avaliação.

### Objetivo
<hr>

Nesta etapa, construiremos um **Modelo de Classificação Binária de Issues**. Para isso, utilizaremos a biblioteca _[Simple Transformers](https://simpletransformers.ai/)_, que provê uma interface simplificada para o treinamento de modelos de aprendizado profundo para Processamento de Linguagem Natural (NLP).

Para a realização desta tarefa, as seguintes etapas se fazem necessárias: 

1. Construção do modelo
2. Treinamento do modelo
3. Avaliação do modelo

Na fase de Avaliação do modelo, você deverá testar o modelo desenvolvido com 10 _issues_ selecionadas no GitHub. 

**Dica 1:** o pré-processamento dos dados antes do treinamento do modelo é uma decisão a ser feita pela dupla.

**Dica 2:** finalizado o treinamento, guarde a pasta "outputs" gerada pelo Simple Transformers. Ela será necessária para a tarefa da próxima semana.

**Dica 3: Como montar o Google Drive dentro do Google Colab**

```python
"""
* Execute o código abaixo na primeira célular do Notebook, antes de iniciar a codificação
* Este código irá montar o seu Google Drive dentro da pasta '/content/drive'
"""
from google.colab import drive
drive.mount('/content/drive')
```

**Dica 4: Como salvar o modelo treinado no Google Drive**

```python
"""
* O código abaixo deve ser executado com o Google Drive montado (ver Dica 3)
* Código a ser executado na célula de treinamento do modelo
"""
# Célula de treinamento do modelo
model.train_model(train, output_dir='/content/drive/MyDrive/outputs/')
```

### Entregáveis
<hr>

Deverá ser entregue o arquivo contendo o caderno do Jupyter Notebook (.ipynb) desenvolvido. O resultado da execução de cada uma das células deverá estar disponível para visualização.

### Critérios de Avaliação
<hr>

1. Organização geral do notebook
2. Conformidade da solução desenvolvida com o problema proposto

### Como foi a experiência?
<hr>

Responda esse [questionário de percepção](https://forms.gle/oiJMNLUAQzkwPp8T7) sobre o desenvolvimento desta tarefa até a próxima aula, dia 13/10/2021.

### Gabarito da tarefa
<hr>

[Desenvolvimento do Modelo](Gabarito_TaskII.ipynb)
