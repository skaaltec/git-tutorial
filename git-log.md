# Git Log

The `git log` command shows the commit history.

## Usage
```bash
git log
```
## Explanation
Displays a list of commits with details like `author`, `date`, and commit `message`.

Use `git log --oneline` for a compact view.

## Example
```bash
git log
git log --oneline
```

##Output

```bash
commit 2a29d0aa8cd46cdfd5eaae38a6f7418e36fce0cc (HEAD -> main, origin/main, origin/HEAD)
Merge: dcf1199 6765131
Author: Amin Jafari <aymin@gmail.com>
Date:   Tue Jan 28 17:10:50 2025 +0330

    Merge branch 'basics/05-git-commit'

commit 676513119c446857222ce46de8af07774c4601b5 (origin/basics/05-git-commit, basics/05-git-commit)
Author: Aymin Jafari <aymin.jeffrey1@gmail.com>
Date:   Tue Jan 28 17:10:27 2025 +0330

    feat: add basics/05-git-commit

commit dcf11999fb8dfa1fbc162847afee8960421c7c7a
Merge: 7e7b1dd 3b7f33f
Author: Amin Jafari <aymin@gmail.com>
Date:   Tue Jan 28 17:04:22 2025 +0330

    Merge branch 'basics/04-git-add'

commit 3b7f33f8f2de9fab353dbc868139ae945ef9c76c (origin/basics/04-git-add, basics/04-git-add)
Author: Aymin Jafari <aymin.jeffrey1@gmail.com>
Date:   Tue Jan 28 17:03:54 2025 +0330

    feat: add basics/04-git-status
```
