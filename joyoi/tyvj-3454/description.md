# 

 
 # 题目描述 
<p>
校园网（schlnet.pas\c\cpp）<br><br>【题目描述】<br>　　一些学校连入一个电脑网络。那些学校已订立了协议：每个学校都会给其它的一些学校分发软件（称作“接受学校”）。注意如果 B 在 A 学校的分发列表中，那么 A 不一定也在 B 学校的列表中。 <br>　　你要写一个程序计算，根据协议，为了让网络中所有的学校都用上新软件，必须接受新软件副本的最少学校数目（子任务 A）。更进一步，我们想要确定通过给任意一个学校发送新软件，这个软件就会分发到网络中的所有学校。为了完成这个任务，我们可能必须扩展接收学校列表，使 其加入新成员。计算最少需要增加几个扩展，使得不论我们给哪个学校发送新软件，它都会到达其余所有的学校（子任务 B）。一个扩展就是在一个学校的接收学校列表中引入一个新成员。<br></p> 

 
 # 输入格式 
<p>
　　输入文件schlnet.in的第一行包括一个整数 N：网络中的学校数目（2 <= N <= 100）。学校用前 N 个正整数标识。接下来 N 行中每行都表示一个接收学校列表（分发列表）。第 i+1 行包括学校 i 的接收学校的标识符。每个列表用 0 结束。空列表只用一个 0 表示。 </p> 

 
 # 输出格式 
<p>
  输出文件schlnet.out中有两行。第一行应该包括一个正整数：子任务 A 的解。第二行应该包括子任务 B 的解。</p> 
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
1 0
</td><td>1
2</td></tr></table>
