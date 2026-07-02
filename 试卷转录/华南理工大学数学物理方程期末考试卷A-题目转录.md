# 华南理工大学期末考试《数学物理方程》试卷 A（题目转录）

> 来源：`raw/网传资料/华南理工大学《数学物理方程》期末考试卷A及答案.pdf`
>
> 说明：该文件来自网传资料，仅作题型参考，不作为确认真题。本文保留题目，并在每题下新增折叠的相似作业索引与参考答案；参考答案为复习用整理。

考试信息：闭卷；试卷共七大题，满分 100 分；考试时间 120 分钟。

## 一、填空（40 分）

### 1.

二阶线性偏微分方程

$$
a_{11}u_{xx}+2a_{12}u_{xy}+a_{22}u_{yy}+b_1u_x+b_2u_y+cu=f
$$

在某点为双曲型的判别条件是在该点处（____）。

来源：PDF 第 1 页。

> [!example]- 相似作业索引
> - [x] 主对应：`raw/作业/第02章/习题2-1.md` 1(4)，练二阶主部系数和判别式。
> - [x] 次对应：`raw/作业/第02章/习题2-2.md` 1(2)、1(4)，练分类后继续化标准形。

> [!success]- 参考答案
> 填：
>
> $$
> a_{12}^2-a_{11}a_{22}>0.
> $$
>
> 等价写法是主部系数矩阵行列式 $a_{11}a_{22}-a_{12}^2<0$。

### 2.

四种固有值问题

（1）

$$
\begin{cases}
X''(x)+\lambda X(x)=0,\\
X(0)=X(l)=0
\end{cases}
$$

（2）

$$
\begin{cases}
X''(x)+\lambda X(x)=0,\\
X'(0)=X(l)=0
\end{cases}
$$

（3）

$$
\begin{cases}
X''(x)+\lambda X(x)=0,\\
X(0)=X'(l)=0
\end{cases}
$$

（4）

$$
\begin{cases}
X''(x)+\lambda X(x)=0,\\
X'(0)=X'(l)=0
\end{cases}
$$

的固有值都记为 $\lambda_n=\omega_n^2$，则（1）、（2）、（3）、（4）的固有函数 $X_n(x)$ 分别为（____），其中 $\omega_n$ 分别为（____）。

来源：PDF 第 1 页。

> [!example]- 相似作业索引
> - [x] 主对应：`raw/作业/第03章/习题3-2.md` 1(2)，练 Neumann-Dirichlet 混合边界的半整数余弦本征函数。
> - [ ] 主对应：`raw/作业/第03章/习题3-2.md` 1(4)、2(3)，练 Neumann-Neumann 边界和零模。
> - [ ] 次对应：`raw/作业/第03章/习题3-2.md` 2(1)，练 Dirichlet-Dirichlet 边界的正弦本征函数。
> - [ ] 说明：本题中的 $X(0)=X'(l)=0$ 与 1(2) 的 $X'(0)=X(l)=0$ 是对称混合边界；作业里没有完全同型题，但频率同为半整数型。

> [!success]- 参考答案
> （1）Dirichlet-Dirichlet：
>
> $$
> X_n(x)=\sin\frac{n\pi x}{l},\qquad
> \omega_n=\frac{n\pi}{l},\qquad n=1,2,\cdots.
> $$
>
> （2）Neumann-Dirichlet：
>
> $$
> X_n(x)=\cos\frac{(2n-1)\pi x}{2l},\qquad
> \omega_n=\frac{(2n-1)\pi}{2l},\qquad n=1,2,\cdots.
> $$
>
> （3）Dirichlet-Neumann：
>
> $$
> X_n(x)=\sin\frac{(2n-1)\pi x}{2l},\qquad
> \omega_n=\frac{(2n-1)\pi}{2l},\qquad n=1,2,\cdots.
> $$
>
> （4）Neumann-Neumann：
>
> $$
> X_0(x)=1,\quad \omega_0=0;\qquad
> X_n(x)=\cos\frac{n\pi x}{l},\quad
> \omega_n=\frac{n\pi}{l},\quad n=1,2,\cdots.
> $$
>
> 易错点：Neumann-Neumann 情形不能漏掉零模 $X_0=1$。

