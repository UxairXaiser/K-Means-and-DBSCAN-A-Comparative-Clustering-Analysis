# Customer Segmentation with K-Means and DBSCAN: A Comparative Clustering Analysis

This project applies clustering techniques for customer segmentation. It leverages K-Means to create well-defined clusters and DBSCAN to detect arbitrarily shaped clusters and outliers. The analysis compares both methods, discussing strengths and limitations for robust segmentation.

## Overview

This repository contains a complete pipeline for customer segmentation, including:
- Data Preprocessing and Exploration
- Outlier Detection and Handling
- Implementation of K-Means and DBSCAN clustering
- Evaluation and comparison of clustering performance

## Dataset

The dataset includes customer information with features such as:
- Age
- Annual Income
- Spending Score
- Website Visits
- Product Categories Purchased
- Total Purchase Amount
- Average Session Duration
- Return Rate
- Discount Usage

*Note: Update the dataset path in the code as needed.*

## Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
pip install -r requirements.txt
```

## Usage

- Open the Jupyter Notebook (`clustering_analysis.ipynb`) or run the provided Python scripts.
- Follow the step-by-step instructions in the notebook to preprocess data, apply clustering, and visualize results.
- Adjust file paths and parameters as needed.

## Discussion

- **K-Means:** Efficient for spherical clusters but sensitive to outliers.
- **DBSCAN:** Excels in detecting arbitrarily shaped clusters and filtering noise, making it ideal when the data contains outliers.

## Conclusion

This project demonstrates how to perform customer segmentation using different clustering techniques. The comparative analysis highlights when each method performs best, providing insights for selecting the appropriate algorithm based on data characteristics.
