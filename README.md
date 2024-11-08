#Project Overview
The Customer Segmentation Analysis for E-Commerce aims to classify customers into segments based on their behavior and purchasing power. This segmentation will support the development of targeted marketing strategies to enhance customer engagement and boost sales.

#Objectives
The primary goals of this project include:
Segmenting Customers: Using clustering techniques to categorize customers based on income and spending behavior.
Understanding Each Segment: Identifying and profiling customer segments for more effective marketing strategies.
Providing Actionable Recommendations: Developing strategies to engage and retain each customer segment.
Dataset Overview

#This project utilizes a customer dataset that includes:
Customer ID: Unique identifier for each customer
Age: Age of the customer
Gender: Gender of the customer
Annual Income: Customer’s yearly income
Spending Score: A score assigned based on customer spending behavior

#Methodology
Data Cleaning: Address missing values, normalize numerical data, and encode categorical values.
Clustering Model: Using KMeans Clustering to identify patterns within the data and group customers into segments.
Data Visualization: Use plots to illustrate the findings, such as scatter plots, box plots, and histograms for clear insights.

#Data Preprocessing
Data Cleaning: Checked for and handled missing or inconsistent values.
Normalization: Scaled numerical columns to ensure consistency in clustering.
Encoding: Converted categorical data (e.g., gender) to numerical form for clustering.

#Clustering
Elbow Method: Determined that 4 clusters was the optimal number, based on the elbow in the WCSS curve.
Cluster Profiles:
Cluster 0: Low income, high spending.
Cluster 1: High income, low spending.
Cluster 2: High income, high spending (premium customers).
Cluster 3: Low income, low spending.

#Visualization
Elbow Plot: Shows the optimal number of clusters.
Annual Income vs Spending Score Scatter Plot: Highlights clusters by customer income and spending.
Box Plot of Spending Score by Gender: Reveals spending habits across genders.
Income and Age Histograms: Provides demographic insights on age and income distributions.

#Insights
Cluster Analysis: Each cluster represents a unique customer group, differing by income level and spending behavior.
Cluster 2 (high-income, high-spending) customers are likely to be interested in premium offers.
Clusters 0 and 3 consist of lower-income customers, with varied spending habits.
Cluster 1 represents high-income customers with lower spending, potentially open to incentives for increased spending.

#Recommendations
Targeted Marketing:
Cluster 2: Focus on premium product offerings.
Clusters 0 & 3: Provide budget-friendly deals and promotions.
Income-Based Incentives:
Target high-income, low-spending customers (Cluster 1) with value-driven offers.
Gender-Neutral Campaigns:
Spending habits are similar across genders, so campaigns should focus on interests rather than gender-specific messaging.
Age-Based Offers:
Target the predominant age groups (30-50 and 70+), with tailored marketing strategies.

#Technologies Used
Python: Data processing, analysis, and clustering.

#Libraries:
Pandas, NumPy for data manipulation
Scikit-Learn for clustering
Matplotlib, Seaborn for visualization

#Clone the Repository:
git clone https://github.com/Angela-Nkrumah/Customer-Segmentation.git

#Install Requirements:
pip install -r requirements.txt

#Open and execute the Jupyter notebook to see the analysis in action.

#References
Scikit-Learn Documentation on Clustering
Medium Article on Customer Segmentation
