# Lista de Tarefas com Nuxt 3

Este é um projeto de exemplo de uma aplicação de Lista de Tarefas utilizando Nuxt 3 e um banco de dados integrado com [NuxtHub](https://hub.nuxt.com/).

## Funcionalidades

- Adicionar uma nova tarefa
- Listar todas as tarefas
- Deletar uma tarefa

## Estrutura do Projeto

```plaintext
project-root/
├── api/
│   └── todos/
│       ├── [id].js
│       └── index.get.js
        └── index.post.js
├── pages/
│   └── index.vue
├── package.json
└── nuxt.config.js
