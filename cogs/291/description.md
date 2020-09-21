# 题目描述


<p>
	【问题描述】
</p>
<p>
	Z 国坐落于遥远而又神奇的东方半岛上，在小Z 的统治时代公路成为这里主要的交通手段。Z 国共有n 座城市，一些城市之间由双向的公路所连接。非常神奇的是Z 国的每个城市所处的经度都不相同，并且最多只和一个位于它东边的城市直接通过公路相连。Z 国的首都是Z 国政治经济文化旅游的中心，每天都有成千上万的人从Z 国的其他城市涌向首都。
</p>
<p>
	为了使Z 国的交通更加便利顺畅，小Z 决定在Z 国的公路系统中确定若干条规划路线，将其中的公路全部改建为铁路。
</p>
<p>
	我们定义每条规划路线为一个长度大于1 的城市序列，每个城市在该序列中最多出现一次，序列中相邻的城市之间由公路直接相连(待改建为铁路)。并且，每个城市最多只能出现在一条规划路线中，也就是说，任意两条规划路线不能有公共部分。
</p>
<p>
	当然在一般情况下是不可能将所有的公路修建为铁路的，因此从有些城市出发去往首都依然需要通过乘坐长途汽车，而长途汽车只往返于公路连接的相邻的城市之间，因此从某个城市出发可能需要不断地换乘长途汽车和火车才能到达首都。
</p>
<p>
	我们定义一个城市的“不便利值”为从它出发到首都需要乘坐的长途汽车的次数，而Z 国的交通系统的“不便利值”为所有城市的不便利值的最大值，很明显首都的“不便利值”为0。小Z 想知道如何确定规划路线修建铁路使得Z 国的交通系统的“不便利值”最小，以及有多少种不同的规划路线的选择方案使得“不便利值”达到最小。当然方案总数可能非常大，小Z 只关心这个天文数字mod Q 后的值。
</p>
<p>
	注意：规划路线1-2-3 和规划路线3-2-1 是等价的，即将一条规划路线翻转依然认为是等价的。两个方案不同当且仅当其中一个方案中存在一条规划路线不属于另一个方案。
</p>
<p>
	【输入格式】
</p>
<p>
	输入文件第一行包含三个正整数N、M、Q，其中N 表示城市个数，M 表示公路总数，N 个城市从1~N 编号，其中编号为1 的是首都。Q 表示上文提到的设计路线的方法总数的模数。接下来M 行，每行两个不同的正数ai、bi (1≤ ai , bi ≤ N)表示有一条公路连接城市ai 和城市bi。 输入数据保证一条公路只出现一次。
</p>
<p>
	【输出格式】
</p>
<p>
	输出文件应包含两行。第一行为一个整数，表示最小的“不便利值”。 第二行为一个整数，表示使“不便利值”达到最小时不同的设计路线的方法总数 mod Q 的值。<br/>
如果某个城市无法到达首都，则输出两行-1。
</p>
<p>
	【输入样例】
</p>
<p>
	5 4 100<br/>
1 2<br/>
4 5<br/>
1 3<br/>
4 1
</p>
<p>
	<br/>
【输出样例】<br/>
1<br/>
10
</p>
<p>
	<br/>
【样例说明】<br/>
以下样例中是10 种设计路线的方法：<br/>
(1) 4-5<br/>
(2) 1-4-5<br/>
(3) 4-5, 1-2<br/>
(4) 4-5, 1-3<br/>
(5) 4-5, 2-1-3<br/>
(6) 2-1-4-5<br/>
(7) 3-1-4-5<br/>
(8) 1-4<br/>
(9) 2-1-4<br/>
(10) 3-1-4
</p>
<p>
	<br/>
【数据规模和约定】<br/>
对于20%的数据，满足N,M ≤ 10。<br/>
对于50%的数据，满足N,M ≤ 200。<br/>
对于60%的数据，满足N,M ≤ 5000。<br/>
对于100%的数据，满足1 ≤ N,M ≤ 100000，1 ≤ Q ≤ 120000000。
</p>