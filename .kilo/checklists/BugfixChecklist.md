# Bugfix Checklist

## Understanding

- [ ] Bug is described clearly.
- [ ] Expected behavior is known.
- [ ] Actual behavior is known.
- [ ] Owning module is identified.

## Fix Scope

- [ ] Fix changes the smallest safe area.
- [ ] Unrelated cleanup is not included.
- [ ] Validation is not weakened to hide the bug.

## Regression Protection

- [ ] Regression test was added or updated when practical.
- [ ] Existing tests still describe meaningful behavior.
- [ ] The cause and fix are documented in PR notes or report.
