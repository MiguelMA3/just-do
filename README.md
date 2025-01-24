Hello there

just-do/
├── cmd/              # Executáveis do projeto
│   └── server/       # Arquivo main.go para rodar o servidor
├── pkg/              # Pacotes reutilizáveis
│   ├── models/       # Definições de modelos (projeto, tarefas, usuários)
│   ├── db/           # Lógica de banco de dados (CRUD)
│   ├── handlers/     # Handlers para endpoints da API
│   └── utils/        # Utilitários gerais
├── config/           # Arquivo(s) de configuração (config.yaml, .env, etc.)
├── migrations/       # Scripts de migração do banco (se for centralizado)
└── go.mod            # Dependências do projeto
