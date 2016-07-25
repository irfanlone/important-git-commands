# important-git-commands
Some important and handy git commands

#### explicitly tells you which branches are tracking which remote branches
```sh
 git remote show origin
```

#### Show helpful guides that come with Git
```sh
 git help -g
```

#### Combine `n` commit's together
```sh
 git rebase -i HEAD~n
```


#### Delete a branch <branch_name>
```sh
 git branch -D <branch_name>
```

#### Reset current branch to destination branch
```sh
 git reset --hard <destination_branch_name>
```

#### UnCommit `n` commits in current branch
```sh
 git reset --soft HEAD~n
```

#### UnCommit everything in current branch with respect to another branch <branch_name>
```sh
 git reset --mixed <branch_name>
```
