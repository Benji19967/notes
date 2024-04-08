# Git

# Resolving merge conflicts

Suppose, 

```shell
git pull origin master
```

created a merge conflict. 

You can manually resolve the files or:

```shell 
git checkout --theirs/ours <path-to-file>
git add <path-to-file>
```

to keep local (`--ours`) or remote (`--theirs`) changes.
