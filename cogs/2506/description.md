# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<strong>【注意：本场比赛准备仓促而且无人验题，可能会出现各种各样的小错误，对题面或者数据范围有疑问的同学请在cogs用户群中提问】</strong> 
</p>
<p>
<strong>【公告：第二题样例n应该为5，已修改，第三题样例已上传，第二题题面已修改为：“</strong><strong>所经过的零食店的消费指数不能超过c（除了起点和终点以外）</strong><strong><strong>”，第三题中敌方牌中没有敏捷单位】</strong></strong> 
</p>
<p>
<b>【由于没有用评测机跑过数据，为了卡掉复杂度不正确的算法，考试过程中可能对数据范围或者时间限制的<u>常数级</u>修改，注意到数据修改请及时修改自己的<u>数组大小</u>。此外请同学们使用最优时间复杂度的算法】</b> 
</p>
<p>
<b>【OI赛制，本场比赛结束后不评测，Day2结束后统一评测】</b> 
</p>
<p>
<br/>
</p>
<p>
   话说一年半以前，紫萱学姐展开了对杨廷学长的追求。在经历了不懈的努力之后，学姐终于成为了一名……金牌单身狗。但是这位痴情的少女并没有放弃，于是决定在保送之后继续进行这项征程，并为参加比赛的各位在役OI选手送上半熟的狗粮。
</p>
<p>
   历经了半年的停课之后，学姐回到了陌生又熟悉的班里，但是她已经找不到学长的位置了。于是她决定采用一种高效率的寻找方法：瞎找法。
</p>
<p>
   我们将学姐的班级视为一个二维平面，每个整数坐标对应一张桌子，学姐从班级的某个位置(x0,y0)开始瞎找，每次检查一下当前所在的这个桌子是谁的，然后进行下一次移动，直到找到学长的桌子(xt,yt)，便停止移动。
</p>
<p>
   给出学姐的初始坐标和每次移动的方向，请你判断在寻找的过程中学姐一共检查了多少张桌子。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
   第一行五个整数n,x0,y0,xt,yt，分别代表学姐移动的次数和学长桌子的坐标。
</p>
<p>
   接下来n行，第i行两个整数dx,dy，代表学姐第i次移动沿与x/y轴平行的方向移动了dx/dy个单位。如果dx/dy为负数，表示沿x/y轴的反方向移动了-dx/-dy个单位。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
   输出学姐检查过的桌子总数，如果学姐进行完所有移动之后都没有找到学长的桌子，那么输出“SingleDogMZX”（不含引号）。
</p>
<h3>
【样例输入】
</h3>
<pre>5 1 1 3 2
1 1
0 -2
0 2
1 0
0 -1
</pre>
<h3>
【样例输出】
</h3>
<pre>4
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
样例中，检查了(1,1)(2,2),(2,0),(3,2)共4张桌子
</p>
<p>
对于30%的数据，学姐每次移动时不会移动到已经检查过的桌子。
</p>
<p>
对于60%的数据，任何时刻学姐的横纵坐标都为≤2500的自然数。
</p>
<p>
对于90%的数据，任何时刻学姐的横纵坐标的绝对值都为≤2500的自然数。
</p>
<p>
对于100%的数据，任何时刻学姐的横纵坐标的绝对值都为≤10^9的自然数，n≤1000000。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
mzx
</p>
