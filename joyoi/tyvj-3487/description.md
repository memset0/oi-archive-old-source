# 

 
 # 题目描述 
<p>
很久以前，在一个遥远的星系，一个黑暗的帝国靠着它的超级武器统治者整个星系。某一天，凭着一个偶然的机遇，一支反抗军摧毁了帝国的超级武器，并攻下了星系中几乎所有的星球。这些星球通过特殊的以太隧道互相直接或间接地连接。

 
 # 输入格式 
<p>
输入文件第一行包含两个整数，N (1 <= N <= 2M) 和M (1 <= M <= 200,000)，分别表示星球的数目和以太隧道的数目。星球用0~N-1的整数编号。

 
 # 输出格式 
<p>
输出文件的第一行是开始时星球的连通块个数。
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
<tr><td>8 13
0 1
1 6
6 5
5 0
0 6
1 2
2 3
3 4
4 5
7 1
7 2
7 6
3 6
5
1
6
3
5
7

</td><td>
1
1
1
2
3
3
</td></tr></table>