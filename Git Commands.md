
---

# Git Commands

## Configuration

### 1. `git config`
- Configure Git settings.
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "youremail@example.com"
   ```

## Repository Initialization

### 2. `git init`
- Create a new Git repository in the current directory.
   ```bash
   git init
   ```

### 3. `git clone`
- Clone a remote repository.
   ```bash
   git clone <repository_url>
   ```

## Staging and Committing

### 4. `git add`
- Stage changes for commit.
   ```bash
   git add file.txt
   ```

### 5. `git commit`
- Commit changes to the repository.
   ```bash
   git commit -m "Commit message"
   ```

## Viewing Changes

### 6. `git status`
- View the status of your repository.
   ```bash
   git status
   ```

### 7. `git diff`
- Show changes between working directory and the last commit.
   ```bash
   git diff
   ```

### 8. `git log`
- View commit history.
   ```bash
   git log
   ```

## Branching

### 9. `git branch`
- List all branches.
   ```bash
   git branch
   ```

### 10. `git checkout`
- Switch to a branch.
   ```bash
   git checkout branch_name
   ```

### 11. `git merge`
- Merge a branch into the current branch.
   ```bash
   git merge branch_name
   ```

### 12. `git branch -d`
- Delete a branch.
   ```bash
   git branch -d branch_name
   ```

## Remote Repository

### 13. `git remote`
- List remote repositories.
   ```bash
   git remote -v
   ```
### 14. `git remote add origin`
- Add Existing Drirectory to Repository
   ```bash
   git remote add origin <URL>
   ```
### 15. `git pull`
- Fetch changes from a remote repository.
   ```bash
   git pull origin master
   ```

### 16. `git push`
- Push changes to a remote repository.
   ```bash
   git push origin master
   ```

## Undoing Changes

### 17. `git reset`
- Unstage changes.
   ```bash
   git reset file.txt
   ```

### 18. `git revert`
- Create a new commit to reverse a previous commit.
   ```bash
   git revert <commit_hash>
   ```

### 19. `git reset --hard`
- Discard changes in the working directory.
   ```bash
   git reset --hard HEAD
   ```

## Tagging

### 20. `git tag`
- Create, list, or delete tags.
   ```bash
   git tag v1.0
   ```

### 21. `git push --tags`
- Push tags to a remote repository.
   ```bash
   git push --tags
   ```

## Collaboration

### 22. `git fetch`
- Download objects and refs from another repository.
   ```bash
   git fetch origin
   ```

### 23. `git merge`
- Merge changes from a remote branch into your current branch.
   ```bash
   git merge origin/branch_name
   ```

### 24. `git pull`
- Fetch and merge changes from a remote repository.
   ```bash
   git pull origin branch_name
   ```

### 25. `git push`
- Push changes to a remote repository.
   ```bash
   git push origin branch_name
   ```
