# Repo Health Check

Check all your public repos for broken README links, missing referenced files, and empty descriptions, then get a report of what's broken before anyone else finds it.

## Goal
All public repos checked, every README link works, every referenced file exists, and every repo has a description. A report of all issues is written.

## How to Run

**Option A (Quick):** Paste this directly:

```
/goal Check all my public GitHub repos for broken README links, missing referenced files, and empty descriptions. Use the gh CLI to list repos and fetch READMEs. Verify by actually checking each link and file path, don't assume. Write the results to repo-health-report.md grouped by repo. Do not modify any repos, just report. Stop when the report is written.
```

**Option B (Reusable):** Save the goal above as a custom command called `/repo-health`, then schedule it:

```
/loop 24h /repo-health
```

## Tips
- This is report-only. It never modifies your repos.
- Requires the `gh` CLI installed and authenticated.
- Run it once manually before scheduling, to see what it finds.
- Great as an overnight loop so you wake up to a clean report.
