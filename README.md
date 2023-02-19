# Clustering_NGOFundAllocation
Kmeans - on clusters of nations for fund allocation

The dataset is taken from KAGGLE : https://www.kaggle.com/code/vikarna/ngo-cluster-analysis/data

Problem Statement : Generate a list of nations in need of support from a non-governmental organisation(NGO) named HELP International based on socioeconomic and health parameters. 

Before applying Kmeans, there needs to be the identification of the number of clusters. For determining the number of clusters three methods are implemented (Maillie, 2019):
i.	Gap statistics
ii.	Silhouette method
iii.	Elbow plot

While gap statistics generateS 3 clusters as optimal, silhouette analysis produceS 2 followed by 3 as the optimal number of clusters. Furthermore, the  elbow analysis yieldes 3-5 clusters. 

The kmeans method is used in this scenario with cluster counts of 2, 3, 4, and 5. The ideal cluster number (k=3) is then chosen.


Interpretation of the result:

There are 3 clusters of countries obtained from K-means. 
Cluster no. 3 contains countries with highest child_mortality, higher imports and fertility, moderate to high inflation, and, lower exports, life_expectancy, health, gdp, and,  income. 

Hence, the reason that cluster number 3 was chosen for funding was due to the reasons that it contains the least developed countries, while cluster 2 contains upper and highly developed nations and Cluster 1 contains developing/ middle developed nations.

