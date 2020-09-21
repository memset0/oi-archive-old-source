<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　Berland解放战争的每一次周年庆典上都要举办阅兵式，今年也不例外。所有人都在全力准备——坦克排成一列，大炮做好了开火准备，士兵正在向广场进发，而Generalov的空军又一次遇到了麻烦。今年新建了许多摩天楼，这使得飞机很难从城市上空飞过。Generalov决定让飞机从南向北飞，并且飞行路线上不能有摩天楼，否则周年庆典会变成一场惨剧。Berland建筑部只给出了N座摩天楼的信息，因为其他的楼相比之下实在太小了，不会给飞行带来麻烦。从南向北看这座城市，以地平线为x轴建立坐标系，第i座摩天楼可以看作x轴上方的一个高度为Hi的长方形。它的西边横坐标为Li，东边横坐标为Ri。这里地形平坦，因此所有建筑的底部都在地平线上。作为国防部的顶级程序员，你的任务是要用摩天楼的信息，给出所有摩天楼的轮廓线。轮廓线具有以下性质：<br/>
　　1、从南向北看城市，把建筑投影在一个平面上。每座摩天楼都在轮廓线和地平线围成的区域内部或边界上。<br/>
　　2、轮廓线的起点、终点均在地平线上，也就是说纵坐标为0。<br/>
　　3、轮廓线的每条边都平行于坐标轴，也就是说要么水平要么竖直。<br/>
　　4、轮廓线的顶点坐标为整数。<br/>
　　5、轮廓线和地平线围成的面积必须尽可能小。<br/>
　　6、在面积最小的前提下，轮廓线必须尽可能短。<br/>
　　7、轮廓线上相邻的两条线段必须垂直。</div>
# 输入格式

<div class="pdcont">　　第一行一个整数N。<br/>
　　接下来有N行，每行包含三个整数Hi,Li和Ri。</div>
# 输出格式

<div class="pdcont">　　第一行输出一个整数M，表示轮廓线的顶点个数。<br/>
　　接下来输出M行，每行包含两个整数，表示每个顶点的横、纵坐标。要求按照从左至右遍历轮廓线的顺序输出顶点，注意第一个顶点和最后一个顶点的纵坐标为0（参见样例）。</div>
# 样例输入一

<div class="pdcont">　　2<br/>
　　3 0 2<br/>
　　4 1 3</div>
# 样例输出一

<div class="pdcont">　　6<br/>
　　0 0<br/>
　　0 3<br/>
　　1 3<br/>
　　1 4<br/>
　　3 4<br/>
　　3 0</div>
# 样例输入二

<div class="pdcont">　　5<br/>
　　3 -3 0<br/>
　　2 -1 1<br/>
　　4 2 4<br/>
　　2 3 7<br/>
　　3 6 8</div>
# 样例输出二

<div class="pdcont">　　14<br/>
　　-3 0<br/>
　　-3 3<br/>
　　0 3<br/>
　　0 2<br/>
　　1 2<br/>
　　1 0<br/>
　　2 0<br/>
　　2 4<br/>
　　4 4<br/>
　　4 2<br/>
　　6 2<br/>
　　6 3<br/>
　　8 3<br/>
　　8 0</div>
# 数据规模和约定

<div class="pdcont">　　1≤N≤10^5<br/>
　　1≤Hi≤10^9<br/>
　　-10^9≤Li&lt;Ri≤10^9</div>

</div>