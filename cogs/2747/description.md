# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
在回家的路上，凯伦决定停在超市买些杂货。
</p>
<p>
她需要买很多商品，但由于她是学生，她的预算还是相当有限的。其实她只能花最高b美元。
</p>
<p>
超市里有n种商品，第i种商品价格为c[i]美元。当然，每种商品只能买一次。最近，超市一直在努力增加业务，作为忠实客户的凯伦，获得了n张优惠券，如果凯伦买了第i件商品，她可以用第i张优惠券来降低d[i]的价格。当然，如果不买相应的商品就无法使用优惠券。
</p>
<p>
然而，优惠券有一定限制：对于所有i≥2，为了使用第i张优惠券，凯伦也必须使用第xi张优惠券（这可能意味着使用更多的优惠券来满足该优惠券的要求）。凯伦想知道，用她的钱最多可以买多少商品。
</p>
<p>
<br/>
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
第一行输入包含两个整数n和b（1≤n≤5000,1≤b≤10^9），商店中的货物数量和凯伦的钱数。
</p>
<p>
接下来的n行描述以下项：
</p>
<p>
其中第i行开始是两个整数分别为次c[i]和d[i](1&lt;=d[i]&lt;c[i]&lt;=10^9)，表示第i个商品的价钱和用第i张优惠券买这个商品可以减少的价钱，如果i&gt;=2，接下来是另一个整数x[i](1&lt;=x[i]&lt;i)，表示第x[i]张优惠券应该先被使用。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行，一个整数，即凯伦能买到的最大的商品数。
</p>
<h3>
【样例1】
</h3>
<pre><p>
input
</p>

<p>
6 16
</p>

<p>
10 9
</p>

<p>
10 5 1
</p>

<p>
12 2 1
</p>

<p>
20 18 3
</p>

<p>
10 2 3
</p>

<p>
2 1 5
</p>

<p>
output
</p>

<p>
4
</p>
</pre>
<h3>
【样例2】
</h3>
<pre><p>
input
</p>

<p>
5 10
</p>

<p>
3 1
</p>

<p>
3 1 1
</p>

<p>
3 1 2
</p>

<p>
3 1 3
</p>

<p>
3 1 4
</p>

<p>
output
</p>

<p>
5
</p>
</pre>
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
