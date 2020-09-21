
# 题目描述

J 国有 $n$ 座城市，这些城市之间通过 $m$ 条单向道路相连，已知每条道路的长度。

一次，居住在 J 国的 Rainbow 邀请 Vani 来作客。不过，作为一名资深的旅行者，Vani 只对 J 国的 $k$ 座历史悠久、自然风景独特的城市感兴趣。  
为了提升旅行的体验，Vani 想要知道他感兴趣的城市之间「两两最短路」的最小值（即在他感兴趣的城市中，最近的一对的最短距离）。

也许下面的剧情你已经猜到了——Vani 这几天还要忙着去其他地方游山玩水，就请你帮他解决这个问题吧。

# 输入格式

每个测试点包含多组数据，第一行是一个整数 $T$，表示数据组数。注意各组数据之间是互相独立的。  
对于每组数据，第一行包含三个正整数 $n,m,k$，表示 J 国的 $n$ 座城市（从 $1 \sim n$ 编号），$m$ 条道路，Vani 感兴趣的城市的个数 $k$。  
接下来 $m$ 行，每行包括 $3$ 个正整数 $x,y,z$，表示从第 $x$ 号城市到第 $y$ 号城市有一条长度为 $z$ 的单向道路。注意 $x,y$ 可能相等，一对 $x,y$ 也可能重复出现。  
接下来一行包括 $k$ 个正整数，表示 Vani 感兴趣的城市的编号。

# 输出格式

输出文件应包含 $T$ 行，对于每组数据，输出一个整数表示 $k$ 座城市之间两两最短路的最小值。


# 样例

#### 样例输入
```plain
2
6 7 3
1 5 3
2 3 5
1 4 3
5 3 2
4 6 5
4 3 7
5 6 4
1 3 6
7 7 4
5 3 10
6 2 7
1 2 6
5 4 2
4 3 4
1 7 3
7 2 4
1 2 5 3
```

#### 样例输出
```plain
5
6
```

#### 样例解释
对于第一组数据，$1$ 到 $3$ 最短路为 $5$；$1$ 到 $6$ 最短路为 $7$；$3,6$ 无法到达，所以最近的两点为 $1,3$，最近的距离为 $5$。

对于第二组数据，$1$ 到 $2$ 最短路为 $6$；$5$ 到 $3$ 最短路为 $6$；其余的点均无法互相达，所以最近的两点为 $1,2$ 和 $5,3$，最近的距离为 $6$。

# 数据范围与提示

$2 \le k \le n,1 \le x,y \le n,1 \le z \le 2 \times 10^9,T ≤ 5$。

|测试点编号|$n$ 的规模|$m$ 的规模|约定|
|:-:|:-:|:-:|:-:|
|$1$|$\le 1,000$|$\le 5,000$|无|
|$2$|$\le 1,000$|$\le 5,000$|无|
|$3$|$\le 100,000$|$\le 500,000$|保证数据为有向无环图|
|$4$|$\le 100,000$|$\le 500,000$|保证数据为有向无环图|
|$5$|$\le 100,000$|$\le 500,000$|保证数据为有向无环图|
|$6$|$\le 100,000$|$\le 500,000$|无|
|$7$|$\le 100,000$|$\le 500,000$|无|
|$8$|$\le 100,000$|$\le 500,000$|无|
|$9$|$\le 100,000$|$\le 500,000$|无|
|$10$|$\le 100,000$|$\le 500,000$|无|
