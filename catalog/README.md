# Skill Catalog

One-page summaries. Full operational prompts are private; see `preview/` for watermarked excerpts.

## symfony-code-review

**Category:** Quality check  
**Problem:** Inconsistent manual reviews miss DDD violations and test gaps.  
**Pattern:** Thin dispatcher → `symfony-code-reviewer` subagent (3 diff scopes).  
**Output:** Verdict + Blocking + Tests + Conventions report.  
**Preview:** [SKILL.md excerpt](../preview/.cursor/skills/symfony-code-review/SKILL.md)

## create-feature-spec

**Category:** Workflow  
**Problem:** Design decisions live in issue comments, lost at implementation time.  
**Pattern:** Epic issues → `docs/specs/<slug>-spec.md` with Invariants vs Approach per task.  
**Preview:** [SKILL.md excerpt](../preview/.cursor/skills/create-feature-spec/SKILL.md) · [ADR 002](../docs/adrs/002-invariants-vs-approach-specs.md)

## validate-pr

**Category:** Workflow  
**Problem:** PRs merge without verifying all acceptance criteria.  
**Pattern:** Diff vs issue + optional spec file; invariants are hard gates, approach is flexible.  
**Preview:** [SKILL.md excerpt](../preview/.cursor/skills/validate-pr/SKILL.md)

## fix-flaky-test

**Category:** Incident  
**Problem:** Intermittent CI failures erode trust; masking makes it worse.  
**Pattern:** Reproduce loops → root cause → 15x stability proof before done.  
**Preview:** [SKILL.md excerpt](../preview/.cursor/skills/fix-flaky-test/SKILL.md)

See [README](../README.md) for the full table.
