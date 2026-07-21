# Hi, I'm Harshit Srivastava 👋

Backend Developer from **Delhi, India**, building secure, production-ready **REST APIs** with **Java** and **Spring Boot**.

I focus on layered architecture, JWT/OAuth security, relational data modeling, automated testing, Docker, and shipping services to the cloud (Neon / Railway / Vercel).

---

## 🚀 Live Projects

- 📝 **[Notes API](https://notes-api-ivory.vercel.app)** · [Swagger](https://notesapi-production-5cfd.up.railway.app/swagger-ui.html)
- 🔗 **[ShortLink](https://url-shortner-1nyvhhqea-harsshit.vercel.app/)** · [API health](https://urlshortner-production-b193.up.railway.app/actuator/health)
- 🎬 **[Movie Platform](https://github.com/HarsshitSri/movie_backend)** — in progress (catalog → booking)

---

## 🛠️ Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate_/_JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI_/_Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)
![H2](https://img.shields.io/badge/H2-0000BB?style=for-the-badge&logoColor=white)

### DevOps & Cloud
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E699?style=for-the-badge&logo=neon&logoColor=black)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Actuator](https://img.shields.io/badge/Spring_Actuator-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### Testing & Documentation
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-9B59B6?style=for-the-badge&logo=mockito&logoColor=white)
![OpenAPI](https://img.shields.io/badge/OpenAPI_/_Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### 📝 [Notes API](https://github.com/HarsshitSri/notes_api)

Production-ready REST API for secure note management with JWT auth, ownership-scoped CRUD, tests, and a live Neon → Railway → Vercel deploy.

**Highlights**
- JWT-based stateless authentication and user-scoped CRUD
- Keyword search, pagination, and sorting
- OpenAPI / Swagger docs · **26** unit & integration tests
- Multi-stage Docker build; PostgreSQL on **Neon**, API on **Railway**, UI on **Vercel**

`Java 21` `Spring Boot` `Spring Security` `JWT` `PostgreSQL` `OpenAPI` `Docker` `JUnit` `Neon` `Railway` `Vercel`

🌐 **Live:** [Web app](https://notes-api-ivory.vercel.app) · [Swagger](https://notesapi-production-5cfd.up.railway.app/swagger-ui.html)

---

### 🔗 [ShortLink — URL Shortener](https://github.com/HarsshitSri/Url_Shortner)

Full-stack URL shortener with JWT auth, optional OAuth, ownership controls, Gemini safety checks, and cloud deployment.

**Highlights**
- Email/password JWT auth; Google & GitHub **OAuth2** → same JWT session
- Owner-scoped create / list / patch / delete; redirects & metadata
- Soft **Gemini** URL safety analysis (Spring AI)
- **PostgreSQL** + **Flyway**; Docker Compose; Neon / Railway / Vercel

`Java 21` `Spring Boot` `Spring Security` `OAuth2` `JWT` `Flyway` `PostgreSQL` `Docker` `Neon` `Railway` `Vercel`

🌐 **Live:** [UI](https://url-shortner-1nyvhhqea-harsshit.vercel.app/) · [API health](https://urlshortner-production-b193.up.railway.app/actuator/health)

---

### 🎬 [Movie Platform Backend](https://github.com/HarsshitSri/movie_backend)

REST API + product-style UI for auth, catalog, ratings, reviews, and watchlists — designed to grow into full ticket booking.

**Current**
- JWT auth with RBAC (`USER` / `ADMIN`); BCrypt hashing
- Movie catalog with pagination/sorting; public reads, admin-only writes
- Ratings (1–10) with denormalized averages, written reviews, personal watchlist
- Seeded demo catalog (**30** titles) + HTML/CSS/JS UI; PostgreSQL + Docker Compose

**Planned**
- Theatres, showtimes, seat booking, payments

`Java 21` `Spring Boot 3.5` `Spring Security` `PostgreSQL` `JWT` `RBAC` `Docker`

---

### 🎓 [Student Management System](https://github.com/HarsshitSri/Student_Management_System)

REST API for students, courses, and enrollments — many-to-many domain model with JWT roles and a browser UI.

**Highlights**
- Students ↔ courses via an **Enrollment** join entity; pagination and search
- JWT auth with `ADMIN` / `STUDENT` roles and role-aware UI
- DTOs, Bean Validation, global exception handling (404 / 400 / 409)
- Cannot delete students/courses that still have enrollments
- Docker Compose; unit + controller tests

`Java` `Spring Boot` `Spring Security` `Spring Data JPA` `PostgreSQL` `JWT` `Docker`

---

## Engineering Principles

- ✔ REST-first API design
- ✔ Clean layered architecture
- ✔ Stateless authentication
- ✔ Testable service layer
- ✔ Dockerized deployments
- ✔ Production-ready configuration
- ✔ CI-friendly project structure

---

## 📫 Connect

- GitHub: [HarsshitSri](https://github.com/HarsshitSri)

Actively seeking **Backend Developer**, **Java Developer**, and **Software Engineer** roles where I can build reliable, scalable backend systems.

---

## GitHub Stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=HarsshitSri&show_icons=true&theme=transparent&hide_border=true&cache_seconds=1800" alt="Harshit Srivastava GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HarsshitSri&layout=compact&theme=transparent&hide_border=true&cache_seconds=1800" alt="Top languages" />
</p>

![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=HarsshitSri&theme=github-compact&hide_border=true&area=true)
