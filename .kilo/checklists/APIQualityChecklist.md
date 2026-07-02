# API Quality Checklist

Use when changing exported types, public helpers, shared data modules, store actions, SDKs, or module indexes.

## Type Safety

- [ ] Public constants use the strongest available key type.
- [ ] Public parameters use domain types instead of broad strings when possible.
- [ ] Public APIs avoid unnecessary `any`.
- [ ] Casts are removed when stronger types make them unnecessary.

## Return Types

- [ ] Public helpers use named or reusable return types when practical.
- [ ] Long anonymous return types are avoided.
- [ ] Related helpers use consistent return shapes.

## Module Boundaries

- [ ] Data modules do not import heavy runtime logic.
- [ ] Core logic does not expose unrelated data.
- [ ] Shared data has one source of truth.

## Imports and Exports

- [ ] Unused imports are removed.
- [ ] Public exports are intentional.
- [ ] Ownership of exported types is clear.

## Tests

- [ ] Test names match actual assertions.
- [ ] Assertions verify behavior, not only existence.
- [ ] Invalid lookups or boundary cases are covered when practical.
