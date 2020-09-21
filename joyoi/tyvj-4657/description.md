# 

 
 # 题目描述 
<p>夏令营快要结束的时候，很多营员提出来要把整个夏令营期间的资料刻录成一张光盘给大家，以便大家回去后继续学习。组委会觉得这个主意不错！可是组委会一时没有足够的空光盘，没法保证每个人都能拿到刻录上资料的光盘，怎么办呢？！</p>

<p>　　DYJ分析了一下所有营员的地域关系，发现有些营员是一个城市的，其实他们只需要一张就可以了，因为一个人拿到光盘后，其他人可以带着U盘之类的东西去拷贝啊！</p>

<p>　　他们愿意某一些人到他那儿拷贝资料，当然也可能不愿意让另外一些人到他那儿拷贝资料，这与我们宣扬的团队合作精神格格不入！！！</p>

<p>　　现在假设总共有N个营员（2&lt;=N&lt;=200），每个营员的编号为1~N。DYJ给每个人发了一张调查表，让每个营员填上自己愿意让哪些人到他那儿拷贝资料。当然，如果A愿意把资料拷贝给B，而B又愿意把资料拷贝给C，则一旦A获得了资料，则B，C都会获得资料。</p>

<p>　　现在，请你编写一个程序，根据回收上来的调查表，帮助DYJ计算出组委会至少要刻录多少张光盘，才能保证所有营员回去后都能得到夏令营资料？</p> 

 
 # 输入格式 
<p><span style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">先是一个数</span><font face="Calibri" style="font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">N</font><font face="宋体" style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">，接下来的</font><font face="Calibri" style="font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">N</font><font face="宋体" style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">行，分别表示各个营员愿意把自己获得的资料拷贝给其他哪些营员。即输入数据的第</font><font face="Calibri" style="font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">i+1</font><font face="宋体" style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">行表示第</font><font face="Calibri" style="font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">i</font><font face="宋体" style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">个营员愿意把资料拷贝给那些营员的编号，以一个</font><font face="Calibri" style="font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">0</font><font face="宋体" style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">结束。如果一个营员不愿意拷贝资料给任何人，则相应的行只有</font><font face="Calibri" style="font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">1</font><font face="宋体" style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">个</font><font face="Calibri" style="font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">0</font><font face="宋体" style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">，一行中的若干数之间用一个空格隔开。</font></p> 

 
 # 输出格式 
<p><span style="font-family: 宋体; font-size: 14px; line-height: 18px; background-color: rgb(228, 240, 248);">一个正整数，表示最少要刻录的光盘数。</span></p> 
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
<tr><td>5
2 4 3 0
4 5 0
0
0
1 0</td><td>1</td></tr></table>