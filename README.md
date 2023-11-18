# GIT
Basic commands of GIT
git init: Initializes a new Git repository in the current directory.
git status: Shows the status of changes as untracked, modified, or staged.
git add: Stages changes for commit. You need to specify files or use . to add all changes.
git rm --cached file_name: Unstages a file (removes it from the staging area).
git rm -f file_name: Removes a file from both the working directory and the staging area.
touch f_name: Creates a new file named f_name.
git add .: Stages all changes, including untracked files.
git config --global user.email "email" and git config --global user.name "username": Sets global user email and name configuration.
git rm -r --cached: Unstages all changes recursively.
git log --oneline: Shows a compact one-line representation of commit history.
git reset --mixed "id": Resets the staging area to the specified commit.
git reset --soft "id": Resets the staging area and the commit, keeping changes in the working directory.

The following commands are related to branches:
touch .gitignore: Creates a file to specify files and directories that should be ignored by Git.
git checkout -b branch_name: Creates a new branch and switches to it.
git branch b_name: Creates a new branch without switching to it.
git branch -a: Lists all branches, including remote branches.
git checkout master: Switches to the master branch.
git checkout b_name: Switches to the specified branch.
git branch -d b_name: Deletes the specified branch.
git merge b_name: Merges the specified branch into the current branch.
The following commands are related to working with remotes:

git remote add origin https………..: Adds a remote named "origin" with the specified URL.
git remote -v: Shows the URLs of remotes.
git pull origin b_name: Fetches changes from the remote and merges them into the current branch.
git push -u origin b_name: Pushes the branch to the remote and sets it as the upstream branch.
git push origin b_name: Pushes the branch to the remote.
git push origin --delete b_name: Deletes the specified branch on the remote.
