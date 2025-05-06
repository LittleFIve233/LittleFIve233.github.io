---
layout: post
title: "检查Wii U破解"
date: 2023-02-04 16:00:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 检查破解
---

## Aroma＆Tiramisu

### 简介

Aroma无疑是现在最好的CFW了，它拥有插件加载器，它还是tiramisu的升级版，继承了一切来自tiramisu的好处，例如无需花钱无需担心初始化系统砖机，它们的前置叫payloadloader，以下方法用于检查payloadloader的安装状态

#### 检查PayloadLoader（Aroma&Tiramisu）

检查payloaderloader要在打开安全使用须知软件（黄色感叹号）软件时按住X即可检查，通常会有以下的情况：

如果出现黑屏白字的英语大意说不要运行两次，则你的主机已安装payloadloader，且目前正在运行tiramisu或老版Aroma

如果你的主机正常进入了安全健康须知，则需要拔下存储卡之后重启主机并重新进入安全健康须知，如果进入之后自动返回wiiu菜单，则你的主机已经安装payloadloader

如果主机已经安装了自启动payloadloader，请在开机时按住 X键 尝试进入environmentloader

<hr />

## Haxchi&CBHC（脑锻炼破解与冷启动脑锻炼固化）

### 简介

Haxchi是以前大部分破解玩家或是一劳永逸玩家的首选，通过被注入haxchi的DSVC软件启动自制系统。

因为Haxchi可以变更为CBHC，在开机时冷启动自制系统以节省时间

#### 检查Haxchi&CBHC

检查Haxchi要在主菜单上找是一个写着Haxchi的软件，不过商家一般会把它的启动图标和启动画面改成“一键破解”之类的应用，这个就是haxchi；或者直接打开游戏可能会跳出199-9999的错误，**这是没启用自制系统的报错**，如果你要安装aroma，可以直接进行正常步骤安装

检查CBHC很简单，在开机时会有Autobooting的黑屏画面，这就是CBHC；或通过检查数据管理的主机储存中有没有一个叫Don't touch me的软件。**！当你不知道在干什么时，千万不要删除这个软件！**

<hr />

## Mocha/Indexiine（浏览器破解与浏览器固化）

### 简介

Mocha是通过网页破解启动HBL之后需要在HBL里选择MochaCFW自制程序（或IOSUHAX），通常大部分人会做Indexiine来节省打开它的时间，商家们会叫它浏览器破解

Indexiine则包含一个可配置的payload，以便indexiine，自启动mocha

#### 检查Mocha/Indexiine

检查Mocha可以在开机后直接打开你自己安装的游戏，可能会跳出199-9999的错误，**这是没启用自制系统的报错**，如果你要安装aroma，可以直接进行正常步骤安装，**如果你一直需要打开网页破解则不需要检查！**

检查Indexiine需要在打开浏览器后（必须在首页而不是其他网页）等待几秒，判断会不会自动跳转到HBL或是其他的自制程序里或者自动卡死浏览器，如果出现了这些现象就代表你安装了Indexiine


**请注意：如果以上三种都没有检查出来那就是未破解状态**
