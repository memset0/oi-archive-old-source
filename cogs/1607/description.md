# 题目描述


<h3>
【题目描述】
</h3>
<p>
某城市的地铁是线性的，有 $n(2\le n\le 50)$ 个车站，从左到右编号为 $1～n$。有 $M_1$ 辆列车从第 $1$ 站开始往右开，还有 $M_2$ 辆列车从第 $n$ 站开始往左开。在时刻 $0$，Mario 从第 $1$ 站出发，目的是在时刻 $T(0\le T\le 200)$ 会见车站 $n$ 的一个间谍。在车站等车时容易被抓，所以她决定尽量躲在开动的火车上，让在车站等待的总时间尽量短。列车靠站停车时间忽略不计，且 Mario 身手敏捷，即使两辆方向不同的列车在同一时间靠站，Mario 也能完成换乘。（修正，数据范围内有时刻T超过200的存在，建议将数据T认为大小为500.————5801）
</p>
<p>
（提示：输入数据中包含多组数据，最后以0为输入结束的标记————5801）
</p>
<p align="center">
<img width="590" height="128" title="" align="" alt="" src="/upload/image/20180918/20180918101849_40262.png"/> 
</p>
<h3>
【输入格式】
</h3>
<p>
输入第 $1$ 行为 $n$，第 $2$ 行为 $T$，第 $3$ 行有 $n-1$ 个整数 $t_1,t_2,\dots ,t_{n-1}(1\le t_i\le 70)$，其中 $t_i$ 表示地铁从车站 $i$ 到 $i+1$ 的行驶时间（两个方向一样）。第 $4$ 行为 $M_1(1\le M_1\le 50)$，即从第 $1$ 站出发向右开的列车数目。第 $5$ 行包含 $M_1$ 个整数 $d_1,d_2,\dots ,d_{M_1}(0\le d_i\le 250.d_i\lt d_i+1)$，即各列车的出发时间。第 $6$、$7$ 行描述从第 $n$ 站出发向左开的列车，格式同第 $4$、$5$ 行。
</p>
<p>
最后一种情况以一行0结尾。
</p>
<h3>
【输出格式】
</h3>
<p>
输出仅包含一行，即最少等待时间。无解输出“impossible”。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
4
</p>

<p>
55
</p>

<p>
5 10 15
</p>

<p>
4
</p>

<p>
0 5 10 20
</p>

<p>
4
</p>

<p>
0 5 10 15
</p>

<p>
4
</p>

<p>
18
</p>

<p>
1 2 3
</p>

<p>
5
</p>

<p>
0 3 6 10 12
</p>

<p>
6
</p>

<p>
0 3 5 7 12 15
</p>

<p>
2
</p>

<p>
30
</p>

<p>
20
</p>

<p>
1
</p>

<p>
20
</p>

<p>
7
</p>

<p>
1 3 5 7 11 13 17
</p>

<p>
0
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>Case Number 1: 5
Case Number 2: 0
Case Number 3: impossible
</pre>
<h3>
【提示】
</h3>
<p>
数据很弱，别抱太大希望。
</p>
<h3>
【来源】
</h3>
<p>
UVa 1025 A Spy in the Metro
</p>
