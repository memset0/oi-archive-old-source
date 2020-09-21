<div id="pcont1" style="margin-top:20px; display:block;">

# 问题描述

<div class="pdcont">　　有一位使者要游历各国，他每到一个国家，都能学到一种文化，但他不愿意学习任何一种文化超过一次（即如果他学习了某种文化，则他就不能到达其他有这种文化的国家）。不同的国家可能有相同的文化。不同文化的国家对其他文化的看法不同，有些文化会排斥外来文化（即如果他学习了某种文化，则他不能到达排斥这种文化的其他国家）。<br/>
　　现给定各个国家间的地理关系，各个国家的文化，每种文化对其他文化的看法，以及这位使者游历的起点和终点（在起点和终点也会学习当地的文化），国家间的道路距离，试求从起点到终点最少需走多少路。</div>
# 输入格式

<div class="pdcont">　　第一行为五个整数N，K，M，S，T，每两个整数之间用一个空格隔开，依次代表国家个数（国家编号为1到N），文化种数（文化编号为1到K），道路的条数，以及起点和终点的编号（保证S不等于T）；<br/>
　　第二行为N个整数，每两个整数之间用一个空格隔开，其中第i个数C<sub>i</sub>，表示国家i的文化为C<sub>i</sub>。<br/>
　　接下来的K行，每行K个整数，每两个整数之间用一个空格隔开，记第i行的第j个数为a<sub>ij</sub>，a<sub>ij</sub>= 1表示文化i排斥外来文化j（i等于j时表示排斥相同文化的外来人），a<sub>ij</sub>= 0表示不排斥（注意i排斥j并不保证j一定也排斥i）。<br/>
　　接下来的M行，每行三个整数u，v，d，每两个整数之间用一个空格隔开，表示国家u与国家v有一条距离为d的可双向通行的道路（保证u不等于v，两个国家之间可能有多条道路）。</div>
# 输出格式

<div class="pdcont">　　输出只有一行，一个整数，表示使者从起点国家到达终点国家最少需要走的距离数（如果无解则输出-1）。</div>
# 样例输入

<div class="pddata">2 2 1 1 2<br/>
1 2<br/>
0 1<br/>
1 0<br/>
1 2 10</div>
# 样例输出

<div class="pddata">-1</div>
# 输入输出样例说明

<div class="pdcont">　　由于到国家2必须要经过国家1，而国家2的文明却排斥国家1的文明，所以不可能到达国家2。</div>
# 样例输入

<div class="pddata">2 2 1 1 2<br/>
1 2<br/>
0 1<br/>
0 0<br/>
1 2 10</div>
# 样例输出

<div class="pddata">10</div>
# 输入输出样例说明

<div class="pdcont">　　路线为1 -&gt; 2。</div>
# 数据规模和约定

<div class="pdcont">　　对于20%的数据，有2≤N≤8，K≤5；<br/>
　　对于30%的数据，有2≤N≤10，K≤5；<br/>
　　对于50%的数据，有2≤N≤20，K≤8；<br/>
　　对于70%的数据，有2≤N≤100，K≤10；<br/>
　　对于100%的数据，有2≤N≤100，1≤K≤100，1≤M≤                                                  N^2，1≤k<sub>i</sub>≤K，1≤u, v≤N，1≤d≤1000，S≠T，1 ≤S, T≤N。</div>

</div>