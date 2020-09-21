# 

 
 # 题目描述 
<p>
　　工业和医学上经常要用到一种诊断技术——核磁共振成像(Magnetic Resonance Imagers)。利用该技术可以对三维物体(例如大脑)进行扫描。扫描的结果用一个三维的数组来保存，数组的每一个元素表示空间的一个像素。数组的元素是0~255的整数，表示该像素的灰度。例如0表示该像素是黑色的，255表示该像素是白色的。

 
 # 输入格式 
<p>
　　第一行是三个正整数L，W．H(L，W，H≤50)，表示物体的长、宽、高。

 
 # 输出格式 
<p>
　　一个整数N，表示一共识别出几个部件。</p> 

 
 # 提示 
<p>
【问题分析】
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
<tr><td>2 2 2					
0
1 1 1 1 2 2 2 2
</td><td>2</td></tr></table>