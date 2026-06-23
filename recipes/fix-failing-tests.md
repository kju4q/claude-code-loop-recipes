# Fix Failing Tests

Iteratively fix failing tests one by one with verification.

## Goal
All tests passing with no regressions introduced.

## How to Run

```
/goal Fix all failing tests in the current branch. Run the test suite after each fix. Only move to the next failing test after the current one passes. Stop when the full test suite is green.
```

## Recommended Schedule

```
/loop 5m fix-failing-tests
```

## Guardrails
- Always run the full test suite after fixes.
- Use a separate verifier agent.
- Add a cost or iteration cap if the test suite is large.