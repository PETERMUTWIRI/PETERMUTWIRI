<div align="center">
  <img src="https://github.com/PETERMUTWIRI/readme-images/blob/main/images/PETERMUTWI.MD.png" alt="PETERMUTWIRI">
</div>

<h3 align="center">Hi there, 👋 I’m Peter Mutwiri</h3>
<h2 align="center">Full-Stack Engineer | AI-Agent Builder | CloudOps Mercenary</h2>

<p align="center">
  <strong>Current mission:</strong> Ship production-grade AI copilots, keep the AWS bill low, and stop Stripe from eating SaaS margins.
</p>
---

### 🚀 Latest Fire (2024-2025)

| Stack | What Went Live | Repo / Link |
|-------|----------------|-------------|
| **MutsynChub** – Analytics Copilot | Redis-driven event hub, DuckDB + pg-vector, 5 autonomous agents (embed, chat, KPI, entity, industry detector). 100 % TypeScript, serverless on Vercel. | [mutsynchub.app](https://mutsynchub.app) |
| **Neon-Stack-Auth Refactor** | Fixed race-conditions, cache poisoning, TS strict-null, zero build errors. SSR role resolution, Google SSO, atomic logout hook. 
| **Vibe-Code Agency** | 4 shipped sites in 30 days (Next.js, Tailwind, Stripe, Resend). 100 % prompt-to-prod, 0 % hand-written CRUD. | Portfolio below |
| **POS Plug-in** | Node bridge that pushes CSV sales → DuckDB lake nightly; used by 3 Kenyan retailers. | [petermutwiri/pos-sync](https://github.com/PETERMUTWIRI/pos-sync) |

---

### 🧠 Agent Architecture I Use

1. **Ingest** – S3 / Webhook → Redis Streams (event sourcing)  
2. **Embed** – OpenAI text-embedding-3 → pg-vector (DuckDB for OLAP)  
3. **Plan** – ReAct loop (function-calling) with deterministic guardrails  
4. **Memory** – Thread-level conversation memory, long-term Zep hybrid  
5. **Ops** – Vercel edge functions, CloudWatch alarms, SLO: 250 ms p95  
6. **Wallet** – Usage-metered → Stripe meter events → automatic top-up

---

### ☁️ Cloud & Ops
- **AWS** – CDK-Terraform hybrid, VPC-less serverless, EventBridge pipes, S3 life-cycle 30 d → Glacier.  
- **Oracle Cloud** – Always-Free ARM VM running Plausible analytics + n8n workflows.  
- **Vercel** – All customer front-ends, Preview-per-PR, 0-downtime.  
- **DuckDB-WASM** – Browser-side OLAP, no backend for &lt; 50 MB datasets.  
- **Monitoring** – Grafana Cloud (Prometheus), PagerDuty on 5 % error budget burn.

---

### 🛠️ Current Toolkit
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=next.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF?style=flat-square&logo=duckdb&logoColor=000)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-232F3E?style=flat-square&logo=amazon-aws&logoColor=orange)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

---

### 📈 GitHub Pulse
[![Stats](https://github-readme-stats.vercel.app/api?username=PETERMUTWIRI&show_icons=true&theme=radical)](https://github.com/PETERMUTWIRI)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=PETERMUTWIRI&layout=compact&theme=radical)](https://github.com/PETERMUTWIRI)

---

### 🤝 Open to
- Fractional SRE / AI-agent gigs   
- Technical writing on serverless + AI patterns

Last commit: 2025-01-20 UTC
