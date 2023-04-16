---
categories:
- Shoka
date: 2023/3/19 10:19:38
tags:
- Shoka
- Webmention
title: Shoka:+Webmention
---
> Thanks❤️🌹😋 For   
[Webmention Demo](https://whyouare111.github.io/hexo-icarus-showcase/2021/02/02/webmention-demo/) By WhyYouAre。  
[IndieWeb, Webmentions](https://kwaa.dev/indieweb) By 藍+85CD。  
[Webmention](https://kaix.in/0001/webmention/) By dimlau。   
[算法花园](http://blog.xiang578.com/note/641ea60f-a31e-4979-9327-c50509c146e3.html) By Runye。

是这样的： 在魔改Shoka的基础上，现在已经实现了正常接收Webmention并将其显示的功能（~虽然样式还不是很好看~），至于发送Webmention，选择了使用Telegraph手动发送的方式

很简单的啦🤩，指南不写了，不行翻我源码。

~不过我这改的也有点小问题，有时候一些链接显示不出来~

没事儿没事儿随便了，就改成这样吧！反正现在用Webmention的人不多，丑一点就丑一点吧无所谓了。

这个坑就算是填好了😋

2023/4/16: 彻底解决，通过修改主题文件，解决将站外链接全部Base64化导致Webmention无法识别的问题，同时采用www.webmention.app提供的服务自动进行发送