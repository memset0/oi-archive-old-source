
# Content

`forgottencsc`在测他的高精度有符号整数板子。

共$T$组数据，每组数据形如$a \quad op \quad b$。

其中$op \in \{+,-,*,/\}$，除法为向0取整。

请输出对应的运算结果。

# Standard Input

8

-114514 + 1919

1919 - 114514

114514 * -1919

-114514 / 1919

114514191981011451419198101145141919810 + 893364893364893364893364893364893364

114514191981011451419198101145141919810 - 893364893364893364893364893364893364

114514191981011451419198101145141919810 * 893364893364893364893364893364893364

114514191981011451419198101145141919810 / 893364

# Standard Output

-112595

-112595

-219752366

-59

115407556874376344784091466038506813174

113620827087646558054304736251777026446

-102302958907883222168882661314089880036718020113095798810138317706889140840

-128183128020618081117213253662719

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
</table>


# Constraints

对于25%的数据：

$0 \leq \sum{|a|} + \sum{|b|} \leq 2 \times 10^{10^3}$

对于50%的数据：

$0 \leq \sum{|a|} + \sum{|b|} \leq 2 \times 10^{10^4}$

对于75%的数据：

$0 \leq \sum{|a|} + \sum{|b|} \leq 2 \times 10^{10^5}$

对于100%的数据：

$0 \leq \sum{|a|} + \sum{|b|} \leq 2 \times 10^{10^6}$

# Note

数据随机

数据是用Boost.Multiprecision造的

欢迎提供Hack

# Source

