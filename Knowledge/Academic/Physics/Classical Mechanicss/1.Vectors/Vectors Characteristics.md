# Characteristics of Vectors

A **[[Scalars and Vectors#^de794b|vector]]** is fully defined by four characteristics: **magnitude**, **direction**, **line of action**, and **sense**.

---

### 1. Magnitude  
> The magnitude (or length) of a vector represents *how much* of the quantity is present.  
> It corresponds to the numerical value or size of the vector, often denoted by $|\vec{A}|$ or simply $A$.

---

### 2. Direction  
> The direction indicates *where* the vector is pointing in space.  
> It is measured relative to a reference axis, plane, or coordinate system (for example, an angle with the $x$-axis).

---

### 3. Line of Action  
> The line of action is the infinite straight line along which the vector acts.  
> Every point on this line shares the same direction as the vector.  
> In mechanics, the position of this line often affects the physical result (for example, torque).

---

### 4. Sense  
> The sense specifies *which way* along the line of action the vector points.  
> For example, a vector directed east rather than west along the same horizontal line.

---

```tikz
\begin{document}
\begin{tikzpicture}[>=stealth,scale=1]

% Line of action (dashed)
\draw[dashed,gray] (0,0) -- (10,5) node[pos=0.95, above right, gray] {Line of Action};

% Vector
\draw[black,very thick,->] (2,1) -- (8,4) node[midway,above left] {$\vec{AB}$};

% Points
\node at (2,1) [below left] {$A$};
\node at (8,4) [above right] {$B$};

% Sense arrow label
\node at (5,2.5) [below right] {Sense $\rightarrow$};

\end{tikzpicture}
\end{document}
```
