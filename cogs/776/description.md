# 题目描述


<p>
【问题描述】
</p>
<p>
通常对一个长度为n(n≤24)的整数数列进行排序操作，实际上是对它们按照从小到大的顺序重整。一般情况下可以比较任意两个数之间的大小并交换它们的位置，但这里我们限制只能数列的某一个前缀序列翻转，除此之外的任何操作都是不允许的。更精确地说，假设数列a1，a2，…，an，一个合法的操作是把数列变为ak,ak-1，…，a2，a1，ak+1，ak+2，…，an，
</p>
<p>
其中1<k< span="">≤n。例如，数列3 2 1 4，可能的操作有3种，分别是2 3 1 4(即操作3，2)，1 2 3 4(即操作3，2，1)，4 1 2 3(即操作整个数组)。</k<>
</p>
<p>
你的任务是求出一个序列用上面的方法排序至少需要多少步。
</p>
<p>
<br/>
</p>
<p>
【输入】
</p>
<p>
输入格式(输入文件名sorta．in)
</p>
<p>
输入文件有两行：
</p>
<p>
第1行是一个整数n，表示数列的长度。
</p>
<p>
第2行有n个整数，表示待排序的数列，每个整数的绝对值不大于32767。
</p>
<p>
<br/>
</p>
<p>
【输出】
</p>
<p>
输出格式(输出文件名sorta．out)
</p>
<p>
输出文件有两行：
</p>
<p>
第1行是一个整数s，表示完成排序所需的最少步数。
</p>
<p>
第2行有s个整数，按顺序表示完成排序的过程，每一步输出表示操作的k值。
</p>
<p>
<br/>
</p>
<p>
【输入输出样例】
</p>
<p>
输入(sorta．in)
</p>
<p>
4
</p>
<p>
3 2 1 4
</p>
<p>
输出(sorta．out)
</p>
<p>
1
</p>
<p>
3
</p>
<p>
样例提示：只需要一步就可以完成排序3 2 1 4，1 2 3 4。
</p>
<p>
<br/>
</p>