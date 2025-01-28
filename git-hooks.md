# Git Hooks

Git hooks are scripts that run automatically before or after Git commands.

## Usage
- Place scripts in the `.git/hooks/` directory.
- Common hooks: `pre-commit`, `post-commit`, `pre-push`.

## Explanation
- Use hooks to enforce workflows, run tests, or automate tasks.
- Hooks are local to your repository.

## Example
```bash
# .git/hooks/pre-commit
#!/bin/sh
echo "Running tests..."
npm test
```

