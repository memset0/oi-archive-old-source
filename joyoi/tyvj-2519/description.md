# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
* Line 1: 两个用空格分开的整数，分别表示Start 和 Finish。

 
 # 输出格式 
<p>

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
<tr><td>2 12
</td><td>
6

输出解释:

 2    10  1x0 + 1x1  ROUND
 3    11  0x0 + 2x1  NOT round
 4   100  2x0 + 1x1  ROUND
 5   101  1x0 + 2x1  NOT round
 6   110  1x0 + 2x1  NOT round
 7   111  0x0 + 3x1  NOT round
 8  1000  3x0 + 1x1  ROUND
 9  1001  2x0 + 2x1  ROUND
10  1010  2x0 + 2x1  ROUND
11  1011  1x0 + 3x1  NOT round
12  1100  2x0 + 2x1  ROUND