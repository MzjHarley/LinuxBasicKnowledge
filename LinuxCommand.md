|Author|Date|
|---|---|
|MZJ|3/8,2022|

---

|command|function|
|---|---|
| [command] --help| 命令帮助|  
|whatis [command] |命令帮助 | 
|man [command] |命令帮助  |
|info [command] |命令帮助  |
|help [InnerCommand] |内置命令帮助  |
|tap |补全文件或提示  |
|shutdown -r [time]  |重启  ||
|shutdown -h [time]  |关机  |
|echo [contents] >/>> [file] |输入到文件  |
|cat [file] |打开文件  |
|cat > [file] |创建文件并写入  |
|touch [file] |创建文件  |
|ls -a [directory] |查看目录所有文件  |
|ls -l [file] |查看文件详细信息 | 
|history |历史命令  |
|passwd |更换密码  |
|pwd|打印当前目录|
|rm -f [file] |强制删除文件  |
|rm -rf [directory] |强制删除目录  |
|stat [file]|查看文件详细信息  |
|who |查看当前用户  |
|whoami |查看当前用户  |
|file [file]   |文件类型  |
|whereis [command]| 命令位置  |
|mv [OtherDirectory] |[file] 文件迁移 | 
|mv [file] [file1] | 同一目录下文件更名 | 
|tac [file] |从文件最后一行读取至结束 | 
|which [command]  |文件位置及别名  |
|type [command]  |命令类型  |
|clear |清屏  |
|chmod {ugo}{+-=}{rwx} [file/directory]|改变文件目录的权限|
|mkdir [-p] [directory]|创建目录，参数表示递归创建|
|rmdir [-p] [directory]|删除空目录，参数表示递归删除|
|cp[-r,-p][file/directoy][directory]|将文件或目录复制到指定目录下，默认复制文件，-r复制目录，-p保留文件属性|
|cp -r [directory][inexistentDirectory]|复制时更名|
|more [file]|分页查询，enter换行，翻页|
|less [file]|分页查询，可搜索 /+content|
|head -n [num] [file]|显示文件的前num行，默认显示前10行|
|head -c num [file]|显示文件的前num个字节|
|tail -n [num] [file]|显示文件的后num行，默认显示后10行|
|tail -c num [file]|显示文件的前num个字节|
|tail -f [file]|动态显示文件末尾(并非一行)内容，在文件更新时同样工作|
|chown [user] [file/directory]|将file/directory所有者改为user|
|chgrp [group][file/directory]|将file/directory所有组改为group|
|useradd [user]|添加用户user|
|userdel -r [user]|删除用户及其主目录|
