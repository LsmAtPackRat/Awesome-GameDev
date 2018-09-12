# Awesome-GameDev
本仓库用于整理一些优秀的游戏开发资料。



### 框架/子系统

- [《守望先锋》架构设计与网络同步](https://mp.weixin.qq.com/s?__biz=MzA4MDc5OTg5MA==&mid=2650592121&idx=2&sn=3ad22849eedca5f7a4ad6d97e4ef9d1f&chksm=8796c284b0e14b9265b4c86ed6726d7bd6cfa4f9fd11f88d1bb11ca00fe6b38ae31fb6564651&scene=21#wechat_redirect)：⭐⭐⭐⭐⭐，Tim Ford在GDC2017上的演讲，介绍了ECS框架以及《守望先锋》的预表现层技术。
- [《守望先锋》中的网络脚本化的武器和技能系统](http://gad.qq.com/article/detail/28219)
- [浅谈《守望先锋》中的 ECS 构架](https://blog.codingnow.com/2017/06/overwatch_ecs.html)：⭐⭐⭐⭐，云风Blog谈及对《守望先锋》ECS框架的理解。
- [任务系统2.0，实现无锁的工作窃取（一）：基础](https://mp.weixin.qq.com/s?__biz=MzA4MDc5OTg5MA==&mid=2650598248&idx=3&sn=d4ee3077c27b4732e8ab04967f2b18be&chksm=8796fa95b0e17383e8f5fda46d488443d4a795a05c9225fb076175d87366f0c3ac93135fd083&mpshare=1&scene=24&srcid=0104pzmA1YsJyx0yWpBJ1xfv#rd)：⭐⭐。
- [如何在任务系统中实现无锁的工作窃取（二）](https://mp.weixin.qq.com/s?__biz=MzA4MDc5OTg5MA==&mid=2650598264&idx=3&sn=8ac5d7c3451b247c90481f8648c50b3e&chksm=8796fa85b0e17393404f7bb0a4b6caf85e2635d419e832dc0cadf3f3866e15e5513c2a05271d&mpshare=1&scene=24&srcid=0104dWTbpdULQSGD0hIxovQo#rd)：⭐⭐。
- [任务系统的核心问题（三）：如何实行无锁工作队列](https://mp.weixin.qq.com/s?__biz=MzA4MDc5OTg5MA==&mid=2650598367&idx=2&sn=d7e9ce853fb51c287d7d2409dd143f9b&chksm=8796fa22b0e173348e87ee49056c36a54c75f8844b603504c0625f114b196076e61ce0e1223c&mpshare=1&scene=24&srcid=0105xF6i3T3YzqKJck6EvrLL#rd)：⭐⭐。
- [Are we out of memory?](http://www.swedishcoding.com/2008/08/31/are-we-out-of-memory/)：⭐⭐⭐，讲述引擎自制内存分配器的各种策略的经典博文。
- 



### 服务器

- [当多线程并发遇到Actor](https://mp.weixin.qq.com/s/mzZatZ10Rh19IEgQvbhGUg)：⭐⭐⭐，一篇讲解Actor并发模型的入门文章，简单易懂。
- [Actor模型原理](https://www.cnblogs.com/MOBIN/p/7236893.html)：⭐⭐⭐，一些Actor的总结性叙述。示例看一下图即可。
- [Actor模型和CSP模型的区别](https://www.jdon.com/concurrent/actor-csp.html)：⭐⭐⭐，简单易懂。
- [10 分钟了解 Actor 模型](https://www.jianshu.com/p/449850aa8e82)：⭐⭐⭐，介绍了一点关于Supervisor/Fault Tolerance/Distribution的相关内容，不过很少。
- [Go Doc](https://golang.org/doc/)：⭐⭐⭐⭐⭐，Go官方文档，内容非常丰富。
- [The Go Memory Model](https://golang.org/ref/mem)：⭐⭐⭐⭐，Go官方的Memory Model文档，使用Go开发服务器必读。
- [Go Concurrency](https://golang.org/doc/effective_go.html#concurrency)：⭐⭐⭐⭐，Go官方的介绍Concurrency的文档，使用Go开发服务器必读。
- [维基百科Coroutine](https://en.wikipedia.org/wiki/Coroutine)：⭐⭐⭐，Coroutine相关资料的索引。
- [对于实时联网游戏，该如何做后台技术选型？](https://mp.weixin.qq.com/s?__biz=MzA4MDc5OTg5MA==&mid=2650603860&idx=1&sn=ad3f5c0ced94047778c3c12edeee60dc&chksm=879710a9b0e099bf5224de600fb0ef79509c13f4eddb24a9b968e32ccb069fd257c4558ce315&scene=21#wechat_redirect)：⭐⭐，泛泛谈论了网络拓扑/协议/序列化/并发等，可以参考。
- 




### 网络同步

- [从《王者荣耀》谈游戏的帧同步](https://mp.weixin.qq.com/s?__biz=MzA4MDc5OTg5MA==&mid=2650595000&idx=1&sn=a5dcf715bbb05974b83c0a46c83931cd&chksm=8796cf45b0e1465308c925b6e6bc20ae9eea51b055b83eeea1b5eaf768eba3745f5cfe7695a0&mpshare=1&scene=24&srcid=0908BufMWDPsTYCHRwb8Zz9O#rd)：⭐⭐⭐
- [Introduction to Networked Physics : Three ways to network a physics simulation](https://gafferongames.com/post/introduction_to_networked_physics/)：⭐⭐⭐⭐⭐，[Glenn Fiedler](https://gafferongames.com/about)写的网络物理同步的系列博客。讲解了deterministic lockstep，snapshot interpolation，state synchronization这三种同步技术。
- [《守望先锋》架构设计与网络同步](https://mp.weixin.qq.com/s?__biz=MzA4MDc5OTg5MA==&mid=2650592121&idx=2&sn=3ad22849eedca5f7a4ad6d97e4ef9d1f&chksm=8796c284b0e14b9265b4c86ed6726d7bd6cfa4f9fd11f88d1bb11ca00fe6b38ae31fb6564651&scene=21#wechat_redirect)：⭐⭐⭐⭐⭐，其中的net code部分讲解了《守望先锋》的预表现层技术。
- [Latency Compensating Methods in Client/Server In-game Protocol Design and Optimization](https://developer.valvesoftware.com/wiki/Latency_Compensating_Methods_in_Client/Server_In-game_Protocol_Design_and_Optimization)：⭐⭐⭐⭐⭐，Valve的延迟补偿技术的一篇经典资料（Source engine）。
- [I-Shot-You-First-Networking](https://www.gdcvault.com/play/1014345/I-Shot-You-First-Networking)：一个GDC VAULT的一个讲解同步技术的视频。
- 



### 渲染

- [没有人告诉你有关显卡落后1帧后的事情](http://gad.qq.com/program/translateview/7213977)
- [一篇光线追踪的入门](https://zhuanlan.zhihu.com/p/41269520)：⭐⭐⭐⭐，洛城在知乎上的文章。
- [卡通渲染及其相关技术](https://zhuanlan.zhihu.com/p/26409746)：⭐⭐⭐⭐，洛城在知乎上的文章。
- [Unity 2D 动态阴影怎么实现](https://zhuanlan.zhihu.com/p/30877199)：⭐⭐⭐⭐
- [基于Flash3D的粒子系统实现](http://www.kidsang.com/archives/715#more-715)：⭐⭐，这篇文章提供了一些粒子系统的实现思路。
- 



### 运行时/虚拟机

- [A No-Frills Introduction to Lua 5.1 VM Instructions](http://luaforge.net/docman/83/98/ANoFrillsIntroToLua51VMInstructions.pdf)：⭐⭐⭐⭐，Lua 5.1 VM原理解析。
- 



### 数据结构

- [Pitfalls of Object-Oriented Programming](https://www.gamedevs.org/uploads/pitfalls-of-object-oriented-programming.pdf)：⭐⭐⭐⭐，讲解如何设计缓存友好的数据结构。
- [Data-Oriented design](http://gamesfromwithin.com/category/data-oriented-design)：⭐⭐⭐⭐，在游戏中设计缓存友好的数据结构（需翻墙）。
- 



### PCG (Procedural-Content-Generation)

- [这些坑别踩！游戏随机地图生成开发经验分享](https://mp.weixin.qq.com/s/BifoQTnGt31sDUMbTledaw)：⭐⭐，写的比较简单，有一些参考价值。
- [开放世界游戏中的大地图背后有哪些实现技术？](http://gulu-dev.com/post/2014-11-16-open-world#toc_10)：⭐⭐⭐⭐，技术盘点类文章。
- 



### Game AI

- 



### Demo开发

- [Unity仿Splatoon喷漆效果(一)](https://zhuanlan.zhihu.com/p/43050863)：⭐⭐⭐
- 

