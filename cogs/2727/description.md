# 题目描述


<h3>
【题目描述】
</h3>
<p>
农夫约翰为牛们做了很好吃的食品，但是牛很挑食。每一头牛只喜欢一些食品或饮料而别的一概不吃。虽然他不一定能把所有牛喂饱，但他还是想让尽可能多的牛得到他们喜欢的食品和饮料。
</p>
<p>
农夫约翰做了 $F(1\le F\le 100)$ 种食品并准备了 $D(1\le D\le 100)$ 种饮料。他的 $N(1\le N\le 100)$ 头牛都已决定了是否愿意吃某种食物和喝某种饮料。农夫约翰想给每一头牛一种食品和一种饮料，使得尽可能多的牛得到喜欢的食物和饮料。
</p>
<p>
注意，每一件食物或饮料只能给一头牛。例如，如果食物 $2$ 被一头牛吃掉了，没有别的牛能吃食物 $2$。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行：三个整数 $N,F$ 和 $D$。
</p>
<p>
第二到 $N+1$ 行：每一行由两个数 $F_i$ 和 $D_i$ 开始，分别是第 $i$ 头牛可以吃的食品数和可以喝的饮料数。下面 $F_i$ 个整数是第 $i$ 头牛可以吃的食品号，再下面的 $D_i$ 个整数是第 $i$ 头牛可以喝的饮料号码。
</p>
<h3>
【输出格式】
</h3>
<p>
一行：一个整数，表示农夫约翰最多可以喂饱牛的数目。
</p>
<h3>
【样例输入】
</h3>
<pre>4 3 3
2 2 1 2 3 1
2 2 2 3 1 2
2 2 1 3 1 2
2 1 1 3 3
</pre>
<h3>
【样例输出】
</h3>
<pre>3
</pre>
<h3>
【提示】
</h3>
<p>
牛 $1$：食品从 $\{1,2\}$, 饮料从 $\{1,2\}$ 中选。<br/>
牛 $2$：食品从 $\{2,3\}$, 饮料从 $\{1,2\}$ 中选。<br/>
牛 $3$：食品从 $\{1,3\}$, 饮料从 $\{1,2\}$ 中选。<br/>
牛 $4$：食品从 $\{1,3\}$, 饮料从 $\{3\}$ 中选。
</p>
<p>
一个方案是：
</p>
<p>
牛 $1$：不吃。<br/>
牛 $2$：食品 $2$, 饮料 $2$。<br/>
牛 $3$：食品 $1$, 饮料 $1$。<br/>
牛 $4$：食品 $3$, 饮料 $3$。
</p>
<p>
用鸽笼定理可以推出没有更好的解（一共只有 $3$ 种食品和饮料）。当然，别的数据会更难。
</p>
<h3>
【来源】
</h3>
<p>
USACO Open07 Gold
</p>
