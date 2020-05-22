# diff 命令

## 常见选项

- \-\-cache 将暂存区与头指针指向的提交进行比较

## 常见用法

- git diff <file_name> 将工作区与暂存区的文件<file_name>进行比较
- git diff --cache <file_name> 将暂存区文件<file_name>与头指针指向的提交中的同个文件进行比较

## 说明

- 默认情况下 git diff 命令是将工作区与暂存区的文件进行比较；
- 增加 \-\-cache 选项时，git diff 命令是将暂存区与头指针指向的版本进行比较；
