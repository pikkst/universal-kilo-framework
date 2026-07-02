# Kilo System Map

This file explains how the universal `.kilo` framework works.

## Canonical Flow

```text
User Task
  -> Context Engine
    -> Orchestrator
      -> Implementation
        -> Checklists
          -> Guardian
            -> Visible Guardian Pass
              -> Commit / PR / Final Response
```

## Layer Ownership

### Context Engine

Owns:

- task classification
- context selection
- token budget
- stop rules
- decision freeze

Does not own:

- implementation
- review policy
- PR creation

### Orchestrator

Owns:

- task lifecycle
- agent role selection
- execution plan
- review pipeline
- completion criteria

Does not own:

- project-specific business rules
- full-codebase scanning by default

### Checklists

Own:

- practical review criteria
- feature quality
- API quality
- testing quality
- documentation quality
- PR readiness

### Guardian

Owns:

- final quality gate
- blocker detection
- visible Guardian Pass

## No Duplication Rule

If new guidance belongs to an existing layer, update that layer instead of creating a new one.

Examples:

- Context selection -> `context_engine/`
- Task lifecycle -> `orchestrator/`
- Review criteria -> `checklists/`
- Final blocker gate -> `guardian/`
- Project-specific rules -> `project_profile/`

## Token Rule

Start with index and map files.

Load deeper files only when needed.

Never load the full project or full `.kilo` folder by default.
