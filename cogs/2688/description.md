# 题目描述


<h3>
【题目描述】
</h3>
<p>
 从前有一个渔夫抓到了一条特别的鱼，放走了。
</p>
<p>
渔夫再次抓到了这条鱼，正要再次放走之时，这条鱼吐出了一片迷雾，迷雾散去以后，渔夫不见了。
</p>
<p>
渔夫睁开眼，发现自己到了一个石碑面前，碑上有一行小写英文字符串S，下面写着：“汝等既有护生之念，应是善良之人，理当授以嘉奖。但是为了证明你的善良，你需要展现你的智慧，以确保吾所见之善良，并非出于汝之愚笨。上面的字符串，你若于其中找到最长的子串，使得这个子串既出现在前缀，又出现在后缀，还出现在字符串的中间，也就是既非前缀又非后缀的位置，则该石碑会将其所藏之物拱手相送。”
</p>
<p>
渔夫听完以后，可谓一脸懵逼，遂将这个问题分享给你，希望你能够解决。若能解决，渔夫愿意拿出10,000,000,000,000 mod 250 元，作为解决这个问题的报酬。
</p>
<h3>
【输入格式】
</h3>
<p>
 第一行是一个数字q，表示这个问题有q组不同问题。
</p>
<p>
接下来q行每行一个由小写英文字母组成的字符串S，意义见于上文。
</p>
<h3>
【输出格式】
</h3>
<p>
输出共q行，每行一个字符串，表示对于每组问题，所求的字符串，如果不存在长度大于0且满足要求的字符串，就改成输出”---”（不包含引号）
</p>
<h3>
【样例输入】
</h3>
<pre>1
niconiconi
</pre>
<h3>
【样例输出】
</h3>
<pre>ni</pre>
<h3>
【提示】
</h3>
<p>
前10%的数据，q&lt;=10
</p>
<p>
前30%的数据，q&lt;=30
</p>
<p>
前50%的数据，q&lt;=100
</p>
<p>
所有数据，q&lt;=200,000
</p>
<p>
题目保证O(n)算法能过！
</p>
<h3>
【来源】
</h3>
<p>
QBXT春季训练营第二次测试T3 OR 51nod 1286
</p>