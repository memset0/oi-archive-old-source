# 

 
 # 题目描述 
<p>
　　"今天你要去远行，送你风雨中….."，伴着凄美的歌声，郭靖夫妇终于踏上征程。为了尽快到达边疆为国效力，他们搭上了2002次列车。可在途径sweet station时，被该站站长缠住了身，是什么原因呢？

 
 # 输入格式 
<p>
　　在输入的文本文件train.in中第1行中为两个正整数：n（n≤20）m（m≤100），第2行到第m+1行，每行有3个不超过1000正整数。第i+1行的3个数分别为：Reach[i]， Cost[i]和Stay[i]，它们用单个空格分隔。</p> 

 
 # 输出格式 
<p>
　　在输出的文本文件train.out中仅有一行，为车站的最大收益（精确到小数点后2位）。注意，如果火车a从第i车道离开时，火车b刚好到站（即Reach[a]+Stay[a] =Reach[b]），则它不能进入第i车道。</p> 

 
 # 提示 
<p>
　　注：如果你的程序对她的问题的每个测试点都能在时限1秒内解决，你一定会收到一份精美礼品，信不信由你！</p> 
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
<tr><td>　　1 3
　　2 5 1
　　3 4 1
　　5 6 2
</td><td>　　0.11</td></tr></table>