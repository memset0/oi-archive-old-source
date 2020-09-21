# 题目描述

<p>在鸡年来临之际，为了彻底打击程序猿及猴族的残余势力，计算鸡村的大数据计算中心需要应对大量的区间求和问题以进行合理规划。</p>
<p>区间求和是这么一个问题：给你长度为 $n - 1$ 的数组，下标编号为 $[1, n)$。有 $q$ 个询问，其中第 $j$ 个询问是要求下标区间在 $[l_j, r_j)$ 内所有数的和。</p>
<p>数据分块鸡不会前缀和，它只知道分块大法好。它会将该数组切成若干小块，假设分界点为 $a_0, a_1, a_2, \dots, a_k$，其中 $a_0 = 1, a_k = n$，那么第 $i$ 块覆盖的下标区间即为 $[a_i, a_{i+1})$，并会存储这个区域内所有元素的和。</p>
<p>每次查询 $[l_j, r_j)$ 数据分块鸡总会尽可能利用整块存储的信息，并在边界处进行微调。会遇到如下几种情况：</p>
<ul><li>存在 $[a_i, a_{i+1})$ 使得 $[l_j, r_j) = [a_i, a_{i+1})$，那么数据分块鸡将直接使用该块内存储的元素总和，需要花费 $1$ 的代价；</li>
<li>如果不是，若存在 $[a_i, a_{i+1})$ 使得 $[l_j, r_j) \subseteq [a_i, a_{i+1})$，那么数据分块鸡将会用该块内存储的元素总和减去不在询问区间内的元素总和以求得答案，需要花费 $(l_j - a_i) + (a_{i+1} - r_j)$ 的代价；</li>
<li>如果不是上面任何一种情况，那么询问区间一定会跨越多个块。对于每一块：<ul><li>首先如果 $[a_i, a_{i+1}) \subseteq [l_j, r_j)$，那么这一整块的元素总和将会被加进答案，需要花费 $1$ 的代价。</li>
<li>除此之外，如果 $[a_i, a_{i+1})$ 与 $[l_j, r_j)$ 有交，那么 $[l_j, r_j)$ 肯定是覆盖了该块的一个前缀或一个后缀。此时数据分块鸡会在如下两种计算方法里进行抉择，选取代价最小的计算方法：<ul><li>要么直接求和计算，花费的代价为两个区间交集的元素个数；</li>
<li>要么拿块内元素总和减去不在询问区间内的元素总和，花费的代价为该块内包含的元素个数减去两个区间交集的元素个数。</li>
</ul></li>
</ul></li>
</ul><p>最后总代价为每步的代价之和。</p>
<p>现在，给你 $n$ 和这 $q$ 个询问，请你帮数据分块鸡决定分块的分界点使得总代价最小吧！</p>

# 输入格式


<p>第一行两个正整数 $n, q$。</p>
<p>接下来 $q$ 行，每行三个整数 $l_i, r_i$，表示询问区间 $[l_i, r_i)$，保证 $1 \le l_i &lt; r_i \le n$。</p>

# 输出格式


<p>输出共一行，一个整数表示最小代价。</p>

# 样例一


<h4>input</h4>
<pre>5 10
1 3
1 3
1 2
3 5
2 4
3 4
1 2
2 5
2 5
4 5

</pre>

<h4>output</h4>
<pre>13

</pre>

<h4>explanation</h4>
<p>最优方案为选取集合 $\{1, 3, 5\}$。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务编号</th>
<th>分值</th>
<th>$n$</th>
<th>$q$</th>
</tr></thead><tbody><tr><td>1</td><td>20</td><td>$\le 300$</td><td>$\le 300$</td></tr><tr><td>2</td><td>20</td><td>$\le 3000$</td><td>$\le 3000$</td></tr><tr><td>3</td><td>20</td><td>$\le 50000$</td><td>$\le 5$</td></tr><tr><td>4</td><td>40</td><td>$\le 50000$</td><td>$\le 10^5$</td></tr></tbody></table></div>

<p>对于所有数据，保证 $n \ge 2$。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=285">样例数据下载</a></p>