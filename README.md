<div align="center">

# Phạm Hải Đăng · DANG-PH

**Backend Engineer** — NestJS · Microservices · Distributed Systems

Designed and operated an **11-service production MMORPG backend**, running 24/7 under real concurrent traffic.  
Focused on **concurrency control**, **distributed transactions**, and **system reliability**.

📍 Bắc Từ Liêm, Hà Nội &nbsp;·&nbsp; 📧 dangph.ptit@gmail.com &nbsp;·&nbsp; 🎓 PTIT — GPA 3.3/4.0

</div>

---

## 🛠 Tech Stack

**Languages**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Backend & Architecture**  
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat-square&logo=google&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**Databases**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**DevOps & Infra**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=DANG-PH&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=DANG-PH&layout=compact&theme=tokyonight&hide_border=true&langs_count=6)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=DANG-PH&theme=tokyonight&hide_border=true)

</div>

---

## 🚀 Featured Project — Sacred Dragon Warriors

> Production MMORPG backend · 14 months in production · 24/7 availability

| Metric | Value |
|--------|-------|
| Microservices | 11 services · 7 databases · 100+ APIs |
| Throughput | ~1,000 RPS stable · peaks ~1,200–1,500 RPS |
| Latency (p50 / p95 / p99) | ~60ms / ~230ms / <500ms |
| Error rate (soak test) | ~0.1% |
| Deployments shipped | 281 across 11 services · 90% CI/CD success rate |
| Transaction reliability | 0% partial-failure incidents |
| Client releases | 26 releases in first 1.5 months of production |

**Technical highlights:**

- **Saga + Outbox pattern** — distributed transactions with 0 partial-failure incidents across all transactional flows
- **Redis + Lua scripting** — atomic item purchases, race condition prevention under high concurrency
- **Dirty Flag + async batch writes** — cut DB write load ~90%, maintained stable throughput at 700–1,000 RPS
- **Fire-and-Forget** — offloaded non-critical Redis ops, reduced per-request latency ~10ms
- **PayOS + VietQR** — idempotent webhook handling, 100% transaction accuracy across ~100 test cases
- **PM2 + Telegram/Discord alerting** — detected 15 incidents, enabled proactive response across all services
- **Defense-in-depth** — Cloudflare + Nginx + JWT + RBAC + OAuth2 against DDoS, brute-force, unauthorized access

**Infrastructure:** 3-node Ubuntu VPS cluster (2 vCPU · 4 GB RAM each) · horizontal scaling · cross-region load testing (Hanoi ↔ HCM)

🔗 [Demo](https://ngocrongdark.com) · [Backend repo](https://github.com/DANG-PH/MICROSERVICE_API_GATEWAY) · [Game client](https://download.ngocrongdark.com)

---

## 💼 Work Experience

**Gamota – Gabros Studio** · Backend Developer Intern *(11/2025 – 2/2026)*  
Real-time multiplayer backend · WebSocket · Redis-backed state · idempotent distributed transaction workflows · load-tested 1,000+ CCU

**Mobifos JSC – Gahu Studio** · Fullstack Developer Intern *(8/2025 – 11/2025)*  
3 NestJS microservices · RabbitMQ retry pipelines (recovered ~30% transient failures) · MySQL indexing + Redis caching (cut latency ~70%) · ~2,000 CCU production system

---

## 📌 What I Focus On

```
Distributed transactions    →  Saga · Outbox · idempotency · eventual consistency
Concurrency control         →  Redis + Lua · distributed locking · race condition prevention  
Observability               →  structured logging · alerting · incident detection
Performance                 →  async batching · caching strategies · throughput optimization
Security                    →  JWT · RBAC · OAuth2 · rate limiting · DDoS mitigation
```

---

<div align="center">

**Open to backend roles in gaming or fintech**  
*Building things that stay up.*

</div>
