# 题目描述


<h3>
【背景】
</h3>
<p>
<br/>
</p>
<p>
在Nescafe27和28中，讲述了一支探险队前往Nescafe之塔探险的故事……
</p>
<p>
当两位探险队员以最快的时间把礼物放到每个木箱里之后，精灵们变身为一缕缕金带似的光，簇簇光芒使探险队员们睁不开眼睛。待一切平静下来之后，探险队员来到了一座宫殿中，玉制的石椅上坐着两个人……
</p>
<p>
“你们就是……Nescafe之塔护法中的两位？”
</p>
<p>
“是的，我们就是神刀护法xlk和飞箭护法riatre……你们来这里做什么？”
</p>
<p>
“我们是前来拜访圣主和四位护法的……”
</p>
<p>
“如果你们想见圣主和其它两位护法，你们必须穿过前方的七色彩虹。请随我来吧……”
</p>
<p>
<br/>
</p>
<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
探险队员们跟随两位护法来到了七色虹前。七色虹，就是平面直角坐标系中赤橙黄绿青蓝紫七个半圆，第i座(1&lt;=i&lt;=7)半圆形彩虹的圆心是(xi,0)，半径是ri，半圆上所有点的纵坐标均为非负数。探险队员可以看做一条竖直的、长度等于身高的线段，线段的底端纵坐标为0，最高的一位探险队员的身高为h。
</p>
<p>
<img src="/upload/image/20121104/20121104091112_87662.png" alt=""/> 
</p>
<p>
现在探险队员们要从(0,0)到达(x0,0)，穿越彩虹的过程中，探险队员的整个身体必须始终在至少一个半圆形彩虹的内部。由于彩虹的半径ri可能太小了，不足以满足这个条件，因此两位护法决定帮助他们把所有彩虹的半径都增大一个非负实数r。探险队员们想知道，r最小是多少呢？
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
第一行两个实数h、x0，表示身高和目的地横坐标。
</p>
<p>
接下来七行每行两个实数xi、ri，表示七座半圆形彩虹的圆心和半径。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
输出最小的r，四舍五入保留2位小数。
</p>
<h3>
【样例输入】
</h3>
<pre>4.0 36.0
0.0 4.0
6.0 4.0
12.0 4.0
18.0 4.0
24.0 4.0
30.0 4.0
36.0 4.0
</pre>
<h3>
【样例输出】
</h3>
<pre>1.00</pre>
<h3>
【提示】
</h3>
<p>
对于 100% 的数据，满足0&lt;=xi,x0&lt;=10000，0&lt;h&lt;100。
</p>
<p>
各个测试点0.5s
</p>
<h3>
【来源】
</h3>
<p>
http://www.tyvj.cn/Problem_Show.aspx?id=2053
</p>