
Mathematical logic studies **statements** and their **truth values**, along with rules for combining and reasoning about them.

**Statements** (or *propositions*) are sentences that have exactly **two possibilities**: they are either *true* $(T)$ or *false* $(F)$.

---

# Propositional Logic

### Negation (NOT)
The negation of a statement $P$, written $\lnot P$ (read "not $P$"), reverses its truth value:
- If $P$ is true, $\lnot P$ is false.
- If $P$ is false, $\lnot P$ is true.

$$
\begin{array}{c|c}
P & \neg P \\
\hline
T & F \\
F & T \\
\end{array}
$$

---

### Conjunction (AND)
The conjunction $P \land Q$ (read "$P$ and $Q$") is **true only if both $P$ and $Q$ are true**. Otherwise, it is false.

$$
\begin{array}{c|c|c}
P & Q & P \land Q \\
\hline
T & T & T \\
T & F & F \\
F & T & F \\
F & F & F \\
\end{array}
$$

---

### Disjunction (OR)
The disjunction $P \lor Q$ (read "$P$ or $Q$") is **true if at least one of $P$ or $Q$ is true**. It is false only when both are false.

$$
\begin{array}{c|c|c}
P & Q & P \lor Q \\
\hline
T & T & T \\
T & F & T \\
F & T & T \\
F & F & F \\
\end{array}
$$

---

### Implication (IF…THEN)
The implication $P \implies Q$ (read "if $P$, then $Q$") is **false only when $P$ is true and $Q$ is false**; otherwise it is true.

$$
\begin{array}{c|c|c}
P & Q & P \implies Q \\
\hline
T & T & T \\
T & F & F \\
F & T & T \\
F & F & T \\
\end{array}
$$

> **Intuition:** If the premise ($P$) is false, the statement doesn’t make a claim, so the implication is automatically true.

---

### Equivalence (IF AND ONLY IF)
The equivalence $P \iff Q$ (read "$P$ if and only if $Q$") is **true when both statements have the same truth value**, either both true or both false.

$$
\begin{array}{c|c|c}
P & Q & P \iff Q \\
\hline
T & T & T \\
T & F & F \\
F & T & F \\
F & F & T \\
\end{array}
$$

> **Tip:** $P \iff Q$ can also be written as $(P \implies Q) \land (Q \implies P)$.