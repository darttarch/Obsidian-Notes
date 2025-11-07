## The identity Function:
The function 
$$\Large
 \text{id}_X:X\to X, \ x\mapsto x
$$
is called the $\textbf{identity function}$ of $X$

---
## The Inclusion Function:
if $X\subseteq Y$ then $i:X\to Y$ is called the $\textbf{inclusion of }X \textbf{ into }Y$ .
When $X=Y$ we have $i=\text{id}_X$.

---
## The Constant Function:
If $X$ and $Y$ are non empty sets and $b\in Y$ then $X\to X, \ x\mapsto b$ is the called the $\textbf{constant function}$

---
## The Restriction Function:
If $f:X\to Y$ and $A\subseteq X$ then the function
$$\huge
f|_A: A\to Y
$$
is called the $\textbf{restriction}$ on $f$ to $A$.
clearly $f|_A=f\implies A=X$

---
## The extension Function:
Let $A\subseteq X$ and $g:A\to Y$.
then any function $f:X\to Y$ with $f|_A =g$ is called the $\textbf{extension}$ of $g$. written$f\supseteq g$

---
## The Characteristics Function:
Let $X\ne \varnothing$ and $A\subseteq X$. then the $\textbf{characteristic function}$ of $A$ is:
$$
\chi_A: X\to \{0,1\}, \quad x\mapsto
\large\begin{cases}
1, \quad x\in A \\
0, \quad x\in A^c
\end{cases}
$$

---
## The Projection Function:
If $X_1,\dots,X_n$ are non empty sets, then the projections:
$$
\text{pr}_k: \prod_{j=1}^{n} X_j\to X_k, \quad x=(x_1,\dots,x_n)\mapsto x_n,$$
$$k=1,\dots n$$
are functions.