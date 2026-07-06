```markdown
# mybatis-plus-doc Development Patterns

> Auto-generated skill from repository analysis

## Overview

This skill teaches you the conventions, workflows, and best practices for contributing to the `mybatis-plus-doc` repository. The project is a documentation site built with JavaScript and the Astro framework, with documentation content managed in Markdown and configuration in JavaScript. You'll learn how to update docs, manage configuration, and follow the established coding and commit patterns.

## Coding Conventions

- **File Naming:**  
  Use camelCase for JavaScript files.  
  _Example:_  
  ```
  htmlModules.js
  nav.js
  ```

- **Import Style:**  
  Use relative imports for modules.  
  _Example:_  
  ```js
  import htmlModules from './htmlModules.js';
  ```

- **Export Style:**  
  Use named exports.  
  _Example:_  
  ```js
  export const nav = [ /* ... */ ];
  ```

- **Commit Messages:**  
  Freeform, often short and descriptive.  
  _Examples:_  
  ```
  update doc
  更正默认值描述
  update to 4.0
  ```

## Workflows

### Update Single Doc File
**Trigger:** When you want to fix a typo, clarify a section, or make a small update to a specific documentation page.  
**Command:** `/update-doc`

1. Edit the target Markdown file under `docs/` (e.g., `docs/01.指南/01.快速入门/05.注解.md`).
2. Commit the change with a message like `update doc` or a brief description.

### Update HTML Modules JS
**Trigger:** When you need to adjust or fix HTML module settings/content in the documentation site.  
**Command:** `/update-htmlmodules`

1. Edit `docs/.vuepress/config/htmlModules.js`.
2. Commit the change, often with a message like `update doc` or `update to 4.0`.

### Update Multiple Doc Files
**Trigger:** When you want to update multiple related documentation files in one go.  
**Command:** `/batch-update-docs`

1. Edit several Markdown files under `docs/`.
2. Commit all changes together with a message like `update doc`.

### Add or Update Low-Code Platform Section
**Trigger:** When introducing or revising documentation about the low-code platform.  
**Command:** `/update-lowcode-docs`

1. Edit or create files under `docs/06.低代码平台/`.
2. Optionally add or update images under `docs/.vuepress/public/img/`.
3. Update navigation if needed (`docs/.vuepress/config/nav.js`).
4. Commit all changes together.

### Update Deploy Script
**Trigger:** When you need to change deployment behavior or fix deployment issues.  
**Command:** `/update-deploy-script`

1. Edit `deploy.sh`.
2. Commit the change.

## Testing Patterns

- **Framework:** Unknown (not detected in the repository).
- **Test File Pattern:** Test files are named with the pattern `*.test.*` (e.g., `example.test.js`).
- _Example:_  
  ```
  // example.test.js
  import { someFunction } from './someModule';

  test('should work', () => {
    expect(someFunction()).toBe(true);
  });
  ```

## Commands

| Command                 | Purpose                                                        |
|-------------------------|----------------------------------------------------------------|
| /update-doc             | Update or correct a single documentation file                  |
| /update-htmlmodules     | Change HTML modules configuration for the documentation site   |
| /batch-update-docs      | Update several documentation files at once                     |
| /update-lowcode-docs    | Add or update the low-code platform section and related assets |
| /update-deploy-script   | Update the deployment script                                   |
```
