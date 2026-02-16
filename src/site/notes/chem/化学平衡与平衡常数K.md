---
{"dg-publish":true,"permalink":"/chem/化学平衡与平衡常数K/","dgPassFrontmatter":true,"created":"2025-08-18T09:08:45.680+08:00","updated":"2026-02-16T10:26:53.037+08:00"}
---

化学平衡与K是评价化学反应限度的工具。

## （一）基本原理

### 1.le Chatelier原理


> [!NOTE]+ le Chatelier原理的使用条件
> 封闭体系：指与环境只有能量交换而无物质交换的体系。
> 判定：对于已达平衡的$pVT$均相封闭体系，只改变其中一个热学量时。
> 结果：能减弱但不能抵消。
> > [!attention] 能使用
> > 1. 升降温度
> > 2. 推拉活塞/稀释液体（稀释时向系数和较大的一侧移动）
>
> > [!attention] 不能使用
> > 1. 恒压充入
> > 2. 改变浓度

### 2.平衡移动

定义：指各组分**物质的量**发生变化。物质的量的增大减小是同时的。
反应侧降低，生成侧升高，称向右移动。
反应侧升高，生成侧降低，称向左移动。

### 3.等效平衡原理

相同反应条件下，给定初始条件下，此时进行反应，平衡是等效的。

| 反应条件     | 恒温恒容  | 恒温恒容<br>（前后分子数相同） | 恒温恒压    |
| -------- | :---- | :---------------- | :------ |
| **初始条件** | 换算后相同 | 换算后成比例            | 换算后成比例  |
| **浓度关系** |       | 浓度成比例             |         |
| **物质的量** |       | 物质的量成比例           | 物质的量成比例 |
如果恒容且初始成比例，按照加压模型计算。
结论：$\alpha_{1} + \alpha_{2} = 1$
***
### 4. 化学平衡

> [!note]+ 定义
> 反应商的值为定值（称为K）的化学反应状态，叫做平衡态
> > [!attention]+ K的定义
> > $$
K = \frac{\left( \frac{p_{1}}{p^{\Theta}} \right)^{\alpha_{1} }\left( \frac{p_{2}}{p^{\Theta}} \right)^{\alpha_{2}}\cdots{}}{\left( \frac{p_{3}}{p^{\Theta}} \right)^{\alpha_{3} }\left( \frac{p_{4}}{p^{\Theta}} \right)^{\alpha_{4}}\cdots{}}
\cdot{}
\frac{\left( \frac{c_{1}}{c_{0}^{\Theta}} \right)^{\beta_{1} }\left( \frac{c_{2}}{c_{0}^{\Theta}} \right)^{\beta_{2}}\cdots{}}{\left( \frac{c_{3}}{c_{0}^{\Theta}} \right)^{\beta_{3} }\left( \frac{c_{4}}{c_{0}^{\Theta}} \right)^{\beta_{4}}\cdots{}}$$

K的运算互相乘除。推广情况：$K_{x} , K_{p}$都是相互等价的，可以用来判断。
由van's Hoff等温式可知，K的值**只与温度有关**。
***
**特殊模型：单物质模型——
包括单气体、单溶质（多重平衡的首尾）它们的浓度、分压应该为定值。
***
### 5.电化学中的K

> [!note]+ 基本公式
> $\mathrm{lg}K^{\Theta} = \frac{nE_\text{总}}{0.0592}$
> $E = E^{\Theta} + \frac{0.0592}{n}\mathrm{lg}\frac{[氧化态]}{[还原态]}$
> $n_{1}E_{1} + n_{2}E_{2} = n_{3}E_{3}$

## （二）例题

> [!example] 例一 
> 计算100$\mathrm{mL}$，6$\mathrm{M}$ $NH_{3}(aq)$最多溶解$AgCl$____g

$solution.$ 
$$\begin{align}
Ag^{+} + 2NH_{3} \ce{<=>}& [Ag(NH_{3})_{2}]^{+} \cdots\cdots\cdots K = 8\times 10^{7}\\ 
AgCl(s) \ce{<=>}& Ag^{+} + Cl^{-}\cdots\cdots\cdots K_\text{sp} = 1.25\times 10^{-10}\\ 

AgCl + 2NH_{3} \ce{<=>}& [Ag(NH_{3})_{2}]^{+} + Cl^{-}\cdots\cdots\cdots K = \frac{1}{100} \\
采用三段式：&\begin{matrix}\\
x & 0.6 & \quad & \quad \\
x & 2x & x & x  \\
\quad & 0.6-2x & x & x \\ 
\end{matrix} \\

