# Awesome-Android-Performance
Explore Android performance optimization in depth
<div align="center">
<img src="https://github.com/JsonChao/Awesome-Android-Performance/blob/master/screenshots/android-performance.png">
</div>

> 深入探索Android性能优化，从应用层、Framework层、Native层、ART/Dalvik以及Linux内核实现原理等各个层次深入挖掘各项性能优化技术~


# 前言

众所周知，性能优化是Android细分领域中最难且也是知识面涉及最深和最广的方向之一，但是如果你想要成为一名顶尖的Android工程师，性能优化细分领域则是非常好的实战与理论结合的场所。因此，为了将性能优化涉及的各个层面的知识成体系地融合到一起，笔者创建了Awesome-Android-Performance这个项目，希望能带领读者从Android系统架构中的应用层、Framework层、Native层、ART/Dalvik以及Linux内核层这一大垂直领域去深入探索与挖掘性能优化的极致技术。


# Contents

## 一、稳定性优化

>  [深入探索Android稳定性优化](https://juejin.im/post/5e69a4fd51882549003d2f0e)（已完成）

Android稳定性优化是一个需要长期投入，持续运营和维护的一个过程，上文中我们不仅深入探讨了Java Crash、Native Crash和ANR的解决流程及方案，还分析了其内部实现原理和监控流程。到这里，可以看到，要想做好稳定性优化，我们必须对**虚拟机运行、Linux信号处理和内存分配有一定程度的了解，只有深入了解这些底层知识，我们才能比别人设计出更好的稳定性优化方案。**


## 二、启动速度优化

>  [深入探索Android启动优化](https://juejin.im/post/5e6f18a951882549422ef333)（已完成）

想要极致地提升App的启动速度，我们需要有一定的广度，在文中**引入了始于后端的AOP编程来实现无侵入式的函数插桩**，也需要有一定的深度，从里面的探索之旅来看，**我们先后涉及了Framework层、Native层、Dalvik虚拟机、甚至是Linux IO和文件系统相关的原理**。


## 三、内存优化

>  [Android性能优化之内存优化](https://juejin.im/post/5e72b2d151882549236f9cb8)（已完成）

内存优化可以说是性能优化中最重要的优化点之一，可以说，如果你没有掌握系统的内存优化方案，就不能说你对Android的性能优化有过多的研究与探索。


>  [深入探索Android内存优化](https://juejin.im/post/5e780257f265da575209652c)（已完成）

真正的将内存优化做到极致，还不点击去一探究竟？


## 四、绘制优化

>  [Android性能优化之绘制优化](https://juejin.im/post/5e5f090de51d4526e4190980)（已完成）

首先，让我们从全局的角度去认识绘制优化，并为其打下良好的优化基础。


>  [深入探索Android布局优化（上）](https://juejin.im/post/5e1d15a851882536ca666a49)（已完成）

>  [深入探索Android布局优化（下）](https://juejin.im/post/5e1e6cf66fb9a0301828ca0a)（已完成）

布局优化看似是Android性能优化中最简单的专项优化项，但是笔者却花费了整整三万字的篇幅才能比较完整地将其核心知识传授给大家。因此，不要小看每一个专项优化点，深入进去，必定满载而归。


>  [深入探索Android卡顿优化（上）](https://juejin.im/post/5e41fb7de51d4526c80e9108)（已完成）

>  [深入探索Android卡顿优化（下）](https://juejin.im/post/5e49fc29e51d4526d326b056)（已完成）

卡顿优化可以说是Android性能优化中最复杂的环节，笔者从卡顿优化分析方法与工具、自动化卡顿检测方案及优化、ANR分析与实战、卡顿单点问题检测方案、界面秒开、优雅监控耗时盲区等多个维度来展开对App的卡顿优化进行深入讲解，相信读者必定有所收获。


## 五、包体积优化

>  [深入探索Android包体积优化](https://juejin.im/post/5e7ad1c0e51d450edc0cf053)（已完成）

如果要想对包体积做更深入的优化，我们就必须对 APK 组成，Dex、So 动态库以及 Resource 文件格式，还有 APK 的编译流程 有深入地了解，这样我们才能有 足够的内功素养 去实现包体积的深度优化，而此文将会带我们深入其中。


## 六、网络优化

> [《深入探索 Android 网络优化（一、网络核心筑基篇）》](https://juejin.im/post/5eba5a39e51d454de64e49b1)（已完成）

- 《计算机网络 自顶向下方法》前 6 章
- **《趣谈网络协议》1 - 5章**

- **慕课网之《编程必备基础 计算机组成原理+操作系统+计算机网络》网络部分 9 - 13章**

- [(建议精读)HTTP灵魂之问，巩固你的 HTTP 知识体系](https://juejin.im/post/5e76bd516fb9a07cce750746)
- [(建议收藏)TCP协议灵魂之问，巩固你的网路底层基础](https://juejin.im/post/5e527c58e51d4526c654bf41)
- [一位前端小姐姐的五万字面试宝典](https://juejin.im/post/5e91b01651882573716a9b23#heading-90)
- [面试带你飞：这是一份全面的 计算机网络基础 总结攻略](https://juejin.im/post/5ad7e6c35188252ebd06acfa#heading-2)
- [JavaGuide - 网络](https://github.com/Snailclimb/JavaGuide#%E7%BD%91%E7%BB%9C)
- [interview - 网络](https://github.com/huihut/interview#%EF%B8%8F-%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C)
- [总结了17年初到18年初百场前端面试的面试经验(含答案)](https://juejin.im/post/5b44a485e51d4519945fb6b7#heading-38)
- [CS-Notes - 网络](https://github.com/CyC2018/CS-Notes#cloud-%E7%BD%91%E7%BB%9C)


> [《深入探索 Android 网络优化（二、网络优化筑基篇） 》](https://juejin.im/post/5ecf149af265da76ce577fbc)（已完成）

- **极客时间之Android开发高手课 网络优化基础 1周**
- **《Web 性能权威指南》1 - 13章**

- 极客时间之《透视HTTP协议》优化基础部分


>  [《深入探索 Android 网络优化（三、网络优化篇） 》](https://juejin.im/post/5edc594ef265da76ea2e988c)（已完成）

- **慕课网之Top团队大牛带你玩转Android性能分析与优化 第八章 App网络优化**
- **极客时间之Android开发高手课 网络优化方案 1周**
- **极客时间之Android开发高手课 网络优化监控**
- **《Android移动性能实战》第三章 网络**

- wanandroid 网络优化


## 七、IO 优化

>  深入探索 Android IO 优化

学习资料：极客时间之Android开发高手课 IO优化（进阶）


## 八、存储优化

>  深入探索 Android 存储优化

学习资料：《Android性能优化最佳实践》第四章 存储优化（基础）、慕课网之Top团队大牛带你玩转Android性能分析与优化 第十二章第二节 存储优化（进阶）、极客时间之Android开发高手课 存储优化（进阶）、《Android移动性能实战》第一章 磁盘（经验）


## 九、耗电优化

>  [深入探索 Android 耗电优化](https://juejin.im/post/5ee8103b6fb9a047a64476e6)（已完成）

学习资料：《Android性能优化最佳实践》第六章 耗电优化（基础）、慕课网之Top团队大牛带你玩转Android性能分析与优化 第九章 App电量优化（进阶）、极客时间之Android开发高手课 耗电优化（进阶）、《Android移动性能实战》第五章 电池（经验）

## 知识星球（推荐）

**出身普通的人，如何真正改变命运？**

这是我过去五、六年一直研究的命题。首先，是为自己研究，因为我是从小城镇出来的，通过持续不断地逆袭立足深圳。**越是出身普通的人，就越需要有耐心，去进行系统性地全面提升，这方面，我有非常丰富的实践经验和方法论**。因此，我开启了 “JsonChao” 的成长社群，希望和你一起完成系统性地蜕变。

### 星球目前有哪些服务？

- 每周会提供一份让 **个人增值，避免踩坑 的硬干货**。
- 每日以文字或语音的形式分享我个人学习和实践中的 **思考精华或复盘记录**。
- 提供 **每月 三 次成长**、技术或面试指导的咨询服务。
- 更多服务正在研发中...

### 超哥的知识星球适合谁？

- **如果你希望持续提升自己，获得更高的薪资或是想加入大厂**，那么超哥的知识星球会对你有很大的帮助。
- **如果你既努力，又焦虑**，特别适合加入超哥的知识星球，因为我经历过统一的阶段，而且最后找到了走出焦虑，靠近梦想的地方。
- **如果你希望改变自己的生活状态**，欢迎加入超哥的知识星球，和我一起每日迭代，持续精进。

### 星球如何定价？

365元每年

每天一元，给自己的成长持续加油💪

为了回馈 JsonChao Github 的忠实用户，我申请了 200 张优惠券，先者到先得，错过再无

<div align="center">
<img src="https://mmbiz.qpic.cn/mmbiz_png/PjzmrzN77aAPxe8aibFBdkiaY9ldh9uQVxw0WFJ9TicCRlhZIFibIb2ex74hWel3DpkS46aX5vFlwuZXKTNMb2ZnHg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" width=30%>
</div>

## 公众号

我的公众号 `JsonChao` 开通啦，专注于构建一套未来Android开发必备的知识体系。每个工作日为您推送高质量文章，让你每天都能涨知识。如果您想第一时间获取最新文章和最新动态，欢迎扫描关注~

<div align="center">
<img src="https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/7da61f2739d34818be8a51a7afbbbb53~tplv-k3u1fbpfcp-watermark.image?" width=30%>
</div>


### About me

- #### Email: [chao.qu521@gmail.com]()
- #### Blog: [https://jsonchao.github.io/](https://jsonchao.github.io/)
- #### 掘金: [https://juejin.im/user/5a3ba9375188252bca050ade](https://juejin.im/user/5a3ba9375188252bca050ade)
    
### License

Copyright 2019 JsonChao

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
