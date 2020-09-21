# 

 
 # 题目描述 
<p>
游乐园已经开始运行一个崭新的模拟过山车。模拟的轨道由n 段铁轨组成，并且首尾相连。第一段铁轨从高度0开始。操作员Byteman能通过调整连续几段的铁轨高度来改造这条轨道。在被改造的一段前面的铁轨高度不受影响。 每一次铁轨被调整。后面的轨必须升起或降低来保持连通，并保证起点高度为0。下页举例说明轨道改造过程。

 
 # 输入格式 
<p>
输入的第一行包括一个正整数n——铁轨的数目，1≤n≤1000000000。下面的行包括改造和运行，各有一个标识符：

 
 # 输出格式 
<p>
第i行需包含一个整数，
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
<tr><td>4
Q 1
I 1 4 2
Q 3
Q 1
I 2 2 -1
Q 3
E
</td><td>4
1
0
3