# 题目描述


<p>
【题目描述】
</p>
<p>
现在给你一些连续的整数，它们是从 A 到 B 的整数。一开始每个整数都属于各自的集合，然后你需要进行如下操作：
</p>
<p>
每次选择两个属于不同集合的整数，如果这两个整数拥有大于等于 P 的公共质因子，那么把他们所在的集合合并。
</p>
<p>
反复上述操作，直到没有可以合并的集合为止。
</p>
<p>
现在，小 X 想知道，最后有多少个集合。
</p>
<p>
【输入格式】
</p>
<p>
一行，三个整数 A,B,P
</p>
<p>
【输出格式】
</p>
<p>
一个数，表示最终集合的个数。
</p>
<p>
【输入样例】
</p>
<p>
10 20 3
</p>
<p>
【输出样例】
</p>
<p>
7
</p>
<p>
解释： {10 ， 20 ， 12 ， 15 ， 18} ， {11}，{13} ， {14} ， {16} ， {17} ， {19}
</p>
<p>
【数据规模】
</p>
<p>
A&lt;=B&lt;=100000; 2&lt;=P&lt;=B
</p>
<p>
80% B&lt;=1000.
</p>
