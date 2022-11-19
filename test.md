lol kek korvalol 

Лимоны желтые 
I love memes

Блаблабла

Лимоны желтые 
I love memes

Апельсины оранжевые 
Яблоки бывают и зелеными и красными 

Абд
лол кек 

Эта информация была добавлена из локального репозитория

Эта информация была добавлена в удаленном репозитории

Изменения

Local info added

# Git Instruction Continued

To fix changes made in your file and save its current status, use "git commit -m"message"" command.

It's always a good idea to check that your file did change before committing changes.

A block of these 3 commands must follow every change you want to save and commit:
git status - git add file.name - git commit -m"message".

To create a new branch in a repository, use "git branch new_branch_name" command

To see all branches existing, use "git branch" command

To switch from one branch to another, use "git checkout branch_name" command

To merge any branch with the current one, use "git merge branch_name" (name of the branch we want to merge with the current one)

If you no longer need any branch, you can delete it by using "git branch -d branch_to_delete" command

If you want to exclude any files (like images)from pushing/uploading, you can exclude them using 'git ignore" command

To switch branches, use "git checkout branch_name" command

When we work in two branches at the same time, a conflict of changes may arise when different changes were made in the same text block. When we try to merge these branches later, Git will inform you about a conflict and suggest that you choose what particular changes you want to save.

To display and see your commits in a nice graph/tree, use "git log --graph" command

To download an existing remote (Git) repository to your PC, use "git clone repository_address" command

The "git clone" command is compound: it both downloads all changes, and tries to merge all branches on a local PC and in a remote repository

To download all info from the current repository and automatically merge it with your version, use "git pull" command

To upload your version of repository to a remote repository, use "git push" command. This action REQUIRES AUTHORIZATION in a remote repository.

## How To Set Collaboration

1. Create account on GitHub.com
2. Create a local repository
3. Connect your local repo with a remote one (using GitHub help/prompts)
4. Push your local repo to a remote (GitHub) repo (you may need to authorize in a remote repo)
5. Make changes "on another computer"
6. Pull the actual status from a remote repository

To suggest your changes and request integrating (merging) these changes in a remote repository, use "pull request" command

## How to make pull request

* Fork a remote repository
* Clone YOUR version of the remote repository
* Create a new branch and make changes in THIS NEW BRANCH
* Commit changes
* Send (push) your version to your GitHub repo
* On GitHub site, choose "pull request" command

