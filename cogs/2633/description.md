# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
一个长度为n的序列，一开始序列数的权值都是0,有m次操作
</p>
<p>
支持两种操作，
</p>
<p>
1 L R x，给区间[L,R]内,第一个数加x,第二个数加$2^2\cdot x$,第三个数加$3^2\cdot x$...第R-L+1个数加$(R-L+1)^2\cdot x$
</p>
<p>
2 L R 查询区间[L,R]内的权值和
</p>
<p>
每次询问的答案对$2^{64}$取模
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
第一行两个数n，m，表示序列长度和操作次数
</p>
<p>
接下来m行，每行描述一个操作，有如下两种情况：
</p>
<p>
<br/>
</p>
<p>
1 L R x，给区间[L,R]内,第一个数加x,第二个数加$2^2\cdot x$,第三个数加$3^2\cdot x$...第R-L+1个数加$(R-L+1)^2\cdot x$
</p>
<p>
2 L R 查询区间[L,R]内的权值和
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
为了减少输出，你只需要输出所有答案对$2^{64}$取膜之后的异或和。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5 5
</p>

<p>
1 3 4 1
</p>

<p>
2 1 5
</p>

<p>
2 2 2
</p>

<p>
1 3 3 1
</p>

<p>
1 2 4 1
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>5</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
对于10%的数据 n，m&lt;=2000
</p>
<p>
对于30%的数据 n,m&lt;=10000
</p>
<p>
对于100%的数据，n，m&lt;=100000,1&lt;=L&lt;=R&lt;=n,0&lt;=x&lt;=$10^9$
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
一只名字很长的蒟蒻
</p>