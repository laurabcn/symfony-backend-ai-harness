<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: audit-conventions
description: Audit a bounded context or path against Symfony DDD conventions — strict_types, Object Mothers, find* vs search*, event assertions in tests, event-driven sync, authorization-in-handler — and produce an epic-style remediation plan with work-packages (Invariants/Approach). Read-only. Triggers like "audita convenciones", "audit conventions Order", "audit src/Context/Order".
argument-hint: "[context name or path e.g. Order or src/Context/Order]"
allowed-tools: Bash, Read, Grep, Glob, Agent, AskUserQuestion
---

# audit-conventions

Audits an existing **bounded context** (or path) against high-value static agreements from `artifacts/conventions/SYMFONY_DDD_CQRS.md` and `.cursor/rules/symfony-ddd-conventions.mdc`. Returns a **remediation plan** — not fixes.

## Arguments

- `$1`: context name (`Order`) or path (`src/Context/Order`). If omitted, ask.

Normalize: bare name → `src/Context/<Name>`; path with `/` → use as-is.

## Agreements to audit

Each agreement gets a read-only pass scoped to `$1`. Every violation cites `file:line`.

---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
