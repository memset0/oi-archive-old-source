# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
七十君最近爱上了排序算法，于是Ta让十七君给Ta讲冒泡排序。
</p>
<p>
十七君给七十君讲完了冒泡排序以后，七十君回家苦思冥想，又创造了一种名
</p>
<p>
为七十排序的算法。下面是这个算法排序一个排列的过程：
</p>
<p>
首先从左到右扫描每个相邻数对。如果这两个数是逆序的，则将第二个数(也
</p>
<p>
就是小的数)放在整个排列的开头，其他数位置不变，并把计数器加一。如果
</p>
<p>
没有逆序的相邻数对了，就说明已经排好序了，算法终止。
</p>
<p>
七十君认为计数器的值反映了这个算法的运行时间。但十七君觉得七十君发明
</p>
<p>
的这个算法会很慢，所以他请你帮忙算算，对于所有长度为n的排列P，
</p>
<p>
 <img src="/upload/image/20151019/20151019193837_27666.jpg" alt=""/>  
</p>
<p>
的值，这里f(P)表示排列P运行算法结束时计数器的值。
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
一行一个整数n。
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
如果E(n)=a/b，求c使得
</p>
<p>
   bc 三 a  (mod 10^9+7)
</p>
<p>
并输出，其中0≤c&lt;10^9+7，如果e不存在输出-1。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre>4</pre>
<h3>
【样例输出】
</h3>
<pre>250000005</pre>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
对于排列4 1 3 2，算法结束时计数器的值为5。
</p>
<p>
4 1 3 2，4和1形成逆序，将1放到排列最前方。
</p>
<p>
1 4 3 2，4和3形成逆序，将3放到排列最前方。
</p>
<p>
3 1 4 2，3和1形成逆序，将1放到排列最前方。
</p>
<p>
1 3 4 2，4和2形成逆序，将2放到排列最前方。
</p>
<p>
2 1 3 4，2和1形成逆序，将1放到排列最前方。
</p>
<p>
1 2 3 4，现在排列已经排序完毕。
</p>
<p>
E(4)=3.25。
</p>
<p>
<br/>
</p>
<p>
 数据范围与约定
</p>
<p>
对于20％的数据，n≤8。
</p>
<p>
对于40％的数据，n≤30。
</p>
<p>
对于60％的数据，n≤200。
</p>
<p>
对于1OO％的数据，n≤10^5。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>