# Example: Game Feature Task

## Task

Add a new player progression data module.

## Context Plan

- player state owner
- related data modules
- core progression logic
- UI if player-facing
- save/load code if persistent
- tests near the system

## Execution Plan

```text
Task summary: Add progression data module
Task type: feature / architecture
Risk level: medium
Context level: standard
In scope: data definitions, helpers, focused tests
Out of scope: full save rewrite, unrelated UI redesign
Validation: typecheck, lint, tests, build
```

## Quality Gate Focus

- data module has strong key types
- helpers have reusable return types
- game logic is not duplicated
- persistence impact is documented
- tests cover required entries and accessors
