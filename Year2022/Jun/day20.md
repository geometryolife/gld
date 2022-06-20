# 2022年6月20日，星期一

## Todo List

- [x] 冥想 20 分钟
- [x] 复习单词
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] 每日英语晨读纠音
- [x] 流利说英语打卡
- [x] 英语趣配音打卡
- [x] 芝士派英语打卡
  - [x] 早间 - Asteroid samples contain 'clues to origin of life'
  - [x] 晚间 - Friends: Rachel Works on Her Gossiping Problem
- [x] 每日一道算法题
--------
- [x] 刷 B 站
  - [x] [全面革新的Evo轻薄本究竟有多好用？12代酷睿轻薄本推荐！「超极氪」](https://b23.tv/CJme9E8)
  - [x] [英国博士生vlog|治愈早餐健身 出门享受阳光的放松周末](https://b23.tv/FGcFRQQ)

### 赏析一句英语句子

Newlyweds traditionally move in with the wife's parents and may live with them up to a year, until they can build a new house nearby.

传统上，新婚夫妻要搬到妻子的父母家里，可能会同他们一起生活长达一年，直到新婚夫妻能够在附近建造一所新房子为止。

#### 句子主干

- Newlyweds traditionally move in （主+谓）
- **move in**
  - and may live with them up to a year,
  - and 连接的并列谓语

#### 一级修饰

- **move in**
  - with the wife's parents
  - 介词短语作句子主干的状语
- **and may live**
  - until they can build a new house nearby.
  - until 引导的时间状语从句

#### 词汇注释

- `newlywed` n. 新婚夫妇
- `nearby` ad. 在附近 a. 附近的
- `move in` 搬来（一起住），逼近
- `up to` 达到（某数量、规格等），至多有，直到

### 芝士派英语打卡

#### [Asteroid samples contain 'clues to origin of life' 日本隼鸟2号带回样本中发现氨基酸，首次在地球外确认存在“生命之源” ！](https://reading.baicizhan.com/h5/listen-movie.html?id=749&wxapp=mint_danni_ear#/home)

- **词汇**

  - `probe` n. 航天探测器
  - `asteroid` n. 小行星
  - `celestial` a. 太空的
  - `bring sth back` 带某物回来

- **为什么氨基酸被称作生命之源？**

首先蛋白质是构成地球生命的物质基础，而氨基酸作为蛋白质的基本单元，被称为生命之源就不足为奇了。
氨基酸在人体内通过代谢可以发挥下列一些作用：合成组织蛋白质，变成酸、激素、抗体、肌酸等含氨物质，转变为碳水化合物和脂肪，氧化成二氧化碳和水及尿素，产生能量。
日本机构此次所监测到的二十种氨基酸是组成生命体中的蛋白质的主要单元。

#### [Friends: Rachel Works on Her Gossiping Problem (Season 5 Clip) | TBS 老友记——我八卦吗？我只不过是在传递信息而已！](http://reading.baicizhan.com/h5/listen-movie.html?id=750&wxapp=mint_danni_ear#/home)

- **词汇**

  - `stapler` n. 订书机
  - `resolution` n. 决心
  - `botch` v. 笨手笨脚地弄糟
  - `keep an eye on` 监视
  - `pass sth on` 把（信息）传给……

- **为什么人们喜欢聊八卦？**

英国社会心理学家尼古拉斯·埃姆勒发现在日常谈话中，80%-90%是闲言碎语，其中有65%的内容是八卦。
那为什么人们喜欢聊八卦呢？第一，对于大脑而言，八卦等于奖赏。
当看到八卦信息的时候，大脑的β波活动最强。这个β波跟奖赏有关，比如忽然中了100万元彩票，就会激活很强的β波。
第二，八卦自古以来就有价值，聊八卦就相当于进行信息交换。到了现代社会，聊八卦仍然可以帮助人们获得信息并识别和筛选信息。
最后，八卦能满足减压的心理需求和“亲社会”倾向。但切勿八卦别人的隐私，总在背后议论他人是非的人，往往令人避而远之。

## Get

- @See https://awsl.blog/2021/Manjaro-Controversies
- 装arch的时候怕折腾可以直接用带gui的改版，@See https://archlinuxgui.in/
 - https://mirrorz.org/_/list/archlinux-gui/
- arch上的工具是不是会一直跟着更新啊，ubuntu的话需要升级最新的版本才能用新的工具，要不就全得靠自己了
  - arch用上最新的也有一定的麻烦，不过好在aur基本都有老版本可以安装，只是需要手动重新在bin里面改链接
  - （java好一点，自带了一个快速切换的工具，python这种就要手动链接了，不过用虚拟环境问题也不大）
  - 有些主流的依赖也会存在跟不上版本的情况，比如我之前用python3.10，pytorch过了蛮长时间才支持3.10，
  - 而huggingface的transfomers只支持老版本的pytorch，所以只能用python3.9
  - 这种时候我会觉得ubuntu更好点，因为很多软件都只在ubuntu上测试编译通过，换到arch需要自己去找老版本编译器和库
- 不过抛开引战话题不谈，严肃地说，我觉得 Linux 上的 procfs 是个很多操作系统不具备的非常棒的功能
  - 还有命名空间（namespace）、cgroups、seccomp 这类容器化技术
- win的cpu调度比linux强，但是新版本的win的ui真的是乱做，各种bug和资源占用。升级win11可以感觉到性能有变好，但是存在奇怪的卡顿
- 毕竟 wintel，intel 肯定还是优先照顾 Windows 了（指12代U）
  - @银河-蜗牛 也可以说是闭源的优势吧，大部分算法会首先在Linux上实现，win可以直接借鉴，而微软自己的算法，虽然可能有论文，但是代码是闭源的。
- 前几天我还花了100多块钱去买了个网卡，新机器的螃蟹卡都没linux的驱动
 - Linux的驱动问题确实比较难受，国内蛮多硬件厂家只有win/mac的驱动
 - @N/A 是的，好多都不给开源，开源的也是残血的功能
 - 这确实。Windows 也爱从 Linux“抄”接口，比如 futex 和 io_uring
- 之前看到 futex2 进主线内核的时候，很多人说“Linux 终于有 WaitForMultiObjects 了”，颇有一种 windows 高高在上的感觉。然而实际上这是一种误解
  - WaitForMultiObjects 根本不是 futex，而是类似于 poll 的等价物，而且有非常奇怪的语义和最多等待64个句柄的硬限制
  - futex2 的主要用途是 wine 的 FSYNC 补丁，用来模拟 WaitForMultipleObjects 调用的，但是不是因为 Linux 的调用不够强，
  - 实际上 eventfd + epoll 的模型（ESYNC）要强大得多，只不过 Windows 上的句柄是一种非常便宜的资源，
  - 导致很多程序会大量申请甚至泄漏句柄，而由于 posix 的传统，文件描述符是一种比较珍贵的资源，
  - 在 Linux 上泄漏文件描述符的不可接受的，所以才需要用 futex 来模拟
  - 如果这个话题感兴趣，可以看看这篇文章尤其是这则邮件，其中有非常详细的介绍
    - https://www.phoronix.com/scan.php?page=news_item&px=Linux-Kernel-Wine-Sync-API-2021
    - https://lore.kernel.org/lkml/f4cc1a38-1441-62f8-47e4-0c67f5ad1d43@codeweavers.com/T/
- 部分游戏Linux下完全无法运行，大部分通过proton才能运行而且可能存在缺陷，win的霸主地位依然无法撼动
- @疯子 vs选译决定的，consol就是main，win32就是winmain
  - @見賢思齊 由运行时库决定的吗
  - 据我所知应该是编译时决定的，Windows 有命令行子系统和窗口子系统，不是同一回事
    - 关于这个可以参见这篇文章：
    - @See https://nullprogram.com/blog/2021/02/08/#:~:text=Solution%3A%20compiled%20shell%20%E2%80%9Cscripts%E2%80%9D
- 是不是可以抓包之后伪造成别人的电脑绕过wifi密码直接上网？
  - @dragove 我看他们的思路和前面那个老哥说的差不多，就是强制让WiFi断连然后WiFi一般都会是自动去连接，有一个密码校验然后抓连接的时候握手包，分析握手包
  - 我也不是很了解，我对 WIFI 的唯一了解来自这个视频：https://b23.tv/av202477524 根据视频内的说法，现在主流的带密码的WIFI在连接过程中是加密的，不过可以暴力破解密码
- 反过来也是，多进程和多线程架构在两个操作系统上效能差距很大
  - 是的，这更多是两个操作系统接口设计的巨大差异导致的，用一个去模拟另一个非常困难，并不是说不能被模拟的那个接口就是更先进的接口，也有可能只是差异过大，或者也可能是设计太过糟糕
- 大佬们我遇到一个神仙问题，就是我Ubuntu突然密码进不了了
  - 先切到tty，登录root用户，再用faillock --reset --user <username>来解锁输错密码被锁定的用户
- [Linux 社区已经成为了一个肮脏的泥潭](https://zhuanlan.zhihu.com/p/451374861)
- 这些廉价机器，其实就是可以用来搞Hadoop生态的，但是我用完之后就基本上用不到了，Hadoop当时的灵感来源就是用廉价机器做成计算集群，但是对于 Spark那种框架，用廉价机器就没那么好的效果了，Spark和Flink这些东西需要更高的配置
- [WebVirtCloud is virtualization web interface for admins and users](https://github.com/retspen/webvirtcloud)
- 如果你是想在笔记本上面用一个Linux发行版，比较推荐的是用 Fedora，最好是Gnome桌面的，基本上没有驱动方面的担忧

## Summary

闷热的天气总是会给人带来厚重的疲惫感，并降低工作效率。
今天忙了一天的工作，感觉很疲惫，不过也有一点小满足感。
明天计划回顾一下前端知识，然后继续学习剩下的一小部分 CSS 的内容。
