# 

 
 # 题目描述 
车展结束后，游乐园决定举办一次盛大的山道拉力赛，平平和韵韵自然也要来参加大赛。<BR>赛场上共有n个连通的计时点，n-1条赛道（构成了一棵树）。每个计时点的高度都不相同（父结点的高度必然大于子结点），相邻计时点间由赛道相连。由于马力不够，所以韵韵的遥控车只能从高处驶向低处。而且韵韵的车跑完每条赛道都需花费一定的时间。<BR>举办方共拟举办m个赛段的比赛，每次从第u个计时点到第v个计时点，当然其中有不少比赛韵韵的遥控车是不能参加的（因为要上坡）。平平想知道他能参加多少个赛段的比赛，并且想知道他完成这些赛段的总用时。<BR> 

 
 # 输入格式 
第一行两个整数n，m。<BR>接下来n-1行每行3个整数a、b、t。<BR>表示韵韵的遥控车可以花t秒从第a个计时点到第b个计时点。<BR>接下来m行每行2个整数u、v，意义如描述所示。<BR> 

 
 # 输出格式 
第一行输出一个正整数，表示能参加的赛段数。<BR>第二行输出一个正整数，表示总用时。 

 
 # 提示 
第一个计时点的高度是最高的；<BR>u≠v；<BR>对于50％的数据&nbsp;n≤1000&nbsp;m≤1000；<BR>对于100％的数据&nbsp;n≤10000&nbsp;m≤100000；<BR>答案小于2^64。<BR>f1zsy&nbsp;birdor 
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
<tr><td>6 2
1 2 1
2 4 1
2 5 1
5 6 1
1 3 1
2 6
4 5
</td><td>1
2
</td></tr></table>
