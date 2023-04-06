# Unsupervised-Learning-Model-

# About the Project:
In this project, Bertelsmann partners AZ Direct and Arvato Financial Solutions have provided two datasets one with demographic information about the people of Germany, and one with that same information for customers of a mail-order sales company. We’ll look at relationships between demographics features, organize the population into clusters, and see how prevalent customers are in each of the segments obtained.
Unsupervised learning technique is used to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, I will also need to assess and clean the data in order to convert the data into a usable form.
 
Unsupervised learning allows machine learning algorithms to work with unlabeled data to predict outcomes. Unsupervised learning is all about understanding how to group our data when we either
1. Do not have a label to predict. 
2. Are not trying to predict a label, but rather group our data together for some other reason.
![R](https://user-images.githubusercontent.com/122751229/230243736-f4e36b8d-e799-46f5-96a2-e4c15f39a5a7.jpg)

## Steps of the project as follows:
1.	Load The data
2.	Preprocessing (Data Cleaning & engineering)
3.	Feature Transformation (feature scaling and perform the PCA)
4.	Interpret Principal Components
5.	Clustering
6.	Compare Customer Data to Demographics Data
### Data cleaning
Exploring and understanding the data is important in Analysis. Data cleaning helps to remove, identify null, irrelevant and missing values. In this project data cleaning is used on behalf of the following features:
-	missing or unknown values encoded in the data? 
-	certain columns that should be removed from the analysis because of missing data? 
-	Some data points (rows) that should be treated separately from the rest? 
-	Consider the level of measurement for each feature in the dataset (e.g. categorical, ordinal, numeric). 
-	 Are there features that need to be re-encoded before they can be used?
-	Are there additional features that can be dropped at this stage?
cleaning procedure is created that will apply first to the general demographic data, then later to the customers data.

### Feature Transformation:
After cleaning the Data, dimensionality reduction techniques is used to identify relationships between variables in the dataset, resulting in the creation of a new set of variables that account for those correlations. For this Principal component analysis (PCA) is used to find the vectors of maximal variability.
#### Principal Component Analysis (PCA) 
It is a technique that is used to reduce the dimensionality of your dataset. The reduced features are called principal components, or latent features. These principal components are simply a linear combination of the original features in your dataset.
You learned that these components have two major properties:
1.	They aim to capture the most amount of variability in the original dataset.
2.	They are orthogonal to (independent of) one another.
### Clustering
Finally, on the transformed data, clustering techniques is applied to identify groups in the general demographic data. Then same clustering model is used on the customers dataset to see how market segments differ between the general population and the mail-order sales company. K-mean is used to cluster the data.
#### K-mean Clustering
1.	In the K-means algorithm, 'k' represents the number of clusters you have in your dataset. You choose k as the number of clusters you believe to be in your dataset or...
2.	You use the elbow method to determine k for your data.
Then this number of clusters is created within your dataset, where each point is assigned to each group.



