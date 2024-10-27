# Amazon Sales Analysis Project

## Project Summary

This project provides a comprehensive analysis of Amazon sales data, utilizing visualizations and insights to understand sales patterns, performance metrics, and customer trends. The analysis was carried out using a combination of data exploration, cleaning, clustering, and advanced data visualization techniques.

## Aim

The aim of this project is to extract key insights from Amazon sales data, identify trends, and provide visual analytics that can support data-driven decisions for enhancing sales and customer engagement.

## Index

1. Introduction
2. Data Collection and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Clustering Analysis (K-Means)
5. Sales Prediction (Linear Regression)
6. Visualization Results
7. Metrics Overview
8. Conclusion and Future Scope

## Introduction

The "Amazon Sales Analysis" project is a Python-based data analysis endeavor aimed at exploring and understanding sales data obtained from Amazon. The project employs various Python libraries, including NumPy, Pandas, Matplotlib, Seaborn, and Scikit-Learn to analyze and visualize the dataset.

## Data Collection and Preprocessing

### Data Loading and Inspection

The first step involves loading the sales data from a CSV file using Pandas. The dataset contains 128,976 entries with 21 columns, including information such as Order ID, Date, Status, Sales Channel, Quantity, Amount, and more. Initial inspection using methods like `head()`, `info()`, and `shape` provides a quick overview of the data structure.

### Data Cleaning

The dataset undergoes cleaning processes to enhance its usability. Unrelated or blank columns, such as 'New' and 'PendingS', are dropped. Null values are handled by dropping rows or filling in missing information. Data types are adjusted, ensuring consistency, and columns like 'Date' are converted to datetime objects for better analysis.

## Exploratory Data Analysis (EDA)

### 1. Size Analysis
The distribution of purchases based on size is explored using count plots, revealing that M-Size is the most popular among buyers.

### 2. Grouping by Size
Grouping the data by size allows for a deeper understanding of the quantity of products sold for each size. The analysis confirms that M-Size products dominate sales.

### 3. Courier Status and Order Status
Analyzing the shipping methods and order statuses through count plots indicates that the majority of orders are shipped through couriers.

### 4. Category Distribution
A histogram is used to visualize the distribution of purchases across different product categories, highlighting that T-shirts are the most frequently bought items.

### 5. B2B Analysis
The project includes a pie chart to showcase the distribution of Business-to-Business (B2B) and retailer buyers, indicating that 99.3% of buyers are retailers.

### 6. Fulfilment Analysis
A pie chart illustrates the distribution of fulfilment methods, with Amazon being the primary fulfilment service.

### 7. Scatter Plot and State-wise Distribution
Scatter plots are used to explore relationships between product categories and sizes. Additionally, state-wise distribution plots provide insights into the geographical concentration of buyers, with Maharashtra having the highest number of customers.

## Clustering Analysis (K-Means)

### K-Means Clustering
To further understand customer behavior, a K-Means clustering algorithm was applied to segment customers based on their purchasing patterns. The optimal number of clusters was determined using the Elbow Method, which revealed that 3 clusters provided the best representation of the data.

- **Cluster 1**: Represents frequent buyers with high-value purchases.
- **Cluster 2**: Represents average buyers with moderate purchasing frequency.
- **Cluster 3**: Represents infrequent buyers with low-value purchases.

The clustering results provide valuable insights into different customer segments, which can be used for targeted marketing strategies.

### Customer Segmentation

To better understand our customers, we perform customer segmentation using clustering techniques like K-Means. This analysis helps identify different types of customers based on their purchasing behaviors.

### Visualization of Clusters

![K-Means Clustering Placeholder](./images/k_means_clustering_placeholder.png)

depicting K-Means clustering results here. This visualization helps identify different customer groups based on their purchasing behavior.

## Sales Prediction (Linear Regression)

### Sales Prediction

Using a simple linear regression model, we predict future sales trends based on available features. This helps in forecasting and making data-driven decisions.

### Visualization of Sales Prediction

![Sales Prediction Placeholder](./images/sales_prediction_placeholder.png)

depicting the results of the sales prediction model here. This visualization provides insights into future sales trends.

## Visualization Results

Below are the key visualizations from the analysis:

### Sales Trends Over Time

![Sales Trends Placeholder](./images/sales_trends_placeholder.png)

depicting sales trends over time here. This visualization helps identify seasonal sales peaks and troughs.

### Top-Selling Products

![Top Products Placeholder](./images/top_products_placeholder.png)

showing the top products by sales volume. This visualization provides insights into customer preferences and popular items.

### Customer Segmentation

![Customer Segmentation Placeholder](./images/customer_segmentation_placeholder.png)

*Description*: Include the customer segmentation chart here, highlighting the different types of customers and their purchasing behaviors.

### Key Metrics Overview

![Metrics Overview Placeholder](./images/metrics_overview_placeholder.png)

*Description*: Include the metrics summary image, providing key performance indicators such as average sales, number of customers, and most purchased categories.

## Metrics Overview

The following metrics were extracted during the analysis:

- **Order Summary**:
  - **Total Orders**: 128,976
  - **Average Quantity per Order**: 0.9
  - **Average Amount per Order**: 648.56
  - **Standard Deviation of Amount**: 281.18
  - **Postal Codes Range**: Min - 110001, Max - 989898

- **Fulfillment and Sales Details**:
  - **Fulfilled by Amazon vs. Merchant**: Insights on orders fulfilled by Amazon vs. those fulfilled by merchants.
  - **Sales Channels**: Analysis of sales channel usage, including Amazon.in and other channels.
  - **Average Sales per Order**: Average sales per order was calculated as 668.16 for Easy Ship and 649.07 for Unknown Fulfillment.

## Results & Inferences

The analysis uncovered several critical insights:

- **Top Categories**: Product categories that dominate sales are highlighted.
- **Customer Behavior**: Identification of customer groups that are more likely to purchase during promotional periods.
- **Seasonal Trends**: Seasonal spikes in sales, which could be aligned with holidays or major promotional campaigns.
- **Customer Segments**: K-Means clustering identified distinct customer segments that can be targeted for personalized marketing.
- **Sales Forecasting**: Linear regression was used to predict future sales trends, providing valuable insights for inventory management and marketing.

## Conclusion & Future Scope

The Amazon Sales Analysis project provides valuable insights into customer preferences, popular product categories, geographic distribution, customer segmentation, and sales forecasting. This information can be leveraged by the business to make informed decisions, optimize inventory, and enhance customer satisfaction. Future work could involve more advanced predictive modeling for future sales forecasting, more granular customer behavior analysis, and tailored marketing campaigns based on customer segments.

## Images

All images extracted from the notebook are placeholders here; you need to replace each placeholder with the corresponding image generated in the analysis.

## Contact

For further questions, please feel free to reach out at niteesh.nigam99@gmail.com.
