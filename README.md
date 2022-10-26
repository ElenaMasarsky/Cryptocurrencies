# Cryptocurrencies

## Overview of the analysis:
Before pitching an investment in cryptocurrencies we want to analyze the data set of crypto currencies available to us and create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
The popularity of bitcoin has coused a price jump that makes it unaffordable for
many new investors. However, there are many many more cryptocurrencies available at more affordable price.
Since there is no known output for what we are  looking for we are going to use unsupervesed machine leaning to create this analysis and discover trends that will convince us to invest in these new curencies.  

The data needs to be processed to fit the machine learning models. To group the cryptocurrencies, we decided on a clustering algorithm. We’ll use data visualizations to share our findings. So, we are going to follow these steps:  

* Preprocessing the Data for PCA  
* Reducing Data Dimensions Using PCA  
* Clustering Cryptocurrencies Using K-means  
* Visualizing Cryptocurrencies Results  


## Resuls:  

### Initial Data Frame before cleaning contains 1255 rows of data  
![pic](https://github.com/ElenaMasarsky/Cryptocurrencies/blob/main/Resources/initial_df.png)  

### Cleaned Data Frame consists of 532 rows of data  
![pic](https://github.com/ElenaMasarsky/Cryptocurrencies/blob/main/Resources/cleaned_df.png)  

### Elbow Curve indicates the best value for K=4  
![pic](https://github.com/ElenaMasarsky/Cryptocurrencies/blob/main/Resources/elbow_curve.png)  

### 3D Scatterplot with Clusters, Visualizing Tradable Cryptocurrencies  
![pic](https://github.com/ElenaMasarsky/Cryptocurrencies/blob/main/Resources/3D_scatter.png)  

### Tradable Cryptocurrencies Scatter Plot
![pic](https://github.com/ElenaMasarsky/Cryptocurrencies/blob/main/Resources/scatter_plot.png)  