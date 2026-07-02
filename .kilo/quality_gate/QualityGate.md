# Quality Gate

## Required Output

Before PR creation or final delivery, produce:

```text
Quality Gate:
- Architecture:
- User flow:
- API quality:
- Persistence impact:
- Validation:
- Documentation:
- Delivery readiness:
```

## Review Areas

### Architecture

- clear owner
- no duplicate system
- existing patterns reused

### User Flow

- feature is reachable
- action reaches intended logic
- inputs are validated in code

### API Quality

- strong public types
- named return types when useful
- unused imports removed

### Persistence Impact

- saved data changes are documented
- migrations or defaults are considered

### Validation

- relevant checks were run
- skipped checks are explained

### Delivery Readiness

- branch is focused
- docs are updated
- known limitations are listed
