# 题目描述


<h3>
【题目背景】
</h3>
<p>
<br/>
</p>
<p>
在上次全是黄段子的无聊世界后，为了能振兴德〇志帝国的钱包，元首和他的追随者们又参加一个作死的游戏。经吼拉姆的仔细侦查，元首确信这次的主办者 约瑟泰迪 和上次的 泰迪绫女 完全不是一个人。
</p>
<p>
元首：“咱这次来能都拿多少钱？”
</p>
<p>
约瑟泰迪：“一块钱都没有，咩。”
</p>
<p>
元首：“气死偶咧！偶到河北省来，就是想要......”
</p>
<p>
约瑟泰迪：“你说啥都是没有用滴，你们已经被COJS的小伙伴么围观咧，想要出去的话就必须玩一个游戏。”
</p>
<p>
<br/>
</p>
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
元首和他的小伙伴总计n个人坐在圆桌旁，桌子上有一瓶 霸〇洗发水。
</p>
<p>
从第一个人开始报数，同时把洗发水向下一个人传递。
</p>
<p>
如果恰好这个人报到的是n，那么霸王龙的效果就会发动，给那个人加上特技，把那个人duang的一下从游戏中除外。
</p>
<p>
接下来从下一个存活的的人开始报数并且同时传递洗发水。值得注意的是，这次的n值还是游戏开始时的n值。
</p>
<p>
如果有时刻只剩下一个人，那么就是这个人获胜。
</p>
<p>
由于元首的追随者们的忠心耿耿，他们决定还有以下规则。
</p>
<p>
每个人都有一个鬼畜值。
</p>
<p>
如果一个人报到n的时候，他的鬼畜值比报到n-1的人的鬼畜值小，那么他直接把洗发水传给那个人，然后霸王龙的效果发动。
</p>
<p>
此外一切照常。
</p>
<p>
已知每次元首都是赢，现在求元首的编号。
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
第一行有一个数 n
</p>
<p>
接下来的一行有n个数并且第i个数表示编号为i的人的善良值。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
只有一行，为最后一个出局的人的编号。在你的输出里最后的回车符、换行符或空格符将会被忽略。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
3
</p>

<p>
50 25 30
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>2</pre>
<h3>
【数据范围】
</h3>
<p>
0&lt;=n&lt;=1000。
</p>
<p>
每个人的善良值&lt;= 2^64。且没有人的善良值和另一个人的相同。
</p>
<h3>
【吐槽范围】
</h3>
<p>
题面描述保证正确但和你想的似乎不太一样。
</p>