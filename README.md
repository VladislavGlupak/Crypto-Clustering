# Crypto-Clustering

This repo represents Jupyter notebook that clusters cryptocurrencies by their performance in different time periods, and plots results.

---

## Approach

1. Original data:

- Prepare data
- Find the Best Value for k Using the Original Data
- Cluster Cryptocurrencies with K-means Using the Original Data

2. Optimize Clusters with Principal Component Analysis

3. PCA data:

- Prepare data
- Find the Best Value for k Using the PCA Data
- Cluster data with K-means Using the Original Data

- Visualize and Compare the Results

---

## Technologies

This project leverages the following tools for financial analysis:

- [Conda](https://docs.conda.io/en/latest/) - source package management system and environment management system.

- [Pandas](https://pandas.pydata.org) - Python library that’s designed specifically for data analysis.

- [JupyterLab](https://jupyter.org) - For running and review Python-based programs.

- [KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) - For find groups which have not been explicitly labeled in the data.

- [PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) - For reducing the dimensionality of such datasets, increasing interpretability but at the same time minimizing information loss.

- [StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html) - For Standardization of datasets

---

## Input data

Crypto market data - `/Resources/crypto_market_data.csv`, contains prices changes in different time periods.

---

## Running analisys

1. Install Jupyter Lab
2. Install Anaconda framework
3. Install `pip install -U scikit-learn`
4. Install `conda install -c pyviz hvplot`
5. Clone repository
6. Open Jupyter notebook in the project folder
7. Open `*.ipynb` file and run it

---
