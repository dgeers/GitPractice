#Git Cheatsheet
**Name:** Jojo Karlin
**Date:** January 17, 2017

Git reference = https://www.git-scm.com/docs

Here are commands we used:

1. Setting up Github to handshake with my computer:
git config --global user.name "[name]
git config --global user.email "[email address]
git config --list
git init
git remote add origin [URL of your remote repo]
git remote -v
git status


2. Using/Revising Git files
git log    -- Show commit logs
git add .  --  Add file contents to the current index
git commit -m "[clear message describing the changes you made]"  -- commit your revision for upload


git push origin master  --- Send new version of file to Github