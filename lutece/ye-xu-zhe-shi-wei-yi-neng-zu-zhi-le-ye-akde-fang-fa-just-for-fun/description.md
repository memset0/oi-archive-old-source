
# Content

어떠한 문자열에 대해서, 이 문자열을 뒤집어도 같은 문자열이 나온다 이 문자열을 팰린드롬이라 부른다. 예를 들어, "a", "aa", "appa", "queryreuq"와 같은 문자열은 모두 팰린드롬이다.

당신은 빈 문자열 $S$가 있을 때, 두 가지 연산을 처리해야 한다.

$1$.$S$의 맨 뒤에 알파벳 소문자를 하나 추가한다.

$2$.$S$의 맨 뒤에 있는 문자를 제거한다.

각각의 연산을 처리한 후, 당신은 해당 문자열에 있는 팰린드롬 부분문자열의 갯수를 세어야 한다. 문자열 $S$와 $1 ≤ i ≤ j ≤ |S|$인 정수 $i, j$에 대해서, $S[i, j]$를 $S$의 $i$번째 문자부터 $j$번째 문자까지를 포함하는 부분문자열 이라고 정의하자. 당신은 $S[i, j]$가 팰린드롬인 모든 정수쌍 $(i, j)$의 갯수를 세어서, 이를 출력하여야 한다.

一个字符串如果从前往后读和从后往前读是一样的，那么它被称为回文串。举个例子，"a","aa","appa","queryreuq"都是回文串。

对于一个初始为空的字符串$S$，你可以进行以下两种操作：

$1$.在$S$的末尾加一个小写字母。

$2$.移除$S$的最后一个字母。

每进行完一个操作，你需要统计$S$中回文串的数量。对于字符串$S$和整数$i,j(1<=i<=j<=|S|)$,$S[i,j]$代表$S$中第$i$个字符到第$j$个字符构成的子串。你需要输出满足$S[i,j]$是回文串的$(i,j)$对数。

<p hidden = "hidden">对于任何字符串，即使该字符串被反转，也会返回相同的字符串，该字符串称为回文。 例如，诸如“a”，“aa”，“appa”和“queryreuq”的字符串都是回文。

当你有空字符串 S 时，你必须处理两个操作。

 1 。添加 S ，后跟一个小写字母字符。

 2 。删除 S 结尾的字符。

处理完每个操作后，您必须计算字符串中回文子串的数量。 对于整数 i，j ，这是一个字符串 S 和 1≤i≤j≤| S | ， S [i，j] 代替 i 到 j  作为包含的子字符串 你应该打印所有整数对（i，j）$的数量， S [i，j] 是回文。</p>

# Standard Input

입력은 두개의 줄로 되어있다.

첫번째 줄에 쿼리의 갯수 $Q$가 주어진다.

두번재 줄에 쿼리가 길이 $Q$의 문자열로 주어진다. 이 중 $i$번째 문자 $K\_{i}$는 $i$번째 쿼리의 내용을 나타낸다.

$K\_{i}$는 '$-$' 이거나, 영어 소문자 ('$a$', '$b$', ..., '$z$') 중에 하나이다. (따옴표는 제외한다.)

만약 이 문자가 '$-$'이라면, $S$의 맨 뒤의 문자를 제거해야 하며, 영어 소문자라면 $S$의 맨 뒤에 $K\_{i}$를 삽입해야 한다.

각 쿼리를 처리한 이유 문자열의 길이가 항상 $1$ 이상이 보장된다.

* $1 ≤ Q ≤ 10,000$

输入包含两行。

第一行，$Q$，给出操作的次数。

第二行，操作以一个长度为$Q$的字符串给出，第$i$个字符$K\_{i}$表示第$i$次操作。

$K\_{i}$是‘$-$’或者小写英语字母('$a$','$b$',...'$z$')（不包括括号）。

如果字符是$‘-$’，你应该移除$S$的最后一个字母。如果字符是小写字母，你应该在$S$的最后加入一个字母$K\_{i}$.

保证每次操作后字符串$S$的长度始终是正数。

$(1<=Q<=10000)$

<p hidden = "hidden">输入是两行。

第一行给出查询数 Q 。

在第二行中，查询以长度为 Q 的字符串形式给出。  i 字符 Ki 表示 i 查询的内容。

 Ki 要么是' - '，要么是小写英文字符' a '，' b '，...，' z '之一。 （除了报价。）

如果这个字符是' - '，则删除 S 结尾的字符，如果是小写字母，则在 S 结尾插入 Ki 。

处理每个查询的原因字符串始终保证至少为 1 。</p>

# Standard Output

한 줄에 $Q$개의 정수를 하나의 공백으로 구분하여 출력한다. 이 중 $i$번째 정수는 $i$번째 쿼리에 대한 정답을 의미한다.

一行输出$Q$个数，以空格隔开，第$i$个整数代表第$i$次操作后的答案。

<p hidden = "hidden">打印由一行上的单个空格分隔的 Q 整数。  i  integer是 i 查询的正确答案。</p>

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
<tr><td>17
qu-uer-ryr-reu-uq</td><td>1 2 1 2 3 4 3 4 5 7 5 7 9 11 9 11 13</td></tr></table>


# Constraints



# Note



# Source

