PROOF OF WORK



Git Commit History



```text

62f8dbd Merge pull request #1 from MalikUsama804/development

2119f5b (origin/development, development) fix: resolved merge conflict

986392f (origin/staging, staging) fix: staging label

d246f26 feat: updated script with staging env

592fe9e feat: initial commit with deploy script

```



Q1: Difference between Git and GitHub



Git is a version control system that tracks file changes on a computer. It allows developers to create commits and branches. GitHub is an online platform that hosts Git repositories. It helps developers share code and collaborate.



Q2: Working Directory, Staging Area, and Local Repository



The Working Directory is where we create and edit files. The Staging Area contains changes selected using `git add`. The Local Repository stores committed changes using `git commit`. The workflow moves changes from the Working Directory to the Staging Area and then to the Local Repository.



Q3: Difference between git stash pop and git stash apply



Both commands restore stashed changes. `git stash pop` applies the changes and removes the stash entry if successful. `git stash apply` applies the changes but keeps the stash entry. This allows the saved changes to be reused later.



Q4: Difference between git fetch and git pull



`git fetch` downloads changes from the remote repository without merging them into the current branch. `git pull` downloads changes and integrates them into the current branch. Fetch lets us inspect updates first. Pull is useful when we want to bring remote changes into our current branch.



