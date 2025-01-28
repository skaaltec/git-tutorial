# Git Reset

The `git reset` command undoes changes.

## Usage
```bash
git reset --soft <commit>  # Undo commits but keep changes
git reset --hard <commit>  # Discard all changes
```

## Explanation
- Use --soft to undo commits but keep changes in the working directory.

- Use --hard to discard all changes and reset to a specific commit.

## Example
```bash
git reset --soft HEAD~1
git reset --hard HEAD~1
```