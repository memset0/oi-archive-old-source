# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
（参考<a target="_blank" href="../problem/problem.php?pid=1757">COGS 1757</a>）
</p>
<p>
    Asm.Def和Chenyao在玩游戏.游戏内容是这样的:&#34;现在黑板上有1~n个数字,两人轮流选择一个数,并把它和它的所有约数擦去.擦去最后一个数的人会赢.&#34;由Asm.Def先取，Chenyao后取。Asm.Def想知道自己怎样才能获胜，就找到了cstdio帮忙。已知Chenyao和cstdio都是会写LCT的神犇，他们的智力均为INF，而Asm.Def得到了cstdio的帮助，因此他们做出的决策总是最优的。
</p>
<p>
    但是今天，cstdio在忙着切集训队互测题，于是他请你写程序帮助Asm.Def列出所有的先手必胜决策。
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
一行一个整数n，代表黑板上正整数的个数。
</p>
<p>
对于所有数据，1 ≤ n ≤ 24.
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
输出包含一行，从小到大依次输出所有必胜决策，用空格隔开。若Asm.Def无法获胜，则输出0。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>5</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
Asm.Def第一步选择4，取走4的所有约数1,2,4，局面变成3,5，此时Chenyao只能取走3或5，则Asm.Def取走剩下的一个数即可获胜。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
<br/>
</p>
<p>
游戏来自《训练指南》，
</p>
<p>
背景来自HA(High-School A-Team)
</p>
<p>
<br/>
</p>