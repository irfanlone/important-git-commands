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


#### Delete a local branch <local_branch_name>
```sh
 git branch -D <local_branch_name>
```

#### Reset current branch to destination branch
```sh
 git reset --hard <destination_branch_name>
```

#### cherry-pick commit `commit-hash` into current branch
puts the commit `commit-hash` on top of your current branch
```sh
 git cherry-pick 'commit-hash'
```

#### UnCommit `n` commits in current branch
```sh
 git reset --soft HEAD~n
```

#### UnCommit everything in current branch with respect to another branch <branch_name>
```sh
 git reset --mixed <branch_name>
```

#### Delete remote branch <remote_branch_name>
```sh
 git push origin --delete <remote_branch_name>
```
######or
```sh
 git push origin :<remote_branch_name>
```

#### Create local and remote tracking branch
```sh
git checkout -b <branch>
git push -u origin <branch>
```

