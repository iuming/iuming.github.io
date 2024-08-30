---
title: 基于EasyTier组网的远程桌面连接
author: 刘铭
date: Aug, 30, 2024
---

## 下载EasyTier

进入[EasyTier](https://github.com/EasyTier/EasyTier/releases)的Github界面下载适应计算机系统版本的安装包进行安装

![Download](EasyTier_Download.png)

----

## 安装EasyTier

按照安装软件的正常程序进行安装即可，安装位置可随意更改。

----

## 打开EasyTier

![EasyTier GUI](EasyTier_GUI.png)

----

## 输入本机虚拟IP地址

![更改IP地址](Input_IP.png)

----

## 输入同一组网的网络名称和密码

![同一组网账号密码](EasyTier_Password.png)

----

## 点击运行网络

![Start](EasyTier_Start.png)

----

## 检查是否在同一组网下

![Check](EasyTier_Check.png)  

----

## 打开远程桌面连接

![Remote Desktop Connect](RDC.png)

----

## 完成连接

注意：现在工作站使用的是流量下的外网，请不要<span style="color:red">传输大文件、打开ihepbox进行同步</span>等耗费流量的操作！

另外，本地的虚拟IP在内部组网之间不能冲突。

----

## Comment


<div id="disqus_thread"></div>
<script>

    var disqus_config = function () {
        // Replace PAGE_URL with your page's canonical URL variable
        this.page.url = "https://iuming.github.io/slides/20240830/BasedEasyTierRemoteDesktopConnect.html";  
        
        // Replace PAGE_IDENTIFIER with your page's unique identifier variable
        this.page.identifier = BasedEasyTierRemoteDesktopConnect; 
    };
    
    (function() {  // REQUIRED CONFIGURATION VARIABLE: EDIT THE SHORTNAME BELOW
        var d = document, s = d.createElement('script');
        
        // IMPORTANT: Replace EXAMPLE with your forum shortname!
        s.src = 'https://EXAMPLE.disqus.com/embed.js';
        
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>
    Please enable JavaScript to view the 
    <a href="https://disqus.com/?ref_noscript" rel="nofollow">
        comments powered by Disqus.
    </a>
</noscript>