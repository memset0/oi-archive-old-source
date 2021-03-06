
# Content

在非常流行的`DOTA`游戏中，补兵是非常重要的一种技术统计。如果一个单位被对方的多个单位攻击至死，则对该单位造成最后一次（致命的）伤害的攻击者将会获得更多的奖励（金钱和经验），这名攻击者被记录一次补兵。

现在假设有多个人攻击对方的一个单位，而你是其中的一个，你并不想在前面出手攻击，而只想打一次就直接将对方打死，完成一次补兵。假设其他人每次攻击的伤害和每两次攻击之间的间隔都是固定的，而你的攻击伤害也是固定的。输入将给出每个人两次攻击之间的间隔时间，并假设每个人第一次攻击的时刻值就是他的两次攻击之间的时间间隔值。例如，一个人攻击间隔为$2$，则他会在时刻$2$、$4$、$6$、$8$……进行攻击。

时间以整数计算。

如果多个人同时攻击导致对方死亡，攻击伤害最大的那个被记录一次补兵。如果你是攻击伤害最大的之一（还有其他和你攻击伤害一样的，但没有更大的），则你被记录一次补兵。

一个单位血量小于等于$0$就被判为死亡。

你的任务是求出合适的攻击时间段，使得这次补兵能够完成。这个时间段一定是一个区间，你需要输出的是它的两个端点。

# Standard Input

输入包含多组数据。每组数据第一行是一个整数$N$($2 \leq N \leq 1000$)，表示攻击对方某个单位的人数。$N=0$表示输入结束。接下来有$N-1$行，每行两个整数，分别表示每个人每次攻击的伤害$A$($1\leq A \leq 10$)，以及每两次攻击之间的间隔$T$($1 \leq T \leq 100$)。最后有一行包含两个整数，分别表示你的攻击伤害$P$($1 \leq P \leq 100000$)以及对方单位的血量$H$($P < H \leq 1000000$)。

# Standard Output

对每组数据，输出一行，如果不能完成补兵，输出`Impossible`，否则输出最早可以完成补兵的时间和最晚可以完成补兵的时间，用空格间隔。

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
<tr><td>2
2 2
3 10
2
20 2
3 10
0</td><td>8 10
Impossible</td></tr></table>


# Constraints



# Note

输入数据较多，尽量用`scanf`和`printf`代替`cin`和`cout`。

# Source


