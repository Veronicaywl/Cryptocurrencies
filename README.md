# Cryptocurrencies

## Project Overview

In this project, we are going to use unsupervised machine learning to cryptocurrencies. Create a classification report for the investment bank to propose a crytocurrency investment portfolio for their clients. 
Methods for cryptocurrencies analysis:

- Reduce the data dimension by using Principal Component Analysis
- Use K-Means to clusterize cryptocurrencies 
- Create classification reports with 2D and 3D scatter plots to visualized the analysis results.

## Result
After we break down all the data, there are 532 tradable cryptocurrencies in the current market. 

### Clusterized Cryptocurrencies by using K-Means - Elbow Curve

As we don't want to add too many clusteres into the analysis, we used elbow curve to determind the clustered that we will use in the unsupervised machine learning. Based on the graph shown below, the best k value is 4. Therefore, we will use 4 clusteres to categorized cryptocurrenices in our output.


![Elbow_curve](https://user-images.githubusercontent.com/94089680/166110613-51f36158-9b88-4f68-bbf1-30a003464bbd.png)


### Visualization 

- 3D scatter plot with 4 clusteres

We used PCA algorithm to reduce the dimensions to three components. 

![3D_scatter](https://user-images.githubusercontent.com/94089680/166111752-2dcac26a-3f2f-4928-b9d2-ec22ced98f24.png)


The outliner shown above on the 3D graph is class 2. It's the cryptocurrency that no close to all other clusters. 

- Tradable Currency Table

At a glance of the tradable crypto table, majority of the cryptocurrencies fall in class 0 and class 1. The only class 2 crypto currency is BitTorrent. 

![Tradable_crypto_table](https://user-images.githubusercontent.com/94089680/166112067-45d29687-2818-4593-913f-8e6c0785b1db.png)

- 2D scatter plot with TotalCoinMined vs TotalCoinSupply

As we can see the graph, there is one point from class 1 and point from class 2 seems is the outliner compare to all other cryptocurrencies. We use pca algorithm method to show better visualization on this graph. 

![2D_scatter](https://user-images.githubusercontent.com/94089680/166111858-49b204d8-8a98-4e8e-9e1b-279f3225923a.png)

## Summary

We classified 532 cryptocurrencies based on their feature similarities. Hope all the graphics that we provided will be consider relavent to the investment bank for their clients. 