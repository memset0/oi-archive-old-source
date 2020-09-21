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
Farmer John的农场沿着一条长直道路而建，所以他农场上的每个地点都可以简单地用该地点在道路上的位置来表示（相当于数轴上的一个点）。一个传送门可以用两个数x和y表示，被拖到地点x的牛粪可以瞬间传送到地点y，反之亦然。
</p>
<p>
<br/>
</p>
<p>
Farmer John想要将牛粪从地点a运输到地点b，他建造了一个可能对这一过程有所帮助的传送门（当然，如果没有帮助，他也可以不用）。请帮助他求出他需要使用拖拉机运输牛粪的总距离的最小值。
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
输入仅包含一行，为四个用空格分隔的整数：a和b，表示起始地点和结束地点，后面是x和y，表示传送门。所有的位置都是范围为0…100的整数，不一定各不相同。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个整数，为Farmer John需要用拖拉机运输牛粪的最小距离。
</p>
<h3>
【样例输入】
</h3>
<pre>3 10 8 2</pre>
<h3>
【样例输出】
</h3>
<pre>3</pre>
<h3>
【提示】
</h3>
<p>
在这个样例中，最佳策略是将牛粪从位置3运到位置2，传送到位置8，再运到位置10。 所以需要用拖拉机的总距离为1 + 2 = 3。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://www.usaco.org/index.php?page=feb18results" target="_blank">USACO 2018 February Contest</a> Bronze problem 1
</p>
<p>
供题：Brian Dean
</p>