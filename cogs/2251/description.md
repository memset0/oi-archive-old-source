# 题目描述


<h3>
【题目描述】
</h3>
<p>
CC开演唱会，除了伙同主持人插浑打科，整场就只唱了三首歌，其中有两首话筒都拿反了！观众们怒不可遏，一致要求退票。
</p>
<p>
现在有n个人要求退票，而CC需要退掉m张票。为了方便，CC会念出一个字符串，一旦某个人被点到名字，就会到CC那里退掉一张票。这可能会导致某个人被退掉多张票，或者某个人没有被退票，这都没关系，CC只关心最终退票的数量，只要最终有m张票被退掉，就算完成要求。
</p>
<p>
由于CC比较懒，他希望念出的字符串长度最短，因此他想让你编一个程序，判断至少需要念出多长的字符串。
</p>
<p>
注意：每个人的名字都是由小写字母组成。由于来退票的人都很特立独行，因些不会存在一个人的名字是另一个人的名字的子串的情况。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行有两个整数n和m，分别代表退票的人数和退票的张数。
</p>
<p>
接下来n行，每行一个字符串，代表这n个人的名字。
</p>
<p>
数据保证所有人的名字长度之和不会超过10^5。
</p>
<h3>
【输出格式】
</h3>
<p>
一行，一个整数，代表CC至少要念出多长的字符串。
</p>
<h3>
【样例输入】
</h3>
<p>
4 5
</p>
<p>
monika
</p>
<p>
tomek
</p>
<p>
szymon
</p>
<p>
bernard
</p>
<h3>
【样例输出】
</h3>
<p>
23
</p>
<h3>
【提示】
</h3>
<p>
样例解释：
CC只需念出“szymonikaszymonikatomek”即可。
</p>
<p>
数据规模：
</p>
<p>
<img src="/upload/image/20160419/20160419111032_16333.jpg" alt="" height="267" width="403"/> 
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>