# 

 
 # 题目描述 
此次NOIP中，不知道是由于晚饭克星的存在，还是其他生物的影响，一直迟迟没找到报名地点。就在万分无奈之际，DL的老师似乎得到不明生物的指示，收到了一大堆的数字。<BR>	MMOIer发现，原来这大堆数字是用一种失败的加密方式得到的数字串。每组数字串有三个数字a,b,n。表示该组代表的数字是a/b的第n位。另外，我们把东为x轴正方向，北为y轴正方向，则每个数字代表的含义如下：（@表示车原来的位置，对应位置上的数字代表走到该位置上）：<BR>	#5##0<BR>	7#1##<BR>	#4@2#<BR>	##3#6<BR>	9##8#<BR>如密码'1'表示向北移动一格。密码'6'表示向东移动2格，然后向南移动一格。<BR>我们现在需要求出每组数字串代表的字符，然后求出按照这些密码的指示最后会到达的位置。假设车辆在(0,0)的位置出发。<BR><BR> 

 
 # 输入格式 
文件第一行两个数，N。<BR>以下有N行，每行有3个正整数a,b,n。<BR><BR> 

 
 # 输出格式 
输出文件有两行，第一行依次为每组数据对应的密码(不用空格隔开)。最后一行则是最后到达的位置，格式用坐标的形式。参见样例。<BR> 

 
 # 提示 
2/7=&nbsp;0.2857142……&nbsp;小数点后第3位是5,来到了(-1,2)<BR>14/7=2.000000……&nbsp;小数点后第4位是0,来到了（1,4）;<BR><BR>第1~3&nbsp;个点，k1+k2..+kn&lt;150000<BR>第4~5&nbsp;个点，b&lt;32767,n&lt;120<BR>第6~10个点，n&lt;1500,m&lt;120,0&lt;a,b,k&lt;10^9,全部数据保证合法。<BR><BR><BR> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>2
2 7 3
14 7 4

</td><td>50
(1,4)

</td></tr></table>