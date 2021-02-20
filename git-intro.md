# Revisions and the Cloud - Personal Notes

## Intro to **Git**

## VCS - Version Control System

VCS is a system that allows history tracking of files, that can be later reverted to and modified.

There are three types of VCS:

1. Local Version Control - Entails of database on your hard disk.
2. _CVCS_ (Centralized Version Control) - Database uses a server that enables multiple access to users.
3. _DVCS_ (Distributed Version Control) - Basically allows the user to mirror the repos on a backup source.

**Git** is a _DVCS_

Using Git “commit” command takes a snapshot of the changes to the file and stores a reference to it.

'Committed’ - Data is securely stored in a local database.
‘Modified’ - File has been changed but not committed to the database
‘Staged’ - Flagged a file’s changed version to be committed in the next snapshot

\*FunFact\* : We can thank Linus Torvalds, the chief architect of the Linux kernel for ‘Git’ and 'GitHub'.

# Testing Git on my MBP :

shawnebanks@shawns-MBP ~ % git config --global user.name master
Shawn Ebanks
shawnebanks@shawns-MBP ~ % git config --global user.email master
shawnebanks@rocketmail.com

## To check settings, use the git config --list command.

### My Result :

shawnebanks@shawns-MBP ~ % git config --list master
credential.helper=osxkeychain
filter.lfs.required=true
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
user.name=Shawn Ebanks
user.email=shawnebanks@rocketmail.com
core.editor=code --wait
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true

# Getting Help

There are three ways to get more information on a particular command, by accessing the manual:

git help command

git command --help

man git-command

# Git Commands:

After you edit a file, Git flags it as **modified** because of changes made after the previous commit.

To check file status use the below command:
git status

### Tracking and Staging a New File:

Single File use - git add filename
All files use - git add \*

### Committing a File

git commit -m “made change x,y,z”
**Your message should be short and significant**

### Pushing Changes

After changes are committed the next step is to push it to the remote repo for later reference.
Use: ‘git push origin master’

Renaming/Removing Remotes
use the ‘git remote rename’ command.

Remove
Use ‘git remote rm file name’

Commit Mistakes
You can use the –amend command when you need to alter a commit message or forgot to add some files.
Use ‘git commit --amend’

NOTE: When git reset --hard is used, Git overwrites all changes in the working directory, permanently destroying any uncommitted changes.

All notes came from the below source

[Source credits](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2)



- [Return to main page](https://shawn-ebanks.github.io/Reading-Notes/)