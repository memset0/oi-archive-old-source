# 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;童年的我们，充满了新奇的想法。这天，小朋友们用彩虹画笔在云霞上绘制了世界上最美丽的图画。那描绘的是一条大河波浪宽，风吹稻花香两岸的情景。欣赏着自己的作品，小朋友们别提多开心了。这时，Q小朋友对C小朋友说：你看，河面上那一弯弯船儿，多漂亮啊！可是，这么多船儿，哪一只最大呢？<br />
&nbsp;&nbsp;&nbsp;&nbsp;C小朋友最在意他在Q小朋友心目中的形象了，当然想完美地回答这个问题了。你能帮帮他么？<br />
&nbsp;&nbsp;&nbsp;&nbsp;船的定义为：中间是长宽比例为1：2的矩形，两头是两个等腰直角三角形的等腰梯形。注意：必须保证在船所占据的矩形中除了船的图形外都是空白，见样例。</p> 

 
 # 输入格式 
<p>第一行两个数n、m,表示云霞的长宽<br />
以下n行，每行m个字母，表示图案。0表示空白，1表示有图案。</p> 

 
 # 输出格式 
<p>第一行两个数x、y，表示找到的最大的船的左上角的坐标。<br />
以下若干行若干列，为找到的图形。<br />
注意：在（9，22）点起始的图形是合法的最小的船。如果不存在船，输出：&#39;Oh,my&nbsp;god!&#39;。如果多解，输出最靠上的一个。如果仍多解，输出最靠左的一个。</p> 

 
 # 提示 
<p>【限制】<br />
20％的数据，n&lt;=10,m&lt;=10<br />
40％的数据，n&lt;=100,m&lt;=100<br />
60％的数据，n&lt;=500,m&lt;=500<br />
100％的数据，n&lt;=2000,m&lt;=2000<br />
【样例解释】<br />
尽管以(2，12)起始有个更大的&ldquo;船&rdquo;，但是由于（4，25）这个该&ldquo;船&rdquo;占据的矩形中的点不是空白，该船不合法。所以答案是左上角坐标为（7，3）的船。由SRC原创</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>10 30
000000000000000000000000000000
000000000001111111111111100000
000000000000111111111111000000
000000000000011111111110100000
000000000000001111111100000000
000000000000000000000000000000
001111111111000000000000000000
000111111110000000000000000000
000011111100000000000111111000
000000000000000000000011110000
</td><td>7 3
1111111111
0111111110
0011111100
</td></tr></table>
