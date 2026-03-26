# Tech Stack — AIPulse (Draft)

## MVP Goals
- Fast internal deployment
- Simple data ingestion (manual + CSV) → later automated connectors
- Clear dashboard + use‑case registry + governance
- Agentic reporting pipeline

## Recommended Stack (Phase 1)
**Frontend:**
- Next.js + Tailwind (fast UI, OSS friendly)

**Backend / API:**
- FastAPI or Node.js (NestJS) — choose based on team preference

**Data & Storage:**
- Postgres (core app data)
- Redis (queues, caching)
- Object storage (reports/assets)

**Analytics / Metrics:**
- PostHog or Metabase for quick dashboards
- OpenTelemetry for agent/tool telemetry (optional)

**Agentic Ops:**
- Background jobs (Celery/RQ or BullMQ)
- LLM orchestration (Langfuse/LangSmith optional)

**Auth & Governance:**
- Role‑based access (RBAC)
- Audit logs from day 1

## Phase 2–3 Additions
- Connectors: Jira, GitHub, Slack, MS Teams, Copilot, Gemini, ChatGPT Enterprise
- Policy engine: OPA / Open Policy Agent
- Governance workflows: approvals + risk register
- Integrations with data governance tools (OpenMetadata)

## Why this stack
- OSS‑friendly
- Low‑ops for internal MVP
- Easy to extend for OSS community
