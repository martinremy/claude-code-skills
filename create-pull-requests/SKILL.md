---
name: creating-github-pull-requests
description: Use this skill when creating GitHub PRs
allowed-tools: Bash, Read, Grep, Glob
---

# Creating PRs

When creating GitHub pull requests (PRs),
- The PR description should have at least the following sections:
  - If the PR addresses a GitHub or Linear issue, the first section of the PR description should be "## Issue" followed by "Closes <issue>" where <issue> is "#N" for GitHub or ISSUE-ID for Linear.
  - Changes: A description of the changes introduced by this PR, for someone reading this PR in the future to get an overview.
  - Decisions: Briefly describe design decisions that were made in the course of writing this change set.
  - New patterns: New patterns that were introduced by this PR that future developers should be aware of.
  - Refactors: Briefly describe refactoring / simplification / DRY-ifying that was made.
  - New tests: Very briefly describe the new tests that were added.
  - Not done: Parts of the implementation that were deferred.
