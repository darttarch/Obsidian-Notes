# Zermelo–Fraenkel Set Theory (ZF, ZFC)

The Zermelo–Fraenkel axioms form the standard foundation of modern mathematics.  
All mathematical objects are treated as sets, and all relationships are expressed through the membership relation $\in$.  
Axioms $1$–$8$ form **ZF**; adding the Axiom of Choice gives **ZFC**.

---

[[Axiom of Extensionality|$\large{\textbf{1. Axiom of Extensionality}}$]]  
Two sets are equal if and only if they have the same elements:
$$
\forall X \forall Y \big[ \forall z (z \in X \iff z \in Y) \implies X = Y \big].
$$

---

[[Axiom of Pairing|$\large{\textbf{2. Axiom of Pairing}}$]]  
For any sets $a$ and $b$, there exists a set $\{a,b\}$ whose only elements are $a$ and $b$:
$$
\forall a \forall b\, \exists X\, \forall z\, (z \in X \iff (z = a \lor z = b)).
$$

---

[[Axiom Schema of Separation|$\Large{\textbf{3. Axiom Schema of Separation}}$]]  
If $P(x,p)$ is a definable property with parameter $p$, then for any set $X$ there exists a subset
$$
Y = \{x \in X \mid P(x,p)\},
$$
containing exactly those elements of $X$ that satisfy $P$.

---

[[Axiom of Union|$\Large{\textbf{4. Axiom of Union}}$]]  
For every set $X$, there exists a set equal to the union of all its members:
$$
\forall X\, \exists Y\, \forall z\, (z \in Y \iff \exists A (A \in X \land z \in A)).
$$

---

[[Axiom of Power Set|$\Large{\textbf{5. Axiom of Power Set}}$]]  
For every set $X$, there exists a set $\mathcal{P}(X)$ consisting of all subsets of $X$:
$$
\forall X\, \exists Y\, \forall z\, (z \in Y \iff z \subseteq X).
$$

---

[[Axiom of Infinity|$\Large{\textbf{6. Axiom of Infinity}}$]]  
There exists a set that contains the empty set and is closed under the successor operation:
$$
\exists I\, [\,\varnothing \in I \,\land\, \forall x (x \in I \implies x \cup \{x\} \in I)\, ].
$$

---

[[Axiom Schema of Replacement|$\Large{\textbf{7. Axiom Schema of Replacement}}$]]  
If $F(x,y)$ defines a functional relation, then for every set $X$ there exists a set
$$
Y = \{\, y \mid \exists x \in X,\, F(x,y) \,\}.
$$
In other words, the image of a set under a definable function is also a set.

---

[[Axiom of Regularity (Foundation)|$\Large{\textbf{8. Axiom of Regularity}}$]]  
Every non-empty set $X$ contains an element $y$ such that $X$ and $y$ are disjoint:
$$
\forall X \big[ X \neq \varnothing \iff \exists y \in X\, (X \cap y = \emptyset) \big].
$$
This prevents infinitely descending membership chains.

---

[[Axiom of Choice|$\Large{\textbf{9. Axiom of Choice}}$]]  
For every family $X$ of non-empty sets, there exists a function $f$ with domain $X$ such that
$$
\forall A \in X,\, f(A) \in A.
$$
That is, every family of non-empty sets has a choice function.

---

> [!rmk|*]
> Axioms $1$–$8$ constitute the **Zermelo–Fraenkel** system (**ZF**).  
> Adding the Axiom of Choice yields **ZFC**.
> 