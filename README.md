_This is the repository for the git-masters_

# Workshop
Provide an opportunity to learn something about git. 

# First workshop
Simulate a day to day task

## Assingnations

| Assignee         | Task           | Title              | Description                                              | Status |
| -------------    |:-------------: | -----:             | -----:                                                   | -----: |
| | 1 			       | Bug in total       | Currenttly total add x and y it should substract instead | open |
| | 2              | Bug in total       | Remove the total++                                       | open |
| | 3              | Add division       | Add division to current console.log                      | open |
| | 4              | Add multiplication | Add multiplication to current console.log                | open |
| | 5              | User Model         | Add a field age = 12 to user model                       | open |
| | 6              | User Model         | Add a field country 'Tsalal' to user model               | open |
| | 7              | User Model         | Add a field cell '819-121-1111' to user model            | open |
| | 8              | User Model         | Add a field email 'test@email.com' to user model         | open |
| | 9              | User Model         | Add a field isActive false to user model                 | open |
| | 10             | User Model         | Add a field isLogged false to user model                 | open |

## Do it

1. Create a feature branch then do the following
    ```sh
    git fetch
    git checkout release/sprint-0
    modifier fichier (do your task)
    git checkout -b feature/yourname
    git add .
    git commit -m "your message"
    modifier fichier (add new console.log at the end of the file with your name)
    git add -u
    git commit -m "your message"
    ```
2. Wait that presenter merge one of the new branches into release/sprint-0
    ```sh
    git fetch
    ```
3. Do an interactive rebase... and squash the two commits
    ```sh
    ??? invent how to do it
    ```
4. Run test your code
    ```sh
    node source.js
    ```
5. Push your code
6. Ask the presenter to merge your code into release/sprint-0

# Basic Git commands
* git fetch: fetch all the remote modifications
* git pull: is like a git fetch followed with a git merge
* git status: show the changes made to latest snapshot 
* git merge: merge changes from two branch
* git branch: list current branches
* git branch branch-name: creates a new branch with name branch-name
* git checkout branch: checkout an existing branch
* git checkout -b branch-name: create a new branch branch-name then checked it out.
* git checkout -: return to previous branch
* git log: log the changes made to a branch 
* git show: show the changes made

# More Git commands
* git rebase: rebase 
* git bisect: allow to find a working copy of your code
* git reflog: show the reference log
* git cherry-pick: pick a commit hash or reflog
* git reset: reset the current HEAD to another commit or branch

# More topics
* .gitignore
* git alias
* git config

# Some usefull links
* https://learngitbranching.js.org/
* https://book.git-scm.com/book/en/v2
* https://services.github.com/on-demand/downloads/github-git-cheat-sheet/


