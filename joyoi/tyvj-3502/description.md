# 

 
 # 题目描述 
<p>
最近，佳佳迷上了一款好玩的小游戏：antbuster。

 
 # 输入格式 
<p>
输入的第一行是2个用空格隔开的整数，n、m，分别表示了地图的长和宽。

 
 # 输出格式 
<p>
如果在第t秒或之前蚂蚁抢到了蛋糕，输出一行“Game over after x seconds”，其中x为游戏结束的时间，否则输出“The game is going on”。
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
<tr><td>3 5
1 1 2
2 2
5

</td><td>5
5 1 3 1 4
4 1 3 0 4
3 1 3 0 3
2 1 3 0 2
1 1 4 0 1

样例说明：
    3*5的地图，有1个单次伤害为1、攻击范围为2的激光炮塔，它的位置为（2，2），模拟游戏的前5秒。5秒内有5只蚂蚁出生，都是向东爬行，其中第1~4只在路过（0，2）点时被激光塔伤了1格血。在第5秒的时候，最早出生的蚂蚁按移动规则1~3本来该向东移动，但由于规则4的作用，它在发现向北和向西移动都会到达不可达点后，最终选择了向南移动。

数据说明：
100%的数据满足1 ≤ n,m ≤ 8，s ≤ 20，t ≤ 200,000