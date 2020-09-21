# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
满汉全席是中国最丰盛的宴客菜肴，有许多种不同的材料透过满族或是汉族的料理方式，呈现在數量繁多的菜色之中。由于菜色众多而繁杂，只有极少數博学多闻技艺高超的厨师能够做出满汉全席，而能够烹饪出经过专家认证的满汉全席，也是中国厨师最大的荣誉之一。世界满汉全席协会是由能够料理满汉全席的专家厨师们所组成，而他们之间还细分为许多不同等级的厨师。
</p>
<p>
为了招收新进的厨师进入世界满汉全席协会，将于近日举办满汉全席大赛，协会派遣许多会员当作评审员，为的就是要在參赛的厨师之中，找到满汉料理界的明日之星。
</p>
<p>
大会的规则如下：每位參赛的选手可以得到n 种材料，选手可以自由选择用满式或是汉式料理将材料当成菜肴。
</p>
<p>
大会的评审制度是：共有m 位评审员分别把关。每一位评审员对于满汉全席有各自独特的見解，但基本见解是，要有兩样菜色作为满汉全席的标志。如某评审认为，如果没有汉式东坡肉跟满式的涮羊肉锅，就不能算是满汉全席。但避免过于有主見的审核，大会规定一个评审员除非是在认为必备的两样菜色都没有做出來的狀况下，才能淘汰一位选手，否则不能淘汰一位參赛者。
</p>
<p>
换句话說，只要參赛者能在这兩种材料的做法中，其中一个符合评审的喜好即可通过该评审的审查。如材料有猪肉，羊肉和牛肉时，有四位评审员的喜好如下表：
</p>
<p>
评审一 评审二 评审三 评审四
</p>
<p>
满式牛肉 满式猪肉 汉式牛肉 汉式牛肉
</p>
<p>
汉式猪肉 满式羊肉 汉式猪肉 满式羊肉
</p>
<p>
<br/>
</p>
<p>
如參赛者甲做出满式猪肉，满式羊肉和满式牛肉料理，他将无法满足评审三的要求，无法通过评审。而參赛者乙做出汉式猪肉，满式羊肉和满式牛肉料理，就可以满足所有评审的要求。
</p>
<p>
但大会后來发现，在这样的制度下如果材料选择跟派出的评审员没有特别安排好的话，所有的參赛者最多只能通过部分评审员的审查而不是全部，所以可能会发生没有人通过考核的情形。
</p>
<p>
如有四个评审员喜好如下表时，则不论参赛者采取什么样的做法，都不可能通过所有评审的考核：
</p>
<p>
评审一 评审二 评审三 评审四
</p>
<p>
满式羊肉 满式猪肉 汉式羊肉 汉式羊肉
</p>
<p>
汉式猪肉 满式羊肉 汉式猪肉 满式猪肉
</p>
<p>
<br/>
</p>
<p>
所以大会希望有人能写一个程序來判断，所选出的m 位评审，会不会发生 没有人能通过考核的窘境，以便协会组织合适的评审团。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行包含一个数字 K，代表测试文件包含了K 组资料。
</p>
<p>
每一组测试资料的第一行包含兩个数字n 跟m（n≤100，m≤1000），代表有n 种材料，m 位评审员。
</p>
<p>
为方便起見，材料舍弃中文名称而给予编号，编号分别从1 到n。
</p>
<p>
接下來的m 行，每行都代表对应的评审员所拥有的兩个喜好，每个喜好由一个英文字母跟一个数字代表，如m1 代表这个评审喜欢第1 个材料透过满式料理做出來的菜，而h2 代表这个评审员喜欢第2 个材料透过汉式料理做出來的菜。
</p>
<p>
每个测试文件不会有超过100 组测试资料
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
每笔测试资料输出一行，如果不会发生没有人能通过考核的窘境，输出GOOD；否则输出BAD（大写字母）。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
2
3 4
m3 h1
m1 m2
h1 h3
h3 m2
2 4
h1 m2
m2 m1
h1 h2
m1 h2
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
GOOD
BAD
</p>
</pre>
<h3>
【提示】
</h3>
<p>
数据为林荫手造，有官方数据敬请覆盖
</p>
<h3>
【来源】
</h3>
<p>
JSOI2010
</p>