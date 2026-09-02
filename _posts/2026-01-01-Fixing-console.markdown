---
layout: post
title: "疑难解答&修复主机"
date: 2026-01-21 16:59:00 +0800
categories: WiiU
tags: hacks WiiU
img: https://s11.ax1x.com/2024/03/02/pF0RUs0.png
describe: 疑难解答&修复主机
---

# 疑难解答&修复主机

此文章将会尽量解决部分对已破主机的误操作导致的破解丢失或主机遇到极个别特殊情况

> **由于Aroma引进了全新的插件功能，不稳定情况持续攀升！所以如果在本页无法找到或没有解决你的问题，请及时加群与我交流！**

<hr />

## 我格式化了我的储存卡，接下来该怎么办！

如果你之前有储存卡文件的备份，请将储存卡重新格式化为FAT32后恢复原备份。

如果没有储存卡文件备份，请在[准备SD卡（Aroma）](https://wiiu.1919810.com/wiiu/2026/01/21/Prepare-SD-Aroma.html)教程中下载并将文件放入储存卡

如果wii模式有破解则在破解系统正常运行后[使用vWii Decaffeinator重置系统](#)后[重新破解vWii](https://wiiu.1919810.com/wiiu/2023/02/04/Hack-vWii.html)

<hr />

## 开机有黑色闪屏画面后正常进入了系统

请尝试打开安装的游戏，如果报错199-9999是未检查到SD卡中的文件。

请确认储存卡中是否有破解文件以及储存卡文件系统格式是否为FAT32

如果一切文件正常请吹吹卡槽或者重新插拔一下SD卡，然后重启检查是否已经正常

如果问题依旧出现，请尝试备份储存卡文件之后格式化储存卡并在[准备SD卡（Aroma）](https://wiiu.1919810.com/wiiu/2026/01/21/Prepare-SD-Aroma.html)教程中下载并将文件放入储存卡

<hr />

## 主机开机卡死（黑屏）

### 自启动、选择或升级Aroma后卡死

> （开机状态，破解中途，开机有wiiulogo）

可能是SD卡内的文件不正常，请重新在[准备SD卡（Aroma）](https://wiiu.1919810.com/wiiu/2026/01/21/Prepare-SD-Aroma.html)教程中下载并将文件放入储存卡

### 添加Aroma插件后开机黑屏

> （开机状态，开机有wiiulogo）

如果长时间没有更新Aroma，请优先[更新Aroma](https://wiiu.1919810.com/wiiu/2026/01/21/Prepare-SD-Aroma.html)

如果更新后依旧无法正常开机，请将SD卡的wiiu/environment/aroma文件夹重命名为aromabackup，并按照[准备储存卡文件](https://wiiu.1919810.com/wiiu/2026/01/21/Prepare-SD-Aroma.html)重新设置一个新Aroma环境后尝试排除插件问题

### 格式化存储卡后彻底无法开机

> （开机不出现wiiulogo，一直黑屏）

请检查主机电源灯光颜色，如果为蓝中带紫的颜色则代表你安装了isfshax，请寻求他人的帮助解决

<hr />

## 主机开机报错（出现错误代码）

### 开机直接出现黑屏报错160-0103

（开机出现wiiulogo后报错）

系统无法启动默认桌面程序，为常见的CBHC砖机

[请尝试USB漏洞（需要最新系统与硬件设备支持）](https://wiiu.1919810.com/wiiu/2026/01/21/udpih.html)恢复原数值

### 其他160-XXXX错误代码

（开机出现wiiulogo后报错）

若为开机后跳出，请尝试向维修游戏机的师傅寻求帮助

<hr />

## 主机运行中出现的问题

### 启动游戏报错199-9999

未检测到SD卡或者缺少sigpatch模块，[请检查破解文件是否完整](https://wiiu.1919810.com/wiiu/2026/01/21/Prepare-SD-Aroma.html)

### 互联网设备均正常，但是主机无法连接到网络

请不要将硬盘盒或其他干扰WiFi的设备放在主机附近

### 主机无法更新系统，报错105-3029

主机在破解时做过屏蔽更新，[请按照此教程解除屏蔽更新](https://wiiu.1919810.com/wiiu/2026/01/21/UDFiine.html)

### DO NOT RUN EXPLOIT TWICE（Tiramisu）

目前仅出现在Tiramisu，表示CFW已经运行。

请长按电源键强制关闭主机。

如果是需要进入HBL，请使用Mii工作室打开HBL（Tiramisu）

如果没有正确安装破解，请重启主机并按照[教程安装破解](https://wiiu.1919810.com/wiiu/2026/01/21/Hack-WiiU.html)

### WUPInstallerGX2出现缺少sigpatch或checkSDFAT32提示

检查是否有[放入sigpatch_module](https://wiiu.1919810.com/wiiu/2026/01/21/Prepare-SD-Aroma.html)或安装包是否完整

### 安装的游戏打开后卡死

如果是安装在USB存储设备中出现的，可能USB存储设备出问题了，若插拔USB设备后依然有此问题，请考虑换新USB设备或者重新安装游戏

如果是安装在主机闪存中的游戏出现的，请尝试初始化主机，

### 系统自带软件打开后卡死

请尝试跳过破解之后重新打开软件。

若问题依然存在，可能主机闪存的寿命已经到头了

### 数据管理说要删除一些不必要的数据

这里指的是软件没有安装完成而残留的文件。请总是确认删除这些数据，因为它们本来就没有存在的必要。

如果它一直卡在删除数据的进程中，那么你可以选择自己手动删除这些数据。使用FTPiiU浏览至```/storage_mlc/usr/import```然后删除这个文件夹中任何存在的文件。这是未完成安装的东西存放的地方。如果安装到USB设备中，则应该是```/storage_usb/usr/import```文件夹。```import```文件夹里应始终都没有内容。

<hr />

## 主机按照教程破解中途出现问题

### 主机在进入Aroma后左上角出现一些乱七八糟的提示

这是正常的，请仔细阅读提示，并按L↓select调整提示中出现的插件

### 打开浏览器自动卡死、自动加载破解或者自动显示DO NOT RUN EXPLOIT TWICE

以前可能安装过indexiine（网页破解固化），需要[卸载indexiine](https://wiiu.1919810.com/wiiu/2026/01/21/uninstall-indexiine.html)

### 浏览器漏洞常见错误

**FSGetMountSource failed**：未检测到SD卡。请确保你的SD卡为FAT32格式！如果问题仍然存在，请尝试吹吹卡槽（或尝试其他方法清理）并重新插入SD卡。

**SD Mount failed**：无法正确挂载SD卡。说明SD卡已经被识别，但是格式可能不正确，请检测你的储存卡是否为FAT32格式，如果格式正确，请检测你的分区表引导是否为MBR！如果不是MBR请转换为MBR！

**FSOpenFile failed […] payload.elf**： SD卡上缺少payload文件。请确认在wiiu文件夹下是否有一个叫做payload.elf的文件。

**FSOpenFile failed**：缺少必要文件。如果是打开HBL或者Tiramisu自启动HBL时报错，可能是/wiiu/apps/homebrew_launcher里没有homebrew_launcher.elf

### 使用完vWii Decaffeinator，系统无法更新，一直为最新状态

请注意，AutobootModule已经阻止了系统更新，因此在使用某些需要更新功能的自制程序时（例如vWii Decaffeinator）需要开机按住+键后进入黑色菜单按住+和-直到Update Unblock!后再去卸载PayloadLoader才能使用系统更新，[请在使用之前请关闭屏蔽主机更新](https://wiiu.1919810.com/wiiu/2026/01/21/UDFiine.html)

