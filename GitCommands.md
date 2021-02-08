# Git Commands

## GitFlow
* GitFlow is a branching model for Git, which was created by Vincent Driessen. Gitflow Workflow helps with continuous software development by implementing DevOps practices. The Workflow defines a strict branching model designed around the project release by providing a robust framework for managing larger projects. 

The overall flow of Gitflow is:
 
     1. A develop branch is created from master
     2. A release branch is created from develop
     3. Feature branches are created from develop
     4. When a feature is complete, it is merged into the develop branch
     5. When the release branch is done, it is merged into develop and master
     6. If an issue in master is detected, a hotfix branch is created from master
     7. Once the hotfix is complete, it is merged to both develop and master

![Alt Text](https://miro.medium.com/max/1400/1*uUpzVOpdFw5V-tJ_YvgFmA.png)

## Repository
* The repository in Git contains a collection of files of a project and tracks all changes made to files within your project.
* A Git repository is the ` .git/ ` folder inside a project
* Working in repositories keeps projects organized and protected.

![Alt Text](https://github.com/ab344/miniproject1-601/blob/main/assets/repository.png)

## Clone
* Cloning a repository into a newly created directory creates remote-tracking branches for each branch in the cloned repository. It also creates and checks out an initial branch that is forked from the cloned repository’s currently active branch. 

* Click [here](https://git-scm.com/docs/git-clone) to find out more. 
* ` git clone ` 

## Fork
* When you “fork” a project, GitHub will make a copy of the project that is entirely yours; it lives in your namespace, and you can push to it. This allows giving collaborators push access. 
* Click [here](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project) to find out more.

## Branch
* Branching is diverging from the main line of development to continue to do work without messing with that main line. 
* Click [here](https://git-scm.com/docs/git-branch) to find out more.
* ` git branch `

## Commit
* The command, git-commit, records changes to the repository.
* A new commit is a direct child of HEAD, usually the tip of the current branch and the branch is updated to point to it.
* Click [here](https://git-scm.com/docs/git-commit) to find out more. 
* ` git commit `

## Merge
* Joins two or more development histories together.
* The git merge command allows you to take the independent lines of development created by git branch and integrate them into a single branch.
* Click [here](https://git-scm.com/docs/git-merge) to find out more.
* ` git merge `

#####

## Checkout
* Checkout makes it easier to switch between the different version that are in development. This is an important step when using Git. As well as checkout help match the version in the main branch, and select where the development is made. This command also makes looking at old commits as reference easier as well. 
* Click [here](https://git-scm.com/docs/git-checkout) to find out more. 
* ` git checkout `

![Alt text](https://github.com/ab344/miniproject1-601/blob/main/assets/git-checkout.png)

## Push
* Push is used to load what is in local storage to the repository. It can be used to show other developers or update previous data. 
* Click [here](https://git-scm.com/docs/git-push) to find out more. 
* ` git push `

![Alt text](https://github.com/ab344/miniproject1-601/blob/main/assets/git-push.png)

## Pull
* Pull is used to download the the desired files from remote repository to the local machine. It is a commonly used command as developers use this command to keep their project updated between the remote and local versions. 
* Click [here](https://git-scm.com/docs/git-pull) to find out more.
* ` git pull `

![Alt text](https://github.com/ab344/miniproject1-601/blob/main/assets/Git-PUSH-pULL.png)

## Remote 
* Remote is command with many subcommands which let you do several actions to a repository. 
* These subcommands include ` Add, Remove, Show,... ` 
* Click [here](https://git-scm.com/docs/git-remote) to find out more.
![Alt text](https://github.com/ab344/miniproject1-601/blob/main/assets/remote-branches-1.png)

### Remote Add
* This command lets you create and update information on the repository. 
* ` git remote add `

### Remote Remove
* This command lets you remove remote from the local repository, but would not affect server. 
* ` git remote rm `

### Remote Show
* This command lets the user easily manage remotes, including showing and removing current ones as well as adding new ones. 
* ` git remote show `

## Status
* Status is used to show the user information regarding the repository they are working on. This includes which shows current branch, and any modified files. 
* Click [here](https://git-scm.com/docs/git-status) to find out more.
* ` git status `

![Alt text](https://github.com/ab344/miniproject1-601/blob/main/assets/git%20status.png)

## Master Branch
* The master branch is first branch created when initializing with the first commit. This branch symbolizes the best code from the development. This is because a branch point to the commits made, hence why the good code is pushed to the master, while the experimental ones are saved in others.
* Click [here](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging) to find out more.

![Alt text](https://github.com/ab344/miniproject1-601/blob/main/assets/git-branches-merge.png) 
