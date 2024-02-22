Overview
This project performs the following tasks:

Data Loading: It loads cryptocurrency market data from a CSV file into a Pandas DataFrame.

Data Preparation: It preprocesses the data by normalizing numerical features using StandardScaler from scikit-learn.

Determining Optimal K: It determines the optimal number of clusters (k) using the elbow method.

Clustering Cryptocurrencies: It clusters cryptocurrencies using the K-means algorithm with the optimal value of k.

Files
Crypto_Clustering.ipynb: Main script to execute the analysis.
crypto_market_data.csv: Input data containing cryptocurrency market information.
jpgs: screeshot of plotted outcomes from the analysis
README.md: This file providing an overview of the project.

Results
After running the analysis, you will obtain insights into the cryptocurrency market, including the optimal number of clusters and the clustering results.

Analysis:
#### Answer the following questions: 

* **Question:** What is the best value for `k` when using the PCA data?

  * **Answer:**4


* **Question:** Does it differ from the best k value found using the original data?

  * **Answer:** no
  * 
  * **Question:** After visually analysing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** There was no impact

 Comparison of Elbow curve from Kmean and PCA methods

![image](https://github.com/pmadata/CryptoClustering/assets/143486132/73d4a7b2-9971-42da-89a0-02ded721c6ae)

Composite of Clusters between methods 
![image](https://github.com/pmadata/CryptoClustering/assets/143486132/787a144a-fca3-47bc-ad90-d6da54459e81)
