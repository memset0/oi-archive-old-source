# 题目描述


<h3>
【题目描述】
</h3>
<p>
我们有n个城市，这些城市的关系组成了一棵有根树，首都是树根
</p>
<p>
要求你支持以下操作：
</p>
<p>
第i个操作有以下两种形式：
</p>
<p>
1、1 u 表示在第i个时刻u这个城池被野蛮人的军队暴揍了一顿
</p>
<p>
2、2 u v k val
</p>
<p>
这个操作表示国王将从u城池走到v城池，但是这个国王是处女座
</p>
<p>
所以他只会在没有被揍过的城市或者这个城市被揍的时刻&lt;=val的城市中停留休息
</p>
<p>
又因为这个国王很懒，所以他能休息就一定会休息
</p>
<p>
现在国王希望每次出行前都能知道他第k个休息的城市的编号是多少
</p>
<p>
如果他休息不足k次就可以到达v城池，请输出-1
</p>
<p>
由于野蛮人很奇怪，所以野蛮人不会暴揍一个城池两次或两次以上
</p>
<p>
注意国王并不会在起点和终点休息
</p>
<h3>
【输入格式】
</h3>
<p>
第一行输入n表示节点数量
</p>
<p>
以下n个正整数分别表示每个城市的父亲，父亲为0的节点为首都
</p>
<p>
之后输入m表示操作次数
</p>
<p>
以下m个操作如题意所示
</p>
<p>
数据保证每个城池最多会被揍过一次
</p>
<p>
数据保证u!=v,数据保证当第i个操作是第二种操作时，0&lt;=val&lt;=i
</p>
<p>
数据保证n，m&lt;=100000
</p>
<h3>
【输出格式】
</h3>
<p>
对于第二种操作输出相应的答案
</p>
<h3>
【样例输入】
</h3>
<p>
样例输入1：
</p>
<p>
<br/>
</p>
<p>
3
</p>
<p>
0 1 2
</p>
<p>
5
</p>
<p>
2 1 3 1 0
</p>
<p>
1 2
</p>
<p>
2 1 3 1 0
</p>
<p>
2 1 3 1 1
</p>
<p>
2 1 3 1 2
</p>
<p>
样例输入2：
</p>
<p>
6
</p>
<p>
2 5 2 2 0 5
</p>
<p>
3
</p>
<p>
2 1 6 2 0
</p>
<p>
1 2
</p>
<p>
2 4 5 1 0
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
样例输出1：
</p>
<p>
2
</p>
<p>
-1
</p>
<p>
-1
</p>
<p>
2
</p>
<p>
样例输出2：
</p>
<p>
5
</p>
<p>
-1
</p>
<p>
<br/>
</p>