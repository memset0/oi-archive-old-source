# 题目描述


【问题描述】<br/>
<p>
n个城市之间有通讯网络，每个城市都有通讯交换机，直接或间接与其它城市连接。因电子设备容易损坏，需给通讯点配备备用交换机。但备用交换机数量有限，不能全部配备，只能给部分重要城市配置。于是规定：如果某个城市由于交换机损坏，不仅本城市通讯中断，还造成其它城市通讯中断，则配备备用交换机。请你根据城市线路情况，计算需配备备用交换机的城市个数，及需配备备用交换机城市的编号。
</p>
<p>
<span style="color:red;"> <span style="font-size:large;">一句话：给你个连通图，让你求图中割点个数，并按顺序输出。 </span></span> 
</p>
<div>
【输入格式】
</div>
<div>
输入文件有若干行<br/>
第一行，一个整数n，表示共有n个城市$(2&lt;=n&lt;=100)$<br/>
下面有若干行,每行2个数a、b，a、b是城市编号，表示a与b之间有直接通讯线路。
</div>
<div>
【输出格式】
</div>
<div>
输出文件有若干行<br/>
第一行，1个整数m，表示需m个备用交换机，下面有m行，每行有一个整数，表示需配备交换机的城市编号，输出顺序按编号由小到大。如果没有城市需配备备用交换机则输出0。
</div>
<div>
【输入输出样例】
</div>
<p>
输入文件名： gd.in
</p>
<p>
<br/>
</p>
<p>
7
</p>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
2 4
</p>
<p>
3 4
</p>
<p>
4 5
</p>
<p>
4 6
</p>
<p>
4 7
</p>
<p>
5 6
</p>
<p>
6 7
</p>
<p>
<br/>
</p>
<div>
<br/>
</div>
<p>
输出文件名：gd.out
</p>
<p>
<br/>
</p>
<p>
2
</p>
<p>
2
</p>
<p>
4
</p>
<p>
<br/>
</p>
<div>
<br/>
</div>