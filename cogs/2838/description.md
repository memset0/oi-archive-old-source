# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
wcg有一个二元关系R，R 可以被表示成n * n 的布尔数组。
</p>
<p>
现在希望找到长度都为n 的数组f 和g，要求满足Rx;y = 1 当且仅当f(x) &lt;= g(y)。
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
第一行包含一个整数n(1 &lt;= n &lt;= 1000)，表示数组的大小。
</p>
<p>
接下来的n 行表示二元关系R。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
第一行输出能否找到数组f 和g，如果能找到输出YES，否则输出NO。-10e9 &lt;= fi; gi &lt;= 10e9
</p>
<p>
第二行输出n 个整数，表示数组f。
</p>
<p>
第三行输出n 个整数，表示数组g 。
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
<pre><p>
3
</p>

<p>
111
</p>

<p>
110
</p>

<p>
100
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
YES
</p>

<p>
0 1 2
</p>

<p>
2 1 0
</p>
</pre>
<h3>
【数据范围】
</h3>
<p>
<br/>
</p>
<p>
对于20% 的数据，n &lt;= 10。
</p>
<p>
对于50% 的数据，n &lt;= 100。
</p>
<p>
对于100% 的数据，n &lt;= 1000。
</p>
<p>
开启spj
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
qbxt 2017.10.6 t3
</p>
