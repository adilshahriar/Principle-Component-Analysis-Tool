A Python tool for performing Principal Component Analysis (PCA) — a dimensionality reduction technique that transforms high-dimensional data into a smaller set of uncorrelated variables (principal components) while preserving as much variance as possible.
Features

Standardize and preprocess input data
Compute principal components via eigendecomposition / SVD
Explained variance and cumulative variance reporting
Scree plots and 2D/3D projection visualizations
Reduce datasets to a chosen number of components
Support for CSV and other tabular data inputs

Installation
bashgit clone https://github.com/yourusername/pca-tool.git
cd pca-tool
pip install -r requirements.txt
Usage
bashpython pca_tool.py --input data.csv --components 2
Requirements

Python 3.8+
NumPy
pandas
matplotlib
scikit-learn
