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

现如今，Android 行业人才已逐渐饱和化，但高级人才依旧很稀缺，我们经常遇到的情况是，100份简历里只有2、3个比较合适的候选人，大部分的人都是疲于业务，没有花时间来好好学习，或是完全不知道学什么来提高自己的技术。对于 Android 开发者来说，尽早建立起一个完整的 Android 知识框架，了解目前大厂高频出现的常考知识点，掌握面试技巧，是一件非常需要重视的事情。

去年，为了进入一线大厂去做更有挑战的事情，拿到更高的薪资，我提前准备了半年的时间，沉淀了一份 「两年磨一剑」 的体系化精品面试题，而后的半年，我都在不断地进行面试，总共面试了二三十家公司，每一场面试完之后，我都将对应的面试题和详细的答案进行了系统化的总结，并更新到了我的面试项目里，现在，在每一个模块之下，我都已经精心整理出了 超高频和高频的常考 知识点。

在我近一年的大厂实战面试复盘中逐渐对原本的内容进行了大幅度的优化，并且新增了很多新的内容。它可以说是一线互联网大厂的面试精华总结，同时后续还会包含如何写简历和面试技巧的内容，能够帮你省时省力地准备面试，大大降低找到一个好工作的难度。

这份面试项目不同于我 Github 上的 Awesome-Android-Interview 面试项目：https://github.com/JsonChao/Awesome-Android-Interview，Awesome-Android-Interview 已经在 2 年前（2020年 10 月停止更新），内容稍显陈旧，里面也有不少点表述不严谨，总体含金量较低。而我今天要分享的这份面试题库，是我在这两年持续总结、细化、沉淀出来的体系化精品面试题，里面很多的核心题答案在面试的压力下，经过了反复的校正与升华，含金量极高。

在分享之前，有一点要注意的是，一定不要将资料泄露出去！细想一下就明白了：

1、如果暴露出去，拿到手的人比你更快掌握，更早进入大厂，拿到高薪，你进大厂的机会就会变小，毕竟现在好公司就那么多，一个萝卜一个坑。 

2、两年前我公开分享的简陋版 Awesome-Android-Interview 面试题库现在还在被各个培训机构当做引流资料，加大了现在 Android 内卷。。

所以，这一点一定要切记。

现在，我已经在我的成长社群里修订好了 《体系化高频核心 Android 面试题库》 中的 ”计算机基础高频核心面试题“ 和 ”Java 和 kotlin 高频核心面试题“ 部分，后续还会为你带来我核心题库中的：

- “Android基础 高频核心面试题”
- “基础架构 高频核心面试题”
- “跨平台 高频核心面试题”
- “性能优化 高频核心面试题”
- ”Framework 高频核心面试题“
- ”NDK 高频核心面试题“

获取方法：扫描下方的二维码。

<div align="center">
<img src="https://mmbiz.qpic.cn/mmbiz_png/PjzmrzN77aBMyo7G0TS2tYYJicPHRLD5KlvoaRA6EP1QvjiaSSkxcOPibnXXtOpgRJw5J3EYHcribkDBuWUfhRF35Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1" width=30%>
</div>

$\color{#FF0000}{出身普通的人，如何真正改变命运？}$

这是我过去五、六年一直研究的命题。首先，是为自己研究，因为我是从小城镇出来的，通过持续不断地逆袭立足深圳。**越是出身普通的人，就越需要有耐心，去进行系统性地全面提升，这方面，我有非常丰富的实践经验和方法论**。因此，我开启了 “JsonChao” 的成长社群，希望和你一起完成系统性地蜕变。

### 星球目前有哪些服务？

- 每周会提供一份让 **个人增值，避免踩坑 的硬干货**。
- 每日以文字或语音的形式分享我个人学习和实践中的 **思考精华或复盘记录**。
- 提供 **每月 三 次成长**、技术或面试指导的咨询服务。
- 更多服务正在研发中...

### 超哥的知识星球适合谁？

- **如果你希望持续提升自己，获得更高的薪资或是想加入大厂**，那么超哥的知识星球会对你有很大的帮助。
- **如果你既努力，又焦虑**，特别适合加入超哥的知识星球，因为我经历过同样的阶段，而且最后找到了走出焦虑，靠近梦想的地方。
- **如果你希望改变自己的生活状态**，欢迎加入超哥的知识星球，和我一起每日迭代，持续精进。

### 星球如何定价？

365元每年

每天一元，给自己的成长持续加油💪

为了回馈 JsonChao Github 的忠实用户，我申请了少量优惠券，先到者先得，错过再无

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
