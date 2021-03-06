
# 题目描述

> `UNSC`一些最精良的舰队赫然在目：‘巴士拉号’、‘汉尼拔号’、以及舰队的骄傲——超级航空母舰‘特拉法加号’。在那些飞船中没有人类的信号发出来，也感觉不到任何活跃的电磁场”    ——《光环：初次反击》

致远星战况如何，是网络上非常流行的一句话，意同“日本投降矣”。但在《光环》中，这句话绝不仅仅是一句玩笑。它背后是星盟（$The Covernant$）以技术碾压对人类远、近地殖民地以及`UNSC`舰队的血洗。致远星作为人类除了母星以外最大的军事堡垒，它的玻璃化预示着地球保卫战的提前开启，而由致远星逃出的舰队大部分用于充实家园舰队的防御力量，以抵抗星盟忏悔先知亲帅的星盟舰队。

致远星的幸存者们历尽千辛万苦合流回到了地球，然而因为舰船的受损情况和当前性能不同，家园舰队的防卫力量需要的岗位也不同，如何分配这些战舰成为了难题。例如卡戎级轻型护卫舰和巴黎级重型护卫舰，利戟级驱逐舰和勤勉级驱逐舰能承担的任务都完全不同。

“然而这和我ZSGW红太阳`xlb`有什么关系呢”，被迫听完`Melantha`一顿絮叨的`xlb`如此想到。看见面前手舞足蹈的菜鸡`Melantha`，他决定用五分钟写出一个程序按照书中所说来分配这些战舰（NP完全问题被解决了！）。`Melantha`自然被惊呆了，`xlb`不无得意的说：“看你这么菜，给你降低一点难度吧，只让你考虑三种战舰的分配”。菜鸡也还有张嘴是不是，你决定码出这个程序来证明你和`xlb`之间的差距并不是云泥之异。
\
\
\
\
书中说，一共有$n$个岗位，每个岗位都对战舰有所需求，将通过一个字符串$S$表述。假设卡戎级为$X$型，伟岸级为$Y$型，巴黎级为$Z$型，每个字母表达一个岗位的需求：\
$A$种为“地面支援任务”，需要一艘$X$或$Y$型\
$B$种为“行星防御任务”，需要一艘$X$或$Z$型\
$C$种为“舰队护航任务”，需要一艘$Y$或$Z$型

同时，因为星盟舰队装备的能量投影仪对这些战舰的钛-A装甲板几乎是一击必杀，所以每艘战舰的位置都必须被巧妙安排才能应付某个方向的战略需求。假设在A处有X型战舰布防，则可能B处布置Y型战舰就会对战局造成干扰，反之，C处和D处可能必须有一艘Z型战舰布防。这些将由一个六元组给出$(x,xp,xu,y,yp,yu)$，其中$xu$或$yu$等于1时为真，0时为假。分别表示$x$位置布置$xp$战舰为$xu$或$y$位置布置$yp$战舰为$yu$。

然而从致远星防御舰队“埃普西隆-艾瑞达尼”波江座舰队十不存一，所剩无几的战舰并不能保证所有岗位的填补，输出是否能满足要求。如果能，第一行输出 "Noob" ，第二行输出能填补所有岗位需求的方案（如有多种，输出其中之一即可）。倘若所有安排方法均不能填补所有空缺，输出"Winter_Contingency"（不包括引号）

# 输入格式

第一行一个数字$n$\
第二行为字符串$S$，代表需求，同“题目描述”中说的一样\
第三行为一个数字$q$，代表UNSC海军司令部的要求数\
第$4$~$q+3$行为命令六元组$(x,xp,xu,y,yp,yu)$

# 输出格式

第一行输出`Noob`或`Winter_Contingency`。\
如果可行，第二行输出一串以`X`、`Y`、`Z`组成的字符串$T$，第$i$个字符表示在第$i$个需求位置布置$T[i]$种战舰

# 样例

输入#1
```
5
ACCAC
5
2 Z 1 3 Y 0
4 Y 0 1 X 0
5 Y 1 3 Y 0
1 X 0 1 Y 1
3 Z 0 2 Y 0
```
输出#1
```
Noob
YZZYZ
```
输入#2
```
10
ABACABCBAC
10
3 X 1 2 X 0
10 Y 0 9 X 1
2 X 1 4 Y 1
10 Z 1 2 X 0
2 X 1 2 Z 1
10 Z 1 9 X 0
2 X 1 4 Y 1
10 Y 0 9 Y 1
1 Y 1 8 Z 1
8 X 0 2 Z 1
```
输出#2
```
Noob
YZYYYZZZYZ
```

# 数据范围与提示

#基本约定：\
Ⅰ.数据保证提出的q条要求全部合法，即要求A处必须（不）为X型时，X属于该类型任务的需求之一\
Ⅱ.本题已开启Special Judge，答案仅需输出一组可行解即可

#数据范围：\
![](/source/guoj/1317/img/aHR0cHM6Ly9zMi5heDF4LmNvbS8yMDE5LzA4LzE5L20zNnZkQS5wbmc=.png)\

#样例解释：\
-> #1：\
2 Z 1 3 Y 0的意思是，输出的字符串一定要满足一下两个条件之一\
①第2个位置为Z\
②第3个位置不为Y\
4 Y 0 1 X 0的意思是，输出的字符串一定要满足一下两个条件之一\
①第4个位置为Z\
②第1个位置不为Y\
5 Y 1 3 Y 0的意思是，输出的字符串一定要满足一下两个条件之一\
①第5个位置为Y\
②第3个位置不为Y\
1 X 0 1 Y 1的意思是，输出的字符串一定要满足一下两个条件之一\
①第1个位置不为X\
②第1个位置为Y\
3 Z 0 2 Y 0的意思是，输出的字符串一定要满足一下两个条件之一\
①第3个位置不为Z\
②第2个位置不为Y\
YZZYZ明显满足以上所有条件，故作为可行解输出

#写在结尾的话：\
在这样一场毒瘤的考试中\
输出Winter Contingency就可以得分，无疑是出题人无私的馈赠

~~可惜由于赛制原因不能了（by某GuOJ管理员：Yuki）~~

大段精心构造的题面，没有涵盖题目的半毛钱内容\
你可以利用这道题，对你是否与p*h的实力有云泥之异进行初步检查\
提前告知了的模型，较低的难度和不大的代码量，能帮助你把分数收入囊中\
出题人相信，这个美妙的题目，可以给已经走上AK之路上的你，提供一个有力的援助

