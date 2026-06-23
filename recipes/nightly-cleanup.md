# Nightly Cleanup

Run overnight to handle small maintenance tasks.

## Goal
Stale branches cleaned, old comments addressed, and repo health checks passed.

## How to Run

```
/goal Run overnight maintenance: close stale PRs, address post-merge review comments, clean up old branches, and generate a summary report. Output results to .claude/inbox/nightly-report.md.
```

## Recommended Schedule

Run before sleep:

```
/loop overnight nightly-cleanup
```

## Tips
- Results land in an inbox for morning review.
- Combine with a verifier that checks for broken links or failing checks.