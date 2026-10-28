<h1 align="center">Mikaela Perez Guedes</h1>

<p align="center">
  <b>Full Stack Software Engineer</b> · Node.js · TypeScript · Java · React<br/>
  Porto Alegre, Brazil · 🇧🇷 / 🇺🇸
</p>

---

I build backend-heavy products end to end: APIs, data models, the frontend that sits on top of them and the pipeline that ships them. For the last three years I've been working on production systems, and the part I care about most is the one users never see: **data that stays correct under concurrency, failures that are handled on purpose, and code the next person can safely change.**

### 🔭 Featured project

#### [fintech-wallet-platform](https://github.com/mikaelapg/fintech-wallet-platform)

A digital wallet built around the hard parts of moving money.

- **Double-entry ledger** on PostgreSQL, append-only and enforced by the database
- **Idempotent transfers** (`Idempotency-Key`) — retries and double clicks never move money twice
- **Race-safe balances** — row locking in deterministic order, proven by concurrent integration tests
- **Transactional outbox → RabbitMQ**, idempotent consumers, retry with backoff and dead-letter queue
- Redis cache-aside and rate limiting, JWT auth, RFC 9457 errors, OpenAPI docs
- React + TanStack Query frontend, Docker, Kubernetes manifests (HPA, PDB, probes) and GitHub Actions CI

`Node.js` `TypeScript` `Fastify` `PostgreSQL` `Redis` `RabbitMQ` `React` `Docker` `Kubernetes`

### 🛠️ Stack

| | |
|---|---|
| **Backend** | Node.js, TypeScript, Java, Spring Boot, Fastify, Express, REST APIs |
| **Frontend** | React, TypeScript, TanStack Query, Tailwind CSS, HTML, CSS |
| **Data** | PostgreSQL, MongoDB, Redis |
| **Messaging** | RabbitMQ, event-driven architecture, outbox pattern |
| **DevOps** | Docker, Kubernetes, GitHub Actions, AWS |
| **Practices** | Automated testing, clean code, code review, Scrum / Kanban |

### 💡 How I work

- I start from the failure modes: what happens on retry, on timeout, when two requests race.
- I push invariants down to the database when they matter (constraints, transactions, locks).
- I test behavior against real dependencies, not mocks of them.
- I write down the *why* of technical decisions so the team doesn't have to guess.

### 📫 Let's talk

Open to **Full Stack / Backend** opportunities, remote or hybrid.
