# git-cheatsheet


### config global information
```sh
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

### config local repo information
```sh
git config user.name "Your Name Here"
git config user.email your@email.com
```

### list configuration
```sh
git config --list
```

### check out a particular commit.
```sh
git checkout <sha1>
```

### remove local branch
```sh
git branch -d the_local_branch
```

### remove a remote branch
```sh
git push origin :the_remote_branch
```

### sync remote repo
```sh
git remote add origin <server>
```

### init repo
```sh
git init
```

### add specific file
```sh
git add “nombre_de_archivo”
```

### add all files
```sh
git add .
```

### Commit message
```sh
git commit –m “mensaje”
```

### ammend files to last commit
```sh
git commit --amend
```

###
```sh
git diff <source_branch> <target_branch>
```

###
```sh
git tag 1.0.0 commit_id
```

###
```sh
git log
```
