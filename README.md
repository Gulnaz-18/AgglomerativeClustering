# AgglomerativeClustering

The task is to cluster NBA players based on the players' per-game average performance in the 2018-2019 season. The goal is to achieve the best performance by exploring several different clustering methods, feature engineering, distance metrics, and evaluation measures.
The NBA players belong to 5 positions on the basketball court: SG (shooting guard), PG (point guard), SF (small forward), PF (power forward), and C (center). The attribute position in the data file thus constitutes proper ground truth for evlauating clustering performance. Therefore, when you cluster the data, the attribute position shouldn't be included.

Note that, however, clustering is a discovery process. The ground truth attribute is only a plausible way of evaluating clustering results. It doesn't mean an ideal clustering must necessarily agree with the ground truth. For instance, if one includes Games Played and Minutes Per Game in cluster analysis, these two attributes can help distinguish between starting and bench palyer, which is not captured by attribute position. The clustering results are thus expected to be different than position.
