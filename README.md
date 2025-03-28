# Credit Card Customer Segmentation (Unsupervised Learning)


Overview

This dataset contains information on credit card customers and their transaction behavior. It is used for unsupervised learning tasks such as customer segmentation through clustering techniques.

Dataset Information

The dataset includes the following features:

Customer Information:

CUSTID (categorical) – Unique identification number for each credit card holder.

Financial Data:

BALANCE (numeric) – Balance amount left in the account.

BALANCEFREQUENCY (numeric) – Frequency of balance updates (0-1 scale).

PURCHASES (numeric) – Total purchase amount.

ONEOFFPURCHASES (numeric) – Maximum purchase made in one transaction.

INSTALLMENTSPURCHASES (numeric) – Total purchases made in installments.

CASHADVANCE (numeric) – Amount of cash advances taken.

Transaction Behavior:

PURCHASESFREQUENCY (numeric) – Frequency of purchases (0-1 scale).

ONEOFFPURCHASESFREQUENCY (numeric) – Frequency of one-time purchases (0-1 scale).

PURCHASESINSTALLMENTSFREQUENCY (numeric) – Frequency of installment purchases (0-1 scale).

CASHADVANCEFREQUENCY (numeric) – Frequency of cash advances (0-1 scale).

CASHADVANCETRX (numeric) – Number of cash advance transactions.

PURCHASESTRX (numeric) – Number of purchase transactions.

Credit and Payments:

CREDITLIMIT (numeric) – Credit card limit.

PAYMENTS (numeric) – Total payments made.

MINIMUM_PAYMENTS (numeric) – Minimum payment made.

PRCFULLPAYMENT (numeric) – Percentage of full payments made.

TENURE (numeric) – Duration of credit card usage (in months).

Tasks to be Performed

1. Exploratory Data Analysis (EDA)

Perform statistical analysis and visualize trends.

Identify key insights from categorical and numerical variables.

2. Data Preprocessing

Handle missing values.

Identify and treat outliers using the Z-score method.

Address highly correlated variables.

3. Dimensionality Reduction

Apply Principal Component Analysis (PCA) to retain 95% of the variance.

4. Clustering Analysis

Determine the optimal number of clusters for K-Means using:

The Elbow Method

Silhouette Score

Build a K-Means clustering model.

Visualize the clusters using a bar plot.

Usage Instructions

Load the dataset using Pandas in a Python environment.

Perform EDA and preprocess the data.

Apply dimensionality reduction if necessary.

Perform clustering and interpret customer segments.

This dataset helps businesses understand customer spending patterns and segment them into distinct groups for targeted marketing strategies.

