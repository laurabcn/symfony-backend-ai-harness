<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: review-tests
description: Run Codeception tests, diagnose failures, fix broken tests or source code, and re-run until all pass. Understands DDD/CQRS test structure, Object Mothers, and Codeception patterns. Triggers like "corre els tests", "run tests", "passa els tests", "arregla els tests que fallen", "fix failing tests".
argument-hint: "[test file, suite, or context - defaults to full test suite]"
allowed-tools: Bash, Read, Write, Edit, Glob, Grep
---

# Review & Fix Codeception Tests

Run tests, diagnose failures, apply fixes, and re-run until all pass. Iterate up to 5 times.

## Parameters

- `$ARGUMENTS`: Optional test scope:
  - Specific file: `tests/Unit/Order/Domain/OrderTest.php`
  - Context directory: `tests/Unit/Order`
  - Suite name: `unit`, `functional`, `acceptance`
  - Empty: runs the full test suite

## Workflow

Execute the following loop (max 5 iterations):

### 1. Determine the test command

Resolve the test scope from `$ARGUMENTS`:

- **Specific file:** `vendor/bin/codecept run <suite> <file>` — infer suite from path (`tests/Unit/` → `unit`, `tests/Functional/` → `functional`)
- **Directory:** `vendor/bin/codecept run <suite> --path <dir>`
- **Suite name:** `vendor/bin/codecept run <suite>`
- **Empty:** `vendor/bin/codecept run`

If the project has a `Makefile` with a `test` target, prefer it — but always fall back to `vendor/bin/codecept run` if uncertain.

### 2. Run the tests
---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
