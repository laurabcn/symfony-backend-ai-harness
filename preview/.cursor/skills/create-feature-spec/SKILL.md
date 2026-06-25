<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: create-feature-spec
description: From a GitHub epic/milestone or parent issue, read subtasks and design comments, review with the developer, and generate a per-task spec at docs/specs/<slug>-spec.md splitting Invariants from Approach — committed on a branch. Upstream of validate-pr and start-task. Triggers like "genera el spec", "crea el spec de l'epic", "create feature spec".
argument-hint: "[epic issue number or URL] [optional slug]"
allowed-tools: Bash, Read, Grep, Agent, AskUserQuestion, Write, Edit
---

# create-feature-spec

Turns a refined epic into a **per-task spec** the team commits and reuses. Each task section splits:

- **Invariants** — outcomes that MUST hold. Breaking one is a real gap.
- **Approach** — the agreed way. A PR satisfying invariants differently is fine.

Does **not** create issues — assumes tasks exist. Reads them, reviews with developer, writes spec.

## Arguments

- `$1`: epic issue number or GitHub URL. If omitted, ask.
- `$2` (optional): slug for filename, e.g. `order-migration`.
---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
