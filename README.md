# Ncut
# This code comes from https://www.cis.upenn.edu/~jshi/software/
在运行过程中遇到了两个问题

问题1：需要调用C++文件，matlab缺少编辑器
解决方式：
下载安装gcc,安装过程 https://blog.csdn.net/weixin_42137289/article/details/89442092

问题2：运行报错 Error in eigs_new (line 240)
解决方式：
使用eigs()代替eigs_new,仍然出错，用的是matlab 2017a
不想再装低版本的，就从好友安装版本 matlab 2016a 复制了eigs.m文件
将eigs.m文件修改为eigs_new,成功运行。

已有代码仓库：https://github.com/panji1990/Ncut9



