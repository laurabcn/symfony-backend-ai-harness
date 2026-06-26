<!--
  PREVIEW ONLY — © Laura Riera
  Generated from private repository. Not licensed for redistribution.
  Full implementation: private. Contact for demo.
-->

> **Portfolio preview** — excerpt only. Remaining content is redacted.

---
name: sync-domain-models
description: Refresh the domain-models-reference skill to match current domain code. Detects which aggregates, repositories or search criteria changed since the reference was last updated, re-reads only those files, and rewrites affected sections. Triggers like "sync domain models", "actualiza domain-models-reference", "sincroniza el skill de modelos".
allowed-tools: Bash, Read, Grep, Glob, Write, Edit
---

# sync-domain-models

On-demand maintenance for `.cursor/skills/domain-models-reference/SKILL.md`. Goal: sync with code **surgically** — touch only sections whose underlying domain changed.

## Procedure

1. **Read the reference skill** at `.cursor/skills/domain-models-reference/SKILL.md`. Note documented domains (`## <Domain>` sections) and cited paths.

2. **Find baseline commit** — last commit that touched the reference skill:
   ```bash
---

<!-- REDACTED: remainder omitted -->

[Content redacted — full version available in private repository]

*This preview shows structure and approach, not operational instructions.*
