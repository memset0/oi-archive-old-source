# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
在遥远的地方有一个大海。
</p>
<p>
在大海上有N个小岛。
</p>
<p>
有一些有向的桥将这些小岛连接起来。
</p>
<p>
有一个叫做“壹号国”的国家位于1号小岛上。
</p>
<p>
还有一个叫做“其它国”的国家位于N号小岛上。
</p>
<p>
“壹号国”起兵进攻“其它国”，挑起了一场战争。
</p>
<p>
“其它国”想到了一个策略，想通过破坏一些桥，斩断1号小岛同N号小岛的联系，借此来实现防守。
</p>
<p>
破坏不同的桥有不同的代价。
</p>
<p>
“其它国”有个大仙儿，能掐会算，他能算出来为实现防守策略而拆桥所需要的最小代价。
</p>
<p>
“壹号国”有一个建筑队，能把一个桥重建并使其坚不可摧，他们也能在2～N-1号小岛任意两个小岛间新建一个坚不可摧的桥。
</p>
<p>
但是在“其它国”开始拆桥之前，“壹号国”没有足够的时间了，所以它只能新建一个桥或者将一个已经存在的桥重建。
</p>
<p>
现在问题是：“壹号国”想让“其它国”拆桥的最小代价最大化，那么那个可能的最大解是多少呢？
</p>
<p>
<br/>
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
输入文件有多组测试数据。
</p>
<p>
文件的第一行有一个整数，即接下来测试数据的个数,不超过100组。
</p>
<p>
对于每个测试数据，第一行有两个数：N，M，（4&lt;=N&lt;=100;
</p>
<p>
0&lt;=M&lt;=N*(N-1)/2）,分别表示小岛的个数及桥的个数。
</p>
<p>
接下来有M行，每一行有三个整数a,b,c，（1&lt;=a,b&lt;=N;
</p>
<p>
1&lt;=c&lt;=10000），表示有一个有向的桥从小岛a连向小岛b，拆除它的代价为c。
</p>
<p>
数据保证没有重边。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个测试数据，输出只有一行，即上述可能的最大解。
</p>
<h3>
【样例输入】
</h3>
<pre>4
4 0
4 2
1 2 2
3 4 2
4 3
1 2 1
2 3 1
3 4 10
4 3
1 2 5
2 3 2
3 4 3
</pre>
<h3>
【样例输出】
</h3>
<pre>0
2
1
3
</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>