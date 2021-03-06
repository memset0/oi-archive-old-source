# 题目描述


<p>
【问题描述】
</p>
<p>
CE数码公司开发了一种名为自动涂色机（APM）的产品。它能用预定的颜色给一块由不同尺寸且互不覆盖的矩形构成的平板涂色。
</p>
<p>
<img src="/upload/image/20121023/20121023091426_60139.png" width="400" height="273" alt=""/> 
</p>
<p>
    为了涂色，APM需要使用一组刷子。每个刷子涂一种不同的颜色C。APM拿起一把有颜色C的刷子，并给所有颜色为C且符合下面限制的矩形涂色：
</p>
<p>
    为了避免颜料渗漏使颜色混合，一个矩形只能在所有紧靠它上方的矩形涂色后，才能涂色。例如图中矩形F必须在C和D涂色后才能涂色。注意，每一个矩形必须立刻涂满，不能只涂一部分。
</p>
<p>
    写一个程序求一个使APM拿起刷子次数最少的涂色方案。注意，如果一把刷子被拿起超过一次，则每一次都必须记入总数中。
</p>
<p>
【输入】
</p>
<p>
文件paint.in第一行为矩形的个数N。下面有N行描述了N个矩形。每个矩形有5个整数描述，左上角的y坐标和x坐标，右下角的y坐标和x坐标，以及预定颜色。
</p>
<p>
颜色号为1到20的整数。
</p>
<p>
平板的左上角坐标总是(0, 0)。
</p>
<p>
坐标的范围是0..99。
</p>
<p>
N小于16。
</p>
<p>
【输出】
</p>
<p>
输出至文件paint.out，文件中记录拿起刷子的最少次数。
</p>
<p>
【样例】
</p>
<p>
paint.in
</p>
<p>
7
</p>
<p>
0 0 2 2 1
</p>
<p>
0 2 1 6 2
</p>
<p>
2 0 4 2 1
</p>
<p>
1 2 4 4 2
</p>
<p>
1 4 3 6 1
</p>
<p>
4 0 6 4 1
</p>
<p>
3 4 6 6 2
</p>
<p>
paint.out
</p>
<p>
3
</p>
<p>
<br/>
</p>
