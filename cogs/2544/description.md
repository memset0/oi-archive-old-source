# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
Opah很难Q中人，于是她决定主W。W是范围伤害，可以给予一个区间内敌人伤害。
</p>
<p>
Opah一共有n名敌人，她的敌人们站在一根数轴上。
</p>
<p>
Opah的W可以给予k个不同的敌人伤害，所以说她希望找到k名数轴上的敌人，使任意无序二元敌人对$(x_i,x_j)$的距离之和最小，即$$\sum_{1\leq i\leq j\leq n}|x_i - x_j|$$最小
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行有两个被空格隔开的正整数，分别为$n$($n&lt;=10^5$)和$k(k&lt;=n)$
</p>
<p>
第二行有n个被空格隔开的数，表示每一名敌人的坐标($|x_i|&lt;2^{30}$)
</p>
<p>
（保证没有两名敌人在同一位置）
</p>
<h3>
【输出格式】
</h3>
<p>
一个整数ans,表示最小距离和
</p>
<h3>
【样例输入】
</h3>
<pre><p>
4 3
1 2 3 8
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
选1,2,3，这三个点。
</p>
<p>
|1-2|+|1-3|+|2-3|=4
</p>
<p>
<br/>
</p>
<p>
对于100%的数据, $1&lt;= n &lt;= 10^5$
</p>
<p>
30%: $n &lt;= 10^2$
</p>
<p>
30%: $n &lt;= 10^3$
</p>
<p>
20%: $n &lt;= 10^4$
</p>
<p>
20%: $n &lt;= 10^5$
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
Ra~piz！
</p>