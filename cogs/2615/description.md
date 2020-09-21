# 题目描述


<h3>
【题目描述】
</h3>
<p>
传说中的交互式题目来也（可惜是个水题233）（用评测插件实现的，请大家自觉遵守规定QwQ利用漏洞骗分是可耻的行为）
</p>
<p>
第一，你并不用在意I/O文件名，因为按照规则你并不被允许读写文件，这里也不会告诉你文件格式233333333
</p>
<p>
第二，普及一下啥叫交互式题目：
</p>
<p>
    一般来说是提供一个库文件/头文件供程序引用，其中包含一些类方法（然而COGS对其的支持基本可以吔屎(╯‵□′)╯︵┻━┻），包括初始化、询问、提交等。你的程序需要从这些类方法而不是文件中获取信息。
</p>
<p>
    其次，交互式题目除了时间限制、内存限制之外往往有调用次数限制并根据你的调用次数给分（COGS对于不同分数的支持也可以吔屎了(╯‵□′)╯︵┻━┻）。
</p>
<p>
第三，介绍一下题目内容
</p>
<p>
    一共有$N$个初始端，编号为1..N。每个初始端都有一个对应的映射端。不同的初始端不会有同一个映射端。但是出于某些原因你不能直接调查每个初始端对应的映射端，你只能得到这样的信息：初始端1 4 5 8对应的映射端是3 7 5 9。你并不能得到具体对应关系，也就是说回答是无序的。
</p>
<h3>
【交互方法】
</h3>
<p>
交互库提供一个包含3个类方法的Interacitve类，其中包含的可供选手调用的方法如下：
</p>
<p>
int Initialize();
</p>
<p>
int* Quest(int*);
</p>
<p>
void Submit(int*);
</p>
<p>
（没错，此题是Pascal不友好的）
</p>
<p>
首先请在程序开头调用Initialize方法，该方法返回1个int值，为$N$。你只能调用一次否则就会异常退出。
</p>
<p>
Quest方法接收一个int指针（其实就是你想询问映射关系的数组$A_0..m$），该数组第0位是你想询问映射关系的数量$m$。此后的$m$个元素为你想询问的映射关系的初始端。该方法返回一个指向存储对应映射端的数组$B_0..m-1$。为了方便使用，该方法返回的数组已经按升序排好。
</p>
<p>
Submit方法接收一个指向数组$S_0..N$的指针。$S_0$应置为0，$S_i$表示计算得的初始端$i$对应的映射端。
</p>
<p>
调用示例：
</p>
<p>
int n=Inter.Initialize();
</p>
<p>
Inter.Submit(ans);
</p>
<h3>
【交互示例】
</h3>
<p>
以下为成功交互的一个例子，但显然并不是正解（以下代码已略去交互库部分）
</p>
<pre class="prettyprint lang-cpp">/*&lt;Interactive Library&gt;*/
int main(){
    int n=Inter.Initialize();    
    int ans[n]={0};
    int q[]={5,1,6,8,2,3};
    int* r=Inter.Quest(q);
    for(int i=0;i&lt;5;i++){
        ans[r[i]]=q[i+1];
    }
    Inter.Submit(ans);
    return 0;
}</pre>
<h3>
【评分标准】
</h3>
<p>
设出题人的标程可达到的最小询问次数为$S$，你的询问次数为$S_x$，则按照如下规则判分：
</p>
<p>
$S_x&lt;S$ Score=12;
</p>
<p>
$S_x==S$ Score=10;
</p>
<p>
$S_x&lt;=S+1$ Score=9;
</p>
<p>
$S_x&lt;=S+2$ Score=8;
</p>
<p>
$S_x&lt;=S+3$ Score=7;
</p>
<p>
$S_x&lt;=S+5$ Score=6;
</p>
<p>
$S_x&lt;=S+10$ Score=5;
</p>
<p>
$S_x&lt;=2S$ Score=4;
</p>
<p>
$S_x&lt;=3S$ Score=3;
</p>
<p>
$S_x&lt;=5S$ Score=2;
</p>
<p>
$S_x&lt;=10S$ Score=1;
</p>
<p>
$S_x&gt;10S$ Score=0;
</p>
<h3>
【提示】
</h3>
<p>
请在提交的代码前加入如下代码（警告：不要擅自拆封或修改其中的代码）：
</p>
<p>
<br/>
</p>
<pre class="prettyprint lang-cpp">%:include &lt;bits/stdc++.h&gt;
using namespace std;class Interactive&lt;%private:static const int _=10010;bool __;int ___;int ____&lt;:_:&gt;;int _____&lt;:_:&gt;;int ______&lt;:100:&gt;;int _____________;void _______()&lt;%FILE* ________=fopen(&#34;Interactive.in&#34;,&#34;rb&#34;);fread(______,sizeof(int),100,________);fread(&amp;_____________,sizeof(int),1,________);fread(_____+1,sizeof(int),_____________,________);fclose(________);%&gt;void _________()&lt;%for(int ___________=0,____________=1;____________&lt;=_____________;____________++,___________=___________&lt;99?___________+1:0)&lt;%_____&lt;:____________:&gt;=_____&lt;:____________:&gt;^______&lt;:___________:&gt;;%&gt;%&gt;void ___________________________(int* ___________________)&lt;%for(int ___________=0,____________=1;____________&lt;=_____________;____________++,___________=___________&lt;99?___________+1:0)&lt;%___________________&lt;:____________:&gt;=___________________&lt;:____________:&gt;^______&lt;:___________:&gt;;%&gt;%&gt;void ______________(int* _______________)&lt;%FILE* ________________=fopen(&#34;Interactive.out&#34;,&#34;wb&#34;);int _________________=0;fwrite(&amp;_________________,sizeof(int),1,________________);fwrite(&amp;_____________,sizeof(int),1,________________);fwrite(_______________+1,sizeof(int),_____________,________________);fwrite(&amp;___,sizeof(int),1,________________);fclose(________________);%&gt;public:int Initialize()&lt;%int _________________=0xFFFFFFFF;if(__)exit(233);_______();_________();FILE* ________________=fopen(&#34;Interactive.out&#34;,&#34;wb&#34;);fwrite(&amp;_________________,sizeof(int),1,________________);fclose(________________);__=true;return _____________;%&gt;int* Quest(int* q)&lt;%memset(____,0,sizeof(____));for(int ___________=1;___________&lt;=q&lt;:0:&gt;;___________++)&lt;%____&lt;:___________-1:&gt;=_____&lt;:q&lt;:___________:&gt;:&gt;;%&gt;sort(____,____+q&lt;:0:&gt;);___++;return ____;%&gt;void Submit(int* ___________________)&lt;%___________________________(___________________);______________(___________________);exit(0);%&gt;%&gt;Inter;
</pre>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【数据范围】
</h3>
<p>
100% n&lt;=10000,保证所有的的映射端为1~n的排列。
</p>
<h3>
【来源】
</h3>
<p>
Albert S. Chang
</p>
<p>
FHZOI 2017
</p>
<p>
<br/>
</p>