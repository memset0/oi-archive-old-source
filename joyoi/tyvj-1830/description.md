# 

 
 # 题目描述 
“藏地密码”是2008年非常流行的一本全面反映西藏历史的百科式小说。书中是这样描绘的：13世纪中叶，在这片古老的大地上，商业已经非常繁荣，那里人们延续着古老的交易方式。他们牵着骆驼在城市之间往来奔波，贩运成批的商品，换来一袋袋的金币。<BR>在这片大地上有n个国家，标号为1...n。在一些城市之间有路可通，有路就有商队。但是在不同的城市之间经商所得的收益不同，在下面的这个n=4的例子中，在城市1和城市2之间进行一次交易可以获得40枚金币，在城市2和3之间交易一次可以获得50枚金币，等等。<BR><img src="/source/joyoi/tyvj-1830/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTgzMC9Qcm9ibGVtSW1nLzE4MzAuanBn.jpg" border=0 align=middle><BR>在任意两个城市之间，这样的交易只能进行一次。因为你第二次贩运你的商品时，人们对它们就不会感兴趣了。<BR>现在你只身来到这个大地上，用有限的资金在每个城市中购买了一支商队。你需要想办法让你的这n支商队给你带来最大的经济收益。 

 
 # 输入格式 
输入文件的第一行有两个整数n（1&lt;=n&lt;=100）、m（m&gt;=0），分别表示这个大地上的城市数和道路数。<BR>接下来有m行，每行包括三个整数i、j（1&lt;=i,j&lt;=n且i&lt;&gt;j）、v（1&lt;=v&lt;=10000），表示一条道路的信息。其中i和j表示这条路在城市i和城市j之间，v表示沿着这条路进行一次交易所得的收益。i和j的顺序是无关的，并且任意两个城市之间最多存在一条路。 

 
 # 输出格式 
你的输出文件应该只有一行，包含n个整数。<BR>其中第k个整数表示你在城市k中的商队将要前往哪个城市进行交易（如果这支商队进行交易的话）或者为0（如果这支商队不进行任何交易）。<BR> 

 
 # 提示 
给出这个大地的地图和每两个城市之间的贸易值（如果这两个城市之间有路可通的话），你需要指挥你的n值商队进行一次经商，使得这n支商队在这次经商中获得的总利益最大。<BR>当然，你的每支商队只能进行一次交易，即它们只能从它们所在的一个城市到达一个相邻的城市。当然，它们也可以不进行任何交易。<BR>本题的解不一定是唯一的。即对于一个测试数据，可能有多种经商方案使总收益最大。在这种情况下，你只要输出最优方案中的任意一种即可。<BR> 
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
<tr><td>4 5
1 2 40
1 3 30
2 3 50
2 4 30
3 4 20
</td><td>2 3 1 2
</td></tr></table>
