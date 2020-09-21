# 题目描述


<h3>
【题目描述】
</h3>
<p>
fibonotci序列定义为下：
</p>
<p>
F[n]=s[n-1]F[n-1]+s[n-2]F[n-2] (n&gt;=2)
</p>
<p>
F[0]=0,F[1]=1
</p>
<p>
其中s是一个循环长度为n的循环数组，即满足s[i]=s[i % n]。
</p>
<p>
不过，s这个数组被熊孩子修改了几个位置，他把s中的第j个位置修
</p>
<p>
改为了vj，也就是说，对于位置j，s[j]=v[j](j&gt;=n)。
</p>
<p>
请你在熊孩子修改之后，求出F[k]对P取模的结果。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个整数k，P。
</p>
<p>
接下来一行一个整数n，接下来一行n个整数，表示s[i]。
</p>
<p>
再接下来一行一个整数m，表示熊孩子的修改。
</p>
<p>
接下来m行，每行两个整数j，v[j]，表示熊孩子做的修改，除修改位
</p>
<p>
置之外的位置i，满足，s[i]=s[i%n](i&gt;=n)
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个整数，表示答案
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
10 8
</p>
<p>
3
</p>
<p>
1 2 1
</p>
<p>
2
</p>
<p>
7 3
</p>
<p>
5 4
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
 4
</p>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
对于20%的数据，m=0
</p>
<p>
对于50%的数据，k&lt;=10^6
</p>
<p>
对于100%的数据，n,m&lt;=50000,0&lt;=K&lt;=10^18,1&lt;=P&lt;=10^9,
</p>
<p>
1&lt;=s[i],v[j]&lt;=10^9,n&lt;=j&lt;=10^18，数据保证j互不相同
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
Codeforces 575 A
</p>