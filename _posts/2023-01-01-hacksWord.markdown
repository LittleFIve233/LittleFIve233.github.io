---
layout: post
title: "WiiU名词讲解及纠正"
date: 2023-02-05 14:09:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 名词讲解与纠正
---

## 前言

这篇文章还是很有必要的，现在大部分国内玩家都以为wiiu仍在使用虚拟系统，实则不是

**首先听我说……继rednand后就没虚拟系统了，你们用的真的只是CFW！**

<hr />

# 名词讲解

CFW：自制固件

OFW：官方固件

Homebrew：自制程序

wps格式为插件，wuhb和rpx为Aroma自制程序后缀。elf和rpx为HBL自制程序后缀

# CFW讲解与纠正

## 2016及更早

### Rednand

**这才是真正的虚拟系统。**这是在SD卡中创建一个与主机存储(8/32GB)一样大小的分区，然后通过cfwbooter的引导fw.img进入Rednand，从而实现无区域限制以及运行自制软件和盗版游戏。

## 2017-2021

### iosuhax（cfwbooter，fw.img，网页破解）

**这不是虚拟系统！！！**

这是最初的cfw，通过对wiiu内核注入漏洞来实现在真实系统运行自制软件和盗版游戏。

**这是国内在wiiu使用排第一的cfw。。**

### mocha（网页破解……吗）

它是iosuhax的升级，相比iosuhax的fw.img需要通过cfwbooter引导，它直接是一个自制软件，只需要通过网页漏洞或者别的方法进入hbl，然后运行mocha cfw自制程序即可启用cfw，相对于iosuhax，mocha不仅拥有iosuhax的全部功能，更是有可配置的菜单，直到现在的Aroma和tiramisu（提拉米苏）都有着mocha的一份功劳。哦对，它还可以引导Rednand（虚拟系统）

**可能在国内太冷门了所以没什么人用它。。。**

### haxchi（脑锻炼破解）

首先是它为啥要叫脑锻炼破解……

wiiu中所有的dsvc都可以安装haxchi，然后因为脑锻炼是eshop的dsvc中最便宜的ds游戏，所以大部分商家都选择脑锻炼，从而导致现在基本都是叫脑锻炼破解的结果。

haxchi相对于网页破解，只是换了切入口而已，从网页换到了应用程序。haxchi通过注入正版dsvc，让自己能够在ofw下运行，相对于网页破解，已经省去了很多步骤了，同时搭配可配置payload也更方便

**是国内在wiiu使用排第二的cfw。。**

### CBHC（破解固化）

很多商家指的冷启动固化。。跟网页固化差距大了。。

CBHC通过Haxchi打开的切入口，进一步修改系统默认桌面的TitleID(你可以理解为是软件在wiiu系统的代名词)，来达到默认启动CFW的效果。

**与haxchi同名次。**

### indexiine（网页固化）

商家指的网页固化。。

这个就单纯是把你打字或者需要手点的时间省去了。它是通过替换wiiu浏览器的主页html实现的自动加载hbl或cfw。将wiiu浏览器默认加载的空白html改为附有破解的html，等wiiu浏览器加载完成主页后，就自动进入hbl或cfw了

**国内第三cfw。。**

## 2022至今

### Tiramisu（提拉米苏，提拉米苏固化）

全新的cfw！不仅有了模块化，相比cbhc固化还更安全！

提拉米苏和提拉米苏固化跟haxchi/CBHC原理差不多，同样是注入，同样是修改ID，因为cbhc的程序可以删除，造成砖机；提拉米苏则直接注入系统软件，让你不可删除，这样一来就保证了wiiu不会因为有人手欠导致砖机。

**估计马上就成国内第一cfw了。。**

### Aroma

全新的环境！相对于提拉米苏，插件更强，还有更多的新功能。

唯一一点坏处就是废除了所有的elf格式的自制软件，导致了wiiu一大半自制软件的死亡

**目前仍在beta，但已可供最终用户使用**

<hr />

## 昙花一现的CFW

### Frappaccino CFW（星冰乐CFW）

我并没有接触过Frappaccino CFW，但是它是fork的mochacfw，相对于mocha来说，它的功能更多，但是终究还是太冷门了。

[Frappaccino CFW 星冰乐CFW介绍](https://www.tekqart.com/forum.php?mod=viewthread&tid=74523&highlight=%E6%98%9F%E5%86%B0%E4%B9%90)

**撰写本文时，它的github页也没了。。**

### Potatohax

potatohax是由failfshax的泄密者制作的……起初是称为更好的cbhc，安装和固化在wiiu chat软件中。

**结果没活一周，就被FailST漏洞作者发布的提拉米苏代替。。**

（potatohax于2021-12-25日发布，提拉米苏于2022-1-1日发布）