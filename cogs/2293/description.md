# 题目描述


<h3>
【题目描述】
</h3>
<p>
题目自然和香蕉是一样的，不过数据有所加强
</p>
<p>
做法和原来的香蕉有所不同，所以称为EX_香蕉
</p>
<p>
<br/>
</p>
<p>
以下是题面：
</p>
<p>
HZOI从HZ的级部拿到了无数的香蕉
</p>
<p>
不过由于HZOI的人数太多了，分配香蕉成了巨大的问题
</p>
<p>
现在HZOI的人坐成一排，你要负责给他们分香蕉
</p>
<p>
每个人最少要拿一个香蕉，最多拿m个香蕉
</p>
<p>
同时为了避免发生争吵
</p>
<p>
设第i个人拿到的香蕉为A，则第i+1个拿到的香蕉数量B要满足A&lt;=B或者满足A%B&gt;0
</p>
<p>
注意香蕉总数是无限的
</p>
<p>
现在给定你HZOI的人数和m，求你有多少种不同的分配方案
</p>
<p>
如果两个分配方案存在某个人拿到的香蕉数量不同，则视为不同的方案
</p>
<p>
由于方案数可能很大，所以要求你输出方案数模998244353后的值
</p>
<h3>
【输入格式】
</h3>
<p>
第一行输入m表示限制
</p>
<p>
第二行输入T，表示有T组询问
</p>
<p>
以下T行，每行一个n表示HZOI的人数
</p>
<p>
T&lt;=50,m&lt;=1000000,n&lt;=20亿
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个询问输出对应的答案
</p>
<h3>
【样例输入】
</h3>
<p>
2
</p>
<p>
1
</p>
<p>
2
</p>
<h3>
【样例输出】
</h3>
<p>
3
</p>
<p>
<br/>
</p>
<p>
UPD：为了防止成为辣鸡卡常出题人，时限有所放宽
</p>