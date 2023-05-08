Download Link: https://assignmentchef.com/product/solved-webscience-assignment2-top-k-most-probable-triangles-in-uncertain-graphs
<br>
In this project, you will work with graph data. Given a potentially large probabilistic network and an integer k, you must design and implement a solution to discover the top-k most probable triangles. A probabilistic network is a network where edges are annotated with existential probabilities. This means that an edge <em>e</em> is present with a probability <em>p</em>(<em>e</em>). Therefore, if a triangle is formed among the edges <em>a</em>, <em>b</em> and <em>c</em>, then the existential probability of the triangle is <em>p</em>(<em>a</em>) * <em>p</em>(<em>b</em>) * <em>p</em>(<em>c</em>). An example is given in Figure 1.

<h1>Datasets</h1>

You are free to use any probabilistic graph available. A small dataset will be given. However, since not many real-life probabilistic networks are publicly available, you may work use synthetic datasets as follows: you may take any undirected network and simply assign probabilities to the edges by using a probability distribution such as uniform, normal, power-law, etc. Two excellent repositories for graph data are:

<a href="http://snap.stanford.edu/data/index.html">http://snap.stanford.edu/data/index.html </a><a href="http://networkrepository.com/">http://networkrepository.com/</a>

<h1>Requirements</h1>

Given a probabilistic graph you should implement a scalable and efficient algorithm to detect the <em>k</em> most probable triangles. Your algorithm must be implemented in Scala or Python and you should use Apache Spark. Note that the parameter <em>k</em> is user-defined and must be given as an input to the algorithm. Please note that in case you want to use a graph library, in Scala you may use GraphX or GraphFrames. However, if you want to use Python, then only the GraphFrames library is supported. More information about the GraphFrames library may be found in the following link:

<a href="https://graphframes.github.io/graphframes/docs/_site/index.html">http://graphframes.github.io/graphframes/docs/_site/index.html</a>

The graph will be given in edge-list format. Each line contains three numbers. The first two correspond to the edge and the third one corresponds to the probability of the edge. Please note, that it is not mandatory to work with a graph library. In case you have other ideas to work with such as using a sparse adjacency matrix or adjacency lists you are free to use them. However, please take care of the scalability issue, since your solution must be able to scale for large networks.


