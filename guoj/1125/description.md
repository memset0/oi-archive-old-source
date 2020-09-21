
# 题目描述

*“普通的欧几里得，*

*稀有的扩展欧几里得，*

*史诗的类欧几里得，*

*金色……传说。”*

试求$\sum_{x=1}^L A^xB^{\lfloor \frac{Px+R}{Q} \rfloor}$，其中$A, B$是$N$行$N$列的矩阵。

# 输入格式

第一行五个空格隔开的非负整数$P, Q, R, L, N$，其中$P, Q, L, N$均不为$0$。

接下来$N$行，每行$N$个空格隔开的非负整数，其中第$i$行的第$j$个数表示$A_{i, j}$。

接下来$N$行，每行$N$个空格隔开的非负整数，其中第$i$行的第$j$个数表示$B_{i, j}$。

# 输出格式

共$N$行，每行$N$个空格隔开的非负整数，其中第$i$行的第$j$个数表示$C_{i, j}$模$998244353$，其中$C$是答案矩阵。

# 样例

**样例 1 输入**
```
8 5 2 3 1
1
2
```

**样例 1 输出**
```
44
```

**样例 2 输入**
```
998244353 654321321 1234567 512 2
123 345
101 233
765 234
606 723
```

**样例 2 输出**
```
359941153 675459034
50358289 228823864
```

本题有附加样例，请自行下载。

# 数据范围与提示

对于$10\%$的数据，$L \leq 10^6, N = 1, A_{1, 1} = 1, R = 0$；

对于$40\%$的数据，$L \leq 10^{18}, N = 1, A_{1, 1} = 1, R = 0$；

对于$60\%$的数据，$L \leq 10^{18}, N = 1, A_{1, 1} = 1$；

对于$80\%$的数据，$L \leq 10^{18}, N \leq 20$，且$A$是单位矩阵；

对于$100\%$的数据，$L \leq 10^{18}, N \leq 20$；

对于$100\%$的数据，$P, Q, R, \lfloor \frac{PL}{Q} \rfloor \leq 10^{18}, 0 \leq A_{i, j}, B_{i, j} < 998244353$。

来源：HNOI 2018 省队集训 Day 7 T3
