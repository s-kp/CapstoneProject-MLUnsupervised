# CapstoneProject-MLUnsupervised
To Identify Major Customer Segments On Transnational Dataset Using Unsupervised ML Clustering Algorithms.
In this project, our task is to identify major customer segments on a transnational dataset which contains all the transactions occurring between 01/12/2010 and 09/12/2011for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. The dataset provided contains information about Invoice No, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID and Country for each transaction. To achieve our goal of segmentation, we followed the following sequence of steps.

1. Understanding the dataset, doing some basic inspection on the raw data to check the number of columns, understanding distribution of data and checking statistics of the data in each variable. Checking for and handling missing values, Cleaning the data.
2. Feature engineering: After getting some insights from the dataset we created some new features, altered the existing features to understand the hidden patterns in the data.
3. EDA & Data insight on original data: we put out interesting inferences from the data to derive some meaningful results by visualizing some plots and distributions.
4. After having understood the original data, we moved ahead to generate a new dataset based on Recency, Frequency and Monetary values of all the unique customers in order to do a behavioral customer segmentation. We did some feature engineering and EDA on this new dataset as well. We also made some transformations in this dataset to make it ready to be passed to different clustering algorithms.
5. We started with a simple binning and quantile based simple segmentation model first then moved to more complex models because simple implementation helps having a first glance at the data and know where/how to exploit it better.
6. Then we moved to k-means clustering and visualized the results with different number of clusters. As we know there is no assurance that k-means will lead to the global best solution. We moved forward and tried Hierarchical Clustering and DBSCAN clusterer as well.
7. We created several useful clusters of customers on the basis of different metrics and methods to categorize the customers on the basis of their behavioral attributes to define their value, loyalty, profitability etc for the business.
## BINNING RFM SCORES 
1.	Lost poor customers
2.	Average customers 
3.	Good customers 
4.	Best customers
## RFM QUANTILE CUT 
1.	Lost poor customers
2.	Lost loyal customers
3.	Good customers
4.	Best customers
## K-MEANS (2 CLUSTERS)
1.	Best customers
2.	Lost poor customers
## K-MEANS (4 CLUSTERS)
1.	Losing loyal customers
2.	Best customers
3.	Lost poor customers
4.	Recently visited average customers
## K-MEANS (5 CLUSTERS)
1.	Lost poor customer
2.	Best customers
3.	Recently visited average customers
4.	Losing loyal customers
5.	Average customers
## AGGLOMERATIVE (2 CLUSTERS)
1.	Average customers
2.	Best customers
## AGGLOMERATIVE (3 CLUSTERS)
1.	Best customers
2.	Losing loyal customers
3.	Lost poor customers
## DBSCAN (4 CLUSTERS)
1.	Average customers
2.	Lost poor customers
3.	Good customers
4.	Losing loyal customers

