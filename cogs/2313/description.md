# 题目描述


<p>
<br/>
</p>
<p>
【题目描述】
</p>
<p>
给定一棵有根树，树根为1
</p>
<p>
每个点有颜色ci
</p>
<p>
给定k个询问A,B，询问有多少个点对(x,y)满足cx=A，cy=B，且x是y的祖先
</p>
<p>
数据保证A不等于B
</p>
<p>
<br/>
</p>
<p>
【输入格式】
</p>
<p>
第一行输入n，m，k表示节点总数，颜色总数和询问次数
</p>
<p>
之后第一行输入树根的颜色
</p>
<p>
以下从第二行到第n行，每行输入当前节点的父亲和当前节点的颜色(感觉不用再解释了QAQ)
</p>
<p>
之后k行，每行两个数A，B描述一个询问
</p>
<p>
n，k&lt;=200000,m&lt;=25000
</p>
<p>
<br/>
</p>
<p>
【输出格式】
</p>
<p>
对于每个询问输出正确的答案
</p>
<p>
<br/>
</p>
<p>
【样例输入】
</p>
<p>
6 3 4
</p>
<p>
1
</p>
<p>
1 2
</p>
<p>
1 3
</p>
<p>
2 3
</p>
<p>
2 3
</p>
<p>
5 1
</p>
<p>
1 2
</p>
<p>
1 3
</p>
<p>
2 3
</p>
<p>
3 1
</p>
<p>
【样例输出】
</p>
<p>
1
</p>
<p>
3
</p>
<p>
2
</p>
<p>
1
</p>
<p>
来源：IOI 
</p>
<p>
BZOJ 3351
</p>
<p>
<br/>
</p>