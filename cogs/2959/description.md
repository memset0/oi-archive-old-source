# 题目描述


<img src="http://172.30.1.3/kindeditor/plugins/emoticons/images/0.gif" alt="" border="0"/> 
<h3>
【题目描述】
</h3>
<p>
r神在和小b比赛玩一个名为“消消乐”的游戏，在一个 $n\times m$ 的棋盘上，一些棋子分布在格点上，游戏玩家有一个名为超蓝光波的武器，可以消除一行或者一列的所有棋子，使用超蓝光波需要耗费一点能量，消除完所有的棋子之后，花费能量越少得分越高。 rqy神为了超过排名第一的小b，夺得荣誉称号“天下第一”，他需要寻求你的帮助，他希望知道最少需要使用多少次“超蓝光波”，以及在哪行、哪列使用。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个正整数 $n(n\le 2000)$，$m(m\le 2000)$；
</p>
<p>
接下来 $n$ 行，每行 $m$ 个字符，表示棋盘，其中“.”表示该处没有棋子，“*”表示该处有棋子，棋子个数 $\le 100000$。
</p>
<h3>
【输出格式】
</h3>
<p>
第一行输出一个正整数，表示最少需要使用的“超蓝光波”次数。
</p>
<p>
第二行 $N+1$ 个正整数，第一个数为 $N$，表示需要消掉的行数，从小到大输出每个需要消除的行号。
</p>
<p>
第三行 $M+1$ 个正整数，第一个数为 $M$，表示需要消掉的列数，从小到大输出每个需要消除的列号。
</p>
<p>
如果有多种情况，任意输出一种即可。
</p>
<h3>
【样例输入】
</h3>
<pre>3 4
.*..
**.*
..*.</pre>
<h3>
【样例输出】
</h3>
<pre>3
3 1 2 3
0</pre>
<h3>
【提示】
</h3>
<p>
手动链表：下一题 <a href="./problem.php?pid=2952" style="text-decoration:none;">[SYOI 2018] 国政议事</a> 
</p>
<h3>
【来源】
</h3>
<p>
SYOI 2018
</p>