### 3.

表达波动方程初值问题

$$
\begin{cases}
u_{tt}=a^2u_{xx},\quad -\infty<x<+\infty,\ t>0,\\
u(x,0)=\varphi(x),\quad u_t(x,0)=\psi(x)
\end{cases}
$$

的解的达朗贝尔公式是（____）。

来源：PDF 第 1 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第05章/习题5-1.md` 2(2)，先化成标准 Cauchy 问题，再套 d'Alembert 公式。
> - 次对应：`raw/作业/第05章/习题5-1.md` 4、5，练波速 $a$、依赖区间和影响区域。

> [!success]- 参考答案
> 达朗贝尔公式为
>
> $$
> u(x,t)=\frac{1}{2}\left[\varphi(x-at)+\varphi(x+at)\right]
> +\frac{1}{2a}\int_{x-at}^{x+at}\psi(\xi)\,d\xi.
> $$
>
> 易错点：积分项前是 $1/(2a)$，积分区间是 $[x-at,x+at]$。

### 4.

由泊松公式，三维波动方程初值问题

$$
\begin{cases}
u_{tt}=a^2(u_{xx}+u_{yy}+u_{zz}),\quad -\infty<x,y,z<+\infty,\ t>0,\\
u(x,y,z,0)=\varphi(x,y,z),\quad u_t(x,y,z,0)=0
\end{cases}
$$

的解可表示为（____），其中 $S^M_{at}$ 表示以 $M(x,y,z)$ 为球心，以 $at$ 为半径的球面。

来源：PDF 第 1 页。

> [!example]- 相似作业索引
> - 弱对应：`raw/作业/第03章/习题3-2.md` 4(1)，练二维波动方程的模态频率和初值展开。
> - 弱对应：`raw/作业/第05章/习题5-3.md` 3，练高维波动方程 $u_{tt}-a^2\Delta u$ 的结构和能量法。
> - 说明：作业里没有三维波动方程 Poisson 公式的直接同型题；本题更适合作为公式填空单独记忆。

> [!success]- 参考答案
> 由于初速度为 $0$，三维 Poisson 公式化为
>
> $$
> u(M,t)=
> \frac{\partial}{\partial t}
> \left[
> \frac{1}{4\pi a^2t}
> \iint_{S^M_{at}}\varphi(Q)\,dS_Q
> \right].
> $$
>
> 其中 $Q$ 是球面 $S^M_{at}$ 上的点。

### 5.

函数（____）称为三维拉普拉斯方程

$$
u_{xx}+u_{yy}+u_{zz}=0
$$

的基本解。

来源：PDF 第 1 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第07章/习题7-2.md` 1，练基本解进入 Green 第二公式和边界积分公式。
> - 次对应：`raw/作业/第07章/习题7-1.md` 3，练直接判定调和函数和计算 Laplace 算子。
> - 说明：`习题7-2.md` 1 用的是二维基本解；本题问三维 Laplace 方程基本解，注意不要把二维对数型和三维 $1/(4\pi r)$ 混用。

> [!success]- 参考答案
> 三维 Laplace 方程的基本解通常写为
>
> $$
> \Phi(M,M_0)=\frac{1}{4\pi r_{MM_0}},
> \qquad r_{MM_0}=|M-M_0|.
> $$
>
> 其中 $M\ne M_0$，即 $r_{MM_0}>0$；极点处为奇异点。
>
> 易错点：二维基本解是对数型，三维基本解是 $1/r$ 型。

### 6.

根据调和函数的性质，诺伊曼问题

$$
\begin{cases}
\Delta u=0,\quad (x,y,z)\in\Omega,\\
\left.\dfrac{\partial u}{\partial n}\right|_{\Gamma}=f(x,y,z)
\end{cases}
$$

