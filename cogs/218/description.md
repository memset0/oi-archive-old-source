# 题目描述


<p>
【问题描述】
</p>
<p>
笨小猴的词汇量很小，所以每次做英语选择题的时候都很头痛。但是他找到了一种方法，经实验证明，用这种方法去选择选项的时候选对的几率非常大!
</p>
<p>
这种方法的具体描述如下：假设maxn是单词中出现次数最多的字母的出现次数，minn是单词中出现次数最少的字母的出现次数，如果maxn-minn是一个质数，那么笨小猴就认为这是个Lucky Word，这样的单词很可能就是正确的答案。
</p>
<p>
【输入】
</p>
<p>
输入文件word.in只有一行，是一个单词，其中只可能出现小写字母，并且长度小于100。
</p>
<p>
【输出】
</p>
<p>
输出文件word.out共两行，第一行是一个字符串，假如输入的单词是Lucky Word，那么输出“Lucky Word”，否则输出“No Answer”；
</p>
<p>
第二行是一个整数，如果输入单词是Lucky Word，输出maxn-minn的值，否则输出0。
</p>
<p>
【输入输出样例1】
</p>
<p>
word.in
</p>
<pre>error
</pre>
<p>
word.out
</p>
<pre>Lucky Word
2
</pre>
<p>
【输入输出样例1解释】
</p>
<p>
单词error中出现最多的字母r出现了3次，出现次数最少的字母出现了1次，3-1=2，2是质数。
</p>
<p>
【输入输出样例2】
</p>
<p>
word.in
</p>
<pre>olymipic
</pre>
<p>
word.out
</p>
<pre>No Answer
0
</pre>
<p>
【输入输出样例2解释】
</p>
<p>
单词olymipic中出现最多的字母i出现了2次，出现次数最少的字母出现了1次，2-1=1,l不是质数。
</p>
<p>
<br/>
</p>