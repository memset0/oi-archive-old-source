# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
zzsyz实验楼里面种了一棵滑稽树，只有滑稽之力达到大乘期的oier才能看到。虽然我们看不到，但是还是知道一些信息：
</p>
<p>
这真的是一棵树，由n个节点，n-1条边联通。一号滑稽果同时也是整棵滑稽树的树根。滑稽树上每个节点有一个滑稽果，每个滑稽果有它的重量。
</p>
<p>
雪甜甜公主是神犇当然看得到那棵滑稽树啦，现在她感兴趣的是这样三件事
</p>
<p>
1：滑稽树太大啦，雪甜甜公主有的时候只想知道，在以某一个滑稽果为根的子滑稽树里面，重量第k小的果子的重量是多少？
</p>
<p>
2：除了重量第k小的果子，雪甜甜还想知道以某个滑稽果为根的子滑稽树里面，重量在[a, b]这个范围内的滑稽果有多少个。
</p>
<p>
3：雪甜甜还喜欢吃滑稽果，但是吃完，原来滑稽果的位置上还会长出一个新的滑稽果，只是重量可能不一样。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个正整数n，表示滑稽树有n个节点。
</p>
<p>
第二行n个正整数，分别描述1号，2号,,,，n号节点滑稽果的重量。
</p>
<p>
接下来n-1行，每行2个正整数u, v ∈ [1, n]，表示滑稽果u与滑稽果v之间有树枝连接。
</p>
<p>
接下来一个正整数q，表示雪甜甜有q次行动
</p>
<p>
之后q行，有这样3种形式
</p>
<p>
1 u k 雪甜甜公主询问以u为根的子滑稽树中，重量第k小的滑稽果的重量。
</p>
<p>
2 u a b 雪甜甜公主想知道，以u为根的子滑稽树中，重量在[a, b]范围内的滑稽果有多少个。
</p>
<p>
3 u x 雪甜甜公主吃掉了编号为u的滑稽果，但是在原位置上立刻长出来了一个重量为x的滑稽果。因为位置没有变，所以编号还是u。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每次询问，输出结果。
</p>
<h3>
【样例输入】
</h3>
<pre>5
3 4 6 1 2
1 2
1 3
3 4
3 5
7
1 1 4
2 1 1 5
3 4 5
1 1 4
2 3 3 6
3 5 7
1 3 3
</pre>
<h3>
【样例输出】
</h3>
<pre>4
4
5
2
7
</pre>
<h3>
【样例解释】
</h3>
<p>
<img alt="" src="/upload/image/20170220/20170220202455_56273.png"/> 
</p>
<h3>
【数据范围以及提示】
</h3>
<p>
<br/>
</p>
<p>
对于前35%的数据满足，N &lt;= 5000
</p>
<p>
对于前50%的数据满足，N &lt;= 10000
</p>
<p>
对于前100%的数据满足，N &lt;= 30000
</p>
<p>
滑稽果的重量：对于100%的数据满足 滑稽果的重量 &lt;= 10000
</p>
<p>
询问：询问的个数Q：
</p>
<p>
对于前50%的数据满足 Q &lt;= 10000
</p>
<p>
对于前100%的数据满足 Q &lt;= 50000
</p>
<p>
对于前25%的数据，只有第一种询问。
</p>
<p>
对于前65%的数据，有第1，2种询问。
</p>
<p>
对于100%的数据第1，2，3种询问都存在。
</p>
<p>
对于前35%的数据，满足一个特殊的限制条件：每次询问的滑稽果u = 1
</p>
<p>
保证询问k小重量的滑稽果的时候，k值∈ [1, 子树的节点数]
</p>
<p>
来自 http://syzoj.com/problem/279
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
