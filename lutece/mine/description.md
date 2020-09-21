
# Content

在电子科大沙河校区的学生内网“风中论坛”中，有一种名叫“踩地雷”的游戏，游戏规则如下：
* 玩家在$0$到$9$中任意选择一个数字，并押上一定的赌金。
* 地雷号码由每日发贴排行榜产生，将上榜的$N$名会员的当日发帖量的最后一位加起来，得到的数字的十位和个位就是地雷号码，称为“大雷”，它们加起来余$10$也是地雷号码，称为“小雷”。
* 如果两个大雷不相同，则选择的数字不是这$3$个雷号之一的玩家净赢$1$倍赌金。
* 如果两个大雷不相同，而且其中没有$0$，则选择的数字是大雷的玩家净输$3$倍赌金，选择的数字是小雷的玩家净输$2$倍赌金。
* 如果两个大雷不相同，而且其中有$0$，则选择的数字是大雷（包括$0$）的玩家净输$4$倍赌金。
* 如果两个大雷相同，则选择的数字不是大雷或者小雷的玩家净输$1$倍赌金。
* 如果两个大雷相同，而且不是$0$，则选择的数字是大雷的玩家净赢$3$倍赌金，选择的数字是小雷的玩家净赢$2$倍赌金。
* 如果两个大雷相同，而且是$0$，则选择的数字是$0$的玩家净赢$4$倍赌金。

现在假设所有上榜的会员当日发帖量的最后一位是$0$到$9$中每个数字的概率都是$\frac{1}{10}$，给定$N$，求玩家压在每个数字上期望上能得到多少倍赌金的净收益。

# Standard Input

输入包含多组数据。每组数据只有$1$个整数$N$($1\leq N\leq 1000$)，$N=0$表示输入结束。

# Standard Output

对每组数据，输出$1$行，包含$10$个数字，分别代表玩家压$0$到$9$分别能得到多少倍赌金的净收益。输出保留到$2$位小数。

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1
0</td><td>-3.20 0.30 0.30 0.30 0.30 0.30 0.30 0.30 0.30 0.30</td></tr></table>


# Constraints



# Note



# Source

