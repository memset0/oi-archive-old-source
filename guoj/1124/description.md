
# 题目描述

*“三种选择都没戏，*

*分岔路口难救命，*

*天要我输我不语，*

*下个悲剧就是你。”*

给定一棵树，多次询问从一个点移动到另一个点的最优策略下的期望步数。

你有两种移动方法：沿着一条边，从一端走到另一端，花费一步；或者均匀随机地选择一个点，移动到那里，花费一步。

# 输入格式

第一行，两个空格隔开的正整数$n, q$，表示树的点数和询问的次数。

接下来$n-1$行，每行两个空格隔开的正整数$x, y$，表示有一条连接第$x$个点和第$y$个点的边。

接下来$q$行，每行两个空格隔开的正整数$x, y$，表示该次询问从第$x$个点移动到第$y$个点。

# 输出格式

共$q$行，每行一个实数，表示该次询问最优策略下的期望步数。

当你的答案与标准答案的绝对误差不超过$10^{-6}$时，即认为正确。

# 样例

**样例 1 输入**
```
4 4
1 2
2 3
3 4
1 1
1 2
1 3
1 4
```

**样例 1 输出**
```
0.00000000
1.00000000
2.00000000
2.33333333
```

本题有附加样例，请自行下载。

# 数据范围与提示

对于$20\%$的数据，$n \leq 5, q \leq 10$；

对于$50\%$的数据，$n \leq 1,000, q \leq 2,000$；

对于另$20\%$的数据，树退化为一条链；

对于$100\%$的数据，$n \leq 100,000, q \leq 200,000$；

对于$100\%$的数据，$x, y \leq n$，保证给出的树合法。

来源：HNOI 2018 省队集训 Day 7 T2
