# Custometrs' clustering

## Purpose

The purpose of this project is to segment customers based on their basic features into a couple of similar clusters.
To accomplish this the following steps have been executed:

1. Explanatory Data Analysis
2. Data preprocessing
3. Checking for K-Means assumptions
4. K-Means clustering
5. Hierarchical clustering

## Data set information

The dataset was downloaded from kaggle competition <a href="https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python">Mall Customer Segmentation Data</a>.
The dataset contains 200 records, each for one customer. The features available in the dataset are as following:
  

- `CustomerID` - unique identifier of a customer
- `Genre` - gender of the customer
- `Age` - age of the customer
- `Annual Income (k$)` - annual income of the customer
- `Spending Score (1-100)` - score assigned to the customer based on his/her behavior and spending nature

## Analysis

The file `customers-clustering.ipynb.ipynb` contains the main jupyter notebook with the whole preprocessing and modelling process.

The analysis was performed in Jupyter Notebooks using libraries such as: numpy, pandas, matplotlib, seaborn, scikit-learn, scipy
