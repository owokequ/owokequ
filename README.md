<div align="center">

# Hi, I'm Artem 👋

### Junior Java Backend Developer

I build secure and maintainable backend applications with **Java**, **Spring Boot**, and **PostgreSQL**.  
My current focus is backend architecture, authentication, databases, asynchronous communication, and automated testing.

[![Telegram](https://img.shields.io/badge/Telegram-@owoke-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/owoke)
[![Email](https://img.shields.io/badge/Email-owokequ%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:owokequ@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=owokequ&style=for-the-badge&color=0e75b6)

</div>

---

## 👨‍💻 About me

- Developing backend applications with **Java 21** and **Spring Boot**
- Building **CareerFlow** — a backend service for authentication, user profiles, résumés, and job-search workflow
- Learning how production systems handle security, transactions, caching, messaging, testing, and deployment
- Improving my knowledge of **Spring Security**, **JPA/Hibernate**, **PostgreSQL**, **Redis**, and **Kafka**
- I prefer understanding not only *how* code works, but also *why* a system is designed this way

---

## 🛠 Tech stack

### Backend

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![MapStruct](https://img.shields.io/badge/MapStruct-FF6F00?style=flat-square)

### Data and messaging

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Liquibase](https://img.shields.io/badge/Liquibase-2962FF?style=flat-square&logo=liquibase&logoColor=white)

### Testing and infrastructure

![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=flat-square)
![Testcontainers](https://img.shields.io/badge/Testcontainers-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Featured project

### [CareerFlow](https://github.com/owokequ/CareerFlow)

Backend service that is being developed as the foundation of a job-application tracking platform.

**Implemented:**

- Registration and login with Spring Security
- JWT access tokens and refresh-token rotation
- Refresh tokens stored as hashes in Redis
- Email verification and password recovery
- Protection against user enumeration during password reset
- Redis-based rate limiting
- PostgreSQL persistence with Liquibase migrations
- Kafka events published after successful transaction commit
- User profile and résumé modules
- Unit and integration tests with JUnit, Mockito, and Testcontainers
- Docker Compose environment
- GitHub Actions CI and Docker image publishing

**Architecture and stack:**

```text
Client
  ↓
Spring Security + JWT
  ↓
Controller → Service → Repository
  ↓             ↓
PostgreSQL    Redis
  ↓
Kafka events → asynchronous consumers
```

`Java 21` · `Spring Boot` · `Spring Security` · `PostgreSQL` · `Redis` · `Kafka`  
`Liquibase` · `MapStruct` · `Testcontainers` · `Docker` · `GitHub Actions`

---

## 📚 Current learning focus

- Integration and architecture testing
- Transaction boundaries and event-driven communication
- Database indexing and query performance
- Observability: logs, metrics, health checks, and tracing
- Clean architecture and modular monolith design
- Algorithms and data structures for backend interviews

---

## 📫 Contact

- Telegram: [@owoke](https://t.me/owoke)
- Email: [owokequ@gmail.com](mailto:owokequ@gmail.com)

<div align="center">

### Thanks for visiting my profile!

</div>
