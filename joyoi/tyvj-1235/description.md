# 

 
 # 题目背景 
tyvj20100619比赛,祝大家取得好成绩。^-^<BR> 

 
 # 题目描述 
John是他镇上唯一的牧师。10月26日是他一年中最忙的日子，因为在一个古老传说中这一天结婚的夫妻将受到上帝的保佑，而他要负责为镇上的每一对新人做祈祷。每对新人将在Si到Ti的时间段举行他们的婚礼，而根据传统他们在婚礼中某一段时间要举行一个仪式，他们站在John面前接受John给他们的祈祷。仪式的持续时间是整数，且至少要超过婚礼持续时间的一半，并且这个仪式不能中途被打断。令John头痛的是，同一时刻他只能为一对新人祈祷，他不知道如何安排时间使得他可以为所有新人完成祈祷。<BR>请写一个程序告诉John能否通过合理的安排使得他能为所有新人举行仪式。<BR> 

 
 # 输入格式 
输入包含多组测试数据，且保证最多有十组。<BR>每组数据第一行包含一个整数n(1&lt;=n&lt;=30000)，表示举行婚礼的新人对数。<BR>接下来n行，每行包含两个整数Si和Ti(0&lt;=Si&lt;=Ti&lt;=2147483647)，表示每个婚礼的起始和终止时刻。<BR>输入以一组n=0结束。对于这组数据程序不应有任何输出。<BR> 

 
 # 输出格式 
对于每组输入，如果能找到一种合法的安排，输出一行“YES”，否则输出“NO”。 

 
 # 提示 
必须超过整个时间的一半，不包括等于。 
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
<tr><td>3
1 5
2 4
3 6
2
1 5
4 6
0
</td><td>NO
YES
</td></tr></table>