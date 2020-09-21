<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小新正在玩一个简单的电脑游戏。<br>游戏中有一条环形马路，马路上有n 个机器人工厂，两个相邻机器人工厂之间由一小段马路连接。小新以某个机器人工厂为起点，按顺时针顺序依次将这n 个机器人工厂编号为1~n，因为马路是环形的，所以第n 个机器人工厂和第1 个机器人工厂是由一段马路连接在一起的。小新将连接机器人工厂的这n 段马路也编号为1~n，并规定第i 段马路连接第i 个机器人工厂和第i+1 个机器人工厂（1 ≤ i ≤ n-1），第n 段马路连接第n 个机器人工厂和第1个机器人工厂。<br>游戏过程中，每个单位时间内，每段马路上都会出现一些金币，金币的数量会随着时间发生变化，即不同单位时间内同一段马路上出现的金币数量可能是不同的。小新需要机器人的帮助才能收集到马路上的金币。所需的机器人必须在机器人工厂用一些金币来购买，机器人一旦被购买，便会沿着环形马路按顺时针方向一直行走，在每个单位时间内行走一次，即从当前所在的机器人工厂到达相邻的下一个机器人工厂，并将经过的马路上的所有金币收集给小新，例如，小新在i（1 ≤ i ≤ n）号机器人工厂购买了一个机器人，这个机器人会从i 号机器人工厂开始，顺时针在马路上行走，第一次行走会经过i 号马路，到达i+1 号机器人工厂（如果i=n，机器人会到达第1 个机器人工厂），并将i 号马路上的所有金币收集给小新。<br>游戏中，环形马路上不能同时存在2 个或者2 个以上的机器人，并且每个机器人最多能够在环形马路上行走p 次。小新购买机器人的同时，需要给这个机器人设定行走次数，行走次数可以为1~p 之间的任意整数。当马路上的机器人行走完规定的次数之后会自动消失，小新必须立刻在任意一个机器人工厂中购买一个新的机器人，并给新的机器人设定新的行走次数。<br>以下是游戏的一些补充说明：<br>1. 游戏从小新第一次购买机器人开始计时。<br>2. 购买机器人和设定机器人的行走次数是瞬间完成的，不需要花费时间。<br>3. 购买机器人和机器人行走是两个独立的过程，机器人行走时不能购买机器人，购买完机器人并且设定机器人行走次数之后机器人才能行走。<br>4. 在同一个机器人工厂购买机器人的花费是相同的，但是在不同机器人工厂购买机器人的花费不一定相同。<br>5. 购买机器人花费的金币，在游戏结束时再从小新收集的金币中扣除，所以在游戏过程中小新不用担心因金币不足，无法购买机器人而导致游戏无法进行。也因为如此，游戏结束后，收集的金币数量可能为负。<br>现在已知每段马路上每个单位时间内出现的金币数量和在每个机器人工厂购买机器人需要的花费，请你告诉小新，经过m 个单位时间后，扣除购买机器人的花费，小新最多能收集到多少金币。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行 3 个正整数，n，m，p，意义如题目所述。<br>接下来的 n 行，每行有m 个正整数，每两个整数之间用一个空格隔开，其中第i 行描述了i 号马路上每个单位时间内出现的金币数量（1 ≤ 金币数量≤ 100），即第i 行的第j（1 ≤ j ≤m）个数表示第j 个单位时间内i 号马路上出现的金币数量。<br>最后一行，有 n 个整数，每两个整数之间用一个空格隔开，其中第i 个数表示在i 号机器人工厂购买机器人需要花费的金币数量（1 ≤ 金币数量≤ 100）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共一行，包含1 个整数，表示在m 个单位时间内，扣除购买机器人花费的金币之后，小新最多能收集到多少金币。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3 2<br>1 2 3<br>2 3 4<br>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>对于 40%的数据，2 ≤ n ≤ 40，1 ≤m≤ 40。<br>对于 90%的数据，2 ≤ n ≤ 200，1 ≤m≤ 200。<br>对于 100%的数据，2 ≤ n ≤ 1000，1 ≤m≤ 1000，1 ≤ p ≤m。</p>
</div>
</div>