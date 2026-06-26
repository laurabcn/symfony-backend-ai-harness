<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: atomize-feature
description: Decompose a GitHub epic or milestone into atomic, non-overlapping, dependency-ordered work-packages (~3 SP each) with adversarial critique (coverage, overlap, dependencies, sizing). Read-only on issues — returns a plan for create-feature-spec and create-github-issue. Triggers like "atomiza la feature", "atomize epic", "descompón el epic PROJ-123", "break down this epic".
argument-hint: "[epic issue number or URL]"
allowed-tools: Bash, Read, Grep, Glob, Agent, AskUserQuestion
---

# atomize-feature

Turns a refined **epic** (GitHub issue with sub-issues or linked tasks) into a **reviewed work-breakdown** ready for `create-feature-spec` and issue creation. **Read-only** on GitHub — returns a plan; the developer creates issues and the spec.

## Arguments

- `$1`: epic issue number or GitHub URL. If omitted, ask.

## Phases

### 1. Understand

Fetch the epic via `gh issue view` (title, body, comments, labels, milestone). List existing child issues / linked tasks so the breakdown does **not** duplicate them.

Map the **code surface** the epic will touch:
- Read `domain-models-reference` skill + `Grep`/`Glob` on `src/Context/`
- Locate aggregates, command/query handlers, `On<Event>...Listener`, controllers, routes, Object Mothers / test paths
- Note cross-cutting risks: event-driven sync, find*/search*, strict_types, authorization-in-handler

---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
