
# 题目描述

大中锋的学院要组织学生参观博物馆，要求学生们在博物馆中排成一队进行参观。  
他的同学可以分为四类：一部分最喜欢唱、一部分最喜欢跳、一部分最喜欢 rap，还有一部分最喜欢篮球。

如果队列中 $k,k + 1,k + 2,k + 3$ 位置上的同学依次，最喜欢唱、最喜欢跳、最喜欢 rap、最喜欢篮球，那么他们就会聚在一起讨论蔡徐坤。  
大中锋不希望这种事情发生，因为这会使得队伍显得很乱。

大中锋想知道有多少种排队的方法，不会有学生聚在一起讨论蔡徐坤。  
两个学生队伍被认为是不同的，当且仅当两个队伍中至少有一个位置上的学生的喜好不同。  
由于合法的队伍可能会有很多种，种类数对 $998244353$ 取模。

# 输入格式

输入数据只有一行。  
每行 $5$ 个整数，第一个整数 $n$，代表大中锋的学院要组织多少人去参观博物馆。  
接下来四个整数 $a、b、c、d$，分别代表学生中最喜欢唱的人数、最喜欢跳的人数、最喜欢 rap 的人数和最喜欢篮球的人数。  
保证 $a + b + c + d ≥ n$。 

# 输出格式

每组数据输出一个整数，代表你可以安排出多少种不同的学生队伍，使得队伍中没有学生聚在一起讨论蔡徐坤。结果对 $998244353$ 取模。

# 样例

#### 样例输入 1
```plain
4 4 3 2 1
```

#### 样例输出 1
```plain
174
```

#### 样例输入 2
```plain
996 208 221 132 442
```

#### 样例输出 2
```plain
442572391
```

# 数据范围与提示

对于 $20\%$ 的数据，有 $n = a = b = c = d ≤ 500$；  
对于 $100\%$ 的数据，有 $n ≤ 1000,a,b,c,d ≤ 500$。
