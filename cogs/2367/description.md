# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
给你一个完全图，有n个节点，标号为1..n  
</p>
<p>
每个点的权值就是自己的标号  
</p>
<p>
查询图中最小生成树有多少个，这个的最小生成树必须满足父亲节点的标号小于自己,边的权值是连接的两个点的标号的gcd  
</p>
<p>
有4个操作  
</p>
<p>
D u v 删除边(u,v)，保证有边相连。  
</p>
<p>
Q 查询最小生成树有多少个  
</p>
<p>
S 查询当前的最小生成树权值和为多少  
</p>
<p>
A 加一个节点，标号为当前最大的节点的标号+1，并且将他和每个节点连接一条边  
</p>
<p>
<br/>
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
<br/>
</p>
<p>
第一行两个数n,m  
</p>
<p>
然后m行表示操作数  
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>无</pre>
<h3>
【样例输出】
</h3>
<pre>无</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
0% n&lt;=10 m&lt;=10 并且只有查询操作  
</p>
<p>
20% n&lt;=1000 m&lt;=1000 并且只有查询操作和加点操作  
</p>
<p>
60% n&lt;=30000 m&lt;=30000 保证图的连通性，并且每个节点被删除的边的个数不会超过sqrt(i)个,Q操作不超过20次  
</p>
<p>
100% n&lt;=500000 m&lt;=500000 保证图的连通性，并且每个节点i被删除的边的个数不会超过sqrt(i)个，最后一次操作是查询  
</p>
<p>
答案 mod 100000007  
</p>
<p>
删除的节点的标号必然&gt;=1000  
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
改编自某题
</p>