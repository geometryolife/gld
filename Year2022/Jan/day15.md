# 2022年1月15日，星期六
## Todo List

- [x] 复习昨天的单词
- [x] [背诵 20 个新单词](#背诵-20-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
--------
- [x] 看完 GoWP 第三章的内容
- [x] [写一篇知乎回答贴](#写一篇知乎回答贴)
- [x] 将知乎回答贴同步到公众号、今日头条
- [x] [理解空格](#理解空格)

### 背诵 20 个新单词

1. **evade**
2. **flee**
3. **retreat**
4. **fulfill**
5. **fulfillment**
6. **engage**
7. **engagement**
8. **engaged**
9. **implement**
10. **implementation**
11. **exert**
12. **resort**
13. **operational**
14. **operative**
15. **operator**
16. **exploit**
17. **exploitation**
18. **practitioner**
19. **slave**
20. **slavery**

### 赏析一句英语句子

When public opinion is particularly polarised, as it was following the end of the Franco regime, monarchs can rise above "mere" politics and "embody" a spirit of national unity.

当公众舆论两极分化严重时，就像弗朗哥政权结束时那样，君主能够超越“纯粹的”政治，并“体现”民族团结的精神。

#### 句子主干

- monarchs can rise above "mere" politics （主+谓+宾）
- **can...politics**
  - and (can) "embody" a spirit of national unity
  - and 连接的并列谓宾

#### 一级修饰和二级修饰

- **monarchs**
  - When public opinion is particularly polarised,
  - When 引导的时间状语从句，作句子主干的时间状语
  - **When...polarised,**
    - as it was following the end of the Franco regime,
    - as 引导的非限定性定语从句，补充说明时间状语从句

#### 词汇注释

- `opinion` n. 舆论
- `particularly` ad. 特别，尤其
- `polarise` v. 两极分化，截然对立
- `regime` n. 政权，政体，管理体制

### 写一篇知乎回答贴

[Go 语言如何入门，求入门书籍推荐？](https://www.zhihu.com/question/510570892/answer/2311513272)

### 理解空格

本文对了解的空格分为几个Level，看大家能达到哪个level。

- **Level1：半角空格**

历史最悠久的空格，在1967年，ASCII 规范中被定义。
空格在 ASCII 中编码为0x20, 占位符为一个半角字符。在日常英文书写和代码编写中使用。

- **Level2: 全角空格**

中文输入中的空格（标准说法为中日韩表意字符(CJK)中使用的宽空格）。和其他汉字一样，作为GBK的一个字符，其对应的unicode码为u3000.宽度是2个半角空格的大小。
例如：

```text
  国父　孙中山先生
```

- **Level3: 不间断空格（non-breaking space）**

unicode 为 u00A0, 在代码中可能会出现的编码错误（utf8 编码0xC2 0xA0）就是它了。
在Word中，会遇到一个有多个单词组成的词组被分割在两行文字中，这样很容易让人看不明白。这时候，不间断空格就可以上场了。
输入不间断空格，会将不间断空格连着的单词在一行展示。

上面英文使用了不间断空格，下面没有使用。所以上面的英文自动在一行展示，而下面没有。
在word中输入不间断空格的方式为（Ctrl + Shift + Space）

除了在 Word 等文本编辑软件中使用，其实不间断空格在 html 中大量使用。`&nbsp;` 是 html 中最为常见的空格。
由于 html 页面中，如果有多个连着的半角空格，则空格只会展示一个。而使用 `&nbsp;` 空格，则会显示占位半个自宽。

- **Level4: 零宽度空格（ZERO WIDTH SPACE）**

零宽度空格有两种：

零宽度空格 unicode 编码为 u200B.
不可见非打印字符。有了半角空格，也有了全角空格，其实还有零宽度空格。因为宽度为零，因此该字符是一个不可见字符。
这个编码虽然是不可见的，但是也是非常有用的。它可以替换 html 中的`<wbr/>`标签(软换行, html5 新增)。

零宽度非中断空格（ZWNBSP）的 unicode 编码为 u2060 （之前使用 ufeff 表示，unicode 3.2 开始 ufeff 标记 unicode 文档的字节序。）
该空格结合了 non-breaking space 和 零宽度空格的特点。既会自动换行，宽度又是0。

零宽度空格（软换行）举例：

```text
一行连续的英文编码:

<p style="font-size:100px;">PhpIsTheBestProgramingLanguageInTheWorld</p>
chrome 中将显示不换行：


而如果在每个可以换行的地方加上 <wbr />, 则可以在标记的最近的地方换行。

<p style="font-size:100px;">Php<wbr />Is<wbr />The<wbr />Best<wbr />Programing<wbr />Language<wbr />In<wbr />The<wbr />World</p>
chrome 中将显示：
```

- **Level5: 其他空格字符空格**

虽然已经有半角空格、全角空格，但是上面的空格如果字体变化了，不会随着字体的变化而变化。
因此，又有了可以随着字体的变化而变化的空格，简单罗列如下：

在 html 的宽度度量中，有一种单位叫 em，是按照字体大小定义的，下面的 em 也是字体的宽度。
打印字符的空格有很多种，罗列几个：

| 名称                             | unicode 编码 | html 标记       | 特征和用途                                                                                  |
|----------------------------------|--------------|-----------------|---------------------------------------------------------------------------------------------|
| 短空格                           | u2002        | `&ensp;`        | html 中占位半个字                                                                           |
| 长空格                           | u2003        | `&emsp;`        | html 中占位一个字                                                                           |
| 1/3em空格                        | u2004        | `&emsp13;`      | 占用1/3个空格                                                                               |
| 1/4em空格                        | u2005        | `&emsp14;`      | 占用1/4个空格                                                                               |
| 1/6em空格                        | u2006        | `&emsp14;`      | 占用1/6个空格                                                                               |
| 数样间距 (figure space)          | u2007        | `&numsp;`       | 在等宽字体中，宽度是一个字符的宽度。                                                        |
| 行首前导空格 (punctuation space) | u2008        | `&puncsp;`      | 宽度约为 0x20 的宽度。                                                                      |
| 瘦弱空格 (thin space)            | u2009        | `&thinsp;`      | 宽度是全角打印空格的 1/5 或者 1/6 (宽度不定，法文设置为1/8)，主要用在打印两个空的引号之间。 |
| hair space                       | u200a        | `&hairsp;`      | (浏览器目前不支持), 最窄的空格，推荐标准为 (1/10, 1/16)                                     |
| narrow no-break space            | u202f        | `&nnbsp;`       | 和0a 类似，不同语种中不太一样。                                                             |
| medium mathematical space        | u205f        | `&mediumspace;` | 在格式化数学公式时使用。是 4/18 的 em宽度，例如："a + b"中，a 和 + 之间应该用 这个空格      |

[本文原地址](https://segmentfault.com/a/1190000022353208)

## Get
### 使用 Neovim 的收获

1. `list` 选项
  默认关闭，开启后可以显示缩进的符号、行尾的符号等。
```text
列表模式：默认情况下，将制表符显示为">"，将尾随空格显示为"-"，将不可分割的空格字符显示为"+"。
有助于查看制表符和空格之间的差异以及尾随空格。"列表字符"选项进一步更改。

光标显示在 Tab 字符所占用空间的开头，而不是像往常在正常模式下那样显示在末尾。
要在显示带空格的制表符时获取此光标位置，请使用：
:set list lcs=tab:\ \ 
```

2. `listchars` 选项
  这个选项可以设置缩进标记、行尾标记的符号等。
```text
在"list"模式和：list 命令中使用的字符串。
它是以逗号分隔的字符串设置列表。
```

## Others

人在输出东西的时候提神，输入东西的时候犯困，这个现象很普遍，不过这个只是表象。
大脑是一个非常神奇的感知机、调节机，造成上面的现象或许是大脑的某个区域正在休眠。
让人快速入睡的一个方法，就是让大脑疲惫。如何让大脑疲惫？

当身体进入放松状态，让大脑去做一些输入性的工作，比如进入`冥想`，想象一些东西，思考一些问题，人能在非常短的时间里入睡。

## Summary

今天，我花了半天时间写了一篇帖子，接近 3000 字。
或许现在的知识储备还是太少了，如此短的一篇内容还是得花很长时间。
如果一天写一篇内容，那么将占据我大把时间，留给自己的时间就非常少了。

今天最大的收获就是使用 Neovim 时了解了 `list` 和 `listchars` 选项，并以此引导我去了解了多种类型的空格。
因为在此之前，我知道空格只有半角与全角之分，Neovim/Vim 就像一个宝藏库，学习一个小技巧就像发现了某个宝藏。
他能不断地驱使我去探索和求知，毕竟 Vi 家族凝聚了半个多世纪程序员们智慧的结晶。
