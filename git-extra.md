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