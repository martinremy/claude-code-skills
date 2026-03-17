---
name: writing-github-issues
description: Use this skill when writing GitHub issues
allowed-tools: Bash, Read, Grep, Glob
---

# Writing GitHub Issues

When writing GitHub issues, make sure you:
- Understand existing patterns in the codebase that are relevant to the new feature in the issue.
- If the new feature requires additional instances of existing patterns, write the issue in a way that can be implemented DRY-ly, but don't overcomplicate things.
- Have read `AGENTS.md` or `CLAUDE.md` to understand guidelines for the project.
- Include things like audit logging and tests in your issue if they are important to the feature.
- Ask clarifying questions if needed.
- Don't be overly prescriptive by adding large code blocks to the issue.  In most cases, leaving implementation details to the developer or coding agent is best.
