# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
   P老师需要去商店买n支铅笔作为小朋友们参加NOIP的礼物。她发现商店一共有3种包装的铅笔，不同包装内的铅笔数量有可能不同，价格也有可能不同。为了公平起见，P老师决定只买同一种包装的铅笔。
</p>
<p>
   商店不允许将铅笔的包装拆开，因此P老师可能需要购买超过n支铅笔才够给小朋友们发礼物。
</p>
<p>
   现在P老师想知道，在商店每种包装的数量都足够的情况下，要买够至少n支铅笔最少需要花费多少钱。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
从文件中读入数据。
</p>
<p>
   输入的第一行包含一个正整数n，表示需要的铅笔数量。
</p>
<p>
   接下来三行，每行用两个正整数描述一种包装的铅笔:其中第一个整数表示这种包装内铅笔的数量，第二个整数表示这种包装的价格。
</p>
<p>
   保证所有的7个数都是不超过10000的正整数。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出到文件中。
</p>
<p>
输出一行一个整数，表示P老师最少需要花费的钱。
</p>
<p>
<br/>
</p>
<h3>
【样例输入1】
</h3>
<pre>57
2 2
50 30
30 27</pre>
<h3>
【样例输出1】
</h3>
<pre>54</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
铅笔的三种包装分别是:
</p>
<p>
   ·2支装，价格为2;
</p>
<p>
   ·50支装，价格为30;
</p>
<p>
   ·30支装，价格为27。
</p>
<p>
   P老师需要购买至少_57支铅笔。
</p>
<p>
   如果她选择购买第一种包装，那么她需要购买29份，共计2x29=_5 8支，需要花费的钱为2*29=58
</p>
<p>
   实际上，P老师会选择购买第三种包装，这样需要买2份。虽然最后买到的铅笔数量更多了，为30*2=60支，但花费却减少为27*2=54，比第一种少。
</p>
<p>
   对于第二种包装，虽然每支铅笔的价格是最低的，但要够发必须买2份，实际的花费达到了30*2=60，因此P老师也不会选择。
</p>
<p>
   所以最后输出的答案是54。
</p>
<p>
<br/>
</p>
<h3>
【样例输入2】
</h3>
<pre>9998
128 233
128 2333
128 666</pre>
<h3>
【样例输出2】
</h3>
<pre>18407</pre>
<h3>
【样例输入3】
</h3>
<pre>9999
101 1111
1 9999
1111 9999</pre>
<h3>
【样例输出3】
</h3>
<pre>89991</pre>
<h3>
【数据规模】
</h3>
<p>
<br/>
</p>
<p>
   子任务会给出部分测试数据的特点。如果你在解决题目中遇到了困难，可以尝试只解决一部分测试数据。
</p>
<p>
   每个测试点的数据规模及特点如下表:
</p>
<p>
<img src="/upload/image/20161124/20161124060941_84732.jpg" alt=""/> 
</p>
<p>
<br/>
</p>
<p>
上表中“整倍数”的意义为:若为“√”，表示对应数据所需要的铅笔数量n一定是每种包装铅笔数量的整倍数(这意味着一定可以不用多买铅笔)。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
【来源】
<p>
NOIP2016 普及组题1
</p>