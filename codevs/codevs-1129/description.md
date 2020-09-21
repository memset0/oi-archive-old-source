<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>小涵很喜欢电脑游戏，这些天他正在玩一个叫做《三国》的游戏。 在游戏中，小涵和计算机各执一方，组建各自的军队进行对战。游戏中共有N 位武将（N 为偶数且不小于4），任意两个武将之间有一个“默契值”，表示若此两位武将作为一对组合 作战时，该组合的威力有多大。游戏开始前，所有武将都是自由的（称为自由武将，一旦某 个自由武将被选中作为某方军队的一员，那么他就不再是自由武将了），换句话说，所谓的 自由武将不属于任何一方。游戏开始，小涵和计算机要从自由武将中挑选武将组成自己的军 队，规则如下：小涵先从自由武将中选出一个加入自己的军队，然后计算机也从自由武将中 选出一个加入计算机方的军队。接下来一直按照“小涵→计算机→小涵→……”的顺序选择 武将，直到所有的武将被双方均分完。然后，程序自动从双方军队中各挑出一对默契值最高 的武将组合代表自己的军队进行二对二比武，拥有更高默契值的一对武将组合获胜，表示两 军交战，拥有获胜武将组合的一方获胜。 已知计算机一方选择武将的原则是尽量破坏对手下一步将形成的最强组合，它采取的具 体策略如下：任何时刻，轮到计算机挑选时，它会尝试将对手军队中的每个武将与当前每个 自由武将进行一一配对，找出所有配对中默契值最高的那对武将组合，并将该组合中的自由 武将选入自己的军队。 下面举例说明计算机的选将策略，例如，游戏中一共有6 个武将，他们相互之间的默契 值如下表所示</span><br><img height="548" src="/source/codevs/codevs-1129/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9aFQ2Ymg4eWg=.do" width="550"><img src="/source/codevs/codevs-1129/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TTU2TVRNNEU=.do" width="550"><span>　　小涵想知道，如果计算机在一局游戏中始终坚持上面这个策略，那么自己有没有可能必 胜？如果有，在所有可能的胜利结局中，自己那对用于比武的武将组合的默契值最大是多 少？ 假设整个游戏过程中，对战双方任何时候均能看到自由武将队中的武将和对方军队的武 将。为了简化问题，保证对于不同的武将组合，其默契值均不相同。</span></p>
<p><span><br></span></p>
<p><span><span>对于40%的数据有N≤ 10。</span><br><span>对于70%的数据有N≤ 18。</span><br><span>对于100%的数据有N≤ 500</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入共N 行。 第一行为一个偶数N，表示武将的个数。 第2 行到第N 行里，第（i+1）行有（N−i）个非负整数，每两个数之间用一个空格隔 开，表示i 号武将和i+1，i+2，……，N 号武将之间的默契值（0 ≤ 默契值≤ 1,000,000,000）。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出共1 或2 行。 若对于给定的游戏输入，存在可以让小涵获胜的选将顺序，则输出1，并另起一行输出 所有获胜的情况中，小涵最终选出的武将组合的最大默契值。 如果不存在可以让小涵获胜的选将顺序，则输出0。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6</span><br><span>5 28 16 29 27</span><br><span>23 3 20 1</span><br><span>8 32 26</span><br><span>33 11</span><br><span>12</span><br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>1</span><br><span>32</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>首先小涵拿走5 号武将；计算机发现5 号武将和剩下武将中的4 号默契值最高，于是拿</span><span>走4 号；小涵接着拿走3 号；计算机发现3、5 号武将之一和剩下的武将配对的所有组合中，</span><span>5 号和1 号默契值最高，于是拿走1 号；小涵接着拿走2 号；计算机最后拿走6 号。在小涵</span><span>手里的2，3，5 号武将中，3 号和5 号配合最好，默契值为32，而计算机能推出的最好组合</span><span>为1 号和6 号，默契值为27。结果为小涵胜，并且这个组合是小涵用尽所有方法能取到的</span><span>最好组合。</span></p>
</div>
</div>