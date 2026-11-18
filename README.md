<div align="center">

<img src="https://avatars.githubusercontent.com/u/105883792?v=4" width="110" height="110" alt="Mouad Elattar" style="border-radius:50%;" />

# Mouad Elattar

**Software Engineer** · Full-Stack Systems · APIs · Data Platforms

*I design and ship software that stays clear under complexity — structured data, reliable interfaces, and systems people can operate.*

[![GitHub](https://img.shields.io/badge/GitHub-MOUAD010-181717?style=flat-square&logo=github)](https://github.com/MOUAD010)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mouad%20Elattar-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/mouad-el-attar)
[![Email](https://img.shields.io/badge/Email-mouad.elattar.dev%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mouad.elattar.dev@gmail.com)
[![Location](https://img.shields.io/badge/Based%20in-Morocco-1F2937?style=flat-square)](https://github.com/MOUAD010)

</div>

---

## About

I am a software engineer focused on building **end-to-end applications** — from data models and APIs to the interfaces that consume them. My work centers on systems that ingest external data, persist it cleanly, expose it through well-defined boundaries, and remain operable in production.

I approach problems by clarifying the domain first: what must be true in the data, which boundaries protect the system, and which parts should stay replaceable. That usually leads to typed contracts, explicit repositories, guarded admin surfaces, and infrastructure that can be rebuilt the same way every time.

I am especially interested in:

- Backend services and API design
- Full-stack product development
- Database schema design and data synchronization
- Application security and authentication
- Containerized deployment and operational tooling
- Thoughtful architecture over premature abstraction

I treat continuous learning as part of the job: deepen fundamentals, then apply them in production-shaped projects.

---

## Technical Skills

Skills below are organized by **evidence**. Primary stack items appear in my public project work. Additional technologies are self-reported from prior study and practice.

### Evidenced in public work

| Area | Technologies |
| --- | --- |
| **Languages** | TypeScript, JavaScript, SQL |
| **Frontend** | React, Next.js (App Router), Tailwind CSS |
| **Backend & APIs** | Next.js Route Handlers, external API clients, Zod validation |
| **Data** | PostgreSQL, Drizzle ORM, schema design, sync pipelines |
| **Auth & Security** | Auth.js / NextAuth, bcrypt, session guards, HTML sanitization (DOMPurify) |
| **i18n & Content** | next-intl (EN / FR / AR), TipTap rich text, SEO / sitemap tooling |
| **DevOps** | Docker, Docker Compose, multi-stage Node builds |
| **Tooling** | Git, ESLint, npm |

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,postgres,docker,tailwind,git" alt="Core technology icons" />
</p>

### Also experienced with *(self-reported)*

| Area | Technologies |
| --- | --- |
| **Languages & Backend** | Java, Spring Boot, PHP |
| **Infrastructure** | Cloudflare |

> These are listed separately because they are not yet demonstrated in my public repositories. Happy to discuss them in conversation or via private work samples.

---

## Featured Project

### [BotolaHub](https://github.com/MOUAD010/botolahub) — Football data platform & editorial CMS

**Problem.** Moroccan league fans and editors need a single place for fixtures, standings, teams, players, and news — kept current from live data sources, not maintained by hand.

**What it does.**

- Public multilingual site (English, French, Arabic) for competitions, matches, teams, and player profiles
- Automated sync from API-Football into PostgreSQL (catalog, fixtures, standings, squads, live updates)
- Admin CMS for news, media, ads, analytics, and sync control
- SEO surfaces: sitemap generation, Open Graph images, JSON-LD, Search Console integration
- Search, match ticker, standings, lineups, and comparison stats

**Technical approach.**

- **Next.js + TypeScript** full-stack application with App Router route groups for site and admin
- **PostgreSQL + Drizzle ORM** with a deliberate schema for competitions, fixtures, players, news, and sync runs
- **Repository layer** separating domain reads from persistence
- **Auth.js credentials flow** with bcrypt-hashed admin accounts, JWT sessions, and `requireAdmin` API guards
- **Background live worker** via Docker Compose calling an authenticated internal sync endpoint
- **Input validation** with Zod; **XSS hardening** for rich HTML via DOMPurify
- **Multi-stage Docker** production image (Node 22 Alpine, non-root user, standalone Next output)

**Stack.** TypeScript · Next.js · React · PostgreSQL · Drizzle · Auth.js · Zod · next-intl · TipTap · Tailwind · Docker

**Why it matters.** It is not a tutorial app. It combines product UI, domain modeling, external API ingestion, auth-bound admin APIs, and containerized operations in one codebase.

**Repository:** [github.com/MOUAD010/botolahub](https://github.com/MOUAD010/botolahub)

---

## Engineering Principles

How I prefer to work when building software:

| Principle | In practice |
| --- | --- |
| **Clarity over cleverness** | Prefer readable structure and explicit names to dense abstractions |
| **Separation of concerns** | UI, domain access, sync jobs, and auth boundaries stay distinct |
| **Typed contracts** | Validate at the edges (Zod, schema constraints) before trusting input |
| **Secure by default** | Hash secrets, guard privileged routes, sanitize untrusted HTML |
| **Operability** | Dockerized builds, env-driven config, sync jobs that can be observed and retried |
| **DRY / KISS** | Share what is stable; avoid premature frameworks around one-off logic |
| **Maintainability** | Schema, repositories, and admin workflows should be extendable without rewrites |
| **Documentation as interface** | Env examples, scripts, and structure that explain how the system runs |

---

## Currently Exploring

Areas I am actively deepening — not claims of production expertise yet:

- **Software architecture** patterns for growing full-stack systems
- **Application security** beyond authentication basics (threat modeling, hardening checklists)
- **DevOps practices** around observability, CI, and safer release workflows
- **AI integration** in engineering workflows and product features (assistive tooling, not magic)

---

## GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=MOUAD010&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&ring_color=58A6FF" alt="MOUAD010 GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MOUAD010&layout=compact&theme=dark&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top languages" height="165" />

<br />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=MOUAD010&theme=dark&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" alt="GitHub streak" />

<br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MOUAD010&bg_color=0D1117&color=58A6FF&line=58A6FF&point=C9D1D9&area=true&hide_border=true" alt="Contribution activity graph" />

</div>

---

## Contact

I am open to software engineering conversations, collaboration, and opportunities where reliable full-stack systems matter.

| | |
| --- | --- |
| **Email** | [mouad.elattar.dev@gmail.com](mailto:mouad.elattar.dev@gmail.com) |
| **GitHub** | [github.com/MOUAD010](https://github.com/MOUAD010) |
| **LinkedIn** | [linkedin.com/in/mouad-el-attar](https://www.linkedin.com/in/mouad-el-attar) |
| **Featured work** | [BotolaHub](https://github.com/MOUAD010/botolahub) |

---

<div align="center">

*Built with intention — clear systems, honest skills, measurable work.*

</div>
