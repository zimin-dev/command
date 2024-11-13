## Git Commands

- `git --version` - check Git version
- `git config --list` - view settings
- `git config --global user.name "Sasha Zimin"` - set author's name
- `git config --global user.email "info@zimin.dev"` - set author's email
- `git init` - create a new repository
- `git config --global init.defaultBranch 'name'` - change default branch name (e.g., main, master)
- `git status` - view files in the index (staged but not committed from the working directory)
- `git add file` - add changes to the index
- `git commit` - save changes from the index to the repository
- `git commit -m "message"` - create and save a new commit
- `git checkout "commit hash"` - switch to a specific commit by hash (view in logs)
- `git log` - view commit logs
- `git checkout "branch name"` - switch to a specific branch at the latest commit
- `git checkout "commit hash"` - switch to a previous commit (moves HEAD to that commit)
- `git checkout main` (or `master`) - switch to the main branch and set HEAD to the latest commit
- `git checkout branchname` - switch to the selected branch (moves HEAD)
- `git cat-file -t 2c4f323 (hash)` - display file info, file type (commit, tree)
- `git cat-file -p 2c4f323` - display commit/tree author info and file changes by hash
- `git status` - shows the current repository state
- `git branch` - list all branches
- `git branch newbranchname` - create a new branch
- `git checkout -b newbranchname` - create a new branch and switch to it
- `git branch -m newbranchname` - rename a branch
- `git branch -d branchname` - delete a specific branch (you must exit it first)
- `git merge branchname` - merge one branch into another (execute while on the receiving branch)
- `code .` - open current project in VSCode from terminal
- `git clone url` - download a repository from hosting to your machine
- `origin` - the primary remote repository name on hosting, created when cloning
- `git branch -a` - shows all branches, including remote ones
- `git pull` - fetch changes from a remote branch to a local one
- `git push` - push local changes to a remote branch
- `git remote add origin url` - add a remote repository to your local machine

## Git Status

- `untracked` - not trackable
- `unmodified` - unmodified
- `modified` - modified
- `staged` - staged for commit

## Git Object

- `blob` - for files, stores different versions
- `tree` - directory containing other directories and files, as well as files within these directories
- `commit` - contains author’s name and email after saving changes
- `annotated tag` - create a tag to navigate between repository versions
