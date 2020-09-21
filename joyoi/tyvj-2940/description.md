# 

 
 # 题目描述 
<p>
贪吃的九头龙(dragon.pas/c/cpp)

 
 # 输入格式 
<p>
　　输入文件dragon.in的第1行包含三个整数N (1<=N <=300)，M (2<=M <=N)，K (1<=K <=N)。 N个果子依次编号1,2,...,N，且最大的果子的编号总是1。第2行到第N行描述了果树的形态，每行包含三个整数a (1<=a <=N)，b (1<=b <=N)，c (0<=c <=105)，表示存在一段难受值为c的树枝连接果子a和果子b。</p> 

 
 # 输出格式 
<p>
输出文件dragon.out仅有一行，包含一个整数，表示在满足“大头”的要求的前提下，九头龙的难受值的最小值。如果无法满足要求，输出-1。</p> 

 
 # 提示 
<p>
该样例对应于题目描述中的例子。</p> 
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
<tr><td>8 2 4
1 2 20
1 3 4 
1 4 13
2 5 10
2 6 12
3 7 15
3 8 5
</td><td>4</td></tr></table>