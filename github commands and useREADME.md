# GitHub Commands Reference

This document provides a list of commonly used Git commands and their usage. These commands will help you manage repositories, branches, and changes in your GitHub projects.

## Basic Commands

### 1. `git init`
- **Usage**: Initializes a new Git repository in the current directory.
- **Example**: `git init`

### 2. `git clone`
- **Usage**: Clones a remote repository to your local machine.
- **Example**: `git clone https://github.com/user/repository.git`

### 3. `git status`
- **Usage**: Displays the state of the working directory and the staging area, showing any changes.
- **Example**: `git status`

### 4. `git add`
- **Usage**: Stages changes (tracked and untracked) to be committed.
- **Example**: `git add .` (adds all changes)

### 5. `git commit`
- **Usage**: Records changes to the repository with a descriptive message.
- **Example**: `git commit -m "Add new feature"`

### 6. `git push`
- **Usage**: Uploads local repository content to a remote repository.
- **Example**: `git push origin main`

### 7. `git pull`
- **Usage**: Fetches changes from a remote repository and merges them into the current branch.
- **Example**: `git pull origin main`

### 8. `git branch`
- **Usage**: Lists, creates, or deletes branches.
- **Example**: `git branch` (lists branches)

### 9. `git checkout`
- **Usage**: Switches branches or restores working tree files.
- **Example**: `git checkout -b new-feature` (creates and switches to a new branch)

### 10. `git merge`
- **Usage**: Combines the changes from one branch into another.
- **Example**: `git merge feature-branch` (merges `feature-branch` into the current branch)

### 11. `git remote`
- **Usage**: Manages set URLs for repositories.
- **Example**: `git remote add origin https://github.com/user/repository.git`

### 12. `git fetch`
- **Usage**: Downloads objects and refs from another repository.
- **Example**: `git fetch origin`

### 13. `git log`
- **Usage**: Shows the commit history for the current branch.
- **Example**: `git log --oneline`

### 14. `git reset`
- **Usage**: Resets the current HEAD to a specified state.
- **Example**: `git reset --hard HEAD~1` (resets to the previous commit, discarding changes)

### 15. `git rebase`
- **Usage**: Reapplies commits on top of another base tip.
- **Example**: `git rebase main` (reapplies changes from the current branch onto the `main` branch)

## Advanced Commands

### 16. `git stash`
- **Usage**: Temporarily saves changes in the working directory that are not ready to be committed.
- **Example**: `git stash save "Work in progress"`

### 17. `git cherry-pick`
- **Usage**: Applies changes from a specific commit to the current branch.
- **Example**: `git cherry-pick <commit-hash>`

### 18. `git revert`
- **Usage**: Reverses a specific commit by creating a new commit.
- **Example**: `git revert <commit-hash>`

### 19. `git tag`
- **Usage**: Creates a tag to mark a specific point in history as important (e.g., for releases).
- **Example**: `git tag v1.0.0`

### 20. `git diff`
- **Usage**: Shows the differences between commits, commit and working tree, etc.
- **Example**: `git diff HEAD`

---

These commands provide a solid foundation for working with Git and GitHub.