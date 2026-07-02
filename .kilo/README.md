# Universal `.kilo` Framework

This folder is the starting point for AI coding agents working inside a project.

It is intentionally project-agnostic. Customize `project_profile/PROJECT_PROFILE.md` for each project.

## Start Here

Read these first:

1. `.kilo/README.md`
2. `.kilo/SYSTEM_MAP.md`
3. `.kilo/project_profile/PROJECT_PROFILE.md`
4. `.kilo/context_engine/TaskAnalyzer.md`
5. `.kilo/orchestrator/TaskLifecycle.md`

Do not load the full `.kilo` folder by default.

## Main Workflow

```text
Task
  -> Context Engine
    -> Orchestrator
      -> Implementation
        -> Review Checklists
          -> Guardian Pass
            -> PR or Final Delivery
```

## Universal Rules

- One task equals one branch and one PR when Git is available.
- Do not work directly on `main` or `master` unless explicitly requested.
- Select the smallest useful context.
- Do not create duplicate systems.
- Prefer existing patterns before adding new architecture.
- Be honest about validation that was not run.
- For user-facing work, verify the feature is reachable from the real app flow.
- For public APIs, preserve strong types and named return types.
- Produce a visible Guardian Pass before PR creation.

## Folder Map

```text
context_engine/   context selection and token efficiency
orchestrator/     task lifecycle and execution process
checklists/       practical review criteria
guardian/         final quality gates
rules/            mandatory universal rules
prompts/          reusable task prompts
templates/        report, PR, ADR, and task templates
examples/         example workflows for common project types
project_profile/  project-specific customization files
```
