# 2021年12月27日，星期一
## TODO

- [x] [背诵 20 个新单词](#背诵-20-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
--------
- [x] 给 geonv 增加一些配置
  - [x] 增加分屏、调整窗口、打开 rc 文件的键映射
  - [x] 增加 Markdown snippets
- [ ] 阅读一遍 NVIM REFERENCE MANUAL
- [ ] 给 Neovim 配置增加一个运行函数
- [ ] 学习如何用 Lua 处理日期和时间


### 背诵 20 个新单词

1. **define**
  - vt. 定义，规定，使明确
  - de·fin·e => de-加强 + fin-限制 + -e → 加强限制 → 下定义。

2. **definition**
  - n. 定义，精确度，清晰度
  - de·fin·ition => definite【明确的】 + -ion。即明确范围，定义，解释，是单词 definite 派生的名词。

3. **identify**
  - vt. 鉴定，识别，认出，确认，发现，察觉，理解，认同，支持，同情，与...有密切关系
  - vt. & vi. 等同于，有关联
  - ident·ify => ident-相同 + -ify使... → 认出相同的东西。

4. **identifiable**
  - adj. 可辨认的，可以确认的
  - ident·ifi·able => identify【确认】 + -i- + -able，表形容词。

5. **identity**
  - n. 身份，相同，一致，特性，恒等式
  - ident·ity => ident- 相同 + -ity 表名词 → 同一性。

6. **determine**
  - v. 决定，决心，测定，确定
  - de·termine => de-加强动作 + termin-界限 → 加强界限 → 下决心。

7. **determinism**
  - n. 决定论，宿命论
  - de·termin·ism

8. **judge**
  - n. 法官，裁判员，审判员，鉴定人
  - vt. 审理，鉴定，判断，判决，裁定
  - vi. 下判断，作评价

9. **behavior**
  - n. 行为，举止，表现
  - be·hav·ior => be- 表示动作 + have【有】 + -ior → [一个人]拥有的动作 → 举动。

10. **behavioral**
  - adj. 行为的，动作的
  - be·hav·ior·al

11. **conduct**
  - n. 行为，举动，举止，指导，实施方式
  - vt. 为人，指挥，管理，实施，传导（电、热）
  - con·duct => con-共同 + duct-引导 → 引导大家一起做 → 指挥。

12. **manner**
  - n. 样子，礼貌，礼节，风格，方式，方法，态度，规定，（人或物的）种类
  - man-, manu- = 手

13. **performance**
  - n. 施行，工作情况，成绩，行为，表现，演出，表演，性能，执行，履行
  - per·form·ance => perform【履行，表现】 + -ance, 表名词。引申词义性能等。

14. **demand**
  - n. 要求，需求，需要
  - v. 要求，查询
  - de·mand => de-一再 + mand命令 → 一再令人做 → 苛求。

15. **require**
  - vt. 需要，命令，要求
  - re·quire => re-再 + quire-询问 → 再寻求 → 请求。

16. **claim**
  - n. 要求，要求权，断言，权利，声称，索要，索赔
  - vt. 要求，认领，主张，索要
  - vi. 提出要求，主张，断言
  - claim- = cryout，shout，表示“呼喊，叫喊”。

17. **acclaim**
  - n. 喝彩，欢呼，赞同，赞扬
  - v. 欢呼，喝彩，称赞
  - ac·claim => ac-一再 + claim-喊 → 一再喊 → 欢呼。

18. **claimant**
  - n. 提出要求者，原告，索偿人
  - claim·ant => claim【要求】 + -ant

19. **command**
  - n. 命令，指挥，控制，部队，司令部
  - v. 命令，指挥，控制
  - com·mand => com-一起 + mand-命令 → 命令大家一起做 → 指挥。

20. **assert**
  - vt. 主张，坚持，断言，维护
  - as·sert => as + sert-插入 → 强行插入观点 → 断言。


### 赏析一句英语句子

Though not biologically related, friends are as "related" as fourth cousins, sharing about 1% of genes.

朋友之间虽然没有血缘关系，但却“亲”如第四代表亲，约有1%的基因相同。

- 句子主干
  - friends are as "related" （主+系+表）

- 一级修饰
  - **frends**
    - Though (they are) not biologically related,
    - Though 引导的让步状语从句，作句子主干的让步状语
  - **related**
    - as fourth cousins (are),
    - as 引导的比较状语从句
  - **are**
    - sharing about 1% of genes.
    - 现在分词短语作伴随状语

- 词汇注释
  - `biologically` 生物地，生物学地，生物学上
  - `gene` 基因


## Get
### 使用 Neovim 的收获

1. `:!`
  ```vim
  " 使用 shell 执行命令
  :!{cmd}
  ```

2. `:r` 或者 `:re` 或者 `:read`
  ```vim
  " 在光标下方插入文件
  :r[ead] [++opt] [name]
  ```
  
3. `:r!` 或者 `:read!`
  ```vim
  " 执行命令并将其标准输出插入到光标或指定行的下方
  :[range]r[ead] [++opt] !{cmd}
  ```

4. `v_g_CTRL-A` 与 `v_g_CTRL-X`
  ```vim
  " 生成递增序列
  {Visual}g CTRL-A
  " 生成递减序列
  {Visual}g CTRL-X
  ```


## Others

**时间管理（Time Management）** 就是用技巧、技术和工具帮助人们完成工作，实现目标。时间管理并不是要把所有事情做完，而是更有效的运用时间。时间管理的目的除了要决定你该做些什么事情之外，另一个很重要的目的也是决定什么事情不应该做；时间管理不是完全的掌控，而是降低变动性。时间管理最重要的功能是透过事先的规划，做为一种提醒与指引。


## Summary

今天开启了生活日记的记录旅程～
