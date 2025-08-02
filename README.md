# Principal Component Analysis (PCA)

This project demonstrates **Principal Component Analysis (PCA)** for dimensionality reduction and visualization of high-dimensional data using Python libraries like NumPy, Pandas, Matplotlib, and scikit-learn.

---

## 📌 Overview

**Principal Component Analysis (PCA)** is a statistical technique used to simplify a dataset by reducing its number of dimensions (features), while retaining as much variance (information) as possible. It does this by projecting the data onto new axes (principal components) that are linear combinations of the original features.

This notebook:
- Loads and explores a dataset.
- Applies PCA to reduce the number of dimensions.
- Visualizes the transformed data.
- Shows how much variance is explained by each component.

---

## 📊 Components Used

### 🔢 NumPy
- Used for efficient numerical operations, especially for computing means, covariances, eigenvectors, and eigenvalues manually (in case of custom PCA).

### 📊 Pandas
- Used for loading and handling tabular data with ease.

### 📈 Matplotlib & Seaborn
- Used for plotting:
  - Original data
  - Transformed data in reduced dimensions
  - Variance explained by each principal component

### 🧪 scikit-learn
- `PCA` from `sklearn.decomposition` used to perform PCA easily.
- `StandardScaler` from `sklearn.preprocessing` used to normalize the data before applying PCA.

---

## 🔧 Requirements

Install the required packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn


🎯 Objectives Demonstrated
Understand the mathematics behind PCA (Covariance Matrix, Eigenvectors).

Use scikit-learn to simplify PCA computation.

Compare high-dimensional vs low-dimensional visualization.

Interpret explained variance to decide how many components to retain.

📷 Output Preview
Scree Plot (Explained Variance by Components)

2D and 3D Scatter Plots after PCA

Comparison between original and reduced features


