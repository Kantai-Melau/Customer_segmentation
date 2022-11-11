## Customer Segmentation

# Files:

customer_classification_pca.ipynb - this file is our main notebook used to run our Python script for ETL, EDA and Algorithms.

Categorized.csv - This is the output file which consists of the original data with an additional "Category" column. This "Category" column is the cluster the row was assigned to by the algorithm.

Categorized_tsne.csv - This is the output file from our K-Means algorithm without the use of PCA and consists of the original data with an additional "Category" column. This "Category" column is the cluster the row was assigned to by the algorithm.

data folder - this contains a CSV with the original data.

Customer Classifiers.ppt - this is our PowerPoint Presentation which outlines our project.

Technical Documentation - This is our written report on our findings during this project.


# The Project:

For this project we looked at the dataset from Maven Technologies and applied clustering algorithms to group their 7000+ customers. This technique can be used by marketting teams to target groups of customers which suit their marketting strategies better.



Note that we have used variables for accessing PostgreSQL. If you wish to replicate this project, these variable will need to be replaced with your own login credentials.