# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2717/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjcxNy9wcm9ibGVtc19pbWFnZXMvMzIxOC8xOTU0LmpwZw==.jpg"> 

 
 # 输入格式 
<p>
The input contains several test cases. The first line of each test case contains an integer n(1<=n<=100000), The following n-1 lines each contains three integers u(0 <= u < n),v(0 <= v < n),w(0 <= w < 2^31), which means there is an edge between node u and v of length w. 

 
 # 输出格式 
<p>
For each test case output the xor-length of the xor-longest path.

 
 # 提示 
<p>
The xor-longest path is 1->2->3, which has length 7 (=3 ⊕ 4) 
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
<tr><td>4
1 2 3
2 3 4
2 4 6
</td><td>7
