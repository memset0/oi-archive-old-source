<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个n个顶点的有向图，每个顶点有且仅有一条出边。<br>对于顶点i，记它的出边为(i, a[i])。<br>再给出q组询问，每组询问由两个顶点a、b组成，要求输出满足下面条件的x、y：<br>1. 从顶点a沿着出边走x步和从顶点b沿着出边走y步后到达的顶点相同。<br>2. 在满足条件1的情况下max(x,y)最小。<br>3. 在满足条件1和2的情况下min(x,y)最小。<br>4. 如果满足条件1、2和3的存在多组，这时候选择x&gt;=y的那一组。<br>如果不存在满足条件1的x、y，输出-1 -1。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数n和q (n,q&lt;=500,000)。<br>第二行n个正整数a[1],a[2],...,a[n] (a[i]&lt;=n)。<br>下面q行，每行两个正整数a,b (a,b&lt;=n)，表示一组询问。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出q行，每行两个整数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>12 5<br>4 3 5 5 1 1 12 12 9 9 7 1<br>7 2<br>8 11<br>1 2<br>9 10<br>10 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 3<br>1 2<br>2 2<br>0 1<br>-1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>第一组数据是样例</p>
</div>
</div>