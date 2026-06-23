# Nightly Cleanup

Run overnight to handle small maintenance tasks.

## Goal
Stale branches cleaned, old comments addressed, and repo health checks passed.

## How to Run

**Option A (Quick):** Paste this directly before bed:

```
/goal Run maintenance: close stale PRs, address post-merge review comments, clean up old branches, and generate a summary report. Output results to .claude/inbox/nightly-report.md. Stop when done.
```

**Option B (Reusable):** Save the goal above as a custom command called `/nightly-cleanup`, then run:

```
/loop 8h /nightly-cleanup
```

## Tips
- Results land in an inbox for morning review.
- Combine with a verifier that checks for broken links or failing checks.
- Use a real interval (e.g. 8h) or schedule it via your system.