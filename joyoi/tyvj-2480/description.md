# 

 
 # 题目描述 
<p>
    Farmer John以及他的N(1 <= N <= 2,500)头奶牛打算过一条河，但他们所

 
 # 输入格式 
<p>
* 第1行: 2个用空格隔开的整数：N 和 M

 
 # 输出格式 
<p>
* 第1行: 输出1个整数，为FJ把所有奶牛都载过河所需的最少时间
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
<tr><td>5 10
3
4
6
100
1

输入说明:

    FJ带了5头奶牛出门。如果是单独把木筏划过河，FJ需要花10分钟，带上
1头奶牛的话，是13分钟，2头奶牛是17分钟，3头是23分钟，4头是123分钟，将
5头一次性载过去，花费的时间是124分钟。


</td><td>50

输出说明:

    Farmer John第一次带3头奶牛过河（23分钟），然后一个人划回来
（10分钟），最后带剩下的2头奶牛一起过河（17分钟），总共花费的时间是
23+10+17 = 50分钟。