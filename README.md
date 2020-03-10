# Git rebase use cases

This repository was created to test git rebase features.

## How to show git log
Use command:

```git log```

## History

Master history:

![Master history](docs/master-log.png?raw=true)

## How to rebase x commit from current branch?

Use command:

```git rebase -i <branch name>~<number of commits>```

Example:

```git rebase -i KAM-123~4```

Than use interactive menu to modify your commits.