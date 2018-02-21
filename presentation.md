---
title: Git Introduction
author: David Kurka
date: 05/12/2017
header-includes:
    - \institute[Imperial College London]{\includegraphics[width=3cm]{imperial-logo.png}}
---


# Why

## Organisation

![](./finalversion.png)


## Organisation (closer example)

![](./thiagofinal.jpeg)

## Team work

![](./screenshot_2018-02-21_15-36-14.png)


# Tools

## Git is not Github!

- **Git** = tool
- Github = **a** cloud service
- Alternatives:
  - Gitlab (better, less popular)
  - Bitbucket

## Tools

- Command line (default)
- Git Gui (default)
- Editor integration (matlab, atom, visual studio code)
- Gui clients:
   - Github desktop
   - Gitg
   - TortoiseGit

# Git basics

## Hidden Mess

![](local.png)

## Working Tree, Staging Area and Git Directory

![](areas.png)


## Basic commands


![](git-local-remote.png)

## Basic commands

~~~
git status
git add
git diff
git commit
git log
~~~


## File Status

![](lifecycle.png)




## Remote Server

~~~
git clone
git pull
git push
~~~

## Github + Git


~~~
git remote add origin https://github.com/try-git/try_git.git
git push origin master
git pull origin master
~~~


## Advanced operations

- merging
- branching
- forks/pull requests

# Workflows

## Branching worflows - Long-running branches

![](lr-branches-2.png){width=45%} ![](successsfull-branching-model.png){width=45%}


## Branching worflows - Topic Branches

![Before](./topic-branches-1.png){width=45%}
![After](./topic-branches-2.png){width=45%}

## Github Workflows

- Fork
- Pull Requests
- Testing/Deploy
- Code Review
<!-- ## Forks and Pull Requests -->
