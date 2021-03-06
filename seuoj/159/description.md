
# 题目描述

2019 年 SEUCPC 春季赛到了。

出题人又在忙着出题了，这次他们一共准备了 $n$ 个备选题。

yky 发现，善良的出题人给每道题预估了一个难度 $a_i$。

命题组不限制比赛的题目数量，但为了保证每位选手们在赛场上有不错的比赛体验，命题组要求赛题的难度之和是 $n$ 的倍数。

如果有多种出题方案，命题组认为任意一种都是可行的。若不存在，则输出 `"-1"`（不含引号）。

命题组准备把锅丢给出题人，可出题人都忙着去出题了，所以命题组把这件重要的事情交给了赛场上的你。

# 输入格式

第一行一个整数 $n(1\leq n\leq 2\times 10^6)$，表示备选题的数量。

接下来 $n$ 行，每行一个整数 $a_i(1\leq a_i\leq 10^9)$，表示每道题的难度。

# 输出格式

第一行一个整数 $m(1\leq m\leq n)$ 表示出题的数量。

接下来 $m$ 行，每行一个整数 $b_i$，表示题目的编号。

如果有多种结果，输出任意一种即可。

若无解，仅输出一行 `"-1"`（不含引号）。

# 样例

#### 输入样例

```plain
4
3
2
5
9
```

#### 输出样例

```plain
2
1
3
```

#### 样例解释

对于样例，一共有 $4$ 道备选题，$4$ 道题的难度分别是 $3,\ 2,\ 5,\ 9$。其中的一种方案为选择 $1,\ 3$ 题，难度和为 $3+5=8$，为 $4$ 的倍数。


# 数据范围与提示



