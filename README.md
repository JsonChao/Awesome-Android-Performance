# Awesome-Android-Performance
Explore Android performance optimization in depth
<div align="center">
<img src="https://github.com/JsonChao/Awesome-Android-Performance/blob/master/screenshots/android-performance.png">
</div>

> 深入探索Android性能优化，从应用层、Framework层、Native层、ART/Dalvik以及Linux内核实现原理等各个层次深入挖掘各项性能优化技术~

## 前言

众所周知，性能优化是Android细分领域中最难且也是知识面涉及最深和最广的方向之一，但是如果你想要成为一名顶尖的Android工程师，性能优化细分领域则是非常好的实战与理论结合的场所。因此，为了将性能优化涉及的各个层面的知识成体系地糅合到一起，笔者创建了Awesome-Android-Performance这个项目，希望能带领读者从Android系统架构中的应用层、Framework层、Native层、ART/Dalvik以及Linux内核层这一大垂直领域去深入探索与挖掘性能优化的极致技术。

## Contents

### [全面了解](https://github.com/JsonChao/Awesome-Android-Performance/edit/master/notes/%E5%85%A8%E9%9D%A2%E4%BA%86%E8%A7%A3%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96.md)（已完成）

- 极客时间之Android开发高手课 导读（了解）
- 《Android开发艺术探索》第十五章 Android性能优化（了解）


### [稳定性优化]()（进行中~）

