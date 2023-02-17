# Cryptocurrencies

## Objectives: 

- Describe the differences between supervised and unsupervised learning, including real-world examples of each.
- Preprocess data for unsupervised learning.
- Cluster data using the K-means algorithm.
- Determine the best number of centroids for K-means using the elbow curve.
- Use PCA to limit features and speed up the model.



 **In unsupervised learning, there are two key differences from the above approach:**

1. There are no paired inputs and outcomes.
2. The model uses a whole dataset as input.

*Unsupervised learning is used in one of the following two ways:*

1. Transform the data to create an intuitive representation for analysis or to use in another machine learning model; or
2. Cluster or determine patterns in a grouping of data, rather than to predict a classification.

## Resources

+ Datasets:
    - crypto_data.csv
    
 + Technologies used:
    - Python
    - Jupyter notebook
    - Sklearn, pandas, and hvplot libraries
    - Unsupervised Machine Learning
    
    
As we already know unsupervised learning isn't the solution for every data analytic challenge. Just because supervised learning might not work for one situation doesn't mean unsupervised learning will work instead. Understanding the data and what can be done with it is an important first step before choosing an algorithm.

![Capture](https://user-images.githubusercontent.com/114257085/219530239-f48cccc8-40bd-4f19-bc31-25e6fb9450f8.PNG)

### Clustering Crytocurrencies Using K-Means

**Finding the Best Value for `k` Using the Elbow Curve**

![Capture](https://user-images.githubusercontent.com/114257085/219530393-e272c48b-0106-4e41-aee3-c23c39848b62.PNG)



### Visualizing Cryptocurrencies Results

**3D-Scatter with Clusters**

![Capture](https://user-images.githubusercontent.com/114257085/219529853-ce5a0032-f56a-4059-81c4-0e967fa93dd8.PNG)

**Table with tradable cryptocurrencies.**

![Capture](https://user-images.githubusercontent.com/114257085/219530536-e6a3224c-3a03-44e5-a4a5-6eda7b57411c.PNG)


**Table 'hvplot.scatter' plot using x="TotalCoinsMined" and y="TotalCoinSupply".**

![Capture](https://user-images.githubusercontent.com/114257085/219530756-7c634272-5bad-4605-ada1-4ae9edb20168.PNG)



