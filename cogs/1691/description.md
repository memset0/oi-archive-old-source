# 题目描述


<h3>
【题目描述】
</h3>
<p>
Kaykobad教授把为ACM选手买饭的任务交给了Nasa。Nasa决定买n种不同的食物。然后他询问了m名选手对每种食物的需求量。选手们当然不会给出任何符合逻辑的回答，他们只是想尽可能的多吃！Nasa很清楚，如果他们得到了想要的分量，他们就只会浪费粮食。Nasa决定不让这件事发生。
</p>
<p>
因此他机智的算出了对于每名选手吃一份每种食物能获得多少“满意值”。某人吃一份某种事物的满意值可能是零。如果每个人得到的总满意值超过上限，他就会浪费粮食。Nasa决定不让任何人得到的满意值超过该人的满意值上限。他计划，就算给某个人分数份食物，也不能让任何人的总满意值超过上限！
</p>
<p>
Nasa还决定给所有人买完全相同的套餐，这样就不会有人抱怨不公平。
</p>
<p>
在满足这些条件后，他最终意识到他的钱是无限的（反正可以找学校报销），因此他将会花尽可能多的钱。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行有两个整数n，m（3&lt;=n,m&lt;=20），代表食物种类和人数。
</p>
<p>
第二行有n个实数，代表每种食物的单价。
</p>
<p>
接下来的m行每行描述一名选手：
</p>
<p>
这一行有个n+1个实数。前n个实数是他吃一份每种食物得到的满意值，第n+1个实数是他的满意值上限。
</p>
<h3>
【输出格式】
</h3>
<p>
按格式输出Nasa最多能花多少钱，向上取整。你可以假设不会有舍入误差问题。具体格式见样例。
</p>
<h3>
【样例输入】
</h3>
<p>
3 3
</p>
<p>
1 0.67 1.67
</p>
<p>
1 2 1 430
</p>
<p>
3 0 2 460
</p>
<p>
1 4 0 420
</p>
<h3>
【样例输出】
</h3>
<p>
Nasa can spend 1354 taka.
</p>
<h3>
【提示】
</h3>
<p>
taka是孟加拉国的货币单位。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;page=show_problem&amp;problem=1439" target="_blank">Uva 10498 Happiness</a> 
</p>
<p>
Problemsetter: Mustaq Ahmed, University of Waterloo
</p>