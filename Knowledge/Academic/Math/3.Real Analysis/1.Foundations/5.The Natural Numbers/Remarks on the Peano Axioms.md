## 1. The Successor Function

For $n \in \mathbb{N}$, the element $\nu(n)$ is called the **successor** of $n$, and $\nu$ is called the **successor function**.

The element $0$ is the only natural number that is **not** the successor of any number.  
Thus, the successor function  
$$
\nu : \mathbb{N} \to \mathbb{N}^\times := \mathbb{N} \setminus \{0\}
$$  
is **surjective**.

Moreover, from Peano's Axiom $(N_0)$—which ensures $0$ is not a successor—and the injectivity of $\nu$, we obtain that  
$$
\nu : \mathbb{N} \to \mathbb{N}^\times
$$  
is a **bijection**.

### Proof

$$
N := \{ n \in \mathbb{N} \; ; \; \exists n' \in \mathbb{N} : \nu(n') = n \} \cup \{0\}
     = \operatorname{im}(\nu) \cup \{0\}.
$$

By definition, $\operatorname{im}(\nu) = \mathbb{N}^\times$, so every natural number except $0$ is a successor.

---

## 2. Notational Convention

Instead of repeatedly writing  
$$
0, \; \nu(0), \; \nu(\nu(0)), \; \nu(\nu(\nu(0))), \; \dots
$$  
we usually denote them simply as  
$$
0, 1, 2, 3, \dots
$$  
where $1 := \nu(0)$, $2 := \nu(1)$, and so on.

---

## 3. The Induction Axiom $(N_1)$

The Peano Axiom $(N_1)$ expresses the **Principle of Mathematical Induction**:

> If a property $P(n)$ satisfies:  
> 1. $P(0)$ is true, and  
> 2. For all $n \in \mathbb{N}$, $P(n) \Rightarrow P(\nu(n))$,  
>
> then $P(n)$ is true for all $n \in \mathbb{N}$.

Equivalently, every subset $S \subseteq \mathbb{N}$ that contains $0$ and is closed under $\nu$ must be all of $\mathbb{N}$.

---