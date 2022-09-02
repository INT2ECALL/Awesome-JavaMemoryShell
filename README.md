<div align="center">
    <h1>Java内存马系列</h1>
    <p>收集与Java内存马相关的文章和工具</p>
</div>
<br/>

# 索引

- [文章](#文章)
- [内存马](#内存马)
    - [Webshell](#Webshell)
    - [红队工具](#红队工具)
    - [Webshell管理工具](#Webshell管理工具)
- [查杀工具](#查杀工具)
- [JVM相关工具](#JVM相关工具)
- [交流讨论](#交流讨论)

# 内容

## 文章

- [一文看懂内存马](https://www.freebuf.com/articles/web/274466.html)
- [JAVA内存马的“一生”](https://xz.aliyun.com/t/11003#toc-13)
- [JavaWeb 内存马一周目通关攻略](https://su18.org/post/memory-shell/)
- [JavaWeb 内存马二周目通关攻略](https://su18.org/post/memory-shell-2/)
- [基于全局储存的新思路 | Tomcat的一种通用回显方法研究](https://mp.weixin.qq.com/s?__biz=MzIwNDA2NDk5OQ==&mid=2651374294&idx=3&sn=82d050ca7268bdb7bcf7ff7ff293d7b3)
- [基于内存 Webshell 的无文件攻击技术研究](https://landgrey.me/blog/12/)
- [利用 intercetor 注入 spring 内存 webshell](https://landgrey.me/blog/19/)
- [针对spring mvc的controller内存马-学习和实验(注入菜刀和冰蝎可用的马)](https://www.cnblogs.com/bitterz/p/14820898.html)
- [利用 intercetor 注入 spring 内存 webshell](https://www.cnblogs.com/bitterz/p/14820898.html)
- [SpringBoot拦截器注入内存马实验](https://xz.aliyun.com/t/9746)
- [蓝军反治系列之打造weblogic的持久化内存马后门](https://mp.weixin.qq.com/s/9eDuJdYJMSNGVanZPt6dNQ)
- [Weblogic 内存马（一）](https://kuron3k0.github.io/2021/04/23/weblogic-memshell-1/)
- [Weblogic 内存马（二）](https://kuron3k0.github.io/2021/04/29/weblogic-memshell-2/)
- [Tomcat 内存马学习(一)：Filter型](http://wjlshare.com/archives/1529)
- [tomcat无文件内存webshell](https://uuzdaisuki.com/2021/06/29/tomcat%E6%97%A0%E6%96%87%E4%BB%B6%E5%86%85%E5%AD%98webshell)
- [Java安全之基于Tomcat实现内存马](https://www.cnblogs.com/nice0e3/p/14622879.html)
- [关于Tomcat内存马的一切](https://github.com/Am-ev/Tomcat-Webshell)
- [Resin回显及内存马](https://xz.aliyun.com/t/9639)
- [一枚野生resin filter内存马调试](https://www.anquanke.com/post/id/239866)
- [JBOSS 无文件 webshell 的技术研究](https://paper.seebug.org/1252/)
- [查杀Java web filter型内存马](https://gv7.me/articles/2020/kill-java-web-filter-memshell/)
- [深入浅出内存马（一）](https://jishuin.proginn.com/p/763bfbd5f9cc)
- [Java Agent 从入门到内存马](https://xz.aliyun.com/t/9450#toc-9)
- [Tomcat 内存马检测](https://www.anquanke.com/post/id/219177)
- [Tomcat 源代码调试笔记 - 看不见的 Shell](https://mp.weixin.qq.com/s/x4pxmeqC1DvRi9AdxZ-0Lw)
- [JBoss & WildFly Filter 内存马](https://mp.weixin.qq.com/s?__biz=MzU0MDg5MzIzMQ==&mid=2247486028&idx=1&sn=0c42579dff3cac3e4db7c50f9ae647ce&chksm=fb33030ccc448a1a17ec5feafe452837dd5d983cee2362236c29416d13d7d5222b9ed209e20b&scene=126&sessionid=1647240134&key=fb28ed52e6f6c17c69d1fbb322eb357105beaaa6d27b55736443a2301cb7c7c39b200bd4fae8145f9c8b751cfd595550e7af6941837d5b3ac9740b128cc2471e14dd6da37e26497ab4bfc6ddd7044e8b84d426afa145e742a224ea8656eb531a0a8f829b208160fb93261ffb07f9a00ec09b4ed251183b5fe04e159c1c18ac12&ascene=1&uin=NTY2NTA4NjQ%3D&devicetype=Windows+Server+2016+x64&version=6304051b&lang=zh_CN&exportkey=A3z2qh%2F9r3tz%2B)
- [Java安全之Weblogic内存马](https://www.cnblogs.com/nice0e3/p/14956677.html)
- [Tomcat容器攻防笔记之Valve内存马出世](https://www.anquanke.com/post/id/225870)
- [WebSocket 内存马，一种新型内存马技术](https://www.freebuf.com/articles/web/339616.html)
- [新型 tomcat websocket 内存马检测与防护思路探究](https://www.freebuf.com/articles/web/339361.html)
- [tomcat6下的Filter内存马注入](https://cloud.tencent.com/developer/article/1937711)

## 内存马

### Webshell

- [memShell](https://github.com/rebeyond/memShell) - a webshell resides in the memory of java web server
- [msmap](https://github.com/hosch3n/msmap) - Msmap是一个内存马生成器，兼容多种容器、组件、编码器、WebShell / Proxy / Killer 和管理客户端
- [MemShellDemo](https://github.com/jweny/MemShellDemo) - 本项目为各类内存马的Demo合集
- [JAVA_memshells](https://github.com/minhangxiaohui/JAVA_memshells) - java 内存马系列 实现（Servlets 、组件、Agent）
- [weblogic_memshell](https://github.com/keven1z/weblogic_memshell) - 一个基于javaagent+ASM的无文件落地的javaagent，兼容多种容器(weblogic,Tomcat,Springboot)
- [java_memshell](https://github.com/kuron3k0/java_memshell) - java各中间件的内存马、回显研究
- [JSP-WebShells](https://github.com/threedr3am/JSP-WebShells) - Collect JSP webshell of various implementation methods. 收集JSP Webshell的各种姿势
- [ZhouYu](https://github.com/threedr3am/ZhouYu) - SpringBoot 持久化 WebShell
- [MemoryShell](https://github.com/su18/MemoryShell) - JavaWeb MemoryShell Inject/Scan/Killer/Protect Research & Exploring
- [MemShell](https://github.com/ax1sX/MemShell) - A List of Memory Shell related component relationships for some middleware
- [MemShell](https://github.com/veo/wsMemShell) - WebSocket Webshell，一种新型WebShell技术


### 红队工具
- [shiro_attack](https://github.com/j1anFen/shiro_attack) - 利用shiro反序列化漏洞进行回显命令执行以及注入各类内存马
- [Dr4gonSword](https://github.com/ccdr4gon/Dr4gonSword) - 内存马利用工具
- [Shiro-EXP](https://github.com/Veraxy00/Shiro-EXP) - 基于Apache Shiro反序列化漏洞进行利用链的探测，附内存马。
- [ysoserial](https://github.com/su18/ysoserial) - 支持了一键打入 Spring/Tomcat/Jetty/JBoss/Resin/Websphere 内存马功能，内存马支持命令执行、冰蝎、哥斯拉、WebSocket 四种利用方式；并支持 Tomcat 回显命令执行、Neoreg 流量隧道内存马、Tomcat Websocket 内存马、Tomcat Executor 内存马、Tomcat Upgrade 内存马、RMI 内存马等；
防御绕过：在部分系统中使用了 WAF/RASP 等防御模式，本项目去除大多数原版特征，并在执行恶意动作时使用了多种能够绕过 RASP 的执行方式，绕过防护


### Webshell管理工具
- [Behinder](https://github.com/rebeyond/Behinder) - “冰蝎”动态二进制加密网站管理客户端
- [Godzilla](https://github.com/BeichenDream/Godzilla) - 哥斯拉webshell管理工具
- [As-Exploits](https://github.com/yzddmr6/As-Exploits) - 中国蚁剑后渗透框架
## 查杀工具
- [copagent](https://github.com/LandGrey/copagent) - A java memory web shell extracting tool
- [java-memshell-scanner](https://github.com/c0ny1/java-memshell-scanner) - 通过jsp脚本扫描并查杀各类中间件内存马，比Java agent要温和一些。
- [java-memshell-scanner](https://github.com/tovd-go/java-memshell-scan) - 简单的修改了一下c0ny1师傅的代码，添加了对websocket内存马查杀的支持
- [DuckMemoryScan](https://github.com/huoji120/DuckMemoryScan) - 一个简单寻找包括不限于iis劫持,无文件木马,shellcode免杀后门的工具
- [GuanYu](https://github.com/threedr3am/GuanYu) - JVM类加载监控agent，可配置黑名单，禁止恶意类加载（包括jsp webshell）


## JVM相关工具
- [jattach](https://github.com/apangin/jattach) - The utility to send commands to a JVM process via Dynamic Attach mechanism
- [arthas](https://github.com/alibaba/arthas) - Arthas is a Java Diagnostic tool open sourced by Alibaba

# 交流讨论

欢迎关注公众号，一起交流学习。
<p align="center">
    <img src="https://s1.ax1x.com/2022/08/27/vWFPpj.png" alt="vWFPpj.png" border="0" />
</p>

