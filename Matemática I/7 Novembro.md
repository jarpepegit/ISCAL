# Matemática I
## Licenciatura em Gestão
### Teste 1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 7 de Novembro
---
**1.** Estabeleça correspondências de modo a obter proposições verdadeiras:

(1) Se $\displaystyle\lim_{x\to a}f(x)=+\infty$ e $\displaystyle\lim_{x\to a}g(x)=0$ então $\displaystyle\lim_{x\to a}(f(x))^{g(x)}=+\infty^0$ é uma indeterminação. $\boxed{(1)-(A)}$ $\colorbox{yellow}{\textbf{0,5 val.}}$ 

(2) Se $\displaystyle\lim_{x\to a}f(x)=0^+$ e $\displaystyle\lim_{x\to a}g(x)=-7$ então $\displaystyle\lim_{x\to a}(f(x))^{g(x)}=0^{-7}=+\infty$  $\boxed{(1)-(C)}$ $\colorbox{yellow}{\textbf{0,5 val.}}$ 

(3) Se $\displaystyle\lim_{x\to a}f(x)=+\infty$ e $g$ é uma função estritamente crescente numa vizinhança de $a$, com limite nulo então  $\displaystyle\lim_{x\to a}\frac{f(x)}{g(x)}=+\infty\,\,\, \textsf{ ou }-\infty$ $\boxed{(3)-(C)}$ ou $\boxed{(3)-(D)}$  $\colorbox{yellow}{\textbf{0,5 val.}}$ 

(4) Se $\displaystyle\lim_{x\to a}f(x)=+\infty$ e $\displaystyle\lim_{x\to a}g(x)=-\infty$ então $\displaystyle\lim_{x\to a}(f(x))^{g(x)}=0$ $\boxed{(4)-(E)}$ $\colorbox{yellow}{\textbf{0,5 val.}}$ 

---
**2.** Sendo $f(x)=\frac{1}{3}e^{\sqrt{x}}-1$, caracterize a função inversa (lei de transformação, domínio e contradomínio).

$\colorbox{yellow}{\textbf{0,5 val.}}$ &nbsp; Cálculo do domínio e contradomínio de $f$

Para calcular o domínio de $f$, notar que $\sqrt{x}\ge0$.
Para calcular o contradomínio de $f$, notar que

$$\begin{align*}\sqrt{x}\ge0 &\quad\Rightarrow\quad e^{\sqrt{x}}\ge e^0=1\\[2ex]&\quad\Rightarrow\quad \tfrac{1}{3}e^{\sqrt{x}}\ge \tfrac{1}{3}\\[2ex]&\quad\Rightarrow\quad \underbrace{\tfrac{1}{3}e^{\sqrt{x}}-1}_y\ge \tfrac{1}{3}-1=-\tfrac{2}{3}\end{align*}$$

--- 

$$\begin{array}{ccccc}\textsf{D}_f &=&[0,+\infty[&=&\textsf{D}'_{f^-1} & \colorbox{yellow}{\textbf{0,5 val.}}\\[2ex] \textsf{D}'_f&=&\left[-\frac{2}{3},+\infty\right[&=&\textsf{D}_{f^{-1}} & \colorbox{yellow}{\textbf{0,5 val.}}\end{array}$$

---
$\colorbox{yellow}{\textbf{0,5 val.}}$ &nbsp; **Lei de transformação**

$$\begin{align*}\tfrac{1}{3}e^{\sqrt{y}}-1=x &\quad\Leftrightarrow\quad e^{\sqrt{y}}-3=3x\\[2ex]&\quad\Leftrightarrow\quad e^{\sqrt{y}}=3+3x\\[2ex]&\quad\Leftrightarrow\quad \sqrt{y}=\ln(3+3x)\\[2ex]&\quad\Leftrightarrow\quad \boxed{y=\ln^2(3+3x)}\end{align*}$$

---
**3.** Calcule o polinómio de Maclaurin de ordem $2$ de $f(x)=\sqrt{x+1}$ e use-o para calcular um valor aproximado de $\sqrt{2}$.

$\colorbox{lightgreen}{\textbf{0,4 val.}}$ &nbsp; $f(x)=\sqrt{x+1}\quad\Rightarrow\quad f(0)=1$.

$\colorbox{lightgreen}{\textbf{0,4 val.}}$ &nbsp; $f'(x)=\frac{1}{2\sqrt{x+1}}\quad\Rightarrow\quad f'(0)=\frac{1}{2}$.

$\colorbox{lightgreen}{\textbf{0,4 val.}}$ &nbsp; $f''(x)=-\frac{1}{4(x+1)^{\frac{3}{2}}}\quad\Rightarrow\quad f''(0)=-\frac{1}{4}$.

$\colorbox{lightgreen}{\textbf{0,4 val.}}$ &nbsp; **Polinómio de Maclaurin**

$$\boxed{p_{2,0}^f(x)=1+\tfrac{1}{2}x-\tfrac{1}{8}x^2}$$

$\colorbox{lightgreen}{\textbf{0,4 val.}}$ &nbsp; $\sqrt{2}=\sqrt{1+1}\quad\approx\quad p_{2,0}^f(1)=1+\frac{1}{2}-\frac{1}{8}=\frac{11}{8}\quad\approx\quad 1,375$





<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc3OTgzMjk2MCwtMTczODk0OTc0MiwtMT
E2MTA0NDU5MCwtMTQ3MjQ3MTYxMSw5NDc1MDU5LDk0NzUwNTks
LTEwNjAwNjk3MTMsNTEwMzM5OTc5LDE2NzAyMjM0MTMsMzUzNz
A1NjM5LDE1MDM4MTI1NzUsMTE0MTU4ODMzNyw1MjEyNjEwNjBd
fQ==
-->