# 

 
 # 题目描述 
　Victoria是一位颇有成就的艺术家，他因油画作品《我爱北京天安门》闻名于世界。现在，他为了报答帮助他的同行们，准备开一个舞会。<BR>　　Victoria准备邀请n个已经确定的人，可是问题来了：<BR>　　这n个人每一个人都有一个小花名册，名册里面写着他所愿意交流的人的名字。比如说在A的人名单里写了B，那么表示A愿意与B交流；但是B的名单里不见的有A，也就是说B不见的想与A交流。但是如果A愿意与B交流，B愿意与C交流，那么A一定愿意与C交流。也就是说交流有传递性。<BR>　　Victoria觉得需要将这n个人分为m组，要求每一组的任何一人都愿意与组内其他人交流。并求出一种方案以确定m的最小值是多少。<BR>　　注意：自己的名单里面不会有自己的名字。<BR> 

 
 # 输入格式 
第一行一个数n。接下来n行，每i+1行表示编号为i的人的小花名册名单，名单以0结束。1&lt;=n&lt;=200。 

 
 # 输出格式 
一个数，m。<BR> 

 
 # 提示 
Vivian&nbsp;Snow<BR> 
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
<tr><td>18
0
18 0
0
0
11 0
0
0
0
0
0
5 0
0
0
0
0
0
0
2 0
</td><td>16
</td></tr></table>
