# rebase 命令

## 常见选项

- \-i 以交互式的方式执行 rebase

## 常见用法

- git rebase -i <commit> 在指定提交的基础上以交互式的方式进行 rebase
- git rebase <commit> 在当前分支以指定的提交为基础进行 rebase

## 说明

- pick 抓取commit对象，直接使用，不修改任何内容
- reword 抓取commit对象，使用该对象，但修改其comment
- squash 抓取commit对象，将其合并进前一个commit中
