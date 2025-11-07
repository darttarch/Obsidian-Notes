>[!def|*]
>Let $X$ be a non empty set.
>A binary relation $\mathcal{R}$ is subsets of the Cartesian product $X\times X$ (i.e $\mathcal{R}\subset X^2$), its elements are the ordered pair $(x,y)$, but instead of writing $(x,y)\in \mathcal{R}$ we denoted them by $x\mathcal{R}y$.

#### Reflexivity:
A relation $\mathcal{R}$ on $X$ is *reflexive* if and only if, for all $x\in X$, we have $x\mathcal{R}x$, that is the diagonal
$$
\Delta_X:=\set{(x,x)|x\in X}
$$
is a contained in $\mathcal{R}$.

#### Transitivity:
A relation $\mathcal{R}$ on $X$ is *transitive* if an only if
$$
(x\mathcal{R}y)\land(y\mathcal{R}z)\implies(x\mathcal{R}z)
$$

#### Symmetry:
A relation is $\mathcal{R}$ on $X$ is *symmetric* if and only if 
$$
x\mathcal{R}y \implies y\mathcal{R}x
$$

If  a relation $\mathcal{R}$ is reflexive, transitive and symmetric, it's called an **equivalence relation**, denoted by $\Large \sim$. for each $x\in X$ the set
$$
[x]:=\set{y\in X: x\sim y}
$$
is called **equivalence class** of $x$, and each $y\in[x]$ is a **representative** of this class.
The set
$$
X/\sim:=\set{[x]:x\in X}
$$
"$X$ modulo $\sim$" is the set of all equivalence classes of $X$. $X/\sim$ is a subset of $\mathcal{P}(X)$.