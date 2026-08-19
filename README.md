# 01 — Executive / Strategy

> Part of the **Hermes Organizational Decision System**. This repo is the
> **Executive / Strategy** line. It references the shared ontology in
> [`00-kojiki-ontology`](https://github.com/hermes-ios/00-kojiki-ontology) for the
> canonical schemas, taxonomy, decision-rights, and handoff standards.

## Primary question
> Where should we go?

## Purpose
Strategic direction, portfolio priorities, resource allocation, strategic initiatives, and scenario choices.

## Sub-functions
Corporate Strategy, Strategic Planning, Market Intelligence, Competitive Intelligence, Portfolio Strategy, Resource Allocation, Strategic Initiatives, Scenario Planning

## Typical roles
CEO, Chief Strategy Officer, VP Strategy, Head of Strategy, Strategy Director, Strategic Planning Manager, Competitive Intelligence Manager, Strategy Analyst

## Inputs
Market/competitive intelligence; financial state; organizational capabilities; execution evidence.

## Outputs
Strategy, priorities, resource allocation decisions, strategic initiatives, strategic assumptions.

## Learning focus
Strategy assumptions; market turning points; competitive patterns; investment outcomes; opportunity costs; early indicators.

## Operating tree
```text
MARKET / ENVIRONMENT →
    SIGNAL →
    INTERPRETATION →
    OPPORTUNITY / THREAT →
    STRATEGIC DIAGNOSIS →
    STRATEGIC THESIS →
    OPTIONS →
    RESOURCE ALLOCATION →
    EXECUTION →
    RESULT →
    STRATEGIC LEARNING
```

## Decision states
```text
UNKNOWN → OBSERVED → INVESTIGATING → VALIDATED → STRATEGIC PRIORITY → EXECUTING → SCALING → MATURE → EXIT / ABANDON
```

## Decision outputs
`Invest · Don't Invest · Accelerate · Maintain · Investigate · Exit`

## Critical prompts (what this function thinks about)
> What changed?
> Why does this matter?
> Is this signal or noise?
> What opportunity does this create?
> What threat does this create?
> What happens if we do nothing?
> What is our structural advantage?
> What capabilities do we possess?
> What capabilities are missing?
> What are the available strategic options?
> What is the opportunity cost of each?
> What assumptions does this strategy depend on?
> What evidence would invalidate our thesis?
> Where should resources move?
> What should we stop?
> What should we start?
> What should we double down on?
> What is the next strategic decision?

## Canonical record schema (docx Learning Ledger + Decision Object Fields)
Every decision in this line is recorded as:
- a **Decision Object** (docx S9) — see `schema/decision-object.json`
- a **Learning Ledger** entry (docx S7) — see `schema/learning-ledger.json`

and the agent must run the **Orientation Protocol** first (see `AGENT.md`).

## How to use
1. Read `AGENT.md` — the first-run Orientation Protocol.
2. Read `SCHEMA.md` — how this line maps to the universal schema.
3. Read `data/01-executive-strategy.json` — the machine-readable spec.
4. See `data/example.json` — one fully worked decision (Decision Object + Ledger).
5. Use `decision-graph.mmd` — agent-decodable operating tree + state model.
6. Validate new records: `python3 tools/validate.py data/<name>.json`
