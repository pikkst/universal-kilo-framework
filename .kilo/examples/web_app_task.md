# Example: Web App Feature Task

## Task

Add a settings page with profile preferences.

## Context Plan

- app router
- settings route or layout
- user store
- API client for profile update
- related tests

## Execution Plan

```text
Task summary: Add settings page
Task type: feature
Risk level: medium
Context level: standard
In scope: route, UI form, save action, tests
Out of scope: auth redesign, database migration unless required
Validation: typecheck, lint, tests, build
```

## Quality Gate Focus

- page is reachable from navigation
- submit action calls intended API/store
- form validation exists
- error and loading states exist
