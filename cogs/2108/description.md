# 题目描述


<h3>
【题目描述】
</h3>
<p>
有两个仅包含小写英文字母的字符串 A 和 B。现在要从字符串 A 中取出 k 个互不重叠的非空子串，然后把这 k 个子串按照其在字符串 A 中出现的顺序依次连接起来得到一个新的字符串，请问有多少种方案可以使得这个新串与字符串 B 相等？注意：子串取出的位置不同也认为是不同的方案。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行是三个正整数 n,m,k，分别表示字符串 A 的长度，字符串 B 的长度，以及问题描述中所提到的 k，每两个整数之间用一个空格隔开。 第二行包含一个长度为 n 的字符串，表示字符串 A。 第三行包含一个长度为 m 的字符串，表示字符串 B。
</p>
<h3>
【输出格式】
</h3>
<p>
输出共一行，包含一个整数，表示所求方案数。由于答案可能很大，所以这里要求输出答案对 1,000,000,007 取模的结果。
</p>
<h3>
【样例输入1】
</h3>
<pre>6 3 1 
aabaab 
aab</pre>
<h3>
【样例输出1】
</h3>
<pre>2</pre>
<h3>
【样例输入2】
</h3>
<pre>6 3 2 
aabaab 
aab</pre>
<h3>
【样例输出2】
</h3>
<pre>7</pre>
<h3>
【样例输入3】
</h3>
<pre>6 3 3 
aabaab 
aab</pre>
<h3>
【样例输出1】
</h3>
<pre>7</pre>
<h3>
【提示】
</h3>
<p>
<img src="/upload/image/20151109/20151109134841_28363.jpg" alt=""/> 
</p>
<p>
对于第 1 组数据:1≤n≤500,1≤m≤50,k=1;
</p>
<p>
对于第 2 组至第 3 组数据:1≤n≤500,1≤m≤50,k=2;
</p>
<p>
对于第 4 组至第 5 组数据:1≤n≤500,1≤m≤50,k=m;
</p>
<p>
对于第 1 组至第 7 组数据:1≤n≤500,1≤m≤50,1≤k≤m;
</p>
<p>
对于第 1 组至第 9 组数据:1≤n≤1000,1≤m≤100,1≤k≤m;
</p>
<p>
对于所有 10 组数据:1≤n≤1000,1≤m≤200,1≤k≤m。
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>