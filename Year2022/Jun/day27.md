# 2022年6月27日，星期一

## Todo List

- [x] 晨跑三公里
- [x] 冥想 20 分钟
- [x] 复习单词
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] 每日英语晨读纠音
- [x] 流利说英语打卡
- [x] 英语趣配音打卡
- [x] 芝士派英语打卡
  - [x] 早间 - Elephant's Incredible Memory
  - [x] 晚间 - Meilin Lee and Her Friends Collecting Money for Concert | Turning Red
- [x] 每日一道算法题
--------
- [x] 刷 B 站
  - [x] [【下一站，茶山刘（东南大学版）】](https://b23.tv/ldffPgZ)
  - [x] [价值70元一只的法国极品生蚝如何养殖？全靠一根大棒槌](https://b23.tv/eYbEbjI)
  - [x] [刘强东套现66亿 拿出5.6亿欧洲买豪宅做岛主？](https://b23.tv/6baDf20)
  - [x] [一条视频价值6亿，和苹果总裁库克对话，央视点名何同学有多牛？](https://b23.tv/852VJUQ)
  - [x] [存储只是用来扩容？那你亏大了！看看如何百分百压榨存储的价值](https://b23.tv/gamEOAc)

### 赏析一句英语句子

The parliament also agreed to ban websites that "incite excessive thinness" by promoting extreme dieting.

议会还同意封禁那些通过宣传极端节食来“煽动过度瘦身”的网站。

#### 句子主干

- The parliament also agreed to ban websites （主+谓+宾）

#### 一级修饰和二级修饰

- **websites**
  - that "incite excessive thinness"
  - that 引导的定语从句，修饰 websites
  - **incite**
    - by promoting extreme dieting.
    - 介词短语作方式状语

#### 词汇注释

- `parliament` n. 议会，国会
- `ban` vt. 禁止 n. 禁令
- `incite` vt. 煽动，鼓动
- `excessive` a. 过度的，过分的

### 芝士派英语打卡

#### [Elephant's Incredible Memory 大象记忆力惊人，简直就是“移动的硬盘”！](https://reading.baicizhan.com/h5/listen-movie.html?id=763&wxapp=mint_danni_ear#/home)

- **词汇**

  - `incredible` a. 极好的
  - `benevolent` a. 仁慈的
  - `hostile` a. 敌对的
  - `as many as` 多达

- **大象的记忆力为什么这么好？**

大象的大脑是陆地上所有哺乳动物当中最大的，趋同的进化让它的大脑呈现出和人类大脑近似的结构。
大象的脑部有着很多的神经元和神经突触，以及高度发达的与情感有密切关联的海马体，如此一来，大象的一些重要体验都能够被刻入长期的记忆里。
这种对重要程度的分区功能，让大象的记忆成为了一个复杂而且具有适应能力的载体，也让大象的记忆力能够远超机械记忆。
独特的大脑结构正是大象记忆力这么好的原因。

#### [Meilin Lee and Her Friends Collecting Money for Concert | Turning Red 青春变形计——可爱哭了！谁会不想rua胖嘟嘟的小熊猫呢！](http://reading.baicizhan.com/h5/listen-movie.html?id=764&wxapp=mint_danni_ear#/home)

- **词汇**

  - `magical` a. 有魔力的
  - `keyney` 肾
  - `that's the stuff` 这就对了

- **小熊猫为什么叫“小”熊猫？**

众所周知，小熊猫并不是指幼年时期的大熊猫，而是一种和大熊猫不同的生物，那为什么小熊猫会被称作“小”熊猫呢？
其实，最初“熊猫”是属于小熊猫的称呼，包括其英文名称 Panda（尼泊尔语，红色的猫），最早也是指小熊猫。
后来，外国人在野外发现了大熊猫，又因为大熊猫被发现时和小熊猫在一起，而大熊猫又比小熊猫大很多，所以被称为大熊猫（giant panda），而小熊猫改称为红熊猫（red panda）。

### 群聊的收获

- 基本上主流软件都可以在archwiki上搜索到，质量也都不错，省去了找文档的烦恼。用arch是真的能帮你节省大量时间
  - 当然，使用老版本编译器这种需求什么的，arch对于老软件的支持就那样了，
  - 有这种需求可能就不太适合使用archlinux（虽然docker一般能解决）
- @银河-蜗牛 分享文件的那种吗，加入的节点越多越快那种？
  - syncthing吗？你说的是 btorrent 吧。syncthing 我印象中算法是类似 rsync 的，应该不能多设备加速。不过挺久没看文档了我也记不清楚了
- Arch Linux 0.1版本与02年发布 @see https://wiki.archlinux.org/title/Arch_Linux#The_early_years
- scp 协议被弃用了
  - 但不代表 scp 命令不能用了
  - 现在 openssh 9.0 当中 scp 命令默认使用 sftp 协议，而不是 scp 协议
  - 旧版本也可以用 scp -s 使用 sftp 协议传输
  - https://wiki.archlinux.org/title/SCP_and_SFTP#Secure_copy_protocol_(SCP)
  - scp现在默认用 sftp 协议
    - 旧版本 openssh 也可以用 scp -s 来使用 sftp 协议（刚才提到过
- wayland一堆接口都还不稳定，而且sway上有好多接口都还没有实现，感觉开发进度也挺慢的
  - wayland现在坑可能比 x11 还多，但是架构上比x11有优势太多了
  - 好像我见到的wayland下的wm，都使用wlroots作为依赖
- 记得前不久看的一篇文章：
  - https://dudemanguy.github.io/blog/posts/2022-06-10-wayland-xorg/wayland-xorg.html
  - https://news.ycombinator.com/item?id=31752760 Wayland 不会拯救 Linux 桌面
- 这个我不是很了解，我对 Wayland 协议具体规定了些什么都不太了解（这个有什么资料吗，还是说直接读规范文档？

## Summary

今天找师傅把升降桌按好了，整个流程感觉很容易，早知道这么简单我就自己安装了。
我想轻微吐槽一下，这个安装师傅的活做得一般般，升降桌控制面板有些歪，不过倒不是很影响使用，只是有些不整齐，看起来不美观。
这个控制面板的按钮有些是有问题的，今晚联系了客服，明天看售后怎么处理吧。
