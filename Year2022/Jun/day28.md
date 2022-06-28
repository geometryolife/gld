# 2022年6月28日，星期二

## Todo List

- [x] 晨跑三公里
- [x] 冥想 20 分钟
- [x] 复习单词
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] 每日英语晨读纠音
- [x] 流利说英语打卡
- [x] 英语趣配音打卡
- [x] 芝士派英语打卡
  - [x] 早间 - Days of heavy rain cause flooding in China, India, Bangladesh
  - [x] 晚间 - Spies in Disguise - Ending Scene
- [x] 每日一道算法题
--------
- [x] Web 前端零基础入门 P139-P148
- [x] 刷 B 站
  - [x] [刘强东当年的丑闻，现在反而帮了他！](https://b23.tv/O3kqiT2)
  - [x] [刘强东案件公开听证会，现场曝光大量证据，究竟是谁在搞“阴谋”](https://b23.tv/1x98Am0)
  - [x] [a16z 梭哈web3](https://b23.tv/tmr6JrU)
  - [x] [#IPFS创业之路 Boost助力Filecoin闪电存储交易！传输提高20倍！](https://b23.tv/uzsHf0K)
  - [x] [626盗号事件发生过程，你的QQ被盗了吗？](https://b23.tv/wHfYJo0)
  - [x] [原创短剧！当我在“前女友”家隔离了十四天……（真人版）](https://b23.tv/sqJCjos)

### 赏析一句英语句子

Such measures have a couple of uplifting motives.

这些措施有几个令人振奋的动机。

#### 句子主干

- Such measures have a couple of uplifting motives. （主+谓+宾）

#### 词汇注释

- `uplifting` a. 令人振奋的
- `motive` n. 动机，原因，目的

### 芝士派英语打卡

#### [Days of heavy rain cause flooding in China, India, Bangladesh 暴雨致较大洪水，广州持续洪水红色预警](https://reading.baicizhan.com/h5/listen-movie.html?id=765&wxapp=mint_danni_ear#/home)

- **词汇**

  - `occurrence` n. 事件
  - `issue` v. 发布
  - `uproot` v. 使离开家园
  - `bring on` 引起，导致

- **遭遇洪水的自救技巧**

首先，如果遭遇突发洪水，在无法及时转移的情况下，需要快速前往地势较高的地方暂避。
若洪水继续上涨，应该马上寻找并依附于门板、桌椅或者大块的塑料泡沫等能漂浮的物体。
其次，如果发现高压线、铁塔倾斜或电线断头下垂，一定要迅速远避，防止直接触电或因地面"跨步电压”触电。
需要格外注意的是，一定不能攀爬带电的电线杆、或是泥坯房的屋顶进行躲避。
此外，如果在车中遭遇洪水、车辆被洪水淹没，在落水的第一时间需要立刻解开安全带并打开车门，采用侧门逃生。

#### [Spies in Disguise - Ending Scene 变身特工—— 莫名其妙被“绑架”，稀里糊涂当leader？](http://reading.baicizhan.com/h5/listen-movie.html?id=766&wxapp=mint_danni_ear#/home)

- **词汇**

  - `elevated` a. 高出正常水平的
  - `theatrics` n. 戏剧性行为，夸张行为
  - `covert` a. 秘密的
  - `make a face` 板起脸
  - `take sth off` 脱下

- **变身特工：顶级特工变身小鸽子，大战凶手，拯救世界**

《变身特工》是由威尔·史密斯和“荷兰弟”汤姆·赫兰德配音的动画片，改编自动画《鸽子与特工》，讲述了一个因为意外事故全球陷入危机，顶级特工兰斯变身鸽子和天才发明家沃尔特联手拯救世界的故事。
2020年，该电影荣获第47届安妮奖电影类最佳角色设计提名。
这部电影在青少年眼中，或许只是一部轻松的喜剧动画片，但其实这部影片也传达了一些深刻的价值观念：反对暴力解决问题，用和平的方式守护世界家园。
通过特工的故事，这部电影也告诉我们“多数人被世界改变，而少数人则能改变世界”。
改变世界的往往是少数“怪人”的坚持，这些“怪人”所坚持的或许也曾是很多人的信念，只是他们渐渐不再坚信，而往往正是因为这些“怪人”的坚持，才最终唤醒了大众，使问题得到解决。

## Get

### English Vocabulary

- `to serve as` 作为，担任

### 群聊的收获

- @倾听者 查issue看到，json的规范要求实现必须可以读取所有符合json格式要求的数据，但是可以对数字设置长度限制
  - https://github.com/stedolan/jq/issues/1959#issuecomment-522644933
  - @倾听者 https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/BigInt
  - 据我所知 json 规范没有规定 number 类型的实现和范围，一般是遵循 js 实现成浮点数，但不会把 number 当作精确的 bigint
    - 可以看到一些实现在要求 json 里传递整数时用的是字符串类型
    - 可能是用例较少，标准化的动力不足吧（quickjs 是原生自带了 bigfloat 和 bigdecimal 拓展 https://bellard.org/quickjs/jsbignum.html
    - https://github.com/jakm/msgpack-cli
    - https://npm.io/package/msgpack-cli 像这种不知道是否符合你的需求
  - 主要是 msgpack 没有规范的文本语法，json 的类型系统也不及 msgpack（缺少 int64 类型和 binary 类型）
- @银河-蜗牛 请问为什么我这cpu使用率这么低，负载却有100多吖
  - 我知道linux中平均负载指的是一定时间内的运行态进程数+不可中断进程数的总数
  - 但不知道怎么判断是具体哪一块导致负载高/委屈
    - https://man.archlinux.org/man/uptime.1
    - 如果我没猜错的话，你的机器应该是有8核心吧
    - 这是因为两种CPU负载的计算方式不同
    - uptime 使用的是占满一颗核心为100%，而 iostat 使用的是占满全部核心为100%
    - 详见这篇文章：https://blog.vmsplice.net/2020/02/why-cpu-utilization-metrics-are.html 为什么 CPU 使用率指标令人困惑（Solaris 模式，Irix 模式）
    - 如果有条件的话也可以用更方便的工具监控系统状态，比如 bpytop 或者 btop++，不行的话也可以用 htop
    - 那我就不太清楚了，这个最好用某一个你熟悉的具体工具来监测，不同工具使用的指标、数据来源理论上可能不同

## Summary

今天乐歌售后客服联系我了，把昨天升降桌的控制面板按钮无法按下的问题解决了，只需要把其中一颗螺丝拧松一点即可。
问题虽解决了，但是我也要吐槽一下这个面板：一个固定面板螺丝，拧紧会让控制按钮无法按下，这奇葩设计！

今天终于刷完了尚硅谷前端基础教程的视频了，下一步的目标就是学习 js 视频教程。
