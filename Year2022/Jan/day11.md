# 2022年1月11日，星期二
## Todo List

- [x] 复习昨天的单词
- [x] [背诵 20 个新单词](#背诵-20-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
--------
- [x] 给 geonv 增加配置
  - [x] 在插入模式下，让 C-p、C-n、C-b、C-f 映射为方向键
  - [x] 在插入模式下，让 C-j、C-k 映射为原 C-n、C-f 的效果
  - [x] 在插入模式下，让 C-m 映射为输入二合字母，且让 Enter 键不失效
- [x] 做午饭、做晚饭

### 背诵 20 个新单词

1. **contest**
  - n. 竞赛，争论
  - vt. 竞争，争取，争辩
  - vi. 竞争
  - con·test => con- 共同 + test【测试】→ 共同测试 → 比赛。

2. **contain**
  - vt. 包含，容纳，控制
  - vi. 自制
  - con·tain => con- 强调 + tain- 持，握。

3. **container**
  - n. 容器，集装箱
  - con·tain·er => contain【包含】+ -er 表物，是单词 contain 派生的动作执行者（施动）名词。

4. **constitute**
  - vt. 构成，组成，任命
  - con·stitut·e => con- 一起 + stitut- 站 + -e → 放到一起 → 构成。

5. **constituent**
  - n. 成分，选民，构成物
  - a. 构成的，组织的，选举的
  - con·stitut·ent => con- 一起 + stitu- 站 + -ent 表名词、形容词。

6. **consist**
  - vt. 组成，存在于，一致
  - con·sist => con- 共同 + sist- 站 → 站到一起 → 组成。

7. **limited**
  - a. 有限制的，有限制，有限责任的
  - n. 特别快车
  - limit·ed => limit【界限，限制】+ -ed 表形容词。

8. **restriction**
  - n. 限制，限定，约束
  - re·strict·ion => restrict【限制】+ -ion 表名词，是单词 restrict 派生的名词。

9. **restrict**
  - vt. 限制，限定，约束
  - re·strict => re- 回 + strict- 拉 → 拉回来 → 限制。

10. **restrictive**
  - a. 限制的，约束的，限定的
  - n. 限制词
  - re·strict·ive => restrict【限制】+ -ive 表形容词，是单词 restrict 派生的形容词。

11. **constraint**
  - n. 强制，约束
  - con·straint => con- 一起 + straint 拉 → 拉到一起 → 限制，强制。

12. **constrain**
  - vt. 强迫，限制，关押
  - con·strain => con- 一起 + strain 拉 → 拉到一起 → 限制，强制。

13. **bind**
  - vt. 绑，约束，装订，包扎，使结合
  - vi. 凝固，有约束力

14. **finite**
  - a. 有限的，有穷的，限定的
  - n. 有限物
  - fin·ite => fin- 终结，边界 + -ite 表形容词，引申义有边界的，有限制的。

15. **promise**
  - n. 谎言，约定的事情，有指望
  - vt. 允诺，约定，预示
  - vi. 允诺，有前途，有指望
  - pro·mis·e => pro- 前面 + mis- 送 + -e → 在做事前送出的话 → 允诺。

16. **promising**
  - a. 有希望的，前途有希望的
  - promise【承诺，保证】+ -ing 表形容词。

17. **guarantee**
  - n. 担保，抵押品，保证书
  - vt. 保证，担保
  - guar·ant·ee => guard【守卫】+ ant + ee 表人。

18. **commit**
  - v. 犯（罪或错等），自杀，承诺，调拨（钱、资源），（就某事）表态，送交（到精神病院、监狱等），记（在纸上，记忆中）
  - com·mit => com- 共同 + mit- 送 → 共同送 → 委任。

19. **commitment**
  - n. 承诺，保证，现身，奉献，已承诺（或同意的事），花费，使用
  - com·mit·ment => commit【委托】+ -ment 表名词。

20. **pledge**
  - n. 诺言，保证，抵押，抵押物
  - v. 正式承诺，使发誓，抵押，典当，承诺拨款
  - 来自古法语 plege 保证，来自 Proto-Germanic plego 责任，担保。


### 赏析一句英语句子

But embarrassing scandals and the popularity of the republican left in the recent Euro-elections have forced him to eat his words and stand down.

但令人尴尬的丑闻和左翼共和党近期在欧洲选举中的大受欢迎迫使他不得不食言并退位。

#### 句子主干

- But embarrassing scandals and the popularity ... have forced him （主+谓+宾+宾补）
- **him**
  - to eat his words and stand down.
  - 动词不定式短语作 him 的补足语

#### 一级修饰

- **the popularity**
  - of the republican left in the recent Euro-elections
  - 介词短语作后置定语，修饰 the popularity

#### 词汇注释

- `embarrassing` a. 使人尴尬的，令人为难的
- `scandal` n. 丑闻，流言蜚语
- `popularity` n. 受欢迎，普及，声望
- `republican` n. 共和党党员
- `stand down` （从要职上）退下，离职，下台

## Get
### 使用 Neovim 的收获

1. `i_CTRL-F`

```text
当键前面有"!"时，Vim 不会插入键，而是重新缩进当前行。
这允许您定义用于重新缩进当前行的命令键。
CTRL-F 是此操作的默认键。如果为此定义了 CTRL-I，请小心，因为 CTRL-I 是<Tab>的 ASCII 代码。

当"*"位于键之前时，Vim 将在插入键之前重新缩进该行。
如果"cinkeys"包含"*<Return>"，Vim 会在打开新行之前重新缩进当前行。

当键前面有一个零（但出现在"!"或"*"之后）时，仅当键是您在该行中键入的第一个字符时，Vim 才会重新缩进该行。
当在"="之前使用时，Vim 只会在单词前只有空格的情况下重新缩进该行。

当键前面既没有"!"也不在"*"时，Vim 会在您键入键后重新缩进该行。因此，';'设置包含';'的行的缩进。
```

2. `:help key-notation` 看一些标记（`CR`, `NL`, `BS`, ...）的含义。

3. 回车与换行的区别

```text
符号 ASCII码 意义
\n 10 换行NL
\r 13 回车CR

回车 \r 本义是光标重新回到本行开头，r 的英文 return，控制字符可以写成 CR，即 Carriage Return。
换行 \n 本义是光标往下一行（不一定到下一行行首），n 的英文 newline，控制字符可以写成 LF，即 Line Feed。
在不同的操作系统这几个字符表现不同，比如在 WIN 系统下，这两个字符就是表现的本义。
在 UNIX 类系统，换行 \n 就表现为光标下一行并回到行首。
在 MAC 上，\r 就表现为回到本行开头并往下一行，至于 Enter 键的定义是与操作系统有关的。
通常用的 Enter 是两个加起来。

在计算机还没有出现之前，有一种叫做电传打字机（Teletype Model 33）的玩意，每秒钟可以打10个字符。
但是它有一个问题，就是打完一行换行的时候，要用去0.2秒，正好可以打两个字符。
要是在这0.2秒里面，又有新的字符传过来，那么这个字符将丢失。
于是，研制人员想了个办法解决这个问题，就是在每行后面加两个表示结束的字符。
一个叫做“回车”，告诉打字机把打印头定位在左边界；另一个叫做“换行”，告诉打字机把纸向下移一行。
这就是“换行”和“回车”的来历，从它们的英语名字上也可以看出一二。
后来，计算机发明了，这两个概念也就被般到了计算机上。
那时，存储器很贵，一些科学家认为在每行结尾加两个字符太浪费了，加一个就可以。于是，就出现了分歧。

/*======================================*/
\n: UNIX 系统行末结束符
\n\r: window 系统行末结束符
\r: MAC OS 系统行末结束符
/*======================================*/
一个直接后果是，Unix/Mac 系统下的文件在 Windows 里打开的话，所有文字会变成一行；
而 Windows 里的文件在 Unix/Mac 下打开的话，在每行的结尾可能会多出一个 ^M 符号。

C++ 语言编程时（windows系统）\r 就是 return 回到本行行首，这就会把这一行以前的输出覆盖掉。
如：
int main() {
cout << "hahaha" << "\r" << "xixi";
}
最后只显示 xixi 而 hahaha 被覆盖了
\n 是回车+换行，把光标先移到行首，然后换到下一行，也就是下一行的行首。
int main() {
cout << "hahaha" << "\n" << "xixi";
}
则显示
hahaha
xixi
```


## Summary

昨晚趁着年货节买了几个米家的家电，今天上午就到了。在京东买东西最好的一点就是，买的东西能最快到手里，这点淘宝是没法比的。
今天就用这些新厨具来做饭，换了新电饭锅、电磁炉煮饭速度快了不少，之前一直是用电热炉，烧饭菜比较慢。

今天捣鼓优化了 Neovim 的配置，也没花太多时间学其他的内容。
