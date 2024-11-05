# CRUD Web com PostgreSQL em C#

Este projeto é uma aplicação CRUD (Create, Read, Update, Delete) desenvolvida em C# para gerenciamento de dados em uma interface web, utilizando PostgreSQL como banco de dados. A aplicação permite operações básicas de criação, leitura, atualização e exclusão de registros, servindo como base para sistemas mais complexos.

## Configuração

No arquivo `appsettings.json`, configure a string de conexão com o banco de dados PostgreSQL:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Host=localhost;Port=5432;Database=CRUD_POSTGRE_AULA;Username=postgres;Password=123"
  }
}
```

## Estrutura do Projeto

```plaintext
├── Controllers          # Controladores para rotas CRUD
├── Models               # Modelos e conexão com banco de dados
├── Views                # Arquivos de visualização (HTML ou Razor)
├── appsettings.json     # Configurações do projeto
├── Program.cs           # Arquivo de entrada da aplicação
├── Startup.cs           # Configuração de serviços e middlewares
└── README.md            # Documentação do projeto
```

## Tecnologias Utilizadas

- **C# e ASP.NET Core**: Framework de desenvolvimento em C# para criação de aplicações web.
- **PostgreSQL**: Banco de dados relacional para armazenamento de dados.
- **Entity Framework Core**: ORM para manipulação de banco de dados.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
