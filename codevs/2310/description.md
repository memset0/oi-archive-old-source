<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>在一个遥远的世界里有两个国家：位于大陆西端的杰森国和位于大陆东端的 克里斯国。两个国家的人民分别信仰两个对立的神：杰森国信仰象征黑暗和毁灭 的神曾·布拉泽，而克里斯国信仰象征光明和永恒的神斯普林·布拉泽。</span></p>
<p><span> 幻想历 8012年 1月，杰森国正式宣布曾·布拉泽是他们唯一信仰的神，同 时开始迫害在杰森国的信仰斯普林·布拉泽的克里斯国教徒。</span></p>
<p><span> 幻想历 8012年 3月2日，位于杰森国东部小镇神谕镇的克里斯国教徒发动 起义。 </span></p>
<p><span>幻想历 8012年 3月7日，神谕镇的起义被杰森国大军以残酷手段镇压。 </span></p>
<p><span>幻想历 8012年 3月8日，克里斯国对杰森国宣战。由数十万大军组成的克 里斯军团开至两国边境，与杰森军团对峙。 </span></p>
<p><span>幻想历 8012年 4月，克里斯军团攻破杰森军团防线进入神谕镇，该镇幸存 的克里斯国教徒得到解放。</span></p>
<p><span> 战争随后进入胶着状态，旷日持久。战况惨烈，一时间枪林弹雨，硝烟弥漫， 民不聊生。</span></p>
<p><span> 幻想历 8012年 5月12日深夜，斯普林·布拉泽降下神谕：“Trust me, earn eternal life.”克里斯军团士气大增。作为克里斯军团的主帅，你决定利用这一机 会发动奇袭，一举击败杰森国。具体地说，杰森国有 N 个城市，由 M条单向道 路连接。神谕镇是城市 1而杰森国的首都是城市 N。你只需摧毁位于杰森国首都 的曾·布拉泽大神殿，杰森国的信仰，军队还有一切就都会土崩瓦解，灰飞烟灭。</span></p>
<p><span>为了尽量减小己方的消耗，你决定使用自爆机器人完成这一任务。唯一的困 难是，杰森国的一部分城市有结界保护，不破坏掉结界就无法进入城市。而每个 城市的结界都是由分布在其他城市中的一些结界发生器维持的，如果想进入某个 城市，你就必须破坏掉维持这个城市结界的所有结界发生器。</span></p>
<p><span> 现在你有无限多的自爆机器人，一旦进入了某个城市，自爆机器人可以瞬间 引爆，破坏一个目标（结界发生器，或是杰森国大神殿），当然机器人本身也会 一起被破坏。你需要知道：摧毁杰森国所需的最短时间。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行两个正整数 N, M。</span></p>
<p><span> 接下来 M行，每行三个正整数 ui, vi, wi，表示有一条从城市ui到城市 vi的单 向道路，自爆机器人通过这条道路需要 wi的时间。</span></p>
<p><span> 之后 N 行，每行描述一个城市。首先是一个正整数 li，维持这个城市结界所 使用的结界发生器数目。</span><span style="">之后li个1~N 之间的城市编号，表示每个结界发生器的 位置。如果 Li = 0，则说明该城市没有结界保护，保证L1 = 0 。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅包含一个正整数 ，击败杰森国所需的最短时间。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>6 6 </span><br><span> 1 2 1 </span><br><span> 1 4 3 </span><br><span> 2 3 1 </span><br><span> 2 5 2 </span><br><span> 4 6 2 </span><br><span> 5 3 2 </span><br><span> 0 </span><br><span> 0 </span><br><span> 0 </span><br><span> 1 3 </span><br><span> 0 </span><br><span> 2 3 5 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>对于 20%的数据，满足 N≤15，M≤50； </span><br><span>对于 50%的数据，满足 N≤500，M≤6,000； </span><br><span>对于 100%的数据，满足 N≤3,000，M≤70,000，1≤wi≤10<sup>8</sup></span><span>。 </span><br><span>输入数据保证一定有解，且不会存在维持某个城市结界的结界发生器在这个</span><br><span>城市内部。 </span><br><span>连接两个城市的道路可能不止一条， 也可能存在一个城市自己到自己的道路。</span></p>
</div>
</div>