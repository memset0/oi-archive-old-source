# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
第1行： 两个整数， M 和 N。

 
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
<tr><td>4 5
1 0 0 0 0
3 0 0 0 0
0 0 2 0 0
0 0 0 4 0

输入解释：
池塘含4行5列。Bessie在第2行第1列并且想跳到第4行第4列。池塘里有1块
石头和3片荷叶。
</td><td>2
3

输出解释：

至少需要2片荷叶。一共有三种摆法：
	第4行第2列，第2行第3列
	第1行第3列，第3行第2列
	第1行第3列，第2行第5列

          R1C2,R2C3     R1C3,R3C2     R1C3,R2C5
          1 0 0 0 0     1 0 X 0 0     1 0 X 0 0
          3 0 X 0 0     3 0 0 0 0     3 0 0 0 X
          0 0 2 0 0     0 X 2 0 0     0 0 2 0 0
          0 X 0 4 0     0 0 0 4 0     0 0 0 4 0