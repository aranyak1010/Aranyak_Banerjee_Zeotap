# eCommerce Transaction Analysis

## Overview

This project focuses on analyzing eCommerce transactions through Exploratory Data Analysis (EDA), customer segmentation, and clustering techniques. The main objective is to derive insights from transaction data that can enhance marketing strategies, improve customer engagement, and ultimately drive sales.

## Table of Contents

- [Project Description](#project-description)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Customer Segmentation](#customer-segmentation)
- [Clustering Techniques](#clustering-techniques)
- [Conclusion](#conclusion)
- [Getting Started](#getting-started)

## Project Description

This project analyzes transaction data from an eCommerce platform to uncover trends and patterns that can help in improving customer experience and increasing sales. The analysis follows several steps:

1. Data cleaning and preprocessing.
2. Exploratory Data Analysis (EDA) to visualize and understand key metrics.
3. Customer segmentation via K-means clustering to identify distinct customer groups.
4. Profiling segments to derive actionable insights.

## Data Source

The transaction data used for this analysis is sourced from Zeotap. The dataset includes features such as:

- Transaction ID
- Customer ID
- Customer Name
- Transaction Date
- Quantity
- Total Value
- Price
- Shipping information
  etc.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Exploratory Data Analysis (EDA)

EDA provides preliminary insights into the data. During this phase, the following steps were undertaken:

- **Data Cleaning**: Removal of duplicates, handling missing values, and correcting data types.
- **Descriptive Statistics**: Overview of transaction amounts, frequency of purchases, and customer demographics.
- **Visualizations**: Charts to illustrate trends over time, popular products, and customer purchase behavior.

Some visualizations included:
- Time series analysis of sales.
- Product category distribution.
- Heatmaps showing correlation between variables.

## Customer Segmentation

To better understand customer behavior, we performed customer segmentation using RFM (Recency, Frequency, Monetary) analysis. 

The segmentation process involved:

1. Calculating RFM metrics for each customer.
2. Grouping customers based on their RFM scores.
3. Identifying high-value customers and those at risk of churning.

## Clustering Techniques

To gain deeper insights into distinct customer segments, we applied clustering algorithms. K-means clustering was primarily used. The steps included:

1. Determining the optimal number of clusters using the Elbow Method.
2. Fitting the K-means algorithm to the dataset.
3. Analyzing the resulting clusters to characterize customer segments.
4. Calculate the Silhouette score and Davies-Bouldin Index

Clusters were visualized in 2D using PCA (Principal Component Analysis).

## Conclusion

The analysis revealed valuable insights into customer behaviors and preferences. The results of the clustering provide a clear picture of distinct customer segments. This information can guide targeted marketing efforts, personalized promotions, and enhance customer satisfaction.

## Getting Started

To run the project locally, ensure you have Python installed along with the necessary packages. Follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/eCommerce-Transaction-Analysis.git
   cd eCommerce-Transaction-Analysis
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

4. Explore the notebooks to understand EDA, customer segmentation, and clustering.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
