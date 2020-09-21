# 题目描述


<h3>
【问题描述】
</h3>
<p>
在河上有一座独木桥，一只青蛙想沿着独木桥从河的一侧跳到另一侧。在桥上有一些石子，青蛙很讨厌踩在这些石子上。由于桥的长度和青蛙一次跳过的距离都是正整 数，我们可以把独木桥上青蛙可能到达的点看成数轴上的一串整点： 0 ， 1 ，……， L （其中 L 是桥的长度）。坐标为 0 的点表示桥的起点，坐标为 L 的点表示桥的终点。青蛙从桥的起点开始，不停的向终点方向跳跃。一次跳跃的距离是 S 到 T 之间的任意正整数（包括 S,T ）。当青蛙跳到或跳过坐标为 L 的点时，就算青蛙已经跳出了独木桥。
</p>
<p>
<img src="/upload/image/20131126/20131126230636_38987.jpg" alt="" width="360" height="240" title="" align=""/> 
</p>
<p>
题目给出独木桥的长度 L ，青蛙跳跃的距离范围 S,T ，桥上石子的位置。你的任务是确定青蛙要想过河，最少需要踩到的石子数。
</p>
<h3>
【输入文件】
</h3>
<p>
输入文件的第一行有一个正整数 L （ 1 &lt;= L &lt;= 10^9 ），表示独木桥的长度。第二行有三个正整数 S ， T ， M ，分别表示青蛙一次跳跃的最小距离，最大距离，及桥上石子的个数，其中 1 &lt;= S &lt;= T &lt;= 10 ， 1 &lt;= M &lt;= 100 。第三行有 M 个不同的正整数分别表示这 M 个石子在数轴上的位置（数据保证桥的起点和终点处没有石子）。所有相邻的整数之间用一个空格隔开。
</p>
<h3>
【输出文件】
</h3>
<p>
输出文件只包括一个整数，表示青蛙过河最少需要踩到的石子数。
</p>
<h3>
【输入样例】
</h3>
<pre>10
2 3 5
2 3 5 6 7
</pre>
<h3>
【输出样例】
</h3>
<pre>2
</pre>
<h3>
【数据规模】
</h3>
<p>
对于30%的数据，L &lt;= 10000；<br/>
对于全部的数据，L &lt;= 10^9。
</p>