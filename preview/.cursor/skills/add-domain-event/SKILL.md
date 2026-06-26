<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: add-domain-event
description: Scaffold a domain event class and its Application listener following DDD/hexagonal conventions — event in Domain/Event, listener in Application/Listener, record() call on the aggregate. Triggers like "afegeix un domain event", "crea un event de domini", "add domain event", "nou event".
argument-hint: "[ContextName] [EventName, e.g. OrderPlaced]"
allowed-tools: Bash, Read, Write, Edit, Grep, Glob, AskUserQuestion
---

# add-domain-event

Scaffold a domain event + its listener from a single command. Does not implement business logic — leaves TODOs where domain decisions are needed.

## Arguments

- `$1`: Bounded context name (e.g. `Order`). If omitted, ask.
- `$2`: Event name in PascalCase past tense (e.g. `OrderPlaced`, `CustomerEmailChanged`). If omitted, ask.

## Step 1 — Locate context

Find `src/Context/<ContextName>/` to confirm it exists. If not, warn and stop.

Identify the aggregate root class in `src/Context/<ContextName>/Domain/` — look for the class matching `<ContextName>.php` or ask the user which aggregate emits this event.

## Step 2 — Create the domain event class

**Path:** `src/Context/<ContextName>/Domain/Event/<EventName>.php`

```php
<?php
---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
