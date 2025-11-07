
## Properties of Propositional Logic

### 1. De Morgan's Law
$$
\begin{align}
\lnot (P \land Q) &\equiv \lnot P \lor \lnot Q \\
\lnot (P \lor Q) &\equiv \lnot P \land \lnot Q
\end{align}
$$

**Example:**  
- P: It is raining  
- Q: I have an umbrella  

$$\lnot (P \land Q) \equiv \lnot P \lor \lnot Q$$  
“Not raining **and** having an umbrella” is equivalent to “It is not raining **or** I don’t have an umbrella.”

---

### 2. Commutative Law
$$
\begin{align}
P \land Q &\equiv Q \land P \\
P \lor Q &\equiv Q \lor P
\end{align}
$$

**Example:**  
- P: I will study  
- Q: I will exercise  

$$P \land Q \equiv Q \land P$$  
Order doesn’t matter: “Study and exercise” is the same as “Exercise and study.”

---

### 3. Associative Law
$$
\begin{align}
P \land (Q \land R) &\equiv (P \land Q) \land R \\
P \lor (Q \lor R) &\equiv (P \lor Q) \lor R
\end{align}
$$

**Example:**  
- P: I eat breakfast  
- Q: I go to work  
- R: I exercise  

Grouping doesn’t matter:  
$$P \land (Q \land R) \equiv (P \land Q) \land R$$

---

### 4. Idempotent Law
$$
\begin{align}
P \land P &\equiv P \\
P \lor P &\equiv P
\end{align}
$$

**Example:**  
- P: I am happy  

$$P \land P \equiv P$$  
Repeating the same statement does not change its truth.

---

### 5. Distributive Law
$$
\begin{align}
P \land (Q \lor R) &\equiv (P \land Q) \lor (P \land R) \\
P \lor (Q \land R) &\equiv (P \lor Q) \land (P \lor R)
\end{align}
$$

**Example:**  
- P: I study  
- Q: I sleep early  
- R: I exercise  

Distributing P over Q or R:  
$$P \land (Q \lor R) \equiv (P \land Q) \lor (P \land R)$$

---

### 6. Absorption Law
$$
\begin{align}
P \land (P \lor Q) &\equiv P \\
P \lor (P \land Q) &\equiv P
\end{align}
$$

**Example:**  
- P: I will attend class  
- Q: I will do homework  

$$P \land (P \lor Q) \equiv P$$  
Adding extra conditions doesn’t change the main statement.

---

### 7. Double Negation Law
$$
\lnot (\lnot P) \equiv P
$$

**Example:**  
- P: I am awake  

Negating twice brings you back:  
$$\lnot (\lnot P) \equiv P$$