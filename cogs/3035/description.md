# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
Farmer John最讨厌的农活是运输牛粪。为了精简这个过程，他制造了一个伟大的发明：便便传送门！与使用拖拉机拖着装满牛粪的大车从一个地点到另一个地点相比，他可以使用便便传送门将牛粪从一个地点瞬间传送到另一个地点。
</p>
<p>
<br/>
</p>
<p>
Farmer John的农场沿着一条长直道路而建，所以他农场上的每个地点都可以简单地用该地点在道路上的位置来表示（相当于数轴上的一个点）。一个传送门可以用两个数x和y表示，被拖到地点x的牛粪可以瞬间传送到地点y。
</p>
<p>
<br/>
</p>
<p>
Farmer John决定建造一个起点位于x=0的传送门；你的任务是帮助他确定最佳的终点y。具体地说，在他的农场上有N堆牛粪（1≤N≤100,000）。第i堆牛粪需要被从位置ai移动到位置bi，Farmer John会分别运输每一堆牛粪。我们设di为FJ使用拖拉机运输第i堆牛粪的距离，则当他直接使用拖拉机运输第i堆牛粪时，有di=|ai−bi|，或者di可能在他使用传送门的情况下可以变得更小（比方说，用他的拖拉机从ai运到x，再从y运到bi）。
</p>
<p>
<br/>
</p>
<p>
请帮助FJ求出，在他恰当选择传送门的终点y的情况下，能够达到的所有di的和的最小值。在所有牛粪的运输中，终点位置y是相同的。
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
输入的第一行包含N。在下面的N行中，第i行包含ai和bi，每个整数都在−10^8…10^8之间。这些数值不一定各不相同。
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
输出一个数，为能够达到的di的和的最小值。注意这个数字可能超过标准的32位整数型能够表示的范围，所以你可能需要使用更大的数据类型，例如C/C++中的“long long”。同样你可能需要考虑答案是否一定是一个整数……
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>3
-5 -7
-3 10
-2 7
</pre>
<h3>
【样例输出】
</h3>
<pre>10</pre>
<h3>
【提示】
</h3>
<p>
在这个样例中，通过设置y=8，FJ可以实现d1=2，d2=5，d3=3。注意y取区间[7,10]中的任意值都能够得到最优解。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://www.usaco.org/index.php?page=feb18results" target="_blank">USACO 2018 February Contest</a> SILVER Problem 1
</p>
<p>
供题：Brian Dean
</p>