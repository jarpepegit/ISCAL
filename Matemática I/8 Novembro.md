# Matemática I
## Licenciatura em Gestão
### Teste 1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 8 de Novembro
---
**3.** Resolva a inequação $\ln(2-\frac{6}{x+1})\le 0$, apresentando a solução na forma de intervalo ou união de intervalos.

$\colorbox{yellow}{\textbf{0,75 val.}}$ &nbsp; $\ln(2-\frac{6}{x+1})\le 0\quad\Leftrightarrow\quad \boxed{e^{\ln\left(2-\frac{6}{x+1}\right)}\le e^0}\quad\textsf{e}\quad\boxed{\quad 2-\frac{6}{x+1}>0}$

$\colorbox{yellow}{\textbf{0,75 val.}}$ &nbsp; $e^{\ln\left(2-\frac{6}{x+1}\right)}\le e^0\quad\Leftrightarrow\quad \left(2-\frac{6}{x+1}\right)\le 1\quad\Leftrightarrow\quad\frac{x-5}{x+1}\le 0$

![Análise de Sinais](https://raw.githubusercontent.com/jarpepegit/ISCAL/main/Matem%C3%A1tica%20I/AnaliseSinais(x-5)%3A(x%2B1).png)

$$\textsf{C.S.}_1=]-1,5]$$

$\colorbox{yellow}{\textbf{0,75 val.}}$ &nbsp; $2-\frac{6}{x+1}>0\quad\Leftrightarrow\quad\frac{2x-4}{x+1}>0$

![Análise de Sinais](https://raw.githubusercontent.com/jarpepegit/ISCAL/main/Matem%C3%A1tica%20I/AnaliseSinais(2x-4)%3A(x%2B1).png)

$$\textsf{C.S.}_2=]-\infty,-1[\,\cup\,]2,+\infty[$$

$\colorbox{yellow}{\textbf{0,75 val.}}$ &nbsp; $\textsf{C.S.}=\textsf{C.S.}_1\cap\textsf{C.S.}_2=\,]2,5]$


---
**4.** Sendo $g(x)=e^{-2x}$:
(a) Determine uma equação da reta tangente $r$ ao gráfico de $g$, no ponto de abscissa $0$ e, usando a fórmula do resto de Lagrange, mostre que "$g$ está por cima de $r$". 

$\colorbox{yellow}{\textbf{1,5 val.}}$ &nbsp; $g(0)=1$&nbsp;,&nbsp;  $g'(x)=-2e^{-2x}\Rightarrow g'(0)=-2$. Então
$$\textsf{\underline{Reta tangente}: }\quad  r=g(0)+g'(0)(x-0)\quad\Leftrightarrow\quad r=1-2x$$

Usando o resto de Lagrange $r_1^g(x)=\frac{g''(\xi)}{2!}x^2$, com $0<\xi<x$ numa vizinhança de $0$, pelo Teorema de Taylor, temos que

$$r_1^g(x)=g(x)=p^g_{1,0}(x)+r_1^g(x).$$

Como $\frac{g''(\xi)}{2!}x^2=\frac{4}{2!}e^{-2\xi}x^2>0$, segue-se que
$$e^{-2x}=1-2x+


(b) Determine o polinómio de **Maclaurin** de ordem $3$ de $g$ e use-o para obter um valor aproximado de $\frac{1}{e}$.

$\colorbox{yellow}{\textbf{0,25 val.}}$ &nbsp; $g''(x)=4e^{-2x}\quad\Rightarrow\quad g''(0)=4$.

$\colorbox{yellow}{\textbf{0,25 val.}}$ &nbsp; $g'''(x)=-8e^{-2x}\quad\Rightarrow\quad g'''(0)=-8$.

$\colorbox{yellow}{\textbf{0,5 val.}}$ &nbsp; **Polinómio de Maclaurin de g de ordem 3:** 
$$\begin{align*}p^g_{3,0}(x) &=g(0)+\tfrac{g'(0)}{1!}x+\tfrac{g''(0)}{2!}x^2+\tfrac{g'''(0)}{3!}x^3\\[2ex]&=1+\tfrac{-2}{1!}x+\tfrac{4}{2!}x^2+\tfrac{-8}{3!}x^3\\[2ex]&=1-2x+2x^2-\tfrac{4}{3}x^3\end{align*}.$$ 

$\colorbox{yellow}{\textbf{0,5 val.}}$ &nbsp; **Valor aproximado de** $\frac{1}{e}$.
$$\tfrac{1}{e}=e^{-1}=e^{-2(\frac{1}{2})}\approx p^g_{3,0}\left(\tfrac{1}{2}\right)=1-2\tfrac{1}{2}+2\left(\tfrac{1}{2}\right)^2-\tfrac{4}{3}\left(\tfrac{1}{2}\right)^3=\tfrac{1}{3}.$$


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4Nzc2NDQ0NzUsMTkxMzM0Mjc4NCw4Nj
c5MjcwNjgsLTUwODQzNjYxNywtMjA3MDEwMTkwMF19
-->