# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer 
There is a bijection that occurs in $G_{1}$ when every node can mapped to a comparable node in $G_{2}$. Since both of the graphs have the same number of nodes then there must be something in function _f_ that can map a node from $G_{1}$ that can be mapped and correspond with a node in $G_{2}$. 

With $G_{1}$ being fully connected, there have to be vertices in $V_{1a}$ and $V_{1b}$ in which an edge would connect them. Using the logic we have, there must be something in function _f_ such that can map the aforementioned edge to the corresponding nodes in $G_{2}$. The only reason that this is possible is because of the bijection of the nodes from $G_{1}$ and $G_{2}$. Then also the function that maps $G_{1}$ to $G_{2}$. 

$\therefore$ the function works to map every node and edge from $G_{1}$ to $G_{2}$ while preserving the relations. We can say that every fully connected graph with the same number of nodes is isomorphic because of the mapping function. Which we can use to preserve the relations from $G_{1}$ that satisfies $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Sources 
I followed the slides provided to us. I also looked at vijaykodru repo to see the links he had because Nolan told me they were also very helpful. 

## Plagarism Statement
“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”

