# 题目描述


<p>
【题目描述】
</p>
<p>
<br/>
</p>
<p>
无限循环数字串S由长度为n的循环节s构成。设s为12345(n=5)，则数字串S为123451234512345…
</p>
<p>
设Si为S的第i位数字，在上面的例子中，S1=1，S2=2，S6=1。
</p>
<p>
设S的一个子串S[l,r]的交错和为sum(l,r)：
</p>
<p>
sum(l,r) = Sl - S1+1 + Sl+2 - Sl+3 + … + (-1)r-lSr
</p>
<p>
如sum(2,7) = 2 - 3 + 4 - 5 + 1 - 2 = -3
</p>
<p>
<br/>
</p>
<p>
现给定循环节s，要求支持两种操作：
</p>
<p>
1 pos digit：
</p>
<p>
修改循环节s上的某一位，即将spos改为digit。
</p>
<p>
2 l r：
</p>
<p>
求S[l,r]内所有子串的交错和的和，即
</p>
<p>
<br/>
</p>
<p>
输出ans对109+7的模。
</p>
<p>
<br/>
</p>
<p>
【输入格式】
</p>
<p>
<br/>
</p>
<p>
第一行一个整数n，表示循环节s的长度。
</p>
<p>
第二行一个长度为n的数字串，表示循环节s。
</p>
<p>
第三行一个整数m，表示操作次数。
</p>
<p>
以下m行，每行3个整数。
</p>
<p>
若第一个数为1，表示是修改操作1 pos digit。
</p>
<p>
若第一个数为2，表示是询问操作2 l r。
</p>
<p>
<br/>
</p>
<p>
【输出格式】
</p>
<p>
<br/>
</p>
<p>
对于每个询问操作输出一行，表示答案。
</p>
<p>
<br/>
</p>
<p>
【样例输入】
</p>
<p>
5
</p>
<p>
12345
</p>
<p>
5
</p>
<p>
2 1 5
</p>
<p>
2 6 10
</p>
<p>
1 3 5
</p>
<p>
2 1 5
</p>
<p>
2 1 6
</p>
<p>
【样例输出】
</p>
<p>
19
</p>
<p>
19
</p>
<p>
25
</p>
<p>
36
</p>
<p>
【数据范围】
</p>
<p>
<br/>
</p>
<p>
对于10%的数据点，n, m &lt;= 50；
</p>
<p>
对于20%的数据点，n, m &lt;= 1000；
</p>
<p>
对于40%的数据点，1 &lt;= l &lt;= r &lt;= n；
</p>
<p>
对于100%的数据点，n, m &lt;= 200000；1 &lt;= l &lt;= r &lt;= 1018；1 &lt;= pos &lt;= n；0 &lt;= digit &lt;= 9；
</p>