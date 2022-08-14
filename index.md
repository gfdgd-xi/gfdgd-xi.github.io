# UEngine 运行器（最新版本 1.8.0）
新版本Deepin/UOS发布后，可以在应用商店安装部分官方已适配的安卓应用，对爱好者来说，不能自己安装APK软件包始终差点意思，本程序可以为Deepin/UOS上的UEngine安卓运行环境安装自定义APK软件包，并能发送安装的APK包启动菜单到桌面或系统菜单。   
**本程序依照 GPLV3 协议开源**  
![image.png](https://storage.deepin.org/thread/202208140944423790_image.png)
[点此查看更多关于这个程序的介绍](https://gfdgd-xi.github.io/uengine-runner/)和[这个程序的帮助](https://gfdgd-xi.github.io/uengine-runner/Help)  

## 下载链接
蓝奏云：[https://gfdgdxi.lanzoui.com/b01oaxnbi](https://gfdgdxi.lanzoui.com/b01oaxnbi)，密码：[2rh3](https://gfdgdxi.lanzoui.com/b01oaxnbi)  
Github：[https://github.com/gfdgd-xi/uengine-runner](https://github.com/gfdgd-xi/uengine-runner)  
Gitee：[https://gitee.com/gfdgd-xi/uengine-runner](https://gitee.com/gfdgd-xi/uengine-runner)  
星火应用商店（已审核通过）：spk://store/tools/spark-uengine-runner  
软件源更新：使用方法见下  
UEngine 运行器内部更新：可以使用 UEngine 运行器自带的更新程序进行更新（只支持 1.6.0 及以上版本）  

# Wine 运行器（最新版本 2.0.0）
一个能让Linux用户更加方便运行Windows应用的程序，内置了对wine图形话的支持和各种Wine工具和自制Wine程序打包器、运行库安装工具等等  
同时也内置了基于VirtualBox制作的小白Windows虚拟机安装工具，可以做到只需要用户下载系统镜像并点击安装即可，无需顾及虚拟机安装、创建、虚拟机的分区等等  
**本程序依照 GPLV3 协议开源**  
![image.png](https://storage.deepin.org/thread/202208140946222834_image.png)
## 下载链接
Gitee：https://gitee.com/gfdgd-xi/deep-wine-runner  
Github：https://github.com/gfdgd-xi/deep-wine-runner  
Gitlink：https://www.gitlink.org.cn/gfdgd_xi/deep-wine-runner  
蓝奏云：https://gfdgdxi.lanzouj.com/b01nz7y3e，密码:7oii  
软件源更新：使用方法见下  
星火应用商店：spk://store/tools/spark-deepin-wine-runner  

# 添加软件源
此软件源为开发者自建的软件源，使用这个软件源即可在 apt 获取本开发者开发/适配的应用程序以及更新  
下面有两个源，根据自己实际情况进行选择，输入以下其中一条命令即可添加完 apt 源  
Gitlink 源（国内推荐）：
```bash
wget https://code.gitlink.org.cn/gfdgd_xi/gfdgd-xi-apt-mirrors/raw/branch/master/sources/gitlink.sh && bash gitlink.sh && rm gitlink.sh
```
Github 源（国外推荐）：
```bash
wget https://gfdgd-xi.github.io/gfdgd-xi-apt-mirrors/sources/github.sh && bash github.sh && rm github.sh
```