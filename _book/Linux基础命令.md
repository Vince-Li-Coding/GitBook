#Linux基础命令

**/ 斜杠         \反斜杠        |竖杠        .  表示当前目录      .. 表示上一层目录**   



### cd   当前目录下的子目录名

`change directory`

 cd   当前目录下的子目录名       进入该目录

cd .. 跳入上一层目录

cd ~  直接进入家目录

cd .. / ..  跳入上一层的上一层目录

cd -   跳入上一次使用的目录



### /

根目录,类似于windows中的盘符

一个路径的第一个斜杠就是根目录



### ~

本用户的家目录





### ls

显示当前目录下的文件



### pwd

显示当前正在操作的路径

`print wrok directory`



### touch

**touch 文件名**

创建一个文件



### mkdir   目录名

创建一个目录



### rm   文件名

删除此文件

rm   -r   目录名    删除此目录

-f  强制删除

(命令  选项   参数)



### clear  清屏



### tree

以目录树的形式显示当前目录下的目录和文件

tree  目录名   显示指定目录下的目录树





### cp 文件名   位置

复制文件到指定位置

`cp 目录/文件    目标目录/` 

cp 命令不加参数不可以复制文件夹



### mv   文件名   位置

移动,剪切文件

如果位置不存在,则重命名此文件为位置名