- [Android稳定性优化](https://blog.csdn.net/gs344937933/article/details/89888975) （了解）

- 《Android性能优化最佳实践》第五章 稳定性优化 （基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第十一章 App稳定性优化（进阶）
- 极客时间之Android开发高手课 崩溃优化 （进阶）
- [美团外卖Android Crash治理之路](https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651748107&idx=1&sn=55dff1b286e92cfb6aaee776df8ec89e&chksm=bd12ae468a652750a7624c30eca56f6f83347b16cdfb9153b647c6e5229a822b16724a1bbd9d&scene=38#wechat_redirect) （进阶）
- [海神平台Crash监控SDK（Android）开发经验总结](https://mp.weixin.qq.com/s/PoWPWy3cXFlG1nohgJTJgw) (进阶）
- [Android Native Crash 收集](https://mp.weixin.qq.com/s?__biz=MzAxNzMxNzk5OQ==&mid=2649485876&idx=1&sn=29ead87814c62a9b3e80cd6ada51e13c&chksm=83f83b34b48fb2225db860a290b4e7ee3b30475d887c2b38e8e29881b297c3cdb5c6d44deaed&scene=38#wechat_redirect) (进阶）
- [理解Android Crash处理流程](http://gityuan.com/2016/06/24/app-crash/)（进阶）
- [Android应用ANR分析](https://www.jianshu.com/p/30c1a5ad63a3) (进阶）
- [ANR监测机制](https://www.jianshu.com/p/ad1a84b6ec69) （进阶）
- [理解Android ANR的触发原理](http://gityuan.com/2016/07/02/android-anr/) （进阶）
- [理解Android ANR的信息收集过程](http://gityuan.com/2016/12/02/app-not-response/) （进阶）

- [巧妙定位ANR问题](https://www.jianshu.com/p/545e5e7bbf94) （经验）
- [剖析 SharedPreference apply 引起的 ANR 问题](ttps://mp.weixin.qq.com/s/IFgXvPdiEYDs5cDriApkxQ) （经验）
 

### [启动速度优化](https://jsonchao.github.io/2019/11/10/%E6%B7%B1%E5%85%A5%E6%8E%A2%E7%B4%A2Android%E5%90%AF%E5%8A%A8%E9%80%9F%E5%BA%A6%E4%BC%98%E5%8C%96/)（已完成）

- 《Android性能优化最佳实践》第二章 启动优化部分 （基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第三章 App启动优化（进阶）
- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第七章 App线程优化（进阶）
- [墙上时钟时间 ，用户cpu时间 ，系统cpu时间的理解](https://www.jianshu.com/p/ab3ef6894633)（进阶）

- 极客时间之Android开发高手课 启动优化（进阶）
- [支付宝客户端架构解析：Android 客户端启动速度优化之「垃圾回收」](https://mp.weixin.qq.com/s?__biz=MzUyMDk2MzUzMQ==&mid=2247483789&idx=1&sn=f3843b9ce282ab7d4e3c6225d780f9cd&chksm=f9e31529ce949c3f8c5d1ef7b96a3c09d358fec8c3d891c6640129152dbb3529b338f81b901f&token=401298154&lang=zh_CN&utm_medium=hao.caibaojian.com&utm_source=hao.caibaojian.com)（进阶）
- [支付宝 App 构建优化解析：通过安装包重排布优化 Android 端启动性能](https://mp.weixin.qq.com/s/79tAFx6zi3JRG-ewoapIVQ)（进阶）
- [微信Android热补丁实践演进之路](https://mp.weixin.qq.com/s/-NmkSwZu83HAmzKPawdTqQ)（进阶）
- [安卓App热补丁动态修复技术介绍](https://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=400118620&idx=1&sn=b4fdd5055731290eef12ad0d17f39d4a)（进阶）
- [浅析dex文件加载机制](https://www.cnblogs.com/lanrenxinxin/p/4712224.html) （进阶）
- [Dalvik Optimization and Verification With dexopt](https://blog.csdn.net/tabactivity/article/details/51444855)（进阶）

- 《Android移动性能实战》第八章 响应时延（经验）


### [绘制优化](https://jsonchao.github.io/2019/07/28/Android%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E4%B9%8B%E7%BB%98%E5%88%B6%E4%BC%98%E5%8C%96/)（待完善~）

- 《Android进阶解密》第十六章 绘制优化（基础）
- 《Android性能优化最佳实践》第二章 绘制优化（基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第五章 App布局优化 第六章 App卡顿优化（进阶）
- 极客时间之Android开发高手课 卡顿优化、UI优化（进阶）
- 《Android移动性能实战》第四章 CPU（进阶）
- 《Android移动性能实战》第七章 流畅度（进阶）

### [内存优化](https://jsonchao.github.io/2019/08/18/Android%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E4%B9%8B%E5%86%85%E5%AD%98%E4%BC%98%E5%8C%96/)（待完善~）

- Android进阶解密第十七章 内存优化
- 《Android性能优化最佳实践》第三章 内存优化
- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第四章 App内存优化
- 《Android移动性能实战》第二章 内存

### 包体积优化

- 《Android性能优化最佳实践》第七章 安装包大小优化
- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第十章 App瘦身优化（进阶）
- 极客时间之Android开发高手课 包体积优化

### 网络优化

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第八章 App网络优化
- 《Web性能权威指南》第八章 移动网络的优化建议
- 极客时间之Android开发高手课 网络优化
- 《Android移动性能实战》第三章 网络

### IO优化

- 极客时间之Android开发高手课 IO优化

### 存储优化

- 《Android性能优化最佳实践》第四章 存储优化
- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第十二章第二节 存储优化（进阶）
- 极客时间之Android开发高手课 存储优化
- 《Android移动性能实战》第一章 磁盘

### 耗电优化

- 《Android性能优化最佳实践》第六章 耗电优化
- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第九章 App电量优化（进阶）
- 极客时间之Android开发高手课 耗电优化
- 《Android移动性能实战》第五章 电池


### About me

- #### Email: [chao.qu521@gmail.com]()
- #### Blog: [https://jsonchao.github.io/](https://jsonchao.github.io/)
- #### 掘金: [https://juejin.im/user/5a3ba9375188252bca050ade](https://juejin.im/user/5a3ba9375188252bca050ade)
    
### License

Copyright 2018 JsonChao

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
