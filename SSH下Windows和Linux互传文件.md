##SSH下Windows和Linux互传文件

* 1.Install 安装lrzsz
>  pi@raspberrypi:~ $ sudo apt-get install lrzsz
>  
>Attention：我使用的命令是apt-get install ，如果你的是其他请注意查找安装方法，单独的rz或sz是不行的

###1、从win向linux上传文件执行命令如下

>  pi@raspberrypi:~ $ rz

>此时会弹出一个Windows的对话框，选择你要上传的文件就可以了，注意文件不能为空文件，也就是大小为0字节的文件，文件为空文件是不行的，会一直处于上传的状态

### 2、从linux下载传文件到win执行命令如下
> pi@raspberrypi:~ $ sz REMAD.md  

>sz加要下载的文件名即可。
>此时会弹出一个Windows的对话框，选择你要保存的文件夹就可以了。

Ps：其实安装方法，可以下载二进制包自己编译安装.




