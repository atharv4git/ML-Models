# Research papers 📄
Contains:
1. <big>Clustering algoritms, their improved versions and validation methods.</big>
    1. __K-Means Clustering:__
        >k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.
        >The problem is computationally difficult (NP-hard); however, efficient heuristic algorithms converge quickly to a local optimum. These are usually similar to the expectation-maximization algorithm for mixtures of Gaussian distributions via an iterative refinement approach employed by both k-means and Gaussian mixture modeling. They both use cluster centers to model the data; however, k-means clustering tends to find clusters of comparable spatial extent, while the Gaussian mixture model allows clusters to have different shapes.
        >The unsupervised k-means algorithm has a loose relationship to the k-nearest neighbor classifier, a popular supervised machine learning technique for classification that is often confused with k-means due to the name. Applying the 1-nearest neighbor classifier to the cluster centers obtained by k-means classifies new data into the existing clusters. This is known as nearest centroid classifier or Rocchio algorithm.
        <center>

        ![](kmeans.gif)

        <small>source: https://dashee87.github.io/images/kmeans.gif</small>
        </center>

    2. __Heirarchical Clustering:__
        >In data mining and statistics, hierarchical clustering (also called hierarchical cluster analysis or HCA) is a method of cluster analysis that seeks to build a hierarchy of clusters. Strategies for hierarchical clustering generally fall into two categories:
        >Agglomerative: This is a "bottom-up" approach: Each observation starts in its own cluster, and pairs of clusters are merged as one moves up the hierarchy.
Divisive: This is a "top-down" approach: All observations start in one cluster, and splits are performed recursively as one moves down the hierarchy.
In general, the merges and splits are determined in a greedy manner. The results of hierarchical clustering[1] are usually presented in a dendrogram.
The standard algorithm for hierarchical agglomerative clustering (HAC) has a time complexity of ${\displaystyle {\mathcal {O}}(n^{3})}$ and requires ${\displaystyle \Omega (n^{2})}$ memory, which makes it too slow for even medium data sets. However, for some special cases, optimal efficient agglomerative methods (of complexity ${\displaystyle {\mathcal {O}}(n^{2})}$ are known: SLINK[2] for single-linkage and CLINK[3] for complete-linkage clustering. With a heap, the runtime of the general case can be reduced to ${\displaystyle {\mathcal {O}}(n^{2}\log n)}$, an improvement on the aforementioned bound of ${\displaystyle {\mathcal {O}}(n^{3})}$, at the cost of further increasing the memory requirements. In many cases, the memory overheads of this approach are too large to make it practically usable.
Except for the special case of single-linkage, none of the algorithms (except exhaustive search in ${\displaystyle {\mathcal {O}}(2^{n})}$) can be guaranteed to find the optimum solution.
Divisive clustering with an exhaustive search is ${\displaystyle {\mathcal {O}}(2^{n})}$, but it is common to use faster heuristics to choose splits, such as k-means.
Hierarchical clustering has the distinct advantage that any valid measure of distance can be used. In fact, the observations themselves are not required: all that is used is a matrix of distances.

        <center>

        ![](hierarch.gif)

        <small>source: https://dashee87.github.io/images/hierarch.gif</small>
        </center>
    3. __DB-Scan Clustering:__
        >Density-based spatial clustering of applications with noise (DBSCAN) is a data clustering algorithm proposed by Martin Ester, Hans-Peter Kriegel, Jörg Sander and Xiaowei Xu in 1996.[1] It is a density-based clustering non-parametric algorithm: given a set of points in some space, it groups together points that are closely packed together (points with many nearby neighbors), marking as outliers points that lie alone in low-density regions (whose nearest neighbors are too far away). DBSCAN is one of the most common clustering algorithms and also most cited in scientific literature.
In 2014, the algorithm was awarded the test of time award (an award given to algorithms which have received substantial attention in theory and practice) at the leading data mining conference, ACM SIGKDD. As of July 2020, the follow-up paper "DBSCAN Revisited, Revisited: Why and How You Should (Still) Use DBSCAN" appears in the list of the 8 most downloaded articles of the prestigious ACM Transactions on Database Systems (TODS) journal.
        <center>

        ![](dbscan.gif)

        <small>source: https://ml-explained.com/articles/dbscan-explained/dbscan.gif</small>
        </center>
<hr>

### Contact:

|Type | Link | 
| :---: | :---: |
|(🐤)[Twitter] | https://twitter.com/akayyy_in |
|(📷)[Instagram] | https://www.instagram.com/kuchbhiiiatharv/ |
|(🔗)[Webpage] | https://atharv4git.github.io/webpage/ |
