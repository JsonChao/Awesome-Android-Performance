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

首先需要对性能优化有一个宏观的认知~


### [稳定性优化](https://jsonchao.github.io/2019/11/24/%E6%B7%B1%E5%85%A5%E6%8E%A2%E7%B4%A2Android%E7%A8%B3%E5%AE%9A%E6%80%A7%E4%BC%98%E5%8C%96/)（已完成）

Android稳定性优化是一个需要长期投入，持续运营和维护的一个过程，上文中我们不仅深入探讨了Java Crash、Native Crash和ANR的解决流程及方案，还分析了其内部实现原理和监控流程。到这里，可以看到，要想做好稳定性优化，我们必须对**虚拟机运行、Linux信号处理和内存分配有一定程度的了解，只有深入了解这些底层知识，我们才能比别人设计出更好的稳定性优化方案。**


### [启动速度优化](https://jsonchao.github.io/2019/11/10/%E6%B7%B1%E5%85%A5%E6%8E%A2%E7%B4%A2Android%E5%90%AF%E5%8A%A8%E9%80%9F%E5%BA%A6%E4%BC%98%E5%8C%96/)（已完成）

想要极致地提升App的启动速度，我们需要有一定的广度，在文中**引入了始于后端的AOP编程来实现无侵入式的函数插桩**，也需要有一定的深度，从里面的探索之旅来看，**我们先后涉及了Framework层、Native层、Dalvik虚拟机、甚至是Linux IO和文件系统相关的原理**。


### [绘制优化](https://jsonchao.github.io/2019/07/28/Android%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E4%B9%8B%E7%BB%98%E5%88%B6%E4%BC%98%E5%8C%96/)

- 《Android进阶解密》第十六章 绘制优化（基础）
- 《Android性能优化最佳实践》第二章 绘制优化（基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第五章 App布局优化 第六章 App卡顿优化（进阶）
- 极客时间之Android开发高手课 卡顿优化、UI优化（进阶）

- 《Android移动性能实战》第四章 CPU（经验）
- 《Android移动性能实战》第七章 流畅度（经验）


### [内存优化](https://jsonchao.github.io/2019/08/18/Android%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96%E4%B9%8B%E5%86%85%E5%AD%98%E4%BC%98%E5%8C%96/)（进行中~）

- Android进阶解密第十七章 内存优化（基础）
- 《Android性能优化最佳实践》第三章 内存优化（基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第四章 App内存优化（进阶）
- 极客时间之Android开发高手课 内存优化（进阶）

- 《Android移动性能实战》第二章 内存（经验）


### 包体积优化

- 《Android性能优化最佳实践》第七章 安装包大小优化（基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第十章 App瘦身优化（进阶）
- 极客时间之Android开发高手课 包体积优化（进阶）


### 网络优化

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第八章 App网络优化（进阶）

- 极客时间之Android开发高手课 网络优化（进阶）
- 《Web性能权威指南》第八章 移动网络的优化建议（进阶）

- 《Android移动性能实战》第三章 网络（经验）


### IO优化

- 极客时间之Android开发高手课 IO优化（进阶）


### 存储优化

- 《Android性能优化最佳实践》第四章 存储优化（基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第十二章第二节 存储优化（进阶）
- 极客时间之Android开发高手课 存储优化（进阶）

- 《Android移动性能实战》第一章 磁盘（经验）


### 耗电优化

- 《Android性能优化最佳实践》第六章 耗电优化（基础）

- 慕课网之Top团队大牛带你玩转Android性能分析与优化 第九章 App电量优化（进阶）
- 极客时间之Android开发高手课 耗电优化（进阶）

- 《Android移动性能实战》第五章 电池（经验）


## 赞赏

如果这个库对您有很大帮助，您愿意支持这个项目的进一步开发和这个项目的持续维护。你可以扫描下面的二维码，让我喝一杯咖啡或啤酒。非常感谢您的捐赠。谢谢！

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-Android-Interview/master/screenshot/wexin_play.jpg" width=20%><img src="https://raw.githubusercontent.com/JsonChao/Awesome-Android-Interview/master/screenshot/Apaliy.jpg" width=20%>
</div>


----

## Contanct Me

###  ●  微信：

> 欢迎关注我的微信：`bcce5360`  

###  ●  微信群：

> **微信群如果不能扫码加入，麻烦大家想进微信群的朋友们，加我微信拉你进群。**

<div align="center">
<img src="https://raw.githubusercontent.com/JsonChao/Awesome-Android-Interview/master/screenshot/wexin_qrcode.jpg" width=35%>
</div>
        

###  ●  QQ群：

> 2千人QQ群，**Awesome-Android学习交流群，QQ群号：959936182**， 欢迎大家加入~


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
