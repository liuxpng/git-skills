# mv 命令

## 常见用法

- git mv <old_file_name> <new_file_name> 重命名文件

## 说明

- git mv 命令直接将文件重命名为新名称，并加入到暂存区，之后可直接使用 git commit 命令提交；
- 该命令等价于以下各种操作的集合：
    - 重命名文件，用 mv 命令，或图形化操作；
    - 使用 git rm <old_file_name> 命令删除旧文件；
    - 使用 git add <new_file_name> 命令将新文件加入暂存区；
    
