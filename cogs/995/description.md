# 题目描述


<p>
	【题目描述】
</p>
<p>
	CG同学又弄到一批新牛，新牛到农场后首先要学习汉语，数的朗读成为新牛的一个难题，
</p>
<p>
	朗读绝对值小于10亿的数。
</p>
<p>
	新牛知道汉语有如下读数规则：
</p>
<p>
	1.首先要读符号位，然后读整数部分。整数部分之后可能出现小数点，如果有小数部分
</p>
<p>
	则小数点一定出现，并且读出小数点之后读出小数部分。
</p>
<p>
	2.符号位读法是：
</p>
<p>
	（1）正数，不论正号‘+&#39;是否出现，都不必读出符号位；
</p>
<p>
	（2）负数的最左边的符号为‘-&#39;，读成“负”（以“F”来表示“负”）。
</p>
<p>
	3.整数部分的读法是：
</p>
<p>
	（1）如果整数部分不存在或整数部分全是零则直接读成“零”（以“0”来表示“零”）；
</p>
<p>
	（2）否则从整数部分中最左边的非零数字开始读起，然后以十，百，千，万，亿（分别以“S“，“B”，“Q”，“W”，“Y”来表示）等数量单位来拼读整数部分。
</p>
<p>
	4.整数部分中：
</p>
<p>
	（1）每一个非零数字都必须结合各个相应的数量单位读出来；
</p>
<p>
	（2）每一段连续的“零”只能读成一个“零”，但是某一段连续的“零”的左侧或右侧不存在非零数字（这里只考虑整数部分）则这一段“零”不应该读出来；
</p>
<p>
	5.如果有小数部分，则先读“点”（以“D”表示“点”），然后从左至右有顺序地读出各个小数位。在读小数部分的时候不可以使用十，百，千，万，亿等数量单位；但是小数部分的每一个数字都必须读出来，连续的零不可以读成一个“零”，而应分别读出。
</p>
<p>
	6.如果数中有小数点而没有小数部分，则不应该把小数点读出来。
</p>
<p>
	例如：
</p>
<p>
	-0020030004.567应该读成“F2Q03W04D567”，000.89应该读成“0D89”。
</p>
<p>
	请你编写一个程序帮助新牛把给定的数正确的读出来。
</p>
<p>
	【输入数据】
</p>
<p>
	输入文件仅一行，存放了一个数（不超过250个字符），其绝对值小于10亿；
</p>
<p>
	【输出数据】
</p>
<p>
	输出文件仅一行，输出这个数的正确读法。
</p>
<p>
	【样例输入】
</p>
<p>
	-0020030004.567
</p>
<p>
	【样例输出】
</p>
<p>
	F2Q03W04D567
</p>
<p>
	<br/>
</p>
