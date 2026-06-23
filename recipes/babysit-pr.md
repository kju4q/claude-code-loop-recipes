# Babysit PRs

Automatically handle code review comments, rebase, and move PRs forward.

## Goal
All review comments addressed + tests passing + PR ready for merge or merge conflicts resolved.

## How to Run

**Option A (Quick):** Paste this directly:

```
/goal Address all review comments on PR #123, rebase if needed, ensure tests pass, and update the PR. Stop when the PR is ready for final review.
```

**Option B (Reusable):** Save the goal above as a custom command called `/babysit-pr`, then run:

```
/loop 10m /babysit-pr 123
```

## Tips
- Add a verifier step that runs tests after changes.
- Use browser control if the PR has UI changes.
- Set a max iteration count to avoid runaway loops.
- You perform the final merge — the loop prepares the PR.