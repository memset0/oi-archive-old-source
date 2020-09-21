# 题目描述


<h3>
【题目描述】
</h3>
<p>
在一个地图上有N个地窖（N&lt;=200）,每个地窖中埋有一定数量的地雷。同时，给出地窖之间的连接路径，并规定路径都是单向的,且保证都是小序号地窖指向大序号地窖，也不存在可以从一个地窖出发经过若干地窖后又回到原来地窖的路径。某人可以从任一处开始挖地雷，然后沿着指出的连接路径往下挖（仅能选择一条路径），当无连接路径时挖地雷工作结束。设计一个挖地雷的方案，使他能挖到最多的地雷。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数n表示地窖的个数。
</p>
<p>
接下来一行有n个正整数，表示每个地窖中的地雷数。
</p>
<p>
接下来好多行.....
</p>
<p>
x1 y1   //表示可从x1到达y1,且保证x1&lt;y1
</p>
<p>
x2 y2   //表示可从x2到达y2,且保证x2&lt;y2
</p>
<p>
...
</p>
<p>
0 0     //表示输入结束
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
K1-K2-…-Ki                                //挖地雷的顺序
</p>
<p>
MAX                                        //最多挖出的地雷数
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
6
</p>

<p>
5 10 20 5 4 5
</p>

<p>
1 2
</p>

<p>
1 4
</p>

<p>
2 4
</p>

<p>
3 4
</p>

<p>
4 5
</p>

<p>
4 6
</p>

<p>
5 6
</p>

<p>
0 0
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
3-4-5-6
</p>

<p>
34
</p>
</pre>
<h3>
【来源】
</h3>
<p>
《信息学奥赛一本通》
</p>