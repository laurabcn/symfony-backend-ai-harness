<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: refactor-to-value-object
description: Extract a primitive field into a Value Object — create the VO class in Domain/ValueObject, update the aggregate, handlers, and tests. Triggers like "extreu a value object", "crea un value object", "refactor to value object", "nou VO".
argument-hint: "[ContextName] [FieldName, e.g. Email] [primitive type: string|int|float]"
allowed-tools: Bash, Read, Write, Edit, Grep, Glob, AskUserQuestion
---

# refactor-to-value-object

Extract a primitive into a proper Value Object following DDD conventions. Updates the aggregate, all usages, and tests in one pass.

## Arguments

- `$1`: Bounded context name (e.g. `Order`). If omitted, ask.
- `$2`: VO name in PascalCase (e.g. `Email`, `OrderStatus`, `CustomerId`). If omitted, ask.
- `$3`: Underlying primitive type (`string`, `int`, `float`). If omitted, infer from current usages.

## Step 1 — Locate context and usages

1. Confirm `src/Context/<ContextName>/` exists.
2. Grep for current usages of the field as primitive — find aggregate property, constructor, getter, handlers, Object Mothers, tests.
3. Check `src/Context/<ContextName>/Domain/ValueObject/` for an existing `<FieldName>.php` — if it exists, warn and stop.

## Step 2 — Create the Value Object

**Path:** `src/Context/<ContextName>/Domain/ValueObject/<FieldName>.php`

Template for a simple string VO:

```php
<?php

---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
