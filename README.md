# Cryptocurrencies with Unsupervised Machine Learning

## Project Overview

The purpose of this project is to create a report that includes what cryptocurrencies are on the trading market and  how client could be grouped to create a classification system for their new investment.


## Deliverable  using follow technical analysis

-  Preprocessing the Data for PCA
-  Reducing Data Dimensions Using PCA
-  Clustering Cryptocurrencies Using K-means
-  Visualizing Cryptocurrencies Results

## Visualizing Cryptocurrencies Results

Clustering Cryptocurrencies Using K-means
![image](https://github.com/NadaAdem/Crypto_currencies/blob/main/Resources/elbow_curve.png)


Create  new  dataFrame(clustered_df ) by concatenating the crypto_df and pcs_df
![image](https://github.com/NadaAdem/Crypto_currencies/blob/main/Resources/clustered_df.png)



The DataFrame of clustered_df use a 3D Scatter plot using the Plotly Express scatter_3d() function to visualize the 4 Classes.
![image](https://github.com/NadaAdem/Crypto_currencies/blob/main/Resources/3D%20Plot.png)




A table is created featuring the tradable cryptocurrencies using the hvplot.table().
![image](https://github.com/NadaAdem/Crypto_currencies/blob/main/Resources/hvplot.table.png)


A 2D hvplot scatter plot with x="TotalCoinsMined_scaled", y="TotalCoinSupply_scaled", and by="Class" with the CoinName displayed.
![image](https://github.com/NadaAdem/Crypto_currencies/blob/main/Resources/scatter.png)

