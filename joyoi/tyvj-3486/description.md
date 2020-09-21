# 

 
 # 题目描述 
<p>
火星人最近研究了一种操作：求一个字串两个后缀的公共前缀。比方说，有这样一个字符串：madamimadam，我们将这个字符串的各个字符予以标号：

 
 # 输入格式 
<p>
第一行给出初始的字符串。

 
 # 输出格式 
<p>
对于输入文件中每一个询问操作，你都应该输出对应的答案。一个答案一行。
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
<tr><td>7
Q 1 7
Q 4 8
Q 10 11
R 3 a
Q 1 7
I 10 a
Q 2 11

</td><td>
5
1
0
2
1

数据规模：
对于100%的数据，满足：
1、	所有字符串自始至终都只有小写字母构成。
2、	M <= 150,000
3、	字符串长度L自始至终都满足L <= 100,000
4、	询问操作的个数不超过10,000个。

对于第1，2个数据，字符串长度自始至终都不超过1,000
对于第3，4，5个数据，没有插入操作。
</td></tr></table>