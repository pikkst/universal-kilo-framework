# Game Project Profile

Use this profile for browser games, desktop games, game tools, simulations, and game systems.

## Common Context

Read:

- game state owner
- system module being changed
- related data definitions
- save/load code if persistent state changes
- UI screen if player-facing
- tests for affected system

## Common Validation

```bash
npm run typecheck
npm run lint
npm run test
npm run build
```

## Review Focus

- player action is reachable
- deterministic generation uses fixed inputs in tests
- save/load impact is documented
- UI does not own core game rules
- data modules remain reusable
- simulation cost is reasonable
