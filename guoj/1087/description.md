
# 题目描述

现在有一个长度为 $N$ 的字符串 $S$ ，描述了一行 $N$ 个格子。

其中 $S[i](i \in [1,N])$ 有三种取值：

- `.` 表示第 $i$ 个格子为空。
- `#` 表示第 $i$ 个格子上有一个炮塔。
- `*` 表示第 $i$ 个格子上有一个干扰器。

一开始你在第一个格子，保证为空。

你有一个容量无限的背包。

每个时刻，你可以往左走或往右走，或者将干扰器装入背包(如果当前位置上有干扰器)，或者在当前位置放下一个干扰器(如果当前位置为空且背包非空)，或者什么都不干。

如果某次操作结束后，当前位置上有炮塔，且不存在相邻位置上有干扰器，则你会被炮塔打死。

请问在经过无限时间之后的一个时刻，你最多能持有多少干扰器(即这个时刻在包里的干扰器)。


# 输入格式

多组数据。

第一行一个整数 $T$ 表示数据组数。

接下来 $T$ 行，每行一个字符串 $S_i$ ，意义见题面描述。

# 输出格式

$T​$ 行，每行一个数表示答案。

# 样例

#### 样例输入

```plain
3
...**.*..*....*..
.#.**.*..*....*..
..#**.*..*.#..*..
```

#### 样例输出

```plain
5
0
5
```

#### 样例解释

对于第一组数据，显然你可以拿到所有干扰器。

对于第二组数据，你如果往右走就会被打死，因此你无法进行任何操作。

对于第三组数据，由于第一个炮塔存在相邻的干扰器，因此你可以经过第一个炮塔，然后拿走前 $4$ 个干扰器，接下来你可以在第二个炮塔左边放下一个干扰器，然后经过第二个炮塔，拿走第 $5$ 个干扰器，然后再反向经过第二个炮塔，拿回之前放下的干扰器，此时就拿到了全部干扰器。

# 数据范围与提示

- 对于所有数据，令 $N_i$ 表示 $S_i$ 的长度：
  - $T \le 100​$ 。
  -  $\forall i，1 \le N_i \le 4 \times 10^5$ 
  -  $\displaystyle \sum_{i=1}^{T}N_i \le 3 \times 10^6$  。
- 时间限制 $1s​$ ，空间限制 $512MB​$ 。
- $subtask1(20pts):​$ 不存在 `#` 后面为 `*` 。
- $subtask2(20pts):​$ 不存在 `#` 后面为 `#` 。
- $subtask3(20pts): \forall i，N_i \ge 3$ 且 $S_i[2]=S_i[3]=​$ `*`。
- $subtask4(20pts):T=1,N_1 \le 100$ 。
- $subtask5(20pts):​$ 无额外限制。

命题人：kcz

