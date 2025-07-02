# 2.
Considere os seguintes modelos de programação linear **M1** e **M2**:
$$(\textsf{M1})\begin{array}{rc}
\max & z=2 x_1-x_2 \\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} x_1+2x_2 &\geq& 2 \\
 x_1-2 x_2 &\leq& 2 \\
 x_1+2 x_2 &\leq& 10 \\
 x_1 &\leq& 4\\[1ex]
 x_1, x_2 &\geq& 0\end{array}
\end{array}\qquad(\textsf{M2})\begin{array}{rc}
\min & z=- x_1+3x_2 \\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} x_1\,-\,x_2 &\leq& 4 \\
 2x_1 + x_2 &\geq& 3 \\
 x_1 + x_2 &\leq& 7 \\[1ex]
 x_1, x_2 &\geq& 0\end{array}
\end{array}$$

a) Com base na resolução gráfica:

> i) **[20]** Determine, usando o vetor gradiente, a solução ótima de M1 e o respetivo valor ótimo.

<iframe src="https://www.geogebra.org/classic/awuryyux?embed" width="900" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>


**Critérios**
- Diagrama correto &nbsp;&nbsp; **(5pts)**
- Linhas de fronteira &nbsp;&nbsp; **(5pts)**
- Determinação do vetor gradiente: $\nabla z = (2,-1)$ &nbsp;&nbsp; **(2pts)**
-  Tracejado de algumas linhas de nível. &nbsp;&nbsp; **(2pts)**
-  Solução ótima $p^\ast=E=(4,1)$. &nbsp;&nbsp; **(3pts)**
-  Valor ótimo $z^\ast_{p_{\textsf{otm}}}=2(4)-(1)=7$. &nbsp;&nbsp; **(3pts)**

---
> ii) **[10]** Determine o intervalo de variação de $b_2$, termo independente da segunda restrição de M1, na análise de sensibilidade a esse termo.

**Critérios**
- Identificação das linhas relevantes: $\boxed{x_1-2x_2=2}$, &nbsp;$\boxed{x_1=4}$ &nbsp;&nbsp; **(4pts)**
- Determinação dos extremos de $b_2$, usando as linhas relevantes. &nbsp;&nbsp; **(4pts)**
- Apresentação final da resposta: $\boxed{-2\le b_2\le 4}$ &nbsp;&nbsp; **(2pts)**

---
> iii) **[10]** Efetue a análise de sensibilidade ao coeficiente de $x_2$ na função objetivo de M1.

**Critérios**
- função objetivo: $z=2x_1+c_2x_2$ &nbsp;&nbsp; **(2pts)**
- declives das retas relevantes: 
	- $m_{r_2}=-\frac{1}{2}$ &nbsp;&nbsp; **(1pt)**
	- $m_{r_4}=-\infty$ &nbsp;&nbsp; **(1pt)**
- Análise de declives: 
	- $-\frac{1}{2}\le-\frac{2}{c_2}<+\infty \iff-\frac{1}{4}\ge\frac{1}{c_2}>-\infty$ &nbsp;&nbsp; **(3pts)** 

	- $-4\le c_2<0$ &nbsp;&nbsp; **(3pts)**

---

---
b) **[20]** Escreva o dual de **M2** e, utilizando as condições de complementaridade, determine a correspondente solução ótima e o respectivo valor, sabendo que $(x_1^\ast,x_2^\ast)=(4,0)$ é a solução ótima do modelo primal. 

**Critérios**

- Formulação do problema dual. &nbsp;&nbsp; **(8pts)**  

$$(\textsf{Primal})\begin{array}{rc}
\min & z=-x_1+3x_2 \\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} x_1 \,-\,x_2 &\geq& 4 \\
 2x_1+ x_2 &\geq& 3 \\
 x_1+x_2 &\leq& 7 \\[1ex]
 x_1, x_2 &\geq& 0\end{array}
\end{array}\qquad(\textsf{Dual})\begin{array}{rc}
\max & w=4y_1+3y_2+7y_3\\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} y_1+2y_2+y_3 &\leq& -1 \\
 -y_1+y_2+y_3 &\leq& 3 \\[1ex]
 y_1 &\leq& 0 \\
 y_2 &\geq& 0 \\ 
 y_3 &\leq& 0 \\
 \end{array}
\end{array}$$

- Como usar as condições de complementaridade. &nbsp; &nbsp;**(2pts)**

Usando as condições de complementaridade, ao substituir a solução ótima $(4,0)$ nas  restrições do problema primal; naquelas onde há folga, as variáveis de decisão correspondentes no dual serão 0.

- Restrições no primal com folga. &nbsp; &nbsp;**(4pts)**

Assim, temos que há folga  nas restrições $r_2: 8\geq 3$, e  $r_3: 4\leq 7$. Portanto, $\boxed{y_2^\ast=0,\,\, y_3^\ast=0}$. 

- Restrição sem folga no dual. &nbsp; &nbsp;**(4pts)**

Como $x_1^\ast\neq 0$; então $y_1^\ast+2y_2^\ast+y_3^\ast=-1$, e, em consequência, $\boxed{y_1^\ast=-1}$. 

- Conclusão. &nbsp; &nbsp;**(2pts)**

Em conclusão, a solução ótima do problema dual é $(-1,0,0)$. O valor ótimo correspondente é $w^\ast=-4=z^\ast$. 


> Written with [StackEdit](https://stackedit.io/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MDA1MDUzOCwtNzMzMTU2NDQ3LC0xMj
ExMzE5MDI2XX0=
-->