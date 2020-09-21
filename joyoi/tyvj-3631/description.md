# 

 
 # 题目描述 
<p>
给你N颗宝石，每颗宝石都有重量和价值。要你从这些宝石中选取一些宝石，保证总重量不超过W，且总价值最大为，并输出最大的总价值。

 
 # 输入格式 
<p>
输入文件中包含多组数据。每组数据的格式如下：第一行是两个正整数n和W，1≤n≤100,1≤W≤2^30，分别表示宝石的数目和最多能带走的宝石重量。接下来的n行，每行有两个正整数weighti和valuei，1≤weighti≤2^30, 0≤valuei≤2^30，分别表示第i颗宝石的重量和价值，且保证weighti能写成a*2^b(1≤a≤10,0≤b≤30)的形式。同一行的两个正整数之间用空格隔开。

 
 # 输出格式 
<p>
对于输入的每组数据，输出一个整数C，表示小P最多能带走的宝石的总价值。每个结果整数C单独占一行，且保证C不会超过2^30。
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
<tr><td>4 10
8 9
5 8
4 6
2 5
4 13
8 9
5 8
4 6
2 5
16 75594681
393216 5533
2 77
32768 467
29360128 407840
112 68
24576 372
768 60
33554432 466099
16384 318
33554432 466090
2048 111
24576 350
9216 216
12582912 174768
16384 295
1024 76
-1 -1
</td><td>14
19
1050650