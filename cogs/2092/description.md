# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
从“蓝翔”号向太空看去，星星开始眨眼。
</p>
<p>
但Asm.Def很快意识到那些不是星星。每次闪光都意味着一个目标在虚空中化作一团火球。
</p>
<p>
三分钟后，闪光停了下来。
</p>
<p>
“搞定了。”杜舰长兴奋地说，“但我们的一些通信卫星被碎片打坏了。”
</p>
<p>
“没事，一部分卫星也能凑合着用，但是得满足条件。”
</p>
<p>
“什么条件？”
</p>
<p>
“我懂，让我做一点微小的贡献。”Asm.Def推开舰长，开始操作。
</p>
<p>
<img src="/upload/image/20151104/20151104060605_97005.png" alt=""/> 
</p>
<p>
Asm.Def需要从剩下的N颗卫星中选出一部分，组成通信网络。第i颗卫星有一个识别码A[i]，要求他选出的所有卫星识别码的xor（按位异或，即C++中的’^’运算符）值为零，这样才能正常运作。
</p>
<p>
Asm.Def需要找出一组解。如果有多组，输出任意一组。
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
第一行一个整数N。
</p>
<p>
接下来一行N个整数，为A[1]~A[N]，代表1~N号卫星的识别码。
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
第1行：一个整数k&gt;0，代表选出了k颗卫星。
</p>
<p>
第2行：k个互不相等，在1~N之间的整数，代表选出的卫星编号。要求这些卫星识别码的xor为零。数据保证存在至少一组解。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
10
23 17 19 10 21 3 15 26 10 14
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
4
1 2 3 5
</p>
</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
23 xor 17 xor 19 xor 21 = 0
</p>
<p>
对于10%的数据，N&lt;=5，A[i]=1.
</p>
<p>
对于40%的数据，N&lt;=20.
</p>
<p>
对于70%的数据，N&lt;=60.
</p>
<p>
对于100%的数据，N&lt;=1000，1&lt;=A[i]&lt;2^60。
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
“Asm.Def战记之拉格朗日点”杯
</p>