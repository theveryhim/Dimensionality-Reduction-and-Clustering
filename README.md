# MNIST

Some of tasks done in this section which is part of a ML assignment:
- PCA and LDA analysis on MNIST dataset
- Implement an Auto-encoder network
- Clustering with K-means
- Clustering with GMM

## PCA and LDA Analysis on MNIST Dataset

| Method                          | Accuracy   |
|---------------------------------|------------|
| Original Data                   | 0.885      |
| Manual PCA                      | 0.865      |
| RBF Kernel PCA                  | 0.8175     |
| Polynomial Kernel PCA           | 0.825      |
| Linear Kernel PCA               | 0.865      |
| LDA Projected Data              | 0.755      |

## K-means Results

| K (Number of Clusters) | Dunn Index |
|------------------------|------------|
| 3                      | 0.363      |
| 4                      | 0.265      |
| 5                      | 0.460      |

# Cove data-set

Some of tasks done in this section which is part of a MDA assignment:
- Using the PCA algorithm, choose the value of k in such a way that at least 90% of the variance of the samples is maintained
- Reduce the dimensions of the samples using the obtained eigenvectors.
<p align="center">
    <img src="images/1.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

- Divide the data(covtype.info) into three chunks and group the data into 7 clusters using one of the BRF or Cure algorithms.
<p align="center">
    <img src="images/2.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

- Evaluate using metrics *Silhouette Score* and *Davies-Bouldin Index*
```markdown
Silhouette Score: 0.42960626042271594
Davies-Bouldin Index: 4.129832832292689
```

# Brain tumor: Description included in notebook

Some of tasks done in this section which is part of a DeepLearning assignment:
## Dimensionality Reduction
- Load data
- Flatten
- Split
- PCA
- Reconstruction
<p align="center">
    <img src="images/3.png" alt="Descriptive Alt Text" class="fit-width-image">
</p>

## Classifier
In this section use Support Vector Machine (SVM) for predicting Tumor from features.
Our purpose is comparing accuracy on test data before and after dimensionality reduction.

```
Test Accuracy before PCA: 0.8039
Test Accuracy after PCA: 0.6470
```