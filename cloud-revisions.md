# Notes: Cloud Revisions

### Version Control
Version control allows you to track the changes that have been made to a project from version to version so that you're easily able to revert to previous versions.
Centralized version control allows multiple people to collaborate on a single file
Distributed Version Control also allows for collaboration in a way that doesn't jeaopardize the entire project if the server goes down. It works by having clients create mirrored repositories.

### Git
Git is a DVCS (Distributed version control system) that works by storing snapshots of data. Each time you commit a file Git stores the snapshot as a new version.
Git works locally on the computer and does not need to be connected to the internet or a server.
Git states:
- Committed: Data is securely stored in a local database
- Modified: File has been changed but not committed to the database
- Staged: Flagged a files changed version to be committed in the next snapshot

### Workflow
There are three components to the local Git respository:
1. Working directory: Where the actual files are
2. Index: The staging area
3. Head: Points to the most recent commit

All files in a working project are either tracked or untracked.
- Tracked: These files can be modified, unmodified, or staged - they were part of the most recent file snapshot
- Untracked: These files were not in the last snapshot and are not in the staging area.

**File Status Workflow:**
1. Once a file has been edited, Git flags it as modified since changes were made after the last commit
2. Stage the modified file
3. Commit staged changes

**Check file status:**
To determine the state of files, use "git status" command. It will tell you what branch you're on and whether you have any untracked files.

**Track and stage a file:**
- git add filename
- or add all files in a repository with "git add *"

**Committing a file:**
- git commit -m "message about what you changed"

**Push changes:**
- git push origin master


[<--HOME](https://erinsp.github.io/reading-notes/)
