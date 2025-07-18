# Matemática I

## 1. 
Seja $f$ a função definida por
$$f(x)=\begin{cases} x^2+e^{x^2} & x<1\\[2ex] x+\dfrac{1}{x} & x>1\end{cases}$$

### a) [10] 
Sabendo que é contínua em $\mathbb{R}\setminus{1}$, mostre que $f$ não é prolongável por continuidade a $\mathbb{R}$.

> - Basicamente temos que mostrar que  $L=\displaystyle\lim_{x\to 1} f(x)$ não existe. **(2 val.)**
> - Cálculo dos limites laterais
> $L_-=\displaystyle\lim_{x\to 1^-}f(x)=\displaystyle\lim_{x\to 1^-}x^2+e^{x^2}=1+e$. **(3 val.)**
> $L_+=\displaystyle\lim_{x\to 1^+}f(x)=\displaystyle\lim_{x\to 1^+}x+\dfrac{1}{x}=1+1=2$. **(3 val.)**
> - Conclusão: $L_-\neq L_+\implies L$ não existe. Portanto, **não** podemos definir $f(1)=L$. **(2 val.)**

### b) [10]
Determine uma equação da reta tangente ao gráfico de $f$ no ponto de abcissa $2$.
> - Necessitamos saber, **ponto de passo** e **declive**. **(2 val.)**
> - Ponto de passo = ponto de tangência=$(2,f(2))=(2,2+\tfrac{1}{2})=(2,\tfrac{5}{2})$. **(2 val.)**
> - Declive = $f'(2)=2-\tfrac{1}{2^2}=\tfrac{7}{4}$. **(2 val.)**
> - Equação da reta: $\frac{y-y_0}{x-x_0}=m$.
> $\frac{y-\frac{5}{2}}{x-2}=\frac{7}{4}$.
> $y=\frac{7}{4}(x-2)+\frac{5}{2}$
> $4y=7x-4\iff 7x-4y=4$. **(4 val.)**

### c) [15]
Calcule $\displaystyle\lim_{x\to+\infty}\left(f(x)-\frac{1}{x}\right)^{\frac{1}{\log(x+1)}}$
> $L=\displaystyle\lim_{x\to+\infty}\left(f(x)-\frac{1}{x}\right)^{\frac{1}{\log(x+1)}}=\displaystyle\lim_{x\to+\infty}\left(x\right)^{\frac{1}{\log(x+1)}}$. **(5 val.)**
> $\log L = \displaystyle\lim_{x\to+\infty}\frac{1}{\log(x+1)}\log(x)=\lim_{x\to+\infty}\frac{\frac{1}{x}}{\frac{1}{x+1}}=\lim_{x\to+\infty}\frac{x+1}{x}=1$. **(5 val.)** 
> $\log L=1\implies L=e$. **(5 val.)**

### d) [15]
Para $x<1$, estude $f$ quanto à monotonia e existência de extremos relativos.
> Para $x<1$, temos $f(x)=x^2+e^{x^2}$. **(1 val.)**
> $f'(x)=2x+2xe^{x^2}=2x(\underbrace{1+e^{x^2}}_{>0})$ **(3 val.)**
> Portanto, $f'(x)<0$ se $x<0$ e $f


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTkxNDE4ODEwLC03NTc1MjQzMTgsLTIwMT
QwNDU3NjEsNzc1MjY3MTc4LC0xNzk2MzY2NzA2XX0=
-->