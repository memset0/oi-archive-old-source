
# 题目描述

zjd 最近迷上了更衣室大战，于是他看着哲学的画面想到了一个美(gān)妙(gà)的问题：

有一个更衣室，大汉们一个一个进去。开始时更衣室里有 $n$ 个大汉。每个大汉有一个愉悦值 $a_i$，最后进来的大汉会选择和前若干个大汉讨论学术问题，若他与 $p$ 至 $n-1$ 这些大汉一起讨论一个愉悦值为 $x$ 的哲学会获得 $a_p\oplus a_{p+1}\oplus\ldots\oplus a_{n}\oplus x$ 的真实愉悦。

之后有 $m$ 个操作：

1. `A x`：添加操作，表示在序列末尾添加一个愉悦值为 $x$ 的大汉，使得更衣室里人数 $n$ 增加 $1$。
2. `Q l r x`：询问操作，你需要找到一个位置 $p(l\leq p\leq r)$，使得：第 $p$ 到 $n$ 位大汉一起讨论愉悦值为 $x$ 的哲学并使获得的真实愉悦最大，输出最大是多少。

其中，$\oplus$为 C++ 中的异或(`^`)运算，它的运算结果是数字中的每一个二进制位做逻辑异或后得到的值。

# 输入格式

第一行包含两个整数 $n,\ m(1\leq n,\ m<=3\times 10^5)$，含义如问题描述所示。

第二行包含 $n$ 个非负整数，表示初始的愉悦值 $a_i(0\leq a_i\leq 10^7)$。

接下来 $m$ 行，每行描述一个操作，格式如题面所述。

# 输出格式

对于每一个询问操作输出一行一个整数表示询问的答案。

# 样例

#### 样例输入

```plain
5 5
2 6 4 3 6
A 1
Q 3 5 4
A 4
Q 5 7 0
Q 3 6 6
```

#### 样例输出

```plain
4
5
6
```

# 数据范围与提示



