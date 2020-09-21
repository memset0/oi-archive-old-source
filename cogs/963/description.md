# 题目描述


<p>
【问题描述】
</p>
<p>
<br/>
</p>
<p>
    栋栋最近迷上了随机算法，而随机数是生成随机算法的基础。栋栋准备使用线性同余法（Linear Congruential Method）来生成一个随机数列，这种方法需要设置四个非负整数参数m,a,c,X[0],按照下面的公式生成出一系列随机数&amp;{X_n}&amp;：
</p>
<p>
<br/>
</p>
<p>
                           $X_{n+1}=(aX_{n}+c)$$mod$ $m$
</p>
<p>
<br/>
</p>
<p>
其中mod m表示前面的数除以m的余数。从这个式子可以看出，这个序列的下一个数总是由上一个数生成的。
</p>
<p>
<br/>
</p>
<p>
    用这种方法生成的序列具有随机序列的性质，因此这种方法被广泛地使用，包括常用的C++和Pascal的产生随机数的库函数使用的也是这种方法。
</p>
<p>
<br/>
</p>
<p>
    栋栋知道这样产生的序列具有良好的随机性，不过心急的他仍然想尽快知道X[n]是多少。由于栋栋需要的随机数是0,1,...,g-1之间的，他需要将X[n]除以g取余得到他想要的数，即X[n] mod g，你只需要告诉栋栋他想要的数X[n] mod g是多少就可以了。
</p>
<p>
<br/>
</p>
<p>
【输入格式】
</p>
<p>
<br/>
</p>
<p>
    输入文件randoma.in中包含6个用空格分割的整数m,a,c,X[0],n和g，其中a,c,X[0]是非负整数，m,n,g是正整数。
</p>
<p>
<br/>
</p>
<p>
【输出格式】
</p>
<p>
<br/>
</p>
<p>
    输出到文件randoma.out中，输出一个数，即X[n] mod g
</p>
<p>
<br/>
</p>
<p>
【样例输入】
</p>
<p>
<br/>
</p>
<p>
    11 8 7 1 5 3
</p>
<p>
<br/>
</p>
<p>
【样例输出】
</p>
<p>
    2
</p>
<p>
<br/>
</p>
<p>
【样例说明】
</p>
<p>
<br/>
</p>
<p>
 计算得X[n]=X[5]=8,故(X[n] mod g) = (8 mod 3) = 2
</p>
<p>
<br/>
</p>
<p>
【数据规模】
</p>
<p>
<br/>
</p>
<p>
 40%的数据中m为质数
</p>
<p>
 30%的数据中m与a-1互质
</p>
<p>
<br/>
</p>
<p>
 50%的数据中n&lt;=10^6
</p>
<p>
 100%的数据中n&lt;=10^18
</p>
<p>
<br/>
</p>
<p>
 40%的数据m,a,c,X[0]&lt;=10^4
</p>
<p>
 85%的数据m,a,c,X[0]&lt;=10^9
</p>
<p>
 100%的数据中m,a,c,X[0]&lt;=10^18
</p>
<p>
<br/>
</p>
<p>
 100%的数据中g&lt;=10^8
</p>
<p>
<br/>
</p>
<p>
 对于所有数据,n&gt;=1,m&gt;=1,a&gt;=0,c&gt;=0,X[0]&gt;=0,g&gt;=1。
</p>