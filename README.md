# Customer Segmentation using K-Means Clustering

This project uses K-Means clustering to segment customers based on their age, annual income, and spending score. The dataset used is the [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python).

## Project Overview

- **Clustering Algorithm**: K-Means
- **Dataset**: Mall Customer Segmentation Data
- **Libraries Used**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Steps**:
  - Data Exploration (EDA)
  - Data Preprocessing (Scaling)
  - Applying K-Means Clustering
  - Visualization of Clusters
  - Analysis of Cluster Centers

## How to Run

- Open the `customer_segmentation_using_kmeans.ipynb` notebook in Jupyter.
- Ensure you have the necessary dependencies listed in `requirements.txt` or the environment file.
- Run all the cells to reproduce the analysis.

## Results

- The final dataset with cluster labels is saved in `mall_customers_with_clusters.csv`.
- Cluster centers are saved in `cluster_centers.csv`.
- Plots showing cluster visualizations are saved in the `output/` folder.

## Observations

- Customers have been segmented based on their spending habits, income levels, and age groups. This analysis provides actionable insights for business marketing strategies.
