Let $f:X\to Y$ be a [[Functions|function]].


---

Injection:

$f$ is injective (one-to-one) if distinct elements in the domain map to distinct elements in the codomain:

$$a \neq b \implies f(a) \neq f(b) $$  
Or equivalently:  
$$ f(a)=f(b) \implies a=b $$  
> Note: Some elements of the codomain may remain unmapped; this is allowed in injective functions.  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
% Domain ellipse  
\draw[thick] (0,0) ellipse (1.2cm and 2cm);  
  
% Codomain ellipse  
\draw[thick] (5,0) ellipse (1.2cm and 2cm);  
  
% Domain nodes  
\foreach \i/\y in {1/1.0, 2/0.33, 3/-0.33, 4/-1.0} {  
    \node[fill=black, circle, minimum size=2pt, label=left:$a_\i$] (a\i) at (0,\y) {};  
}  
  
% Codomain nodes (5 points for consistency)  
\foreach \i/\y in {1/1.0, 2/0.5, 3/0.0, 4/-0.5, 5/-1.0} {  
    \node[fill=black, circle, minimum size=2pt, label=right:$b_\i$] (b\i) at (5,\y) {};  
}  
  
% Injective arrows  
\draw[->, thick] (a1) -- (b2);  
\draw[->, thick] (a2) -- (b4);  
\draw[->, thick] (a3) -- (b1);  
\draw[->, thick] (a4) -- (b5);  
  
\end{tikzpicture}  
\end{document}  
```  
  
  
---  
  
Surjection:  
  
$f$ is surjective (onto) if every element of the codomain is an image of some element in the domain:  
  
$$\forall\ y \in Y, \ \exists\ x \in X : f(x) = y$$  
```tikz  
\begin{document}  
\begin{tikzpicture}  
% Domain ellipse  
\draw[thick] (0,0) ellipse (1.2cm and 2cm);  
  
% Codomain ellipse  
\draw[thick] (5,0) ellipse (1.2cm and 2cm);  
  
% Domain nodes  
\foreach \i/\y in {1/1.0, 2/0.33, 3/-0.33, 4/-1.0} {  
    \node[fill=black, circle, minimum size=2pt, label=left:$a_\i$] (a\i) at (0,\y) {};  
}  
  
% Codomain nodes (5 points for consistency)  
\foreach \i/\y in {1/1.0, 2/0.5, 3/0.0, 4/-0.5, 5/-1.0} {  
    \node[fill=black, circle, minimum size=2pt, label=right:$b_\i$] (b\i) at (5,\y) {};  
}  
  
% Surjective arrows (all codomain elements covered)  
\draw[->, thick] (a1) -- (b1);  
\draw[->, thick] (a2) -- (b2);  
\draw[->, thick] (a3) -- (b3);  
\draw[->, thick] (a4) -- (b4);  
% Extra mapping to show multiple domain elements can map to same codomain  
\draw[->, thick] (a2) -- (b5);  
  
\end{tikzpicture}  
\end{document}  
```  
  
  
---  
  
Bijection:  
  
$f$ is bijective if it is both injective and surjective (one-to-one and onto).  
  
> Note: Each domain element maps to a unique codomain element, and every codomain element is covered.  
  
  
```tikz  
\begin{document}  
\begin{tikzpicture}  
% Domain ellipse  
\draw[thick] (0,0) ellipse (1.2cm and 2cm);  
  
% Codomain ellipse  
\draw[thick] (5,0) ellipse (1.2cm and 2cm);  
  
% Domain nodes  
\foreach \i/\y in {1/1.0, 2/0.5, 3/0.0, 4/-0.5, 5/-1.0} {  
    \node[fill=black, circle, minimum size=2pt, label=left:$a_\i$] (a\i) at (0,\y) {};  
}  
  
% Codomain nodes  
\foreach \i/\y in {1/1.0, 2/0.5, 3/0.0, 4/-0.5, 5/-1.0} {  
    \node[fill=black, circle, minimum size=2pt, label=right:$b_\i$] (b\i) at (5,\y) {};  
}  
  
% Bijection arrows  
\foreach \i in {1,2,3,4,5} {  
    \draw[->, thick] (a\i) -- (b\i);  
}  
  
\end{tikzpicture}  
\end{document}  
```