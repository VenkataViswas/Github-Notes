# Git Commands Reference

This file serves as a quick reference for commonly used Git commands.

## Initializing a Repository

- **`git init`**  
  Initializes a new Git repository in the current directory.

## Staging and Committing Changes

- **`git add <file>`**  
  Stages a specific file (or files) for commit.

- **`git commit -m "message"`**  
  Commits staged changes with a message describing the commit.

## Pushing Changes

- **`git push`**  
  Pushes local commits to a remote repository.

## Checking Status and Differences

- **`git diff`**  
  Shows differences between the working directory and the staging area.

- **`git status`**  
  Displays the status of the working directory and the staging area.

- **`git log`**  
  Shows the commit history.

## Undoing Changes

- **`git reset --hard <commit ID>`**  
  Resets the repository to the specified commit, discarding all changes after that commit.

## Working with Branches

- **`git checkout -b <branch name>`**  
  Creates and switches to a new branch with the specified name.

## Merging Changes

There are three main commands for merging changes between branches:

- **`git cherry-pick <commit ID>`**  
  Adds specific commits from one branch to another (often used to apply single commits to `main`).

- **`git merge <branch name>`**  
  Merges changes from the specified branch into the current branch without reordering commits.

- **`git rebase <branch name>`**  
  Merges changes from the specified branch into the current branch with a linear commit history.

---

Use these commands to manage your Git workflow effectively!
