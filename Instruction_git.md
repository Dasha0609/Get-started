# **Git step-by-step**

## What the git is?

the most popular version control tool used in software development

![picutre](images/Capture.JPG)

## Local repository creation

To initialize local reposotory shoukd be used command:

      git init

## Status verification

to verify rep status shoud be used command:

       git status

## Add file contents to the index

to update the index of current contect in the working tree should be used:

       git add <file name>

## Captures a snapshot of the projects

to launch a text editor prompting you for a commit message shuld be used:

       git commit

## Commit a snapshot of all changes

to commit a snapshot of all changes in the working directory should be used:

       git commit -a

## Creates a commit with a passed commit message

Passing the -m option will forgo the text editor prompt in favor of an inline message:

       git commit -m

## Differences between commits

to view the changes you made relative to the index (staging area for the next commit). You can stage these changes by using:

       git diff <path>

## Show commit logs

to see your commit or other's commit message history should be used:

       git log

to show the commit id abd comment per-commit only it's easy to use:

       git log --oneline

to be able to see exactly what was merged in where use — graph

       git log --graph

to see all the branches in the history use — all flag.

       git log --all

## Switch branches or restore working tree files

To update files in the working tree to match the version in the index or the specified tree could be used:

       git checkout <hash>

## Branchings

Branching means you diverge from the main-line of development and continue to do work without messing with that main-line.

### Available branches

To check existing in your file available branches you van use:

    git branch

### New branch creation

You can add new branch by running:

    git branch <branch_name>

### Branch deleting 

to delete a branch you should run:

    git branch -d <branchname>
    
### Merging 

Once you have work isolated in a branch, you will eventually want to incorporate it into your main branch. You can merge any branch into your current branch with the:

     git merge

### *Merge conflicts*

*If you want to see which files are unmerged after a merge conflict, run the:*

    git status

*If you change the same part of the same file differently in the two branches you’re merging, You will get a merge conflict.*

## Remote repository

wgy are you using remotd reps....BLA BLA BLA
