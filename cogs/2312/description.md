# 题目描述


<h3>
【题目描述】
</h3>
<p>
QAQ最近学会了树状数组，他觉得非常的开心，他发现树状数组开了O2之后跑的飞快
</p>
<p>
他仔细想了想，发现这是很容易从生物的角度上去解释的，植物总是需要氧气的嘛
</p>
<p>
由于QAQ非常的开心，所以他决定去解决一些简单的求和问题
</p>
<p>
首先有两个长度为n的序列a和f，先给定你序列a
</p>
<p>
之后我们定义fi为[li,ri]这个区间中a序列的和
</p>
<p>
然后给定m个操作，每个操作有两种类型：
</p>
<p>
1、M i u 把ai的值修改为u
</p>
<p>
2、Q L R 询问f序列中[L,R]的和
</p>
<h3>
【输入格式】
</h3>
<p>
第一行输入n，m表示序列长度和操作个数
</p>
<p>
第二行有n个正整数表示ai
</p>
<p>
以下n行每行li，ri如题意所示
</p>
<p>
之后m行每行一个操作如题意所示
</p>
<p>
n,m&lt;=100000,保证每个区间都是合法的
</p>
<p>
输入数据全部都是正整数，a序列中任意时刻任意数不会超过10000
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个Q询问输出对应的答案
</p>
<h3>
【样例输入】
</h3>
<pre><p>
10 10
</p>

<p>
8147 1081 9770 7755 5052 4944 5857 2691 905 8022
</p>

<p>
3 5
</p>

<p>
1 10
</p>

<p>
6 9
</p>

<p>
4 6
</p>

<p>
1 1
</p>

<p>
1 1
</p>

<p>
1 1
</p>

<p>
2 3
</p>

<p>
1 1
</p>

<p>
7 9
</p>

<p>
M 10 1740
</p>

<p>
M 3 8055
</p>

<p>
Q 1 2
</p>

<p>
Q 2 3
</p>

<p>
M 6 5791
</p>

<p>
Q 2 3
</p>

<p>
M 8 4314
</p>

<p>
M 7 4409
</p>

<p>
M 4 7749
</p>

<p>
M 3 7383
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
67089
</p>

<p>
60624
</p>

<p>
62318
</p>
</pre>
<h3>
【来源】codechef
</h3>
