# 

 
 # 题目描述 
<p>
　　X市最近新出土了一批文物，其上刻着一些奇怪的符号，经过专家的论证，这些符号是古代"炼金术士"留下的。所谓"炼金术士"就是古代化学家，他们将泥土、沙子、木炭以及一切他们认为有用的东西堆在炉子里烧，企图从中得到金子。我们应该感谢他们，黑火药就是他们发明的。<br>　　专家们一致认为，这些符号是"炼金术士"们工作过程中记下的试验数据，包括他们将哪些东西放进了炉子，以及打开炉子后，又得到了什么。经过长年累月的研究，"炼金术士"们认为，物质的变化过程与物质的量是有关系的，如果知道了这些关系，就可以节省不少原料。但是他们使用了一些非常特殊的符号来表示各种原料的比例。为了进一步了解古代"炼金术士"的工作情况，专家们想要知道这些反应中所需的物质的量的比例到底是怎样的。专家们已经列出了每个反应的化学方程式。当然，它们都是未被配平过的。你可以假设，输入的化学方程式所表示的反应类型将只有两种：复分解反应、氧化还原反应。也就是说，你只要解决这两种反应类型的化学方程式配平问题即可。<br></p> 

 
 # 输入格式 
<p>
　　每个测试点只包括一行，就是待配平的化学方程式。输入的化学方程式将符合化学的书写规范，不必判错。</p> 

 
 # 输出格式 
<p>
　　只有一行，依次输出反应物、生成物前所配的系数。两个数之间用一个空格分隔，行尾不要有多余的空格。若无法配平，则输出"No solution"。</p> 

 
 # 提示 
<p>
样例：<br>　　输入：FeCl3+NaOH=Fe(OH)3+NaCl<br>　　输出：1 3 1 3<br>　　输入：H2O+SO2+I2=H2SO4+HI<br>　　输出：2 1 1 1 2<br>　　输入：CO2+H2O=C6H12O6+H2O+O2<br>　　输出：No solution<br><br>约束条件：<br>　　输入的方程式长度不超过255。<br>　　反应物、生成物的总个数不多于100。<br>　　元素种类总数不多于100。<br>　　方程式中的元素都可以在元素周期表中找到。<br>　　测试数据和答案中的整数不会超过 。<br>　　括号嵌套的最大深度不超过10。<br><br>附：提供元素周期表<br>('Ac','Ag','Al','Am','Ar','As','At','Au','B','Ba','Be','Bh','Bi','Bk', 'Br','C','Ca','Cd','Ce','Cf','Cl','Cm','Co','Cr','Cs','Cu','Db','Dy', 'Er','Es','Eu','F','Fe','Fm','Fr','Ga','Gd','Ge','H','He','Hf','Hg', 'Ho','Hs','I','In','Ir','K','Kr','La','Li','Lr','Lu','Md','Mg','Mn', 'Mo','Mt','N','Na','Nb','Nd','Ne','Ni','No','Np','O','Os','P','Pa', 'Pb','Pd','Pm','Po','Pr','Pt','Pu','Ra','Rb','Re','Rf','Rh','Rn','Ru', 'S','Sb','Sc','Se','Sg','Si','Sm','Sn','Sr','Ta','Tb','Tc','Te','Th', 'Ti','Tl','Tm','U','Uub','Uun','Uuu','V','W','Xe','Y','Yb','Zn','Zr')<br><br></p> 
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
<tr><td></td><td></td></tr></table>
