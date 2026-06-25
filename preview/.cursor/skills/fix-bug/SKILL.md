<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: fix-bug
description: Diagnose and fix a bug from a GitHub issue in a Symfony event-driven backend. Gathers context (issue, logs, traces), pins root cause (handlers, listeners, aggregates), proposes fixes, and in fix mode implements with regression test after confirmation. Investigate-only mode stops at diagnosis. Triggers like "arregla el bug", "diagnostica el error", "fix bug PROJ-XXXX", "--investigate".
argument-hint: "[PROJ-XXXX] [--investigate] [optional pasted log/trace]"
allowed-tools: Bash, Read, Grep, Glob, Edit, Write, Agent, AskUserQuestion, Skill
---

# fix-bug

Takes a bug from issue to verified fix: read ticket, gather signals, **pin root cause before code**, propose options, implement after confirmation.

Composes: diagnosis → branch → fix → test → handoff to `symfony-code-review` and `pr-description`.

## Mode

- **fix** (default) — steps 1–9
- **investigate** — steps 1–5 only, stop at diagnosis. Trigger: `--investigate`, "solo investiga"

## Arguments

---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
