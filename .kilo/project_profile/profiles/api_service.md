# API Service Profile

Use this profile for backend APIs, SaaS services, worker services, and microservices.

## Common Context

Read:

- route/controller files
- service layer
- validation schema
- database model or repository
- auth middleware if relevant
- tests near the endpoint

## Common Validation

```bash
npm run typecheck
npm run lint
npm run test
npm run build
```

## Review Focus

- request validation
- auth and permission boundaries
- database writes are intentional
- errors are safe and useful
- public API types remain stable
- migrations are documented when data shape changes