有解的必要条件是（____）。

来源：PDF 第 2 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第07章/习题7-1.md` 7，练 Neumann 问题有解的相容条件：区域积分等于边界通量。
> - 次对应：`raw/作业/第01章/习题1-3.md` 1，练齐次 Neumann 条件下的相容条件和“唯一到常数”。

> [!success]- 参考答案
> 必要条件为
>
> $$
> \iint_{\Gamma} f(x,y,z)\,dS=0.
> $$
>
> 理由是
>
> $$
> 0=\iiint_{\Omega}\Delta u\,dV
> =\iint_{\Gamma}\frac{\partial u}{\partial n}\,dS
> =\iint_{\Gamma}f\,dS.
> $$

### 7.

设函数

$$
G(M,M_0)=\dfrac{1}{4\pi r_{MM_0}}-v
$$

为区域 $\Omega$ 上的格林函数，则 $\Omega$ 上的狄利克雷问题

$$
\begin{cases}
\Delta u=0,\quad (x,y,z)\in\Omega,\\
u|_{\Gamma}=f(x,y,z)
\end{cases}
$$

的解可表示为（____）。

来源：PDF 第 2 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第07章/习题7-2.md` 1，练 Green 第二公式、基本解和边界积分表示。
> - 次对应：`raw/作业/第07章/习题7-1.md` 6，练球面/球体平均值性质，帮助理解边界数据决定内部值。
> - 说明：作业里没有完全同型的三维 Dirichlet Green 函数表示题；本题要额外注意 $G=\frac{1}{4\pi r}-v$ 的符号约定。

> [!success]- 参考答案
> 按题中
>
> $$
> G(M,M_0)=\frac{1}{4\pi r_{MM_0}}-v
> $$
>
> 的符号约定，Dirichlet 问题的解为
>
> $$
> u(M_0)=
> -\iint_{\Gamma}
> f(M)\frac{\partial G(M,M_0)}{\partial n_M}\,dS_M.
> $$
>
> 易错点：如果教材把 Green 函数定义成 $v-\frac{1}{4\pi r}$，上式符号会相反；本题按题面定义取负号。

### 8.

贝塞尔方程

$$
x^2y''+xy'+(x^2-5)y=0
$$

的通解是（____）。

来源：PDF 第 2 页。

> [!example]- 相似作业索引
> - 弱对应：`raw/作业/第03章/习题3-2.md` 9，练极坐标分离变量中的径向方程和角向模态。
> - 说明：作业里没有 Bessel 方程的直接同型题；Bessel 展开在当前复习口径中属于网传资料出现的降级题型。

> [!success]- 参考答案
> 标准 Bessel 方程为
>
> $$
> x^2y''+xy'+(x^2-\nu^2)y=0.
> $$
>
> 本题 $\nu^2=5$，所以 $\nu=\sqrt5$，通解可写为
>
> $$
> y=C_1J_{\sqrt5}(x)+C_2Y_{\sqrt5}(x).
> $$
>
> 也可用 $J_{\sqrt5}(x)$、$J_{-\sqrt5}(x)$ 作一组线性无关解。

## 二、（10 分）将方程化为标准形

将方程

$$
y^2u_{xx}-x^2u_{yy}=2
$$

化为标准形。

