# branch 命令

## 常见选项

- \-d 删除本地分支
- \-D 强制删除未合并的分支
- \-r 删除本地远程分支

## 常见用法

- git branch <branch_name> 创建分支
- git branch -d <branch_name> 删除本地分支
- git branch -D <branch_name> 强制删除未合并的分支
- git branch -d -r <branch_name> 删除远程分支

## 说明

- 常用的有：创建分支，删除本地分支；
- 注意：当使用-D选项时，确认要删除的分支是否真的要删除；
- 注意：使用-r选项时需谨慎，删除本地远程分支，push后会删除对应的远程分支；
