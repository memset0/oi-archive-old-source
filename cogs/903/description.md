# 题目描述


<div>
USACO/snail(译 by Felicia Crazy)
<hr/>
</div>
<p>
描述
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">萨丽·斯内尔（Sally Snail，蜗牛）喜欢在 N x N 的棋盘上闲逛（1 &lt; n &lt; 120）。她总是从棋盘的左上角出发。棋盘上有空的格子（用“.”来表示）和 B 个路障（用“#”来表示）。下面是这种表示法的示例棋盘：</span>
</p>
<pre>          A B C D E F G H
        1 S . . . . . # .
        2 . . . . # . . .
        3 . . . . . . . .
        4 . . . . . . . .
        5 . . . . . # . .
        6 # . . . . . . .
        7 . . . . . . . .
        8 . . . . . . . .</pre>
<br/>
萨丽总是垂直（向上或者向下）或水平（向左或者向右）地走。她可以从出发地（总是记作 A1 ）向下或者向右走。
<p>
<span style="font-family:&#39;Times New Roman&#39;;">一旦萨丽选定了一个方向，她就会一直走下去。如果她遇到棋盘边缘或者路障，她就停下来，并且转过 90 度。她不可能离开棋盘，或者走进路障当中。并且，萨丽从不跨过她已经经过的格子。当她再也不能走的时候，她就停止散步。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">这里是上面的棋盘上的一次散步路线图示： </span> 
</p>
<pre>         A B C D E F G H
        1 S---------+ # .
        2 . . . . # | . .
        3 . . . . . | . .
        4 . . . . . +---+
        5 . . . . . # . |
        6 # . . . . . . |
        7 +-----------+ |
        8 +-------------+


</pre>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">萨丽向右走，再向下，向右，向下，然后向左，再向上，最后向右走。这时她遇到了一个她已经走过的格子，她就停下来了。但是，如果她在 F5 格遇到路障后选择另外一条路——向我们看来是左边的方向转弯，情况就不一样了。 </span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">你的任务是计算并输出，如果萨丽聪明地选择她的路线的话，她所能够经过的最多格子数。 </span> 
</p>
<p>
 
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">PROGRAM NAME: snail </span> 
</h3>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">INPUT FORMAT (file snail.in)</span> 
</h3>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">输入的第一行包括 N ——棋盘的大小，和 B ——路障的数量（1 &lt;= B &lt;= 200）。接下来的 B 行包含着路障的位置信息。下面的样例输入对应着上面的示例棋盘。下面的输出文件表示问题的解答。注意，当 N 〉26 时，输入文件就不能表示 Z 列以后的路障了（这一点你不必在程序中做出判断）。 </span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">OUTPUT FORMAT  (file snail.out)</span> 
</h3>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">输出文件应该只由一行组成，即萨丽能够经过的最多格子数。</span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;"><strong>SAMPLE INPUT (file snail.in) </strong></span> 
</p>
<p>
<span style="font-family:&#39;Times New Roman&#39;;">8 4 E2 A6 G1 F5 </span> 
</p>
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Times New Roman&#39;;">SAMPLE OUTPUT (file snail.out) </span> 
</h3>
<span style="font-family:&#39;Times New Roman&#39;;">33</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
<p>
<br/>
</p>
<span style="font-family:&#39;Times New Roman&#39;;"></span> 
<p>
<br/>
</p>
<p>
<br/>
</p>