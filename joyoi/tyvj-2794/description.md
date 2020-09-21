# 

 
 # 题目描述 
<p>
一个XOR门包含两个输入和一个输出，它的工作可以用下表描述：

 
 # 输入格式 
<p>
文件第一行包含三个整数，分别表示输入的个数，门的个数，连接到输出的门的编号。以下的m行描述网络中的连接情况。第I行表示第I个门的两个输入，两个输入为范围[-n,m]之间的一个整数。如果输入是网络的第k个输入，则连接的描述是一个整数－k，如果输入是第j个门，则连接的描述是一个整数j。以下两行各有一个n位二进制串，表示输入的上限和下限。</p> 

 
 # 输出格式 
<p>
输出文件包含一个整数，表示给定范围内有多少种输入可以使输出为1。</p> 
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
<tr><td>5 6 5
-1 -2
1 3
1 -2
2 -3
4 6
-4 -5
00111
01110
</td><td>5</td></tr></table>