# 题目描述


<p>
	Abstinence岛的居民非常喜欢喝alkoholfree啤酒。虽然到目前为止这种啤酒还是从波兰进口的，但今年他们要在岛上的某一城市建一 啤酒厂。所有城市都位于海岸边，彼此之间通过一条环绕全岛的高速公路联接。啤酒投资商搜集了一些啤酒需求量的信息，譬如每个城市的日啤酒消费量为多少件， 任意俩城市的距离等。一件啤酒每英里的运输费用是一泰勒，因而，将适当件数的啤酒从啤酒厂运往各个城市时，每天的费用将会是很大一笔数目。问题的关键在于 啤酒厂的位置。投资商想找到一个使得日花费量为最小的城市来建造啤酒厂。
</p>
<p>
	任务
</p>
<p>
	编写一程序：
</p>
<ul>
	<li>
		从文件读入城市的个数，任意两城市的距离，以及他们的日啤酒消费量；
	</li>
	<li>
		计算日运输费用的最小值；
	</li>
	<li>
		结果写入文件.
	</li>
</ul>
<p>
	输入
</p>
<p>
	第一行的整数N表示城市的个数，5&lt;=N&lt;=10000(我们假定城市都是沿高速公路编号，相邻的城市编号也紧接。城市一与城 市N相邻）。接下来的N行每行为俩个用单个空格隔开的非负数。第I+1行的数字Z（I）与D（I）分别表示为城市I的啤酒需求量和从城市I沿高速公路到下 一城市的距离（用英里做度量）。公路的总长不超过1000000英里。每一城市日啤酒需求量不大于1000件。
</p>
<p>
	输出
</p>
<p>
	你的程序将在文件的第一行且只在这一行写入一整数，此整数应为日运输费用的最小值。
</p>
<p>
	样例输入
</p>
<pre>6
1 2
2 3
1 2
5 2
1 10
2 3
</pre>
<p>
	样例输出
</p>
<pre>41
</pre>
