#Wired-brain-receipes

<!-- Git is a type of VCS which stands for Version Control System
This is a sample website made as part of [_Learn Enough™ Git to BeDangerous_](https://www.learnenough.com/git-tutorial), possibly the greatestbeginner Git tutorial in the history of the Universe. You should totally [check it out](https://www.learnenough.com/git-tutorial), and be sure to [jointhe email list](https://www.learnenough.com/#email_list) and[follow @learnenough](http://twitter.com/learnenough) on Twitter.After finishing _Learn Enough™ Git to Be Dangerous_, you'll know enough Gitto be _dangerous_. This means you'll be able to use Git to track changes inyour projects, back up data, share your work with others, and collaboratewith programmers and other users of Git.

3 Stages of it Project: Working directory > Staging Area (index) > .git dir (aka repo)

PRocess of creating a repo:
1- Check folder using pdw command to make note of repo location.
Create Mainfolder/child_folder (mkdr + folder name without space).

2- Create files using touch command. Use ls command to check if files have been created.
3- Before initializing folder, check if it is not already a repo with the command git Status.
4- Use git init to initialize current filder as the git repo.
5- Use git status once again to check if folder is a repo. Any untrcked files will be marked red.
6- Next we need to push everything to github, but first we have to add all files to the repo using
git add . or git git add -A.
7- Commit ( save all modified documents) using the command git commit -m "type message here"
8- Check status of repo using git status, once more, and the follow the rest of the instructions on github.com
(steps may be different if folder is already a repo)

git remote add origin https://github.com/iGyalchester/test2.git
git branch -M master
git push -u origin master

add, commit, and push

Couple of usefl commands:
cd | change directory
pwd | displays all directory in folder
ls | lists files in directory
touch | create new empty file
mkdir | use to create empty folder
git status --short | Used to see what changes have been applied to repo folder(?)
M = Modified files, A = New files added to staging area, ?? = New file is untracked by git
git diff | used to compare files inside of repo folder
git commit | -a -m = commit everything in staging area
git mv | rename file
git rm | remove file from folder! Also stops git from tracking the file!
git rm --cashed | to untrack but not delete file.
git checkout | -b to create a new brand and checkout
git branch | crates a branch without checking out
git stash | save to new branch. list - shows list of work in progress stached. show - shows what files have been changed
WIP | not a command but it means work in progress
git reset | --soft: use when trying to add more changes before committing. --hard to start over (deletes all staged work)
-->