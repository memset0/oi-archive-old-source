# 题目描述


<h3>
【题目描述】
</h3>
<p>
给你一张无向图G(V,E)。每个顶点都有一个标号，它是一个[0,2^31-1]内的整数。不同的顶点可能会有相同的标号。
</p>
<p>
对每条边(u,v)，我们定义其费用cost(u,v)为u的标号与v的标号的异或值。
</p>
<p>
现在我们知道一些顶点的标号。你需要确定余下顶点的标号使得所有边的费用和尽可能小。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有两个整数N,M(1&lt;=N&lt;=500,0&lt;=M&lt;=3000)，N是图的点数，M是图的边数。
</p>
<p>
接下来有M行，每行有两个整数u,v，代表一条连接u,v的边。
</p>
<p>
接下来有一个整数K，代表已知标号的顶点个数。接下来的K行每行有两个整数u,p，代表点u的标号是p。假定这些u不会重复。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个整数，即最小的费用和。
</p>
<h3>
【样例输入】
</h3>
<p>
3 2
</p>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
2
</p>
<p>
1 5
</p>
<p>
3 100
</p>
<h3>
【样例输出】
</h3>
<p>
97
</p>
<h3>
【提示】
</h3>
<p>
一个可能的标号方案是：点1标5，点2标4，点3标100.
</p>
<p>
SPOJ上原题的输入输出格式和这里有所不同。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://www.spoj.com/problems/OPTM/" target="_blank">SPOJ 839 Optimal Marks</a> 
</p>
<p>
Resource: Guo HuaYang
</p>