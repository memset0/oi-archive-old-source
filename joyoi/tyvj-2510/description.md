# 

 
 # 题目描述 
<p>
Oh those picky N (1 <= N <= 50,000) cows! They are so picky that

 
 # 输入格式 
<p>
* Line 1: A single integer, N

 
 # 输出格式 
<p>
* Line 1: The minimum number of stalls the barn must have.

 
 # 提示 
<p>
不妨试下这个数据,对于按结束点SORT,再GREEDY的做法
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
<tr><td>5
1 10
2 4
3 6
5 8
4 7
</td><td>4


OUTPUT DETAILS:

Here's a graphical schedule for this output:

Time     1  2  3  4  5  6  7  8  9 10
Stall 1 c1>>>>>>>>>>>>>>>>>>>>>>>>>>>
Stall 2 .. c2>>>>>> c4>>>>>>>>> .. ..
Stall 3 .. .. c3>>>>>>>>> .. .. .. ..
Stall 4 .. .. .. c5>>>>>>>>> .. .. ..

Other outputs using the same number of stalls are possible.</td></tr></table>