来源：PDF 第 2 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第02章/习题2-1.md` 1(3)，同属平方变系数双曲型特征线练习；但本题特征线为 $x^2+y^2=C$、$x^2-y^2=C$，不可直接套用 2-1(3) 的特征线。
> - 主对应：`raw/作业/第05章/习题5-1.md` 1，练变系数双曲型方程的特征变量和通解。
> - 次对应：`raw/作业/第02章/习题2-2.md` 1(4)，练变系数双曲型方程化标准形的完整流程。

> [!success]- 参考答案
> 主部系数为 $A=y^2,\ B=0,\ C=-x^2$，判别式
>
> $$
> B^2-AC=x^2y^2>0
> $$
>
> 所以在 $xy\ne0$ 处为双曲型。特征方程为
>
> $$
> y^2(dy)^2-x^2(dx)^2=0,
> $$
>
> 即
>
> $$
> y\,dy=\pm x\,dx.
> $$
>
> 取两族特征变量
>
> $$
> \xi=x^2+y^2,\qquad \eta=x^2-y^2,
> $$
>
> 令 $u(x,y)=U(\xi,\eta)$。代入可得
>
> $$
> y^2u_{xx}-x^2u_{yy}
> =
> 4(\xi^2-\eta^2)U_{\xi\eta}
> -2\eta U_{\xi}
> +2\xi U_{\eta}.
> $$
>
> 因而标准形可写为
>
> $$
> 4(\xi^2-\eta^2)U_{\xi\eta}
> -2\eta U_{\xi}
> +2\xi U_{\eta}=2,
> $$
>
> 或除以 $4(\xi^2-\eta^2)$：
>
> $$
> U_{\xi\eta}
> -\frac{\eta}{2(\xi^2-\eta^2)}U_\xi
> +\frac{\xi}{2(\xi^2-\eta^2)}U_\eta
> =
> \frac{1}{2(\xi^2-\eta^2)}.
> $$

## 三、（10 分）求解问题

$$
\begin{cases}
u_{tt}=a^2u_{xx},\quad 0<x<l,\ t>0,\\
u(0,t)=0,\quad u(l,t)=0,\\
u(x,0)=\sin\dfrac{\pi x}{l},\quad u_t(x,0)=\sin\dfrac{\pi x}{l}
\end{cases}
$$

来源：PDF 第 3 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第03章/习题3-2.md` 4(1)，练零 Dirichlet 边界下初值正好是单个正弦模态时，直接保留对应模态。
> - 次对应：`raw/作业/第03章/习题3-2.md` 2(1)，练 Dirichlet 正弦基和 Fourier 正弦系数；注意它是热方程，不是波动方程。
> - 说明：作业里没有完全同型的一维固定端波动题；本题可按固定端弦振动模板直接做。

> [!success]- 参考答案
> 零 Dirichlet 边界取正弦模态。由于初值正好是第一模态，设
>
> $$
> u(x,t)=T(t)\sin\frac{\pi x}{l}.
> $$
>
> 代入方程得
>
> $$
> T''(t)+\left(\frac{a\pi}{l}\right)^2T(t)=0.
> $$
>
> 记
>
> $$
> \omega=\frac{a\pi}{l},
> $$
>
> 则
>
> $$
> T(t)=A\cos\omega t+B\sin\omega t.
> $$
>
> 由 $u(x,0)=\sin\frac{\pi x}{l}$ 得 $A=1$；由 $u_t(x,0)=\sin\frac{\pi x}{l}$ 得 $B\omega=1$，所以 $B=1/\omega=l/(a\pi)$。因此
>
> $$
> \boxed{
> u(x,t)=
> \left[
> \cos\frac{a\pi t}{l}
> +\frac{l}{a\pi}\sin\frac{a\pi t}{l}
> \right]
> \sin\frac{\pi x}{l}
> }.
> $$

## 四、（10 分）用固有函数法求解

$$
\begin{cases}
u_{tt}=a^2u_{xx}+t\sin\dfrac{\pi x}{l},\quad 0<x<l,\ t>0,\\
u(0,t)=0,\quad u(l,t)=0,\quad t\ge 0,\\
u(x,0)=0,\quad u_t(x,0)=0,\quad 0\le x\le l
\end{cases}
$$

