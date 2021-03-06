
# 题目描述

小雅米最喜欢看别人打架了，不管谁赢了，她都会觉得舒服了。

现在有一个村庄，里面有许多住户，每家都有人打架，它们之间某些住户可以直达，整个村庄的所有住户呈树形结构。小雅米将按照一定的旅游路线到各家参观打架，每看完一家打架，她都会舒服一次。但每家住户都有一个上限：即如果小雅米在那里舒服超过了上限次，会引起别人的不舒服。如果小雅米发现下一个到的点的路径上有已经达到舒服上限的点，那么为了生命安全，她将结束这次旅游。初始时小雅米在 $1$ 号住户（$1$ 号点的打架也需要观看），请问小雅米最多能沿着旅游路线走多长？

# 输入格式

第一行输入一个整数 $n(1\leq n \leq 5 \times 10^5)$，表示村庄里住户的数目。 

第二行到第 $n$ 行，每行两个整数 $u, v(1 \leq u, v \leq n)$，表示住户 $u, v$ 之间可以直达。

第 $n + 1$ 行 $n$ 个整数，第 $i$ 个整数表示 $v_i(0 \leq v_i \leq 10^9)$ 每个住户可以舒服的上限。

第 $n + 2$ 行 $n$ 个整数 $u_1,u_2,u_3,\ldots,u_n(1\leq u_i\leq n)$，表示参观路线，第 $i$ 次的路线表示在树上从点 $u_{i - 1}$ 走到点 $u_i(1 \leq i \leq n)$，途径的所有点都必须参观，如果能沿着这条路走到 $u_i$ 点，算作成功完成长度为 $1$ 的旅游。

# 输出格式

输出一个整数，表示最多沿着旅游路线走多长。

# 样例

#### 样例输入1

```plain
6
1 2
1 3
2 4
2 6
3 5
4 4 3 1 1 1
4 3 6 2 5 1
```

#### 样例输出1

```plain
5
```

# 数据范围与提示



