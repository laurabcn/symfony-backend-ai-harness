# Symfony Backend AI Harness — Portfolio Preview

> **© Laura Riera** — This public repository contains **watermarked excerpts** of an AI development harness for Symfony/DDD backends. It demonstrates architecture and design decisions; **operational prompts are not fully published**.

Senior Backend Engineer specializing in **PHP/Symfony**, **DDD**, **hexagonal architecture**, **CQRS**, and **event-driven** systems.

## What this is

A documented AI harness that accelerates:

- Feature planning (specs with Invariants vs Approach)
- Code review against DDD conventions
- PR validation and description
- Bug diagnosis and flaky test fixes

The [private implementation](https://github.com/laurariera) powers day-to-day development. This repo shows **structure and decisions**, not copy-paste-ready prompts.

## Pipeline

See [docs/architecture/pipeline.md](docs/architecture/pipeline.md).

```
atomize → create-feature-spec → start-task → implement → symfony-code-review → validate-pr → pr-description
```

## Skill catalog (preview excerpts)

| Skill | Category | Preview |
|-------|----------|---------|
| symfony-code-review | Quality | [preview](preview/.cursor/skills/symfony-code-review/SKILL.md) |
| validate-pr | Workflow | [preview](preview/.cursor/skills/validate-pr/SKILL.md) |
| pr-description | Workflow | [preview](preview/.cursor/skills/pr-description/SKILL.md) |
| create-feature-spec | Workflow | [preview](preview/.cursor/skills/create-feature-spec/SKILL.md) |
| start-task | Workflow | [preview](preview/.cursor/skills/start-task/SKILL.md) |
| fix-bug | Incident | [preview](preview/.cursor/skills/fix-bug/SKILL.md) |
| fix-flaky-test | Incident | [preview](preview/.cursor/skills/fix-flaky-test/SKILL.md) |
| triage-pr-comments | Workflow | [preview](preview/.cursor/skills/triage-pr-comments/SKILL.md) |
| domain-models-reference | Reference | [preview](preview/.cursor/skills/domain-models-reference/SKILL.md) |

Agent: [symfony-code-reviewer](preview/.cursor/agents/symfony-code-reviewer.md) (excerpt)

## Architecture decisions

- [ADR 001: Thin dispatcher + subagent](docs/adrs/001-thin-dispatcher-plus-subagent.md)
- [ADR 002: Invariants vs Approach](docs/adrs/002-invariants-vs-approach-specs.md)
- [ADR 003: Skill categories](docs/adrs/003-skill-categories.md)

## Stack

PHP 8.3 · Symfony 6.4 · MongoDB · Kafka · AWS SQS · CQRS · PHPStan · Codeception · Cursor

## Important

- Files under `preview/` are **auto-generated excerpts** (~20% of content). See [PREVIEW_NOTICE.md](PREVIEW_NOTICE.md).
- Do **not** use `preview/` as installable Cursor skills — content is intentionally incomplete.
- Full demo available on request during interviews.

## Contact

Laura Riera — Backend Engineer (Symfony/DDD)
