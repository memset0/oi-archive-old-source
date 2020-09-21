# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
Bessie在为即将来临的汽车大赛准备赛车，它想购买一些附加装备来增强赛车的性能。赛车当前的质量为M(1≤M≤1，000)，具有F (1≤F≤1,000，000)大小的动力。商店里有N(1≤N≤10，000)个装备，编号1…N。Bessie可以随便购买多少个装备，但每个装备只能买一件。
</p>
<p>
装备P_i可以增加F_i (1≤F_i≤1,000，000)的动力，但同时也增加了M_i(1≤M_i≤1,000)的质量。牛顿第二定律说：F=MA，F是力，M是质量，A是加速度。如果Bessie希望赛车的加速度最大(否则的话希望赛车的质量最轻)，那么它应当购买多少附加装备呢?
</p>
<p>
例如，一辆赛车的初始值为F=1500，M=100，有4种附加装备：
</p>
<p>
i F_i M_i
</p>
<p>
1 250 25
</p>
<p>
2 150 9
</p>
<p>
3 120 5
</p>
<p>
4 200 8
</p>
<p>
如果只购买装备2，加速度为：(1500+150)/(100+9)=165/109=15.13761。
</p>
<p>
下表列出了购买装备的各种组合情况，在第1列中，1表示要买，0表示不买。
</p>
<p>
Parts Aggregate Aggregate
</p>
<p>
1234 F M F/M
</p>
<p>
0000 1500 100 15.0000
</p>
<p>
0001 1700 108 15.7407
</p>
<p>
0010 1620 105 15.4286
</p>
<p>
001 1 1820 113 16.1062
</p>
<p>
0100 1650 109 15.1376
</p>
<p>
0101 1850 117 15.8120
</p>
<p>
0110 1770 114 15.5263
</p>
<p>
011 1 1970 122 16.1475&lt;-最大的F/M
</p>
<p>
1000 1750 125 14.0000
</p>
<p>
1001 1950 133 14.6617
</p>
<p>
1010 1870 130 14.3846
</p>
<p>
1011 2070 138 15.0000
</p>
<p>
1100 1900 134 14.179l
</p>
<p>
1101 2100 142 14.7887
</p>
<p>
1110 2020 139 14.5324
</p>
<p>
1111 2220 147 15.1020
</p>
<p>
因此，最佳的购买方案是2，3，4。
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
第1行：3个整数F，M，N
</p>
<p>
第2…N+I行：第i+l行包含2个整数F_i和M_i
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
若干行，每行输出一个要购买的装备的编号，以升序输出。如果不需要购买，则输出&#39;NONE&#39;(不要引号)。
</p>
<p>
数据保证答案唯一。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>1500 100 4
250 25
150 9
120 5
200 8</pre>
<h3>
【样例输出】
</h3>
<pre>2
3
4</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>