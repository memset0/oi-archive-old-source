# 

 
 # 题目描述 
<p>
Byteotian 大学由一幢主建筑和n个小别墅组成. 它们之间许多单向的道路连接,任意两个建筑之间可能有多条单向路,也有可能一条路从自己出发并回到自己.任意两个建筑之间都是连通的(即要么可以从A走到B,要么可以从B走到A). 

 
 # 输入格式 
<p>
第一行两个整数 n 和 m ( 1<= n, m<= 1 000 000) 表示大学里别墅的个数和道路条数(别墅编号从1到n,大学主建筑的编号为n + 1). 接下来m行每行两个整数 ai, bi ( 1 <=ai, bi<= n + 1 for 1 i m) 表示一条单向路. 

 
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
<tr><td>3 5
1 2
1 3
2 3
3 4
3 4

</td><td>4
1
1