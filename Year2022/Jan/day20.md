# 2022年1月20日，星期四
## Todo List

- [x] 复习昨天的单词
- [x] [背诵 20 个新单词](#背诵-20-个新单词)
- [x] [赏析一句英语句子](#赏析一句英语句子)
- [x] 看曾仕强教授讲易经的智慧2集
  - [x] 003 天人合德
  - [x] 004 以人为本
- [x] 弹 1 小时 Ukulele
--------
- [x] [安装模糊查找工具 fzf](#安装模糊查找工具-fzf)
- [x] 给 geonv 增加 fzf.vim 插件


### 背诵 20 个新单词

1. **integrated**
  - a. 综合的，完整的，互相协调的
  - in·tegr·at·ed => integrate【完整】+ -ed 形容词后缀 → 完整的。
  - integr- = whole 表示“完整”，由前缀 in-（否定）+ tag-（接触）组成。

2. **recruit**
  - n. 新年，新手，新会员，补给品
  - vt. 恢复，补充，充实，征募
  - vi. 征募新兵，复原，得到补充
  - re·cruit => re- 再 + cruit- 生长 → 恢复。

3. **assimilation**
  - n. 同化，同化作用，吸收
  - as·simil·at·ion => assimilate【vt. 使同化】+ -ion 表名词，是单词 assimilate 派生的名词。

4. **assimilate**
  - vt. 使同化，吸收，使相似，把……比作
  - vi. 被吸收，被同化
  - as·simil·ate => as- 强调 + simil- 相同 + -ate 表动词 → 成为相同 → 同化。

5. **enroll**
  - vt. 登记，使加入
  - vi. 参军，注册
  - en·roll => en- 进入，使 + roll【卷，册】。
  - en- 入、内、在……之内，使……，rol- 圆，环，滚动

6. **enrollment**
  - n. 登记，注册，入伍
  - en·roll·ment => enroll【登记】 + -ment 表名词。

7. **inject**
  - vt. 注射，注入，使入轨
  - in·ject => in- 进 + ject- 扔 → 扔进去 → 注射。

8. **enlist**
  - vt. 征募，参与，谋取
  - vi. 从军，应募，赞助
  - en·list => en- 进入，使 + list【清单，列表】。

9. **imitate**
  - vt. 模仿，效法，冒充，仿造
  - imit·ate => imit- 像 + -ate 表动词 → 做得相像 → 模仿。

10. **imitation**
  - n. 模仿，效法，冒充，赝品
  - imit·at·ion => imitate【模仿】+ -ion 表名词。引申词义模仿品，仿制品，是单词 imitate 派生的名词。

11. **duplication**
  - n. 副本，复制
  - du·plic·at·ion => duplicate【副本】+ -ion 表名词，是单词 duplicate 派生的名词。

12. **clone**
  - n. 靠营养生殖而由母体分离繁殖的植物，无性繁殖，无性系，克隆
  - vt. 无性繁殖，克隆

13. **attack**
  - n. 攻击，抨击
  - vt. 攻击，抨击，动手干
  - vi. 攻击
  - at·tack => at- 强调 + tack- = tach- = nail 钉子 → 眼中钉 → 攻击，抨击。

14. **predator**
  - n. 食肉动物，掠夺者
  - pred·ator => pred- 掠夺，掠食 + -ator 表名词，做事的人或物。

15. **plague**
  - n. 瘟疫，天罚，麻烦，灾祸
  - vt. 折磨，使苦恼，使得灾祸
  - plag·ue => plag- 击打 + -ue。

16. **hack**
  - n. 劈，砍，砍痕，出租车，干咳，晒架，鹤嘴锄
  - vt. 劈，砍，出租，用旧
  - vi. 劈，砍，干咳，驾驶出租车
  - a. 出租的

17. **backward**
  - a. 向后的，相反的
  - ad. 向后地，相反地
  - back·ward => back【后面】+ -ward 向... → 向后的。

18. **fade**
  - vi. 褪色，消失，凋谢
  - vt. 使褪色
  - n. 淡入，淡出
  - a. 平淡的

19. **recession**
  - n. 后退，凹处，衰退，归还
  - re·cess·ion => recess【休息】+ -ion 名词后缀 → 走回去 → 撤退，是单词 recess 派生的名词。

20. **downgrade**
  - vt. 使降低，使降级
  - down·grad·e => down【向下】+ grad- 步，级 → 降级。


### 赏析一句英语句子

The most successful monarchies strive to abandon or hide their old aristocratic ways.

最成功的君主们努力抛弃或隐藏他们先前的贵族生活方式。

#### 句子主干

- The most successful monarchies strive to abandon （主+谓+宾）
- **to abandon**
  - or (to) hide their old aristocratic ways.
  - or 连接的并列宾语

#### 词汇注释

- `strive` vi. 努力，奋斗，抗争
- `aristocratic` a. 贵族的，贵族气派的，高贵的


### 安装模糊查找工具 fzf

安装脚本将为 `bash`、`zsh` 和 `fish` 设置以下键绑定。

- `CTRL-T`
  - 将选定的文件和目录粘贴到命令行上
  - 设置 `FZF_CTRL_T_COMMAND` 以覆盖默认命令
  - 设置 `FZF_CTRL_T_OPTS` 以传递其他选项

- `CTRL-R`
  - 将历史记录中的选定命令粘贴到命令行
  - 如果您想按时间顺序查看命令，请再次按 `CTRL-R`，按相关性切换排序
  - 设置 `FZF_CTRL_R_OPTS` 以传递其他选项

- `ALT-C`
  - `cd` 进入所选目录
  - 设置 `FZF_ALT_C_COMMAND` 以覆盖默认命令
  - 设置 `FZF_ALT_C_OPTS` 以传递其他选项

如果使用的是 `tmux 会话`，可以通过设置 `FZF_TMUX_OPTS`（例如 `-d 40%`）在 tmux 拆分窗格或 tmux 弹出窗口中启动 fzf。
有关可用的选项，请参阅 `fzf-tmux--help`。

更多提示可以在[维基](https://github.com/junegunn/fzf/wiki/Configuring-shell-key-bindings)页面上找到。

## Summary

### 我的音乐梦

刚上大学的时候我买了一把尤克里里，其实那是我买的第二把尤克里里。

我为什么会买尤克里里呢？故事得从我的高中生活讲起……

那个时候可能是班级活动月（时间过去几年了我也不是很确定），我的班主任飞哥让班干们组织一场活动，时间安排在开班会的时间段。
班主任也不知道弄什么活动，就全权交给了班干们负责，在他们集思广益之下，他们跟几个对音乐很感兴趣的同学就敲定办一场班级音乐会。

一个星期后的班会，那个晚上，那场给我留下深刻记忆的班级音乐会如期而至。
我们班里那几个热爱音乐的同学：伟哥、大表姐、锌欧、幺哥……组成的临时乐团给我们班带来了很多个精彩的歌唱节目、弹唱节目。
那时的我也沉醉在那场美妙的晚会里，被他们的歌声，他们的弹奏深深打动着，突然间觉得自己心里的紧张压抑荡然无存。
那时候我才发觉普通的一把尤克里里、一把吉他、一把贝斯在现场演绎出来的一首歌跟在手机里听的感觉很不一样。
也就是那个时候我萌生出了一个想法，我也想买一把吉他或是一把尤克里里。
虽然时间过去很多年了，我也不记得那个晚会表演了多少节目，但是有一首歌让我至今也没有忘记，也是因为那首歌让我有了买吉他或尤克里里的冲动。
那首歌是梁静茹的《小手拉大手》，是宫崎骏的动画电影《猫的报恩》的主题曲《幻化成风》的中文版。
我当时非常喜欢这部电影，也曾被这部电影感动过很多次，这部电影陪伴我走过了我那个不成熟的青春。

之后我求教了我那几个的同学，我也想向他们学习乐器。那时后我对乐器方面一点了解都没有，也在纠结着是买吉他还是尤克里里。
后来，在大表姐的建议下，我买了尤克里里。尤克里里相比吉他更简单易学，也更适合小白的我。

我买了第一把尤克里里（20160521），应该是两百多块钱吧。当时拿到手后，我尝试照着手机里的教学视频学弹奏。
遗憾的是，我买来没多久，它就被迫一直吃灰了。当时高中生活异常紧张，每天除了吃饭睡觉就是学习了。
每天三点一线的生活让我几乎没有时间去玩尤克里里，只有偶尔晚上洗完澡后弹个十几二十分钟。
索性就把它搁置了，我也奋力进入高考这批大军里边，好好准备高考。

高中的生活稍纵即逝，结束了高考，我以为可以好好练习尤克里里了，但是好想又有意无意地把它再次搁置。
刚开始玩了一点，后来忙着看志愿、填志愿花去了很多时间，还有家里各种杂事要做。
练习尤克里里的时间被日常琐事占据了。填完志愿后，我的伯父生病了，那时后在医院了照看了他一段时间。
后面，受到自媒体影响，我又尝试去写自媒体。高考后那3个月的暑假，在我东捣鼓西捣鼓中不知不觉就结束了……

上大学后，我遇到了一个人，一个几乎影响了我整个大学生活的人。因为她，我内心在不经意间燃起了音乐梦想。
或许也是因为一时起兴吧，我决定买一把新的尤克里里，好好学一学，我希望有机会能为她弹唱歌曲。
于是，我买了第二把尤克里里，KAKA 的 KUC-MAD，一千块，还分了期。对当时的我来说，那是比较贵的一把琴。
当时想，买一把好一点的琴，或许能激励自己更努力地练习吧。

热情好像很快就退散了，弹了一段时间，也或许当时自己把自己很多的业余时间贡献到了其他地方，结果断断续续地学。
其实最后大学毕业了，我感觉自己也没学好尤克里里。不过还好，至少让我发现自己对音乐的深爱。
大学里还跟我的音乐启蒙老师学了一个学期的竹笛，后面又选修了一门键盘课。

也许是因为这些断断续续的影响，让我感受到音乐的美好，让我懂得如何去更好地欣赏音乐，音乐已然成为我人生中不可或缺的一样东西。

我想，既然我开始写生活日记，开始做 ToDo，那么我也借此机会，完成最初的梦想。
从今天开始，我每天坚持练习1个小时尤克里里，把那些本该在过去学习的东西再慢慢捡起来。

### 今日总结

今天有些许收获吧，但也花了很多时间在刷 B 站视频和直播上，看完后我也思考了一些我日后的规划，但又觉得自己的想法或许不太成熟。
