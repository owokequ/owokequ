<div align="center">

# Привет, я Артём 👋

### Java Backend Developer

Проектирую backend-системы на **Java** и Spring ecosystem: от безопасного API и работы с данными до асинхронных интеграций, тестов и deployment.

[![Telegram](https://img.shields.io/badge/Telegram-@owoke-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/owoke)
[![Email](https://img.shields.io/badge/Email-owokequ%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:owokequ@gmail.com)
![Profile views](https://komarev.com/ghpvc/?username=owokequ&style=for-the-badge&color=0e75b6)

</div>

---

## 👨‍💻 Обо мне

- Разрабатываю backend на **Java 21**, **Spring Boot** и **PostgreSQL**
- Думаю о production concerns: security, data integrity, observability и failure scenarios
- Практикую event-driven подход: Kafka, transactional outbox/inbox, idempotency и retry handling
- Умею работать не только с кодом: migrations, Docker Compose, CI, health checks и metrics
- Английский использую в документации, API, code review и технической коммуникации

## 🛠 Актуальный стек

**Backend:** Java 21 · Spring Boot 4 · Spring MVC · Spring Security · Spring Cloud Gateway · JPA/Hibernate · Maven

**Data & messaging:** PostgreSQL · Redis · Apache Kafka · Liquibase · JSON Schema contracts

**Testing:** JUnit 5 · Mockito · Testcontainers · ArchUnit · Integration tests

**Infrastructure:** Docker · Docker Compose · GitHub Actions · Caddy · Prometheus · Grafana

**Frontend:** TypeScript · React 19 · TanStack Router / Query · React Hook Form · Zod · Vite

---

## 🚧 Основной проект — [dating](https://github.com/owokequ/dating)

**dating** — production-oriented dating planner, находящийся в активной разработке (*in progress*). Пользователи создают пару, выбирают места и события, предлагают свидание и получают уведомления через web-приложение или Telegram.

### Что уже реализовано

- 7 Spring Boot services с принципом **database per service**
- API Gateway и централизованная edge security
- RS256 JWT + JWKS, HttpOnly cookies, CSRF protection, CORS и Redis rate limiting
- Versioned Kafka events, transactional outbox / consumer inbox, retry и DLQ-потоки
- Idempotency keys для операций со свиданиями
- PostgreSQL + Liquibase migrations; отдельная база у каждого сервиса
- Media processing и S3-compatible storage
- KudaGo places/events integration и moderation workflow
- Telegram OIDC login, in-app / email / Telegram notifications
- CI: backend verification, frontend lint/tests/build, contract validation и Docker image builds
- Production-like deployment: Caddy TLS, Actuator, Prometheus/Grafana и external availability monitoring

> Цель проекта — не просто собрать CRUD, а проработать реальные границы распределённой системы: повторную доставку событий, консистентность, безопасность браузерной сессии и observability.

---

## 🎯 Сейчас углубляюсь в

- Distributed systems и delivery semantics
- Spring Security / OAuth2 / JWT
- Transaction boundaries, locking и data consistency
- PostgreSQL indexing и query performance
- Observability: metrics, tracing и alerting
- System design и backend interview preparation

## 📫 Контакты

- Telegram: [@owoke](https://t.me/owoke)
- Email: [owokequ@gmail.com](mailto:owokequ@gmail.com)

<div align="center">

*Open to backend opportunities and thoughtful technical conversations.*

</div>
