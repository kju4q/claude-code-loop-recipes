# Review and Merge

Review a PR and prepare it for merge with verification.

## Goal
PR reviewed, all issues addressed, tests green, and ready for you to merge.

## How to Run

**Option A (Quick):** Paste this directly:

```
/goal Review PR #456. Run tests, check for common issues, address feedback, and prepare the PR for merge. Use a verifier agent before finishing. Stop when the PR is ready for you to merge.
```

**Option B (Reusable):** Save the goal above as a custom command called `/review-and-merge`, then run:

```
/loop 15m /review-and-merge 456
```

## Important
The loop prepares the PR. **You** do the final merge or approval. Claude Code cannot autonomously merge PRs.