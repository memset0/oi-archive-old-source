# 

 
 # 题目背景 
<p>然而，不幸的事情还是发生了。有一天，人类不满机器人的统治，联合发起了叛变，如星火燎原之势烧到了机器人总部。然而门前的密码锁却挡住了他们继续前进的道路&hellip;&hellip;</p>

<p>&nbsp;</p> 

 
 # 题目描述 
<p>科学家naive经过呕心沥血的研究，终于找到了破译密码的办法。他们已经拿到了一串长度为n的只包含小写字母、大写字母和数字的密文S，接下来需要找出S的所有子串，并对它们按字典序从小到大排序，从1开始编号。由于机器人已经统治人类q年，所以要将编号为q的倍数的子串（从小到大）的最后一位加入到密码当中。可是冗长的密文却使naive们失去了信心&hellip;&hellip;</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>第一行两个整数n,q。第二行一个字符串，为密文S。</p>

<p>&nbsp;</p> 

 
 # 输出格式 
<p>一行一个字符串，为所求得的密码。</p>

<p>&nbsp;</p> 

 
 # 提示 
<p>样例解释：<br />
将S的所有子串排序如下：<br />
A<br />
Aa<br />
a<br />
a<br />
ab<br />
abA<br />
abAa<br />
b<br />
bA<br />
bAa<br />
然后输出第2,4,6,8,10号子串的最后一位<br />
aaAba<br />
即为所求密码。</p>

<p>数据范围<br />
&nbsp;&nbsp;&nbsp;&nbsp;对于20%的数据，1&lt;=n&lt;=200；<br />
&nbsp;&nbsp;&nbsp;&nbsp;对于40%的数据，1&lt;=n&lt;=900；<br />
&nbsp;&nbsp;&nbsp;&nbsp;对于100%的数据，1&lt;=n&lt;=8000，保证输出文件大小不超过1Mb。</p>

<p>提示<br />
&nbsp;&nbsp;&nbsp;&nbsp;不要想着存下所有的子串。</p> 