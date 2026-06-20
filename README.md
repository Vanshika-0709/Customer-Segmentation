# Customer Segmentation using RFM Analysis and K-Means Clustering

## Project Overview

This project segments customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering. The goal is to identify distinct customer groups and provide business insights for targeted marketing strategies.

#Problem Statement

Businesses often treat all customers similarly, leading to ineffective marketing campaigns. This project aims to identify customer segments based on transaction history and spending patterns.

# Dataset

* Online Retail Dataset
* Contains customer transactions, invoice details, product information, quantity, unit price, and purchase dates.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## Project Workflow

### 1. Data Cleaning

* Removed records with missing Customer IDs
* Removed cancelled and invalid transactions
* Handled negative and zero monetary values
* Created TotalPrice feature

### 2. Exploratory Data Analysis (EDA)

* Analyzed missing values
* Studied quantity and price distributions
* Examined customer purchasing behavior
* Identified outliers and business patterns

### 3. Feature Engineering

Created RFM features:

* Recency: Days since last purchase
* Frequency: Number of purchases
* Monetary: Total customer spending

### 4. Data Preprocessing

* Applied log transformation to reduce skewness
* Standardized features using StandardScaler

### 5. Customer Segmentation

* Used K-Means Clustering
* Determined optimal clusters using Elbow Method and Silhouette Score
* Segmented customers into four groups

## Customer Segments

### VIP Customers

* High spending
* High purchase frequency
* Recent purchases

### Loyal Customers

* Regular purchases
* Consistent spending
* Active customers

Potential Loyalists

* Moderate spending
* Can be converted into loyal customers

 At-Risk Customers

* Low spending
* Inactive for a long period
* Require retention campaigns

Business Recommendations

* Reward VIP customers with exclusive offers.
* Provide loyalty benefits to regular customers.
* Offer personalized promotions to potential loyalists.
* Run win-back campaigns for at-risk customers.

Results

Successfully segmented 4,322 customers into meaningful groups using RFM analysis and K-Means clustering, enabling data-driven marketing and customer retention strategies.

Author

Vanshika Vyas
