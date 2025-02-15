01-09-2025-git

- `git clone`: does a one-time download from github to your local computer
    - make sure the directory you are cloning into is not already a git repo

- `git status`: shows the current state of the working directory and staging area (including uncommitted changes and staged files)
    - helps identify what changes are ready to be committed or need to be staged

- `git add <file>`: stages changes in the specified file (preparing it for inclusion in the next commit)

- `git commit -m "<message>"`: creates a commit with the staged changes and attaches a descriptive message. saves the staged changes in the local repository, creating a snapshot of the project at that point in time

- `git push <remote> <branch>`: Uploads changes from your local machine to the specified remote repository (`<remote>`) on the given branch (`<branch>`).

- `git pull <remote> <branch>`: Fetches and integrates changes from the specified remote repository (`<remote>`) on the given branch (`<branch>`) to your local machine.
