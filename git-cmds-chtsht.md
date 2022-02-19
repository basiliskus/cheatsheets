# Git Commands Cheatsheet

<!-- MarkdownTOC -->

- [Git Commands Cheatsheet](#git-commands-cheatsheet)
  - [Commands](#commands)
    - [Setup](#setup)
    - [Create](#create)
    - [Local Changes](#local-changes)
    - [Commit History](#commit-history)
    - [Branches & Tags](#branches--tags)
    - [Update & Publish](#update--publish)
    - [Merge & Rebase](#merge--rebase)
    - [Undo](#undo)
    - [Inspect & Compare](#inspect--compare)
    - [Tracking Path Changes](#tracking-path-changes)
    - [Share & Update](#share--update)
    - [Temporary Commits](#temporary-commits)
    - [Ignoring Patterns](#ignoring-patterns)
    - [Help & Documentation](#help--documentation)
  - [Best Practices](#best-practices)
  - [Commit Message Guidelines](#commit-message-guidelines)
  - [Glossary](#glossary)
  - [References](#references)

<!-- /MarkdownTOC -->

## Commands

### Setup

Set the name you want attached to your commit transactions  
`$ git config --global user.name "[name]"`

Set the email you want attached to your commit transactions  
`$ git config --global user.email "[email address]"`

Enable helpful colorization of command line output  
`$ git config --global color.ui auto`

### Create

Clone an existing repository  
`$ git clone ssh://user@domain.com/repo.git`

Create a new local repository  
`$ git init`

### Local Changes

Show modified files in working directory, staged for your next commit  
`$ git status`

Add a file as it looks now to your next commit (stage)  
`$ git add <file>`
`$ git add -p <file>`

Add all current changes to the next commit  
`$ git add .`

Changes to tracked files  
`$ git diff`

Diff of what is staged but not yet committed  
`git diff --staged`

Unstage a file while retaining the changes in working director  
`git reset <file>`

Commit your staged content as a new commit snapshot  
`git commit -m <descriptive message>`

Commit all local changes in tracked files  
`$ git commit -a`

Commit previously staged changes  
`$ git commit`

Change the last commit  
_Don‘t amend published commits!_  
`$ git commit --amend`

### Commit History

Show all commits, starting with newest  
`$ git log`

Show changes over time for a specific file  
`$ git log -p <file>`

Who changed what and when in `<file>`  
`$ git blame <file>`

### Branches & Tags

List all existing branches  
`$ git branch`

Create a new branch based on your current HEAD  
`$ git branch <new-branch>`

Switch HEAD branch  
`$ git checkout <branch>`

Create a new tracking branch based on a remote branch  
`$ git checkout --track <remote/branch>`

Delete a local branch  
`$ git branch -d <branch>`

Mark the current commit with a tag  
`$ git tag <tag-name>`

### Update & Publish

List all currently configured remotes  
`$ git remote -v`

Show information about a remote  
`$ git remote show <remote>`

Add new remote repository, named `<remote>`  
`$ git remote add <shortname> <url>`

Download all changes from `<remote>`, but don‘t integrate into HEAD  
`$ git fetch <remote>`

Download changes and directly merge/integrate into HEAD  
`$ git pull <remote> <branch>`

Publish local changes on a remote  
`$ git push <remote> <branch>`

Delete a branch on the remote  
`$ git branch -dr <remote/branch>`

Publish your tags  
`$ git push --tags`

### Merge & Rebase

Merge `<branch>` into your current HEAD  
`$ git merge <branch>`

Rebase your current HEAD onto `<branch>`  
_Don‘t rebase published commits!_  
`$ git rebase <branch>`

Abort a rebase  
`$ git rebase --abort`

Continue a rebase after resolving conflicts  
`$ git rebase --continue`

Use your configured merge tool to solve conflicts  
`$ git mergetool`

Use your editor to manually solve conflicts and (after resolving) mark file as resolved  
`$ git add <resolved-file>`  
`$ git rm <resolved-file>`

### Undo

Discard all local changes in your working directory  
`$ git reset --hard HEAD`

Discard local changes in a specific file  
`$ git checkout HEAD <file>`

Revert a commit (by producing a new commit with contrary changes)  
`$ git revert <commit>`

Reset your HEAD pointer to a previous commit  
...and discard all changes since then  
`$ git reset --hard <commit>`

...and preserve all changes as unstaged changes  
`$ git reset <commit>`

...and preserve uncommitted local changes  
`$ git reset --keep <commit>`

### Inspect & Compare

Show the commit history for the currently active branch  
`git log`

Show the commits on branchA that are not on branch  
`git log branchB..branchA`

Show the commits that changed file, even across rename  
`git log --follow [file]`

Show the diff of what is in branchA that is not in branch  
`git diff branchB...branchA`

Show any object in Git in human-readable format  
`git show <SHA>`

### Tracking Path Changes

Delete the file from project and stage the removal for commit  
`git rm <file>`

Change an existing file path and stage the move  
`git mv <existing-path> <new-path>`

Show all commit logs with indication of any paths that move  
`git log --stat -M`

### Share & Update

Add a git URL as an alias  
`git remote add [alias] [url]`

Fetch down all the branches from that Git remote  
`git fetch [alias]`

Merge a remote branch into your current branch to bring it up to date  
`git merge [alias]/[branch]`

Transmit local branch commits to the remote repository branch  
`git push [alias] [branch]`

Fetch and merge any commits from the tracking remote branch  
`git pull`

### Temporary Commits

Save modified and staged changes  
`git stash`

List stack-order of stashed file changes  
`git stash list`

Write working from top of stash stack  
`git stash pop`

Discard the changes from top of stash stack  
`git stash drop`

### Ignoring Patterns

Save a file with desired patterns as .gitignore with either direct string matches or wildcard globs  
`logs/`
`*.notes`
`pattern*/`

System wide ignore pattern for all local repositories
`git config --global core.excludesfile <file>`

### Help & Documentation

Get help on the command line
`$ git help <command>`

## Best Practices

- **Commit Related Changes**: A commit should be a wrapper for related changes. For example, fixing two different bugs should produce two separate commits. Small commits make it easier for other developers to understand the changes and roll them back if something went wrong. With tools like the staging area and the ability to stage only parts of a file, Git makes it easy to create very granular commits.

- **Commit Often**: Committing often keeps your commits small and, again, helps you commit only related changes. Moreover, it allows you to share your code more frequently with others. That way it‘s easier for everyone to integrate changes regularly and avoid having merge conflicts. Having few large commits and sharing them rarely, in contrast, makes it hard to solve conflicts.

- **Do Not Commit Half-done Work**: You should only commit code when it‘s completed. This doesn‘t mean you have to complete a whole, large feature before committing. Quite the contrary: split the feature‘s implementation into logical chunks and remember to commit early and often. But don‘t commit just to have something in the repository before leaving the office at the end of the day. If you‘re tempted to commit just because you need a clean working copy (to check out a branch, pull in changes, etc.) consider using Git‘s «Stash» feature instead.

- **Test Code Before You Commit**: Resist the temptation to commit something that you «think» is completed. Test it thoroughly to make sure it really is completed and has no side effects (as far as one can tell). While committing half-baked things in your local repository only requires you to forgive yourself, having your code tested is even more important when it comes to pushing/sharing your code with others.

- **Write Good Commit Messages**: Begin your message with a short summary of your changes (up to 50 characters as a guideline). Separate it from the following body by including a blank line. The body of your message should provide detailed answers to the following questions:
  › What was the motivation for the change?
  › How does it differ from the previous implementation?
  Use the imperative, present tense («change», not «changed» or «changes») to be consistent with generated messages from commands like git merge.

- **Version Control is not a Backup System**: Having your files backed up on a remote server is a nice side effect of having a version control system. But you should not use your VCS like it was a backup system. When doing version control, you should pay attention to committing semantically (see «related changes ») - you shouldn‘t just cram in files.

- **Use Branches**: Branching is one of Git‘s most powerful features - and this is not by accident: quick and easy branching was a central requirement from day one. Branches are the perfect tool to help you avoid mixing up different lines of development. You should use branches extensively in your development workflows: for new features, bug fixes, ideas…

- **Agree on a Workflow**: Git lets you pick from a lot of different workflows: long-running branches, topic branches, merge or rebase, git-flow… Which one you choose depends on a couple of factors: your project, your overall development and deployment workflows and (maybe most importantly) on your and your teammates‘ personal preferences. However you choose to work, just make sure to agree on a common workflow that everyone follows.

## Commit Message Guidelines

- https://gist.github.com/turbo/efb8d57c145e00dc38907f9526b60f17
- https://github.com/joelparkerhenderson/git_commit_message
- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
- https://www.conventionalcommits.org/en/v1.0.0/

## Glossary

- **commit**: a Git object, a snapshot of your entire repository compressed into a SHA
- **branch**: a lightweight movable pointer to a commit
- **clone**: a local version of a repository, including all commits and branches
- **remote**: a common repository on GitHub that all team members use to exchange their changes
- **fork**: a copy of a repository on GitHub owned by a different user
- **pull request**: a place to compare and discuss the differences introduced on a branch with reviews, comments, integrated tests, and more
- **HEAD**: representing your current working directory, the HEAD pointer can be moved to different branches, tags, or commits when using `git checkout`

## References

- https://www.git-tower.com/blog/git-cheat-sheet/
- https://github.com/github/training-kit/blob/master/downloads/github-git-cheat-sheet.md
- https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf
