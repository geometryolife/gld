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
2. **entire**
3. **general**
4. **overall**
5. **throughout**
6. **comprehensive**
7. **universal**
8. **universality**
9. **wholly**
10. **link**

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
