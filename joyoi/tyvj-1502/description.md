# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;你所在的省刚获得国家拨款兴建高铁，高铁的起止城市是国家选定的，中途可能经过若干城市。根据国家拨款的政策，国家将负担费用最大的两个区间，其余的必须由省负担。假如高铁线路中途只经过一个城市，国家只负担费用较大的区间。假如是直达的，国家将不负担任何费用。<BR>&nbsp;&nbsp;&nbsp;&nbsp;你被省里选定作为这个项目的总工程师，你必须规划出一条高铁线路，使得省负担的费用最少。当然，路线上每个城市最多只经过一次。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行是一个正整数n，n&lt;=50，代表城市之间的高铁建设费用估算（注意并非每对城市之间的建设费用都进行了估算）。接下来n行是用空格分隔的三个整数s,e,c。s和e代表城市的编码，高铁的起点和终点城市分别是编码为0和1，其余的城市依次编码。c&lt;=1000，是在s和e之间建设费用估算，从s到e与从e到s的建设费用是相同的。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;输出只有一行，格式为c1&nbsp;c2&nbsp;…&nbsp;cm&nbsp;cost，各数字用一个空格分隔，代表高铁线路规划和省负担的费用。ci代表城市编码（注意c1=0，cm=1），cost是费用。我们保证输入肯定有解，如果有多个解，输出当中经过城市最少的解，如果仍有多个解，则输出当中按字典序排列最小的解。<BR> 
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
0 2 10
0 3 6
2 4 5
3 4 3
3 5 4
4 1 7
5 1 8
</td><td>0 3 4 1 3
</td></tr></table>