# 1. Addition

Two vectors $\mathbf{a}$ and $\mathbf{b}$ are added by parallel translation of one of the vectors, say $\mathbf{b}$, such that the tail of $\mathbf{b}$ coincides with the head of $\mathbf{a}$. Then the vector $\mathbf{a}+\mathbf{b}$ is the vector starting at the tail of $\mathbf{a}$ and ending at the head of $\mathbf{b}$.

Rules of vector addition:

$\alpha.$ Commutativity
$$
\mathbf{a} + \mathbf{b} = \mathbf{b} + \mathbf{a}$$

```tikz
\begin{document}
\begin{tikzpicture}[>=stealth]

\draw[very thick,->] (0,0)--(6,0) node[midway,below]{$\mathbf{a}$};
\draw[very thick,->] (0,0)--(1.6,3) node[midway,left]{$\mathbf{b}$};

\draw[dashed,very thick,->] (6,0)--(7.6,3) node[midway,right]{$\mathbf{b}$};
\draw[dashed,very thick,->] (1.6,3)--(7.6,3) node[midway,above]{$\mathbf{a}$};

\draw[very thick,->] (0,0)--(7.6,3) node[midway,below,sloped] {$\mathbf{a}+\mathbf{b}=\mathbf{b}+\mathbf{a}$};
\end{tikzpicture}
\end{document}
```

---
$\beta.$ Associativity
$$
\mathbf{a}+(\mathbf{b}+\mathbf{c}) = (\mathbf{a}+\mathbf{b})+ \mathbf{c}$$

```tikz
\begin{document}
\begin{tikzpicture}[>=stealth]
% base point
\coordinate (0) at (0,0);

% vector a
\coordinate (A) at (6,0.4);
\draw[very thick,->] (0)--(A) node[midway,sloped,below]{$\mathbf{a}$};

% vector b
\coordinate (B) at (6.5,3);
\draw[very thick,->] (A)--(B) node[midway,right]{$\mathbf{b}$};

% vector c
\coordinate (C) at (2,5);
\draw[very thick,->] (B)--(C) node[midway,right]{$\mathbf{c}$};

% vector sums
\draw[->,red,very thick] (0)--(C) node[sloped,black,midway,above]{$\mathbf{a}+(\mathbf{b}+\mathbf{c}) = (\mathbf{a}+\mathbf{b})+ \mathbf{c}$};

\draw[very thick,->,red] (0)--(B) node[black,midway,sloped,above]{$\mathbf{a}+\mathbf{b}$};

\draw[very thick,->,red,dashed] (A)--(C) node[black,midway,sloped,above]{$\mathbf{b}+\mathbf{c}$};

\end{tikzpicture}
\end{document}
```

---

$\gamma.$ Vector substraction
$$
\mathbf{a} - \mathbf{b}=\mathbf{a}+(-\mathbf{b})
$$

```tikz
\begin{document}
\begin{tikzpicture}[>=stealth]

% coordinates
\coordinate (A) at (0,0);
\coordinate (B) at (7,0);
\coordinate (C) at (8,4);
\coordinate (D) at (1,4);

%vevtors
\draw[->,very thick] (A)--(B) node[midway,below]{$\mathbf{b}$};
\draw[->,very thick] (A)--(D) node[midway,left]{$\mathbf{a}$};
\draw[->,very thick] (B)--(C) node[midway,right]{$\mathbf{a}$};
\draw[->,very thick] (C)--(D) node[midway,above]{$\mathbf{-b}$};
\draw[->,very thick] (B)--(D) node[midway,sloped,above]{$\mathbf{a}-\mathbf{b}$};


\end{tikzpicture}
\end{document}
```

>[!rmk|*]
>Substracting $\mathbf{a}$ from itself yeilds the so called *zero*(*null*) vector, $$ \mathbf{a}-\mathbf{a}=\mathbf{0} $$
>
For all vectors the following holds:
>$$
\mathbf{a}+\mathbf{0}=\mathbf{a}$$


# 2. Multiplication by a Scalar:


