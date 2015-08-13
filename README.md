# What is GIT?

* Source code managment system.
* Version control.
* Allow you to manually add files to control.
* The difference between svn and git, git is all local.

# Commands

More information on the [git documentation page](http://git-scm.com/doc)

*Italics* indicate parameters you need to put in.

* Initiate git repository: git init 
* Get difference between two commits: git diff *commit_id-1 commit_id-2*
* Add files to staging area: git add *file_name*
* Add all files to the staging area: git add -A
* Commit: git commit -m "*commit message, preferable starting with a verb and no more than a sentance*"
* Setup remote: git remote add *remote_name remote_url*
* Get repo from github and merge: git pull *origin master*
* Get repo from github: git clone *url*
* See all commits: git log
* See staging area: git status
* See changes from the parent: git show *commit_id*
* If the changes do not work out, back to last commit. **DANGER** you can never get the changes back: git reset --hard
* Make a new branch: git branch *branch_name*
* Checkout a branch: git checkout *branch_name*
* Make a branch and switch to it: git checkout -b *branch_name*

# Setup 

* git config --global color.ui auto
* git config --global user.name "*First and Last Names*”
* git config --global user.email "*email@domain.com*”

