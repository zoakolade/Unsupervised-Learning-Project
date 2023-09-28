# machine_learning_project-unsupervised-learning

## Project Outcomes
Unsupervised Learning: perform unsupervised learning techniques on a wholesale data dataset. The project involves four main parts: exploratory data analysis and pre-processing, KMeans clustering, hierarchical clustering, and PCA.
## Duration:
Approximately 1 hour and 40 minutes

## Project Description:
In this project, we will apply unsupervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

The data set for this project is the "Wholesale Data" dataset containing information about various products sold by a grocery store. The project will involve the following tasks:

Exploratory data analysis and pre-processing: We will import and clean the data sets, analyze and visualize the relationships between the different variables, handle missing values and outliers, and perform feature engineering as needed.
Unsupervised learning: We will use the Wholesale Data dataset to perform k-means clustering, hierarchical clustering, and principal component analysis (PCA) to identify patterns and group similar data points together. We will determine the optimal number of clusters and communicate the insights gained through data visualization.
The ultimate goal of the project is to gain insights from the data sets and communicate these insights to stakeholders using appropriate visualizations and metrics to make informed decisions based on the business questions asked."

## Project Goals
The objective of this project was to extract meaningful patterns and group similar data points together within the Wholesale dataset, which comprises information about a wide range of products sold by a grocery store.The variables available in the dataset were: Channel, Region, Fresh, Milk, Grocery, Frozen, Detergents_Paper, Delicassen. This was achieved through the application of unsupervised machine learning techniques aimed at gaining valuable insights from the data.

## Process
Initially, the dataset underwent an importation process, followed by essential data cleaning and exploratory data analysis (EDA). This encompassed tasks such as identifying and addressing null values, outlier detection, and creating visual charts and graphs to gain preliminary insights into the data.

Subsequently, the cleaned data underwent preprocessing and feature engineering steps to prepare it for machine learning models. This involved managing missing values, addressing outliers, partitioning the dataset into training and testing subsets, and standardizing predictor variables.

Finally, the unsupervised machine learning techniques employed included Kmeans Clustering and Hierarchical Clustering. Additionally, Principal Component Analysis (PCA) was utilized to derive insights from the wholesale customer data, helping identify the most effective combinations of features that describe customer behavior.

## Results
- Hierarchical clustering demonstrated superior performance in grouping customers.
- Hierarchical clustering provided a more streamlined outcome, yielding two clusters as opposed to eleven in the K-means clustering model.
- Visualization of K-means clustering was not very informative due to the two-dimensional nature of the data.
- Determining the optimal number of clusters in the K-means clustering model was challenging, as the elbow method did not exhibit a clear elbow point.
- PCA analysis revealed that only three components were necessary to effectively describe customers, as these components maximized the variance.
- For future analyses, one option is to explore alternative methods for handling outliers, as the current IQR-based approach resulted in the removal of a significant number of rows. Subsequently, the models can be reevaluated with this revised dataset.
- Another potential avenue for future analysis is to experiment with different ways of segregating the data, such as further column removal or the addition of dummy columns, to potentially yield more insights.
