# 题目描述


<p>
裁缝有一块非常珍贵的丝绸围巾。可惜的是，围巾的某些部分已经被蛀虫给咬坏了。裁缝当然不愿意就这么把围巾给丢了，于是，他想把围巾给裁成两块小围巾送给他的两个女儿。自然，两块小围巾的面积之和越大越好。
</p>
<p>
这块围巾是一个正三角形，三条边被均匀地分成了N段，即这个正三角形被均匀地分成了N<sup>2</sup>个单元，每个单元是一个面积为1的正三角形。图一所 示为一个N=5的围巾，图中带阴影的单元表示被蛀虫咬坏的部分。从上往下看，围巾被分成了N行，第一行有1个单元，第二行有3个单元，其中有2个是形如D 的，有1个是形如Ñ 的（这两种三角形我们认为是形状相同的）。第三行有5个，其中有3个是形如D 的，有2个是形如Ñ 的…… 。用坐标（X,Y）给每个单元定位，第一行的单元的坐标为（1,1）；第二行从左到右的三个单元的坐标依次为（2,1）、（2,2）、（2,3）；…。
</p>
<p>
<a href="../../wiki/Image:Scarfcut.jpg"><img alt="Image:Scarfcut.jpg" src="../../mw/images/4/45/Scarfcut.jpg" border="0" height="131" width="253"/></a> 
</p>
<p>
围巾的剪裁条件如下：
</p>
<ol>
<li>
裁成的两块小围巾形状与原来的大围巾完全相同，都是正三角形。
</li>
<li>
每一块小围巾里都不存在被蛀虫咬坏的部分。
</li>
<li>
裁剪时必须沿着单元的边界裁剪。
</li>
<li>
要求两块小围巾的面积的总和最大。
</li>
</ol>
<p>
图中，最优的裁剪方法已经用粗线画了出来，面积和为4+9=13。
</p>
<p>
现在需要你编一个程序来帮助裁缝解决这个问题。
</p>
<p>
输入
</p>
<p>
输入文件第一行为一个整数N（1&lt;=N&lt;=100），表示这块围巾总共被分成了N2个单元。第二行为一个整数M（0&lt;= M&lt;=N2-2），表示这块围巾共有M个单元被蛀虫咬坏了。接下的M行，每一行有两个正整数X和Y，为这M个被蛀虫咬坏的单元的坐标。
</p>
<p>
输入文件中同一行相邻两项之间用一个或多个空格隔开。
</p>
<p>
输出
</p>
<p>
输出文件仅含一个整数，为你所找到的裁出两块小围巾面积总和的最大值。
</p>
<p>
样例输入
</p>
<pre>5
5
3 2
4 1
4 4
5 4
5 2
</pre>
<p>
样例输出
</p>
<pre>13
</pre>