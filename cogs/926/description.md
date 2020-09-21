# 题目描述


<div>
	<p>
		萨沙入侵开始了！萨沙是一群穷凶极恶的海盗，他们在入侵我们的星域，企图占领整个宇宙。
	</p>
	<p>
		统合部为了保护星域的安全，决定设置一个忠诚点数榜单以激励飞行员去干掉这群入侵者。
	</p>
	<p>
		然而，统合部的工程师不知道如何编辑这个榜单，于是他们找到了宇宙中最聪明的你，让你来完成这项工作。
	</p>
	<p>
		榜单是一个自动化的系统。榜单接受3种操作：上传一条击杀记录、查询某飞行员当前排名以及返回某区间内排名记录。
	</p>
	<p>
		当某飞行员上传新的击杀记录的时候，原有该飞行员的击杀记录将被删除。
	</p>
	<p>
		为了减轻服务器的负担，统合部决定每次返回区间排名的时候，只返回10名飞行员的记录。
	</p>
	<p>
		Input
	</p>
	<p>
		第一行是一个整数n（10&lt;=n&lt;=250000）表示操作总数目。接下来n行,每行包含了一个操作。操作的具体格式如下：
	</p>
	<p>
		+id  point 上传最新击杀记录。ID表示飞行员的编码，由大写英文字母组成，不超过10个字符。point为最多8位的正整数。
	</p>
	<p>
		?id 查询飞行员排名。该飞行员的得分记录必定已经在前面上传。如果两个飞行员的得分相同，则先得到该得分的飞行员排在前面。
	</p>
	<p>
		?num 返回自第num名开始的最多10名玩家名字。num必定合法，即不小于1，也不大于当前有记录的玩家总数。
	</p>
	<p>
		Output
	</p>
	<p>
		对与?id的操作，输出对应id飞行员当前排名
	</p>
	<p>
		对与?Num的操作，在一行中输出从第num名起往后最多10名飞行员，每个飞行员中间用一个空格间隔。
	</p>
	<p>
		样例：
	</p>
	<p>
		lp.in
	</p>
	<p>
		20
	</p>
	<p>
		+ORZLCCOW 1000000
	</p>
	<p>
		+BOB 1000000
	</p>
	<p>
		+TB 2000000
	</p>
	<p>
		+KAAALA 10000000
	</p>
	<p>
		?TB
	</p>
	<p>
		?1
	</p>
	<p>
		+DAM 100000
	</p>
	<p>
		+BOB 1200000
	</p>
	<p>
		+ORZLCCOW 900000
	</p>
	<p>
		+PB 12340000
	</p>
	<p>
		+LEO 9000000
	</p>
	<p>
		+POM 9000000
	</p>
	<p>
		+GRACE 8000000
	</p>
	<p>
		+WALT 9000000
	</p>
	<p>
		+SANDY 8000000
	</p>
	<p>
		+MICK 9000000
	</p>
	<p>
		+JACK 7320000
	</p>
	<p>
		?2
	</p>
	<p>
		?5
	</p>
	<p>
		?POM
	</p>
	<p>
		lp.out
	</p>
	<p>
		2
	</p>
	<p>
		KAAALA TB ORZLCCOW BOB
	</p>
	<p>
		KAAALA LEO POM WALT MICK GRACE SANDY JACK TB BOB
	</p>
	<p>
		WALT MICK GRACE SANDY JACK TB BOB ORZLCCOW DAM
	</p>
	<p>
		4
	</p>
	<p>
		<br/>
	</p>
	<p>
		数据范围：
	</p>
	<p>
		20%数据满足N&lt;=100
	</p>
	<p>
		100%数据满足N&lt;=250000
	</p>
	<p>
		<br/>
	</p>
	<p>
		<br/>
	</p>
	<p>
		<br/>
	</p>
</div>