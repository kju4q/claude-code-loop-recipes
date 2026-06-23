# Fix Failing Tests

Iteratively fix failing tests one by one with verification.

## Goal
All tests passing with no regressions introduced.

## How to Run

This works best as a **run-until-done** task using `/goal` (not an interval loop):

```
/goal Fix all failing tests in the current branch. Run the test suite after each fix. Only move to the next failing test after the current one passes. Stop when the full test suite is green.
```

## Tips
- Always run the full test suite after fixes.
- Use a separate verifier agent.
- Add a cost or iteration cap if the test suite is large.
- Let the agent self-pace — no need for a timed `/loop`.