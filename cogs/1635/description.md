# 题目描述


<h3>
【题目描述】
</h3>
<p>
现有一颗二叉树，求从根结点到叶子结点的一条最短的路径，路径的值是这条路径上所有结点的值之和。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件将包含二叉树中序和后序遍历。你的程序将从输入文件读取两行（直至文件末尾）。第一行将包含中序遍历树的序列值，第二行将包含后序遍历树的序列值。所有输入值均不同，大于0且小于10000。 你可以假设所有二叉树的结点数将不超过10000且大于等于1。
</p>
<h3>
【输出格式】
</h3>
<p>
输出最短路径的叶子结点的值，如果有多条最短路径，输出叶子结点最小的值。
</p>
<h3>
【样例输入】
</h3>
<pre>3 2 1 4 5 7 6
3 1 2 5 6 7 4
7 8 11 3 5 16 12 18
8 3 11 7 16 18 12 5
255
255
</pre>
<h3>
【样例输出】
</h3>
<pre>1
3
255</pre>
<h3>
【来源】
</h3>
<p>
UVa 548 Tree
</p>