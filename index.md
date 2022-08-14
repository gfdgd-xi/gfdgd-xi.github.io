# UEngine 运行器
新版本Deepin/UOS发布后，可以在应用商店安装部分官方已适配的安卓应用，对爱好者来说，不能自己安装APK软件包始终差点意思，本程序可以为Deepin/UOS上的UEngine安卓运行环境安装自定义APK软件包，并能发送安装的APK包启动菜单到桌面或系统菜
单。   
<iframe src="https://gfdgd-xi.github.io/uengine-runner/" width=99%>  

# Wine 运行器
一个图形化了以下命令的程序  
```bash
env WINEPREFIX=容器路径 wine（wine的路径） 可执行文件路径
```
让你可以简易方便的使用 wine  
<iframe src="https://gfdgd-xi.github.io/deep-wine-runner/" width=99%>  


# 添加软件源
Gitlink 源（国内推荐）：
```bash
wget https://code.gitlink.org.cn/gfdgd_xi/gfdgd-xi-apt-mirrors/raw/branch/master/sources/gitlink.sh && bash gitlink.sh && rm gitlink.sh
```
Github 源（国外推荐）：
```bash
wget https://gfdgd-xi.github.io/gfdgd-xi-apt-mirrors/sources/github.sh && bash github.sh && rm github.sh
```