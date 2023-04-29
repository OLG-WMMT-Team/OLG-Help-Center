---
title: 游戏安装教程
author: kKsk
date: 2023-04-28
category: Jekyll
layout: post
---

## 第一步：下载并解压游戏

[下载链接](111)

下载完成后请自行解压游戏，压缩包内自带一个WMMT6R文件夹，双击打开然后将其拖放出来其实就可以了

> ##### 提示
> 
> 推荐使用Bandzip进行解压
{: .block-tip }

## 第二步：下载并配置游戏运行库

游戏的运行需要用到以下几个运行库  

```
1. C++所有运行库
2. Runtime
3. Node.js
```

在此我提供以上所有运行库的下载方式，请您遵照教程继续进行前先下载完毕

[运行库下载链接（提取码:1145）](https://www.123pan.com/s/RY30Vv-aEV9h.html)  

**下载完成后，则可以开始配置游戏运行库了**  

### 配置C++所有运行库  

1. 打开该文件

![pic1](https://pic2.imgdb.cn/item/644d2cbc0d2dde5777e1aa69.jpg)

2. 双击打开**DirectX Repair.exe**(若需要申请管理员权限则点击**是**)

![pic2](https://pic2.imgdb.cn/item/644d2d350d2dde5777e215a4.jpg)
 
3. 点击**检测并修复**，等待其修复完毕即可

![pic3](https://pic2.imgdb.cn/item/644d2da70d2dde5777e27e00.jpg)

> ##### 警告
>
> 若最后修复C++过程中遇到无法安装问题，请继续即可  
> 一般并不影响游戏运行
{: .block-danger }

### 配置Runtime

1. 打开该文件

![pic1](https://pic2.imgdb.cn/item/644d2f300d2dde5777e416ce.jpg)

2. 将图片内文件拖放解压到**C盘根目录**即可

![pic2](https://pic2.imgdb.cn/item/644d2f780d2dde5777e45ee2.jpg)

3. 右键，以**管理员方式**运行**REG.bat**文件

> 若一瞬间弹出了几个黑色cmd窗口则说明已成功

![pic3](https://pic2.imgdb.cn/item/644d2ff40d2dde5777e4e50f.jpg)

### 配置Node.js

1. 打开该文件

![pic1](https://pic2.imgdb.cn/item/644d30980d2dde5777e58b41.jpg)

2. 点击**Next**(一直点击Next即可，不需要更改任何内容，傻瓜式下一步安装）

![pic2](https://pic2.imgdb.cn/item/644d30c50d2dde5777e5bffe.jpg)

3. 安装完毕后就可以了

## 第三步：注册iauthdll.dll文件

1. 打开WMMT6R/AMCUS文件夹
2. 在文件管理器的地址栏处点击一下，然后**右键复制路径**

![pic1](https://pic2.imgdb.cn/item/644d32210d2dde5777e77bf4.jpg)

3. 在Windows徽标上右键，并点击**终端管理员**

![pic2](https://pic2.imgdb.cn/item/644d32d10d2dde5777e83342.jpg)

> ##### 注意
> 
> 若您的系统是Windows7/8/8.1，打开终端的方式可能与图并不一样  
> 您需要遵照以下方法，使用cmd进行代替  
> 1. 点击**Windows徽标**  
> 2. 在所有软件中，找到**命令提示符**  
> 3. 右键，点击**以管理员身份运行**  
> 4. 打开完毕  
> 
> [若文字表示看不懂的话可参考该链接](http://www.65ly.com/a/07/1670375990127435.html)
{: .block-warning }

4. 在终端窗口中，输入代码: `cd 地址` (**地址**两字请使用**你刚才复制的地址**所替换)，输入完毕后**按下回车**即可

如图示例：

![pic3](https://pic2.imgdb.cn/item/644d35140d2dde5777eac525.jpg)

5. 输入代码： `regsvr32 iauthdll.dll`，**按下回车**即可

如图示例：

![pic4](https://pic2.imgdb.cn/item/644d35ad0d2dde5777eb5e5b.jpg)

按下回车后，**必须出现**以下图片所示窗口，才算成功，**否则请检查您是否有使用管理员运行**

![pic5](https://pic2.imgdb.cn/item/644d35e40d2dde5777eb9d51.jpg)