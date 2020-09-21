# 题目描述


<p>
	山峰和山谷（grz）<br/>
Description<br/>
 Byteasar特别喜欢爬山，在爬山的时候他就在研究山峰和山谷。为了能够让他对他的旅程有一个安排，他想知道山峰和山谷的数量。<br/>
 给定一个地图，为Byteasar想要旅行的区域，地图被分为n*n的网格，每个格子(i,j) 的高度w(i,j)是给定的。<br/>
 若两个格子有公共顶点，那么他们就是相邻的格子。（所以与(i,j)相邻的格子有(i−1, j−1),(i−1,j),(i−1,j+1),(i,j−1),(i,j+1),(i+1,j−1),(i+1,j),(i+1,j+1)）。<br/>
 我们定义一个格子的集合S为山峰（山谷）当且仅当：<br/>
1.S的所有格子都有相同的高度。<br/>
2.S的所有格子都联通<br/>
3.对于s属于S，与s相邻的s’不属于S。都有ws&gt;ws’（山峰），或者ws&lt;ws’（山谷）。 <br/>
你的任务是，对于给定的地图，求出山峰和山谷的数量，如果所有格子都有相同的高度，那么整个地图即是山峰，又是山谷。<br/>
Input Format (grz.in)<br/>
 输入文件grz.in第一行包含一个正整数n，表示地图的大小（1&lt;=n&lt;=1000）。接下来一个n*n的矩阵，表示地图上每个格子的高度。(0&lt;=w&lt;=1000000000)<br/>
Output Format (grz.out)<br/>
 输出文件grz.out应包含两个数，分别表示山峰和山谷的数量。<br/>
Sample Input 1<br/>
5<br/>
8 8 8 7 7<br/>
7 7 8 8 7<br/>
7 7 7 7 7<br/>
7 8 8 7 8<br/>
7 8 8 8 8<br/>
Sample Output 2<br/>
2 1<br/>
Sample Input 2<br/>
5<br/>
5 7 8 3 1<br/>
5 5 7 6 6<br/>
6 6 6 2 8<br/>
5 7 2 5 8<br/>
7 1 0 1 7<br/>
Sample Output 2<br/>
3 3</p>