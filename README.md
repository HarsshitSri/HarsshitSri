# Hi, I'm Harshit Srivastava 👋

Backend developer focused on building **REST APIs with Java and Spring Boot**. I enjoy designing clean layered architectures, modeling relational data, and shipping services that are documented, tested, containerized, and deployed.

- 🔭 Recently shipped **[ShortLink](https://github.com/HarsshitSri/Url_Shortner)** — a full-stack URL shortener with JWT auth, ownership, Docker, and a live Neon → Railway → Vercel deploy
- 🌱 Also building a **[Movie Booking backend](https://github.com/HarsshitSri/movie_backend)** — growing it from auth + catalog toward full ticket booking and payments
- 💬 Ask me about: Spring Boot, Spring Security + JWT, REST API design, PostgreSQL, Docker, Flyway, Railway / Vercel / Neon

🌐 **Live:** [ShortLink UI](https://url-shortner-1nyvhhqea-harsshit.vercel.app/) · [API health](https://urlshortner-production-b193.up.railway.app/actuator/health)

---

## 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate_/_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E699?style=for-the-badge&logo=neon&logoColor=black)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Swagger](https://img.shields.io/badge/OpenAPI_/_Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### 🔗 [ShortLink — URL Shortener](https://github.com/HarsshitSri/Url_Shortner)

Resume-grade full-stack URL shortener: Spring Boot API + static UI, shipped end-to-end to the cloud.

- **Auth:** email/password register & login with **JWT**; owner-scoped create / list / patch / delete
- **Optional OAuth:** Google + GitHub (Spring OAuth2 → same JWT session)
- **Product:** short-link redirects, metadata, soft **Gemini** safety checks, tour UI, dark/light theme
- **Data:** **PostgreSQL** + **Flyway** migrations (`users`, ownership, OAuth provider fields)
- **Ops:** multi-stage **Docker** images + Compose; deploy templates for **Neon** (DB), **Railway** (API), **Vercel** (UI)
- **Live:** [UI](https://url-shortner-1nyvhhqea-harsshit.vercel.app/) · [API](https://urlshortner-production-b193.up.railway.app/) · [Health](https://urlshortner-production-b193.up.railway.app/actuator/health)

`Java 21` `Spring Boot 3.4` `Spring Security` `JWT` `OAuth2` `PostgreSQL` `Flyway` `Docker` `Neon` `Railway` `Vercel`

### 🎬 [Movie Booking Backend](https://github.com/HarsshitSri/movie_backend)

A REST API backend for a movie platform, built as a layered monolith designed to scale toward full ticket booking and payments.

- User registration & login with **BCrypt password hashing** and **JWT** token issuance
- Movie catalog CRUD with **pagination and sorting** via Spring Data
- User ratings (1–10) with denormalized average-rating caching on movies
- Request validation with DTOs, global exception handling, normalized **PostgreSQL** schema
- **Docker + Docker Compose** setup and extensive design docs (architecture, API, database, decisions)

`Java 21` `Spring Boot 3.5` `Spring Security` `PostgreSQL` `JWT` `Docker`

### 📝 [Notes API](https://github.com/HarsshitSri/notes_api)

A stateless REST service for per-user note management with fully enforced JWT authentication.

- Register/login flow with a **custom authentication provider** and stateless JWT filter chain
- Note CRUD strictly **scoped to the authenticated user** (ownership checks at the service layer)
- Keyword search, pagination, and sorting with JPQL + Spring Data
- **Swagger UI / OpenAPI 3** docs and **25 unit & integration tests** (JUnit 5, Mockito, MockMvc)
- MySQL by default, H2 profile for local dev, multi-stage Docker build with Compose

`Java 21` `Spring Boot` `Spring Security` `MySQL` `H2` `JWT` `OpenAPI` `Docker`

### 🎓 [Student Management System](https://github.com/HarsshitSri/Student_Management_System)

A RESTful CRUD backend for managing student records, demonstrating clean layered architecture.

- Full CRUD endpoints for student records following HTTP standards
- **Controller → Service → Repository** separation
- PostgreSQL persistence with Spring Data JPA and Hibernate

`Java` `Spring Boot` `Spring Data JPA` `PostgreSQL` `Maven`

---

## 🧩 What I Focus On

- **Layered architecture** — controllers, services, repositories, DTOs, and mappers with clear boundaries
- **Security** — Spring Security, JWT-based stateless auth, optional OAuth2, BCrypt hashing, per-user data isolation
- **Data modeling** — normalized relational schemas, Flyway migrations, JPA relationships, constraints, and pagination
- **API quality** — bean validation, centralized error handling, consistent response envelopes, OpenAPI docs
- **Ship it** — multi-stage Docker builds, Compose for local stacks, env-based config, cloud deploy (Neon / Railway / Vercel)

---
