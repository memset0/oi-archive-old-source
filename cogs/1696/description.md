# 题目描述


<h3>
【题目描述】
</h3>
<p>
我是一位不愿透露姓名的人事部主任，就职于一家中等规模的公司。现在我有一个小问题，因此需要一名有经验程序员的帮助。
</p>
<p>
<img src="/upload/image/20140905/20140905164648_61683.jpg" alt=""/> 
</p>
<p>
目前，我们的公司被分成了一些或多或少独立的部门。为了使我们的业务更加高效，需要按照层次结构组织这些部门，表示哪些部门由其他部门掌管。例如，如果有四个部门A，B，C,D，我们可以将它们按照上图中的方法组织，其中A部门控制B和D部门，D部门控制C部门。
</p>
<p>
有一个部门是中央管理部（即图中的A部门），显然它必须在层次结构的顶端，但其余部门的相对重要性并未被确定，因此在上图中，C部门和D部门可以交换位置使得C部门掌管D部门。但是，让有些部门相互协作或许是不可能的，在这种情况下它们不能直接掌管对方。例如，如果上图中的A和D不能互相协作，那么图1的组织方式就是不合法的。
</p>
<p>
一般而言，总有许多种组织部门的方法，因此能够找到最佳方案（例如，让技术部掌管市场部并不是一个好的主意）。但这个任务对你而言太复杂了，你的任务仅仅是帮助我们计算应该给我们雇来寻找最佳组织方法的咨询顾问多少费用。为了计算这一费用，我们需要知道这个问题到底有多难，因此你需要计算出有多少种组织部门的不同方式。
</p>
<p>
对了，我需要在五小时之内得到答案。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行有三个整数N，M，K（1&lt;=N&lt;=12,0&lt;=M&lt;=1500,1&lt;=K&lt;=N）。N代表部门数量，K代表中央管理部的编号。
</p>
<p>
接下来有M行，每行有两个整数1&lt;=i,j&lt;=N（i≠j），代表部门i和部门j无法协作（也就是说i无法掌管j，而j也无法掌管i）。
</p>
<h3>
【输出格式】
</h3>
<p>
输出组织部门的方案数。答案保证不超过64位有符号整数的范围。
</p>
<h3>
【样例输入】
</h3>
<p>
5 5 2
</p>
<p>
3 1
</p>
<p>
3 4
</p>
<p>
4 5
</p>
<p>
1 4
</p>
<p>
5 3
</p>
<p>
4 1 1
</p>
<p>
1 4
</p>
<p>
3 0 2
</p>
<h3>
【样例输出】
</h3>
<p>
3
</p>
<p>
8
</p>
<p>
3
</p>
<h3>
【提示】
</h3>
<p>
<img src="/upload/image/20140905/20140905170136_24312.jpg" alt=""/> 
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;page=show_problem&amp;problem=1707" target="_blank">UVa 10766 Organising the Organisation</a> 
</p>