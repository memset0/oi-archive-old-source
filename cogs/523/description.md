# 题目描述


<p class="STYLE9">农夫约翰总是希望他的奶牛有足够的水喝，因而他曾测绘过一张地图，该图描述了连接农场上水井和谷仓的N（1&lt;=N&lt;=700）条水管的分布情况。他吃惊地发现大量不同口径的水管明显以随意的方式连接着。</p>
<p class="STYLE9">他想要计算出通过水管系统的总流量。</p>
<p class="STYLE9">由两条水管串联而形成的水管的流量等于二者流量的最小值。例如两条流量分别为5和3的水管串联形成的水管则被从逻辑上变为一条流量为3的单管，如图所示：</p>
<p class="STYLE9">+---5---+---3---+  -&gt;  +---3---+</p>
<p class="STYLE9">同样，并联的水管允许通过的水量是二者流量的总和，如图所示：</p>
<p class="STYLE9">   +---5---+<br/>
---+       +---  -&gt;  +---8---+<br/>
   +---3---+</p>
<p class="STYLE9">最后，没有和其他任何水管连接的水管可以删除掉；它对总体的流量没有贡献值，如图所示：</p>
<p class="STYLE9">   +---5---+<br/>
---+             -&gt;  +---3---+<br/>
   +---3---+--<br/>
这迷宫式的配管系统中的所有水管流量均可按照这一原则变为一个单管的总流量。</p>
<p class="STYLE9">给定一个管道地图，请确定水井和谷仓之间的总流量。</p>
<p class="STYLE9">考虑以下样例，图中结点均以字母标记。</p>
<p><br/>
         +-----------6-----------+<br/>
A+---3---+B                      +Z<br/>
         +---3---+---5---+---4---+<br/>
                 C       D</p>
<p>管道 BC 和 CD 可组合为:</p>
<p>         +-----------6-----------+<br/>
A+---3---+B                      +Z<br/>
         +-----3-----+-----4-----+<br/>
                     D</p>
<p>然后，管道 BD 和 DZ 可组合为:</p>
<p>         +-----------6-----------+<br/>
A+---3---+B                      +Z<br/>
         +-----------3-----------+</p>
<p>然后，BZ的两条分支可组合为:</p>
<p>         B<br/>
A+---3---+---9---+Z</p>
<p>然后，AB 和 BZ 组合生成净流量3：</p>
<p>A+---3---+Z</p>
<p class="STYLE9">编程读入一组管道数据，管道以端结点方式描述，然后计算出从&#34;A&#34;到&#34;Z&#34;的净流量。测试数据中的所有管道网络都可以使用以上规则生成。</p>
<p class="STYLE9">管道i连接两个不同的结点a_i和b_i（a_i和b_i的范围都是&#34;A-Za-z&#34;）,管道i的流量为F_i(1&lt;= F_i&lt;=1000)。注意：大写和小写会被看做是不同的结点名称。</p>
<p class="STYLE9">针对你前50次的提交，系统会提供额外的测试用例反馈。</p>
<p class="STYLE9">程序名：flow</p>
<p class="STYLE9">输入格式：</p>
<p class="STYLE9">*第一行：一个整型数：N；</p>
<p class="STYLE9">*第二行到第N+1行：第i+1行以两个字母和一个整型数的形式描述了管道i，即：空格隔开的a_i b_i F_i。</p>
<p class="STYLE9">输入样例（flow.in）：</p>
<p class="STYLE9">5<br/>
A B 3<br/>
B C 3<br/>
C D 5<br/>
D Z 4<br/>
B Z 6<br/>
 </p>
<p class="STYLE9">输出格式：</p>
<p class="STYLE9">*第一行：一个整型数，该数描述了从水井&#34;A&#34;到谷仓&#34;Z&#34;的管道的最大流量。</p>
<p class="STYLE9">样例输出（flow.out）：</p>
<p class="STYLE9">3</p>
