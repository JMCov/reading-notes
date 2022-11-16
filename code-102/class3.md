# Git

Before I define what Git is I need to define what a **Distributed Version Control System (DVCS)** is.

- A **DVCS** is a allows clients to create mirrored repositories to prevent loss of data if the server goes offline.

Git is a DVCS that stores data in a file system made up of snapshots. Files reside in Git in 3 separate stages.

1. **Commited** - Data is securely stored in a local database
2. **Modified** - File has been changed but not committed to the database
3. **Staged** - Flagged a file's changed version to be committed in the next snapshot

## Using Git

We can clone existing Git repositories by using the following command:

`git clone https://github.com/MyURL`

This will copy all versions of all files for a project to your local computer.

After you make changes in your text editor you must perform the acronym ACP

1. Add `git add filename`
2. Commit `git commit -m "Text describing the changes`
3. Push `git push origin main`

These steps will sync your local repository to the one located on GitHub.

### Things I want to know more about

I would like to learn more about the funcionality and extensions of VS Code. I know we have barely dipped our toes in at this point.

[Back to Home](../README.md)
