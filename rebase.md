# rebase 命令

## 常见选项

- \-i

## 常见用法

- git rebase -i <commit>
- git rebase <commit>

## 说明

- pick 抓取commit对象，直接使用，不修改任何内容
- reword 抓取commit对象，使用该对象，但修改其comment
- squash 抓取commit对象，将其合并进前一个commit中
