# 题目描述


<h3>
【题目描述】
</h3>
<p>
给出一个M行N列的网格，其中部分格子被染色。你将要计算在下面所述的约束下，填满网格剩余部分的方法总数：
</p>
<p>
网格中的每一个格子都应染成黑白二色之一。网格中所有的黑色格子应当四连通，所有的白色格子也应该四连通。在下面的两张图片中，只有右图是合法的。
</p>
<p>
<img src="/upload/image/20140130/20140130161043_78261.gif" alt=""/><img src="/upload/image/20140130/20140130161050_89872.gif" alt=""/> 
</p>
<p>
另外，不能有全黑或全白的2*2子网格。在下面的两张图中，左边的图片中有2*2的全黑和全白网格，因此不合法，而由图中没有2*2的同色网格，因此是合法的。
</p>
<p>
<img src="/upload/image/20140130/20140130161304_52545.gif" alt=""/><img src="/upload/image/20140130/20140130161309_23670.gif" alt=""/> 
</p>
<p>
不能改变已被染色格子的颜色。所有的格子都必须被染色。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有2个正整数M,N，代表行数和列数
</p>
<p>
接下来的M行，每行有N个字符，它们代表了开始时M*N网格的状态。这些字符可能是如下三种：
</p>
<p>
#：一个被染成黑色的格子。
</p>
<p>
o：一个被染成白色的格子。
</p>
<p>
.：一个没有染色的格子。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个正整数，即染色方案总数。
</p>
<h3>
【样例输入】
</h3>
<p>
sample 1:
</p>
<p>
<br/>
</p>
<p>
3 3
</p>
<p>
o..
</p>
<p>
.##
</p>
<p>
...
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
sample 2:
</p>
<p>
<br/>
</p>
<p>
5 5
</p>
<p>
..#..
</p>
<p>
.....
</p>
<p>
....o
</p>
<p>
o....
</p>
<p>
.#...
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
sample 3:
</p>
<p>
<br/>
</p>
<p>
7 5
</p>
<p>
.....
</p>
<p>
..o..
</p>
<p>
#....
</p>
<p>
.....
</p>
<p>
..o..
</p>
<p>
...#.
</p>
<p>
o....
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
sample 4:
</p>
<p>
<br/>
</p>
<p>
2 3
</p>
<p>
###
</p>
<p>
oo#
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
sample 5:
</p>
<p>
<br/>
</p>
<p>
6 8
</p>
<p>
........
</p>
<p>
........
</p>
<p>
........
</p>
<p>
........
</p>
<p>
.#......
</p>
<p>
........
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
sample 1:
</p>
<p>
4
</p>
<p>
<br/>
</p>
<p>
sample 2:
</p>
<p>
0
</p>
<p>
<br/>
</p>
<p>
sample 3:
</p>
<p>
176
</p>
<p>
<br/>
</p>
<p>
sample 4:
</p>
<p>
1
</p>
<p>
<br/>
</p>
<p>
sample 5:
</p>
<p>
71582
</p>
<h3>
【提示】
</h3>
<p>
对于20%的数据，2&lt;=M,N&lt;=4
</p>
<p>
对于100%的数据，2&lt;=M,N&lt;=8
</p>
<h3>
【来源】
</h3>
<p>
Problemsetter: Jimmy Mårdell, Member of Elite Problemsetters&#39; Panel
</p>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=17&amp;page=show_problem&amp;problem=1513" target="_blank">UVa10572 Black &amp; White</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》，P387 例题3
</p>
