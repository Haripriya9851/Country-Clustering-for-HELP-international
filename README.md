# Country-Categorization-for-HELP-international Using Unsupervised Learning

# Objective
To categorise the countries using socio-economic and health factors that determine the overall development of the country. 
# Dataset Details:
Kaggle Dataset - [Unsupervised Learning on Country Data](https://www.kaggle.com/datasets/rohan0301/unsupervised-learning-on-country-data/data)

Dataset used has 10 columns and description of each is as follows.

Column Name - Description

country	- Name of the country

child_mort	- Death of children under 5 years of age per 1000 live births

exports 	- Exports of goods and services per capita. 

health 		- Total health spending per capita. 

imports	- Imports of goods and services per capita. 

Income		- Net income per person

Inflation 	- The measurement of the annual growth rate of the Total GDP

life_expec 	- The average number of years a new born child would live if the current mortality patterns are to remain       the same

total_fer 	- The number of children that would be born to each woman if the current age-fertility rates remain the same.

gdpp 	-	The GDP per capita. Calculated as the Total GDP divided by the total population.

# What is Done Here?
1.	Visualize power of different unsupervised clustering algorithms by applying them on the country dataset mentioned.
2.	Algorithms Used: K-Means Clustering, Agglomerative Clustering, DBSCAN Clustering
3.	PCA

# Conclusion 
In this notebook I have:
1.	Classified countries using different unsupervised learning algorithms like K-Means, DBSCAN and Hierarchical clustering
2.	Identified that features like GDP, Health, Income, Child mortality rate contribute more to the classification of clusters
3.	To confirm that, used PCA Technique. Dropped highly correlated features and checked the error rate of the model on k-means algorithm. There was no much change in the SSE and cluster needed(refer graph).

