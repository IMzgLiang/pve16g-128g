# pve16g-128g  

这是一个脚本，用于将16g的pve系统，扩容到更大的硬盘，比如128g  

条件：
要保证pve系统能够联网，因为要安装一个软件parted

使用：
apt-get update 使用前要更新一下软件包列表

通过git clone 命令下载代码以后，进入pve16g-128g目录

给expansion文件赋予执行权限 chmod 777 expansion

执行 ./expansion

执行完，即可在pve的网页端看到结果
