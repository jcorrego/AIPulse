# Market Landscape (Deep) — AIPulse

## Scope of analysis
AI adoption analytics, AI governance platforms, and adjacent observability/metadata tools.

---

## 1) Adoption & Impact Analytics
### Worklytics (MeasureAI)
- **Positioning:** AI adoption dashboard across tools (Copilot, Gemini, ChatGPT, Zoom/Slack, etc.).
- **Key features:** multi‑tool usage aggregation, team/role adoption trends, benchmarks, exportable datasets, ROI linkage.
- **Signals:** usage metadata only (privacy‑first, no prompt content).
- **Deployment:** SaaS + API integrations; “first metrics in ~1 week” (vendor claim).
- **Why it matters:** strong adoption + ROI analytics; less on governance/enablement workflows.
- Source: https://www.worklytics.co/measureai

### Jellyfish — AI Impact
- **Positioning:** AI ROI for engineering teams; SDLC impact analytics.
- **Key features:** unified metrics across dev tooling, comparisons across AI assistants, outcome‑linked analytics.
- **Integrations:** Jira/GitHub/DevOps + assistants (Copilot, Gemini, Cursor, etc.).
- **Deployment:** enterprise SaaS, heavier integrations.
- **Why it matters:** strong for engineering ROI, weaker on enablement/governance.
- Source: https://jellyfish.co/platform/jellyfish-ai-impact/

---

## 2) AI Governance Platforms
### Credo AI
- **Positioning:** enterprise AI governance for agents, models, apps.
- **Key features:** AI registry, risk management, policy engine, compliance packs (EU AI Act/NIST), runtime monitoring.
- **Deployment:** enterprise, large‑scale; broad stakeholder model (legal/compliance/infosec/product).
- **Why it matters:** very strong governance; heavy and likely over‑scoped for AIPulse MVP.
- Source: https://www.credo.ai/product

### Enzai
- **Positioning:** AI governance & enablement platform.
- **Key features:** intake, registry, compliance, monitoring, third‑party AI risk mgmt, legal‑compliance focus.
- **Deployment:** enterprise SaaS with many integrations; governance‑first.
- **Why it matters:** governance depth, but heavy infrastructure/compliance focus.
- Source: https://www.enz.ai/

---

## 3) Adjacent — Metadata / Data Governance
### OpenMetadata
- **Positioning:** open‑source metadata platform for data discovery, observability, and governance.
- **Key features:** metadata graph, data asset inventory, many connectors.
- **Why it matters:** not AI‑adoption focused but could supply inventory layer for AI governance.
- Source: https://open-metadata.org/

---

## 4) Adjacent — LLM Observability (Not direct competitors)
- **Langfuse / LangSmith / Langtrace**: tracing, evals, telemetry for LLM apps.
- **Why it matters:** complementary to AIPulse for deeper model/prompt analytics.

---

## Summary: What AIPulse should NOT include (to keep deployment simple)
- Full enterprise compliance pack management (EU AI Act/NIST) → **out of MVP**.
- Deep model‑level risk monitoring + runtime enforcement → **out of MVP**.
- Heavy cross‑system auto‑discovery of all AI assets → **out of MVP**.

## What AIPulse should include (minimal, differentiating)
- Use‑case registry + lifecycle (propose → approve → measure → decide).
- Adoption metrics + ROI with **review cost / rework**.
- Enablement layer (coaching, progress, playbooks).
- Agentic ops: automated monthly report + alerts.

---

## Recommendation
Start with **adoption + enablement + lightweight governance**. Integrations can be manual/CSV in MVP, then expand based on demand.
