# 在Lubuntu里使用Windows软件

放着好好的Linux软件不用却想去用Windows软件？其实就Windows下各种常用软件没有Linux版(比如《微信电脑版》)，或是很简陋(比如《QQ for Linux》)……

逃离了充斥着各种广告弹窗和安全软件弹窗的Windows世界，又要重返？<span title="《黑客帝国》">*真是“[逃不掉的宿命](https://www.bilibili.com/bangumi/play/ss28888)”*</span>……

## 方案1：《Wine》

如其名，若想要用这个办法，操作复杂够你喝*一壶*的了。

你将要面对：

1. 安装依赖项如天书大典的《`winetricks`》。
2. 去Github寻找《`winetrick-zh`》并`make`它。
3. 配置`wine`的“容器”时，下载各种又大又难下载的容器组件，诸如“`W2KSP4_EN.exe`”。

## 方案2：虚拟机

用后脚跟都能想出来的方案，简单却可行可靠。

比如这个例子：

1. 下载并安装《[VirtualBox](https://www.virtualbox.org)》。
2. 前往[msdn](https://msdn.itellyou.cn/)站点下载你想要的Windows系统镜像文件。
3. 找一份**非Ghost**的系统安装教程，按说明安装。
