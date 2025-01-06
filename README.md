# RFM Analysis using K-means Clustering

This repository contains a Jupyter Notebook dedicated to performing RFM (Recency, Frequency, Monetary) analysis, a popular customer segmentation method in marketing analytics, combined with K-means clustering for advanced customer segmentation. The notebook leverages customer transaction data to generate meaningful insights that can help businesses enhance customer retention strategies and personalize marketing efforts.

## Features

- **Data Cleaning and Preparation**: Prepares raw transactional data for analysis.
- **RFM Metrics Calculation**: Computes Recency, Frequency, and Monetary values for each customer.
- **Customer Segmentation**: Uses K-means clustering to categorize customers into meaningful segments based on their RFM scores.
- **Visualizations**: Provides charts and graphs to illustrate customer behavior patterns.
- **Actionable Insights**: Identifies key customer groups for targeted marketing campaigns.

## Prerequisites

- Python 3.7 or above
- Jupyter Notebook

### Required Libraries
Ensure the following Python libraries are installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn


## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/nafiurrahmanniloy/RFM-Analysis-using-K-means-clustering.git
   ```
2. Navigate to the project directory:
   ```bash
   cd RFM-Analysis-using-K-means-clustering
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook RFM.ipynb
   ```
4. Follow the steps outlined in the notebook to perform the RFM analysis on your dataset.

## Example Dataset
The notebook supports transactional data in CSV format with the following columns:
- **CustomerID**: Unique identifier for each customer.
- **InvoiceDate**: Date of the transaction.
- **InvoiceNo**: Unique identifier for each transaction.
- **Amount**: Monetary value of the transaction.

## Outputs
- RFM scores for each customer.
- Customer segmentation visualizations using K-means clustering.
- Insights and recommendations for customer targeting.


