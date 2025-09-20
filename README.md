# machine-learning

## ml-dimred-models.ipynb:

This program explores the performance of two different pipelines of feature extraction:
1. direct application of CNN at the pictures (unfinished)
2. CNN feature extraction

At each pipeline, a number of clustering models with a variety of parameters are applied so that we have a complete picture of which parameter combination for each model is best, according to their accuracy scores from the evaluation process (which also includes the computation of precision, recall, f-score and mean squared error.

At each step, there are visual representations of the results wherever that is possible.

## ml-pretrained-trained.ipynb:

This program explores how dimension reduction is done using three different ways: dimesnion reduction with PCA, LLE and autoencoders using deep neural networks (with 2 hidden layers).

Then performs clustering with K-means using eucledian distances and cosine distance, and agglomerative clustering. 

Each pair of dimension reduction - clustering is evaluated by purity, f-measure and silhouette score. The most efficient number of clusters is then computed based on the silhouette score.

At each step, there are visual representations of the results wherever that is possible.
