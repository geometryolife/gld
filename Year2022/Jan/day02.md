# 2022年1月2日，星期日
## Todo List

- [x] 复习昨天的单词
- [x] [背诵 20 个新单词](#背诵-20-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
--------
- [ ] 给 Neovim 配置增加一个运行函数
- [ ] 学习如何用 Lua 处理日期和时间
- [ ] 复习二分查找算法
- [x] 给 blink 提关于中文输入法的 issue
  - [x] 中文输入法第一次击键无法输入中文
  - [x] 中文输入法无法输入正确的双引号
- [ ] 交医保
--------
- [x] 更新知乎的回答贴
- [x] 记录收获
- [x] 回顾前面所学的单词

### 背诵 20 个新单词

1. **manufacturer**
  - n. 制造业者，厂商
  - manu·fact·ur·er => manufacture【制造】+ -er 表人，是单词 manufacture 派生的动作执行者（施动）名词。

2. **sense**
  - n. 感应，感觉，感官，意识，观念，情理，知觉，理智
  - vt. 感觉，察觉，检测
  - sens·e => sens- = feel，表示“感觉”。源自拉丁语 sentire "to feel"。

3. **sensory**
  - adj. 知觉的，感觉的，传递感觉的
  - sens.ory => sens- 感觉 + -ory 表形容词。

4. **perceive**
  - vt. 感觉，认知，理解
  - per·ceiv·e => per- 完全的 + ceive = cip- 抓住，理解。

5. **conscious**
  - adj. 有意识的，知觉的，觉察的
  - con·sci·ous => con- 强调 + sci- 知道 + -ous 形容词后缀 → 知道的 → 有意识的。

6. **consciousness**
  - n. 意识，知觉，自觉
  - con·sci·ous·ness => conscious【有意识的】+ -ness 表名词，是单词 conscious 派生的名词。

7. **subconscious**
  - n. 潜在意识，下意识
  - adj. 下意识的，潜意识的
  - sub·con·sci·ous => sub- 下面 + conscious【有意识的】→ 在意识之下 → 潜意识的。

8. **detect**
  - vt. 发现，察觉，探测
  - de·tect => de- 不，非，使相反 + tect- 覆盖，即揭开覆盖，查明。

9. **detector**
  - n. 发现者，检验器，检波器
  - de·tect·or => detect【发现，察觉】+ -or 表人，是单词 detect 派生的动作执行者（施动）名词。

10. **cognitive**
  - adj. 认知的，认识的
  - co·gn·itive => co- 共同 + gn- 知道 + -itive 表形容词。

11. **comprehension**
  - n. 理解，包含
  - com·prehens·ion => com- 全部 + prehens- 抓住 + -ion 表名词，是单词 comprehend 派生的名词。

12. **predict**
  - v. 预知，预言，预报
  - pre·dict => pre- 预先 + dict- 说 → 预言。

13. **prediction**
  - n. 预言，预报
  - pre·dict·ion => predict【预言】+ -ion 名词后缀，是单词 predict 派生的名词。

14. **unpredictability**
  - n. 不可预测性，不可预知性
  - un·pre·dict·ab·ility => un- 不，非 + predict【预知】+ -ability 表名词。

15. **forcast**
  - n. 预想，预测，预报
  - v. 预想，预测，预报
  - fore·cast => fore- 在前 + cast【扔】→ 预先扔下 → 预料。

16. **foreseeable**
  - n. 在可以预见的未来
  - adj. 可预见到的，可预知的，能预测的
  - fore·see·able => foresee【预见，预知】+ -able 表形容词。

17. **create**
  - vt. 创造，建造，引起，任命
  - cre·ate => cre- 增长 + -ate 表动词 → 增长 → 创造。

18. **innovation**
  - n. 改革，创新
  - in·nov·ation => innovate【v. 改革，创新】+ -ion 表名词，是单词 innovate 派生的名词。

19. **innovative**
  - adj. 革新的，创新的，富有革新精神的
  - in·nov·at·ive => in- 进入 + nov- 新 + -ative 表形容词，是单词 innovate 派生的形容词。

20. **formulate**
  - vt. 规划，制定，构想，准备，确切表达，认真阐述
  - form·ul·ate => formula【公式】+ -ate 表动词 → 成公式。


### 赏析一句英语句子

The study also found that the genes for smell were something shared in friends but not genes for immunity.

该研究还发现，朋友之间有着相似的嗅觉基因，而不具有相似的免疫力基因。

#### 句子主干

- The study also found （主+谓+宾从）
- that the genes for smell were something
  - that 引导的宾语从句，作 found 的宾语

#### 一级修饰

- **that**
  - but not genes for immunity.
  - 补充说明
- **something**
  - shared in friends
  - 过去分词短语作后置定语，修饰 something

#### 词汇注释

- `smell` n. 嗅觉，气味
- `immunity` n. 免疫力，豁免，免除

### 中文输入法第一次击键无法输入中文

[GitHub issue 地址](https://github.com/blinksh/blink/issues/1350)

### 中文输入法无法输入正确的双引号

[GitHub issue 地址](https://github.com/blinksh/blink/issues/1349)


## Get
### 使用 Git 的收获

#### Git 克隆项目（仓库）到本地后拉取其他远程分支

1. 从 GitHub 克隆远程仓库

```bash
# 克隆 gld 仓库到本地
git clone git@github.com:geometryolife/gld.git

# 进入项目的根目录
cd gld

# 默认克隆项目的主分支，其他分支并没有被克隆到本地
git branch -a

=== Output ===
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/img
  remotes/origin/main
```

2. 拉取其他远程分支到本地

```shell
# 创建本地分支 img，并与远程的 origin/img 分支同步
# git checkout -b 本地分支名 远程分支名
git checkout -b img origin/img

=== Output ===
Branch 'img' set up to track remote branch 'img' from 'origin'.
Switched to a new branch 'img'

# 再次查看，img 分支已经被拉取下来了，同时也切换到了 img 分支
git branch -a

=== Output ===
* img
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/img
  remotes/origin/main
```

#### 在 Git 中创建一个空分支

1. 应用场景介绍

有时候我们需要在 Git 项目仓库里面创建一个空分支，该分支不继承任何提交，没有父节点，是一个干净的分支。
我们可以在这个分支里专门存放图片、文档或其他与代码无关的资料，目前 GitHub Pages 的项目主页默认会使用空分支创建。

例如：我现在想在`gld`仓库里创建一个`img`分支专门用来存放图片，而且我不想让这个存放图片的分支包含任何历史提交。

2. 创建孤立（空）分支

使用`git checkout -b`命令创建的分支是有父节点的，这意味着新的分支包含了历史提交，所以我们需要使用`git checkout --orphan`命令，创建孤立分支。

```shell
git checkout --orphan img

=== Output ===
Switched to a new branch 'img'
```

3. 清除内容

使用`git checkout --orphan 分支名`创建的分支会把原分支的内容拷贝过来，因为要创建空分支，所以需要使用`git rm -rf .`来清除拷贝的内容。

```shell
# 查看状态可以发现，原分支的文件被复制并添加了
git status

=== Output ===
On branch img
No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   LICENSE
        new file:   README.md
        new file:   Year2021/Dec/day27.md
        new file:   Year2021/Dec/day28.md
        new file:   Year2021/Dec/day29.md
        new file:   Year2021/Dec/day30.md
        new file:   Year2021/Dec/day31.md
        new file:   Year2022/day01.md
        new file:   Year2022/day02.md

# 删除所有文件
git rm -rf .

=== Output ===
rm 'LICENSE'
rm 'README.md'
rm 'Year2021/Dec/day27.md'
rm 'Year2021/Dec/day28.md'
rm 'Year2021/Dec/day29.md'
rm 'Year2021/Dec/day30.md'
rm 'Year2021/Dec/day31.md'
rm 'Year2022/day01.md'
rm 'Year2022/day02.md'

# 再次查看
git status

=== Output ===
On branch img
No commits yet
nothing to commit (create/copy files and use "git add" to track)
```

4. 初始化空分支

如果空分支没有任何文件被提交的话，使用`git branch`是看不到空分支的，我创建一个`README.md`文件来描述这个分支。
提交后，再使用`git branch`就能看到我创建的空分支`img`了。

使用branch来查看分支是否创建成功

```shell
# 未提交孤立分支前
git branch -a

=== Output ===
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main

# 添加文件（README.md）到暂存区
git add .
# 提交
git commit -m "Initial commit"
# 再次查看
git branch -a

=== Output ===
* img
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
```

5. 提交到远程分支

```shell
git push origin img

=== Output ===
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 244 bytes | 244.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'img' on GitHub by visiting:
remote:      https://github.com/geometryolife/gld/pull/new/img
remote:
To github.com:geometryolife/gld.git
 * [new branch]      img -> img

# 此时可以看到远程分支了，也可以在 GitHub 上查看
git branch -a

=== Output ===
* img
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/img
  remotes/origin/main
```


6. `git ckeckout --orphan` 帮助信息

> 从`<start_point>`开始创建一个名为`<new_branch>`的新孤儿分支，并切换到它。在这个新分支上的第一个提交将没有父，这将是与所有其他分支和提交完全脱节的新历史的根源。
> 
> 索引和工作树的调整就像您之前运行`git checkout <start_point>`一样。这允许您通过轻松运行`git commit -a`进行根提交来启动新的历史记录，记录一组类似于`<start_point>`的路径。
> 
> 当您想在不暴露其完整历史记录的情况下从提交发布树时，这可能会很有用。您可能希望这样做是为了发布当前树为“干净”但其完整历史记录包含专有或其他受困代码位的项目的开源分支。
> 
> 如果您想开始一个断开连接的历史记录，记录一组与`<start_point>`完全不同的路径，那么您应该在创建孤儿分支后立即从工作树的顶层运行`git rm -rf .`来清除索引和工作树。之后，您将准备好准备新文件，重新填充工作树，从其他地方复制它们，提取`tarball`等。


## Others

- `断言`：断言（assertion）是一种在程序中的一阶逻辑（如：一个结果为真或假的逻辑判断式），目的为了表示与验证软件开发者预期的结果——当程序执行到断言的位置时，对应的断言应该为真。若断言不为真时，程序会中止执行，并给出错误信息。

## Summary

今天的收获蛮多的，明天坚持早起，加油！
