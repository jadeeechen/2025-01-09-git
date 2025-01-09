# 2025-01-09-git

- `git clone`: does a one-time download from github to your local computer
    - make sure the directory you are cloning into is not already a git repo
- `git status`: shows the current state of the working directory and staging area, including uncommitted changes and staged files
    - helps identify what changes are ready to be committed or need to be staged
    - use `git add <file>` to stage changes or `git restore <file>` to discard changes

- `git add <file>`: stages changes in the specified file, preparing it for inclusion in the next commit
    - use `git status` to check which changes are staged or need to be added

- `git commit -m "<message>"`: creates a commit with the staged changes and attaches a descriptive message
    - saves the staged changes in the local repository, creating a snapshot of the project at that point in time
    - use `git status` to verify that the commit has been successfully created
