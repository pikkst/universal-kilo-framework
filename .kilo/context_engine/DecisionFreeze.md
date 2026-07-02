# Decision Freeze

## Purpose

Prevent repeated analysis loops.

## Freeze Point

After task type, systems, risk level, context level, and likely files are identified, freeze the decision.

## Reopen Only If

- a source file contradicts the plan
- validation reveals a hidden dependency
- task instructions conflict
- scope expands unexpectedly
- a blocker appears

## Not A Reason To Reopen

- uncertainty without new evidence
- curiosity about unrelated files
- desire to refactor more
- repeated reading of the same instruction

## Required Behavior

After freeze:

1. Move to Orchestrator.
2. Build the execution plan.
3. Implement the smallest safe change.
