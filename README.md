# Cryptocurrencies

**Overview**

For this module we used unsupervised machine learning using K-means algorithm to cluster tradable cryptocurrencies. We preprocessed the data for PCA, reducing data dimensions using PCA, clustering cyrptocurrencies using K-means and then visualizing the results. 

**Results**

Using the scaled data we used PCA with n_components=3 to reduce the dimension of the data to three principal components. 

We then determined the k-value and created an elbow curve. We used K=4. 

![Screenshot 2023-04-13 at 1 57 49 AM](https://user-images.githubusercontent.com/118235205/232194229-bc175e70-7153-4f20-8bed-430cacaf700d.png)


We created a 3D-scatter plot containing each cryptos principal; component values, their name, and which algorithm is used. Using hvPlot we created a sorting table containing the name, alogrithm, prooftype, total coin supply, coins mined and their class. Finally we used the MinMaxScaler().fit_transform() to scale the TotalCoinsMined and TotalCoinSupply columns and created a new dataframe with these scaled values. 

![Screenshot 2023-04-13 at 1 58 14 AM](https://user-images.githubusercontent.com/118235205/232194334-b385214d-e3e4-40ec-b0d7-840852f89973.png)


![Screenshot 2023-04-13 at 1 58 05 AM](https://user-images.githubusercontent.com/118235205/232194339-0c2cfef0-6e8a-48a5-82a8-b11a9a28a887.png)


![Screenshot 2023-04-13 at 1 58 22 AM](https://user-images.githubusercontent.com/118235205/232194342-fdea1415-7282-4051-82b4-9c8138446f15.png)
