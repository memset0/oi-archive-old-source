# 题目描述


<p>
	<strong>【问题描述】 </strong>
</p>
<p>
	    一个潜水员在潜水时使用一种特殊的装置：一个有两个容器的气筒。一个容器中装的是氧气，另一个容器中装氮气。潜水员需要携带的氧气和氮气量依赖于潜水的时间和深度。潜水员有一系列的气筒，用来在不同的情况下携带。每个气筒可以用这样几个量来描述：气筒的质量，气筒中所能容纳的氧气量，以及可以容纳的氮气量。为了能完成最近的一个任务，潜水员需要一定量的氧气和氮气。潜水员有一系列准备好的气筒。他希望能携带总质量尽可能小的气筒下水。现在请你帮他计算一下至少要携带多少质量的气筒下水才能完成这个任务。
</p>
<p>
	<strong>【</strong><strong>示例说明</strong><strong>】</strong>
</p>
<p>
	    潜水员有以下 5 个气筒。每个气筒用三个整数来描述：气筒所能容纳的氧气的量，氮气的量和气筒的质量：
</p>
<p>
	3 36 120 <br/>
10 25 129 <br/>
5 50 250 <br/>
1 45 130 <br/>
4 20 119
</p>
<p>
	    如果这次任务中潜水员需要携带 5 升 氧气， 60 升 氮气。那么他至少要携带总质量为 249 的气筒下水（样例中的第一个和第二个气筒或者第四个和第五个气筒）。
</p>
<p>
	<strong>【</strong><strong>任务</strong><strong>】</strong>
</p>
<p>
	写一个程序：
</p>
<p>
	•  从输入文件中读入完成任务所需要的氧气和氮气量以及气筒的个数和对每个气筒的描述。
</p>
<p>
	•  计算潜水员完成任务至少需要携带的多少质量的气筒。
</p>
<p>
	•  将结果写入输出文件中。
</p>
<p>
	注意：题目中给出的气筒总是能够容纳足够多的气体使得潜水员能完成任务。
</p>
<p>
	<strong>【</strong><strong>输入格式</strong><strong>】</strong>
</p>
<p>
	    在文件的第一行中有两个整数 t 和 a ，分别描述完成任务所需的氧气和氮气量。（ 1 ≤ t ≤ 21 ， 1 ≤ a ≤ 79 ）。第二行中有一个整数 n ，表示气筒的个数。（ 1 ≤ n ≤ 1000 ）。以后 n 行中，每行有三个整数 t i ， a i ， w i ， t i 表示第 i 个气筒所能容纳的氧气量， a i 表示第 i 个气筒所能容纳的氮气量， w i 表示气筒 i 的质量。（ 1 ≤ a i ≤ 21 ， 1 ≤ t i ≤ 79 ， 1 ≤ w i ≤ 800 ）。
</p>
<p>
	<strong>【</strong><strong>输出格式</strong><strong>】</strong>
</p>
<p>
	    输出文件只有一行，这行中包含一个整数，表示最少需要携带的多少质量的气筒来完成改任务）。
</p>
<p>
	<strong>【</strong><strong>样例输入</strong><strong>】</strong>
</p>
<p>
	<strong>ple.in</strong>
</p>
<p>
	5 60 <br/>
5 <br/>
3 36 120 <br/>
10 25 129 <br/>
5 50 250 <br/>
1 45 130 <br/>
4 20 119
</p>
<p>
	<strong>【</strong><strong>样例输出</strong><strong>】</strong>
</p>
<p>
	<strong>ple.out</strong>
</p>
<p>
	249
</p>