# DevOps

## Descrição
Projeto CRUD em Java (Spring Boot) com Swagger. Integração com Azure DevOps para CI/CD.

## Endpoints
- `GET /users` – Lista usuários
- `POST /users` – Cria um novo usuário

## Tecnologias
- Java 17
- Spring Boot 3
- H2 Database
- Swagger (OpenAPI)
- Azure Pipelines

## Gitflow
- `main`: Produção
- `develop`: Desenvolvimento
- `release`: Pré-produção
- `usuario/tarefa`: Branches de feature

## Pipeline
- Build: Compilação com Maven
- Test: Execução de testes (em breve)
- Deploy: Azure Web App
