
# 2.
Considere os seguintes modelos de programação linear **M1** e **M2**:
$$(\textsf{M1})\begin{array}{rc}
\min & z=-2 x_1+x_2 \\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} x_1+2x_2 &\geq& 2 \\
 x_1-2 x_2 &\leq& 2 \\
 x_1+2 x_2 &\leq& 10 \\
 x_2 &\leq& 4\\[1ex]
 x_1, x_2 &\geq& 0\end{array}
\end{array}\qquad(\textsf{M2})\begin{array}{rc}
\max & z=-2 x_1+x_2 \\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} x_1\,+\,x_2 &\geq& 1 \\
 x_1-2 x_2 &\geq& -6 \\
 x_1+2 x_2 &\leq& 10 \\
 x_1 \phantom{+2x_2}&\leq& 4\\[1ex]
 x_1, x_2 &\geq& 0\end{array}
\end{array}$$

a) Com base na resolução gráfica:

> i) [18] Determine, usando o vetor gradiente, a solução ótima de M1 e o respetivo valor ótimo.

<iframe src="https://www.geogebra.org/classic/bpqbkhhd?embed" width="900" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

O vetor gradiente da função objetivo $z=-2x_1+x_2$ é $\nabla z =(-2,1)$. Na direção do vetor gradiente, a função objetivo **aumenta** de valor. Como queremos é **minimizar** o valor da função objetivo, temos é de ir na **direção contrária** ao vetor gradiente. Logo, a solução ótima é o **vértice mais afastado** da origem, na direção do vetor $-\nabla z$. No gráfico, este vértice é $\mathsf{P}^\ast=(6,2)$, que resulta de intersectar as equações de fronteira das restrições 
$$r_2: x_1-2x_2\leq 2 \quad\textsf{e}\quad r_3: x_1+2x_2\leq 10\hspace{0.2cm}$$
O respetivo valor ótimo é $z^\ast=-2(6)+1(2)=-10$.

> **Critérios**
> - Linhas de fronteira da região admissível: **8pts**
> - Gradiente: **2pt**
> - Tracejado de linhas de nível: **2pt**
> - Determinação da solução ótima, usando linhas de nível na direção **contrária** do vetor gradiente: **3pts.** 
> - Resolução do sistema de equações de fronteira relevantes: **1pt**
> - Valor ótimo: **2pts.**


---
> ii) [8] Altere apenas um dos coeficientes da função objetivo de modo que M1 tenha solução ótima múltipla que inclua a solução obtida em i). Indique essa solução e o respetivo valor ótimo.

Da análise de sensibilidade aos coeficientes da função objetivo, vemos que a solução óptima $\textsf{P}^\ast$ irá manter-se como tal, desde que os declives das retas de nível da função objetivo e das retas de fronteira das restrições relevantes para a determinação de $\textsf{P}^\ast$, estejam relacionadas do seguinte modo
$$-\infty\le-\frac{c_1}{c_2}\leq-\frac{1}{2}\qquad\textsf{ou}\qquad+\infty\geq-\frac{c_1}{c_2}\ge\frac{1}{2}$$ 
Em particular, se queremos obter soluções ótimas múltiplas que incluam a solução ótima $\textsf{P}^\ast=(6,2)$, podemos, por exemplo, fazer que o gradiente $\nabla z$ aponte na direção contrária ao gradiente da reta de fronteira $r_2$, $\nabla r_2=(1,-2)$, ou, na direção contrária ao gradiente da reta de fronteira $r_3$,  $\nabla r_3=(1,2)$. No primeiro caso, podemos tomar, por exemplo, $c_1=-2$ e $c_2=4$, e, em consequência, o ponto $\textsf{D}=(2,0)$ e qualquer ponto do segmento $\textsf{DP}^\ast$, é solução ótima para a função objetivo $z=-2x_1+4x_2$. O valor ótimo correspondente é $z^\ast=-2(6)+4(2)=-2(2)+4(0)=-4$. No segundo caso, podemos tomar, por exemplo, $c_1=-2$ e $c_2=-4$. Assim, o ponto $B=(2,4)$ passa a ser ótimo, e, qualquer ponto da aresta $\textsf{BP}^\ast$ também o é. O valor ótimo da função objetivo correspondente $z=-2x_1-4x_2$ é $z^\ast=-2(6)-4(2)=-2(2)-4(4)=-20$.

> **Critérios**
> - Escrever a função objetivo em termos do coeficiente cuja sensibilidade queremos analisar:  **2pts**
> - Determinação dos declives usados na comparação: **3 ptos**
> - Determinação da desigualdade resultante da comparação: **2pts**
> - Determinação do intervalo de sensibilidade do coeficiiente em questão: **1pt**

