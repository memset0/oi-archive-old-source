# 题目描述


<title>
Problem 4105. -- [Thu Summer Camp 2015]平方运算
</title>
<h2>
Description
</h2>
<div class="content">
<p>
现有一个长度为N的序列{X1,X2,...,XN}，要求支持两种操作：
</p>
<div>
</div>
<div>
1. 0 l r  表示将[l, r]范围内的$X_i$变为${X_i}^2 \mod p $.<br/>
</div>
<div>
2. 1 l r  询问$\sum_{i = l}^r X_i$.<br/>
</div>
<div>
</div>
</div>
<h2>
Input
</h2>
<div class="content">
<p>
第一行有三个整数N，M，p，分别代表序列的长度、平方操作与询问操作的总次数以及在平方操作中所要模的数。
</p>
<div>
</div>
<div>
接下来一行N个数代表一开始的序列{X1,X2,...,XN}。
</div>
<div>
</div>
<div>
接下来M行，每行三个整数op,l,r。其中op代表本次操作的类型。若op=0，代表这是一次平方操作，平方的区间为[l,r]；如果op=1，代表这是一次询问操作，询问的区间为[l,r]。
</div>
<div>
</div>
</div>
<h2>
Output
</h2>
<div class="content">
<p>
对于每次的询问操作，输出一行代表这段区间内数的总和。注意：答案没有对任何数取模。
</p>
<div>
</div>
</div>
<h2>
Sample Input
</h2>
<div class="content">
<span class="sampledata">3 3 11<br/>
1 2 3<br/>
1 1 3<br/>
0 1 3<br/>
1 1 3</span> 
</div>
<h2>
Sample Output
</h2>
<div class="content">
<span class="sampledata">6<br/>
14</span> 
</div>
<h2>
HINT
</h2>
<div class="content">
<p>
<br/>
</p>
<p>
 对于100%的数据，∀i,Xi∈[0,p),l,r∈[1,n]
</p>
<br/>
<div>
N，M，p的范围如下：
</div>
<br/>
<div>
</div>
<br/>
<div>
编号<span class="Apple-tab-span" style="white-space:pre;"> </span> N<span class="Apple-tab-span" style="white-space:pre;"> </span> M<span class="Apple-tab-span" style="white-space:pre;"> </span> p
</div>
<br/>
<div>
1<span class="Apple-tab-span" style="white-space:pre;"> </span> 1000<span class="Apple-tab-span" style="white-space:pre;"> </span> 1000<span class="Apple-tab-span" style="white-space:pre;"> </span> 233
</div>
<br/>
<div>
2<span class="Apple-tab-span" style="white-space:pre;"> </span> 1000<span class="Apple-tab-span" style="white-space:pre;"> </span> 1000<span class="Apple-tab-span" style="white-space:pre;"> </span> 2332
</div>
<br/>
<div>
3<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 5
</div>
<br/>
<div>
4<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 8192
</div>
<br/>
<div>
5<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 23
</div>
<br/>
<div>
6<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 45
</div>
<br/>
<div>
7<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 37
</div>
<br/>
<div>
8<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 4185
</div>
<br/>
<div>
9<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 5850
</div>
<br/>
<div>
10<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 2975
</div>
<br/>
<div>
11<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 2542
</div>
<br/>
<div>
12<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 55000<span class="Apple-tab-span" style="white-space:pre;"> </span> 2015
</div>
<br/>
<div>
13<span class="Apple-tab-span" style="white-space:pre;"> </span> 60000<span class="Apple-tab-span" style="white-space:pre;"> </span> 60000<span class="Apple-tab-span" style="white-space:pre;"> </span> 2003
</div>
<br/>
<div>
14<span class="Apple-tab-span" style="white-space:pre;"> </span> 65000<span class="Apple-tab-span" style="white-space:pre;"> </span> 65000<span class="Apple-tab-span" style="white-space:pre;"> </span> 2010
</div>
<br/>
<div>
15<span class="Apple-tab-span" style="white-space:pre;"> </span> 70000<span class="Apple-tab-span" style="white-space:pre;"> </span> 70000<span class="Apple-tab-span" style="white-space:pre;"> </span> 4593
</div>
<br/>
<div>
16<span class="Apple-tab-span" style="white-space:pre;"> </span> 75000<span class="Apple-tab-span" style="white-space:pre;"> </span> 75000<span class="Apple-tab-span" style="white-space:pre;"> </span> 4562
</div>
<br/>
<div>
17<span class="Apple-tab-span" style="white-space:pre;"> </span> 80000<span class="Apple-tab-span" style="white-space:pre;"> </span> 80000<span class="Apple-tab-span" style="white-space:pre;"> </span> 1034
</div>
<br/>
<div>
18<span class="Apple-tab-span" style="white-space:pre;"> </span> 85000<span class="Apple-tab-span" style="white-space:pre;"> </span> 85000<span class="Apple-tab-span" style="white-space:pre;"> </span> 5831
</div>
<br/>
<div>
19<span class="Apple-tab-span" style="white-space:pre;"> </span> 90000<span class="Apple-tab-span" style="white-space:pre;"> </span> 90000<span class="Apple-tab-span" style="white-space:pre;"> </span> 9905
</div>
<br/>
<div>
20<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 100000<span class="Apple-tab-span" style="white-space:pre;"> </span> 9977
</div>
<p>
<br/>
</p>
</div>
