<div align="center">
    <h1>Java内存马系列</h1>
    <p>收集与Java内存马相关的文章和工具</p>
</div>
<br/>

# 索引

- [文章](#文章)
    - [JavaAgent技术](#JavaAgent技术)
    - [内存马相关](#内存马相关)
- [内存马](#内存马)
    - [Webshell](#Webshell)
    - [红队工具](#红队工具)
    - [Webshell管理工具](#Webshell管理工具)
- [查杀工具](#查杀工具)
- [JVM相关工具](#JVM相关工具)
- [交流讨论](#交流讨论)

# 内容

## 文章

### 基础原理
#### JavaAgent技术
- [JVM源码分析之javaagent原理完全解读](https://developer.aliyun.com/article/2946)
- [破解 Java Agent 探针黑科技](https://zhuanlan.zhihu.com/p/135872794)
- [JVM Attach机制实现](http://lovestblog.cn/blog/2014/06/18/jvm-attach/)

### 内存马相关
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
- [瞒天过海计之Tomcat隐藏内存马](https://tttang.com/archive/1368/)
- [从一个被Tomcat拒绝的漏洞到特殊内存马](https://xz.aliyun.com/t/10577)
- [Linux下内存马进阶植入技术](https://xz.aliyun.com/t/10186)
- [Java内存攻击技术漫谈](https://xz.aliyun.com/t/10075)
- [论如何优雅的注入Java Agent内存马](https://xz.aliyun.com/t/11640)
- [Tomcat容器攻防笔记之JSP金蝉脱壳](https://www.anquanke.com/post/id/224698)
- [一种新的Tomcat内存马 - Upgrade内存马](https://mp.weixin.qq.com/s?__biz=MzkxNDMxMTQyMg==&mid=2247493034&idx=1&sn=19da761e0945b563551d4187d174a194&chksm=c172f43bf6057d2d94affce2ed8e7c8c5f20ee5fbaa80f62ab0917851685e721eb74a5954fc6#rd)
- [Executor内存马的实现](https://xz.aliyun.com/t/11593)
- [Executor内存马的实现（二）](https://xz.aliyun.com/t/11613)
- [Java 动态调试技术原理及实践）](https://tech.meituan.com/2019/11/07/java-dynamic-debugging-technology.html)
- [硬核图解 Tomcat 整体架构](https://cloud.tencent.com/developer/article/1745954)
- [Tomcat源码学习笔记 - Connector组件（一）](http://chujunjie.top/2019/04/21/Tomcat%E6%BA%90%E7%A0%81%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0-Connector%E7%BB%84%E4%BB%B6-%E4%B8%80/)
- [死磕Tomcat系列(2)——EndPoint源码解析](https://juejin.cn/post/6844903874122383374)
- [中间件内存马注入&冰蝎连接(附更改部分代码)](https://mp.weixin.qq.com/s/eI-50-_W89eN8tsKi-5j4g)
- [冰蝎，从入门到魔改](https://www.anquanke.com/post/id/212271?display=mobile)
- [冰蝎3.0的使用方法与默认密码更改方法](https://www.freebuf.com/news/251074.html)
- [内存马的攻防博弈之旅](http://blog.nsfocus.net/webshell-interceptor/)
- [利用shiro反序列化注入冰蝎内存马](https://www.cnblogs.com/yyhuni/p/shiroMemshell.html)



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
- [MemShell-1](https://github.com/changheluor007/MemShell-1) - 免杀Tomcat Filter型内存马
- [memShell](https://github.com/feihong-cs/memShell) - Java memShell

### 红队工具
- [shiro_attack](https://github.com/j1anFen/shiro_attack) - 利用shiro反序列化漏洞进行回显命令执行以及注入各类内存马
- [Dr4gonSword](https://github.com/ccdr4gon/Dr4gonSword) - 内存马利用工具
- [Shiro-EXP](https://github.com/Veraxy00/Shiro-EXP) - 基于Apache Shiro反序列化漏洞进行利用链的探测，附内存马。
- [ysoserial](https://github.com/su18/ysoserial) - 支持了一键打入 Spring/Tomcat/Jetty/JBoss/Resin/Websphere 内存马功能，内存马支持命令执行、冰蝎、哥斯拉、WebSocket 四种利用方式；并支持 Tomcat 回显命令执行、Neoreg 流量隧道内存马、Tomcat Websocket 内存马、Tomcat Executor 内存马、Tomcat Upgrade 内存马、RMI 内存马等；
防御绕过：在部分系统中使用了 WAF/RASP 等防御模式，本项目去除大多数原版特征，并在执行恶意动作时使用了多种能够绕过 RASP 的执行方式，绕过防护
- [taycan-sdk](https://github.com/bigBestWay/taycan-sdk) - 通过native层修改java层(JVM)，使用JVMTI及JNI API可以修改java任意类、执行任意代码，完成hook、插入内存马、反射等功能。
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
- [MemoryShellHunter](https://github.com/sf197/MemoryShellHunter) - MemoryShellHunter是一款结合动态Building Call Graph的内存马Scanner/Killer工具。支持Agent和Attach方式启动检测，弥补常规内存马检测工具需要人工验证WebSocket内存马的问题。


## JVM相关工具
- [jattach](https://github.com/apangin/jattach) - The utility to send commands to a JVM process via Dynamic Attach mechanism
- [arthas](https://github.com/alibaba/arthas) - Arthas is a Java Diagnostic tool open sourced by Alibaba
- [visualvm](http://visualvm.github.io/) - VisualVM is distributed as a standalone tool at GitHub, and as an optional component of the GraalVM. Both are the same bits with the same features. Standalone tool runs on any compatible JDK, bundled tool is configured to run using the host GraalVM.
- [dumpclass](https://github.com/INT2ECALL/dumpclass) - Dump classes from running JVM process by sa-jdi.jar.
# 交流讨论

欢迎关注公众号，一起交流学习。
<p align="center">
    <img src="https://s1.ax1x.com/2022/08/27/vWFPpj.png" alt="vWFPpj.png" border="0" />
</p>

