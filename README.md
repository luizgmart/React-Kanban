 🗂️ Kanban App

Um aplicativo de **Kanban** construído com **React**, **TypeScript** e **Vite**, com gerenciamento de tarefas via contexto global e integração com uma API REST fake usando **JSON Server**.

------

 🚀 Tecnologias

- ⚛️ React
- 🧠 Context API
- 🧩 TypeScript
- ⚡ Vite
- 🗄️ JSON Server (mock API)



Estrutura do Projeto
📦 kanban-app
├── public
├── src
│   ├── components       # Componentes reutilizáveis
│   ├── context          # Contexto global (TasksContext)
│   ├── entities         # Tipagens (ex: Task.ts)
│   ├── pages            # Telas principais
│   ├── services         # Serviços de API (ex: tasksService)
│   ├── App.tsx
│   └── main.tsx
├── db.json              # Base de dados do JSON Server
├── .env
└── vite.config.ts


✅ Funcionalidades

Criar novas tarefas

Editar tarefas existentes

Excluir tarefas

Persistência simulada com JSON Server

Interface limpa com separação de responsabilidades
