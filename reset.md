# reset 命令

## 常见选项

- \-\-hard 同时将工作区，暂存区恢复到指定提交

## 常见用法

- git reset HEAD 让暂存区恢复成和HEAD一致
- git reset HEAD <file_name> 将暂存区文件<file_name>恢复成和HEAD中的版本一致
- git reset --hard HEAD 让工作区和暂存区恢复成和HEAD一致
- git reset --hard <commit> 将工作区和暂存区恢复成和指定的<commit>一致

## 说明

- \-\-hard 选项使用时需谨慎，若非明确某些更改是放弃的，不需要的，不要使用该选项；
