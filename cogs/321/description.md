# 题目描述


<p>
<strong>题目背景： </strong> 
</p>
<p>
有n个木块排成一行，从左到右依次编号为1~n。你有k种颜色的油漆，其中第i 种颜色的油漆足够涂ci 个木块。所有油漆刚好足够涂满所有木块，即  c1+c2+...+ck=n。相邻两个木块涂相同色显得很难看，所以你希望统计任意两个相邻木块颜色不同的着色方案。<br/>
【输入】<br/>
第一行为一个正整数k，第二行包含k个整数c1,  c2, ... , ck。<br/>
【输出】<br/>
输出一个整数，即方案总数模1,000,000,007的结果。<br/>
【样例】
</p>
<table border="1" width="371">
<tbody>
<tr>
<td width="193">
输入
</td>
<td width="162">
输出
</td>
</tr>
<tr>
<td>
3<br/>
1 2 3
</td>
<td>
10
</td>
</tr>
<tr>
<td>
5<br/>
2 2 2 2 2
</td>
<td>
39480
</td>
</tr>
<tr>
<td>
10<br/>
1 1 2 2 3 3 4 4 5 5
</td>
<td>
85937576
</td>
</tr>
</tbody>
</table>
<p>
【数据规模】<br/>
50%的数据满足：1 &lt;= k &lt;= 5, 1 &lt;= ci &lt;= 3<br/>
100%的数据满足：1 &lt;=  k &lt;= 15, 1 &lt;= ci &lt;= 5
</p>