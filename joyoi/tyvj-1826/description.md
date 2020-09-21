# 

 
 # 题目描述 
NJ市的快速发展得益于其便捷的交通。可是，随着经济的发展，大量的人进入NJ市，NJ市的交通也承受着巨大的压力。现在，NJ市正在筹划建设一个新型的交通枢纽，从而减轻交通的压力。<BR>NJ市包含n个区，有些区之间有双向的干道存在。新型交通枢纽建设在这些干道的基础上，将其中的部分干道改进为新型干道。改进后，干道能承受的压力可以比原来增加几十倍。为了和谐发展，在新型的交通枢纽建成后，要求任何两个区之间都可以只通过新型干道（直接或间接地）连接。政府已经预测出每条干道改进为新型干道的费用。政府希望建设新型交通枢纽的总费用最小，并以巨额奖金向市民征集方案。政府很快发现费用最小的方案不一定唯一，所以决定将奖金平分给每一种方案的第一个设计者，即如果一个人设计的费用是最小的而且前面没人和他设计出一模一样的方案，则他可获奖。<BR>Js08被奖金深深的吸引，准备设计一种方案。可是，他发现方案可能会很多，如果最后获奖者太多，巨额的资金分到每个人头上的也不会太多。所以他决定先算一下可行的方案数是多少。<BR><BR> 

 
 # 输入格式 
输入的第一行包含两个数n&nbsp;(1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;100)，m&nbsp;(1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;1,000)，分别表示该市有多少个区和有多少条干道。接下来m行，每行三个数ai、bi、ci&nbsp;(1&nbsp;≤&nbsp;ai,&nbsp;bi&nbsp;≤&nbsp;n,&nbsp;1&nbsp;≤&nbsp;ci&nbsp;≤&nbsp;1,000,000,000)，表示ai区和bi区之间有一条干道，如果改进需要ci的费用。<BR>输入保证任何两个区之间至多有一条干道。对于任何一个费用c，不会有超过10条干道的费用都是c。<BR><BR><BR> 

 
 # 输出格式 
输出费用最小的方案有多少种。由于答案可能很大，你只要输出方案数除以31011的模即可。 

 
 # 提示 
JSOI2008江苏省代表队组队第三轮选拔赛&nbsp;本次竞赛共分两试，本试卷为第二试。 
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
<tr><td>4 6
1 2 1
1 3 1
1 4 1
2 3 2
2 4 1
3 4 1
</td><td>8</td></tr></table>