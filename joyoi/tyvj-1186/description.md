# 

 
 # 题目背景 
欧几里德旅行商(Euclidean&nbsp;Traveling&nbsp;Salesman)问题也就是货郎担问题一直是困扰全世界数学家、计算机学家的著名问题。现有的算法都没有办法在确定型机器上在多项式时间内求出最优解，但是有办法在多项式时间内求出一个较优解。<BR><BR>为了简化问题，而且保证能在多项式时间内求出最优解，J.L.Bentley提出了一种叫做bitonic&nbsp;tour的哈密尔顿环游。它的要求是任意两点(a,b)之间的相互到达的代价dist(a,b)=dist(b,a)且任意两点之间可以相互到达，并且环游的路线只能是从最西端单向到最东端，再单项返回最西端，并且是一个哈密尔顿回路。<BR> 

 
 # 题目描述 
著名的NPC难题的简化版本<BR><BR>现在笛卡尔平面上有n(n&lt;=1000)个点，每个点的坐标为(x,y)(-2^31&lt;x,y&lt;2^31，且为整数)，任意两点之间相互到达的代价为这两点的欧几里德距离，现要你编程求出最短bitonic&nbsp;tour。<BR> 

 
 # 输入格式 
第一行一个整数n<BR><BR>接下来n行，每行两个实数或整数x,y，表示某个点的坐标。<BR><BR>输入中保证没有重复的两点，<BR>保证最西端和最东端都只有一个点。<BR> 

 
 # 输出格式 
一行，即最短回路的长度，保留2位小数。<BR> 

 
 # 提示 
《算法导论（第二版）》&nbsp;15-1<BR> 
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
<tr><td>7
0 6
1 0
2 3
5 4
6 1
7 5
8 2
</td><td>25.58
</td></tr></table>
