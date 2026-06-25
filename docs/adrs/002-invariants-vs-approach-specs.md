# ADR 002: Invariants vs Approach in feature specs

## Status

Accepted

## Context

Per-task specs must guide implementation and PR validation without over-constraining solutions.

## Decision

Each task section in `docs/specs/<slug>-spec.md` splits:

- **Invariants** — outcomes that MUST hold. `validate-pr` treats violations as misses.
- **Approach** — the current agreed path. Alternative implementations that satisfy invariants are acceptable.

Cross-cutting agreements live in a shared epic-level block.

## Consequences

- validate-pr can distinguish "wrong outcome" from "different but valid implementation"
- Specs capture design decisions from issue comments, not just AC text
- create-feature-spec and validate-pr must stay aligned on this vocabulary
