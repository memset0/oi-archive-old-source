# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
* 第1行: 2个用空格隔开的整数：N和K

 
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
<tr><td>4 3
2 1
2 3
4 1

输入说明:

牧场被划分成了4行4列。Bessie的站位必须保证她能射到站在(2,1)，(2,3)

以及(4,1)的奶牛：

          . . . .
          C . C .
          . . . .   <--- 奶牛们的位置
          C . . .
</td><td>
5

输出说明:

Bessie可以选择站在以下格子中的任意一个：(2,1)，(2,3)，(3,2)，(4,1)，
以及(4,3)。下右图中，Bessie与其他牛共同占有的格子被标记为'*'：
       . . . .           . . . .
       B . B .   ---\    * . * .
       . B . .   ---/    . B . .
       B . B .           * . B .</td></tr></table>