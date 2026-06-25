# ADR 001: Thin dispatcher plus subagent for code review

## Status

Accepted

## Context

Code review logic (conventions checklist, test analysis, output format) is large. The entry skill (symfony-code-review) also handles three diff scopes (staged, branch, PR).

Duplicating review logic in each scope leads to drift.

## Decision

- **symfony-code-review** — thin dispatcher: resolve diff, call subagent, relay report
- **symfony-code-reviewer** — holds all review knowledge and output template

Three forms differ only in which diff they pass.

## Consequences

- Convention changes: edit one agent file
- Dispatcher stays small and stable
- Subagent can be invoked multiple times per context for deep reviews
