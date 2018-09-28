# Distributed-Hierarchical-Clustering
Clustering is often an essential first step in various speech related tasks like Speaker recognition, Hierarchical Sampling
techniques for ASR, Phoneme clustering etc. Hierarchical clustering, a widely used clustering technique, can offer a richer representation by suggesting the potential group structures but its higher computation cost limits its use on large datasets.
Moreover, parallelization of such an algorithm is challenging as it exhibits inherent data dependency during the hierarchical
tree construction. In this project, We would like to parallelize hierarichal clustering using two different frameworks
- mapreduce and spark and compare their performances.
Further, we would like to leverage these clusters to obtain a more variable dataset which would be further labelled for training an ASR. Finally, we would be comparing ASR performance on test dataset when trained with samples obtained after clustering and randomly sampled.
