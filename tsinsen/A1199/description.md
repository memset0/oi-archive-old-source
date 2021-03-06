<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　设<b><i>T=(V, E, W) </i></b>是一个无圈且连通的无向图（也称为无根树），每条边带有正整数的权，我们称<b><i>T</i></b>为树网（<i>treenetwork</i>），其中<b><i>V, E</i></b>分别表示结点与边的集合，<b><i>W</i></b>表示各边长度的集合，并设<b><i>T</i></b>有<i>n</i>个结点。<br/>
　　<b>路径：</b>树网中任何两结点<b><i>a,b</i></b>都存在唯一的一条简单路径，用<b><i>d(a,b)</i></b>表示以<b><i>a,b</i></b>为端点的路径的长度，它是该路径上各边长度之和。我们称<b><i>d(a,b)</i></b>为<b><i>a,b</i></b>两结点间的距离。<br/>
　　一点<b><i>v</i></b>到一条路径<b><i>P</i></b>的距离为该点与<b><i>P</i></b>上的最近的结点的距离：<br/>
　　<b><i>d(v</i></b><b><i>，</i></b><b><i>P)</i></b><b>=</b>min{<b><i>d(v</i></b><b><i>，</i></b><b><i>u)</i></b><b><i>，</i></b><b><i>u</i></b>为路径<b><i>P</i></b>上的结点}。<br/>
　　<b>树网的直径：</b>树网中最长的路径称为树网的直径。对于给定的树网<b><i>T</i></b>，直径不一定是唯一的，但可以证明：各直径的中点（不一定恰好是某个结点，可能在某条边的内部）是唯一的，我们称该点为树网的中心。<br/>
　　<b>偏心距</b><b><i>ECC(F)</i></b>：树网<b><i>T</i></b>中距路径<b><i>F</i></b>最远的结点到路径<b><i>F</i></b>的距离，即<br/>
　　ECC(F) = max{d(v, F), v∈V}。<br/>
　　<b>任务：</b>对于给定的树网<b><i>T=(V, E,W)</i></b>和非负整数<i>s</i>，求一个路径<b><i>F</i></b>，它是某直径上的一段路径（该路径两端均为树网中的结点），其长度不超过s（可以等于s），使偏心距<b><i>ECC(F)</i></b>最小。我们称这个路径为树网<b><i>T=(V,E,W)</i></b>的<b>核（</b><b><i>Core</i></b><b>）</b>。必要时，<b><i>F</i></b>可以退化为某个结点。一般来说，在上述定义下，核不一定只有一个，但最小偏心距是唯一的。<br/>
　　下面的图给出了树网的一个实例。图中，A-B与A-C是两条直径，长度均为20。点W是树网的中心，EF边的长度为5。如果指定<i>s</i>=11，则树网的核为路径DEFG（也可以取为路径DEF），偏心距为8。如果指定<i>s</i>=0（或<i>s</i>=1、<i>s</i>=2），则树网的核为结点F，偏心距为12。<br/>
<img width="259" height="224" src="source/tsinsen/A1199/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9RDJubm0zeTk=.do"/></div>
# 输入格式

<div class="pdcont">　　输入包含<i>n</i>行：<br/>
　　第1行，两个正整数<i>n</i>和<i>s</i>，中间用一个空格隔开。其中<i>n</i>为树网结点的个数，<i>s</i>为树网的核的长度的上界。设结点编号依次为1, 2, ..., <i>n</i>。<br/>
　　从第2行到第<i>n</i>行，每行给出3个用空格隔开的正整数，依次表示每一条边的两个端点编号和长度。例如，“2 4 7”表示连接结点2与4的边的长度为7。<br/>
　　所给的数据都是正确的，不必检验。</div>
# 输出格式

<div class="pdcont">　　输出一个非负整数，为指定意义下的最小偏心距。</div>
# 样例输入

<div class="pddata">5 2<br/>
1 2 5<br/>
2 3 2<br/>
2 4 4<br/>
2 5 3</div>
# 样例输出

<div class="pddata">5</div>
# 样例输入

<div class="pddata">8 6<br/>
1 3 2<br/>
2 3 2<br/>
3 4 6<br/>
4 5 3<br/>
4 6 4<br/>
4 7 2<br/>
7 8 3</div>
# 样例输出

<div class="pddata">5</div>
# 数据规模和约定

<div class="pdcont">　　40%的数据满足：5&lt;=<i>n</i>&lt;=15<br/>
　　70%的数据满足：5&lt;=<i>n</i>&lt;=80<br/>
　　100%的数据满足：5&lt;=<i>n</i>&lt;=300, 0&lt;=<i>s</i>&lt;=1000。边长度为不超过1000的正整数。</div>

</div>