Here are some notes on definitions and notation that Godsil and Royle use throughout the book.

<b><em> Definition. </em></b> A <em> graph </em> $X$ consists of a <em>vertex set</em> $V(X)$ and an <em>edge set</em> $E(X)$. Vertices will be denoted by single letters ($a, b, c, x, y, z$, you get the point), while edges will be denoted by a pair of letters representing the vertices the edge connects. This pair will be written as a product for brevity, in opposition to the standard notation of set brackets.

It's overly verbose and annoying to speak of "vertices connected by an edge", or "an edge that includes the given vertex," so graph theorists came up with some additional terminology to make graph theory and the English language more compatible.

<b><em>Definition.</b></em> If $xy$ is an edge, then we say that the vertex $x$ is a <em>neighbor</em> of the vertex $y$, or equivalently that $x$ is <em>adjacent</em> to $y$. This will be denoted by $x \sim y$.

<b><em>Definition.</em></b> The <em>valency</em> of a vertex is its total number of neighbors. 

Valency is also often referred to as degree, but this is yet another over-used word in mathematics. Godsil and Royle use the term valency, so I will do this also.

<b><em>Definition.</em></b> A vertex is <em>incident</em> with an edge if it is one of the two vertices of the edge.

We'd like to be able to speak about the "total opposite" of some given graph. We then need a notion of complements.

<b><em>Definition.</em></b> Let $X$ be a graph. The <em>complement</em> of $X$, denoted $\overline{X}$, is the graph with vertex set $V(X)$ and edge set $\{uv: u, v \in V(X), uv \not\in E(X) \}$.
