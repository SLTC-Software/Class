# GIT

The following is general information about Git.

## What is GIT?

* Source code managment system.
* Version control.
* Allow you to manually add files to control.
* The difference between svn and git, git is all local.

## Commands

More information on the [git documentation page](http://git-scm.com/doc)

*Italics* indicate parameters you need to put in.

* Initiate git repository: git init 
* Get difference between two commits: git diff *commit_id-1 commit_id-2*
* Add files to staging area: git add *file_name*
* Add all files to the staging area: git add -A
* Commit: git commit -m "*commit message, preferable starting with a verb and no more than a sentance*"
* Setup remote: git remote add *remote_name remote_url*
* Get repo from github and merge into local: git pull *origin master*
* Get repo from github (this is the only way without initializing the local): git clone *url*
* See all commits: git log
* See staging area: git status
* See changes from the parent: git show *commit_id*
* If the changes do not work out, back to last commit. **DANGER** you can never get the changes back: git reset --hard
* Make a new branch: git branch *branch_name*
* Checkout a branch: git checkout *branch_name*
* Make a branch and switch to it: git checkout -b *branch_name*

## Setup 

* git config --global color.ui auto
* git config --global user.name "*First and Last Names*"
* git config --global user.email "*email@domain.com*"

### Make your life easier

We can add a git completion script by moving [git-completion.bash](git-completion.bash) to your home git directory. You get to your home directory and move the file from your git bash using:
```{bash}
cd ~
mv old_path/git-completion.bash ./git-completion.bash
```

Confused? Try [this video](https://www.youtube.com/watch?t=38&v=IfLhXM4RnB4) It also gives instructions on how to use the other two files. 

## Installation

* [Windows](https://www.udacity.com/wiki/ud775/install-git/install-git-windows)
* [Mac](https://www.udacity.com/wiki/ud775/install-git/install-git-mac)
* [Linux](https://www.udacity.com/wiki/ud775/install-git/install-git-linux)

# GitHub

* Use GitHub private repos to collaborate, backup code, and maintain a clean development environment
* Use Wiki to document 
* Use Issues to report/track bugs
* Remember a forked private repo is still private
* If you prefer side-by-side diffs, check out [Split diffs](https://github.com/blog/1884-introducing-split-diffs)
* GitHub uses [Markdown](https://help.github.com/articles/github-flavored-markdown/) for README, wikis (though this can be changed), and issues

# More information

I really like this [free class](https://www.udacity.com/course/how-to-use-git-and-github--ud775). Most of the material in our git introduction came from this class. 
