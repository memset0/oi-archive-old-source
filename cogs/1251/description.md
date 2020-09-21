# 题目描述


<h3>
【题目描述】
</h3>
<p>
农夫每天去种地都要过一条河，这条河很宽，过河要走上面的木桩。木桩有n支，排成一排，从左岸延伸到右岸，编号从1到n。左岸在1号桩的左边，右岸在n号桩的右边。但这些木桩会定时升降，因此每天他都花不少时间在过河上。所以他想找一种最快过河的方法。
</p>
<p>
在时刻0，农夫在左岸，他要在最短时间内到达右岸。在任何时刻，每一支桩都只能处于升或降的其中一种状态。升起的桩才可以站上去，农夫只能站在升起的桩上或岸上。
</p>
<p>
每一支桩在时刻0都是降的状态，接着升起A分钟，降下B分钟，再升起A分钟后，再降下B分钟后，这样一直交替升降下去。例如：A=2，B=3的桩，在时刻0降，在时刻1，2升，在时刻3，4，5降，等等。A和B是常数时间，而且对于每一支桩都可能不同。
</p>
<p>
设在时刻t农夫站在p桩，那么在时刻t+1，农夫能走到p桩的左右5个桩上或岸上，也可以原地不动，当然桩是可站立的。例如，在5号桩，他能走到1，2，3，4，5，6，7，8，9，10号桩，或到左岸。
</p>
<p>
请帮农夫找一种能最快到达右岸的方法。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行是桩的数目，n(5&lt;n≤1000)。接下来的n行每一行有两个整数A和B(1≤A，B≤5)，用一个空格隔开。按从1到n的顺序描述每一支桩的升和降的间隔时间。
</p>
<h3>
【输出格式】
</h3>
<p>
只有一行，即最早到达右岸的时刻。当不可能到达右岸时，输出“NO”。
</p>
<h3>
【样例输入】
</h3>
<pre>10
1  1
1  1
1  1
1  1
2  1
1  1
1  1
1  1
1  1
1  1
</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<br/>