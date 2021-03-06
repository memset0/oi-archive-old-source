
# 题目描述

小雅米有一张 $n$ 个点的无向图，刚刚学会了可达矩阵的小雅米计算了这张图的可达矩阵。然而贪玩的小雅米弄丢了这张无向图，他只依稀记得这张图的边数很少。现在他急得哇哇大哭，现在希望你帮助小雅米得到一张可达矩阵与原来相同且边数最少的图。

# 输入格式

第一个一个正整数 $n(1 \leq n \leq 100)$，代表图中点的数量。

下面 $n$ 行每行 $n$ 个非负整数，其中第 $i$ 行第 $j$ 个整非负数 $d_{i,j} = 1$ 表示顶点 $i$ 与顶点 $j$ 相连通，$d_{i,j} = 0$ 表示顶点 $i$ 与顶点 $j$ 不连通。

数据保证对于任意 $i,j$ 都有$d_{i,j}=d_{j,i}$ 且 $d_{i,j}\in\{0,1\}$，并且对于任意 $i$ 都有 $d_{i,i}=1$

# 输出格式

第一行一个正整数 $m$ 代表你构造的图的边数。

下面 $m$ 行，每行两个正整数 $u,v(1 \leq u,v \leq n)$ 代表 $u$ 与 $v$ 之间有一条边。

注意当你输出的 $m$ 大于最少需要的边数或输出不满足格式要求时会被直接判定为 "Wrong Answer"。

# 样例

#### 输入样例

```plain
3
1 1 1
1 1 1
1 1 1
```

#### 输出样例

```plain
2
1 2
2 3
```

# 数据范围与提示



