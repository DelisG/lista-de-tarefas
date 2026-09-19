# Lista de Tarefas

Aplicação full stack para organizar tarefas do dia: API REST em Node.js e Express com MongoDB e front-end em HTML, CSS e JavaScript, seguindo o padrão MVC.

> **EN:** Full stack to-do app: a Node.js/Express REST API with MongoDB and a vanilla HTML/CSS/JavaScript front end, following the MVC pattern.

<!-- Print da aplicação: salve a imagem em docs/print.png e remova este comentário -->
<!-- ![Tela da lista de tarefas](docs/print.png) -->

[Demonstração no GitHub Pages](https://delisg.github.io/lista-de-tarefas/) (versão estática, lê as tarefas de `src/models/list.json`) · [Documentação técnica](documentacao.md)

## Funcionalidades

- Adicionar tarefa com descrição, data e hora
- Listar e excluir tarefas pela interface
- API REST com CRUD completo de tarefas, testada no Postman

## API

| Rota | Método | Descrição |
| --- | --- | --- |
| `/lists` | GET | Lista todas as tarefas |
| `/lists/:id` | GET | Busca uma tarefa pelo id |
| `/lists` | POST | Cria uma tarefa |
| `/lists/:id` | PUT | Atualiza uma tarefa |
| `/lists/:id` | DELETE | Remove uma tarefa |
| `/lists` | DELETE | Remove todas as tarefas |

## Tecnologias

Node.js · Express · MongoDB · Mongoose · HTML · CSS · JavaScript

## Autora

**Delis Guerra**, Engenheira de Software Full Stack · Recife-PE
[LinkedIn](https://www.linkedin.com/in/delisguerra) · [GitHub](https://github.com/Delisg)
