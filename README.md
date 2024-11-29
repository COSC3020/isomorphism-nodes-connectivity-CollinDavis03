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
**The first step is to complete the graph definition. This means that in a complete graph with n vertices, every pair of vertices is connected by an edge.**

This will give us the equation for edges. 

$|E|$ = (n over 2) = $(n(n-1))/2$

**Step 2: Defining a Mapping Function.** 

Since $G_{1}$ and $G_{2}$ have the same number of vertices (n), we can define the bijection ($f : V_{1} \rightarrow V_{2}$) such that each vertex in $G_{1}$ is uniquely paired with a vertex in $G_{2}$

**Step 3: Verify that Adjacency relationships are Preserved.**

For a complete graph to exist, every vertex in $G_{1}$ is connected to every other vertex. Therefore, for any pairs of vertices $(u,v)
\in V_1$:
        $(u,v) \in E_1 \rightarrow (f(u), f(v)) \in E_2$
Which similarly because f is bijective, for every pair $(f(u), f(v)) \in E_24 there is going to be a corresponding $(u, v) \in E_1$ 

This will make it so adjacency relationships are preserved under the mapping of f. 

**Step 4: Conclude Isomorphism** 

Since f is a bijection, f preserves adjacency relationships, and Both $G_1$ and $G_2$ have the same number of edges and vertices. 

We can conclude that $G_1$ and $G_2$ are isomorphic. 

## Sources 
I followed the slides provided to us. I also looked at vijaykodru repo to see the links he had because Nolan told me they were also very helpful. 

## Plagarism Statement
“I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.”

