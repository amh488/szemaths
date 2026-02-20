---
{"dg-publish":true,"permalink":"/math/x - ln x型偏移全解/","dgPassFrontmatter":true,"created":"2026-02-17T11:12:43.247+08:00","updated":"2026-02-20T19:18:59.786+08:00"}
---

引：方法来自T7导学猫团队。
对于$x-\ln x$母函数证明和积偏移结论的通法。这里始终设$x_{1}<x_{2}$

#### （一）和积待证式的转化

$$\begin{gather*}
首先有x_{1}-\ln x_{1}=x_{2}-\ln x_{2}=m\\
由x_{1}+x_{2} \sim A\\
2m+\ln x_{1} +\ln x_{2} \sim A \Rightarrow x_{1}x_{2} \sim e^{A-2m};\\
同理由x_{1}x_{2} \sim B\\
\ln x_{1} +\ln x_{2} \sim \ln B \Rightarrow x_{1}+x_{2}\sim \ln B +2m
\end{gather*}
$$

#### （二）处理方法

$$\begin{gather*}
对于x_{1}+x_{2} \sim A,\,(x_{2}-x_{1})(x_{2}+x_{1}) \sim A(x_{2}-x_{1}),\,x_{2}^2-Ax_{2} \sim x_{1}^2-Ax_{1}\\
构造F(x)=x^2-Ax+h(m),\, 令F(x)单调且F(1)=0,\\
知道x_{1}<1<x_{2},必然知道F(x_{1}) \sim F(x_{2}),得证.\\
\\
对于x_{1}x_{2} \sim B,\,(x_{2}-x_{1})x_{2}x_{1} \sim B(x_{2}-x_{1}),\,x_{2}+\frac{B}{x_{2}} \sim x_{1}+\frac{B}{x_{1}}\\
构造F(x)=x+\frac{B}{x}+h(m),\, 令F(x)单调且F(1)=0,\\
知道x_{1}<1<x_{2},必然知道F(x_{1}) \sim F(x_{2}),得证.
\end{gather*}
$$

关键是这个$h(m)$不好构造。事实上增强函数的构造几乎是任意的，我们不难发现，若是和模型，令$h(m)=e^{A-2m}$;若是积模型，令$h(m)=-(\ln B+2m)$.

#### （三）一些结论

$>m-1;>\frac{2}{3}m-\frac{4}{3}\sqrt{ m };m+\frac{1}{m}+\ln m$

$<m+\sqrt{ m };<m+\frac{m\ln m}{m-1}; <\frac{4m+2}{3}$

