# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
  在研究过指向标之后，B先生知道外星人住在一个闪烁的星月系统中，于是他决定拜访那颗星球。虽然科学家们还没有发现这颗星球，不过B先生已经知道星球每隔T秒闪烁一次。
</p>
<p>
  有n个天文学家从1到n编号。他们试着通过每秒钟向宇宙发送请求来检测星球。
</p>
<p>
  天文学家们循环轮流发送请求：第i个天文学家在第i-1个天文学家发送请求ai秒后才发送自己的请求，第一个天文学家在第n个天文学家发送请求a1 秒后发送自己的请求，第一个天文学家在第0时刻发出他的第一个请求。
</p>
<p>
  由于星球在首次观测之后的T秒内的哪一秒出现是不确定的，若星球在[i, i+1)时闪烁（0&lt;=i&lt;T-1），且天文学家j是首次观测到星球，则称j抢占了[i,i+1)的时间片段。
</p>
<p>
  输出每个天文学家所抢占的时间片段数。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
共一行输入T和n， (1 ≤ T ≤ 10^9, 2 ≤ n ≤ 2·10^5).
</p>
<h3>
【输出格式】
</h3>
<p>
共一行，输出每个天文学家所抢占的时间片段数。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
4 2
</p>

<p>
2 3
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre> 3 1 </pre>
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
http://codeforces.com/contest/819/problem/D
</p>
