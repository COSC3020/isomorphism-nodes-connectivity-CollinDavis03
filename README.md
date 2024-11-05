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
A bijection is established when each node in \( G_1 \) uniquely maps to a comparable node in \( G_2 \). Given that \( G_1 \) and \( G_2 \) contain the same number of nodes, we can define a mapping function \( f \) that creates this one-to-one correspondence between them.

Since \( G_1 \) is a fully connected graph, there exist nodes \( V_{1a} \) and \( V_{1b} \) that share an edge. For the mapping \( f \) to be valid in an isomorphic context, it must map every such edge in \( G_1 \) to a corresponding edge between the associated nodes in \( G_2 \). This edge mapping is feasible because \( f \) provides a bijection between all nodes in \( G_1 \) and \( G_2 \).

In conclusion, \( f \) consistently maps nodes and edges from \( G_1 \) to \( G_2 \) while retaining adjacency. Hence, any two fully connected graphs with the same number of nodes are isomorphic, as the mapping function \( f \) maintains the relations in \( G_1 \) such that \( (u, v) \in E_1 \) if and only if \( (f(u), f(v)) \in E_2 \).

## Sources 
I followed the slides provided to us. I also looked at vijaykodru repo to see the links he had because Nolan told me they were also very helpful. 

## Plagarism Statement
“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”

