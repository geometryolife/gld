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
2. **contain**
3. **container**
4. **constitute**
5. **constituent**
6. **consist**
7. **limited**
8. **restriction**
9. **restrict**
10. **restrictive**
11. **constraint**
12. **constrain**
13. **bind**
14. **finite**
15. **promise**
16. **promising**
17. **guarantee**
18. **commit**
19. **commitment**
20. **pledge**


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
