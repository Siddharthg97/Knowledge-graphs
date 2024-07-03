## What is a knowledge graph?
A knowledge graph, also known as a semantic network, represents a network of real-world entities—such as objects, events, situations or concepts—and illustrates the relationship between them. This information is usually stored in a graph database and visualized as a graph structure, prompting the term knowledge “graph.”

A knowledge graph is made up of three main components: nodes, edges, and labels. Any object, place, or person can be a node. An edge defines the relationship between the nodes. For example, a node could be a client, like IBM, and an agency like, Ogilvy. An edge would be categorize the relationship as a customer relationship between IBM and Ogilvy. <br />
Nodes and relationships will be annotated with their **types** and described by a collection of attributes that characterize them. For instance, a node representing a city will typically have a **property indicating its current population or its geographical location**, a person would have a date of birth, a name, and so on.


https://www.ibm.com/topics/knowledge-graph  <br />
https://github.com/Siddharthg97/Knowledge-graphs/blob/main/Images/img1.JPG <br />https://neo4j.com/blog/what-is-knowledge-graph/ <br />

## Present application of KG
There are a number of popular, consumer-facing knowledge graphs, which are setting user expectations for search systems across enterprises. Some of these knowledge graphs include:<br />

1)DBPedia and Wikidata are two different knowledge graphs for data on Wikipedia.org. DBPedia is comprised of data from the infoboxes of Wikipedia while Wikidata focuses on secondary and tertiary objects. Both typically publish in a RDF format.  <br />
2)Google Knowledge Graph is represented through Google Search Engine Results Pages (SERPs), serving information based on what people search. This knowledge graph is comprised of over 500 million objects, sourcing data from Freebase, Wikipedia, the CIA World Factbook, and more. <br />
However, knowledge graphs also have applications in other industries, such as:

3)Retail: Knowledge graphs have been for up-sell and cross-sell strategies, recommending products based on individual purchase behavior and popular purchase trends across demographic groups. <br />
Entertainment: Knowledge graphs are also leveraged for artificial intelligence (AI) based recommendation engines for content platforms, like Netflix, SEO, or social media. Based on click and other online engagement behaviors, these providers recommend new content for users to read or watch.<br />
4)Finance: This technology has also been used for know-your-customer (KYC) and anti-money laundering initiatives within the finance industry. They assist in financial crime prevention and investigation, allowing banking institutions to understand the flow of money across their clientele and identify noncompliant customers.<br />
5)Healthcare: Knowledge graphs are also benefiting the healthcare industry by organizing and categorizing relationships within medical research. This information assists providers by validating diagnoses and identifying treatment plans based on individual needs. 

## Graph Algorithms using NEo4j library
Refer the link - https://neo4j.com/docs/graph-data-science/current/algorithms/ <br />
Graph algorithms are used to compute metrics for graphs, nodes, or relationships. < br/>
They can provide insights on relevant entities in the graph (centralities, ranking), or inherent structures like communities (community-detection, graph-partitioning, clustering).
Many graph algorithms are iterative approaches that frequently traverse the graph for the computation using random walks, breadth-first or depth-first searches, or pattern matching.
Due to the exponential growth of possible paths with increasing distance, many of the approaches also have high algorithmic complexity.
Fortunately, optimized algorithms exist that utilize certain structures of the graph, memoize already explored parts, and parallelize operations. Whenever possible, we’ve applied these optimizations.

The Neo4j Graph Data Science library contains a large number of algorithms, which are detailed in the Algorithms chapter. <br />

https://neo4j.com/docs/graph-data-science/current/machine-learning/machine-learning/

## Development of Knowledge graphs in python & their purpose
Refer link for KG python development- https://lopezyse.medium.com/knowledge-graphs-from-scratch-with-python-f3c2a05914cc <br />
For purpose we use - <br />
Next, we create a NetworkX graph (G) to represent the KG. Each row in the DataFrame (df) corresponds to a triple (head, relation, tail) in the KG. The add_edge function adds edges between the head and tail entities, with the relation as a label.<br />
refer link - https://lopezyse.medium.com/knowledge-graphs-from-scratch-with-python-f3c2a05914cc

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

