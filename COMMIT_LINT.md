# Commit Lint Guidelines

This project enforces conventional commit messages to maintain clarity and consistency in the commit history.

## Commit Message Format

Each commit message should be structured as follows:

```
<type>(optional scope): <description>
```

### Examples

```
feat(button): add primary button variant
fix(ui): resolve alignment issue in header
docs: update README with usage instructions
refactor: simplify form validation logic
```

### Allowed Types

- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect meaning of the code (white-space, formatting, etc)
- refactor: A code change that neither fixes a bug nor adds a feature
- perf: A code change that improves performance
- test: Adding or correcting tests
- chore: Changes to the build process or auxiliary tools

## How to Commit

1. Stage your changes:  
   `git add .`

2. Commit using the format above:  
   `git commit -m "feat(component): add new card component"`

3. Push your changes:  
   `git push`

> **Tip:** Use tools like [commitlint](https://commitlint.js.org/) and [husky](https://typicode.github.io/husky/) to automate commit message linting.

[← Back to main README](./README.md)
