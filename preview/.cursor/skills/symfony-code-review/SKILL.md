<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: symfony-code-review
description: Review pending Symfony backend changes against DDD/hexagonal conventions (PHPStan v2 max, CS Fixer, Object Mothers, strict_types, find*/search*, event-driven patterns) plus bugs, edge cases, and static test quality/coverage-gap analysis. Three forms by scope — staged/uncommitted, branch vs base, or GitHub PR — all delegating to the symfony-code-reviewer subagent. Read-only. Triggers like "revisa el código", "code review", "revisa la rama", "revisa la PR 123", "review changes before commit".
argument-hint: "[scope: empty=staged | 'branch' | base-branch | PR number/URL]"
allowed-tools: Bash, Read, Grep, Agent
---

# symfony-code-review

Runs a Symfony/DDD-aware code review of pending changes. It is a **thin dispatcher**: it resolves the diff for the chosen *form*, then hands that diff to the **`symfony-code-reviewer`** subagent, which holds all the review knowledge and returns the report. The subagent is the single source of truth — the three forms differ **only in which diff they feed it**.

Reads conventions from `.cursor/rules/symfony-ddd-conventions.mdc` and `artifacts/conventions/SYMFONY_DDD_CQRS.md`. **Read-only** — it never edits, commits, or posts anywhere.

---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
