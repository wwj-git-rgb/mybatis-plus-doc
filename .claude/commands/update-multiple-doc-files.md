---
name: update-multiple-doc-files
description: Workflow command scaffold for update-multiple-doc-files in mybatis-plus-doc.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /update-multiple-doc-files

Use this workflow when working on **update-multiple-doc-files** in `mybatis-plus-doc`.

## Goal

Update several documentation files at once, typically to synchronize content, apply batch edits, or update related sections.

## Common Files

- `docs/**/*.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Edit several markdown files under docs/
- Commit all changes together with a message like 'update doc'

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.