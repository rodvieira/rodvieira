# Hi, I'm Rodrigo Vieira 👋

**Senior Frontend Engineer** — React & TypeScript · Scalable Frontend Architecture ·
Micro-Frontends & Design Systems

8+ years building scalable, production-grade React applications — Design Systems,
Micro-Frontends, high-traffic checkout platforms, and complex administrative
interfaces. I design frontend architectures for scalability, modularity, and
long-term maintainability, and collaborate on backend services in Node.js and Go to
ship seamless, end-to-end solutions. Currently going deeper on AI-native
development: structured LLM tool calling, provider-agnostic architectures, and
Spec-Driven workflows with GitHub Spec Kit + Claude Code.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rodrigo--vieira--dev-informational?style=flat&logo=linkedin&logoColor=white&color=2bbc8a)](https://www.linkedin.com/in/rodrigo-vieira-dev/)
[![Location](https://img.shields.io/badge/Based%20in-S%C3%A3o%20Paulo%2C%20Brazil-informational?style=flat&logo=googlemaps&logoColor=white&color=2bbc8a)](https://github.com/rodvieira)

---

## 🔭 Currently

- 💼 Senior Software Engineer at **NTConsult** — Design Systems, Micro-Frontends
  (Qiankun), and a NestJS/GraphQL BFF on Hexagonal Architecture.
- 🎯 Shipped **[Pricing Optimizer](https://pricing-optimizer-web.vercel.app)**
  end-to-end — an AI product split across a Go API and a Next.js frontend, two
  independently deployed repos sharing one OpenAPI contract.
- 🧠 Working AI-native by design: Spec-Driven Development, `.claude/` workflow
  committed alongside the code, not bolted on after.
- 🌎 Open to senior frontend / fullstack roles on international, remote-first teams.

---

## 🚀 Featured projects

### 🎨 [pricing-optimizer-web](https://github.com/rodvieira/pricing-optimizer-web) — *AI pricing-page generator, frontend*

Paste a product URL, watch three AI-generated pricing-page variations stream in live
over SSE, compare strategies side by side, export as JSX, HTML, or a Stripe Pricing
Table config. Feature-Sliced architecture, hand-rolled SSE consumption (`fetch` +
`ReadableStream`, since `EventSource` can't POST), 108 unit + 14 e2e tests, Lighthouse
98 measured against the live deploy.

`Next.js 16` `TypeScript` `TanStack Query` `Tailwind v4` `Playwright`

**[→ Live app](https://pricing-optimizer-web.vercel.app)** · [Repo](https://github.com/rodvieira/pricing-optimizer-web)

### ⚙️ [pricing-optimizer-api](https://github.com/rodvieira/pricing-optimizer-api) — *AI pricing-page generator, backend*

Contract-first Go API: two-tier scraping (fast static fetch first, headless Chromium
only when the page is a client-rendered SPA), three pricing strategies generated in
parallel via structured LLM tool calling, one `LLMProvider` interface swapping
Anthropic and Groq by env var, OpenTelemetry tracing, $0/month infra by construction.

`Go 1.26` `Chi` `PostgreSQL` `Redis` `Cloud Run`

**[→ Live API](https://pricing-optimizer-api-hnzq7nvuqq-uc.a.run.app/v1/healthz)** · [Repo](https://github.com/rodvieira/pricing-optimizer-api)

---

## 💼 Experience highlights

- **NTConsult** *(2024 – present)* — Built a corporate Design System from scratch
  (React, TypeScript, Vanilla-Extract, Storybook, Atomic Design); led a
  Micro-Frontends architecture with Qiankun; built and maintain a BFF in NestJS +
  GraphQL on Hexagonal Architecture with OpenTelemetry/Prometheus observability.
- **Retornar** *(2020 – 2024)* — Designed a high-scale payment checkout supporting
  peaks of 20,000 concurrent users; built the company's Backoffice platform from
  scratch; shipped a cross-platform React Native app.
- **aiqfome** *(2022 – 2023)* — Raised unit test coverage to 85%+ on a restaurant
  management system built with React, Electron, and TypeScript.

Full history on [LinkedIn](https://www.linkedin.com/in/rodrigo-vieira-dev/).

---

## 🛠️ Tech I work with

![React](https://img.shields.io/badge/Code-React-informational?style=flat&logo=react&logoColor=white&color=2bbc8a)
![TypeScript](https://img.shields.io/badge/Code-TypeScript-informational?style=flat&logo=typescript&logoColor=white&color=2bbc8a)
![Next.js](https://img.shields.io/badge/Code-Next.js-informational?style=flat&logo=next.js&logoColor=white&color=2bbc8a)
![Node.js](https://img.shields.io/badge/Code-Node.js-informational?style=flat&logo=node.js&logoColor=white&color=2bbc8a)
![Go](https://img.shields.io/badge/Code-Go-informational?style=flat&logo=go&logoColor=white&color=2bbc8a)
![GraphQL](https://img.shields.io/badge/API-GraphQL-informational?style=flat&logo=graphql&logoColor=white&color=2bbc8a)
![NestJS](https://img.shields.io/badge/Backend-NestJS-informational?style=flat&logo=nestjs&logoColor=white&color=2bbc8a)
![PostgreSQL](https://img.shields.io/badge/DB-PostgreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=2bbc8a)
![Redis](https://img.shields.io/badge/DB-Redis-informational?style=flat&logo=redis&logoColor=white&color=2bbc8a)
![Docker](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=2bbc8a)
![GCP](https://img.shields.io/badge/Cloud-GCP-informational?style=flat&logo=googlecloud&logoColor=white&color=2bbc8a)
![Vercel](https://img.shields.io/badge/Cloud-Vercel-informational?style=flat&logo=vercel&logoColor=white&color=2bbc8a)
![OpenTelemetry](https://img.shields.io/badge/Observability-OpenTelemetry-informational?style=flat&logo=opentelemetry&logoColor=white&color=2bbc8a)

**Also:** Micro-Frontends (Qiankun) · Design Systems (Atomic Design, Storybook,
Vanilla-Extract) · Hexagonal Architecture · DDD · Prompt Engineering

---

## 📜 Certifications

Software Architecture Fundamentals · SOLID Principles for Clean Code · Domain-Driven
Design (DDD) Fundamentals · Advanced Go (Golang) Development · Hexagonal Architecture
for Software Development

---

## 📊 GitHub

![Rodrigo's GitHub stats](https://github-readme-stats.vercel.app/api?username=rodvieira&show_icons=true&hide_border=true&theme=default)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=rodvieira&layout=compact&hide_border=true&theme=default)

---

## 🤝 Let's talk

Open to senior frontend and fullstack conversations — remote, international teams.
Reach out on [LinkedIn](https://www.linkedin.com/in/rodrigo-vieira-dev/).
