# 2021年12月28日，星期二
## TODO List

- [x] 复习昨天的单词
- [x] [背诵 20 个新单词](#背诵-20-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
--------
- [x] [阅读一遍 NVIM REFERENCE MANUAL](阅读一遍-NVIM-REFERENCE-MANUAL)
- [ ] 给 Neovim 配置增加一个运行函数
- [ ] 学习如何用 Lua 处理日期和时间
--------
- [ ] 学习杨旭的二分查找算法视频

### 背诵 20 个新单词

1. **assertion**
  - n. 断言，主张
  - as·sert·ion => assert【断言】 + -ion，表名词，是单词 assert 派生的名词。

2. **request**
  - n. 请求，需要，申请书
  - vt. 请求，要求，邀请
  - re·quest => re- 再 + quest【寻求】 → 再寻求 → 要求。

3. **affirm**
  - v. 断言，确认
  - af·firm => af- 一再 + firm【坚定】 → 一再坚定地说 → 证实。

4. **allegation**
  - n. 断言，主张，申辩
  - alleg·ation => allege【宣称】 + -ation 表名词，是单词 allege 派生的名词。

5. **ignore**
  - vt. 不理睬，忽略，忽视，驳回
  - i·gnor·e => i- 不 + gnor- 知道 + -e → 不知道 → 不理睬。

6. **ignorant**
  - adj. 无知识的，不知道的，由无知产生的
  - i·gnor·ant => ignore【无知】 + -ant 表形容词。

7. **neglect**
  - n. 疏忽，忽略，漏做
  - vt. 疏忽，忽视，不顾
  - neg·lect => neg- 否定 + lect- 选择 → 不选择 → 忽视。

8. **overlook**
  - vt. 俯瞰，眺望，没注意到
  - n. 眺望，俯瞰到的景色
  - over·look => over- 上 + look【看】 → 在上面看 → 俯视，再上升为疏忽。

9. **own**
  - adj. 自己的，嫡亲的，同胞的
  - vt. 拥有，支配，自认，承认，顺从于
  - vi. 承认，供认

10. **ownership**
  - n. 所有权，物主身份
  - own·er.ship => owner【所有者】 + -ship 抽象名词后缀。

11. **property**
  - n. 财产，不动产，房地产，属性，性质，特性
  - proper·ty => proper- 个人的 + -ty 名词后缀。即个人或私人所有的财产或财物。

12. **monopoly**
  - n. 垄断，专卖权，独占事业
  - mono·poly => mono- 单个的 + poly- 卖 → 独家卖 → 垄断。

13. **possession**
  - n. 拥有，占有，所有，财产，领土，领地，自制，着迷
  - poss·ess·ion => possess【拥有】 + -ion 表名词 → 能坐在上面 → 拥有，是单词 possess 派生的名词。

14. **possess**
  - vt. 持有，占有，拥有，克制，支配，迷住
  - poss·ess => poss- 有力的 + -ess 存在。

15. **occupy**
  - vt. 占领，占（时间、空间等），住进，担任，使从事，使全神贯注
  - oc·cup·y => oc- 再次 + cup- 抓 + -y → 抓住地盘 → 占领。

16. **occupation**
  - n. 职业，占有，占有期，占领，占领军
  - oc·cup·ation => occupy【占用，占据，居住】 + -ation 表名词。引申词义职业，是单词 occupy 派生的名词。

17. **state**
  - n. 州，状态，情形，国家，政府，隆重仪式
  - adj. 国家的，州的，邦的
  - v. 陈述，说明，公布，规定
  - stat·e => estate n. 财产；身份和 state n. 情况。罗马帝国后期罗马人越发觉着 sc-, sp- 和 st 开头的单词难发音或发音难听，就在前边加了个 e-。

18. **statement**
  - n. 陈述，指令，声明，证词
  - stat·e·ment => state【说明】 + -ment 名词后缀 → 站着说话 → 声明立场。

19. **statesman**
  - n. 政治家
  - stat·es·man => state【政府】 + -s + man【人】。

20. **understatement**
  - n. 软弱无力的陈述，克制的说法
  - under·stat·e·ment => understate【不完全地陈述, 保守地说】 + -ment。

### 赏析一句英语句子

This is what a study, published from the University of California and Yale University in the Proceedings of the National Academy of Sciences, has concluded.

这是由加州大学和耶鲁大学共同发表在《美国国家科学院院刊》上的一项研究得出的结论。

#### 句子主干

- This is what a study, ... has concluded. （主+系+表从）

#### 一级修饰与二级修饰

- **what a study, ... has concluded**
  - published from the University of California and Yale University
  - 过去分词短语补充说明 a study
  - **published**
    - in the Proceedings of the National Academy of Sciences,
    - 介词短语作地点状语

#### 词汇注释

- `proceedings` 会刊，公报
- `academy` 学院，研究院，学会


### 阅读一遍 NVIM REFERENCE MANUAL

昨天这个 TODO 特指 `:h lua` 这部分的内容。

## Get
### 阅读 NVIM REFERENCE MANUAL 的收获

1. **JIT 与 JIT 编译器**

**JIT 编译器**，英文写作 `Just-In-Time Compiler`，中文意思是`即时编译器`。
**JIT** 是一种提高程序运行效率的方法。通常，程序有两种运行方式：*静态编译*与*动态解释*。
静态编译的程序在执行前全部被翻译为机器码，而动态解释执行的则是一句一句边运行边翻译。

2. **提示用户善用 GitHub TOC**

:arrow_upper_left: (Feeling lost? Use the GitHub TOC!)

## Summary

今天速读了一遍 NVIM REFERENCE MANUAL 之 `lua.txt`，有少部分收获，我的词汇量少，阅读起来还是有些困难。
`:h lua` 的内容比之前我阅读的 `nvim-lua-guide-zh` 内容要细致一些，我打算过几天翻译 `lua.txt`。
相比于速读，翻译能让我更深入地学习，或许会花上一天时间才能翻译完。
现在是凌晨 1 点，刚刚赏析完英语句子，准备提交了。昨天的额外 ToDo 今天还是没做完，只能和今天的额外 ToDo 顺延到明天了。
