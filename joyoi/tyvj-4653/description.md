# 

 
 # 题目描述 
<p>所谓傻瓜电梯指的是在响应用户请求时缺乏相应的&ldquo;智商&rdquo;，在上升或下降的过程中不<br />
能把中途的乘客捎带入电梯，而只会严格按照用户发出请求的先后顺序依次完成任务。<br />
比如，原来电梯在1楼，首先6&nbsp;楼有一位乘客发出请求，要求由6&nbsp;楼乘坐到10楼去，<br />
此时电梯马上会上去，但在电梯上升到3&nbsp;楼时，另外一位乘客请求由5&nbsp;楼乘坐到8楼去，傻<br />
瓜电梯却不会在上升途中把5&nbsp;楼的乘客捎带上去，而只会先把6&nbsp;楼的乘客送到10&nbsp;楼，然后<br />
再下来把5搂的乘客送到8楼。<br />
傻瓜电梯由i&nbsp;楼上升到i+1楼（或下降到i-1&nbsp;楼）的时间都是3&nbsp;秒，每到达一个楼层，<br />
不管进出乘客有多少，也不管乘客只有进、只有出或者进出电梯都有，所耽搁的时间都是6<br />
秒。现在味味要根据傻瓜电梯接受到的n个用户请求，编程计算傻瓜电梯把所有乘客送到目<br />
标楼层时总共所需要的时间。<br />
如果某批乘客到达目标楼层后，电梯没有马上要响应的请求，则电梯在前一批乘客的<br />
目的地等待，这个等待时间也需计入总花费时间。直到下一批乘客发出新请求，电梯才会从<br />
当前位置出发，前往下一批乘客的出发楼层。</p> 

 
 # 输入格式 
<p>第一行包含两个整数x（1&lt;=x&lt;=100）和n（1&lt;=n&lt;=100），分别表示<br />
傻瓜电梯开始所在的楼层和总共接收到的请求数目。下面有n行，每行包含3个整数，依次<br />
表示该请求发出的时间、乘客目前所在的楼层和将要去的目标楼层。其中请求发出的时间以<br />
秒为时刻单位，最大可能的值是2000。如果某两个请求的发出时间相同，则按照输入文件<br />
中原始的先后顺序依次处理。</p> 

 
 # 输出格式 
<p>只包含一行一个整数，表示傻瓜电梯把所有乘客送到目标楼层后总<br />
共所需要的时间（从得到第一条请求时开始计算时间），单位是秒。</p> 

 
 # 提示 
<p>输入样例1：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输出样例1：</p>

<p>3&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;162<br />
10&nbsp;10&nbsp;2<br />
18&nbsp;1&nbsp;9<br />
2&nbsp;1&nbsp;12<br />
8&nbsp;6&nbsp;10</p>

<p>【样例&nbsp;1&nbsp;解释】<br />
第一批乘客发出请求到离开电梯所需时间：3*2+6+3*11+6=51<br />
从前一批乘客离开电梯到第二批乘客离开电梯所需时间：3*6+6+3*4+6=42<br />
第三批乘客从出发地出发到离开电梯所需时间：<br />
3*8+6=30（由于出发地与前一批乘客目的地相同，所以上下客时间不必再加6）<br />
从前一批乘客离开电梯到第四批乘客离开电梯所需时间：3+6+3*8+6=39<br />
总花费时间：51+42+30+39=162</p>

<p>输入样例2：&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;输出样例2：</p>

<p>1&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;60<br />
10&nbsp;2&nbsp;3<br />
30&nbsp;5&nbsp;1</p> 
