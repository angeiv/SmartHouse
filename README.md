树莓派智能家居项目
==
---
项目说明
--
本项目由运行[Raspbian]（基于[Debian]）系统的[树莓派]（英文：Raspberry Pi）`B型 Rev2.0 UK 开发板`，运行其上的[PHP]和运行在[Android]的APP控制端组成。

**项目链接**

  - [Raspberry Pi系统上的C语言源代码][1]
  - [Android APP源代码][2]
  - [PHP源代码][3]
  - [项目主页][6]

本文想法由`亓根火柴`发表在CSDN上的[《用树莓派通过Java实现远程控制电灯》][4]所启发，在此感谢原作者，以下是部分参考：

> 我们用[Yeelink]的手机客户端（浏览器也行）去改变服务上设备的状态（0/1），然后让树莓派检测该设备上的状态，最后根据获取到的状态控制继电器。


**启发：**我们可以用Android APP访问由树莓派搭建的PHP网页，对应的网页在树莓派系统中`创建或者修改`文件，`系统每隔几秒检测下文件的内容`，以此来达到模拟Yeelink的按钮操作，达到控制电器的目的。

##Project Explanation
This project is consist of `Raspberry Pi Rev2.0 UK Board` running [Raspbian] \(based on Debian\),php on it and using Android APP to control it.

**Project Link**

  - [C programming languages source code on Raspberry Pi][1]
  - [Android APP source code][2]
  - [PHP source code][3]
  - [Project Homepage][6]

This article is inspired by the article [《用树莓派通过Java实现远程控制电灯》][4] posted on [CSDN Blog][5] by `亓根火柴`,thanks for the author,some referances are as follows:

> 我们用[Yeelink]的手机客户端（浏览器也行）去改变服务上设备的状态（0/1），然后让树莓派检测该设备上的状态，最后根据获取到的状态控制继电器。
(We use [Yeelink] mobile client (browser also) to change the status of the service equipment (0/1), and then let the raspberry pi detect the status of the device, according to the acquired state to control appliances. --translated by google)

**Inspired ideas:**
We have access PHP webpages by using Android APP,these websites `create or modify` files on Raspberry Pi,`system detects these files every few seconds`,to simulate the button on Yeelink,in order to control appliances.

---

版本修订记录
--

**0.1 内部测试版本 [2014-07-27]**
  - 确定思路
  - 由受到启发的思路来`创建项目`
  - `创建说明文件`

**x.x 公开测试版本 [20xx-xx-xx]**

**x.x 候选版本 [20xx-xx-xx]**

**x.x 稳定版本 [20xx-xx-xx]**


##Revision
**0.1 Alpha [2014-07-27]**
  - Confirm thought
  - `create project` from inspired ideas
  - `Create readme`

**x.x Beta [20xx-xx-xx]**

**x.x Release Candidate [20xx-xx-xx]**

**x.x Stable [20xx-xx-xx]**

---
使用材料
--

以下列举了本项目使用到的`硬件`、`软件`等:

* 硬件部分
      - 树莓派   - 一个小型控制中心，运行Linux系统
      - 手机     - 运行有Android系统带有Wi-Fi的手机
      - 继电器   - 控制电路开关
      - 用电器   - 受控电器
* 软件部分
      - Android  - 安卓系统
      - PHP      - PHP网页开发
      - Raspbian - Linux系统
      - ADT      - 安卓开发工具，包含Eclipse + ADT 插件,Android SDK 工具,Android 平台工具
      - JDK      - Java开发环境

##Material

This project contains `hardware`,`software` are as follows:

* Hardware
      - Raspberry Pi - A small control center,running Linux operating system
      - Phone        - A phone running Android operating system with Wi-Fi
      - Relays       - Control power switch
      - Appliances   - Control appliances
* Software
      - Android  - Android Operating System
      - PHP      - PHP website
      - Raspbian - Linux Operating System
      - ADT      - Android Developer Tools,including Eclipse + ADT plugin,Android SDK Tools,Android Platform-tools

---
许可证
--

GPL v2

##License

GPL v2

---
致谢
--

本文使用Markdown语言编写，采用[Dillinger]在线编译器编写，
Dillinger是一个完全开源项目。

##Acknowledgements
This article uses Markdown language, and using [Dillinger], a online markdown editor, Dillinger is a 100% open source project.

---
关于我
--

张幸 (Angeiv)

个人主页 http://zhangxing.tk/blog

CSDN博客 http://blog.csdn.net/angeiv

电子邮件 447407567#qq.com（把 # 换成 @）

##About Me

Zhang Xing (Angeiv)

Personal Homepage http://zhangxing.tk/blog

CSDN Blog http://blog.csdn.net/angeiv

E-mail  447407567#qq.com (replace # with @)

---
参考文献
--

```
[1] 亓根火柴. 用树莓派通过Java实现远程控制电灯[EB/OL]. [2013-12-29]. http://blog.csdn.net/qigenhuochai/article/details/17661845.
```
##References
```
[1] 亓根火柴. 用树莓派通过Java实现远程控制电灯[EB/OL]. [2013-12-29]. http://blog.csdn.net/qigenhuochai/article/details/17661845.
```

[Raspbian]:http://raspbian.org/
[Debian]:http://debian.org
[树莓派]:http://www.raspberrypi.org/
[PHP]:http://php.net
[Android]:http://www.android.com/
[1]:https://github.com/angeiv/RaspberryPi_SmartHouse
[2]:https://github.com/angeiv/Android_SmartHouse
[3]:https://github.com/angeiv/PHP_SmartHouse
[Yeelink]:http://www.yeelink.net/
[4]:http://blog.csdn.net/qigenhuochai/article/details/17661845
[5]:http://blog.csdn.net
[Dillinger]:http://dillinger.io/
[6]:https://github.com/angeiv/SmartHouse
