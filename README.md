# Mern-9

# Git Commands & purposes.

> git add : move file from untracked stage to tracked stage.
--> git add . : all files at once, will compare and only add changed/new one.
--> git add FileName : For a Specific files.

> git commit : from unstaged to satged, ready to push.
--> git commit -m "message": to write message in one line.
--> git commit: opens a new screen to write message in details, use ";q" to go back to git bash screen.

> git push: move your files from local storage to remote storage.
--> git push: when you are already in desired file/origin
--> git push -u origion branch name: use when you need to specify branch name/be in origion branch

> git log: show us the history of commit in details way.
--> git log --oneline: show us the history of commit in one line.

> git status: Show us the status of files and changes.

> git diff fileName: show us the changes we done in a specific file.

> git branch: show us the all branches we have created so far.

> git branch -a: show us the branches existing on local storage.
> git branch branchName: create a new branch but don't move us in it.
--> git branch -b branchName: create a new branch and also move us into it.

> git checkout branchName: Move us between different branches.

> git merge branchName: Merge a child branch into a parent branch. We can't merge a parent into a child branch. Sometimes conflicts arise, we need to solve it by selecting a given option in Vs Code.

> git stash: Temporary save our changes into a stack for later use.

# Some Other Concepts

- Pull Request
- Git Clone
- detached head