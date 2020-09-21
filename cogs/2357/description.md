# 题目描述


<h3>
【题目描述】
</h3>
<p>
QAQ喜欢玩序列
</p>
<p>
现在他有一个长度为$n$的序列a
</p>
<p>
之后他有$m$个询问
</p>
<p>
每次他想知道在区间$[L,R]$中恰好出现$k$次的数有多少个
</p>
<p>
因为QAQ觉得这个题目太简单，所以他决定强制在线
</p>
<h3>
【输入格式】
</h3>
<p>
第一行输入$n$，如题意所示
</p>
<p>
之后有$n$个正整数，表示a序列
</p>
<p>
之后输入$m$，如题意所示
</p>
<p>
以下每行一个询问$L，R，k$,含义如题意所示
</p>
<p>
输入的$L，R$进行了加密，设上次询问的答案为$ans$(第一次询问时$ans=0$）
</p>
<p>
则$L=(L+ans)\mod n+1，R=(R+ans)\mod n+1$
</p>
<p>
如果$L&gt;R$,就交换$L$和$R$
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
3
</p>
<p>
1 1 2
</p>
<p>
3
</p>
<p>
1 2 2
</p>
<p>
1 2 1
</p>
<p>
1 3 1
</p>
<h3>
【样例输出】
</h3>
<p>
0
</p>
<p>
2
</p>
<p>
1
</p>
<h3>
【提示】
</h3>
<p>
样例解释：注意题目中的输入是加密的QAQ
</p>
<p>
对于100%的数据,$n=100000,a_i&lt;=10^9$
</p>