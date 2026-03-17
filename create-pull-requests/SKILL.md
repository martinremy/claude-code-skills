---
name: creating-github-pull-requests
description: Use this skill when creating GitHub PRs
allowed-tools: Bash, Read, Grep, Glob
---

# Creating PRs

When creating GitHub pull requests (PRs),
- If the PR addresses a GitHub issue, the first section of the PR description should be "## Issue" followed by "Closes #N" where N is the issue number.
- The PR description should have at least the following sections:
  - Issue: If the PR completes or fixes a GitHub issue, this section should contain "Closes #N" where N is the issue number.
  - Changes: A description of the changes introduced by this PR, for someone reading this PR in the future to get an overview.
  - Decisions: Briefly describe design decisions that were made in the course of writing this change set.
  - New patterns: New patterns that were introduced by this PR that future developers should be aware of.
  - Refactors: Briefly describe refactoring / simplification / DRY-ifying that was made.
  - New tests: Very briefly describe the new tests that were added.
  - Not done: Parts of the implementation that were deferred.
