<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小白的生日就要到了，小蓝决定送一件自己亲手做的手工艺品使自己的礼物与众不同。具体来说，小蓝已经通过某种方式制作出了一个<span style="text-decoration: underline;">p</span><span style="text-decoration: underline;">×</span><span style="text-decoration: underline;">q</span><span style="text-decoration: underline;">×r的木块（由pqr个单位小木块组成）</span>。但由于小蓝手艺不精，现在这个木块中的有些单位小木块是有问题的(有裂缝、里面是空心等等)，这样的礼物小蓝是不可能直接送出去的。</p>
<p>于是小蓝决定在这个木块中再挖出一个<span style="text-decoration: underline;">a</span><span style="text-decoration: underline;">×</span><span style="text-decoration: underline;">a</span><span style="text-decoration: underline;">×b</span>的子木块(即要求挖出的长方体木块存在两条长度相等的相邻边)，当然这个子木块中是不能包含有问题的单位小木块的。为了使这个木块上能包含更多的图案，小蓝希望从所有可行的方案中挑取<span style="text-decoration: underline;">4ab</span>的值最大的方案。但小蓝光检测木块中哪些地方有问题就已经耗尽了体力，作为小蓝的好友，你能帮帮小蓝吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每个输入文件中仅包含一个测试数据。</p>
<p>第一行包含三个由空格隔开的正整数，p,q,r。</p>
<p>     接下来有pq行，每行包含r个字符，每个字符只可能是’P’(Poor)或者’N’(Nice)，表示该单位小木块有问题或者没问题。具体的说，<span style="text-decoration: underline;">第</span><span style="text-decoration: underline;">1+(yp+x-p)</span><span style="text-decoration: underline;">行的第</span><span style="text-decoration: underline;">z</span><span style="text-decoration: underline;">个字符描述的是坐标为</span><span style="text-decoration: underline;">(x,y,z)</span><span style="text-decoration: underline;">的小木块情况</span>。(1&lt;=x&lt;=p,1&lt;=y&lt;=q,1&lt;=z&lt;=r)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;输出文件仅包含一个整数，表示最佳方案的4ab的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2 5</p>
<p>PNNNN</p>
<p>PNNNN</p>
<p>NPPNP</p>
<p>PNNNP</p>
<p>NNNNP</p>
<p>PPNNP</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>24</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，0&lt;p,q,r&lt;=150，输入中至少包含一个’N’</p>
</div>
</div>