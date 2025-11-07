
# Consequences of the Real Number Axioms

---

## 1. Consequences of the Addition Axioms

### 1.1 Uniqueness of Zero
There is only one zero in the set of real numbers $\mathbb{R}$.

**Proof Sketch:**  
If $0_1$ and $0_2$ are both zeros, then
$$
0_1 = 0_1 + 0_2 = 0_2 + 0_1 = 0_2.
$$

---

### 1.2 Existence and Uniqueness of Negatives
Each $x \in \mathbb{R}$ has a unique additive inverse $-x$.

**Proof Sketch:**  
If $x_1$ and $x_2$ are both negatives of $x$, then
$$
x_1 = x_1 + 0 = x_1 + (x + x_2) = (x_1 + x) + x_2 = 0 + x_2 = x_2.
$$

---

### 1.3 Solving Linear Equations
For $a, b \in \mathbb{R}$, the equation
$$
a + x = b
$$
has the unique solution
$$
x = b + (-a) = b - a.
$$

**Proof Sketch:**  
$$
(a + x = b) \iff ((x + a) + (-a) = b + (-a)) \iff (x + 0 = b + (-a)) \iff x = b + (-a).
$$

---

## 2. Consequences of the Multiplication Axioms

1. **Uniqueness of the multiplicative unit**  
   There exists exactly one $1 \in \mathbb{R}$ such that
   $$
   1 \cdot x = x \cdot 1 = x \quad \forall x \in \mathbb{R}.
   $$

2. **Uniqueness of the reciprocal**  
   For every $x \neq 0$, there exists a unique reciprocal $x^{-1}$ such that
   $$
   x \cdot x^{-1} = x^{-1} \cdot x = 1.
   $$

3. **Solving linear equations in multiplication**  
   For $a \in \mathbb{R} \setminus \{0\}$, the equation
   $$
   a \cdot x = b
   $$
   has a unique solution
   $$
   x = b \cdot a^{-1}.
   $$

---

## 3. Consequences of the Axiom Connecting Addition and Multiplication

1. **Multiplying by zero**  
   For any $x \in \mathbb{R}$,
   $$
   x \cdot 0 = 0 \cdot x = 0.
   $$

2. **Zero-product property**  
   For any $x, y \in \mathbb{R}$,
   $$
   x \cdot y = 0 \implies x = 0 \text{ or } y = 0.
   $$

3. **Negation via multiplication by -1**  
   For any $x \in \mathbb{R}$,
   $$
   -x = (-1) \cdot x.
   $$

4. **Double negative equals the original**  
   For any $x \in \mathbb{R}$,
   $$
   (-1) \cdot (-x) = x.
   $$

5. **Multiplying two negatives**  
   For any $x \in \mathbb{R}$,
   $$
   (-x) \cdot (-x) = x \cdot x.
   $$

---

## 4. Consequences of the Order Axioms

1. **Trichotomy law**  
   For any $x, y \in \mathbb{R}$, exactly one of the following holds:
   $$
   x < y, \quad x = y, \quad x > y.
   $$

2. **Transitivity of inequalities**  
   For any $x, y, z \in \mathbb{R}$,
   $$
   (x < y) \wedge (y \le z) \implies x < z,
   $$
   $$
   (x \le y) \wedge (y < z) \implies x < z.
   $$

---

## 5. Consequences of the Axioms Connecting Order with Addition and Multiplication

### 5.1 Addition preserves order
For any $x, y, z, w \in \mathbb{R}$,
$$
(x < y) \implies (x + z < y + z),
$$
$$
(x \le y) \wedge (z \le w) \implies (x + z \le y + w),
$$
$$
(x \le y) \wedge (z < w) \implies (x + z < y + w).
$$

### 5.2 Multiplication preserves/reverses order
For any $x, y, z \in \mathbb{R}$,
$$
(0 < x) \wedge (0 < y) \implies 0 < xy,
$$
$$
(x < 0) \wedge (y < 0) \implies 0 < xy,
$$
$$
(x < 0) \wedge (0 < y) \implies xy < 0,
$$
$$
(x < y) \wedge (0 < z) \implies xz < yz,
$$
$$
(x < y) \wedge (z < 0) \implies yz < xz.
$$

### 5.3 Negation and order
For any $x \in \mathbb{R}$,
$$
(0 < x) \implies (-x < 0).
$$

---
>[!rmk|*]
these properties are all derived from the axioms mentioned in [[Definition and The Axioms of the Set of Real Numbers]]

#refine 