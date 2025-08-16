📘 API do Fórum Hub  
O Challenge Fórum Hub API é um aplicativo backend desenvolvido em Java com Spring Boot, que simula a estrutura de um fórum real.  
Ele permite o gerenciamento completo de usuários, tópicos e respostas, com autenticação segura via JWT, controle de acesso com Spring Security, documentação via Swagger e versionamento do banco com Flyway.  

Este projeto foi desenvolvido como parte do programa **Oracle Next Education (ONE)** em parceria com a **Alura**, na **Turma G8**.  

---

🚀 Tecnologias e Dependências  
- ☕ Java 17  
- 🌱 Spring Boot 3  
- 🌐 Spring Web  
- ⚡ Spring Boot DevTools  
- 🔄 Spring Data JPA  
- 🔐 Spring Security  
- 📝 Lombok  
- 🗃 Flyway (versionamento do banco)  
- 📑 Validation API  
- 🗄 MySQL Driver  
- 🔑 JWT (JSON Web Token)  
- 📖 SpringDoc OpenAPI + Swagger  

---

🛠️ Funcionalidades  
- 🔐 Autenticação segura com **Spring Security + JWT**  
- 👤 **CRUD de usuários** (cadastro, atualização de senha, exclusão do próprio perfil com confirmação de senha)  
- 💬 **CRUD de tópicos** (restrito ao autor autenticado)  
  - Status automático: `NAO_RESPONDIDO` ou `RESPONDIDO`  
- 💡 **CRUD de respostas** (somente o autor pode atualizar ou excluir)  
- 📈 **Relatório**: contagem de tópicos e respostas por usuário  
- ✅ Testes de endpoints com **Insomnia**  
- 🧪 Documentação interativa com **Swagger UI**  
- 🗃 Versionamento de banco com **Flyway**  

---

🧑‍💻 Autora  
**Karolina Anjos**  
💼 Desenvolvedora Java | Back-End  
🎓 Aluna do programa Oracle Next Education (ONE) – Turma G8  

📫 Meu perfil no LinkedIn: [Karolina Anjos](COLE_SEU_LINK_AQUI)  
🐙 GitHub: [Karolinanjos](https://github.com/Karolinanjos)  

---

🧠 Aprendizados  
Este projeto me proporcionou uma experiência prática com:  
- Estruturação profissional em MVC  
- Segurança com JWT e controle de acesso no Spring Security  
- Manipulação de entidades relacionadas no JPA  
- Versionamento de banco com Flyway  
- Boas práticas REST  
- Criação de endpoints protegidos e públicos  
