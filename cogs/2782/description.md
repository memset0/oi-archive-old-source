# 题目描述


<h3>
【题目描述】
</h3>
<p>
给出n个点(xi,yi)，满足对于任意的i,j满足1&lt;=i,j&lt;=n,当xi=xj时必有yi=yj。求出一个次数不超过n-1的多项式，使得对于任意的i满足1&lt;=i&lt;=n，有f(xi)=yi。现在请你求出多项式f(x)。
</p>
<p>
为了防止精度误差，本题在模998244353意义下求解(=119&lt;&lt;23|1，是一个质数，原根是3)
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数n。
</p>
<p>
接下来n行，每行两个整数xi,yi。数据保证0&lt;=xi,yi&lt;998244353
</p>
<h3>
【输出格式】
</h3>
<p>
一行n个整数，分别对应多项式f(x)中x^0到x^(n-1)的系数。
</p>
<h3>
【样例输入】
</h3>
<pre>4
1 1
2 5
3 14
4 30
</pre>
<h3>
【样例输出】
</h3>
<pre>0 166374059 499122177 332748118  </pre>
<h3>
【数据范围】
</h3>
<p>
对于50%的数据，n&lt;=500
</p>
<p>
对于100%的数据，n&lt;=5000
</p>
<h3>
【提示】
</h3>
<p>
又是垃圾Mike出的多项式题。
</p>
<p>
我猜快速插值跑不过牛顿插值……求神犇光速打脸，我用的是牛顿插值。
</p>
<p>
upd:被自己O(n(logn)^3)的垃圾插值打脸了……
</p>