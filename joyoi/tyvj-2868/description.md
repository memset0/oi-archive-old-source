# 

 
 # 题目描述 
<p>
一个餐厅在相继的N天里，第i天需要Ri块餐巾(i=l，2，…，N)。餐厅可以从三种途径获得餐巾。

 
 # 输入格式 
<p>
输入文件共3行，第1行为总天数；第2行为每天所需的餐巾块数；第3行为每块餐巾的新购费用p，快洗所需天数m，快洗所需费用f，慢洗所需天数n，慢洗所需费用s。</p> 

 
 # 输出格式 
<p>
输出文件共n+1行。第1行为最小的费用。下面的n行为从第1天开始每天需要的总餐巾数、需购买的新餐巾数、结束时往快、慢洗部送洗的餐巾数以及用到的来自快洗的餐巾数和来自慢洗的餐巾数。</p> 
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
<tr><td>3
3 2 4
10 1 6 2 3</td><td>64
3 3 1 2 0 0
2 1 2 0 1 0
4 0 0 0 2 2 