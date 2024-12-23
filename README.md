# Git and GitHub Commands for Windows

## 1. Install Git on Windows
1. Download and install Git from [https://git-scm.com/download/win](https://git-scm.com/download/win).

## 2. Configure Git Settings
Open Git Bash and configure your Git settings:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## 3. Check Git Version
```bash
git --version
```

## 4. Initialize a New Git Repository
```bash
git init
```

## 5. Check the Status of Your Repository
```bash
git status
```

## 6. Add Files to the Staging Area
```bash
git add .
```

## 7. Commit the Changes
```bash
git commit -m "Initial commit"
```

## 8. Create a New Repository on GitHub
1. Go to [https://github.com/new](https://github.com/new) and follow the instructions to create a new repository.

## 9. Add the Remote Repository URL
```bash
git remote add origin https://github.com/yourusername/your-repo.git
```

## 10. Push Your Changes to the Remote Repository
```bash
git push -u origin master
```

## 11. Pull Changes from the Remote Repository
```bash
git pull origin master
```

## 12. Clone an Existing Repository
```bash
git clone https://github.com/yourusername/your-repo.git
```

## 13. Create a New Branch
```bash
git branch new-branch
```

## 14. Switch to the New Branch
```bash
git checkout new-branch
```

## 15. Merge Changes from Another Branch
```bash
git merge branch-name
```

## 16. Delete a Branch
```bash
git branch -d branch-name
```

## 17. View the Commit History
```bash
git log
```

## 18. View the Differences Between Commits
```bash
git diff
```

## 19. Reset the Repository to a Previous Commit
```bash
git reset --hard commit-hash
```

## 20. Stash Changes
```bash
git stash
```

## 21. Apply Stashed Changes
```bash
git stash apply
```

## 22. View the List of Stashed Changes
```bash
git stash list
```

## 23. Drop a Specific Stash
```bash
git stash drop stash@{index}
```
