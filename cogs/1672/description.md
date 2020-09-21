# 题目描述


<h3>
【题目描述】
</h3>
<p>
一天机房的夜晚，无数人在MC里奋斗着。。。
</p>
<p>
大家都知道矿产对于MC来说是多么的重要，但由于矿越挖越少，勇士们不得不跑到更远的地方挖矿，但这样路途上就会花费相当大的时间，导致挖矿效率低下。
</p>
<p>
cjj提议修一条铁路，大家一致同意。
</p>
<p>
大家都被CH分配了一些任务：
</p>
<p>
zjmfrank2012负责绘制出一个矿道地图，这个地图包括家（当然这也是一个矿，毕竟不把家掏空我们是不会走的），和无数个矿，所以大家应该可以想出这是一个无向无环图，也就是一棵树。
</p>
<p>
Digital_T和cstdio负责铺铁路。。所以这里没他们什么事，两位可以劳作去了。
</p>
<p>
这个时候song526210932和RMB突然发现有的矿道会刷怪，并且怪的数量会发生变化。作为采矿主力，他们想知道从一个矿到另一个矿的路上哪一段会最困难。。。（困难值用zjm的死亡次数表示）。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有一个整数N，代表矿的数量。矿的编号是1到N。
</p>
<p>
接下来N-1行每行有三个整数a,b,c，代表第i号矿和第j号矿之间有一条路，在初始时这条路的困难值为c。
</p>
<p>
接下来有若干行，每行是“CHANGE i ti”或者“QUERY a b”，前者代表把第i条路（路按所给顺序从1到M编号）的困难值修改为ti，后者代表查询a到b所经过的道路中的最大困难值。
</p>
<p>
输入数据以一行“DONE”结束。
</p>
<h3>
【输出格式】
</h3>
<p>
对每个“QUERY”操作，输出一行一个正整数，即最大困难值。
</p>
<h3>
【样例输入】
</h3>
<p>
3
</p>
<p>
1 2 1
</p>
<p>
2 3 2
</p>
<p>
QUERY 1 2
</p>
<p>
CHANGE 1 3
</p>
<p>
QUERY 1 2
</p>
<p>
DONE
</p>
<h3>
【样例输出】
</h3>
<p>
1
</p>
<p>
3
</p>
<h3>
【提示】
</h3>
<p>
对于60%的数据，1&lt;=N&lt;=50
</p>
<p>
对于100%的数据，1&lt;=N&lt;=10000，1&lt;=c&lt;=1000000,1&lt;=操作次数&lt;=100000
</p>
<h3>
【来源】
</h3>
<p>
由GDFRWMY 改编自<a href="http://www.spoj.com/problems/QTREE/" target="_blank">SPOJ 375 QTREE</a> 
</p>
<p>
数据by cstdio
</p>