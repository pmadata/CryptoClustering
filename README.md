Overview
This project performs the following tasks:

Data Loading: It loads cryptocurrency market data from a CSV file into a Pandas DataFrame.

Data Preparation: It preprocesses the data by normalizing numerical features using StandardScaler from scikit-learn.

Determining Optimal K: It determines the optimal number of clusters (k) using the elbow method.

Clustering Cryptocurrencies: It clusters cryptocurrencies using the K-means algorithm with the optimal value of k.

Files
main.py: Main script to execute the analysis.
crypto_market_data.csv: Input data containing cryptocurrency market information.
README.md: This file providing an overview of the project.
Results
After running the analysis, you will obtain insights into the cryptocurrency market, including the optimal number of clusters and the clustering results.

Conclusion
This project demonstrates how to analyze cryptocurrency market data using Python. By applying clustering techniques, we can identify patterns and group similar cryptocurrencies together based on their price change percentages over different time periods.
