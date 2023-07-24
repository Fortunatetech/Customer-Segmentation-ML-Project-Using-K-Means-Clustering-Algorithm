# Customer Segmentation Machine Learning Project Using K-Means Clustering Algorithm

This repository contains the code and data for a customer segmentation project that uses the K-Means clustering algorithm. The goal of this project is to group customers based on their age, annual income, and spending score, allowing businesses to better understand their customer base and tailor marketing strategies to specific segments.

## Model Building

In this section, we trained the K-Means clustering model and determined the optimal number of clusters using the Within Clusters Sum of Squares (WCSS) method. The following steps were taken:

1. **Training the K-Means Clustering Model:** We implemented the K-Means algorithm to cluster the customers based on their age, annual income, and spending score.

2. **Choosing the Number of Clusters:** To determine the appropriate number of clusters, we used two methods:
   - **Silhouette Score:** This metric helps evaluate the quality of clustering by measuring how similar an object is to its own cluster compared to other clusters.
   - **Elbow Method:** By plotting the WCSS values for different numbers of clusters, we identified the "elbow point," which represents the optimal number of clusters.

## Segmenting Customers Based on Age and Spending Score

After performing the customer segmentation based on age and spending score, we visualized the results using a donut pie chart. The conclusions drawn from the chart are as follows:

1. **Cluster 3 (Customers with low Age and high Spending Scores):** This is the largest segment, comprising approximately 34.9% of the total customer base. It indicates that a significant portion of customers are relatively young but have high spending scores.

2. **Cluster 4 (Customers with low Age and medium Spending Scores):** This segment represents around 29.0% of the total customers, consisting of younger customers with moderate spending scores.

3. **Cluster 1 (Customers with high Age and medium Spending Scores) and Cluster 2 (Customers with medium Age and low Spending Scores):** These are relatively smaller segments, each accounting for approximately 17.4% of the total customers. Cluster 1 includes older customers with moderate spending scores, while Cluster 2 comprises middle-aged customers with lower spending scores.

The donut pie chart provides valuable insights into the customer segmentation based on age and spending scores, enabling targeted marketing strategies and personalized customer engagement.

## Segmenting Customers Based on Annual Income and Spending Score

Similarly, we performed customer segmentation based on annual income and spending score and visualized the results using another donut pie chart. The conclusions drawn are as follows:

1. **Customers with medium annual income (38-68k$) and medium Spending Scores (35-62):** This is the largest cluster, representing approximately 41.4% of the total customers.

2. **Customers with high annual income (70-135k$) and low Spending Scores (1-40):** This cluster accounts for around 18% of the total customers. These customers have higher annual incomes but tend to have lower spending scores.

3. **Customers with low annual income (15-40k$) and low Spending Scores (1-40)** and **Customers with low annual income (15-40k$) and high Spending Scores (60-100):** These clusters have smaller proportions, representing approximately 12.2% and 11.6% of the total customers, respectively. These customers have lower annual incomes and exhibit varying spending behaviors.

4. **Customers with high annual income (70-135k$) and high Spending Scores (60-100):** This cluster accounts for around 16.8% of the total customers. These customers have higher annual incomes and tend to have higher spending scores.

The donut pie chart provides insights into the distribution of customer segments based on their annual income and spending scores, helping guide targeted marketing strategies tailored to each segment's needs and preferences.

## Segmenting Customers Based on Age, Annual Income, and Spending Score