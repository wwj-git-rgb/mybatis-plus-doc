---
name: update-htmlmodules-js
description: Workflow command scaffold for update-htmlmodules-js in mybatis-plus-doc.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /update-htmlmodules-js

Use this workflow when working on **update-htmlmodules-js** in `mybatis-plus-doc`.

## Goal

Make changes to the HTML modules configuration for the VuePress documentation site.

## Common Files

- `docs/.vuepress/config/htmlModules.js`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Edit docs/.vuepress/config/htmlModules.js
- Commit the change, often with message 'update doc' or 'update to 4.0'

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.