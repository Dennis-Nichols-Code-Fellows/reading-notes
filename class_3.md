# Class 3 -  Revisions and the Cloud

These notes cover the assigned notes in the udemy [Git Tutorial[(https://blog.udemy.com/git-tutorial-a-comprehensive-guide/).

## Version Control

**Version control** is a way of recording the history of changes and iterations to a file. This history also enables reverting a file to an older version.

### Types of Version Control Systems (VCS)

- **Local** VCS keeps a database of changes on your hard drive.
- **Centralized** VCS keeps a database of changes on a remote server that can be accessed by different members of a team. This allows collaboration and better control by admins.
- **Distributed** VCS increases the reliability of the changes database (repository or **repo**) by spreading multiple copies of the repo over several differnt servers.

## Git

**Git** is a distributed VCS that stores snapshots of files in progress. Git handles tracking of file changes mainly on the local machine but can also *commit* changes to a shared file in a distributed repository.

Git files exist in the following states:

1. **Modified** - changes have been made but have neither been staged nor committed.
2. **Staged** - changes have been flagged to be committed to the repo in the next snapshot.
3. **Committed** - the current snapshot of the file is securely stored in the repo.

### Setting up Git

-Git can be installed by various means and for different OSs
-It is important to config Git with your Username and email from the beginning.

### Setting up a Git repo

1. navigate to the active project's directory with your CLI / shell
2. Use the command `git init`
3. To start tracking, perform an initial commit

Note - you can also create a copy (**clone**) an existing repo to your machine by using the following command:
`git clone [repo URL]`

## Git Workflow

A local git repo consists of three components:

1. Working Directory - the file resides here (may be modified vs. the head)
2. Index - an area used for staging changes
3. Head - points to the most recently committed version of a file.
