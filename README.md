# MyOS
OS
操作系统课程设计项目

Member:沙威   1452745
Member:刘加祯 1452814
Member:张子健 1452831

开发环境

Linux Ubuntu 14.04
bochs 2.6.8
sublime-text 2

使用方法

确保你已经装了Ubuntu 和 Bochs
在terminal里面运行下面的命令完成配置，如果是中国IP可能需要切换Ubuntu的源（163的源速度较快）.
$ sudo  apt-get update 
$ sudo  apt-get install build-essential 
$ sudo  apt-get install xorg-dev                                        
$ sudo  apt-get install bison   
$ sudo  apt-get install libgtk2.0-dev
$ sudo  apt-get install nasm
$ sudo  apt-get install vgabios

首先打开到目标文件夹下,然后运行:
$ cd OSCourseProject /Tinix-master
$ sudo make image
$ bochs 
$ 回车再输入 c 进入

项目分工

张子健负责进程调度算法的修改，添加了一个用户级应用时钟作为一个单独的进程，美化系统界面。
沙威主要添加了一个用户级应用日历作为单独进程。
刘加祯主要添加了一个用户级应用计算器作为单独进程。

托管地址：

https://github.com/BlackZIjian/MyOS/graphs/contributors
