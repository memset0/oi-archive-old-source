# 题目描述


<p>
<b>【问题描述】</b><br/>
     奶牛们开办了一个奶酪工厂来生产世界著名的约克奶酪。在接下来的 N (1&lt;=N&lt;=10000)  星期中，由于牛奶和劳动力的价格变化，奶酪的成本也在变化。因此奶酪工厂在第 i 个星期要花 C_i (1&lt;=C_i&lt;=5000)  分来生产一个单位的奶酪。 由于采用了最先进的技术，约克奶酪工厂在一个星期内可以生产任意多的奶酪。
</p>
<p>
约克奶酪工厂拥有一个无限大的仓库， 每个星期生产的多余的奶酪都会放在这里。而且每个星期存放一个单位的奶酪要花费 S (1&lt;=S&lt;=100)  分，不过幸运的是由于采用了最先进的技术，奶酪在仓库里不会坏 ^_^
</p>
<p>
工厂最近收到了客户 N 个星期的订单，第 i 个星期要向客户提供 Y_i (0&lt;=Y_i&lt;=10000) 个单位的奶酪。当然这些奶酪可以在第  i 个星期时生产，也可以从仓库中拿取。
</p>
<p>
采用怎么样的生产策略才会使约克工厂的花费最小呢？你能帮帮它们吗？
</p>
<p>
<br/>
</p>
<p>
【输入格式】 <br/>
     * 第 1 行两个整数： N 和 S
</p>
<p>
* 接下来的 N 行中，第 i 行的两个数表示： C_i 和 Y_i
</p>
<p>
【输出格式】 <br/>
    * 输出仅一行，工厂生产的最小花费
</p>
<p>
【输入输出样例】<br/>
 <b><br/>
</b>factory.in<br/>
4 5<br/>
88 200<br/>
89 400<br/>
97 300<br/>
91  500<br/>
factory.out<br/>
126900
</p>
<p>
【输入输出样例说明】<br/>
最佳生产方案如下：第一个星期生产 200 个单位的奶酪全部送给客户，第二个星期生产 700 个单位的奶酪， 400  个送给客户，另外 300 个放在仓库。第三个星期把仓库中的 300 个奶酪卖给客户，第四个星期生产 500 个单位的奶酪卖给客户。
</p>