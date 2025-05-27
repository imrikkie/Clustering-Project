# Clustering Steel Grades Based on Microstructure and Yield Strength

This project applies unsupervised learning to cluster steel samples based on their microstructural characteristics and mechanical performance (Yield Strength). It demonstrates how machine learning can uncover hidden patterns in material properties.

## 📌 Objective

To classify steel grades using clustering techniques by analyzing:
- Microstructural parameters (e.g., grain size, phase content)
- Yield Strength (MPa)

## 📊 Dataset Description

The dataset includes:
- Microstructural features: ferrite, pearlite, bainite, martensite fractions, grain size, etc.
- Mechanical property: Yield Strength (MPa)

## 🛠️ Methodology

### 1. Data Preprocessing
- Removed `Yield_Strength_MPa` for unsupervised clustering.
- Normalized features using `StandardScaler`.

### 2. Dimensionality Reduction
- Applied PCA to reduce feature space to 2 components.
- First 2 components explained ~34% of the total variance.

### 3. Clustering
- Used the Elbow Method to determine the optimal number of clusters (k = 4).
- Applied `KMeans` for clustering and assigned cluster labels.

### 4. Visualization
- Plotted clusters in the 2D PCA-reduced space for interpretation.

## 🔍 Insights

- Clustering grouped steels with similar microstructures.
- Potential to analyze Yield Strength trends within each cluster.
- Useful for material classification and design optimization.

## 🚀 Future Scope

- Implement Hierarchical Clustering or DBSCAN for validation.
- Analyze feature importance to understand cluster drivers.
- Explore correlation of Yield Strength across clusters.

## 📂 Files

- https://github.com/imrikkie/Clustering-Project/blob/main/Clustering_Steel_Grades_Updated%20new%20(1).ipynb – Main notebook with code and outputs.
- https://github.com/imrikkie/Clustering-Project/blob/main/Clustering_Steel_Grades_Report.docx – Project documentation with detailed explanation.

## 📧 Contact

For questions or collaboration, feel free to connect!

