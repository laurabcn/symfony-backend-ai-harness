<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: write-object-mother
description: Generate an Object Mother for an aggregate or value object following vault conventions — create(), random(), custom(?field=null) — placed in tests/_support/Helper/<Context>/. Triggers like "crea un object mother", "genera l'object mother", "write object mother", "nou mother".
argument-hint: "[path to aggregate or VO class, e.g. src/Context/Order/Domain/Aggregate/Order.php]"
allowed-tools: Bash, Read, Write, Grep, Glob, AskUserQuestion
---

# write-object-mother

Generate a complete Object Mother for an aggregate or value object. Reads the target class to derive all fields, types, and constraints.

## Arguments

- `$1`: Path to the class (e.g. `src/Context/Order/Domain/Aggregate/Order.php`). If omitted, ask.

## Step 1 — Read the target class

Read the class file. Extract:
- **Namespace and class name**
- **Bounded context** — from the namespace path (e.g. `App\Context\Order\...` → context = `Order`)
- **Constructor or `create()` factory** — list all parameters with types
- **Value objects used** — note which fields have VOs so the Mother uses primitives

If the class has no `create()` factory and no public constructor, warn the user and ask how to instantiate it.

## Step 2 — Determine output path

**Location:** `tests/_support/Helper/<Context>/<ClassName>Mother.php`

Check if a Mother already exists at that path — if so, ask whether to overwrite or extend.
---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
