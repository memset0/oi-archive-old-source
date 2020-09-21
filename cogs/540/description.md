# 题目描述


<p>
【问题描述】
</p>
<p>
贝希被困在一个三角形的迷宫之中。这个迷宫有N行（1 &lt;= N &lt;= 1000000）。比如下图是一个3行的迷宫。
</p>
<p align="center">
<br/>
<img alt="" src="http://www.lydsy.com/JudgeOnline/images/1772_1.jpg" height="224" width="273"/>
</p>
<p>
迷宫的第i行有2*i-1个三角形，从左到右分别编号为（i，1）、（i，2）等等。
</p>
<p>
贝希每次可以从一个三角形走到任意一个一个跟当前的三角形有邻边的三角形。比如说，如果她目前处于三角形（3，3），那么，她可以走到三角形（3，2）、（3，4）和（4，4）。贝希每次需要一分钟的时间来移动到下一个三角形。
</p>
<p align="center">
<img alt="" src="http://www.lydsy.com/JudgeOnline/images/1772_2.jpg" height="230" width="349"/><br/>
 
</p>
<p>
农夫约翰发现贝希被困了！于是她跟踪贝希的iPhone手机（可怜的触摸屏～），得知贝希目前处于三角形（Si，Sj）。因为约翰对贝希有着无穷无尽的浓浓爱意，所以他希望贝希能尽可能快地回到他的身边。
</p>
<p>
在迷宫的三角形之中，有M（1 &lt;= M &lt;= 10000）个是出口。在任何一个出口都可以让贝希逃离迷宫。一旦贝希进入一个作为出口的三角形，她用多一分钟就可以逃离这个迷宫。
</p>
<p>
找到一个可以让贝希逃离迷宫最小时间T，并输出她应该从哪一个出口逃离迷宫，这个出口记为（OUTi，OUTj）。如果有多个出口同时需要时间T，输出那个行的编号小的出口，如果仍然有多个出口，输出那个列的编号小的。
</p>
<p>
输入格式
</p>
<p>
＊第一行：两个由空格隔开的整数：N和M。
</p>
<p>
＊第二行：两个由空格隔开的整数：Si和Sj。
</p>
<p>
＊第三到第M+2行：第i+2行有两个由空格隔开的整数Ei和Ej，表示三角形（Ei，Ej）是出口。
</p>
<p>
样例输出：
</p>
<p>
4 2<br/>
2 1<br/>
3 5<br/>
4 4
</p>
<p>
输出格式：
</p>
<p>
＊第一行：两个由空格隔开的整数：OUTi和OUTj。
</p>
<p>
＊第二行：一个单独的整数：T。
</p>
<p>
样例输出：
</p>
<p>
4 4<br/>
4<br/>
 
</p>