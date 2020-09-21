# 题面



<div class="pdcont"><b>【问题描述】</b><br/>
　　在平面直角坐标系中有n个整点，部分点之间有一些边存在，保证所有边只在顶点处相交且所有点度数至少为2，这些边将整个坐标系分成了若干个域。我们定义一个域的“左下角”为包含边界的域中横坐标最小的整点（横坐标相同取纵坐标最小点），每次询问给定一个点，对于所有非无限域（包含有限个整点），问“左下角”在给定点左下方（横纵坐标满足小于等于关系）的所有非无限域的内部（不含边界）的整点个数。<br/>
<b>【输入格式】</b><br/>
　　第一行给定两个整数n，m，q，表示整点个数、边数和询问次数；<br/>
　　接下来n行，每行两个整数x，y，表示一个整点，按读入顺序编号1-n；<br/>
　　接下来m行，每行两个整数a，b，表示编号为a和b的两个点间有一条边；<br/>
　　接下来q行，每行两个整数x’，y’，表示询问中给定的点。<br/>
<b>【输出格式】</b><br/>
　　对于每个询问，每行输出一个整数，表示满足条件的非无限域内部整点个数之和。<b></b><br/>
<b>【样例输入】</b><br/>
　　4 4 1<br/>
　　0 0<br/>
　　2 0<br/>
　　0 2<br/>
　　2 2<br/>
　　1 2<br/>
　　1 3<br/>
　　2 4<br/>
　　3 4<br/>
　　1 1<br/>
<b>【样例输出】</b><br/>
　　1<br/>
<b>【数据规模】</b><br/>
　　20%的数据中，所有边与x轴或y轴平行，-1000&lt;=x,y,x’,y’&lt;=1000。<br/>
　　另有20%的数据，n&lt;=1000，q&lt;=1000。<br/>
　　100%的数据中，n&lt;=100000，q&lt;=100000，-10^9&lt;=x,y,x’,y’&lt;=10^9。</div>


