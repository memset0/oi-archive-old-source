<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个魔法森林里，住着一只聪明的小猫聪聪和一只可爱的小老鼠可可。虽 然灰姑娘非常喜欢她们俩，但是，聪聪终究是一只猫，而可可终究是一只老鼠， 同样不变的是，聪聪成天想着要吃掉可可。 <br>一天，聪聪意外得到了一台非常有用的机器，据说是叫 GPS，对可可能准确 的定位。有了这台机器，聪聪要吃可可就易如反掌了。于是，聪聪准备马上出发， 去找可可。而可怜的可可还不知道大难即将临头，仍在森林里无忧无虑的玩耍。 小兔子乖乖听到这件事，马上向灰姑娘报告。灰姑娘决定尽快阻止聪聪，拯救可 可，可她不知道还有没有足够的时间。 <br>整个森林可以认为是一个无向图，图中有 N 个美丽的景点，景点从 1 至 N 编号。小动物们都只在景点休息、玩耍。在景点之间有一些路连接。 <br>当聪聪得到 GPS 时，可可正在景点 M(M≤N)处。以后的每个时间单位，可可 都会选择去相邻的景点(可能有多个)中的一个或停留在原景点不动。而去这些地 方所发生的概率是相等的。假设有 P 个景点与景点 M 相邻，它们分别是景点 R、 景点 S，……景点 Q，在时刻 T 可可处在景点 M，则在(T＋1)时刻，可可有 1/（1 + P） 的可能在景点 R，有 1/（1 + P） 的可能在景点 S，……，有 1/（1 + P） 的可能在景点 Q，还有1/（1 + P）的可能停在景点 M。 <br>我们知道，聪聪是很聪明的，所以，当她在景点 C 时，她会选一个更靠近 可可的景点，如果这样的景点有多个，她会选一个标号最小的景点。由于聪聪太 想吃掉可可了，如果走完第一步以后仍然没吃到可可，她还可以在本段时间内再 向可可走近一步。 <br>在每个时间单位，假设聪聪先走，可可后走。在某一时刻，若聪聪和可可位 于同一个景点，则可怜的可可就被吃掉了。 <br>灰姑娘想知道，平均情况下，聪聪几步就可能吃到可可。而你需要帮助灰姑 娘尽快的找到答案。</p>

<img src="/source/codevs/codevs-1784/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzg0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NTc3MDQ1Ny43MC45NDgxMzA4NjExNjEucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>数据的第 1 行为两个整数 N 和 E，以空格分隔，分别表示森林中的景点数和 连接相邻景点的路的条数。 第 2 行包含两个整数 C 和 M，以空格分隔，分 别表示初始时聪聪和可可所在 的景点的编号。 接下来 E 行，每行两个整数，第 i+2 行的两个整数 Ai和 Bi表示景点 Ai和景 点 Bi 之间有一条路。 所有的路都是无向的，即：如果能从 A 走到 B，就可以从 B 走到 A。 输入保证任何两个景点之间不会有多于一条路直接相连，且聪聪和可可之间 必有路直接或间接的相连。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出到文件 cchkk.out 中。 输出 1 个实数，四舍五入保留三位小数，表示平均多少个时间单位后聪聪会把可可吃掉</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例输入1：</p>
<p>4 3</p>
<p>1 4</p>
<p>1 2</p>
<p>2 3</p>
<p>3 4</p>
<p>样例输入2：</p>
<p>9 9</p>
<p>9 <span style="">3</span></p>
<p><span style=""> 1 2</span></p>
<p><span style=""> 2 3</span></p>
<p><span style=""> 3 4</span></p>
<p><span style=""> 4 5</span></p>
<p><span style=""> 3 6</span></p>
<p><span style=""> 4 6</span></p>
<p><span style=""> 4 7</span></p>
<p><span style=""> 7 8</span></p>
<p><span style=""> 8 9</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例输出1：</p>
<p>1.500</p>
<p>样例输出2：</p>
<p>2.167 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于样例输出1：开始时，聪聪和可可分别在景点 1 和景点 4。 第一个时刻，聪聪先走，她向更靠近可可(景点 4)的景点走动，走到景点 2， 然后走到景点 3；假定忽略走路所花时间。 可可后走，有两种可能： 第一种是走到景点 3，这样聪聪和可可到达同一个景点，可可被吃掉，步数为 1，概率为0.5。 <br>第二种是停在景点 4，不被吃掉。概率为0.5。 <br>到第二个时刻，聪聪向更靠近可可(景点 4)的景点走动，只需要走一步即和 可可在同一景点。因此这种情况下聪聪会在两步吃掉可可。 所以平均的步数是 1*0.5 +2*0.5 =1.5 步。</p>
<p>对于样例输出2，详见图片。</p>
</div>
</div>