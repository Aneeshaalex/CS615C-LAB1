# CS615C-LAB1
# Comprehensive Guide to Git Operations

## Introduction
This README provides an extensive list of essential Git commands and operations for version control.

## Configuration
Set up global configurations:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --global core.editor "code --wait" # Set default editor
```

## Repository Management
- **Initialize a Repository:** `git init`
- **Clone a Repository:** `git clone https://github.com/username/repository.git`

## Tracking Changes
- **Check Status:** `git status`
- **Stage Changes:** `git add filename`
- **Commit Changes:** `git commit -m "Commit message"`
- **Commit All Changes:** `git commit -a -m "Commit message"`
- **Amend Last Commit:** `git commit --amend -m "New message"`

## Branching and Merging
- **Create Branch:** `git branch new-branch`
- **Switch Branch:** `git checkout new-branch`
- **Create & Switch:** `git checkout -b new-branch`
- **List Branches:** `git branch --list`
- **Delete Branch:** `git branch -d branch-name`
- **Merge Branch:** `git merge branch-name`

## Remote Repositories
- **Add Remote:** `git remote add origin https://github.com/user/repo.git`
- **View Remotes:** `git remote -v`
- **Remove Remote:** `git remote remove origin`
- **Push to Remote:** `git push origin main`
- **Pull from Remote:** `git pull origin main`

## Syncing Changes
- **Fetch Remote Changes:** `git fetch`
- **Rebase Current Branch:** `git rebase origin/main`

## History and Logs
- **View Commit History:** `git log`
- **View Compact History:** `git log --oneline`
- **Check Differences:** `git diff`
- **View Staged Changes:** `git diff --cached`

## Undoing Changes
- **Unstage File:** `git reset filename`
- **Discard Changes:** `git checkout -- filename`
- **Revert Commit:** `git revert HEAD`
- **Reset to Previous Commit:** `git reset --hard commit-hash`

## Stashing Changes
- **Save Changes:** `git stash`
- **List Stashes:** `git stash list`
- **Apply Stash:** `git stash apply`
- **Drop Stash:** `git stash drop`
- **Pop Stash:** `git stash pop`

## Tags
- **Create Tag:** `git tag v1.0`
- **List Tags:** `git tag`
- **Push Tags:** `git push origin --tags`
- **Delete Tag:** `git tag -d v1.0`

## Submodules
- **Add Submodule:** `git submodule add https://github.com/user/repo.git path/to/submodule`
- **Update Submodules:** `git submodule update --init --recursive`

## Conclusion
This guide covers a wide range of Git operations to manage projects efficiently. For more information, visit the [official Git documentation](https://git-scm.com/doc).

