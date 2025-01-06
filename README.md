RFM Analysis

This repository contains a Jupyter Notebook dedicated to performing RFM (Recency, Frequency, Monetary) analysis, a popular customer segmentation method in marketing analytics. The notebook leverages customer transaction data to generate meaningful insights that can help businesses enhance customer retention strategies and personalize marketing efforts.

Features

Data Cleaning and Preparation: Prepares raw transactional data for analysis.

RFM Metrics Calculation: Computes Recency, Frequency, and Monetary values for each customer.

Customer Segmentation: Assigns RFM scores and categorizes customers into meaningful segments.

Visualizations: Provides charts and graphs to illustrate customer behavior patterns.

Actionable Insights: Identifies key customer groups for targeted marketing campaigns.

Prerequisites

Python 3.7 or above

Jupyter Notebook

Required Libraries

Ensure the following Python libraries are installed:

pandas

numpy

matplotlib

seaborn

You can install the dependencies using the command:

pip install -r requirements.txt

How to Use

Clone the repository:

git clone https://github.com/yourusername/rfm-analysis.git

Navigate to the project directory:

cd rfm-analysis

Open the Jupyter Notebook:

jupyter notebook RFM.ipynb

Follow the steps outlined in the notebook to perform the RFM analysis on your dataset.

Example Dataset

The notebook supports transactional data in CSV format with the following columns:

CustomerID: Unique identifier for each customer.

InvoiceDate: Date of the transaction.

InvoiceNo: Unique identifier for each transaction.

Amount: Monetary value of the transaction.

Outputs

RFM scores for each customer.

Customer segmentation visualizations.

Insights and recommendations for customer targeting.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments

Special thanks to the open-source community for providing tools and inspiration for this project.
