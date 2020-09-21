
# 题目描述

已知多项式方程：

$$a_0+a_1x+a_2x^2+\cdots+a_nx^n=0$$

求这个方程在 $[1,m]$ 内的整数解（$n$ 和 $m$ 均为正整数）。

# 输入格式

输入共 $n + 2$ 行。  
第一行包含 $2$ 个整数 $n, m$，每两个整数之间用一个空格隔开。  
接下来的 $n+1$ 行每行包含一个整数，依次为 $a_0,a_1,a_2\ldots a_n$。

# 输出格式

第一行输出方程在 $[1,m]$ 内的整数解的个数。

接下来每行一个整数，按照从小到大的顺序依次输出方程在 $[1,m]$ 内的一个整数解。

# 样例

#### 样例输入 1
```plain
2 10 
1
-2
1
```

#### 样例输出 1
```plain
1
1
```

#### 样例输入 2
```plain
2 10
2
-3
1
```

#### 样例输出 2
```plain
2
1
2
```

#### 样例输入 3
```plain
2 10
1
3
2
```

#### 样例输出 3
```plain
0
```

# 数据范围与提示

对于 $30\%$ 的数据：$0<n\le 2,|a_i|\le 100,a_n≠0,m<100$。  
对于 $50\%$ 的数据：$0<n\le 100,|a_i|\le 10^{100},a_n≠0,m<100$。  
对于 $70\%$ 的数据：$0<n\le 100,|a_i|\le 10^{10000},a_n≠0,m<10^4$。  
对于 $100\%$ 的数据：$0<n\le 100,|a_i|\le 10^{10000},a_n≠0,m<10^6$。  
