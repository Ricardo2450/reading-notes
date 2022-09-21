# Revisions and the Cloud

>## *[Git a comprehensive guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2)*

## *What is git*?
+ git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. 

+ relies on local operations because most necessary information can be found in local resources.
+ It also tracks every single change applied to any file or directory. Also, it is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. 

**Git can reside in three main states**:
+ **Committed** - Data is securely stored in a local database
+ **Modified** - File has been changed but not committed to the database
+ **Staged** - Flagged a file’s changed version to be committed in the next snapshot

>## Setting up a Git Repository
***Follow these steps using the Terminal or Command Line***:

**Step 1** - Switch to the target project’s directory. Ex. cd file name 

**Step 2** - Use the git init command.

+ Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.

**Step 3** - To start tracking these repository files, perform an initial commit by typing the following:
+ git add *.c
+ git add LICENSE
+ git commit -m “any message here”

Now, your files are tracked and there’s an initial commit. We will discuss the particular commands in detail soon.

>## Cloning
+ You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL.
    * git clone file name

>## Checking file status
+ To determine the state of files, utilize the git status command:
    + git status

> ## Tracking and Staging a New File
+ **Single File** - Track one file only by using the following format:
    + git add file name

+ **All Files** - Track all files in a repository by using the following command:
    + git add *

***Note*** - After using these commands, files are tracked and staged for committing.

>## Committing a File
+ After staging one or multiple files, you should commit the changes and record what you did within the commit message.
    + git commit -m “made change x,y,z”

+ **Committing All Changes**:
    + git commit -a

>## Pushing Changes
+ Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.
    + git push origin master

>## Remote Repositories
+ versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

[Return to home page](../README.md)
