<script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?807ee27dfca59506248e7f74c812ca3d";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script>

# 作品列表
- 自建 apt 软件源
- UEngine 运行器
- Wine 运行器
- Deepin Community Live CD
- Waydroid 运行器
- ……

# 自建 apt 软件源
## 如何添加该 apt 源？
```bash
wget http://apt.gfdgdxi.top/sources/github.sh; bash github.sh; rm github.sh
```

# UEngine 运行器
虽然通过Deepin/UOS应用商店已经能够安装部分安卓应用，但对于安卓应用爱好者来说，不能自由地安装任意APK软件包实在是不尽如人意。本软件可以实现在Deepin/UOS上安装任意APK软件包，并能将其启动图标发送到系统桌面或启动器中，方便用户快速启动它。  
![](https://storage.deepin.org/thread/202212181918041904_%E5%9B%BE%E7%89%87.png)
## 地址
https://gitee.com/gfdgd-xi/uengine-runner  
https://github.com/gfdgd-xi/uengine-runner  

# Wine 运行器
Wine运行器是一个能让Linux用户更加方便地运行Windows应用的程序。原版的 Wine 只能使用命令操作，且安装过程较为繁琐，对小白不友好。于是该运行器为了解决该痛点，内置了对Wine图形化的支持、Wine 安装器、微型应用商店、各种Wine工具、自制的Wine程序打包器、运行库安装工具等。  
它同时还内置了基于Qemu/VirtualBox制作的、专供小白使用的Windows虚拟机安装工具，可以做到只需下载系统镜像并点击安装即可，无需考虑虚拟机的安装、创建、分区等操作，也能在非 X86 架构安装 X86 架构的 Windows 操作系统（但是效率较低，可以运行些老系统）。  
而且对于部分 Wine 应用适配者来说，提供了图形化的打包工具，以及提供了一些常用工具以及运行库的安装方式，以及能安装多种不同的 Wine 以测试效果，能极大提升适配效率。  
且对于 Deepin23 用户做了特别优化，以便能在缺少 i386 运行库的情况下运行 Wine32。同时也为非 X86 架构用户提供了 Box86/64、Qemu User 的安装方式  
![](https://storage.deepin.org/thread/202210022215217037_%E6%88%AA%E5%9B%BE_%E9%80%89%E6%8B%A9%E5%8C%BA%E5%9F%9F_20221002221112.png)  
## 地址
https://gitee.com/gfdgd-xi/deep-wine-runner  
https://github.com/gfdgd-xi/deep-wine-runner  
## QQ 交流群
762985460

# Waydroid 运行器
Waydroid运行器是可以通过GUI形式半自动配置Waydroid的工具，使用户使用Waydroid更为方便。Waydroid本身存在很多因AOSP未考虑PC用户而产生的问题(如没有自带Houdini,默认英语,默认非小窗模式)而使用户使用起来非常难受,本运行器支持以GUI形式自动化安装以及配置Waydroid，并会创建快捷控制的快捷方式，可以用于玩游戏/刷视频/Android开发等。  
## 地址
https://gitee.com/gfdgd-xi/waydroid-runner  
https://github.com/gfdgd-xi/waydroid-runner  
## QQ 交流群
872491938

# Deepin Community Live CD
Deepin Community Live CD 是一个让用户能够在系统出现问题时进行临时的维护和工作的镜像，预装了较为常用的维护工具，部分安装镜像还带系统安装功能。  
## 地址
https://gitee.com/gfdgd-xi/deepin-community-live-cd/  
## QQ 交流群
881201853

<h1 id="copyright">©2020~Now gfdgd xi</h1>
<script>
var d = new Date();
document.getElementById("copyright").innerHTML="©2020~" + d.getFullYear() + " gfdgd xi";
</script>
