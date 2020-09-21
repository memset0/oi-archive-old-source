
# 题目描述

白兔在玩游戏。

在一个$n * n$的棋盘中放入$n$个车，使得任意两个车不能互相可达（即不在同一行或同一列）。

白云要从$(1, 1)$出发，每一步可以往上下左右走一格，最终到达$(n, n)$。同时，它不能超出棋盘的边界，且不能走到有车的格子。

问白兔有多少种放车的方法使得白云能够达成目标。

# 输入格式

第一行一个整数$T$，表示数据组数。
接下来$T$行每行一个整数$n$表示询问。

# 输出格式

输出$n$行，每行一个整数表示答案。对$10^9 + 7$取模。

# 样例

**样例 1 输入**
```
5
1
2
3
4
5
```

**样例 1 输出**
```
0
0
2
12
70
```

# 数据范围与提示

对于$10\%$的数据，$n \leq 5$。

对于$40\%$的数据，$n \leq 15$。

对于$80\%$的数据，$n \leq 10^7$。

对于$100\%$的数据，$T \leq 500, n \leq 10^9$。

出题人：laofu

来源：HNOI 2018 省队集训 Day 2 T2
