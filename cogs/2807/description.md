# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
lc出去浪,发现了一大堆钻石,可是钻石在有规律地消失,lc想知道最后剩下钻石的价值。
</p>
<p>
给出p-1堆钻石,第i堆钻石含有i+1个不同的钻石.第i堆钻石有1/(i*(i+1))的概率不消失,每个钻石不消失的概率为1/2,.第i堆每个钻石权值为2^(i+1),求最后获得价值的期望。
</p>
<p>
lc很认真所以,他想知道精确答案,即在膜(orz lc)p意义下的结果。而且他经常去浪,所以会有多组数据。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
第一行包含一个整数T，表示数据组数。接下来T组数据。
</p>
<p>
每组数据只有一行一个数,表示p。
</p>
<h3>
【输出格式】
</h3>
<p>
共T行,每行输出在模p意义下的期望。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
3
</p>

<p>
3
</p>

<p>
5
</p>

<p>
7<span style="font-family:monospace;"></span> 
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
1
</p>

<p>
4
</p>

<p>
3
</p>
</pre>
<h3>
【数据范围与约定】
</h3>
<p>
p为奇素数,且p&lt;=4e7。
</p>
<h3>
【来源】
</h3>
<p>
HZOI 2017
</p>