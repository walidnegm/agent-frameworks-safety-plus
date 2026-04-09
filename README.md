# Agent Risk, Safety & Security — Layered Defense Architecture

A 22-layer, 6-tier defense-in-depth framework for managing risk, safety, and security in production LLM agents and agentic systems.

Built from real production incidents — not theory.

## Architecture

```
Tier 1: Risk Assessment & Safety          (Layers 1-4)
Tier 2: Governance & Inventory            (Layers 5-7)
Tier 3: Runtime Controls                  (Layers 8-15)
Tier 4: Agentic Graph Execution           (Layers 16-17)
Tier 5: Infrastructure Security           (Layer 18)
Tier 6: Assurance & Operations            (Layers 19-22)
```

## Core premise

Every LLM call is both a trust boundary and a control boundary. Prompt-level controls are the weakest layer. Deterministic code controls — auth, schema enforcement, output validation, execution verification — are the real defense.

## [Read the full document](agent-risk-safety-security.md)

---

*Built by the Bot0 team.*
