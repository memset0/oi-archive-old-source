# 

 
 # 题目描述 
<p>
第二幕 神秘的锁

 
 # 输入格式 
<p>
　　输入文件第一行有两个整数n，m（2<=n<=5000,1<=m<=20）。n代表金属片的个数，m代表锁一共有m种可能的灵异值。接下来的n行，第i行的数Ai（1 <=  Ai <= 100）代表从左往右数第i片金属片的灵异值。接下来的m行，每行一个整数Ki，代表锁的一种灵异值。</p> 

 
 # 输出格式 
<p>
　　输出文件分为m组，第i组输出对应当锁的灵异值为Ki时劳拉的开锁过程。对于第i组输出，若灵异值为Ki时锁是可以被打开的，则应该先输出一行"Great！"，接下来的n－1行每行一个数，第j行的数Tj代表第j次劳拉将选择当前从左到右数的第Tj和第Tj＋1片金属熔合；若无论劳拉如何移动金属片，最后都不可能得到灵异值为Ki的金属片，则只输出一行"Impossible！"。</p> 
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
<tr><td>　　4 2
　　2
　　1
　　4
　　3
　　2
　　5
</td><td>　　Great!
　　2
　　1
　　1
　　Impossible!