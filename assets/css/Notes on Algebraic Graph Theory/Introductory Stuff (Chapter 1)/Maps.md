Like any discipline of mathematics, graph theory has maps. We need to define these fundamental notions of structure-preserving maps for graph theory. Luckily, or perhaps confusingly, the terminology for these maps is the same in graph theory as in algebra.

<b><em>Definition.</em></b> Let $X, Y$ be graphs. A <em>graph homomorphism</em> $\varphi: X \rightarrow Y$ is a function that preserves adjacency of vertices. In other words, if $uv \in E(X)$, then $\varphi(u)\varphi(v) \in E(Y)$.

Let's clarify my (slight) abuse of notation here. Above, I wrote $\varphi: X \rightarrow Y$, and then later wrote $\varphi(u)$ for $u \in V(X)$. A homomorphism of graphs is truly a function defined on the vertex sets of the graphs that is interpreted in the wider structure of their edge sets. This is common graph theory notation, which is why I adopted it here. 

Now let's compare the above definition with the following.

<b><em>Definition.</em></b> Let $X, Y$ be graphs. A <em>graph isomorphism</em> $\varphi: X \rightarrow Y$ is an invertible function that preserves adjacency of vertices in both directions. In other words, $uv \in E(X)$ if and only if $\varphi(u)\varphi(v) \in E(Y)$.

We changed two things about our earlier definition.
1. We required $\varphi$ to be invertible.
2. We strengthened the adjacency condition to be an if and only if statement.

These structure-preserving maps help us to recognize when two graphs are secretly the same.

<b><em>Definition.</em></b> Two graphs $X$ and $Y$ are <em>isomorphic</em> if there is some graph isomorphism $\varphi: X \rightarrow Y$. To denote this, we write $X \cong Y$.

