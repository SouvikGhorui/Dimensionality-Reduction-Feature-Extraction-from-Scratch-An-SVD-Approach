# Dimensionality-Reduction-Feature-Extraction-from-Scratch-An-SVD-Approach
## 📌 Project Overview
This project implements Principal Component Analysis (PCA) from scratch to perform dimensionality reduction on high-dimensional image data.Instead of using pre-built libraries like sklearn.PCA, this implementation utilizes Singular Value Decomposition (SVD) via NumPy to mathematically extract the most significant features ("Eigenfaces") from the Olivetti Faces dataset.
## 🎯 Key Results
**Original Dimensions:** 4,096 features ($64 \times 64$ pixels).Reduced Dimensions: ~60 components.
**Compression Rate:** Achieved a 98% reduction in feature space while retaining 90% of the variance (information).
**Outcome:** Successfully reconstructed facial structures with minimal Mean Squared Error (MSE).
## 🧮 Mathematical Concepts Used
This project bridges pure mathematics and computer vision:
**Linear Algebra:** Covariance Matrices, Matrix Factorization ($X = U \Sigma V^T$).
**Eigen-Analysis:** Extracting Eigenvalues (variance magnitude) and Eigenvectors (principal directions).
**Statistical Analysis:** Calculating cumulative variance to determine the optimal number of components ($k$).
## 🛠️ Tech Stack
**Language:** Python 3.14.3
**Core Libraries:** NumPy (Linear Algebra), Matplotlib (Visualization)
**Data:** sklearn.datasets (Olivetti Faces)
