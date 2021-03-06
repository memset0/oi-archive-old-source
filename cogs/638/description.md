# 题目描述


<p>
【问题描述】
</p>
<p>
有两种类型的职业摔跤手：一种是“好选手”，另一种是“差选手”。对于任何一对职业摔跤手来说，他们中可能有、<u><b>也可能没有</b></u>比赛。假定有 n 位职业摔跤手，并且有一份清单，上面列出了 r 对参加比赛的摔跤手。写一个程序,它能够确定是否可能指定某些摔跤手为好选手，而将余下的摔跤手指定为坏选手，从而使得每一场比赛都是在一个好选手与一个差选手之间进行。如果有可能做出这样的指定，你的程序就应该将它产生出来，否则输出无解“No”。
</p>
<p>
【输入格式】
</p>
<p>
第1行有三个整数n，r。n是职业摔跤手的数量，r是比赛场数，它们之间用一个空格隔开。
</p>
<p>
接下来的r行，每行用两个数V<sub>1</sub>，V<sub>2</sub>表示V<sub>1</sub>号摔跤手与V<sub>2</sub>号摔跤手比赛，选手从1开始编号。
</p>
<p>
【输出格式】
</p>
<p>
输出有两行，第一行“好选手”的编号，第二行为“差选手”的编号，编号之间用一个空格隔开。
</p>
<p>
注意：为了鼓励选手，使输出答案唯一，请尽量多的将选手设为“好选手”，并且在可行条件下选择编号小的选手为“好选手”。
</p>
<p>
如果无解，则输出一行“No”。
</p>
<p>
【输入输出样例】
</p>
<pre>rassle.in
4 4
1 2
1 4
2 3
3 4
</pre>
<pre>rassle.out
1 3
2 4
</pre>
<p>
【数据范围】
</p>
<p>
n&lt;=10000, r&lt;=10000
</p>
