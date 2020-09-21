# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
小涵向小宇推荐了一款小游戏。
</p>
<p>
游戏是这样的，在一个n*n的地图中，有若干个格子上有障碍物。你需要雇佣搬运工，将这些障碍物全部清除。不过每次操作你只能让搬运工将某一行或者某一列的障碍物全部清除。如果你让搬运工清除第i行障碍物，需要付出ai元；如果你让搬运工清除第j列障碍物，需要付出bj元。
</p>
<p>
小涵告诉小宇，必须用尽可能少的次数消除这些障碍物。若有多种方案，则必须花费尽量少的费用。结果小宇想了很久仍然没有闯过第一关，只好向你求助了。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第1行，一个正整数n。
</p>
<p>
第2~n+1行，每行n个字符。第i+1行的第j个字符表示地图的坐标(i, j)的格子（左上角为起点(1, 1)）。’*’表示障碍，’.’表示空格。
</p>
<p>
第n+2行，n个正整数，第i个数表示清除地图第i行的费用。
</p>
<p>
第n+3行，n个正整数，第i个数表示清除地图第i列的费用。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出2行。第1行是最少次数，第2行是在最少次数的前提下费用的最小值。
</p>
<h3>
【样例输入】
</h3>
<pre>3
...
.*.
**.
10 5 17
1 8 4
</pre>
<h3>
【样例输出】
</h3>
<pre>2
9
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
30%的数据满足对于任意i和j(1 &lt;= i, j &lt;= n)，有ai = bj。
</p>
<p>
100%的数据满足1 &lt;= n &lt;= 200，0 &lt;= ai, bj &lt;= 100.
</p>
<p>
[样例说明]一共有三个障碍物，坐标分别是(2, 2), (3, 1), (3, 2)。消除第1列和第2列是最优方案。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
HZOI
</p>