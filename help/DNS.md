# 由DNS设置引起的“打不开本站”的问题的解决办法

即修改DNS设置。设置一个合适的DNS服务器就行了。

## Windows

<small>参考自CSDN博客《[解决打不开 xxx.github.io的万能解决方法](https://blog.csdn.net/weixin_43769878/article/details/109217112)》</small>

以`Windows XP`为例。

1. 如图，在“`控制面板`”中找到“`网络链接`”，选中自己所用网络，右键，`属性`。
![DNS-Windows-1](https://wyz-2015.github.io/help/img/Win-1.png)
2. 如图，选中“`Internet 协议 (TCP/IP) (IPv4)`”，点击“`属性`”，设置DNS服务器地址。建议直接填“`114.114.114.114`”，可用、好记。想用其他的DNS服务器请参阅上方文献。
![DNS-Windows-2](https://wyz-2015.github.io/help/img/Win-2.png)
3. 成功进入。
![DNS-Windows-3](https://wyz-2015.github.io/help/img/Win-3.png)

## Linux

### 偶尔访问的用户

通过修改“`/etc/resolv.conf`”文件以设置DNS服务器。当次有效，重启后若还要访问就需要重复以下上述操作了。

以`Lubuntu`为例。

1. 在“`终端`”里键入：
``` bash
sudo vim /etc/resolv.conf
```
2. 如图，将
``` conf
nameserver xxx.xxx.xxx.xxx
```
改为
``` conf
nameserver 114.114.114.114
```
![DNS-Linux-1](https://wyz-2015.github.io/help/img/Lin-1.png)
<br><small>图中使用《`Vim`》编辑文件，实际操作时可以使用你喜爱的编辑器。</small>

### 经常访问的用户

啊……我懒得写了。看[这里](https://jingyan.baidu.com/article/e9fb46e15d83517521f766f1.html)吧。

## MacOS

*@钟俊川*
