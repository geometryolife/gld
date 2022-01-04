# 2022年1月3日，星期一
## Todo List

- [x] 复习昨天的单词
- [x] [背诵 20 个新单词](#背诵-20-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] [每日一题算法题](#每日一题算法题)
--------
- [ ] 给 Neovim 配置增加一个运行函数
- [ ] 学习如何用 Lua 处理日期和时间
- [x] [复习二分查找算法](#复习二分查找算法)
- [ ] 交医保
--------
- [x] 速看回顾李沐 d2l-v2 的视频 9～15 集
- [x] 把昨天创建空分支的收获分享到知乎
- [x] [做午饭](#做午饭)


### 背诵 20 个新单词

1. **formulation**
2. **invent**
3. **novelty**
4. **promote**
5. **further**
6. **contribute**
7. **contributory**
8. **advance**
9. **advanced**
10. **boost**
11. **motivate**
12. **motion**
13. **motive**
14. **motor**
15. **assist**
16. **propel**
17. **criticize**
18. **criticism**
19. **critic**
20. **critique**

### 赏析一句英语句子

Why this similarity exists in smell genes is difficult to explain, for now.

这种相似性为何存在于嗅觉基因中，目前还很难解释。

#### 句子主干

- is difficult to explain, for now. （主从+系+表）
- Why this similarity exists in smell genes
  - Why 引导的主语从句

#### 要点注释

动词不定式 to explain 作状语；介词短语 for now 作句子主干的时间状语。

### 每日一题算法题

#### 二分查找

> 给定一个 n 个元素有序的（升序）整型数组 nums 和一个目标值 target，
> 写一个函数搜索 nums 中的 target，如果目标值存在返回下标，否则返回 -1。
> 
> 来源：力扣（LeetCode）
> 链接：https://leetcode-cn.com/problems/binary-search

### 复习二分查找算法

[学习地址](https://github.com/geometryolife/gld/blob/main/Year2021/Dec/day29.md#%E5%AD%A6%E4%B9%A0%E6%9D%A8%E6%97%AD%E7%9A%84%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE%E7%AE%97%E6%B3%95%E8%A7%86%E9%A2%91)

看视频回顾了，并把之前的笔记补得更全些，对二分查找已经比较熟悉了。

### 做午饭

今天切猪肉的时候，想着那个煎盘平时都是煎蛋，索性把还没切完的猪肉片成肉片，等会煎来吃吃看。
我用之前特意制的鱼油来煎，煎出来的猪肉片特香。不过，我腌肉片的时候撒的盐多了一些，吃起来比较咸。
总之盐放少点，味道绝对杠杆的，下次再弄来吃吃。

## Get
### 阅读《Go 高级编程》的收获

今天翻开了《Go 高级编程》这本书，在前言里提到 WebAssembly 是第一个 Web 汇编语言和虚拟机标准。
曾经在很多时候看到有人提起 WebAssembly 这个技术术语，但没有去了解它，今天好奇，就点了一个视频来看看，看完后对这个技术算是有个大致的认识了。

[【代码实战】下一代web技术，WebAssembly入门教程，让我们初步认识一下-哔哩哔哩](https://b23.tv/mZButC7)

- 概述

> 视频中提到 WebAssembly 是下一代 Web 技术，众所周知的前端三剑客：HTML、CSS、JavaScript。
> 2019年12月5日，WebAssembly 正式成为 World Wide Web Consortium（W3C）的标准，我想这会给 Web 注入新的技术源泉。
> WebAssembly 有一套完整的语义，`wasm` 是体积小、加载快的二进制格式，其目标就是充分发挥硬件能力以达到原生执行效率。
> WebAssembly 是一种可以使用非 JavaScript 语言编写代码并能在浏览器上运行的技术方案，实际上，是一种`新的字节码格式`。

- 工作原理

> WebAssembly 是除了 JavaScript 以外，另一种可以在网页中运行的编程语言。
> 过去如果你想在浏览器中运行代码来对网页中各种元素进行控制，只有 JavaScript 这一种选择。
> WebAssembly 与其他的汇编语言不一样，它不依赖于具体的物理机器，可以抽象地理解成它是`概念机器的机器语言`。

- WebAssembly 的优势

> **文件加载**： WebAssembly 文件体积更小，所以加载（下载）速度更快。
> 
> **解析**：解码 WebAssembly 比解析 JavaScript 要快。
> 
> **编译和优化**：编译和优化所需的时间较少，因为在将文件推送到服务器之前已经进行了更多优化，JavaScript 需要为动态类型多次编译代码。
> 
> **重新优化**：WebAssembly 代码不需要重新优化，因为编译器有足够的信息可以在第一次运行时获得正确的代码。
> 
> **执行**：执行可以更快，WebAssembly 指令更接近机器码。
> 
> **垃圾回收**：目前 WebAssembly 不直接支持垃圾回收，垃圾回收都是手动控制的，所以比自动垃圾回收效率更高。
> 
> **安全**：可以放 hash 和签名等等。

- WebAssembly 的应用

> WebAssembly 可用于视频和音频编解码器，图形和 3D，多媒体和游戏，密码计算或便携式语言实现等领域。

## Summary

今天稍微了解了一下 WebAssembly，我今天又开始刷算法题了。希望能坚持一个月，这里就给自己立一个 Flag 吧！
