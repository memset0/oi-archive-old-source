# 

 
 # 题目描述 
<p>
你刚刚从宁静的滑铁卢搬到一个大而喧闹的城市。你每天不再骑自行车到学校,而是步行和乘地铁。因为你不想上课迟到,你想知道多长时间能到达学校。<br>你走的速度是10公里/小时。地铁的速度是40公里/小时。假定你是幸运的,当你到达一个地铁站,马上能够乘上地铁立即出发。你可能会上下地铁许多次, 如果你愿意的话，你可以在不同的地铁线路之间切换。所有的地铁线路都是双向的。<br></p> 

 
 # 输入格式 
<p>
输入包括你家和学校的坐标（均表示为x,y），紧接着是若干条地铁线路，每一条地铁线路包含按顺序的非负整数x和y，表示线路上的若干地铁站的坐标。你可以假定地铁在地铁站之间是沿直线行走，坐标代表整数米。每条地铁线路最少两个站。地铁线路最后以-1，-1结尾。城市中的地铁站总数不超过200。</p> 

 
 # 输出格式 
<p>
输出你从家到学校的最快路径所耗费的分钟数，四舍五入到最近的分钟。</p> 
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
<tr><td>0 0 10000 1000
0 200 5000 200 7000 200 -1 -1 
2000 600 5000 600 10000 600 -1 -1
</td><td>21</td></tr></table>
