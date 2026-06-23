# Claude Code Loop Recipes

Practical, copy-paste ready loops for Claude Code.

These recipes are designed to be **immediately usable**. Each one includes a clear goal, verification step, and schedule so you can run them with minimal setup.

## The Core Principle: Write the Check First

Before running any loop, define **how it will prove success**.

- Use `/goal` to set a measurable finish line.
- Pair every builder with a verifier.
- Add stop conditions and cost caps when possible.

This is what turns a vague agent into a reliable system.

## How to Use These Recipes

1. Copy the recipe into Claude Code.
2. Adjust the paths/commands to your project.
3. Run the loop (usually via `/loop` or `/goal`).

## Recipes

- [Babysit PRs](./recipes/babysit-pr.md)
- [Fix Failing Tests](./recipes/fix-failing-tests.md)
- [Nightly Cleanup](./recipes/nightly-cleanup.md)
- [Review and Merge](./recipes/review-and-merge.md)

## Go Deeper

For the original thinking behind these patterns, see [go-deeper.md](./go-deeper.md).