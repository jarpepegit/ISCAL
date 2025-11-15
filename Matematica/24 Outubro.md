# Matemática
## Licenciatura em Contabilidade
### Teste de Avaliação Contínua


**1.** Considere as funções reais de variável real $f$, $g$, e $h$ definidas por
$$f(x)=\begin{cases}\arctan(2-x), & x<1\\[2ex] 3x+6\ln x, & x\ge 1\end{cases}\quad\Bigg|\quad g(x)=4-4e^{2x-4}\quad\Bigg|\quad h(x)=\sin x+2e^x$$
> a) [15] Estude a continuidade da função $f$ em todos os pontos do domínio e averigue a existência de assíntotas verticais no gráfico.

**Critérios de correção**

$\colorbox{yellow}{\textbf{3 val.}}$ $\hspace{0.2cm}\underline{x<1}:\quad f(x)=\arctan(2-x)$ é a composição de duas funções contínuas: $\boxed{\arctan(x)}$, contínua em $\mathbb{R}$, e $\boxed{2-x}$, contínua também em $\mathbb{R}$ (é um polinómio). Portanto, a composição $\boxed{\arctan(2-x)}$ é contínua, em particular, em $]-\infty,1[$.

$\colorbox{yellow}{\textbf{3 val.}}$ $\hspace{0.2cm}\underline{x>1}:\quad f(x)=3x+6\ln x$ é a soma de duas funções contínuas: $\boxed{3x}$, contínua em $\mathbb{R}$, e $\boxed{6\ln x}$, contínua em $]0,+\infty[$. Portanto, a soma $\boxed{3x+6\ln x}$ é contínua, em particular, em $]1,+\infty[$.

$\colorbox{yellow}{\textbf{2 val.}}$ $\hspace{0.2cm}\underline{x=1}:$
$$\begin{matrix}\displaystyle\lim_{x\to 1^+}f(x) = \lim_{x\to 1^+}3x+6\ln x = \boxed{3} \\[3ex] \displaystyle\lim_{x\to 1^-}f(x) = \lim_{x\to 1^-}\arctan(2-x) = \boxed{\tfrac{\pi}{4}} \end{matrix}$$
Logo, $\nexists\displaystyle\lim_{x\to 1}f(x)\implies$ $f$ **não é contínua** em $x=1$.

$\colorbox{yellow}{\textbf{1 val.}}$ &nbsp; **Conclusão:** &nbsp; A função $f$ é contínua $\forall\,x\in\mathbb{R}\setminus\{1\}$.

---

**Existência de assíntotas verticais**

$\colorbox{lightgreen}{\textbf{3 val.}}$ &nbsp; Dado que a função $f$ é **contínua** $\forall\,x\in\mathbb{R}\setminus\{1\}$, o único ponto onde poderia existir assíntota vertical é $x_0=1$.

$\colorbox{lightgreen}{\textbf{2 val.}}$ &nbsp; Porém, vimos que $\displaystyle\lim_{x\to 1^+}f(x) = 3$ e $\displaystyle\lim_{x\to 1^-}f(x) =\tfrac{\pi}{4}$. Logo, $\boxed{x_0=1}$ também **não é assíntota vertical**.

$\colorbox{lightgreen}{\textbf{1 val.}}$ &nbsp; **Conclusão:** &nbsp; $\nexists$ &nbsp; assíntotas verticais.

---

> b) [15] Estude $f$ quanto à monotonia e extremos relativos.

**Critérios de correção**

$\colorbox{lightblue}{\textbf{1 val.}}$ &nbsp; $f'(x)=\dfrac{-1}{1+(2-x)^2}\quad,\quad x<1$.

$\colorbox{lightblue}{\textbf{1 val.}}$ &nbsp; $f'(x)=3+\dfrac{6}{x}\quad,\quad x>1$.

$\colorbox{lightblue}{\textbf{1 val.}}$ &nbsp; $f$ não é contínua em $x_0=1\implies$ $\nexists$ &nbsp; $f'(1)$.

**Pontos críticos**

**Regulares:** pontos onde $f'(x)=0$.

$\colorbox{lightblue}{\textbf{2 val.}}$ &nbsp; para $x<1\quad,\quad f'(x)=\dfrac{-1}{\underbrace{1+(2-x)^2}_{>0,\,\, \forall\, x\in\mathbb{R}}}<0$. Logo, $f'(x)=0$ **não tem solução**.

$\colorbox{lightblue}{\textbf{2 val.}}$ &nbsp; para $x>1\quad,\quad f'(x)=3+\dfrac{6}{x}>0$. Logo, $f'(x)=0$ **não tem solução**.

$\colorbox{lightblue}{\textbf{2 val.}}$ &nbsp; **Conclusão:** $f$ não tem pontos críticos regulares.

**Singulares:** pontos onde $\nexists\,f'(x)$.

$\colorbox{lightblue}{\textbf{2 val.}}$ &nbsp; Como $f$ não é contínua em $x_0=1$; então $\nexists\,f'(1)$.

**Análise de Sinais**

![Análise de Sinais](https://raw.githubusercontent.com/jarpepegit/ISCAL/main/Matematica/AnaliseSinais.png)

![Análise de Sinais](Matematica/AnaliseSinais.png)





















<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE2MDU3NTQxMDAsLTMxMTY5NDY1MSw5Mz
YzNjUzMDEsMTI3Nzg1NzkxNCwxMzQxNDExMzk5LC0xMDM0NDYw
NzY5LC0xNDA5MjU2OTEyXX0=
-->