## What is a knowledge graph?
A knowledge graph, also known as a semantic network, represents a network of real-world entities—such as objects, events, situations or concepts—and illustrates the relationship between them. This information is usually stored in a graph database and visualized as a graph structure, prompting the term knowledge “graph.”

A knowledge graph is made up of three main components: nodes, edges, and labels. Any object, place, or person can be a node. An edge defines the relationship between the nodes. For example, a node could be a client, like IBM, and an agency like, Ogilvy. An edge would be categorize the relationship as a customer relationship between IBM and Ogilvy.

https://www.ibm.com/topics/knowledge-graph  <br />
https://github.com/Siddharthg97/Knowledge-graphs/blob/main/Images/img1.JPG <br />https://neo4j.com/blog/what-is-knowledge-graph/ <br />

## Graph Algorithms using NEo4j library
Refer the link - https://neo4j.com/docs/graph-data-science/current/algorithms/ <br />
Graph algorithms are used to compute metrics for graphs, nodes, or relationships. < br/>
They can provide insights on relevant entities in the graph (centralities, ranking), or inherent structures like communities (community-detection, graph-partitioning, clustering).
Many graph algorithms are iterative approaches that frequently traverse the graph for the computation using random walks, breadth-first or depth-first searches, or pattern matching.
Due to the exponential growth of possible paths with increasing distance, many of the approaches also have high algorithmic complexity.
Fortunately, optimized algorithms exist that utilize certain structures of the graph, memoize already explored parts, and parallelize operations. Whenever possible, we’ve applied these optimizations.

The Neo4j Graph Data Science library contains a large number of algorithms, which are detailed in the Algorithms chapter. <br />

https://neo4j.com/docs/graph-data-science/current/machine-learning/machine-learning/

## Knowledge graphs development in python & their purpose
Refer link for KG python development- https://lopezyse.medium.com/knowledge-graphs-from-scratch-with-python-f3c2a05914cc <br />

### Purpose
Refer
1)Once knowldge graph is developed it can be used to find the shortest path b/w two nodes.
2) Can be used to determine node importance
#### Create Embeddings
Graph embeddings are mathematical representations of nodes or edges in a graph in a continuous vector space. These embeddings capture the structural and relational information of the graph, allowing us to perform various analyses, such as node similarity calculation and visualization in lower-dimensional space.< br />

Next, we’ll use the node2vec algorithm, which learns embeddings by performing random walks on the graph and optimizing to preserve the local neighborhood structure of nodes. <br />

1) Refer T-SNE for dimensionality reduction for data visualization of nodes <br />
2) Clustering of nodes using several algorithms like - KMeans, DBSCAN <br />
https://lopezyse.medium.com/knowledge-graphs-from-scratch-with-python-f3c2a05914cc

