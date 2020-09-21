# 题目描述


<h3>
【题目描述】
</h3>
<p>
Mike第一次坐在文科15班的教室中，见到了许多新同学。Mike记忆力极差，为了记住同学们的名字，Mike准备他们的名字抄下来。Mike又太懒，于是他把这项工作交给了你。
</p>
<p>
Mike一共有3种命令：第一种，在名单里加入一个同学的名字S(均为小写字母)；第二种，Mike看错了第i个命令加入的同学的名字，在他的名字后面插入字符串T(可能进行多次插入).
</p>
<p>
为了检验你做的是否正确，Mike要求你立即回答出每次操作后，名单中本质不同的回文子串数量。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数n，表示Mike一共有n个命令。
</p>
<p>
接下来n行，每行开始有一个整数tp，表示是哪一种命令。
</p>
<p>
tp=1时，接下来是一个字符串S，表示这位同学的名字。
</p>
<p>
tp=2时，接下来是一个整数i和一个字符串T，表示在第i次加入的名字后面插入T。(可能多次插入，保证这个同学的名字在当前的名单中)
</p>
<h3>
【输出格式】
</h3>
<p>
n行，每行一个整数，表示每次操作后本质不同的回文子串个数。
</p>
<h3>
【样例输入】
</h3>
<pre>10
1 miike
1 mmike
1 mikke
2 2 ekim
1 jhzejkhzhe
2 2 ekim
2 3 ekimm
1 foolmike
2 2 mike
1 mikeisfool
</pre>
<h3>
【样例输出】
</h3>
<pre>5
6
7
11
15
15
15
19
22
23
</pre>
<h3>
【提示】
</h3>
<p>
数据范围为n&lt;=200000，L&lt;=2000000
</p>
<p>
对于20%的数据，保证n&lt;=2000
</p>
<p>
对于另外20%的数据，保证不含2操作
</p>
<h3>
【来源】
</h3>
<p>
这实际上是Mike做的一个梦……Mike活在理科1班
</p>