# 题目描述


<h3>
【题目描述】
</h3>
<p>
Farmer John有N头奶牛（2&lt;=N&lt;=20），其中第i头牛每天能生产M(i)个单位的牛奶（1&lt;=M(i)&lt;=100000000）。FJ希望简化每天挤奶的过程，因此他在谷仓里装了一台崭新的挤奶机。不幸的是，他发现这台机器非常敏感：只有当谷仓左右两侧的奶牛产奶数量完全相等时，它才能正常工作！
</p>
<p>
我们称所有奶牛的一个子集是“平衡的”，如果它能被分成产奶数量完全相等的两组。因为只有一个平衡的奶牛子集才能让挤奶机工作，FJ希望知道在他的N头奶牛中有多少个子集是平衡的。请你帮助他计算出这个数目。
</p>
<h3>
【输入格式】
</h3>
<p>
第1行：一个整数N。
</p>
<p>
第2到N+1行：第i+1行包含M(i)。
</p>
<h3>
【输出格式】
</h3>
<p>
第1行：平衡子集的数量。
</p>
<h3>
【输入样例】
</h3>
<p>
4
</p>
<p>
1
</p>
<p>
2
</p>
<p>
3
</p>
<p>
4
</p>
<h3>
【输出样例】
</h3>
<p>
3
</p>
<h3>
【提示】
</h3>
<p>
有4头奶牛，产奶数量为1,2,3,4.
</p>
<p>
有三个平衡子集：{1,2,3}，可以被分成{1,2}和{3}；{1,3,4}可以被分成{1,3}和{4}；{1,2,3,4}可以被分成{1,4}和{2,3}。
</p>
<h3>
【来源】
</h3>
<p>
USACO 2012 US Open, Gold Division, Balanced Cow Subsets
</p>