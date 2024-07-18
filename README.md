# To Do App

Aplicação desenvolvida utilizando a biblioteca Flet do Python, que é baseada no Flutter.

## Interface Principal
A interface principal do aplicativo possui 3 abas e um campo de preenchimento de texto:

1. **Campo de texto**: O usuário pode digitar sua tarefa e pressionar "Enter" ou clicar no botão de adicionar para salvar a tarefa.
2. **Aba "Todos"**: Exibe todas as tarefas que o usuário adicionou.
3. **Aba "Em andamento"**: Exibe apenas as tarefas que estão em andamento (não finalizadas).
4. **Aba "Finalizados"**: Exibe todas as tarefas que foram finalizadas.

## Funcionalidades

- **Adicionar Tarefa**: O usuário pode adicionar novas tarefas digitando no campo de texto e pressionando "Enter" ou clicando no ícone de adição.
- **Marcar como Concluída**: O usuário pode marcar uma tarefa como concluída clicando na caixa de seleção ao lado da tarefa. Tarefas concluídas são movidas para a aba "Finalizados".
- **Filtrar Tarefas**: O usuário pode alternar entre as abas para visualizar todas as tarefas, apenas as tarefas em andamento ou apenas as tarefas finalizadas.

## Estrutura do Código

A classe principal `ToDo` é responsável pela configuração da interface e pela manipulação das tarefas no banco de dados SQLite.

## Requerimentos
```python
pip install -r .\requirements.txt
```

## Ferramentas Utilizadas
<img src="imgs/flet.png" width=50><img src="imgs/python.png">

