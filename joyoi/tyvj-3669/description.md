# 

 
 # 题目描述 
<p>
Farmer John尝试通过和奶牛们玩益智玩具来保持他的奶牛们思维敏捷. 其中一个大型玩具是

 
 # 输入格式 
<p>
* 第 1 行: 用空格隔开的两个整数N和M

 
 # 输出格式 
<p>
第 1..询问的次数 行: 对于每一次询问, 输出询问的结果.
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
0 1 2
0 2 4
1 2 3
0 2 4
1 1 4

输入解释:
一共有4盏灯; 5个指令. 下面是执行的情况:
	        灯
            1 2 3 4
  Init:     O O O O   O = 关  * = 开
  0 1 2 ->  * * O O  改变灯 1 和 2 的状态
  0 2 4 ->  * O * *
  1 2 3 ->  1        输出在2..3的范围内有多少灯是亮的
  0 2 4 ->  * * O O  改变灯 2 ,3 和 4 的状态
  1 1 4 ->  2        输出在1..4的范围内有多少灯是亮的




</td><td>
1
2
</td></tr></table>