# 

 
 # 题目描述 
<p>
Byte City 的街道形成了一个标准的棋盘网络 – 他们要么是北南走向要么就是西东走向. 北南走向的路口从 1 到 n编号, 西东走向的路从1 到 m编号. 每个路口用两个数(i, j) 表示(1 <= i <= n, 1 <= j <= m). 

 
 # 输入格式 
<p>
第一行三个数n, m 和 k – 表示北南走向的路的个数以及西东走向的路和乘客等车的站点的个数. ( 1 <= n <= 10^9, 1 <= m <= 10^9, 1 <= k <= 10^5). 

 
 # 输出格式 
<p>
一个数表示最多能接到的乘客数量. 
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
<tr><td>8 7 11
4 3 4
6 2 4
2 3 2
5 6 1
2 5 2
1 5 5
2 1 1
3 1 1
7 7 1
7 4 2
8 6 2
</td><td>11