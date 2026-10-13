# Hi, I'm Isenewo Oluwaseyi Ephraim

### Backend Engineer · Node.js (TypeScript) · Go · Python · AWS Certified Solutions Architect

I build backend systems that hold up in production: APIs, payment flows, real-time services and distributed infrastructure, deployed on AWS with Terraform and Docker.

- 🔀 **290+ merged pull requests** to open-source backends, smart-contract and fintech projects ([see them](https://github.com/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged+-user%3AOluwaseyi89))
- 🏗️ Designed and shipped multi-service platforms end to end: API, database, payments, infrastructure and CI
- 💼 **Open to backend engineering roles** (remote or on-site), based in Nigeria

[![AWS Certified Solutions Architect – Associate](https://img.shields.io/badge/AWS_Certified-Solutions_Architect-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://www.credly.com/badges/a3f4c771-db13-4a31-b0ff-51a8a9cf58ef/public_url)
[![AWS Certified Cloud Practitioner](https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://www.credly.com/badges/1b7edc11-16e1-4c29-b281-608f9e8731ea/public_url)

---

## 🛠️ Featured Backend Projects

### [Global Rate Limiter as a Service](https://github.com/Oluwaseyi89/global-rate-limiter) · Go, Redis, NGINX, Docker
Central rate limiting for microservices that share strict external API quotas.
- Sliding-window algorithm on Redis sorted sets, with **atomic Lua scripts** so concurrent requests can't race
- Built for high availability: Redis primary-replica, a **3-state circuit breaker**, a local-cache fallback, and 3 instances behind a least-conn load balancer
- P95/P99 latency analytics, async audit logging through a worker pool, graceful shutdown, liveness and readiness probes

### [Parcel App](https://github.com/Oluwaseyi89/parcel-app) · Python (Django + DRF), Java (Spring Boot), PostgreSQL, Celery, Terraform on AWS ECS Fargate
Multi-vendor commerce and delivery platform covering checkout, dispatch, courier workflows and vendor operations. [Live demo](https://parcel-app-web.vercel.app)
- Django/DRF core API with Celery and Redis background jobs, and cookie-session auth shared by the web, admin and mobile clients
- A separate **Spring Boot payment service** that integrates Paystack, with transaction verification
- Infrastructure as code with Terraform, deployed to AWS ECS Fargate

### [Funkey Grab & Bite](https://github.com/Oluwaseyi89/funkey-grab-and-bite) · Go (Gin), PostgreSQL, Terraform, AWS
Food-commerce operations platform with ordering, catering, programmable promotions, and an admin command centre. [Live demo](https://funkey-bite-web.vercel.app)
- Go API organised by business domain, with a real-time event contract for order updates
- AWS infrastructure defined in Terraform

### [Infinite Canvas](https://github.com/Oluwaseyi89/real-time-canvas) · Go (Gin), WebSocket, PostgreSQL, Redis
Real-time collaborative whiteboard with presence, offline sync and session replay ("time travel").
- Go WebSocket service handling multi-user sessions, with Redis for live state and PostgreSQL for persistence
- Separate CI pipelines for the service and the web client

### [Road Sense Analytics](https://github.com/Oluwaseyi89/toyota-hack-the-track) · Python (Django Channels, FastAPI), scikit-learn
Real-time motorsport telemetry platform built for the Toyota GR Cup *Hack the Track* hackathon. [Live demo](https://road-sense-app.vercel.app)
- Telemetry REST APIs and WebSocket streaming, a FastAPI analytics engine, and ML models for tire wear, fuel and pit strategy

<details>
<summary><b>More projects</b></summary>

- [**Queue-as-a-Service**](https://github.com/Oluwaseyi89/queue-as-a-service) (Rust): a message queue for AI agents, exposed over MCP. Cargo workspace, WAL persistence, JWT/API-key auth, Prometheus and Grafana, strict CI (clippy, cargo-deny)
- [**FinEdge**](https://github.com/Oluwaseyi89/fin-edge) (Rust/Axum, PostgreSQL): expense and budget management for SMEs, with multi-company support
- [**NeuraPlay**](https://github.com/Oluwaseyi89/neuraplay-cloudrun) (Django, Gemini, Google Cloud Run): AI game-coaching backend with speech-to-text and text-to-speech pipelines
- [**Terraform Projects**](https://github.com/Oluwaseyi89/terraform-projects) (HCL): modular multi-cloud infrastructure for AWS (VPC, EKS, RDS, Lambda), Azure and GCP

</details>

---

## 🌍 Open-Source Contributions

Merged work in production codebases, mostly **TypeScript/Node.js backends** and Stellar/Starknet smart contracts:

| Project | Stack | What I contributed |
|---|---|---|
| [CRYPTOInsured / zeus](https://github.com/CRYPTOInsured-Foundation/zeus/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged) | TypeScript, Cairo, Rust | Escrow factory, atomic-swap escrow with platform fees, lock timeouts and automatic refunds, a P2P integration test suite, Stellar backend integration |
| [StreamPay Backend](https://github.com/Streampay-Org/StreamPay-Backend/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged) | Node.js, TypeScript | `POST /streams` API with Zod validation, Soroban RPC client with retry policy, transaction-submission layer, immutable audit-log pipeline |
| [ChronoPay Backend](https://github.com/Chronopay-Org/ChronoPay-Backend/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged) | Node.js, TypeScript | Booking-intent APIs with owner/admin authorization, slot-update endpoint, cache-invalidation strategy |
| [ACBU Backend](https://github.com/Pi-Defi-world/acbu-backend/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged) | Node.js, TypeScript, PostgreSQL | Real USDC→XLM swap on the Stellar DEX, RabbitMQ schema-validation fix, gitleaks secret scanning in CI |
| [CarbonScribe](https://github.com/CarbonScribe/carbon-scribe/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged) | TypeScript, Go, Rust | **24 merged PRs**: set up the Go/Gin service, auth-service refactor, CI workflows, contract deployment, review of contributor submissions |
| [NFTopia (Stellar)](https://github.com/NFTopia-Foundation/nftopia-stellar/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged) | TypeScript, Rust (Soroban) | **18 merged PRs**: email/password auth with wallet linking, GraphQL bootstrap fixes, CI pipelines, testnet contract deployment |

➡️ [All merged pull requests](https://github.com/pulls?q=is%3Apr+author%3AOluwaseyi89+is%3Amerged+-user%3AOluwaseyi89)

---

## 📊 GitHub Activity

<p align="left">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Oluwaseyi89&show_icons=true&include_all_commits=true&hide=stars,issues&show=prs_merged,reviews&theme=tokyonight&hide_border=true&border_radius=8&cache_seconds=21600" alt="GitHub stats"/>
  <img height="170" src="https://streak-stats.demolab.com/?user=Oluwaseyi89&theme=tokyonight&hide_border=true&border_radius=8" alt="GitHub streak"/>
</p>

---

## 🧰 Tech Stack

**Primary languages:** Node.js (TypeScript), Go, Python
**Also production-capable in:** Java (Spring Boot), Rust

<p align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white"/>
</p>
<p align="left">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
</p>

**Blockchain (bonus):** Stellar/Soroban, Starknet/Cairo, Ethereum

---

## 📫 Let's Talk

<p align="left">
  <a href="https://isenewo-oluwaseyi.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjEwIi8%2BPHBhdGggZD0iTTIgMTJoMjAiLz48cGF0aCBkPSJNMTIgMmExNS4zIDE1LjMgMCAwIDEgNCAxMCAxNS4zIDE1LjMgMCAwIDEtNCAxMCAxNS4zIDE1LjMgMCAwIDEtNC0xMCAxNS4zIDE1LjMgMCAwIDEgNC0xMHoiLz48L3N2Zz4%3D&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/oluwaseyi-isenewo-6463838a"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDEgMSAwLTQuMTI1IDIuMDYyIDIuMDYyIDAgMCAxIDAgNC4xMjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://x.com/IsenewoE"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
</p>
