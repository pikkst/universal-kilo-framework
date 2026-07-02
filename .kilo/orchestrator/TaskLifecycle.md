# Task Lifecycle

## Standard Flow

```text
Receive task
  -> Read .kilo/README.md and SYSTEM_MAP.md
    -> Run Context Engine
      -> Freeze task decision
        -> Build Execution Plan
          -> Implement
            -> Validate
              -> Review
                -> Produce Guardian Pass
                  -> Commit / PR / Final response
```

## Branch Rule

For repositories using Git:

- create a new branch per task
- do not work directly on main/master
- commit focused changes only
- open one PR per task

## Scope Rule

Do only the requested task.

Move extra improvements to follow-up notes.
