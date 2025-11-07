
> [!def|*]
> A set $\mathbb{R}$ is called the set of **real numbers**, and its elements are real numbers, if the following list of conditions holds. This list is called the **axiom system** of the real numbers.

---

$\LARGE\textbf{(I)}$ **Axioms for Addition**

An operation  
$$
\huge +:\mathbb{R} \times \mathbb{R} \longrightarrow \mathbb{R}
$$

$1_+.$ **Existence of a neutral element:**  
There exists a neutral (identity) element $0$ (called *zero*) such that  
$$
\huge x + 0 = 0 + x = x
$$

$2_+.$ **Existence of an inverse element:**  
For every element $x \in \mathbb{R}$ there exists an element $-x \in \mathbb{R}$ (called the *negative* of $x$) such that  
$$
\huge x + (-x) = (-x) + x = 0
$$

$3_+.$ **Associativity:**  
$$
\huge x + (y + z) = (x + y) + z
$$

$4_+.$ **Commutativity:**  
$$
\huge x + y = y + x
$$

> [!rmk]
> If an operation is defined on a set $G$ satisfying axioms $1_+$, $2_+$, and $3_+$, we say that a **group structure** is defined on $G$, or simply that $G$ is a **group**.  
> If the operation is called addition, the group is called an **additive group**.  
> If it is also known that the operation is commutative (axiom $4_+$), the group is called **commutative** or **Abelian**.  
>  
> Thus, axioms $1_+$–$4_+$ assert that $\mathbb{R}$ is an **additive Abelian group**.

---

$\LARGE\textbf{(II)}$ **Axioms for Multiplication**

An operation  
$$
\huge \bullet : \mathbb{R} \times \mathbb{R} \longrightarrow \mathbb{R}
$$

$1_\bullet.$ **Existence of a neutral element:**  
There exists a neutral (identity) element $1$ (called *one*) such that  
$$
\huge x \cdot 1 = 1 \cdot x = x
$$

$2_\bullet.$ **Existence of an inverse element:**  
For every $x \in \mathbb{R}^* = \mathbb{R} \setminus \{0\}$ there exists an element $x^{-1} \in \mathbb{R}^*$ (called the *inverse* of $x$) such that  
$$
\huge x \cdot x^{-1} = x^{-1} \cdot x = 1
$$

$3_\bullet.$ **Associativity:**  
$$
\huge x \cdot (y \cdot z) = (x \cdot y) \cdot z
$$

$4_\bullet.$ **Commutativity:**  
$$
\huge x \cdot y = y \cdot x
$$

> [!rmk]
> With respect to multiplication, the set $\mathbb{R}^* = \mathbb{R} \setminus \{0\}$ is a **multiplicative Abelian group**.

---

$\LARGE\textbf{(I,II)}$ **The Connection Between Addition and Multiplication**

Multiplication is **distributive** with respect to addition:  
$$
\huge x \cdot (y + z) = x \cdot y + x \cdot z
$$

> [!rmk]
> By the commutativity of multiplication, the distributive law also holds in reversed order:  
> $$(y + z) \cdot x = y \cdot x + z \cdot x.$$  
>  
> If two operations are defined on a set $G$ satisfying the above axioms, we say that $G$ is a **field**.

---

$\LARGE\textbf{(III)}$ **Order Axioms**

Between elements of $\mathbb{R}$ there exists a relation $\leq$ such that for all $x, y \in \mathbb{R}$, one can determine whether $x \leq y$ or not.  
The following conditions must hold:

$0_\le.$ **Reflexivity:**  
$\forall x \in \mathbb{R}, \quad (x \leq x)$

$1_\le.$ **Antisymmetry:**  
$$(x \leq y) \land (y \leq x) \Rightarrow (x = y)$$

$2_\le.$ **Transitivity:**  
$$(x \leq y) \land (y \leq z) \Rightarrow (x \leq z)$$

$3_\le.$ **Totality (Trichotomy):**  
$$\forall x, y \in \mathbb{R}, \ (x \leq y) \lor (y \leq x)$$

The relation $\leq$ on $\mathbb{R}$ is called an **inequality**.

> [!rmk]
> A set with a relation satisfying axioms $0_\le$, $1_\le$, and $2_\le$ is called **partially ordered**.  
> If, in addition, axiom $3_\le$ holds, the set is **linearly ordered**.  
>  
> Thus, the set $\mathbb{R}$ is **linearly ordered** by the relation of inequality.

---

$\LARGE\textbf{(I,III)}$ **The Connection Between Addition and Order**

For all $x, y, z \in \mathbb{R}$:  
$$
(x \leq y) \Rightarrow (x + z \leq y + z)
$$

---

$\LARGE\textbf{(II,III)}$ **The Connection Between Multiplication and Order**

For all $x, y \in \mathbb{R}$:  
$$
(0 \leq x) \land (0 \leq y) \Rightarrow (0 \leq x \cdot y)
$$

---

> [!rmk]
> A system satisfying Axioms (I), (II), and (III) is called an **ordered field**.

---

$\LARGE\textbf{(IV)}$ **Axiom of Completeness**

> [!axm|*]
> If $X$ and $Y$ are nonempty subsets of $\mathbb{R}$ such that for all $x \in X$ and $y \in Y$ we have $x \leq y$,  
> then there exists $c \in \mathbb{R}$ such that  
> $$x \leq c \leq y \quad \text{for all } x \in X, \ y \in Y.$$

>[!rmk]
>The previous axioms (I–III) define an **ordered field**.  
The addition of the completeness axiom (IV) uniquely characterizes the field of **real numbers**.  
 >
In particular, the rational numbers $\mathbb{Q}$ form an ordered field, but not a complete one — this is what distinguishes $\mathbb{R}$.
