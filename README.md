# GIT TASK


## Version Control
Version control is a system that manages changes to a project's source code, facilitating collaboration among multiple contributors. It maintains a centralized repository where developers can commit changes, create branches for new features or bug fixes, and merge modifications seamlessly. This collaborative approach ensures a systematic and organized development process, preventing conflicts and enhancing team efficiency.  

## Git vs GitHub
- Git: Git is a distributed version control system (DVCS) that manages and tracks changes in source code during software development. It allows developers to work offline, commit changes locally, and collaborate with others.

while

- GitHub: GitHub is a web-based platform and hosting service that utilizes Git for version control. It provides a centralized location in the cloud where developers can store and collaborate on Git repositories. GitHub extends Git's functionality with additional features like issue tracking, pull requests, and project management tools.


## GitHub Alternatives
1. Bitbucket
2. GitLab
3. SourceForge

## Git Fetch vs Git Pull

## Git Fetch
- git fetch is a command that downloads new changes from a remote repository to your local machine.
- It updates your local repository, including the remote branches, but it does not automatically merge those changes into your current working branch.
- Use git fetch when you want to see what changes exist in the remote repository before deciding to integrate them into your local branch.

## Git Pull 
- git pull is a command that not only fetches changes from a remote repository but also automatically merges them into your current working branch.
- It is a shorthand for running git fetch followed by git merge, effectively updating your local branch with the latest changes from the remote repository.
- Use git pull when you want to quickly update your local branch with the latest changes from the remote and automatically merge them.

## Git Rebase
In simple terms, `git rebase` is used to integrate changes from one branch into another. The command is:
```bash
git rebase branch-name

```

## Git Cherry-pick

In simple terms, git cherry-pick is used to apply a specific commit from one branch to another. The command is:

```bash
git cherry-pick commit-hash
```

