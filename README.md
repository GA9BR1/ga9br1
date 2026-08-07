# Gustavo Alberto

**Backend engineer — Ruby and Elixir.** Goiânia, Brazil.

I work on the parts users never see: constraint solvers, message-driven services,
background pipelines, and APIs that have to hold up under load.

---

## Open source

Core contributor to two Ruby libraries at **[Rebase](https://github.com/Rebase-BR)**:

**[csp-resolver](https://github.com/Rebase-BR/csp-resolver)** · *48 commits*
A gem for solving [Constraint Satisfaction Problems](https://en.wikipedia.org/wiki/Constraint_satisfaction_problem) — you declare variables, domains and
the constraints between them, and it finds an assignment that satisfies all of them.
Used for scheduling, planning, and configuring systems with hard rules.

**[sports-manager](https://github.com/Rebase-BR/sports-manager)** · *37 commits*
Tournament scheduling built on top of `csp-resolver`. Turns court availability, match
length, rest windows and participant constraints into a calendar that actually works.

---

## Selected projects

**[insurance_flow](https://github.com/GA9BR1/insurance_flow)** — `Rails` `GraphQL` `RabbitMQ` `Sneakers` `Sinatra` `Postgres` `Docker`
Vehicle insurance policy issuing, split across three services: a GraphQL gateway that
validates and authorizes, a REST API that owns the policy data, and a web app with three
auth paths (Cognito, Google OAuth, email/password) — all wired over RabbitMQ, JWT-authenticated
end to end. One `docker compose up` brings the whole thing up.

**[e-teg-challenge](https://github.com/GA9BR1/e-teg-challenge)** — `TypeScript` `React` `Fastify` `Prisma` `Postgres` `Docker`
Client onboarding through single-use form links, with an admin panel to issue links, read
responses and manage theming. TypeScript monorepo, containerized end to end: `docker compose up`
runs migrations and seeds on its own. Unit, integration and browser E2E tests all run in-container.

**[rinha-de-backend-2024-q1](https://github.com/GA9BR1/rinha-de-backend-2024-q1)** — `Ruby` `Agoo` `Postgres` `PgBouncer` `Nginx`
A concurrency gauntlet. Ruby on the Agoo web server, PgBouncer pooling in front of Postgres,
Nginx balancing — built to survive the Rinha de Backend load test and profiled with Gatling.

**[medical_exams_csv](https://github.com/GA9BR1/medical_exams_csv)** — `Ruby` `Sidekiq` `Vue` `Postgres` `Docker`
Bulk medical-exam ingestion. CSV uploads are queued to Sidekiq and processed asynchronously;
the UI polls job status and folds new records in without a page reload. Search by token, CPF
or result date, with pagination.

---

## Writing

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

---

## Stack

| | |
|---|---|
| **Languages** | Ruby · Elixir · TypeScript · Dart · Python · SQL |
| **Backend** | Rails · Phoenix · Sinatra · Fastify · GraphQL · Sidekiq · Sneakers · RabbitMQ |
| **Data** | PostgreSQL · Redis · PgBouncer · MySQL |
| **Frontend** | React · Vue · Flutter |
| **Infra** | Docker · Nginx · Linux · GitHub Actions · Grafana |

---

## Elsewhere

[LinkedIn](https://linkedin.com/in/gustavoalbertodev) · [dev.to](https://dev.to/ga9br1) · [Medium](https://medium.com/@gustavoalberttodev)

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=ga9br1&layout=compact&hide_border=true&langs_count=8" alt="Most used languages" />
