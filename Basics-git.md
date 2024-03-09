# Git --> Git is a Version Control System.

Version Control System is a tools that helps to track changes in code.

Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development.

# Features of Git?

- Tracks history
- Free and open source
- Supports non-linear development
- Creates backups
- Scalable
- Supports collaboration
- Branching is easier
- Distributed development

# let’s explain a scenario before Git:-

- Developers used to submit their codes to the central server without having copies of their own
- Any changes made to the source code were unknown to the other developers
- There was no communication between any of the developers-

# Now let’s look at the scenario after Git:

- Every developer has an entire copy of the code on their local systems
- Any changes made to the source code can be tracked by others
- There is regular communication between the developers

# Branch in Git

Branch in Git is used to keep your changes until they are ready. You can do your work on a branch while the main branch (master) remains stable. After you are done with your work, you can merge it with the main office.

# Steps to push project

0th step :-
git init
initialize an existing directory as a Git repository

1st step :-
cd - change directory
syntax - cd (path of file) --> from this directory will be changed and now you are ready to do changes for that file.

2nd step :-
git status --> tells about the status, like any changes made or not.

3rd step :-
git add (file name) / . {for to add all changed files} --> this will add all changes to the file and ready to be committed.

4th step :-
git commit -m "Message" --> this will commit the file. Now our branch will become ahead of the main branch i.e. changes were made only on our device(laptop) and it is yet to be pushed to github.

5th step :-
git push origin master --> this uploads local repo content to remote repo.

6th :- for error: src refspec main does not match any
git push -u origin master
git commit -m "Message"
git push origin master

# FOR STATRING NEW PROJECT

make github repo <br>
git init <br>
git remote add origin (github repo link) <br>
git remote -v --> to verify remote <br>
git branch --> to check branch <br>
git branch -M main --> to rename branch <br>
git push origin (branch name like main/master)

# Branch Commands

- git branch --> to check branch
- git branch -M main --> to rename branch
- git checkout (branch name) --> to navigate
- git checkout -b (new branch name) --> to create new branch
- git brach -d (branch name) --> to delete existing branchf

# Merging Code

- git diff (branch name) --> to compare commits, branches, files and more
- git diff --staged --> diff of what is staged but not yet commite
- git merge (branch name) --> to merge 2 branches

# Pull Request

- It lets you tell others about changes you've pushed to a branch in a repository on GitHub.

# Pull Command

git pull origin main
used to fetch and download content from a remote repo and immediately update the local repo to match that content.

# Resolving Merge Conflicts

An event that takes place when Git is unable to automatically resolve differences in code between two commits.

git log --> to get history of all the commits. from this we get hash value.

# Undoing Changes

Case 1 : staged changes<br>
git reset (file name) --> for perticular file <br>
git reset --> for all file

Case 2 : commited changes (for one commit)<br>
get reset HEAD-1

Case 3 : commited changes (for many commits)<br>
git reset (commit hash)<br>
git reset --hard (commit hash)

# Fork

A fork is a new repository that shares code and visibility settings with the original "upstream" repository.<br>
Fork is a rough copy
