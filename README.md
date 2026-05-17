# Implementation-of-K-Means-Clustering-for-Customer-Segmentation

## AIM:
To write a program to implement the K Means Clustering for Customer Segmentation.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import the required modules.
2. Load the dataset.
3. use KMeans() to perform Kmeans cluster. 
4. Run the python program and check the output.

## Program:
```
/*
Program to implement the K Means Clustering for Customer Segmentation.
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans

data = pd.read_csv("Mall_Customer.csv")

X = data.iloc[:, [3, 4]].values

kmeans = KMeans(n_clusters=5, random_state=0)

y_kmeans = kmeans.fit_predict(X)

plt.scatter(X[:, 0], X[:, 1], c=y_kmeans, s=50)

# Plot centroids
plt.scatter(kmeans.cluster_centers_[:, 0],
            kmeans.cluster_centers_[:, 1],
            s=200,
            marker='X')

# Labels
plt.xlabel("Annual Income")
plt.ylabel("Spending Score")
plt.title("Customer Segmentation using K-Means")

plt.show()
Developed by: MUTTHU M
RegisterNumber:  212225040269
*/
```

## Output:
<img width="687" height="526" alt="image" src="https://github.com/user-attachments/assets/e69c1b44-88c8-43e9-9ebb-faa0523501dc" />


## Result:
Thus the program to implement the K Means Clustering for Customer Segmentation is written and verified using python programming.
