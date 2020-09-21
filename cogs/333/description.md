# 题目描述


<h3>
【问题描述】
</h3>
<p>
克里特岛以野人群居而著称。岛上有排列成环行的 $M$ 个山洞。这些山洞顺时针编号为 $1,2,\dots,M$。岛上住着 $N$ 个野人，一开始依次住在山洞 $C_1,C_2,\dots,C_N$ 中，以后每年，第 $i$ 个野人会沿顺时针向前走 $P_i$ 个洞住下来。每个野人 $i$ 有一个寿命值 $L_i$，即生存的年数。下面四幅图描述了一个有 $6$ 个山洞，住有三个野人的岛上前四年的情况。三个野人初始的洞穴编号依次为 $1,2,3$；每年要走过的洞穴数依次为 $3,7,2$；寿命值依次为 $4,3,1$。
</p>
<p>
<span><img alt="Image:Savage1.gif" src="../../mw/images/8/87/Savage1.gif" height="138" width="246"/></span> <img alt="Image:Savage2.gif" src="../../mw/images/e/e8/Savage2.gif" height="103" width="238"/> 
</p>
<p>
<img alt="Image:Savage3.gif" src="../../../../mw/images/4/45/Savage3.gif" height="131" width="230"/> <img alt="Image:Savage4.gif" src="../../mw/images/2/21/Savage4.gif" height="110" width="238"/> 
</p>
<p>
奇怪的是，虽然野人有很多，但没有任何两个野人在有生之年处在同一个山洞中，使得小岛一直保持和平与宁静，这让科学家们很是惊奇。他们想知道，至少有多少个山洞，才能维持岛上的和平呢？
</p>
<h3>
【输入文件】
</h3>
<p>
输入文件的第 $1$ 行为一个整数 $N(1\le N\le 15)$，即野人的数目。第 $2$ 行到第 $N+1$ 每行为三个整数 $C_i, P_i, L_i(1\le C_i,P_i\le 100,0\le Li\le 10^6)$，表示每个野人所住的初始洞穴编号，每年走过的洞穴数及寿命值。
</p>
<h3>
【输出文件】
</h3>
<p>
输出文件仅包含一个数 $M$，即最少可能的山洞数。输入数据保证有解，且 $M$ 不大于 $10^6$。
</p>
<h3>
【样例输入】
</h3>
<pre>3
1 3 4
2 7 3
3 2 1
</pre>
<h3>
【样例输出】
</h3>
<pre>6
</pre>
<h3>
【样例说明】
</h3>
<p>
该样例对应于题目描述中的例子。
</p>