# Hi, I'm Nikolay (Kolja) 👋

**Junior .NET Developer** · Russia · Aiming to relocate to Serbia

I'm a self-taught backend developer focused on building real systems — not just CRUD apps. My background spans .NET microservices architecture, BI analytics, and AI-assisted development workflows.

---

## 🛠 Tech Stack

**Backend**
![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat&logo=dotnet&logoColor=white)

**Architecture & Patterns**
Clean Architecture · CQRS · DDD · Vertical Slice Architecture · FastEndpoints
Outbox Pattern · Optimistic Concurrency · Idempotency · Domain Events · Soft Delete

**Infrastructure**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
YARP · MassTransit · MinIO · SignalR

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Analytics & ML**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
KNN classifier (review sentiment analysis) · BI reporting

---

## 📦 Projects

### [AuHub](https://github.com/jinxinzero7/AuHub) — Online Auction Platform
> Diploma project · April–May 2026

A production-ready auction system built with a microservices architecture.

- **4 microservices**: Identity, Auctions, Notifications, Payment
- **11 Docker containers**, YARP API Gateway with rate limiting & health checks
- **Real-time bidding** via SignalR with sniper protection (auto-extend on late bids)
- **13 auction statuses** covering the full lifecycle from Draft to TransactionComplete
- **Payment system**: wallet-based reserve/release/charge/transfer
- **Async messaging**: RabbitMQ + MassTransit with Outbox Pattern
- **Security**: JWT + refresh token rotation with replay attack detection
- **Testing**: 90 unit tests (xUnit + NSubstitute + FluentAssertions)

Frontend: [AuHub-Frontend](https://github.com/jinxinzero7/AuHub-Frontend) · Next.js 16 + TypeScript + TailwindCSS

---

### [Event Platform API](https://github.com/jinxinzero7/Events) — Event Management System
> Educational project

Clean Architecture monolith with role-based access and ticketing.
JWT auth · role system (Attendee / Organizer / Admin) · ticket purchasing · refund system

---

### [ToDo API](https://github.com/jinxinzero7/ToDoList) — Minimal REST API
> First independent project

ASP.NET Core + SQLite · CRUD via Entity Framework · foundational project

---

## 🧠 About My Workflow

I treat AI tools as a serious part of the development process — not a shortcut, but a force multiplier. I design architecture, make technical decisions, review generated code, write tests, and fix bugs. This is how I shipped a full microservices system with 4 services, real-time bidding, and a complete payment engine within tight deadlines.

That said: writing code by hand matters too, and my next portfolio project will be built primarily that way — with AI in the mentor role.

---

## 🏆 Other

- 🥈 2nd place — *Профессионалы 2025*, BI Analytics (regional)
- 🥉 3rd place — *Профессионалы 2026*, BI Analytics (regional)

---

## 🎯 What I'm Building Toward

After my diploma defense I'm planning a portfolio project: 3–4 microservices, Polly resilience patterns, Redis caching, CI/CD with GitHub Actions, full integration test coverage — documented in English, targeting the international job market.

Long-term goal: remote .NET developer role, relocation to Serbia.

---

*Open to junior .NET roles — remote preferred.*
