# Matemática I

## 1. 
Seja $f$ a função definida por
$$f(x)=\begin{cases} x^2+e^{x^2} & x<1\\[2ex] x+\dfrac{1}{x} & x>1\end{cases}$$

### a) [10] 
Sabendo que é contínua em $\mathbb{R}\setminus{1}$, mostre que $f$ não é prolongável por continuidade a $\mathbb{R}$.

> - Basicamente temos que mostrar que  $L=\displaystyle\lim_{x\to 1} f(x)$ não existe. **(2 val.)**
> 
> - Cálculo dos limites laterais
> 
> $L_-=\displaystyle\lim_{x\to 1^-}f(x)=\displaystyle\lim_{x\to 1^-}x^2+e^{x^2}=1+e$. **(3 val.)**
> 
> $L_+=\displaystyle\lim_{x\to 1^+}f(x)=\displaystyle\lim_{x\to 1^+}x+\dfrac{1}{x}=1+1=2$. **(3 val.)**
> - Conclusão: $L_-\neq L_+\implies L$ não existe. Portanto, **não** podemos definir $f(1)=L$. **(2 val.)**

### b) [10]
Determine uma equação da reta tangente ao gráfico de $f$ no ponto de abcissa $2$.
> - Necessitamos saber, **ponto de passo** e **declive**. **(2 val.)**
> - Ponto de passo = ponto de tangência=$(2,f(2))=(2,2+\tfrac{1}{2})=(2,\tfrac{5}{2})$. **(2 val.)**
> - Declive = $f'(2)=2-\tfrac{1}{2^2}=\tfrac{7}{4}$. **(2 val.)**
> - Equação da reta: $\frac{y-y_0}{x-x_0}=m$.
> 
> $\frac{y-\frac{5}{2}}{x-2}=\frac{7}{4}$.
> 
> $y=\frac{7}{4}(x-2)+\frac{5}{2}$
> 
> $4y=7x-4\iff 7x-4y=4$. **(4 val.)**

### c) [15]
Calcule $\displaystyle\lim_{x\to+\infty}\left(f(x)-\frac{1}{x}\right)^{\frac{1}{\ln(x+1)}}$
> $L=\displaystyle\lim_{x\to+\infty}\left(f(x)-\frac{1}{x}\right)^{\frac{1}{\ln(x+1)}}=\displaystyle\lim_{x\to+\infty}\left(x\right)^{\frac{1}{\ln(x+1)}}$. **(5 val.)**
> 
> $\log L = \displaystyle\lim_{x\to+\infty}\frac{1}{\ln(x+1)}\ln(x)=\lim_{x\to+\infty}\frac{\frac{1}{x}}{\frac{1}{x+1}}=\lim_{x\to+\infty}\frac{x+1}{x}=1$. **(5 val.)**
>  
> $\log L=1\implies L=e$. **(5 val.)**

### d) [15]
Para $x<1$, estude $f$ quanto à monotonia e existência de extremos relativos.
> Para $x<1$, temos $\boxed{f(x)=x^2+e^{x^2}.}$ **(1 val.)**
> 
> $f'(x)=2x+2xe^{x^2}=2x(\underbrace{1+e^{x^2}}_{>0})$ **(3 val.)**
> Portanto, 
> - $f'(x)<0$ se $x<0$ **(0,5 val.)** 
> - $f'(x)>0$ se $x>0$. **(0,5 val.)**
> Contudo, como estamos **restritos** a $x<1$, segue-se que 
> - $f'(x)<0$ para qualquer $x<0$ **(2 val.)**
> - $f'(x)>0$ para qualquer $0<x<1$ **(2 val.)**
> 
> **Interpretação:** 
> - $f$ é **decrescente** em $]-\infty,0[$ **(2 val.)**
> - $f$ é **crescente** em $]0,1[$ **(2 val.)**
> - $f$ tem um **mínimo relativo** em $x=0$. **(2 val.)**

## 2.
### a) [10]
Determine $f(x)$ tal que $f'(x)=x+\ln(5x)$ e $f(1)=-\frac{1}{2}$.
> Queremos é encontrar $f(x)=\displaystyle\int x + \ln(5x)\,dx$ &nbsp;&nbsp;**(1 val.)**
> Cálculo auxiliar: $\boxed{\displaystyle\int\ln(u)\,du=u\ln u -u}$ &nbsp;&nbsp;**(2 val.)**
> 
> Substituição: $\boxed{u=5x}$ então $\boxed{du=5dx}$ &nbsp;&nbsp;**(2 val.)**
> 
> Cálculo do integral indefinido &nbsp;&nbsp;**(2 val.)**
> $$f(x)=\displaystyle\int x + \ln(5x)\,dx = \tfrac{x^2}{2}+\tfrac{1}{5}(5x\ln(5x)-5x)+ C.$$
> Uso da condição inicial: $\boxed{f(1)=-\tfrac{1}{2}}$ &nbsp;&nbsp;**(2 val.)**
> $$-\tfrac{1}{2}=f(1)=\tfrac{1}{2}+\tfrac{1}{5}(5\ln(5)-5)+C\implies C=-\ln(5).$$
> Conclusão: $f(x)= \frac{x^2}{2}+\frac{1}{5}(5x\ln(5x)-5x)-\ln(5)$. &nbsp;&nbsp; **(1 val.)**

### b) [13]
Calcule $\displaystyle\int_1^e\frac{4+\ln x}{x+x\ln x}\,dx$, efetuando a mudança de variável $\ln x=t$.
> $\boxed{\ln x=t}\Rightarrow\boxed{\frac{1}{x}dx=dt}\Rightarrow\boxed{dx=e^tdt}$ &nbsp;&nbsp;**(3 val.)**
> 
> $\displaystyle\int_1^e\frac{4+\ln x}{x+x\ln x}\,dx=$


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTkyNTE2MTU4MCwtMjc2OTg0OTcxLDE2Mz
kwOTYyNjcsLTc1NzUyNDMxOCwtMjAxNDA0NTc2MSw3NzUyNjcx
NzgsLTE3OTYzNjY3MDZdfQ==
-->