# 

 
 # 题目描述 
<p>
火星探险问题（mars.cpp/c/pas）<br><br>【问题描述】<br><br>　　火星探险队的登陆舱将在火星表面着陆，登陆舱内有多部障碍物探测车。登陆舱着陆后，探测车将离开登陆舱向先期到达的传送器方向移动。探测车在移动中还必须采集岩石标本。每一块岩石标本由最先遇到它的探测车完成采集。每块岩石标本只能被采集一次。岩石标本被采集后，其他探测车可以从原来岩石标本所在处通过。探测车不能通过有障碍的地面。本题限定探测车只能从登陆处沿着向南或向东的方向朝传送器移动，而且多个探测车可以在同一时间占据同一位置。如果某个探测车在到达传送器以前不能继续前进，则该车所采集的岩石标本将全部损失。<br><br>【编程任务】<br>　　用一个P×Q 网格表示登陆舱与传送器之间的位置。登陆舱的位置在(X1,Y1)处，传送器的位置在(XP ,YQ)处。<br><br><center><img src="/source/joyoi/tyvj-3218/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzIxOC9wcm9ibGVtc19pbWFnZXMvMTYyNi9wMS5naWY=.gif"></img></center><br>　　给定每个位置的状态，计算探测车的最优移动方案，使到达传送器的探测车的数量最多，而且探测车采集到的岩石标本的数量最多。</p> 

 
 # 输入格式 
<p>
由文件mars.in提供输入数据。<br>　　文件的第1行为探测车数，第2 行为P的值，第3 行为Q 的值。接下来的Q 行是表示登陆舱与传送器之间的位置状态的P×Q 网格。用3 个数字表示火星表面位置的状态：0 表示平坦无障碍，1表示障碍，2 表示石块。</p> 

 
 # 输出格式 
<p>
程序运行结束时，将每个探测车向传送器移动的序列输出到文件mars.out 中。<br>　　每行包含探测车号和一个移动方向，0 表示向南移动，1 表示向东移动。</p> 
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
10
8
0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 1 1 0 0 0
0 0 0 1 0 2 0 0 0 0
1 1 0 1 2 0 0 0 0 1
0 1 0 0 2 0 1 1 0 0
0 1 0 1 0 0 1 1 0 0
0 1 2 0 0 0 0 1 0 0
0 0 0 0 0 0 0 0 0 0</td><td>1 1
1 1
1 1
1 1
1 0
1 0
1 1
1 0
1 0
1 0
2 1
2 1
2 1
2 1
2 0
2 0
2 0
2 0
2 1
2 0
2 0
2 1
2 0
2 1
2 1
2 1</td></tr></table>
