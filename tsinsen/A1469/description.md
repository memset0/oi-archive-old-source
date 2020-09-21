<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　瓦西亚小姐到公园里去散步。这个公园有N处林中空地，从1到n编号。并且有M跳林中小径连接这些空地，小径从1到M编号，第i条连接空地Xi和Yi。Xi可以等于Yi，代表这条小径从这个空地出发绕一圈又回到这个空地。并且，两个空地之间可能有多条小径连接。<br/>
　　瓦西亚小姐在编号为1的空地，她想走遍所有的小径正好一次，并且她最后能回到1号空地。不幸的是，瓦西亚小姐不知道这样的走法是否存在。请你帮助她，判断一下这样的走法是否存在。如果不可能这样走，告诉她最少还需添加多少条小径能使这样的走法存在。</div>
# 输入格式

<div class="pdcont">　　第一行两个整数N,M<br/>
　　接下来m行每行两个整数Xi,Yi，意义如提述</div>
# 输出格式

<div class="pdcont">　　一个整数。<br/>
　　若这样的走法存在，则输出0，否则输出最少添加多少条边。</div>
# 样例输入

<div class="pddata">2 5<br/>
1 1<br/>
1 2<br/>
1 2<br/>
2 2<br/>
1 2</div>
# 样例输出

<div class="pddata">1</div>
# 数据规模和约定

<div class="pdcont">　　对于15%的数据1&lt;=n,m&lt;=10<br/>
　　对于20%的数据1&lt;=n,m&lt;=100<br/>
　　对于50%的数据1&lt;=n&lt;=100;1&lt;=m&lt;=1000<br/>
　　对于75%的数据1&lt;=n,m&lt;=1000<br/>
　　对于所有数据1&lt;=n,m&lt;=10^6</div>

</div>