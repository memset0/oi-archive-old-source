# 题目描述

<p>可怜、蒜斜、镁团经常在一起打三人麻将。可是今天蒜斜和镁团去玩“你问你猜”了，因此可怜只能自己一个人打。可怜找了一套只有一种花色的麻将，即这套麻将中只有 $9$ 种不同的牌，大小分别为 $1$ 到 $9$，每种牌都有 $4$ 张。为了方便，在这儿我们只考虑一个简化后的麻将规则。</p>
<p>定义面子为三张大小相同或者大小相邻的麻将牌，即大小形如 $i,i,i(1 \leq i \leq 9)$ 或者 $i,i+1,i+2(1 \leq i \leq 7)$。定义对子为两张大小相同的麻将牌，即大小形如 $i,i(1 \leq i \leq 9)$。</p>
<p>定义一个麻将牌集合 $S$ 是胡的当且仅当它的大小为 $14$ 且满足下面两个条件中的至少一个：</p>
<ol><li>$S$ 可以被划分成五个集合 $S_1$ 至 $S_5$。 其中 $S_1$ 为对子，$S_2$ 至 $S_5$ 为面子。</li>
<li>$S$ 可以被划分成七个集合 $S_1$ 至 $S_7$，它们都是对子，且对应的大小 <strong>两两不同</strong>。</li>
</ol><p>举例来说，下列集合都是胡的：</p>
<ol><li>$\{1,1,1,1,2,3,4,5,6,7,8,9,9,9\}$</li>
<li>$\{1,1,2,2,4,4,5,5,6,6,7,7,8,8\}$</li>
<li>$\{1,1,2,2,3,3,4,4,5,5,6,6,7,7\}$</li>
</ol><p>而下列集合都不是胡的：</p>
<ol><li>$\{1,1,1,2,3,4,5,6,7,8,9,9,9\}$</li>
<li>$\{1,1,1,1,4,4,5,5,6,6,7,7,8,8\}$</li>
<li>$\{1,1,1,2,2,2,3,3,3,4,4,4,5,7\}$</li>
</ol><p>在麻将游戏游戏开始的时候，这 $36$ 张牌被随机打乱并从左到右摆成一排，形成了牌山。两个牌山是不同的当且仅当存在一个位置 $i$，这两个牌山第 $i$ 个位置的牌的大小不同。经过简单的排列组合，我们可以发现一共有 $36! / (4!)^{9} \approx 1.408 \times 10^{29}$ 种不同的牌山。</p>
<p>游戏开始时，玩家会依次从牌山的最左边摸取 $13$ 张牌。接着游戏会进行至多 $23$ 轮，在每一轮中：</p>
<ol><li>玩家先从当前牌山的最左边摸取一张牌。</li>
<li>如果当前玩家手上的 $14$ 张牌可以胡，玩家可以选择胡，也可以选择不胡。如果选择胡，则游戏结束。</li>
<li>玩家从手上的 $14$ 张牌中选一张打出去。</li>
</ol><p>众所周知，麻将是一个运气游戏：当运气来了的时候，牌桌前栓一条狗都能赢。可怜随手写了三个简单的麻将 AI，在给定参数 $k$ 的情况下，这三个 AI 会分别按照以下策略打牌：</p>
<ol><li>每一次要打牌的时候打出手上数值最小的牌，如果有多张则打出最早摸上来的那一张。并只有在游戏的第 $k$ 轮的时候才会选择胡牌，其他轮数即使当前手牌是胡的也选择不胡牌。</li>
<li>每一次要打牌的时候打出手上数值最大的牌，如果有多张则打出最早摸上来的那一张。并只有在游戏的第 $k$ 轮的时候才会选择胡牌，其他轮数即使当前手牌是胡的也选择不胡牌。</li>
<li>每一次要打牌的时候打出手上最早摸上来的牌。并只有在游戏的第 $k$ 轮的时候才会选择胡牌，其他轮数即使当前手牌是胡的也选择不胡牌。</li>
</ol><p>可怜发现，即使这些 AI 的策略非常的简单，但是它们也是能胡牌的。定义一个牌山为 $k$-天选的，当且仅当在固定参数为 $k$ 的时候，不管选用这三个 AI 中的哪一个来打牌都能胡牌。举例来说，下面这个牌山就是一个 $2$-天选的牌山：</p>
<pre><code>1 2 2 3 3 4 4 5 6 6 7 7 7 1 5 1 1 2 2 3 3 4 4 5 5 6 6 7 8 8 8 8 9 9 9 9</code></pre>
<p>现在，可怜想要你帮她计算一些有关$k$-天选牌山的数据。</p>
<h4>Small Task</h4>
<p>在这个部分中，你需要对于每一个 $k \in [1, 23]$，构造一个 $k$-天选的牌山。</p>
<p>输出格式：输出 $23$ 行，每行 $36$ 个空格隔开的 $1-9$ 的数字，第 $i$ 行描述一个 $i$-天选的牌山。</p>
<p>提交文件：<code>mahjong1.out</code>。</p>
<h4>Large Task</h4>
<p>在这个部分中，你需要对于每一个 $k \in [1, 23]$，计算有多少个不同的 $k$-天选的牌山。</p>
<p>输出格式：输出 $23$ 行，每行一个整数。第 $i$ 行描述 $i$-天选的牌山数量对 $998244353$ 取模后的值。</p>
<p>提交文件：<code>mahjong2.out</code>。</p>