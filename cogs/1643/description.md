# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
    一定数量（k个）的球从一个满二叉树的根上一个接一个掉下来， 每次球先访问非终端节点。然后他继续下落， 或走左子树，或走右子树，直到它停在一个叫FBT的叶子节点。为了标志小球下落的路线， 在每一个非终端节点设一个标志，真或者假。最初， 所有标志都是假， 当一个小球访问一个非终端节点时，如果这个节点标志为假，则标志为真，然后沿左子树走。否则， 同样要改变这个节点的标志，从真变到假，然后沿右子树走。 此外，所有FBT节点都被连续的标号，深度为1的节点从1号开始标，然后标深度为2的，以此类推。 每一层都从左到右开始编号。
</p>
<p>
     如下图表示一个深度为4编号从1…..15的满二叉树。从所有节点标号为假开始，第一个球将改变1，2，4的标志，最后落在8上。第二个球将改变1，3，6的标志，最后落在12上。很明显，第三个球将改变1，2，5的标志，最后落在10上。
</p>
<p>
                    <img alt="" src="/upload/image/20140524/20140524212437_96558.gif"/> 
</p>
<p>
<br/>
</p>
<p>
                                         1个深度为4并连续编号的FBT
</p>
<p>
    现在每组数据给你两个数，第一个数是D，即FBT最大深度，第二个数是I，即第几个球将掉下来。你将要算出第I个球将落在哪个节点上。
</p>
<p>
    请编写一个程序去实现以上要求。
</p>
<p>
数据范围：<span style="line-height:1.5;">     2&lt;=D&lt;=20, and 1&lt;=I&lt;=524288</span> 
</p>
<p>
<br/>
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
包含L+2行：
</p>
<p>
第1行：N，表示共有N组数据。(n&lt;=1000)
</p>
<p>
第2行到第L+1行，每行2个正整数，即
</p>
<p>
D1 I1
</p>
<p>
……….
</p>
<p>
Dk Ik
</p>
<p>
……….
</p>
<p>
Dl Il
</p>
<p>
第L+2行：-1（表示输入文件结束）
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
包含L行，每行一个数据，即第I个小球将落在第几个节点上。
</p>
<h3>
【样例输入】
</h3>
<pre>5
4 2
3 4
10 1
2 2
8 128
-1

</pre>
<h3>
【样例输出】
</h3>
<pre>12
7
512
3
255
 
</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
uva679
</p>
