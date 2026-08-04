<div align="center">

# Karim Mattar

### Senior Software &amp; Platform Engineer

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=620&lines=Python+%C2%B7+TypeScript+%C2%B7+Go+%C2%B7+C%2B%2B;I+build+backend+systems+that+stay+up.;Identity+%C2%B7+Payments+%C2%B7+Real-time+Data+%C2%B7+Platforms" alt="Python, TypeScript, Go, C++ — I build backend systems that stay up." />

<br />

<a href="https://www.linkedin.com/in/karim-hady-69147a195" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDAxLTIuMDYzLTIuMDY1IDIuMDY0IDIuMDY0IDAgMTEyLjA2MyAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyNSAweiIvPjwvc3ZnPg==" alt="LinkedIn" />
</a>
<a href="mailto:karimhady111@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://wa.me/201095121211" target="_blank">
  <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
</a>
<img src="https://img.shields.io/badge/Cairo,%20Egypt-2C3E50?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Cairo, Egypt" />

</div>

---

## 👋 About me

I am a software engineer with **6+ years of experience** building backend and platform systems that run in production.

Today I work at **[Digified](https://digified.io)**, a digital identity company. We build eKYC: we help banks and fintechs verify who their customers really are, using document reading, face matching, and government data checks. My job is the backend — the services behind all of it.

I like problems where **correctness matters**. Money must not be lost. A token must not leak. A market feed must not drop a tick. I write code with that in mind, and I ship it with tests, metrics, and logs so I can prove it works.

I ship production code in **Python, TypeScript, Go, and C++**. I pick the language that fits the job, not the one I like most.

## 🧠 What I do

| | |
| :-- | :-- |
| 🔐 **Identity &amp; security** | OAuth2 / OIDC providers, multi-tenant IAM, RS256 JWTs with JWKS, MFA (TOTP, WebAuthn, SMS), RBAC, consent and revocation flows, encrypted PII. |
| 💳 **Payments &amp; billing** | Invoices, subscriptions, promo codes, payment links, and webhook-confirmed payments — built so raw card data is never stored. |
| 📈 **Real-time &amp; data** | Stock-exchange market-data feeds, Redis Streams pipelines with retries and dead-letter queues, and Oracle → PostgreSQL / TimescaleDB ingestion holding six years of history. |
| ☁️ **Platform &amp; infra** | Docker, CI/CD, reverse proxies with automatic TLS, object storage, and observability with Prometheus, Grafana and OpenTelemetry. |

## 🚀 Selected work

<table>
<tr>
<td width="50%" valign="top">

### 🟣 Deployly &nbsp;<sub>`personal`</sub>

A hosting platform for frontend apps, like Vercel. You push code and get an
immutable deployment on its own URL, with **instant rollback** and **automatic
TLS** on custom domains.

The design rule it is built around: the request hot path **never** touches
Postgres, Redis, or S3.

`Go` `Next.js` `Caddy` `PostgreSQL` `Redis` `S3 / MinIO` `Docker`

</td>
<td width="50%" valign="top">

### 🟡 Yudi &nbsp;<sub>`personal`</sub>

A markup language for portfolios. One `.yudi` file compiles into three
things: an animated website, a print-ready PDF CV, and a link-in-bio page.

Includes a full language toolchain — lexer, parser, typed AST, renderer, CLI —
plus a multi-tenant SaaS API with its own IAM layer.

`TypeScript` `Fastify` `Drizzle` `PostgreSQL` `Next.js`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔵 Identity Provider &nbsp;<sub>`work`</sub>

A multi-tenant OAuth2 / OIDC identity provider for the MENA region.
Schema-per-tenant isolation, Authorization Code + PKCE, consent screens,
JWKS discovery, MFA, and eKYC verification built in.

`Go` `PostgreSQL` `Docker`

</td>
<td width="50%" valign="top">

### 🟢 Market Data Platform &nbsp;<sub>`work`</sub>

An end-to-end pipeline for an Egyptian stock-exchange data feed: a **C++17**
bridge on the exchange protocol, a NestJS customer API, and a Python service
that lands six years of history into TimescaleDB.

`C++17` `NestJS` `Python` `TimescaleDB` `Oracle` `Redis`

</td>
</tr>
</table>

## 🧭 Where I have worked

- 🔷 **Digified** &nbsp;·&nbsp; *current* — backend services for a digital identity and eKYC platform:
  authentication and authorization, licensing, notifications and OTP, and third-party integrations.
- 📈 **Capital markets** — market-data infrastructure for an Egyptian stock-exchange feed:
  protocol bridge, customer APIs, billing, and a historical time-series store.
- 🏥 **Medical conferences &amp; e-learning** — registration portals, learning systems,
  and event platforms used by real attendees.
- 🧩 **SaaS products** — backend and full-stack work across several products and teams.

## 🛠️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)

**Infrastructure &amp; observability**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO%20%2F%20S3-C72E49?style=flat-square&logo=minio&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)

**Security &amp; auth**

![OAuth2 / OIDC](https://img.shields.io/badge/OAuth2%20%2F%20OIDC-EB5424?style=flat-square&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![WebAuthn](https://img.shields.io/badge/WebAuthn%20%2F%20TOTP-3423A6?style=flat-square&logo=webauthn&logoColor=white)
![Let's Encrypt](https://img.shields.io/badge/Let's%20Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white)

## 📊 On GitHub

> **A note on the numbers here.** Almost all of my professional work lives in
> **private repositories** — company GitLab and a self-hosted Gitea — so my public
> profile does not show it. The projects above are the real picture of what I build.
> I am happy to walk through any of them in a call.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/karimmattar/karimmattar/output/snake.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/karimmattar/karimmattar/output/snake-light.svg" />
  <img src="https://raw.githubusercontent.com/karimmattar/karimmattar/output/snake.svg" alt="Contribution snake animation" />
</picture>

</div>

## 🤝 Let's talk

If you are building something where reliability matters — identity, payments,
real-time data, or the platform underneath them — I would enjoy talking about it.

<div align="center">

<a href="mailto:karimhady111@gmail.com">
  <img src="https://img.shields.io/badge/Say%20hello-karimhady111@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me" />
</a>
<a href="https://www.linkedin.com/in/karim-hady-69147a195" target="_blank">
  <img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2EyLjA2MiAyLjA2MiAwIDAxLTIuMDYzLTIuMDY1IDIuMDY0IDIuMDY0IDAgMTEyLjA2MyAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyNSAweiIvPjwvc3ZnPg==" alt="LinkedIn" />
</a>

<br /><br />

<sub>Thanks for stopping by. ⭐</sub>

</div>
