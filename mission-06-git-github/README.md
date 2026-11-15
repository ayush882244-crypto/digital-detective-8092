# mission 6 - git and github

## 1 task / objective
learn version control concepts practice git workflow create branch open pull request and write git glossary

## 2 work completed
inspected git status staged changes and reviewed log history
created branch update-about and added my learning section to root readme
simulated pull request merge workflow into main
documented git glossary and collaboration concepts

## 3 commands / tools used
- git status: inspect modified and untracked files
- git add: stage files for commit
- git commit: create a permanent snapshot in history
- git log: view commit history
- git branch: list and create branches
- git checkout / switch: switch between branches
- git merge: combine branch history into current branch

## 4 my understanding

### task 6.1 - basic git workflow
| git operation | what it does in your own words |
| --- | --- |
| check repository status | git status shows branch name and lists modified or untracked files |
| stage selected changes | git add prepares specific changed files to be recorded in next commit |
| create a commit | git commit records the staged changes permanently with a message |
| view commit history | git log displays past commits with commit hash and message |

difference between staging and committing:
staging lets you pick which files are ready to be saved while committing takes that snapshot and stores it permanently in git history

### task 6.2 and 6.3 - branch and pull request
- branch created: update-about
- changes made: added my learning section to root readme
- branch merged into main branch
- what is a branch:
  an independent copy of the code where you can work on changes without affecting main branch
- what is a pull request:
  a request on github to review compare and merge changes from a feature branch into main
- why they are useful:
  they allow multiple people to work on different parts safely and review code before merging

### task 6.4 - git command glossary
- initialise a repository: git init creates a new git repository in current directory
- check status: git status shows current branch and status of working files
- stage changes: git add adds modified files to staging area
- commit changes: git commit saves staged changes to local git history with a message
- view history: git log displays list of previous commits
- create or list branches: git branch shows existing branches or creates a new one
- switch branches: git switch or git checkout switches to another branch
- publish changes: git push uploads local commits to remote repository on github
- retrieve remote changes: git pull fetches and merges changes from remote repository to local

## 5 difficulties faced
understanding the difference between git add and git commit

## 6 how i resolved them
practiced staging one file first and checking with git status before committing

## 7 evidence / files
- git branch update-about and commit history

## 8 commit details
commit message: complete git and github collaboration mission
