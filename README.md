avsocks 科学操长城软件  by avplayer.org 社区
=======


avsocks 科学操长城软件，由2部分构成，一个运行在能科学上网的服务器上，一个运行在不能科学上网的电脑上。
两个部分实际上为同一个可执行文件，都是  avsocks

在能科学上网的电脑上执行 avsocks -d ，加 -d 进入后台模式

在不能科学上网的电脑上执行 avsocks -d --avserver 能科学上网的电脑的名字或ip

好了，本地 4567 端口就开了 socks5 代理了。


# 编译

依赖 boost 和 openssl
