# Git and GitHub Commands for Windows

## Install Git on Windows
1. Download and install Git from [https://git-scm.com/download/win](https://git-scm.com/download/win).

## Configure Git Settings
Open Git Bash and configure your Git settings:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Check Git Version
```bash
git --version
```

## Initialize a New Git Repository
```bash
git init
```

## Check the Status of Your Repository
```bash
git status
```

## Add Files to the Staging Area
```bash
git add .
```

## Commit the Changes
```bash
git commit -m "Initial commit"
```

## Create a New Repository on GitHub
1. Go to [https://github.com/new](https://github.com/new) and follow the instructions to create a new repository.

## Add the Remote Repository URL
```bash
git remote add origin https://github.com/yourusername/your-repo.git
```

## Push Your Changes to the Remote Repository
```bash
git push -u origin master
```

## Pull Changes from the Remote Repository
```bash
git pull origin master
```

## Clone an Existing Repository
```bash
git clone https://github.com/yourusername/your-repo.git
```

## Create a New Branch
```bash
git branch new-branch
```

## Switch to the New Branch
```bash
git checkout new-branch
```

## Merge Changes from Another Branch
```bash
git merge branch-name
```

## Delete a Branch
```bash
git branch -d branch-name
```

## View the Commit History
```bash
git log
```

## View the Differences Between Commits
```bash
git diff
```

## Reset the Repository to a Previous Commit
```bash
git reset --hard commit-hash
```

## Stash Changes
```bash
git stash
```

## Apply Stashed Changes
```bash
git stash apply
```

## View the List of Stashed Changes
```bash
git stash list
```

## Drop a Specific Stash
```bash
git stash drop stash@{index}
```

