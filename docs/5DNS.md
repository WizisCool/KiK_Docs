---
title: Loader加载器或部署Hanbot时闪退问题的解决办法
description: Loader


---

#### 此篇指南会告知你如何解决Loader加载器闪退
     这个问题通常是由于你的网络环境问题,无法连接至下载CDN分发服务器而导致的闪退问题
     你需要手动调整你的DNS设置,这里以阿里云公众DNS为例(你也可以尝试其它的DNS,例如腾讯云,114等)


1. 打开Windows 10系统控制面板，点击右上角的以图标方式显示，点击“网络和共享中心”选项。
     ![](https://alidns-com.oss-cn-zhangjiakou.aliyuncs.com/articles-detail-image/1599708871230-9dfe0dc5-5233-4d48-ad4d-f45188b54335.jpeg)

2. 点击网络和共享中心左侧的“更改适配器设置”链接，如下图：
     ![](https://alidns-com.oss-cn-zhangjiakou.aliyuncs.com/articles-detail-image/1599708871458-e10222a3-db64-4513-b1c7-676a0a6b1d0c.jpeg)

3. 选中正在联网的网络连接,我这里是WIFI连接，鼠标右键菜单里选择“属性”
     ![](https://alidns-com.oss-cn-zhangjiakou.aliyuncs.com/articles-detail-image/1599708871704-b869f16f-fcf6-4584-a448-28700855cd7f.jpeg)

4. 在网络连接属性窗口中选中“Internet 协议版本 4 (TCP/IPv4)”，然后点击“属性”。
     ![](https://cdn.jsdelivr.net/gh/WIzisCool/PicGo_Res@master/img/%7BF948A1DA-6046-4844-97CA-147063143182%7D.png)

5. 选择使用指定的DNS，在DNS服务器地址中输入223.5.5.5 和 223.6.6.6，输入后确定退出即设置完成。
     ![](https://alidns-com.oss-cn-zhangjiakou.aliyuncs.com/articles-detail-image/1599708872536-faabdb1f-d88e-4030-ac7a-a230ce9ee3f1.png)

6. 打开CMD命令提示符，通过```nslookup alidns.com``` 命令进行验证，若最终解析结果是配置的IPV4公共DNS（223.5.5.5或223.6.6.6）返回的，则说明配置成功  

     ![](https://alidns-com.oss-cn-zhangjiakou.aliyuncs.com/articles-detail-image/1599708873222-b8c84784-7274-40ee-b40a-453b95d73138.png)
