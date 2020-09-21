# 题目描述

<p>阿塞拜疆因地毯而闻名。作为一位地毯设计大师，你在做新设计时想画一条折线。一条折线是二维平面上包含 $t$ 条线段的线段序列，而这些线段由包含 $t+1$ 个点 $p_0,p_1,\cdots,p_n$ 的点序列按照此规则构成：对所有的 $0 \le i &lt; n$，都有一条线段连接点 $p_i$ 和 $p_{i+1}$。</p>
<p>为完成这个新设计，你已经标出了二维平面中的 $n$ 个小圆点。小圆点 $i$ 的坐标为 $(x_i,y_i)$。不存在 $x$ 坐标或 $y$ 坐标相同的两个小圆点。</p>
<p>现在你想要找到一个点序列 $(sx_0,sy_0),(sx_1,sy_1),\cdots,(sx_2,sy_2)$，由该点序列构成的折线需满足</p>
<ul><li>该折线从 $(0,0)$ 开始（即 $sx_0=sy_0=0$ ）。</li>
<li>该折线经过所有的小圆点（它们不必是线段的端点）。</li>
<li>该折线仅包括水平线段和竖直线段（对于构成该折线的连续两个点，其 $x$ 坐标或 $y$ 坐标相等，且不重合）。</li>
<li>折线中的线段可以相交或重叠；换言之，平面上的每个点可以被任意数量的线段覆盖。</li>
</ul><p>本题是一个有部分分的提交答案型题目。请从上方「附加文件」下载 $10$ 个输入文件，这些文件给出了小圆点的位置。对每个输入文件，你需要提交一个答案文件，描述满足要求的折线。你的得分将取决于折线中的线段数量（参见下面的计分方式一节）。</p>

# 输入格式


<p>这是一道提交答案题，共有 $10$ 组输入数据，这些数据命名为 <code>a1.in</code> ~ <code>a10.in</code>。</p>
<p>第一行，一个整数 $n$，表示小圆点的数量。</p>
<p>接下来 $n$ 行，每行两个整数$x_i,y_i$，表示第 $i$ 个小圆点的坐标。</p>

# 输出格式


<p>对于每组输入数据，你需要提交相应的输出文件 <code>a1.out</code> ~ <code>a10.out</code>。</p>
<p>第一行，一个整数 $t$，表示在折线中你使用的线段数量。</p>
<p>接下来 $t$ 行，每行两个整数 $(sx_i,sy_i)$ ,第 $i$ 行表示你选取的点序列中第 $i$ 个点的坐标。</p>
<p>你的输出需要满足:</p>
<ul><li>$-2\times 10^9 \le sx_i,sy_i \le 2 \times 10^9$。</li>
</ul><p>你不需要输出 $(sx_0,sy_0)$换言之，第 $i+1$ 行输出的是 $(sx_i,sy_i)$。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">4
2 1
3 3
4 4
5 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain6">2 0
2 3
5 3
5 2
4 2
4 4</code></pre>
<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/536/bline.png" alt="样例一示意图"/></p>

# 数据范围


<h4>计分方式</h4>
<p>对每个测试点，你最多能够得到 $10$ 分，</p>
<p>如果给出一条非法的折线，你将得到 $0$ 分。否则，得分将根据一个递减序列 $c_1,\cdots,c_{10}$ 来计算。</p>
<p>假设你的解答是一条包含 $t$ 条线段的合法折线。那么，你将得到</p>
<ul><li>$i$ 分，如果 $c_i=t,(1 \le i \le 10)$。</li>
<li>$i+\frac{c_i-t}{c_{i+1}-c_i}$ 分，如果 $c_{i+1} &lt; t &lt; c_i(1 \le i \le 9)$。</li>
<li>$0$ 分，如果 $t &gt; c_1$。</li>
<li>$10$ 分，如果 $t &lt; c_{10}$。</li>
</ul><p>可以这样理解：在 $k \in (c_{i+1},c_i)$ 这个区间上，你的得分是随着 $k$ 减小线性增大的。一旦得分，得分一定在 $[1,10]$ 区间内。</p>
<p>由于某些计分方式的原因，OJ上每个测试点的得分为实际得分下取整得到的值。</p>
<p>以下是每个测试点 $n$ 与 $c_i$ 的信息：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>$n$</th><th>$c_1$</th><th>$c_2$</th><th>$c_3$</th><th>$c_4$</th><th>$c_5$</th>
                                               <th>$c_6$</th><th>$c_7$</th><th>$c_8$</th><th>$c_9$</th><th>$c_{10}$</th></tr></thead><tbody><tr><td>$1$</td><td>$20$</td><td>$50$</td><td>$45$</td><td>$40$</td><td>$37$</td><td>$35$</td>
                              <td>$33$</td><td>$28$</td><td>$26$</td><td>$25$</td><td>$23$</td></tr><tr><td>$2$</td><td>$600$</td><td>$1200$</td><td>$937$</td><td>$674$</td><td>$651$</td><td>$640$</td>
                               <td>$628$</td><td>$616$</td><td>$610$</td><td>$607$</td><td>$603$</td></tr><tr><td>$3$</td><td>$5000$</td><td>$10000$</td><td>$7607$</td><td>$5213$</td><td>$5125$</td><td>$5081$</td>
                               <td>$5037$</td><td>$5020$</td><td>$5012$</td><td>$5008$</td><td>$5003$</td></tr><tr><td>$4$</td><td>$50000$</td><td>$100000$</td><td>$75336$</td><td>$50671$</td><td>$50359$</td><td>$50203$</td>
                                <td>$50047$</td><td>$50025$</td><td>$50014$</td><td>$50009$</td><td>$50003$</td></tr><tr><td>$5$</td><td>$72018$</td><td>$144036$</td><td>$108430$</td><td>$72824$</td><td>$72446$</td><td>$72257$</td>
                                <td>$72067$</td><td>$72044$</td><td>$72033$</td><td>$72027$</td><td>$72021$</td></tr><tr><td>$6$</td><td>$91891$</td><td>$183782$</td><td>$138292$</td><td>$92801$</td><td>$92371$</td><td>$92156$</td>
                                <td>$91941$</td><td>$91918$</td><td>$91906$</td><td>$91900$</td><td>$91894$</td></tr><tr><td>$7 \sim 10$</td><td>$100000$</td><td>$200000$</td><td>$150475$</td><td>$100949$</td><td>$100500$</td><td>$100275$</td>
                                 <td>$100057$</td><td>$100027$</td><td>$100015$</td><td>$100009$</td><td>$100003$</td></tr></tbody></table></div>

<p>对于所有测试数据，满足$1 \le n \le 100000,-10^9 \le x_i,y_i \le 10^9$。</p>
<p><a href="http://uoj.ac/download.php?type=problem&amp;id=536">输入数据下载</a></p>