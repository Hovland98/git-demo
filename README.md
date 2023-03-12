# git-demo

## Commands

Clone repo (copy repo to local machine):

```bash
git clone <repo_link>
```

List local branches:

```bash
git branch
```

List remote branches:

```bash
git branch -r
```

Create a new branch:

```bash
git branch <branch_name>
```

Switch to branch:

```bash
git switch <branch_name>
```

List local branches:

```bash
git branch
```

List remote branches:

```bash
git branch -r
```

Create a new branch:

```bash
git branch <branch_name>
```

List changed files:

```bash
git status
```

Add file to be commited:

```bash
git add <file>
```

Commit changes:

```bash
git commit -m "<message>"
```

List remote repos (your repo is usually called `origin`):

```bash
git remote
```

Stash away changes that you want to keep for later but don't want to commit yet:

```bash
git stash
```

Apply the changes that you stashed away:

```bash
git stash apply
```

Merge changes from another branch into current branch:

```bash
git switch <merge_to_branch>
git merge <merge_from_branch> -m "<message>"
Fetch updates from remote repo:
```

```bash
git fetch
```
