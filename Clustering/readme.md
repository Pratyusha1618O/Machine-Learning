## Clustering Techniques:
Download the following customer dataset from below link:

Data Set:

https://www.kaggle.com/shwetabh123/mall-customers  

This dataset givesthe data of Income and money spent by the customers visiting a Shopping Mall.  

The data set contains Customer ID, Gender, Age, Annual Income, and Spending Score. Therefore, as a mall owner you need to find the group of people who are the profitable customers for the mall owner. Apply at least two clustering algorithms (based on Spending Score) to find the group of customers.  

a. Apply Data pre-processing (Label Encoding, Data Transformation....) techniques if necessary.  

b. Perform data-preparation (Train-Test Split)

c. Apply Machine Learning Algorithm

d. Evaluate Model.

e. Apply Cross-Validation and Evaluate Model


## Report Answers

- (a) Data Pre-processing
Loaded the Mall Customers dataset.
Applied Label Encoding to the Gender column.
Standardized the Annual Income and Spending Score features using StandardScaler.

- (b) Data Preparation
Since clustering is an unsupervised learning technique, Train-Test Split is not applicable because there are no target labels.

- (c) Machine Learning Algorithms
K-Means Clustering
Agglomerative Clustering

- (d) Model Evaluation
Evaluated both clustering algorithms using the Silhouette Score.
A higher Silhouette Score indicates better-defined clusters.

- (e) Cross-Validation
Cross-Validation is not applicable for clustering because there is no labeled target variable to validate against.