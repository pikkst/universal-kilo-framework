# Task Analyzer

## Purpose

Classify the task before loading code or documents.

## Required Output

```text
Task type:
Primary system:
Secondary systems:
Risk level:
Context level:
Likely files:
Validation needed:
Docs needed:
```

## Task Types

- feature
- bugfix
- refactor
- documentation
- architecture
- test-only
- release
- research
- maintenance

## Risk Levels

### Low

Small isolated change.

### Medium

Touches multiple files or user-facing behavior.

### High

Touches architecture, persistence, security, auth, money, data migration, or critical flows.

## Context Levels

### Minimal

1–3 files.

### Standard

3–8 files.

### Deep

8–15 files plus key docs.

## Rule

Classify once, then freeze the decision unless new evidence appears.
