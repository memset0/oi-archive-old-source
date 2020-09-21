# 题目描述

<p>零点的钟声敲响，猴年终于到来啦~</p>
<p>在这新年的第一天，猴族收到了从世界各地发来的贺电。正当猴族首领猴腮雷开心地收着贺电时，一封来自跳蚤国的贺电吸引了他的注意：</p>
<p>“猴年大吉！在这个大喜的日子里怎么能少了我跳蚤国王。还记得吗？是当年评选十二生肖的时候，你使用了一票否决权否决了跳蚤，真是令人难忘的回忆呢。所以今天我带来了一些小礼物，真的是很小的礼物，希望您收下。 ——跳蚤国王”</p>
<p>猴族首领猴腮雷愣住了，正当此时急急忙忙跑过来一个猴兵：“不好了，跳蚤国军队兵临城下了！”</p>
<p>跳蚤国拥有世界上最跳的坦克，可以直接从前线跳到敌人后方，情况十分危急。于是猴族首领猴腮雷立即下令：“进入战争状态，启动所有的高达，装备腮雷迎战！”</p>
<p>猴族一共拥有 $1024$ 台高达，每个高达有一个编号，为一个 $0$ 到 $2^{32} - 1$ 的整数。（不一定连续）</p>
<p>猴族一共拥有 $1024$ 个机库，编号为 $0$ 到 $1023$。每个高达都存放在某个机库中（<strong>一个机库可能存放多个高达</strong>）。</p>
<p>前线将领只知道自己管辖范围内的高达的编号而不知道位置，只有猴族首领猴腮雷清楚每个高达存放在哪个机库，所以他需要把位置信息发给前线将领。</p>
<p>但是，猴族的通讯技术不发达，猴族首领猴腮雷找到了你 —— 请你设计一个通讯方式传输高达的位置。</p>

# 任务描述


<p>你需要写一个程序，实现编码和解码的功能。</p>
<h4>编码</h4>
<p>如果是编码，输入的第一行为一个字符串 “<samp>encode</samp>”。</p>
<p>接下来 $1024$ 行，每行两个整数 $k, v$，表示编号为 $k$ 的高达存放在编号为 $v$ 的机库。保证 $0 \leq k &lt; 2^{32}$，$0 \leq v &lt; 1024$，<strong>保证 $k$ 互不相同</strong>。</p>
<p>你需要输出一个<strong> 01 串</strong>，表示发送给前线将领的信息。</p>
<h4>解码</h4>
<p>如果是解码，输入的第一行为一个字符串 “<samp>decode</samp>”。</p>
<p>接下来一行，是你的程序编码出的 01 串。</p>
<p>接下来一行，一个正整数 $Q$，表示前线将领管辖了 $Q$ 个高达。</p>
<p>接下来 $Q$ 行，每行一个整数 $k$ 表示一个高达编号。保证一定是合法的高达编号，<strong>保证编号互不相同</strong>。</p>
<p>对于每个高达编号，你需要输出一行，为它所在的机库编号。</p>

# 样例一


<p>见样例数据下载。</p>
<p>其中，<samp>encode.in</samp> 和 <samp>encode.out</samp> 为一个编码的例子，<samp>decode.in</samp> 和 <samp>decode.out</samp> 为一个解码的例子。</p>

# 限制与约定


<p>如果解码出的机库编号错误，直接 $0$ 分；</p>
<p>如果你的程序正常执行，设编码出的 01 串长度为 $n$，则你可以获得如下分数：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>得分</th><th>条件</th><th>得分</th><th>条件</th></tr></thead><tbody><tr><td>1</td><td>$n \leq 10^5$</td><td>6</td><td>$n \leq 15000$</td></tr><tr><td>2</td><td>$n \leq 43008$</td><td>7</td><td>$n \leq 14000$</td></tr><tr><td>3</td><td>$n \leq 40000$</td><td>8</td><td>$n \leq 13000$</td></tr><tr><td>4</td><td>$n \leq 30000$</td><td>9</td><td>$n \leq 12750$</td></tr><tr><td>5</td><td>$n \leq 20000$</td><td>10</td><td>$n \leq 12500$</td></tr></tbody></table></div>

<p>如果有多个条件被满足，取得分最高的那一个。</p>
<p>各测试点满足以下约定：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$0 \leq k \lt 1024$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="7">无</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>
<p>由于程序会被执行两次，时间限制 $1\texttt{s}$ 是指编码和解码各有 $1\texttt{s}$ 时限。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=178">样例数据下载</a></p>
