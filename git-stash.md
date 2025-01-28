# Git Stash

The `git stash` command temporarily saves changes.

## Usage
```bash
git stash          # Save changes
git stash pop      # Reapply changes
```
## Explanation
- Use git stash to save uncommitted changes and switch branches.

- Use git stash pop to reapply the saved changes.

## Example
```bash
git stash
git checkout main
git stash pop
```