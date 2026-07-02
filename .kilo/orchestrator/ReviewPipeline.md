# Review Pipeline

## Review Order

```text
Scope Review
  -> Architecture Review
    -> User Flow Review
      -> API Quality Review when needed
        -> Test Review
          -> Documentation Review
            -> Guardian Pass
              -> PR Readiness Review
```

## Scope Review

- one task only
- no unrelated refactor
- no unrelated files

## Architecture Review

- no duplicate system
- clear ownership
- existing patterns reused
- persistence impact identified

## User Flow Review

For user-facing features:

- feature is reachable from the real app flow
- UI calls intended action
- input bounds are enforced in code

## API Quality Review

Use when public types, helpers, data modules, store actions, or indexes change.

- strongest available types
- no unnecessary `string` widening
- named return types where useful
- no unused imports
- test names match assertions

## Guardian Pass

Before PR creation, produce:

```text
Guardian Pass:
- Architecture:
- User flow:
- API quality:
- Persistence impact:
- Validation:
- Merge readiness:
```
