# 题目描述


<h3>
【题目描述】
</h3>
<p>
摩尔瓦多的移动电话公司摩基亚（$Mokia$）设计出了一种新的用户定位系统。和其他的定位系统一样，它能够迅速回答任何形如“用户C的位置在哪？”的问题，精确到毫米。但其真正高科技之处在于，它能够回答形如“给定区域内有多少名用户？”的问题。
</p>
<p>
在定位系统中，世界被认为是一个$W \times W$的正方形区域，由$1 \times 1$的方格组成。每个方格都有一个坐标$(x,y)，1&lt;=x,y&lt;=W$。坐标的编号从$1$开始。对于一个$4 \times 4$的正方形，就有$1&lt;=x&lt;=4,1&lt;=y&lt;=4$（如图）：
</p>
<p>
<img src="/upload/image/20141020/20141020165440_68597.png" alt=""/> 
</p>
<p>
请帮助Mokia公司编写一个程序来计算在某个矩形区域内有多少名用户。
</p>
<h3>
【输入格式】
</h3>
<p>
有三种命令，意义如下：
</p>
<p>
</p><table style="width:100%;" cellspacing="0" cellpadding="2" bordercolor="#000000" border="1">
<tbody>
<tr>
<td>
命令
</td>
<td>
参数
</td>
<td>
意义
</td>
</tr>
<tr>
<td>
0
</td>
<td>
W
</td>
<td>
初始化一个全零矩阵。本命令仅开始时出现一次。
</td>
</tr>
<tr>
<td>
1
</td>
<td>
x y A
</td>
<td>
向方格$(x,y)$中添加A个用户。A是正整数。
</td>
</tr>
<tr>
<td>
2
</td>
<td>
X1 Y1 X2 Y2
</td>
<td>
查询$X1&lt;=x&lt;=X2，Y1&lt;=y&lt;=Y2$所规定的矩形中的用户数量
</td>
</tr>
<tr>
<td>
3
</td>
<td>
无参数
</td>
<td>
结束程序。本命令仅结束时出现一次。
</td>
</tr>
</tbody>
</table>
<p></p>
<h3>
【输出格式】
</h3>
<p>
对所有命令2，输出一个一行整数，即当前询问矩形内的用户数量。
</p>
<h3>
【输入样例】
</h3>
<p>
0 4
</p>
<p>
1 2 3 3
</p>
<p>
2 1 1 3 3
</p>
<p>
1 2 2 2
</p>
<p>
2 2 2 3 4
</p>
<p>
3
</p>
<h3>
【输出样例】
</h3>
<p>
3
</p>
<p>
5
</p>
<h3>
【提示】
</h3>
<p>
</p><table style="width:100%;" cellspacing="0" cellpadding="2" bordercolor="#000000" border="1">
<tbody>
<tr>
<td>
输入
</td>
<td>
输出
</td>
<td>
意义
</td>
</tr>
<tr>
<td>
0 4
</td>
<td>
<br/>
</td>
<td>
大小为$4 \times 4$的全零正方形
</td>
</tr>
<tr>
<td>
1 2 3 3
</td>
<td>
<br/>
</td>
<td>
向$(2,3)$方格加入3名用户
</td>
</tr>
<tr>
<td>
2 1 1 3 3
</td>
<td>
<br/>
</td>
<td>
查询矩形$1&lt;=x&lt;=3,1&lt;=y&lt;=3$内的用户数量
</td>
</tr>
<tr>
<td>
<br/>
</td>
<td>
3
</td>
<td>
查询结果
</td>
</tr>
<tr>
<td>
1 2 2 2
</td>
<td>
<br/>
</td>
<td>
向$(2,2)$方格加入2名用户
</td>
</tr>
<tr>
<td>
2 2 2 3 4
</td>
<td>
<br/>
</td>
<td>
查询矩形$2&lt;=x&lt;=3,2&lt;=y&lt;=4$内的用户数量
</td>
</tr>
<tr>
<td>
<br/>
</td>
<td>
5
</td>
<td>
查询结果
</td>
</tr>
<tr>
<td>
3
</td>
<td>
<br/>
</td>
<td>
终止程序
</td>
</tr>
</tbody>
</table>
<p></p>
<h3>
【数据规模】
</h3>
<p>
$1&lt;=W&lt;=2000000$
</p>
<p>
$1&lt;=X1&lt;=X2&lt;=W$
</p>
<p>
$1&lt;=Y1&lt;=Y2&lt;=W$
</p>
<p>
$1&lt;=x,y&lt;=W$
</p>
<p>
$0&lt;A&lt;=10000$
</p>
<p>
命令1不超过$160000$个。
</p>
<p>
命令2不超过$10000$个。
</p>
<h3>
【来源】
</h3>
<p>
Balkan Olypiad in Informatics 2007,$Mokia$
</p>