# 2022年3月4日，星期五
## Todo List

- [x] 复习昨天的单词
- [x] [背诵 10 个新单词](#背诵-10-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] [每日一道算法题](#每日一道算法题)
--------
- [x] 敲一遍《Rust 权威指南》第 8 章动态数组部分的代码
- [x] 刷 B 站
  - [x] [【个人成长】我不是一个好学生！也不爱看书！但我四年成专家！](https://b23.tv/jMxTkNi)
  - [x] [【超高級和包丁】用ZDP189制作一把镜面柳刃日式厨刀](https://b23.tv/0y4jirQ)
  - [x] [分享南怀瑾老先生治疗肠胃病的一个秘方](https://b23.tv/YUC9gOy)
  - [x] [南怀瑾老师讲肠胃对于一个修行人的重要性](https://b23.tv/mjSwVcJ)

### 背诵 10 个新单词

1. **related**
  - a. 讲述的，叙述的，有关系的，有关联的，相关的，有联系的
  - re·lat·ed => relate【相关，讲】+ -ed 表形容词 → 相关的，讲述的。

2. **relatively**
  - ad. 相对地，比较地，相当地，相关地
  - re·lat·ive·ly => relative【有关系的】+ -ly 副词后缀，是单词 relative 派生的副词。

3. **relate**
  - vt. 讲，叙述，使互相关联
  - vi. 有关，符合，相处得好
  - re·lat·e => re- 向后，往回 + lat- 拿，带 + -e → 即带回来，引申词系联系，相关。

4. **relative**
  - n. 亲戚，关系词
  - a. 有关系的，相对的，比较的
  - re·lat·ive => relate【关系，相关】 + -ive 形容词后缀，是单词 relate 派生的形容词。

5. **tie**
  - n. 带子，线，鞋带，领带，领结，关系，束缚，平局，不分胜负
  - vt. 系，打结，扎，约束，与...成平局
  - vi. 结合，打结，不分胜负

6. **contact**
  - n. 联系，交际，熟人，接触
  - vi. 接触，联系
  - vt. 使接触
  - con·tact => con- 共同 + tact- 接触 → 共同接触。

7. **concerning**
  - prep. 关于
  - con·cern·ing => concern【关心】+ -ing 表介词。
  - con·cern => con- 强调 + cern- 分开，筛选，即区分开的，关心自己那一部分的。

8. **relevant**
  - a. 有关联的，有关系的，适当的，相应的
  - re·lev·ant => re- 再 + lev- 举起 + -ant 表形容词 → 再举起 → 有关的。

9. **irrelevant**
  - a. 不恰当的，无关系的，不相干的
  - ir·re·lev·ant => ir- 不，非 + relevant【相关的】→ 不相关。

10. **regarding**
  - prep. 关于，至于
  - re·gard·ing => regard【和……有关】+ -ing 表介词。
  - re·gard => re- 再，重新 + gard- 看，看护 → 一再看护 → 关心，看待。


### 赏析一句英语句子

The court would be recklessly modest if it followed California's advice.

如果法院听取了加州政府的建议，那它真是"谦虚"得不计后果。

#### 句子主干

- The court would be recklessly modest （主+系+表）

#### 一级修饰

- **The...modest**
  - if it followed California's advice.
  - if 引导的条件状语从句，做句子主干的条件状语

#### 词汇注释

- `recklessly` ad. 不计后果地，不顾一切地，不在乎地，鲁莽地
- `modest` a. 谦虚的，适度的

### 每日一道算法题

[2169.得到 0 的操作数](https://leetcode-cn.com/problems/count-operations-to-obtain-zero)

> 给你两个**非负**整数`num1`和`num2`。
> 每一步**操作**中，如果 `num1 >= num2`，你必须用 `num1` 减 `num2`；否则，你必须用 `num2` 减 `num1`。
> 例如，`num1 = 5` 且 `num2 = 4` ，应该用 `num1` 减 `num2`，因此，得到 `num1 = 1` 和 `num2 = 4`。
> 然而，如果 `num1 = 4` 且 `num2 = 5`，一步操作后，得到 `num1 = 4` 和 `num2 = 1`。
> 返回使 `num1 = 0` 或 `num2 = 0` 的**操作数**。
> 
> 示例 1：
> 输入：num1 = 2, num2 = 3
> 输出：3
> 解释：
> - 操作 1 ：num1 = 2 ，num2 = 3 。由于 num1 < num2 ，num2 减 num1 得到 num1 = 2 ，num2 = 3 - 2 = 1 。
> - 操作 2 ：num1 = 2 ，num2 = 1 。由于 num1 > num2 ，num1 减 num2 。
> - 操作 3 ：num1 = 1 ，num2 = 1 。由于 num1 == num2 ，num1 减 num2 。
> 此时 num1 = 0 ，num2 = 1 。由于 num1 == 0 ，不需要再执行任何操作。
> 所以总操作数是 3 。
> 
> 示例 2：
> 输入：num1 = 10, num2 = 10
> 输出：1
> 解释：
> - 操作 1 ：num1 = 10 ，num2 = 10 。由于 num1 == num2 ，num1 减 num2 得到 num1 = 10 - 10 = 0 。
> 此时 num1 = 0 ，num2 = 10 。由于 num1 == 0 ，不需要再执行任何操作。
> 所以总操作数是 1 。


## Summary

今天上午出去拿中药了，耽误了一上午，没有学习什么。
下午花了半小时回顾了 The Book 前 7 章的内容，花了一个半小时敲代码。
吃完晚饭，花了两个小时买了个保温饭盒，还买了几本技术书籍：
《Kali Linux 高级渗透测试》、《Go 黑帽子》、《Rust 实战：从入门到精通》、《Rust 编程之道》、《面向 WebAssembly 编程：应用开发方法与实践》。
最后报名了 LeetCode 周赛，模拟了一次前几期中美团的周赛，用 Rust 写感觉还是蛮舒服的。
