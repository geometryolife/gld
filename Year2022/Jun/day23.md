# 2022年6月23日，星期四

## Todo List

- [x] 冥想 30 分钟
- [x] 复习单词
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] 每日英语晨读纠音
- [x] 流利说英语打卡
- [x] 英语趣配音打卡
- [x] 芝士派英语打卡
  - [x] 早间 - Here's the Best Time of Day to Take a Shower
  - [x] 晚间 - Funny Friends Moments
- [x] 每日一道算法题
--------
- [x] Web 前端零基础入门 P116-P125
- [x] 刷 B 站
  - [x] [老爸今天又吃出了“大锅饭”新高度](https://b23.tv/wZKCgqz)
  - [x] [拳打M1？M2芯片到底如何？M2 MacBook Pro上手](https://b23.tv/J937A2F)
  - [x] [【建筑之美】大疆深圳总部“天空之城”，在天上办公是什么感觉？](https://b23.tv/akYDIOM)
  - [x] [【4K】大疆总部天空之城即将竣工，2022年最值得期待的建筑，深圳新地标](https://b23.tv/9FO7Iz4)
  - [x] [Zaha Hadid Architects——深圳湾超级总部基地C塔项目](https://b23.tv/6YKU84C)
  - [x] [油豆腐这个做法火了，饭店卖48元，成本不到10元，鲜香入味真解馋](https://b23.tv/4uZgIaF)
  - [x] [这是甜妹会发出的声音吗？反差萌翻唱《荒羽》](https://b23.tv/ZkYrfNm)

### 赏析一句英语句子

Each spouse retains whatever property he or she brought into the marriage, and jointly-acquired property is divided equally.

夫妻双方在离婚后可保留各自带入婚姻的任何财产，他们共同获得的财产则被平均分配。

#### 句子主干

- (1) Each spouse retains （主+谓+宾从）
- **Each spouse**
  - (2) and jointly-aquired property is divided equally. （主+谓）
  - and 连接的并列句
- **retains**
  - whatever property he or she brought into the marriage,
  - whatever 引导的宾语从句，作 retains 的宾语

#### 词汇注释

- `retain` vt. 保留，保持，聘请
- `jointly` ad. 共同地，联合地

### 芝士派英语打卡

#### [Here's the Best Time of Day to Take a Shower 洗澡时间还会影响睡眠时间？早洗还是晚洗，别选错了！](https://reading.baicizhan.com/h5/listen-movie.html?id=755&wxapp=mint_danni_ear#/home)

- **词汇**

  - `circadian` a. 昼夜节律的
  - `slumber` v. 睡觉
  - `constantly` ad. 持续不断地
  - `come up with` 提出
  - `back up` 证实

- **你真的会洗澡吗？**

洗澡水温最佳的温度是35-40°C，不过由于夏天和冬天的温度差异，建议夏天的洗澡水温在37°C，冬天在40°C最为合适。
洗澡水的水温过高，皮肤毛细血管扩张，表面的油脂更容易被破坏，会加剧皮肤干燥的程度，给皮肤带来损伤，再加上热水刺激皮肤神经末梢，会使皮肤有痛痒感。
而水温过低会让毛孔紧闭、血管骤缩、体内的热量散发不出，也容易受凉感冒。
如果长时间洗凉水澡，也容易诱发关节炎以及慢性的胃肠疾病。
而最佳的洗澡时间在10-15分钟，洗澡时间太长的话，皮脂膜会被过度清洁，从而导致皮肤问题。
沐浴露也建议选择pH值偏中性或者弱酸性的，更接近皮肤表层的弱酸性环境。

#### [Funny Friends Moments 老友记——Ross好心办坏事，死亡奏鸣曲吓坏众人](http://reading.baicizhan.com/h5/listen-movie.html?id=756&wxapp=mint_danni_ear#/home)

- **词汇**

  - `parade` n. 旅行
  - `unbelievable` a. 难以置信的
  - `Scottish` n. 苏格兰人
  - `hang out` 闲逛
  - `there is no way` 不可能，绝不

苏格兰风笛 —— 音乐知识小课堂
苏格兰风笛是乐器的一种，属使用哨片的气鸣乐器，由吹管，气囊，演奏管与和旋管组成。
苏格兰风笛的发音粗犷有力、音色嘹亮、采用各种装饰音，适用于表现英雄气概。
苏格兰人的婚礼上最常用的乐器就是风笛。除此之外，风笛还会用在苏格兰人的狂欢节日中。
苏格兰的男男女女常会在某个闲暇的下午时分，吹起风笛，跳起欢快的舞，寻找心仪的对象。

## Get

- 动态节点分配。避免Ext2/3/4对节点数量的限制。
  - Btrfs的节点限制是完全不同的（ext4的节点是在文件系统创建时分配的，创建后不能调整大小，
  - 通常是1-2百万，硬限制是40亿，btrfs的节点是根据需要动态分配的，硬限制是2^64，大约18.4万亿，大约是ext4硬限制的46亿倍）。
  - btrfs有两个硬限制，64bit的object id，和分配给metadata的空间大小
  - btrfs所有数据都以btree节点的形式存在，(objectid，item type，offset) → value
- 太空应该问题不大，太满会导致gc困难
  - gc是啥这里
  - 固态硬盘的垃圾回收
  - 我也不了解具体是啥，看起来好像有点像碎片整理
  - 以前用老旧的机械硬盘的时候，做完碎片整理能明显感觉到性能提升
  - [SSD 就是大U盤？聊聊閃存類存儲的轉換層](https://farseerfc.me/flash-storage-ftl-layer.html)
  - 因为擦除的限制，nand段内只能连续写入，不能随机写，（PS：对nand来说写入是置0，擦除是置1，所以，要垃圾回收做数据整理，有同样连续写入限制的smr也有gc
  - 它时不时就需要stop world to gc，nand读写速度快难以察觉，但是smr读写速度慢就很糟心了
  - 有人曾经在组raid的时候遇到写入的时候smr花20分钟去gc
  - @Coelacanthus | https://blog.coelacanthus.moe 既然写入是置0，擦除是置1，这个寿命应该叫“擦除寿命”叭
    - 擦除的时候消耗寿命，写入的时候不会。
    - 0和1只是表示电压差，而且其实应该叫擦写寿命，一般来说单纯的擦除对用户意义不大，所以叫写入寿命
- Debian 系的 pip 打了很多 patch，行为和上游原版的 pip 很不一样。
  - 原版 pip 默认安装到全局 site-packages，用户级需要添加 --user 参数，
  - 也就是说直接 pip install 是会报 permission dennied。而 Debian 系
  - 而 Debian 系用 sudo 安装也不会装到系统 site-packages 里，而是安装到 /usr/local/lib 里面
  - python 的包管理其实是很简单的，而网上流传的 python 包管理混乱很大程度来自 Debian 乱搞
  - [Debian 系统上捉摸不定的 Python](https://frostming.com/2022/03-27/python-on-debian/)
  - 一般来说最佳实践是，如果安装命令行工具，就用 pipx，如果开发就用 venv
  - 但是这样是项目级的，pyproject.toml 是要进版本控制系统的
  - 这样等于是把用户配置写进项目配置里面了
  - pip 其实就是缺一个可靠的 lock 文件
    - pip-tools 也做得不够完善，它生成的“lock 文件”不是跨平台的
  - 这样来看的话 pip 有点 unix 哲学的味道，虚拟环境用的是 venv（其实是 python 解释器自己支持的），
  - 构建是用 setuptools（现在可以用任意 PEP 517 构建后端）
- 所以我还是推荐使用poetry，poetry除了奇怪的目录命名（好像是某种哈希算出来的），其他都挺不错的
  - poetry 有个硬伤，不能全局换镜像源，必须修改项目 pyproject.toml 里的每一个包才能换源，这很不现实
- python 我觉得一个问题是软件源没有专门的元数据分发，现在有 PEP 了，最近没关注不知道 pypi 部署上没有
  - 没有专门的元数据分发就会导致检查更新的性能很差
  - 我记得还有个用nodejs写的python包管理来着
- 我一般是用`pip install --user -U $(pip list | awk 'NR > 2 {print $1}')`来更新所有包，
  - 这是用户级，如果是开发项目的话就直接用 pip-tools 了，它有更新所有包的功能
  - @see https://setuptools.pypa.io/en/latest/userguide/pyproject_config.html
  - 学到了，但我应该不会加到.zshrc（平时尽量避免使用pip install全局安装，除非那个包官方仓库和aur里都没有并且又有特殊需求不用venv）
  - 其实 --user 安装的包是会覆盖掉本地安装的包的，所以还是有潜在的和发行版冲突的风险，所以一般建议用 pipx
    - pipx 是自动建立一个 venv
  - 好像没有包管理可以解决两个不同的依赖依赖同一个依赖的不同版本的问题
    - 这个问题是没法解决的，除非编程语言层面有办法阻止你把对象跨越库的边界传递
    - 比如依赖B和C，B依赖 A<2.0，C依赖 A>=2.0
    - 除非编程语言有办法阻止你把 A<2.0 返回的值传递给 A>=2.0，否则是不可能安全的
  - 如果有源码，构建工具可以自动把函数名/类名/方法名重命名就可以解决
    - 不过是源码分发的情况下
  - 让构建工具去做这种事情感觉不太安全
    - 那我感觉做得有点过头了，还得构建工具能解析编程语言的语法才行（不如在编程语言级别做这个限制
  - 我几年前这样更新的时候，有一个包卸载的时候出问题了，导致整个更新流程终止，原来的包列表也找不到了
    - 我从来没遇到过一个包卸载出问题导致整个包列表没了的情况，不过 pip 处理包卸载确实有点问题
    - （不如说原子性地处理安装、卸载、升级本身就是个难题），但是我遇到的只会影响卸载失败的那一个包，而不会导致整个包列表都出问题
    - pip 查找包列表是查看每个包的 .dist-info 目录的，每个包都有自己的 .dist-info
- 解释性语言的缺陷+1：包管理工具比编译型语言难做
  - 这点是为什么？
  - 他们有提供二进制的能力（npm和pip都能装很多软件），本身有版本隔离的困难
- [关于依赖管理的真相 — 前端包管理器探究](https://mp.weixin.qq.com/s/t6RZAKb6mXTfXl7XbpZ_vw?utm_source=pocket_mylist)
- 上传包的人风格各式各样，很难保证他们不会用一些魔法操作（比如把函数名写在字符串里，这样重命名的时候也没法检测出来吧）
  - 其实也可以把问题抛黑板开发者。例如java commons collection有两个版本collection和collection4，直接通过包名区分
    - 是的，作为库A的开发者，这是个解决办法
    - 编译型语言这个好做，把版本编码到符号里
    - 确实，符号版本控制。说到这个我就想到，前段时间看过一篇文章，讲C语言的ABI，就是说C语言不支持“把版本编码到符号里”这个操作，导致了很多问题
    - @see https://thephd.dev/to-save-c-we-must-save-abi-fixing-c-function-abi @see https://news.ycombinator.com/item?id=30660528
    - 人编译型语言，完全可以用soversion
- 咦，不是说C的ABI稳定吗？
  - 实现非常稳定，大家不敢动
  - ABI稳定指的是结构体对齐有标准，并且函数符号不会重命名
  - 重命名也不代表不稳定吧？譬如如果语言标准规定了如何编码
    - 对，规定了的话还好，问题是就怕没规定
- 我觉得 soversion 更多算一个兜底机制，告诉你找不到 so 了，该重新编译了
  - 但是ABI要解决的是不需要重新编译
  - 他还是一个共存机制，因为多版本使用不同文件名，所以可以直接共存
    - 至于共存，那确实很少见有包用到了这种共存了
    - 好像现在 arch 的 ffmpeg 是处于这个共存的状态的
    - ffmpeg 应该算是典型的 soversion 的例子
    - 开源软件大家一般直接rebuild或者改改rebuild了，用不太上
      - 大多数库 rebuild 一下没啥问题，但是一些基础库要是 rebuild 的话得重建大量包，所谓“重新编译世界”
      - 所以glibc以版本符号发布
      - 是的，所以基础库就需要符号版本控制了
  - electron也可以吧，版本直接写在文件名里，electron 更多算自带依赖（vendoring）了吧
  - 闭源软件主流环境是Windows，Windows没有soversion
- 以及 Haskell 那种完全没有稳定 ABI 的，天天更新（说的就是你，pandoc）https://github.com/archlinux/svntogit-community/commits/packages/pandoc/trunk
  - haskell 每次更新都要更新所有的反向依赖

## Summary

今天看了十集前端视频，还是有不少收获的，主要是集中在动画效果这部分内容，感觉前端能做不少有趣的东西。
花了一个多小时看完了《Linux 命令行大全》第15章 —— 存储介质，虽然学习到的新内容不多，但也让我了解了一些还没用过的设备命令。
