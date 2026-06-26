<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: create-endpoint
description: Generate a Symfony DDD/CQRS HTTP endpoint skeleton — Query or Command, Handler, Controller, route, service tag, and unit/functional test — following hexagonal layering. Use when adding a new API endpoint to a bounded context. Triggers like "crea el endpoint", "create endpoint", "genera GET /orders/{id}".
argument-hint: "[context] [query-or-command name] [HTTP method] [path] — or path to endpoint.json"
allowed-tools: Bash, Read, Write, Edit, Glob, Grep, AskUserQuestion
---

# create-endpoint

Generates a **complete endpoint skeleton** in an existing Symfony DDD project. Business logic in the handler stays as TODO — the skill wires structure, config, and tests.

## Arguments

**Option A — inline:**
- `$1`: bounded context name (e.g. `Order`)
- `$2`: operation name PascalCase (e.g. `GetOrderById`)
- `$3`: HTTP method (`GET` → query, `POST`/`PUT`/`PATCH`/`DELETE` → command)
- `$4`: path (e.g. `/orders/{orderId}`)

**Option B — config file:**
- `$1`: path to `endpoint.json` (see schema below)

If ambiguous, ask via AskUserQuestion.

## Before generating

---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
