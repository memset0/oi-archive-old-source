# 题目描述


<h3>
【问题描述】
</h3>
<p>
Hanks 博士是BT (Bio-Tech，生物技术) 领域的知名专家。现在，他正在为一个细胞实验做准备工作：培养细胞样本。 
</p>
<p>
Hanks 博士手里现在有N 种细胞，编号从1~N，一个第i 种细胞经过1 秒钟可以分裂为S<sub>i</sub> 个同种细胞（S<sub>i</sub> 为正整数）。现在他需要选取某种细胞的一个放进培养皿，让其自由分裂，进行培养。一段时间以后，再把培养皿中的所有细胞平均分入M 个试管，形成M 份样本，用于实验。Hanks 博士的试管数M 很大，普通的计算机的基本数据类型无法存储这样大的 M 值，但万幸的是，M 总可以表示为m<sub>1</sub> 的m<sub>2</sub> 次方，即 M = m1<sup>m2</sup> ，其中m<sub>1</sub>，m<sub>2</sub> 均为基本数据类型可以存储的正整数。
</p>
<p>
注意，整个实验过程中不允许分割单个细胞，比如某个时刻若培养皿中有4 个细胞，Hanks 博士可以把它们分入2 个试管，每试管内2 个，然后开始实验。但如果培养皿中有5个细胞，博士就无法将它们均分入2 个试管。此时，博士就只能等待一段时间，让细胞们继续分裂，使得其个数可以均分，或是干脆改换另一种细胞培养。
</p>
<p>
为了能让实验尽早开始，Hanks 博士在选定一种细胞开始培养后，总是在得到的细胞“刚好可以平均分入M 个试管”时停止细胞培养并开始实验。现在博士希望知道，选择哪种细胞培养，可以使得实验的开始时间最早。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件名为 cell.in，共有三行。
第一行有一个正整数 N，代表细胞种数。
第二行有两个正整数 m<sub>1</sub>，m<sub>2</sub>，以一个空格隔开，m1<sup>m2</sup> 即表示试管的总数M。
第三行有 N 个正整数，第i 个数Si 表示第i 种细胞经过1 秒钟可以分裂成同种细胞的个数。
</p>
<h3>
【输出格式】
</h3>
<p>
输出文件 cell.out 共一行，为一个整数，表示从开始培养细胞到实验能够开始所经过的最少时间（单位为秒）。如果无论 Hanks 博士选择哪种细胞都不能满足要求，则输出整数-1。
</p>
<h3>
【样例输入1】
</h3>
<pre>1
2 1
3
</pre>
<h3>
【样例输出1】
</h3>
<pre>-1
</pre>
<h3>
【样例说明1】
</h3>
<p>
经过 1 秒钟，细胞分裂成3 个，经过2 秒钟，细胞分裂成9 个，……，可以看出无论怎么分裂，细胞的个数都是奇数，因此永远不能分入 2 个试管。
</p>
<h3>
【样例输入2】
</h3>
<pre>2
24 1
30 12
</pre>
<h3>
【样例输出2】
</h3>
<pre>2
</pre>
<h3>
【样例说明2】
</h3>
<p>
第 1 种细胞最早在3 秒后才能均分入24 个试管，而第2 种最早在2 秒后就可以均分（每试管144/(241)=6 个）。故实验最早可以在2 秒后开始。
</p>
<h3>
【数据范围】
</h3>
<p>
对于 50%的数据，有m1<sup>m2</sup> ≤ 30000。
对于所有的数据，有1 ≤N≤ 10000，1 ≤m<sub>1</sub> ≤ 30000，1 ≤m<sub>2</sub> ≤ 10000，1 ≤ S<sub>i</sub> ≤ 2,000,000,000。
</p>