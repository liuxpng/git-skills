# checkout 命令

## 常见选项

- \-b 创建新分支并切换到该分支

## 常见用法

- git checkout <branch_name> 基于当前最新的commit创建一个新分支，名为<branch_name>
- git checkout -- <file_name> 放弃工作区文件<file_name>的更改
- git checkout -b <branch_name> 基于当前最新的commit创建一个新分支，名为<branch_name>，并切换到该分支

## 说明

- 创建分支时，可以在命令后增加一个可选参数：某个commit的md5值，表示基于该commit创建一个分支；
- 使用 git checkout -- <file_name> 时，放弃的时工作区的更改，而非暂存区
