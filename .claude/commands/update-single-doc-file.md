---
name: update-single-doc-file
description: Workflow command scaffold for update-single-doc-file in mybatis-plus-doc.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /update-single-doc-file

Use this workflow when working on **update-single-doc-file** in `mybatis-plus-doc`.

## Goal

Update or correct a single documentation file, often for minor fixes, clarifications, or content improvements.

## Common Files

- `docs/**/*.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Edit the target markdown file under docs/ (e.g., docs/01.指南/01.快速入门/05.注解.md)
- Commit the change with a message like 'update doc' or '更正默认值描述'

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.