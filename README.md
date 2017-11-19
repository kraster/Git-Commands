# Git Basic commands

1. Configure GIT
2. Create repositories
3. Core GIT commands
4. Branches commands
5. Log commands
6. Reset commands
7. Refactor filenames

#### 1. Configure GIT
* **git config --global user.name "[name]"**
* **git config --global user.email "[email/address]"**

#### 2. Create repositories
* Clone a repository: **git clone repo.git**
* Create a new local repository: **git init [project-name]**

#### 3. Core GIT commands
* Changed files in your working directory: **git status**
* Changes to tracked files: **git diff**
* Changes between two branches: **git diff [first-branch] [second-branch]**

* Add files to commit: **git add** (add all files - **git add .**)
* Commit: **git commit -m "new changes"** (commit all local changes - git commit -A)

* Download changes: **git pull**
* Publish local changes: **git push**

#### 4. Branches commands
* List all current branches: **git branch**
* Create a new branch: **git branch <branch>**
* Push upstream a new branch: **git push --set-upstream origin <branch>**
* Switch HEAD branch: **git checkout <branch>**
* Create a new tracking branch based on a remote branch: **git checkout --track <remote/branch>**
* Delete a local branch: **git branch -d <branch>**
* Delete a branch on the remote: **git branch -dr <branch>**

#### 5. Log commands
* Show all commits, starting with the newest: **git log**
* Show changes over time for a specific file: **git log -p <file>**
* Who changes what and when in <file>: **git blame <file>** (**q to exit**)

#### 6. Reset commands
* Discard all local changes in your working diretory: **git reset --hard HEAD**
* Discard local changes in a specific file: **git checkout HEAD <file>**
* Revert a commit: **git revert <commit>**
* Reset your HEAD pointer to a previous commit and discard all changes since then: **git reset --hard <commit>**

#### 7. Refactor filenames
* Delete file from the working directory and stage deletion: **git rm [file]**
* Changes the file name and prepares it for commit: **git mv [file-original] [file-renamed]**



#### More advanced commands can be found on:
http://www.git-tower.com/blog/git-cheat-sheet/

https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf
