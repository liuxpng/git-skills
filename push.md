# push 命令

## 常见选项

- \-f 强制推送至远程仓库

## 常见用法

- git push 推送本地当前分支至其跟踪跟踪的远程分支
- git push <remote_name> <branch_name> 推送本地当前分支至指定的远程分支
- git push -f <remote_name> <branch_name> 强制推送本地当前分支至指定的远程分支

## 说明

- git push 默认推送当前分支至其跟踪的远程分支，当且仅当本地仓库只有一个远程仓库名为origin；
- 强制推送 \-f 参数，不推荐使用，是一个危险的命令，会将远程分支的历史改变导致部分代码丢失；
