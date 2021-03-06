
# Content

UPD：据悉，808 换成 Seve 了。

在 HSAHRBNU，有一群善于咕咕咕的鸽子。

![](/source/lutece/ge-zi-yu-808/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvcGlnZW9uLmpwZw==.jpg)

（这些鸽子可能不喜欢照相的 HeRaNO QAQ）

鸽子是很可爱的动物，Kanade 很喜欢。她每天早晨都要喂鸽子，然而这些鸽子渐渐地不爱运动，变得越来越胖，最后甚至飞不起来了。

Kanade 很着急，这些鸽子需要运动来减肥。她想到一个好方法，和 HSAHRBNU 的学生一起跳 808。

鸽子们按照学生们站队伍的方法，分成 $n$ 个队站好，每个队有一定数量的鸽子。每两个鸽子队伍相距一定的距离，这个距离有大有小，但可以忽略队伍本身的长宽，并且没有两个鸽子队站在同一位置。即鸽子队伍可以看成在 $x$ 轴上互不重合的点。Kanade 将队伍从左到右编号为 $1\sim n$。每个队伍都有一个位置坐标，第 $i$ 队的位置坐标为 $(p_i,0)$。

808 是鬼畜到令鸽子发指的一套操，这些鸽子并不想跳，所以它们会逃走。而每当鸽子逃走，Kanade 就会发动技能把它们抓回来（鸽子：悲剧啊！）。Kanade 也会调整一队鸽子的位置，使一些队伍相邻且互相熟悉的鸽子不会组团逃跑。

总的说来，会有以下两种操作：

- $\texttt{A l r c}$，若 $c>0$，则表示 Kanade 又抓回一些逃跑的鸽子，她将这些鸽子放到编号在 $[l,r]$ 范围内的队伍中，每个队伍放 $c$ 只。若 $c<0$，则表示编号在 $[l,r]$ 范围内的队伍中，每个队伍都跑了 $-c$  只鸽子；
- $\texttt{B x y}$，表示 Kanade 调整了一队鸽子的位置，将位置标号为 $x$ 的鸽子调整至位置编号为 $y$ 的鸽子队伍的位置，若 $x<y$，则位置编号在 $[x+1,y]$ 的鸽子队伍依次调整至前一个队伍先前的位置；若 $x>y$，则位置编号在 $[y,x-1]$ 的鸽子队伍依次调整至后一个队伍先前的位置。

它们在运动场上跳操，众所周知运动场是一片草地。因为鸽子最后要集合，所以不能让集合时鸽子产生的的总距离过长，否则会严重地破坏草地。鸽子队伍会全部集合于某一位置，一只鸽子产生的距离为这只鸽子所在队伍位置与集合位置之间的距离。若一只鸽子位于 $x=p_i$，集合位置为 $x=p$，那么这只鸽子产生距离为 $|p_i-p|$。一队鸽子产生的距离为这一队里所有鸽子产生的距离总和。

在最初与每次操作后，Kanade 都会询问这些鸽子应该集合到哪里，才能使此时的这些队鸽子产生的总距离最小。请帮助她完成这些操作。

# Standard Input

第一行两个整数，分别为 $n,m$ ，分别表示鸽子队伍数和操作数；

第二行有 $n$ 个正整数，第 $i$ 个正整数 $a_i$ 表示第 $i$ 个队伍初始时的鸽子数；

第三行有 $n$ 个整数，第 $i$ 个整数 $p_i$ 表示第 $i$ 队鸽子的初始位置；

接下来 $m$ 行，每行一个操作，格式如题目描述。

# Standard Output

输出 $m+1$ 行，第一行输出最初时鸽子应集合到的位置，第 $i+1$ 行输出进行前 $i$ 个操作后这些鸽子应集合到的位置。如果有多个位置可行，请输出集合位置坐标最小的位置。

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
<tr><td>5 3
3 5 1 1 3
1 2 3 4 5
A 3 5 1
B 4 1
A 2 4 2</td><td>2
2
3
3</td></tr><tr><td>7 10
193583 6358 22382 661398 141138 847695 352714
-779173 -115080 203688 251913 346218 347023 862476
B 2 3
A 3 6 861466
A 1 1 770468
A 3 6 -719552
A 2 4 378094
A 7 7 926295
B 7 1
B 2 5
B 3 4
A 1 7 470977</td><td>347023
347023
346218
251913
251913
251913
251913
251913
251913
203688
251913</td></tr></table>


# Constraints

$1\le n\le 10^5,0\le m\le 10^5,1\le l\le r\le n,1\le x,y\le n,1\le a_i,|c|\le 10^9,|p_i|\le 10^9,x\neq y$，保证 $p_i$ 从小到大给出。保证每次操作后，所有鸽子队伍都至少有 $1$ 只鸽子。

# Note

对于第一个样例，这 $5$ 队鸽子从左至右分别有 $3,5,1,1,3$ 只，位于 $x=1,x=2,x=3,x=4,x=5$ 位置。

最初，根据计算可知，$x=2$ 为最好的集合位置，所有鸽子产生的距离 $s=3\times |1-2|+5\times |2-2|+1\times |3-2|+1\times |4-2|+3\times |5-2|=15$；

Kanade 向第 $3,4,5$ 队鸽子各加入了 $1$ 只鸽子，现在这 $5$ 队鸽子从左至右分别有 $3,5,2,2,4$ 只，虽然集合位置在 $x=2$ 和在 $x=3$ 产生的距离相等，但要输出一个更靠左的位置，即 $x=2$；

Kanade 将第 $4$ 队鸽子调到第 $1$ 队的位置，原第 $1,2,3$ 队鸽子各向右串一个位置。现在这 $5$ 队鸽子从左至右分别有 $2,3,5,2,4$ 只，位于 $x=1,x=2,x=3,x=4,x=5$ 位置，现在最好的集合位置为 $x=3$ 位置；

Kanade 向第 $2,3,4$ 队鸽子各加入了 $2$ 只鸽子，现在这 $5$ 队鸽子从左至右分别有 $2,5,7,4,4$ 只，现在最好的集合位置仍为 $x=3$ 位置。

# Source


