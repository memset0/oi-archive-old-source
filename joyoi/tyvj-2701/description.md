# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
第一行只有两个整数n，m，保证有2≤n≤300，1≤m≤n(n-1)/2。其中n代表总人数，m代表好朋友的对数。文件第二行有n个整数，第i个整数代表第i个小朋友的意愿，当它为1时表示同意睡觉，当它为0时表示反对睡觉。接下来文件还有m行，每行有两个整数i，j。表示i，j是一对好朋友，我们保证任何两对i，j不会重复。

 
 # 输出格式 
<p>
只需要输出一个整数，即可能的最小冲突数。

 
 # 提示 
<p>
在第一个例子中，所有小朋友都投赞成票就能得到最优解</p> 
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
<tr><td>3 3
1 0 0
1 2
1 3
3 2
</td><td>1</td></tr></table>