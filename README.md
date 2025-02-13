
# CS615C-LAB1
# Lab 1: Comprehensive Git Operations

## INSTALLATION AND CONFIGURATION
### 1. **Install Git**
- Download and install Git from [git-scm.com](https://git-scm.com/).

### 2. **Verify Installation**
```bash
git --version
```

### 3. **Configure User Information**
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
### 4. **Check Configuration**
```bash
git config --list
```

## PROCEDURE
### 1. **Initialize a Repository**
```bash
git init
```
### 2. **Check Repository Status**
```bash
git status
```
### 3. **Create and Stage a File**
```bash
echo "Hello, Git!" > hello.txt
git add hello.txt
```
### 4. **Commit Changes**
```bash
git commit -m "Initial commit with hello.txt"
```
### 5. **View Commit History**
```bash
git log --oneline
```
### 6. **Create and Switch to a New Branch**
```bash
git checkout -b feature-branch
```
### 7. **Merge Branches**
```bash
git checkout main
git merge feature-branch
```
### 8. **Push to Remote Repository**
```bash
git remote add origin https://github.com/username/repository.git
git push -u origin main
```
### 9. **Stash Changes**
```bash
git stash
git stash list
git stash apply
```
### 10. **Undo Changes**
```bash
git reset HEAD filename
git checkout -- filename
```
### 11. **Tagging Commits**
```bash
git tag v1.0
git push origin v1.0
```
### 12. **Rebasing Branches**
```bash
git checkout feature-branch
git rebase main
```
### 13. **Deleting Branches**
```bash
git branch -d feature-branch
```

## RESULTS
- Successfully installed and configured Git.
- Demonstrated various Git commands and operations.

## CONCLUSION
This exercise provided hands-on experience with Git installation, configuration, and essential version control operations.

