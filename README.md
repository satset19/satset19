# Satriyo Laksono

Backend-leaning full-stack developer building event-driven, multi-tenant messaging systems with Go, TypeScript, and Kafka.

---

## Stack

- **Languages:** Go, TypeScript, JavaScript, Dart, SQL
- **Backend:** Fiber, GORM, Node.js, Fastify, NestJS, Express, Hapi, GraphQL (Apollo), gRPC
- **Frontend & Mobile:** React, Vite, TanStack (Router/Query/Table), Tailwind, shadcn/ui, Ant Design, Flutter
- **Data:** PostgreSQL, MongoDB, Redis, Trino, DuckDB, S3-compatible object storage
- **Messaging:** Kafka, NATS JetStream, WebSocket
- **Infra & Ops:** Docker, Docker Swarm, Podman, GitLab CI, OpenBao (Vault), nginx, Prometheus, Grafana, Loki

## What I've Been Working On

Professional work on a multi-tenant chat & CRM platform built around WhatsApp messaging:

- **NATS → Kafka migration** across ~6 Go and TypeScript services: per-tenant topics, SASL auth, dead-letter queues, bounded retries, and request-reply between services.
- **WhatsApp session agent** (TypeScript, Fastify, Baileys): per-tenant sessions, outbound send throttling, identity resolution (LID ↔ phone), chat-history sync with progress reporting, media upload to object storage.
- **Event ingestion pipeline** (Go): persists messaging events to PostgreSQL with idempotent upserts, Postgres CDC into per-tenant streams, and realtime fan-out over WebSocket.
- **Realtime & REST APIs** (Go, Fiber): WebSocket push service with Kafka consumer groups and lag metrics; CRUD and reporting APIs over PostgreSQL and a Trino/DuckDB data lake.
- **Deployment platform rework:** Kubernetes/Helm → Podman → Docker Swarm, a control-plane API that provisions per-tenant containers, shared GitLab CI templates (kaniko, semantic-release, commitlint), secrets from OpenBao, and a pinned in-house CI tool image.
- **Frontend** (React, Vite, TanStack, shadcn/ui): chat & CRM dashboard features — history-sync UI, contact cards, media upload, accessibility fixes.
- **Observability & docs:** structured logging with tenant context, Prometheus/Grafana dashboards, and design docs + changelogs per feature.

## Public Projects

| Repo | Language |
|------|----------|
| [discord-roast](https://github.com/satset19/discord-roast) | JavaScript |
| [pengeluaran-api](https://github.com/satset19/pengeluaran-api) | TypeScript |
| [Photocam](https://github.com/satset19/Photocam) | TypeScript |
| [geotaging](https://github.com/satset19/geotaging) | TypeScript |
| [satriyo-portofolio](https://github.com/satset19/satriyo-portofolio) | TypeScript |

## Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=satset19&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_border=true)

---

[laksonosatriyo@gmail.com](mailto:laksonosatriyo@gmail.com)
