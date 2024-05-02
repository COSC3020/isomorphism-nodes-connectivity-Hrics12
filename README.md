[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


Graphs $G_1=(V_1 , E_1)$ and $G_2=(V_2 , E_2)$, where $V_1$ and $V_2$ are the sets of vertices and $E_1$ and $E_2$ are the sets of edges in the graphs.
Since $G_1$ and $G_2$ are completely connected and have the same number of vertices so you can build a bijection by pairing the vertices in $V_1$ with the vertices in $V_2$. Because every pair of vertices is connected by an edge in both graphs the condition $(u,v) \in E_1$ iff $(f(u),f(v)) \in E_2$ is satisfied for all $u$ and $v$ in $V_1$
