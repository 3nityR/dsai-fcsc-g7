# Customer Segmentation - Data Analysis with a Customer Database

## Problem Statement

The goal of this project is to use machine learning to analyse customer data and segment customers into distinct personality clusters. This clustering will help the company better understand its customer base, their preferences, behaviors, and needs, ultimately leading to more targeted and effective marketing strategies, improved customer satisfaction, and increased revenue.

## Data

The project will utilise a dataset of customer data retrieved from Kaggle, which include:

## Approach

The project takes the following steps:

See [01-data-extraction.ipynb](/01-data-extraction.ipynb)

1. **Data extraction**: Clean the customer data, handle missing values, and perform any necessary feature engineering.

See [02-data-visualisation.ipynb](/02-data-visualisation.ipynb.ipynb)

2. **Data visualisation**: Conduct a thorough Exploratory Data Analysis to gain insights into the data, identify potential patterns, and guide the feature selection process.

See [03-data-process.ipynb](/03-data-processing.ipynb)

3. **Data processing**: Preprocess the customer data, encode categorical variables, scale features, and perform dimensionality reduction to facilitate effective clustering.

See [04-data-clustering.ipynb](/04-data-clustering.ipynb)

4. **Data clustering**: Determine the optimal number of clusters using the elbow method and segment customers using agglomerative clustering.

See [05-data-insights.ipynb](/05-data-insights.ipynb)

5. **Data insights**: Interpret and characterise the resulting customer personality clusters by analysing the cluster centroids, feature importances, and representative customer profiles within each cluster.

## Results

The project identified the following customer segments:

Based on these insights, we recommend the following strategies for the company:

## Learning Takeaways:

The project allowed us to explore the concepts below that were not covered in the course's curriculum.

- **Feature engineering**: we learnt how to extract meaningful features from raw data that better facilitate downstream tasks
- **Preprocessing techniques**: we learnt how to utilise industry-standard techniques such as:
  - Standardising features by removing the mean and scaling the variance
  - Label encoding categorical features into numerical features
  - Reducing correlated and redundant features using Principle Component Analysis
- **Clustering techniques**: we learnt how to determine the optimal number of clusters using the elbow method
- **Cluster interpretation**: we learnt how to use Exploratory Data Analysis to profile clusters

## Contributors

| Name         | Mat. Number | Contributions                   |
| ------------ | ----------- | ------------------------------- |
| Xu Jialu     | U2220758B   | Data extraction & visualisation |
| Tam Yik Lock | U2222001C   | Data processing & clustering    |
| Zhou Ziheng  | U2222255F   | Data insights                   |

## References

- [Kaggle | Customer Personality Analysis Dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- [ResearchGate | Determining The Appropiate Cluster Number Using Elbow Method for K-Means Algorithm](https://www.researchgate.net/publication/339670247_Determining_The_Appropiate_Cluster_Number_Using_Elbow_Method_for_K-Means_Algorithm)
- [IBM | What Is Principal Component Analysis (PCA)?](https://www.ibm.com/topics/principal-component-analysis)
- [scikit-learn | AgglomerativeClustering Docs](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
