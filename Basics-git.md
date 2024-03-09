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
make github repo
git init
git remote add origin (github repo link)
git remote -v        --> to verify remote 
git branch           --> to check branch
git branch -M main   --> to rename branch
git push origin main / (master)

# Branch Commands
- git branch         --> to check branch
- git branch -M main --> to rename branch
- git checkout (branch name)  --> to navigate
- git checkout -b (new branch name)  --> to create new branch