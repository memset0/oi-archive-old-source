# 题目描述


<p>
	【问题描述】
</p>
<p>
	一条街的一边有几座房子.因为环保原因居民想要在路边种些树.路边的地区被分割成 块,并被编号成1..N.每个部分为一个单位尺寸大小并最多可种一棵树.每个居民想在门 前种些树并指定了三个号码B,E,T.这三个数表示该居民想在B和E之间最少种T棵树.当 然,B≤E,居民必须记住在指定区不能种多于区域地块数的树,所以T≤E-B+l.居民们想 种树的各自区域可以交叉.你的任务是求出能满足所有要求的最少的树的数量.
</p>
<p>
	【输入】
</p>
<p>
	第一行包含数据N,表示区域的个数;
</p>
<p>
	第二行包含H,表示房子的数目;
</p>
<p>
	下面的H行描述居民们的需要:b e t(1&lt;=b&lt;=e&lt;=30000,t&lt;=e-b+1);
</p>
<p>
	【输出】
</p>
<p>
	输出文件仅有一行，写有树的数目。
</p>
<p>
	【样例输入】
</p>
<p>
	trees.in
</p>
<p>
	9<br/>
4<br/>
1 4 2<br/>
4 6 2<br/>
8 9 2<br/>
3 5 2
</p>
<p>
	【样例输出】
</p>
<p>
	trees.out
</p>
<p>
	5
</p>
<p>
	 【数据规模】
</p>
<p>
	<br/>
</p>
<div>
	<div>
		30%的数据满足0&lt;n&lt;=1000,0&lt;h&lt;=500；
	</div>
</div>
<p>
	<br/>
</p>
<p>
	100%的数据满足n&lt;=30000,h&lt;=5000。
</p>