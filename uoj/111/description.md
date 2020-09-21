# 题目描述

<p>印尼首都雅加达市有 $N$ 座摩天楼，它们排列成一条直线，我们从左到右依次将它们编号为 $0$ 到 $N − 1$。除了这 $N$ 座摩天楼外，雅加达市没有其他摩天楼。</p>
<p>有 $M$ 只叫做 “doge” 的神秘生物在雅加达市居住，它们的编号依次是 $0$ 到 $M − 1$。编号为 $i$ 的 doge 最初居住于编号为 $B_i$ 的摩天楼。每只 doge 都有一种神秘的力量，使它们能够在摩天楼之间跳跃，编号为 $i$ 的 doge 的跳跃能力为 $P_i$ （$P_i &gt; 0$）。</p>
<p>在一次跳跃中，位于摩天楼 $b$ 而跳跃能力为 $p$ 的 doge 可以跳跃到编号为 $b − p$ （如果 $0 \leq b − p &lt; N$）或 $b + p$ （如果 $0 \leq b + p &lt; N$）的摩天楼。</p>
<p>编号为 $0$ 的 doge 是所有 doge 的首领，它有一条紧急的消息要尽快传送给编
号为 $1$ 的 doge。任何一个收到消息的 doge 有以下两个选择:</p>
<ol><li>跳跃到其他摩天楼上；</li>
<li>将消息传递给它当前所在的摩天楼上的其他 doge。</li>
</ol><p>请帮助 doge 们计算将消息从 $0$ 号 doge 传递到 $1$ 号 doge 所需要的最少总跳跃步数，或者告诉它们消息永远不可能传递到 $1$ 号 doge。</p>

# 输入格式


<p>输入的第一行包含两个整数 $N$ 和 $M$。</p>
<p>接下来 $M$ 行，每行包含两个整数 $B_i$ 和 $P_i$。</p>

# 输出格式


<p>输出一行，表示所需要的最少步数。如果消息永远无法传递到 $1$ 号 doge，输出 $−1$。</p>

# 样例一


<h4>input</h4>
<pre>5 3
0 2
1 1
4 1

</pre>

<h4>output</h4>
<pre>5

</pre>

<h4>explanation</h4>
<p>下面是一种步数为 $5$ 的解决方案：</p>
<ul><li>$0$ 号 doge 跳跃到 $2$ 号摩天楼，再跳跃到 $4$ 号摩天楼（$2$ 步）。</li>
<li>$0$ 号 doge 将消息传递给 $2$ 号 doge。</li>
<li>$2$ 号 doge 跳跃到 $3$ 号摩天楼,接着跳跃到 $2$ 号摩天楼，再跳跃到 $1$ 号摩天楼（$3$ 步）。</li>
<li>$2$ 号 doge 将消息传递给 $1$ 号 doge。</li>
</ul>
# 子任务


<p>所有数据都保证 $0 \leq B_i &lt; N$。</p>
<ul><li>子任务 1 （10 分）<ul><li>$1 \leq N \leq 10$</li>
<li>$1 \leq P_i \leq 10$</li>
<li>$2 \leq M \leq 3$</li>
</ul></li>
<li>子任务 2 （12 分）<ul><li>$1 \leq N \leq 100$</li>
<li>$1 \leq P_i \leq 100$</li>
<li>$2 \leq M \leq 2000$</li>
</ul></li>
<li>子任务 3 （14 分）<ul><li>$1 \leq N \leq 2000$</li>
<li>$1 \leq P i ≤ 2000$</li>
<li>$2 \leq M \leq 2000$</li>
</ul></li>
<li>子任务 4 （21 分）<ul><li>$1 \leq N \leq 2000$</li>
<li>$1 \leq P_i \leq 2000$</li>
<li>$2 \leq M \leq 30000$</li>
</ul></li>
<li>子任务 5 （43 分）<ul><li>$1 \leq N \leq 30000$</li>
<li>$1 \leq P_i \leq 30000$</li>
<li>$2 \leq M \leq 30000$</li>
</ul></li>
</ul><p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=111">样例数据下载</a></p>
