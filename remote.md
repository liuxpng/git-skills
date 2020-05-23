# remote 命令

## 常见选项

- \-v 列出远程仓库的配置列表

## 常见用法

- git remote -v 列出远程仓库的配置列表
- git remote add <remote_name> <remote_url> 增加远程仓库，设置别名为<remote_name>
- git remote rm <remote_name> 删除远程仓库<remote_name>
- git remote show <remote_name> 查看远程仓库<remote_name>的详情
- git remote rename <old_remote_name> <new_remote_name> 重命名远程仓库<old_remote_name>为<new_remote_name>

## 说明

- \-v 参数以列表的形式查看远程仓库，仅会列出远程仓库的别名及地址，及拉取和推送的地址；
- show 命令可以查看具体某个远程仓库的信息，包括分支的跟踪，默认推送的分支，拉取的分支；
