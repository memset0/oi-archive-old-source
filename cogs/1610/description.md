# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
如果存在一个数列C满足下列条件，我们就认为字符串A为字符串B的一个子序列：
</p>
<p>
(1)数列C恰好有length(A)个数；
</p>
<p>
(2)0&lt;=C[0]&lt;C[1]&lt;...&lt;C[length(A)-1]&lt;length(B)；
</p>
<p>
(3)对于每一个i,有A[i]=B[C[i]]（0&lt;=i&lt;length(A)）。
</p>
<p>
举个例子，&#34;abcd&#34;是&#34;aaaaaabbbcd&#34;的子序列，而&#34;abcd&#34;不是&#34;aaaaacccdb&#34;的子序列，当然了，任意一个字符串都是它本身的一个子序列。
</p>
<p>
在本题中，给你一个较长的字符串A，和许多较短的字符串Bi，你需要写一个效率比较高的程序告诉我们Bi是否为A的子序列。
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
输入文件的第一行为字符串A，第二行有一个整数M(0&lt;M&lt;=10000)，表示短字符串Bi的个数，接下来有M行，每行有一个字符串Bi。
</p>
<p>
字符串A的长度不超过100000，Bi的长度不超过50，所有的字符串都至少有一个字母，所有的字母均为小写。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出有M行，每行含义为：对于每一个Bi，如果它是A的子序列则输出&#34;Yes&#34;，否则输出&#34;No&#34;。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>subsequence
2
sequence
bus
</pre>
<h3>
【样例输出】
</h3>
<pre>Yes
No
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