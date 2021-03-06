# log 命令说明

## 常见选项

- \-\-oneline 以每个提交一行的形式显示提交历史
- \-\-graph 以分支图形化的形式显示提交历史
- \-\-all 显示所有分支的提交历史
- \-n <number> 显示指定数量个提交历史

## 常见用法

- git log <选项> [branch_name] 以指定格式显示指定分支的提交历史
- git log --oneline 以每个提交一行的形式显示所有分支的提交历史
- git log --graph 以图形化的形式显示所有分支的提交历史
- git log --oneline --graph -n 5 以每个提交为一行，总体为图形化的形式显示最近5个提交历史

## 说明

- git log 命令默认显示所有分支的提交详情；
- 所有选项均可同时使用，效果叠加；
