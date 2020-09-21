# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
电子对撞机(刘洪轩)
</div>
<div style="text-align:center;font-size:14px;vertical-align:middle;" id="pres">
<div style="font-weight:bold;margin:8px 0px 6px;">
时间限制：<span style="text-decoration:underline;">3.0s</span>   内存限制：<span style="text-decoration:underline;">256.0MB</span> 
</div>
</div>
<div id="psrc" style="margin-top:20px;display:none;">
<div class="pdsec">
试题来源
</div>
<div class="pdcont">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【题意描述】
</h3>
<div class="pdcont">
感谢HQ提供题目描述<br/>
Q国最近科学技术不断进步，经过不懈努力，Q国主席QQ终于在质子对撞机的基础上研发了新一代能量供给装置：电子对撞机。<br/>
这个设备呈长条状且对外封闭，设备内部有N个带有一定能量的电子。长条状的外形使得这些电子只能沿条形走向左右运动。设备长度为L，左端位置为0，右端位置为L。内部的电子速率恒定，每一个单位时间在左右方向上移动一个单位长度，而方向可能是向左或向右。当两个电子相遇即运动到同一个点时，它们之间会发生对撞，对撞后它们的速率不变但运动方向反向。设备的两个端点处(即坐标为0和L的位置)存在保护外壳，当电子运动到端点时会和外壳发生碰撞，碰撞后电子也会保持不变的速率但运动方向反向。电子分为高能电子和低能电子，电子之间对撞会产生能量，低能电子和低能电子对撞会产生1个单位的能量，低能电子和高能电子对撞会产生4个单位的能量，高能电子和高能电子对撞会产生25个单位的能量，电子和外壳碰撞不会产生能量。设备内部还有M个能量接收器，每个接收器可以接受从A到B的一个区间内（包括两个端点）的能量，且接收器可以接受的范围没有交集。若电子对撞的位置处于接收器的接受范围内，对撞产生的能量会被接收器接受，若对撞位置不在接收器上，这些能量则会丢失。这项技术的核心在于：对撞时电子的能量不会有损失，所以电子对撞机可以一直不断地运行下去供给能量。<br/>
现在QQ已经制造出了第一批电子对撞机，并测得了时刻为0时电子的位置和运动状态，现在QQ想知道从时刻0到时刻T(包括T)总共接收到的能量，于是这个任务交给了神犇你。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行四个整数 N, M, L, T，分别表示电子个数，能量接收器个数，设备长度和时间。<br/>
之后N行每行3个整数，Xi, Pi, Ei分别表示第i个电子的位置，运动方向和能量级别。<br/>
Pi为1表示向右运动，为-1表示向左运动。<br/>
Ei为0表示低能电子，为1表示高能电子。<br/>
之后M行每行2个整数，Ai和 Bi，表示接收器的接收范围。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
仅一行，包括一个整数，表示总共接收到的能量数。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3 1 8 7<br/>
2 1 0<br/>
4 -1 0<br/>
7 1 1<br/>
3 6<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
5<br/>
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
T=1时，在位置3，第一个电子和第二个电子对撞，产生1的能量。<br/>
在位置8，第三个电子和右侧外壳碰撞。<br/>
T=3.5时，在位置5.5，第二个电子和第三个电子对撞，产生4的能量。<br/>
T=4时，在位置0，第一个电子和左侧外壳碰撞。<br/>
T=6时，在位置8，第三个电子和右侧外壳碰撞。<br/>
T=6.5时，在位置2.5，第一个电子和第二个电子对撞，产生1的能量，由于在接收器范围外，能量丢失。<br/>
最后结果为1+4=5个单位能量。<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
输入保证开始时任意两个电子不处于同一个位置。<br/>
输入保证接收器的接受范围没有交集，且所有接收器按坐标从小到大的顺序给出。<br/>
共20组数据，满足如下条件<br/>
<table style="border-collapse:collapse;border:medium none;" cellpadding="2px" cellspacing="0" align="center">
<tbody>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
1 ~ 2<br/>
</td>
<td style="border:1pt solid;" valign="top">
N &lt;= 10<br/>
</td>
<td style="border:1pt solid;" valign="top">
M &lt;= 3<br/>
</td>
<td style="border:1pt solid;" valign="top">
L &lt;= 1000,<br/>
T &lt;= 100000<br/>
</td>
<td rowspan="7" style="border:1pt solid;" valign="top">
2 &lt;= N &lt;= 1000000,<br/>
1 &lt;= M &lt;= 10,<br/>
2 &lt;= L &lt;= 100000000,<br/>
0 &lt;= T &lt;= 1000000000,<br/>
0 &lt; X &lt; L<br/>
0 &lt;= A &lt; B &lt;= L<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
3 ~ 4<br/>
</td>
<td style="border:1pt solid;" valign="top">
N &lt;= 100<br/>
</td>
<td rowspan="2" style="border:1pt solid;" valign="top">
Ei = 0<br/>
</td>
<td style="border:1pt solid;" valign="top">
L &lt;= 1000000<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
5 ~ 6<br/>
</td>
<td rowspan="2" style="border:1pt solid;" valign="top">
N &lt;= 1000<br/>
</td>
<td rowspan="5" style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
7 ~ 8<br/>
</td>
<td rowspan="2" style="border:1pt solid;" valign="top">
M = 1 且<br/>
A1 = 0, B1 = L<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
9 ~ 10<br/>
</td>
<td rowspan="2" style="border:1pt solid;" valign="top">
N &lt;= 100000<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
11~12<br/>
</td>
<td rowspan="2" style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
13~20<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
</tbody>
</table>
</div>
</div>
