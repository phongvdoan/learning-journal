# Git vs GitHub

## Version Control

- A system that allows someone to revisit various versions of a file or a set of files by recording changes.
    - revert to previous version
    - track modifications and modifying individuals
    - compare changes
- Centralized Version Control
    - A single server storing all changes and file versions that can be accessed by many clients.
- Distributed Version Control
    - Allows for mirrored repositores that can be replace any lost information.

## Git

- A DVCS that stores data in a file system using snapshots.
- Project`s history resides on local disk allowing continuous work.
- Can detect file corruption or loss of information in transit.
- Track all changes applied.
- Three main states:
    - Committed - data is securely stored in local database
    - Modified - file has been changed but not committed
    - Staged - flagged a file`s changed version to be committed in the next snapshot.

### Initial Customization

- `git config` tool that set the configuration of git
    - `git config --global user.name "Your name"`
    - `git config --global user.email "Your email"`
    - `git config --global core.editor editor`
    - `git config --list` to check settings
    - `git help command` to view manual

### Setting up a Git Repository

#### Importing

1. `cd` to target project`s directory
2. `git init`
3. `git add *.c`
4. `git add LICENSE`
5. `git commit -m "insert message"`

#### Cloning

- `git clone https://github.com/repo`

### Workflow

- Local Repository
    - Working Directory where the actual files are
    - Index which is used for staging
    - Head most recent commit
- Saving Changes
    - Tracked files are part of the most recent snapshot so it can be modified` unmodified, or staged.
    - Untracked files were not in the last snapshot

### Life Cycle of File Status

1. After editing a file, it is flagged as modified
2. Stage modified file
3. Commit the staged file

### Check File Status

- `git status`

### Tracking and Staging a New File

- `git add filename` or `git add *`

### Commiting a File

- `git commit -m "made changes to.."`
- `git commit -a`

### Pushing Changes

- `git push origin master`

### Stashing Changes

- Hides changes
- `git stash`
- To retrieve the hidden changes `git stash apply`

## Remote Repositories

- Git automaticly gives the name origin to the server in which you cloned from
- `git remote` or `git remote -v` to view all remote handles