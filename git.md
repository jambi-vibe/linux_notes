# Git

## Repository

Initialize the current directory as a Git repository:

`git init`

*adds .git dir to the current dir, tracks changes in the root recursively(all the way down). 
Ignores all duplicate non-changed files.
can be done after or before the creation of empty files. won't track empty dir

Show the root directory of the current repository:

`git rev-parse --show-toplevel`

## Changes

Check repository status

`git status`

*checks git, will show naything that is tracked but not added, added and ready to commit, and if nothing is ready tracked, the branch is displayed.

Add all changes to Git staging:

`git add .`

*stages files for commit.
'.' means all files and dir recursivley from the root
can add single files
````bash

git add note.md

````

Commit added changes:

`git commit -m "message"`

*used for short two or three word description of what was changed.
makes changes "official" on the repo, though can be undone(as descriped later)

## Setup Github and Git repository link

# Check existing remote repository link

`git remote -v`

*displays the connected github repository, typically named "origin"
used to check which Github repo that local repo is connected to

# Add remote repository link

`git remote add  origin <URL>`

*used to initialized the connected Github repo
````bash

git remote origin https://github.com/username/repo_name

````
get repo_name when you set up the repo on github, will provide https link to copy

# Change romote repository link

`git remote set-url origin <URL>`

## Pushing

# First push and set upstream

`git push -u origin main`

# Pushes after initial push

`git push`

