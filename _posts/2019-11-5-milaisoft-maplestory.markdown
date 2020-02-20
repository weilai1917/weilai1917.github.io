---
layout: post
title: 简爱冒险使用手册
date: 2019-11-05 17:00:20 +0300
description: 韩服冒险岛登陆器使用手册.
pagetag: milaisoft-maplestory
img: blackmaple.jpg 
fig-caption: 
tags: [韩服, 冒险岛, Naver, 登录器]
---

![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/16.png)

![MapleStory]({{site.baseurl}}/assets/img/milaisoft-maplestory/maplestory.png)

## 首先关注

*	软件名称必须是  **MapleStory.exe**。
*	软件采用 Naver一次性登录密钥 (不是Naver OTP) ，请放心使用。
*	软件存放目录，请放在非游戏目录的其他文件夹下或桌面。
*	最新版下载地址 https://github.com/weilai1917/MapleStory/releases/tag/v3.0
*	软件永久免费使用，使用交流群：908378560，仅交流软件使用问题。

# 使用步骤
### 1. 手机应用市场下载 **Naver app**；

### 2. 一次性登陆码目录如图：
![左上角更多]({{site.baseurl}}/assets/img/milaisoft-maplestory/1.png){:width="250" }
![右上角设置]({{site.baseurl}}/assets/img/milaisoft-maplestory/2.jpg){:width="250" }
![Naver账号]({{site.baseurl}}/assets/img/milaisoft-maplestory/3.jpg){:width="250" }
![收取一次性登录号码]({{site.baseurl}}/assets/img/milaisoft-maplestory/4.jpg){:width="250" }
![8位数号码]({{site.baseurl}}/assets/img/milaisoft-maplestory/5.jpg){:width="250" }
### 3. 启动配置；启动游戏前，先配置冒险岛路径和LE路径；配置一次过后，下次启动不用再配置；
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/6.png){:width="250" }
### 4. 代理规则配置(加速器无视此步骤)；
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/7.png){:width="250" }
记得把软件加入到代理中，否则无法联网启动游戏哦。NGM，NGM64，游戏MapleStory，启动MapleStory，都必须要加入到允许规则里。
### 5. 如果是加速器，请在配置中勾选 代理是加速器。

### 错误集合
### 1. NGMDLL64.dll 错误
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/8.png)
NGM更新了，更新下NGMDLL64，而且网络访问要把NGM64.exe加入到网络中。NGM目录在 C:\Program Data\Nexon,NGM64官网下载地址：http://platform.nexon.com/NGM/Bin/NGMDll64.dll 再或者网页启动一次，让冒险岛自己下载最新的NGMDLL64.dll

### 2. 选频道掉线
  1.点击你的账号，重新登录一次；
  2.如果还是不行，检查下代理；

### 3. 冒险岛登录失败，NaverGame登录成功；
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/11.png)
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/12.png)

这类错误，先在网页上登录，看是否可以登录。Naver Game 无法登录一般是没有给本程序设置代理。冒险岛登录失败，去登录官网。
  - 锁号了？ 
  - 有没有默认的登录账号，勾上红色的，然后点蓝色的。再登录。

### 4.	无法进入游戏，弹出框框
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/13.png)
进入游戏提示无法进入游戏，重新点击一下登录，获取一下游戏最新登录信息，也无需输入OTP码。
如图：提示为，当前在官网已经登出，直接点一下登录就可以了。

### 5. Naver 登录失败
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/14.png)
按前面的步骤，找到正确的一次性密码

### 6. 软件启动过后，很久才出现NGS和游戏
一般是使用了代理模式，请在设置中勾选代理是加速器模式。
也有可能是因为游戏的NGS更新，一般20分钟后，还没反应，就进程关掉游戏，再进游戏。

### 7. 启动游戏后，弹语言问题，请下载最新版。
![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/15.png)
弹出此可能性问题是注册表路径修改失败，请以管理员运行。（如果是中文系统请不要勾选配置中的韩文系统，韩文系统默认不走LE）
- LE 位置不要带有中文目录，也尽量不要放在C盘。
- 如果还不行，请带上注册表 \HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Wizet\Maple 位置如图群内咨询。

![ ]({{site.baseurl}}/assets/img/milaisoft-maplestory/16.png)


