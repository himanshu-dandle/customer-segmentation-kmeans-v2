
# Customer Segmentation using K-Means Clustering

This project applies K-Means clustering to segment customers based on their age, income, and spending scores, using data from a mall. Customer segmentation helps businesses understand customer behavior and design targeted marketing strategies.

## Table of Contents
1. [About the Project](#about-the-project)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [License](#license)

## About the Project

Customer segmentation helps businesses identify and group customers with similar behaviors to tailor marketing strategies effectively. In this project, we use K-Means clustering to analyze a dataset of mall customers. By grouping them based on attributes like age, annual income, and spending score, the goal is to discover meaningful segments for business insights.

## Dataset

The dataset used is the [Mall Customer Segmentation Data](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python) from Kaggle. It contains the following features:
- **CustomerID**: Unique ID for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer.
- **Spending Score (1-100)**: A score assigned based on customer behavior and spending nature.

## Project Structure

```
customer-segmentation/
├── data/                     # Contains the dataset file
├── notebooks/                # Jupyter notebook with analysis
├── output/                   # Output images and results
└── README.md                 # Project description
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/himanshu-dandle/customer-segmentation-kmeans-v2.git
   ```
2. Navigate to the project folder:
   ```bash
   cd customer-segmentation-kmeans-v2
   ```
3. Install required dependencies using `requirements.txt` or `conda`:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/customer_segmentation_using_kmeans.ipynb
   ```
2. Run all cells in the notebook to reproduce the results.

## Results

- The final dataset with cluster labels is saved in `output/mall_customers_with_clusters.csv`.
- Cluster visualizations are saved in the `output/` folder as `.png` files.

## License

Distributed under the MIT License. See `LICENSE` for more information.
