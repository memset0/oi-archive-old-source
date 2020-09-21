# 题目描述


<h3>
【问题描述】
</h3>
<p>
有 $N(N&lt;=20)$ 台 PC 放在机房内，现在要求由你选定一台 PC，用共 $N-1$ 条网线从这台机器开始一台接一台地依次连接他们，最后接到哪个以及连接的顺序也是由你选定的，为了节省材料，网线都拉直。求最少需要一次性购买多长的网线。（说白了，就是找出 $N$ 的一个排列 $P_1 P_2 P_3 ..P_N$ 然后 $P_1 -&gt; P_2 -&gt; P_3 -&gt; ... -&gt; P_N$ 找出 $|P_1P_2|+|P_2P_3|+...+|P_{N-1}P_N|$ 长度的最小值）
</p>
<h3>
【输入格式】
</h3>
<p>
第一行 $N$，下面 $N$ 行，每行分别为机器的坐标 $(x,y)$（$x$ 为实数 $-100\le x,y\le 100$）
</p>
<h3>
【输出格式】
</h3>
<p>
最小的长度，保留两位小数。
</p>
<h3>
【输入样例】
</h3>
<pre>3
0 0
1 1
1 -1
</pre>
<h3>
【输出样例】
</h3>
<pre>2.83
</pre>