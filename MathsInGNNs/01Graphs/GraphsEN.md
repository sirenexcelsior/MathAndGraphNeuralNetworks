# Graphs

*Definition 1.1* A graph is a data structure that can usually be represented as a binary group $G=(V,E)$, it consists of a non-empty set $V$ and a set $E$ of edges, each of which has one or two vertices connected to it. If these two sets are infinite, we call the graph infinite, but in general we only discuss finite graphs.

In particular, tree structures and chain structures are special graph structures.

## Directed vs. Undirected Graphs

*Definition 1.2* **Directed graphs** are a special case of graphs, which are those graphs whose edges are directed, where an edge can usually be represented as an ordered pair $(u, v)$, i.e., pointing from node $u$ to node $v$. And **undirected graphs** are those graphs whose edges have no directionality.

## Bipartite Graphs

*Definition 1.3* Bipartite Graphs is a graph whose nodes can be divided into two disjoint sets $U_1$ and $U_2$ such that every link connects a node in $U_1$ to one in $U_2$; that is, $U_1$ and $U_2$ are independent sets.

$$G= \\{ (V,E)|V=U_1\cap U_2,U_1\cap  U_2= \varnothing \\} $$

### Folded/Projected Bipartite Graphs
