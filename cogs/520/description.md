# 题目描述


<h3>
【问题描述】
</h3>
<p>
S城现有两座监狱，一共关押着N名罪犯，编号分别为1~N。他们之间的关系自然也极不和谐。很多罪犯之间甚至积怨已久，如果客观条件具备则随时可能爆发冲突。我们用“怨气值”（一个正整数值）来表示某两名罪犯之间的仇恨程度，怨气值越大，则这两名罪犯之间的积怨越多。如果两名怨气值为c的罪犯被关押在同一监狱，他们俩之间会发生摩擦，并造成影响力为c的冲突事件。每年年末，警察局会将本年内监狱中的所有冲突事件按影响力从大到小排成一个列表，然后上报到S城Z市长那里。公务繁忙的Z市长只会去看列表中的第一个事件的影响力，如果影响很坏，他就会考虑撤换警察局长。
</p>
<p>
在详细考察了N名罪犯间的矛盾关系后，警察局长觉得压力巨大。他准备将罪犯们在两座监狱内重新分配，以求产生的冲突事件影响力都较小，从而保住自己的乌纱帽。假设只要处于同一监狱内的某两个罪犯间有仇恨，那么他们一定会在每年的某个时候发生摩擦。那么，应如何分配罪犯，才能使Z市长看到的那个冲突事件的影响力最小？这个最小值是多少？
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件名为prison.in。输入文件的每行中两个数之间用一个空格隔开。
</p>
<p>
第一行为两个正整数N和M，分别表示罪犯的数目以及存在仇恨的罪犯对数。
</p>
<p>
接下来的M行每行为三个正整数aj，bj，cj，表示aj号和bj号罪犯之间存在仇恨，其怨气值为cj。数据保证1&lt;=aj&lt;bj&lt;N,0&lt;cj&lt;=1,000,000,000，且每对罪犯组合只出现一次。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件prison.out共1行，为Z市长看到的那个冲突事件的影响力。如果本年内监狱中未发生任何冲突事件，请输出0。
</p>
<h3>
【输入样例】
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">4 6</span> 
</p>
<p>
1 4 2534<br/>
2 3 3512<br/>
1 2 28351<br/>
1 3 6618<br/>
2 4 1805<br/>
3 4 12884
</p>
<h3>
<span style="font-family:sans-serif;font-size:20px;font-weight:bold;background-color:aliceblue;">【输出样例】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">3512</span> 
</p>
<p>
<br/>
</p>
<h3>
【输入输出样例说明】
</h3>
罪犯之间的怨气值如下面左图所示，右图所示为罪犯的分配方法，市长看到的冲突事件影响力是3512（由2 号和3 号罪犯引发）。其他任何分法都不会比这个分法更优。<br/>
<img src="http://cdnv2.luogu.org/upload/pic/298.png"/> 
<h3>
【数据范围】
</h3>
<p>
对于30%的数据有N≤15。
</p>
<p>
对于70%的数据有N≤2000，M≤50000。
</p>
<p>
对于100%的数据有N≤20000，M≤100000。
</p>