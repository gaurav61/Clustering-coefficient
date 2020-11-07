# Clustering coefficient of graphs

## Prerequisite
* CUDA
* C++

## Problem statement
  Our objective is to find the clustering coefficient of any given graph G(V,E). By definition, the clustering coefficient is a measure of the degree to which nodes in a graph tends to cluster together.<br />

  Clustering coefficient of a node of a graph is given by ratio of number of triangles enclosed by the node to number of wedges enclosed by the same. Here, a wedge is subgraph with 2 edges and 3 vertices, with above mentioned node as middle vertex. Average clustering coefficient of a graph G(V,E) is given by:-

  c(G) = 1/|V| x c(v) for all v∈V
  c(v) = δ(v)/T(v)
  T(v) = d(v)C2
  where,
  δ(v) = Number of triangles in the graph containing vertex v
  T(v) = Number of wedges containing v
  c(v) = Clustering coefficient of the vertex v.
  d(v) = Degree of vertex v