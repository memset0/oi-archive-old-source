# 题目描述


<p>
在威斯康星州每年万圣节前夕奶牛们要通过盛装打扮和收集糖果进行庆祝，农夫约翰把奶牛们留在了他的N (1 &lt;= N &lt;= 100,000)个牛栏中。
</p>
<p>
因为牛栏不是足够的大，约翰让奶牛按指定的路线在牛栏间行走。他在牛栏i布置下一个牛栏号next_i (1 &lt;= next_i &lt;= N)，以告诉奶牛要怎么行走到下一个牛栏。奶牛需要这样行走以搜集更多的糖果。
</p>
<p>
约翰要求奶牛i从i号牛栏开始行走搜集糖果。一头奶牛一旦返回她访问过的牛栏时将停止行走。
</p>
<p>
计算每头奶牛访问过的牛栏数，也就是每头奶牛曾经搜集糖果的位置数。
</p>
<p>
输入格式：
</p>
<p>
  第一行：一个单独的整数N
</p>
<p>
  第2..N+1行：第i+1行包含一个单独的整数next_i
</p>
<p>
SAMPLE INPUT (file treat.in):
</p>
<p>
4
</p>
<p>
1
</p>
<p>
3
</p>
<p>
2
</p>
<p>
3
</p>
<p>
<br/>
</p>
<p>
输入解释:
</p>
<p>
<br/>
</p>
<p>
四个牛栏.
</p>
<p>
 * 牛栏 1 直接让奶牛返回 牛栏 1.
</p>
<p>
 * 牛栏 2 让奶牛去 牛栏 3
</p>
<p>
 * 牛栏 3 让奶牛去 牛栏 2
</p>
<p>
 * 牛栏 4 让奶牛去 牛栏 3
</p>
<p>
<br/>
</p>
<p>
输出格式:
</p>
<p>
* 第1..N行: 行 i 包含一个单独的整数表示曾经访问牛栏的总数
</p>
<p>
SAMPLE OUTPUT (file treat.out):
</p>
<p>
1
</p>
<p>
2
</p>
<p>
2
</p>
<p>
3
</p>
<p>
输出解释:
</p>
<p>
奶牛1: 开始于 1, 下一个是 1. 总共访问数是 1.
</p>
<p>
奶牛2: 开始于 2, 下一个是 3, 下一个是 2. 总共访问数是 2.
</p>
<p>
奶牛3: 开始于 3, 下一个是 2, 下一个是 3. 总共访问数是 2.
</p>
<p>
奶牛4: 开始于 4, 下一个是 3, 下一个是 2, 下一个是 3. 总共访问数是 3.
</p>
