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
- UEngine 运行器（最新版本 1.8.0）
- Wine 运行器（最新版本 2.0.0-2）
- ……

# 自建 apt 软件源
此软件源为开发者自建的软件源，使用这个软件源即可在 apt 获取本开发者开发/适配的应用程序和所需的一些依赖和社区的一些软件以及更新  
这个源并不是为了替代星火应用商店，相反还添加了星火应用商店的 deb 包，因为我的程序也是依靠星火应用商店的，这个源只是为了方便获取我程序的更新而已，仅此  
下面有两个源，根据自己实际情况进行选择，输入以下其中一条命令即可添加完 apt 源  
Gitlink 源（国内推荐）：
```bash
wget https://code.gitlink.org.cn/gfdgd_xi/gfdgd-xi-apt-mirrors/raw/branch/master/sources/gitlink.sh && bash gitlink.sh && rm gitlink.sh
```
Github 源（国外推荐）：
```bash
wget https://gfdgd-xi.github.io/gfdgd-xi-apt-mirrors/sources/github.sh && bash github.sh && rm github.sh
```

# UEngine 运行器（最新版本 1.8.1）
新版本Deepin/UOS发布后，可以在应用商店安装部分官方已适配的安卓应用，对爱好者来说，不能自己安装APK软件包始终差点意思，本程序可以为Deepin/UOS上的UEngine安卓运行环境安装自定义APK软件包，并能发送安装的APK包启动菜单到桌面或系统菜单。   
**本程序依照 GPLV3 协议开源**  
**想要在线获取 UEngine 运行器评分功能的结果？可见：https://gfdgd-xi.github.io/uengine-runner-info**  
程序的部分工作原理可见：[https://www.52pojie.cn/thread-1672077-1-1.html](https://www.52pojie.cn/thread-1672077-1-1.html)  
![image.png](https://storage.deepin.org/thread/202208140944423790_image.png)  
[点此查看更多关于这个程序的介绍](https://gfdgd-xi.github.io/uengine-runner/)和[这个程序的帮助](https://gfdgd-xi.github.io/uengine-runner/Help)  
[![star](https://gitee.com/gfdgd-xi/uengine-runner/badge/star.svg?theme=dark)](https://gitee.com/gfdgd-xi/uengine-runner/stargazers)  
## 下载链接
蓝奏云：[https://gfdgdxi.lanzoui.com/b01oaxnbi](https://gfdgdxi.lanzoui.com/b01oaxnbi)，密码：[2rh3](https://gfdgdxi.lanzoui.com/b01oaxnbi)  
Github：[https://github.com/gfdgd-xi/uengine-runner](https://github.com/gfdgd-xi/uengine-runner)  
Gitee：[https://gitee.com/gfdgd-xi/uengine-runner](https://gitee.com/gfdgd-xi/uengine-runner)  
星火应用商店：spk://store/tools/spark-uengine-runner  
软件源更新：使用方法见下  
UEngine 运行器内部更新：可以使用 UEngine 运行器自带的更新程序进行更新（只支持 1.6.0 及以上版本）  

# Wine 运行器（最新版本 2.1.0）
一个能让Linux用户更加方便运行Windows应用的程序，内置了对wine图形话的支持和各种Wine工具和自制Wine程序打包器、运行库安装工具等等  
同时也内置了基于VirtualBox制作的小白Windows虚拟机安装工具，可以做到只需要用户下载系统镜像并点击安装即可，无需顾及虚拟机安装、创建、虚拟机的分区等等  
Wine 运行器吾爱专版和 Wine 运行器部分组件工作原理可见：[https://www.52pojie.cn/thread-1675552-1-1.html](https://www.52pojie.cn/thread-1675552-1-1.html)  
**本程序依照 GPLV3 协议开源**  
**想要在线获取 Wine 运行器评分功能的结果？可见：https://gfdgd-xi.github.io/wine-runner-info**  
![截图_选择区域_20220826143213.png](https://storage.deepin.org/thread/202208261437088825_截图_选择区域_20220826143213.png)  
更多软件介绍均可见下方 Gitee、Github、Gitlink 下载链接  
[![star](https://gitee.com/gfdgd-xi/deep-wine-runner/badge/star.svg?theme=dark)](https://gitee.com/gfdgd-xi/deep-wine-runner/stargazers)  
## 下载链接
Gitee：[https://gitee.com/gfdgd-xi/deep-wine-runner](https://gitee.com/gfdgd-xi/deep-wine-runner)  
Github：[https://github.com/gfdgd-xi/deep-wine-runner](https://github.com/gfdgd-xi/deep-wine-runner)  
Gitlink：[https://www.gitlink.org.cn/gfdgd_xi/deep-wine-runner](https://www.gitlink.org.cn/gfdgd_xi/deep-wine-runner)  
蓝奏云：[https://gfdgdxi.lanzouj.com/b01nz7y3e](https://gfdgdxi.lanzouj.com/b01nz7y3e)，密码:[7oii](https://gfdgdxi.lanzouj.com/b01nz7y3e)  
软件源更新：使用方法见下  
星火应用商店：[spk://store/tools/spark-deepin-wine-runner](spk://store/tools/spark-deepin-wine-runner)  

# spark-webapp-runtime-runner 运行器（最新版本1.1.0）
一个 spark-webapp-runtime（星火网页应用运行环境）图形化运行器，可以让你更加方便的使用星火网页应用运行环境  
**本程序依照 GPLV3 协议开源**  
![image.png](https://storage.deepin.org/thread/202208140957462252_image.png)   
更多软件介绍均可见下方 Gitee、Github、Gitlink 下载链接  
[![star](https://gitee.com/gfdgd-xi/spark-webapp-runtime-runner/badge/star.svg?theme=dark)](https://gitee.com/gfdgd-xi/spark-webapp-runtime-runner/stargazers)  
## 下载链接
Gitee：[https://gitee.com/gfdgd-xi/spark-webapp-runtime-runner](https://gitee.com/gfdgd-xi/spark-webapp-runtime-runner)  
Github：[https://github.com/gfdgd-xi/spark-webapp-runtime-runner](https://github.com/gfdgd-xi/spark-webapp-runtime-runner)  
Gitlink：[https://gitlink.org.cn/gfdgd_xi/spark-webapp-runtime-runner](https://gitlink.org.cn/gfdgd_xi/spark-webapp-runtime-runner)  
蓝奏云：[https://gfdgdxi.lanzouj.com/b01nzcuqd](https://gfdgdxi.lanzouj.com/b01nzcuqd)，密码:[awcg](https://gfdgdxi.lanzouj.com/b01nzcuqd)  
星火应用商店：[spk://store/tools/spark-webapp-runtime-runner](spk://store/tools/spark-webapp-runtime-runner)

# 程序最新版本更新日志
## UEngine 运行器（最新版本 1.8.1）
**※1、修复在 APK 详细信息中图标可能过大导致无法正常使用的问题**  
**※2、修复 APK 路径带空格无法正常安装的问题**  
3、修复打包器打包的 APK 带下划线“_”无法正常打包的问题  
4、修复打包器下方命令返回过多空白行的问题  
5、修复程序生成的默认图标任然是旧版图标的问题  
![image.png](https://storage.deepin.org/thread/202208302154473781_image.png)  
[![star](https://gitee.com/gfdgd-xi/uengine-runner/badge/star.svg?theme=dark)](https://gitee.com/gfdgd-xi/uengine-runner/stargazers)  

## Wine 运行器（最新版本 2.1.0）
**※1、新增新的 Wine 安装器，并支持将安装的 Wine 打包到 Wine 程序 deb 包中**   
**※2、Wine 打包器打包 Windows 应用支持将 Wine 打包入 deb 内，可以不依赖 Wine（一般不推荐把 Wine 打包入内，推荐用依赖的形式），并支持设置自定义依赖和生成模板**  
**※3、开始初步多语言支持**  
**※4、修复了在没有安装任何 Wine 的情况下使用高级功能导致程序闪退的问题**  
**※5、支持云端自动获取数据配置 Wine 容器**  
**※6、支持手动导入配置文件自动配置 Wine 容器**  
**※7、新增从云端下载 Dll 的功能**  
**※8、修复了 Dll 提取工具不会在 winecfg 中添加原装的问题**  
9、修改错别字（图形话=>图形化）  
10、修复评分功能名称为空也可以上传评分的问题  
11、去除 toilet 依赖，使在 Deepin 23 Preview 上运行更佳  
12、支持删除所有由 Wine 创建的启动器快捷方式  
![截图_选择区域_20220826143213.png](https://storage.deepin.org/thread/202208261437088825_截图_选择区域_20220826143213.png)  
[![star](https://gitee.com/gfdgd-xi/deep-wine-runner/badge/star.svg?theme=dark)](https://gitee.com/gfdgd-xi/deep-wine-runner/stargazers)  

### spark-webapp-runtime-runner 运行器（最新版本1.1.0）
※1、程序全部重构，语言从 Python 转 C++、GUI 从 Tkinter 转 DTK、布局大改，参考了 sgb76 大佬的 Wine 运行器设计图、zty79的桌面快捷方式编辑器的参考布局  
※2、程序新增打包功能  
![截图_选择区域_20220808172505.png](https://storage.deepin.org/thread/202208081725151597_截图_选择区域_20220808172505.png)   
[![star](https://gitee.com/gfdgd-xi/spark-webapp-runtime-runner/badge/star.svg?theme=dark)](https://gitee.com/gfdgd-xi/spark-webapp-runtime-runner/stargazers)  

# Deepin Community Live CD 版本列表
| 版本号 | tiny | mini | full | install | tiny(本地版本) | mini(本地版本) | full(本地版本) | install(本地版本) | 15.11 | 23 |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| 1.4.0(待发布) | ● | ● | ● | ● | ● | ● | ● | ● | ● | × |
| 1.3.0 |  |  | ● |  |
| 1.2.1 |  | ● | ● | ● | | ● |
| 1.2.0 | ● | ● | ● | ● | ● | ● | ● | ● |
| 1.1.1 |  |  | ● |  |
| 1.1.0 | ● | ● | ● |  | ● | ● | ● |
| 1.0.5 |  |  | × |  |
| 1.0.4 |  |  | ● |  |
| 1.0.3 |  |  | ● |  |
| 1.0.2 |  |  | ● |  |
| 1.0.1 |  |  | ● |  |
| 1.0.0-rc |  |  | ● |  |
| 1.0.0-beta |  |  | ● |  |

# ©2020~Now gfdgd xi、为什么您不喜欢熊出没和阿布呢