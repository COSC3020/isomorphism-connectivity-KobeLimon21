# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

We can use two graphs here, our first graph with V: (A,B,C,D) and E: ((A,B),(B,D),(D,C)). Our second graph is V: (W,X,Y,Z) and E: ((W,X),(X,Z),(Y,Z)). 

We can map these vertices to each other:

A -> W 

B -> X

C -> Y 

D -> Z 

This is one to one, as each vertex has one specific vertex it is mapped to being that each one is unique. It is also onto, because each vertex in the second graph has a corresponding vertex in the first graph. There fore by the definition of bijection, there is a bijection here. 

This shows that both of these graphs are isomorphic despite not being completely connected as the edges (A,C) and (W,Y) do not exist here. Therefore this shows that two graphs can be isomorphic without being completely connected.





sources:
ta ali - helped to explain how to go about the mathemetical aspect of isomorphism. 
