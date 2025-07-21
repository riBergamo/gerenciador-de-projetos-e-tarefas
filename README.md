**Gerenciador de Projetos e Tarefas**

Sistema completo para organização de projetos e tarefas, desenvolvido com Spring Boot e React.

**📌 Descrição**

Este sistema permite o cadastro e gerenciamento de projetos, com suas respectivas tarefas. Ele foi construído com foco em aprendizado prático e aplicação de boas práticas de desenvolvimento.

**Diagrama:**

<img width="600" height="448" alt="gerenciador" src="https://github.com/user-attachments/assets/25dac5ef-c3c9-4d48-a49c-eddc2791e0d3" /><br>

**🚀 Tecnologias Utilizadas:**

- Java 17 + Spring Boot
- PostgreSQL
- React
- JWT (autenticação)
- Maven

**➕ Funcionalidades Principais:**

- Cadastro e login de usuários
- Criação e edição de projetos
- Atribuição de tarefas a recursos
- Gerenciamento de status das tarefas

**⛏️ Como rodar o projeto:**
```bash
#Backend
cd backend
./mvnw spring-boot:run
```
```bash
#Frontend
cd frontend
npm install
npm run dev
```
```yaml
#Configurações
- PostgreSQL rodando na porta 5432
- Banco `integrado-db`
- JWT configurado no `application.properties`
```




