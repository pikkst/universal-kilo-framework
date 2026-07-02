# Execution Plan

## Required Plan

```text
Task summary:
Task type:
Risk level:
Context level:
Files inspected:
Files likely to change:
In scope:
Out of scope:
Validation plan:
Docs plan:
Branch name:
```

## Implementation Order

```text
Inspect existing implementation
  -> Make smallest safe change
    -> Add or update tests
      -> Update docs if needed
        -> Run validation
          -> Produce visible Guardian Pass
            -> Prepare PR notes
              -> Create PR or final response
```

## Stop Conditions

Stop and re-plan when:

- ownership is unclear
- scope expands
- validation fails unexpectedly
- task touches more systems than expected
- a blocker appears
