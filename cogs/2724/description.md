# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
“低价购买”这条建议是在奶牛股票市场取得成功的一半规则。要想被认为是伟大的投资者，你必须遵循以下的问题建议:“低价购买；再低价购买”。每次你购买一支股票,你必须用低于你上次购买它的价格购买它。买的次数越多越好!你的目标是在遵循以上建议的前提下，求你最多能购买股票的次数。你将被给出一段时间内一支股票每天的出售价(2^16范围内的正整数)，你可以选择在哪些天购买这支股票。每次购买都必须遵循“低价购买；再低价购买”的原则。写一个程序计算最大购买次数。
</p>
<p>
这里是某支股票的价格清单：
</p>
<p>
日期  1  2  3  4  5  6  7  8  9 10 11 12
</p>
<p>
价格 68 69 54 64 68 64 70 67 78 62 98 87
</p>
<p>
最优秀的投资者可以购买最多4次股票，可行方案中的一种是：
</p>
<p>
日期    2  5  6 10
</p>
<p>
价格   69 68 64 62
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
第1行: N (1 &lt;= N &lt;= 5000)，股票发行天数
</p>
<p>
第2行: N个数，是每天的股票价格。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件仅一行包含两个数:最大购买次数和拥有最大购买次数的方案数(&lt;=2^31)当二种方案“看起来一样”时（就是说它们构成的价格队列一样的时候）,这2种方案被认为是相同的。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
12
</p>

<p>
68 69 54 64 68 64 70 67 78 62 98 87
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>4 2</pre>
<h3>
【提示】
</h3>
<p>
数据可能比较水,我只是把题搬过来,然后造一些比较坑的数据.有兴趣的同学可以自己造些加强版的数据,然后用我的代码验证一下.
</p>
<h3>
【来源】
</h3>
<p>
洛谷p1108
</p>