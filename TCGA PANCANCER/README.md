# TCGA PANCANCER DATASET 


This is a subset of the RNA-Seq (HiSeq) PANCAN data set gotten from UCI machine learning repository. It is a random extraction of gene expressions of patients having different types of tumor. Analysis performed on the dataset include:

***
1. **Normalization** using `log(x +1)` and `(sample-mean)/standard deviation`.
***
2. **Dimensionality reduction** using `Principal Component Analysis`.
***
3. **Clustering** with `Leiden Algorithm` and **Visualization** using `T-distributed Stochastic Neighbor Embedding (T-SNE) and Uniform Manifold Approximation and Projection (UMAP)`.
***
4. **Differential Gene Expression** using `wilcoxon method` and **Visualization** using `(Dendrogram, Heatmap, Violinplot, and Matrix plot)`.
***


*Citation Request:*
*The original data set is hosted at Synapse.org (syn4301332) and is maintained by the cancer genome atlas pan-cancer analysis project.*



	
 