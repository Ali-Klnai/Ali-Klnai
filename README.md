<h1 align="center">Ali Kalantari</h1>
<h3 align="center">Backend Developer · Fintech · .NET &amp; Python</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/aliikalantari"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alii.kalantary@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Istanbul-Turkey-555?style=flat" alt="Location">
  <img src="https://komarev.com/ghpvc/?username=Ali-Klnai&style=flat&color=1F4E79" alt="Profile views">
</p>

---

### 👋 About Me

I'm a **Backend Developer** with **1.5+ years** of hands-on production experience in a regulated Turkish fintech, where I've **solo-architected two production microservices** (one of them integrating with the **Central Bank of Turkey** for regulatory reporting). My stack is **.NET (8 / 9 / 10)** and **Python (FastAPI)**, with deep work across **PostgreSQL · MySQL · SQL Server · Redis · RabbitMQ**.

Currently pursuing an **M.Sc. in Computer Engineering** at **Yıldız Technical University** on a full-tuition scholarship.

---

### 🛠 Tech Stack

```
Languages    C# (.NET 8/9/10) · Python (3.11+, async) · TypeScript · JavaScript · SQL
Backend      ASP.NET Core · FastAPI · NestJS · Worker / Background Services · SignalR
Architecture Clean Architecture · Microservices · Event-Driven · CQRS · Saga · Outbox/Inbox
Databases    PostgreSQL · MySQL · SQL Server · SQLite · Redis (cache + queues + locks)
Messaging    RabbitMQ · MassTransit · BullMQ · gRPC
ORM          EF Core 8/9 · SQLAlchemy 2.0 (async) · Prisma · Dapper
Auth/Sec     JWT + refresh tokens · OAuth2 · BCrypt · AES · RBAC · distributed locks
Tools        Docker · GitLab CI/CD · Serilog · Polly · FluentValidation
```

---

### 🚀 Featured Work

#### Production Engineering (Confidential Fintech, 2024 – Present)

> Day-job projects — code is proprietary, but here's what I built solo:

- 🏛️ **TCMB RIBS Regulatory Microservice** — .NET 10 / EF Core 9 / PostgreSQL; integrates with the **Central Bank of Turkey's Risky-Transactions Reporting System**. Solo-architected, shipped against a hard regulatory deadline. Dual cron pipelines · 6-state machine · maker-checker (4-eyes) · 17-scenario mock test harness.
- 🧪 **Fraud-Operations Backend** — Python / FastAPI; coordinates async transactions across **3 databases** (2× PostgreSQL + MySQL). JWT+OTP · 5-role RBAC · 7 self-healing background services · tiered SLA escalation (60 min → 10 d CRITICAL).
- 📊 **Enterprise Reporting Platform** — .NET 8; **5-database** orchestration (MySQL + 3× PostgreSQL + SQL Server). 20+ regulator-grade reports (AML, MASAK SIB XML). Quartz cron · Polly circuit-breaker · SHA256-keyed Redis caching. 14 controllers · ~84 endpoints · 120+ entities.
- 📡 **Multi-Channel Notification Platform** — .NET 9 / RabbitMQ; spans **7 microservice projects** with provider Strategy + Fallback (SMS / Email / Push) and two-stage Persist → Dispatch consumer pipeline with DLQs.
- 🎯 **Real-time Call-Center Platform** — .NET 8 + SignalR (3 hubs); integrates **8 third-party services** (VoIP, KYC, Jira, KPS national-identity registry) behind a Polly HTTP pipeline.

#### Personal Side-Projects (private — full details available on request / for in-person interviews)

- 💳 **QR-Pay** — Multi-tenant restaurant QR-payment SaaS. TypeScript monorepo (Turborepo) with NestJS API + Next.js admin & customer apps. iyzico payment integration via Strategy Pattern, Socket.IO real-time, BullMQ async jobs, JWT + refresh-token across 4 roles.
- 🛡️ **AI Document Verification Panel** — Python / FastAPI + **Ollama (gemma4:31b vision model)** for image-based document field matching. Dual-AI provider strategy (Ollama + Gemini fallback), public-form subsystem with tracking numbers, FastAPI BackgroundTasks for async inference, production-ready (systemd + Nginx + Let's Encrypt).

#### Public Reference Series — Distributed Systems Patterns

Standalone study projects, each focused on one pattern — kept as working references:

| Pattern | Repo |
|---|---|
| Saga Orchestration | [Microservices.Saga.Orchestration](https://github.com/Ali-Klnai/Microservices.Saga.Orchestration) |
| Saga Choreography | [Microservices.Saga.Choreography](https://github.com/Ali-Klnai/Microservices.Saga.Choreography) |
| Outbox / Inbox Pattern | [Microservices.Outbox.Inbox.Design.Pattern](https://github.com/Ali-Klnai/Microservices.Outbox.Inbox.Design.Pattern) |
| Event Sourcing | [Microservices.Event.Store](https://github.com/Ali-Klnai/Microservices.Event.Store) |
| CQRS | [Microservices.CQRS](https://github.com/Ali-Klnai/Microservices.CQRS) |
| Two-Phase Commit | [Microservices.2PC](https://github.com/Ali-Klnai/Microservices.2PC) |
| API Gateway (YARP) | [Microservices.API.Gateway.YARP](https://github.com/Ali-Klnai/Microservices.API.Gateway.YARP) |
| Distributed Tracing | [Microservices.Traceability](https://github.com/Ali-Klnai/Microservices.Traceability) |
| E-Commerce Backend (Clean Architecture + SignalR) | [ETicaretAPI](https://github.com/Ali-Klnai/ETicaretAPI) · [ETicaretClient](https://github.com/Ali-Klnai/ETicaretClient) |
| Tourism Platform (N-tier + SignalR live dashboard) | [TraversalProject](https://github.com/Ali-Klnai/TraversalProject) |

---

### 📈 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Ali-Klnai&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true&title_color=1F4E79&icon_color=1F4E79" alt="GitHub stats">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ali-Klnai&layout=compact&theme=default&hide_border=true&title_color=1F4E79&langs_count=8" alt="Top languages">
</p>

---

### 🌐 Languages

**Persian** (Native) · **Turkish** (C2) · **Azerbaijani** (C1) · **English** (B1)

---

### 📫 Get in Touch

- **Email:** alii.kalantary@gmail.com
- **LinkedIn:** [linkedin.com/in/aliikalantari](https://www.linkedin.com/in/aliikalantari)
- **Location:** İstanbul, Türkiye · *Work permit eligible · No military obligation*

<p align="center"><i>Open to backend / software engineering opportunities in Türkiye.</i></p>
