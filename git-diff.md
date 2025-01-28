# Git Diff

The `git diff` command shows changes between commits, branches, or the working directory.

## Usage
```bash
git diff
```

## Explanation
- Displays line-by-line changes in files.

- Use `git diff --staged` to see changes in the staging area.

## Example
```bash
git diff
git diff --staged
```

## Output
```bash
λ git diff
diff --git a/git-init.md b/git-init.md
index 1dcdc1e..d34ecf6 100644
--- a/git-init.md
+++ b/git-init.md
@@ -19,4 +19,7 @@ git init
 mkdir my-project
 cd my-project
 git init
+```
+```bash
+git diff
 ```