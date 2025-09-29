## What is git? Why do we need it?
git is a version control system that works locally on your computer. 
you need version control when coding 
then github takes it further with a centralized place for teams to contribute and stay up to date with codebase. 



## What are the top 10 commands? What do they do?
1. git clone <https://name-of-the-repository-link>
2. git branch <branch-name> - creates branch for devs to work in parallel on same project. 
3. git branch - lets you view branches.
4. git branch -d <branch-name> - deletes a branch
5. git checkout - switches from one branch to another
6. git checkout -b <branch-name> - switches to new branch AND creates at same time
7. git status - checks if branch is up to date, what changes have been made, etc. 
8. git add - includes changes of a file into next commmit.
9. git add -a - add everything at once
10. git commit -m "commit message"
11. git push <remote> <branch-name>
12. git push - once you do remote once, can just ujse push
13. git pull <remote> - gets updated from remote repo
14. git revert <hashcode> - undo changes we've made
15. git merge - integrates your feature branch with all of its commits back to master branch.

## How do you open a PR?
git checkout -b <branch-name>
#make changes, yada yada. commits along the way. 
git status
git add -a(to add changes you've made)
git commit -m "final change"
git push origin <branch-name> 
go to github, open a PR, fill in description. once approved, merge. 