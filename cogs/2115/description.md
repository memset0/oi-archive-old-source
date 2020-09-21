# 题目描述


<h3>
【题目描述】
</h3>
<p>
一棵树上有黑白两种颜色的点，树上每条边都有边权。树上的点最初都为白色，现在我们需要维护两种操作。
</p>
<p>
1.C操作，把编号为x的点的颜色翻转。
</p>
<p>
2.A操作，查询最远的两个白点的距离
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数N，代表点的个数(N&lt;=100000)；
</p>
<p>
之后的N-1行，每行三个整数x,y,z代表x和y之间存在一条边权为z的边（-1000&lt;=z&lt;=1000)
</p>
<p>
之后是一个Q，代表有Q个操作。
</p>
<p>
接下来的Q行，每行有为一个C操作或一个A操作
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个A操作，输出最远的两个白点的距离，如果树上没有白点，输出They have disappeared.
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
3
</p>
<p>
1 2 1
</p>
<p>
1 3 1
</p>
<p>
7
</p>
<p>
A
</p>
<p>
C 1
</p>
<p>
A
</p>
<p>
C 2
</p>
<p>
A
</p>
<p>
C 3
</p>
<p>
A
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
<br/>
</p>
<p>
2
</p>
<p>
2
</p>
<p>
0
</p>
<p>
They have disappeared.
</p>
<p>
<br/>
</p>