# 题目描述


<p>
【题面】
</p>
<p>
     在召唤师峡谷，英雄们又爆发了一场场激烈的战斗，璐璐可以为战斗的英雄们提供一个防护罩，防止英雄们由于血量过低而提早退出战场。如果英雄的血量过低，就算璐璐治疗他也无济于事。他还是会被敌方强大的炮火击败。而英雄的血量过高，则不用璐璐的治疗，所以璐璐希望对战场中血量第Ki小的英雄进行治疗。
</p>
<p>
    由于战场上瞬息万变，英雄的血量总是在不断的变化中，另外，激烈的战场影响了璐璐的心情，所以Ki总是在不断的变化中，璐璐想知道她该对谁进行治疗，请告诉她。 
</p>
<p>
【输入与输出说明】 
</p>
<p>
      第一行输入一个T，代表有T组数据。
        输入 N 与 M 表示 有N个英雄， 接下来有M次变化。 
</p>
<p>
      下一行 是N个数据， 表示N个英雄的初始血量。
</p>
<p>
      接下来的M行 每一行输入 ai 
</p>
<p>
           若 ai=1 则      则再输入bi     
表示血量为bi的英雄阵亡一个。 
</p>
<p>
           若 ai=2 则      则再输入bi    表示复活了一个血量为bi的英雄。
</p>
<p>
           若 ai=3 则      则再输入bi与ci，则表示一个bi血量的英雄血量变成了ci。
</p>
<p>
           若 ai=4 则      再输入Ki ，表示查询血量第Ki小的英雄，并输出他的血量并换行。
</p>
<p>
           对于所有ai=2或3，保证bi存在。 
</p>
<p>
【样例输入】
</p>
<p>
    1
</p>
<p>
    5 7 
</p>
<p>
    10 20 50 30 40 
</p>
<p>
    4 3 
</p>
<p>
    1 20 
</p>
<p>
    2 25 
</p>
<p>
    3 50 35 
</p>
<p>
    4 4 
</p>
<p>
    3 10 30 
</p>
<p>
    4 3 
</p>
<p>
【样例输出】 
</p>
<p>
    30 
</p>
<p>
    35 
</p>
<p>
    30 
</p>
<p>
【数据规模】
</p>
<p>
    所有数据保证小于等于1&lt;&lt;20. 
</p>
<p>
    5%的数据保证t&lt;=2, n=&lt;10，m&lt;=15; 
</p>
<p>
    10%的数据保证t&lt;=5, n&lt;=20，m&lt;=300; 
</p>
<p>
    30%的数据保证t&lt;=20, n&lt;=1000，m&lt;=3000;
</p>
<p>
    50%的数据保证t&lt;=25, n&lt;=3000，m&lt;=6000; 
</p>
<p>
    100%的数据保证t&lt;=50, n&lt;=10000，m&lt;=30000; 
</p>
<p>
<br/>
</p>
<p>
    时限2秒。空间32MB。 
</p>