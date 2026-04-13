# Agent Risk, Safety & Security — Layered Defense Architecture

A **23-layer, 6-tier defense-in-depth framework** for building and operating safe, secure, and governable LLM applications and agentic systems in production.

Grounded in real production incidents, implementation failures, and practical control design — not just theory.

## Architecture

| Tier | Name | Layers | Scope |
|------|------|--------|-------|
| 1 | Risk Assessment & Safety | 1–4 | Understand what can go wrong — risk taxonomy, safety evaluation, reasoning and reliability risks. Drives everything below. |
| 2 | Governance & Inventory | 5–8 | Know your trust surface. Govern prompts, models, settings, knowledge sources, grounding strategy, error policy, identity, and change authority. |
| 3 | Runtime Controls | 9–16 | Enforce security at every stage of the LLM call lifecycle, including modality transitions. |
| 4 | Agentic Graph Execution | 17–18 | Node-level security and safety for graph-based agent orchestration. |
| 5 | Infrastructure Security | 19 | Network, secrets, encryption, data retention, tenant isolation, observability. |
| 6 | Assurance & Operations | 20–23 | Verify, monitor, detect drift, enforce via guardian agents, respond, and prioritize. |


## Core Premise

Every LLM call is both a **trust boundary** and a **control boundary**. Prompt-level controls help, but they are the weakest layer. Real resilience comes from deterministic controls such as authorization, schema enforcement, context integrity, output validation, execution verification, and operational assurance.


## [Read the full document](agent-risk-safety-security.md)


*Built by the Bot0 team.*
