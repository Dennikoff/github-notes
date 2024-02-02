# github-notes

It is a sandbox for tesing git-hub commands 
and some notes to quickly find and use the right
command. Here I use only **CLI** to use git.

## Basic

### add files
```shell
  git add .
```

### commit with add
```shell
  git commit -am "message"
```


## Working with stash

### stash
```shell
git stash [--include-untracked]
```

### get from stash 

```shell
  git stash pop
```

## Working with branches

### checkout with create new branch

```shell
  git checkout -b "branch-name"
```

### change branch head 

Without checkout to new branch
```shell
  git branch -f "branch-from" "branch-to"
```

With checkout

```shell
  git checkout -B "branch-from" "branch-to"
```

