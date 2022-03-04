# 2022年3月3日，星期四
## Todo List

- [x] 复习昨天的单词
- [x] [背诵 10 个新单词](#背诵-10-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] [每日一道算法题](#每日一道算法题)
--------
- [x] 精读《Rust 权威指南》第 10 章
- [x] 刷 B 站
  - [x] [带大家去山里看养殖杂交野猪第三代！顺便弄一只回来烤！](https://b23.tv/asqoLc4)
  - [x] [英国博士生vlog|新生活与新开始 学游泳看新房办公室学习](https://b23.tv/fUxmYsz)
- [x] 刷知乎
  - [x] [了解下Rust模块使用方式](https://zhuanlan.zhihu.com/p/474899358)
  - [x] [结构化面试3次失败，从说不清楚话，到93分，我是如何做到的！（经验分享）](https://zhuanlan.zhihu.com/p/373103164)

### 背诵 10 个新单词

1. **differentiate**
  - v. 区别，区分
  - dif·fer·ent·i·ate => different【不同的】+ -i- + -ate 表动词。引申义辨别，使差异化。
  - dif·fer·ent => differ【不同】+ -ent 表形容词。
  - dif·fer => dif- 分开 + fer- 带来 → 分开带 → 不同。

2. **entire**
  - n. 整个，全部
  - a. 全体的，完全的，全部的
  - en·tir·e => en- 否定 + tir- 接触 + -e → 没有被接触过，没有被破坏过 → 完整的。

3. **general**
  - n. 一般，将军，大体
  - a. 全面的，大体的，总的，一般的，普遍的
  - n. 常规
  - gener·al => gener- 出生 + -al → 出生[一般] → 普通的。

4. **overall**
  - a. 全部的，全体的，从头至尾的，一切在内的
  - ad. 从头到位，总的来说
  - n. 罩衫，工作服
  - over·all => over- 在上 + all【全部的】。

5. **throughout**
  - ad. 到处，贯穿全部地，自始自终
  - prep. 遍及，在各处
  - through·out => through【穿越】+ out 外面的。

6. **comprehensive**
  - a. 广泛的，有理解力的，综合的
  - com·prehens·ive => com- 全部 + prehens- 抓住 + -ive 表形容词 → 全部抓住的 → 综合性的，是单词 comprehend 派生的形容词。

7. **universal**
  - a. 全世界的，普遍的，宇宙的，通明的
  - n. 一般概念
  - uni·vers·al => uni- 一个 + vers- 转 + -al 名词或形容词后缀 → 即转为一体的，引申义通用的。

8. **universality**
  - n. 大学
  - uni·vers·ity => uni- 一个 + vers- 转 + -ity 表名词 → 由宇宙引申为知识，知识之地 → 大学。

9. **wholly**
  - ad. 完全地，整个，统统，全部
  - whol·ly => whole【全部】+ -ly 副词后缀，是单词 whole 派生的副词。

10. **link**
  - n. 环，连结物，链接，火把
  - vt. 连结，联合，挽住
  - vi. 连接起来
  - 来自 PIE kleng 弯，转。来自 PIE klei 弯，转，倾斜，词源同 lean，incline 引申词义关联，联系。


### 赏析一句英语句子

It is hard, the state argues, for judges to assess the implications of new rapidly changing technologies.

加州政府认为，让法官去评估日新月异的技术所产生的潜在影响确实比较困难。

#### 句子主干

- It is hard... （主+系+表）
- **It**
  - for judges to assess the implications
  - It 为形式主语，动词不定式短语作真正的主语

#### 一级修饰

- **It is hard...**
  - the state argues,
  - 插入语
- **the implications**
  - of new and rapidly changing technologies.
  - 介词短语作后置定语，修饰 the implications

#### 要点注释

for judges to... 中，介词 for 引出动词不定式短语的逻辑主语 judges。

#### 词汇注释

- `argue` v. 争吵，辩论 vt. 坚决主张，提出理由证明
- `assess` vt. 评估，评定，估算
- `implication` n. 可能的影响
- `rapidly` ad. 迅速地，很快地，立即
- `new rapidly changing` 日新月异

### 每日一道算法题

[26.删除有序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array)

> 给你一个**升序排列**的数组 `nums`，请你**原地**删除重复出现的元素，使每个元素**只出现一次**，返回删除后数组的新长度。
> 元素的**相对顺序**应该保持**一致**。
> 由于在某些语言中不能改变数组的长度，所以必须将结果放在数组 `nums` 的第一部分。
> 更规范地说，如果在删除重复项之后有 `k` 个元素，那么 `nums` 的前 `k` 个元素应该保存最终结果。
> 将最终结果插入 `nums` 的前 `k` 个位置后返回 `k`。
> 不要使用额外的空间，你必须在**原地修改输入数组**并在使用 **O(1)** 额外空间的条件下完成。
> 
> 判题标准：
> 
> 系统会用下面的代码来测试你的题解：
> 
> int[] nums = [...]; // 输入数组
> int[] expectedNums = [...]; // 长度正确的期望答案
> 
> int k = removeDuplicates(nums); // 调用
> 
> assert k == expectedNums.length;
> for (int i = 0; i < k; i++) {
>     assert nums[i] == expectedNums[i];
> }
> 如果所有断言都通过，那么您的题解将被**通过**。
> 
> 示例 1：
> 输入：nums = [1,1,2]
> 输出：2, nums = [1,2,_]
> 解释：函数应该返回新的长度 2 ，并且原数组 nums 的前两个元素被修改为 1, 2 。不需要考虑数组中超出新长度后面的元素。
> 示例 2：
> 输入：nums = [0,0,1,1,1,2,2,3,3,4]
> 输出：5, nums = [0,1,2,3,4]
> 解释：函数应该返回新的长度 5 ， 并且原数组 nums 的前五个元素被修改为 0, 1, 2, 3, 4 。不需要考虑数组中超出新长度后面的元素。

## Summary

今天总算是把《Rust 权威指南》第10章读完了，明天开始第11章的内容。
