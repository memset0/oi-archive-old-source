# 题目描述


<h3>
【题目描述】
</h3>
<p>
现在请求你维护一个数列，要求提供以下两种操作：
</p>
<p>
1、 查询操作。
</p>
<p>
语法：Q L
</p>
<p>
功能：查询当前数列中末尾L个数中的最大的数，并输出这个数的值。
</p>
<p>
限制：L不超过当前数列的长度。 
</p>
<p>
2、 插入操作。
</p>
<p>
语法：A n
</p>
<p>
功能：将n加上t，其中t是最近一次查询操作的答案（如果还未执行过查询操作，则t=0)，并将所得结果对一个固定的常数D取模，将所得答案插入到数列的末尾。
</p>
<p>
限制：n是非负整数并且在长整范围内。
</p>
<p>
注意：初始时数列是空的，没有一个数。
</p>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
第一行两个整数，M和D，其中M表示操作的个数(M &lt;= 200,000)，D如上文中所述，满足$1 \leq int64_{max}$
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
对于每一个查询操作，你应该按照顺序依次输出结果，每个结果占一行。
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>5 100
A 96
Q 1
A 97
Q 1
Q 2</pre>
<h3>
【样例输出】
</h3>
<pre>96
93
96</pre>
<h3>
【题目来源】
</h3>
<p>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=1012">耒阳大视野（衡阳八中） OJ 1012</a> 
</p>
