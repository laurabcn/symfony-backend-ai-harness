<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: fix-flaky-test
description: Diagnose and fix a flaky Codeception/PHPUnit test — reproduce by looping, pin mechanism (shared DB state, ordering, time, async races, Object Mother randomness), apply smallest fix, prove stability over N runs. Never masks flake (no skip/retry/timeout-bump). Triggers like "arregla el test flaky", "fix flaky test", "test intermitente".
argument-hint: "[test path or Class::method] [optional CI output]"
allowed-tools: Bash, Read, Grep, Glob, Edit, AskUserQuestion, Skill
---

# fix-flaky-test

Makes an intermittently-failing test **reliable by fixing root cause** — never hiding it. Win condition: same test green every time, mechanism understood.

## Arguments

- `$1`: test path, `Class::method`, or CI failure description
- `$2`: pasted CI output

## Hard rules

- **Never** skip, retry wrapper, sole sleep bump, delete test, weaken assertion
---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