\frac{1}{100} =& \frac{x^{2}}{(0.6-2x)^{2}} \\
\implies x =&\ 0.05\mathrm{mol} \\
m =&\ 7.175\\
\end{align}
$$

> [!example] 例二
> 忽略$S^{2-}$的第二步水解，计算$0.1\mathrm{M}$的$Na_{2}S$中$S^{2-}$的水解率
> $K_{a_{2}}(H_{2}S) = 10^{-13}$

$solution.$ 
$$
\begin{align} \\
S^{2-} + H_{2}O \ce{<=>}& HS^{-} + OH^{-} \cdots\cdots\cdots K = \frac{HS^{-}\cdot OH^{-}}{S^{2-}} = \frac{10^{-14}}{K_{a_{2}}} \\ \\
三段式： 
\begin{matrix}\\
0.1 &  &  &  \\ \\
x &  & x & x  \\
0.1-x &  &  &  \\ 
\end{matrix}\\
K = 10^{-1} =& \frac{x^{2}}{0.1-x} \quad \implies \frac{x}{0.1} = \frac{\sqrt{ 5 }-1}{2} \approx 0.618 \approx 62\%
\end{align} \\

$$

> [!example] 例三 氧化还原与沉淀竞争
> 判断银离子和碘离子会发生什么反应：
> $$
\begin{equation}
\begin{cases}
2Ag^{+} + 2I^{-} \ce{<=>} 2Ag + I_{2} \cdots\cdots K^{\Theta} =\ ? \\
Ag^{+} + I^{-} \ce{<=>} AgI\ce{v} \cdots\cdots K_\text{sp}(AgI) = 8.51\times 10^{-17}\\
\end{cases}
\end{equation}
> $$
> $E^{\Theta}\left( Ag^{+}\text{/}Ag \right) = 0.7996\mathrm{V}$
>$E^{\Theta}\left( I_{2}\text{/}I^{-} \right) = 0.535\mathrm{V}$
>计算并判断哪个反应为主反应。

$solution.$ $E_\text{总} = E^{\Theta}\left( Ag^{+}\text{/}Ag \right) - E^{\Theta}\left( I_{2}\text{/}I^{-} \right) =\ 0.2646\mathrm{V}$
$即K^{\Theta} = 10^{8.94}$
$K_{2} = \frac{1}{K_\text{sp}} =\ 1.18\times 10^{16}$
$故沉淀反应为主反应.$

## （三）高考热力学大题

高考热力学大题有很强的套路性，掌握了分析方法即有做题的思路。

$$
应当看
\begin{equation}
    \begin{cases}
    K值的变化情况，只与温度有关 \\
    平衡的移动(相对含量变化) \\
    速率变化\\
    \end{cases}
\end{equation}
$$
$$
计算方法
\begin{equation}
    \begin{cases}
    找元素守恒 \\
    找物质的比值关系 \\
    列三段式\\
    \end{cases}
\end{equation}
$$
$$
一个核心：识图找物质
$$
>[!note]+ 识图方法（推理判断题）
>1. 主要物质
>	 通过水解、电离等定性判断哪个很多
>	 题图不会错，通过细节判断反应是否充分、吸放热、速率
>	 观察物质增多减少（不单调时考虑竞争）
>2. 理想情况
>	 这里指：对称+斜率大+条带窄时，理想情况为分段函数，可以判断一定条件下发生了物质转化。
>3. 首末位置以及特殊点
>	 看极端情况下谁特别多，比如pH和浓度、时间
>4. 多重平衡曲化直
>前两种情况都抓住了主要方面，先研判特殊物质。一般会先出题。

当题图分析与自己的思路相违背时，考虑：
1. 存在某些“常识”也即化学环境、反应条件、另外的物质/反应等等，这些应该自己知道；
2. 题目中存在你没看到的信息/你没分析出来的结论，这个往往就是解题的出口。 
***
#### 2023山东

$\quad\quad\quad\quad\mathrm{I.}\quad\mathrm{HCOOH}\ce{<=>}\mathrm{CO} + \mathrm{H_{2}O}(快)$
![2023山东](/img/user/chem/img/2023%E5%B1%B1%E4%B8%9C%E5%8E%9F%E7%90%86.png)

