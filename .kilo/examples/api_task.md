# Example: API Feature Task

## Task

Add a customer search endpoint.

## Context Plan

- route/controller
- service layer
- validation schema
- repository/model
- auth middleware if relevant
- endpoint tests

## Execution Plan

```text
Task summary: Add customer search endpoint
Task type: feature
Risk level: medium
Context level: standard
In scope: route, validation, service, tests
Out of scope: auth redesign, unrelated database changes
Validation: typecheck, lint, tests, build
```

## Quality Gate Focus

- request validation exists
- permission boundary is clear
- query is safe and bounded
- response type is stable
- tests cover valid and invalid input
