# 

 
 # 题目背景 
Freda的城堡——<BR>“Freda，城堡外发现了一些入侵者！”<BR>“喵...刚刚探究完了城堡建设的方案数，我要歇一会儿嘛lala~”<BR>“可是入侵者已经接近城堡了呀！”<BR>“别担心，rainbow，你看呢，这是我刚设计的导弹防御系统的说~”<BR>“喂...别卖萌啊……” 

 
 # 题目描述 
Freda控制着N座可以发射导弹的防御塔。每座塔都有足够数量的导弹，但是每座塔每次只能发射一枚。在发射导弹时，导弹需要T1秒才能从防御塔中射出，而在发射导弹后，发射这枚导弹的防御塔需要T2分钟来冷却。<BR>所有导弹都有相同的匀速飞行速度V，并且会沿着距离最短的路径去打击目标。计算防御塔到目标的距离Distance时，你只需要计算水平距离，而忽略导弹飞行的高度。导弹在空中飞行的时间就是&nbsp;(Distance/V)&nbsp;分钟，导弹到达目标后可以立即将它击毁。<BR>现在，给出N座导弹防御塔的坐标，M个入侵者的坐标，T1、T2和V，你需要求出至少要多少分钟才能击退所有的入侵者。 

 
 # 输入格式 
第一行五个正整数N,M,T1,T2,V。<BR>接下来M行每行两个整数，代表入侵者的坐标。<BR>接下来N行每行两个整数，代表防御塔的坐标。 

 
 # 输出格式 
输出一个实数，表示最少需要多少分钟才能击中所有的入侵者，四舍五入保留六位小数。 

 
 # 提示 
对于40%的数据，N,M&lt;=20.<BR>对于100%的数据，&nbsp;1≤N≤50,&nbsp;1≤M≤50，坐标绝对值不超过10000，T1,T2,V不超过2000. 
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
<tr><td>3 3 30 20 1
0 0
0 50
50 0
50 50
0 1000
1000 0
</td><td>91.500000
</td></tr></table>
