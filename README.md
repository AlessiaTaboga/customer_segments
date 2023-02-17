# customer_segments

## Udacity Machine Learning Engineer Nanodegree

### Unit 4: Unsupervised Learning

## Project: Create Customer Segments

This project requires Python, the Python file ‘visuals.py’ provided by Udacity and the following libraries:
-	NumPy
-	Pandas
-	Matplotlib
-	Seaborn
-	Scikit-learn

### Data
Data contain information on various clients of a wholesale distributor in Portugal. Data include the annual spending amounts (in monitary units, m.u.) on different product categories.
Data can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).
There are 440 data points and 8 features:
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous); 
2) `Milk`: annual spending (m.u.) on milk products (Continuous); 
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous); 
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal)

### Project Overview
In this project, unsupervised machine learning techniques are applied to customer data of a wholesale distributor to identify hidden customer segments. Identifying different type of customers can help the wholesale distributor make better and more informed business decisions. For example, it could provide insights into how to best structure their delivery services to meet the needs of each customer.
The project contains several sections:
-	Data exploration (including descriptive statistics, feature distributions and correlations)
-	Data preprocessing (feature logarithm scaling, outlier detection)
-	Feature transformation with PCA
-	Dimensionality reduction with PCA
-	Clustering using Gaussian Mixture Model (testing number of clusters and evaluating using silhouette score; finding that 2 clusters provide the best results)
-	Data recovery (inverse transformation of cluster centres)
-	Conclusion (discussion on ways the clustered data can be used by the wholesale distributor; comparison between identified clusters and original feature ‘channel’) 

This Udacity project of the Machine Learning Engineer Nanodegree was designed to give students hands-on experience with unsupervised learning techniques and work towards developing conclusions for a potential client on a real-world dataset. 
