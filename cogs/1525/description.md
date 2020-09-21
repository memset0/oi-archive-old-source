# 题目描述


<h3>
【题目描述】
</h3>
<p>
给你一个r行c列的网格。行被编号为0到r-1，列被编号为0到c-1.第i行第j列的点可以和点(i-1,j),(i,j-1),(i+1,j)和(i,j+1)连边，如果这些点存在。现在，网格中已经有了一些边。你可以向其中添加其他的边。你加边的方式必须使得网格中所有的点都连通，但没有环。你要计算出加边的方案总数。
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组数据。
</p>
<p>
输入文件的第一行是一个整数T（1&lt;=T&lt;=30），即数据组数。
</p>
<p>
接下来是T组数据。
</p>
<p>
每组数据的第一行有3个整数r(1&lt;=r&lt;=200),c(1&lt;=c&lt;=8)和md(1&lt;=md&lt;=1000000)。
</p>
<p>
接下来有2*r-1行，描述了网格和已经添加的边。
</p>
<p>
每行有2*c-1个字符。
</p>
<p>
下面，将这些行从0开始编号，将每行的字符也从0开始编号。
</p>
<p>
偶数行的第偶数个字符将是一个&#39;.&#39;，代表一个点。
</p>
<p>
偶数行的第奇数个字符是一个代表左右两点之间没有边的&#39;S&#39;，或是一个代表有边的&#39;-&#39;。
</p>
<p>
奇数行的第偶数个字符是一个代表上下两点之间没有边的&#39;S&#39;，火石一个代表有边的&#39;|&#39;。
</p>
<p>
奇数行的第计数个字符是一个&#39;S&#39;,代表周围四个点围成的空格。
</p>
<p>
观察样例以更清楚地理解格式。
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，输出使所有点连通成一棵树的添边方案总数。这个数有可能很大，因此输出它模md的值。如果没有这样的添边方法，输出一行&#34;Impossible&#34;，不含引号。
</p>
<h3>
【样例输入】
</h3>
<p>
6
</p>
<p>
2 2 1000
</p>
<p>
.S.
</p>
<p>
SSS
</p>
<p>
.S.
</p>
<p>
2 2 100
</p>
<p>
.-.
</p>
<p>
|S|
</p>
<p>
.S.
</p>
<p>
2 2 100
</p>
<p>
.-.
</p>
<p>
|S|
</p>
<p>
.-.
</p>
<p>
3 3 10000
</p>
<p>
.S.S.
</p>
<p>
SSSSS
</p>
<p>
.S.S.
</p>
<p>
SSSSS
</p>
<p>
.S.S.
</p>
<p>
3 3 10000
</p>
<p>
.-.-.
</p>
<p>
SSSSS
</p>
<p>
.-.-.
</p>
<p>
SSSSS
</p>
<p>
.-.-.
</p>
<p>
3 3 10000
</p>
<p>
.S.S.
</p>
<p>
|S|S|
</p>
<p>
.S.S.
</p>
<p>
|S|S|
</p>
<p>
.S.S.
</p>
<h3>
【样例输出】
</h3>
<p>
4
</p>
<p>
1
</p>
<p>
Impossible
</p>
<p>
192
</p>
<p>
9
</p>
<p>
9
</p>
<h3>
【提示】
</h3>
<p>
为了适应评测机的linux环境，对本题的数据格式进行了修改。在UVa原题中，无边的地方用空格表示，而在这里换成了字符S。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=572&amp;page=show_problem&amp;problem=2438" target="_blank">UVa11443 Tree in a Grid</a> 
</p>