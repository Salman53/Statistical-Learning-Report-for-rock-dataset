Rock Dataset – Statistical Learning Project
📌 Introduction

This project presents a comprehensive statistical analysis of the Rock dataset from R.
The analysis includes univariate statistics, Principal Component Analysis (PCA), and clustering techniques, aiming to uncover hidden patterns in rock samples and their impact on reservoir productivity.

📂 Dataset

Source: R built-in dataset rock

Observations: 48 rock samples

Variables:

area – area of pores (in pixels)

peri – perimeter of pores (in pixels)

shape – shape factor = perimeter / √area

perm – permeability (in milli-Darcies)

🔬 Methods

Univariate Analysis: Distribution analysis, skewness, boxplots, histograms

Model Fitting: Compared distributions (Exponential, Gamma, Weibull, Log-Normal, etc.) using AIC/BIC

PCA (Principal Component Analysis): Reduced dimensionality while retaining key variance

Clustering:

Hierarchical Clustering (dendrograms with different linkage methods)

K-Means & K-Medoids (PAM)

Model-Based Clustering (Gaussian Mixtures, BIC-based selection)

📊 Results

The Weibull and Gamma distributions provided the best fits for pore characteristics.

PCA showed that PC1 and PC2 captured over 88% of the total variance.

Clustering revealed 2–3 optimal clusters, separating samples by permeability and pore characteristics.

🛠️ Technologies Used

Language: R

Libraries: datasets, moments, gamlss, cluster, mclust, factoextra

📌 Key Insights

Pore area and perimeter show strong positive correlation.

Shape variable is positively skewed, with some outliers.

Reservoir productivity is closely linked to permeability clusters.
