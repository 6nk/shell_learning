## ls

ls 字符匹配

- ls -l my_scr[ai]pt

- ls -l f[a-i]ll

- ls -l f[!a]ll

## mkdir
创建目录
- mkdir -p new_dir/sub_dir/under_dir 批量创建目录和子目录

## tree

- tree 该命令能够以一种美观的方式展示目录、子目录以及其中的文件。

## ps

- --forest 该参数可以显示进程的层级信息

## du

显示当前目录下所有的文件、目录和子目录的占用空间大小，按照从目录层级最底层逐级向上

- -c 显示所有已列出文件总大小
- -h用户易读的格式
- -s显示每个输出参数的总计

du -shc *

## history

可以唤回历史列表中任意一条命令，只需输入惊叹号和命令在历史列表中的编号即可

- !20