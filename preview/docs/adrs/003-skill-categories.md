# ADR 003: Skill categories

## Status

Accepted

## Context

Skills vary in size and invocation pattern. One-size-fits-all leads to bloated context or false auto-invocation.

## Decision

| Category | Pattern | Examples |
|----------|---------|----------|
| Workflow | Self-contained SKILL.md, procedural steps | pr-description, start-task, fix-bug |
| Quality | Dispatcher → subagent | symfony-code-review → symfony-code-reviewer |
| Reference | Static map, read on demand | domain-models-reference |
| Convention | Rule (.mdc) + extended doc | symfony-ddd-conventions + SYMFONY_DDD_CQRS.md |

Workflow skills that orchestrate user-visible actions should not auto-invoke without explicit trigger.

## Consequences

- Clear placement for new skills
- Review logic centralized in agents
- Large convention docs live outside SKILL.md (progressive disclosure)
