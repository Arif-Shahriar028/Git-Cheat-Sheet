### Merge specific files from Git branches (suppose file.txt from branch2 to branch1)

```
$ git checkout --patch branch2 file.txt
```

### Add a file to previous commit

```
$ git commit --amend
```

if you dont want to edit the messege:

```
$ git commit --amend --no-edit
```

### problem: Your branch and 'origin/main' have diverged

solution:
`$ git reset --hard origin/master`
Then that just resets my (local) copy of master (which I assume is screwed up) to the correct point, as represented by (remote) origin/master.

WARNING: You will lose all changes not yet pushed to origin/master.

### problem: fatal: refusing to merge unrelated histories

solution:
`$ git pull origin branch_name --allow-unrelated-histories
