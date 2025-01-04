## Commit Message Guidelines

### Format Rules

- Use conventional commit message format.
- Start with type: feat|fix|docs|style|refactor|test|chore|build
- Use imperative mood ("add" not "added")
- Limit first line to 50 characters
- Add blank line after subject
- Wrap body at 72 characters
- Use bullet points for multiple changes
- Reference issues/tickets where applicable

### Types

- feat: New feature or functionality
- fix: Bug fix
- docs: Documentation changes
- style: Formatting, missing semicolons, etc
- refactor: Code restructuring
- test: Adding/updating tests
- chore: Maintenance tasks
- build: Changes that affect the build system or external dependencies (example scopes: maven, gulp, broccoli, npm)

### Examples

```text
feat: add user authentication endpoint

- Implement JWT token generation
- Add password hashing
- Create user validation middleware
Refs: #123

fix: resolve null pointer in user service

Handle case where user profile is undefined
Fixes: #456

refactor: simplify order processing logic

- Extract payment processing to separate service
- Remove duplicate validation code
- Improve error handling
```
