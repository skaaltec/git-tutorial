# Frequently Asked Questions

## How do I undo the last commit?
Use `git reset HEAD~1` to undo the last commit.

## How do I resolve merge conflicts?
1. Open the conflicted files.
2. Resolve the conflicts manually.
3. Stage the resolved files:
   ```bash
   git add <file>
   ```
4. Complete the merge:
   ```bash
   git commit
   ```

## How do I delete a branch?
- Use `git branch -d <branch>` to delete a branch locally.
- Use `git push origin --delete <branch>` to delete a branch remotely.

## Next Steps
1. Create the folders and files in your repository.
2. Copy and paste the content into the respective `.md` files.
3. Commit and push the changes to GitHub or GitLab.

Let me know if you need further assistance! 😊