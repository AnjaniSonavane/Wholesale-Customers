# Wholesale-Customers Data1

 The data set refers to clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories
The dataset downloaded from UCI machine learning repository.

Implementation:
- EDA and any data cleaning
- Implemented Feature Scaling to Normalize the data(compare the histogram and KDE for MinMaxScaler 
and StandardScaler)
- Finding optimal number of features using RFECV and shown the plot between Number of features 
selected vs Cross validation score (used channel as target variable)
- Implemented KMeans Clustering for K=2 to K=15 and based on elbow method identify what is the 
optimum number of clusters
- Implemented PCA with number of original features to answer how much variance is explained by 
first 2 components and by first 4 components and visualize the clusters in the data
- Implemented XGBoost Classifier with 5 Fold CV and report the performance metrics
