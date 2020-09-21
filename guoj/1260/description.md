
# 题目描述

Z 国坐落于遥远而又神奇的东方半岛上，在小 Z 的统治时代公路成为这里主要的交通手段。 Z 国共有 $n$ 座城市，一些城市之间由双向的公路所连接。非常神奇的是 Z 国的每个城市所处的经度都不相同，并且**最多只和一个位于它东边的城市直接通过公路相连**。Z 国的首都是 Z 国政治经济文化旅游的中心，每天都有成千上万的人从 Z 国的其他城市涌向首都。

为了使 Z 国的交通更加便利顺畅， 小 Z 决定在 Z 国的公路系统中确定若干条<u><b>规划路线</b></u>，将其中的公路全部改建为铁路。

我们定义每条<u><b>规划路线</b></u>为一个长度大于 $1$ 的城市序列，每个城市**在该序列中最多出现一次**，序列中相邻的城市之间由公路直接相连(待改建为铁路)。并且，每个城市**最多只能出现在一条<u>规划路线</u>中**，也就是说，任意两条<u><b>规划路线</b></u>不能有公共部分。

当然在一般情况下是不可能将所有的公路修建为铁路的，因此从有些城市出发去往首都依然需要通过乘坐长途汽车，而**长途汽车只往返于公路连接的相邻的城市之间**， 因此从某个城市出发可能需要不断地换乘长途汽车和火车才能到达首都。

我们定义一个城市的“不便利值”为从它出发到首都需要乘坐的长途汽车的次数，而 Z 国的交通系统的“不便利值”为所有城市的不便利值的最大值，很明显首都的“不便利值”为 $0$。小 Z 想知道如何确定<u><b>规划路线</b></u>修建铁路使得 Z 国的交通系统的“不便利值” 最小， 以及有多少种不同的<u><b>规划路线</b></u>的选择方案使得“不便利值”达到最小。当然方案总数可能非常大，小 Z 只关心这个天文数字 $\operatorname{mod} Q$ 后的值。

注意：<u><b>规划路线</b></u> $1-2-3$ 和<u><b>规划路线</b></u> $3-2-1$ 是等价的，即将一条<u><b>规划路线</b></u>翻转依然认为是等价的。 两个方案不同当且仅当其中一个方案中存在一条<u><b>规划路线</b></u>不属于另一个方案。

# 输入格式

输入第一行包含三个正整数 $N$、$M$、$Q$，其中 $N$ 表示城市个数，$M$ 表示公路总数，$N$ 个城市从 $1\sim N$ 编号，其中编号为 $1$ 的是首都。$Q$ 表示上文提到的设计路线的方法总数的模数。 接下来 $M$ 行， 每行两个不同的正数 $a_i$、$b_i$ $(1\le a_i,b_i\le N)$ 表示有一条公路连接城市 $a_i$ 和城市 $b_i$。输入数据保证一条公路只出现一次。

# 输出格式

输出应包含两行。第一行为一个整数，表示最小的“不便利值”。 第二行为一个整数，表示使“不便利值”达到最小时不同的设计路线的方法总数 $\operatorname{mod} Q$ 的值。

如果某个城市无法到达首都，则输出两行 $-1$。

# 样例

#### 输入样例
```plain
5 4 100
1 2
4 5
1 3
4 1
```
#### 输出样例
```plain
1
10
```
#### 样例说明
以下样例中是 $10$ 种设计路线的方法：

(1) $4-5$  
(2) $1-4-5$  
(3) $4-5, 1-2$  
(4) $4-5, 1-3$  
(5) $4-5, 2-1-3$  
(6) $2-1-4-5$  
(7) $3-1-4-5$  
(8) $1-4$  
(9) $2-1-4$  
(10) $3-1-4$

# 数据范围与提示

#### 数据规模和约定

对于 $20\%$ 的数据，满足 $N,M\le 10$。

对于 $50\%$ 的数据，满足 $N,M\le 200$。

对于 $60\%$ 的数据，满足 $N,M ≤ 5000$。

对于 $100\%$ 的数据，满足 $1\le N,M\le 100000$，$1\le Q\le 120000000$。

#### 评分方式
每个测试点单独评分。对于每个测试点，第一行错则该测试点得零分，否则若第二行错则该测试点得到 $40\%$ 的分数。如果两问都答对，该测试点得到 $100\%$ 的分数。
