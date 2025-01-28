# Git Tag

The `git tag` command marks specific points in history.

## Usage
```bash
git tag <name>          # Create a tag
git tag -a <name> -m "Message" # Create an annotated tag
```
## Explanation
- Tags are often used to mark release points (e.g., v1.0.0).

- Use git push --tags to push tags to the remote.

## Example
```bash
git tag v1.0.0
git push --tags
```