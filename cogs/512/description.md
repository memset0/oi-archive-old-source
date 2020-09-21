# 题目描述


<p>
【问题描述】<br/>
在平面上有n个点，一个点每过一个单位时间就会向4个方向（上下左右）扩散一个距离，如下图所示：<br/>
<img src="/upload/image/20120925/20120925165429_22016.jpg" alt=""/><br/>
两个点a和b连通，记作e(a,b)，当且仅当a、b的扩散区域有公共部分。连通块的定义是块内的任意两个点u、v都必定存在路径e(u,a0),e(a0,a1),……e(ak,v)。给定平面上n个点的坐标，问最早什么时刻它们形成一个连通块。<br/>
【输入文件】<br/>
第一行一个数：n<br/>
下面n行，每行两个整数x,y，代表一个点的坐标。<br/>
【输出文件】<br/>
一个整数，表示最早的时刻所有点形成的连通块。<br/>
【样例输入】<br/>
2<br/>
0 0<br/>
5 5<br/>
【样例输出】<br/>
5<br/>
【数据规模】<br/>
对于20%的数据，满足1&lt;=n&lt;=5; 1&lt;=x[i],y[i]&lt;=50;<br/>
对于100%的数据，满足1&lt;=n&lt;=50;1&lt;=x[i],y[i]&lt;=10^9
</p>