来源：PDF 第 3 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第04章/习题4-3.md` 1(1)，练非齐次波动方程、正弦展开和 Duhamel 模态积分。
> - 次对应：`raw/作业/第03章/习题3-2.md` 4(1)，练零 Dirichlet 边界下的固有函数展开。
> - 说明：本题比 `习题4-3.md` 1(1) 更干净，因为边界和初值已经齐次，只需要处理方程右端 $t\sin\frac{\pi x}{l}$。

> [!success]- 参考答案
> 右端只有第一正弦模态，设
>
> $$
> u(x,t)=T(t)\sin\frac{\pi x}{l},\qquad
> \omega=\frac{a\pi}{l}.
> $$
>
> 代入方程得
>
> $$
> T''(t)+\omega^2T(t)=t,\qquad T(0)=0,\quad T'(0)=0.
> $$
>
> 可用 Duhamel 模板：
>
> $$
> T(t)=\int_0^t\frac{\sin\omega(t-\tau)}{\omega}\tau\,d\tau.
> $$
>
> 计算得
>
> $$
> T(t)=\frac{t}{\omega^2}-\frac{\sin\omega t}{\omega^3}.
> $$
>
> 因此
>
> $$
> \boxed{
> u(x,t)=
> \left[
> \frac{t}{\left(\frac{a\pi}{l}\right)^2}
> -
> \frac{\sin\left(\frac{a\pi t}{l}\right)}
> {\left(\frac{a\pi}{l}\right)^3}
> \right]
> \sin\frac{\pi x}{l}
> }.
> $$

## 五、（10 分）用积分变换法求解问题

$$
\begin{cases}
u_t=a^2u_{xx},\quad -\infty<x<+\infty,\ t>0,\\
u(x,0)=\sin x
\end{cases}
$$

已知傅氏逆变换

$$
F^{-1}\left[e^{-a^2\lambda^2t}\right]
=\dfrac{1}{2a\sqrt{\pi t}}e^{-\frac{x^2}{4a^2t}}.
$$

来源：PDF 第 3 页。

> [!example]- 相似作业索引
> - 主对应：`raw/作业/第06章/习题6-1.md` 1(1)，同为全直线热方程 Cauchy 问题，初值同为 $\sin x$；作业中 $a=1$，本题保留参数 $a$。
> - 次对应：`raw/作业/第06章/习题6-1.md` 1(2)、1(3)，练 Poisson 热核公式和热核矩。
> - 说明：本题要求“积分变换法”，作业用 Poisson 热核/Fourier 模态处理；本质都是全直线热方程初值问题。

> [!success]- 参考答案
> 对 $x$ 作 Fourier 变换，记 $\widehat u(\lambda,t)=F[u]$，则
>
> $$
> \frac{\partial \widehat u}{\partial t}
> =
> -a^2\lambda^2\widehat u,
> \qquad
> \widehat u(\lambda,t)=e^{-a^2\lambda^2t}\widehat{\sin x}.
> $$
>
> 因而
>
> $$
> u(x,t)=
> F^{-1}\left[e^{-a^2\lambda^2t}\widehat{\sin x}\right].
> $$
>
> 因为 $\sin x$ 是 $\partial_{xx}$ 的特征模态，衰减因子为 $e^{-a^2t}$，所以
>
> $$
> \boxed{u(x,t)=e^{-a^2t}\sin x.}
> $$
>
> 快速验证：$u_t=-a^2e^{-a^2t}\sin x$，$u_{xx}=-e^{-a^2t}\sin x$，故 $u_t=a^2u_{xx}$。

## 六、（10 分）求解泊松方程边值问题

$$
\begin{cases}
\Delta u(x,y,z)=-12,\quad x^2+y^2+z^2<4,\\
u|_{x^2+y^2+z^2=4}=8
\end{cases}
$$

来源：PDF 第 3 页。

> [!example]- 相似作业索引
> - 弱对应：`raw/作业/第07章/习题7-1.md` 3，练直接计算 $\Delta u$。
> - 弱对应：`raw/作业/第07章/习题7-1.md` 6，练三维球体/球面平均值和球坐标思想。
> - 说明：作业里没有完全同型的球内 Poisson 方程 Dirichlet 计算题；本题可用径向试探 $u=A+Br^2$ 配合边界条件快速求解。

> [!success]- 参考答案
> 右端和边界都是球对称的，令
>
> $$
> r^2=x^2+y^2+z^2,\qquad u=A+Br^2.
> $$
>
> 因为
>
> $$
> \Delta(r^2)=\Delta(x^2+y^2+z^2)=6,
> $$
>
> 所以
>
> $$
> \Delta u=6B=-12,
> \qquad B=-2.
> $$
>
> 边界为 $r=2$，由 $u|_{r=2}=8$ 得
>
> $$
> A-2\cdot4=8,\qquad A=16.
> $$
>
> 因此
>
> $$
> \boxed{
> u(x,y,z)=16-2(x^2+y^2+z^2)
> }.
> $$

## 七、（10 分）求解圆盘的热传导问题

$$
\begin{cases}
u_t=a^2\left(u_{rr}+\dfrac{1}{r}u_r\right),\quad 0\le r<1,\ t>0,\\
u(1,t)=0,\\
u(r,0)=1-r^2
\end{cases}
$$

来源：PDF 第 4 页。

> [!example]- 相似作业索引
> - 弱对应：`raw/作业/第03章/习题3-2.md` 2(1)、2(3)，练热方程的分离变量法和 Dirichlet/Neumann 本征函数选择。
> - 弱对应：`raw/作业/第03章/习题3-2.md` 9，练极坐标区域中的径向/角向分离变量。
> - 说明：作业里没有圆盘热传导的 Bessel 零点展开直接同型题；本题属于“热方程 + 圆域径向分离变量 + Bessel 函数”的网传题型，复习优先级低于一维热方程和第七章 Green/极值原理。

> [!success]- 参考答案
> 这是径向热方程。令 $u(r,t)=R(r)T(t)$，分离变量得
>
> $$
> \frac{T'}{a^2T}=
> \frac{R''+\frac{1}{r}R'}{R}
> =-\mu^2.
> $$
>
> 因而
>
> $$
> T(t)=e^{-a^2\mu^2t},
> $$
>
> 且径向方程为
>
> $$
> R''+\frac{1}{r}R'+\mu^2R=0,
> $$
>
> 即零阶 Bessel 方程。要求 $r=0$ 处有界，故取 $R(r)=J_0(\mu r)$；边界 $u(1,t)=0$ 给出
>
> $$
> J_0(\mu)=0.
> $$
>
> 记 $\mu_n$ 为 $J_0$ 的第 $n$ 个正零点，则
>
> $$
> u(r,t)=\sum_{n=1}^{\infty}A_nJ_0(\mu_n r)e^{-a^2\mu_n^2t}.
> $$
>
> 由初值
>
> $$
> 1-r^2=\sum_{n=1}^{\infty}A_nJ_0(\mu_n r)
> $$
>
> 和正交关系
>
> $$
> \int_0^1rJ_0(\mu_mr)J_0(\mu_nr)\,dr
> =
> \frac{1}{2}J_1^2(\mu_n)\delta_{mn},
> $$
>
> 得
>
> $$
> A_n=
> \frac{2}{J_1^2(\mu_n)}
> \int_0^1r(1-r^2)J_0(\mu_nr)\,dr.
> $$
>
> 该积分可化为
>
> $$
> \int_0^1r(1-r^2)J_0(\mu_nr)\,dr
> =
> \frac{4J_1(\mu_n)}{\mu_n^3},
> $$
>
> 因此
>
> $$
> A_n=\frac{8}{\mu_n^3J_1(\mu_n)}.
> $$
>
> 最终答案为
>
> $$
> \boxed{
> u(r,t)=
> \sum_{n=1}^{\infty}
> \frac{8}{\mu_n^3J_1(\mu_n)}
> J_0(\mu_nr)e^{-a^2\mu_n^2t},
> \qquad J_0(\mu_n)=0.
> }
> $$
