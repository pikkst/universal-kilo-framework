# Context Budget

## Purpose

Control token usage and avoid unnecessary file loading.

## Initial Limits

- Minimal task: up to 3 files
- Standard task: up to 8 files
- Deep task: up to 15 files

## Expansion Rule

Load one additional file only when it reduces implementation risk.

Before loading more, state:

```text
Known context:
Missing information:
Why one more file is needed:
Expected file:
```

## Stop Rule

Stop when implementation path, owner, likely files, validation, and docs are clear.
