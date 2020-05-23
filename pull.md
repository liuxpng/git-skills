# pull 命令

## 常见用法

- git pull 拉取当前分支跟踪的远程分支到本地并合并进本地分支
- git pull <remote_name> <branch_name> 拉取指定的远程分支到本地并合并到当前本地分支

## 说明

- 只有当前本地仓库只有一个远程仓库时，且名称为 origin时，才可以直接使用 git pull 命令，省略远程仓库名和分支名；
- 拉取指定远程分支时，可以是任何远程分支；
- git pull 命令本质上是 git fetch 命令与 git merge 命令的合体执行；
