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
> - Para escrever a equação de uma reta necessitamos saber, **ponto de passo** e **declive**. **(2 val.)**
> - Ponto de passo = ponto de tangência=$(2,f(2))=(2,2+\tfrac{1}{2})=(2,\tfrac{5}{2})$. **(1 val.)**
> - Declive = $f'(2)=2-\tfrac{1}{2^2}=\tfrac{7}{4}$. **(1 val.)**
> - Equação da reta: $\frac{y-y_0}{x-x_0}=m$.
> $\frac{y-\frac{5}{2}}{x-2}=\frac{7}{4}$.
> $y=\frac{7}{4}(x-2)+\frac{5}{2}$


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTI3NTA0NTU4OCwtMTc5NjM2NjcwNl19
-->