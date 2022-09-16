# git-workshop

### Git Commands

-  `git init` makes your current directory a local git repository.
-  `git add` lets you add/stage the files you want with the changes or ALL to your commit.
-  `git commit` allows you to commit your changes.
-  `git push` pushes your changes from your local repository to your GitHub repository.
-  `git clone` allows you to clone down an existing repo, whether it is yours or not
-  `git merge` allows you to merge a branch with another branch
-  `git remote` allows you to check, add or remove your HTTPS or SSH link to connect your repo to GitHub
-  `git pull` will pull every change that is commited and pushed to that particular branch
-  `git status` allows you to check untracked, unstaged and staged files in your local repo

### Typical Git Flow

NOTE: This can be done on a new or existing local repository BUT you must create a repo on GitHub.
This is the typical workflow when working with repositories but not all encompassing.

1. Create local repo using `git init`
2. Create files you will be working on
3. Once all changes are done and you are ready to commit, run `git add <filename>` OR `git add <filename> <filename>` OR `git add .`
4. To commit your changes, you may use `git commit` OR `git commit -m "Your commit message"`
5. When commited, you will then run `git push`

## JQUERY SUCKS :)

### More Complex Git Flow

These commands will be more widely used during big projects or when you enter the workforce. These are very important
to learn to make sure you are follow the proper Git workflow when working in a group or large scale project. Typical
Git workflow still applies unless the repo has been cloned down or it already exists.

Given an example that we have recently been added to an existing project with a vast array of files.

In plain English: You will clone down the repo, ensure you have the most up to date code, you will create a new feature branch to keep the main branch protected, work on the files by adding, changing, removing files, you will stage the files changed, then commit and push up to be reviewed by the code review individual.

1. `git clone <link>` this will clone down all the files into your local environment
2. `git pull <branch>` will ensure that you have the most up to date code from the branch you are working on
3. `git checkout -b <branch>` will create a new branch from the one you are currently working
4. `git add .` add/stage all of your changes
5. `git status` will allows you to make sure the files you want are staged
6. `git commit -m "Verbose Message"` to commit your changes
7. `git push -u origin <branch>` will let you create a pull request for your changes to be reviewed before they are merged **IMPORTANT**
