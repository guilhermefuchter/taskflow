# TaskFlow - Etapa 1
\n## Estrutura do Projeto
O projeto TaskFlow é uma aplicação de gerenciamento de tarefas e projetos baseada em microserviços, utilizando Spring Boot e arquitetura hexagonal.
\n### Serviços
*   **service-discovery**: Servidor Eureka para registro e descoberta de serviços.
*   **auth-service**: Serviço de autenticação e autorização (Spring Security + JWT).
*   **gateway-service**: API Gateway (Spring Cloud Gateway) para roteamento e filtro de segurança.
*   **task-service**: Serviço de gerenciamento de tarefas (novo, usando Gradle).
*   **project-service**: Serviço de gerenciamento de projetos (novo, usando Gradle).
\n### Execução
Para iniciar a aplicação, utilize o Docker Compose na raiz do projeto:
```bash
docker-compose build
docker-compose up
```
