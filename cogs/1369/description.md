# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
Dr.Kong 有一台高级电视机，这台电视机可以接受100个频道（从0到99编号）。电视的配套遥控器有13个按钮：
</p>
<p>
           1    2    3   ↑
</p>
<p>
           4    5    6   ↓
</p>
<p>
           7    8    9
</p>
<p>
           -    0
</p>
<p>
  当按&#34;↑&#34;键时，当前频道编号会增加1(如果当前为99频道，则会切换到0频道)。如果按&#34;↓&#34;键，当前频道编号会减小1(如果当前为0频道，则会切换到99频道)。当要切换到0~9频道时，可以直接在遥控器上按相应的键。当要切换到10~99频道时，可以先按&#34;—&#34;键，
</p>
<p>
然后按2个与频道编号相对应的数字键(即先按与频道编号的十位数字相对应的键，然后按与个位数字相对应的键)。
</p>
<p>
  由于遥控器长时间的使用和某些未知原因，遥控器上的某些键已经坏了，不能再起作用了。现在你的任务是，能否告诉Dr.Kong，如何用最少的按键次数来将频道从编号X切换到编号Y。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
输入数据有5行，前4行包含遥控器上每个按键的信息。0表示对应的键坏了，1表示对应的键可以使用。第5行包含2个整数，分别是X 和 Y    (0 &lt;= X &lt;= 99; 0 &lt;= Y &lt;= 99)。数据之间用一个空格隔开。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行，将频道从编号X切换到编号Y所需要的最小按键次数。如果不可能将频道从编号X 切换到编号Y，则输出-1.
</p>
<h3>
【样例输入】
</h3>
<pre>0 0 1 1
1 1 1 1
1 1 1
1 1
23 52</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
