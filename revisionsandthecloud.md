# Revisions and the Cloud

## Version Control
* Records changes and allows the user to revisit past iterations of files.
* Allows for mistakes to be fixed
* Allows for files to be reverted to previous iterations.
* Tracks who made the changes and what changes were made

### Local Version Control
* A database that is stored on an individuals' computer.  (Not on the cloud)
 
### Centralized Version Control (CVCS)
* Created out of a need for collaboration between developers
* Single server that stores all files and changes that can be accessed by various users
* Accelerates collaboration process and increases understanding of what various members of team are doing with the shared code

### Distributed Version Control
* Addresses the vulnerability of CVS by creating a copy of repo locally.  If server goes down, devs will still be able to work on the code locally
* Creates mirrored repos for devs to use
* Allows for simultaneous workflow which allows multiple people to work on code at the same time

# Git
* **Snapshots**
    * Git is a DVCS. It stores data as files made up of snapshots.
    * Every changed version that is saved (commit) creates a snapshot of the file and stores a reference to it.
* **Local Operations**
    * Mostly relies on local operations because most info can be found through local resources
    * Expedites the process because the project's history is stored locally, and it does not have to be fetched from the server
* **Tracking Changes**
    * All changes are tracked via Git.
    * Git will detect file corruption or information that gets lost in transit
* **Loss of Data**
    * Git is set up to minimize the irreversible damage (lost data)
    * Difficult for Git to lose snapshots of files
* **States**
    * Commited
        * Data securely stored in local database
    * Modified
        * File has changed but not commited to database
    * Staged
        * Flags a changed version a file to be commited in the next snapshot
### History of Git
* Created circa 2005
* Has become one of the most used Version Control Systems (VDS) worldwide
* Born from BitKeeper no longer being free

# Workflow

### Local Repository Structure
* ACP = add, commit, push
* Working Directory: Where files reside
* Index: Staging area
* Head: Points to most recent commit
* Working Directory(add)>Index(commit)>Head

### Saving Changes
* All files in a working copy of a project file are tracked in a tracked or untracked state
* **Tracked**
    * Can be modfied, unmodified, or staged. Part of most recent snapshot file
* **Untracked**
    * Not in the last snpashot and do not reside in staging area
* Cloned repositories have files that are tracked and unmodified.  This is because they have been checked but have not been edited.

### The Life Cycle of File Status
1. After editing a file, Git flags it as modified because changes have been made since the previous commit
2. Modified file is staged
3. Finally, staged changes are commited

### Check File Status
* Determine the state of files by using the git status command: $ git status

### Tracking and Staging a New File
* Single file tracking uses: git add filename
* All file tracking uses the command: $ git add *

### Committing a File
* After staging files, you should commit the changes with a message that explains what you did
* Code as follows: $ git commit -m "text here"

### Committing All Changes
* Commits a snapshot of all modifications to tracked files
* Code as follows: $ git commit -a

### Pushing Changes
* How to push to remote repository (GitHub): $ git push origin master
* Pushes from local computer to the cloud

### Stashing Changes
* $ git stash
    * Stores changes without committing them
    * Temporarily removes changes and hides them
* $ git stash apply
    * Retrieves hidden changes when ready to resume working on the changes

# Remote Repositories
* Reside online or on a network
* Teams can use remote repos to push and pull from
* Can work with multiple repos

### Cloned Repositories
* Cloned repositories will be called origin
* Master will be assigned to local branch

### Seeing Your Remotes
* $ git remote
    * view short names of all specified remote handles
* git remote -v
    * view all remote urls next to their corresponding short names

