# Git-and-GitHub
  - [x] Git: Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.
  - [x] GitHub: GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.

# Git Commands
  - [x] git init [repository name]->This command is used to start a new repository.Initialized empty git repasitory.
  - [x] git config -> This command sets the author name and email address respectively to be used with your commits.
    - Usage: git config –global user.name “[name]” 
    - Usage: git config –global user.email “[email address]” 
  - [x] git clone [url] -> This command is used to obtain a repository from an existing URL.
  - [x] git status 
  - [x] git add [file] -> This command adds a file to the staging area. Stage changes for next commit.
    - Usage: git add *  -> This command adds one or more to the staging area.
  - [x] git commit -> This command records or snapshots the file permanently in the version history.Create a commit that includes all staged changes.
    - Usage: git commit -m “[ Type in the commit message]”
    - Usage: git commit -a   -> This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.
  - [x] git push [variable name] master -> This command sends the committed changes of master branch to your remote repository.
    - git push [variable name] [branch] -> This command sends the branch commits to your remote repository.
    - git push –all [variable name]  -> This command pushes all branches to your remote repository.
    - git push [variable name] :[branch name] -> This command deletes a branch on your remote repository.
  - [x] git pull [Repository Link] -> This command fetches and merges changes on the remote server to your working directory.
  - [x] git log -> To show the chronological commit history for a repository. This helps give context and history for a repository. git log is available immediately on a recently cloned repository to see history.
  - [x] git checkout (id)-> Temporarly move another commit.
    - git checkout [branch name] -> This command is used to switch from one branch to another.
    - git checkout -b [branch name]  -> This command creates a new branch and also switches to it.
  - [x] git revert (id) -> Revert changes of commit by creating a new commit 
  - [x] git resert --hard [id] -> Undo changes by deleting all commits sice [id]