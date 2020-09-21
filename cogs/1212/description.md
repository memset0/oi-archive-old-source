# 题目描述


<h3>
【题目描述】
</h3>
<p>
奶牛在熊大妈的带领下排成了一条直队。  
</p>
<p>
显然，不同的奶牛身高不一定相同……
</p>
<p>
现在，奶牛们想知道，如果找出一些连续的奶牛，要求最左边的奶牛A是最矮的，最右边的B是最高的，且B高于A奶牛，中间如果存在奶牛，则身高不能和A、B奶牛相同。问这样的奶牛最多会有多少头？
</p>
从左到右给出奶牛的身高，请告诉它们符合条件的最多的奶牛数（答案可能是0，2，但不会是1）。
<h3>
【输入格式】
</h3>
<p>
第一行一个数N (2≤N≤100000)，表示奶牛的头数。
</p>
<p>
接下来N个数，每行一个数，从上到下表示从左到右奶牛的身高(1≤身高= maxlongint)。
</p>
<h3>
【输出格式】
</h3>
<p>
一行，表示最多奶牛数。
</p>
<h3>
【样例输入】
</h3>
<pre>5
1
2
3
4
1
</pre>
<h3>
【样例输出】
</h3>
<pre>4
</pre>
<h3>
【提示】
</h3>
<p>
样例解析,取第1头到第4头奶牛，满足条件且为最多。
</p>