
# Content

# 第一章：小试牛刀

天地苍茫、风云际会。代码大陆已经有很长、很长的时间没有出现一个堪当大任的新人了。大陆上的码农们不思进取，只想守着自己的一亩三分地。偶有几个叛逆之人，也常因为力量不足而被扼杀在摇篮里。久而久之，人们都被局限在调库、调参中。而造出轮子的大神则一直把持高位，算法的秘密只会传给自己的亲传弟子。之所谓强者愈强，弱者愈弱。直到有一天，一个闪耀的新星在遥远的东方，那还没有被完全控制的地方，诞生了。

「滚滚长江东逝水，浪花淘尽英雄。千古几人可穷算法？尔等于此不知天高地厚，还不快滚回家，免得贻笑大方。” 台阶上，一名中年男子呵斥道。而台阶下是一个粉毛少女，黛眉微蹙：“你不试试怎么知道我不行？」

「呵呵，我还不知道你们这些人的本事？靠自己悟来的算法能顶甚么用？瞧你年纪轻轻，不赶快去学怎么调库，真以为自己能学得懂高深莫测的算法？」

「那我倒要问问你这个尸位素餐的家伙，空有一个位置，你又会什么东西？年轻时曾在代码力量黄榜上待了一会，就真以为自己配靠这个吃一辈子？」少女貌似对中年男人分外了解。

「黄毛小儿，今天我 ZXyang 就要教训教训你。码环，开！” 话音刚落，一道乳白色的光自天上照来，包裹着中年男子。“我虽许久未训练，但一身功夫仍在。你可知当年我最擅长的领域，可是传说中的字符串！今日我便教教你，为何自己想的算法不如我这种亲传之人。」 中年男子双手一挥，白光骤然开始旋转。光内开始出现了一些奇怪的字符。字符的数量越来越多，从一两个，堆积到了几十，然后上百。最后，光内竟然有上万的字符。倘若普通码农，看到这惊人的字符量，想必已经吓得战战兢兢、不敢动弹了吧。然而，粉毛少女丝毫不为之动摇，甚至嘴角划出一丝淡淡的微笑。

「你笑什么？我对字符串匹配问题深有研究，今日的我早已经在单串匹配问题上达到大成之境。字符串匹配的最快算法，毫无疑问的就是 $O(n^2)$ 的暴力匹配算法。现在的我使用这个算法，可以在 1 秒之内处理上万的字符。不会你真以为自创的算法有可能超越我吧？」 中年男子虽然仍然声色凌厉，但可以看出来，他的神情之间已经透露着些许慌乱。

「我笑你虽年纪大我一截，悟性竟然如此之差，竟然还在用暴力匹配来解决单串匹配问题。就你这样的水平，在我的前缀函数法面前，就像是一个想和举重冠军比摔跤的三岁小儿。」粉发少女自信地说。

「(ˉ▽￣～) 切~~，我还以为你自创的算法真的能打破暴力算法的瓶颈，看来你还是太年轻啊。我早就领悟过前缀函数法了。这么一个 $O(n^3)$ 的垃圾算法，怎么可能打败我的暴力匹配？」 中年男子笑着说。

「唉，和你们这种老顽固真是没话说，」 粉发少女笑了笑，「码环，起！」

刹那间，粉发少女周身飞速出现字符，这些字符晶莹剔透、一尘不染，已然不是凡物。而真正令 ZXyang 惊奇的，是字符的数量。

「千、万、十万、百万！你是怎么在这么短的时间内聚集这么大的数据的？」

「老顽固，这还只是我 0.1 秒内处理的数据量！现在，让我来教训教训你！」

----

给出两个不含空格的字符串 $a$ , $b$ 。
输出 $b$ 串在 $a$ 串中所有出现位置。

请尽量使用 KMP 算法，因为 Sugar 想用 KMP 算法暴打 ZXyang
![OIP.jpg](/source/lutece/di-yi-zhang-xiao-shi-niu-dao/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMDMvazlSZWp1VEJVU0RJVkhHLmpwZw==.jpg)

# Standard Input

第一行一个字符串 $a$。
第二行一个字符串 $b$。

# Standard Output

一行输出所有匹配位置。(下标从 1 开始，输出左端点)

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1211122122
12</td><td>1 5 8</td></tr><tr><td>Sugar!!!!
uga</td><td>2</td></tr></table>


# Constraints

$1\leq |a| , |b| \leq 10^6$
字符集为 ASCII 编码中的非控制字符。

# Note



# Source

