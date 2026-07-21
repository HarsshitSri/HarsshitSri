# Hi, I'm Harshit Srivastava 👋

Backend developer based in **Delhi**, building **REST APIs with Java and Spring Boot**. I care about clean layered architecture, JWT security, relational data modeling, and shipping services that are documented, tested, containerized, and deployed.

- 🔭 Live in production: **[Notes API](https://notes-api-ivory.vercel.app)** · **[ShortLink](https://url-shortner-1nyvhhqea-harsshit.vercel.app/)**
- 🌱 Building toward a full **[Movie Platform](https://github.com/HarsshitSri/movie_backend)** (auth, catalog, ratings, reviews, watchlist → booking next)
- 💬 Ask me about: Spring Boot, Spring Security + JWT, REST API design, PostgreSQL, Docker, Neon / Railway / Vercel

---

## 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate_/_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
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

### 📝 [Notes API](https://github.com/HarsshitSri/notes_api)

Stateless notes service with JWT auth, ownership-scoped CRUD, and a live Neon → Railway → Vercel deploy.

- Register / login with **JWT**; notes strictly scoped to the authenticated user
- Keyword search, pagination, and sorting; **Swagger / OpenAPI** docs
- Static web UI + production frontend on **Vercel**; **26** unit & integration tests
- Multi-stage **Docker** build; production DB on **Neon**, API on **Railway**

`Java 21` `Spring Boot` `Spring Security` `PostgreSQL` `JWT` `OpenAPI` `Docker` `Neon` `Railway` `Vercel`

🌐 **Live:** [Web app](https://notes-api-ivory.vercel.app) · [Swagger](https://notesapi-production-5cfd.up.railway.app/swagger-ui.html)

### 🔗 [ShortLink — URL Shortener](https://github.com/HarsshitSri/Url_Shortner)

Full-stack URL shortener shipped end-to-end: Spring Boot API + static UI, auth, ownership, and cloud deploy.

- Email/password **JWT** auth; owner-scoped create / list / patch / delete
- Optional **Google + GitHub OAuth** (Spring OAuth2 → same JWT session)
- Short-link redirects, metadata, soft **Gemini** safety checks, dark/light tour UI
- **PostgreSQL** + **Flyway**; multi-stage **Docker** + Compose; Neon / Railway / Vercel

`Java 21` `Spring Boot` `Spring Security` `JWT` `OAuth2` `PostgreSQL` `Flyway` `Docker` `Neon` `Railway` `Vercel`

🌐 **Live:** [UI](https://url-shortner-1nyvhhqea-harsshit.vercel.app/) · [API health](https://urlshortner-production-b193.up.railway.app/actuator/health)

### 🎬 [Movie Platform Backend](https://github.com/HarsshitSri/movie_backend)

REST API + product-style UI for auth, catalog, ratings, reviews, and watchlists — designed to grow into full ticket booking.

- **JWT** auth with **RBAC** (`USER` / `ADMIN`); BCrypt hashing; inactive accounts rejected
- Movie CRUD with pagination/sorting; public reads, admin-only writes
- Numeric ratings (1–10) with denormalized averages, written reviews, personal watchlist
- Seeded demo catalog (**30** titles) + HTML/CSS/JS UI; **PostgreSQL** + Docker Compose
- Design docs for architecture, API, DB, and deployment; theatres / booking / payments on the roadmap

`Java 21` `Spring Boot 3.5` `Spring Security` `PostgreSQL` `JWT` `RBAC` `Docker`

### 🎓 [Student Management System](https://github.com/HarsshitSri/Student_Management_System)

REST API for students, courses, and enrollments — many-to-many domain model with JWT roles and a browser UI.

- Students ↔ courses via an **Enrollment** join entity; pagination and search
- **JWT** auth with `ADMIN` / `STUDENT` roles and role-aware UI
- DTOs, Bean Validation, global exception handling (404 / 400 / 409)
- Guardrails: cannot delete students/courses that still have enrollments
- Vanilla HTML/CSS/JS frontend, Docker Compose, unit + controller tests

`Java` `Spring Boot` `Spring Security` `Spring Data JPA` `PostgreSQL` `JWT` `Docker`

---

## 🧩 What I Focus On

- **Layered architecture** — controllers, services, repositories, DTOs, and mappers with clear boundaries
- **Security** — Spring Security, JWT-based stateless auth, optional OAuth2, BCrypt, RBAC, per-user data isolation
- **Data modeling** — normalized schemas, JPA relationships (including join entities), constraints, pagination, Flyway where it fits
- **API quality** — bean validation, centralized error handling, consistent responses, OpenAPI docs, automated tests
- **Ship it** — multi-stage Docker builds, Compose for local stacks, env-based config, cloud deploy (Neon / Railway / Vercel)

---

## 📫 Connect

- GitHub: [HarsshitSri](https://github.com/HarsshitSri)
- Open to backend / Java roles — feel free to reach out