---
> iii) [10] Determine o intervalo de variação de $b_3$, termo independente da terceira restrição de M1, na análise de sensibilidade a esse termo.

Como a ideia é manter relevantes as restrições $r_3: x_1+2x_2\le b_3$  e  $r_2: x_1-2x_2\le 2$ na determinação da solução ótima, resolvemos o sistema seguinte em termos de $b_3$, 
$$\begin{array}{lcl}
x_1+2x_2 &=& b_3\\
x_1-2x_2 &=& 2
\end{array}$$
Segue-se que $x_1=\frac{b_3+2}{2}$ e $x_2=\frac{b_3-2}{4}$. 

Logo, o ponto $(x_1,x_2)$ que acabamos de calcular fica restrito, pela equação de fronteira da restrição $r_2$, entre os pontos $D=(2,0)$ e $F=(10,4)$. Deste modo, se olharmos, por exemplo, para as primeiras coordenadas, temos que 
$$2\le\frac{b_3+2}{2}\le 10\quad\Leftrightarrow\quad 2\le b_3\le 18.$$
Se olharmos, por outro lado, para as segundas coordenadas, temos
$$0\leq\frac{b_3-2}{4}\leq 4\quad\Leftrightarrow\quad 2\le b_3\le 18.$$

> **Critérios**
> - Identificação das equações relevantes na análise e identificação do sistema a analisar: **3pts**
> - Identificação dos pontos usados na determinação do intervalo de sensibilidade de $b_3$: **2pts**
> - Uso desses pontos para encontrar o intervalo de variação de $b_3$: **3pts**
> - Conclusão: **2pts**
---

b) [18] Escreva o dual de M2 e, utilizando as condições de complementaridade, determine a correspondente solução ótima e o respetivo valor, sabendo que $(x_1^\ast,x_2^\ast)=(0,3)$ é a solução ótima do modelo primal.

$$(\textsf{Primal})\begin{array}{rc}
\max & z=-2 x_1+x_2 \\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} x_1 \,+\,x_2 &\geq& 1 \\
 x_1-2 x_2 &\geq& -6 \\
 x_1+2 x_2 &\leq& 10 \\
 x_1 \phantom{+2x_2}&\leq& 4\\[1ex]
 x_1, x_2 &\geq& 0\end{array}
\end{array}\qquad(\textsf{Dual})\begin{array}{rc}
\min & w=y_1-6y_2+10y_3+4y_4 \\[1ex]
\text { s.a. } & \\
&\begin{array}{rcl} y_1+y_2+y_3+y_4 &\geq& -2 \\
 y_1-2 y_2+2y_3 &\geq& 1 \\[1ex]
 y_1 &\leq& 0 \\
 y_2 &\leq& 0 \\ 
 y_3 &\geq& 0 \\
 y_4 &\geq& 0\end{array}
\end{array}$$

Usando as condições de complementaridade, ao substituir a solução ótima $(0,3)$ nas  restrições do problema primal; naquelas onde há folga, as variáveis de decisão correspondentes no dual serão 0. Assim, temos que há folga  nas restrições $r_1: 3\geq 1, r_3: 6\leq 10$ e $r_4: 0\leq 4$. Portanto, $y_1^\ast=0$, $y_3^\ast=0$ e $y_4^\ast=0$. Como $x_2^\ast\neq 0$; então $y_1^\ast-2y_2^\ast+2y_3^\ast=1$, e, em consequência, $y_2^\ast=-\frac{1}{2}$. Em conclusão, a solução ótima do problema dual é $(0,-\tfrac{1}{2},0,0)$. O valor ótimo correspondente é $w^\ast=3=z^\ast$. 

> **Critérios**
> - Escrever o dual: **8pts = (6: restrições, 2: condições de nonnegatividade)**
> - Uso das condições de complementaridade: **5pts**
> - Solução ótima e valor ótimos: **5pts**
---
> c) [6] Comente a afirmação: *O valor de qualquer solução admissível de um problema de programação linear é sempre menor ou igual que o valor de qualquer solução admissível do correspondente dual*.

Depende. Se o **problema primal é de maximização**, então sim, O valor de qualquer solução admissível de um problema de programação linear é sempre **menor ou igual que** o valor de qualquer solução admissível do correspondente dual. Porém, se o **problema primal é de minimização**, então é ao contrário, o valor de qualquer solução admissível de um problema de programação linear é sempre **maior ou igual que** o valor de qualquer solução admissível do correspondente dual

> **Critério**
> - Tudo ou nada: **6pts** Se o argumento faz parcialmente sentido, considerar: **3pts**
 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3OTU3MTAwM119
-->