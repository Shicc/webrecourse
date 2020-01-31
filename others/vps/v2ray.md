# V2ray的使用

2020/01/31 更新

* Windows推荐使用V2rayN，[GitHub下载](https://github.com/2dust/v2rayN/)。使用和更新都比QV2ray方便，但感觉性能没有QV2ray好，Android端也是Kitsunebi性能比V2rayNG好。
* iOS客户端可以使用最新的shadowrocket，需手动配置。
* 不同系列的软件二维码，url不能互扫互加。同系列比如都带有v2ray字样的可以，shadowrocket的二维码只shadowrocket可以用，Kitsunebi同样。

## Linux & Windows & Mac

我嫌用配置文件很麻烦，所以就找了一个有GUI的，方便使用。Qv2ray，[下载链接](https://github.com/lhy0403/Qv2ray)，找到releases，自己下载所需版本。

Linux下，点击下载得到的Qv2ray.AppImage文件，Windows下解压压缩包后点qv2ray.exe，就可以打开软件，先打开软件，在顶部的*preferences*里可以设置中文，点击OK后重启即可生效，先设置中文，之后的设置我就按照中文界面来说。

去这个 [链接](https://github.com/v2ray/v2ray-core/releases/) 下载v2ray核心文件，必须有这个，不然运行不起。Linux的64位系统下载*v2ray-linux-64.zip*,Windows的64位系统*v2ray-windows-64.zip*,下载完后解压。

在Linux系统下，进入主目录下的：/.config/qv2ray,创建vcore文件夹,把上一步解压得到的几个文件复制到vcore文件夹下。Windows系统下，第一步中解压得到的文件夹中进入/config/qv2ray,创建vcore文件夹,把上一步解压得到的十几个文件复制到vcore文件夹下。

打开软件后点击添加,导入源里就可以选择几种添加方式，选择VMess和二维码，在左下角粘贴上所给的URL，点击导入。

这个软件好像还是测试版，有些小问题，不过不影响使用。每次打开软件后，都在状态栏找到它点击右键，再找到系统代理，选择启用系统代理，就可以用了

## Windows

上面一条里讲的Windows可以正常用，Windows下还有更多v2ray的软件，最为丰富，可自己下载来操作。
* V2rayN:[Link](https://github.com/2dust/v2rayN/)
* V2rayW:[Link](https://github.com/Cenmrev/V2RayW/)
* Clash for Windows:[Link](https://github.com/Fndroid/clash_for_windows_pkg)

## Android

推荐下载Kitsunebi或V2RayNG，和以前的SSR操作基本一样。

### Kitsunebi:
百度网盘：[Link](https://pan.baidu.com/s/1qssCfvxZ2DTZXRpRiPF51g) 提取码: 8ftm

Google Play:[link](https://play.google.com/store/apps/details?id=fun.kitsunebi.kitsunebi4android&hl=en_US)

### V2RayNG:

百度网盘：[Link](https://pan.baidu.com/s/1qssCfvxZ2DTZXRpRiPF51g) 提取码: 8ftm

Google Play:[link](https://play.google.com/store/apps/details?id=com.v2ray.ang)

Github:[Link](https://github.com/2dust/v2rayNG)

以Kitsunebi为例：安装软件后，点击上方加号，添加节点，从URL导入，然后你就能看到节点了，再点上分加号，，选择规则集，点加号，选择新建绕过局域网和大陆，然后点击才出现的这个配置。返回到最开始的界面，点击这个节点的横条，点击下方按钮，然后就可以正常使用了。

## iOS
找一个美区ID下载Kitsunebi。
