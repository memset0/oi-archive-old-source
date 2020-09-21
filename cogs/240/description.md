# 题目描述


<p>
问题描述
</p>
<p>
码头仓库是一块N×M个格子的矩形，有的格子是空闲的——没有任何东西，有的格子上已经堆放了沉重的货物——太重了而不再可能被移动。
</p>
<p>
现在，仓库管理员有一项任务，要将一个小箱子推到指定的格子上去。管理员可以在仓库中移动，但不得跨过沉重的不可移动的货物和箱子。当管理 员站在与箱子相邻的格子上时，他可以做一次推动，把箱子推到另一个相邻的格子。考虑到箱子很重，仓库管理员为了节省体力，想尽量减少推箱子的次数。你能帮 帮他么？
</p>
<p>
输入文件
</p>
<p>
输入文件第一行有两个数N，M（1&lt;=N,M&lt;=100），表示仓库是N×M的矩形。以下有N行，每行有M个字符，表示一个格子的状态。
</p>
<ul>
<li>
S 表示该格子上放了不可移动的沉重货物。
</li>
<li>
w 表示该格子上没有任何东西
</li>
<li>
M 表示仓库管理员初始的位置
</li>
<li>
P 表示箱子的初始位置
</li>
<li>
K 表示箱子的目标位置
</li>
</ul>
<p>
输出文件
</p>
<p>
输出文件只有一行，一个数，表示仓库管理员最少要推多少次箱子。如果仓库管理员不可能将箱子推到目标位置，那么请输出NIE，表示无解。
</p>
<p>
样例输入
</p>
<p>
<br/>
</p>
<p>
10 12
</p>
<p>
SSSSSSSSSSSS
</p>
<p>
SwwwwwwwSSSS
</p>
<p>
SwSSSSwwSSSS
</p>
<p>
SwSSSSwwSKSS
</p>
<p>
SwSSSSwwSwSS
</p>
<p>
SwwwwwPwwwww
</p>
<p>
SSSSSSSwSwSw
</p>
<p>
SSSSSSMwSwww
</p>
<p>
SSSSSSSSSSSS
</p>
<p>
SSSSSSSSSSSS
</p>
<p>
<br/>
</p>
<p>
样例输出
</p>
<p>
7
</p>