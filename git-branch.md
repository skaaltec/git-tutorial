# Git Branch

The `git branch` command lists, creates, or deletes branches.

## Usage
```bash
git branch          # List branches
git branch <name>   # Create a new branch
git branch -d <name> # Delete a branch
```

## Explanation
Branches allow you to work on multiple features or fixes simultaneously.

Use `git branch` to see all branches in your repository.

## Example
```bash
git branch feature-login
git branch
```

## Output
```bash
λ git branch
  advanced/01-git-stash
  advanced/02-git-tag
  advanced/03-git-reset
  advanced/04-git-revert
  advanced/05-git-cherry-pick
  advanced/06-git-hooks
  basics/01-git-init
  basics/02-git-clone
  basics/03-git-status
  basics/04-git-add
  basics/05-git-commit
  basics/06-git-log
  basics/07-git-diff
* branching/01-git-branch # working branch
  branching/02-git-checkout
  branching/03-git-merge
  branching/04-git-rebase
  collaboration/01-git-remote
  collaboration/02-git-fetch
  collaboration/03-git-pull
  collaboration/04-git-push
  collaboration/05-git-pull-request
  main
  workflows/01-feature-branch
  workflows/02-git-flow
  workflows/03-github-flow
(END)
```