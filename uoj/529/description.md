# 题目描述

<p>众所周知，<code>114514</code> 是一个带有味道的数字。</p>
<p>蒜斜不太喜欢 <code>114514</code>，就像米斯达不喜欢 <code>4</code> 一样。但是总有一些讨厌的群友给蒜斜发这个数字，最开始，在蒜斜的禁言+拉黑手段下，这样的风气稍微缓解了一点。但是好景不长，群友们渐渐发明出了新的手段：有一些群友会把若干个 <code>114514</code> 穿插在一起，从而变成一个新的字符串。例如两个 <code>114514</code> 就能够穿插形成 <code>111145144514</code>, <code>114151145144</code> 等字符串。</p>
<p>对于一些短的字符串，蒜斜还能勉强分辨出这些字符串是怎么由 <code>114514</code> 得到的。但是有些时候群友会发一些特别复杂的字符串，这就让蒜斜犯了难。于是他找到了你，希望你能帮助他把一些字符串拆分成 <code>114514</code>，这样他就有证据可以去禁言那些讨厌的群友了。</p>
<p>具体来说，蒜斜会给你一些长度为 $6$ 的倍数的只包含字符 <code>1</code>,<code>4</code>,<code>5</code> 的字符串 $S$。而你要找到$n=|S|/6$个序列，$x_{1,1},x_{1,2}, \dots, x_{1,6}, \dots, x_{n,1}, \dots, x_{n,6}$。要求：</p>
<ol><li>对于每个$i (1\leq i\leq n)$，有$1\leq x_{i,1} &lt; x_{i,2} &lt; \dots &lt; x_{i,6}\leq |S|$。</li>
<li>所有的$x_{i,j} (1\leq i \leq n, 1 \leq j\leq 6)$两两不同。</li>
<li>对于每个$i (1\leq i \leq n)$，有$S_{x_{i,1}}=S_{x_{i,2}}=S_{x_{i,5}}=$<code>1</code>, $S_{x_{i,3}}=S_{x_{i,6}}=$<code>4</code>, $S_{x_{i,4}}=$<code>5</code>。这里对于$S$中的字符，下标从$1$开始。</li>
</ol>
# 输入格式


<p>第一行一个整数$T (1\leq T\leq 10^5)$表示数据组数。</p>
<p>接下来$T$行，每行一个字符串$S (1\leq |S|\leq 6\times 10^5)$。保证所有的字符串长度总和不超过$6\times 10^5$，且保证存在一种拆分方案。</p>

# 输出格式


<p>对于每组数据，输出$|S|/6$行，每行$6$个整数，表示一种拆分方案。如果存在多种合法的拆分方案，你只需要输出任意一种即可。</p>

# 样例输入


<pre>3
114514
111144551144
111141154115114454514414

</pre>


# 样例输出


<pre>1 2 3 4 5 6
1 2 5 7 9 11
3 4 6 8 10 12
1 2 5 8 13 18
3 4 9 12 14 21
6 7 15 17 20 22
10 11 16 19 23 24

</pre>


# 限制与约定


<p><strong>Small Task</strong>: 保证 $S$ 的最后 $|S|/6$ 个字符都为<code>4</code>。</p>
<p><strong>Large Task</strong>: 无特殊限制。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$1024\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=529">样例数据下载</a></p>