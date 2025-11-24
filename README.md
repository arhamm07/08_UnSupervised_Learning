# Unsupervised Learning Algorithms

This repository contains a collection of Jupyter Notebooks demonstrating various unsupervised learning algorithms. Each notebook provides a theoretical overview of the algorithm followed by a practical implementation using Python libraries such as `scikit-learn`, `matplotlib`, and `seaborn`.

## Algorithms Covered

### 1. K-Means Clustering
*   **File:** `01_k_means_clustering.ipynb`
*   **Description:** Implementation of the K-Means clustering algorithm. It demonstrates how to partition data into `k` distinct clusters based on distance to the centroid of a cluster.
*   **Key Concepts:** Centroids, Inertia, Elbow Method.

### 2. Hierarchical Clustering
*   **File:** `02_Hierarchichal_clustering.ipynb`
*   **Description:** Explores Hierarchical clustering, a method of cluster analysis which seeks to build a hierarchy of clusters.
*   **Key Concepts:** Agglomerative Clustering, Dendrograms, Linkage methods (Ward).

### 3. DBSCAN and OPTICS
*   **File:** `03_dbscan_and_optics_clustering.ipynb`
*   **Description:** Covers density-based clustering algorithms: DBSCAN (Density-Based Spatial Clustering of Applications with Noise) and OPTICS (Ordering Points To Identify the Clustering Structure).
*   **Key Concepts:** Core points, Border points, Noise, Epsilon, MinPts, Density reachability.

### 4. Gaussian Mixture Models (GMM)
*   **File:** `04_GMM.ipynb`
*   **Description:** Introduces Gaussian Mixture Models, a probabilistic model that assumes all the data points are generated from a mixture of a finite number of Gaussian distributions with unknown parameters.
*   **Key Concepts:** Expectation-Maximization (EM) algorithm, Means, Covariances, Mixing coefficients, AIC/BIC.

### 5. Principal Component Analysis (PCA)
*   **File:** `05_PCA.ipynb`
*   **Description:** A detailed guide to PCA, a dimensionality reduction technique used to emphasize variation and bring out strong patterns in a dataset.
*   **Key Concepts:** Dimensionality reduction, Eigenvalues, Eigenvectors, Covariance matrix, Explained variance ratio.

### 6. t-SNE (t-Distributed Stochastic Neighbor Embedding)
*   **File:** `t-sne.ipynb`
*   **Description:** Demonstrates t-SNE, a non-linear dimensionality reduction technique well-suited for embedding high-dimensional data for visualization in a low-dimensional space of two or three dimensions.
*   **Key Concepts:** Manifold learning, High-dimensional data visualization, Perplexity.

## Libraries Used
*   **Scikit-learn:** For implementing machine learning algorithms.
*   **Pandas:** For data manipulation and analysis.
*   **NumPy:** For numerical computing.
*   **Matplotlib:** For creating static, animated, and interactive visualizations.
*   **Seaborn:** For statistical data visualization.
*   **SciPy:** For scientific computing and technical computing (used in Hierarchical clustering).
*   **Plotly:** For interactive graphing (used in t-SNE).

## Getting Started
To run these notebooks, ensure you have Python installed along with the required libraries. You can install the dependencies using pip:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn scipy plotly
```

Clone the repository and open the notebooks using Jupyter Lab or Jupyter Notebook.