> [!note]+ 分析与解答
> 快平衡的性质：很快平衡（需要时间）+K值不变
> (2)$\sqrt{K_{a}x}\quad kx\sqrt{K_{a}x}$
> (3)列表格$|C|\mathrm{1M}|$，$t_{1}$时0.14M的$\mathrm{HCOOH}$解得$K_{1} = 5$，找到比例关系1:5，同时$\mathrm{CO_{2}}$与$\mathrm{H_{2}}$始终1:1,即$\mathrm{CO_{2}}$也是y。考虑到含碳物种和为1，且那俩的比例为1:5，解得$\mathrm{CO} = \frac{5(1-y)}{6}$，故比值为$\frac{5(1-y)}{6y}$。平衡常数为$\frac{6y^{2}}{1-y}$
> 下边$H^{+}$催化，故时间变短往左移；考虑到$\mathrm{HCOOH}$的电离，$H^{+}$增多导致$\mathrm{HCOOH}$的含量上升，平衡右移故$\mathrm{CO}$的含量升高。于是选a。通过元素守恒和K值，可以知道填减小和不变.

***

#### 2024山东

![2024山东2](/img/user/chem/img/2024%E5%B1%B1%E4%B8%9C%E5%8E%9F%E7%90%862.png)

> [!note]+ 分析(3)
> 先列表格。$1.2\mathrm{H_{2}O}\quad 2\mathrm{H_{2}}\quad 0.6\mathrm{CO}\quad 0.2\mathrm{CO_{2}}$代表着$4.4\mathrm{H}\quad 0.8\mathrm{C\quad 2.2\mathrm{O}}$ 可能没有用。接着考察比例关系，易知$\mathrm{CO}$和$\mathrm{H_{2}}$若不发生反应$\mathrm{II}$则始终为1:1，又因为反应$\mathrm{III}$不消耗它们则其和始终为定值。因此考虑二者与其平均值的插值——这里是0.7——就能够了解生成的$\mathrm{CO_{2}}$含量也是0.7。而现在是0.2，于是$\mathrm{CaO}$吸收掉0.5，就是$\mathrm{CaCO_{3}}$的摩尔数。
> 
> 下边，考虑我们说过的单物质模型，必须重视，那么$\mathrm{CO_{2}}$的分压是不变的。
> 前文说过总压是$p$。这类变不变的模型最先考虑K值，最后考虑平衡移动。考虑反应$\mathrm{I},\mathrm{II}$，则温度不变$K_{x}$不变，代表着$\frac{n_{\mathrm{CO_{2}}}\cdot n_{\mathrm{H_{2}}}}{n_{\mathrm{CO}}\cdot n_{\mathrm{H_{2}O}}}$与$\frac{n_{\mathrm{CO}}\cdot n_{\mathrm{H_{2}}}}{n_{\mathrm{H_{2}O}}}$同时不变，前者取倒数相乘得$\frac{n^{2}_{\mathrm{CO}}}{n_{\mathrm{CO_{2}}}}$不变。也即$n_{\mathrm{CO}}$不变。显然地，其分压不变。


***
#### 2025山东

![2025山东1](/img/user/chem/img/2025%E5%B1%B1%E4%B8%9C%E5%8E%9F%E7%90%861.png)
![2025山东1](/img/user/chem/img/2025%E5%B1%B1%E4%B8%9C%E5%8E%9F%E7%90%862.png)

>[!note]+ 分析与解答
>前判断：$\mathrm{S_{2}}$只与反应$\mathrm{I}$有关，于是$\mathrm{S_{2}}$变化表现$\Delta H_{1}<0$，根据初始含量列表格（**气态！**）$1\mathrm{Ca}\quad 1\mathrm{S}\quad 2\mathrm{O}\quad 0.2\mathrm{H}$。又由于$\mathrm{II}$的K不变，得到$\mathrm{H_{2}}$和$\mathrm{H_{2}O}$比例关系100倍，同时也得到$\Delta H_{2} = 0$，判断不会因温度改变平衡移动。换算到$\mathrm{lg}$就是始终2倍。即可判断出乙是$\mathrm{H_{2}O}$丁是$\mathrm{H_{2}}$。
>
>接下来看增大减小，温度不变，$\mathrm{II}$的反应应该不会移动。上升代表了$\mathrm{H_{2}}$或$\mathrm{H_{2}O}$增加。我们考虑温度上升的情况，考察反应的$K_{x}$，底下是三次而上边是两次，只有K值变小也即逆向移动的时候才能满足，证明$\Delta H_{3}<0$，单减的是$\mathrm{H_{2}S}$，剩下那个是$\mathrm{SO_{2}}$。
>
>我们把不同的相看成不同的体系，先提醒一下自己，同相该元素守恒吗？**不同相**之间，往往对应着**比例关系**，往往**差量计算、比例关系计算**。由$\mathrm{S}$和$\mathrm{H}$守恒以及$\mathrm{O}$不守恒，计算知$\frac{0.9+a}{2}$和$150a$
>
>平衡移动+K为定值。增大和减小。



