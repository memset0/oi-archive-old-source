# 

 
 # 题目描述 
<p>
网络传输问题（network.pas\c\cpp）

 
 # 输入格式 
<p>
　　输入文件network.in第一行为N(N≤80）。之后的第2到第N+1行分别描述计算机1到N，每行第一个数字为计算机i需要的安全验证的来源计算机编号j，在1到N 之间，若为0则无需验证。之后紧跟着的是与计算机i相连的计算机的编号，一直读到该行结束。</p> 

 
 # 输出格式 
<p>
　　输出文件network.out仅一行，为传递所需要的最短时间。</p> 
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
<tr><td>12
0 2 3
1 1 4 5
1 1 6 7
0 2 8
0 2 9
0 3 9
0 3 10
0 4 11
0 5 6 10 11
0 7 9 12
0 1 9 12
10 11 12</td><td>4</td></tr></table>