# Git Rebase

The `git rebase` command rewrites commit history by moving branches.

## Usage
```bash
git rebase <branch>
```

## Explanation
- Reapplies commits from the current branch onto the target branch.

- Creates a linear commit history.

## Example
```bash
git checkout feature-login
git rebase main
```

