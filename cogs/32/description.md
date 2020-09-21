# 题目描述


<h3>
【问题描述】
</h3>
<p>
给定一个 n*m 的矩形位图，位图中的每个像素不是白色就是黑色，但至少有一个是白色的。第 i 行、第 j 列的像素被称作像素 (i, j) 。两个像素 p1 = (i1, j1) ， p2 = (i2, j2) 之间的距离定义为： d(p1, p2) = |i1 - i2| + |j1 - j2|.
</p>
<h3>
【任务】
</h3>
<p>
编一个程序完成以下操作：
</p>
<p>
1 ．从输入文件中读入此位图的有关信息。
</p>
<p>
2 ．对于每个像素，计算此像素与离其最近的“白像素”的距离。
</p>
<p>
3 ．将结果写到输出文件里面。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行包含两个整数 n, m （ 1 ≤ n ≤ 182, 1 ≤ m ≤ 182 ），用一个空格隔开。接下来 n 行，每一行都包含一个长度为 m 的 01 串；第 i+1 行，第 j 列的字符若为 1 ，则像素 (i, j) 是白色的；否则是黑色的。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件包含 n 行 , 每行有 m 个用空格隔开的整数。第 i 行、第 j 列的整数表示 (i, j) 与离它最近的白像素之间的距离
</p>
<h3>
【样例输入】
</h3>
<pre>3 4
0001
0011
0110
</pre>
<h3>
【样例输出】
</h3>
<pre>3 2 1 0
2 1 0 0
1 0 0 1
</pre>