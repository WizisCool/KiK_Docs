---
title: KiK指南
description: KiK指南
slug: /

# hide_table_of_contents: false
---

## 入门
如何开始使用KiK平台的说明。  

-------------------------  
[Hanbot Database 数据库网站](https://db.hanbot.cc) | 可以查询Hanbot各个英雄脚本胜率情况  
[Hanbot.cc官方网站](https://hanbot.cc) | Hanbot.cc官方站
-------------------------  

### 状态
:::tip 状态
当前状态: 正常  
支持版本: 13.18.530.4653
:::
### 下载  

- [下载线路 ①](https://github.cab/d/Onedrive/KiK.Loader.zip)
- [下载线路 ②](https://github.cab/d/AliCloud/KiK/KiK.Loader.zip)
- 👆解压密码: `1` 
- `使用IDM等第三方多线程下载工具可能导致无法解析而无法下载,最好使用浏览器下载`

:::danger 务必注意! 
  **不支持中文路径!!!**  
  **关闭杀毒软件**,包括**微软自带Microsoft Defender！！！**  
  添加**&[DEP数据保护](./2DEP.md)!!!**  
:::
:::caution 自我检查
> *请确保你的装载器是从上面下载的,确保KiK加载器无任何蠕虫木马感染,否则会导致某些防封效果失效*    
>*你可以通过以下算法校验你的ZIP压缩包 *  
md5: `9740997205a742256e5690f747ead786`  
sha256: `fad6491668be99b17c5502b2f863212961c4ff8be757d50dbdbb624548a3cc31`
:::  
## 说明

### 要求
KiK的正常运行有一些要求。

### 加载器要求
- 必须以**管理员身份权限**运行 `KiK装载程序`
- KiK加载器应该被**解压**到一个简单的路径，比如 `C:\KiK\` 或者 `D:\KiK`  

  :::danger   千万注意!!!  
  请不要把 `KiK加载器.exe` 直接放在 **桌面** 运行 或 直接 **不解压** 运行！！！  
  不要把KiK放在中文路径中！！！
  :::
### 系统要求
- 请在运行KiK之前**关闭**所有的**杀毒软件** (包括Windows系统自带的Windows Defender)  

- 如果你遇到了Kik加载器,**崩溃**,**闪退**等,  
  并且重启软件和重启电脑后依然会遇到此问题,  
  请为你的KiK加载器添加**DEP数据保护**     [如何添加DEP数据保护](./2DEP)

- 如果你确保你已经完成了以上两点,仍然无法运行KiK
  1. 尝试安装所有运行库,例如 `VC++支持库`, `Net3.x支持库`, `DX修复`, 等等
  2. 尝试重装你的操作系统,推荐操作系统(`Windows 10 22H2`,`Windows 11 22H2`)
      

### 下面是关于使用Hanbot x64的指南
  - 1. [如何使用US等第三方缓存](./3US)
  - 2. [Loader加载器闪退或Hanbot部署时闪退的解决办法(修改DNS)](./4DNS)

## 开发者指南
- [跳转至开发者API](./99DevAPI)