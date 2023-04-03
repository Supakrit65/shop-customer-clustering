# shop-customer-clustering

This project aims to cluster customers based on their Annual Income and Spending Score using the **K-Means** Clustering algorithm.

## Dataset

The dataset used in this project is `Customers.csv`, which contains information about customers' gender, age, annual income, spending score, and profession.

## Data Preprocessing

First, we removed the missing values. We then performed label encoding for the gender column and one-hot encoding for the profession column.

After encoding, we normalized the features of the dataset to have zero mean and unit variance using the StandardScaler from sklearn.

## Elbow Method and Silhouette Method

We used the Elbow method and Silhouette method to determine the optimal number of clusters for K-Means Clustering.

## Clustering Result

We used K-Means Clustering with 4 clusters to cluster the customers based on their annual income and spending score.

The scatterplot shows that the customers in Cluster 0 have low annual income and low spending score, while customers in Cluster 1 have high annual income and high spending score. Customers in Cluster 2 have high annual income and low spending score, while customers in Cluster 3 have low annual income and high spending score.

Overall, this clustering result can help businesses to target different groups of customers based on their annual income and spending score.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

