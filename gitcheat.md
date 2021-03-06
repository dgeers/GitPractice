#Git Cheatsheet

**Name:** Doug Geers

**Date:** January 17, 2017

FYI, the Git reference is here: https://www.git-scm.com/docs

- Git Markdown quick guide: https://help.github.com/articles/basic-writing-and-formatting-syntax/#headings


#Here are commands we used:

##1. Setting up Github to handshake with my computer:

- `git config` --global user.name "[name]

- `git config` --global user.email "[email address]

- `git config` --list

- `git init`

- `git remote` add origin [URL of your remote repo]

- `git remote -v ` -- 

- `git status`  -- Show the working tree status


##2. Revising/Staging Git files

- `git log`    -- Show commit logs

- `git add .`  --  Add file contents to the current index.  Usefulness of this stage is that you might have local files that you don't want to add and send to collaborators.  

- `git commit -m "[clear message describing the changes you made]" ` -- commit your revision for upload

- `git push origin master`  --- Send new version of file to Github. Origin is your computer.  Master is master branch of Github tree for this project.  These may be changed.

- `git reset` - Will remove all items from the commit list

- `git ignore` - Will remove one item from your commit list

