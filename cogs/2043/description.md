# 题目描述


<img src="/upload/image/20151105/20151105160227_59088.jpg" alt=""/>
<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
有n只猴子，第一只尾巴挂在树上，剩下的n-1只，要么被其他的猴子抓住，要么抓住了其他的猴子，要么两者均有。当然一只猴子最多抓两只另外的猴子，因为只有两只猴爪子嘛。现在给出这n只猴子抓与被抓的信息，并且在某个时刻可能某只猴子会放掉它左手或右手的猴子，导致某些猴子落在地上。求每只猴子落地的时间。
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
第一行两个n,m，表示有n只猴子，并且总时间为m-1.
</p>
<p>
接下来n行，描述了每只猴子的信息，每行两个数，分别表示这只猴子左手和右手抓的猴子的编号，如果是-1，表示该猴子的那只手没抓其他的猴子。
</p>
<p>
再接下来M行，按时间顺序给出了一些猴子放手的信息，第1+n+i行表示i-1时刻某只猴子的放手信息，信息以两个数给出，前者表示放手的猴子的编号，后者表示其放的是哪只手，1左2右。
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
共输出n行，第i行表示第i只猴子掉落的时刻，若第i只猴子道M-1时刻以后还没掉落，就输出-1。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
3 2
</p>

<p>
-1 3
</p>

<p>
3 -1
</p>

<p>
1 2
</p>

<p>
1 2
</p>

<p>
3 1
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
-1
</p>

<p>
1
</p>

<p>
1
</p>
</pre>
<h3>
【提示】
</h3>
<p>
n&lt;=200000,m&lt;=400000
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>